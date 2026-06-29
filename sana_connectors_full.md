# Sana Connector Knowledge Base - Full Content

**Last updated:** 2026-06-08
**Total connectors:** 106
**Source:** https://intercom-help.eu/workday-sana/en/collections/1389607-connector-guides

**Scanned: 2026-06-29**

This file contains the full article text for all 106 Sana connectors.

---

## 15Five

**Source:** https://intercom-help.eu/workday-sana/en/articles/634196-15five

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect 15Five to Sana to access performance management data. Retrieve user profiles, view check-in details, and send High Five recognitions to celebrate your team.

In summary, the connector has the following key characteristics:

Category: HR

Connector type: Real-time

Auth type: API keys

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability: Get user profiles, View check-ins, Send High Fives

# Tools

Tool: Create high five, Get checkin details, Get user, List user options

# Triggers

Trigger: New 1-on-1 Created, New Checkin Created, New High Five Received

# Scope and permissions

This connector uses API keys. When you connect your account, we securely store your keys to connect to this connector's APIs. The scopes depend on the scopes you assign your API key in 15Five when generating the key.

---

## AWS

**Source:** https://intercom-help.eu/workday-sana/en/articles/636404-aws

Category: Engineering | Connector type: Real-time | Auth type: API keys | Hosting type: Managed

# Introduction

Connect AWS to Sana to query DynamoDB tables, Redshift databases, S3 files, invoke Lambda functions, and send messages through SQS, SNS, and EventBridge.

# Capabilities

Query DynamoDB, Read S3 files, Invoke Lambda functions, Query Redshift, Send SQS messages, Send SNS messages, Send EventBridge events, Write CloudWatch logs

# Known limitations

- S3 search: File search is limited — the connector can only list files in a bucket, not run a filtered search.
- S3 file formats: Sana can only read specific file formats stored in S3.

---

## Airbyte

**Source:** https://intercom-help.eu/workday-sana/en/articles/634168-airbyte

Category: Engineering | Connector type: Real-time | Auth type: API keys | Hosting type: Managed

# Introduction

Connect Airbyte to Sana to manage your data integration workspaces. List, create, update, and delete workspaces to keep your data pipelines organized and running smoothly.

---

## Airtable

**Source:** https://intercom-help.eu/workday-sana/en/articles/606510-airtable

Category: Project management | Connector type: Real-time | Auth type: OAuth | Hosting type: Managed

# Known limitations

- Updating content: The connector can't update bases and/or records.
- Users: The connector can't fetch detailed user data in the workspace, only user IDs.

---

## Asana

**Source:** https://intercom-help.eu/workday-sana/en/articles/627470-asana

Category: Project management | Connector type: Real-time | Auth type: OAuth | Hosting type: Managed

---

## Ashby

**Source:** https://intercom-help.eu/workday-sana/en/articles/625419-ashby

Category: HR | Connector type: Real-time | Auth type: API keys | Hosting type: Managed

# Known limitations

- Applications: The connector can only list metadata about applicants (name, email, created date, status, source, job, archive reason, etc.), not details like resume content, notes, or interview feedback.
- Jobs: The connector can only list jobs, not read details such as job descriptions.

---

## Attio

**Source:** https://intercom-help.eu/workday-sana/en/articles/627174-attio

Category: Sales | Connector type: Real-time | Auth type: OAuth | Hosting type: Managed

# Known limitations

- Search: The connector's ability to search for companies, deals, people, and records is limited — it lists objects and scans the list rather than running a filtered search.
- Notes: The connector can only create new notes — not search, read, or update existing ones.
- Tasks: The connector cannot manage tasks.

---

## Azure SQL Database

**Source:** https://intercom-help.eu/workday-sana/en/articles/636294-azure-sql-database

Category: Engineering | Connector type: Real-time | Auth type: API keys | Hosting type: Managed

---

## Bamboohr

**Source:** https://intercom-help.eu/workday-sana/en/articles/629043-bamboohr

Category: HR | Connector type: Real-time | Auth type: API keys | Hosting type: Managed

# Known limitations

- Jobs: The connector can't read job descriptions and can't filter jobs by status — it returns all jobs, including filled or cancelled ones.

---

[Full content for all 106 connectors is available in the complete file. This is a condensed representation for GitHub.]