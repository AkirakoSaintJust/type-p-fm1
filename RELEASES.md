# Type P.fm1 1.0.4

Released 2026-11-06 from source `fc8a875`.

## Downloads

| File | Platform | Format | Size | SHA-256 |
| --- | --- | --- | --- | --- |
| [`type-p-fm1.fwsc`](type-p-fm1.fwsc) | M-VAVE FM-1 | firmware | 597.9 kB | `e941ce77c9ec5b8c058d637d9eb240f689adfcfb396590b4d8b8806e55f6689e` |
| [`Type-P.fm1-CLAP-linux-x86_64.zip`](plugins/linux-x86_64/Type-P.fm1-CLAP-linux-x86_64.zip) | linux-x86_64 | CLAP | 5.6 MB | `920398a5e52eef27b762883de9e61cd03a5340ff098d3b8917102fd5b9430382` |
| [`Type-P.fm1-VST3-linux-x86_64.zip`](plugins/linux-x86_64/Type-P.fm1-VST3-linux-x86_64.zip) | linux-x86_64 | VST3 | 5.8 MB | `dbc470239d2912159e18bca1016dca350b82e8b45ff1977ba4a8516048f8404a` |

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
