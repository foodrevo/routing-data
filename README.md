# Foodrevo public routing data

This repository publishes immutable, versioned public OpenStreetMap datasets for
self-hosted routing. It contains no application source, delivery addresses,
customer records, courier routes, GPS histories, credentials or signing keys.

Map data is © OpenStreetMap contributors and is available under the
[Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/).
See [OpenStreetMap copyright and attribution](https://www.openstreetmap.org/copyright).
Regional extracts are supplied by [Geofabrik](https://download.geofabrik.de/europe/hungary.html).

Each release identifies the source extract, preprocessing profile, pinned OSRM
image and graph identity. Its archive contains the public source PBF, derived
OSRM graph files and a manifest with individual file sizes and SHA-256 hashes.
Deployment must verify both the archive checksum and manifest checksum, then
validate every manifest entry. Releases and assets must never be replaced.

The first dataset is `hu-20261014-car-mld-26.10-378a62919507`, prepared for the
standard car profile with OSRM 26.10 MLD from the 14 October 2026 Hungary extract.
This data does not establish a usable building entrance, legal parking or live
traffic conditions.
