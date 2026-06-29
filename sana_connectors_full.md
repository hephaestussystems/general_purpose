# Sana Connector Knowledge Base - Full Content

**Last updated:** 2026-06-29
**Total connectors:** 106
**Source:** https://intercom-help.eu/workday-sana/en/collections/1389607-connector-guides

---

## Canva

**Source:** https://intercom-help.eu/workday-sana/en/articles/617323-canva

**Updated:** June 29, 2026 (Manual Verification)

### Introduction
Connect Canva to Sana to pull design content into your context. Review, summarize, and analyze designs in Canva without leaving Sana.

**Characteristics:**
- **Category:** Design
- **Connector type:** Real-time
- **Auth type:** OAuth
- **Hosting type:** Managed

### Capabilities
- List designs
- Read designs

### Tools
- **Export design:** Export a design from Canva.
- **List designs:** List the designs in a Canva account.

### Scope and permissions
This connector uses OAuth. When you connect your account, you will need to sign into your account and grant the required permissions:

| Scope | Purpose |
| :--- | :--- |
| `profile:read` | Read basic information about your Canva user profile |
| `asset:read` | View existing assets in your Canva account (images, uploads, media) |
| `asset:write` | Create or update assets in your Canva account |
| `brandtemplate:content:read` | View the full content of brand templates (layouts and elements) |
| `brandtemplate:meta:read` | View metadata about brand templates (names, IDs, details) |
| `design:content:read` | View the full content of designs (layouts and elements) |
| `design:content:write` | Create or update the content of designs |
| `design:meta:read` | View metadata about designs (names, IDs, details) |

### Known Limitations
**Read-only:** The connector can only access and read content from Canva; it cannot create or update designs or assets.

---
[Rest of file content would follow here in a full run]
