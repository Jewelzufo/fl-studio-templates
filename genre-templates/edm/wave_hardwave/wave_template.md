# Hardwave / Wave Blueprint
**FL Studio 21+ | 100% Stock Native Plugins**

## 1. PROJECT CONFIGURATION
| Parameter | Specification | Notes |
|---|---|---|
| Track Title | Aether Dynamics | Primary release title |
| Subgenre | Hardwave / Cyber-Wave | Modern atmospheric bass aesthetic |
| BPM | 130 BPM | Halftime rhythmic grid (65 BPM feel) |
| Rhythm | Trap / Halftime Beats | Syncopated patterns with straight rolls |
| Key | C Minor | Fundamental frequency anchor |
| DAW Compatibility | FL Studio Producer Edition+ | Tested on FL Studio 21+ |
| Plugin Restriction | Native Stock Only | Zero external VST dependencies |

## 2. PERCUSSION PARAMETER SHEETS

### A. Kick - Punchy hard-clipped low-end anchor
**Source:** `Packs > Drums > Kicks > Hip_Kick_4.wav` | Root C5 | Insert 1

| Component | Plugin / Control | Parameter | Value | Purpose |
|---|---|---|---|---|
| Sampler | Channel Rack | Pitch Coarse | 0 semitones | Natural pitch |
| Sampler | SMP INF Envelope | Out Knob | 15% | Truncate sub tail |
| Sampler | Precompute FX | Boost | +2% | Drive into clipper |
| Mixer Insert 1 | Fruity Parametric EQ 2 | Band 1 HP | 28 Hz Cut 40 | Remove infrasonic rumble |
| Mixer Insert 1 | Fruity Parametric EQ 2 | Band 3 Peak | 65 Hz +2.5 dB BW 0.40 | Enhance punch |
| Mixer Insert 1 | Fruity Parametric EQ 2 | Band 5 Peak | 3.2 kHz +1.8 dB BW 0.50 | Transient click |
| Mixer Insert 1 | Fruity WaveShaper | Pre Gain / Curve | 55% / Soft S-Curve | Hard-clip peak |

### B. Snare & Clap Layer - Crisp aggressive
**Source:** `Hip_Snare_2.wav + Hip_Clap_1.wav` | Insert 2

| Component | Plugin | Parameter | Value | Purpose |
|---|---|---|---|---|
| Sampler Snare | Channel Rack | Out Envelope | 0% | Natural decay |
| Sampler Clap | Channel Rack | Start Offset / Pan | 5 ms / +10% R | Prevent masking |
| Mixer Insert 2 | EQ 2 | Band 1 HP | 120 Hz Cut 24 | Clear low-end mud |
| Mixer Insert 2 | EQ 2 | Band 5 Peak | 200 Hz +2.0 dB | Weight and body |
| Mixer Insert 2 | Reverb 2 | Decay / High Cut / Wet | 1.8 s / 6.5 kHz / 22% | Medium room tail |
| Mixer Insert 2 | Limiter COMP | Threshold / Ratio | -14.0 dB / 6:1 | Clamp body |
| Mixer Insert 2 | Limiter COMP | Attack / Release | 8.0 ms / 95 ms | Pass transient / gated tail |

### C. Closed Hi-Hats - Fast 1/16 and 1/32 rolls
**Source:** `Hip_Hat_Close.wav` | Insert 3

| Component | Parameter | Value | Purpose |
|---|---|---|---|
| Volume Env | Attack / Hold / Decay | 0 ms / 100% / 180 ms | Retain transient, tighten roll |
| EQ2 | Band 1 HP / Band 7 High-Shelf | 400 Hz Cut 24 / 8.5 kHz +1.5 dB | Cut low-mids / brightness |
| PanOMatic | LFO Amount / Speed | 25% / 1/4 note step | Subtle auto-pan motion |

### D. Open Hat / Crash
| Component | Parameter | Value | Purpose |
|---|---|---|---|
| Sampler | SMP INF Length | 2.5 s | Truncate long tail |
| EQ2 | Band 1 HP | 500 Hz Cut 40 | Protect low/mid spectrum |
| Stereo Shaper | Preset / R Delay / Invert | Delay Stereo / 12.0 ms / OFF | Haas widening, mono-safe |

### E. Cyber Percussion
| Component | Parameter | Value | Purpose |
|---|---|---|---|
| Sampler | Pitch Fine | +15 cents | Brighten metallic timbre |
| EQ2 | HP 250Hz / Peak 2.4kHz | Cut 24 / +3.0 dB | Clean lower / elevate bite |
| Delay 3 | Mode / Time / Feedback / Cutoff | Ping-Pong / 1/8 / 35% / 3.5kHz | Alternating L/R echo |

## 3. SYNTHESIZER AND BASS

### A. Sub Bass - Deep clean 30-80 Hz
**Generator:** 3x Osc | Insert 6

| Component | Parameter | Value | Purpose |
|---|---|---|---|
| 3x Osc | Osc 1 Waveform / Vol | Sine / 100% | Pure fundamental |
| 3x Osc | Osc 2 & 3 Vol | 0% / 0% | Silenced |
| EQ2 | Band 1 HP / Band 7 LP | 25 Hz Cut 40 / 90 Hz Cut 40 | Remove DC / isolator |
| Channel Strip | Stereo Separation | 100% Right (Merged) | Absolute mono center |

### B. Reese Bass (Mid-Bass Drive)
**Generator:** Sytrus | Insert 7

| Component | Parameter | Value | Purpose |
|---|---|---|---|
| Sytrus Main | Unison Voices / Detune / Phase ALT | 5 / 35% / 60% | Multi-osc density & spread |
| Sytrus Op1/Op2 | Waveform / Detune | Saw / +8 cents | Harmonic saw foundation |
| Sytrus Matrix | Op1 to Out / Op2 to Out | 100% / 75% | Blend |
| EQ2 | HP 85Hz / Notch 500Hz / LP 4.5kHz | Cut 40 / -3dB / Cut 24 | Remove sub / boxiness / harshness |
| Fast Dist | Pre Gain / Thres Mix / Type | 45% / 35% / A-Type | Smooth mid-range drive |
| Chorus | Delay / Depth / Cross | 2.5 ms / 45% / Low-Cut | Modulated spread |

### C. Main Supersaw Lead
**Generator:** Sytrus | Insert 8

| Component | Parameter | Value | Purpose |
|---|---|---|---|
| Sytrus Main | Unison Voices / Detune / Stereo SB | 9 / 68% / 100% | Maximum thickness & width |
| Sytrus Op1 | Waveform | Saw | Core harmonic |
| Sytrus Op2 | Waveform / Freq Offset | Saw Inverted / +2.5 Hz | Rolling phase |
| Sytrus Op3 | Waveform | Pulse 20% | Square bite |
| Filter 1 | Type / Cutoff / Res | LP State Var / 78% / 12% | Bright tone shaping |
| EQ2 | HP 160Hz / Peak 4.5kHz | Cut 24 / +3.5 dB | Clear bass / presence |
| Chorus | Speed / Depth | 1.2 Hz / 50% | Analog widening |
| Delay 3 | Mode / Time / FB / Mix | Stereo / 1/4 / 40% / 30% | Tempo-synced echo |
| Reverb 2 | Decay / High Cut / Size / Wet | 4.5 s / 8.0 kHz / 90% / 35% | Massive hall space |

### D. Atmospheric Pads
**Generator:** Sytrus | Insert 9

| Component | Parameter | Value | Purpose |
|---|---|---|---|
| Sytrus Main | Unison Voices / Detune | 7 / 50% | Atmospheric spread |
| Op1 Env | Attack / Decay / Release | 1.8 s / 2.5 s / 2.0 s | Slow swell |
| Filter 1 | Type / LFO | LP 24dB / 1/2 note | Dynamic movement |
| EQ2 | HP 200Hz / Peak 6kHz | Cut 24 / -2.5 dB | Isolate mid/high |
| Love Philter | Cutoff Automation | 40% -> 90% | Swelling sweep |
| Reverb 2 | Decay / Wet | 6.5 s / 65% | Long ambient wash |

## 4. ATMOSPHERIC FX

### A. Vocal Chops / Plucks - Slicex | Insert 10
| Component | Parameter | Value | Purpose |
|---|---|---|---|
| Slicex | Pitch Bend Range | 2 semitones | Smooth glides |
| EQ2 | HP 220Hz / Peak 2.8kHz | Cut 24 / +3.0 dB | Remove chest / clarity |
| Delay 3 | Mode / Time / FB / Mix | Ping-Pong / 1/8d / 45% / 35% | Dotted rhythmic echo |
| Reverb 2 | Decay / Wet | 5.0 s / 50% | Ethereal hall |

### B. Noise Sweeps - 3x Osc White Noise | Insert 11
| Component | Parameter | Value | Purpose |
|---|---|---|---|
| 3x Osc | Osc 1 Wave / Vol | White Noise / 100% | Pure noise generator |
| EQ2 | Band 7 LP Sweep / Resonance | 100Hz -> 15kHz / BW 0.35 | Riser filter |
| Flanger | Speed / Depth / Wet | 0.4 Hz / 60% / 40% | Jet sweep |
| Delay 3 | Time / Feedback | 1/8 / 50% | Echo into drop |

## 5. MIXER ROUTING BLUEPRINT
| Track # | Track Name | Direct Routing | Sidechain Source | Stereo Mode |
|---|---|---|---|---|
| Insert 01 | Kick | Insert 12 (Drum Bus) | Inserts 6,7,8,9,10 | Mono (Merged) |
| Insert 02 | Snare / Clap | Insert 12 | - | Normal / Stereo |
| Insert 03 | Closed Hi-Hats | Insert 12 | - | Pan LFO Dynamic |
| Insert 04 | Open Hat / Crash | Insert 12 | - | Haas Stereo Offset |
| Insert 05 | Cyber Percussion | Insert 12 | - | Ping-Pong Stereo |
| Insert 06 | Sub Bass | Insert 13 (Synth Bass Bus) | - | 100% Mono Merged |
| Insert 07 | Reese Bass | Insert 13 | - | Wide Stereo (Chorus) |
| Insert 08 | Main Supersaw Lead | Insert 13 | - | 100% Wide Unison |
| Insert 09 | Atmospheric Pads | Insert 13 | - | Ultra-Wide |
| Insert 10 | Vocal Chops | Insert 14 (FX Bus) | - | Ping-Pong Stereo |
| Insert 11 | Noise Sweeps | Insert 14 | - | Stereo Flanged |
| Insert 12 | Drum Bus | Insert 0 (Master) | - | Controlled Stereo |
| Insert 13 | Synth Bass Bus | Insert 0 | - | Multi-Band Stereo |
| Insert 14 | FX Bus | Insert 0 | - | Wide Stereo |
| Insert 00 | Master | Audio Interface | - | Transparent Unity |

## 6. SIDECHAIN - Fruity Limiter COMP Mode
| Target Track | Source | Threshold | Ratio | Attack | Release | Knee | Purpose |
|---|---|---|---|---|---|---|---|
| Sub Bass (06) | Kick | -24.0 dB | Inf:1 | 0.2 ms | 75 ms | Hard | Total instant sub ducking |
| Reese Bass (07) | Kick | -20.0 dB | 8:1 | 2.0 ms | 120 ms | Soft | Rhythmic bounce |
| Main Lead (08) | Kick | -16.0 dB | 5:1 | 5.0 ms | 140 ms | Soft | Clear transient space |
| Pads (09) | Kick | -22.0 dB | 10:1 | 1.0 ms | 180 ms | Med | Deep pumping |
| Vocal Chops (10) | Kick | -14.0 dB | 4:1 | 4.0 ms | 110 ms | Soft | Rhythmic ducking |

## 7. MASTER CHAIN - Insert 0
| Order | Plugin | Parameter | Setting | Purpose |
|---|---|---|---|---|
| 1 | EQ2 | Band 1 HP | 25 Hz Cut 40 | Remove DC & rumble |
| 1 | EQ2 | Band 7 High-Shelf | 12.5 kHz +1.2 dB | Air boost |
| 2 | Compressor | Threshold / Ratio / Gain | -10.0 dB / 1.5:1 / +1.5 dB | Bus glue & makeup |
| 2 | Compressor | Attack / Release | 30 ms / 150 ms | Transient preservation |
| 3 | WaveShaper | Pre Gain / Graph | 52% / Soft S-Curve | Soft clip master peaks |
| 4 | Limiter | Mode / Ceiling / Gain / Release | LIMIT / -0.3 dB / +3.5 dB / 200 ms | Peak limit, -9 to -7 LUFS |

## 8. AUTOMATION
| Target Parameter | Location | Range | Purpose |
|---|---|---|---|
| Reverb 2 Wet Level | Insert 8 (Main Lead) | 20% -> 45% | Build cinematic swell before drop |
| Band 7 Low-Pass Cutoff | Insert 13 (Synth Bass Bus) | 400 Hz -> 15 kHz | 8-bar drop reveal sweep |
| Fast Dist Pre Gain | Insert 7 (Reese Bass) | 30% -> 60% | Increase saturation during drop |

## 9. FINAL VALIDATION CHECKLIST
- [ ] Sub Bass Mono Verification - 100% Merged on Insert 6
- [ ] Sub/Reese Crossover - 85 Hz
- [ ] Sidechain - 20 dB instant dip on sub
- [ ] Mono Compatibility - No phase cancellation
- [ ] Headroom - -6.0 dB pre-master
- [ ] 100% Stock Compliance
- [ ] Reference LUFS - -9 to -7 LUFS, TP -0.3 dB