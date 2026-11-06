# Type P.fm1 1.0.3

Released 2026-11-06 from source `c160c86`.

## Downloads

| File | Platform | Format | Size | SHA-256 |
| --- | --- | --- | --- | --- |
| [`type-p-fm1.fwsc`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.3/type-p-fm1.fwsc) | M-VAVE FM-1 | firmware | 597.9 kB | `f4883e4bdaea49eb187848f6ce1a3ebc9a996305cfb59fec6508295c801d203e` |
| [`Type-P.fm1-CLAP-linux-aarch64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.3/Type-P.fm1-CLAP-linux-aarch64.zip) | linux-aarch64 | CLAP | 5.5 MB | `bbbef6bcf3993b3ab76919e6cb47cd3025aaf30938bc8ac5f0fe3790a31dd2a1` |
| [`Type-P.fm1-VST3-linux-aarch64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.3/Type-P.fm1-VST3-linux-aarch64.zip) | linux-aarch64 | VST3 | 5.7 MB | `0670975c2170106931e91e4f488233c6997c2253432342618bcf4895ec48d967` |
| [`Type-P.fm1-CLAP-linux-x86_64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.3/Type-P.fm1-CLAP-linux-x86_64.zip) | linux-x86_64 | CLAP | 5.5 MB | `750453dfec3fa255ad597049432501889686f44c7d49e1f4fbc8a6d8a63df50c` |
| [`Type-P.fm1-VST3-linux-x86_64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.3/Type-P.fm1-VST3-linux-x86_64.zip) | linux-x86_64 | VST3 | 5.7 MB | `b8f45fb419e895a9914a59380f7697f0079ec0be79abea62f6df6b8a1691b24e` |
| [`Type-P.fm1-CLAP-windows-x86_64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.3/Type-P.fm1-CLAP-windows-x86_64.zip) | windows-x86_64 | CLAP | 3.9 MB | `9c2655fbe99117fd6005f74d50973ba3f421b424ca13eddd751e93dfff986bd3` |
| [`Type-P.fm1-VST3-windows-x86_64.zip`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.3/Type-P.fm1-VST3-windows-x86_64.zip) | windows-x86_64 | VST3 | 3.9 MB | `6402fa47d6c0f2bb46b297c823e40ef064d33f8182e03336af84a5f0223f8c0a` |
| [`type-p-fm1-1.0.3-source.tar.gz`](https://github.com/AkirakoSaintJust/type-p-fm1/releases/download/v1.0.3/type-p-fm1-1.0.3-source.tar.gz) | source | source | 26.8 MB | `c60c6f54cc0a20aaf8212f0659a19a96f1eaacbd97db509a7168e3e460fc96f6` |

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
