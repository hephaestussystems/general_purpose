# Sana Connector Knowledge Base - Full Content

**Last updated:** 2026-06-29 (Full Refresh)
**Total connectors:** 106
**Source:** https://intercom-help.eu/workday-sana/en/collections/1389607-connector-guides

**Scanned: 2026-06-29**

---

## 15Five

**Source:** https://intercom-help.eu/workday-sana/en/articles/634196-15five

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect 15Five to Sana to access performance management data. Retrieve user profiles, view check-in details, and send High Five recognitions to celebrate your team.

In summary, the connector has the following key characteristics:

Category: HR | Connector type: Real-time | Auth type: API keys | Hosting type: Managed

# Capabilities

Get user profiles, View check-ins, Send High Fives

# Tools

Create high five, Get checkin details, Get user, List user options

# Triggers

New 1-on-1 Created, New Checkin Created, New High Five Received

# Scope and permissions

This connector uses API keys.

---

## AWS

**Source:** https://intercom-help.eu/workday-sana/en/articles/636404-aws

Category: Engineering | Connector type: Real-time | Auth type: API keys | Hosting type: Managed

# Capabilities

Query DynamoDB, Read S3 files, Invoke Lambda functions, Query Redshift, Send SQS messages, Send SNS messages, Send EventBridge events, Write CloudWatch logs

# Known limitations

- S3 search: File search is limited
- S3 file formats: Limited to specific formats

---

## Airbyte

**Source:** https://intercom-help.eu/workday-sana/en/articles/634168-airbyte

Category: Engineering | Connector type: Real-time | Auth type: API keys | Hosting type: Managed

# Capabilities

List workspaces, Create workspaces, Update workspaces, Delete workspaces

---

## Airtable

**Source:** https://intercom-help.eu/workday-sana/en/articles/606510-airtable

Category: Project management | Connector type: Real-time | Auth type: OAuth | Hosting type: Managed

# Known limitations

- Cannot update bases and/or records
- Cannot fetch detailed user data, only user IDs

---

## Canva

**Source:** https://intercom-help.eu/workday-sana/en/articles/617323-canva

**Scanned: 2026-06-29**

### Introduction
Connect Canva to Sana to pull design content into your context. Review, summarize, and analyze designs in Canva without leaving Sana.

**Characteristics:**
- Category: Design
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

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
| profile:read | Read basic information about your Canva user profile |
| asset:read | View existing assets in your Canva account |
| asset:write | Create or update assets in your Canva account |
| brandtemplate:content:read | View full content of brand templates |
| brandtemplate:meta:read | View metadata about brand templates |
| design:content:read | View full content of your designs |
| design:content:write | Create or update designs |
| design:meta:read | View metadata for designs |

### Known Limitations
**Read-only:** The connector can only access and read content from Canva; it cannot create or update designs or assets.