# Protocol-Native Provider-Agnostic Alpha

Status: foundational architecture principle.

This document defines a constitutional law of Alpha:

> Alpha is protocol-native and provider-agnostic.

Or:

> Alpha depends on contracts, not providers.

And:

> Providers may power Alpha, but protocols define Alpha.

This is not a feature.

It is not a later engineering preference.

It is a condition for Alpha to remain sovereign, durable, safe, and buildable in a world where AI providers, models, tools, agent harnesses, databases, interfaces, and runtimes will keep changing.

## Core Principle

Everything in Alpha should be built around:

- open contracts
- safe protocols
- interchangeable capabilities
- portable representations
- scoped permissions
- inspectable behavior
- adapter boundaries
- testable interfaces
- graceful fallback

No provider, model, tool, harness, database, interface, runtime, cloud, or framework should become Alpha's identity or single point of dependency.

Alpha may use powerful providers.

Alpha may use current models.

Alpha may use agent harnesses, CLIs, browsers, local tools, cloud services, vector stores, media generators, speech systems, and future execution environments.

But all of them are replaceable participants.

They are not Alpha.

## Why This Matters

The current AI world is unstable.

Models change quickly.

Providers rise, fall, merge, degrade, improve, change prices, change policies, change latency, change safety behavior, change APIs, and change what they are willing to support.

If Alpha becomes tightly coupled to one provider's strengths, limitations, pricing, policy, interface, or worldview, Alpha becomes fragile.

Worse: Alpha's values could silently become the provider's values.

That cannot happen.

Alpha's core must live in its own protocols, contracts, artifacts, Life Graph, permissions, transparency, safety boundaries, and alignment rules.

Models should execute capabilities.

They should not define the paradigm.

Agents should also remain identifiable.

Alpha may use many agents, sub-agents, harnesses, and model-backed workers, but they must not collapse into one vague `Agent`.

Each agent or sub-agent should have a scoped identifier, capability contract, authority scope, lineage, and Activity context.

This matters because intent, provenance, responsibility, and rollback depend on knowing which actor did what.

## Providers Are Adapters

Every external intelligence or execution system should enter Alpha as an adapter behind a capability contract.

An adapter may provide:

- language reasoning
- multimodal understanding
- speech
- image generation
- video generation
- search
- retrieval
- coding
- browser control
- local automation
- scheduling
- messaging
- payments
- storage
- verification
- translation
- summarization
- planning
- tool execution

But Alpha should interact with the capability, not with the provider identity as the core abstraction.

The question should be:

> What capability is needed here, under what contract, with what permissions and consequences?

Not:

> What can this one provider do?

## Capability Contracts

Capability contracts describe what a provider, tool, model, agent, or service can do for Alpha.

A capability contract should make clear:

- what capability is offered
- what inputs are allowed
- what outputs are expected
- what data may be exposed
- what permissions are required
- what context is necessary
- what context must be withheld
- what cost may be incurred
- what latency is expected
- what provenance is attached
- what failure modes exist
- what fallback exists
- what must be validated before becoming consequential

Capability contracts should be model-neutral.

They should be usable by large models, small models, local models, deterministic services, human review, rule engines, or future systems.

## Protocols Before Providers

Alpha protocols should define:

- how intent is represented
- how context is scoped
- how artifacts are described
- how permissions travel
- how Activity reports condition
- how memories are referenced without being exposed
- how Alpha-originated findings are made inspectable
- how actions are proposed, approved, executed, reversed, or refused
- how Alphas communicate with each other
- how models and tools receive only what they are allowed to receive

Providers can implement or participate in these protocols.

They should not replace them.

## Alpha-To-Alpha Communication

Alpha systems should eventually be able to communicate with each other.

This must not mean exposing a person's raw Life Graph, memory, preferences, identity, schedule, messages, or private context.

Alphas should communicate through consentful, purpose-bound envelopes.

Core rule:

> Alphas should communicate through consentful, purpose-bound envelopes, never by exposing the person behind them.

For example, two Alphas coordinating dinner should not exchange raw calendars or personal reasons.

They may exchange:

- availability windows
- dietary constraints if consented
- relevant boundaries
- proposed options
- shared artifact references
- accepted next steps

They should avoid exposing:

- private memories
- unrelated schedule details
- sensitive reasons
- personal graph structure
- hidden preferences
- relationship context not needed for the purpose
- child data unless explicitly and safely scoped

The communication layer should support:

- minimum necessary disclosure
- redaction
- provenance
- consent
- revocation
- purpose limitation
- scoped identity
- verification
- auditability
- safe refusal

## Life Graph Boundary

The Life Graph is the connected layer of your life in Alpha.

It should never be treated as raw material for providers.

Models, tools, agents, and other Alphas may receive scoped representations, never full access by default.

The Life Graph can provide:

- filtered context
- artifact references
- relevant boundaries
- permission-scoped summaries
- Activity
- purpose-bound envelopes

It should not leak:

- full personal history
- raw memories
- unrelated preferences
- private relationship context
- sensitive child data
- hidden graph structure
- cross-context details

## CLI And Tooling Direction

Alpha should be friendly to CLI tooling, local tooling, automated tests, and contract validation from the beginning.

This matters because provider-agnostic systems need inspectable boundaries.

Future Alpha tooling should make it easy to:

- validate artifacts
- validate envelopes
- test capability contracts
- swap providers
- run local providers
- inspect Activity
- replay safe traces
- verify permission boundaries
- simulate Alpha-to-Alpha exchange
- run conformance tests
- detect provider-specific leakage
- measure cost, latency, and failure behavior

CLI-first does not mean terminal-first user experience.

It means the underlying system should be scriptable, testable, inspectable, and portable.

## What This Refuses

Alpha should refuse:

- provider lock-in as architecture
- model-specific behavior as identity
- hidden dependency on one AI company's worldview
- protocols that only work with one provider
- artifacts that cannot be exported or interpreted outside one runtime
- memory systems that require one cloud
- agent workflows that cannot be inspected or swapped
- Alpha-to-Alpha communication by raw data sharing
- prompts as the only source of truth
- brittle behavior that depends on one model's current quirks

## What This Allows

Provider-agnostic does not mean provider-hostile.

Alpha can still use the best available tools.

It can use:

- strong frontier models
- small local models
- specialized models
- deterministic services
- human review
- provider SDKs
- agent harnesses
- browsers
- CLIs
- databases
- search systems
- media generators
- speech systems

But each should sit behind contracts and protocols.

Alpha should be able to replace one without rewriting the concept.

## Working Sentences

> Alpha is protocol-native and provider-agnostic.

> Alpha depends on contracts, not providers.

> Providers may power Alpha, but protocols define Alpha.

> Providers are replaceable. Protocols are constitutional.

> Models are workers, not the identity of Alpha.

> Alphas should communicate through consentful, purpose-bound envelopes, never by exposing the person behind them.
