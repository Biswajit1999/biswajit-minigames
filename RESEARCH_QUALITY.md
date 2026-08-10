# Research Quality Upgrade

This repository has been upgraded with a compact research-quality layer: reference anchors, validation checks, and explicit scientific/software boundaries.

## Scope

Browser minigame collection upgraded with deterministic QA, accessibility checks and lightweight performance telemetry.

## Equations And Models

- Frame time budget 16.67 ms
- Score-normalization and reaction-time metrics

## Reference Anchors

The file `data/research-reference.json` stores benchmark anchors used by `scripts/validate_repository.mjs`. These are intentionally small and auditable so the repository can be checked without network access.

## Browser Upgrade

If this repository contains a browser interface, `research-overlay.js` adds a non-invasive mission-control quality panel with validation status and benchmark telemetry.

## References

- Nielsen, J., 1994. Usability Engineering. Morgan Kaufmann.
