---
name: section-12-linear-algebra-computational-geometry-layout
description: Develop comprehensive, professional-level learning modules and training materials on computational Geometry for Layout — Hulls, Voronoi, Delaunay, and Triangulation within Linear Algebra & Geometry for Visualization — structure visualization space through computational geometry — compute convex hulls (definition and affine invariance, monotone-chain and Graham-scan orientation-test cores, group-boundary-outlier-framing applications, alpha-shape and 3D extensions); build Voronoi partitions (nearest-site cells with metric.... Use this skill whenever the user asks to create, teach, or deepen training on computational, geometry, layout, hulls, voronoi, delaunay, triangulation, Linear algebra and geometry, or requests workshops, lessons, curricula, job aids, or expert instruction in this area — even when the word “module” is never used.
compatibility: Any environment that can write Markdown files; benefits from web research access for authoritative sources; no external tools or packages required.
metadata:
  author: Promptstation skill-building pipeline (Data Visualization course 10, section 12)
  version: 1.0.0
  category: professional-education
---

# Computational Geometry for Layout: Hulls, Voronoi, Delaunay, and Triangulation — Professional Training

## Mission

Produce professional-grade learning modules and training materials on **computational Geometry for Layout: Hulls, Voronoi, Delaunay, and Triangulation** within The mathematical engine of graphics — vectors, matrices, transformations, projections, and geometry mastered for coordinate systems, camera mathematics, layout algorithms, and the linear-algebraic core of data visualization itself.

Subject scope: Covers the discrete-geometry algorithms that structure space in visualization: the convex hull — the boundary fundamental: the hull concept (the convex-hull-as-smallest-convex-containing-set definition connecting to section 10's convex-combination reading, the rubber-band intuition, the hull as the extreme-point subset and its stability under the section 3 affine transforms: the affine-invariance property); the hull algorithms at practitioner depth (the Graham-scan angular-sweep approach with its orientation-test core from section 1's perp product and section 2's determinants, the Andrew-monotone-chain alternative as the implementation-practical favorite, the QuickHull divide-and-conquer at awareness, the O(n log n) complexity floor and the output-sensitive traditions); the hull applications in visualization (the group-boundary rendering for clustered scatter plots and set diagrams: the hull-with-padding-and-smoothing conventions using section 11's curves, the outlier detection as non-hull membership diagnostics, the collision and extent computations for camera framing and label avoidance, the hull hierarchies for multi-level grouping displays); and the hull extensions (the alpha-shape concept at awareness: the concave-hollow-boundary family for non-convex cluster outlines, the dynamic and streaming hull updates at awareness from the real-time discipline, the 3D hull connections to surface reconstruction in the spatial visualization context) as the boundary layer; the Voronoi diagram — the proximity partition: the Voronoi concept (the nearest-site partition of the plane: the region-per-point definition where every location belongs to its closest generator, the cell-as-polygon structure with the section 10 distance-metric dependence: the L1-L2-L∞ Voronoi shape variations as the metric-geometry demonstration); the computation approaches (the Fortune sweep-line algorithm at awareness as the classic O(n log n) method, the Delaunay-duality route as the practical computation path below, the library landscape: the d3-delaunay and Voronoi ecosystem interfaces from the DOM discipline, the bounded-clip-to-viewport conventions for display); the Voronoi applications in visualization (the nearest-neighbor interpolation display: the value-at-any-point-as-nearest-site reading for scattered data surfaces, the spatial-dominance and catchment maps: the service-area and territory readings from the spatial discipline, the label-placement and collision avoidance using cell geometry, the Voronoi-treemap generalization: the non-rectangular hierarchical space partitioning from the treemap tradition, the hover-target regions for scattered points: the invisible-cell hit-testing application connecting to section 13); the weighted and higher-order variants (the power diagrams and Apollonius concepts at awareness for weighted proximity, the k-nearest higher-order diagrams at awareness); and the dual relationship statement (the Voronoi-Delaunay duality as the structural backbone: the edge-adjacency correspondence enabling one computation to produce both) as the partition layer; the Delaunay triangulation — the connectivity dual: the Delaunay concept (the triangulation of the site set where no point lies inside any triangle's circumcircle: the empty-circumcircle criterion, the duality with Voronoi from the cell-adjacency reading: the Delaunay-edge-connects-Voronoi-neighbors correspondence, the angle-optimality property: the max-min-angle tendency avoiding sliver triangles); the computation and libraries (the incremental and divide-conquer algorithms at awareness, the Bowyer-Watson cavity approach as the conceptual-intuition standard, the d3-delaunay, Triangle, and CGAL ecosystem at practitioner awareness, the robustness requirements: the exact-arithmetic and perturbation traditions for cocircular and degenerate cases connecting to section 14); the Delaunay applications in visualization (the mesh generation for surface and terrain rendering from the spatial and 3D disciplines: the scattered-points-to-triangle-mesh pipeline, the interpolation foundation: the barycentric-interpolation-within-Delaunay-triangles from section 1's barycentric coordinates producing continuous surfaces, the contour generation via triangle edge crossing: the marching-triangles analog of the marching-squares family from the field-visualization traditions, the natural-neighbor interpolation using Voronoi-cell-area weights at awareness, the network-proximity structures: the relative-neighborhood-graph and Gabriel-graph subgraphs for network layout initialization); the constrained and quality variants (the constrained Delaunay with forced edges for boundaries and obstacles at awareness: the polygon-mesh requirement in maps, the refinement and Steiner-point insertion for quality meshes at awareness from the mesh-generation literature); and the triangulation beyond Delaunay (the triangle-strip-and-fan rendering primitives from the graphics-APIs discipline as the display-side triangulation, the polygon-triangulation requirement: the ear-clipping method at practitioner depth for filling arbitrary polygons in canvas and WebGL contexts) as the connectivity layer; spatial indexing structures — the query accelerators: the bounding volume hierarchy (the AABB trees from section 1's collision computations: the recursive box partitioning for fast proximity and intersection queries from the graphics and 3D disciplines, the build-and-query complexity profile, the dynamic-update strategies for moving data); the grid and hash methods (the uniform spatial hashing for evenly distributed points: the bucket-lookup patterns from the performance discipline, the occupancy-grid conventions in interaction systems); the quadtree and octree family (the recursive quadrant partitioning: the point-region and region quadtree distinctions, the d3-quadtree interface as the visualization-ecosystem standard for force layouts and nearest-neighbor queries from the DOM and network traditions, the octree 3D extension for spatial data from the 3D discipline); the kd-tree and range structures (the alternating-split kd-trees for nearest-neighbor search in low dimensions: the section 10 metric queries accelerated, the range-tree and interval concepts at awareness for axis-aligned queries); and the index-selection framework (the data-distribution, query-type, and update-frequency decision matrix: the static-batch versus dynamic-streaming selections from the performance discipline, the dimension-scaling caveats: the curse-of-dimensionality index degradation motivating the reduction methods) as the accelerator layer; layout algorithms as applied geometry — the composition view: the force-directed layout geometry (the spring-and-repulsion force computations as section 1 vector arithmetic at scale: the distance-force functions from section 10, the quadtree-accelerated Barnes-Hut approximation from the network tradition: the hierarchical-far-field-multipole intuition, the convergence and energy readings connecting to section 7's stability diagnostics); the packing algorithms (the circle-and-rectangle packing as constraint geometry: the collision-resolution iteration patterns from the bubble-chart traditions, the treemap squarification as the area-partition optimization from the hierarchy discipline); the label-placement geometry (the candidate-position generation and collision detection via the index structures: the section 13 intersection tests applied, the leader-line computation using hull and Voronoi proximity data); the jitter and dodge computations (the systematic-overlap resolution via small random or deterministic offsets: the distribution-preserving jitter conventions from the exploratory-analysis discipline); and the geometry-pipeline integration (the hull-Voronoi-Delaunay-index composition in a single interactive view: the layered spatial-computation architecture from the performance discipline, the incremental-recomputation strategies for filtered and streaming data) as the composition layer; and the section anti-patterns — the failure library: the brute-force-nearest-neighbor O(n²) loops freezing interactive views, remedied by the index-structure selection framework; the degenerate-cocircular crashes in Delaunay computation on grid-aligned data, remedied by the perturbation and robustness traditions; the voronoi-unclipped overflow rendering cells beyond the viewport, remedied by the bounding conventions; the hull-padding artifacts producing self-intersecting outlines at concavities, remedied by the alpha-shape and curve-smoothing awareness; the sliver-triangle interpolation streaks from poor triangulation quality, remedied by the angle-optimality and refinement understanding; the static-index staleness after data updates returning wrong neighbors, remedied by the dynamic-update and rebuild strategies; and the layout-force-blindness tuning force-directed parameters without the distance-force function understanding, remedied by the section 10 metric integration with detection methods as the discipline.

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
- The linear-algebra canon at practitioner depth (the Strang-style matrix-factorization and vector-space traditions with the 3Blue1Brown-lineage geometric intuition emphasis)
- The computer-graphics mathematics tradition (the transformation-pipeline, projection, and quaternion literature from the graphics-textbook canon)
- The computational-geometry literature (the convex-hull, Delaunay-Voronoi, triangulation, and intersection traditions behind layout and spatial algorithms)
- The matrix-decomposition applications (the SVD, eigenvalue, and PCA lineage connecting linear algebra to dimensionality reduction and data analysis)
- The numeric-computing documentation (the GLM, gl-matrix, ndarray, and NumPy-lineage library materials for practical computation)
- The numerical-stability and floating-point literature at practitioner depth (the precision, conditioning, and accumulation-error traditions)
- The projection-and-map-mathematics traditions (the cartographic projection mathematics connecting to the geospatial discipline)
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
# Computational Geometry for Layout: Hulls, Voronoi, Delaunay, and Triangulation [— audience/context subtitle]

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

Avoid: Formula-copying without geometric intuition — applying transformation matrices and decompositions as incantations, unable to diagnose why a projection inverts, a quaternion gimbal-flips, or an SVD sign-flips between runs; Composition-order blindness — multiplying transformation matrices in the wrong order (rotate-then-translate versus translate-then-rotate) and debugging the resulting geometry archaeologically instead of algebraically; Row-versus-column and handedness chaos — mixing conventions across libraries and platforms (D3 versus WebGL versus NumPy), producing mirrored, transposed, or silently wrong results; Floating-point naivete — accumulating transformation error across long matrix chains, subtracting nearly-equal large coordinates, and ignoring conditioning until jitter and drift destroy the render; SVD-eigendecomposition mystification — treating dimensionality reduction and layout mathematics as black boxes, so the scree-plot, sign, rotation, and rank decisions go unexamined; exercises without evaluation criteria; modules that stop at inspiration without a single decision the learner can now make better; and any content that overstates certainty beyond what the evidence supports.

## Decision Heuristic

When allocating depth under time or length limits, ask:

1. Where will this audience actually stall in practice?
2. Which unit protects the most value if taught well?
3. Can the learner run the framework tomorrow without me?
4. Is every example doing work a plain sentence could not?
5. What would a skeptical domain expert say about this material?

If two topics compete for space, keep the one that changes a decision.

## Final Principle

The goal is not more content about Linear algebra and geometry. The goal is that a practitioner could take this material and perform: Structure visualization space through computational geometry: compute convex hulls (definition and affine invariance, monotone-chain and Graham-scan orientation-test cores, group-boundary-outlier-framing applications, alpha-shape and 3D extensions), build Voronoi partitions (nearest-site cells with metric dependence, Fortune and duality computation routes, interpolation-dominance-label-treemap-hit-target applications, weighted variants), master Delaunay triangulation (empty-circumcircle criterion and Voronoi duality, Bowyer-Watson intuition with robustness requirements, mesh-interpolation-contour-natural-neighbor applications, constrained refinement variants, ear-clipping polygon triangulation), deploy spatial indexes (AABB hierarchies, spatial hashing, quadtree-octree families with d3 interfaces, kd-trees, selection framework by distribution-query-update profile), compose layout algorithms (Barnes-Hut force geometry, packing constraints, label placement via collision tests, jitter conventions, layered incremental pipelines), and avoid brute-force, degenerate, unclipped, padding-artifact, sliver, staleness, and force-blindness failures — with the same evidence discipline the field's best practitioners use. The module must function simultaneously as a learning resource, a practical reference, and a working methodology.

## Bundled References

Read `references/domain-content-map.md` during Phases 3–4 for the unit-by-unit content map: scope statements, teaching bullets, evidence anchors, and trade-off prompts.

Read `references/exercise-and-checklist-library.md` during Phases 5–6 for the ready-to-adapt exercises and the professional gate checklists.
