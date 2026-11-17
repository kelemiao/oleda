# Oleda resources

Public, versioned Oleda resource packages. This repository stores resource releases and integrity manifests only; it does not contain the mod source code.

- Packages include public machine/group waypoint information and full-resolution point images.
- Private amber waypoints, private photos, authentication secrets and player-specific teleport data are excluded.
- The game server continues to provide current public metadata and resource versions. Private data remains in authenticated, owner-scoped responses.
- Oleda downloads fixed-version assets directly from verified sources, checks the signed server manifest, length and SHA-256, and caches them locally.
- A valid session is required to import encrypted `.oledapack` resources. No decryption key is published here.
- Download links on the Oleda website point to external release storage, not the server's FRP tunnel.

Mirrors may be unavailable or delayed. Every candidate must return exactly the published bytes; checksum failures are rejected. No credentials are sent to mirrors.

These resources are distributed for use with Oleda. Publication does not grant additional rights to third-party works or create an open-source license for artwork. Font redistribution must retain its original license.
