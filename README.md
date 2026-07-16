# SafeX Solutions — Process-Improvement Proposal
**Group 40 Mini-Project · Week 2 Individual Module · Ayza Waseem**

## What this is
A working fix for one recurring inefficiency at a cybersecurity/digital-services firm: vulnerability
assessment findings are usually handed off as a static report with no shared record of what's still
open, who owns it, or by when. This repo contains a spreadsheet-based **Vulnerability Findings &
Remediation Tracker** that replaces that email-and-memory hand-off, plus the write-up explaining the
current process, the proposed process, and the expected impact.

## Contents
| File | Description |
|---|---|
| `Process_Improvement_Proposal.docx` | Full written proposal: current process, proposed process, the module explained, expected impact, implementation plan, risks. |
| `SafeX_Vulnerability_Tracker.xlsx` | The working module — a 4-tab workbook (Read Me, SLA Reference, Findings Log, Dashboard), pre-loaded with 10 sample findings. |
| `screenshots/` | Rendered screenshots of every tab in the workbook. |
| `Video_Script_and_Progress_Report.md` | Talking-point outline for the mandatory explanation video, and this week's progress-report text. |

## How to run / view the module
1. Open `SafeX_Vulnerability_Tracker.xlsx` in Excel, or upload it to Google Drive and open with Google Sheets.
2. Read the **Read Me** tab first — it has the colour legend and usage notes.
3. Go to **Findings Log** to see the sample data. Try adding a new row: fill in the blue-font cells, and
   pick a Severity and Status from the dropdown lists.
4. Open the **Dashboard** tab — the totals and chart update automatically, no refresh needed.
5. To change remediation policy (e.g. give High severity findings 5 days instead of 7), edit the
   **SLA Reference** tab — every finding's due date recalculates automatically.

## Why a spreadsheet, not custom software
The required technologies for this task are Excel, Google Docs, or an existing SafeX system — deliberately,
so a delivery team can adopt the fix the same day with no procurement, licensing, or training overhead.
Everything here (SLA lookups, due-date math, conditional-formatting colour coding, dropdown validation, and
a live formula-driven dashboard) is built entirely with native spreadsheet features.

## Scope note
This module is scoped to the Process-Improvement Proposal track only. It is coordinated with, and does not
duplicate, the other Week 2 modules from this group: Yousma's Data Cleaning & Mini-Analysis task and
Mahira's Internal Documentation task.
