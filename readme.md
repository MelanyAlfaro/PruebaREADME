# ThemePark@UCR

> An immersive Web/VR application offering virtual experiences of the University of Costa Rica — built for future students, current students, and the general public.

![Sprint](https://img.shields.io/badge/sprint-0-blue)
![Status](https://img.shields.io/badge/status-in%20progress-yellow)
![License](https://img.shields.io/badge/license-CC--BY--NC--SA-lightgrey)
![Course](https://img.shields.io/badge/course-CI--0128-orange)

---

## What is this?

ThemePark@UCR is a virtual theme park built on top of the UCR campus. It allows people to explore university facilities, discover academic programs, and engage with immersive 2D/3D learning experiences — without needing to be physically present.

The platform combines a web application with a VR experience for Meta Quest, a relational database backend, and gamification mechanics (escape rooms, rankings, missions) designed to engage young audiences.

→ Full context and motivation: [`docs/conceptualization/overview.md`](docs/conceptualization/overview.md)

---

## Quick start

> Prerequisites: <!-- to be defined by the team: Node version, Unity version, DB engine, etc. -->

```bash
git clone <repository-url>
cd themepark-ucr
# install dependencies, configure environment, run
```

→ Full setup instructions: [`CONTRIBUTING.md`](CONTRIBUTING.md)

---

## Project structure

```
ThemePark@UCR/
├── README.md
├── COMMIT_GUIDELINES.md
├── CONTRIBUTING.md
├── src/                        ← application source code
├── tests/                      ← test projects
└── docs/
    ├── conceptualization/      ← product vision, roadmap, NFRs
    ├── architecture/           ← tech stack, DoD, git strategy, diagrams
    └── database/               ← data requirements, EER, logical model
```

---

## Teams & modules

| Team   | Module           | Members         | Jira       |
| ------ | ---------------- | --------------- | ---------- |
| Team A | _to be assigned_ | _to be defined_ | [Board](#) |
| Team B | _to be assigned_ | _to be defined_ | [Board](#) |
| Team N | _to be assigned_ | _to be defined_ | [Board](#) |

→ Role assignments per sprint: [`docs/conceptualization/overview.md#teams`](docs/conceptualization/overview.md)

---

## Documentation

| Section                                                                                            | Description                                                    |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| [`docs/conceptualization/overview.md`](docs/conceptualization/overview.md)                         | Context, problem, stakeholders, proposed solution              |
| [`docs/conceptualization/environment-analysis.md`](docs/conceptualization/environment-analysis.md) | Business strategy, legacy systems, regulatory aspects          |
| [`docs/conceptualization/product-vision.md`](docs/conceptualization/product-vision.md)             | Product vision, external systems, module descriptions per team |
| [`docs/conceptualization/product-roadmap.md`](docs/conceptualization/product-roadmap.md)           | Sprint-by-sprint delivery plan                                 |
| [`docs/conceptualization/non-functional-req.md`](docs/conceptualization/non-functional-req.md)     | Security, performance, accessibility, and other NFRs           |
| [`docs/architecture/stack.md`](docs/architecture/stack.md)                                         | Technologies, frameworks, and exact versions used              |
| [`docs/architecture/system-diagram.md`](docs/architecture/system-diagram.md)                       | High-level architecture diagram and explanation                |
| [`docs/architecture/methodology.md`](docs/architecture/methodology.md)                             | Scrum processes, ceremonies, and artefacts                     |
| [`docs/architecture/definition-of-done.md`](docs/architecture/definition-of-done.md)               | Definition of Done checklist                                   |
| [`docs/architecture/git-strategy.md`](docs/architecture/git-strategy.md)                           | Branching model and pull request rules                         |
| [`docs/database/data-requirements/`](docs/database/data-requirements/)                             | Data requirements per team                                     |
| [`docs/database/eer-diagram.md`](docs/database/eer-diagram.md)                                     | Extended Entity-Relationship diagram and design decisions      |
| [`docs/database/logical-model.md`](docs/database/logical-model.md)                                 | Relational model and mapping decisions                         |

---

## Contributing

All contributors must follow the project's commit and branching conventions.

→ [`CONTRIBUTING.md`](CONTRIBUTING.md) — setup, workflow, and onboarding  
→ [`COMMIT_GUIDELINES.md`](COMMIT_GUIDELINES.md) — commit message format and examples

---

## Course information

|             |                                                                          |
| ----------- | ------------------------------------------------------------------------ |
| Course      | CI-0128 — Proyecto Integrador de Ingeniería de Software y Bases de Datos |
| Group       | 01                                                                       |
| Term        | First semester 2026                                                      |
| Institution | Universidad de Costa Rica — ECCI                                         |
| Instructor  | cristian.quesadalopez@ucr.ac.cr                                          |

---

## License

This project is developed under academic context at the Universidad de Costa Rica.  
Documentation is licensed under [CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/).
