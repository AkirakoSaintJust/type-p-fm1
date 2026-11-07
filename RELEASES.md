# Type P.fm1 1.0.4

Released 2026-11-07 from source `ce7418c`.

## Downloads

| File | Platform | Format | Size | SHA-256 |
| --- | --- | --- | --- | --- |
| [`type-p-fm1.fwsc`](type-p-fm1.fwsc) | M-VAVE FM-1 | firmware | 597.9 kB | `684d5167d491c11737d9e25a035d35c373d98d1daf2c61599fe74f83af9a2bc3` |
| [`Type-P.fm1-CLAP-linux-x86_64.zip`](plugins/linux-x86_64/Type-P.fm1-CLAP-linux-x86_64.zip) | linux-x86_64 | CLAP | 5.6 MB | `a79df3323d7e7cc0888dfb685033e3cf076a44197828dadcccf605b0560c0b42` |
| [`Type-P.fm1-VST3-linux-x86_64.zip`](plugins/linux-x86_64/Type-P.fm1-VST3-linux-x86_64.zip) | linux-x86_64 | VST3 | 5.8 MB | `7fd77baa45f0190b53883950c398f03adc46f557e169450fcbf97e7dab90d97f` |

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
