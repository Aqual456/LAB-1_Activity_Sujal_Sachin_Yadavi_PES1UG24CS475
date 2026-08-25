# LAB-1_Activity_Sujal_Sachin_Yadavi_PES1UG24CS475
# Lab 1: Requirements Engineering & UML Use-Case Modelling

**Problem Statement #44 — Database Query Performance Profiler**

## Problem Context

A database observability tool that ingests slow query logs, parses SQL execution plans, identifies missing index candidates, and generates weekly performance optimization digests.

**Stakeholders / Actors:** Database Administrator, Backend Lead, Notification Service (Email/Slack)

## Deliverables

| # | File | Description |
|---|------|-------------|
| 1 | `requirements_table.pdf` | 5 Functional Requirements (FR-001–FR-005) and 2 Non-Functional Requirements (NFR-001, NFR-002), each with Req ID, Type, Description, Priority, Acceptance Criteria, and Rationale. |
| 2 | `uml_usecase_diagram.pdf` | Use-case diagram showing all actors, primary use cases, and at least one `«include»` and one `«extend»` relationship. |
| 3 | `useCase_flow.pdf` | One-page flow for the "Generate Weekly Optimization Digest" use case, including Preconditions, Postconditions, Main Success Scenario, and Alternate Flows. |

## Summary

- **Actors (3):** Database Administrator, Backend Lead, Notification Service
- **Use Cases (7):** Ingest Slow Query Logs, Parse SQL Execution Plan, Identify Missing Index Candidates, Configure Alert Thresholds, Generate Weekly Optimization Digest, View Query Performance Dashboard, Export Performance Report
- **`«include»` relationships:**
  - Identify Missing Index Candidates *includes* Parse SQL Execution Plan
  - Generate Weekly Optimization Digest *includes* Identify Missing Index Candidates
- **`«extend»` relationship:**
  - Export Performance Report *extends* View Query Performance Dashboard

## Course

Lab 1 — Requirements Engineering & UML Use-Case Modelling
PES University, Dept. of CSE
