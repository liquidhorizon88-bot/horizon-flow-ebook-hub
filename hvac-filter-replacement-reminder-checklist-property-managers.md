# HVAC Filter Replacement Reminder Checklist for Property Managers

A neutral source-card worksheet for property managers handling HVAC filter reminders, airflow notes, access questions, and preventive-maintenance messages.

Canonical resource: https://liquidhorizon88-bot.github.io/horizon-flow-ebook-hub/articles/hvac-filter-replacement-reminder-checklist-property-managers.html

## STOP AUTOMATION
Do not let AI diagnose HVAC performance, promise entry or completion times, assign lease responsibility, waive fees, tell residents to alter equipment, or close an airflow/health/safety concern without verified maintenance/manager review.

## Copy/paste intake fields

```text
Resident / unit: [name + unit]
Issue type: [routine filter reminder / airflow complaint / filter size question / access request / recurring issue / unknown]
Filter responsibility source checked: [lease / resident handbook / maintenance policy / owner instruction + as-of date]
Filter size / equipment record checked: [source + as-of date]
Access window or notice requirement: [verified rule + resident preference]
Health/safety language present: [yes/no + exact wording]
Prior related work order: [ticket ID + status]
Approved next step: [resident self-replace / maintenance visit / vendor review / manager review / needs more info]
CRM/PMS labels: [hvac-filter / preventive-maintenance / airflow-review / access-needed / manager-review]
STOP AUTOMATION if: health/safety concern, equipment diagnosis, fee/lease dispute, entry-right question, warranty issue, or unverified completion claim.
```

## Resident-safe acknowledgement

```text
Hi [Name], thanks for the note about the HVAC filter / airflow concern at [unit]. We have logged it and will check the maintenance record and applicable property instructions before confirming the next step. We do not want to guess about filter size, access, responsibility, or timing from the message alone.
```

## AI review prompt

```text
You are helping a property-management team summarize an HVAC filter replacement reminder, airflow note, or preventive-maintenance message for internal review. Use only the verified fields below. Do not invent filter size, lease responsibility, fees, access rights, repair completion, diagnosis, warranty coverage, resident history, or response timing.

Verified fields:
[PASTE INTAKE FIELDS]

Return:
1. One resident-safe acknowledgement under 70 words.
2. Internal summary for the work order.
3. Missing source fields to verify before sending.
4. STOP AUTOMATION risks.
```

Related product: Local Lead Rescue System — https://horizonflow.gumroad.com/l/local-lead-rescue-system?utm_source=gist&utm_medium=free&utm_campaign=ebook_marketing&utm_content=hvac_filter_replacement_reminder
