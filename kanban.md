---
project: r3group-kf
description: "R3GROUP Katty Fashion pilot – digital tools for co-creation, digital twins and technician capacity planning"
type: eu-project

team:
  po: ps.tech@katty-fashion.ro
  tech_lead: el.tech@katty-fashion.ro
  frontend: alexandru.bejenari@katty-fashion.ro
  backend: razvan.boita@katty-fashion.ro

sprint: S1
sprint_start: 2026-03-02
sprint_end: 2026-03-13
depends_on: [ai-rise]
tags: [r3group, digital-twin, capacity-planner, manufacturing]
---

# Project Kanban

## Team
- **Product Owner:** ps.tech@katty-fashion.ro  
- **Tech Lead:** el.tech@katty-fashion.ro  
- **Front-End:** alexandru.bejenari@katty-fashion.ro  
- **Back-End:** razvan.boita@katty-fashion.ro  

---

## Project Context

This repository supports the **Katty Fashion pilot implementation within the R3GROUP Horizon Europe project**.

The goal is to enable **digital integration between product development and manufacturing processes** in garment production through several key tools:

- **Co-creation platform** for collaborative order and design management  
- **Product Digital Twin** connecting technical packs, order data and manufacturing information  
- **Process Digital Twin** for simulation of production changes and reconfiguration impact  
- **Technician Capacity Planner** to optimize task scheduling and department workload  

These tools aim to improve **resilience, reconfigurability and digitalization of the garment production workflow**.   

---

<!-- Valid statuses: Todo, In Progress, Review, Done -->
<!-- Effort format: Nd (e.g. 1d, 0.5d, 3d) -->

| Task | Assignee | Effort | Start | End | Status |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Repository setup and Kanban initialization | @tech-lead | 1d | 2026-03-02 | 2026-03-02 | Done |
| Define system architecture (planner + digital twins) | @tech-lead | 2d | 2026-03-03 | 2026-03-04 | In Progress |
| Setup project documentation (R3GROUP context) | @tech-lead | 1d | 2026-03-04 | 2026-03-04 | In Progress |
| Define technician task model and scheduling logic | @backend | 2d | 2026-03-05 | 2026-03-06 | Todo |
| Implement backend service for technician capacity planner | @backend | 3d | 2026-03-06 | 2026-03-10 | Todo |
| Implement planner UI dashboard (calendar + workload view) | @frontend | 3d | 2026-03-06 | 2026-03-10 | Todo |
| Integrate planner with order and task data model | @backend | 2d | 2026-03-10 | 2026-03-11 | Todo |
| Connect UI with backend API | @frontend | 1.5d | 2026-03-11 | 2026-03-12 | Todo |
| Sprint review and technical validation | @tech-lead | 0.5d | 2026-03-13 | 2026-03-13 | Todo |
