# Mapped Assembly

**Open tools for designing hardware, understanding how it moves, and planning where it works.**

Mapped Assembly builds open-source software for the path from an idea to a physical system. Our projects connect agent-assisted hardware design, programmable CAD, spatial planning, and evidence-aware manufacturing workflows without hiding the underlying models or artifacts.

## Projects

| Project | What it does |
| --- | --- |
| [Forma](https://github.com/Mapped-Assembly/forma-oss) | Turns design requirements into inspectable CAD, wiring, bills of materials, and assembly instructions. |
| [OpenCAD](https://github.com/Mapped-Assembly/Open-CAD) | Provides a modular toolkit for parametric, programmable, and agent-assisted CAD. |
| [OpenIndustries](https://github.com/Mapped-Assembly/Open-Industries) | Places hardware in a browser-based 3D workspace for layout, motion, and workflow review. |
| [CleanRoomOS](https://github.com/Mapped-Assembly/CleanRoomOS) | Demonstrates validated, human-gated planning and evidence workflows for cleanroom sampling. |
| [nano-tech-harness](https://github.com/Mapped-Assembly/nano-tech-harness) | Explores reproducible molecular visualization and evidence-backed materials research workflows. |

## How the pieces fit

```text
requirements -> structured design -> CAD artifacts -> spatial review -> validated operation
                    Forma             OpenCAD       OpenIndustries     CleanRoomOS
```

Each layer is useful on its own. Together, they explore a more open engineering stack in which agents propose work, deterministic tools build and validate artifacts, and people retain control over consequential decisions.

## What we value

- **Inspectable artifacts:** designs should be exportable, reviewable, and useful outside a single application.
- **Deterministic boundaries:** agents assist with intent and iteration; typed contracts and validators protect critical facts.
- **Human authority:** simulation, generation, and automated checks support engineering judgment rather than replace it.
- **Open interfaces:** local workflows, documented formats, CLIs, and MCP tools make projects easier to extend and combine.

## Build with us

The projects are early and evolving. Start with the README and contribution guide in the repository that interests you, try a workflow, or open an issue with a concrete use case. Bug reports, reproducible examples, documentation improvements, and focused pull requests are welcome.

> Generated designs, simulations, and research outputs require independent engineering or scientific review before real-world use.
