# Intent Context Envelope v0

## Status

Early sketch.

This is not a final technical standard. It is a first way to think about how Alpha-shaped parts can exchange meaning without losing human control.

The envelope should be provider-neutral.

It should be usable across models, tools, agents, deterministic services, local runtimes, and future systems.

No provider should define the envelope's meaning.

## Purpose

An Intent Context Envelope carries enough information for a person, agent, tool, artifact, or process to understand:

- what the person may mean
- what context matters
- what outcome is being shaped
- what permissions exist
- what uncertainty remains
- what should happen next

## Why This Matters

In Alpha, everything is connected.

One condition may come from many intents. Several intents may produce one outcome. One memory may change the meaning of a current action. A process may pause because it needs user input. A media artifact may activate a contextual cluster.

Without a shared envelope, parts of the system may act as if they understand each other while silently dropping context.

## Conceptual Fields

### `intent`

What the person or group appears to want, in human-readable form.

This should include confidence and room for correction.

### `context`

Relevant situation, medium, time, social setting, culture, memory, constraints, and current entry point.

Context should be scoped. Not every part needs all context.

### `outcome`

The result being shaped.

The outcome may be practical, creative, social, personal, educational, recreational, emotional, economic, or something else.

### `permissions`

What Alpha is allowed to see, remember, change, spend, share, contact, publish, or automate.

Permissions should be revocable.

### `memory`

Relevant memories or memory references.

Memory should not be treated as neutral data. It is situated life material.

### `artifacts`

Documents, images, videos, audio, messages, plans, generated interfaces, code, prototypes, or other forms involved in the current work.

Artifacts can influence clusters and future context.

### `process`

The current state of work: draft, waiting, queued, running, blocked, sleeping, completed, abandoned, or revised.

### `uncertainty`

What Alpha does not know, may have misunderstood, or should treat as ambiguous.

Uncertainty should be surfaced with care, not used as a reason to stall everything.

### `reasoning_visibility`

What reasoning can be shown by default and what can be asked for.

Alpha should be transparent, but not overwhelm people with unnecessary detail unless they ask.

### `next_step`

The smallest useful next move.

This could be asking, drafting, waiting, showing options, doing nothing, starting a process, or handing control back to the person.

## Minimal Shape

```json
{
  "intent": {
    "summary": "Human-readable intent",
    "confidence": "low | medium | high",
    "open_questions": []
  },
  "context": {
    "entry_point": "text | voice | image | document | event | artifact | other",
    "time": "optional",
    "medium_available": [],
    "relevant_constraints": []
  },
  "outcome": {
    "summary": "Human-readable desired outcome",
    "status": "exploring | proposed | agreed | shaping | completed | revised"
  },
  "permissions": {
    "allowed_actions": [],
    "requires_confirmation": [],
    "revocable": true
  },
  "memory": {
    "references": [],
    "sensitivity": "low | medium | high"
  },
  "artifacts": [],
  "process": {
    "state": "draft | waiting | queued | running | blocked | sleeping | completed | abandoned | revised",
    "needs_user_input": false
  },
  "uncertainty": [],
  "reasoning_visibility": {
    "default": "summary",
    "askable": true
  },
  "next_step": {
    "type": "ask | suggest | draft | wait | act | show_options | do_nothing",
    "summary": "Smallest useful next move"
  }
}
```

## Non-Negotiables

The envelope must not become a hidden surveillance container.

It must also not become a provider-specific payload that only one model, harness, or platform can understand.

It should support:

- data minimization
- context scoping
- permission clarity
- provider-neutral interpretation
- adapter-based execution
- reversibility
- correction
- deletion
- human override
- child safety
- no hidden persuasion
