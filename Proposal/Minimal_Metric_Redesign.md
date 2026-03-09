# Minimal Redesign Proposal for Food Usage Measurement

## Objective

The goal of this proposal is not to redesign the entire food tracking system, but to identify the **smallest set of changes** required to make the existing log actionable.

The emphasis is on feasibility, clarity, and accountability.

---

## Design Principles

The proposed changes follow three principles:

1. **Minimal disruption**  
   Existing workflows should change as little as possible.

2. **Defined meaning**  
   Every recorded value must have a clear, shared interpretation.

3. **Enforced calculation**  
   Usage should be derived, not estimated.

---

## Proposed Changes

### 1. Replace “Servings” With a Defined Unit

Replace the ambiguous “servings” unit with one of the following:
- Weight-based units (preferred), or
- A clearly defined standardized portion size per item

This change alone enables:
- Aggregation
- Comparison
- Trend analysis

---

### 2. Enforce Usage Calculation

Usage should be automatically or procedurally calculated as:

> **Used = Starting Quantity + Additions − Remaining**

Manual entry of “Used” should be discouraged or eliminated to reduce estimation error.

This introduces basic verification and error detection.

---

### 3. Tie Quantities to Demand

Each meal record should explicitly associate food quantities with:
- Census count, and
- Planned production (if available)

This enables:
- Per-person usage analysis
- Identification of overproduction
- Meaningful efficiency metrics

---

### 4. Standardize Across Items

Measurement rules should be consistent across all menu items.

Where consistency is not possible, item-specific rules should be documented explicitly.

This prevents ambiguity and silent interpretation drift.

---

## Expected Outcomes

With these minimal changes, the log would support:
- Valid aggregation across meals and time periods
- Detection of abnormal waste patterns
- Verification of reported improvements
- Clear ownership of results

Most importantly, the system would shift from **documentation** to **measurement**.

---

## Scope Note

This proposal does not address:
- Staffing
- Training
- Procurement
- Software implementation

Its purpose is to demonstrate that accountability begins with measurement clarity.