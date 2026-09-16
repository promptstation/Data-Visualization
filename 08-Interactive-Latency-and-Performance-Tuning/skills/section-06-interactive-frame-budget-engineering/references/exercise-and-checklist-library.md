# Exercise and Checklist Library — Frame Budget Engineering: The Main-Thread Discipline

Read this during Phase 5 (exercises) and Phase 6 (checklists). Adapt
scenarios to the audience's domain; keep evaluation criteria intact — they
are what make the exercises assessable. In full-module mode, write an
expert-quality model solution for each included exercise.

## Table of Contents
- Part A: Practical Exercises
- Part B: Professional Gate Checklists

---

# Part A: Practical Exercises

## Exercise 1 — Engineer frame budgets through arithmetic discipline (16.7-8.3ms totals with practical work budgets
**Scenario:** provide a realistic Latency and performance scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** engineer frame budgets through arithmetic discipline (16.7-8.3ms totals with practical work budgets, allocation by interaction class, overspend-jank mechanics, LoAF-rAF measurement), eliminate long tasks via chunking (process-N-yield loops with calibrated chunk sizes, generator-async implementations), yielding mechanisms (setTimeout-rAF re-entry, scheduler.yield-postTask priorities, MessageChannel tricks) and interruption-resumption state machines with consistency discipline.
**Constraints:** must use the framework taught in the corresponding unit; must state assumptions and trade-offs; one deliverable, length-bounded.
**Deliverable:** the professional artifact this capability produces (memo, table, plan, analysis, or model — as applicable).
**Evaluation criteria:** correct application of the framework; decisions justified with evidence; limitations honestly stated; artifact usable by a colleague without further explanation.

## Exercise 2 — Operate scheduling systems (browser priority realities
**Scenario:** provide a realistic Latency and performance scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** operate scheduling systems (browser priority realities, postTask classes, requestIdleCallback deadline-aware idle work, priority-inversion prevention), architect render scheduling (invalidate-on-demand, coalescing, viewport-priority progressive rendering, adaptive frame-skip, frame-pacing measurement), make offloading decisions through serialization-break-even economics, budget animation work with composited-property preference, centralized loop coordination, reduced-motion alignment, and scroll-timeline mechanics, schedule data computation via idle exploitation, stale-query cancellation, incremental memoized recomputation, progressive approximation, and visibility priority, enforce main-thread hygiene (sync-API avoidance, GC-churn management, containment properties, dependency audits, code splitting) under budget governance (registries, CI checks, runtime monitoring, exception processes), and prevent monolith-flood-starvation-spike-storm-thrashing-blindness anti-patterns.
**Constraints:** must use the framework taught in the corresponding unit; must state assumptions and trade-offs; one deliverable, length-bounded.
**Deliverable:** the professional artifact this capability produces (memo, table, plan, analysis, or model — as applicable).
**Evaluation criteria:** correct application of the framework; decisions justified with evidence; limitations honestly stated; artifact usable by a colleague without further explanation.

## Exercise 3 — Integrated capstone
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

## B1. Engineer frame budgets through checklist
- [ ] Engineer frame budgets through arithmetic discipline (16.7-8.3ms totals with practical work budgets, allocation by interaction class, overspend-jank mechanics, LoAF-rAF measurement), eliminate long tasks via chunking (process-N-yield loops with calibrated chunk sizes, generator-async implementations), yielding mechanisms (setTimeout-rAF re-entry, scheduler.yield-postTask priorities, MessageChannel tricks) and interruption-resumption state machines with consistency discipline?
- [ ] Decisions and their justification are documented for review by a colleague

## B2. Operate scheduling systems (browser checklist
- [ ] Operate scheduling systems (browser priority realities, postTask classes, requestIdleCallback deadline-aware idle work, priority-inversion prevention), architect render scheduling (invalidate-on-demand, coalescing, viewport-priority progressive rendering, adaptive frame-skip, frame-pacing measurement), make offloading decisions through serialization-break-even economics, budget animation work with composited-property preference, centralized loop coordination, reduced-motion alignment, and scroll-timeline mechanics, schedule data computation via idle exploitation, stale-query cancellation, incremental memoized recomputation, progressive approximation, and visibility priority, enforce main-thread hygiene (sync-API avoidance, GC-churn management, containment properties, dependency audits, code splitting) under budget governance (registries, CI checks, runtime monitoring, exception processes), and prevent monolith-flood-starvation-spike-storm-thrashing-blindness anti-patterns?
- [ ] Decisions and their justification are documented for review by a colleague

## B3. Delivery quality checklist
- [ ] Every claim sourced, graded, or flagged as contested?
- [ ] All terminology explained on first use?
- [ ] Trade-offs stated wherever recommendations are context-dependent?
- [ ] Material reads as practitioner-written, not generic?
