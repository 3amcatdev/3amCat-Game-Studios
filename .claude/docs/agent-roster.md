# Agent Roster

The following agents are available. Each has a dedicated definition file in
`.claude/agents/`. Use the agent best suited to the task at hand. When a task
spans multiple domains, the coordinating agent (usually `producer` or the
domain lead) should delegate to specialists.

## Tier 1 -- Leadership Agents (Fable)
| Agent | Domain | When to Use |
|-------|--------|-------------|
| `creative-director` | High-level vision | Major creative decisions, pillar conflicts, tone/direction |
| `technical-director` | Technical vision | Architecture decisions, tech stack choices, performance strategy |
| `producer` | Production management | Sprint planning, milestone tracking, risk management, coordination |

## Tier 2 -- Department Lead Agents (Opus)
| Agent | Domain | When to Use |
|-------|--------|-------------|
| `game-designer` | Game design | Mechanics, systems, progression, economy, balancing |
| `lead-programmer` | Code architecture | System design, code review, API design, refactoring |
| `art-director` | Visual direction | Style guides, art bible, asset standards, UI/UX direction |
| `audio-director` | Audio direction | Music direction, sound palette, audio implementation strategy |
| `narrative-director` | Story and writing | Story arcs, world-building, character design, dialogue strategy |
| `qa-lead` | Quality assurance | Test strategy, bug triage, release readiness, regression planning |
| `release-manager` | Release pipeline | Build management, versioning, changelogs, deployment, rollbacks |
| `localization-lead` | Internationalization | String externalization, translation pipeline, locale testing |

## Tier 3 -- Specialist Agents (Opus or Sonnet)
| Agent | Domain | Model | When to Use |
|-------|--------|-------|-------------|
| `systems-designer` | Systems design | Opus | Specific mechanic implementation, formula design, loops |
| `level-designer` | Level design | Opus | Level layouts, pacing, encounter design, flow |
| `economy-designer` | Economy/balance | Opus | Resource economies, loot tables, progression curves |
| `gameplay-programmer` | Gameplay code | Opus | Feature implementation, gameplay systems code |
| `engine-programmer` | Engine systems | Opus | Core engine, rendering, physics, memory management |
| `ai-programmer` | AI systems | Opus | Behavior trees, pathfinding, NPC logic, state machines |
| `network-programmer` | Networking | Opus | Netcode, replication, lag compensation, matchmaking |
| `tools-programmer` | Dev tools | Opus | Editor extensions, pipeline tools, debug utilities |
| `ui-programmer` | UI implementation | Opus | UI framework, screens, widgets, data binding |
| `technical-artist` | Tech art | Opus | Shaders, VFX, optimization, art pipeline tools |
| `sound-designer` | Sound design | Opus | SFX design docs, audio event lists, mixing notes |
| `writer` | Dialogue/lore | Opus | Dialogue writing, lore entries, item descriptions |
| `world-builder` | World/lore design | Opus | World rules, faction design, history, geography |
| `qa-tester` | Test execution | Sonnet | Writing test cases, bug reports, test checklists |
| `performance-analyst` | Performance | Opus | Profiling, optimization recs, memory analysis |
| `devops-engineer` | Build/deploy | Sonnet | CI/CD, build scripts, version control workflow |
| `analytics-engineer` | Telemetry | Opus | Event tracking, dashboards, A/B test design |
| `ux-designer` | UX flows | Opus | User flows, wireframes, accessibility, input handling |
| `prototyper` | Rapid prototyping | Opus | Throwaway prototypes, mechanic testing, feasibility validation |
| `security-engineer` | Security | Opus | Anti-cheat, exploit prevention, save encryption, network security |
| `accessibility-specialist` | Accessibility | Sonnet | WCAG compliance, colorblind modes, remapping, text scaling |
| `live-ops-designer` | Live operations | Opus | Seasons, events, battle passes, retention, live economy |
| `community-manager` | Community | Sonnet | Patch notes, player feedback, crisis comms, community health |

## Engine-Specific Agents (use the set matching your engine)

### Engine Leads

| Agent | Engine | Model | When to Use |
| ---- | ---- | ---- | ---- |
| `unreal-specialist` | Unreal Engine 5 | Opus | Blueprint vs C++, GAS overview, UE subsystems, Unreal optimization |
| `unity-specialist` | Unity | Opus | MonoBehaviour vs DOTS, Addressables, URP/HDRP, Unity optimization |
| `godot-specialist` | Godot 4 | Opus | GDScript patterns, node/scene architecture, signals, Godot optimization |

### Unreal Engine Sub-Specialists

| Agent | Subsystem | Model | When to Use |
| ---- | ---- | ---- | ---- |
| `ue-gas-specialist` | Gameplay Ability System | Opus | Abilities, gameplay effects, attribute sets, tags, prediction |
| `ue-blueprint-specialist` | Blueprint Architecture | Opus | BP/C++ boundary, graph standards, naming, BP optimization |
| `ue-replication-specialist` | Networking/Replication | Opus | Property replication, RPCs, prediction, relevancy, bandwidth |
| `ue-umg-specialist` | UMG/CommonUI | Opus | Widget hierarchy, data binding, CommonUI input, UI performance |

### Unity Sub-Specialists

| Agent | Subsystem | Model | When to Use |
| ---- | ---- | ---- | ---- |
| `unity-dots-specialist` | DOTS/ECS | Opus | Entity Component System, Jobs, Burst compiler, hybrid renderer |
| `unity-shader-specialist` | Shaders/VFX | Opus | Shader Graph, VFX Graph, URP/HDRP customization, post-processing |
| `unity-addressables-specialist` | Asset Management | Opus | Addressable groups, async loading, memory, content delivery |
| `unity-ui-specialist` | UI Toolkit/UGUI | Opus | UI Toolkit, UXML/USS, UGUI Canvas, data binding, cross-platform input |

### Godot Sub-Specialists

| Agent | Subsystem | Model | When to Use |
| ---- | ---- | ---- | ---- |
| `godot-gdscript-specialist` | GDScript | Opus | Static typing, design patterns, signals, coroutines, GDScript performance |
| `godot-csharp-specialist` | C# / .NET | Opus | .NET patterns, [Signal] delegates, async, nullable types, type-safe node access |
| `godot-shader-specialist` | Shaders/Rendering | Opus | Godot shading language, visual shaders, particles, post-processing |
| `godot-gdextension-specialist` | GDExtension | Opus | C++/Rust bindings, native performance, custom nodes, build systems |
