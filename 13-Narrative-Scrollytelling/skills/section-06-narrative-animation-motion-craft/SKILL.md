---
name: section-06-narrative-animation-motion-craft
description: Develop comprehensive, professional-level learning modules and training materials on animation and Motion Craft — Transitions That Teach within Narrative Scrollytelling for Data Stories — craft purposeful animation through the functional taxonomy (continuity, attention, spatial, state-change, and pacing functions with cost awareness, motion-or-not decision criteria, and every-motion-serves-story audits), master timing and easing (duration scaling with consistency tokens and scroll adaptation, easing.... Use this skill whenever the user asks to create, teach, or deepen training on animation, motion, craft, transitions, teach, Narrative scrollytelling, or requests workshops, lessons, curricula, job aids, or expert instruction in this area — even when the word “module” is never used.
compatibility: Any environment that can write Markdown files; benefits from web research access for authoritative sources; no external tools or packages required.
metadata:
  author: Promptstation skill-building pipeline (Data Visualization course 13, section 6)
  version: 1.0.0
  category: professional-education
---

# Animation and Motion Craft: Transitions That Teach — Professional Training

## Mission

Produce professional-grade learning modules and training materials on **animation and Motion Craft: Transitions That Teach** within The storytelling frontier of the data visualization specialist discipline — scroll-driven narrative graphics mastered end to end: story structure, text-graphics choreography, scroll-trigger implementation, animation craft, and the editorial discipline that turns data into experiences readers finish and remember.

Subject scope: Covers the motion design discipline where animation serves comprehension rather than decoration: the purpose framework for animation — motion with justification: the functional taxonomy of motion (the continuity function, where animation preserves object permanence so readers can track elements across visual states, drawing on cognitive continuity principles; the attention function, where motion guides eyes toward changes using the preattentive motion properties from the perception traditions; the spatial function, where animated camera moves and morphs reveal structural connections from the transition vocabulary of section 2; the state-change function, where animations signal what transformed between steps, supporting the visual-diff clarity of section 4; and the pacing function, where motion tempo contributes to story rhythm from the beat craft of section 3); the cost awareness for animation (the cognitive load that unnecessary motion consumes from attention resources, the duration cost each animation adds to total story time requiring budget discipline, the re-read friction when animations replay on scrollback and slow review, and the accessibility costs for vestibular and attention conditions requiring reduced-motion alternatives); the decision framework for whether to animate (animate when continuity matters and shared elements need tracking support; animate when change is subtle and needs motion emphasis; skip motion when states differ completely and discrete swaps serve better; skip motion when speed matters in data-dense rapid progressions); and the discipline that every motion serves the story (the decorative-motion audit justifying each animation against the functional taxonomy, learned from the parallax backlash history of section 2, and the motion-reduction experiment of testing stories with animations removed to reveal what motion actually contributes) as the purpose foundation; the timing and easing craft — the parameters of motion: the principles of duration selection (durations scale with transition distance and complexity, following interface-animation heuristics; the working range of 200 to 500 milliseconds balances perceptibility against pacing for scroll-triggered chart transitions; consistency systems standardize timing tokens across a story in the design-system tradition; and adaptation to scroll speed manages the conflict between fast scrollers and slow transitions using the interrupt handling of section 5); the vocabulary of easing functions (ease-out curves dominate entrances because decelerating arrivals feel natural under physical-motion intuition; ease-in-out curves suit repositioning where movement is symmetric; linear mapping is required for scrubbed motion where scroll position drives animation progress directly, as in the scrubbing patterns of section 5; and spring physics with overshoot carry playful tones that risk undermining serious data content, a voice-consistency consideration); the patterns of choreography (stagger and cascade techniques animate sequential elements with offsets to create flow, following interface-choreography traditions; simultaneous transitions suit related changes while sequenced transitions suit ordered narrative steps; exits run fast while entrances stay deliberate, keeping attention on new content; and group orchestration coordinates multi-element changes within a single step state, extending the layer sequencing of section 4); the alignment of timing to narrative (motion peaks coincide with key sentences, following the reading rhythm of section 4; settled states hold long enough for comprehension before the next step arrives; and tempo varies across the story, moving faster in montage sequences and slower in revelation moments, following the pacing craft of section 3); and the debugging of timing (too-fast diagnosis from missed transition perception, remedied by duration increases; too-slow diagnosis from waiting friction and scroll-ahead behavior; and readthrough timing verification measuring observed pacing against reading speed, from the testing traditions of section 14) as the timing layer; the chart animation techniques — data-specific motion: the mastery of D3 transitions (the transition API with selection, chaining, duration, easing, and end callbacks, from the DOM manipulation traditions; the enter-update-exit conventions where new elements fade or grow in and removed elements exit gracefully; the key-function discipline in data joins that preserves element identity so the same data points can be tracked across states; and the named-transition and cancellation semantics that manage interruption when readers scroll mid-animation, connecting to the interrupt handling of section 5); the techniques of element morphing (shape tweening between rectangles and paths requires matching point counts, drawing on the curve mathematics traditions; cross-chart-type morphs such as bar to line or scatter to area use shared-element strategies; custom interpolators and attribute tweens handle non-standard properties; and morph legibility requires that intermediate states remain interpretable rather than becoming visual soup); the transitions of axes and scales (axis rescaling animates domain changes with tick morphing from the charting traditions; narrative camera moves coordinate scale domains and translations for spatial stories; and honesty captions clarify that animated axes do not imply data changes); the animations of data updates (value tweens animate numbers and positions to new states for filtered and revealed datasets; ranked-position swap animations with identity tracking appear in race-chart dynamics from the popular data-video traditions at awareness; and enter-heavy revelations accumulate points and bars across steps for growing-dataset stories); and the integration of animation libraries (GSAP timelines orchestrate complex sequenced motion, previewing the ecosystem of section 13; interoperability patterns let GSAP drive SVG and D3 elements in hybrid architectures; and CSS animations complement JavaScript by offloading simple declarative transitions to the compositor for performance) as the chart motion layer; the scroll-linked motion systems — the scrubbing craft: the architecture of scrub animation (the mapping from scroll fraction to animation progress grounds the technique introduced in section 5; pin-and-scrub combinations hold sticky elements while scroll drives their internal animation for cinematic sequences; and granularity decisions choose between smooth continuous scrubbing and stepped scrubbing by content type); parallax with purpose (depth-cue parallax uses differential motion to create spatial layering for geographic and 3D contexts; emphasis parallax moves hero elements differently to hold attention, respecting the boundary against mere decoration established by the backlash history of section 2; and restraint conventions prefer subtle speed differentials over extreme separation effects); the techniques of progressive reveal (draw-on-scroll renders line charts and paths as readers scroll, using stroke-dashoffset traditions; accumulation scrubbing reveals data points and bars progressively with scroll position; and annotation scrub timing makes labels and callouts emerge at precise scroll moments); the performance engineering of scrubbing (transform-only discipline keeps scroll-linked motion compositor-friendly under continuous load, from the performance integration of section 5; throttle and interpolation techniques damp scroll jitter for smoothness; and mobile scrub testing verifies scroll-linked motion on lower-powered devices, from the mobile traditions); and the accessibility of scrubbing (reduced-motion alternatives replace scroll-linked sequences with static or discrete-step versions, and keyboard navigation equivalents make scrubbed content reachable through step navigation, previewing section 11) as the scrubbing layer; the accessibility and restraint of motion — the inclusive discipline: the systems of vestibular safety (complete support for the prefers-reduced-motion preference across all animation systems, integrating media-query and JavaScript detection from the inclusive discipline of section 6's own foundations; hazard awareness for large motions such as full-screen zoom, parallax, and camera moves that can trigger discomfort, requiring restraint and controls; and user motion controls providing pause, stop, and toggle provisions for extended sequences, following the reader-agency principles of section 8); the engineering of photosensitive safety (flash and flicker audits check rapid brightness and state changes against the three-flash thresholds from accessibility criteria; data-animation flicker risks include rapid value changes and blinking highlights, which fast scrolling can multiply; and safe transition conventions prefer cross-fades and smooth tweens over strobes and hard cuts); the cognitive accessibility of motion (distraction management keeps animations supporting rather than competing with text reading; pacing accessibility gives readers controlled speed without auto-advance pressure, following the autonomy systems of section 8; comprehension support provides replay and step-through affordances for processing animated transitions; and a consistent motion language ensures the same transition types mean the same changes throughout the story); the quality of reduced-motion design (the fallback-not-punishment principle requires reduced-motion versions to remain complete and beautiful rather than broken or stripped, conveying identical narrative content through instant state changes and descriptive text; and instant-state clarity communicates what transformed through visual-diff design even without motion, from the differentiation craft of section 4); and the inclusion of motion in testing (reduced-motion readthrough protocols test the complete story with preferences emulated; motion-sensitivity user feedback gathers vestibular-condition reader input on animation comfort where testing partnerships allow; and fast-and-slow scroll behavior testing verifies story integrity across scroll speed ranges) as the inclusive layer; and the section anti-patterns — the failure library: animation worship, polishing motion spectacle while narrative clarity degrades, remedied by the purpose framework and reduction experiments; duration anarchy, where every transition uses different arbitrary timings, remedied by timing token systems; morph soup, shipping unreadable intermediate states in complex shape tweening, remedied by midpoint legibility discipline; scroll race chaos, where animations fight fast scrollers with pileup and contradiction, remedied by interrupt handling from section 5; parallax nostalgia, decorating with depth effects that serve no narrative function, remedied by purpose audits and restraint conventions; the reduced-motion afterthought, bolting on fallbacks late and producing broken stripped experiences, remedied by the fallback-not-punishment principle; library blender, mixing animation systems with conflicting control and producing jank, remedied by interoperability architecture patterns; and timing deafness, shipping transitions never verified against real reading speeds, remedied by readthrough timing verification, with detection methods as the diagnostic.

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
- The narrative-visualization research canon (the Segel-Heer taxonomy of data-story forms, the Hullman martini-glass structure research, the authored-versus-exploratory narrative literature from IEEE VIS and journalism studies)
- The data-journalism practice tradition (the NYT-Snow-Fall lineage, the Pudding essay craft, the Guardian-Propublica-Bloomberg graphics newsroom conventions and their published process write-ups)
- The scroll-implementation ecosystem (the Scrollama, GSAP-ScrollTrigger, Framer-Motion, and Intersection-Observer documentation traditions, the Svelte-and-React scrollytelling component patterns)
- The motion-and-animation craft literature (the animation-for-comprehension research, the easing-and-choreography traditions from the interface-animation canon)
- The web-performance and accessibility standards (the Core-Web-Vitals, prefers-reduced-motion, and scroll-interaction accessibility guidance from the W3C and MDN traditions)
- The editorial-process and ethics literature (the newsroom-collaboration workflows, the data-story ethics and verification traditions from the journalism canon)
- The audience-analytics literature (the scroll-depth engagement measurement and narrative-effectiveness research traditions)
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
# Animation and Motion Craft: Transitions That Teach [— audience/context subtitle]

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
- each absorbed capability (3 in this section) is covered by teaching content AND at least one exercise with evaluation criteria
- exercises have model solutions in full-module mode

### Artifacts
- all gate checklists included and actionable as written
- template structure followed; no placeholder sections

### Quality
- trade-offs stated wherever recommendations are context-dependent
- terminology explained on first use
- reads as practitioner-written, not generic AI advice

## Anti-Patterns

Avoid: Animation worship — choreographing spectacular transitions that dazzle on first scroll and obscure the data on every re-read, mistaking motion polish for narrative clarity; Scroll-jacking reader control — trapping users in forced-motion sequences with no way to skip, re-read, or escape, violating both accessibility standards and basic reader trust; Story without evidence structure — writing the dramatic arc first and bending data selections, scales, and annotations to fit the narrative instead of letting verified findings drive the plot; Desktop-only choreography — designing sticky-panel magic that collapses on mobile viewports, slow networks, and reduced-motion preferences, shipping the afterthought to most of the audience; The unfinishable epic — burying the payoff under twenty screens of setup so scroll-depth analytics show readers abandoning before the story's point ever arrives; exercises without evaluation criteria; modules that stop at inspiration without a single decision the learner can now make better; and any content that overstates certainty beyond what the evidence supports.

## Decision Heuristic

When allocating depth under time or length limits, ask:

1. Where will this audience actually stall in practice?
2. Which unit protects the most value if taught well?
3. Can the learner run the framework tomorrow without me?
4. Is every example doing work a plain sentence could not?
5. What would a skeptical domain expert say about this material?

If two topics compete for space, keep the one that changes a decision.

## Final Principle

The goal is not more content about Narrative scrollytelling. The goal is that a practitioner could take this material and perform: Craft purposeful animation through the functional taxonomy (continuity, attention, spatial, state-change, and pacing functions with cost awareness, motion-or-not decision criteria, and every-motion-serves-story audits), master timing and easing (duration scaling with consistency tokens and scroll adaptation, easing vocabulary from ease-out through linear scrub, choreography with stagger-cascade patterns and enter-exit asymmetry, narrative tempo alignment, and timing debugging), build scroll-linked systems (scrub architecture with pin combinations, purposeful parallax with restraint, progressive reveal techniques, scrub performance engineering, and scrub accessibility), enforce inclusive motion (vestibular safety with complete reduced-motion support and user controls, photosensitive flash avoidance accounting for scroll speed, cognitive distraction management, fallback-not-punishment quality, and reduced-motion testing protocols), and avoid animation worship, duration anarchy, morph soup, scroll race chaos, parallax nostalgia, reduced-motion afterthoughts, library blenders, and timing deafness failures — with the same evidence discipline the field's best practitioners use. The module must function simultaneously as a learning resource, a practical reference, and a working methodology.

## Bundled References

Read `references/domain-content-map.md` during Phases 3–4 for the unit-by-unit content map: scope statements, teaching bullets, evidence anchors, and trade-off prompts.

Read `references/exercise-and-checklist-library.md` during Phases 5–6 for the ready-to-adapt exercises and the professional gate checklists.
