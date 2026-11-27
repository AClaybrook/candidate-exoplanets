# Candidate exoplanets

Planet candidates found in an independent search of public NASA TESS data,
with the evidence behind each. These are **candidates**, not confirmed
planets.

## Candidates

| Candidate | Host | Period (d) | Radius (R⊕) | Status | Report |
|---|---|---|---|---|---|
| **TOI-1467 candidate 2** | TOI-1467 = TIC 240968774, M0/M1 dwarf, 37.4 pc, T = 10.6 | 3.1541320 ± 0.0000041 | ≈ 1.27 | Candidate. Second planet in a system with a confirmed planet (TOI-1467 b). TRICERATOPS FPP = 0.002 with archival AO imaging; NFPP = 0.002 awaits one ground-based transit to clear two faint neighbours. Also flagged as SPOC TCE 2 (sectors 14–86); not a TOI. | [TOI-1467-candidate-2/](TOI-1467-candidate-2/) ([PDF](TOI-1467-candidate-2/TOI-1467_candidate2_report.pdf), [interactive page](TOI-1467-candidate-2/index.html)) |

### Lower-confidence signals (not submitted)

These signals passed automated vetting in the same search, but each is
marginal (S/N 7–10) and has not had the full set of checks.

| Star | Period (d) | Epoch (BJD_TDB) | Depth (ppm) | Duration (h) | Rp (R⊕) | S/N | Tmag |
|---|---|---|---|---|---|---|---|
| TIC 184610711 | 1.87430 | 2459885.7463 | 330 | 0.89 | 1.60 | 8.0 | 9.69 |
| TIC 137708202 | 3.37063 | 2458875.5503 | 451 | 1.95 | 1.26 | 8.1 | 10.69 |
| TIC 51163909 | 1.14147 | 2460671.6990 | 434 | 1.69 | 1.22 | 9.5 | 10.74 |
| TIC 111780978 | 1.08617 | 2459317.3134 | 406 | 0.93 | 1.01 | 7.4 | 11.15 |

## The search, in brief

- **Sample:** 1,942 nearby (< 60 pc) K and M dwarfs (Tmag < 11.5), each seen
  in 2–4 TESS sectors spread over ≥ 3 years. In total 5,989 star-sectors and
  6.8 × 10⁷ photometric measurements.
- **Method:** box-least-squares transit search on stitched SPOC and
  full-frame-image light curves, followed by automated and manual vetting.
- **Calibration:**
  - the same search on inverted light curves gives the false-alarm rate;
  - 708 synthetic planets injected into real light curves give the
    sensitivity.

Acknowledgement: this research has made use of the Exoplanet Follow-up
Observation Program (ExoFOP; DOI: 10.26134/ExoFOP5) website, which is
operated by the California Institute of Technology, under contract with the
National Aeronautics and Space Administration under the Exoplanet Exploration
Program. It uses data collected by the TESS mission, obtained from the MAST
data archive at the Space Telescope Science Institute (STScI).
