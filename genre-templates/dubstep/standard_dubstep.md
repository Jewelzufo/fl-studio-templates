# DUBSTEP - Template
**FL Studio 21+ | 100% Stock | 140 BPM Halftime | Brostep / Riddim / Melodic Dubstep**

> Dubstep is halftime drums (kick on 1, snare on 3), heavy sub 30-60Hz, wobble bass with LFO-modulated filter, FM growl basses, aggressive mid-bass.

## 1. PROJECT CONFIGURATION
| Parameter | Specification | Notes |
|---|---|---|
| Genre | Dubstep / Brostep / Riddim | Modern 2020s style |
| BPM | 140 BPM (Halftime 70 BPM feel) | Range 140-150 |
| Key | F Minor / C Minor | F1-F2 sub sweet spot |
| Rhythm | Halftime Dubstep | Kick beat 1, Snare beat 3 |
| DAW | FL Studio Producer Edition+ | 21+ |
| Plugins | 100% Stock Only | 3x Osc, Sytrus, Fruity FX |

## 2. DRUMS - Halftime Heavy

### A. Kick - Deep punchy, mono, very short
**Source:** `Hip_Kick_4.wav` | Insert 1 | Beat 1 only

| Component | Parameter | Value | Purpose |
|---|---|---|---|
| Sampler | Out Knob | 10% | Ultra-short for sub clearance |
| EQ2 | HP 32Hz / Peak 60Hz +3.5dB / Peak 2.8kHz +2.0dB | Rumble cut / thump / click |
| Soft Clipper | Threshold | -1.0 dB | Round |
| Mixer | Stereo Separation | 100% Right Merged | Mono kick |

**Pattern:** `X---|---|---|----` - Only beat 1, halftime

### B. Snare / Clap - Huge, on beat 3
**Source:** `Hip_Snare_2.wav + Hip_Clap_1.wav` | Insert 2

| Component | Parameter | Value | Purpose |
|---|---|---|---|
| Sampler Clap | Start Offset | 3ms / +8% R | Prevent masking |
| EQ2 | HP 130Hz / Peak 190Hz +2.5dB / Peak 5kHz +2.0dB | Clean / weight / snap |
| Reverb 2 | Decay 1.6s / Wet 24% / Size 88% | Large room |
| Limiter COMP | Threshold -12dB / Ratio 6:1 / ATK 6ms / REL 110ms | Clamp body |
| WaveShaper | Pre 20% | Add grit |

**Pattern:** `----|----|X---|----` - Only beat 3

### C. Hi-Hats & Cymbals
| Element | Pattern | Settings | Purpose |
|---|---|---|---|
| Closed Hat | 1/16 straight + 1/32 rolls | HP 450Hz / Shelf 9.5kHz +1.5dB | Drive |
| Open Hat | Every 4 beats or before snare | Length 500ms | Energy lift |
| Shaker | 1/16 straight | - | Top groove |

## 3. BASS FOUNDATION - Core of Dubstep

### A. Sub Bass - Pure sine, absolute mono
**Generator:** 3x Osc | Insert 5

| Component | Parameter | Value | Purpose |
|---|---|---|---|
| 3x Osc | Osc 1 Sine 100% / Osc2-3 0% | CRS 0 | Pure fundamental F1=43Hz |
| EQ2 | HP 28Hz / LP 75Hz Cut40 | Isolator | No harmonics above 75Hz |
| Mixer | Stereo Separation | 100% Right (Merged) | Absolute mono |

**Note:** Write F0-F1 range, avoid below E0

### B. Wobble Bass - LFO Filter Modulated (Signature)
**Generator:** 3x Osc + Love Philter | Insert 6

| Component | Parameter | Value | Purpose |
|---|---|---|---|
| 3x Osc | Osc1 Saw 60% / Osc2 Saw 40% +7 cents / Osc3 Sine 20% -1oct | Saw blend + sub layer |
| Love Philter | Filter LP 24dB / Cutoff 35% -> LFO mod | Main wobble filter |
| Love Philter LFO | Rate Synced 1/4 / 1/8 / 1/16 / Shape Sine or Saw / Amount 65% | **The wobble** |
| EQ2 | HP 90Hz / Notch 400Hz -2dB / LP 4.5kHz | Crossover / remove box |
| Fast Dist | Pre 22% / Thres 25% / A-Type / Mix 30% | Subtle drive |

**Automation:** LFO Rate 1/4 (intro) -> 1/8 (build) -> 1/16 (drop) = intensity increase

### C. Growl Bass / FM Bass - Brostep Growl
**Generator:** Sytrus | Insert 7 | **THE Brostep Sound**

| Component | Parameter | Value | Purpose |
|---|---|---|---|
| Sytrus Main | Unison 4 voices / Detune 32% / SB 70% | Wide growl |
| Sytrus Op1 | Sine / Ratio 1.00 / Modulates Op2 | Carrier |
| Sytrus Op2 | Sine / Ratio 2.50 / Modulated by Op1 | FM growl - vowel |
| Sytrus Op3 | Saw / Ratio 1.00 / Vol 15% | Adds bite |
| Matrix | Op1->Op2 75% / Op2->Filter1 100% / Filter1->Out 100% | FM routing |
| Filter 1 | LP 24dB / Cutoff 38% / Res 22% / Drive 20% | Vowel filter |
| Filter Env | Attack 0.05s / Decay 0.4s / Amount 35% | Talking envelope |
| EQ2 | HP 90Hz / Notch 280Hz -2.5dB / Peak 1.2kHz +2.5dB / LP 6.5kHz | Crossover / mud / growl presence |
| Fast Dist | Pre 38% / Thres 30% / Type A / Mix 45% | Aggressive brostep drive |
| Waveshaper | Pre 30% / Curve Medium | Extra grit |

**How to make it talk:**
- Automate Op1->Op2 FM amount 40%->85% = vowel morph eee->ooo
- Automate Filter Cutoff 25%->70% = open growl
- Automate Op2 Ratio 2.00->3.50 = formant shift
- LFO on Filter Cutoff 1/8 rate 15% = wobble growl

### D. Riddim Stab Bass - Off-beat choppy
| Component | Parameter | Value | Purpose |
|---|---|---|---|
| 3x Osc | Saw + Square blend / Pulse 30% | Hollow riddim tone |
| Env | Attack 0ms / Decay 180ms / Sustain 0% / Release 90ms | Short stab |
| Pattern | Off-beat 1/8, syncopated, leave gaps | Riddim groove - space is key |

## 4. MELODIC ELEMENTS

### A. Dubstep Supersaw Lead
| Component | Parameter | Value | Purpose |
|---|---|---|---|
| Sytrus Main | Unison 7 voices / Detune 55% / SB 85% | Wide but less than hardwave |
| Op1/Op2 | Saw / Saw Inv +4Hz / Pulse 20% | Wall-of-sound |
| EQ2 | HP 150Hz / Peak 3.5kHz +2dB | Clear / presence |
| Delay 3 | Time 1/4 / FB 35% / Mix 28% | Anthem delay |
| Reverb 2 | Decay 3.8s / Wet 32% / Size 90% | Big space |

### B. Dark Pad / Atmosphere
| Component | Parameter | Value | Purpose |
|---|---|---|---|
| Sytrus Main | Unison 6 voices / Detune 38% | Wide pad |
| Env | Attack 1.2s / Decay 2.0s / Release 2.0s | Slow swell |
| Reverb 2 | Decay 6.0s / Wet 55% | Huge wash |

## 5. FX & TRANSITIONS
| Type | Source / Insert | Settings | Purpose |
|---|---|---|---|
| Riser | 3x Osc White Noise Insert 12 | LP 100Hz->16kHz / Flanger 0.5Hz 60% | 8-bar build |
| Impact | Crash + Reverb 5s tail | Low-end boost 60Hz | Drop hit |
| Laser / Zap | Sytrus Sine -> Fast Dist 70% + Pitch Env +24st | FM zap | Fill |

## 6. MIXER ROUTING
| Track # | Track Name | Routing | Stereo Mode | Notes |
|---|---|---|---|---|
| Insert 01 | Kick | Insert 13 Drum Bus | Mono Merged | Halftime beat 1 |
| Insert 02 | Snare / Clap | Insert 13 | Stereo / Wide | Halftime beat 3 |
| Insert 03 | Hi-Hats Closed | Insert 13 | Pan LFO | 1/16 drive |
| Insert 04 | Open Hat / Crash | Insert 13 | Haas 10ms | Energy |
| Insert 05 | Sub Bass | Insert 14 Bass Bus | 100% Mono | <75Hz pure |
| Insert 06 | Wobble Bass | Insert 14 | Mono 70% | LFO filter |
| Insert 07 | Growl / FM Bass | Insert 14 | Stereo 70% | Brostep main |
| Insert 08 | Riddim Stab Bass | Insert 14 | Stereo 60% | Off-beat chops |
| Insert 09 | Lead / Supersaw | Insert 15 Music Bus | Stereo 80% | Melodic |
| Insert 10 | Pads / Atmosphere | Insert 15 | Ultra-Wide 90% | Intro/break |
| Insert 11 | Vocal Chops | Insert 15 or 16 | Ping-Pong | Hook |
| Insert 12 | FX / Risers | Insert 16 FX Bus | Wide Flanged | Transitions |
| Insert 13 | Drum Bus | Master | Controlled 2:1 | Punch |
| Insert 14 | Bass Bus | Master | Multi-band - CRITICAL | All bass here |
| Insert 15 | Music Bus | Master | Stereo Glue | Melody |
| Insert 16 | FX Bus | Master | Wide | Reverb sends |

## 7. SIDECHAIN - Heavy Pumping
| Target | Source | Threshold | Ratio | Attack | Release | Purpose |
|---|---|---|---|---|---|---|
| Sub Bass 05 | Kick | -28dB | Inf:1 | 0.1ms | 60ms | Instant total duck |
| Wobble Bass 06 | Kick | -22dB | 10:1 | 0.5ms | 90ms | Heavy duck |
| Growl Bass 07 | Kick + Snare | -20dB | 8:1 | 1.0ms | 100ms | Duck to both |
| Riddim Stab 08 | Kick | -18dB | 6:1 | 1.5ms | 80ms | Bounce |
| Growl Bass 07 | Snare | -16dB | 4:1 | 1ms | 90ms | Dubstep trick - sidechain to snare too |

## 8. MASTER CHAIN - Loud, Aggressive
| Order | Plugin | Setting | Purpose |
|---|---|---|---|
| 1 | EQ2 HP 30Hz Cut40 / High Shelf 10kHz +1.5dB | Remove rumble / air | Clean + Bright |
| 2 | Compressor -8dB / 2.5:1 / +2.0dB / 20ms / 100ms | Heavy glue | Aggressive |
| 3 | WaveShaper 58% / Soft S-Curve | Soft clip peaks | Louder |
| 4 | Limiter LIMIT / Ceiling -0.3dB / Gain +4.5dB / Release 150ms | Target **-7 to -5 LUFS** (-6 to -4 brostep) | Extremely loud |

## 9. AUTOMATION ESSENTIALS
| Target | Location | Range | Purpose |
|---|---|---|---|
| Love Philter LFO Rate | Wobble Bass Insert 6 | 1/4 -> 1/8 -> 1/16 | Increase intensity |
| Love Philter Cutoff Base | Wobble Bass | 25%->60% | Open wobble |
| Sytrus Op1->Op2 FM Amount | Growl Bass Insert 7 | 40%->85% | Vowel morph |
| Sytrus Filter Cutoff | Growl Bass | 25%->70% | Open growl |
| Sytrus Op2 Ratio | Growl Bass | 2.00->3.50 | Formant shift |
| Reverb Wet | Pads Insert 10 | 30%->65% | Build wash |

## 10. DUBSTEP ARRANGEMENT
| Section | Bars | BPM Feel | Elements | Notes |
|---|---|---|---|---|
| Intro | 16 | 140 | Pads + filtered drums + vocal chop + sub hint | Dark, LP 300Hz |
| Build 1 | 16 | 140 | Add kick/snare tease + riser + snare roll 1/16->1/32 + wobble LFO 1/4 | LFO rate increase |
| Drop A | 16 | 70 halftime heavy | Full: Kick beat1, Snare beat3, Sub + Wobble + Growl + hats | MAIN DROP |
| Break 1 | 8 | 140 atmospheric | Strip to pads + vocal + light drums | Emotional |
| Build 2 | 8 | 140 | Add riser + vocal buildup + LFO 1/8 | Second tension |
| Drop B | 16 | 70 halftime | Variation: New growl pattern, FM change, riddim stabs | Second hook |
| Bridge | 8 | 140 | Lead + chords + sub only | Melodic moment |
| Drop C / Final | 16 | 70 halftime | All bass layers + lead anthem | Final peak |
| Outro | 8 | 140 | Pads + FX tail + crash | Fade |

## 11. LFO & WOBBLE DESIGN DEEP DIVE

Classic Wobble (3x Osc + Love Philter)

1. 3x Osc: 2 Saws detuned +7 cents + Sine sub layer 
2. Love Philter -> Filter 1: LP 24dB 
3. Love Philter -> LFO: Sine or Saw Down • Rate: Sync 1/8, Amount 60-70% 4. Automate LFO Rate: 1/4 -> 1/8 -> 1/16 over 16 bars 

Growl Talking Bass (Sytrus FM)

1. Op1 (Sine) modulates Op2 (Sine Ratio 2.5) 
2. Filter 1: LP Res 22% - vowel shaping 
3. Automate Op1->Op2 amount 40%->85% = eee->ooo vowel



## 12. VALIDATION CHECKLIST
- [ ] BPM 140 halftime 70, kick beat1 snare beat3 only
- [ ] Sub Mono 100% Right Merged, LP 75Hz, F1 43Hz sweet spot
- [ ] Crossover Sub <75Hz, Wobble/Growl >90Hz HP
- [ ] Wobble LFO - Love Philter LFO synced 1/4->1/16, amount 65%
- [ ] Growl FM - Sytrus Op1->Op2 75% FM ratio 2.5, Filter Res 22%
- [ ] Growl talking - FM amount automation 40->85% vowel morph
- [ ] Sidechain heavy - Sub -28dB Inf:1, Wobble -22dB 10:1, also sidechain to snare
- [ ] Kick ultra-short Out 10%
- [ ] Snare huge on beat 3 only
- [ ] Headroom -6dB pre-master, master -7 to -5 LUFS, TP -0.3dB
- [ ] Stock compliance - Only 3x Osc, Sytrus, EQ2, Delay 3, Reverb 2, Love Philter, Fast Dist, WaveShaper
- [ ] LFO rate automation 1/4->1/16 verified
- [ ] Bass Bus - All bass to Insert 14 for unified filtering
