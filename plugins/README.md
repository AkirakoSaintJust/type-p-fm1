# Plugins

Optional VST3 and CLAP builds. They use the same engine as the firmware
and the web app, with the designed editor and the saved banks.

## Install

- **VST3:** unzip the archive into your VST3 folder. On Linux that is
  `~/.vst3/`, on Windows `C:\Program Files\Common Files\VST3`.
- **CLAP:** unzip the archive into your CLAP folder. On Linux that is
  `~/.clap/`, on Windows `C:\Program Files\Common Files\CLAP`.
- Rescan plugins in your DAW. The plugin name is `P1Onken: Type P.fm1`.

## Licence

The plugin source is GPL-3.0-only. The binary links JUCE 8.0.9, which is
AGPL-3.0-only or commercial, so the binary is conveyed under the
AGPL-3.0-only terms for the JUCE part. The corresponding source is in
`../framework/plugin/` and `../framework/design/`, with the exact upstream
pins and build steps in `../DEPENDENCIES.md`. The licence texts travel
inside this archive in `licences/`, and a copy is in
`../third-party-licenses/`.

## Builds

- `linux-x86_64/Type-P.fm1-CLAP-linux-x86_64.zip`
- `linux-x86_64/Type-P.fm1-VST3-linux-x86_64.zip`
