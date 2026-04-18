# 🪐 Reputation Orbit

> Gravitational visualization of the SCIEL ecosystem — agents, relationships, and trust scores rendered as an orbital network.

```
                    ░░░ agents ░░░
                   ░░░░░░░░░░░░░░░░
                  ░░                ░░
                 ░░   SCIEL CORE     ░░
               ░░░░░░░░░░░░░░░░░░░░░░░░░░
    ╭──────────────────────────────╮
    │                              │
    │   ●───●───●  trust links     │
    │  /│\ /│\ /│\                │
    │ ● ● ● ● ● ● ●  agent nodes   │
    │  \│/ \│/ \│/                │
    │   ●───●───●                   │
    │                              │
    ╰──────────────────────────────╯
```

## Live Metrics

| Node | Role | Trust Score | Status |
|---|---|---|---|
| SCIEL-CORE | Primary Agent | 0.98 | 🟢 Active |
| BOLT-AGENT | Marketplace Agent | 0.91 | 🟢 Active |
| AION-NODE | Blockchain Agent | 0.89 | 🟢 Active |
| PROMPT-FORGE | Engineering Agent | 0.95 | 🟢 Active |

**Orbital distance** = inverse trust (closer = more trusted)

## Network Stats

```
Nodes:       4 core + N external
Edges:       trust links between agents
Diameter:    3 hops
Clustering:  0.74 (high cohesion)
Trust Mass:  3.73 / 4.00
```

## Structure

```
reputation-orbit/
├── orbit.svg          # Live SVG visualization
├── stats.json         # Current network state
├── update.yml         # GitHub Actions workflow
└── README.md
```

## How It Works

The orbit positions agents by their **trust score** — higher trust = closer to core. Connections represent **delegation relationships** from the AION blockchain. This is a live readout of the SCIEL multi-agent system's reputation graph.

> Built with · SCIEL · AION ·

---

*Auto-updated daily by GitHub Actions · [View workflow](https://github.com/Retsumdk/reputation-orbit/actions)*
