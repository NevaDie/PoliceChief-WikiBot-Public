---
layout: default
title: Privacy Policy
---

# Privacy Policy

**Last updated: 7 November 2026**

This page explains what information Police Chief WikiBot handles, why it is
needed, and what choices users have.

## 1. Project and contact

Police Chief WikiBot is an independent community project.

- Project contact: use `/feedback` in Discord
- Project operator: **NevaDie**
- Contact email: **[policechiefwikibot@outlook.com](mailto:policechiefwikibot@outlook.com)**

## 2. Information processed

Depending on the feature used, WikiBot may process:

- Discord user, server, and channel identifiers
- Personal and server language preferences
- Server time-zone and time-format settings
- Configured update and event channels
- Event schedules, native Discord event links, and reminder configuration
- Optional per-occurrence attendance responses and the responding user's Discord ID
- Attendance announcement channel/message IDs used to restore buttons after restarts
- Delivery timestamps for recurring setup reminders
- Command usage information used for aggregate statistics
- Feedback content voluntarily submitted through `/feedback`
- Technical error information required to diagnose failures

WikiBot does not store ordinary Discord chat messages, member lists, server
invitations, email addresses, or IP addresses.

Attendance is voluntary. Event announcements show counts only; event managers
with Manage Events can request a private roster containing responding users'
Discord IDs and their choices. These records cover people who respond, not a
downloaded server member directory. No ordinary chat content is stored.
Read Message History is used only to find the bot's own attendance announcement
after an interrupted send; messages inspected for recovery are not retained.

## 3. Why this information is used

The information above is used to run commands, remember selected settings,
deliver schedules and announcements, keep the service reliable, understand
general usage, and investigate reports.

## 4. Usage statistics

Identifiers used for aggregate usage statistics are pseudonymized and retained for no more than 90 days.

## 5. Retention

- Attendance responses and announcement records are retained until 30 days after
  that occurrence ends. They are also removed when the schedule is deleted or
  the bot leaves the server. Disabling attendance closes responses while keeping
  existing responses until their normal expiry.
- Usage-history records are retained for no more than 90 days.
- User settings are retained until removed or no longer required.
- Server configuration is retained while needed to provide configured features.
- Feedback submitted through `/feedback`, together with the sender's Discord ID
  and server context, is delivered to the project owner as a Discord direct
  message. It remains there until that Discord message is deleted.
- A server ID and delivery time may be kept after a setup reminder is sent, so
  the same reminder is not sent again for 30 days. This record is removed when
  the bot leaves the server.
- Technical logs are retained only as long as needed for security and troubleshooting.

## 6. User controls

Use `/data delete` to remove your recorded usage history, personal language
preference and all stored attendance responses. Use **Clear response** under an
attendance announcement to remove only that occurrence's response. You can
change your response until the event ends. Counts refresh on the next worker
cycle after a data-deletion request.

Server managers can disable configured channels and schedules through the corresponding server commands. Removing WikiBot from a server stops future processing for that server, except for limited records that must temporarily remain for security, integrity, or legal reasons.

## 7. Third-party services

WikiBot operates through Discord and relies on hosting and infrastructure providers. Those services may process technical connection and account information under their own privacy terms.

External links, including Top.gg, Ko-fi, and independent guide websites, lead to services with their own privacy policies.

## 8. Data sharing

WikiBot does not sell personal data. Information is shared only when required to operate the service, respond to a lawful request, protect users and the project, or when the user intentionally submits information to an external service.

## 9. AI-assisted project work

AI tools, including OpenAI's Codex, may assist the project owner with software
development, documentation, data organization, troubleshooting, and translation
drafts. The live bot does not use generative AI to produce command responses,
and ordinary Discord interactions are not automatically sent to an AI provider.

Private feedback is not routinely sent to AI tools. If AI assistance is useful
for investigating a report, only the minimum necessary excerpt should be used
after removing Discord IDs, usernames, server or channel names, and unrelated
personal details. Final decisions about bot behavior, published game data, and
translations are made by the project owner.

See [Use of AI Tools](./docs/ai-use.md) for a plain-language explanation.

## 10. Children

WikiBot is intended for users who are permitted to use Discord under Discord's applicable age requirements and terms.

## 11. Changes

This policy may be updated when WikiBot features, providers, or legal requirements change. The date at the top identifies the latest revision.

## 12. Unofficial project notice

Police Chief WikiBot is not affiliated with, endorsed by, or officially connected to Police Chief, WAL Games, Discord, Top.gg, Ko-fi, or their respective owners.
