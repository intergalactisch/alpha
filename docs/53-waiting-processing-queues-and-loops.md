# Waiting, Processing, Queues And Loops

Status: conceptual system behavior layer.

Alpha is dynamic.

Dynamic systems take time.

Even in a future shaped by AI, people will still wait for things:

- loading
- processing
- generating
- rendering
- arranging
- checking
- coordinating
- waiting on another system
- waiting on another person
- waiting on approval
- waiting on physical-world fulfillment

Alpha should handle waiting as part of the experience, not as a failure of the experience.

## The Core Principle

Waiting should be legible, calm, and under control.

The person should be able to understand:

- what is happening
- what is already done
- what is still being worked on
- what is waiting
- how long it has been going
- what might happen next
- whether anything needs their attention
- whether they can leave and return
- whether they can cancel, pause, change, or reprioritize

The old pattern is:

> spinner, blank screen, mystery, timeout, error.

The Alpha pattern is:

> living process state, clear next step, preserved work, respectful waiting.

## Loading Is Not Enough

A loading spinner only says:

> something is happening.

Alpha often needs to say more:

> I am shaping the first version.

> I am waiting for the image to render.

> I have finished the outline and am checking the sensitive parts.

> This is queued behind two other tasks.

> I need your approval before sending this.

> This may take a while, but you can leave and I will keep the work safe.

Progress should be meaningful.

It should not be fake precision.

Alpha should avoid pretending to know exact timing when it does not.

## Process Objects

Alpha needs a concept of a process object.

A process object is a living representation of something underway.

It may include:

- intent being served
- current task
- current state
- started time
- elapsed time
- approximate expectation
- dependencies
- blockers
- required user input
- queue position
- required approvals
- artifacts being created
- tools or agents involved
- last meaningful update
- next likely step
- cancellation state
- recovery state
- who or what is affected

The person should not need to manage the process object.

But Alpha should be able to show or explain it when helpful.

## Process Views

Alpha should support multiple levels of process visibility.

### Local Process View

For one intent, task, artifact, or outcome, Alpha should be able to show:

- what is happening here
- what is done
- what is waiting
- what needs approval
- what can be changed
- whether the person can leave
- what the next step is

This helps when someone is focused on one thing.

### Calm State-Of-Life Overview

When several things are in motion, Alpha should also be able to provide a calm overview.

This might include:

- what is running
- what is waiting
- what needs attention
- what is ready to review
- what has completed
- what is blocked
- what can be cancelled
- what is no longer relevant

This should not become a productivity dashboard by default.

It should appear when it helps the person regain clarity, trust, or control.

The tone should be:

> here is what is in motion.

Not:

> here is everything you are failing to manage.

## Queue Objects

Alpha may need queues.

Queues are useful when:

- several tasks are running
- one task depends on another
- a slow tool or model is processing
- external services are involved
- a person has multiple outcomes in motion
- physical-world fulfillment is involved
- a group is coordinating actions
- a child-safe or high-risk review is needed

A queue should not feel like bureaucracy.

It should feel like:

> Alpha knows what is in motion.

Queues should make it easy to:

- see what is next
- reorder when appropriate
- pause
- cancel
- resume
- merge related work
- split work
- mark something as no longer relevant
- understand why something is waiting

## Reprioritization

Alpha may suggest reprioritization when context changes.

This can happen when:

- something becomes urgent
- something is blocked
- something becomes irrelevant
- a deadline appears
- a dependency changes
- a person joins or leaves
- a high-consequence action needs attention
- a low-impact task can safely wait
- the user's stated intent changes

Alpha should explain the reason lightly:

> This is waiting on approval, while the draft can continue. Want me to move the draft first?

or:

> This looks less relevant now that you changed direction. Should I pause it?

For low-impact work, Alpha may reorder within agreed boundaries.

For high-impact work, Alpha should ask.

The user must be able to override.

The Alpha-shaped rule:

> suggest, explain, let the user override.

## Loops

Some Alpha work is not one-and-done.

It happens in loops:

- create draft
- review
- revise
- wait for approval
- send
- observe result
- adapt

Or:

- generate option
- user changes direction
- Alpha re-clusters context
- new form appears
- result is checked
- memory is updated or not

Loops are natural in dynamic systems.

They should not feel like being trapped.

An Alpha-shaped loop should have:

- visible purpose
- clear exit
- preserved state
- user control
- meaningful progress
- graceful recovery
- no endless prompting
- no forced engagement

The user should always be able to ask:

> Where are we in this?

## Waiting For User Input

Waiting for user input is a valid process state.

It is not automatically a failure, delay, or broken flow.

Some things should take longer because the person's input matters.

Alpha should not rush past meaningful input just to keep the process moving.

When a process needs input, Alpha should be able to hold it calmly:

- what input is needed
- why it matters
- what can continue without it
- what should wait
- whether the person can return later
- whether the process is safe to leave open
- what will happen if the input never arrives

The task system should support open input dependencies.

It should not treat every unanswered question as abandonment.

It should not silently choose defaults when the person's direction matters.

The Alpha-shaped rule:

> waiting for the person can be care, not friction.

## Useful Checkpoints

Longer processes should be able to expose useful intermediate results.

Intermediate results matter because they let the person:

- steer direction
- correct assumptions
- change tone
- stop early
- choose between paths
- prevent wasted work
- stay in command
- feel that the outcome is still theirs

This is especially useful for:

- creative work
- learning
- design
- planning
- writing
- media generation
- business preparation
- complex coordination
- generated interfaces or tools

But Alpha should not show noisy half-work just because something exists.

Checkpoints should be meaningful.

They should help the person shape the result.

For sensitive or high-consequence processes, Alpha may need to wait until a checkpoint is safe and coherent enough to review.

The Alpha-shaped rule:

> show useful checkpoints, not noisy half-work.

## Checkpoint Types

Not every checkpoint should stop the process.

Alpha should distinguish:

### Preview

A preview shows where the work is.

It does not require a response.

Example:

> I have the rough structure. I am continuing with the examples now.

### Steer-Point

A steer-point is useful when the person's direction could improve the result.

It invites feedback.

Sometimes it can continue without a response.

Sometimes it should wait.

If the person's input matters to the quality, meaning, safety, tone, or direction of the outcome, Alpha should hold the process open rather than assume.

Example:

> This can become more playful or more practical. Which direction feels better?

If independent work can continue without crossing the steer-point, Alpha may continue that independent work.

But it should not cross the decision itself without the user's input unless a default has been agreed or the consequence is clearly low.

### Approval Gate

An approval gate is required when the next step has consequence.

Alpha should wait.

Examples:

- sending a message
- spending money
- publishing
- sharing memory
- deleting
- changing permissions
- involving children
- committing to business, legal, health, financial, or institutional action

The Alpha-shaped rule:

> previews inform, steer-points may wait, approval gates must wait.

## States

Alpha should have human-readable process states.

Possible states:

- not started
- thinking
- clarifying
- waiting for context
- waiting for user input
- waiting for decision
- queued
- preparing
- generating
- rendering
- checking
- waiting for approval
- waiting for another person
- waiting for another system
- paused
- blocked
- retrying
- partially complete
- ready to review
- complete
- cancelled
- safely failed
- stale
- sleeping
- abandoned

These states should be simple enough for people.

They do not need to expose internal system state.

They should explain reality, not machinery.

## Stale, Sleeping, Blocked, And Abandoned

Long-running or old processes need nuance.

Not every old process is abandoned.

Some things are:

- stale: old enough that context may have changed
- sleeping: intentionally left quiet for later
- paused: stopped by the user or context, but still relevant
- blocked: unable to continue without something specific
- abandoned: no longer meaningful or intentionally left behind

Alpha should not silently delete old intent.

It may gently surface old or stuck processes when useful:

> This has been quiet for a while. Is it still alive, sleeping, or should I let it go?

or:

> This is still waiting on your input. Want to keep it open, pause it, or close it?

The user should be able to:

- keep open
- pause
- sleep
- resume
- archive
- delete
- mark no longer relevant
- update the intent
- reconnect the process to a new context

Alpha should not shame stale work.

Old does not mean failed.

Sometimes life moved.

Sometimes the timing changed.

Sometimes something should remain unfinished.

The Alpha-shaped rule:

> old processes should be revisable, not accusatory.

## Time And Estimates

Alpha should understand time honestly.

It may know:

- exact elapsed time
- approximate remaining time
- no reliable estimate
- whether something is unusually slow
- whether waiting is due to a queue, tool, network, person, permission, or external system

Alpha should not fake certainty.

Better:

> This has been running for about two minutes. I do not have a reliable estimate yet, but the render is still active.

Than:

> 37 seconds remaining.

when that number is invented.

## Media-Agnostic Progress

Progress should be available in the medium that fits.

Progress does not need to be live-visible all the time.

The rule:

> always available, not always displayed.

Alpha should be able to show or explain process state whenever it helps.

But low-impact work can often continue quietly in the background.

Status should become more visible when:

- the wait is long
- the consequence is high
- approval is needed
- money, messages, publishing, memories, children, permissions, or external systems are involved
- the person might wonder whether work is safe
- a delay becomes unusual
- the person asks
- the process is blocked
- the next step needs a decision

On a screen, Alpha may show:

- status cards
- queue lists
- progress steps
- artifacts in progress
- dependency maps
- approval gates
- elapsed time
- restart/cancel controls

In conversation, Alpha may say:

> I am still working on the draft. The outline is done; I am checking the tone now.

In audio, Alpha may give short updates or stay quiet until needed.

In a no-screen moment, Alpha may let the person leave and return later.

The medium should be rich enough to help well.

## Background Work

Alpha should support background work.

Not everything should require the person to watch.

When appropriate, Alpha should allow:

- start and leave
- notify only when useful
- return later
- keep work preserved
- summarize what changed
- continue from the last state
- stop quietly when the intent no longer matters

But background work must remain bounded.

Alpha should not use background work as a way to hide autonomy.

The person should be able to ask:

> What are you working on right now?

and:

> Stop that.

## Waiting And Trust

Waiting is a trust moment.

If Alpha is vague while waiting, people may feel:

- ignored
- trapped
- unsure whether work is safe
- unsure whether money or messages were sent
- unsure whether data was lost
- tempted to retry and duplicate work

Alpha should prevent this.

It should clarify:

- no action has been taken yet
- draft saved
- message not sent
- payment not made
- memory not shared
- task is still running
- approval is needed
- safe to leave
- safe to retry

## Queues And Consequence

High-consequence tasks need stronger visibility.

Examples:

- spending money
- sending a message
- publishing
- sharing memories
- deleting
- changing permissions
- involving children
- business, legal, health, financial, or institutional actions

For these, Alpha should show or say:

- what is queued
- what approval is needed
- what will happen if approved
- what has not happened yet
- what can still be changed

Low-consequence tasks can be lighter.

Again:

> process friction should match process consequence.

## Failure, Delay, And Recovery

If something is delayed or stuck, Alpha should not wait forever silently.

It should know when to:

- keep waiting
- retry
- switch tool
- simplify
- ask for help
- mark blocked
- preserve work
- explain the delay
- offer to continue later
- cancel cleanly

This connects to graceful failure.

Delay is not always failure.

But unexplained delay becomes distrust.

## What Alpha Must Avoid

Alpha must avoid:

- blank waiting
- fake progress
- hidden queues
- infinite spinners
- duplicate actions from unclear state
- sending or spending while the user thinks it is still waiting
- losing work during generation
- hiding background autonomy
- making the user manage technical jobs
- notifying too often
- staying silent when consequence is high
- making processing feel like being trapped

## Pressure Point

Question:

> If Alpha shows process state, does it become a task manager or technical dashboard?

Recommended answer:

> It can, if process state becomes the center. Alpha should show process state only as much as needed for trust, control, and calm. The goal is not to manage tasks. The goal is to make dynamic shaping legible while preserving agency.

## Current Working Definition

Alpha-shaped waiting means:

> Dynamic work may take time, but the person should never be left inside mystery. Alpha should keep process state legible, controllable, resumable, and calm.
