# Exercise and Checklist Library — The Browser Input-to-Pixel Pipeline: Where Latency Lives

Read this during Phase 5 (exercises) and Phase 6 (checklists). Adapt
scenarios to the audience's domain; keep evaluation criteria intact — they
are what make the exercises assessable. In full-module mode, write an
expert-quality model solution for each included exercise.

## Table of Contents
- Part A: Practical Exercises
- Part B: Professional Gate Checklists

---

# Part A: Practical Exercises

## Exercise 1 — Decompose the input-to-pixel pipeline (input capture
**Scenario:** provide a realistic Latency and performance scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** decompose the input-to-pixel pipeline (input capture, JavaScript execution, style-layout, paint-raster, composite-display) with per-stage measurement points and cost mechanics (recalculation triggers, forced-synchronous-layout hazards, paint complexity, layer promotion).
**Constraints:** must use the framework taught in the corresponding unit; must state assumptions and trade-offs; one deliverable, length-bounded.
**Deliverable:** the professional artifact this capability produces (memo, table, plan, analysis, or model — as applicable).
**Evaluation criteria:** correct application of the framework; decisions justified with evidence; limitations honestly stated; artifact usable by a colleague without further explanation.

## Exercise 2 — Analyze main-thread contention from data-product computation with offload-destination strategies
**Scenario:** provide a realistic Latency and performance scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** analyze main-thread contention from data-product computation with offload-destination strategies, master event-system mechanics (dispatch phases, coalescing, passive listeners, pointer families, Event-Timing observation) and rAF render-synchronization (vsync alignment, on-demand invalidation, loop coordination).
**Constraints:** must use the framework taught in the corresponding unit; must state assumptions and trade-offs; one deliverable, length-bounded.
**Deliverable:** the professional artifact this capability produces (memo, table, plan, analysis, or model — as applicable).
**Evaluation criteria:** correct application of the framework; decisions justified with evidence; limitations honestly stated; artifact usable by a colleague without further explanation.

## Exercise 3 — Operate compositor-GPU parallel-path knowledge with its caveats
**Scenario:** provide a realistic Latency and performance scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** operate compositor-GPU parallel-path knowledge with its caveats, instrument through Performance-Observer entries, devtools flame-charts, and custom marks with bottleneck attribution, engineer visualization-specific pipelines (chart-update chains, large-DOM costs, hybrid renderers), prevent anti-patterns (thrashing, long tasks, rAF floods, listener leaks, main-thread animation) and consolidate stage-budget-allocation thinking with Amdahl intuition and measurement-verification loops.
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

## B1. Decompose the input to pixel pipeline checklist
- [ ] Decompose the input-to-pixel pipeline (input capture, JavaScript execution, style-layout, paint-raster, composite-display) with per-stage measurement points and cost mechanics (recalculation triggers, forced-synchronous-layout hazards, paint complexity, layer promotion)?
- [ ] Decisions and their justification are documented for review by a colleague

## B2. Analyze main thread contention from checklist
- [ ] Analyze main-thread contention from data-product computation with offload-destination strategies, master event-system mechanics (dispatch phases, coalescing, passive listeners, pointer families, Event-Timing observation) and rAF render-synchronization (vsync alignment, on-demand invalidation, loop coordination)?
- [ ] Decisions and their justification are documented for review by a colleague

## B3. Operate compositor GPU parallel path knowledge checklist
- [ ] Operate compositor-GPU parallel-path knowledge with its caveats, instrument through Performance-Observer entries, devtools flame-charts, and custom marks with bottleneck attribution, engineer visualization-specific pipelines (chart-update chains, large-DOM costs, hybrid renderers), prevent anti-patterns (thrashing, long tasks, rAF floods, listener leaks, main-thread animation) and consolidate stage-budget-allocation thinking with Amdahl intuition and measurement-verification loops?
- [ ] Decisions and their justification are documented for review by a colleague

## B4. Delivery quality checklist
- [ ] Every claim sourced, graded, or flagged as contested?
- [ ] All terminology explained on first use?
- [ ] Trade-offs stated wherever recommendations are context-dependent?
- [ ] Material reads as practitioner-written, not generic?
