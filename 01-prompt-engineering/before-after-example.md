# Before/After Prompt Example

## Scenario

A supplier has delayed the delivery of a product required for an organizational project. The project coordinator needs to communicate the situation clearly without inventing missing information.

---

## Before — Weak Prompt

Write an email about the delayed product.

---

## Initial Result

Subject: Delayed Product

Dear Team,

I wanted to inform you that the supplier has delayed the product delivery. This may affect the project schedule. Please be aware of the delay and take the necessary actions.

Best regards,
Project Coordinator

---

## After — Improved Prompt

**Context:** A supplier has delayed the delivery of a product required for an organizational project.

**Action:** Draft a concise professional email to the internal project team communicating the supplier delivery delay. Clearly state the affected product, the confirmed delay, the revised delivery date if available, the reason for the delay if provided, the confirmed project impact, and any required action.

**Role:** Act as a project coordinator communicating with an internal project team.

**Expected Output:** Provide:
- A clear subject line
- A short summary of the situation
- Confirmed facts
- Project impact
- Required action
- Information that still needs confirmation

Do not invent dates, reasons, names, owners, project impacts, or commitments. If information is unavailable, write [Not Specified].

---

## Improved Result

**Subject: Supplier Delivery Delay – Project Update**

Dear Team,

I would like to provide an update regarding the delivery of the product required for the project. The supplier has confirmed that the delivery has been delayed.

The revised delivery date and reason for the delay have not yet been confirmed. The project impact therefore requires further assessment once the revised delivery information is available.

**Action required:**
- Confirm the revised delivery date when it becomes available.
- Assess the project impact based on the confirmed delivery date.
- Update the project plan if required.

Please note that no additional dates, causes, or commitments have been assumed.

Best regards,  
Project Coordinator

---

## What Improved?

- **Clearer context and audience:** The improved prompt specifies the supplier-delay scenario and that the message is for the internal project team.
- **Better structure:** The improved prompt defines exactly what the output should contain.
- **Higher accuracy:** It explicitly prevents the AI from inventing dates, reasons, names, owners, impacts, or commitments.
- **More actionable output:** The final email separates confirmed information from information that still needs confirmation and identifies the required next steps.
