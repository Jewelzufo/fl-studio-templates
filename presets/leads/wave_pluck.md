# Wave Lead — Emotive Pluck Lead

**BPM:** 130 · **Insert:** 9 · **Root:** C4–C5  
**Character:** Emotive pluck lead — more melodic than arp, more plucky than saw lead

---

## Channel: Sytrus

**Name:** Lead — Emotive Pluck Wave · **Color:** `#FFD700` · **Root:** C4–C5

### Main
| Parameter | Value |
| --- | --- |
| Unison | 5v |
| Detune | 32% |
| SB | 70% |
| ALT | 40% |

> **Reference:** Between pad (7v / 42%) and anthem lead (7v / 55%).

### Operators
| Op | Wave | Ratio | Vol | Route |
| --- | --- | --- | --- | --- |
| Op1 | Saw | 1.00 | 100% | → Filter1 |
| Op2 | Triangle | 1.00 | 50% | → Filter1 |
| Op3 | Sine | 1.00 | 20% | → Out |

### Matrix
| Route | Amount |
| --- | --- |
| Op1 → Filter1 | 100% |
| Op2 → Filter1 | 100% |
| Op3 → Out | 20% |
| Filter1 → Out | 100% |

### Filter1
| Parameter | Value |
| --- | --- |
| Type | LP 24 dB |
| Cutoff | 68% |
| Res | 12% |
| Drive | 10% |
| Env Mod | 25% |

### Envelopes
| Env | Attack | Decay | Sustain | Release | Amount | Character |
| --- | --- | --- | --- | --- | --- | --- |
| Vol Env | 10 ms | 600 ms | 15% | 300 ms | — | Emotive — softer than arp's 0 ms, more sustained than arp's 450 ms / 0% |
| Filter Env | 0 ms | 400 ms | — | — | 25% | Bite |

---

## Mixer: Insert 9

| Parameter | Value |
| --- | --- |
| Sep | 35% Left (65% wide) |
| Vol | −1.0 dB |

---

## FX Chain

| Slot | Effect | Settings |
| --- | --- | --- |
| 1 | EQ2 | HP 140 Hz Cut24 · Peak 2.5 kHz +2.0 dB · Shelf 8 kHz +1.2 dB · Presence + air |
| 2 | Delay3 | Mode Ping-Pong · Time 1/8 dotted · FB 30% · Mix 25% · Cutoff 4.5 kHz · Wide bounce |
| 3 | Reverb2 | Decay 3.5 s · High Cut 7.0 kHz · Wet 35% · Size 88% · Emotive space |
| 4 | Love Philter | LP · Cutoff LFO 1/4 note, 8% amount · Slow movement (optional) |

---

## Sidechain

| Parameter | Value |
| --- | --- |
| Depth | −14 dB |
| Ratio | 3:1 |
| Attack | 5 ms |
| Release | 140 ms |
| Knee | Soft |

---

## MIDI

| Parameter | Value |
| --- | --- |
| Root | C4–C5 |
| Notes | Melodic single notes with occasional 3rds |
| Note Length | 1/8 to 1/2 bar |
| Velocity | 80–100% |
| Slide Notes | 20 ms for legato |
| Portamento | 30 ms, Mono **ON** |