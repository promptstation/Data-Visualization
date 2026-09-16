# Exercise and Checklist Library — Input Handling: Debounce, Throttle, Batch, and the Event Economy

Read this during Phase 5 (exercises) and Phase 6 (checklists). Adapt
scenarios to the audience's domain; keep evaluation criteria intact — they
are what make the exercises assessable. In full-module mode, write an
expert-quality model solution for each included exercise.

## Table of Contents
- Part A: Practical Exercises
- Part B: Professional Gate Checklists

---

# Part A: Practical Exercises

## Exercise 1 — Engineer the input layer against event-flood realities (pointer sample rates
**Scenario:** provide a realistic Latency and performance scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** engineer the input layer against event-flood realities (pointer sample rates, scroll-resize cascades) with useful-update-rate analysis per interaction class, master throttle mechanics (leading-trailing edges, frame-aligned rAF throttles as visual-update defaults, failure modes) and debounce semantics (wait selection by context, maxWait starvation bounds, over-debounce cargo-cult avoidance), consolidate work through rAF batching with latest-value-wins, DOM read-write batching, microtask coalescing, and event-coalescing utilization.
**Constraints:** must use the framework taught in the corresponding unit; must state assumptions and trade-offs; one deliverable, length-bounded.
**Deliverable:** the professional artifact this capability produces (memo, table, plan, analysis, or model — as applicable).
**Evaluation criteria:** correct application of the framework; decisions justified with evidence; limitations honestly stated; artifact usable by a colleague without further explanation.

## Exercise 2 — Optimize event paths via passive listeners
**Scenario:** provide a realistic Latency and performance scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** optimize event paths via passive listeners, delegation, capture arbitration, cleanup hygiene, and touch-action declarations, handle gestures (pointer capture, click-drag disambiguation, multi-touch arbitration, hover emulation, prediction APIs) and inclusive keyboard-focus-reduced-motion input.
**Constraints:** must use the framework taught in the corresponding unit; must state assumptions and trade-offs; one deliverable, length-bounded.
**Deliverable:** the professional artifact this capability produces (memo, table, plan, analysis, or model — as applicable).
**Evaluation criteria:** correct application of the framework; decisions justified with evidence; limitations honestly stated; artifact usable by a colleague without further explanation.

## Exercise 3 — Integrate within frameworks (synthetic-event overhead
**Scenario:** provide a realistic Latency and performance scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** integrate within frameworks (synthetic-event overhead, store propagation control, imperative escapes, batch coordination), architect input pipelines (stage separation, centralized controllers, priority-interruption models with abort-restart, state serialization, multi-input coordination).
**Constraints:** must use the framework taught in the corresponding unit; must state assumptions and trade-offs; one deliverable, length-bounded.
**Deliverable:** the professional artifact this capability produces (memo, table, plan, analysis, or model — as applicable).
**Evaluation criteria:** correct application of the framework; decisions justified with evidence; limitations honestly stated; artifact usable by a colleague without further explanation.

## Exercise 4 — Verify through Event-Timing instrumentation
**Scenario:** provide a realistic Latency and performance scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** verify through Event-Timing instrumentation, CI interaction benchmarks, RUM distributions, and A-B timing experiments, and prevent flood-over-debounce-trailing-loss-thrashing-leak-monolith-race anti-patterns.
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

## B1. Engineer the input layer checklist
- [ ] Engineer the input layer against event-flood realities (pointer sample rates, scroll-resize cascades) with useful-update-rate analysis per interaction class, master throttle mechanics (leading-trailing edges, frame-aligned rAF throttles as visual-update defaults, failure modes) and debounce semantics (wait selection by context, maxWait starvation bounds, over-debounce cargo-cult avoidance), consolidate work through rAF batching with latest-value-wins, DOM read-write batching, microtask coalescing, and event-coalescing utilization?
- [ ] Decisions and their justification are documented for review by a colleague

## B2. Optimize event paths via checklist
- [ ] Optimize event paths via passive listeners, delegation, capture arbitration, cleanup hygiene, and touch-action declarations, handle gestures (pointer capture, click-drag disambiguation, multi-touch arbitration, hover emulation, prediction APIs) and inclusive keyboard-focus-reduced-motion input?
- [ ] Decisions and their justification are documented for review by a colleague

## B3. Integrate within frameworks (synthetic event checklist
- [ ] Integrate within frameworks (synthetic-event overhead, store propagation control, imperative escapes, batch coordination), architect input pipelines (stage separation, centralized controllers, priority-interruption models with abort-restart, state serialization, multi-input coordination)?
- [ ] Decisions and their justification are documented for review by a colleague

## B4. Verify through Event Timing instrumentation, checklist
- [ ] Verify through Event-Timing instrumentation, CI interaction benchmarks, RUM distributions, and A-B timing experiments, and prevent flood-over-debounce-trailing-loss-thrashing-leak-monolith-race anti-patterns?
- [ ] Decisions and their justification are documented for review by a colleague

## B5. Delivery quality checklist
- [ ] Every claim sourced, graded, or flagged as contested?
- [ ] All terminology explained on first use?
- [ ] Trade-offs stated wherever recommendations are context-dependent?
- [ ] Material reads as practitioner-written, not generic?
