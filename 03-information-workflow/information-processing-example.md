# Information Processing Workflow

## Scenario

**Role:** Project Coordinator

**Scenario:** A supplier has delayed the delivery of a product required for an organizational project.

## Information Task Used

**Task:** Extracting and restructuring information into action items.

**Why this task was selected:** The supplier update contains limited information, so the goal is to identify what is confirmed, what action is needed, and what information is still missing without making assumptions.

---

## 1. Input — Raw Information

The following supplier update is the available source:

> The delivery of the required product has been delayed. The revised delivery date will be confirmed soon.

This is the complete available information. No additional supplier details, dates, names, or reasons have been provided.

---

## 2. Prompt

Act as a project coordinator.

Review the supplier delivery update and identify:

1. Confirmed facts
2. Required action items
3. Owners
4. Deadlines
5. Priority
6. Status

Use the following action-item table:

| Action Item | Owner | Deadline | Priority | Status |
|---|---|---|---|---|

Do not invent missing information. If an owner or deadline is not provided, write [Not Specified]. Clearly distinguish confirmed information from assumptions.

---

## 3. AI Output

### Confirmed Information

- The delivery of the required product has been delayed.
- The revised delivery date will be confirmed soon.
- No specific revised date has been provided.

### Action Items

| Action Item | Owner | Deadline | Priority | Status |
|---|---|---|---|---|
| Confirm the revised supplier delivery date | [Not Specified] | [Not Specified] | High | Pending |
| Assess the project impact after the revised date is confirmed | [Not Specified] | [Not Specified] | High | Pending |

---

## 4. Human Review

The AI output was reviewed against the original supplier update.

### Review Findings

- The statement that delivery is delayed is supported by the source.
- The revised delivery date is correctly identified as not yet available.
- No supplier name was added.
- No reason for the delay was invented.
- No specific project delay duration was invented.
- Owners and deadlines were not invented.
- The priority classification is a working project-management classification, not a fact stated by the supplier.

The action items are reasonable next steps, but the project coordinator should confirm ownership and deadlines before assigning them.

---

## 5. Final Structured Output

### Confirmed Status

The required product delivery has been delayed. The revised delivery date is still pending confirmation.

### Action Items

| Action Item | Owner | Deadline | Priority | Status |
|---|---|---|---|---|
| Confirm the revised supplier delivery date | [Not Specified] | [Not Specified] | High | Pending |
| Assess the project impact after the revised date is confirmed | [Not Specified] | [Not Specified] | High | Pending |

### Information Still Required

- Revised delivery date
- Reason for the delay, if available
- Confirmed project impact
- Action owners
- Action deadlines

### Human Decision

The project coordinator should confirm the missing information before making changes to the project schedule or assigning formal commitments.

---

## Workflow Summary

**Input → Prompt → AI Output → Human Review → Final Structured Output**

The workflow demonstrates how unstructured supplier information can be transformed into a decision-ready structure while keeping missing information clearly marked as [Not Specified].
