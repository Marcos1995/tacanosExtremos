# Graph Report - tacanosExtremos  (2026-09-28)

## Corpus Check
- 12 files · ~780,751 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 3 file(s) not represented in the graph (top: .mdc 2, (none) 1)

## Summary
- 47 nodes · 35 edges · 12 communities (8 shown, 4 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `de00cb4e`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- Debug
- Contexto del proyecto
- Verify (UI)
- Web design
- Agent rules
- Laya
- Review
- Tacaños Extremos
- Tacaños Extremos
- DECISIONES.md

## God Nodes (most connected - your core abstractions)
1. `Debug` - 6 edges
2. `Contexto del proyecto` - 6 edges
3. `Verify (UI)` - 4 edges
4. `Web design` - 4 edges
5. `Laya` - 3 edges
6. `Review` - 3 edges
7. `Agent rules` - 3 edges
8. `Tacaños Extremos` - 3 edges
9. `Tacaños Extremos` - 2 edges
10. `1. Root cause` - 1 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Communities (12 total, 4 thin omitted)

### Community 0 - "Debug"
Cohesion: 0.29
Nodes (6): 1. Root cause, 2. Compare, 3. Hypothesis, 4. Fix, Debug, Red flags → back to step 1

### Community 1 - "Contexto del proyecto"
Cohesion: 0.29
Nodes (6): Comandos utiles, Contexto del proyecto, Estado, Notas para el agente, Produccion, Stack

### Community 2 - "Verify (UI)"
Cohesion: 0.40
Nodes (4): 1. Screenshots, 2. Look, 3. Fix and repeat, Verify (UI)

### Community 3 - "Web design"
Cohesion: 0.40
Nodes (4): Before HECHO, Steps, Style = `DESIGN.md`, Web design

### Community 4 - "Agent rules"
Cohesion: 0.50
Nodes (3): Agent rules, Flujo, Think → Simple → Surgical → Verify (Karpathy)

### Community 5 - "Laya"
Cohesion: 0.50
Nodes (3): Laya, Reply (decision-only requests), Steps

### Community 6 - "Review"
Cohesion: 0.50
Nodes (3): Check, Do, Review

### Community 7 - "Tacaños Extremos"
Cohesion: 0.50
Nodes (3): Agent kit, Tacaños Extremos, Verla

## Knowledge Gaps
- **26 isolated node(s):** `1. Root cause`, `2. Compare`, `3. Hypothesis`, `4. Fix`, `Red flags → back to step 1` (+21 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 38 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **4 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What connects `1. Root cause`, `2. Compare`, `3. Hypothesis` to the rest of the system?**
  _26 weakly-connected nodes found - possible documentation gaps or missing edges._