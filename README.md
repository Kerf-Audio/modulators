# Kerf Modulators

**Free beta.** A dockable, track-aware modulation panel for REAPER.

Each plugin on the selected track gets its own block of modulator slots. Drop in
an MSEG, LFO or envelope follower, map it to one or more FX parameters, and it
drives them in real time, even when the panel is hidden.

A thank-you to the REAPER community, which has inspired me since 2007.

## Status: community beta

Kerf Modulators has been tested and works on macOS, Windows and Linux. So far
that testing has been on small projects, around 10 tracks and 20 plugins. It
hasn't yet been tested thoroughly in edge cases or larger projects, so
**expect bugs**. That's where you come in: this beta is open so the REAPER
community can help find them.

Runs on:
- macOS 11+ (Apple Silicon and Intel)
- Windows 10 and 11 (x64)
- Linux (x86_64)

Please [report bugs](../../issues/new/choose) and ask questions in
[Discussions](../../discussions). Even a short report helps: what you did, what
happened, and your system. Support is through GitHub only. I read every report
and fix what I can, as time allows, but there's no guaranteed timescale.

**Back up your projects before using it.**

## Modulators

- **MSEG**: a multi-stage envelope you draw yourself, looped or one-shot, free or synced
- **Envelope Follower**: turns any track's level into modulation, for ducking and sidechain on any parameter
- **LFO**: six shapes (sine, triangle, saw, square, random, Perlin), free or tempo-synced, with jitter
- **Steps**: up to 16 held values on a beat division, with randomise
- **Macros**: four nameable knobs on every track, and the hub every other modulator can drive
- **ADSR**: a four-stage envelope triggered by the transport, a cycle or each media item
- **XY Pad**: two outputs in one control, with a chaos wander, free or beat-locked
- **Waves**: a curve library with real curve operations, saved shapes and undo

## Features

- Native REAPER docker: dock, float, and remember position
- Follows the selected track, with one block per plugin and up to 12 slots each
- Up to 128 targets per modulator, each with its own range and polarity
- Cross-track modulation, including other tracks' macros
- Chaining through macros, with no feedback loops
- Quick knobs per plugin, with templates every new instance picks up
- Native REAPER modulation for the LFO and follower where possible, sample accurate
- Timing compensation so beat-locked modulation lands on the grid
- Keeps running when the panel is hidden or another track is selected
- Everything saved in the project
- Four accent themes in light or dark
- Built-in diagnostics for tracking down stutters

## Roadmap: testing first

This first release phase is for testing and bug fixing. No new features will be
added until version 1.0 is out and stable. Feature requests are welcome in
[Discussions](../../discussions) or as an Issue, and they will be looked at
after 1.0.

## Install

Install with ReaPack. See [INSTALL.md](INSTALL.md) or the [install guide (PDF)](docs/kerf-modulators-install-guide.pdf).

## Documentation

- [Install guide (PDF)](docs/kerf-modulators-install-guide.pdf)
- [User manual (PDF)](docs/kerf-modulators-manual.pdf)

## Licence

Kerf Modulators is free to use, including for commercial work, under the
[Kerf Audio Freeware Licence](LICENSE.txt). It is not open source.
Third-party components are listed in [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).

Danny Wincott, trading as Kerf Audio
