# Overview — ThemePark@UCR

|                      |                                                          |
| -------------------- | -------------------------------------------------------- |
| **Institution**      | Universidad de Costa Rica — Facultad de Ingeniería, ECCI |
| **Document**         | Conceptualization — Overview                             |
| **System**           | ThemePark@UCR                                            |
| **Document version** | 1.0                                                      |
| **System version**   | 0.1.0                                                    |
| **Last updated**     | 2026-04-03                                               |

---

## Table of contents

- [Overview — ThemePark@UCR](#overview--themeparkucr)
  - [Table of contents](#table-of-contents)
  - [1. Introduction](#1-introduction)
  - [2. Definitions, acronyms and abbreviations](#2-definitions-acronyms-and-abbreviations)
  - [3. Teams and members](#3-teams-and-members)
    - [PAW PATROL — _Learning Componentes_](#paw-patrol--learning-componentes)
    - [Team B — _Module name_](#team-b--module-name)
  - [4. System description](#4-system-description)
    - [4.1 Context and current situation](#41-context-and-current-situation)
    - [4.2 Problem it solves](#42-problem-it-solves)
    - [4.3 Stakeholders and user types](#43-stakeholders-and-user-types)
    - [4.4 Proposed solution](#44-proposed-solution)
    - [4.5 Environment analysis](#45-environment-analysis)
    - [4.6 Product vision](#46-product-vision)
    - [4.7 External systems](#47-external-systems)
    - [4.8 Modules per team and epics](#48-modules-per-team-and-epics)
    - [4.9 Functional requirements](#49-functional-requirements)
    - [4.10 Product roadmap](#410-product-roadmap)
    - [4.11 Non-functional requirements](#411-non-functional-requirements)
  - [5. Technical decisions](#5-technical-decisions)
    - [5.1 Methodology and processes](#51-methodology-and-processes)
    - [5.2 Artefacts](#52-artefacts)
    - [5.3 Tech stack](#53-tech-stack)
    - [5.4 Repository and git strategy](#54-repository-and-git-strategy)
    - [5.5 Definition of Done](#55-definition-of-done)
    - [5.6 Data requirements](#56-data-requirements)
    - [5.7 Conceptual database design](#57-conceptual-database-design)
    - [5.8 Logical database design](#58-logical-database-design)
  - [6. References](#6-references)

---

## 1. Introduction

This document presents the conceptualization of the ThemePark@UCR system,
developed as part of course CI-0128 (Proyecto Integrador de Ingeniería de
Software y Bases de Datos), Group 01, first semester 2026, at the Universidad
de Costa Rica.

Its purpose is to establish a shared understanding of what the system is, why
it exists, who it serves, and how the development teams are organized to build
it. It serves as the foundational reference for all teams throughout the
project and should be kept updated as the project evolves.

The document is structured as follows: it opens with team organization and
role assignments, then describes the system context, problem, stakeholders,
and proposed solution. Larger sections that require detailed treatment are
maintained in dedicated files within this repository and linked from the
corresponding section below.

---

## 2. Definitions, acronyms and abbreviations

| Term       | Definition                                                          |
| ---------- | ------------------------------------------------------------------- |
| UCR        | Universidad de Costa Rica                                           |
| ECCI       | Escuela de Ciencias de la Computación e Informática                 |
| VR         | Virtual Reality                                                     |
| Web/VR     | Application accessible via web browser and VR headset               |
| Meta Quest |                                                                     |
| Metaverse  |                                                                     |
| PO         | Product Owner                                                       |
| Scrum      |                                                                     |
| Sprint     | Fixed-length iteration in Scrum                                     |
| MVP        | Minimum Viable Product — smallest functional version of the product |
| DoD        | Definition of Done — checklist a story must pass to be accepted     |
| EER        | Extended Entity-Relationship model, used for conceptual DB design   |
| NFR        | Non-Functional Requirement                                          |
| Epic       |                                                                     |
| US         | User Story                                                          |
| 2D         |                                                                     |
| 3D         |                                                                     |

---

## 3. Teams and members

### PAW PATROL — _Learning Componentes_

| Member | Sprint 0     | Sprint 1     | Sprint 2 |
| ------ | ------------ | ------------ | -------- |
| _Name_ | Scrum Master | Developer    | —        |
| _Name_ | Developer    | Scrum Master | —        |
| _Name_ | Developer    | Developer    | —        |

### Team B — _Module name_

| Member | Sprint 0     | Sprint 1     | Sprint 2 |
| ------ | ------------ | ------------ | -------- |
| _Name_ | Scrum Master | Developer    | —        |
| _Name_ | Developer    | Developer    | —        |
| _Name_ | Developer    | Scrum Master | —        |

---

## 4. System description

### 4.1 Context and current situation

The Universidad de Costa Rica (UCR) requires a Web/VR application to offer
immersive experiences about university life and its campuses. Virtual theme
parks and metaverse technologies are already being adopted by the entertainment
industry, with companies investing heavily in VR-based experiences. UCR aims
to leverage these technologies to universalize access to university education
in Costa Rica and the broader region.

UCR has created a development unit supported by the Escuela de Ciencias de la
Computación e Informática (ECCI) to build the first virtual university theme
park in the region. In parallel, UCR participates in a consortium with Latin
American and European universities proposing VR-based learning experiences in
the context of European Union innovation programs.

### 4.2 Problem it solves

<!-- TODO: Complete  -->

_To be defined _

### 4.3 Stakeholders and user types

| Stakeholder     | Type     | Description                                           |
| --------------- | -------- | ----------------------------------------------------- |
| Future students | End user | Explore campus and academic programs before enrolling |
| General public  | End user | Access immersive educational experiences              |
| Professors      | End user | Participate and contribute to the virtual space       |

<!-- TODO: Complete  -->

### 4.4 Proposed solution

<!-- TODO: Complete  -->

_To be defined _

### 4.5 Environment analysis

→ See [`environment-analysis.md`](environment-analysis.md) for the full
analysis covering business strategy, expected usage, legacy systems,
regulatory aspects, assumptions and constraints, and existing competing
solutions.

### 4.6 Product vision

_To be defined with the Product Owner during Sprint 0._

<!-- TODO: Complete  -->

### 4.7 External systems

_To be defined _

<!-- TODO: Complete  -->

### 4.8 Modules per team and epics

→ See [`epics.md`](epics.md) for the full description of each team's assigned
module, their main epics, inter-module relationships.

### 4.9 Functional requirements

Functional requirements are managed as user stories in Github Projects.

_Add link_

<!-- TODO: Complete  -->

### 4.10 Product roadmap

→ See [`product-roadmap.md`](product-roadmap.md) for the sprint-by-sprint
delivery plan.

### 4.11 Non-functional requirements

→ See [`non-functional-req.md`](non-functional-req.md) for the full list of
system-wide NFRs covering security, privacy, performance, accessibility, and
architecture constraints.

---

## 5. Technical decisions

### 5.1 Methodology and processes

→ See [`methodology.md`](../architecture/methodology.md) for
the full description of the Scrum processes, ceremonies, and roles adopted by
the teams.

### 5.2 Artefacts

→ See [`methodology.md`](../architecture/methodology.md) for
the list of artefacts used throughout the project.

### 5.3 Tech stack

→ See [`../architecture/stack.md`](../architecture/stack.md) for all
technologies, frameworks, and exact versions used, with justifications.

### 5.4 Repository and git strategy

→ See [`../architecture/git-strategy.md`](../architecture/git-strategy.md)
for the branching model, PR rules, and commit conventions.

### 5.5 Definition of Done

→ See [`../architecture/definition-of-done.md`](../architecture/definition-of-done.md)
for the full DoD checklist that every user story must satisfy before it can
be accepted in a sprint review.

### 5.6 Data requirements

→ See [`../database/data-requirements/`](../database/data-requirements/) for
the data requirements organized by team, covering entities, attributes,
relationships, cardinality, and semantic constraints.

### 5.7 Conceptual database design

→ See [`../database/eer-diagram.md`](../database/eer-diagram.md) for the
Extended Entity-Relationship diagram and its design decisions.

### 5.8 Logical database design

→ See [`../database/logical-model.md`](../database/logical-model.md) for the
relational model and the mapping decisions derived from the EER diagram.

---

## 6. References

_This section collects all sources, documents, and resources consulted for the development and justification of the ThemePark@UCR system. Please add books, articles, websites, standards, and any other relevant material used as a reference._

<!-- TODO : Defined format with professor or group -->
