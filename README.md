# OpenStreetMap data for XYARD golf books

Free machine-readable downloads of the identified OSM-derived geographic data.
Packaging revised 29 October 2026. The final geographic data in these historical
releases is unchanged; detailed internal processing descriptions, quality-control
logs and unnecessary editing metadata have been omitted. Tags and download
filenames are retained so existing printed links continue to work. Package bytes
and SHA-256 checksums have changed; use the current checksum attachments.

## Downloads

- [Titirangi_Golf_Club_OSM_Only_2026-10-27.zip](https://github.com/willxuxxl/golf-map-data/releases/download/titirangi-v1-2026-10-27/Titirangi_Golf_Club_OSM_Only_2026-10-27.zip)
- [Royal_Wellington_OSM_Derived_Data_2026-10-20_v1.zip](https://github.com/willxuxxl/golf-map-data/releases/download/royal-wellington-v1-2026-10-20/Royal_Wellington_OSM_Derived_Data_2026-10-20_v1.zip)
- [Windross_Farm_OSM_Derived_Data_2026-10-20_v4.zip](https://github.com/willxuxxl/golf-map-data/releases/download/windross-v4-2026-10-20/Windross_Farm_OSM_Derived_Data_2026-10-20_v4.zip)
- [Remuera_OSM_Derived_Data_2026-10-20_v2.zip](https://github.com/willxuxxl/golf-map-data/releases/download/data-2026-10-20/Remuera_OSM_Derived_Data_2026-10-20_v2.zip)
- [Windross_Farm_OSM_Derived_Data_2026-10-20_v1.zip](https://github.com/willxuxxl/golf-map-data/releases/download/data-2026-10-20/Windross_Farm_OSM_Derived_Data_2026-10-20_v1.zip)

Release pages and their checksum attachments:

- [Titirangi v1, 27 October 2026](https://github.com/willxuxxl/golf-map-data/releases/tag/titirangi-v1-2026-10-27)
- [Royal Wellington / Heretaunga v1, 20 October 2026](https://github.com/willxuxxl/golf-map-data/releases/tag/royal-wellington-v1-2026-10-20)
- [Windross Farm v4, 20 October 2026](https://github.com/willxuxxl/golf-map-data/releases/tag/windross-v4-2026-10-20)
- [Remuera v2 and Windross Farm v1, 20 October 2026](https://github.com/willxuxxl/golf-map-data/releases/tag/data-2026-10-20)

## Contents and interpretation

Archives contain the identified geographic data, original OSM objects and
relevant source IDs, retained source tags, README, licence/provenance records
and checksums. Original projected geometry is also retained where previously
provided. The original and final data represent different stages of the same
identified geographic contents.

JSON is documented project JSON, not GeoJSON. Projected coordinates are
[easting, northing] in NZTM2000 / EPSG:2193, metres. OSM XML uses WGS84 latitude
and longitude. Preserve closed flags, interior rings and relation memberships;
open watercourses are not closed water polygons. Final centres, approach
references and hole assignments remain where supplied.

These are historical data releases, not new surveys or automatic matches for
later book editions. Their packaging dates do not imply refreshed OSM capture.
Mapped green centres are area centroids, not daily pins. Tee starts and edges
are approximate mapped geometry, not verified event tee positions or surveyed
playing boundaries. Mapped water is not an official penalty-area ruling;
trees/scrub are not a field survey. Context may include neighbouring holes.
No club endorsement or tournament approval is claimed.

Remuera has 18 routes and 17 final OSM-derived green boundaries. The original
Hole 4 OSM green remains only as historical source geometry; the final
independently aerial-redrawn Hole 4 boundary is outside that OSM release.
Windross Farm excludes three independently aerial-traced sand patches.

## Licence and scope

Copyright [OpenStreetMap contributors](https://www.openstreetmap.org/copyright).
The included OSM database and Will Xu's database adaptation contributions are
licensed under [ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/).
Preserve the included attribution and licence notices. Reuse, modification,
redistribution and commercial use are permitted subject to ODbL, including
applicable share-alike and machine-readable access requirements. No additional
personal-use-only or non-commercial condition is imposed on this database.
See the licence for warranty and liability provisions. No trademark rights
or club endorsement are granted.

These downloads identify the OSM geographic component. They do not contain
LINZ imagery, DEM/DSM, point clouds, independent terrain/elevation/slope
models, independent aerial traces, private club/event scorecards, book PDFs,
brand assets, editable artwork or production programs. Provider names and
par/handicap values in retained OSM tags are upstream OSM records, not separate
provider datasets or verified club scorecards.

This repository does not certify that all obligations for a complete mixed
database under ODbL section 4.6 have been satisfied. Actual additional contents
and the data used by later book editions must be assessed separately. Other
providers' book-attribution and licence conditions remain applicable even when
their datasets are not included here. Original book design and artwork are
separate from this licensed database. Existing licences and permissions remain
valid. Previous public copies and Git history are not recalled by this revision.
