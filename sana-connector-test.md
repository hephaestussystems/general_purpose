# Sana Connector Knowledge Base - Full Content

**Last updated:** 2026-06-18
**Total connectors:** 3 (test)
**Source:** https://intercom-help.eu/workday-sana/en/collections/1389607-connector-guides

This file contains full article text for 3 Sana connectors, formatted to match the existing knowledge base.

---

## Workday

**Source:** https://intercom-help.eu/workday-sana/en/articles/563343-workday

# Introduction

Sana connects directly to Workday through the Self-Service Agent, giving you access to a wide range of HR, Finance, and Payroll actions without leaving the chat.

# Capabilities

Capability: Personal Information & Benefits — View your compensation, benefits, and personal information
Capability: Time & Attendance — Manage time off requests, view balances, and submit time entries
Capability: Performance & Development — Manage performance reviews, feedback, and goals
Capability: Team & Organization — View your org structure, team information, and coworker details
Capability: Talent & Recruitment — Create referrals, view candidate status, and find job openings
Capability: Payroll — View pay information, direct deposit, and tax forms

Data access is governed by Workday's internal permission system. This means:
- Users can only access data they're authorized to see in Workday
- Permissions mirror what the user can already do in Workday directly
- No additional scope configuration is needed in Sana

# Known limitations

- Speed: As Sana hands the action over to Workday's self-service agent (WSSA) to complete, the overall speed is dependent on how quickly Workday's agent processes the request, so results may arrive more slowly than for actions handled directly in Sana or via other 3rd party connectors.

# FAQ

Q: How do I connect to Workday?
A: You don't need to connect to Workday - it's automatically available when you log in to Sana through SSO. No additional setup required.

Q: What permissions does Workday require in Sana?
A: Your existing Workday permissions determine what you can access in Sana. You can only see and do what you're already authorized for in Workday.

Related Articles: Frequently Asked Questions (FAQ), What is Sana, Privacy and permissions, Mural, Navigational search

---

## SharePoint

**Source:** https://intercom-help.eu/workday-sana/en/articles/563345-sharepoint

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect SharePoint to Sana to search, read, and manage files across sites, drives, and folders. Summarize complex material, extract key points, create folders, and bring together content across your company's knowledge.

In summary, the connector has the following key characteristics:
- Categories: File storage, Documents
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

# Capabilities

This connector is able to do the following:
- List sites
- List drives
- Find files
- Find folders
- Read files
- Create folders
- Share files

# Tools

Create folder, Create link, Create list, Download file, Download files, Find file by name, Find files with metadata, Get current user, Get excel table, Get file by id, Get site, List drives, List files in folder, List sites, Retrieve file metadata, Search and filter files, Search files, Search sites, Select files

# Triggers

File Updated or Deleted (Instant), New File Created, New Folder Created, New List Item, Updated List Item

# Scope and permissions

This connector uses OAuth. Scopes: offline_access (Keep Sana connected without re-login), email (Identify your Microsoft account email), openid (Secure sign-in and basic identity), Site.Manage.All (Configure SharePoint sites and settings), Sites.Read.All (Let Sana read all SharePoint content), Sites.ReadWrite.All (Read and update SharePoint files and lists), User.Read.All (Read organisation users for permissions), Group.Read.All (Read Microsoft 365 groups for access), Sites.FullControl.All (Allow Sana to manage sites)

# Set up instructions

Prerequisites: Sana Enterprise user, connector enabled by workspace owner.

Step 1: Go to the connectors page in Sana
Step 2: Find SharePoint in the list of available connectors
Step 3: Hover the connector card and click the connect button
Step 4: Initialize the Pipedream connection
Step 5: Sign in to SharePoint and approve the requested scopes
Step 6: Complete the set up

# Known limitations

- File formats: Sana can only read specific file formats stored in SharePoint
- Search: The connector does not support full-text search inside files. It can only locate files by title or metadata, then read the file once it has been found

Related Articles: Box, Dropbox, OneDrive, Microsoft Excel, Egnyte

---

## Slack

**Source:** https://intercom-help.eu/workday-sana/en/articles/598448-slack

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Slack to Sana to search conversations and send messages in Slack channels. Find important threads, send updates, manage channels, and stay on top of your team communication without leaving Sana.

In summary, the connector has the following key characteristics:
- Category: Communication
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

# Capabilities

This connector is able to do the following:
- List channels
- Create channels
- Search messages
- Send messages
- Update messages
- Browse files
- Find users

# Tools

Add reaction, Browse files, Create channel, Edit message, Find user by email, Get channel history, Get thread replies, Get user details, List channels, Post message, Search

# Triggers

New Channel Created (Instant), New Interaction Events (Instant), New Keyword Mention (Instant), New Message In Channels (Instant), New Private Channel Created, New Reaction Added (Instant), New Saved Message (Instant), New User Added (Instant), New User Mention (Instant)

# Scope and permissions

This connector uses OAuth. Scopes: chat:write (Send and update messages in channels the app is a member of), chat:write.customize (Customize the appearance of messages sent to channels), chat:write.public (Send messages to public channels the user is not yet a member of), files:read (Read files shared in channels the app has access to)

# Set up instructions

Prerequisites: Sana Enterprise user, connector enabled by workspace owner.

Step 1: Go to the connectors page in Sana
Step 2: Find Slack in the list of available connectors
Step 3: Hover the connector card and click the connect button
Step 4: Initialize the Pipedream connection
Step 5: Sign in to Slack and approve the requested scopes
Step 6: Complete the set up

# Known limitations

- Direct messages: The connector only works with messages in channels — it cannot search, read, or send direct messages or group DMs
- User search: The "find users" capability only matches by exact email
- Channel search: The connector lists channels and searches within those results in batches of 250

Related Articles: Salesforce, Zoom, Attio, Asana, Microsoft Teams

---
