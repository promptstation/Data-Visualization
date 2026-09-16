---
name: section-14-advanced-svg-component-architecture-design-systems
description: Develop comprehensive, professional-level learning modules and training materials on component Architecture and Design Systems for Visualization within Advanced SVG & DOM Manipulation — D3.js and Modern Frameworks — architect chart components through container-presentational splits, well-contracted props APIs, and composition patterns (scoped slots, compound components) with responsive measurement and breakpoint-adaptive rendering; build theming systems flowing design tokens into scales and palettes with CVD-verified dark-mode.... Use this skill whenever the user asks to create, teach, or deepen training on component, architecture, design, systems, visualization, D3 and SVG, or requests workshops, lessons, curricula, job aids, or expert instruction in this area — even when the word “module” is never used.
compatibility: Any environment that can write Markdown files; benefits from web research access for authoritative sources; no external tools or packages required.
metadata:
  author: Promptstation skill-building pipeline (Data Visualization course 05, section 14)
  version: 1.0.0
  category: professional-education
---

# Component Architecture and Design Systems for Visualization — Professional Training

## Mission

Produce professional-grade learning modules and training materials on **component Architecture and Design Systems for Visualization** within Absolute mastery of D3.js — the gold standard for custom web-based data visualization — including advanced SVG craft, the data-join mental model, layouts and transitions, and integration with React, Vue, and Svelte.

Subject scope: Covers the production-scale engineering: the chart-component architecture — the reusable-unit design: the container-presentational split for charts (the data-fetching-and-state container versus the pure-rendering presentational component — the testability and reuse benefits), the props-API design for visualizations (the data-dimensions-encoding-options interface contracts, the sensible-defaults with full-override philosophy, the configuration-object versus discrete-props trade-offs), and the composition-API patterns (the children-and-slots mark composition — the LayerCake-style scoped-slot provision of scales and data, the compound-component patterns — the Chart-Axis-Legend-Tooltip subcomponent families) as the component-design foundation; the responsive-and-adaptive component engineering — the size-independence: the container-measurement patterns (the ResizeObserver-driven dimension state, the aspect-ratio and min-max constraint systems), the breakpoint-adaptive rendering (the layout-switching by size — the legend-repositioning, label-thinning, and mark-simplification rules, the mobile-interaction adaptation from the touch-craft section), and the render-performance integration (the debounced-resize handling, the memoized-scale recomputation) as the adaptive-component craft; the theming-and-token architecture — the style system: the design-token integration (the color-spacing-typography tokens flowing into scales and SVG styles — the theme-object and CSS-custom-property dual mechanisms), the palette-system design (the categorical-sequential-diverging palette families as tokens with the CVD-and-contrast verification baked in, the dark-mode theming architecture), and the typography-and-density themes (the compact-comfortable-spacing modes, the font-scale systems for chart text) as the visual-consistency infrastructure; the state-and-data-layer patterns — the application integration: the data-normalization conventions (the tidy-data input contracts, the internal-transform pipelines — the d3-array processing encapsulated in component logic), the selection-and-filter state architecture (the controlled-versus-uncontrolled component patterns for interactive state, the cross-component state coordination — the linked-view state stores from the interaction section), and the loading-error-empty state design (the skeleton-and-placeholder patterns, the error-boundary integration, the no-data state craft) as the data-layer engineering; the documentation-and-example systems — the knowledge layer: the component-documentation standards (the live-example playgrounds — the Storybook integration for visualization components with the data-variant stories, the props-API documentation with visual examples per option), the usage-pattern guides (the chart-selection guidance — the data-relationship-to-chart-type decision support embedded in docs, the do-and-don't examples with perceptual rationale), and the contribution-documentation (the new-chart-type addition patterns — the extension-point documentation) as the knowledge infrastructure; the testing-strategy for chart systems — the quality architecture: the unit-testing layers (the pure-computation tests — the scales, layouts, and data transforms as isolated functions, the component-render tests — the structure-and-attribute assertions via testing libraries), the visual-regression testing (the screenshot-diff pipelines across data states and themes — the tolerance-calibration for antialiasing variance, the cross-browser capture matrices), the interaction-testing (the simulated-gesture sequences for zoom-brush-hover behaviors), and the accessibility-testing integration (the automated-a11y scans plus the screen-reader smoke tests from section 13) as the multi-layer QA; the versioning-and-migration discipline — the lifecycle management: the chart-component API versioning (the semantic-versioning application to visual APIs — the breaking-change taxonomy: prop removals, default changes, visual-output changes as potentially-breaking), the codemod-and-migration-guide practices for major versions, the visual-diff-based changelog documentation (the before-after galleries for visual changes), and the deprecation-window management (the legacy-component support periods) as the library-lifecycle craft; the performance-governance at system scale — the portfolio layer: the bundle-size budgets for visualization packages (the modular-import enforcement, the tree-shaking verification, the heavy-module code-splitting — the d3-geo and force dynamic-loading patterns), the render-performance budgets in CI (the frame-time and mount-duration thresholds from section 12), and the usage-telemetry integration (the performance-and-usage monitoring of deployed chart components informing optimization priorities) as the system-performance governance; the design-system integration — the organizational layer: the visualization-in-design-system positioning (the chart components as first-class design-system citizens alongside buttons and forms — the Figma-code parity systems for charts, the design-token synchronization), the cross-team adoption patterns (the golden-path chart templates reducing bespoke-chart proliferation, the contribution-model for team-specific extensions), and the governance structures (the chart-review processes applying the perceptual and accessibility standards — the design-review integration from the craft disciplines) as the institutional practice; the multi-framework and headless strategies — the distribution layer: the headless-visualization architecture (the framework-agnostic computation cores — the scales, layouts, and state logic as pure packages with thin React-Vue-Svelte wrappers from the framework sections), the web-component options (the custom-element chart packaging for framework-mixed estates with the SVG-in-shadow-DOM considerations), and the distribution-channel decisions (the npm-package versus CDN versus internal-registry patterns) as the ecosystem strategy; the case-study synthesis — the system exemplars: the documented open-source chart-system architectures (the visx primitive-composition philosophy, the Observable-Plot grammar approach, the enterprise design-system chart suites) analyzed for API design, theming, testing, and documentation patterns as the reference library; and the component-system deliverable — the documented, tested, themed, versioned, governed visualization component architecture.

Write as an experienced practitioner, not as a summarizer of popular content. Every framework taught must be something a real team or professional could run: procedures they can execute, criteria they can judge with, and artifacts they can hand to a colleague. Do not present claims as settled when the field treats them as contested — the training must model evidence discipline.

The module deepens this section's capabilities for a learner progressing from competent beginner toward expert practitioner, and connects them to the surrounding discipline rather than teaching them in isolation.

## Use Cases

### Full learning module
When asked for a comprehensive module on this topic:
1. Scope audience, prerequisites, duration, and discipline mix.
2. Build the evidence base from the authoritative sources below.
3. Write the full progressive module from the template.
4. Include all exercises with model solutions and all gate checklists.
5. Validate against the gate below before delivery.

### Condensed workshop
When asked for a one-day or half-day workshop:
1. Prioritize the units that match where the group is stuck.
2. Compress content to frameworks plus one worked example each; run exercises live with the participants' own material.
3. Leave behind the relevant checklists as job aids.

### Working job aids
When a practitioner needs tools rather than teaching:
1. Deliver the applicable checklists and templates from `references/exercise-and-checklist-library.md`, customized to their situation.
2. Add a one-page rationale per aid so the user understands what each item protects against.

## Core Output Requirements

- Deliverables are Markdown documents: the module, exercise sets with model solutions, and checklists. No placeholders, no "TODO" sections.
- Ground content in authoritative sources:
- Bostock's D3 documentation and Observable notebooks — the data-join, selection, scale, shape, layout, and transition canon from the library's author
- The SVG 1.1 and SVG 2 specifications with MDN SVG reference for paths, transforms, filters, masks, and clipping
- Murray's Interactive Data Visualization for the Web (D3 book lineage) and Nago's D3-tip-style community pattern literature for the pedagogical tradition
- Observable Plot documentation as the higher-level grammar-of-graphics sibling in the D3 ecosystem
- React, Vue, and Svelte official documentation on refs, lifecycle, reactivity, and third-party-DOM-library integration patterns
- The W3C WAI SVG accessibility guidance and ARIA authoring practices for accessible graphics
- Perceptual-edge and Few-lineage chart-design doctrine plus the documented SVG performance-ceiling studies informing the canvas-hybrid decision
- Maintain an evidence ledger while writing: every factual claim or number is either sourced, flagged as disputed/popular account, or omitted. Never invent statistics, studies, or citations.
- Distinguish established research findings from professional conventions and informed recommendations, and say which is which.
- Explain each specialized term in clear language on first use.

## Module Development Workflow

### Phase 1 — Scope and audience
Determine delivery mode (full module / workshop / job aids), learner background, duration, and whether learners bring their own material to work on. Record these choices; they drive depth allocation in Phase 3.

### Phase 2 — Evidence base
Collect the strongest documented examples, findings, and case material for this topic from the authoritative sources. Note what is well established, what is contested, and what is merely conventional. Verify any numbers before publishing them.

### Phase 3 — Architecture
Sequence the material progressively and establish core conceptual distinctions before the concepts are used together. Suggested unit sequence:

1. Unit 1

### Phase 4 — Write the units
For each unit follow the internal structure: teach the framework → show a worked example (weak / improved / professional versions where useful) → connect back to the surrounding discipline → state trade-offs explicitly. Use `references/domain-content-map.md` as the unit-by-unit source of scope, bullets, and evidence guidance.

### Phase 5 — Exercises and assessment
Select and adapt exercises from `references/exercise-and-checklist-library.md`. Adapt scenarios to the audience's domain. For a full module, include expert-quality model solutions; for workshops, convert selected exercises into facilitated live activities.

### Phase 6 — Checklists and job aids
Include the gate checklists from the library, customized to the audience's context without diluting the decision each item forces.

### Phase 7 — Validation gate
Run the Validation Gate below against the finished material before delivery. Fix failures; do not ship and caveat.

## Module Template

ALWAYS use this exact template for full modules:

```markdown
# Component Architecture and Design Systems for Visualization [— audience/context subtitle]

## Who This Module Is For
## Prerequisites
## Learning Outcomes
## Unit 1 — Unit 1
## Integrated Capstone
## Practical Exercises
## Professional Checklists
## Sources and Evidence Notes
```

Each unit internally follows: framework → worked example(s) → disciplinary connection → trade-offs.

## Writing Standards

Throughout the material, prioritize language that is:

* Precise without becoming jargon-heavy
* Practical without discarding rigor
* Honest about limitations and contested findings without being defeatist
* Concrete — anchored in real cases, real artifacts, and verifiable numbers
* Progressive from fundamentals to expert judgment

Where a recommendation depends on context, explain the trade-off rather than presenting an absolute rule.

## Validation Gate

Before delivery, verify:

### Content
- all units present with correct depth for the scoped audience
- core distinctions established before they are used together
- every taught capability has a usable framework, not just an explanation

### Evidence
- every claim and number is sourced or explicitly flagged as disputed
- no invented statistics, studies, dates, or citations anywhere
- sources are authoritative; no SEO-farm or marketing claims presented as fact

### Capability
- each absorbed capability (4 in this section) is covered by teaching content AND at least one exercise with evaluation criteria
- exercises have model solutions in full-module mode

### Artifacts
- all gate checklists included and actionable as written
- template structure followed; no placeholder sections

### Quality
- trade-offs stated wherever recommendations are context-dependent
- terminology explained on first use
- reads as practitioner-written, not generic AI advice

## Anti-Patterns

Avoid: Fighting the data join — imperative append-and-update code ignoring enter-update-exit semantics, producing duplicated, orphaned, or stale elements as data changes; Framework double-ownership — letting both React/Vue/Svelte and D3 mutate the same DOM subtree, producing render conflicts, leaked listeners, and irreproducible state bugs; SVG scale blindness — pushing tens of thousands of nodes into the DOM where style recalculation and layout costs collapse frame rates, ignoring the documented element-count ceiling; Transition choreography chaos — animating everything with uncoordinated durations so comparisons become impossible and motion carries no object-continuity information; Inaccessible-by-default graphics — SVG shipped without titles, descriptions, focusable alternatives, or data-table fallbacks, excluding screen-reader and keyboard users entirely; exercises without evaluation criteria; modules that stop at inspiration without a single decision the learner can now make better; and any content that overstates certainty beyond what the evidence supports.

## Decision Heuristic

When allocating depth under time or length limits, ask:

1. Where will this audience actually stall in practice?
2. Which unit protects the most value if taught well?
3. Can the learner run the framework tomorrow without me?
4. Is every example doing work a plain sentence could not?
5. What would a skeptical domain expert say about this material?

If two topics compete for space, keep the one that changes a decision.

## Final Principle

The goal is not more content about D3 and SVG. The goal is that a practitioner could take this material and perform: Architect chart components through container-presentational splits, well-contracted props APIs, and composition patterns (scoped slots, compound components) with responsive measurement and breakpoint-adaptive rendering, integrate charts as design-system citizens with golden-path templates and review governance, and distribute through headless cores with framework wrappers or web components informed by open-source system case studies — with the same evidence discipline the field's best practitioners use. The module must function simultaneously as a learning resource, a practical reference, and a working methodology.

## Bundled References

Read `references/domain-content-map.md` during Phases 3–4 for the unit-by-unit content map: scope statements, teaching bullets, evidence anchors, and trade-off prompts.

Read `references/exercise-and-checklist-library.md` during Phases 5–6 for the ready-to-adapt exercises and the professional gate checklists.
