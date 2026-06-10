# Alpha Agent Operating Map

Last updated: 2026-06-10

Read this file first. It is the compact operating map for AI agents working on Alpha.

Keep it high signal. Detailed concept work belongs in the linked docs.

Repository language is English only for code, comments, docs, configs, prompts, examples, generated text, and agent-facing instructions. Users may direct agents in other languages, but repository artifacts stay English.

## North Star

Alpha helps people shape life with care.

Current core language:

> Shape life your way, with care.

Current conceptual definition:

> Alpha is accountable mediation between what people mean and what their world around them can become.

Alpha is not primarily an app, assistant, OS, chatbot, social network, productivity tool, marketplace, protocol, or model wrapper.

Those forms may appear inside Alpha.

They are not Alpha.

## Current Constitutional Laws

These rules are always in force when shaping Alpha.

### 1. Protocol-Native And Provider-Agnostic

Alpha is protocol-native and provider-agnostic.

Providers may power Alpha, but protocols define Alpha.

No model, provider, harness, database, tool, interface, cloud, runtime, or framework should become Alpha's identity or single point of dependency.

Build through contracts, protocols, interchangeable capabilities, portable representations, adapter boundaries, and safe fallbacks.

### 2. Clear Responsibility, No Conceptual Overlap

Every Alpha part must have one clear canonical responsibility.

Parts may reference, query, render, enforce, or exchange with each other through explicit contracts.

They must not compete for the same responsibility.

Core rule:

> Shared context is allowed; shared ownership is dangerous.

If two parts appear to do the same thing, resolve it immediately:

- **Merge** if they are the same concept.
- **Split** if one concept contains multiple responsibilities.
- **Reassign** if one part is doing another part's job.

Overlap is a design smell unless it is explicitly a bridge.

No part of Alpha should become a second version of another part.

### 3. Naming Reveals Responsibility

Names are architecture.

Use names that reveal context, concept, and role. Avoid vague names that hide ownership.

Canonical naming grammar:

- **Layer** = owns a broad responsibility over time.
- **Graph** = owns relationships, contextual connectedness, and queryability.
- **Protocol** = owns exchange between parts or Alphas.
- **Contract** = owns a capability boundary with providers, tools, models, services, or agents.
- **Artifact** = digitally handleable result or handle.
- **State** = current dynamic condition.
- **View** = scoped rendering or query perspective.
- **Event** = meaningful change record.
- **Envelope** = scoped portable exchange payload.

Examples:

- `Memory Layer`, not `Memory Object`, for continuity stewardship.
- `Process Layer` and `Process State`, not a catch-all process object.
- `Boundary Layer`, not `Permission Ledger`, for authoritative limits and permissions.
- `Life Graph`, not `Experience Graph`, for the queryable context and relationship engine.
- `Capability Contract`, not provider-specific integration logic.
- `Intent Context Envelope`, not raw provider payload.

Core rule:

> Names should reveal responsibility.

If a name does not reveal what the part owns, rename or rethink the part.

## Canonical Responsibility Map

This map is provisional, but it is the current source of discipline for avoiding overlap.

### Intent

Owns: sourced direction.

Does not own: outcome, request, action, fulfillment, or authority by itself.

Canonical line:

> Intent is sourced direction; Alpha can interpret it, but does not own it.

### Outcome

Owns: what would make Intent meaningfully true enough in context.

Does not own: the living intent, request routing, process execution, or fulfillment.

Canonical line:

> Outcome gives Intent shape.

### Request

Owns: the structured ask for how an actor, capability, system, community, service, or external world could help shape an Outcome.

Does not own: Intent, Outcome, fulfillment, provider selection, or commercial pressure.

Canonical line:

> Request is how Alpha asks an actor or capability to help shape an Outcome.

### Artifact

Owns: a small accountable digital handle.

Does not own: memory, permissions, process, rendering, graph relationships, alignment, or provider behavior.

Canonical line:

> An artifact is a handle, not a container for the whole system.

### Life Graph

Owns: queryable relationships, scoped context, graph events, and views.

Does not own: artifact content, memory continuity, permissions authority, process execution, or rendering.

Canonical line:

> The Life Graph is Alpha's queryable context and relationship engine.

### Graph Event

Owns: meaningful change records.

Graph events explain evolution without making every relationship carry heavy lineage.

Canonical line:

> The Life Graph connects artifacts through events, not constant mutation.

### Contextual Clustering

Owns: no separate object-world.

It is a Life Graph capability: provisional grouping under current intent, context, permission, and relevance.

Canonical line:

> A contextual cluster is a provisional Life Graph grouping, not a separate object-world.

### Memory Layer

Owns: life continuity stewardship.

Does not own: artifacts or graph relationships.

Use:

- **Memory Layer** for continuity.
- **Memory Representation** for internal or graph-level representation of memory material.
- **Memory Artifact** for a handleable digital representation.

Canonical line:

> Memory is continuity; artifacts are handles; the graph connects them.

### Process Layer

Owns: dynamic work state.

Use:

- **Process Layer** for dynamic work responsibility.
- **Process State** for current condition.
- **Process Artifact** for a handleable representation.
- **Process View** for rendering/query perspective.

Canonical line:

> Process is state; artifacts handle it; views show it; the Life Graph connects it.

### Boundary Layer

Owns: authoritative limits, permissions, consent, refusal, revocation, and action constraints.

Use:

- **Boundary Layer** for authority.
- **Boundary State** for current applicable limits.
- **Boundary Artifact** for handleable representation.
- **Boundary Protocol** for exchange.
- **Boundary View** for inspection/control.

Canonical line:

> Boundaries govern what Alpha may, may not, and must ask before doing.

### Protocol

Owns: exchange rules between Alpha-shaped parts or Alphas.

Does not own: meaning, state, authority, or rendering.

Protocols carry and protect information across boundaries.

### Capability Contract

Owns: provider/tool/model/service capability boundaries.

Contracts define what a capability can do, what it may receive, what it returns, what it costs, how it fails, and how it can be swapped.

### Agent Identity

Owns: scoped identity for every agent, sub-agent, tool-using role, or automated actor operating inside Alpha.

Agents must not collapse into one generic `Agent`.

Each agent or sub-agent should have its own identifier, role, capability contract, authority scope, lineage, and current process context.

Canonical line:

> Every agent is an accountable actor, not an anonymous worker in a swarm.

### Rendering / Interface

Owns: how something appears or is spoken now.

Does not own: artifact meaning, graph relationships, memory, permissions, or process state.

### Alignment Layer

Owns: drift checking.

It checks whether Alpha's interpretation, action, artifact, or process still fits intent, context, boundaries, permission, care, and outcome.

## Building Methodology

These rules are always in force when developing Alpha concepts, specs, protocols, docs, or implementation.

### 1. Define The Responsibility Before The Shape

Before adding a new concept, primitive, layer, protocol, artifact, module, or implementation, answer:

- What responsibility does this own?
- What does it explicitly not own?
- Which existing part is closest?
- Does this duplicate another part?
- Is this a layer, graph, protocol, contract, artifact, state, view, event, or envelope?
- How does it connect to the Life Graph?
- How does it respect the Boundary Layer?
- How does it stay provider-agnostic?
- What would break if this part disappeared?

If these answers are unclear, do not add the part yet.

### 2. Avoid Parallel Concepts

Do not create a second concept that solves the same problem with different language.

Current resolved decisions:

- `Experience Graph` should not be a canonical primitive. Experience is an emergent composition from Life Graph queries, artifacts, process state, outcomes, rendering, and context.
- `Contextual Cluster` is a Life Graph capability, not a separate object-world.
- `Memory Object` should not be canonical. Use Memory Layer, Memory Representation, and Memory Artifact.
- `Process Object` should not be canonical. Use Process Layer, Process State, Process Artifact, and Process View.
- `Permission Ledger` should not be canonical. Use Boundary Layer and related boundary terms.
- `Intent Object` should not be the canonical name. Use `Intent` for sourced direction, and use Intent Artifact, Intent State, or Intent Context Envelope only when the form requires it.
- `Outcome Contract` should not be the canonical name. Use `Outcome` for what would make intent meaningfully true enough in context; use Outcome State, Outcome Artifact, Outcome View, or Outcome Protocol when the form requires it.
- `Demand Object` should not be the canonical name. Use `Request` for how Alpha asks an actor or capability to help shape an Outcome; use Request State, Request Artifact, Request View, or Request Protocol when the form requires it.

Intent, Outcome, and Request rule:

- Intent must carry source, authority, scope, and lineage.
- Human and group intent can be sovereign.
- Agent intent can only be derived, scoped, explainable, interruptible, and tied to an identifiable agent actor.
- No intent should be attributed to a generic `Agent` when a specific agent or sub-agent initiated it.
- Outcome must remain inspectable, editable, and aligned with Intent, context, boundaries, and care.
- Request must remain subordinate to Intent and Outcome; it should never become hidden advertising, forced commerce, or autonomous fulfillment pressure.

### 3. Add Through Contracts, Not Coupling

Every new part should connect through:

- scoped Life Graph queries
- accountable graph events
- protocols
- capability contracts
- boundary checks
- provider adapters
- portable artifacts

Do not connect parts by hidden shared state, provider-specific assumptions, raw graph access, or duplicated responsibility.

### 4. Query First, Reason Second

Alpha should query structured, scoped context before asking broad model reasoning to infer everything again.

The Life Graph should make context cheap enough to use often.

### 5. User Control Without Administration

People should not need to manage Alpha's internals.

But they must be able to ask:

- Why is this connected?
- What are you using here?
- What can you do with this?
- What did this affect?
- Do not use this anymore.
- This belongs somewhere else.
- Show me what came from this intent.

Control should feel like natural authority, not record management.

### 6. Keep AGENTS.md Compact

Add only durable rules and canonical pointers here.

Do not add raw brainstorming, temporary plans, stale status, or detailed concept prose.

When a concept becomes durable, update the correct docs and keep this file as the map.

## Canonical Docs

- Current concept map: `docs/46-alpha-concept-map-v0.md`
- Kernel: `docs/39-alpha-kernel.md`
- Working principles: `docs/11-working-principles.md`
- Life Graph: `docs/33-interconnected-life-graph.md`
- Alpha artifacts: `docs/54-alpha-artifacts.md`
- Artifact grammar: `docs/55-artifact-grammar-and-families.md`
- Protocol-native provider-agnostic principle: `docs/56-protocol-native-provider-agnostic.md`
- Intent, Outcome, Request triad: `docs/57-intent-outcome-request.md`
- Platform primitives: `docs/04-platform-primitives.md`
- Security and trust: `docs/07-security-and-trust.md`
- Protocol index: `docs/protocols/00-protocol-index.md`
- Spec index: `docs/specs/00-spec-index.md`

## Required Agent Loop

For substantial work, agents must:

1. Read this file first.
2. Read only the relevant canonical docs for the task.
3. Identify which responsibility the work touches.
4. Check for conceptual overlap before adding anything.
5. Apply the naming grammar.
6. Preserve provider-agnostic protocol-native architecture.
7. Preserve Life Graph boundaries and Boundary Layer authority.
8. Update the correct docs when a durable decision changes.
9. Do not commit or push unless the user explicitly asks.
