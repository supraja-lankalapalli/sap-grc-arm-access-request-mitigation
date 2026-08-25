# Mitigating Control Configuration

## Overview

In this step, I worked on the mitigating control for the SoD risk that was identified during the preventive risk analysis.

The access was still required for the business scenario, so instead of removing the role, I handled the risk by configuring mitigating control `MC_B001`.

My goal in this step was to make sure the identified risk had a proper control, clear ownership, and monitoring responsibility before assigning the mitigation to the user.

---

## Mitigation Details

| Detail | Value |
|---|---|
| Risk ID | B001 |
| Mitigating Control | MC_B001 |
| Target System | TESTGRC447 |
| Mitigation Approver | BST_MITOWN1 |
| Control Monitor | BST_MITCNT1 |

---

## What I Did

I opened the mitigating control setup and configured control `MC_B001` for the identified risk.

I reviewed the control information and maintained the responsibility details for the mitigation process.

I assigned `BST_MITOWN1` as the mitigation approver and `BST_MITCNT1` as the control monitor.

I intentionally kept the approver and monitor as two different users.

This was important because I did not want the same person to approve the mitigation and also be responsible for monitoring the control.

Keeping these responsibilities separate helped maintain better control ownership and supported proper governance around the risk.

After reviewing the control setup, I saved the mitigating control with the required responsibility assignments.

---

## Why This Step Was Important

The SoD risk was already identified, but identifying the risk alone was not enough.

Since the business still required the access, I needed a way to manage the risk without simply removing the requested role.

The mitigating control provided that additional layer of oversight.

By assigning a separate approver and monitor, the control had both accountability and independent monitoring instead of depending on one person for everything.

---

## Evidence

### E21 – Mitigation Control Owner and Monitor Saved

This screenshot shows the mitigating control configuration for `MC_B001`.

It confirms that the mitigation approver and control monitor were maintained separately.

The screenshot also shows that the control information was saved successfully and was ready to be used for the user mitigation assignment.

![Mitigation Control Owner and Monitor](evidence/E21-control-owner-monitor-saved.png)

---

## Result

Mitigating control `MC_B001` was successfully configured for the identified SoD risk.

The control had separate responsibility for approval and monitoring, which helped make the mitigation process stronger and more controlled.

At this point, the control was ready to be assigned to user `BEST1` for risk `B001`.