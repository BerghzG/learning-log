# Requirements Engineering

> According to Roger S. Pressman (2016):  
> *“Understanding the requirements of a problem is among the most difficult tasks faced by a software engineer.”*

Requirements Engineering is a fundamental discipline within software development. It focuses on identifying, analyzing, documenting, validating, and managing the needs and expectations of stakeholders.

Requirements define **what stakeholders need from a system** and **what the system must do** to satisfy those needs**. When done properly, requirements engineering reduces risks, prevents misunderstandings, and lays the foundation for a successful software product.

---

## Software Engineering Life Cycle

## 1. Conception

The **Conception** phase aims to understand the problem at a high level.

At this stage, the team:

- Identifies stakeholders
- Understands the business context
- Defines the scope of the system
- Clarifies high-level goals and constraints

The objective is not to define technical details yet, but to gain a clear macro-level understanding of the problem and the client's needs.

---

## 2. Specification

During the **Specification** phase, requirements are refined, detailed, and documented.

This is the point where:

- Functional and non-functional requirements are prioritized
- Business rules are clarified
- Acceptance criteria are defined
- Documentation becomes precise enough to support system design

Here, we transition from **requirements analysis** to **technical design**, where the solution architecture is created to transform requirements into a working software system.

---

## 3. Validation

The **Validation** phase ensures that the documented requirements are:

- Complete  
- Clear  
- Consistent  
- Feasible  
- Aligned with stakeholder expectations  

Validation helps answer the critical question:

> *“Are we building the right system?”*

It prevents costly errors by detecting misunderstandings before implementation begins.

---

## 4. Requirements Management

Requirements are not static — they evolve.

**Requirements Management** includes activities that:

- Identify and organize requirements  
- Track changes over time  
- Maintain traceability  
- Control versions  
- Assess impact of modifications  

Effective management ensures that changes are handled systematically without compromising project stability.

---

## Types of Requirements

## Functional Requirements

Functional requirements describe **what the system does**.

They define:

- Features
- Services
- Business rules
- System behaviors
- User interactions

In simple terms, functional requirements represent the system’s tasks and capabilities.

If a functional requirement is incorrect or incomplete, the core functionality of the software may be compromised. For this reason, they form the backbone of system development.

**Examples:**

- The system shall allow users to create an account.
- The system shall generate a monthly sales report.

---

## Non-Functional Requirements

Non-functional requirements define **how the system performs its functions**.

They describe quality attributes such as:

- Performance
- Usability
- Reliability
- Security
- Scalability
- Maintainability
- Robustness

While functional requirements define *what* the system does, non-functional requirements define *how well* it does it.

**Examples:**

- The system shall respond to user requests within 2 seconds.
- The system shall be available 99.9% of the time.

---

## Use Cases

A **Use Case** describes how users interact with the system to achieve a specific goal.

It typically includes different types of flows:

## Main Flow (Happy Path)

The **Main Flow** describes the standard, expected sequence of steps that leads to successful completion of the use case.

It answers:
> “What normally happens when everything goes right?”

---

## Alternative Flow

An **Alternative Flow** describes variations from the main flow.

These are valid but non-standard paths — for example:

- Optional user choices
- Conditional branches
- Different execution scenarios

---

## Exception Flow

An **Exception Flow** handles error conditions and unexpected situations.

It defines:

- What happens when something goes wrong
- How the system responds to failures
- How errors are communicated to the user

---

## User Stories

In agile methodologies, the focus shifts from documentation-heavy processes to collaboration and user value.

A **User Story**:

- Is written from the end-user’s perspective  
- Uses business language rather than technical language  
- Focuses on delivering value  

A common format is:

> *As a [type of user], I want [some goal] so that [some benefit].*

User stories encourage communication and ensure the system is designed around real user needs.

---

## Epics

An **Epic** is a large user story or a collection of related stories.

When a feature is too broad or complex, it is broken down into smaller, manageable user stories. This improves:

- Clarity  
- Estimation accuracy  
- Prioritization  
- Incremental delivery  

Epics help organize large initiatives into structured, actionable development tasks.

---

## Final Thoughts

Requirements Engineering is not merely a documentation phase — it is a strategic activity that shapes the success of a software project.

Clear requirements:

- Reduce rework  
- Improve stakeholder alignment  
- Enhance product quality  
- Support predictable delivery  

When requirements are well understood, validated, and managed, the software development process becomes significantly more efficient and reliable.
