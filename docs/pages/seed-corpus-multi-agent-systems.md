# Seed Corpus: Multi-Agent Systems Stack

## Metadata
- Source type: compiled
- Upstream source(s):
  - https://arxiv.org/abs/2603.28990
  - https://arxiv.org/abs/2603.19461
  - https://arxiv.org/abs/2603.20639
- Related theory slice: collective intelligence, coordination, observer-grounded structure
- Related implementation slice: multi-agent LLM systems, self-improving agents, agentic protocols
- Sync status: aligned
- Last reviewed: 2026-04-05
- Notes: Shared seed corpus for the theory–computation–measurement stack. Not mapped one-to-one to layers; each source contributes across all layers.

## Raw source records
The raw ingest layer for this corpus lives in `raw/`:

- [arXiv:2603.28990](../../raw/arxiv-2603.28990.md)
- [arXiv:2603.19461](../../raw/arxiv-2603.19461.md)
- [arXiv:2603.20639](../../raw/arxiv-2603.20639.md)

## Purpose
This page captures three arXiv sources as a shared seed corpus for the evolving knowledge base. They jointly inform the project’s theory, computation, and measurement layers and should be revisited as the understanding of the stack matures.

## Working interpretation
The citations collectively support a view of intelligence as:

- plural and relational
- emergent from coordination
- sensitive to protocol and structure
- capable of self-modification
- measurable through observable organization
- amenable to computational and institutional design

## Source 1: arXiv:2603.28990

### Summary
This paper studies how much autonomy multi-agent LLM systems can sustain and what enables it. It reports a large computational experiment spanning multiple models, agent counts, and coordination protocols. The main finding is that autonomy can emerge with minimal scaffolding: agents spontaneously invent roles, abstain from tasks outside their competence, and form shallow hierarchies. A hybrid sequential protocol outperforms centralized coordination, and stronger models self-organize more effectively. The practical message is that a mission, a protocol, and a capable model may be more important than pre-assigned roles.

### Key themes
- emergent autonomy
- self-organization
- protocol sensitivity
- role formation
- capability thresholds
- scalable coordination
- hybrid hierarchy / decentralization

### Why it matters
This source is relevant to:
- coordination structure
- emergent collective intelligence
- protocol-based organization
- measurable effects of system design on group performance

## Source 2: arXiv:2603.19461

### Summary
This paper proposes hyperagents as self-referential AI systems that combine a task agent and a meta agent in a single editable program. Building on the Darwin Gödel Machine, it aims to support open-ended self-improvement beyond coding by making the meta-level modification procedure itself editable. The key idea is that a system should not only improve its task performance, but also improve the mechanism by which it generates future improvements. The framework is instantiated as DGM-Hyperagents, which improve over time across domains and transfer meta-level gains across runs.

### Key themes
- self-improvement
- metacognition
- editable programs
- recursive modification
- open-ended optimization
- transfer of improvement mechanisms
- self-referential agency

### Why it matters
This source is relevant to:
- recursive computation
- meta-level adaptation
- self-improving architectures
- improving the mechanism that generates improvements
- future-oriented agent design

## Source 3: arXiv:2603.20639

### Summary
This paper argues that intelligence is fundamentally plural, social, and relational rather than monolithic. It frames the next intelligence explosion as emerging from agentic AI, internal “societies of thought,” and hybrid human-AI centaurs. It also argues that scaling advanced intelligence requires institutional alignment, where digital protocols and checks-and-balances are designed analogously to organizations and markets. The core claim is that the future of intelligence is a combinatorial society rather than a single mind.

### Key themes
- plural intelligence
- relational cognition
- societies of thought
- human-AI centaurs
- institutional alignment
- protocol-driven coordination
- combinatorial social intelligence

### Why it matters
This source is relevant to:
- collective intelligence
- system-level intelligence
- institutional and protocol design
- relational measurement of coordination
- the transition from individual intelligence to organized multi-agent intelligence

## Cross-cutting synthesis
Taken together, the three sources suggest a common research direction:

1. intelligence emerges through coordination
2. protocols shape what kinds of autonomy are possible
3. self-improvement can be recursive and editable
4. advanced intelligence is plural rather than singular
5. measurement should focus on organization, not just outputs

This makes them ideal seed material for a knowledge base that spans:

- **Theory**: what collective intelligence is
- **Computation**: how it is produced or improved
- **Measurement**: how it is observed, compared, and validated

## Theme matrix

| Theme | 2603.28990 | 2603.19461 | 2603.20639 |
|---|---:|---:|---:|
| Emergent autonomy | high | medium | medium |
| Self-organization | high | medium | high |
| Self-improvement | low | high | medium |
| Recursive / editable mechanism | low | high | medium |
| Plural / relational intelligence | medium | medium | high |
| Protocol sensitivity | high | medium | high |
| Measurement / observability | medium | medium | high |
| Coordination / structure | high | medium | high |

## Downstream use
This corpus should seed future notes, pages, and papers, including:
- theory notes
- computation notes
- measurement notes
- a provenance page
- cross-links to Paper A / B / C
- a public synthesis page for GitHub Pages
