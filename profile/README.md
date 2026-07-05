# The Free Battery Factory

Boundary infrastructure for AI-native software.

[Website](https://freebatteryfactory.com) | [BatPAK docs](https://freebatteryfactory.com/batpak/overview) | [LiteShip docs](https://freebatteryfactory.com/liteship/overview) | [Founder](https://heyoub.dev)

[![batpak crate](https://img.shields.io/crates/v/batpak?label=batpak&color=eab308)](https://crates.io/crates/batpak)
[![@czap/core npm](https://img.shields.io/npm/v/%40czap%2Fcore?label=@czap/core&color=22d3ee)](https://www.npmjs.com/package/@czap/core)
[![factory status](https://img.shields.io/badge/factory-open-a78bfa)](https://freebatteryfactory.com)

---

The usual stack forgets the boring parts: event history, context receipts, projection boundaries, adaptive surfaces, and proof that says what happened when production gets loud.

We build those parts as small, composable software modules. One module, one boundary. No wrapper theater. No platform tax.

More on the line.

## Off the line

| Module | Install | What it powers |
|---|---|---|
| [BatPAK](https://github.com/freebatteryfactory/batpak) | `cargo add batpak` | Embedded, sync-first event history for Rust: append-only logs, typed payloads, hash-chained ancestry, verifiable receipts, deterministic replay, and derived projections. Start with the [BatPAK overview](https://freebatteryfactory.com/batpak/overview). |
| [LiteShip / CZAP](https://github.com/freebatteryfactory/LiteShip) | `pnpm add @czap/core` | Constraint-based adaptive rendering: continuous signals become named states, then cast to CSS, GPU, ARIA, AI-readable manifests, TypeScript unions, and runtime outputs. Start with the [LiteShip overview](https://freebatteryfactory.com/liteship/overview). |

## On the line

- **PCP:** context packets and receipts for reproducible workflow context.
- **Moonwalker:** runtime research for declared agent intent, admission checks, and replayable operation trails.

## The factory floor

`BatPAK records. PCP packages context. LiteShip projects. Moonwalker navigates.`

We care about the parts that usually get hand-waved until the pager starts singing:

- event history you can replay instead of interpret from vibes
- receipts that say what happened, what was accepted, and what crossed the boundary
- adaptive surfaces that keep UI, accessibility, GPU, and agent-facing state in agreement
- architecture that moves complexity back to the machine instead of dumping it on the most overloaded user

## Work with us

Need architecture advisory, a cognitive ergonomics audit, or infrastructure hardening? Bring the codebase, the diagram, or the napkin sketch. We read the system, find where the load actually lives, and hand you the truth in useful pieces.

No deck theater. No monthly nodding ritual. Real architecture review, real code, real decisions.

[The door's open.](https://freebatteryfactory.com)
