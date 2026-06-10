# Alpha Threads

Status: conceptual core.

This document defines `Thread` as the organizing reference for the movement from Intent through Align to Outcome.

It exists to keep Alpha deterministic enough to trust without turning life into administration.

Core definition:

> A Thread is the organizing reference for the movement from Intent through Align to Outcome.

Shorter:

> Thread is the reference around the movement.

Thread must not become ceremonial.

Alpha should not add Thread fields, statuses, approvals, lifecycle machinery, or management rituals just because a Thread exists.

If a Thread can do its job with an id, an opening Intent reference, and an evolving human label, that is enough.

## Why Thread Exists

Alpha should not leave the relationship between Intent, Align, Outcome, artifacts, Activity, agents, boundaries, and future work to loose inference.

If Alpha only has isolated Intents and Outcomes, it becomes hard to answer:

- What was this about?
- What did Alpha understand?
- What changed the understanding?
- Which artifacts came from this?
- What is still waiting?
- Which agent did this?
- Which boundary applied?
- Why is this connected?

If Alpha tries to answer those questions by making every movement into a project, task list, dashboard, or folder, it becomes bureaucratic.

Thread is the middle:

> enough structure to refer to the movement, little enough structure to stay humane.

## Core Rule

Every Intent opens a Thread.

That Thread may be tiny, quiet, temporary, or fulfilled in seconds.

It may also become durable, shared, revisited, forked, merged, or connected to many artifacts and Activities.

The point is not size.

The point is that Intent, Align, and Outcome never float without a shared reference.

Canonical line:

> Every Intent opens a Thread; the Thread must remain as small as possible.

## What Thread Owns

Thread owns:

- the organizing reference around Intent, Align, and Outcome
- the reference for "what this is about"
- the reference that lets related movement be grouped without becoming a task system
- the reference for later questions such as "what is still open here?"
- the reference used to connect artifacts, Activity, agents, boundaries, and outcomes through the Life Graph

Thread does not own:

- Intent source
- the act of Aligning
- Outcome meaning
- artifact content
- Activity
- boundary authority
- memory continuity
- graph relationship queryability
- rendering
- provider behavior
- execution permission

Core rule:

> Thread is the organizing reference; it does not own meaning, work, artifacts, or relationships.

## Thread, Intent, Align, Outcome

Thread is not a fourth step after Outcome.

It is the reference around the movement.

```text
Thread
  Intent
  Align
  Outcome
```

Intent owns sourced direction.

Align owns the act of reaching shared understanding.

Align is where understanding changes and becomes explainable.

Outcome owns aligned enoughness in context.

Thread gives Intent, Align, and Outcome one shared reference.

The Thread label is not the truth of the topic.

It is a human handle that can become clearer over time.

For example, a Thread may begin with the label:

> Organize a party

And later become:

> Reconnect with the friend group

The original Intent should remain intact.

The Thread label may change because understanding became clearer.

Core rule:

> A Thread gives the movement one reference while its meaning becomes clearer.

## Align Inside A Thread

`Align` is the act.

It is also where important turns in understanding may remain explainable later.

That does not mean every thought, token, tool call, or internal agent move should be preserved.

Align may need to remain explainable when something meaningfully changes or clarifies:

- what Alpha thinks is meant
- what the relevant authority accepted, rejected, corrected, or left uncertain
- which boundary applies
- which context matters
- which prior artifact or memory representation influenced understanding
- which agent or tool contributed to understanding
- which Outcome became possible, revised, refused, or obsolete

Align is not the Alignment Layer.

The Alignment Layer checks drift later.

Core rule:

> Align includes the important turns in understanding that Alpha may need to explain later.

## Relationship Model

Thread gives the movement one required reference.

That does not mean Alpha should turn every connection into a formal relationship record.

The lightweight model:

```text
Thread gives the movement one reference.
Extra explanation is kept only when it helps meaning, lineage, responsibility, current work, or boundaries stay understandable.
The Life Graph stores and queries what needs to remain explainable.
Views show what helps now.
```

Minimum movement:

```text
Intent opens Thread
Align happens inside Thread
Outcome points to Thread
```

Sometimes Alpha needs more than a Thread reference.

For example, it may need to explain that an invitation draft is connected to the party Thread because it helps the current Outcome, waits for the person's review, and cannot be sent without approval.

Those explanations may become relationship claims when they need to remain queryable.

The Life Graph does not invent their meaning by itself.

They may come from:

- the person
- the relevant authority
- Intent capture
- Align
- agents or sub-agents within scope
- Activity Layer
- Boundary Layer
- artifact creation
- provider or tool adapters
- explicit correction

Core rule:

> Thread should make the movement referable, not administrative.

## Why Not Only A Chain

The movement can be written simply:

```text
Intent -> Align -> Outcome
```

But Alpha cannot store life as only a chain.

Life is many-to-many:

- one Thread may hold several related Intents
- several Intents may converge into one Outcome
- one Intent may lead to several Outcomes over time
- Align may revise a prior Outcome
- one artifact may support a current Outcome while also referencing an earlier one
- one agent-originated Intent may exist inside a larger human Thread
- one boundary may limit several possible actions inside the same Thread

Thread provides the shared reference.

Direct relationship claims preserve the explanatory connections.

## Why Not Only Thread Links

If everything only belongs to Thread, Alpha loses explanation power.

It could say:

> this invitation draft belongs to the party Thread.

But it could not explain:

> this invitation draft supports the Outcome "low-pressure party direction", was produced by the host agent, and waits for the user's review before anyone is contacted.

Thread reference answers:

> what does this belong to?

Extra explanation answers:

> why does it matter here?

Both are needed.

## Existing Threads

Every Intent should have a Thread reference for its current movement.

That does not always mean a new durable Thread.

An Intent may enter an existing Thread when the scope is clear:

- the user starts from an existing Thread, artifact, Activity, or view
- the user says the new Intent belongs to something already underway
- an agent creates or Activity surfaces a derived operational Intent inside a Thread
- the current interaction context is already scoped to a Thread
- Alpha proposes or lightly names the connection, and the relevant authority accepts or can easily correct it when consequence is low

If the match is uncertain or consequential, Alpha should not silently attach the Intent to the existing Thread.

It should ask lightly or create a separate Thread that can later be merged.

Core rule:

> Thread matching can be assisted by intelligence, but authority and consequence decide when uncertain joins are allowed.

## No Thread State By Default

Thread does not need state by default.

State is one of the easiest ways for Thread to become ceremonial.

Do not add Thread State unless it earns its place later.

If dynamic work must be tracked, use Activity.

If understanding changes in a way that matters later, keep it explainable through Align.

If something needs to be shown, use a View.

If authority changes, use the Boundary Layer.

Thread should stay minimal.

## After Outcome

Outcome does not automatically grant permission to execute.

After Outcome, Thread becomes more useful as an orientation anchor.

Alpha can use the Thread to:

- connect artifacts that support the Outcome
- show what is still open
- let concrete Tasks point to the same movement when work becomes explicit
- let agents work within scope
- hold Activity calmly
- detect drift
- ask for review
- remember why something exists
- connect future Intents to the right context
- avoid repeating alignment work unnecessarily
- explain why Alpha is suggesting something

Example:

```text
Thread: Future warm party
Intent: "I want to organize something warm with this group someday."
Align: "This seems more about connection than logistics."
Align: "Low-pressure, no invitations yet."
Outcome: "Enough means a low-pressure party direction with possible venues and themes, without inviting people yet."
Artifact: venue findings
Artifact: invitation draft
Task: review invitation draft
Activity: invitation draft waiting for review
Boundary State: no external messages without approval
```

When the person asks:

> What do I still need to do?

Alpha can render an Open Work View from the Thread:

> For the future party, three things are waiting on you: choose whether these venues feel right, review the invitation draft, and decide whether the theme still feels low-pressure.

That view is not a generic task list.

It is a scoped view over Thread, Outcome, Tasks, artifacts, Activity, boundaries, and Life Graph relations.

Core rule:

> Outcome anchors what matters; Thread lets Alpha keep the surrounding work understandable.

## Open Work View

An Open Work View is not a new owner.

It is a View.

It can be rendered from:

- active or waiting Threads
- Outcomes
- Activity
- artifacts needing review
- approval gates
- boundary constraints
- agent work in progress
- relevant time or context

It helps Alpha answer:

> what is still open?

without reducing Alpha to task management.

Core rule:

> Open Work View shows current attention needs; it does not own the work.

## Boundary And Permission

Thread does not grant permission.

A Thread may connect many things, but the Boundary Layer still governs what Alpha may see, use, share, remember, publish, spend, send, or automate.

High-consequence movement inside a Thread should require explicit authority.

Thread can help Alpha know where a boundary applies.

It cannot bypass that boundary.

## Personal And Shared Threads

Threads can be personal or shared.

A personal Thread should not expose private life material just because it later touches another person.

A shared Thread should represent consented overlap, not merged lives.

For example, a shared party Thread may contain:

- shared Outcome
- shared artifacts
- shared decisions
- shared Activity
- consented boundaries

It should not expose:

- private reasons
- private memories
- unrelated preferences
- hidden graph structure
- child-related data outside safe scope

Core rule:

> Shared Threads are consented scopes, not merged inner worlds.

## Provider-Agnostic Requirement

Thread must be provider-neutral.

No model, database, harness, tool, or interface should define what a Thread is.

Providers may help:

- infer possible relations
- summarize Thread state
- render a View
- draft artifacts
- check drift
- run scoped agent work

But Thread meaning must live in Alpha's own contracts, protocols, graph relationships, boundaries, and portable representations.

## What Thread Is Not

Thread is not:

- a chat thread
- a project
- a folder
- a task list
- a workflow engine
- a Life Graph
- a memory store
- a permission system
- a user interface
- a model context window
- a hidden profile

Those forms may appear around a Thread.

They are not the Thread.

## Failure Modes

### Thread Inflation

Risk:

> Every tiny Intent becomes a heavy project, lifecycle, status machine, or ceremony.

Correction:

> Every Intent opens a Thread, but the Thread stays minimal by default.

### Thread Collapse

Risk:

> Thread starts owning artifacts, Activity, memory, permissions, or graph relationships.

Correction:

> Thread owns the organizing reference only.

### Hidden Threading

Risk:

> Alpha silently groups life material in ways the person cannot inspect or correct.

Correction:

> Thread references and extra explanations must be askable, explainable, and correctable.

### Chain Collapse

Risk:

> Alpha only stores Intent -> Align -> Outcome as a line and cannot represent convergence, revision, multiple artifacts, or later work.

Correction:

> Use Thread as scope, plus direct relationship claims where meaning needs explanation.

### Graph Overreach

Risk:

> The Life Graph appears to decide what belongs together.

Correction:

> The Life Graph stores and queries relationship claims; it does not own meaning or authority.

## Working Sentences

> Thread is the reference around the movement.

> Every Intent opens a Thread.

> A Thread is the organizing reference for the movement from Intent through Align to Outcome.

> Thread must not become ceremonial.

> Thread is the organizing reference; it does not own meaning, work, artifacts, or relationships.

> Everything in the movement can point to the Thread; extra explanations explain why.

> A Thread gives the movement one reference while its meaning becomes clearer.

> Thread reference answers what this belongs to; extra explanation answers why it matters here.

> Outcome anchors what matters; Thread lets Alpha keep the surrounding work understandable.

> Open Work View shows current attention needs; it does not own the work.
