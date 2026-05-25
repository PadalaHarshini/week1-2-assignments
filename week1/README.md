# JavaScript Fundamentals: Hands-On Assignments

This repository contains practical implementations of core JavaScript concepts. The tasks cover essential object manipulations, array methods, conditional statements, and arithmetic expressions.

---

##  Table of Contents
1. [Objects & Profiles](#1-objects--profiles)
2. [Array Processing & Iteration](#2-array-processing--iteration)
3. [Conditionals & Logic Engine](#3-conditionals--logic-engine)
4. [Arithmetic & Expense Operations](#4-arithmetic--expense-operations)

---

## 1. Objects & Profiles

### Assignment 1: User Profile Manager
* **Scenario:** Managing a logged-in user’s profile data dynamically.
* **Tasks:**
    * Read and print profile properties.
    * Dynamically add metadata (`lastLogin`).
    * Update user roles.
    * Safely delete specific tracking fields (`isActive`).
    * Extract remaining schema headers using `Object.keys()`.

### Assignment 2: Exam Result Summary
* **Scenario:** Processing subject-wise grades for student records.
* **Tasks:**
    * Iterate through scores to aggregate total marks.
    * Dynamically compute class averages.
    * Identify peak performance thresholds (highest scoring subject).
    * Append elective elements (`computer`) to data schemas.

### Assignment 3: Application Settings Controller
* **Scenario:** Controlling application runtime preferences.
* **Tasks:**
    * Toggle themes conditionally using ternary state switching.
    * Enforce critical application configuration states (`autoSave`).
    * Clean up state properties (`notifications`).
    * Immutably lock objects using `Object.freeze()` to prevent runtime alterations.

---

## 2. Array Processing & Iteration

### Assignment 1: Daily Temperature Analyzer
* **Scenario:** Filtering and scaling meteorological datasets.
* **Tasks:**
    * Isolate extreme heat indices (`filter()`).
    * Transform units from Celsius to Fahrenheit (`map()`).
    * Compute collective analytical trends (`reduce()`).
    * Locate critical outliers and their specific indexes (`find()`, `findIndex()`).

### Assignment 2: Online Course Name Processor
* **Scenario:** Processing string lengths and formats for storefront display grids.
* **Tasks:**
    * Filter out short or invalid metadata fields.
    * Normalize text entries to systematic casing structures.
    * Pipeline individual entries into localized, delimited text display streams.

### Assignment 3: Student Marks List
* **Scenario:** Evaluation logic for academic marking registers.
* **Tasks:**
    * Extract Passing indices.
    * Map collective standard adjustments (grace marks) across global rows.
    * Execute reduction workflows to find performance extremes.

---

## 3. Conditionals & Logic Engine

### Hands-On 1: Smart Login Status Engine
* **Scenario:** Multi-layered authentication gating workflows.
* **Logic:**
    * Unauthenticated users $\rightarrow$ `"Please login"`
    * Authenticated but unverified setups $\rightarrow$ `"Complete your profile"`
    * Fully verified states $\rightarrow$ `"Welcome back!"`

### Hands-On 2: Course Price Tag Labeler
* **Scenario:** Dynamically sorting product itemization strategies.
* **Logic:**
    * $< 500 \rightarrow$ `"Budget Course"`
    * $500 - 1000 \rightarrow$ `"Standard Course"`
    * $> 1000 \rightarrow$ `"Premium Course"`

### Hands-On 3: Enrollment Eligibility Checker
* **Scenario:** Instant verification using concise ternary logic expressions.
* **Logic:** Validates multi-flag dependencies simultaneously before issuing confirmation messages.

---

## 4. Arithmetic & Expense Operations

### Billing Operations
* **Scenario:** Sequential processing of a localized point-of-sale workflow.
* **Formula Flow:**
    $$\text{Total} \xrightarrow{+500} \text{Subtotal}_1 \xrightarrow{+1200} \text{Subtotal}_2 \xrightarrow{-200} \text{Net Price} \xrightarrow{+18\% \text{ GST}} \text{Final Bill}$$
* Outputs a cleanly precision-rounded localized currency value (`.toFixed(2)`).

---

##  Getting Started

To run any of the source scripts in your environment, execute the node process directly from your terminal:

```bash
node assignment6.js
