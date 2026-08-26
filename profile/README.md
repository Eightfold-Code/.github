# Eightfold

**Composable AI infrastructure built around adaptation.**

Eightfold explores a simple premise: everything should be a module, and every module should be replaceable.

We are building an AI system that can evolve through small, inspectable, reproducible components instead of one permanently fixed application.

## The three layers

| Layer | Repository | Purpose |
| --- | --- | --- |
| Runtime | [eightfold-harness](https://github.com/Eightfold-Code/eightfold-harness) | Runs sessions, profiles, tools, models, and plugins |
| Capabilities | [eightfold-treasury](https://github.com/Eightfold-Code/eightfold-treasury) | Catalogs and distributes installable adaptations |
| Presentation | [eightfold-armoury](https://github.com/Eightfold-Code/eightfold-armoury) | Catalogs and distributes visual skins and themes |

~~~text
Armoury  →  presentation
Treasury →  capabilities
Harness  →  runtime
~~~

Harness is the engine. Treasury is the catalog. Adaptations are the system.

## Why this structure?

- **Modular by default** — capabilities remain replaceable.
- **Native over parallel** — use the Harness and Cordis lifecycle.
- **Reproducible** — published components resolve to exact Git commits.
- **Composable** — profiles combine capabilities and presentation independently.
- **Inspectable** — manifests describe compatibility, entry points, and permissions.
- **Small by design** — install one component without cloning every component.

## How it works

1. Harness provides the runtime and profile lifecycle.
2. Treasury publishes adaptations such as tools, integrations, and workflows.
3. Armoury publishes presentation-only skins and themes.
4. Profiles select the capabilities and visual layer they need.

The result is an adaptable foundation that can change without turning every feature into a permanent core dependency.

## Status

Eightfold is an active developer preview. Interfaces, registry formats, and installation commands are evolving as the foundation is stabilized.

## Explore

- [Eightfold Harness](https://github.com/Eightfold-Code/eightfold-harness)
- [Eightfold Treasury](https://github.com/Eightfold-Code/eightfold-treasury)
- [Eightfold Armoury](https://github.com/Eightfold-Code/eightfold-armoury)
