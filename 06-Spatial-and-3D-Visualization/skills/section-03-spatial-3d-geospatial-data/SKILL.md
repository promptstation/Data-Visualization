---
name: section-03-spatial-3d-geospatial-data
description: Develop comprehensive, professional-level learning modules and training materials on geospatial Data — Formats, Sources, and Preparation Pipelines within Spatial & 3D Visualization — GIS, Mapbox, Leaflet, Three.js — operate the geospatial format ecosystem (GeoJSON RFC-7946 conventions, TopoJSON topology-compression, MVT vector tiles with tippecanoe pipelines and PMTiles serving, raster-DEM-terrain encodings, Shapefile-GeoPackage interop via GDAL-mapshaper), source data through open portals, geocoding APIs, and real-time feeds.... Use this skill whenever the user asks to create, teach, or deepen training on geospatial, formats, sources, preparation, pipelines, Spatial and 3D, or requests workshops, lessons, curricula, job aids, or expert instruction in this area — even when the word “module” is never used.
compatibility: Any environment that can write Markdown files; benefits from web research access for authoritative sources; no external tools or packages required.
metadata:
  author: Promptstation skill-building pipeline (Data Visualization course 06, section 3)
  version: 1.0.0
  category: professional-education
---

# Geospatial Data: Formats, Sources, and Preparation Pipelines — Professional Training

## Mission

Produce professional-grade learning modules and training materials on **geospatial Data: Formats, Sources, and Preparation Pipelines** within Geospatial and three-dimensional visualization engineering — GIS fundamentals, web-mapping stacks (Leaflet, Mapbox/MapLibre), and Three.js mastered for representing geographic data and complex multidimensional structures.

Subject scope: Covers the data-foundation layer: the GeoJSON standard — the web-native format: the RFC-7946 specification (the geometry types — the Point-LineString-Polygon-MultiPoint-MultiLineString-MultiPolygon-GeometryCollection inventory, the Feature-and-FeatureCollection property model, the right-hand-rule winding and the WGS84-mandate conventions), the GeoJSON strengths and limits (the human-readability and JavaScript-native integration versus the verbosity and no-CRS ambiguity, the large-file performance issues), and the ecosystem tooling (the geojson.io inspection, the turf-js manipulation library, the D3-MapLibre-Leaflet direct consumption) as the format baseline; the TopoJSON alternative — the topology-preserving format: the arc-encoded topology concept (the shared-boundary storage — the quantization and delta-encoding compression achieving the documented order-of-magnitude size reductions, the topology preservation eliminating boundary-sliver artifacts between adjacent polygons), the conversion workflows (the topojson-server-client libraries, the mapshaper conversion), and the rendering integration (the topojson-feature-mesh extraction feeding D3 and canvas renderers — the interior-boundary mesh rendering for choropleths) as the efficient-geography format; the vector-tile architecture — the streaming format: the MVT specification (the Mapbox-Vector-Tile protobuf format — the layer-feature-geometry structure, the tile-local coordinate quantization, the extent convention), the tile-generation pipelines (the tippecanoe and tilemaker tooling — the zoom-level generalization configuration, the minzoom-maxzoom and attribute-filter decisions), the tile-serving infrastructure (the CDN and server options — the static-file pyramids, the dynamic tile servers, the PMTiles single-file format) and the client-consumption (the MapLibre source integration) as the production tile stack; the raster-data domain — the grid formats: the raster-versus-vector distinction (the gridded-cell data — the satellite imagery, elevation models, and climate fields versus the geometry features), the elevation-data systems (the DEM-DSM concepts, the SRTM-Copernicus sources, the terrain-RGB and quantized-mesh tile encodings for web rendering), the image-tile services (the WMS-WMTS standards at awareness, the XYZ-tile conventions), and the raster-in-browser handling (the GeoTIFF parsing — the geotiff-js, the raster-band visualization — the single-band-to-color-ramp mapping, the hillshade computation) as the grid-data literacy; the classic-GIS format awareness — the interop layer: the Shapefile family (the multi-file structure and encoding pitfalls — the legacy ubiquity requiring conversion), the GeoPackage and KML-GPX formats (the modern container and the GPS-exchange conventions), the OSM-PBF data (the planet-and-extract files — the osmium tooling), and the conversion-universal workflow (the ogr2ogr-GDAL as the format-swiss-army-knife, the mapshaper for web-optimized conversions) as the format-interop literacy; the spatial-data-source landscape — the acquisition layer: the open-data ecosystems (the government portals and statistical agencies — the census-geometry and boundary sources, the Natural-Earth zoom-appropriate base geography, the OSM-Geofabrik extracts), the API-sourced geography (the geocoding services — the Nominatim-Mapbox-Geoapify providers, the POI and boundary APIs, the real-time feeds — the transit-vehicle, flight-tracking, and sensor-location streams), and the data-quality assessment discipline (the source-provenance evaluation, the license-compatibility checking, the currency-and-accuracy verification before visualization commitment) as the sourcing practice; the geometry-processing toolkit — the preparation layer: the simplification operations (the Douglas-Peucker and Visvalingam-Whyatt algorithms — the tolerance selection by zoom level, the mapshaper-visvalingam workflows preserving topology), the spatial-operations vocabulary (the buffer-clip-union-intersect-dissolve operations via turf and GDAL — the analysis-ready preparation), the geometry-validation practices (the self-intersection and ring-orientation fixes, the sliver-and-spike removal), and the generalization strategy (the zoom-adaptive detail levels — the multi-resolution dataset preparation for tile pyramids) as the processing craft; the spatial-join and enrichment patterns — the data-integration layer: the point-in-polygon assignment (the spatial-join mechanics — the attaching observations to administrative units, the boundary-edge cases), the attribute-join discipline (the geometry-to-statistics joining via identifier matching — the FIPS-ISO-code conventions, the join-key validation before rendering), and the aggregation-to-geography patterns (the group-by-region summarization feeding choropleths — the normalization decisions previewing section 6) as the integration workflow; the data-pipeline engineering — the ETL discipline: the pipeline-architecture patterns (the source-extract-transform-publish flows — the scripted GDAL-mapshaper-turf chains, the build-time tile generation versus runtime processing decisions, the incremental-update strategies for changing data), the automation tooling (the makefile-GitHub-Actions pipelines for repeatable map-data preparation), and the caching-and-versioning practices (the processed-data snapshots, the tile-pyramid versioning) as the production data engineering; the large-spatial-data strategies — the scale layer: the file-size economics (the national-building-footprint and parcel datasets — the multi-GB source realities demanding tiling not loading), the client-side limits (the browser-memory and parse ceilings for GeoJSON, the streaming-and-progressive-load patterns), the server-side spatial databases (the PostGIS-geo-index literacy at awareness — the spatial-query capabilities), and the reduction hierarchy (the simplify-tile-aggregate escalation ladder matching data treatment to display scale) as the scale engineering; the metadata-and-documentation practice — the data governance: the spatial-metadata conventions (the CRS, extent, resolution, source, date, and license documentation embedded and alongside data), the data-dictionary discipline for feature properties, and the provenance-chain maintenance (the transformation-history recording for reproducibility) as the governance layer; and the geospatial-data deliverable — the format-fluent, pipeline-capable, scale-aware data engineering foundation.

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
# Geospatial Data: Formats, Sources, and Preparation Pipelines [— audience/context subtitle]

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

The goal is not more content about Spatial and 3D. The goal is that a practitioner could take this material and perform: Operate the geospatial format ecosystem (GeoJSON RFC-7946 conventions, TopoJSON topology-compression, MVT vector tiles with tippecanoe pipelines and PMTiles serving, raster-DEM-terrain encodings, Shapefile-GeoPackage interop via GDAL-mapshaper), source data through open portals, geocoding APIs, and real-time feeds with provenance-license-quality assessment, process geometries (Visvalingam simplification by zoom, spatial operations, validation, generalization) and integrate via spatial-joins with key validation, engineer ETL pipelines (build-time tile generation, incremental updates, CI automation, versioned caches), manage large-scale data through the simplify-tile-aggregate ladder against browser limits, and govern through spatial metadata, data dictionaries, and provenance chains — with the same evidence discipline the field's best practitioners use. The module must function simultaneously as a learning resource, a practical reference, and a working methodology.

## Bundled References

Read `references/domain-content-map.md` during Phases 3–4 for the unit-by-unit content map: scope statements, teaching bullets, evidence anchors, and trade-off prompts.

Read `references/exercise-and-checklist-library.md` during Phases 5–6 for the ready-to-adapt exercises and the professional gate checklists.
