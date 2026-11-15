# Reckless Polysynth

The downloads of Reckless Polysynth, a polyphonic virtual-analog synthesiser: three oscillators that can each be a
stack of up to eight detuned copies fanned across the stereo field, a noise source, two filters, four envelopes,
three LFOs locked to the host's tempo, an eight-slot modulation matrix, and four of the Reckless effects hosted
whole in an order you arrange. A VST3, an Audio Unit on macOS and a standalone app, for Windows, macOS and Linux.
Free to use.

**No release has been cut yet.** The download table lands here with the first one. Until then there is nothing to
install, and the links below do not resolve.

| | | |
|---|---|---|
| macOS 13.3 (Ventura) or later, Apple silicon or Intel | `reckless-polysynth-macos.pkg` | signed and notarized installer |
| Windows 10 or 11, 64-bit | `reckless-polysynth-win64-setup.exe` | signed installer |
| Linux x64: Debian, Ubuntu, Mint | `reckless-polysynth-linux-amd64.deb` | `sudo apt install ./reckless-polysynth-linux-amd64.deb` |
| Linux x64, any distribution with glibc 2.38 | `reckless-polysynth-linux-x64.zip` | the VST3 and app to copy by hand |

Every release is listed under [Releases](https://github.com/reckless-technology/polysynth-releases/releases) with its
notes and `SHA256SUMS`, each file's checksum. The download page, the user guide and the news are at
[recklesstechnology.com](https://recklesstechnology.com/).

A little of what is in it: the first filter is a four-pole transistor-ladder lowpass at 24 dB an octave that sweeps
and self-oscillates, and the second is switchable low, band or highpass, the two running in series or in parallel.
The hosted effects are the real Reckless plugins rather than imitations of them — the Mod, the Drive, the Delay and
the Oldsverb — each switched on or off, in a chain order a preset remembers. It comes with fifty-eight factory
presets in six families, and up to 32 voices with glide, the sustain pedal, the wheels and channel pressure.

Reckless Polysynth is installed on its own, apart from the Reckless plugin bundle at
[plugins-releases](https://github.com/reckless-technology/plugins-releases): it is an instrument rather than an
effect, and it is not one of the Pedalboard's chain. It does, however, **share the suite's version number** — one
tag is one number for every product that release carries, so a Polysynth 1.3.0 and a Reckless plugins 1.3.0 are
built from the same commit.

This repository holds the downloads alone — the releases here are written only by the source repository's
promotion, never by hand. The synthesiser is free to use under the end-user licence the installer shows (also at
[recklesstechnology.com/legal/eula](https://recklesstechnology.com/legal/eula/)); it is not open source.
Questions, bugs and ideas: hello@recklesstechnology.com.
