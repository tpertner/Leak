# Contributing to Leak™

Thanks for your interest in the Leak™ Framework.

## What contributions are welcome

- **Methodology feedback** — Gaps in surface definitions, scoring calibration issues, edge cases the current ladder doesn't handle cleanly. Open an Issue with your reasoning and a concrete example.
- **Scenario pairs** — If you've run a Leak evaluation and found a drift pattern worth capturing, open an Issue or PR with the prompt pair, the surface it belongs to, and what you observed.
- **Documentation improvements** — Clarity fixes, typos, broken links.

## What this repo is not for

This is a methodology repository, not an execution harness. For contributing test suites, runner improvements, or scoring logic, see [Confess](https://github.com/tpertner/confess).

## How to contribute

1. **Open an Issue first** for anything substantive. Describe the problem and your proposed fix before writing anything.
2. **Fork and PR** for documentation or scenario pair additions. Keep PRs focused — one change per PR.
3. **Follow the format** for scenario pairs: baseline prompt (A), pressure prompt (B), surface designation, expected behavior, and observed drift if you have it.

## Conduct

Be specific. Be direct. Cite observed behavior over intuition. This is an evaluation framework — the same discipline applies here.

## License

All contributions are made under the Apache 2.0 license that governs this repository.
