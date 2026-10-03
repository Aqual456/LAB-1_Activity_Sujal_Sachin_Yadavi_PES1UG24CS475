# LAB-1_Activity_Sujal_Sachin_Yadavi_PES1UG24CS475

**Individual Project Submission — Software Engineering**
Sujal Sachin Yadavi · PES1UG24CS475

This repository holds all individual-project deliverables, organized into the folder
structure specified for submissions. Each numbered folder maps to one category of
deliverable; see below for what's inside each one and its current status.

---

## Repository Structure

| Folder | Contents | Status |
|---|---|---|
| [`1-RE`](./1-RE) | Requirements Engineering: FR/NFR table, use-case diagram & flows | ✅ Complete |
| [`2-Architectural_Diagram`](./2-Architectural_Diagram) | Component diagram & architecture justification | ✅ Complete |
| [`3-Project_Creation_Screenshots`](./3-Project_Creation_Screenshots) | GitHub repo & Jira board setup screenshots | 🔲 Pending |
| [`4-SRS_and_WBS`](./4-SRS_and_WBS) | SRS document & Work Breakdown Structure | 🔲 Pending |
| [`5-Copilot_Generated_Code`](./5-Copilot_Generated_Code) | GitHub Copilot code screenshot / linked repo | 🔲 Pending |
| [`6-Software_Testing`](./6-Software_Testing) | Testing-tool exercise: bug fix, patch, retest | 🔲 Pending |

---

## 1 — Requirements Engineering (RE)

Covers Lab 1: Requirements Engineering & UML Use-Case Modelling, based on
**Problem Statement #44 — Database Query Performance Profiler**.

| File | Description |
|---|---|
| `requirements_table.pdf` | 5 Functional Requirements (FR-001–FR-005) and 2 Non-Functional Requirements (NFR-001, NFR-002), each with ID, Type, Description, Priority, Acceptance Criteria, and Rationale. |
| `uml_usecase_diagram.pdf` | UML Use-Case Diagram — 3 actors, 7 use cases, with `«include»` and `«extend»` relationships. |
| `usecase_flow.pdf` | Use-Case Flow Specification for "Generate Weekly Optimization Digest" — preconditions, postconditions, main success scenario, alternate flow. |
| `Alternate_Flow_Specification.pdf` | Detailed alternate flows (no slow queries logged; on-demand digest trigger), each with a flow diagram. |
| `Exception_Flow_Specification.pdf` | Detailed exception flows (notification delivery failure; database connection lost), each with a flow diagram. |

> **Note:** An RTM (Requirements Traceability Matrix) table linking requirements to
> design/test artifacts is still to be added to this folder.

---

## 2 — Architectural Diagram

Covers Lab 3: Component Modelling & Architectural Pattern Selection, for the same
system (Database Query Performance Profiler).

| File | Description |
|---|---|
| `component_diagram.pdf` | UML Component Diagram — Microservices architecture with 6 components across two subsystems (Ingestion & Configuration, Analysis & Reporting), plus an external Notification Service. Shows 8+ interfaces with provided/required (ball-and-socket) notation and protocol labels. |
| `Architecture_Justification.pdf` | Architecture selection rationale: why Microservices was chosen over Layered and Client-Server, component responsibility table, security advantage, performance benefit, and accepted trade-offs. |

---

## 3 — Project Creation Screenshots

*Pending.* Will contain screenshots of:
- GitHub repository creation and initial setup
- Jira project/board creation for this individual project

---

## 4 — SRS and Work Breakdown Steps

*Pending.* Will contain:
- Software Requirements Specification (SRS) document
- Work Breakdown Structure (WBS) for the project

---

## 5 — GitHub Copilot Generated Code

*Pending.* Will contain either:
- A screenshot of Copilot-generated code for this project, or
- A link to the repository containing the Copilot-assisted code

---

## 6 — Software Testing

*Pending.* Will contain the results of the software-testing-tools exercise: using
vibe coding (or another AI tool) to fix a bug, add a patch, and retest the provided
game application, along with screenshots of the testing process.

---

## System Under Design

**Database Query Performance Profiler** (Problem Statement #44) — a database
observability tool that ingests slow query logs, parses SQL execution plans,
identifies missing index candidates, and generates weekly performance
optimization digests for a Database Administrator and Backend Lead.
