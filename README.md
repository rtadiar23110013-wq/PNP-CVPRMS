# Computerized Violation Processing and Records Management System for PNP Checkpoints (PNP-CVPRMS)

## 📌 Project Overview

The **Computerized Violation Processing and Records Management System for PNP Checkpoints (PNP-CVPRMS)** is a specialized records and citation management solution designed to streamline checkpoint operations for the Philippine National Police (PNP).

The system modernizes traditional paper-based citation procedures by providing digital verification of drivers and vehicles, automated penalty computation, real-time citation generation, and centralized records management for traffic violations committed at police checkpoints.

\---

## 🗂️ Repository Folder Structure

This repository is organized into structural and design documentation required for the system architecture:

```text
.
├── DFD/                          # Data Flow Diagrams
│   ├── stage0/                   # Context Diagram (Overview of system entities)
│   ├── stage1/                   # Level 1 DFD (Major system processes)
│   └── stage2/                   # Level 2 DFD (Detailed sub-processes)
├── Structured\_Chart/             # System Architecture \& Module Hierarchy
├── HIPO Diagram/                 # Hierarchy plus Input-Process-Output Diagrams
├── Structured\_English/           # Natural language business logic and decision rules
├── Pseudo\_Code/                  # Step-by-step system algorithms
│   └── process\_violation.txt    # Main violation screening and citation logic
├── ERD/                          # Entity-Relationship Diagram \& Database Schemas
└── Data\_Dictionary/              # Comprehensive database field definitions
```

\---

## ⚙️ Key Features \& System Capabilities

1. **Driver \& Vehicle Screening:**

   * Real-time lookup of driver's licenses and vehicle plate numbers.
   * Flagging of stolen vehicles, expired registrations, or wanted individuals.
2. **Violation Recording \& Citation Issuance:**

   * Selection of single or multiple traffic/checkpoint violations.
   * Automatic generation of official citation tickets with unique tracking numbers.
3. **Automated Fine \& Penalty Computation:**

   * Instant computation of total fines based on standard PNP offense schedules.
4. **Centralized Records Management:**

   * Secure logging of violations, checkpoint locations, and duty officer details.
   * Status tracking for ticket payments and record clearance.
5. **Reporting \& Analytics:**

   * Generation of summary reports for checkpoint activity and offense trends.

\---

## 👥 Project Team \& Contributions

* ##### System Architecture \& Documentation: 
* Casey Freud - Leader
* Angelo
* Antonio
* Augusto
* Manuel
* Benjie
* Emmanuel John
* Genuflect
* Ranier

---

# 📑 System Design Documentation

This repository contains various software engineering diagrams and documentation that describe the overall structure, functionality, and workflow of the Computerized Violation Processing and Records Management System (PNP-CVPRMS).

## 📌 Data Flow Diagram (DFD)

### Stage 0 – Context Diagram

**Description:**

The Context Diagram presents the highest-level view of the PNP-CVPRMS. It illustrates how external entities, such as Police Officers, Drivers, Administrators, and the Database, interact with the system through the exchange of information. It defines the system boundary and the major inputs and outputs without showing internal processes.

![Context Diagram](DFD/stage0/context-diagram.png)
---

### Stage 1 – Level 1 Data Flow Diagram

**Description:**

The Level 1 DFD decomposes the Context Diagram into the system's major functional processes. It illustrates how data moves between modules such as Driver Verification, Violation Recording, Citation Processing, Records Management, and Report Generation while interacting with the database.

![Level 1 DFD](DFD/stage1/level1-dfd.png)
---

### Stage 2 – Level 2 Data Flow Diagram

**Description:**

The Level 2 DFD provides a more detailed representation of selected Level 1 processes. It breaks down complex operations into smaller subprocesses, showing the detailed flow of data during checkpoint screening, violation validation, citation generation, and database updates.

![Level 2 DFD](DFD/stage2/level2-dfd.png)
---

## 📌 Structured Chart

**Description:**

The Structured Chart illustrates the hierarchical organization of the system modules. It shows the relationship between the main program and its submodules, indicating how each module communicates and transfers control during system execution.

![Structured Chart](Structured_Chart/structured-chart.png)
---

## 📌 HIPO (Hierarchy plus Input-Process-Output) Diagram

**Description:**

The HIPO Diagram documents each system module by describing its required inputs, internal processing, and generated outputs. It serves as a blueprint for understanding the functional responsibilities of every major component of the PNP-CVPRMS.

![HIPO Diagram](HIPO%20Diagram/hipo-diagram.png)
---

## 📌 Structured English

**Description:**

Structured English provides a clear and readable description of the business rules and decision-making logic used by the system. It uses simple English statements combined with programming constructs such as IF, THEN, ELSE, WHILE, and FOR to describe how each process operates.

![Structured English](Structured_English/structured-english.png)
---

## 📌 Pseudocode

**Description:**

The Pseudocode contains step-by-step algorithmic procedures for implementing the system processes. It describes the logical flow of operations, including driver verification, violation validation, fine computation, citation generation, and database updates without using any specific programming language syntax.

![Pseudocode](Pseudo_Code/process-violation.png)
---

## 📌 Entity Relationship Diagram (ERD)

**Description:**

The Entity Relationship Diagram illustrates the database design of the PNP-CVPRMS. It identifies the system entities, their attributes, primary and foreign keys, and the relationships between tables such as Drivers, Vehicles, Violations, Citations, Police Officers, and Checkpoint Records.

![Entity Relationship Diagram](ERD/erd.png)
---

## 📌 Data Dictionary

**Description:**

The Data Dictionary serves as a comprehensive reference for all database tables and fields used in the system. It defines each attribute's name, data type, length, constraints, purpose, and relationships to ensure consistency during database development and maintenance.

![Data Dictionary](Data_Dictionary/data-dictionary.png)
---
