# Type P.fm1 1.0.3

Released 2026-11-05 from source `0c23f69`.

## Downloads

| File | Platform | Format | Size | SHA-256 |
| --- | --- | --- | --- | --- |
| [`type-p-fm1.fwsc`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.3/type-p-fm1.fwsc) | M-VAVE FM-1 | firmware | 597.9 kB | `f4883e4bdaea49eb187848f6ce1a3ebc9a996305cfb59fec6508295c801d203e` |
| [`Type-P.fm1-CLAP-linux-aarch64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.3/Type-P.fm1-CLAP-linux-aarch64.zip) | linux-aarch64 | CLAP | 5.5 MB | `1c3ab0571ce9322995ee85cc6e47303275b295e71ea6548f96d66af9af8fed14` |
| [`Type-P.fm1-VST3-linux-aarch64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.3/Type-P.fm1-VST3-linux-aarch64.zip) | linux-aarch64 | VST3 | 5.6 MB | `09d6feb93a2ac321b4b1766d516961b4e857f1858ba20a0172e1e76b8a2ce371` |
| [`Type-P.fm1-CLAP-linux-x86_64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.3/Type-P.fm1-CLAP-linux-x86_64.zip) | linux-x86_64 | CLAP | 5.5 MB | `a24b3e7a8af68d34dd990dc2623470d1a84fecb713066ee8b7dbbe7c2f683076` |
| [`Type-P.fm1-VST3-linux-x86_64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.3/Type-P.fm1-VST3-linux-x86_64.zip) | linux-x86_64 | VST3 | 5.7 MB | `2cf9f3adf970288ee2438ed7ce5147902e9fa3618d0e3b56eb26d05d8f1e7bf0` |
| [`Type-P.fm1-CLAP-windows-x86_64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.3/Type-P.fm1-CLAP-windows-x86_64.zip) | windows-x86_64 | CLAP | 3.9 MB | `516cfc96af073fa35a9c9833a78ee36a57c55725a78be97c5a4b5f8e1b621f17` |
| [`Type-P.fm1-VST3-windows-x86_64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.3/Type-P.fm1-VST3-windows-x86_64.zip) | windows-x86_64 | VST3 | 3.9 MB | `2220bb53775328f198f9e7f4d758c9c6ff50683f45c516e33342da54af82378b` |
| [`type-p-fm1-1.0.3-source.tar.gz`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.3/type-p-fm1-1.0.3-source.tar.gz) | source | source | 26.8 MB | `d10fc00f877f68314a7d404f69095c8150609aafded71991e1f52bf33e31dad3` |

The firmware is the device image. Flash it with `umetate flash`.
The plugin archives are optional and use the same engine as the firmware
and the web app.

## Sources

- `src/` is the project: the patch, the panel, the app glue, and the plugin
  identity.
- `framework/` is the complete umetate source, including the generator, the
  plugin, and the tests.
- `LICENSING.md`, `DEPENDENCIES.md`, and `third-party-licenses/` carry the
  notices and the exact upstream pins.

## Licence

The firmware and the umetate source are GPL-3.0-only.
The plugin archives link JUCE 8, which is AGPL-3.0-only or commercial,
so the plugin archives are conveyed under the AGPL-3.0-only terms for
the JUCE part.
See `LICENSING.md`.

`SHA256SUMS` lists every download. Verify with
`sha256sum -c SHA256SUMS`.
