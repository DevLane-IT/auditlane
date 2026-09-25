# AuditLane public roadmap

This roadmap describes the public product direction of AuditLane. It is intentionally high-level and does not expose private implementation details, infrastructure design, credentials, or internal security controls.

## Current focus

### Evidence model
- Keep **MEASURED**, **DEMO**, **UNVERIFIED**, and **AI-GENERATED** states explicit.
- Preserve evidence provenance in finding details.
- Keep recommendations traceable to the evidence that supports them.
- Avoid turning missing evidence into a positive result.

### Audit workflow
- Guided audit setup.
- Bounded audit execution states.
- Clear success and failure states.
- Retry paths that do not present failed runs as completed.

### Reporting
- Structured finding details.
- Evidence and recommendation separation.
- Read-only public report sharing.
- Audit export states.
- Contextual explanations for evidence labels.

### Screen & journey analysis
- Screen capture analysis.
- Flow ordering and journey analysis.
- Explicit limits where behaviour, intent, or abandonment are not proven.

### Comparison & history
- Compare audit runs over time.
- Separate score movement from evidence quality.
- Highlight what improved, regressed, or stayed unchanged.

### Product experience
- Desktop, tablet, and mobile product flows.
- Contextual audit assistant.
- Notifications for long-running or completed work.
- Subscription, billing, and account management flows.

## Later

- Broader automation around recurring audits.
- More comparison and prioritisation workflows.
- Additional integrations where they materially improve the audit workflow.
- Expanded public documentation and examples.

## Not represented here

This public roadmap does not commit to release dates.

It also does not describe private infrastructure, internal security architecture, operational playbooks, source code milestones, or confidential commercial plans.
