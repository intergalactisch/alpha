# Platform Primitives

Alpha should not be designed around apps, chats, or dashboards as the primary objects.

Those are surfaces.

The deeper platform needs new primitives.

Naming note:

`Intent Object`, `Outcome Contract`, and `Demand Object` are still provisional working names. They describe important responsibilities, but their final names should be grilled against the Alpha naming grammar before implementation. In particular, `Outcome Contract` here means an editable human agreement about success, not a provider capability contract.

## 0. Protocol-Native Substrate

Alpha should be protocol-native and provider-agnostic.

Every primitive should be able to connect through contracts, protocols, interchangeable capabilities, and adapter boundaries.

The substrate is not a single provider, model, harness, database, interface, cloud, or runtime.

It is the connective discipline that lets Alpha parts hook into each other without tight coupling.

Core rule:

> Providers may power Alpha, but protocols define Alpha.

This substrate should support:

- capability contracts
- provider adapters
- safe envelopes
- protocol validation
- portable artifacts
- scoped Life Graph access
- permission-aware routing
- Alpha-to-Alpha communication without raw personal data exposure
- fallback when a provider fails or changes

If a primitive only works because one provider behaves in one specific way, the primitive is not stable enough.

## 1. Intent Object

A durable representation of what someone or some group wants.

An intent object includes:

- desired outcome
- emotional target
- constraints
- time horizon
- participants
- budget
- permissions
- anti-goals
- success signals
- uncertainty

Example:

> "Make our group feel close again, without requiring a big planning burden, over the next four weeks."

## 2. Outcome Contract

The system's current interpretation of success.

This should be inspectable and editable by the user. It prevents Alpha from drifting into generic engagement.

Example:

> "Success means at least three members participate weekly, one real meetup is scheduled, and the group creates one shared artifact they actually enjoy."

## 3. Demand Object

A structured request for what the world might create, customize, assemble, source, coordinate, or refuse in response to an intent.

The demand object is how Alpha moves beyond finite catalogs.

It can represent:

- products
- services
- tools
- media
- business systems
- education paths
- community rituals
- games
- institutional actions
- physical-world changes

It should include:

- desired outcome
- constraints
- budget
- time horizon
- quality bar
- sustainability preference
- privacy constraints
- acceptable fulfillment types
- human approval requirements

Shopping is one example. The larger primitive is generative demand.

## 4. Life Graph

The Life Graph is Alpha's queryable context and relationship engine.

It is Alpha-native but human-governed.

It connects intents, artifacts, memory representations, processes, boundaries, people, groups, contexts, outcomes, sources, tools, agents, and graph events through scoped, permission-aware relationships.

The Life Graph owns:

- queryable relationships
- scoped context
- graph events
- views
- relationship claims
- contextual connectedness

The Life Graph does not own:

- artifact content
- memory continuity
- permission authority
- process execution
- rendering
- provider behavior

Core rules:

> The Life Graph is deeply queryable, but never openly exposed.

> Query first, reason second.

Experience is not a separate graph primitive.

An experience emerges from Life Graph queries, artifacts, process state, outcomes, rendering, and context.

## 4a. Contextual Clustering

Contextual clustering is a Life Graph capability.

A contextual cluster is a provisional Life Graph grouping under a specific intent, context, permission scope, moment, medium, or meaning.

It is not a separate object-world.

It may be formed from:

- tags
- categories
- metadata
- time
- vague time-feeling
- provenance
- current intent
- current medium
- boundaries
- permissions
- corrections
- relationship claims
- graph events

Clusters should be real-time and context-sensitive.

What is not a cluster in one moment may become one in another.

A cluster can be:

- suggested
- hidden
- visible
- user-confirmed
- user-rejected
- private
- shared
- sensitive
- temporary

Clusters must remain editable, scoped, askable, and subordinate to the user's meaning.

Every Alpha artifact should be able to participate in clusters without becoming a surveillance object.

## 4b. Alpha Artifact

An Alpha artifact is a small accountable digital handle.

It is not a container for the whole system.

It can represent, reference, or activate intent, context, memory material, process state, boundaries, relationships, or outcomes, but it does not own those responsibilities.

Canonical core:

- `id`
- `family`
- `type`
- `label`
- `created_at`
- `status`
- `purpose`

Artifacts are one way Alpha moves beyond static apps.

In the old paradigm, apps hold functionality.

In Alpha, artifacts make meaning handleable.

## 5. Memory Layer

The Memory Layer owns life continuity stewardship.

Memory is not an artifact.

Memory is not generic storage.

Memory should support life without owning life.

Use:

- **Memory Layer** for continuity stewardship.
- **Memory Representation** for system-level or graph-level representation of memory material.
- **Memory Artifact** for a digitally handleable representation of memory material.

Memory material may include:

- photos
- videos
- text
- voice
- places
- media
- game moments
- rituals
- objects
- future sensory or spatial forms

The Memory Layer should govern:

- who memory material belongs to
- who it is shared with
- whether it is personal, shared, collective, temporary, or sensitive
- what consent applies
- what context matters
- what provenance exists
- whether it can be used for future Alpha context
- whether it can appear in recaps
- whether it can be exported, redacted, hidden, forgotten, or revoked

Canonical rule:

> Memory is continuity; artifacts are handles; the graph connects them.

## 6. Agent Cast

Alpha should feel like one coherent system, but internally it can cast agents into roles.

Possible roles:

- Game Master
- Producer
- Planner
- Archivist
- Host
- Researcher
- Buyer
- Moderator
- Coach
- Critic
- Worldbuilder
- Scheduler
- Builder

The user should not have to manage the cast manually. Alpha should reveal roles only when it helps trust or control.

## 7. Boundary Layer

The Boundary Layer owns authoritative limits, permissions, consent, refusal, revocation, and action constraints.

Alpha needs a natural consent system for what it can know, remember, say, schedule, buy, book, invite, publish, spend, expose to providers, or automate.

The challenge:

> make boundaries feel like trust-building, not enterprise configuration.

Possible boundary language:

- Ask me first.
- Draft only.
- Can suggest.
- Can send after approval.
- Can remember for this group.
- Forget after this phase.
- Never use this in public recaps.
- Do not expose this to providers.

Use:

- **Boundary Layer** for authority.
- **Boundary State** for current applicable limits.
- **Boundary Artifact** for a handleable representation.
- **Boundary Protocol** for exchange.
- **Boundary View** for inspection and control.

The Boundary Layer should create a durable record of granted capabilities, expired capabilities, denied capabilities, revoked capabilities, and consequential actions.

The user should be able to answer:

> What can Alpha do right now?

and:

> What did Alpha do already?

without needing to trust a vague assistant persona.

Canonical rule:

> Boundaries govern what Alpha may, may not, and must ask before doing.

## 8. Generated Interface

Interfaces are rendered moments.

Alpha might generate:

- mission card
- group vote
- game board
- event plan
- shopping list
- recap page
- map
- calendar proposal
- character sheet
- dashboard
- shared archive

The interface should exist because the experience needs it, not because the product category demands it.

Generated interfaces must be provenance-aware. If a UI asks the user to approve money, messages, business actions, private memories, or public publishing, it should clearly show what system or agent produced it and what action approval will trigger.

## 8a. Process Layer And Process State

The Process Layer owns dynamic work state.

Process State represents what is currently happening with work underway.

It may include:

- intent being served
- current task
- current state
- started time
- elapsed time
- approximate expectation
- queue position
- dependencies
- blockers
- required user input
- required approvals
- artifacts being created
- tools or agents involved
- next likely step
- cancellation or pause state
- recovery state

The user should not have to manage process state manually.

But Alpha should be able to explain:

> where are we in this?

and:

> what is still waiting?

and:

> what input do you need from me?

Use:

- **Process Layer** for dynamic work responsibility.
- **Process State** for current condition.
- **Process Artifact** for a handleable representation.
- **Process View** for rendering or query perspective.

Canonical rule:

> Process is state; artifacts handle it; views show it; the Life Graph connects it.

## 9. Simulation Layer

Before acting, Alpha should be able to simulate likely outcomes.

Examples:

- Is this mission too awkward?
- Is this plan too expensive?
- Will this schedule exclude someone?
- Is the group getting tired?
- Is the tone becoming cheesy?
- Is this game balanced?
- Is this purchase aligned with the stated intent?

This layer is how Alpha becomes socially intelligent instead of merely generative.

## 10. Ritual Loop

The most important consumer primitive may be the ritual loop.

A ritual loop is a repeated, emotionally legible sequence that makes people want to return.

For Alpha Circles:

1. Weekly mission appears.
2. Members respond.
3. Alpha creates a playful artifact.
4. The group reacts.
5. Alpha proposes a next step.
6. The shared memory evolves.

The loop should create momentum without becoming obligation.

## 11. Fulfillment Layer

Eventually Alpha can coordinate external action:

- bookings
- purchases
- reservations
- creator services
- local vendors
- delivery
- print/fabrication
- human helpers
- robots and devices

This turns intent into a demand object.

The first MVP can simulate fulfillment manually or require user approval for every step.

Early Alpha should default to approval gates for high-consequence actions:

- spending money
- sending messages as the user
- publishing externally
- sharing memories across people
- deleting important data
- making business, legal, medical, financial, or institutional commitments
- changing access permissions

## 12. Feedback And Adaptation

Alpha must learn from reality, not just from prompts.

Signals:

- participation
- sentiment
- completion
- laughter
- saves
- shares
- repeat use
- real-world action
- explicit feedback
- ignored prompts
- social friction

The question after every loop:

> Did the experience make the intended reality more true?

## 13. Cost And Scale Governor

Alpha needs a governor that decides how much intelligence, compute, tool use, memory, media generation, and autonomy an intent actually deserves.

The default should be:

> use the smallest sufficient system that can honor the intent.

This governor should consider:

- task complexity
- consequence level
- user budget
- time sensitivity
- privacy needs
- sustainability impact
- confidence
- available cached context
- whether a smaller model or deterministic workflow is enough
- whether a human approval step is cheaper and safer than autonomy

Alpha should be able to escalate:

- from rule to small model
- from small model to stronger model
- from one agent to a small cast
- from text to generated UI
- from draft to approved action
- from lightweight summary to deep research
- from cached artifact to regeneration

But escalation should be intentional and visible.

The product should feel infinitely expandable, but internally it should be disciplined:

- no needless background agents
- no repeated large generations when reuse works
- no expensive media by default
- no always-on loops without purpose
- no heavyweight architecture for tiny intents

Scale comes from frugality, composability, and reuse.

## 14. Recovery Layer

Alpha needs a recovery layer between generated software, tools, agents, external services, and the human experience.

The recovery layer should:

- catch failures
- preserve state
- retry safely
- route around broken tools
- translate technical errors into human consequences
- ask only when a decision is needed
- log diagnostics privately
- protect sensitive context
- repair or regenerate broken surfaces where safe

The user should not be the debugger of the system.
