---
name: section-09-spatial-3d-three-js-foundations
description: Develop comprehensive, professional-level learning modules and training materials on three.js Foundations — Scene Graphs, Cameras, Lights, and Materials within Spatial & 3D Visualization — GIS, Mapbox, Leaflet, Three.js — operate the Three.js scene-graph architecture (Scene-Camera-Renderer triad, Object3D hierarchies, render loops) with perspective-orthographic camera selection discipline for data accuracy; build geometries (primitives, BufferGeometry attributes, extrude-lathe-tube data shapes, InstancedMesh batching) and materials.... Use this skill whenever the user asks to create, teach, or deepen training on three, foundations, scene, graphs, cameras, lights, materials, Spatial and 3D, or requests workshops, lessons, curricula, job aids, or expert instruction in this area — even when the word “module” is never used.
compatibility: Any environment that can write Markdown files; benefits from web research access for authoritative sources; no external tools or packages required.
metadata:
  author: Promptstation skill-building pipeline (Data Visualization course 06, section 9)
  version: 1.0.0
  category: professional-education
---

# Three.js Foundations: Scene Graphs, Cameras, Lights, and Materials — Professional Training

## Mission

Produce professional-grade learning modules and training materials on **three.js Foundations: Scene Graphs, Cameras, Lights, and Materials** within Geospatial and three-dimensional visualization engineering — GIS fundamentals, web-mapping stacks (Leaflet, Mapbox/MapLibre), and Three.js mastered for representing geographic data and complex multidimensional structures.

Subject scope: Covers the 3D-rendering engine: the Three.js architecture — the scene-graph model: the core-object triad (the Scene container, the Camera viewpoint, the Renderer output — the render-loop composition), the Object3D hierarchy (the parent-child transform inheritance — the position-rotation-scale local-versus-world coordinates, the group-composition patterns, the traverse-and-search utilities), and the render-loop mechanics (the requestAnimationFrame-driven animation loop, the clock-and-delta timing, the renderer-scene-camera draw call) as the framework anatomy; the camera system — the viewpoint control: the PerspectiveCamera mechanics (the fov-aspect-near-far frustum parameters — the near-far-clipping and z-fighting precision relationship, the perspective-distortion characteristics — the focal-length-equivalent fov choices), the OrthographicCamera alternative (the parallel-projection rendering — the no-depth-distortion property for accurate-comparison 3D-data display, the frustum-box configuration), the camera-manipulation patterns (the position-lookAt targeting, the quaternion-and-euler rotation mechanics, the camera-path animation for narrative tours) and the projection-selection discipline (the perspective for spatial-immersion contexts, the orthographic for data-comparison accuracy — the honest-3D projection choice from the pitfalls) as the viewpoint system; the geometry system — the shape foundation: the primitive-geometry library (the Box-Sphere-Cylinder-Cone-Plane-Torus families with the segment-resolution parameters), the BufferGeometry architecture (the position-normal-uv-color attribute buffers — the typed-array geometry definition from the graphics-APIs discipline, the indexed-geometry efficiency), the geometry-from-data patterns (the ExtrudeGeometry from 2D shapes — the polygon-to-prism extrusion for geographic footprints, the LatheGeometry for revolution surfaces, the TubeGeometry along curves), and the geometry-processing utilities (the merge-and-instance patterns — the InstancedMesh for repeated geometry at scale, the BufferGeometryUtils operations) as the shape toolkit; the material-and-shading system — the appearance layer: the material family hierarchy (the MeshBasicMaterial unlit rendering, the MeshLambert-Phong-Standard-Physical progressive lighting models — the PBR metalness-roughness workflow of MeshStandardMaterial, the transparency-and-opacity handling with the render-order and depth-write discipline), the texture-mapping system (the TextureLoader-and-image textures, the uv-coordinate mapping, the color-maps-normal-maps-roughness-maps PBR channels, the data-driven-texture patterns — the canvas-generated textures for dynamic color mapping), the vertex-color and attribute-driven materials (the per-vertex data encoding — the color-buffer visualization patterns, the ShaderMaterial-customGLSL escape hatch integrating the shader skills) and the material-performance considerations (the shader-compilation costs, the material-sharing discipline) as the appearance system; the lighting system — the illumination model: the light-type vocabulary (the AmbientLight base illumination, the DirectionalLight sun-like parallel light with shadow-casting configuration, the PointLight-SpotLight positional sources, the HemisphereLight sky-ground gradient), the lighting-design patterns (the three-point-lighting convention adapted for data display, the lighting-for-form-perception principle — the surface-shape legibility through shading gradients, the flat-lighting for color-accuracy-critical encoding), and the shadow-system mechanics (the shadow-map rendering — the shadowMap-enable and per-light-castShadow configuration, the shadow-quality-and-performance trade-offs, the shadow-acne-and-bias fixes) with the data-visualization lighting discipline (lighting serving depth-and-form perception without distorting color-encoded meaning — the luminance-conflict avoidance) as the illumination craft; the 3D-data-encoding foundations — the visualization bridge: the position-as-data mapping (the x-y-z scale mappings from data dimensions — the 3D-scatter construction, the axis-and-gridline reference systems for 3D-coordinate legibility), the size-color-opacity encodings in 3D (the sphere-radius magnitude mapping with the volume-perception caution — the square-root-and-cube-root scaling debates, the color-mapping through vertex-colors or instanced attributes), the text-and-label rendering in 3D (the sprite-based billboards — the always-facing-camera labels, the CSS2D-CSS3DRenderer HTML-overlay labels, the SDF-text 3D integration) and the reference-frame furniture (the bounding-box, axis-triad, and ground-plane context elements preventing spatial disorientation) as the encoding foundation; the scene-composition patterns — the assembly craft: the layer-and-group organization (the semantic-scene-graph structure — the data-group, furniture-group, annotation-group separation enabling visibility toggling and selective updates), the visibility-and-LOD management (the layer-visibility controls, the frustum-culling defaults, the LOD-object patterns), the scene-state management (the data-update patterns — the geometry-and-attribute mutation versus rebuild decisions, the disposal discipline — the geometry-material-texture memory cleanup preventing leaks) and the multi-scene coordination (the linked-view patterns — the synchronized cameras across panels, the 2D-3D hybrid layouts) as the composition system; the post-processing-and-effects layer — the render pipeline extensions: the EffectComposer architecture (the render-pass chaining — the bloom, SSAO ambient-occlusion, depth-of-field, and outline passes), the data-visualization-relevant effects (the outline-and-highlight passes for selection feedback, the SSAO depth-cue enhancement for form perception, the antialiasing strategies — the MSAA-FXAA-SMAA options), and the effect-budget discipline (the frame-cost accounting per pass — the clarity-serving selection over cinematic accumulation) as the effects layer; the Three.js-ecosystem orientation — the tooling landscape: the loader ecosystem (the GLTF-GLB model loading — the standard 3D-asset format, the OBJ-FBX legacy formats, the Draco-mesh-compression), the control libraries (the OrbitControls-TransformControls-MapControls interaction helpers), the framework-integrations (the react-three-fiber declarative scene graph — the R3F component model with the drei helper library, the Vue-Svelte wrappers), the physics-and-animation adjuncts (the cannon-rapier physics at awareness, the GSAP-animation integration), and the ecosystem-alternatives context (the Babylon.js comparison at awareness, the model-viewer web-component for simple display) as the ecosystem map; the 3D-performance-foundations — the budget layer: the draw-call economics (the per-object render overhead — the InstancedMesh-and-merged-geometry batching discipline, the material-and-texture-count budgets), the geometry-budget management (the triangle-count realities per device tier, the segment-resolution right-sizing, the LOD-and-simplification strategies), the memory-and-texture discipline (the GPU-memory budgets, the texture-size-and-compression — the KTX2-basis options) and the profiling practice (the renderer-info stats — the draw-calls-triangles-textures counters, the stats.js FPS monitor, the browser-GPU-profiler integration) as the performance foundation for section 13's depth; the debugging-3D-scenes practice — the troubleshooting craft: the common-failure diagnostics (the invisible-object causes — the camera-frustum, material-side, lighting, and scale errors; the z-fighting causes — the near-far-range and coplanar-surface issues; the performance-collapse causes — the draw-call and shader explosions), the scene-inspection tooling (the Three.js-devtools and scene-graph debuggers, the wireframe-and-bounds visualization helpers), and the incremental-scene-building discipline (the one-element-at-a-time verification practice) as the debug toolkit; and the Three.js deliverable — the scene-graph, camera, geometry, material, lighting, and composition foundation for 3D data visualization.

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
- The EPSG registry, PROJ documentation, and geodesy references for coordinate-reference-system and projection foundations
- The GeoJSON (RFC 7946), TopoJSON, and Mapbox Vector Tile specifications with the OGC standards family context
- Leaflet and MapLibre GL JS / Mapbox GL JS official documentation, tutorials, and style-specification references
- Three.js documentation and manual with the WebGL-scene-graph lineage materials
- The cartographic-design canon at practitioner depth (the thematic-mapping, choropleth-classification, and map-color traditions from the Robinson-Brewer lineage including ColorBrewer)
- Tufte's graphical-integrity doctrine and the documented 3D-chart distortion research for the spatial-honesty discipline
- The OpenStreetMap ecosystem documentation (tile servers, data model, attribution requirements) and deck.gl geospatial-layer materials
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
# Three.js Foundations: Scene Graphs, Cameras, Lights, and Materials [— audience/context subtitle]

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

Avoid: Projection illiteracy — mixing coordinate systems silently (WGS84 lat-lon treated as Web-Mercator pixels), producing offset, stretched, or area-distorted maps without any error message; Choropleth classification carelessness — quantile versus equal-interval versus manual breakpoints chosen without distribution analysis, or raw-count shading on unequal areas producing population-density lies; 3D-for-its-own-sake — extruding and perspectivizing data that reads more accurately in 2D, where occlusion, perspective foreshortening, and depth ambiguity destroy value comparison; Tile-and-attribution compliance blindness — violating provider terms, omitting required attribution, or hammering tile servers without caching, risking both legal and infrastructure failure; Scale-and-generalization mismatch — rendering city-level geometry at country zoom (unreadable dense sludge) or vice versa (missing context), ignoring level-of-detail cartographic convention; exercises without evaluation criteria; modules that stop at inspiration without a single decision the learner can now make better; and any content that overstates certainty beyond what the evidence supports.

## Decision Heuristic

When allocating depth under time or length limits, ask:

1. Where will this audience actually stall in practice?
2. Which unit protects the most value if taught well?
3. Can the learner run the framework tomorrow without me?
4. Is every example doing work a plain sentence could not?
5. What would a skeptical domain expert say about this material?

If two topics compete for space, keep the one that changes a decision.

## Final Principle

The goal is not more content about Spatial and 3D. The goal is that a practitioner could take this material and perform: Operate the Three.js scene-graph architecture (Scene-Camera-Renderer triad, Object3D hierarchies, render loops) with perspective-orthographic camera selection discipline for data accuracy, build geometries (primitives, BufferGeometry attributes, extrude-lathe-tube data shapes, InstancedMesh batching) and materials (PBR hierarchy, texture channels, vertex-color encoding, ShaderMaterial escape hatches) under lighting design serving form perception without color-encoding distortion, encode data in 3D position-size-color channels with volume-perception scaling caution and billboard-label systems plus reference-frame furniture, compose scenes through semantic groups, visibility-LOD management, disposal discipline, and post-processing under effect budgets, navigate the ecosystem (GLTF loaders, OrbitControls, react-three-fiber) with draw-call-geometry-memory budget profiling and systematic invisible-object z-fighting and performance debugging — with the same evidence discipline the field's best practitioners use. The module must function simultaneously as a learning resource, a practical reference, and a working methodology.

## Bundled References

Read `references/domain-content-map.md` during Phases 3–4 for the unit-by-unit content map: scope statements, teaching bullets, evidence anchors, and trade-off prompts.

Read `references/exercise-and-checklist-library.md` during Phases 5–6 for the ready-to-adapt exercises and the professional gate checklists.
