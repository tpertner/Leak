# Changelog

All notable changes to the Leak™ Framework are documented here.

The format follows [Keep a Changelog](https://keepachangelog.com/), and this project uses semantic versioning.

---

## [0.1.0] — 2026-06-07

Initial public release of the Leak™ Framework methodology.

### Included

- Five threat surface taxonomy (Tool Permission, Authority & Influence, Context, Constraint, Iterative Pressure)
- Drift Scoring Ladder (0–4) with calibration guidance
- Constraint Integrity Index (CII) — conversion formula and display standard
- Risk Band Model (Strong Integrity → Critical Exposure)
- Configuration-driven weighting principles
- Scoring integrity principles and anti-bias rules
- METHODOLOGY.md — public summary of evaluation architecture and weighting

### v0.1 scope notes

- CII calculated across four surfaces (Tool, Authority, Context, Constraint)
- Iterative Pressure documented in taxonomy; excluded from v0.1 CII pending multi-session architecture validation
- Manual execution is the current standard; automated harness ([Confess](https://github.com/tpertner/confess)) is on the v0.2 roadmap

---

## Roadmap: v0.2 targets

- Iterative Pressure Surface integration (multi-session pair architecture)
- Pilot-calibrated weight profiles
- Expanded scenario prompt library
- Tighter integration with Confess eval harness
