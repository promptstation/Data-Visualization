---
name: section-11-narrative-accessibility-inclusive-scrollytelling
description: Develop comprehensive, professional-level learning modules and training materials on accessibility and Inclusive Scrollytelling — Stories for Every Reader within Narrative Scrollytelling for Data Stories — build inclusive scroll narratives through obligations grounding (WCAG POUR application with scroll-specific criteria focus, legal-ethical mandates with audience reach case, permanent-temporary-situational disability scope, and accessibility-as-quality insight), serve assistive technology (DOM order with landmarks.... Use this skill whenever the user asks to create, teach, or deepen training on accessibility, inclusive, scrollytelling, stories, every, reader, Narrative scrollytelling, or requests workshops, lessons, curricula, job aids, or expert instruction in this area — even when the word “module” is never used.
compatibility: Any environment that can write Markdown files; benefits from web research access for authoritative sources; no external tools or packages required.
metadata:
  author: Promptstation skill-building pipeline (Data Visualization course 13, section 11)
  version: 1.0.0
  category: professional-education
---

# Accessibility and Inclusive Scrollytelling: Stories for Every Reader — Professional Training

## Mission

Produce professional-grade learning modules and training materials on **accessibility and Inclusive Scrollytelling: Stories for Every Reader** within The storytelling frontier of the data visualization specialist discipline — scroll-driven narrative graphics mastered end to end: story structure, text-graphics choreography, scroll-trigger implementation, animation craft, and the editorial discipline that turns data into experiences readers finish and remember.

Subject scope: Covers the inclusion discipline ensuring scroll narratives work for all readers regardless of ability, device, or context: the accessibility obligations — the standards foundation: the application of WCAG to scrollytelling (the POUR principles map onto scroll narratives from the accessibility traditions, and specific criteria demand attention: timing-adjustable content under 2.2.1 so stories never pressure readers, three-flash seizure safety under 2.3.1 for animated data, content-on-hover-or-focus management under 1.4.13, keyboard operability under 2.1.1 for all story interactions, and target-size and spacing requirements for interactive story controls); the legal and ethical mandates (the ADA, European Accessibility Act, and public-sector obligations apply to news and brand stories from the legal landscape traditions; journalism ethics demand universal access because public information must reach all publics, previewing the editorial traditions of section 14; and the audience-reach business case notes that accessible stories reach larger audiences including aging readers and situational disabilities, from curb-cut benefit traditions); the scope of inclusive design (the disability spectrum spans permanent conditions such as vestibular disorders, temporary conditions such as motion sickness, and situational contexts such as reading while commuting; neurodiversity considerations cover attention, cognitive, and processing differences affecting scroll-narrative consumption; literacy and language range requires plain language and translation consideration for broad audiences; and technology diversity includes assistive technology and old device contexts under the robustness criteria); and the insight that accessibility is story quality (the principle that clarity benefits all readers means accessible stories are better structured and clearer for everyone, from universal-design traditions, and the constraint-drives-craft reading holds that accessibility requirements improve narrative design discipline) as the obligations foundation; the screen reader and assistive technology experience — the AT layer: DOM order and reading flow (the narrative sequence must exist in DOM order so linear AT traversal matches visual order, from the structure traditions of the accessibility course; sticky panels create DOM positioning challenges where the visual stage and text column relationship requires deliberate architecture; landmarks and heading structure make story sections navigable for AT wayfinding, from IA traditions; and skip-navigation provisions bypass repeated story chrome, from navigation standards); alternatives for graphic content (each visual state activated by scroll needs a text alternative describing that state, from the description traditions of the accessibility course; data table equivalents expose the underlying values for every story chart, from equivalence systems; annotation and emphasis must be conveyed in text alternatives rather than only visually, extending the systems of section 7; and transition description strategies communicate state changes through live regions or descriptive text, from dynamic-content traditions); the AT compatibility of scroll triggers (the state-change announcement architecture uses aria-live regions to communicate visual state changes as readers scroll, from live-region systems; announcement fatigue prevention throttles updates to significant changes only, avoiding noise floods during scrolling; and scroll observation requires AT testing that verifies story progression communicates coherently in screen reader browse and focus modes); the accessibility of interactive elements (story controls including toggles, filters, and navigation buttons must be fully keyboard accessible, extending the control systems of section 8; focus management in scroll contexts preserves focus visibility and position as layouts shift under sticky positioning; and exploration sections with sandboxes and calculators must operate through assistive technology, extending the freedom patterns of section 8); and the AT testing protocols (screen reader story walkthroughs test the complete experience in NVDA, JAWS, and VoiceOver, from cross-AT traditions; keyboard-only traversal verifies full story navigation without a pointer, applying the unplug-the-mouse discipline; and AT user testing partnerships gather disabled reader feedback on story experiences, from inclusive testing traditions) as the AT layer; the accessibility of motion and vestibular experience — movement inclusion: complete reduced-motion support (the prefers-reduced-motion preference must be honored across all animation systems, integrating CSS and JavaScript detection from the inclusive discipline of section 6; fallback completeness requires reduced-motion versions to convey identical narrative content through instant state changes and text description, per the fallback-not-punishment principle; and scrub and parallax alternatives disable or simplify scroll-linked motion under reduced preferences, extending the scrubbing accessibility of section 6); vestibular trigger management (the large-motion hazard inventory assesses full-screen zoom, parallax, and camera-move effects for discomfort risk; motion intensity restraint prefers subtle targeted motion over sweeping cinematic effects for sensitive audiences; and user motion controls provide pause, stop, and toggle provisions for extended animated sequences, from the reader-agency systems of section 8); photosensitive safety engineering (flash and flicker audits check rapid brightness and state-change sequences against three-flash thresholds from seizure-safety criteria; data animation flicker risks include rapid value changes and blinking highlights, and fast scrolling multiplies flash rates, requiring assessment in scroll-speed contexts; and safe transition conventions prefer cross-fades and smooth tweens over strobes and hard cuts); the cognitive load of motion (distraction management keeps animations supporting rather than competing with text comprehension, from cognitive traditions; pacing accessibility gives readers controlled speed without auto-advance pressure, from the pacing autonomy of section 8; and motion comprehension support provides replay and step-through affordances for processing animated transitions); and motion accessibility testing (reduced-motion mode verification tests the complete narrative experience with preferences emulated; motion-sensitivity user feedback gathers vestibular-condition reader input on animation comfort where available; and fast-and-slow scroll behavior testing verifies story integrity across scroll speed ranges) as the motion layer; visual and cognitive accessibility — perception inclusion: the systems of contrast and legibility (text over graphics requires scrim, backdrop, and shadow treatments meeting 4.5-to-1 contrast ratios across all step backgrounds, systematically verifying the legibility obligations of section 4; data graphics must meet graphical-object contrast thresholds for chart elements and annotations, from color accessibility traditions; zoom and text resize support requires 200 percent zoom and browser text scaling to maintain story function and layout, from resize criteria; and color independence ensures story comprehension never depends on color alone, from redundant-encoding traditions); typography and reading accessibility (readable measure and spacing set text column widths and line heights supporting comprehension, from typography traditions; dyslexia and processing considerations shape font choice and text presentation for diverse readers, from cognitive accessibility traditions; and plain language integration uses clear vocabulary and sentence structures supporting broad literacy range, from language accessibility systems); cognitive structure supports (progress and orientation visibility provides chapter position and story length indicators supporting navigation confidence, extending the navigation provisions of section 8; consistent pattern predictability keeps interaction and visual patterns stable throughout to reduce learning load, from predictability criteria; and content chunking with breathing room paces information to support processing limits, from the load-management pacing of section 3); multi-modal content provision (audio description considerations offer spoken narrative alternatives for visual stories at awareness, from media accessibility traditions; transcript and text versions provide the complete story as readable text articles, from equivalence traditions; and caption and summary provisions support varied consumption depths); and visual-cognitive testing (contrast and zoom verification runs systematically across all steps and story states, not just initial load; and low-vision and cognitive user testing gathers inclusive reader feedback on comprehension and navigation, from user-testing traditions) as the perception layer; accessible implementation practice — the engineering integration: accessibility in architecture (semantic HTML provides the foundation with native elements and landmarks before ARIA enhancement, from structure traditions; component accessibility inheritance means reusable story components carry baked-in accessibility, from the tooling traditions of section 13; and progressive enhancement as accessibility guarantees the complete story without JavaScript, extending the resilience systems of section 5 to serve AT and old technology contexts); accessibility testing integration (automated scanning in CI runs axe-core-class checks per story build, from automated testing traditions, with awareness that manual complement is required; step-state accessibility audits verify every visual state, covering all narrative moments rather than initial load alone; and AT and keyboard testing in QA places screen reader and keyboard protocols as release gates, from testing-triad traditions); accessibility documentation (the story accessibility statement publishes known limitations and supported AT contexts, from statement traditions; component accessibility documentation records interaction patterns and AT behaviors for team reuse; and the accessibility decision log records tradeoffs and accommodations, from governance traditions); remediation and feedback systems (accessibility issue reporting channels let readers report barriers, from feedback traditions; correction priority sequences fixes by barrier severity, from remediation traditions; and accessibility debt tracking inventories known gaps with remediation plans, from governance systems); and inclusive culture practices (accessibility in story kickoffs establishes inclusion requirements at planning rather than bolting them on at the end, from shift-left traditions; team accessibility literacy builds scroll-specific AT and criteria knowledge in story teams, from competency traditions; and disabled creator and reviewer inclusion brings lived-experience voices into story production, from nothing-about-us principles) as the practice layer; and the section anti-patterns — the failure library: the scroll trap experience, where keyboard and AT users cannot progress through or escape scroll-driven stories, remedied by keyboard traversal and escape provision standards; silent state changes, where visual transformations are invisible to screen readers, remedied by live-region announcement architecture; the motion sickness machine, parallax and zoom spectacle without reduced-motion fallbacks, remedied by preference detection and complete fallback obligations; contrast gambling, text over busy visuals failing legibility ratios, remedied by systematic contrast engineering and verification; accessibility as final sprint, bolting remediation onto completed stories at great cost, remedied by shift-left architecture integration; automation-only assurance, treating scanner passes as complete accessibility, remedied by AT testing and manual audit complements; fallback degradation, shipping reduced-motion versions as broken stripped experiences, remedied by the fallback-not-punishment design principle; and statement fiction, published accessibility claims contradicting reader experience, remedied by testing verification and feedback loop systems, with detection methods as the diagnostic.

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
# Accessibility and Inclusive Scrollytelling: Stories for Every Reader [— audience/context subtitle]

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
- each absorbed capability (2 in this section) is covered by teaching content AND at least one exercise with evaluation criteria
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

The goal is not more content about Narrative scrollytelling. The goal is that a practitioner could take this material and perform: Build inclusive scroll narratives through obligations grounding (WCAG POUR application with scroll-specific criteria focus, legal-ethical mandates with audience reach case, permanent-temporary-situational disability scope, and accessibility-as-quality insight), serve assistive technology (DOM order with landmarks and skip navigation, per-step graphic alternatives with data tables and annotation descriptions, scroll trigger live-region architecture with fatigue prevention, interactive element keyboard and focus management, and cross-AT walkthrough testing protocols), include motion sensitivity (complete reduced-motion support with narrative-complete fallbacks, vestibular trigger management with restraint conventions and user controls, photosensitive flash audits accounting for scroll speed multiplication, cognitive load pacing, and reduced-motion and speed-range testing), support visual and cognitive access (text-over-graphics contrast engineering with zoom support, color independence, typography and plain language, progress orientation and pattern predictability, multimodal transcript and audio provisions, and systematic per-step audits with user testing), integrate accessible practice (semantic HTML foundations with component inheritance and progressive enhancement, CI scanning plus per-state manual audits with AT gates, accessibility statements and decision logs, remediation feedback systems, and inclusive culture with shift-left planning and disabled voices), and avoid scroll traps, silent changes, motion sickness machines, contrast gambling, final sprints, automation-only assurance, fallback degradation, and statement fiction failures — with the same evidence discipline the field's best practitioners use. The module must function simultaneously as a learning resource, a practical reference, and a working methodology.

## Bundled References

Read `references/domain-content-map.md` during Phases 3–4 for the unit-by-unit content map: scope statements, teaching bullets, evidence anchors, and trade-off prompts.

Read `references/exercise-and-checklist-library.md` during Phases 5–6 for the ready-to-adapt exercises and the professional gate checklists.
