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
* Item process


---

### Inputs
Under normal circumstances work should not start without *full kit* consisting of:

#### Kanban cards
Cards shall provide information regarding:
* What does the customer want - specification & drawing
* When does the customer want it - due date
* What amount does the customer want - quantity
* Product routing

#### Items
The machining process shall receive all the neccessary items required to produce the component from the **Item** process.

---

### Process
```
|--- Backlog
|--- Requested
  |--- New requests
  |--- Waiting for items
  |--- Ready to start
|--- In progress
  |--- Welding
  |--- Ready for inspection
  |--- Inspection
  |--- Ready for testing
  |--- Testing
  |--- Ready for external services
  |--- External services
|--- Done
```

---

### Outputs
The expected output from the **Products** process consists of:
* Products without any quality related issues regarding:
  - Dimensions and parts - we are sure it will fit
* Documentation that validates that all requirements have been met regarding:
  - Welding traceability
    *we know how it was welded and by whom*
  - Welding operator qualifications
    *we know how to weld it*
  - Non-destructive testing records
    *we know that our welds are free of defects*
  - Proof testing records
    *we know our welds and materials will not fail*
  - Surface treatment records
    *we know that our product will endure*

---

### Customers
The main customer of the *Products* process is the downstream system *Assembly*.

---
