# Dubstep Wobble Bass — Classic

**Genre:** Dubstep / Brostep / Riddim · **BPM:** 140 · **Root:** F1 (43.65 Hz) · **Insert:** 6  
**Source:** 3x Osc + Love Philter

---

## Channel: 3x Osc

**Name:** Wobble Bass — Classic · **Color:** `#8B00FF` · **Root:** F1 (MIDI 29)

### Oscillators
| Osc | Wave | Vol | Coarse | Fine | Detune L | Detune R | Phase | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Osc1 | Saw | 60% | 0 | +0 | 0% | 0% | 0 | — |
| Osc2 | Saw | 40% | 0 | +7 cents | 15% | 15% | 180 | — |
| Osc3 | Sine | 20% | −12 st | — | — | — | — | Sub layer |

**Amp Env:** Attack 0 ms · Decay 0 ms · Sustain 100% · Release 80 ms

---

## Mixer: Insert 6

| Parameter | Value |
| --- | --- |
| Sep | 70% Left (30% wide) |
| Routing | Insert 6 → Insert 14 Bass Bus → Master |

---

## FX Chain

| Slot | Effect | Settings |
| --- | --- | --- |
| 1 | Fruity Love Philter | **Filter1:** LP 24 dB · Cutoff 35% · Res 18% · Drive 10%<br>**LFO1:** Target = Filter1 Cutoff · Shape = Sine · Rate = Synced 1/8 · Amount = 65% |
| 2 | EQ2 | HP 90 Hz Cut40 · Notch 400 Hz −2 dB · Peak 1.5 kHz +1 dB · LP 4.5 kHz Cut24 |
| 3 | Fast Dist | Pre 22% · Thres 25% · Type A · Mix 30% |
| 4 | Chorus | Delay 2.5 ms · Depth 30% · Rate 0.8 Hz · Mix 20% · Low Cut ON |

---

## Sidechain

| Parameter | Value |
| --- | --- |
| Processor | Fruity Limiter (COMP) |
| Input | 1 from Kick |
| Depth | −22 dB |
| Ratio | 10:1 |
| Attack | 0.5 ms |
| Release | 90 ms |
| Knee | Hard |

---

## Automation

| Target | Range / Sequence |
| --- | --- |
| Filter1 Cutoff | 25% → 60% over 8 bars |
| LFO1 Rate | 1/4 (slow) → 1/8 (std) → 1/16 (rapid) → 1/8T (variation) |
| LFO1 Amount | 45% → 75% |