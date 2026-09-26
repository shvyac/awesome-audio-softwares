# Awesome Audio Softwares

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[日本語版はこちら / Japanese](README.ja.md)

A curated list of useful audio software — DAWs, editors, plugin hosts, open-source tools, visualization, and analysis — for musicians, engineers, researchers, and makers.

## Contents

- [DAWs](#daws)
- [Audio editors](#audio-editors)
- [Plugin hosts & formats](#plugin-hosts--formats)
- [Effects & processing](#effects--processing)
- [Synthesizers & modular](#synthesizers--modular)
- [Music visualization](#music-visualization)
- [Audio analysis & metering](#audio-analysis--metering)
- [DJ & live](#dj--live)
- [Infrastructure & I/O](#infrastructure--io)
- [Libraries & frameworks](#libraries--frameworks)
- [Related lists](#related-lists)
- [Contributing](#contributing)

---

## DAWs

Digital audio workstations for multitrack recording, MIDI, mixing, and arranging.

### Open source / free

- [Ardour](https://ardour.org/) - Professional open-source DAW for audio/MIDI recording, mixing, automation, and plugin hosting (LV2, VST2/VST3, AU, LADSPA). Linux, macOS, Windows.
- [LMMS](https://lmms.io/) - Open-source DAW focused on electronic music: pattern sequencing, piano roll, built-in synths/effects, VST/SoundFont support. ([GitHub](https://github.com/LMMS/lmms))
- [Qtractor](https://qtractor.sourceforge.io/) - Qt-based Linux DAW for MIDI and audio with JACK-friendly routing.
- [Zrythm](https://www.zrythm.org/) - Modern GPL DAW with timeline editing, automation, and LV2/VST/CLAP plugin support. v2 (C++/Qt rewrite) is in alpha testing as of 2026.
- [Stargate](https://github.com/stargatedaw/stargate) - Lightweight cross-platform DAW with a routing matrix and built-in plugin suite; aims to run well on modest hardware.
- [Waveform Free](https://www.tracktion.com/products/waveform-free) - Free edition of Tracktion Waveform; full DAW feature set with plugin hosting (registration required).
- [Cakewalk Sonar](https://www.cakewalk.com/sonar) - Full-featured Windows DAW; successor to the now-retired Cakewalk by BandLab (formerly SONAR). Free tier usable without a membership; opens existing `.cwp` projects.

### Commercial (reference)

Widely used commercial DAWs; listed for interoperability and workflow context.

- [REAPER](https://www.reaper.fm/) - Efficient, highly scriptable DAW (Cockos) with broad plugin format support (VST/VST3/AU/CLAP/LV2/JS) and a generous evaluation license. ([cockos.com/reaper](https://www.cockos.com/reaper/))
- [Ableton Live](https://www.ableton.com/live/) - Session/arrangement DAW popular for electronic music and live performance.
- [Logic Pro](https://www.apple.com/logic-pro/) - Apple's macOS/iPad DAW with deep stock instruments and mixing tools.
- [FL Studio](https://www.image-line.com/fl-studio/) - Pattern- and playlist-oriented DAW (Image-Line) with strong beat-making workflows.
- [Cubase](https://www.steinberg.net/cubase/) - Steinberg's long-running production DAW; origin of the VST ecosystem.
- [Bitwig Studio](https://www.bitwig.com/) - Modular, clip-launcher DAW with The Grid and strong modulation/routing.

---

## Audio editors

Multitrack or destructive editors for recording, cleanup, podcasts, and file work.

- [Audacity](https://www.audacityteam.org/) - Free, open-source multitrack audio editor and recorder; widely used for podcasts, cleanup, and simple editing. VST3/Nyquist plugins. Audacity 4 (Sep 2026) brings non-destructive, overlapping/groupable clips, a redesigned UI, and workspaces. ([GitHub](https://github.com/audacity/audacity), [Changelog](https://www.audacityteam.org/changelog/))
- [Tenacity](https://tenacityaudio.org/) - Community fork of Audacity focused on libre defaults and plugin formats (VST, LV2, LADSPA, AU). ([GitHub](https://github.com/tenacityteam/tenacity))
- [Ocenaudio](https://www.ocenaudio.com/) - Free cross-platform audio editor with real-time effects preview, VST support, and a strong spectrogram view.

---

## Plugin hosts & formats

Standalone hosts and the formats plugins ship in.

- [Carla](https://kx.studio/Applications:Carla) - Modular plugin host (KXStudio): LADSPA, DSSI, LV2, VST2/VST3, AU, SF2/SFZ; JACK and native drivers. ([GitHub](https://github.com/falkTX/Carla))
- [LV2](https://lv2plug.in/) - Open plugin standard widely used on Linux (and elsewhere); successor lineage to LADSPA/DSSI.
- [CLAP](https://cleveraudio.org/) - Modern open plugin API (CLever Audio Plugin) with growing host/plugin support.
- [JUCE](https://juce.com/) - Cross-platform C++ framework used to build many commercial and open-source audio apps and plugins.

---

## Effects & processing

FX suites, listening tools, and processing chains.

- [LSP Plugins](https://lsp-plug.in/) - Large open-source suite of studio processors (EQ, dynamics, metering, spatial, etc.) in LV2/LADSPA/VST/CLAP and standalone forms.
- [EffeTune](https://github.com/Frieve-A/effetune) - Real-time audio effect processor by Frieve-A designed for enthusiasts to enhance music listening.
- [Airwindows Consolidated](https://www.airwindows.com/consolidated/) - All of Chris Johnson's free, MIT-licensed Airwindows effects in a single plugin (CLAP/VST3/AU/LV2) for macOS, Windows, and Linux.
- [Neural Amp Modeler](https://www.neuralampmodeler.com/) - Free, open-source neural-network guitar amp/pedal capture and playback plugin; large community model library. ([GitHub](https://github.com/sdatkinson/NeuralAmpModelerPlugin))
- [Ultimate Vocal Remover](https://github.com/anjok07/ultimatevocalremovergui) - Open-source GUI for AI stem separation (vocals/instrumental/drums, etc.) using Demucs, MDX-Net, and other models.
- Stock / host FX - Most DAWs above ship useful EQ, dynamics, delay, and reverb; prefer durable host docs when choosing a primary chain.

---

## Synthesizers & modular

Instruments, modular environments, and drum machines.

- [VCV Rack](https://vcvrack.com/) - Virtual Eurorack modular synthesizer; free Rack Free edition plus commercial modules; DAW plugins available.
- [Cardinal](https://cardinal.kx.studio/) - Open-source modular synthesizer / VCV Rack fork as plugin and standalone. ([GitHub](https://github.com/DISTRHO/Cardinal))
- [plugdata](https://plugdata.org/) - Pure Data as a plugin (VST3/AU/LV2/CLAP) and standalone app with a modern visual patching GUI. ([GitHub](https://github.com/plugdata-team/plugdata))
- [Bespoke Synth](https://bespokesynth.com/) - Modular node-based synth/DAW hybrid with complex routing and VST hosting. ([GitHub](https://github.com/BespokeSynth/BespokeSynth))
- [Surge XT](https://surge-synthesizer.github.io/) - Open-source hybrid synthesizer (wavetable / FM / etc.) as VST3/AU/LV2/CLAP. ([GitHub](https://github.com/surge-synthesizer/surge))
- [Vital](https://vital.audio/) - Spectral warping wavetable synthesizer (free + paid tiers).
- [ZynAddSubFX](https://zynaddsubfx.sourceforge.io/) - Classic open-source softsynth (additive / subtractive / pad). ([GitHub](https://github.com/zynaddsubfx/zynaddsubfx))
- [Hydrogen](https://github.com/hydrogen-music/hydrogen) - Open-source drum machine / pattern sequencer (Linux-focused; cross-builds available).

---

## Music visualization

Real-time visuals driven by audio or MIDI.

- [projectM](https://github.com/projectM-visualizer/projectm) - Cross-platform, open-source music visualization library that is MilkDrop-compatible, rendering real-time audio-reactive visuals via OpenGL.
- [MilkDrop](https://en.wikipedia.org/wiki/MilkDrop) - Classic hardware-accelerated music visualization plugin for Winamp by Ryan Geiss; beat-synced user "presets."
- [Advanced Visualization Studio (AVS)](https://en.wikipedia.org/wiki/Advanced_Visualization_Studio) - Winamp visualization plugin by Nullsoft for building custom visual effect chains.
- [G-Force](https://en.wikipedia.org/wiki/G-Force_(visualization_software)) - Music visualization plugin by Andy O'Meara known for detailed, organic 3D visuals.
- [harmony_visualizer](https://github.com/Frieve-A/harmony_visualizer) - Tool by Frieve-A for visualizing the harmony of MIDI input.

---

## Audio analysis & metering

Spectrograms, MIR tools, loudness meters, and review utilities.

- [Sonic Visualiser](https://www.sonicvisualiser.org/) - Open-source app for detailed visualization, analysis, and annotation of music recordings; Vamp feature plugins. ([GitHub](https://github.com/sonic-visualiser/sonic-visualiser))
- [Spek](https://www.spek.cc/) - Lightweight open-source acoustic spectrum analyser (spectrogram) for checking encodes and transfers. ([GitHub](https://github.com/alexkay/spek))
- [Prism](https://github.com/Boof2015/prism) - Free open-source meter/visualizer rack (spectrum, scope, vectorscope, spectrogram, VU, LUFS) as desktop app and VST3/AU plugins.
- [Vamp plugins](https://vamp-plugins.org/) - Plugin API and collection for audio feature extraction used by Sonic Visualiser and related tools.
- [librosa](https://librosa.org/) - Python library for music and audio analysis (spectrograms, MFCCs, onset/beat, MIR pipelines). ([GitHub](https://github.com/librosa/librosa))
- [aubio](https://aubio.org/) - C/Python library and CLI tools for onset, pitch, tempo, beat, and MFCC analysis. ([GitHub](https://github.com/aubio/aubio))
- [Frieve's Sound Toolbox](https://github.com/Frieve-A/sound_toolbox) - Browser-based sound tools by Frieve-A: preview player, ABX tester, digital sampling visualizer, and more.
- [DIP Bench](https://github.com/Frieve-A/dipbench) - Digital piano benchmark tool by Frieve-A.
- [Audio Review](https://github.com/Frieve-A/audioreview) - Source for an audio equipment review site by Frieve-A with objective evaluations of headphones, speakers, and amplifiers.

---

## DJ & live

- [Mixxx](https://mixxx.org/) - Free, open-source DJ software with beatmatching, effects, MIDI/HID controllers, and library management. ([GitHub](https://github.com/mixxxdj/mixxx))

---

## Infrastructure & I/O

Low-latency audio plumbing used under many Linux (and some cross-platform) tools.

- [JACK](https://jackaudio.org/) - Professional low-latency audio connection kit; still central to many Linux studio graphs.
- [PipeWire](https://pipewire.org/) - Modern Linux multimedia server that can replace/bridge PulseAudio and JACK for apps and pro-audio graphs.
- [SonoBus](https://sonobus.net/) - Open-source, low-latency peer-to-peer network audio streaming for remote jamming and collaboration; standalone and plugin. ([GitHub](https://github.com/sonosaurus/sonobus))

---

## Libraries & frameworks

Building blocks for apps, plugins, and research code.

- [JUCE](https://juce.com/) - See [Plugin hosts & formats](#plugin-hosts--formats).
- [librosa](https://librosa.org/) / [aubio](https://aubio.org/) - See [Audio analysis & metering](#audio-analysis--metering).

---

## Related lists

- [OpenAudio](https://github.com/webprofusion/OpenAudio) - Catalog of open-source audio apps, plugins, and libraries.
- [awesome-linuxaudio](https://github.com/nodiscc/awesome-linuxaudio) - Extensive Linux audio software list (DAWs, synths, effects, utilities).
- [awesome-audio-dsp](https://github.com/BillyDM/awesome-audio-dsp) - Audio DSP resources, open-source plugins, and learning material.
- [Linux DAW](https://linuxdaw.org/) - Curated Linux DAW / plugin directory.
- [awesome.re](https://awesome.re/) - Awesome manifesto.

---

## Contributing

Contributions welcome — open a pull request to add a tool, fix a broken link, or suggest a category.

Prefer **durable official / docs URLs**, short blurbs, and tools that are shipping. Keep product names; mark open-source clearly when helpful.

## License

See [LICENSE](LICENSE).
