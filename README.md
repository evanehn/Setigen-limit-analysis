cat << 'EOF' > README.md
# Setigen & turbo_seti Curved Signal Sensitivity Analysis

Empirical sensitivity analysis evaluating `turbo_seti`'s `FindDoppler` linear drift search against curved sinusoidal orbital paths generated with `setigen`.

## Setup & Parameters
- **Synthetic Frame:** 16,384 frequency channels (`df = 2.79 Hz`), 300 time steps (`30 min` observation), `n_coarse_chan = 1`.
- **Signal Injection:** Unresolved width (`1` channel), `input_snr = 25.0`, randomized orbital periods and Doppler excursion amplitudes.
- **Output:** Scatter plots mapping `recovered_snr` against orbital period and amplitude to identify where linear matched-filtering degrades.
EOF
