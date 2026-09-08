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

### 1. Record Weight, Not Servings

Replace "servings" with weight as the recorded unit.

The alternative — defining a standardized serving size for each item — would technically resolve the ambiguity, but it requires maintaining a definition table across a rotating menu and re-deriving it every time a recipe, pan, or product changes. It drifts silently. Weight is already the same unit across every item on the sheet, and most products arrive with weight on the label.

The kitchen is also already most of the way there. Cooks work from recipes with defined portions, which means batch size is standardized — the system has a stable physical quantity. It simply never recorded what that quantity weighs.

This change enables aggregation, comparison across items, and trend analysis over time. None of the three are possible under the current unit.

---

### 2. Measurement Procedure

Usage is calculated as:

Used = Starting Weight After Prep + Additions − Remaining Weight After Service

The starting weight only has to be measured once per item. Because production follows a standardized recipe, a full pan of a given item weighs approximately the same every time it is made. Establish that weight on the first run, record it, and reuse it. From then on the only weighing required during service is what remains at the end.

Two one-time measurements are needed to make this work:

Item weight. A full pan of each menu item, weighed once, recorded against the recipe.
Pan tare. Hotel pans vary in weight by size and gauge. Record the empty weight of each pan type and subtract it. At production volume, an unsubtracted tare compounds into a material error.

The standing item weight should be re-verified when a recipe changes, when pan size changes, or on a set interval, since yield varies with trim loss, cook loss, and who produced the batch. Treating it as fixed indefinitely reintroduces the drift this proposal is meant to remove.

What this measures, and what it does not. Remaining weight after service is measurable surplus — food produced and not served. Used is what left the pan. Pan weight cannot distinguish food that went onto a plate from food discarded during service, so this procedure measures surplus reliably and does not measure total waste. That boundary should be stated wherever the resulting figures are reported.

Operational cost. Neither kitchen currently has a scale. That is the entire capital requirement. After the one-time item and tare weights are established, the recurring cost is a single weighing per item at the end of service.

Manual entry of "Used" should be eliminated. The value should be derived from the recorded weights rather than estimated, which introduces basic verification and error detection.

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

Measurement rules should be consistent across all menu items. Where consistency is not possible, item-specific rules should be documented explicitly. This prevents ambiguity and silent interpretation drift.

Site identifier. The current form carries no field identifying which facility produced it, which is adequate while it is used at a single site. If the same form is adopted across multiple facilities under one operator, records become indistinguishable once separated from their origin and cannot be pooled or compared by site. A single site field prevents this.

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
