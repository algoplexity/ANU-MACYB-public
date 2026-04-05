# Paper B — Computation

## Metadata
- Source type: computation note
- Related stream: multi-agent systems
- Status: draft
- Scope: computational realization of observer-grounded collective intelligence
- Dependencies: Paper A, seed corpus on multi-agent systems
- Last reviewed: 2026-04-05

## Overview
This page describes how the theory of observer-grounded collective intelligence can be operationalized in computation. The focus is on mechanisms that produce, sustain, and adapt collective behavior across multiple agents.

## Core thesis
If collective intelligence is relational and protocol-sensitive, then the computational problem is not only to build better agents, but to build better systems of interaction among agents.

The relevant object of design is the collective process: how information flows, how roles emerge, how decisions are coordinated, and how the system updates itself over time.

## Computational goals
The system should support:

- distributed task allocation
- adaptive communication
- role discovery
- coordination under partial information
- robust collective response to change
- recursive improvement of the coordination mechanism itself

## Design principles

### 1. Minimal scaffolding
Use the smallest coordination structure that still allows useful collective behavior to emerge.

### 2. Protocol sensitivity
Treat the interaction protocol as a first-class computational object.

### 3. Role emergence
Allow roles to appear dynamically rather than assigning them all in advance.

### 4. Local competence
Let agents abstain from tasks outside their local competence.

### 5. Meta-level adaptation
Support improvement of the coordination procedure, not just the task procedure.

## Canonical computational stack
A practical implementation can be decomposed into:

### Agent layer
Individual agents perform local reasoning, planning, and action.

### Interaction layer
Agents exchange messages, proposals, acknowledgements, and task updates.

### Protocol layer
The protocol defines when agents speak, how they negotiate, and how decisions are committed.

### Meta-control layer
A higher-order process monitors performance and updates the protocol or agent roles over time.

## Computational patterns

### Sequential hybrid coordination
A sequence of local and centralized steps can outperform either extreme alone.

### Emergent division of labor
Agents naturally specialize when the task is complex and the protocol permits specialization.

### Abstention and delegation
Agents should be able to defer, delegate, or decline when confidence is low.

### Recursive improvement
The system should be able to modify the rules that govern its own improvement loop.

## Relation to the seed corpus
The seed corpus suggests three computational implications:

1. **Autonomy is achievable with minimal structure**  
   Systems do not necessarily require rigid role assignment.

2. **Better protocols improve group performance**  
   The coordination mechanism matters as much as the model capability.

3. **Self-improvement can be meta-level**  
   Improvement procedures can themselves be edited and transferred.

These implications motivate a computational architecture that treats interaction structure as a core design variable.

## Implementation considerations
- communication overhead
- role instability
- coordination latency
- task decomposition quality
- fault tolerance
- observability of internal state
- safety constraints on self-modification

## Evaluation targets
The computational system should be evaluated on:

- task success rate
- coordination efficiency
- adaptation speed
- robustness to perturbation
- role stability and flexibility
- improvement over repeated runs

## Links
- [Seed Corpus: Multi-Agent Systems Stack](./seed-corpus-multi-agent-systems.md)
- [Multi-Agent Systems](./multi-agent-systems.md)
- [Paper A — Minimal Unified Theory of Observer-Grounded Collective Intelligence](./paper-a-theory.md)
- [Paper C — Measurement](./paper-c-measurement.md)

## Status
Draft computation note. Expand with implementation details and experiment results as they mature.
