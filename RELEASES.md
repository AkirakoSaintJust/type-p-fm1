# Type P.fm1 1.0.2

Released 2026-11-05 from source `828dcaa`.

## Downloads

| File | Platform | Format | Size | SHA-256 |
| --- | --- | --- | --- | --- |
| [`type-p-fm1.fwsc`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.2/type-p-fm1.fwsc) | M-VAVE FM-1 | firmware | 597.9 kB | `8c90c1acd1dbc83eedd7fc49f15d818e7c53d0ef403d710f9452da1273720f71` |
| [`Type-P.fm1-CLAP-linux-aarch64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.2/Type-P.fm1-CLAP-linux-aarch64.zip) | linux-aarch64 | CLAP | 5.5 MB | `19b58a21326b9b20cba10d51b875181dc2f408d305fc1fd5a197223610205d87` |
| [`Type-P.fm1-VST3-linux-aarch64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.2/Type-P.fm1-VST3-linux-aarch64.zip) | linux-aarch64 | VST3 | 5.6 MB | `c2b1ea58895ee309d5b9e8cf25d698727237d284746cf738b806e6343070aef1` |
| [`Type-P.fm1-CLAP-linux-x86_64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.2/Type-P.fm1-CLAP-linux-x86_64.zip) | linux-x86_64 | CLAP | 5.5 MB | `5bcba37019ecc46c28ab3303acfdf20bbb010b9b0aa8600a2526c4f5e0c783aa` |
| [`Type-P.fm1-VST3-linux-x86_64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.2/Type-P.fm1-VST3-linux-x86_64.zip) | linux-x86_64 | VST3 | 5.7 MB | `1f0bebad072b72e14350e5330f7a69f4efee3403ff56d51b8993e0057cc3530d` |
| [`Type-P.fm1-CLAP-windows-x86_64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.2/Type-P.fm1-CLAP-windows-x86_64.zip) | windows-x86_64 | CLAP | 3.9 MB | `f81b77adf9bf0baa67715cf1d3dc294489e9ca7eb33628c2c6aab24b76ef6675` |
| [`Type-P.fm1-VST3-windows-x86_64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.2/Type-P.fm1-VST3-windows-x86_64.zip) | windows-x86_64 | VST3 | 3.9 MB | `e740c8ac6ea8bfdbc69cecee1008fc29262b3c24f64397fe3820c600f3744c09` |
| [`type-p-fm1-1.0.2-source.tar.gz`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.2/type-p-fm1-1.0.2-source.tar.gz) | source | source | 3.0 MB | `02ba6c9c091bd077c695a8f1c4e05d2df0dfc4e18cbda6994b8bcdffc0f5de41` |

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
