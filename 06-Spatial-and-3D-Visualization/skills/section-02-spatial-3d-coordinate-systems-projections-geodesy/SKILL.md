---
name: section-02-spatial-3d-coordinate-systems-projections-geodesy
description: Develop comprehensive, professional-level learning modules and training materials on coordinate Systems, Projections, and Geodesy within Spatial & 3D Visualization — GIS, Mapbox, Leaflet, Three.js — operate the geodetic frame (WGS84 ellipsoid-datums, axis-order conventions, CRS EPSG architecture with geographic-versus-projected distinctions) and projection mathematics (surface families, conformal-equal-area-compromise taxonomy, Tissot indicatrix reasoning), master Web-Mercator internals (formulas, ±85°.... Use this skill whenever the user asks to create, teach, or deepen training on coordinate, systems, projections, geodesy, Spatial and 3D, or requests workshops, lessons, curricula, job aids, or expert instruction in this area — even when the word “module” is never used.
compatibility: Any environment that can write Markdown files; benefits from web research access for authoritative sources; no external tools or packages required.
metadata:
  author: Promptstation skill-building pipeline (Data Visualization course 06, section 2)
  version: 1.0.0
  category: professional-education
---

# Coordinate Systems, Projections, and Geodesy — Professional Training

## Mission

Produce professional-grade learning modules and training materials on **coordinate Systems, Projections, and Geodesy** within Geospatial and three-dimensional visualization engineering — GIS fundamentals, web-mapping stacks (Leaflet, Mapbox/MapLibre), and Three.js mastered for representing geographic data and complex multidimensional structures.

Subject scope: Builds the mathematical-geographic foundation: the earth-model hierarchy — the geodetic frame: the ellipsoid concept (the WGS84 ellipsoid parameters — the equatorial and polar radii, the flattening; the datum concept — the ellipsoid-plus-origin definition anchoring coordinates to the physical earth, the datum-shift reality — the WGS84-ETRS89-NAD83 family differences producing meter-level offsets), the geoid-versus-ellipsoid distinction (the gravity-surface reality at awareness), and the coordinate-format literacy (the decimal-degrees, degrees-minutes-seconds, and the axis-order conventions — the lat-lon versus lon-lat confusion class that breaks silent data imports) as the geodetic foundation; the CRS architecture — the reference-system model: the EPSG-code system (the registry identifiers — the EPSG:4326 WGS84 geographic, the EPSG:3857 Web-Mercator projected, the national and regional CRS families), the geographic-versus-projected CRS distinction (the angular-coordinate systems versus the planar-meter systems), the CRS-declaration formats (the PROJ-strings, WKT definitions, and the metadata embedding in GeoJSON-Shapefile conventions — the GeoJSON RFC-7946 WGS84-mandate and its practical violations) as the reference-system literacy; the projection mathematics — the transformation engine: the projection-surface families (the cylindrical, conic, and azimuthal developable surfaces — the tangent and secant cases, the distortion-pattern characteristics per family), the distortion-property taxonomy (the conformal shape-preserving projections — the Mercator lineage; the equal-area projections — the Albers-Mollweide-Gall-Peters family; the equidistant and compromise projections — the Robinson-Winkel-Tripel balancing choices), and the Tissot-indicatrix visualization (the distortion-ellipse display making projection effects visible — the Greenland-inflation explanation) as the projection theory; the Web-Mercator deep dive — the universal web projection: the spherical-Mercator mathematics (the x-y formulas from lon-lat — the linear-longitude and nonlinear-latitude mapping, the y-clipping at ±85.05° — the square-world-tile rationale), the area-distortion consequences (the high-latitude inflation factors — the Africa-versus-Greenland truth, the latitude-dependent scale-bar impossibility), the zoom-level relationship (the z-x-y tile mathematics — the 2^z grid at each zoom, the pixel-coordinate computations, the world-size doubling per zoom) as the web-map coordinate core; the projection-selection discipline — the thematic decision: the use-case-to-projection matrix (the web-slippy-map convention — the 3857 default; the small-area thematic maps — the local-CRS and UTM-zone choices; the continental-and-world thematic maps — the Albers-Equal-Area-Conic and Winkel-Tripel recommendations; the polar regions — the azimuthal families), the area-comparison mandate (the equal-area requirement for choropleth and density work — the conformal-prohibition for area-reading tasks), and the projection-transparency practice (the CRS declaration in map furniture and documentation — the projection-disclosure norm) as the selection craft; the transformation practice — the reprojection engineering: the coordinate-conversion mechanics (the proj4js client-side transformation library — the forward and inverse projections, the datum-transformation pipelines), the data-reprojection workflows (the ogr2ogr-mapshaper-turf command-line and library conversion patterns, the QGIS batch reprojection at awareness), and the transformation-error management (the datum-shift accuracy, the antimeridian-crossing handling — the ±180° wrap bugs producing trans-Pacific line spikes, the pole-region clipping issues) as the conversion engineering; the spatial-reference in tile systems — the applied frame: the tile-coordinate-to-geographic conversions (the z-x-y to lat-lon-bounds mathematics — the tile-bbox computation functions, the slippy-map-tilenames conventions), the pixel-to-coordinate mappings (the screen-position to lon-lat inversion through the view transform — the click-to-coordinate patterns), and the multi-CRS layer composition (the mixing GeoJSON-WGS84 data on Mercator maps — the on-the-fly reprojection that libraries handle, and where they silently don't) as the tile-frame literacy; the non-geographic coordinate systems — the generalized spatial frame: the cartesian data-space mappings (the floor-plans, schematics, and network-diagram coordinates — the CRS-free spatial displays), the projected-coordinate illusion in D3 (the projection functions as scale-like data-to-pixel mappers — the d3-geo integration from the D3 discipline), and the custom-CRS registration (the proj4-definition extension for local systems) as the extended frame; the geodesy-precision layer — the accuracy engineering: the coordinate-precision economics (the decimal-place-to-ground-distance mapping — the 5-decimal meter-level convention, the float32-precision limits at planetary scale from the graphics discipline), the GPS-error realities (the consumer-GPS accuracy envelopes — the 3-10m typical errors, the multipath and atmospheric effects, the accuracy-metadata propagation to visualization uncertainty), and the geocoding-accuracy cascade (the address-to-point precision loss — the rooftop-versus-centroid-versus-interpolation quality tiers) as the precision discipline; the measurement-on-maps craft — the spatial computation: the distance-measurement correctness (the geodesic great-circle distances versus the projected-plane distances — the haversine and vincenty formulas, the turf-distance implementations, the Mercator-distance distortion awareness), the area-measurement discipline (the spherical-excess computation on geographic coordinates — the equal-area-projection alternative, the polygon-area functions), and the bearing-and-interpolation utilities (the great-circle intermediate points for curved flight-path rendering — the d3-geoInterpolate pattern) as the measurement toolkit; the debugging-coordinates practice — the troubleshooting craft: the common-CRS-failure diagnostics (the offset-geometry causes — the datum and axis-order errors; the stretched-squashed causes — the wrong-projection assumptions; the trans-Pacific-spike causes — the antimeridian wraps; the invisible-layer causes — the CRS-mismatch extent errors), the coordinate-inspection tooling (the browser-console validation, the geojson.io-mapshaper visual verification, the coordinate-epsg.io registry lookup) and the round-trip-verification discipline (the forward-inverse transformation consistency checks) as the debug toolkit; and the geodesy deliverable — the projection-literate, transformation-capable, precision-aware coordinate mastery.

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
# Coordinate Systems, Projections, and Geodesy [— audience/context subtitle]

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

The goal is not more content about Spatial and 3D. The goal is that a practitioner could take this material and perform: Operate the geodetic frame (WGS84 ellipsoid-datums, axis-order conventions, CRS EPSG architecture with geographic-versus-projected distinctions) and projection mathematics (surface families, conformal-equal-area-compromise taxonomy, Tissot indicatrix reasoning), master Web-Mercator internals (formulas, ±85° clipping, zoom-tile mathematics, area-distortion consequences) with use-case-to-projection selection discipline including equal-area mandates for choropleth work, measure correctly (geodesic distances, spherical areas, great-circle interpolation), and debug through CRS-failure diagnostics with round-trip verification — with the same evidence discipline the field's best practitioners use. The module must function simultaneously as a learning resource, a practical reference, and a working methodology.

## Bundled References

Read `references/domain-content-map.md` during Phases 3–4 for the unit-by-unit content map: scope statements, teaching bullets, evidence anchors, and trade-off prompts.

Read `references/exercise-and-checklist-library.md` during Phases 5–6 for the ready-to-adapt exercises and the professional gate checklists.
