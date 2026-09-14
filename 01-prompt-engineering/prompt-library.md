# Prompt Library

## Scenario

**Role:** Project Coordinator

**Workplace Scenario:** A supplier has delayed the delivery of a product required for an organizational project.

**Purpose:** Use Generative AI to communicate the delay, structure information, assess impact, plan recovery actions, and prepare professional updates while avoiding invented information.

---

## Prompt 1: Supplier Delay Team Update

**Workplace Task:** Communicate a supplier delivery delay to the project team.

**Framework:** C.A.R.E.

**Prompt:**

Context: A supplier has delayed the delivery of a product required for an organizational project.

Action: Create a concise professional update for the project team. Clearly state the affected product, the delivery delay, the reason for the delay if provided, the revised delivery date if available, the impact on the project if confirmed, and any action required from the team.

Role: Act as a project coordinator communicating with an internal project team.

Expected Output: Provide a short and clear team update with:
- Current situation
- Confirmed facts
- Project impact
- Required actions

Do not invent missing information. If a date, reason, owner, impact, or other detail is not provided, write [Not Specified].

**Example Output:**

Subject: Supplier Delivery Delay – Project Update

The delivery of the required product has been delayed. The revised delivery date and reason for the delay have not yet been confirmed.

The project team should monitor the supplier update and assess any potential impact once the revised delivery information is available.

Action required: Confirm the revised delivery date when provided and update the project plan accordingly.

---

## Prompt 2: Supplier Delay Stakeholder Email

**Workplace Task:** Draft a professional email to stakeholders about the supplier delay.

**Framework:** R.C.T.O.

**Prompt:**

Role: Act as a project coordinator.

Context: A supplier has delayed the delivery of a product required for an organizational project.

Task: Draft a professional email to relevant stakeholders explaining the supplier delivery delay.

Output: Include:
- A clear subject line
- Brief summary of the delay
- Confirmed facts
- Project impact
- Required next steps
- Information that still needs confirmation

Do not invent dates, names, reasons, owners, commitments, or project impacts. Use [Not Specified] when information is unavailable.

---

## Prompt 3: Delay Impact Assessment

**Workplace Task:** Assess how the supplier delay may affect the project.

**Framework:** C.A.R.E.

**Prompt:**

Context: A supplier has delayed delivery of a product required for an organizational project.

Action: Analyze the available information and identify confirmed impacts, possible risks, affected activities, and information that needs to be verified.

Role: Act as a project coordinator responsible for monitoring project risks and dependencies.

Expected Output: Present the assessment under these headings:
1. Confirmed Impact
2. Potential Risks
3. Affected Activities
4. Information Requiring Verification
5. Recommended Next Action

Do not assume that the project is delayed by a specific number of days unless this is confirmed. Do not invent dates, owners, or causes.

---

## Prompt 4: Action Item Extraction

**Workplace Task:** Convert supplier delay information into clear action items.

**Framework:** R.C.T.O.

**Prompt:**

Role: Act as a project coordinator.

Context: Review information about a supplier delivery delay for an organizational project.

Task: Extract all clear action items and organize them into an action-item table.

Output: Use exactly these columns:

| Action Item | Owner | Deadline | Priority | Status |
|---|---|---|---|---|

Do not invent owners or deadlines. If they are not provided, use [Not Specified]. Only identify actions supported by the source information.

**Example Output:**

| Action Item | Owner | Deadline | Priority | Status |
|---|---|---|---|---|
| Confirm the revised supplier delivery date | [Not Specified] | [Not Specified] | High | Pending |
| Assess the project impact after the revised date is confirmed | [Not Specified] | [Not Specified] | High | Pending |

---

## Prompt 5: Supplier Delay Recovery Plan

**Workplace Task:** Create a structured recovery plan after a supplier delay.

**Framework:** C.A.R.E.

**Prompt:**

Context: A supplier has delayed delivery of a product required for an organizational project.

Action: Create a structured recovery plan that helps the project coordinator manage the delay and reduce potential project impact.

Role: Act as a project coordinator responsible for project continuity and risk management.

Expected Output: Structure the plan as:
1. Goal
2. Mechanisms
3. Phases
4. Tasks
5. Dependencies
6. Decision Points

Clearly distinguish confirmed information from assumptions. Do not invent deadlines, owners, delivery dates, or supplier commitments. Use [Not Specified] when information is unavailable.

---

## Prompt 6: Management Status Brief

**Workplace Task:** Prepare a concise management update about the supplier delay.

**Framework:** R.C.T.O.

**Prompt:**

Role: Act as a project coordinator preparing a management status brief.

Context: A supplier has delayed delivery of a product required for an organizational project.

Task: Summarize the situation for management and highlight the information needed for decision-making.

Output: Use the following structure:
- Status
- Key Confirmed Facts
- Business or Project Impact
- Key Risk
- Actions Underway
- Decision or Support Required
- Information Still Pending

Keep the language concise and professional. Do not invent information. Use [Not Specified] for missing dates, owners, reasons, figures, impacts, or decisions.
