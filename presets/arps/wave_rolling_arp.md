# Wave Arp — Signature Rolling Arp

**BPM:** 130 · **Insert:** 9/10 · **Root:** C4–C5  
**THE Wave signature** — arpeggiated pluck, rolling rhythmic

---

## Channel: 3x Osc — Light CPU (Recommended for Arp)

**Name:** Arp — Wave Signature · **Color:** `#00FFAA`

### Oscillators
| Osc | Wave | Vol | Coarse | Fine | Detune | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Osc1 | Saw | 50% | 0 | +0 | — | Bright core |
| Osc2 | Triangle | 30% | 0 | +5 cents | 8% | Softens saw |
| Osc3 | Sine | 10% | −12 st | — | — | Subtle sub layer |

### Amp Env
| Attack | Decay | Sustain | Release | Character |
| --- | --- | --- | --- | --- |
| 0 ms | 450 ms | 0% | 180 ms | Pluck shape |

---

## Alternative: Sytrus Version

### Main
| Parameter | Value |
| --- | --- |
| Unison | 3v |
| Detune | 18% |
| SB | 60% |
| ALT | 30% |
| Character | Tighter than pad/lead |

### Operators
| Op | Wave | Ratio | Vol | Fine | Notes |
| --- | --- | --- | --- | --- | --- |
| Op1 | Saw + Triangle blend | 1.00 | 100% | — | — |
| Op2 | Saw | 1.00 | 50% | +5 cents | — |

### Filter1
| Parameter | Value |
| --- | --- |
| Type | LP |
| Cutoff | 72% |
| Res | 12% |
| Env Mod | 30% |

**Filter Env:** Attack 0 ms · Decay 300 ms · Amount 30% · Character = bite

### Vol Env
| Attack | Decay | Sustain | Release |
| --- | --- | --- | --- |
| 0 ms | 450 ms | 0% | 180 ms |

---

## Mixer: Insert 9/10

| Parameter | Value |
| --- | --- |
| Sep | 40% Left (60% wide) |
| Vol | −2.0 dB |

---

## FX Chain

| Slot | Effect | Settings |
| --- | --- | --- |
| 1 | EQ2 | HP 120 Hz Cut24 · Peak 2.8 kHz +1.5 dB BW 0.7 · LP 6.5 kHz Cut24 · Bite |
| 2 | Delay3 | Time 3/16 dotted · FB 25% · Mix 22% · Cutoff 4.0 kHz · **KEY — rolling triplet feel** |
| 3 | Reverb2 | Decay 3.2 s · High Cut 7.5 kHz · Wet 30% · Size 85% |

---

## Arpeggiator — THE CORE

| Method | Setup |
| --- | --- |
| **A — VFX Arpeggiator** | Rate 1/16 · Gate 45% · Octave Range 2 oct · Direction Up · Velocity 80–100% |
| **B — Piano Roll** | Tools → Arpeggiator · Time 1/16 · Gate 45% · Octave 2 |
| **C — Manual** | Write C4 Eb4 G4 Bb4 C5 Eb5 G5 Bb5 etc. · 1/16 rolling · Strum 5–10 ms |

---

## Sidechain

| Parameter | Value |
| --- | --- |
| Depth | −14 dB |
| Ratio | 2.5:1 |
| Attack | 6 ms |
| Release | 150 ms |
| Knee | Soft |
| Character | Subtle, clear |

---

## MIDI

| Parameter | Value |
| --- | --- |
| Chord Input | Cm7 (C4 Eb4 G4 Bb4) held 1 bar |
| Arp Output | C4 Eb4 G4 Bb4 C5 Eb5 G5 Bb5 etc. · 1/16 rolling |
| Note Length | 1/16 short, Gate 45% |
| Velocity | 70–100%, humanize 10–