# Advanced Data Models – Summer Semester 2026

This repository contains materials for the **Advanced Data Models** lecture (SS2026) at the Applied University Esslingen.  The course explores modern data models beyond traditional relational systems and their role in building scalable, AI‑ready architectures.

## Repository structure

- `report.md` – Detailed course design describing philosophy, semester plan, seminar topics, recommended readings, demo ideas, lecture template, interactive activities, infrastructure recommendations, and grading rubric.
- `docs/` – Additional papers, reports or architecture diagrams.
- `groups/` – One subdirectory per group containing all deliverables (see below).

### Group directories

Each group works inside its own subdirectory under `groups/`:

```
groups/
  group1-graph-databases/
  group2-triple-stores/
  group3-vector-databases/
  group4-document-stores/
  group5-key-value-stores/
  group6-wide-column-databases/
  group7-data-lakes/
```

Every group directory follows the same internal structure:

```
README.md       – overview, setup instructions, dependencies
slides/         – presentation files (PDF/PPTX)
demo/           – source code, Dockerfiles, scripts
data/           – sample datasets (or scripts to download them)
notebooks/      – Jupyter notebooks used in preparation or demonstration
```

Each group directory contains placeholder `README.md` files explaining its purpose.  Add further subdirectories as needed.

## Guidelines for students

- Form groups of 2‑3 students and select a topic (graph databases, triple stores, vector databases, document stores, key‑value stores, wide‑column stores or data lakes).
- Deeply study the assigned paper or chapter, prepare your lecture using the template provided in `report.md`, and design an interactive activity and practical demo.
- Use open‑source or free‑tier tools that run on student laptops (e.g. Neo4j, Apache Jena, Milvus, MongoDB, Redis, Cassandra, Delta Lake).  Docker setup is encouraged.
- AI coding assistants (ChatGPT, Codex, Claude) may be used to accelerate code development, but every student must understand and be able to explain what their code does.
- Commit all your materials (slides, demo scripts, data, notebooks) to your group directory in this repository and be prepared to explain your design decisions during your lecture.

For full course philosophy, semester schedule, suggested readings, demo ideas and evaluation rubric, please consult `report.md`.
