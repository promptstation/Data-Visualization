# Exercise and Checklist Library — Coordinate Systems, Projections, and Geodesy

Read this during Phase 5 (exercises) and Phase 6 (checklists). Adapt
scenarios to the audience's domain; keep evaluation criteria intact — they
are what make the exercises assessable. In full-module mode, write an
expert-quality model solution for each included exercise.

## Table of Contents
- Part A: Practical Exercises
- Part B: Professional Gate Checklists

---

# Part A: Practical Exercises

## Exercise 1 — Operate the geodetic frame (WGS84 ellipsoid-datums
**Scenario:** provide a realistic Spatial and 3D scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** operate the geodetic frame (WGS84 ellipsoid-datums, axis-order conventions, CRS EPSG architecture with geographic-versus-projected distinctions) and projection mathematics (surface families, conformal-equal-area-compromise taxonomy, Tissot indicatrix reasoning), master Web-Mercator internals (formulas, ±85° clipping, zoom-tile mathematics, area-distortion consequences) with use-case-to-projection selection discipline including equal-area mandates for choropleth work.
**Constraints:** must use the framework taught in the corresponding unit; must state assumptions and trade-offs; one deliverable, length-bounded.
**Deliverable:** the professional artifact this capability produces (memo, table, plan, analysis, or model — as applicable).
**Evaluation criteria:** correct application of the framework; decisions justified with evidence; limitations honestly stated; artifact usable by a colleague without further explanation.

## Exercise 2 — Execute reprojection engineering (proj4js
**Scenario:** provide a realistic Spatial and 3D scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** execute reprojection engineering (proj4js, ogr2ogr-mapshaper pipelines) with antimeridian and datum-shift error management.
**Constraints:** must use the framework taught in the corresponding unit; must state assumptions and trade-offs; one deliverable, length-bounded.
**Deliverable:** the professional artifact this capability produces (memo, table, plan, analysis, or model — as applicable).
**Evaluation criteria:** correct application of the framework; decisions justified with evidence; limitations honestly stated; artifact usable by a colleague without further explanation.

## Exercise 3 — Convert between tile-pixel-geographic coordinates
**Scenario:** provide a realistic Spatial and 3D scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** convert between tile-pixel-geographic coordinates, enforce precision discipline (decimal-place economics, GPS-geocoding accuracy cascades, float limits).
**Constraints:** must use the framework taught in the corresponding unit; must state assumptions and trade-offs; one deliverable, length-bounded.
**Deliverable:** the professional artifact this capability produces (memo, table, plan, analysis, or model — as applicable).
**Evaluation criteria:** correct application of the framework; decisions justified with evidence; limitations honestly stated; artifact usable by a colleague without further explanation.

## Exercise 4 — Measure correctly (geodesic distances
**Scenario:** provide a realistic Spatial and 3D scenario appropriate to the audience (real or closely modeled on documented practice).
**Objective:** measure correctly (geodesic distances, spherical areas, great-circle interpolation), and debug through CRS-failure diagnostics with round-trip verification.
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

## B1. Operate the geodetic frame checklist
- [ ] Operate the geodetic frame (WGS84 ellipsoid-datums, axis-order conventions, CRS EPSG architecture with geographic-versus-projected distinctions) and projection mathematics (surface families, conformal-equal-area-compromise taxonomy, Tissot indicatrix reasoning), master Web-Mercator internals (formulas, ±85° clipping, zoom-tile mathematics, area-distortion consequences) with use-case-to-projection selection discipline including equal-area mandates for choropleth work?
- [ ] Decisions and their justification are documented for review by a colleague

## B2. Execute reprojection engineering (proj4js, checklist
- [ ] Execute reprojection engineering (proj4js, ogr2ogr-mapshaper pipelines) with antimeridian and datum-shift error management?
- [ ] Decisions and their justification are documented for review by a colleague

## B3. Convert between tile pixel geographic coordinates, checklist
- [ ] Convert between tile-pixel-geographic coordinates, enforce precision discipline (decimal-place economics, GPS-geocoding accuracy cascades, float limits)?
- [ ] Decisions and their justification are documented for review by a colleague

## B4. Measure correctly (geodesic distances, checklist
- [ ] Measure correctly (geodesic distances, spherical areas, great-circle interpolation), and debug through CRS-failure diagnostics with round-trip verification?
- [ ] Decisions and their justification are documented for review by a colleague

## B5. Delivery quality checklist
- [ ] Every claim sourced, graded, or flagged as contested?
- [ ] All terminology explained on first use?
- [ ] Trade-offs stated wherever recommendations are context-dependent?
- [ ] Material reads as practitioner-written, not generic?
