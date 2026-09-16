# Exercise and Checklist Library — SVG Performance, Scale Limits, and Hybrid Rendering Strategies

Read this during Phase 5 (exercises) and Phase 6 (checklists). Adapt
scenarios to the audience's domain; keep evaluation criteria intact — they
are what make the exercises assessable. In full-module mode, write an
expert-quality model solution for each included exercise.

## Table of Contents
- Part A: Practical Exercises
- Part B: Professional Gate Checklists

---

# Part A: Practical Exercises

## Exercise 1 — Model SVG performance costs (retained-mode node
**Scenario:** provide a realistic D3 and SVG scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** model SVG performance costs (retained-mode node, style-recalc, layout, paint chains) determining empirical ceilings through element-count-frame-time benchmarking, climb the in-SVG optimization ladder (static-layer separation, transform-based changes, path merging, instancing, containment hints) before medium abandonment, architect canvas-D3 hybrids with coordinate synchronization, Delaunay-quadtree hit-testing, and shared view-state, deploy progressive rendering (chunked creation, placeholder-refine, virtualization) and WebGL escalation via deck.gl computation-rendering splits under simplest-sufficient-medium discipline.
**Constraints:** must use the framework taught in the corresponding unit; must state assumptions and trade-offs; one deliverable, length-bounded.
**Deliverable:** the professional artifact this capability produces (memo, table, plan, analysis, or model — as applicable).
**Evaluation criteria:** correct application of the framework; decisions justified with evidence; limitations honestly stated; artifact usable by a colleague without further explanation.

## Exercise 2 — Manage SSR-static strategies and long-session leak stability
**Scenario:** provide a realistic D3 and SVG scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** manage SSR-static strategies and long-session leak stability.
**Constraints:** must use the framework taught in the corresponding unit; must state assumptions and trade-offs; one deliverable, length-bounded.
**Deliverable:** the professional artifact this capability produces (memo, table, plan, analysis, or model — as applicable).
**Evaluation criteria:** correct application of the framework; decisions justified with evidence; limitations honestly stated; artifact usable by a colleague without further explanation.

## Exercise 3 — Validate through scale benchmarks
**Scenario:** provide a realistic D3 and SVG scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** validate through scale benchmarks, device-tier testing, and CI performance budgets.
**Constraints:** must use the framework taught in the corresponding unit; must state assumptions and trade-offs; one deliverable, length-bounded.
**Deliverable:** the professional artifact this capability produces (memo, table, plan, analysis, or model — as applicable).
**Evaluation criteria:** correct application of the framework; decisions justified with evidence; limitations honestly stated; artifact usable by a colleague without further explanation.

## Exercise 4 — Integrated capstone
**Scenario:** one realistic problem spanning the whole section.
**Objective:** take the problem through every unit's framework in sequence.
**Constraints:** all unit artifacts required and internally consistent; evidence discipline maintained throughout.
**Deliverable:** a coherent campaign/portfolio document assembled as real professional documentation.
**Evaluation criteria:** consistency across artifacts; each capability demonstrably exercised; trade-offs stated at each decision point.

---

# Part B: Professional Gate Checklists

Use verbatim as module appendices and as workshop job aids. Every item must
force a decision or produce an artifact — items that are merely
inspirational get cut.

## B1. Model SVG performance costs checklist
- [ ] Model SVG performance costs (retained-mode node, style-recalc, layout, paint chains) determining empirical ceilings through element-count-frame-time benchmarking, climb the in-SVG optimization ladder (static-layer separation, transform-based changes, path merging, instancing, containment hints) before medium abandonment, architect canvas-D3 hybrids with coordinate synchronization, Delaunay-quadtree hit-testing, and shared view-state, deploy progressive rendering (chunked creation, placeholder-refine, virtualization) and WebGL escalation via deck.gl computation-rendering splits under simplest-sufficient-medium discipline?
- [ ] Decisions and their justification are documented for review by a colleague

## B2. Manage SSR static strategies and checklist
- [ ] Manage SSR-static strategies and long-session leak stability?
- [ ] Decisions and their justification are documented for review by a colleague

## B3. Validate through scale benchmarks, checklist
- [ ] Validate through scale benchmarks, device-tier testing, and CI performance budgets?
- [ ] Decisions and their justification are documented for review by a colleague

## B4. Delivery quality checklist
- [ ] Every claim sourced, graded, or flagged as contested?
- [ ] All terminology explained on first use?
- [ ] Trade-offs stated wherever recommendations are context-dependent?
- [ ] Material reads as practitioner-written, not generic?
