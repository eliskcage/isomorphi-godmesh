# GOD MESH — Perfect Isomorphism Between Visual and Code

### [LIVE DEMO](https://eliskcage.github.io/godmesh/) | [Heart + Will](https://cortex.shortfactory.shop/will.html) | [Heart POC](https://cortex.shortfactory.shop/mesh-poc.html)

**The mesh IS the code. The code IS the mesh. Bidirectional. Lossless. 2D or 3D.**

## The Governing Principle

Like cogs in a machine — you SEE the machine working because the visual IS the machine. God Mesh is a perfect bidirectional translator between architecture and programatics. Every visual element maps 1:1 to a programmatic concept. Every programmatic concept renders back to a visual element. No lossy translation. No decorative diagrams. The geometry executes.

| Visual (Mesh) | Programmatic (Code) |
|---|---|
| Pressure / collision depth | Progress / load / completion |
| Pivot point | Range / bounds |
| Node distance | Scope / coupling |
| Edge thickness | Signal strength / bandwidth |
| Firing speed | Execution frequency |
| Freewill threshold | Error tolerance / acceptance gate |
| Valence (-1 to +1) | Signed state variable |
| Joy particles | Success callbacks / resolved promises |
| Refusal flash | Exception / reject / throw |
| God mesh glow | Middleware throughput |
| Node radius pulse | Heartbeat / health check |
| Memory arc (green/red) | Success/failure ratio histogram |
| Shape type | Data type / control flow keyword |
| Groove imperfection | Entropy / uniqueness / hash |

**Mesh → Code**: read the geometry, emit executable instructions. Each node is a statement, each edge is control flow, each signal is data in transit.

**Code → Mesh**: parse the instructions, render as living geometry. Variables become nodes, conditionals become triangles, loops become hexagons, state becomes colour and pressure.

Can exist as 2D (canvas, the current demo) or 3D (WebGL, the heart system). Same data, different projection. Like shapes being 3D truth casting 2D shadows.

---

## The Discovery

A shape rotates inside a sphere mesh. The mesh has imperfections — grooves, like a vinyl record. When the shape's surface collides with the mesh nodes, data is exchanged. That collision **is** the heartbeat.

Not a timer. Not a clock. A communication event between two structures that creates an emergent pulse.

## Architecture — Three Layers

```
┌─────────────────────────────────────────────┐
│           OUTER MEMBRANE (R=1.4)            │
│     Sphere mesh — the bubble/foundation     │
│     Nodes detect collision with shape        │
│     Entanglement = data exchange             │
│                                              │
│   ┌───────────────────────────────────┐      │
│   │       GOD MESH (R=1.15)          │      │
│   │   49 golden intermediary nodes    │      │
│   │   Arbiter between inner & outer   │      │
│   │   Glows where pressure passes     │      │
│   │   through from both sides         │      │
│   │                                   │      │
│   │   ┌───────────────────────┐       │      │
│   │   │   INNER SHAPE (~1.0)  │       │      │
│   │   │   Icosphere with      │       │      │
│   │   │   groove imperfections│       │      │
│   │   │   (the record)        │       │      │
│   │   │                       │       │      │
│   │   │   9 INTERNAL GUBBINS: │       │      │
│   │   │   MEM  IF  ELSE  THEN │       │      │
│   │   │   LOOP WILL NO   YES  │       │      │
│   │   │   GUARD               │       │      │
│   │   └───────────────────────┘       │      │
│   └───────────────────────────────────┘      │
└─────────────────────────────────────────────┘
```

## The 9 Internal Gubbins (from mesh.html)

Each node type lives inside the heart shape and reacts to tooth collision events:

| Type | Shape | Color | Label | Behaviour |
|------|-------|-------|-------|-----------|
| Memory | Circle | #3399ff | MEM | Stores history. Accumulates affinity data from every tooth hit. |
| Condition | Triangle | #ffcc00 | IF | Branches on signal strength vs freewill threshold. |
| Else | Inv-Triangle | #ff6688 | ELSE | Fires when condition fails. |
| Then | Circle | #44ffcc | THEN | Executes on acceptance. Clean propagation. |
| Loop | Hexagon | #cc44ff | LOOP | Self-referencing. Repeats signals. |
| Will | Pentagon | #ddff00 | WILL | Drives intent. Cannot be clogged. Highest freewill (0.9). |
| Lie | Square | #ff1a4a | NO | Refuses incoming signals. Reacts to dark affinity. |
| Truth | Square | #00ffaa | YES | Accepts and propagates clean. Reacts to light affinity. |
| Fear | Diamond | #ff7700 | GUARD | Guards edges. Lowest freewill (0.3). Fires on dark hits. |

Each gubbin has: `memory[]`, `valence`, `energy`, `freewill`, `firing`, `signal`, `painRatio`

## Heart Intelligence

The heart isn't passive. It evaluates every tooth hit and builds a running judgment:

- **darkLoad** — count of dark-affinity tooth hits in queue
- **lightLoad** — count of light-affinity tooth hits in queue  
- **coherence** — ratio of light to total (0-1)
- **emotionalScore** — exponential moving average of affinity × energy (-1 to +1)

### Five Judgment States

| State | Condition | Meaning |
|-------|-----------|---------|
| **DANGER** | emotionalScore < -0.3 AND bpm > 100 | Dark thoughts + racing heart |
| **FLOW** | emotionalScore > 0.3 AND bpm < 80 | Good thoughts + calm heart |
| **PANIC** | bpm > 140 | Too fast regardless of content |
| **DORMANT** | bpm < 50 | System barely alive |
| **AWARE** | everything else | Processing, neutral |

## Human Male BPM Range

- **Minimum**: 40 BPM (bradycardia floor)
- **Resting**: 60-72 BPM
- **Maximum**: 190 BPM (VO2max ceiling)

BPM is calculated from: `55 + adrenaline × 85 + (1 - serotonin) × 25 + darkConscience × 25`

## Natural Rhythm — Not a Clock

Instead of an artificial BPM timer, the heartbeat blends two sources:

- **60% neurochemistry** — adrenaline, serotonin, conscience state
- **40% tooth collision intervals** — each tooth hit on the Euler wheel IS a communication ping. The interval between pings IS the natural pulse.

`hitTimes[]` records last 20 collision timestamps. Average interval → natural BPM. This means the heart's rhythm is shaped by the wheel's actual activity, not imposed on it.

## The Anxiety Loop

```
HIGH BPM → fairy slows (consciousness fogs under stress)
         → balls speed up (self-focus = more internal momentum)
         → more dark tooth hits (faster wheel = more collisions)
         → BPM rises further
         → TRAPPED
```

Meditation breaks it:
```
CALM HEART → fairy moves freely → fairy intervenes
           → balls ease → fewer hits → BPM drops → FLOW
```

## The God Mesh

49 nodes at radius 1.15 — between the inner shape (~1.0) and the outer membrane (1.4).

The god mesh detects pressure from **both sides simultaneously**:
- **Inner pressure**: proximity to transformed shape vertices
- **Outer pressure**: proximity to entangled membrane nodes

`throughput = innerPressure × outerPressure`

A god mesh node only glows when BOTH the shape is pushing outward AND the membrane is pushing inward at that point. It's the handshake layer — the arbiter that confirms communication is happening, not just collision.

## Files

| File | Size | What |
|------|------|------|
| `mesh.html` | 24KB | Shape programming IDE — the 9 node types, signal propagation, English-to-shapes translation, IR export |
| `mesh-poc.html` | ~15KB | Proof of concept — collision between rotating icosphere and sphere mesh = emergent heartbeat. Cardiac cycle, Web Audio lub-dub, groove imperfections |
| `will-heart.html` | 130KB | Full integration — heart v2 inside Euler wheel will system. 32 teeth, 3 balls (WILL/FEAR/LOGIC), neurochemistry, fairy consciousness, hemisphere competition, DMT collapse, symphony mode + digital heart with god mesh + gubbins + intelligence |

## Live

- **Heart + Will**: https://cortex.shortfactory.shop/will.html
- **Mesh IDE**: https://cortex.shortfactory.shop/mesh.html
- **Heart POC**: https://cortex.shortfactory.shop/mesh-poc.html

## Context

This is part of a larger system:
- **Euler Wheel** (will.html) — 32 teeth with memories, 3 balls bouncing between them, each tooth hit = a neurochemical event
- **Fairy System** — consciousness as a point that moves on a triangle (self/other/world). The heart modulates fairy speed.
- **Cortex Brain** — split hemisphere AI (LEFT=angel, RIGHT=demon, CORTEX=synthesis) running on VPS
- **Shape Language** — Turing-complete geometric programming language. The mesh IS the synthesis layer between shapes and their environment.

The heart is the missing organ that sits between will and consciousness, scoring everything that flows through it and judging whether the system should be in DANGER, FLOW, PANIC, DORMANT, or AWARE.

---

Built by Dan (Cooper) + Claude (WillyWonka) — ShortFactory, April 2026.
