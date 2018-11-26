---
layout: single
title: <i class="fas fa-cube"></i> Item Process
permalink: /manual/item/
author_profile: false
sidebar:
  nav: "manual"
toc: true
toc_label: Index
toc_icon: list-ol
---
## Goal
The goal of the item process is to provide the required materials, in the required quantity at the required time to it's customer.

---

## Responsibility and authority
### Waterjet operator
The waterjet operator is responsible for the waterjet.

### Sheet metal worker

### Machinist

---

## SIPOC
### Supplier
The main suppliers of the **ITEM PROCESS** is the **ORDER PROCESS** and the **PURCHASE PROCESS**

---

### Inputs
* Kanban cards detailing shape, material grade and quantity
* Stock materials

---

### Process
```
|--- Requested
|--- Cut
      |--- Cutting
            |--- Waterjet
            |--- Saw
            |--- Shear
            |--- Manual
      |--- Cutting done
|--- Form
      |--- Forming
            |--- Bend
            |--- Roll
            |--- Machine
      |--- Forming done
|--- Done
```

---

### Outputs
Items ready for fit-up in steel assemblies and material traceability records (if applicable)

---

### Customers
The main customer of the item process is the product process, but might also include department 61 Workshop or the end customer

---
