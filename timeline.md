---
layout: page
title: Timeline
permalink: /timeline/
---

# Project Timeline

**Reliable Agentic Workflows for Sustainable Multi-Language Scientific Software Interfaces**

**Duration:** July 2026 – December 2026 (6 months)

The project proceeds from workflow design through validation, evaluation,
community refinement, and dissemination. Each phase maps to concrete
deliverables and to the URSSI Fellowship reporting checkpoints.

---

## Phase overview

| Month | Phase | Milestone |
|-------|-------|-----------|
| **1 — July 2026** | Workflow definition & baseline audit | Workflow map produced; automation, AI, validation, and review points identified. |
| **2 — August 2026** | AI-assisted interface & wrapper prototype | Prototype for adapting C++ materials to MATLAB-facing wrappers, docs, and examples. |
| **3 — September 2026** | Validation framework | API unit tests, example integration tests, numerical regression checks, cross-platform CI plan, and human-review rubric drafted. |
| **4 — October 2026** | Case-study evaluation | Validation results and failure modes summarized. |
| **5 — November 2026** | Community feedback & refinement | Feedback from Cantera, URSSI, and MathWorks contacts incorporated. |
| **6 — December 2026** | Final dissemination | Final deliverables released and archived. |

---

## Detailed plan

### Month 1 (July 2026) — Workflow definition & baseline audit
- Map how upstream library and generated-API changes propagate into
  MATLAB-facing wrappers, documentation, examples, tests, packaging, and release
  workflows (**O1**).
- Identify where automation, AI assistance, validation, and human review each
  belong in the workflow.
- **Deliverable:** workflow map.
- **URSSI checkpoint:** project timeline finalized; **Introduction blog post
  submitted (by Aug 1, 2026)**.

### Month 2 (August 2026) — AI-assisted interface & wrapper prototype
- Prototype agentic workflows for adapting existing C++ documentation and
  examples into MATLAB-facing wrappers, documentation, and examples (**O2**).
- Exercise agentic tooling (e.g., the MATLAB Agentic Toolkit) on a representative
  subset of wrappers.
- **Deliverable:** working prototype for the case-study subset.
- **URSSI checkpoint:** bi-weekly check-ins begin (~Aug 14, 2026).

### Month 3 (September 2026) — Validation framework
- Draft API unit tests, example integration tests, numerical regression checks,
  a cross-platform CI plan, and a human-review rubric (**O3**).
- Establish quantitative targets: ≥95% passing unit tests on the evaluated
  subset; 100% crash-free execution for all AI-assisted examples.
- **Deliverable:** validation framework and rubric.

### Month 4 (October 2026) — Case-study evaluation
- Run the documented agentic workflow against the manually maintained baseline
  on a representative subset of wrappers and Live Script examples.
- Summarize validation results and characterize at least three high-impact
  failure modes (incorrect wrapper semantics, invalid docs/examples, numerical
  inconsistencies).
- **Deliverable:** case-study evaluation results and failure-mode summary.
- **URSSI checkpoint:** **Update blog post** (progress / interesting finding /
  issue encountered).

### Month 5 (November 2026) — Community feedback & refinement
- Incorporate feedback from Cantera developers, MATLAB-oriented users, MathWorks
  technical leaders, and URSSI/community reviewers.
- Refine workflow, validation checks, and draft deliverables.
- **Deliverable:** revised workflow and artifacts.

### Month 6 (December 2026) — Final dissemination
- Release final deliverables (**O4**): reusable AI-assisted workflow template,
  validation checklist, failure-mode analysis, Cantera MATLAB case-study report,
  cross-domain transferability sketch, and URSSI-facing guidance on responsible
  use of agentic tools.
- **Deliverable:** final artifacts released and archived.
- **URSSI checkpoint:** **Conclusion blog post** and **final report (~1,500
  words)** submitted.

---

## URSSI reporting checkpoints at a glance

| Date | Item |
|------|------|
| Aug 1, 2026 | Timeline finalized + Introduction blog post |
| ~Aug 14, 2026 | Bi-weekly check-ins begin |
| ~Oct 2026 | Update blog post |
| Dec 2026 | Conclusion blog post + final report (~1,500 words) |

*Community feedback will be requested at three points: after the workflow map,
after validation on representative artifacts, and before final release. At least
three public updates (roughly every two months) will invite feedback on workflow
design, validation criteria, toolbox usability, and generalizability.*

---

## Success metrics

- End-to-end AI-assisted workflow covering **six maintenance stages**: wrapper
  development, documentation generation, example/tutorial generation, code
  validation/unit testing, toolbox packaging, and release/distribution.
- **≥95%** passing unit tests on the evaluated AI-assisted subset.
- **100%** crash-free execution for all AI-assisted examples in the final subset.
- Targeted analysis of **≥3** high-impact failure modes.

---

> This work was supported by the US Research Software Sustainability Institute
> (URSSI) via grant G-2022-19347 from the Sloan Foundation.
