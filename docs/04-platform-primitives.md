# Platform Primitives

Alpha should not be designed around apps, chats, or dashboards as the primary objects.

Those are surfaces.

The deeper platform needs new primitives.

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

## 4. Experience Graph

A living map of the people, tools, memories, places, media, events, open loops, jokes, preferences, and commitments around an intent.

This is where Alpha compounds.

The graph should know:

- who is involved
- what happened
- what mattered
- what is unresolved
- what tone fits
- what constraints exist
- what objects or artifacts were created
- what interventions worked

## 4a. Contextual Cluster

A contextual cluster is a provisional relationship between memories, intents, artifacts, people, places, media, actions, or outcomes.

It is formed from:

- tags
- categories
- metadata
- time
- vague time-feeling
- provenance
- current intent
- current medium
- permissions
- corrections
- relationships between artifacts

Clusters should be real-time and context-sensitive.

What is not a cluster in one moment may become a cluster in another.

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

Every Alpha artifact should be able to activate, handle, and influence clusters without becoming a surveillance object.

## 5. Memory Object

A memory object is a protected artifact of life continuity.

It may include:

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

The memory object should know:

- who it belongs to
- who it is shared with
- whether it is personal, shared, collective, temporary, or sensitive
- what consent applies
- what context matters
- what provenance exists
- whether it can be used for future Alpha context
- whether it can appear in recaps
- whether it can be exported, deleted, or revoked

Memory is not generic storage. Storage is stewardship, not ownership.

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

## 7. Permission Ledger

Alpha needs a natural consent system for what it can know, remember, say, schedule, buy, book, invite, publish, or automate.

The challenge:

> make permissions feel like trust-building, not enterprise configuration.

Possible permission language:

- Ask me first.
- Draft only.
- Can suggest.
- Can send after approval.
- Can remember for this group.
- Forget after this season.
- Never use this in public recaps.

The permission ledger is also a security primitive. It should create a durable record of granted capabilities, expired capabilities, denied capabilities, and consequential actions.

The user should be able to answer:

> What can Alpha do right now?

and:

> What did Alpha do already?

without needing to trust a vague assistant persona.

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

## 8a. Process Object

A process object represents dynamic work underway.

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

The user should not have to manage process objects manually.

But Alpha should be able to explain:

> where are we in this?

and:

> what is still waiting?

and:

> what input do you need from me?

Process objects make waiting, loading, processing, queues, and loops legible without exposing raw machinery.

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
