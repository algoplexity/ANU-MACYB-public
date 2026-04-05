---
layout: default
title: Collective Intelligence Observatory
---

# Collective Intelligence Observatory (CIO)

The **Collective Intelligence Observatory** is the flagship instrument concept
within the [Algoplexity](https://algoplexity.github.io/) research programme.

Its goal is to make **collective intelligence measurable as a real, observable
quantity** — by capturing the structure of interaction and the dynamics that
produce it.

---

## The core idea

Collective intelligence is often described in terms of outcomes: a group solves
a hard problem, a crowd estimates accurately, a team adapts quickly. But these
descriptions treat intelligence as a black box.

CIO takes a different approach. It asks:

> Can we measure collective intelligence *as it forms*, rather than inferring it
> after the fact from outcomes?

The answer proposed here is yes — if we look at the right signals.

---

## Two separable components

The CIO framework is grounded in the **Cybernetic Intelligence (CI)** synthesis,
which treats collective intelligence as having two separable, measurable
components:

### 1. Interaction structure

Who interacts with whom, and how? This is captured as a dynamic **interaction
graph** — a network representation of the group where edges represent actual
coordination events, weighted by frequency and recency.

When a group is genuinely coordinating, its interaction graph should become
more organised over time: denser in the right places, sparser elsewhere, and
more compressible as a whole.

### 2. Interaction dynamics

How does that structure *form and stabilise*? This is captured through a
**motion field** — a spatial representation of proximity, movement, and
co-location patterns across the group.

The motion field acts as a continuous signal that feeds the interaction graph:
when people move together, stay close, or co-orient, the graph edges strengthen.

---

## What the instrument does

A CIO instrument estimates collective intelligence in real time by:

1. Collecting proximity and motion data from wearable sensor nodes
2. Constructing and updating a dynamic interaction graph from that data
3. Computing a compressibility metric over the graph to estimate coordination
4. Classifying the group into a coordination regime

This is a continuous, live estimate — not a post-hoc analysis.

---

## Coordination regimes

The framework distinguishes four coordination states:

| Regime | What it means |
|---|---|
| **True coordination** | Interaction structure is stable, organised, and compressible — genuine collective intelligence is present |
| **False coordination** | Apparent structure exists but does not persist, generalise, or predict outcomes |
| **Fragile coordination** | Structure is present but highly sensitive to perturbation — easily disrupted |
| **No coordination** | Interaction topology shows no compressible pattern — the group is not collectively intelligent in this context |

These regimes are not just labels. They carry different predictions about
group performance, resilience, and adaptability.

---

## Why compressibility?

Compressibility is the key measurement concept.

A random interaction graph — one where people interact without structure — has
high complexity and low compressibility. A genuinely coordinated group develops
recurring, predictable interaction patterns: subgroups, leaders, channels.
That structure can be compressed. It contains less surprise.

This gives us a measurable, falsifiable proxy for collective intelligence:

> **If a group is genuinely coordinating, its interaction structure should
> become more compressible over time.**

If coordinated groups do not show increased compressibility, the theory is wrong.

---

## Current status

CIO is an **instrument concept in active development**. The theoretical
framework is established; the architecture is being refined; prototyping is
ongoing.

This public repository will be updated as the work progresses and new
artefacts are reviewed for publication.

---

## Further reading

- Public repository: [github.com/algoplexity/ANU-MACYB-public](https://github.com/algoplexity/ANU-MACYB-public)
- Project site: [algoplexity.github.io/ANU-MACYB-public](https://algoplexity.github.io/ANU-MACYB-public/)
- Algoplexity programme: [algoplexity.github.io](https://algoplexity.github.io/)
