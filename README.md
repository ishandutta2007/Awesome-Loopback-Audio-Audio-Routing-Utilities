# Awesome-Loopback-Audio-Audio-Routing-Utilities

# Awesome-Loopback-Audio-Audio-Routing-Utilities



Top Loopback Audio Audio Routing Utilities (Opensource) 🌟 Star if you like it! 🌟



A curated list of top loopback audio drivers, virtual audio cables, low-latency audio routing matrices, PipeWire/JACK graph patchbays, and network audio bridges—featuring commercial/proprietary platforms alongside their open-source equivalents.



---



## Table of Contents



- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source Equivalents & Tools](#open-source-equivalents--tools)

  - [macOS Virtual Audio Drivers & Loopback Routers](#macos-virtual-audio-drivers--loopback-routers)

  - [Linux PipeWire, JACK & PulseAudio Graph Routers](#linux-pipewire-jack--pulseaudio-graph-routers)

  - [Windows Virtual Audio Cables & Mixer Suites](#windows-virtual-audio-cables--mixer-suites)

  - [Cross-Platform Network Audio & AoIP Routing](#cross-platform-network-audio--aoip-routing)

  - [Open-Source Audio Effects, DSP Hosts & Per-App Volume Control](#open-source-audio-effects-dsp-hosts--per-app-volume-control)

- [Contributing](#contributing)



---



## Sector Overview & Market Dynamics

The global audio software and signal routing sector is estimated at approximately $5.9B to $14.4B (with the wider professional audio and audio processor ecosystem expanding past $14B+ to $19B by the 2030s). The market exhibits a **moderately fragmented, bifurcated structure**: while network-level AoIP protocol routing is concentrated around dominant standard-bearers like Audinate Dante, consumer, desktop, and studio virtual audio routing remains highly fragmented among boutique indie kernel/driver developers, freemium donationware utilities, and major gaming peripheral conglomerates using software suites to anchor hardware ecosystems.

---

## SaaS/Hosted Platforms

Commercial, proprietary, and subscription/license-based virtual audio routing suites, studio audio hijackers, and commercial AoIP virtual soundcards sorted by company size / valuation (descending).

| Platform / Product | Developer / Company | Company Size (Valuation / Revenue) | Starting Tier Pricing | Free Tier Limits / Free Trial | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Elgato Wave Link](https://elgato.com)** | Corsair Gaming / Elgato | ~$1.46B – $1.49B annual revenue (Corsair Gaming) | Free ($0) | Free forever plan with full access; no hardware lock required as of v3.0 | Proprietary digital audio mixing and sub-routing software for macOS and Windows tailored for creators and streamers. |
| **[Sonar (SteelSeries GG)](https://steelseries.com)** | GN Store Nord / SteelSeries | ~$1.2B valuation (GN Store Nord acquisition) / $500M+ revenue | Free ($0) | Free forever plan with full access; unconstrained hardware support across all brands on Windows | Commercial Windows virtual audio routing and parametric EQ suite splitting game, chat, media, and mic channels. |
| **[Dante Virtual Soundcard](https://audinate.com)** | Audinate (ASX: AD8) | ~$118M – $187M market cap / $46M annual revenue | $14.99 (30-day license) / $49.99 (perpetual single machine) | 30-day free trial; full feature parity with paid tier during the 30-day evaluation period | Commercial software turning a Mac or PC into a Dante-powered AoIP interface with up to 64x64 channels over standard Ethernet. |
| **[Loopback](https://rogueamoeba.com)** | Rogue Amoeba | ~$5M – $10M estimated revenue / ~10–40 employees | $99.00 (single-user perpetual license) | Free trial; full feature access but overlays audible noise degradation after 20 minutes of continuous audio passing (resets by toggling device) | Industry-standard proprietary macOS virtual audio routing studio for combining applications and physical hardware into virtual audio devices. |
| **[Audio Hijack](https://rogueamoeba.com)** | Rogue Amoeba | ~$5M – $10M estimated revenue / ~10–40 employees | $69.00 (single-user perpetual license) | Free trial; full feature access but overlays audible noise degradation after 10 minutes per capture session (resets by restarting app) | Commercial macOS audio recording and node-based routing tool for capturing, processing, and redirecting any application's audio. |
| **[VoiceMeeter (Banana & Potato)](https://vb-audio.com)** | VB-Audio Software | ~$1M – $5M estimated revenue / Boutique independent developer | $8.33 / €7.00 (Standard donationware tier) | Free forever plan for personal non-commercial use; non-blocking donation nag reminder displayed after 30 days of evaluation | Proprietary donationware virtual audio mixer and multi-channel router for Windows streaming, podcasting, and VoIP workflows. |
| **[VB-Cable](https://vb-audio.com)** | VB-Audio Software | ~$1M – $5M estimated revenue / Boutique independent developer | $15.00 (approx. for additional cables A+B / commercial license) | Free forever plan for standard single cable on personal/educational setups; commercial deployment requires volume license | Proprietary virtual audio device driver for Windows and macOS acting as a zero-latency audio cable between two applications. |
| **[Virtual Audio Cable (VAC)](https://muzychenko.net)** | Eugene Muzychenko | <$1M estimated revenue / Independent developer | $15.00 – $50.00 (Home to Business perpetual license) | Free Lite version limited to 1 virtual cable, max 48 kHz/16-bit/2-channels, home non-profit use only; full Trial version injects voice reminder after 30 minutes | Commercial Windows kernel-mode WDM/KS virtual audio driver creating multiple independent virtual playback and recording endpoints. |
| **[Sound Siphon](https://staticz.com)** | Static Z Software | <$1M estimated revenue / Micro-developer (single-person studio) | $49.00 (perpetual license for up to 2 Macs) | 14-day free trial; full unrestricted access to all features during the 14-day evaluation window | Proprietary macOS virtual audio capture and routing driver enabling per-app audio isolation and multi-device mixing. |



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
