# Wave Saw Pad — Lush Atmospheric Bed

**BPM:** 130 · **Insert:** 8 · **Root:** C3–C4  
**Character:** Wide, not harsh

---

## Channel: Sytrus

**Name:** Saw Pad — Lush Wave · **Color:** `#7BA7FF` · **Root:** C3–C4

### Main
| Parameter | Value |
| --- | --- |
| Unison | 7v |
| Detune | 42% |
| SB | 80% |
| ALT | 50% |
| Vol | 0 dB |

> **Reference:** Hardwave supersaw = 9v / 68% / 100% SB · Wave pad = 7v / 42% / 80% SB — wide, not harsh.

### Operators
| Op | Wave | Ratio | Vol | Fine | Role |
| --- | --- | --- | --- | --- | --- |
| Op1 | Saw | 1.00 | 100% | +0 | Core |
| Op2 | Saw (Inverted) | 1.00 | 70% | +3 Hz offset | Rolling phase |
| Op3 | Sine | 0.50 (−12 st) | 15% | — | Sub warmth |

### Matrix
| Route | Amount |
| --- | --- |
| Op1 → Filter1 | 100% |
| Op2 → Filter1 | 100% |
| Op3 → Out | 15% |
| Filter1 → Out | 100% |

### Filter1
| Parameter | Value |
| --- | --- |
| Type | LP 24 dB |
| Cutoff | 58% base (automate 30% → 85%) |
| Res | 10% |
| Drive | 8% |

### Envelopes
| Env | Attack | Decay | Sustain | Release | Amount | Character |
| --- | --- | --- | --- | --- | --- | --- |
| Vol Env | 1.5 s | 2.0 s | 75% | 2.2 s | — | Slow swell signature |
| Filter Env | 1.2 s | 1.5 s | 50% | 1.8 s | +15% | — |

---

## Mixer: Insert 8

| Parameter | Value |
| --- | --- |
| Sep | 20% Left (80–100% ultra-wide) |
| Vol | −3.0 dB |
| Routing | Insert 8 → Bass Bus / Music Bus → Master |

---

## FX Chain

| Slot | Effect | Settings |
| --- | --- | --- |
| 1 | EQ2 | HP 180 Hz Cut24 · Peak 5.5 kHz −2.0 dB BW 0.8 · Soften harsh top |
| 2 | Love Philter | LP 24 dB · Cutoff 30% → 85% over 8 bars · Res 12% · Slow swelling sweep |
| 3 | Chorus | Delay 4.0 ms · Depth 45% · Rate 0.8 Hz · Mix 40% · Low Cut ON |
| 4 | Reverb2 | Decay 7.0 s · High Cut 7.0 kHz · Wet 55% · Size 95% · Diffusion 90% · **HUGE WASH** |
| 5 | Delay3 | Time 1/4 dotted · FB 20% · Mix 15% · Cutoff 4.0 kHz · Optional subtle echo |

---

## Sidechain

| Parameter | Value |
| --- | --- |
| Target | Pads |
| Source | Kick |
| Depth | −20 dB |
| Ratio | 8:1 |
| Attack | 1.5 ms |
| Release | 200 ms |
| Knee | Med |
| Character | Pumping bed |

---

## Automation

| Target | Range | Purpose |
| --- | --- | --- |
| Love Philter Cutoff | 30% → 85% over 8 bars | Swell |
| Reverb2 Wet | 35% → 65% | Build wash |
| Filter1 Cutoff | 48% → 75% | Brighten in drop |