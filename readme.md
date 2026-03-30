# Energy Management in Hybrid and Electric Vehicles – Lab Materials (01USGLO)

This repository contains the laboratory materials for the **2024/2025 edition** of the course *Energy Management in Hybrid and Electric Vehicles (01USGLO)*, held at **Politecnico di Torino** within the Master's Degree in Automotive Engineering.

## 🎯 Purpose of this Repository

This repository is for **instructors** who may want to:
- replicate the course structure fully or partially  
- reuse or adapt the laboratory material  
- design similar hands-on activities on energy management strategies  

The material reflects a **practice-oriented, lab-driven approach** to teaching energy management in hybrid electric vehicles.

---

## 🧪 Course Overview

Students are provided with a **quasi-static simulation model of a series HEV** and are asked to develop and compare different **energy management strategies**.

The course is organized into four modules, each focusing on a specific control approach:

- Rule-Based Control (**RBC**)  
- Equivalent Consumption Minimization Strategy (**ECMS**)  
- Adaptive ECMS (**A-ECMS**)  
- Dynamic Programming (**DP**)  

### 👥 Student Organization
- Students work in groups of 2–3
- Each group submits one assignment per module

### ⏱️ Teaching Format

| Module   | In-class hours |
|----------|----------------|
| RBC      | 6 hours        |
| ECMS     | 6 hours        |
| A-ECMS   | 4.5 hours      |
| DP       | 4.5 hours      |

Each module is structured as follows:
1. Introduction of key concepts using slides by the lab instructor  
2. Hands-on work on the lab assignment with support from 1 lab instructor and 2 teaching assistants. 

Since we have a numerous class (~160 students), we divided the class into two sub-classes; in total, we had 2 lab instructors and 4 teaching assistants.

---

## 📂 Repository Structure

### `01_RBC/`, `02_ECMS/`, `03_AECMS/`, `04_DP/`
Contains assignment templates and notebooks.
Assignment templates (MATLAB Live Scripts) are provided to students and they include: problem description, requirements and expected outputs. 

Students complete these files with their implementations, results and analysis  

Notebooks are released to the students only after an guided coding session held by the lead instructors.
They provide additional explanations, step-by-step example and coding support for initial implementation.
These are used to support students during the first stages of each module.

---

### `models/`
Contains the quasi-static HEV simulation models used throughout the course.

These models are the core environment that the students use to:
- implement control strategies  
- evaluate performance  

---

### `data/`
Includes:
- vehicle parameters  
- driving cycles  

Used as inputs for simulations.

---

### `utilities/`
Helper functions for:
- post-processing  
- visualization  
- result analysis  

---

## 🧑‍🏫 Teaching Notes

- The progression **RBC → ECMS → A-ECMS → DP** guides students from:
  - heuristic approaches  
  - to optimization-based strategies  

- The use of a ommon simulation framework ensures consistency across modules  

- Assignments are designed to balance:
  - implementation effort  
  - conceptual understanding  
  - result interpretation  

---

## 🔧 Reuse & Adaptation

You can adapt this material by:
- modifying vehicle parameters or driving cycles  
- simplifying or extending assignments  
- selecting only a subset of modules (e.g., RBC + ECMS for shorter courses)  

---

## 📬 Contact

If you plan to reuse or adapt this material, feel free to get in touch at federico.miretti@polito.it