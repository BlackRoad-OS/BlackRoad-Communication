# BlackRoad-Communication

© 2026 BlackRoad OS, Inc. All rights reserved.

## PRIVATE REPOSITORY

Internal communication hub for BlackRoad OS team.

## Purpose

This repository serves as the central communication and coordination point:
- Team announcements
- Decision records (ADRs)
- Meeting notes
- Project updates
- RFC (Request for Comments) proposals
- Cross-repo coordination

## Contents

- `announcements/` - Company-wide announcements
- `decisions/` - Architecture Decision Records (ADRs)
- `meetings/` - Meeting notes and agendas
- `rfcs/` - Request for Comments proposals
- `updates/` - Weekly/monthly project updates
- `coordination/` - Cross-team coordination docs
- `templates/` - Communication templates

## Usage

This is a documentation-only repository. No code should live here.

### Creating an ADR

```bash
cp templates/adr-template.md decisions/YYYYMMDD-title.md
```

### Proposing an RFC

```bash
cp templates/rfc-template.md rfcs/YYYYMMDD-title.md
```

## Guidelines

- Keep it concise and actionable
- Use markdown for all documents
- Date-prefix files: YYYYMMDD-title.md
- Tag stakeholders with @mentions
- Link to relevant GitHub issues/PRs

## License

See [LICENSE](./LICENSE) - Internal use only
