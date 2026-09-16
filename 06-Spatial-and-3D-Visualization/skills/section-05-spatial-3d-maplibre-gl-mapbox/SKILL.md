---
name: section-05-spatial-3d-maplibre-gl-mapbox
description: Develop comprehensive, professional-level learning modules and training materials on mapLibre GL and Mapbox — Vector Tiles, Styles, and GPU Map Rendering within Spatial & 3D Visualization — GIS, Mapbox, Leaflet, Three.js — operate the MapLibre-Mapbox GL architecture (view-state cameras, source-layer systems, feature querying) and master the style specification (layer types, data-and-zoom-driven expressions, feature-state dynamics, runtime property updates, Maputnik workflows); integrate vector-tile and GeoJSON sources with.... Use this skill whenever the user asks to create, teach, or deepen training on maplibre, mapbox, vector, tiles, styles, rendering, Spatial and 3D, or requests workshops, lessons, curricula, job aids, or expert instruction in this area — even when the word “module” is never used.
compatibility: Any environment that can write Markdown files; benefits from web research access for authoritative sources; no external tools or packages required.
metadata:
  author: Promptstation skill-building pipeline (Data Visualization course 06, section 5)
  version: 1.0.0
  category: professional-education
---

# MapLibre GL and Mapbox: Vector Tiles, Styles, and GPU Map Rendering — Professional Training

## Mission

Produce professional-grade learning modules and training materials on **mapLibre GL and Mapbox: Vector Tiles, Styles, and GPU Map Rendering** within Geospatial and three-dimensional visualization engineering — GIS fundamentals, web-mapping stacks (Leaflet, Mapbox/MapLibre), and Three.js mastered for representing geographic data and complex multidimensional structures.

Subject scope: Covers the professional vector-mapping stack: the MapLibre-GL architecture — the GPU-map model: the WebGL-rendering foundation (the vector-tile client-side rendering from the graphics-APIs discipline — the GPU-drawn geometry and labels with the smooth-continuous-zoom result), the map-object and view-state model (the center-zoom-bearing-pitch camera state — the 3D-capable view parameters, the style-object architecture as the single rendering specification), the source-layer system (the data-source types — the vector, raster, geojson, image, and video sources; the style-layer rendering rules referencing sources) and the event system (the map-render-and-data events, the layer-feature query interaction — the queryRenderedFeatures-querySourceFeatures mechanics) as the framework anatomy; the style-specification mastery — the declarative rendering language: the style-JSON architecture (the layers array with type-source-paint-layout structure, the layer-type vocabulary — the fill, line, symbol, circle, heatmap, fill-extrusion, raster, and hillshade types, the ordering-and-visibility control), the expression system (the data-driven-styling expressions — the get-match-case-step-interpolate operators enabling property-and-zoom-driven rendering: the zoom-interpolated styling for scale-adaptive maps, the feature-state expressions for dynamic highlighting without restyling), and the style-editing workflows (the Maputnik visual editor, the programmatic style manipulation — the setPaintProperty and setLayoutProperty runtime updates, the style-diff and update mechanics) as the styling core; the vector-tile integration — the data pipeline: the vector-source configuration (the tile-URL templates and TileJSON endpoints, the minzoom-maxzoom-promoteId options), the GeoJSON-source patterns (the inline-data rendering with the cluster options — the built-in geojson clustering, the dynamic-data updates via setData), the runtime-source-layer addition (the addSource-addLayer programmatic data integration, the image-and-video georeferenced overlays — the coordinate-corner registration) and the tile-performance characteristics (the HTTP-caching of tiles, the worker-based parsing, the overzooming behavior beyond maxzoom) as the data integration; the symbol-and-label rendering — the cartographic text: the symbol-layer mechanics (the text-field expressions, the icon-image sprite integration, the placement-along-line geometry), the collision-detection system (the automatic label-decluttering — the text-allow-overlap and icon-optional controls, the label-priority ordering), the font-and-sprite management (the glyph-server requirements — the PBF-font formats, the sprite-sheet generation for icons), and the localization patterns (the multi-language text-field expressions — the name:en-name:local fallbacks) as the label craft; the camera-and-navigation system — the view control: the programmatic camera operations (the flyTo-easeTo-jumpTo animations — the curve-speed-easing parameters, the fitBounds auto-framing with padding), the navigation-control integration (the NavigationControl-GeolocateControl-FullscreenControl UI components, the custom-control authoring), the gesture configuration (the scrollZoom-dragPan-touchPitch fine-grained enable-disable, the maxBounds-minZoom-maxZoom constraints, the hash-URL state synchronization) and the camera-animation choreography (the narrative-map-tour patterns — the sequenced flyTo storytelling, the scrollytelling integration from the narrative course) as the navigation system; the 3D-capabilities — the terrain and extrusion: the terrain-system configuration (the terrain-source setup — the DEM tile integration, the exaggeration control, the terrain-driven layer draping — the fill-line-symbol placement on 3D surface), the fill-extrusion layer patterns (the building-and-polygon height extrusion — the extrusion-height-color expressions from data properties, the pitch-angle 3D perspective viewing), the sky-and-fog atmosphere effects, and the 3D-usage discipline (the terrain for genuine topography, the extrusion for volumetric data — the decoration-avoidance honesty from the pitfalls) as the 3D-map layer; the Mapbox-GL-versus-MapLibre distinction — the ecosystem reality: the fork history and license divergence (the Mapbox-v1-to-v2 license change spawning the MapLibre community fork, the API-similarity and divergence trajectory), the service-model differences (the Mapbox hosted-services integration — the tile, geocoding, routing, and static-API ecosystem with the token billing; the MapLibre BYO-services freedom — the provider-agnostic tile and style sourcing), the capability comparison (the Mapbox-exclusive features versus MapLibre community innovations — the globe-view and protocol extensions), and the selection criteria (the budget, control, privacy, and feature requirements driving the choice — the maplibre-with-commercial-tiles and mapbox-full-service patterns) as the platform literacy; the deck.gl integration — the massive-overlay layer: the MapboxOverlay-MapLibreOverlay interoperation (the deck.gl layers composited into the GL-map context — the shared camera synchronization), the geo-layers vocabulary (the ScatterplotLayer-IconLayer-TextLayer-H3HexagonLayer-TripsLayer-ArcLayer families for massive spatial data), the interleaved-and-overlay rendering modes, and the hybrid-architecture patterns (the base-map-in-GL with data-layers-in-deck for million-feature maps — the graphics-APIs course integration) as the scale-overlay system; the interaction-and-query patterns — the feature interaction: the rendered-feature querying (the queryRenderedFeatures pixel-to-feature lookup — the hover-click feature identification with the layer-filter scoping), the feature-state management (the setFeatureState dynamic per-feature styling — the hover-highlight and selection patterns without data mutation), the popup-tooltip integration (the MapLibre Popup- Marker-anchored HTML overlays with the viewport-positioning discipline) and the cross-layer interaction coordination (the multi-layer query aggregation, the legend-and-filter-driven layer visibility toggling) as the interaction craft; the geocoding-and-search integration — the location-finding layer: the geocoder-control patterns (the Mapbox-Geocoder and Pelias-lineage search UI integration, the custom-geocoding-service wiring), the reverse-geocoding workflows (the click-to-address patterns), the search-result-to-map flows (the result-flyTo-and-highlight choreography), and the autocomplete-and-bias configuration (the proximity-and-bbox result prioritization) as the search integration; the production-engineering practice — the deployment layer: the token-and-key management (the scoped-token security — the URL-restriction and rotation practices, the billing-usage monitoring), the style-and-tile hosting (the CDN strategies, the self-hosted tile infrastructure options — the tileserver-gl and PMTiles patterns), the bundle-and-load optimization (the maplibre-gl bundle size, the lazy-map-loading patterns, the worker-configuration), and the performance-profiling (the map-render profiling, the layer-count and expression-complexity budgets, the style-validation tooling) as the production discipline; and the GL-mapping deliverable — the vector-tile, style-expression, 3D-terrain, and deck.gl-overlay professional mapping capability.

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
# MapLibre GL and Mapbox: Vector Tiles, Styles, and GPU Map Rendering [— audience/context subtitle]

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

The goal is not more content about Spatial and 3D. The goal is that a practitioner could take this material and perform: Operate the MapLibre-Mapbox GL architecture (view-state cameras, source-layer systems, feature querying) and master the style specification (layer types, data-and-zoom-driven expressions, feature-state dynamics, runtime property updates, Maputnik workflows), manage production tokens, hosting, bundles, and profiling — with the same evidence discipline the field's best practitioners use. The module must function simultaneously as a learning resource, a practical reference, and a working methodology.

## Bundled References

Read `references/domain-content-map.md` during Phases 3–4 for the unit-by-unit content map: scope statements, teaching bullets, evidence anchors, and trade-off prompts.

Read `references/exercise-and-checklist-library.md` during Phases 5–6 for the ready-to-adapt exercises and the professional gate checklists.
