# R3GROUP — Katty Fashion Digital Manufacturing Platform

> Katty Fashion pilot implementation for the **R3GROUP Horizon Europe project**, enabling resilient and rapidly reconfigurable garment production through Digital Twins and AAS-based manufacturing architecture.

---

# Quick Links

- KF Team Dashboard  
https://katty-fashion.github.io/kf-cpto/

- Unified Kanban  
https://katty-fashion.github.io/kf-cpto/unified-kanban.html

- R3GROUP Project (CORDIS)  
https://cordis.europa.eu/project/id/101091869

---

# Project Overview

**R3GROUP (Resilient Rapid Reconfigurable Production Process Chains)** is a Horizon Europe research project aimed at enabling **flexible, digital, and resilient manufacturing ecosystems**.

The project focuses on:

- rapid reconfiguration of production systems
- digital integration between design and manufacturing
- interoperability across supply chain partners
- human-centered manufacturing environments.

The **Katty Fashion pilot** demonstrates these capabilities within the **garment manufacturing industry**, integrating digital tools across the full product lifecycle.

---

# Core Digital Concepts

The platform integrates several Industry 4.0 concepts:

### Digital Twin
Digital representation of:

- garments
- manufacturing processes
- production resources

### Asset Administration Shell (AAS)

Standardized digital interface representing assets in the manufacturing system.

Allows interoperability between:

- machines
- software systems
- digital twins.

### Digital Thread

Continuous data flow connecting:

- design
- production planning
- manufacturing execution
- product lifecycle monitoring.

---

# Platform Architecture

## System Architecture Overview

```mermaid
graph TD

A[Designer] --> B[Co-Creation Platform]
B --> C[API Gateway]

C --> D[Product Digital Twin]
C --> E[Process Digital Twin]
C --> F[Capacity Planner]

D --> G[(Digital Product Data)]
E --> H[(Process Models)]
F --> I[(Planning Database)]

D --> J[AAS Layer]
E --> J
F --> J

J --> K[Manufacturing Systems]
