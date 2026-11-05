# Type P.fm1 1.0.2

Released 2026-11-05 from source `08880dc`.

## Downloads

| File | Platform | Format | Size | SHA-256 |
| --- | --- | --- | --- | --- |
| [`type-p-fm1.fwsc`](type-p-fm1.fwsc) | M-VAVE FM-1 | firmware | 597.9 kB | `8c90c1acd1dbc83eedd7fc49f15d818e7c53d0ef403d710f9452da1273720f71` |
| [`Type-P.fm1-CLAP-linux-x86_64.zip`](plugins/linux-x86_64/Type-P.fm1-CLAP-linux-x86_64.zip) | linux-x86_64 | CLAP | 5.6 MB | `4ba275eda9f7c8355d898fed44dbf525b9e6ef59f3b88ecfef261489ae48f834` |
| [`Type-P.fm1-VST3-linux-x86_64.zip`](plugins/linux-x86_64/Type-P.fm1-VST3-linux-x86_64.zip) | linux-x86_64 | VST3 | 5.8 MB | `6ce29d9a6d9d7bb07ab53a50bda82dab5e2f39a143de21205ccfff0b5b1cf6d8` |

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
