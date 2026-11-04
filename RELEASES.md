# Type P.fm1 1.0.1

Released 2026-11-04 from source `31ecc64`.

## Downloads

| File | Platform | Format | Size | SHA-256 |
| --- | --- | --- | --- | --- |
| [`type-p-fm1.fwsc`](type-p-fm1.fwsc) | M-VAVE FM-1 | firmware | 597.9 kB | `1a1d53d3587db2dddcdd5d94c99b9acadfec5442bc568caae908c39291b28345` |
| [`Type-P.fm1-CLAP-linux-x86_64.zip`](plugins/linux-x86_64/Type-P.fm1-CLAP-linux-x86_64.zip) | linux-x86_64 | CLAP | 5.5 MB | `a434b6288c0b49ac407b59d3ad7242ab6ac2bb02822f74532daf17df26fb8480` |
| [`Type-P.fm1-VST3-linux-x86_64.zip`](plugins/linux-x86_64/Type-P.fm1-VST3-linux-x86_64.zip) | linux-x86_64 | VST3 | 5.7 MB | `45bb61f42f3735cb726f667c545ca74735173b212f84796c6f9b1006e71ed04e` |

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
