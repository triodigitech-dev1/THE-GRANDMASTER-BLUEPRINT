# The Grandmaster Blueprint — Documentation Set

> A FIDE-aligned, six-chapter chess mastery curriculum.
> This repository contains the governing documents that define, sequence, assess, and standardize the curriculum.

---

## 1. What This Repository Is

This is the **authoritative documentation set** for _The Grandmaster Blueprint_.

It does **not** contain lesson content itself. It contains the **architecture** that all lesson content must follow:

- What is taught
- Why it is taught
- In what order it is taught
- To what standard it must be built
- How progress is gated and coordinated

Every piece of content produced for this curriculum must trace back to one of these documents.

---

## 2. The Document Set

| #   | File                     | Answers the Question                               | Role                      |
| --- | ------------------------ | -------------------------------------------------- | ------------------------- |
| 1   | `curriculum-map.md`      | **What** is the curriculum?                        | Structure & scope         |
| 2   | `learning-objectives.md` | **What will learners be able to do?**              | Outcomes & assessment     |
| 3   | `content-standards.md`   | **How must content be made?**                      | Quality & FIDE compliance |
| 4   | `course-roadmap.md`      | **In what order is it delivered?**                 | Sequence & gates          |
| 5   | `project-management.md`  | **Who coordinates what, and where does it stand?** | Governance & status       |

---

## 3. Recommended Reading Order

Read the documents in this order. Each one depends on the one before it.

```text
┌──────────────────────────────────────────────────────────────┐
│                     CANONICAL READING ORDER                  │
├──────────────────────────────────────────────────────────────┤
│                                                              │
│   1. curriculum-map.md                                       │
│          │  Defines the structure and scope.                 │
│          ▼                                                   │
│   2. learning-objectives.md                                  │
│          │  Derives outcomes from the map.                   │
│          ▼                                                   │
│   3. content-standards.md                                    │
│          │  Sets the rules for building content.             │
│          ▼                                                   │
│   4. course-roadmap.md                                       │
│          │  Sequences the objectives into a journey.         │
│          ▼                                                   │
│   5. project-management.md                                   │
│             Coordinates, tracks, and governs all of it.      │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

### Why This Order

| Step | Document                 | Reason                                                                |
| ---- | ------------------------ | --------------------------------------------------------------------- |
| 1    | `curriculum-map.md`      | You cannot define outcomes before you know the structure.             |
| 2    | `learning-objectives.md` | You cannot build content before you know what it must achieve.        |
| 3    | `content-standards.md`   | You cannot author content before you know the compliance rules.       |
| 4    | `course-roadmap.md`      | You cannot sequence delivery before objectives and standards exist.   |
| 5    | `project-management.md`  | You cannot coordinate production before the four pillars are defined. |

> **Dependency rule:** A document may never contradict a document that precedes it in this order. If a conflict is found, the earlier document wins and the later document is corrected.

---

## 4. What Each Document Contains

### 4.1 `curriculum-map.md` — The Structure

- Program overview and learning arc
- Six chapters, each with sections, topics, and deliverables
- Master deliverables index
- Competency progression matrix
- Suggested study sequence

**Use it when:** you need to know what exists, what belongs where, and what must be produced.

---

### 4.2 `learning-objectives.md` — The Outcomes

- Program-Level Outcomes (PLOs)
- Terminal and enabling objectives per chapter
- Bloom's taxonomy level for each objective
- Assessment evidence for each objective
- Master assessment matrix

**Use it when:** you need to know what a learner must demonstrate, and how it will be measured.

---

### 4.3 `content-standards.md` — The Quality Law

- Source hierarchy (FIDE Handbook first)
- Rules, notation, rating, title, arbiter, and trainer standards
- Fair play, ethics, accessibility, and inclusivity standards
- Production workflow and review stages
- Compliance checklist and FIDE reference index

**Use it when:** you are authoring, reviewing, or validating any content. Nothing is published until it passes this document's checklist.

---

### 4.4 `course-roadmap.md` — The Journey

- Six phases mapped to the six chapters
- Phase gates with passing standards
- Capstone requirements and weighting
- Competency progression
- Study approach (no timelines assigned)

**Use it when:** you need to know the order of progression, the entry conditions for each phase, and the exit criteria for each gate.

---

### 4.5 `project-management.md` — The Coordination

- Scope definition (in / out)
- Sequencing rules and dependency graph
- Standards governance
- Gate-based milestones
- Production status tracker
- Change history and version log

**Use it when:** you need to know the current state of production, who owns what, and what changed.

---

## 5. Audience Paths

Different readers enter the set at different points. Follow the path that matches your role.

| Role                        | Reading Path                                |
| --------------------------- | ------------------------------------------- |
| **Curriculum Designer**     | Map → Objectives → Standards → Roadmap → PM |
| **Content Author**          | Standards → Map → Objectives → Roadmap      |
| **Reviewer / Validator**    | Standards → Objectives → Map                |
| **Instructor**              | Roadmap → Map → Objectives                  |
| **Learner**                 | Roadmap → Map → Objectives                  |
| **Project Coordinator**     | PM → Map → Objectives → Standards → Roadmap |
| **FIDE Compliance Officer** | Standards → PM                              |

---

## 6. How the Documents Interlock

```text
                ┌─────────────────────────┐
                │   content-standards.md  │
                │   (governs all content) │
                └────────────┬────────────┘
                             │
                             ▼
┌──────────────────┐   ┌──────────────────┐   ┌──────────────────┐
│ curriculum-map   │──►│ learning-        │──►│ course-roadmap   │
│ .md              │   │ objectives.md    │   │ .md              │
│ (structure)      │   │ (outcomes)       │   │ (sequence)       │
└──────────────────┘   └──────────────────┘   └──────────────────┘
         │                      │                      │
         └──────────────────────┼──────────────────────┘
                                ▼
                   ┌─────────────────────────┐
                   │  project-management.md  │
                   │  (tracks & coordinates) │
                   └─────────────────────────┘
```

- **Standards** sits above everything as a governing layer.
- **Map → Objectives → Roadmap** is a strict linear dependency.
- **Project Management** observes and coordinates all four.

---

## 7. How to Use This Set Day to Day

### If you are building content

1. Open `content-standards.md` — confirm the FIDE regulation and the checklist.
2. Open `curriculum-map.md` — confirm the chapter, section, and deliverable.
3. Open `learning-objectives.md` — confirm which objective the content serves.
4. Author the content.
5. Run the compliance checklist before submitting.

### If you are reviewing content

1. Open `learning-objectives.md` — does the content achieve the stated objective?
2. Open `content-standards.md` — does it pass every checklist item?
3. Open `curriculum-map.md` — is it placed in the correct chapter and section?
4. Record the outcome in `project-management.md`.

### If you are tracking progress

1. Open `project-management.md` — view the production status tracker.
2. Update status only after passing the relevant review stage.
3. Log every change in the change history.

### If you are a learner

1. Open `course-roadmap.md` — follow the phases in order.
2. Open `curriculum-map.md` — see what each phase contains.
3. Open `learning-objectives.md` — know what you must be able to do before advancing.
4. Complete each phase gate before moving on.

---

## 8. Rules of the Set

1. **No content without a source.** Every factual claim traces to a FIDE regulation or a named reference.
2. **No content without an objective.** Every deliverable maps to a learning objective.
3. **No advancement without a gate.** Phases are gated; gates are pass/fail.
4. **No contradiction.** Lower-priority documents never override higher-priority ones.
5. **No undocumented change.** Every edit is logged in `project-management.md`.
6. **No timelines.** Progression is gate-based, not date-based.

---

## 9. Document Status Legend

Used throughout the set:

| Status       | Meaning                                         |
| ------------ | ----------------------------------------------- |
| `DRAFT`      | In authoring, not yet reviewed                  |
| `IN REVIEW`  | Submitted, under technical or compliance review |
| `COMPLIANT`  | Passed all standards checks                     |
| `RATIFIED`   | Approved and frozen as the current version      |
| `SUPERSEDED` | Replaced by a newer version                     |

---

## 10. Quick Start

```text
New to the project?
   → Read this README
   → Read curriculum-map.md
   → Read learning-objectives.md
   → Read content-standards.md
   → Read course-roadmap.md
   → Read project-management.md

Ready to author?
   → Standards → Map → Objectives → Build → Checklist → Log

Ready to learn?
   → Roadmap → Gate 1 → Map → Objectives → Gate 2 → ...
```

---
