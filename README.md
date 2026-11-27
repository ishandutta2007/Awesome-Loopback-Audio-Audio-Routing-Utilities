# Awesome-Loopback-Audio-Audio-Routing-Utilities

# Awesome-Loopback-Audio-Audio-Routing-Utilities



Top Loopback Audio Audio Routing Utilities (Opensource) 🌟 Star if you like it! 🌟



A curated list of top loopback audio drivers, virtual audio cables, low-latency audio routing matrices, PipeWire/JACK graph patchbays, and network audio bridges—featuring commercial/proprietary platforms alongside their open-source equivalents.



---



## Table of Contents



- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source Equivalents & Tools](#open-source-equivalents--tools)

  - [macOS Virtual Audio Drivers & Loopback Routers](#macos-virtual-audio-drivers--loopback-routers)

  - [Linux PipeWire, JACK & PulseAudio Graph Routers](#linux-pipewire-jack--pulseaudio-graph-routers)

  - [Windows Virtual Audio Cables & Mixer Suites](#windows-virtual-audio-cables--mixer-suites)

  - [Cross-Platform Network Audio & AoIP Routing](#cross-platform-network-audio--aoip-routing)

  - [Open-Source Audio Effects, DSP Hosts & Per-App Volume Control](#open-source-audio-effects-dsp-hosts--per-app-volume-control)

- [Contributing](#contributing)



---



## SaaS/Hosted Platforms



Commercial, proprietary, and subscription/license-based virtual audio routing suites, studio audio hijackers, and commercial AoIP virtual soundcards.



* **[Loopback (Rogue Amoeba)](https://rogueamoeba.com)** - Industry-standard proprietary macOS virtual audio routing studio for combining applications and physical hardware into virtual audio devices.

* **[Audio Hijack (Rogue Amoeba)](https://rogueamoeba.com)** - Commercial macOS audio recording and node-based routing tool for capturing, processing, and redirecting any application's audio.

* **[VoiceMeeter (Banana & Potato - VB-Audio)](https://vb-audio.com)** - Proprietary donationware virtual audio mixer and multi-channel router for Windows streaming, podcasting, and VoIP workflows.

* **[VB-Cable (VB-Audio)](https://vb-audio.com)** - Proprietary virtual audio device driver for Windows and macOS acting as a zero-latency audio cable between two applications.

* **[Virtual Audio Cable (VAC - Eugene Muzychenko)](https://muzychenko.net)** - Commercial Windows kernel-mode WDM/KS virtual audio driver creating multiple independent virtual playback and recording endpoints.

* **[Dante Virtual Soundcard (Audinate)](https://audinate.com)** - Commercial software turning a Mac or PC into a Dante-powered AoIP interface with up to 64x64 channels over standard Ethernet.

* **[Sound Siphon (Static Z Software)](https://staticz.com)** - Proprietary macOS virtual audio capture and routing driver enabling per-app audio isolation and multi-device mixing.

* **[Elgato Wave Link](https://elgato.com)** - Proprietary digital audio mixing and sub-routing software for macOS and Windows tailored for creators and streamers.

* **[Sonar (SteelSeries GG)](https://steelseries.com)** - Commercial Windows virtual audio routing and parametric EQ suite splitting game, chat, media, and mic channels.



---



## Open-Source Equivalents & Tools



Free and open-source software (FOSS) virtual loopback drivers, PipeWire/JACK patchbays, cross-platform audio routers, and low-latency DSP hosts.



### macOS Virtual Audio Drivers & Loopback Routers



* **[Loopx (huangruiteng)](https://github.com)** - Open-source loopback audio and virtual audio routing utility engineered for clean, low-latency audio redirection.

* **[BlackHole (Existential Audio)](https://github.com)** - Modern, zero-latency open-source macOS virtual audio loopback driver supporting 2 to 256 channels across Intel and Apple Silicon.

* **[Soundflower (MATTINGALLS)](https://github.com)** - Classic open-source macOS kernel extension allowing applications to pass audio seamlessly to other applications.

* **[Background Music](https://github.com)** - Open-source macOS audio utility providing per-application volume control, auto-pause, and system audio recording via a virtual driver.

* **[GroundControl Caster / Open-Source CoreAudio Loopbacks (SimpleAudioLoopback)](https://github.com)** - Official open-source Apple CoreAudio AudioServerPlugIn driver templates powering modern user-space macOS loopback devices.

* **[Hosting AU / Element (Open-Source Modular Host)](https://github.com)** - Open-source modular AU/VST3 audio plugin host and patchbay for routing virtual audio devices and effects on macOS, Linux, and Windows.



### Linux PipeWire, JACK & PulseAudio Graph Routers



* **[PipeWire](https://freedesktop.org)** - Next-generation open-source Linux multimedia server unifying JACK and PulseAudio with ultra-low-latency graph-based audio/video routing.

* **[JACK Audio Connection Kit](https://github.com)** - Professional, low-latency open-source sound server daemon providing real-time sample-accurate audio and MIDI routing between applications.

* **[Helvum](https://freedesktop.org)** - Clean, modern open-source GTK patchbay for PipeWire written in Rust allowing visual drag-and-drop node connections.

* **[qpwgraph](https://github.com)** - Feature-rich Qt-based open-source graph manager for PipeWire enabling persistent patchbay presets and ALSA/JACK node routing.

* **[Carla](https://github.com)** - Fully featured open-source audio plugin host and modular patchbay supporting JACK, PipeWire, LV2, VST2/3, and AU routing.

* **[Cables (PipeWire / JACK Patchbay)](https://github.com)** - Open-source, user-friendly GUI utility for managing PipeWire virtual sinks, loopback links, and audio device routing.



### Windows Virtual Audio Cables & Mixer Suites



* **[Virtual-Audio-Capture-Grabber-Device](https://github.com)** - Open-source DirectShow virtual audio device for Windows enabling instant loopback capture of system playback audio.

* **[FlexASIO](https://github.com)** - Flexible, universal open-source ASIO driver wrapper bridging WASAPI, WDM-KS, and DirectSound for low-latency Windows audio routing.

* **[ASIO4ALL / KoordASIO](https://github.com)** - Open-source low-latency ASIO driver interface built on PortAudio for combining and routing Windows audio endpoints.

* **[Synchronous Audio Router (SAR)](https://github.com)** - Low-latency open-source Windows audio driver routing application audio streams directly through ASIO DAWs and virtual cables.

* **[EarTrumpet](https://github.com)** - Popular open-source Windows volume control and per-app audio device routing utility replacing the default system mixer.



### Cross-Platform Network Audio & AoIP Routing



* **[Sonobus](https://github.com)** - High-quality, low-latency open-source peer-to-peer network audio streaming and routing application for macOS, Windows, Linux, and iOS.

* **[JackTrip](https://github.com)** - Open-source multi-machine uncompressed audio system enabling ultra-low-latency bidirectional audio routing over local networks and the internet.

* **[VBAN Receptor / VBAN-Emitter (Open-Source Implementations)](https://github.com)** - Open-source Linux/macOS/Windows implementations of the VBAN protocol for streaming uncompressed audio to/from VoiceMeeter over UDP.

* **[AES67 Linux Daemon (aes67-linux-daemon)](https://github.com)** - Open-source Linux ALSA/PipeWire AoIP driver interoperable with Dante (AES67 mode) and Ravenna studio networks.

* **[Screamer / AudioRelay Open Alternatives (sndcpy)](https://github.com)** - Lightweight open-source tool forwarding Android device audio to desktop computers over USB/ADB without root.



### Open-Source Audio Effects, DSP Hosts & Per-App Volume Control



* **[EasyEffects (formerly PulseEffects)](https://github.com)** - Comprehensive open-source audio limiter, compressor, parametric equalizer, and noise-reduction suite built natively for PipeWire.

* **[Equalizer APO](https://sourceforge.net)** - Fast, system-wide open-source parametric/graphic equalizer and channel router implemented as a Windows Audio Processing Object.

* **[OBS Studio (Application Audio Capture)](https://github.com)** - Open-source broadcasting studio featuring built-in per-application audio capture, virtual audio monitoring, and multi-track routing.



---



## Contributing



Contributions are welcome! Feel free to open a Pull Request to add more open-source loopback audio drivers, PipeWire/JACK patchbays, virtual audio cables, or AoIP routing utilities.



1. Fork the repository.

2. Add your project under the appropriate category with a concise description.

3. Submit a Pull Request.
