# Resident No-Response Maintenance Access Checklist for Property Managers

Campaign marker: `NO-RESPONSE-MAINTENANCE-ACCESS-READY`

Use this checklist when a resident opened a maintenance request, stopped replying, and the property manager needs a safe, documented way to coordinate access without inventing consent, entry rights, fees, or vendor timing.

Canonical owned article: https://liquidhorizon88-bot.github.io/horizon-flow-ebook-hub/articles/resident-no-response-maintenance-access-checklist-property-managers.html?utm_source=gist&utm_medium=free&utm_campaign=local_lead_rescue_no_response_maintenance_access&utm_content=resource_pack

Free missed-lead checklist: https://liquidhorizon88-bot.github.io/horizon-flow-ebook-hub/free/missed-lead-checklist.html?utm_source=gist&utm_medium=free&utm_campaign=local_lead_rescue_no_response_maintenance_access&utm_content=owned_article

Local Lead Rescue System: https://horizonflow.gumroad.com/l/local-lead-rescue-system?utm_source=gist&utm_medium=free&utm_campaign=local_lead_rescue_no_response_maintenance_access&utm_content=owned_article

## Source fields

- Resident / unit / request ID
- Original issue and urgency: routine / urgent / emergency / habitability-sensitive / unknown
- Last resident reply date + channel
- Access requirement: permission required / notice allowed / emergency entry / manager review required
- Vendor constraints: available windows, lockbox/key rules, pet notes, parking, elevator, gate/fob needs
- Policy/legal review owner

## Resident-safe follow-up

> Hi {{resident_name}}, we still have your maintenance request for {{issue_summary}} open. Please reply with a good access window or confirm whether the issue is resolved. If we do not hear back by {{review_time}}, our team will review the lease/policy record before deciding the next safe step. We will not assume permission or mark the request complete without a documented review.

> Hi {{resident_name}}, quick follow-up: maintenance is ready to schedule {{issue_summary}}, but we need either your preferred access window or manager-reviewed instructions before sending a vendor. Reply here or through the resident portal with any pet, gate, parking, or availability notes.

## CRM labels

- `resident_no_response_access_needed`
- `manager_entry_review_required`
- `vendor_window_pending_resident`
- `possible_emergency_entry_review`
- `request_maybe_resolved_unconfirmed`

## STOP AUTOMATION guardrails

STOP AUTOMATION if the message would claim legal entry rights, waive or charge fees, promise a vendor arrival time, discuss safety/habitability conclusions, expose private resident details to a vendor, or close the request without source proof. Route to manager/legal/policy review instead.

## AI summary prompt

```
Summarize this maintenance no-response case for a property manager. Use only the source notes provided. Include: resident/unit/request ID, issue summary, last contact attempt, access requirement, vendor constraints, CRM label, owner/due time, and unresolved questions. Do not infer consent, entry rights, fees, emergency status, resident intent, or vendor ETA.
```
