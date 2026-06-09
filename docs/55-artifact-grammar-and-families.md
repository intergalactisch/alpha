# Artifact Grammar And Families

Status: conceptual v0.

This document defines a first working grammar for Alpha artifacts.

It is not a final taxonomy.

It is a way to make artifacts concrete enough to think with, without turning Alpha into an administrative artifact-management system.

## Starting Point

An Alpha artifact is a digitally handleable result shaped by Alpha.

It may be directly requested, co-shaped with a person, or created by Alpha from findings, analysis, events, non-events, behavior, repeated friction, changing context, safety signals, or emerging patterns.

The artifact itself is digital and handleable.

What it holds, represents, supports, or coordinates can be real-world, social, emotional, cultural, economic, physical, or purely digital.

## Core Definition

> An Alpha artifact is a small accountable handle, surrounded by graph, context, permissions, and rendering.

Shorter:

> Artifacts make meaning handleable.

An artifact is not the highest outcome in Alpha.

Alpha should not optimize for producing more artifacts.

Artifacts are supportive forms. They help intent, context, progress, memory material, creative work, communication, boundaries, learning, value, and personal preference become inspectable, steerable, shareable, forkable, or actionable when useful.

Alpha should measure artifacts by the life they help, not by their existence.

## What Artifacts Are Not

Artifacts are not the living reality itself.

They can represent, carry, reference, or activate something, but they should not replace it.

- Artifacts can represent intent, but they must not replace living intent.
- Artifacts can hold local context, but they are not context itself.
- Artifacts can represent, carry, reference, or activate memory, but they are not memory itself.
- Artifacts can support outcomes, but they are not the outcome.
- Artifacts can participate in processes, but they are not the whole process.
- Artifacts can be rendered through interfaces, but they are not the interface itself.

This distinction protects Alpha from becoming an output machine.

A plan is not the evening.

A playlist is not the atmosphere.

A dashboard is not grip.

A learning path is not learning.

A memory artifact is not the memory itself.

## Requested, Co-Shaped, And Alpha-Originated

Artifacts can originate in different ways.

### Requested

A person asks Alpha to make or shape something.

Examples:

- a plan
- a draft
- a playlist
- a learning path
- a summary
- a generated interface

### Co-Shaped

A person and Alpha shape the artifact together through conversation, correction, options, editing, or exploration.

Examples:

- a business concept
- a dinner plan
- a creative direction
- a group agreement
- a child learning artifact

### Alpha-Originated

Alpha creates an artifact because something becomes meaningful enough to hold.

This may come from:

- findings
- research
- analysis
- events
- non-events
- behavior
- repeated friction
- changed context
- open loops
- safety signals
- emerging opportunities
- unresolved decisions
- background work

Alpha-originated artifacts are allowed, but they must remain traceable, inspectable, correctable, and disposable in the broad human sense.

They may remain behind the scenes until they matter, but they must not become hidden power.

Alpha may create artifacts from meaning, not from noise.

## Artifact Core v0

The artifact core should stay small.

Core fields:

- `id`
- `family`
- `type`
- `label`
- `created_at`
- `status`
- `purpose`

### `id`

A stable identifier for accountability, reference, lineage, and control.

### `family`

The broad structural family of the artifact.

Family gives orientation.

### `type`

The concrete shape of the artifact.

Type gives form.

Examples:

- `playlist`
- `plan`
- `finding`
- `agreement`
- `draft`
- `queue_item`
- `permission_note`
- `generated_screen`
- `learning_path`

### `label`

A human handle.

The label should help a person refer to the artifact naturally.

### `created_at`

Basic origin data.

An artifact does not need a fully known context of origin, but it should remain capable of gaining one.

### `status`

A light handling status.

Status should orient handling, not become workflow management.

Possible statuses may include:

- `draft`
- `active`
- `waiting`
- `dormant`
- `archived`
- `superseded`

This list is provisional.

### `purpose`

Why the artifact exists as a handleable thing.

Purpose is not the same as intent.

Intent is the living direction.

Purpose is the artifact's supporting role.

Examples:

- `for exploration`
- `to make this intent visible`
- `to coordinate this group`
- `to preserve this finding`
- `to support a decision`
- `for transparency`
- `for play`
- `for rest`
- `for later reference`

Every artifact should be able to answer why it exists.

## Optional Local Fields

Artifacts may also include local fields when useful:

- `source`
- `primary_content`
- `summary`
- `references`
- `owner_or_scope`
- `local_context`
- `intent_ref`
- `origin_intent`

These should not be mandatory for every artifact.

Context is always relevant, but not always stored inside the artifact core.

Intent shapes artifacts, but purpose explains why the artifact exists.

## Derived Layers

Many important artifact properties should be derived by Alpha rather than stored as core artifact fields.

Derived layers may include:

- control surface
- permissions view
- visibility
- attention behavior
- lifecycle actions
- rendering
- portability
- relation view
- cost awareness
- memory association
- truthfulness or verification status
- broader contextual history
- graph relations
- lineage

Control is essential to artifacts, but the control surface is derived, not stored.

Given an artifact and its surrounding context, Alpha should determine what meaningful controls are available.

Examples:

- show why this exists
- correct this
- keep this
- hide this
- share this
- fork this
- export this
- pause this
- continue this
- do not use this later
- remove influence
- change what this means

The artifact control surface should feel like natural authority, not technical management.

## Families And Types

Families should be structural.

Domains like entertainment, gaming, shopping, food, travel, sports, wellbeing, and culture can appear as roles, contexts, content, or expressions across many artifact families.

One primary family keeps the artifact handleable.

Roles and relations keep it true.

Current artifact families v0:

1. Intent Artifacts
2. Context Artifacts
3. Outcome Artifacts
4. Process Artifacts
5. Memory Artifacts
6. Creative Artifacts
7. Social Artifacts
8. Communication Artifacts
9. Learning Artifacts
10. Economic Artifacts
11. Interface Artifacts
12. Boundary Artifacts
13. Personal Artifacts

## 1. Intent Artifacts

Intent artifacts hold a handleable interpretation of what someone, a group, or Alpha is trying to shape, explore, understand, or resolve.

The first artifact of Alpha is often the intent made handleable.

An intent artifact should never claim to be the person's true intent.

It is a current representation that can be corrected, ignored, evolved, forked, or replaced.

Examples:

- `Explore Alpha artifacts`
- `Plan a calm Saturday`
- `Understand why this project feels stuck`
- `Shape the public Alpha repo`
- `Help me feel less overwhelmed`

Intent does not always need confirmation, but consequential intent needs alignment.

## 2. Context Artifacts

Context artifacts hold findings, snapshots, patterns, relevant situations, repeated friction, non-events, or contextual readings.

They are not context itself.

They are local handles that help Alpha or a person understand what may matter.

Examples:

- recurring blocker finding
- context snapshot for a task
- source bundle for a research question
- `this used to matter in another phase`
- `this pattern keeps returning`
- `this process may be stuck because ownership is unclear`

Context artifacts may be Alpha-originated.

They may remain behind the scenes until they become relevant.

## 3. Outcome Artifacts

Outcome artifacts hold an agreed or emerging result, direction, decision, or expression of what good would look like.

They are not the outcome itself.

They help make outcome alignment visible.

Examples:

- agreed direction
- decision result
- success shape
- acceptance criteria in human language
- `what good would look like`
- a result summary

Outcome artifacts should not let Alpha confuse artifact completion with life improvement.

## 4. Process Artifacts

Process artifacts hold work in motion.

They make waiting, queues, loops, blockers, background work, intermediate results, and user input needs legible.

Examples:

- queue item
- waiting state
- work-in-progress tracker
- background task summary
- blocked process note
- intermediate result
- checkpoint summary

Process artifacts should reduce mystery without creating administrative burden.

## 5. Memory Artifacts

Memory artifacts are handleable representations of memory material.

They are not memory itself.

Memory is a broader continuity layer.

Artifacts can represent, carry, reference, or activate memory, but they are not memory itself.

Examples:

- photo collection representation
- Counter-Strike clan era representation
- goodbye moment representation
- family park day representation
- shared trip memory representation
- old playlist associated with a period of life

Memory artifacts require care around consent, context, privacy, resurfacing, and ownership.

## 6. Creative Artifacts

Creative artifacts hold becoming, not just content.

They support private trying, drafts, craft, co-creation, cultural expression, play, art, and creative development.

Examples:

- song draft
- mood board
- concept sketch
- private experiment
- public artwork draft
- game idea
- video concept
- design direction

Creative artifacts should protect the trying phase.

Not every creative artifact should become public culture, identity, training material, or monetized content.

## 7. Social Artifacts

Social artifacts hold shared plans, rituals, agreements, events, relationships, coordination, and group meaning.

Examples:

- dinner plan
- group ritual
- shared agreement
- event flow
- friend-group game night
- family visit plan
- shared birthday idea

Social artifacts may involve multiple people's consent, expectations, boundaries, and memories.

## 8. Communication Artifacts

Communication artifacts hold trusted exchange, message meaning, provenance, summaries, boundaries, and conversational continuity.

Examples:

- trusted thread
- message summary
- contact boundary
- provenance-aware note
- `who said what and under what context`
- handoff summary
- communication preference note

Communication artifacts should support consentful, trustworthy communication.

They should not recreate spam, scam, forced outreach, impersonation, or attention capture.

## 9. Learning Artifacts

Learning artifacts hold growth, explanation, exercises, curiosity, practice, reflection, and child-appropriate learning.

Examples:

- child learning path
- explanation card
- practice set
- curiosity trail
- progress reflection
- study plan
- skill-building exercise

Children require different defaults.

Child learning artifacts should support mistakes, curiosity, safety, imagination, and development without exposing children to adult burdens.

## 10. Economic Artifacts

Economic artifacts hold value and exchange without turning life into commerce.

They support budgets, demand, offers, costs, reciprocity, sponsorship, livelihood, fulfillment, and fair value exchange.

Examples:

- budget sketch
- custom product request
- sponsorship note
- value exchange
- business model sketch
- cost estimate
- cooperative funding idea
- purchase intent

Economic artifacts should not turn every human activity into monetization pressure.

## 11. Interface Artifacts

Interface artifacts are temporary rendered forms around meaning.

They may be screens, cards, voice flows, dashboards, generated tools, comparison views, or other interaction forms.

Examples:

- generated screen
- voice flow
- comparison view
- temporary dashboard
- mini-tool around an artifact
- shareable card
- visual chooser

The artifact is not trapped in the interface.

The interface is one possible rendering.

## 12. Boundary Artifacts

Boundary artifacts hold what Alpha may, may not, and must carefully explain.

They support permissions, consent, revocation, safety boundaries, child boundaries, memory boundaries, sharing boundaries, cost boundaries, and transparency.

Examples:

- permission note
- consent boundary
- `ask me first`
- child-safety boundary
- revocation record
- transparency request
- `do not use this later`
- `never share this`

Boundary artifacts should feel like natural control, not policy administration.

## 13. Personal Artifacts

Personal artifacts help Alpha understand a person without turning them into a profile.

They may hold preferences, taste, boundaries, help preferences, style, routines, rhythms, dislikes, sensitivities, and ways of being supported.

Examples:

- music taste representation
- help preference
- personal boundary
- routine or rhythm note
- `how I like to be supported`
- temporary preference
- communication preference
- creative taste marker

Personal artifacts must remain context-aware, time-aware, correctable, non-judgmental, non-punitive, and unavailable for hidden persuasion.

## Cross-Cutting Roles

Some concepts are important across many artifact families, but should not currently become top-level families.

Cross-cutting roles include:

- truthfulness
- verification
- entertainment
- gaming
- media
- culture
- safety
- sustainability
- privacy
- child-specific constraints
- cost
- provenance
- lineage
- agent operations

Truthfulness is a cross-cutting obligation, not a single artifact category.

Entertainment is essential to life, but it does not need to be a top-level artifact family right now.

It can appear through creative, personal, social, communication, interface, memory, and process artifacts.

## Structure, Roles, And Relations

An artifact should have one primary family.

It may have many roles and relations.

Example:

```json
{
  "id": "artifact_123",
  "family": "creative",
  "type": "playlist",
  "label": "Songs for the drive home",
  "created_at": "2026-06-09T13:45:00+02:00",
  "status": "active",
  "purpose": "for emotional reset after work"
}
```

This artifact might also have roles:

- entertainment
- personal
- memory-associated
- social

And relations:

- linked to a commute routine
- linked to a period of life
- linked to a friend who recommended songs
- linked to a current need for calm

The artifact stays small.

Alpha's graph carries the broader relational history.

## Composite Artifacts

Composite is a structure, not a category.

A composite artifact lets a person hold a whole situation without managing all its parts.

Examples:

- `Plan my move`
- `My Alpha concept work`
- `Our summer trip`
- `My child's learning journey`
- `This business idea`
- `Friday dinner with friends`
- `Launch this public repo`

For the person, it may feel like one thing.

For Alpha, it may be a connected subgraph of intents, contexts, processes, memories, communications, boundaries, outcomes, and artifacts.

Composite artifacts should feel like situations, not systems.

## Lineage, Forks, Merges, And Splits

Artifacts can merge and split because life does.

Artifacts should be stable enough to trust and flexible enough to fork.

An artifact can:

- be forked into another artifact
- merge with another artifact
- split into several artifacts
- be superseded by another artifact
- be represented differently in a new context
- become dormant
- regain relevance later

Alpha should preserve plurality where reality is plural, and choose currentness only where action requires it.

For some artifacts, there must be a current version:

- an active plan
- a shared agreement
- a current permission
- a process status
- a publication version

For others, many versions can coexist:

- creative drafts
- possible interpretations
- memory representations
- alternative outcomes
- design directions
- personal preference changes
- mood playlists

## Visibility And Attention

Artifacts should be share-capable, not share-default.

An artifact can exist without demanding attention.

Visibility should match context, consent, and consequence.

Artifacts may be:

- background
- askable
- visible to the person
- visible when relevant
- visible to a group
- hidden
- archived
- public by deliberate action
- redacted

Artifacts should also respect attention as part of care.

Some artifacts should remain quiet.

Some should surface only in context.

Some should ask for attention only when consequence requires it.

## Portability And Import

Artifacts should be portable where portability does not violate care.

People should be able to export, archive, share, or move artifacts when appropriate.

Portability must respect:

- ownership
- shared consent
- privacy
- redaction
- context boundaries
- provenance
- deletion or revocation
- law

Imported material becomes Alpha-shaped only through context, consent, and use.

Import is not consent for everything.

## Cost And Effort

Artifacts should help Alpha spend effort where meaning justifies it.

Cost does not only mean money.

It can include:

- compute
- time
- attention
- storage
- carbon impact
- social cost
- maintenance burden
- complexity

Cost awareness should not become a technical dashboard by default.

It should appear when it helps the person choose well.

## Human Explainability

Artifacts do not need to be fully human-readable, but they must be human-explainable.

Alpha should be able to explain:

- what this artifact is
- why it exists
- what shaped it
- what it may affect
- what Alpha may do with it
- what the person can do with it

## Working Sentences

> Artifacts make meaning handleable.

> An artifact is a small accountable handle, surrounded by graph, context, permissions, and rendering.

> Alpha should measure artifacts by the life they help, not by their existence.

> Intent shapes artifacts, but purpose explains why the artifact exists.

> Artifacts should be stable enough to trust and flexible enough to fork.

> Artifacts can merge and split because life does.

> Artifacts can represent, carry, reference, or activate memory, but they are not memory itself.

> Artifacts can hold local context, but they are not the context itself.

> Artifacts can represent intent, but they must not replace the living intent.

> Artifacts may support outcomes, but they are not the outcome.
