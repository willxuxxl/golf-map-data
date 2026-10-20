# Will Xu Golf Map Data

Free downloads of the OpenStreetMap-derived geometry used in the corresponding Remuera, Windross Farm and Royal Wellington practice-book projects.

## Downloads

### Royal Wellington books - Version 1.0

[Download matching OSM data - 20 October 2026 v1](https://github.com/willxuxxl/golf-map-data/releases/download/royal-wellington-v1-2026-10-20/Royal_Wellington_OSM_Derived_Data_2026-10-20_v1.zip)

[View release notes and checksums](https://github.com/willxuxxl/golf-map-data/releases/tag/royal-wellington-v1-2026-10-20).

Heretaunga layout: 18 OSM routes and their mapped greens, with the exact two-pass display boundaries and derived centres used by Royal Wellington book Version 1.0. Includes source/projected geometry, mapped fairways, bunkers, tees, watercourses and scrub, plus neighbouring-hole context. The user-supplied tee photograph and all transcribed event/club tee values are excluded, as are all LINZ data and models, book PDFs and brand assets.


### Windross Farm books - Version 4.0

[Download matching OSM data - 20 October 2026 v4](https://github.com/willxuxxl/golf-map-data/releases/download/windross-v4-2026-10-20/Windross_Farm_OSM_Derived_Data_2026-10-20_v4.zip)

[View v4 release notes and checksums](https://github.com/willxuxxl/golf-map-data/releases/tag/windross-v4-2026-10-20).

This release includes the exact two-pass rounded OSM geometry and green centres used by book Version 4.0, its original source geometries, 18 hole routes, route-based fairway ownership and all five mapped scrub features. It does not replace the earlier releases below.

### Earlier editions / Remuera

[View the versioned data release](https://github.com/willxuxxl/golf-map-data/releases/tag/data-2026-10-20).

- [Remuera OSM data — 2026-10-20 v2](https://github.com/willxuxxl/golf-map-data/releases/download/data-2026-10-20/Remuera_OSM_Derived_Data_2026-10-20_v2.zip)
- [Windross Farm OSM data — 2026-10-20 v1](https://github.com/willxuxxl/golf-map-data/releases/download/data-2026-10-20/Windross_Farm_OSM_Derived_Data_2026-10-20_v1.zip)

Downloads are free of charge. Keep the version that corresponds to your book. Older releases will remain available when new editions are added.

## Included data

Each archive contains a machine-readable geometry database, a filtered excerpt of the original OSM ways and nodes, English documentation, an ODbL licence notice, provenance and SHA-256 checksums.

- **Remuera:** 18 mapped hole routes and 17 OSM-derived green display boundaries. The original OSM Hole 4 green is included only as a historical source reference; the book's aerial-redrawn Hole 4 boundary is excluded.
- **Windross Farm:** 18 mapped hole routes and OSM-sourced greens, fairways, bunkers, tees and water; v4 also includes five mapped scrub features. Three separately aerial-interpreted sand patches are excluded.

Projected geometry uses EPSG:2193 (NZTM2000), in metres. The OSM XML excerpt uses explicitly named WGS84 latitude and longitude fields. See each archive's README for details.

## Licence and attribution

Map data: © OpenStreetMap contributors. https://www.openstreetmap.org/copyright

The OSM-derived geometry databases and Will Xu's contributions to them are made available under the [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/). Commercial reuse, modification and redistribution are allowed under that licence. Preserve notices and observe the applicable attribution, share-alike and machine-readable access obligations. See each archive's LICENSE.txt for the scope.

## Scope and limitations

These are OSM-only data releases. They contain no LINZ aerial imagery, elevation raster, derived terrain heat maps, independently aerial-traced geometry, club scorecard data, book PDFs, commercial screenshots, or brand assets. The designed books are not included or licensed by these releases.

This repository provides the identified OSM component of mixed-source projects; it does not establish that every obligation for an entire mixed-source database or a book has been satisfied. Attribution conditions for other sources used in a book remain applicable to that book.

Mapped boundaries and starts are approximate; mapped starts are not verified tee positions, and mapped centres are not current pins. The data is not a survey and carries no club endorsement, putting-level accuracy claim or tournament approval. Data is supplied as-is under the applicable licence.

Files were packaged on 20 October 2026 from the saved project snapshots. The date is not a claim of a new survey or new OSM retrieval. Statements inside archives about local-only preparation describe their packaging state before publication here.
