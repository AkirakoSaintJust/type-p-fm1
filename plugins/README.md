# Plugins

The VST3 and CLAP builds are attached to each [GitHub Release](https://github.com/AkirakoSaintJust/type-p-fm1/releases). They use the same engine as the firmware and the web app, with the designed editor and the saved banks.

## Install

- **VST3:** unzip the archive into your VST3 folder. On Linux that is
  `~/.vst3/`, on Windows `C:\Program Files\Common Files\VST3`.
- **CLAP:** unzip the archive into your CLAP folder. On Linux that is
  `~/.clap/`, on Windows `C:\Program Files\Common Files\CLAP`.
- Rescan plugins in your DAW. The plugin name is `P1Onken: Type P.fm1`.

## Builds

Each release carries a VST3 and a CLAP archive for these platforms:

- `linux-x86_64`
- `linux-aarch64`
- `windows-x86_64`

The archive names follow `Type-P.fm1-<format>-<platform>.zip`.

## Licence

The plugin source is GPL-3.0-only. The binary links JUCE 8.0.9, which is
AGPL-3.0-only or commercial, so the binary is conveyed under the
AGPL-3.0-only terms for the JUCE part. The corresponding source is in
[`../framework/plugin/`](../framework/plugin/) and
[`../framework/design/`](../framework/design/), with the exact upstream pins and
build steps in [`../DEPENDENCIES.md`](../DEPENDENCIES.md). The licence texts are
in [`../third-party-licenses/`](../third-party-licenses/).
