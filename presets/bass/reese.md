# WAVE REESE BASS - STANDARD WAVE | BPM: 130 halftime 65 | Key: C Minor | Insert: 6
# Signature Wave - 4 voices 28% detune, slow 1/4 LFO drift, warm LP 3.2kHz

[Channel: Sytrus]
Name: Reese Bass - Wave Standard | Color: #4A90E2
Main: Unison 4v | Detune 28% | ALT 50% | SB 60% | Vol 0dB
Op1: Saw | Ratio 1.00 | Fine +0 | Vol 100% | Pan 0%
Op2: Saw | Ratio 1.00 | Fine +6 cents | Vol 65% | Pan +4% R
Op3: Sine | Ratio 0.50 (-12st) | Vol 18% | Sub layer

Matrix: Op1->Filter1 100% | Op2->Filter1 100% | Op3->Out 18% | Filter1->Out 100%

Filter1: LP 18dB | Cutoff 62% base | Res 8% | Drive 12% | Key Track 15%
Filter Env: Attack 0.3s | Decay 0.8s | Sustain 60% | Release 0.6s | Amount +25% to Cutoff
Filter LFO: Target=Cutoff | Wave=Sine | Rate=Synced 1/4 | Amount=15% | Phase 0

Volume Env: Attack 0.05s | Sustain 100% | Release 0.35s

[Mixer: Insert 6]
Sep: 30% Left (70% wide) | Routing: Insert 6 -> Insert 13 Bass Bus

[FX Chain]
Slot1 EQ2: HP 80Hz Cut40 | Notch 350Hz -2dB | Peak 1.2kHz +1dB | LP 3.2kHz Cut24
Slot2 Chorus: Delay 3.5ms | Depth 35% | Rate 0.6Hz | Mix 35% | Low Cut ON (CRITICAL)
Slot3 Fast Dist: Pre 28% | Thres 25% | Type A | Mix 40%
Slot4 Reverb2: Decay 1.2s | High Cut 5.5kHz | Wet 12% | Size 70%

[Sidechain]
-18dB | 6:1 | 2.5ms | 130ms | Soft | Gentle bounce

[Automation]
Filter1 Cutoff: 48%->72% over 8 bars
LFO Amount: 10%->20%
Chorus Depth: 25%->45%
Fast Dist Pre: 22%->35%