# I. Executive Summary – Dräger Demo Equipment Management System

I designed and implemented a full-stack Demonstration Equipment Management System for Dräger Medical Systems Inc. in Danvers, MA, managing a 10M USD fleet of high-value medical devices used across North America. The system unified asset tracking, shipping workflows, calibration schedules, service logs, and warehouse–field-office coordination into a single operational platform. Built as an Access/SQL hybrid with custom VBA tooling, it significantly reduced lost equipment, increased utilisation rates, and enabled nationwide transparency for sales engineers and service teams. The platform remained in use after my departure, serving as the operational basis for future system upgrades.

# II. Executive Summary – 100-Words Exceptional Work Statement (xAI Application)

I built a complete end-to-end Demonstration Equipment Management System for Dräger Medical Systems in the US, managing over 10M USD of high-value medical devices. The system unified inventory tracking, shipping, calibration, and service workflows across all North American field offices. I designed the database architecture, implemented the full software stack, optimised operational processes, and delivered a reliable tool that significantly reduced equipment loss and improved utilisation. The platform became the de-facto standard inside the organisation and was used long after my departure. This project demonstrates my capability to design mission-critical systems independently and deliver measurable business impact.

# III. GitHub Repository Structure (README + folders + diagrams)

# III.1. Repository Structure

draeger-demo-equipment-system/
│
├── README.md
├── docs/
│   ├── executive-summary.md
│   ├── system-architecture.md
│   ├── database-schema.md
│   ├── workflow-diagrams.md
│   └── project-impact.md
│
├── diagrams/
│   ├── high-level-architecture.txt
│   ├── asset-flow-diagram.txt
│   ├── database-er-diagram.txt
│   └── shipping-workflow.txt
│
├── src/
│   ├── backend/
│   │   ├── sql-queries/
│   │   │   └── example-queries.sql
│   │   └── schema/
│   │       └── asset-tables.sql
│   │
│   ├── frontend/
│   │   └── vba-screenshots/
│   │       ├── dashboard.png
│   │       ├── asset-form.png
│   │       └── shipping-form.png
│   │
│   └── utils/
│       └── automation-macros.bas
│
└── legacy/
    └── history-and-background.md

# III.2. README.md – Complete GitHub Front Page

# Dräger Demo Equipment Management System  
### Full-Stack Operational Logistics Platform for High-Value Medical Devices  
### Author: Robert Csató

## Overview
This repository documents the design, architecture, and workflow of the Demonstration Equipment Management System built for Dräger Medical Systems Inc. (North America). The system managed a 10M USD device fleet across regional field offices, supporting the company’s sales and clinical teams.

## Features
- Complete asset lifecycle tracking  
- Shipping & return workflow automation  
- Calibration management  
- Service logging and maintenance tracking  
- Multi-location utilisation analysis  
- Warehouse ↔ field office synchronisation  

## Architecture
The system was built as a hybrid:
- SQL-based backend  
- Microsoft Access relational schema  
- VBA-driven frontend  
- Barcode-ready lookup functions  
- Automated alerts & integrity checks

## Repository Structure
- `docs/` → project documentation  
- `diagrams/` → architecture and workflow diagrams  
- `src/` → conceptual backend/frontend assets  
- `legacy/` → historical and background materials  

## Purpose of This Repo
This repository serves as a technical and architectural demonstration of:
- end-to-end system design  
- data modelling  
- operational problem solving  
- cross-department workflow engineering  
- enterprise-grade tool development  

## Relevance
This project highlights the ability to independently design and implement a mission-critical system—highly relevant for engineering roles requiring architectural thinking, evaluation methodologies, user-centric design, and operational excellence.


# III.3. Diagrams (ASCII Text)

        SUPPLIERS / MANUFACTURERS
                    │
                    ▼
           DEMO EQUIPMENT WAREHOUSE
                    │
                    ▼
       ┌───────────────────────────────┐
       │  ASSET TRACKING SUBSYSTEM    │
       └───────────────────────────────┘
                    │
                    ▼
  FIELD OFFICES  ←  SYSTEM  →  SERVICE CENTERS
                    │
                    ▼
        HOSPITAL DEMONSTRATION SITES


# III.3. Asset-flow-diagram.txt

ASSET CREATION
      ↓
INVENTORY STORAGE
      ↓
FIELD OFFICE DISPATCH
      ↓
CUSTOMER DEMONSTRATION
      ↓
RETURN / SERVICE
      ↓
READY FOR NEXT DEPLOYMENT
