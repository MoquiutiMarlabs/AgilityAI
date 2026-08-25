# AgilityAI Repository Instructions

This repository is part of the **AgilityAI Brazil Reference
Implementation Program**.

## General principles

-   Treat repository documentation as the primary source for
    project-specific requirements.
-   Do not invent requirements, architecture decisions, technologies,
    APIs, processes, business rules, or delivery commitments.
-   Clearly distinguish between:
    -   documented requirement;
    -   validated decision;
    -   current EAP/planning direction;
    -   existing repository convention;
    -   technical inference;
    -   technical recommendation;
    -   missing information.
-   If documentation is incomplete, state the limitation before making
    assumptions.
-   Never present a recommendation as an official AgilityAI or Marlabs
    requirement.

## Source authority

Respect the authority and status of each source.

Use this precedence when sources conflict:

1.  formal program documentation and validated decisions;
2.  approved technical specifications and architecture;
3.  current EAP/WBS planning artifacts;
4.  framework/reference documentation;
5.  meeting records;
6.  assessments, working drafts and proposals;
7.  generated technical recommendations.

A meeting statement is not automatically a decision. A planning estimate
is not automatically an engineering commitment. A technology mentioned
in a meeting is not automatically an approved architecture choice.

Repository content may include:

-   AgilityAI framework documentation;
-   Project Charter and program documentation;
-   EAP/WBS planning artifacts;
-   formal decision records;
-   technical specifications;
-   implementation artifacts;
-   source code and tests;
-   meeting/EAP review notes;
-   assessments and gap registers;
-   proposed and approved artifacts.

## Repository organization

When applicable:

-   `docs/decisions/` --- formal validated/proposed decision records
    according to its README;
-   `docs/meetings/` --- meeting notes, EAP reviews, contextual records
    and discussion history;
-   `docs/assessments/` --- investigations, gap assessments and
    analysis;
-   `docs/framework/` --- AgilityAI framework source/reference material;
-   `docs/program/` --- formal program documents and current EAP/WBS;
-   `docs/knowledge/` --- supporting knowledge/reference material.

Do not promote meeting notes or working EAP discussions into formal
decisions without sufficient validation.

## Engineering behavior

Before meaningful code changes:

1.  inspect the repository structure;
2.  identify related code and documentation;
3.  understand existing patterns and conventions;
4.  identify scope and dependencies;
5.  avoid unnecessary dependencies/frameworks;
6.  prefer the smallest coherent solution;
7.  preserve backward compatibility unless explicitly changed.

Do not perform unrelated refactoring.

## Development readiness and estimates

Do not treat an abstract EAP activity as sufficient implementation
scope.

Before committing to a development estimate or substantial
implementation, verify that sufficient information exists regarding, as
applicable:

-   use case/business objective;
-   functional scope;
-   architecture;
-   principal diagrams/flows;
-   integrations/APIs;
-   data/persistence;
-   non-functional requirements;
-   acceptance/validation criteria.

If these inputs are missing, state the dependency. Technical discovery,
guidelines, prototypes and architecture work may continue when their own
scope is clear.

Never convert rough meeting estimates directly into committed
development estimates.

## Current Development context

The working EAP may organize Development through stages such as:

1.  Assets Repository
2.  Preparation and Validation
3.  Database
4.  Model or Prompt
5.  Workflow
6.  API
7.  Application

Treat this as a working planning structure unless the current EAP or a
validated decision makes it authoritative.

Prompt/model engineering, workflow development, accelerators and
platform technologies discussed in meetings are likewise not
automatically mandatory architecture.

## Reuse before creation

Before creating a new framework, accelerator, reusable component,
template or implementation asset:

1.  inspect the repository for existing equivalents;
2.  check documented AI Labs assets/references available to the project;
3.  determine whether to adopt, adapt, extend or create;
4.  avoid duplicating existing work.

Reusable components should be driven by concrete implementation needs
and productization goals, not speculative abstraction.

## Code quality

Prefer:

-   readable and maintainable code;
-   clear naming;
-   modular design;
-   separation of concerns;
-   explicit error handling;
-   secure defaults;
-   testability;
-   observability;
-   low coupling;
-   cohesive components;
-   documented public contracts;
-   minimal unnecessary complexity.

Avoid:

-   overengineering;
-   premature abstraction;
-   silent failures;
-   hardcoded secrets;
-   duplicated business logic;
-   unnecessary dependencies;
-   speculative features.

## Java development

When Java is used:

-   follow the Java version and framework defined by the project;
-   use modern features only when compatible with the runtime;
-   prefer constructor injection where dependency injection is used;
-   use domain-oriented names;
-   avoid unnecessary static mutable state;
-   handle exceptions intentionally;
-   preserve package and architectural conventions;
-   add/update tests when behavior changes.

Do not assume Spring Boot, Maven, Gradle, Lombok, MapStruct or another
framework/tool unless already defined or explicitly requested.

## Agentic AI and LLM development

When implementing AI agents, LLM workflows or RAG:

-   separate deterministic logic from probabilistic model behavior;
-   treat model output as untrusted until validated;
-   prefer structured outputs when appropriate;
-   make prompts/instructions versionable;
-   define retry, timeout, fallback and failure behavior;
-   consider Human-in-the-Loop for consequential actions;
-   avoid uncontrolled autonomous loops;
-   protect secrets and sensitive data;
-   consider latency, token usage, cost, observability and auditability;
-   make external side effects explicit.

## Architecture decisions

For significant technical decisions:

-   identify the problem, scope, constraints and dependencies;
-   inspect existing implementation and relevant documentation;
-   compare reasonable alternatives;
-   explain trade-offs;
-   recommend the option best suited to actual project context;
-   document the decision when formally validated.

Popularity alone is not sufficient justification for a technology.

## Security

Never commit:

-   passwords;
-   API keys;
-   access tokens;
-   private keys;
-   production credentials;
-   sensitive secrets.

Use the repository's secure configuration approach, environment
variables, or an appropriate secret-management solution.

Treat external input, generated content and model responses as
potentially unsafe until validated.

## Testing and validation

When changing behavior:

-   update/add relevant tests;
-   validate expected and error scenarios;
-   preserve existing tests unless requirements changed;
-   do not declare work complete if known tests are failing.

When build/test commands are documented, use them instead of inventing
alternatives.

## Documentation

Update documentation when changes affect:

-   APIs;
-   architecture;
-   configuration;
-   setup;
-   runtime behavior;
-   operational procedures;
-   technical decisions.

Clearly label draft/proposed artifacts that are not approved.

## AgilityAI alignment

Technical work should support, when applicable:

-   repeatability;
-   measurable value;
-   reusable patterns;
-   enterprise integration;
-   governance;
-   security;
-   scalability;
-   observability;
-   operational reliability;
-   productization.

These are engineering goals, not automatic mandates for specific tools
or architectures.

## Communication

For meaningful technical changes, explain:

-   current state;
-   proposed change;
-   reason;
-   dependencies;
-   risks/trade-offs;
-   validation performed.

For simple tasks, respond directly.

When uncertain, state what is known, what is missing and what assumption
is being used.
