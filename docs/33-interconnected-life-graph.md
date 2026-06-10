# Life Graph

Status: conceptual v0.

The Life Graph is Alpha's queryable context and relationship engine.

It is the connected layer of your life in Alpha.

It is not a total map of a person's life.

It is not a hidden profile machine.

It is not a database where everything Alpha can collect is dumped.

It is the Alpha-native but human-governed substrate that helps Alpha understand how parts of a person's or group's world relate, when those relationships matter.

## Core Definition

> The Life Graph is Alpha's queryable context and relationship engine.

Another angle:

> The Life Graph is the connected layer of your life in Alpha.

And the governance boundary:

> The Life Graph is Alpha's connective substrate, governed by the people whose life material it touches.

Alpha uses the Life Graph actively.

It is part of how Alpha understands:

- where things are
- what they are connected to
- which Thread scopes the current movement
- which artifacts came from which intents
- which Activity is moving or waiting
- which boundaries apply
- which context is relevant
- which parts form a situation
- what can be queried, shown, used, ignored, protected, or shared

But the life material inside the graph is not Alpha's possession.

People and groups must retain authority over what may enter, influence, be shown, be shared, be corrected, be scoped, or be forgotten.

## Why It Exists

Alpha should not understand life as isolated tasks, isolated chats, isolated apps, isolated memories, isolated files, or isolated outcomes.

Everything happens in relation.

One condition can lead to another.

Several intents can converge into one state change.

One memory representation can change the meaning of a future conversation.

One family ritual can affect a child's sense of safety, a parent's attention, a shared memory, and a future holiday.

One business decision can affect money, culture, trust, time, family, customers, and creative energy.

The standard:

> do not optimize isolated moments when the meaning lives in the connections.

## Queryability

The Life Graph must be extremely queryable.

Alpha should be able to query it quickly, frequently, and cheaply.

This matters because Alpha should not call a large model every time it needs basic context.

The graph should make many relationship and context questions cheap enough to ask often.

The Life Graph should help Alpha answer:

- Which Thread does this belong to?
- Which Intents, Align, Outcomes, artifacts, Activity, agents, and boundaries are connected around this Thread?
- Which Tasks point to this Thread, and what made them necessary?
- Which artifacts came from this intent?
- Which Activity is blocked by the same boundary?
- Which artifacts, people, contexts, and outcomes are connected to this situation?
- Which old context may influence this current choice?
- Which shared artifacts exist between these people?
- Which things may not be shared with another Alpha?
- Which open loops are connected to this event?
- Which provider, model, tool, or agent influenced this artifact?
- Which relations are explicit, inferred, rejected, private, shared, temporary, or dormant?
- Which minimal context is useful for this task without exposing everything?

Core rule:

> The Life Graph is deeply queryable, but never openly exposed.

Another rule:

> Query first, reason second.

Alpha should query the Life Graph for scoped context, boundaries, relations, and relevant artifacts before asking a model or tool to reason broadly.

This reduces:

- latency
- cost
- compute
- carbon impact
- context-window pressure
- repeated inference
- accidental privacy exposure

The Life Graph should make context cheap enough to use often.

## Core Parts

The Life Graph can be understood through four parts:

1. Nodes
2. Relationship Claims
3. Graph Events
4. Views

These are conceptual parts, not final implementation classes.

## 1. Nodes

Nodes are the things that can participate in the graph.

Possible node families include:

- threads
- artifacts
- intents
- people
- groups
- activities
- tasks
- boundaries
- permissions
- outcomes
- memory representations
- contexts
- events
- non-events
- places
- time periods
- preferences
- communications
- sources
- providers
- tools
- agents
- agent identities
- agent-originated intents
- costs
- decisions
- open loops

Not everything must become an explicit node.

Some things may be inferred, temporary, derived, or only visible inside a view.

The Life Graph contains what Alpha needs to connect, not everything Alpha can collect.

## 2. Relationship Claims

Relationships are first-class in the Life Graph.

The power of the graph is not only in what exists.

It is in how things relate.

A relationship is not just an edge.

It is a contextual claim.

Examples:

- this artifact came from this intent
- this Intent opened this Thread
- this understanding changed around this Thread
- this Outcome belongs to this Thread
- this Outcome answers this Intent
- this Outcome was shaped by Align
- this Activity is blocked by this boundary
- this memory representation is sensitive in this context
- this preference applies to this period, not forever
- this artifact belongs to this shared group context
- this artifact belongs to this Thread
- this artifact supports this Outcome
- this Task points to this Thread
- this Task was caused by this artifact, boundary, Activity, agent, Align, or Outcome
- this Activity belongs to this Thread
- this Activity serves this Outcome
- this outcome was shaped by these three intents
- this provider contributed to this generated artifact
- this specific agent initiated this derived intent
- this sub-agent was spawned for this Activity
- this agent acted under this capability contract
- this action may affect this person, Activity, or relationship

Possible relationship claim types:

- `related_to`
- `opens`
- `derived_from`
- `answers`
- `settled_by`
- `supports`
- `serves`
- `blocked_by`
- `waits_on`
- `belongs_to`
- `shared_with`
- `supersedes`
- `requires_permission`
- `produced_by`
- `influenced_by`
- `references`
- `activated_by`
- `limited_by`
- `forked_from`
- `merged_into`
- `split_into`

These types are provisional.

The important principle:

> Relationships are queryable claims.

The Life Graph does not decide meaning by itself.

It stores and queries relationship claims created, proposed, corrected, rejected, or confirmed by the person, relevant authority, Align, agents within scope, Activity Layer, Boundary Layer, artifacts, providers, tools, or explicit correction.

Thread provides required scope.

Direct links explain meaning, lineage, responsibility, and current work.

Relationship claims may include local context when needed:

- reason
- source
- created_at
- scope
- visibility
- permission boundary
- sensitivity
- status
- relevant context
- inferred or explicit origin
- whether the user confirmed, rejected, corrected, or ignored it

But relationships should not become a huge administrative system.

The Life Graph should query relationships, not babysit them.

## 3. Graph Events

Graph events explain meaningful change.

They are how the Life Graph preserves enough history to explain evolution without forcing every relationship to carry heavy lineage.

Possible graph events:

- `created`
- `forked`
- `merged`
- `split`
- `corrected`
- `shared`
- `revoked`
- `superseded`
- `reinterpreted`
- `completed`
- `abandoned`
- `reactivated`
- `permission_changed`
- `context_changed`
- `provider_used`
- `agent_used`
- `agent_spawned`
- `agent_handoff`
- `initiated_by`
- `authorized_by`
- `performed_by`
- `artifact_created`
- `artifact_updated`
- `relationship_added`
- `relationship_removed`

Graph events matter because artifacts can evolve.

An artifact may not mutate forever.

It may become the basis for a new artifact.

Examples:

- intent artifact -> outcome artifact
- finding artifact -> decision artifact
- creative draft -> public work artifact
- Activity Artifact -> completed result artifact
- private note -> shared agreement artifact
- context snapshot -> boundary artifact
- playlist draft -> shared party artifact

The original artifact can remain stable enough to trust.

The new artifact can have its own identity.

The Life Graph records the transformation through events and relationship claims.

Core rules:

> Artifacts are stable enough to trust and flexible enough to fork.

> The Life Graph connects artifacts through events, not constant mutation.

> Lineage exists where evolution matters.

## 4. Views

Views are scoped ways of querying, rendering, or using the Life Graph.

The Life Graph itself may be rich.

But no person, provider, tool, model, agent, or other Alpha should automatically receive the whole graph.

Possible views:

- personal view
- shared view
- current intent view
- Thread View
- Open Work View
- artifact lineage view
- boundary and safety view
- Activity View
- transparency view
- Alpha-to-Alpha envelope view
- child-safe view
- low-cost execution view
- debugging or recovery view

Views should be permissioned, purpose-bound, and context-sensitive.

The same underlying graph can produce different views for different purposes.

For example:

- a person may see why Alpha connected a plan to a boundary
- a group may see only the shared dinner plan
- a provider may receive only a filtered capability input
- another Alpha may receive only a consented envelope
- a child may see a child-appropriate learning view
- a recovery tool may see Activity without private memories

## How Parts Connect

Parts should connect to the Life Graph through scoped questions and accountable events.

They should not receive raw graph access by default.

Parts include:

- agents
- tools
- model providers
- local services
- interfaces
- artifact renderers
- memory systems
- communication channels
- queues
- safety modules
- cost routers
- child-safety modules
- business modules
- media modules
- other Alphas

They should ask scoped questions:

```text
query_life_graph(
  purpose: "draft dinner options",
  scope: "shared dinner plan",
  needs: ["availability", "dietary constraints", "location preferences", "relevant boundaries"],
  exclude: ["private reasons", "unrelated memories", "raw personal graph"]
)
```

And they should emit accountable events:

```text
emit_graph_event(
  type: "artifact_created",
  artifact_id: "...",
  source: "calendar_adapter",
  purpose: "suggest dinner slot",
  affected_scope: "shared dinner plan"
)
```

Core rule:

> Parts connect to the Life Graph through scoped questions and accountable events.

## Protocol-Native And Provider-Agnostic

The Life Graph must be protocol-native and provider-agnostic.

It should not depend on one model, provider, harness, database, interface, cloud, or runtime.

Providers may help query, enrich, render, or act from the graph.

They should not define the graph's meaning.

Models, tools, agents, providers, and other Alphas should receive scoped representations from the graph, not raw access to a person's life.

The Life Graph should support:

- capability contracts
- provider adapters
- safe envelopes
- protocol validation
- portable artifacts
- scoped graph access
- permission-aware routing
- Alpha-to-Alpha communication without raw personal data exposure
- fallback when a provider fails or changes

## Personal And Shared Life Graphs

The Life Graph can be personal or shared.

But shared does not mean merged lives.

Core rule:

> Shared Life Graphs are consented overlaps, not merged lives.

A personal Life Graph may hold relations around one person's intents, artifacts, memories, preferences, boundaries, Activity, and outcomes.

A shared Life Graph may emerge around:

- a group
- family
- friendship
- project
- event
- community
- business
- game
- trip
- collaboration

A personal or shared Thread can provide scoped continuity inside those graphs.

Thread does not merge lives.

It gives Alpha a consented reference for the movement around Intent, Align, Outcome, artifacts, Activity, agents, and boundaries.

A shared Life Graph should not expose each person's private graph.

It should hold only the shared overlap:

- shared artifacts
- shared decisions
- shared boundaries
- shared plans
- shared Activity
- shared context that has consent to be shared

## Alpha-To-Alpha Communication

Different Alphas should eventually be able to communicate.

They should not communicate by exposing raw Life Graphs.

They should communicate through consentful, purpose-bound envelopes.

Core rule:

> Alphas should communicate through consentful, purpose-bound envelopes, never by exposing the person behind them.

For example, when planning dinner:

An Alpha may share:

- available windows
- consented dietary constraints
- relevant location preference
- proposed options
- shared artifact references
- consented next steps

It should not share:

- raw calendar data
- private reasons for unavailability
- unrelated memories
- hidden preferences
- personal graph structure
- sensitive relationship context
- child data unless explicitly and safely scoped

## Dynamic Contextual Clustering

The Life Graph should support dynamic contextual clusters.

A cluster is not a fixed folder.

It is a provisional relationship that may become relevant under a specific intent, moment, artifact, medium, or context.

Something that is not a cluster in one moment may become one in another.

Clusters should be:

- scoped
- provisional
- correctable
- askable
- context-sensitive
- permission-aware

The graph should allow clusters to form, dissolve, split, merge, or become dormant.

Alpha should never treat a provisional cluster as a fixed identity.

## Many-To-Many Causality

Alpha should allow:

- one intent -> many artifacts
- one intent -> many state changes
- many intents -> one artifact
- many intents -> one state change
- one memory representation -> many future meanings
- one action -> many consequences
- one boundary -> many possible refusals
- one relationship -> many contexts
- one event -> many graph events
- one artifact -> several future artifacts

Examples:

- "I want my family to be closer" and "I want less screen time" and "I want my child to feel seen" may converge into one quiet Sunday ritual.
- A protected memory representation of saying goodbye to a best friend may affect media choices, grief boundaries, friendship rituals, and what Alpha should not resurface casually.
- A business intent may create a document, a customer call, a calendar rhythm, a spending boundary, and a memory representation of what was learned.
- A song from a party may become linked to a group memory representation, a future ritual cue, and a cultural artifact.

## Boundaries And Refusals

The Life Graph should make Alpha more contextual, not more possessive.

It must never:

- try to totalize a person's life
- become a hidden profiling machine
- provide raw graph access to providers, tools, agents, or other Alphas
- silently blend personal context into shared context
- treat old context as permanent truth
- treat inferred relationships as facts
- use sensitive relations without permission
- model children as permanent profiles
- power advertising, manipulation, or hidden persuasion
- trap people inside past taste, behavior, identity, or mistakes
- keep everything "just in case"
- confuse queryability with the right to use
- lower privacy because it is technically convenient
- automate social pressure from relationship data
- make Alpha-to-Alpha communication depend on raw graph sharing

## Human Control

The person does not need to manage the Life Graph as administration.

But the person should be able to ask:

- Why is this connected?
- What context are you using here?
- What did this affect?
- What did you infer?
- Is this shared or private?
- Why did this appear now?
- Do not use this anymore.
- This belongs somewhere else.
- This was only true then.
- Remove this from that shared context.
- Show me the artifacts related to this.
- Show me what came from this intent.

The Life Graph should support correction without turning life into data management.

## Humility About Causality

Alpha can notice patterns, but it should be humble.

Human life is not a clean machine.

Alpha should say:

- "This may be connected."
- "I might be over-associating."
- "These may form a cluster right now."
- "Should these stay together or separate?"
- "Do you want this relationship to matter later?"
- "This intent seems related to another one."
- "This action could affect these people or contexts."

The person remains the authority on meaning.

## Core Standard

An Alpha-shaped Life Graph is healthy when:

1. It is deeply queryable without being openly exposed.
2. It makes relationships first-class without becoming bureaucratic.
3. It connects artifacts through events, not constant mutation.
4. It supports lineage where evolution matters.
5. It enables scoped views instead of raw access.
6. It lets parts connect through scoped questions and accountable events.
7. It remains protocol-native and provider-agnostic.
8. It supports shared overlap without merged lives.
9. It makes Alpha more contextual, not more possessive.
10. It lets people correct, separate, hide, refuse, or re-scope connections.

The question is not:

> What did this single ask produce?

The question is:

> What is connected, what is allowed, what changed, and what should Alpha understand with care?

## Working Sentences

> The Life Graph is Alpha's queryable context and relationship engine.

> The Life Graph is Alpha's connective substrate, governed by the people whose life material it touches.

> The Life Graph is deeply queryable, but never openly exposed.

> Query first, reason second.

> Relationships are first-class.

> A relationship is not just an edge; it is a contextual claim.

> The Life Graph should query relationships, not babysit them.

> The Life Graph connects artifacts through events, not constant mutation.

> Lineage exists where evolution matters.

> Parts connect to the Life Graph through scoped questions and accountable events.

> Shared Life Graphs are consented overlaps, not merged lives.

> The Life Graph should make context cheap enough to use often.

> The Life Graph should make Alpha more contextual, not more possessive.
