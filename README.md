# Status Specs

This repository contains Status specifications, organized for consumption by the status.app website.

## Structure

Specs are stored under:

```
status/
```

Within that folder, documents are grouped by numeric IDs (e.g. `24/curation.md`) as well as `raw/` and `deprecated/`.

## Usage

The `status-web` project mounts this repository as a submodule at:

```
apps/status.app/content/specs
```

Content is then read from `status/...` by Contentlayer and rendered at `https://status.app/specs`.

## Source

These documents were migrated from the archived status specs in `rfc-index`.
