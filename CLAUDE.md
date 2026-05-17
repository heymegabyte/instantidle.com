# instantidle.com

## Purpose

Scale-to-zero Cloudflare Containers deployment app store / launcher for self-hostable services.

## Scope

This skill contains **site-specific/domain-specific logic only**.

It is automatically composed with the shared base layer:
- `.agentskills/base-layer/SKILL.md` (folder)
- base skill slug: `cloudflare-angular-saas`

Do **not** duplicate generic process rules here (TDD loop, Playwright discipline, Semgrep, deploy verification, docs gates). Those belong to the base layer.

## Auto-Inclusion (Repository Detection)

Claude Code / Emdash should auto-select this overlay when repository evidence points to **instantidle.com**:
- git remote / repo name / workspace name
- package or app names
- Cloudflare routes / deployment URLs / domains
- README / docs / branding references

If multiple overlays appear possible, choose the closest one, state the assumption, and continue.

## Site-Specific Focus Areas

- Catalog/app templates, deployment orchestration, and container lifecycle UX
- Cloudflare Containers provisioning, suspend/resume, and cost-aware operations
- Tenant/account boundaries, logs, and deployment state visibility
- Docs for app onboarding, prerequisites, and rollback/recovery flows
