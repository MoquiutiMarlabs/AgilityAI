# AgilityAI Brazil --- Knowledge Guide

**Purpose:** navigation and interpretation guide for the knowledge base
of the AgilityAI Brazil Reference Implementation Program.\
**Status:** supporting guide; **not an official Marlabs or AgilityAI
source**.\
**Rule:** when this guide conflicts with a primary source, the primary
source prevails.

------------------------------------------------------------------------

## 1. Purpose of this guide

This file helps the AgilityAI GPT identify:

-   which source to consult for each type of question;
-   the role and authority of each document;
-   the difference between documented fact, meeting context, inference,
    recommendation and gap;
-   known ambiguities and transcription risks;
-   the relationship between the Brazil program phases and the Align,
    Build and Control framework;
-   known gaps that should not be silently filled;
-   how new project documents should be incorporated.

This guide does **not** replace the original documents and must not be
cited as evidence that a requirement, decision or definition is
official.

------------------------------------------------------------------------

## 2. Current knowledge base

### 2.1 Project Charter --- AgilityAI Brazil Reference Implementation Program

**Role:** primary formal source for the Brazilian program.

Use it primarily for:

-   program vision and objectives;
-   executive sponsorship and project organization;
-   duration and budget assumptions;
-   scope;
-   phases of execution;
-   major deliverables;
-   success criteria;
-   risks and mitigations;
-   expected benefits;
-   productization and go-to-market direction.

Key program intent documented in the Charter:

-   transform the global AgilityAI framework into a repeatable,
    market-ready professional service for Brazil;
-   use Marlabs Brazil as the first real-world/reference implementation;
-   validate the framework in practice;
-   identify implementation gaps;
-   collaborate with AI Labs on improvements;
-   create methodology, playbooks and reusable assets;
-   measure operational improvements and ROI;
-   prepare a commercial AI Transformation offering.

The internal transformation is therefore both an implementation and a
validation environment.

**Authority:** high for the Brazilian program.

**Important limitation:** the Charter defines objectives, scope and
expected outcomes, but does not necessarily define every technical
implementation detail, template, technology or operational procedure.

------------------------------------------------------------------------

### 2.2 AgilityAI --- ABCs

**Role:** primary framework/reference material for AgilityAI.

Use it primarily for:

-   AgilityAI conceptual structure;
-   Align, Build and Control;
-   strategic roadmap;
-   AI maturity/evolution stages;
-   AI engineering lifecycle;
-   governance operating model;
-   AI Labs accelerators;
-   business positioning and expected advantages;
-   recommended next steps for an AI transformation engagement.

#### ALIGN

Covers organizational and strategic preparation, including:

-   Strategy & Use Cases;
-   Process & Data Readiness;
-   AI Governance & Enablement;
-   vision and use-case prioritization;
-   strategic roadmap and ROI;
-   process transformation;
-   data readiness and target-state architecture;
-   policy/risk frameworks;
-   change management;
-   talent strategy and training.

#### BUILD

Covers implementation and engineering, including:

-   Proof of Concept / Proof of Value;
-   AI-assisted engineering;
-   AI SDLC;
-   model evaluation;
-   MLOps / LLMOps;
-   scalable forward deployments;
-   reusable frameworks;
-   Agentic AI accelerators;
-   modular architecture and enterprise integration;
-   domain accelerators.

AI Labs accelerators named in the current presentation include:

-   PromptRouter®;
-   Data Migration;
-   Call Center Analysis;
-   HR Support Virtual Agent;
-   App Mapping & Development;
-   Chat to Enterprise.

The existence of an accelerator does **not** automatically mean it is
mandatory or selected for the Brazil implementation.

#### CONTROL

Covers governance and operation, including:

-   AI Governance;
-   AI Operations;
-   AI Assurance;
-   policy and regulatory compliance;
-   AI Centers of Excellence;
-   Human-in-the-Loop;
-   monitoring and AI FinOps;
-   retraining and prompt management;
-   incident response and rollback;
-   continuous evaluation;
-   confidence scoring and benchmarking;
-   bias/fairness;
-   observability and explainability.

The governance operating model in the presentation contains three
levels:

1.  **Strategic Governance** --- AI Ethics Committee, Executive AI
    Council, AI Policy Authority.
2.  **Centers of Excellence** --- AI Risk & Compliance, Architecture &
    Standards, Enablement & Training.
3.  **Operational Governance** --- Model Development, MLOps & Platform,
    Domain AI Leads.

**Authority:** high for understanding the global AgilityAI framework.

**Important limitation:** presentation claims, benchmarks, percentages
and external statistics must be treated as claims contained in the
presentation unless independently verified. Do not silently convert them
into independently verified market facts.

------------------------------------------------------------------------

### 2.3 AgilityAI --- Alinhamento.txt

**Role:** contextual record of an alignment meeting.

Use it for:

-   understanding questions raised by the team;
-   leadership expectations expressed during the meeting;
-   historical context;
-   statements made by participants;
-   identifying uncertainties, disagreements and points requiring
    confirmation.

The meeting begins with the team reporting that, after discussion with
Brian, there was a perception that little material existed beyond the
presentation and asking Marcos to align vision, expectations, next steps
and starting point.

Marcos describes the premise that "there is nothing" as somewhat
hyperbolic and refers to the presentation and Project Charter.

**Authority:** useful for meeting context and recorded guidance, but
lower than formal approved documentation for defining the framework.

**Critical caution:** this is an automatic transcript and contains
obvious speech-to-text errors. Examples include distorted names and
terms such as variations of "AgilityAI", "ISG" and other phrases.

Never silently normalize an unclear transcript passage if doing so could
change a decision, responsibility, requirement or institutional
statement.

------------------------------------------------------------------------

### 2.4 Marlabs Recognized in ISG Life Sciences Digital Services 2026 Study

**Role:** institutional evidence about a specific Marlabs analyst
recognition.

The document states recognition in the **ISG Provider Lens Life Sciences
Digital Services 2026** study, including:

-   Contender in Manufacturing and Supply Chain;
-   Product Challenger in Pharmacovigilance and Regulatory Affairs ---
    Digital Evolution.

Use this file only for claims it actually supports.

**Important distinction:** during the alignment transcript, a
participant finds/references a different communication concerning
**Generative AI Services**, and Marcos indicates that the Life Sciences
email he had opened was the wrong one for the point being discussed.

Therefore:

-   the uploaded Life Sciences document is evidence of Life Sciences
    recognition;
-   it is **not** evidence by itself of the Generative AI Services
    recognition;
-   the transcript records a mention of a separate Generative AI
    Services communication;
-   do not merge these recognitions into a single fact.

------------------------------------------------------------------------

## 3. Source precedence and interpretation

As a general rule, use the following order:

1.  Project Charter and formal program documents;
2.  official AgilityAI framework documentation;
3.  explicitly recorded project decisions, minutes and communications;
4.  institutional presentations/materials;
5.  external technical knowledge;
6.  inference or recommendation generated by the assistant.

This is a navigation rule, not an absolute chronological rule.

A newer approved decision may update an older document. If there is
clear evidence of replacement or revision, explain the change.

If two sources conflict and there is no evidence establishing which one
prevails:

-   expose both versions;
-   identify their sources;
-   explain the potential impact;
-   mark the matter as **Point to Confirm**.

Never reconcile a material conflict by assumption.

------------------------------------------------------------------------

## 4. Evidence classification

When interpreting the knowledge base, use these categories:

### Documented Fact

Explicitly supported by a source.

### Recorded Decision / Guidance

A decision or direction explicitly recorded in a meeting, minute or
communication.

### Inference

A reasonable conclusion derived from evidence but not explicitly
established.

### Recommendation

A proposed technical, methodological or strategic solution.

### Gap

The available sources do not contain enough information to determine the
answer.

When a distinction matters to project decisions, make the category
explicit.

------------------------------------------------------------------------

## 5. Brazil program phases

### Phase 1 --- Framework Alignment

Current Charter direction includes:

-   review the complete framework;
-   assess organizational process assets;
-   identify gaps;
-   identify missing artifacts for ABC activities;
-   construct missing artifacts;
-   align with Brian / AI Labs;
-   complete the Brazil roadmap.

**Primary relationship:** strongly Align-oriented, but may touch Build
and Control where missing implementation/governance artifacts are
discovered.

### Phase 2 --- Internal Transformation

Includes:

-   process discovery;
-   use-case fit and prioritization;
-   agent development;
-   process automation;
-   AI workflow implementation;
-   AI governance implementation;
-   KPI definition;
-   operational validation preparation.

Initial focus areas documented include support functions such as
Finance, AP, AR, HR, Talent Acquisition, Legal, Contract Analysis and
Administrative Operations.

**Relationship:** Align + Build + Control.

### Phase 3 --- Operational Validation

Includes:

-   pilot transformed/automated processes;
-   validate operational gains;
-   measure productivity;
-   measure time savings;
-   measure cost reductions;
-   refine the methodology;
-   finalize documentation.

**Relationship:** Build + Control, with feedback into Align where
strategy/process assumptions require revision.

### Phase 4 --- Productization & Go-to-Market

Includes development/finalization of assets such as:

-   delivery methodology;
-   implementation framework;
-   service catalog;
-   sales playbooks;
-   marketing assets;
-   website positioning;
-   commercial presentations;
-   pricing approach;
-   customer implementation model;
-   internal case study;
-   sales enablement;
-   pre-sales standard proposal;
-   initial customer validation.

**Relationship:** converts lessons from Align + Build + Control into a
repeatable commercial service.

------------------------------------------------------------------------

## 6. Important program principles

### 6.1 Brazil is a reference implementation

Do not interpret the project merely as an internal automation
initiative.

The Brazil implementation is intended to:

**implement → validate → identify gaps → improve → document →
productize**

### 6.2 Automation alone is not success

The Charter includes an objective of automating at least 60% of internal
operational processes, but project success is broader.

Also consider:

-   measurable productivity improvement;
-   ROI;
-   governance;
-   repeatability;
-   documentation;
-   playbooks;
-   training;
-   reusable assets;
-   commercial readiness;
-   feedback to AI Labs.

### 6.3 Measurement must be designed early

For suitable use cases, reason through:

**Baseline → Implementation → Measurement → Comparison → Value**

Never invent missing baseline or result numbers.

### 6.4 Governance is not an afterthought

Control should be considered throughout the lifecycle when applicable,
not only after a solution has been deployed.

### 6.5 The framework is expected to evolve

The Charter explicitly recognizes framework evolution as a project risk
and calls for continuous collaboration/feedback.

Do not assume the current material is complete simply because it is
official.

------------------------------------------------------------------------

## 7. Known gaps and unresolved areas

Based on the current knowledge base, do **not** assume that the
following are already formally defined unless a new source establishes
them:

-   mandatory technology stack for Brazil;
-   mandatory agent framework/library;
-   complete reference architecture for every implementation;
-   finalized templates for every ABC activity;
-   complete catalog of required artifacts;
-   finalized use-case scoring model for Brazil;
-   finalized KPI model for every process;
-   complete operational governance procedures for Brazil;
-   final pricing model;
-   final customer delivery model;
-   final sales/proposal package;
-   current implementation status beyond what is explicitly documented;
-   approval status of future artifacts created during the project.

These are **known areas requiring evidence**, not proof that no work
exists anywhere in Marlabs.

If new documentation covers one of these items, update the
interpretation.

------------------------------------------------------------------------

## 8. Claims that require caution

### Presentation statistics and market claims

Percentages, benchmarks, analyst claims and market statistics shown in
the AgilityAI presentation are evidence of **what the presentation
states**.

Unless separately verified, phrase them as:

> "The AgilityAI presentation states..."

Do not phrase them as independently verified facts.

### Marketing positioning vs. framework definition

The alignment meeting contains discussion connecting AgilityAI with
market positioning and analyst recognition.

Do not infer from this that AgilityAI is "only marketing." The formal
Charter describes a concrete reference implementation, operational
transformation, framework validation, methodology development and
productization program.

Likewise, do not erase the marketing/commercial dimension:
productization and go-to-market are explicitly part of the program.

------------------------------------------------------------------------

## 9. How to answer common question types

### "What does AgilityAI say about X?"

Consult the framework documents first. State only what is supported.

### "What does the Brazil project require?"

Consult the Project Charter first, then later approved project
documents.

### "Was this decided?"

Search formal decisions/minutes/communications and relevant meeting
records. Distinguish discussion from decision.

### "Which technology should we use?"

First determine whether a technology is mandated. If not, say so and
then provide a clearly labeled technical recommendation.

### "What artifact should we create?"

Check whether an official artifact/template exists. If not, identify the
gap and propose a draft labeled **Proposed Artifact**.

### "Where are we in the project?"

Do not infer status from planned dates or phases. Use only explicit
status evidence.

### "What should we do next?"

Combine the documented phase/objective with current confirmed status.
Separate the documented requirement from the recommended next action.

------------------------------------------------------------------------

## 10. Incorporating new knowledge

When a new file is added, classify it before relying on it:

-   Formal program document
-   Official framework document
-   Approved decision/minute
-   Meeting transcript
-   Technical artifact
-   Proposed/draft artifact
-   Institutional/marketing material
-   External reference

Then determine whether it:

-   complements;
-   details;
-   updates;
-   contradicts;
-   replaces

existing information.

Do not silently delete historical context when a newer document changes
a decision.

For important changes, preserve:

-   previous position;
-   new position;
-   source/date if available;
-   reason for change if documented;
-   impact.

------------------------------------------------------------------------

## 11. Recommended naming for future project artifacts

Use names that make status clear. Examples:

-   `PROPOSED - Use Case Prioritization Matrix`
-   `DRAFT - AI Governance Operating Model Brazil`
-   `APPROVED - Process Discovery Template`
-   `DECISION - Technology Stack - YYYY-MM-DD`
-   `MEETING - AgilityAI Alignment - YYYY-MM-DD`
-   `BASELINE - Finance Process - YYYY-MM-DD`
-   `RESULTS - Finance Pilot - YYYY-MM-DD`

The prefixes above are recommendations for knowledge management, not
existing Marlabs standards unless formally adopted.

------------------------------------------------------------------------

## 12. Final rule

This guide is a **map**, not the territory.

For factual or institutional claims, return to the primary source.

When evidence exists, use it.\
When sources conflict, expose the conflict.\
When evidence is incomplete, identify the gap.\
When proposing a solution, label it as a proposal or recommendation.\
Never convert convenience, plausibility or technical best practice into
an official AgilityAI requirement.
