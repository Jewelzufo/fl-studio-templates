# Dubstep Growl Bass — FM Talking Bass

**BPM:** 140 · **Insert:** 7 · **Root:** F1  
**The Brostep Sound** — Op1 modulates Op2

---

## Channel: Sytrus

**Name:** Growl Bass — Brostep · **Color:** `#FF0000` · **Root:** F1

### Main
| Parameter | Value |
| --- | --- |
| Unison | 4v |
| Detune | 32% |
| SB | 70% |

### Operators
| Op | Wave | Ratio | Vol | Role | Notes |
| --- | --- | --- | --- | --- | --- |
| Op1 | Sine | 1.00 | 100% | Carrier / Modulator | Modulates Op2 |
| Op2 | Sine | 2.50 | 100% | Carrier | Modulated by Op1 · FM growl vowel |
| Op3 | Saw | 1.00 | 15% | Bite layer | — |

### Matrix
| Route | Amount |
| --- | --- |
| Op1 → Op2 | 75% |
| Op2 → Filter1 | 100% |
| Op3 → Out | 15% |
| Filter1 → Out | 100% |

### Filter1
| Parameter | Value |
| --- | --- |
| Type | LP 24 dB |
| Cutoff | 38% |
| Res | 22% |
| Drive | 20% |
| Character | Vowel filter |

**Filter Env:** Attack 0.05 s · Decay 0.4 s · Amount 35% · Character = Talking

---

## FX Chain

| Effect | Settings |
| --- | --- |
| EQ2 | HP 90 Hz · Notch 280 Hz −2.5 dB · Peak 1.2 kHz +2.5 dB · LP 6.5 kHz |
| Fast Dist | Pre 38% · Thres 30% · Type A · Mix 45% |
| Waveshaper | Pre 30% · Curve Medium |
| Chorus | Delay 2.0 ms · Depth 30% · Low Cut **ON** |

---

## Automation — How to Make It Talk

| Target | Range | Effect |
| --- | --- | --- |
| Op1 → Op2 FM Amount | 40% → 85% | eee → ooo vowel morph |
| Filter Cutoff | 25% → 70% | Open growl |
| Op2 Ratio | 2.00 → 3.50 | Formant shift |
| LFO on Filter Cutoff | 1/8 rate, 15% | Wobble growl |

---

## Sidechain

| Source | Depth | Ratio | Attack | Release |
| --- | --- | --- | --- | --- |
| Kick + Snare | −20 dB | 8:1 | 1.0 ms | 100 ms |
| Snare (secondary) | −16 dB | 4:1 | — | — |