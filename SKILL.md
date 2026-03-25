---
name: ics-crm-reminder
description: "Generates ICS calendar files with structured CRM data for B2B sales follow-ups."
version: 1.0.0
metadata:
  openclaw:
    requires:
      bins:
        - python3
    emoji: "📅"
    homepage: "https://github.com/KopfKinoK3/ics-crm-reminder"
---

# ICS CRM Reminder — Mini-CRM im Kalender

Generates professional ICS calendar files with complete CRM information for B2B customer outreach. Double-click to import into Apple Calendar, Google Calendar, or Outlook.

## When to use this skill

Use this skill whenever a user needs to create a calendar reminder for a customer call, follow-up, or sales meeting. The user provides customer data, and the skill generates a clean ICS file with all CRM details structured in the event description.

## Supported fields

| Field | Required |
|-------|----------|
| Company | Yes |
| Date | Yes |
| Time | Yes |
| Contact person | No |
| Phone | No |
| Email | No |
| Topic / Reason | No |
| Priority (high/medium/low) | No |
| Deal phase | No |
| Budget | No |
| Next step | No |
| Notes | No |

## Output

Structured ICS file with mini-CRM entry in the DESCRIPTION field. RFC 5545 compliant.
