# Typed Agnostic State Architecture

## Overview

A living `×data/state` payload that carries explicit type bindings for runtime validation, coherence scoring, and cross-node transport, while remaining task-agnostic (goal-independent reusable cognitive unit, inheriting the TAS principle).

## Layers

### Agnostic Core
- Goal-independent reusable unit.
- Operational facts: phase, threads, ethics, mode, coherence, space_name.
- Not bound to one concrete objective.

### Type Layer
- Explicit `typed_bindings` and schema constraints.
- Enables validation, CoherenceMonitor scoring, and transport fidelity.
- Prevents drift while preserving reusability.

### Mutation Rules
- Consent-gated writes (KickGuard / Dima pattern).
- Phase-aware.
- CoherenceMonitor delta threshold; negative valence requires mitigation.

### Lifecycle Integration
- TAS extracts steps into this state.
- puTASe purifies the payload.
- KickFlow sequences.
- State remains the living carrier across Spaces and flows.

### Persistence & Observability
- Living `×data/state` with submit semantics.
- Traceable via `×data/trace`.
- Ready for parallel_f DAG binding or Flowmusic OSC.

## Relation to TAS / PTAS

TAS (Task-Agnostic Steps) provides the cognitive bricks. Typed Agnostic State is the typed carrier that holds purified (PTAS) and structured payloads while remaining reusable.
