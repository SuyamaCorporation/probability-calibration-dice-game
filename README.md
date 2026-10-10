# Probability Calibration Dice Training Game

A 20-round calibration training game where players estimate the probability of dice outcomes before rolling, then receive Brier score feedback to improve their probabilistic intuition.

## Key Features

- **Six die types**: d4, d6, d8, d10, d12, d20 chosen randomly each round with conditions like "roll ≥ N", "roll ≤ N", or "roll exactly N"
- **Brier score feedback**: per-round and running mean Brier score (estimate/100 − outcome)² computed and colour-coded green/yellow/red
- **Animated die roll**: spinning animation before revealing the result, making estimation visceral and engaging
- **Calibration curve**: 10-bucket bar chart (0–9% through 90–100%) showing actual success frequency vs stated probability after all 20 rounds
- **localStorage history**: saves mean Brier scores across sessions; final screen classifies calibration quality (Excellent / Good / Moderate / Poor)
