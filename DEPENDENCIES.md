# Build dependencies

The firmware and web app build from the tree in this repository. The optional
plugin fetches two pinned upstream projects with CMake `FetchContent`, and the pins
are in `framework/plugin/juce/CMakeLists.txt`, which is the only reference for
them.

- **JUCE** 8.0.9, AGPL-3.0-only or commercial.
  <https://github.com/juce-framework/JUCE>
- **clap-juce-extensions** commit
  `7adee3a1bd4684d4caa5601100e364abccff4b4d`, MIT.
  <https://github.com/free-audio/clap-juce-extensions>
- **CLAP headers** 1.2.7, a submodule of the extension, MIT.
  <https://github.com/free-audio/clap>
- **VST3 SDK** the copy bundled in JUCE 8.0.9, GPL-3.0-only or the Steinberg
  licence. <https://github.com/steinbergmedia/vst3sdk>

JUCE 8 is not GPLv3. A distributed plugin binary that links JUCE is conveyed
under the AGPL-3.0-only terms for the JUCE part. The umetate source keeps its
GPL-3.0-only terms and GPLv3 section 13 permits the combination. A commercial
JUCE licence removes the AGPL obligation.

## Build the plugin

```sh
cmake -S framework/plugin -B build/plugin -DP1_BUILD_JUCE=ON -DP1_BUILD_CLAP=ON
cmake --build build/plugin
```

The build needs a C++20 compiler, CMake 3.22, Ninja or another generator, and
network access for the two `FetchContent` pins. To build offline, point
`FETCHCONTENT_SOURCE_DIR_JUCE` and
`FETCHCONTENT_SOURCE_DIR_CLAP-JUCE-EXTENSIONS` at local checkouts of the exact
pins above.
