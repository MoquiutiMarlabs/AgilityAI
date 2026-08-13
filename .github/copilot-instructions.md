# AgilityAI Repository Instructions

This repository is part of the AgilityAI Brazil Reference Implementation Program.

## General principles

- Treat repository documentation as the primary source for project-specific requirements.
- Do not invent requirements, architecture decisions, technologies, APIs, processes, or business rules that are not documented.
- Clearly distinguish between:
    - documented requirement;
    - existing repository convention;
    - technical inference;
    - technical recommendation;
    - missing information.
- If project documentation is incomplete, state the limitation before making assumptions.
- Never present a recommendation as an official AgilityAI or Marlabs requirement.

## Repository context

The repository may contain:

- AgilityAI framework documentation;
- Project Charter and program documentation;
- architecture decisions;
- technical specifications;
- implementation artifacts;
- source code;
- tests;
- meeting notes;
- proposed artifacts;
- approved artifacts.

Respect the authority and status of each source.

Formal project documentation and approved technical decisions take precedence over drafts, proposals, meeting notes, and generated recommendations.

## Engineering behavior

Before making meaningful code changes:

1. inspect the existing repository structure;
2. identify related code and documentation;
3. understand existing patterns and conventions;
4. avoid introducing unnecessary dependencies or frameworks;
5. prefer the smallest coherent solution;
6. preserve backward compatibility unless a breaking change is explicitly required.

Do not perform unrelated refactoring while implementing a specific task.

## Code quality

Prefer:

- readable and maintainable code;
- clear naming;
- modular design;
- separation of concerns;
- explicit error handling;
- secure defaults;
- testability;
- observability;
- low coupling;
- cohesive components;
- documented public contracts;
- minimal unnecessary complexity.

Avoid:

- overengineering;
- premature abstraction;
- silent failures;
- hardcoded secrets;
- duplicated business logic;
- unnecessary dependencies;
- speculative features.

## Java development

When Java is used:

- follow the Java version and framework already defined by the project;
- use modern language features only when compatible with the configured runtime;
- prefer constructor injection where dependency injection is used;
- use domain-oriented class and method names;
- avoid unnecessary static mutable state;
- handle exceptions intentionally;
- preserve existing package and architectural conventions;
- add or update tests when behavior changes.

Do not assume Spring Boot, Maven, Gradle, Lombok, MapStruct, or any other framework/tool unless it is already defined or explicitly requested.

## Agentic AI and LLM development

When implementing AI agents, LLM workflows, or RAG:

- separate deterministic business logic from probabilistic model behavior;
- treat model output as untrusted input until validated;
- prefer structured outputs when appropriate;
- make prompts and agent instructions versionable;
- define retry, timeout, fallback, and failure behavior;
- consider Human-in-the-Loop for consequential actions;
- avoid uncontrolled autonomous loops;
- protect secrets and sensitive data;
- consider latency, token usage, cost, observability, and auditability;
- make external side effects explicit.

## Architecture decisions

For significant technical decisions:

- identify the problem and constraints;
- inspect existing implementation;
- compare reasonable alternatives;
- explain trade-offs;
- recommend the option best suited to the actual project context;
- document significant decisions when appropriate.

Popularity alone is not sufficient justification for adopting a technology.

## Security

Never commit:

- passwords;
- API keys;
- access tokens;
- private keys;
- production credentials;
- sensitive secrets.

Use the repository's secure configuration approach, environment variables, or an appropriate secret-management solution.

Treat external input, generated content, and model responses as potentially unsafe until validated.

## Testing and validation

When changing behavior:

- update or add relevant tests;
- validate expected and error scenarios;
- preserve existing tests unless requirements changed;
- do not declare work complete if known tests are failing.

When project build or test commands are documented, use those commands instead of inventing alternatives.

## Documentation

Update documentation when changes affect:

- APIs;
- architecture;
- configuration;
- setup;
- runtime behavior;
- operational procedures;
- technical decisions.

Clearly label proposed or draft artifacts when they are not yet approved.

## AgilityAI alignment

Technical work should support, when applicable:

- repeatability;
- measurable value;
- reusable patterns;
- enterprise integration;
- governance;
- security;
- scalability;
- observability;
- operational reliability.

These are engineering goals, not automatic mandates for specific tools or architectures.

## Communication

For meaningful technical changes, explain:

- current state;
- proposed change;
- reason;
- risks or trade-offs;
- validation performed.

For simple tasks, respond directly and avoid unnecessary explanation.

When uncertain, state what is known, what is missing, and what assumption is being used.