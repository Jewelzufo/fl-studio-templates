# Wave Saw Lead — Anthem

**BPM:** 130 · **Insert:** 9 · **Root:** C4–C5  
**Character:** Bright wall-of-sound, less aggressive than Hardwave (9v / 68%)

---

## Channel: Sytrus

**Name:** Saw Lead — Anthem Wave · **Color:** `#FF6B9D`

### Main
| Parameter | Value |
| --- | --- |
| Unison | 7v |
| Detune | 55% |
| SB | 85% |
| ALT | 50% |
| Vol | 0 dB |

> **Reference:** Hardwave = 9v / 68% / 100% SB · Wave anthem = 7v / 55% / 85% SB.

### Operators
| Op | Wave | Ratio | Vol | Fine | Notes |
| --- | --- | --- | --- | --- | --- |
| Op1 | Saw | 1.00 | 100% | — | Core |
| Op2 | Saw (Inverted) | 1.00 | 80% | +4 Hz offset | Rolling phase |
| Op3 | Pulse | 1.00 | 30% | — | Pulse Width 20% · Square bite |

### Matrix
| Route | Amount |
| --- | --- |
| Op1 → Filter1 | 100% |
| Op2 → Filter1 | 100% |
| Op3 → Filter1 | 100% |
| Filter1 → Out | 100% |

### Filter1
| Parameter | Value |
| --- | --- |
| Type | LP State Var |
| Cutoff | 72% (brighter than pad's 58%) |
| Res | 10% |
| Drive | 10% |

### Volume Env
| Attack | Decay | Sustain | Release | Character |
| --- | --- | --- | --- | --- |
| 20 ms | 0.3 s | 80% | 0.4 s | Fast lead, not slow swell |

---

## Mixer: Insert 9

| Parameter | Value |
| --- | --- |
| Sep | 25% Left (75% wide) |
| Vol | −1.5 dB |
| Routing | Insert 9 → Music Bus → Master |

---

## FX Chain

| Slot | Effect | Settings |
| --- | --- | --- |
| 1 | EQ2 | HP 150 Hz Cut24 · Peak 3.5 kHz +2.0 dB · Shelf 9 kHz +1.0 dB · Presence + air |
| 2 | Chorus | Delay 2.0 ms · Depth 40% · Rate 1.0 Hz · Mix 30% · Low Cut ON |
| 3 | Delay3 | Time 1/4 quarter · FB 35% · Mix 28% · Cutoff 5.0 kHz · Anthem delay |
| 4 | Reverb2 | Decay 3.8 s · High Cut 8.0 kHz · Wet 32% · Size 90% |

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
| Root | C4–C5 |
| Note Length | 1/2 to 1 bar, melodic single notes |
| Velocity | 85–100% |