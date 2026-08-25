# Decisions

This directory contains **formal decision records** for the AgilityAI
Brazil Reference Implementation Program.

Its purpose is to maintain traceability of decisions that affect the
project, methodology, architecture, implementation, engineering
standards, or technical direction.

## What belongs here

A document belongs in this directory when it records a decision that has
been explicitly agreed, approved, or validated by the appropriate
project stakeholders.

Examples:

-   approved project decisions;
-   validated methodology decisions;
-   technical or architectural decisions;
-   agreed implementation approaches;
-   approved standards or conventions;
-   decisions resulting from AI Labs alignment;
-   decisions that change or clarify how the Brazil implementation
    should proceed.

## What does NOT belong here

Do not use this directory for:

-   meeting transcripts;
-   meeting notes that primarily record discussion, planning,
    assignments, or open questions;
-   personal interpretations;
-   assumptions;
-   investigation material;
-   gap assessments;
-   proposed artifacts awaiting validation;
-   general project documentation;
-   EAP/WBS working revisions.

Use the appropriate directory instead:

-   `../meetings/` for meeting notes, EAP review records, conversations
    and contextual records;
-   `../assessments/` for investigations, gap assessments and analysis;
-   `../framework/` for AgilityAI framework source material;
-   `../program/` for formal program documentation and the current
    EAP/WBS;
-   `../knowledge/` for supporting knowledge and reference material.

A meeting record may reference a decision, but the decision should only
be promoted to this directory when its status and authority are
sufficiently clear.

## Decision status

When applicable, decision records should clearly identify their status:

-   `PROPOSED` --- under discussion and not yet approved;
-   `VALIDATED` --- reviewed and accepted by the appropriate
    stakeholders;
-   `SUPERSEDED` --- replaced by a newer decision;
-   `CANCELLED` --- explicitly withdrawn.

Only `VALIDATED` decisions should normally be treated as established
project direction.

## Recommended decision record

Each decision document should contain, when applicable:

-   Title
-   Date
-   Status
-   Context
-   Decision
-   Rationale
-   Impact
-   Participants / Decision makers
-   Related sources
-   Related artifacts
-   Open follow-ups

## Source and authority rules

-   A meeting statement is not automatically a project decision.
-   A planning estimate is not automatically a delivery commitment.
-   A working EAP change is not automatically an approved methodology
    definition.
-   A recommendation generated during analysis is not automatically a
    project decision.
-   A proposed Brazil artifact is not automatically an official
    AgilityAI artifact.
-   Technology names discussed in meetings are not automatically
    approved architecture choices.

When there is uncertainty about whether something has been formally
decided, keep it outside this directory until validation is obtained.

## Traceability

When a validated decision originates from a meeting or EAP review:

1.  keep the original meeting record under `../meetings/`;
2.  create a separate decision record here;
3.  reference the source meeting/EAP in `Related sources`;
4.  record the impact on architecture, methodology, implementation or
    planning;
5.  mark later replacements as `SUPERSEDED` rather than deleting
    historical decisions.
