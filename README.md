# quiverkeep-web

> Web thin client for QuiverKeep.

`quiverkeep-web` will host the browser-facing client for dashboard, history, remote visibility, and future product surfaces delivered through the web. It must stay contract-driven and use `quiverkeep-core` as the single source of truth.

## Responsibilities

- render web dashboards and history views;
- expose browser UX for limits, providers, and machine-level visibility;
- consume core APIs without redefining domain calculations;
- evolve independently from desktop while staying contract-compatible.

## Boundaries

- business logic remains in `quiverkeep-core`;
- web-only logic must stay presentational;
- no direct access to storage or hidden core internals.

## Status

Repository initialized. Implementation has not started yet.
