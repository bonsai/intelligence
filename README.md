# intelligence

Ontology for defining intelligence independently of any model, agent, or tool.

## Definition

**Intelligence is the capacity to observe state, transform information into knowledge, discover relations, manage uncertainty, choose actions toward goals, act, learn from feedback, and improve subsequent decisions.**

LLM is not intelligence itself. It is one possible capability provider inside the intelligence system.

## Core loop

```text
PERCEIVE → KNOW → RELATE → REASON → DECIDE → ACT → FEEDBACK → LEARN
                                      ↑                         │
                                      └─────────────────────────┘
```

## Architecture

```text
Intelligence Ontology
        ↓
Agent Ontology
        ↓
Task Ontology
        ↓
Workflow Ontology
        ↓
Tools / gh-aw
```

`bonsai/archimedes` is an implementation of an intelligent architect on top of this ontology.

## Principles

- Intelligence is a system capability, not a model name.
- Evidence and uncertainty are first-class.
- Memory is distinct from knowledge.
- Reasoning is distinct from action.
- Learning requires feedback.
- Agency requires goals and action selection.
- LLMs are optional capability providers.

## Repository structure

- `ontology/` — semantic definitions
- `schema/` — machine-readable contracts
- `docs/` — explanatory model

