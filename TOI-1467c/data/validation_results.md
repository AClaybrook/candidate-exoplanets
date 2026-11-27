# Validation results for TOI-1467 c (candidate)

All measured on 2026-11-26/27 from public data.

| Test | Result | Verdict |
|---|---|---|
| Detection | BLS SDE 9.3, S/N 9.0; TLS S/N 9.7; 24 transits in 4 sectors | detected |
| Independent pipeline | SPOC Data Validation, sectors 14–86 run: TCE 2, P = 3.154093 d, 513 ± 84 ppm, model S/N 8.0, not flagged as an eclipsing binary | independently detected |
| Per-sector depth | 399 ± 135, 665 ± 124, 561 ± 103, 711 ± 136 ppm (χ² p = 0.36) | consistent |
| Single transits | 24/24 positive; χ² = 17.5 for 23 dof (p = 0.78); min leave-one-out S/N 9.2; 2019 alone S/N 6.1, 2022–24 alone S/N 7.7 | consistent, not driven by a few events |
| Odd/even | 1.1σ (our fit), 0.8σ (TLS), significance 0.18 (SPOC) | passes |
| Secondary eclipse | none at phase 0.5 | passes |
| Shape | transit-like box preferred over sinusoid by ΔBIC = 126 | passes |
| Aperture test (2-min pixels) | depth ratio core/pipeline/wide = 1.20/1.00/0.97; confirmed planet b = 1.14/1.00/0.87 | behaves like an on-target planet |
| SPOC ghost diagnostic | core 5.8, halo 0.79 | on the target's core aperture |
| Inverted light curve (same star) | best false signal S/N 5.8, below threshold | passes |
| Survey false-alarm control | 1,940 stars searched inverted: 0 false alarms at 1–10 d, against 5 real signals | passes |
| Keck/HIRES RVs (62) | K = 1.98 ± 0.94 m/s at transit phase; K < 3.9 m/s (2σ), M sin i < 5.5 M⊕ | rules out stellar/brown-dwarf eclipsing companion |
| High-resolution imaging (ExoFOP) | Keck/NIRC2 AO Δ7.2 mag at 0.5″; Gemini speckle Δ6.4–6.7 at 0.5″ | no close companions |
| TRICERATOPS, no imaging | FPP = 0.144 ± 0.007, NFPP = 1.6 × 10⁻³ | — |
| **TRICERATOPS + Keck AO contrast curve** | **FPP = 0.0021 ± 0.0002, NFPP = 2.0 × 10⁻³** | FPP passes (< 0.015); NFPP fails narrowly (> 0.001) |

TRICERATOPS scenario probabilities with the AO contrast curve:

| Scenario | Probability |
|---|---|
| Planet on the target (TP) | 0.976 |
| Diluted background planet (DTP) | 0.021 |
| Eclipsing binary on TIC 240968785 (32″, T = 16.8) | 0.0011 |
| Eclipsing binary on TIC 240968773 (16″, T = 16.8) | 0.0004 |

**What remains.** One ground-based transit showing that TIC 240968773 and
TIC 240968785 do not undergo ~18–23% eclipses would bring NFPP below 0.001
and complete statistical validation.
- **Next mid-transits (UTC, ±3 min):** 2026-11-28 06:14, 2026-12-01 09:56,
  2026-12-04 13:38, 2026-12-07 17:20, 2026-12-10 21:02, 2026-12-14 00:44.
- **Then:** every 3.1541320 d from BJD_TDB 2459887.1638.
