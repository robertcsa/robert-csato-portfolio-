# Dräger North America – Demonstration Equipment Management System  
**Full-Stack Operational Logistics Platform (10M USD Asset Base)**  
**Author: Robert Csató**  
**Location: Danvers, MA (USA)**  
**Period: 2004–2005**

---

## 1. Overview

This document describes the design and implementation of a full-stack, enterprise-grade Demonstration Equipment Management System I developed during my time at **Dräger Medical Systems Inc., North America**.

The system managed:
- the entire **demonstration equipment fleet**,  
- valued at approximately **USD 10 million**,  
- across **all North American regional field offices**,  
- supporting sales engineers, clinical specialists, and emergency care equipment demonstrations.

The platform remained in use **after my departure**, serving as the operational baseline for later internal system upgrades.

---

## 2. Objective of the System

Dräger required a centralised solution capable of:

1. Tracking high-value medical demonstration units  
   (Delta, DeltaM, DeltaXL, Omega, OmegaM, OmegaXL, ventilators, monitors, accessories).

2. Managing:
   - inventory status  
   - location  
   - movement between field offices  
   - shipping and returns  
   - maintenance cycles  
   - calibration intervals  
   - loan periods for hospitals and distributors  

3. Reducing operational losses and misplacements.

4. Improving the speed and reliability of the sales team's demonstration workflow across the US.

---

## 3. System Architecture

The system was designed as a **full-stack Access/SQL hybrid application**, consisting of:

### 3.1. Backend
- Microsoft Access database engine  
- Custom SQL queries  
- Optimised relational schema  
- Asset movement logs  
- Full event history per device  
- Status tracking (Available / Out for Demo / Under Repair / Lost / Retired)

### 3.2. Frontend
- Custom VBA-driven interface  
- Searchable dashboard  
- Multi-filter data views  
- Barcode-based quick lookup (via handheld scanners)  
- Form-based equipment assignment and retrieval workflows  

### 3.3. Operational Modules
- Shipping module  
- Return module  
- Damage & service reporting module  
- Inventory cycle count assistance  
- Field office allocation  
- Automated reminders for overdue devices  

---

## 4. Database Design (Core Tables)

