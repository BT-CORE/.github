# BT CORE

> **Built from experience. Designed as one ecosystem. Made for Open2077.**

## Documentation

### [Open the official BT CORE documentation →](https://botilus.mintlify.io/en)

Installation, configuration, client and server APIs, complete contracts, and
the evolving resource catalog are maintained in the official documentation.

## Contents

- [What is BT CORE?](#what-is-bt-core)
- [Maintained by Botilus](#maintained-by-botilus)
- [From CFX to Open2077](#from-cfx-to-open2077)
- [What we are building](#what-we-are-building)
- [Resources](#resources)
- [Principles](#principles)
- [Project status](#project-status)

## What is BT CORE?

**BT CORE is a core framework and collection of roleplay resources created by
Botilus for [Open2077](https://open2077.net/).**

The project brings systems, ideas, and workflows originally designed through
years of CFX development into a single modular foundation for Open2077. It is
not a loose catalog of unrelated scripts and not a blind one-to-one port. Each
resource is being reconsidered for a new platform, a consistent API, and a
better experience for both server owners and developers.

> [!IMPORTANT]
> BT CORE is under active development. APIs and resources may evolve while the
> foundation is tested against real use cases and the Open2077 platform grows.

## Maintained by Botilus

BT CORE is created and maintained by **Botilus**, who has worked in the CFX
ecosystem since 2015 and contributed to many roleplay servers across different
teams, architectures, and production constraints.

That background includes roughly forty Git repositories and around 300 scripts
written by hand, including more than 40 RedM resources created between 2019 and
2020. This work predates the use of generative AI in the development workflow.

These figures are included only to explain where BT CORE comes from. They are
not a substitute for quality: the project must earn trust through clear code,
reliable behavior, useful documentation, and long-term maintenance.

## From CFX to Open2077

BT CORE is the next step for systems Botilus originally designed throughout
that CFX journey. The goal is to convert the strongest ideas into native
Open2077 resources while improving the parts that experience has shown can be
clearer, safer, and easier to maintain.

That conversion means more than translating APIs. It means:

- revisiting contracts instead of preserving accidental legacy behavior;
- adapting architecture and lifecycle rules to Open2077;
- turning isolated scripts into compatible modules built around one core;
- applying lessons learned from years of real roleplay development;
- documenting public behavior so users do not need to reverse-engineer code;
- building a foundation that can evolve without becoming a patchwork.

Modern tools can accelerate this work, but they do not replace the experience
behind the decisions. Every public contract remains something the project must
understand, test, document, and maintain.

## What we are building

BT CORE aims to provide one coherent ecosystem rather than another collection
of scripts that happen to share a prefix.

The project is built around:

- a central core for shared character, identity, state, and persistence logic;
- modular resources that can be installed and evolved independently;
- predictable client and server exports with explicit contracts;
- consistent configuration, permissions, errors, and lifecycle behavior;
- practical documentation with executable examples;
- resources shaped by real server needs rather than showcase-only features;
- a testing ground that can also help improve the Open2077 ecosystem.

The long-term objective is simple: bring together accumulated experience,
knowledge, and technical standards in a core that feels designed as one system
from the beginning.

## Resources

This overview follows the public roadmap. `Preview` and `pre-release` resources
are still evolving and may not yet be available as stable downloads. The
[official documentation](https://botilus.mintlify.io/en) remains the source of
truth for versions, installation, configuration, and APIs.

### Foundation

| Resource | Status | Main capabilities |
| :--- | :--- | :--- |
| `bt_core` | Preview `0.8.5` | Character identity, persistence, economy, jobs, vehicles, access control, and shared contracts. |
| `bt_inventory` | Preview `0.1.0` | Authoritative inventories, items, weapons, slots, registered containers, and drag-and-drop UI. |
| `bt_lib` | Preview `0.1.0` | Shared client and server helpers for entities, vectors, WebUI, and readiness. |

### Gameplay

| Resource | Status | Main capabilities |
| :--- | :--- | :--- |
| `bt_bank` | Pre-release | Bank accounts, deposits, withdrawals, transfers, and ATMs. |
| `bt_cardealer` | Pre-release | Dealership catalogs, purchases, demonstration vehicles, and test drives. |
| `bt_faction` | Pre-release | Factions, members, ranks, permissions, and shared treasuries. |
| `bt_housing` | Pre-release | Purchasable properties, residents, access rules, and instanced interiors. |
| `bt_phone` | Pre-release | Calls, contacts, messages, news, and player portraits. |
| `bt_shop` | Pre-release | Configurable item stores with server-authoritative purchases and sales. |
| `bt_taxi` | Pre-release | Delamain taxi requests, destinations, pricing, and driving. |
| `bt_traffic` | Pre-release | Ambient vehicle and pedestrian traffic distributed by cells and instances. |

### Platform and interface

| Resource | Status | Main capabilities |
| :--- | :--- | :--- |
| `bt_admin` | Preview `1.1.0` | ACL-protected administration, moderation, player support, world tools, and development utilities. |
| `bt_interaction` | Pre-release | World interaction prompts and consistent WebUI choices. |
| `bt_nuiprotect` | Pre-release | Heuristic WebUI developer-tools detection with configurable enforcement. |
| `bt_radial` | Preview `0.2.1` | Responsive equipped-weapon and service radial with role-aware access to administration tools. |

## Principles

| Principle | Commitment |
| :--- | :--- |
| **Experience** | Turn a decade of hands-on roleplay development into practical decisions. |
| **Cohesion** | Design the core and its resources as one ecosystem with shared conventions. |
| **Quality** | Favor readable, testable, maintainable code over disposable releases. |
| **Clear contracts** | Document inputs, outputs, failures, permissions, and lifecycle expectations. |
| **Honest tooling** | Use modern tools transparently while keeping human ownership of every result. |
| **Evolution** | Improve systems when evidence demands it without abandoning stability or users. |

## Project status

BT CORE is being built and validated alongside Open2077. Resources are released
when their runtime behavior, public contracts, and documentation are ready to
be used—not simply when a prototype looks convincing.

The [official documentation](https://botilus.mintlify.io/en) is the source of
truth for available resources, installation instructions, configuration, and
public APIs.

> **Built from experience. Reworked for a new platform.**
>
> One core, one ecosystem, and years of knowledge brought together.
