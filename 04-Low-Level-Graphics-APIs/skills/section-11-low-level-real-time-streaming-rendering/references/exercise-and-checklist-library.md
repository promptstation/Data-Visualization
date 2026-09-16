# Exercise and Checklist Library — Real-Time and Streaming Rendering: Live Data Graphics

Read this during Phase 5 (exercises) and Phase 6 (checklists). Adapt
scenarios to the audience's domain; keep evaluation criteria intact — they
are what make the exercises assessable. In full-module mode, write an
expert-quality model solution for each included exercise.

## Table of Contents
- Part A: Practical Exercises
- Part B: Professional Gate Checklists

---

# Part A: Practical Exercises

## Exercise 1 — Architect streaming rendering pipelines (WebSocket-SSE ingestion
**Scenario:** provide a realistic Graphics APIs scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** architect streaming rendering pipelines (WebSocket-SSE ingestion, worker decode-batching, backpressure drop policies) with ring-buffer sliding-window structures and texture-offset scroll techniques.
**Constraints:** must use the framework taught in the corresponding unit; must state assumptions and trade-offs; one deliverable, length-bounded.
**Deliverable:** the professional artifact this capability produces (memo, table, plan, analysis, or model — as applicable).
**Evaluation criteria:** correct application of the framework; decisions justified with evidence; limitations honestly stated; artifact usable by a colleague without further explanation.

## Exercise 2 — Implement incremental updates (tail-writes
**Scenario:** provide a realistic Graphics APIs scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** implement incremental updates (tail-writes, transient highlights, dirty regions) within continuous-versus-on-demand render-loop decisions with time-based frame-rate-independent animation.
**Constraints:** must use the framework taught in the corresponding unit; must state assumptions and trade-offs; one deliverable, length-bounded.
**Deliverable:** the professional artifact this capability produces (memo, table, plan, analysis, or model — as applicable).
**Evaluation criteria:** correct application of the framework; decisions justified with evidence; limitations honestly stated; artifact usable by a colleague without further explanation.

## Exercise 3 — Integrate temporal LOD (live binning pyramids
**Scenario:** provide a realistic Graphics APIs scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** integrate temporal LOD (live binning pyramids, streaming sketches, history-live composites) and multi-stream composition with time alignment and priority rendering, engineer end-to-end latency budgets with staleness honesty, ensure resilience (reconnect handling, flood throttling, soak-tested leak discipline).
**Constraints:** must use the framework taught in the corresponding unit; must state assumptions and trade-offs; one deliverable, length-bounded.
**Deliverable:** the professional artifact this capability produces (memo, table, plan, analysis, or model — as applicable).
**Evaluation criteria:** correct application of the framework; decisions justified with evidence; limitations honestly stated; artifact usable by a colleague without further explanation.

## Exercise 4 — Validate through frame-stability
**Scenario:** provide a realistic Graphics APIs scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** validate through frame-stability, latency-tracing, and resource-trend measurement.
**Constraints:** must use the framework taught in the corresponding unit; must state assumptions and trade-offs; one deliverable, length-bounded.
**Deliverable:** the professional artifact this capability produces (memo, table, plan, analysis, or model — as applicable).
**Evaluation criteria:** correct application of the framework; decisions justified with evidence; limitations honestly stated; artifact usable by a colleague without further explanation.

## Exercise 5 — Integrated capstone
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

## B1. Architect streaming rendering pipelines checklist
- [ ] Architect streaming rendering pipelines (WebSocket-SSE ingestion, worker decode-batching, backpressure drop policies) with ring-buffer sliding-window structures and texture-offset scroll techniques?
- [ ] Decisions and their justification are documented for review by a colleague

## B2. Implement incremental updates (tail writes, checklist
- [ ] Implement incremental updates (tail-writes, transient highlights, dirty regions) within continuous-versus-on-demand render-loop decisions with time-based frame-rate-independent animation?
- [ ] Decisions and their justification are documented for review by a colleague

## B3. Integrate temporal LOD (live checklist
- [ ] Integrate temporal LOD (live binning pyramids, streaming sketches, history-live composites) and multi-stream composition with time alignment and priority rendering, engineer end-to-end latency budgets with staleness honesty, ensure resilience (reconnect handling, flood throttling, soak-tested leak discipline)?
- [ ] Decisions and their justification are documented for review by a colleague

## B4. Validate through frame stability, latency tracing, checklist
- [ ] Validate through frame-stability, latency-tracing, and resource-trend measurement?
- [ ] Decisions and their justification are documented for review by a colleague

## B5. Delivery quality checklist
- [ ] Every claim sourced, graded, or flagged as contested?
- [ ] All terminology explained on first use?
- [ ] Trade-offs stated wherever recommendations are context-dependent?
- [ ] Material reads as practitioner-written, not generic?
