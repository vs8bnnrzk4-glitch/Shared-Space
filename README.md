# Shared-Space

Public canonical protocol and specification plane for Project B.R.I.D.G.E.

## Authority boundary

- `GITHUB_COMMIT != AUTHORITY`
- `GITHUB_MERGE != EXECUTION_AUTHORITY`
- `ACCEPTANCE != ACTIVATION`
- `NO_PLANE_MAY_CREATE_AUTHORITY_FOR_ANOTHER_PLANE`

Content in this repository is **proposed** unless a hash-bound release manifest records the required bilateral governance acceptance. No file, commit, branch, pull request, or merge creates execution authority.

## Public-safe content only

This repository may contain public protocol specifications, schemas, contracts, fixtures, conformance tests, release manifests, architecture documentation, and version lineage. It must not contain credentials, secret keys, private host paths, sensitive authority records, private operational evidence, personal data, or attack-useful host internals.
