# Reliable Agentic Workflows for Sustainable Multi-Language Scientific Software Interfaces

[![Live site](https://img.shields.io/badge/%F0%9F%8C%90_Live_site-ssun30.github.io-brightgreen)](https://ssun30.github.io/urssi-cantera-matlab-agentic-workflows/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![URSSI Fellowship](https://img.shields.io/badge/URSSI-Fellowship%202026-blue)](https://urssi.us/)

**🌐 Project website: <https://ssun30.github.io/urssi-cantera-matlab-agentic-workflows/>**

A **URSSI Fellowship** project (2026 cohort) investigating whether **agentic AI
workflows** can reliably maintain and sustain **cross-language interfaces** for
scientific software — using the [Cantera](https://cantera.org) MATLAB interface
as a case study.

This repository is the public home for the project. It holds the timeline, blog
posts, final report, and all openly accessible artifacts produced during the
fellowship.

---

## Why this project

Scientific software often relies on high-level language interfaces to make
compiled libraries accessible, but maintaining these interfaces across evolving
APIs, documentation, tests, and releases is labor-intensive and error-prone.
Cantera — an open-source, object-oriented toolkit for chemical kinetics,
thermodynamics, and transport — is written in C++ and exposes its functionality
through interfaces to Python, MATLAB, C, and Fortran.

Over the past three years, the Cantera MATLAB toolbox has been rebuilt through
two major architectural overhauls in response to changes in MATLAB
interface-generation technology and the sunsetting of legacy features. That
manual experience is the baseline for asking a sharper question:

> **Under what conditions can agentic tools support release-quality maintenance
> of scientific software interfaces, and what recurring failure modes require
> automated validation, human review, or both?**

## Objectives

- **O1 — Map the maintenance workflow.** Document how upstream library and
  generated-API changes propagate into MATLAB-facing wrappers, documentation,
  examples, tests, packaging, and release workflows.
- **O2 — Prototype AI-assisted workflows.** Evaluate where agentic tools can
  assist in updating wrappers as Cantera APIs evolve, adding documentation and
  examples, and validating outputs.
- **O3 — Develop validation checks.** Automated validation to catch executable
  failures, API mismatches, and numerical regressions; human review for semantic
  quality, usability, and MATLAB idiom.
- **O4 — Produce reusable community artifacts.** A workflow template, validation
  checklist, example CI/test components, case-study report, failure-mode
  analysis, and a cross-domain transferability sketch.

## Related repositories

- [Cantera MATLAB toolbox](https://github.com/ssun30/cantera_matlab) — the interface under study
- [Cantera](https://github.com/Cantera/cantera) — upstream C++ library

## License

Released under the [MIT License](LICENSE). Artifacts are intended to remain
archived and citable for reuse after the fellowship.

## Acknowledgment

> This work was supported by the US Research Software Sustainability Institute
> (URSSI) via grant G-2022-19347 from the Sloan Foundation.
