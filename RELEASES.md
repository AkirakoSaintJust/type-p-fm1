# Type P.fm1 1.0.4

Released 2026-11-07 from source `9ff8a41`.

## Downloads

| File | Platform | Format | Size | SHA-256 |
| --- | --- | --- | --- | --- |
| [`type-p-fm1.fwsc`](type-p-fm1.fwsc) | M-VAVE FM-1 | firmware | 597.9 kB | `b13f350a8c1dca20c1b741e9cd8aa5dd66bd2b2eaca5b70b100fc0303d2c9872` |
| [`Type-P.fm1-CLAP-linux-x86_64.zip`](plugins/linux-x86_64/Type-P.fm1-CLAP-linux-x86_64.zip) | linux-x86_64 | CLAP | 5.6 MB | `d6c284ed225bd9dde38f1e19b7f5619e1da18118b9d0062a348eadd0533315ff` |
| [`Type-P.fm1-VST3-linux-x86_64.zip`](plugins/linux-x86_64/Type-P.fm1-VST3-linux-x86_64.zip) | linux-x86_64 | VST3 | 5.8 MB | `edee7ca6b0e8fbc3a0c02fee616a08fbdc780fa90f2e943bcca3876cd5a7baf0` |

The firmware is the device image. Flash it with `umetate flash`.
The plugin archives are optional and use the same engine as the firmware
and the web app.

## Sources

- `src/` is the project: the patch, the panel, the app glue, and the plugin
  identity.
- `framework/` is the complete umetate source, including the generator, the
  plugin, and the tests.
- `vendor/deps/` carries the fetched plugin dependency source.
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
