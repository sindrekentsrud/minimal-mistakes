---
layout: single
classes: wide
title: <i class="fas fa-cubes"></i> Machining process
permalink: /manual/machining/
author_profile: false
sidebar:
  nav: "manual"
toc: true
toc_label: Index
toc_icon: list-ol
---
## Goal
The goal of the machining process is to produce awesome looking parts that are within the specified tolerances in the most efficient way possible.

### Fundamental measurements
* Throughput
* Lead time
* Cycle time
* Flow efficiency

## SIPOC
### Supplier
The main suppliers are:
* Order process
* Material process


---

### Inputs
Under normal circumstances work should not start without *full kit* consisting of:

#### Kanban cards
Cards shall provide information regarding:
* What does the customer want - specification & drawing
* When does the customer want it - due date
* What amount does the customer want - quantity
* Product routing

#### Materials
The **Machining** process shall receive all the neccessary stock required to produce the component from the **Material** process.

---

### Process
```
|--- Backlog
|--- Requested
  |--- New requests
  |--- Waiting for materials
  |--- Waiting for machining
|--- In progress
  |--- CAM
  |--- Setup
  |--- Machining
  |--- Inspection
  |--- Documentation
|--- Done
```

---

### Outputs
The expected output from the **Machining** process consists of:
* Parts without any quality related issues regarding:
  - Dimensions - we are sure it will fit
  - Surface finish - we are sure our customers will be impressed
* Documentation that validates that all requirements have been met regarding:
  - *Documentation to be agreed*

---

### Customers
The main customers of the *Machining* process are the following:
 - **Fit-Up** process
 - **Welding** process
 - **Assembly** sub-system
 - **End-user** customers

---
