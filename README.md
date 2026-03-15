# quiverkeep-web

> Web thin client for QuiverKeep.

`quiverkeep-web` will host the browser-based product client that connects to `quiverkeep-core`. It is the web counterpart to the desktop UI, not the promo site. The repository must stay contract-driven and use `quiverkeep-core` as the single source of truth.

## Responsibilities

- connect to local or remote `quiverkeep-core` instances;
- render browser UX for status, limits, providers, history, and related product views;
- consume core APIs without redefining domain calculations;
- evolve independently from desktop while staying contract-compatible.

## Boundaries

- business logic remains in `quiverkeep-core`;
- promo and marketing copy belong in `quiverkeep-landing`;
- web-only logic must stay presentational;
- no direct access to storage or hidden core internals.

## Status

Repository initialized. Implementation has not started yet.
