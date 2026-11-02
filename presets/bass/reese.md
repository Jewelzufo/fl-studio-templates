# Wave Reese Bass — Standard Wave

**BPM:** 130 (halftime 65) · **Key:** C Minor · **Insert:** 6  
**Signature Wave** — 4 voices, 28% detune, slow 1/4 LFO drift, warm LP at 3.2 kHz

---

## Channel: Sytrus

**Name:** Reese Bass — Wave Standard · **Color:** `#4A90E2`

### Main
| Parameter | Value |
| --- | --- |
| Unison | 4v |
| Detune | 28% |
| ALT | 50% |
| SB | 60% |
| Vol | 0 dB |

### Operators
| Op | Wave | Ratio | Fine | Vol | Pan | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Op1 | Saw | 1.00 | +0 | 100% | 0% | — |
| Op2 | Saw | 1.00 | +6 cents | 65% | +4% R | — |
| Op3 | Sine | 0.50 (−12 st) | — | 18% | — | Sub layer |

### Matrix
| Route | Amount |
| --- | --- |
| Op1 → Filter1 | 100% |
| Op2 → Filter1 | 100% |
| Op3 → Out | 18% |
| Filter1 → Out | 100% |

### Filter1
| Parameter | Value |
| --- | --- |
| Type | LP 18 dB |
| Cutoff | 62% base |
| Res | 8% |
| Drive | 12% |
| Key Track | 15% |

**Filter Env:** Attack 0.3 s · Decay 0.8 s · Sustain 60% · Release 0.6 s · Amount +25% to Cutoff

**Filter LFO:** Target = Cutoff · Wave = Sine · Rate = Synced 1/4 · Amount = 15% · Phase 0

### Volume Env
Attack 0.05 s · Sustain 100% · Release 0.35 s

---

## Mixer: Insert 6

| Parameter | Value |
| --- | --- |
| Sep | 30% Left (70% wide) |
| Routing | Insert 6 → Insert 13 Bass Bus |

---

## FX Chain

| Slot | Effect | Settings |
| --- | --- | --- |
| 1 | EQ2 | HP 80 Hz Cut40 · Notch 350 Hz −2 dB · Peak 1.2 kHz +1 dB · LP 3.2 kHz Cut24 |
| 2 | Chorus | Delay 3.5 ms · Depth 35% · Rate 0.6 Hz · Mix 35% · Low Cut **ON (CRITICAL)** |
| 3 | Fast Dist | Pre 28% · Thres 25% · Type A · Mix 40% |
| 4 | Reverb2 | Decay 1.2 s · High Cut 5.5 kHz · Wet 12% · Size 70% |

---

## Sidechain

| Parameter | Value |
| --- | --- |
| Depth | −18 dB |
| Ratio | 6:1 |
| Attack | 2.5 ms |
| Release | 130 ms |
| Knee | Soft |
| Character | Gentle bounce |

---

## Automation

| Target | Range |
| --- | --- |
| Filter1 Cutoff | 48% → 72% over 8 bars |
| LFO Amount | 10% → 20% |
| Chorus Depth | 25% → 45% |
| Fast Dist Pre | 22% → 35% |