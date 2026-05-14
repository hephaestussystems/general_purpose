# Sana Top 10 Connector Reference

*Compiled by Leila Ahmadi, CTO — Hephaestus Systems*  
*Source: Sana Connector Guides · May 2026*

This document contains the full capability details for the 10 highest-value Sana connectors
for Workday consulting engagements: capabilities, tools, and permissions for each.
Intended for use in LLM-assisted use case development, demo scripting, and client discovery.

---

## #1: Workday

*Source: https://support.sana.ai/en/articles/563343-connector-guide-workday*

### Introduction

Sana connects directly to Workday through the Self-Service Agent, giving you access to a wide range of HR, Finance, and Payroll actions without leaving the chat.

### Capabilities

| Capability | Description |
| --- | --- |
| Personal Information & Benefits | View your compensation, benefits, and personal information |
| Time & Attendance | Manage time off requests, view balances, and submit time entries |
| Performance & Development | Manage performance reviews, feedback, and goals |
| Team & Organization | View your org structure, team information, and coworker details |
| Talent & Recruitment | Create referrals, view candidate status, and find job openings |
| Payroll | View pay information, direct deposit, and tax forms |

> Data access is governed by Workday's internal permission system. This means:
> - Users can only access data they're authorized to see in Workday
> - Permissions mirror what the user can already do in Workday directly
> - No additional scope configuration is needed in Sana

### Known limitations

- Human-in-the-loop: For the Workday connector, Sana does not directly handle read or write actions. When a user wants to update something, Sana hands the request over to Workday’s self-service agent (WSSA), which completes the change on its own. As a result, there is no approval or “human-in-the-loop” step shown in the Sana UI for these actions.
- Speed: As Sana hands the action over to Workday’s self-service agent (WSSA) to complete, the overall speed is dependent on how quickly Workday's agent processes the request, so results may arrive more slowly than for actions handled directly in Sana or via other 3rd party connectors.

---

## #2: SharePoint

*Source: https://support.sana.ai/en/articles/563345-connector-guide-sharepoint*

### Introduction

Connect SharePoint to Sana to search, read, and manage files across sites, drives, and folders. Summarize complex material, extract key points, create folders, and bring together content across your company's knowledge.

In summary, the connector has the following key characteristics:

- Categories: File storage, Documents
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

This connector is able to do the following:

| Capability |
| --- |
| List sites |
| Find files |
| Find folders |
| Read files |
| Create folders |
| Share files |

### Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about SharePoint. In practice, the agent may call one or more tools to achieve a single capability.

| Tool |
| --- |
| Create folder |
| Create link |
| Create list |
| Download file |
| Download files |
| Find file by name |
| Find files with metadata |
| Get current user |
| Get excel table |
| Get file by id |
| Get site |
| List files in folder |
| List sites |
| Retrieve file metadata |
| Search and filter files |
| Search files |
| Search sites |
| Select files |

### Scope and permissions

This connector uses OAuth. When you connect your account, you will need to sign into your account and grant the required permissions:

| Scope | Purpose |
| --- | --- |
| offline_access | Keep Sana connected without re-login |
| email | Identify your Microsoft account email |
| openid | Secure sign-in and basic identity |
| Site.Manage.All | Configure SharePoint sites and settings |
| Sites.Read.All | Let Sana read all SharePoint content |
| Sites.ReadWrite.All | Read and update SharePoint files and lists |
| User.Read.All | Read organisation users for permissions |
| Group.Read.All | Read Microsoft 365 groups for access |
| Sites.FullControl.All | Allow Sana to manage sites |

### Known limitations

- File formats: Sana can only read the following file formats stored in SharePoint: doc, docx, dot, dotx, dotm, xls, xlsm, xlsx, pps, ppsx, ppt, pptx, odp, ods, odt, rtf, eml, msg, htm, html, markdown, md, epub, tif, tiff, pdf, jpeg, jpg, png, gif, webp, loop, fluid, fluidframework, whiteboard, wbtx, form, note, page, pulse, loot, dwg, dsn.
- Search: The connector does not support full-text search inside files. It can only locate files by title or metadata, then read the file once it has been found — broad content-discovery searches are limited.

---

## #3: Outlook Email

*Source: https://support.sana.ai/en/articles/563349-connector-guide-outlook-email*

### Introduction

Connect Outlook Email to Sana to find, send and manage your emails. Revisit old conversations, capture action items, summarize attachments, prepare drafts and send follow-ups based on your context instead of starting from scratch.

In summary, the connector has the following key characteristics:

- Category: Communication
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

This connector is able to do the following:

| Capability |
| --- |
| Find emails |
| List important mail |
| Draft emails |
| Draft replies |
| Send emails |
| Read attachments |
| List labels |
| Update labels |
| List folders |
| List contacts |
| Create contacts |
| Update contacts |

### Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Outlook Email. In practice, the agent may call one or more tools to achieve a single capability.

| Tool |
| --- |
| Add label to email |
| Approve workflow |
| Create contact |
| Create draft email |
| Create draft reply |
| Download attachment |
| Find contacts |
| Find email |
| Find shared folder email |
| Get current user |
| Get message |
| List contacts |
| List folders |
| List important mail |
| List labels |
| Move email to folder |
| Remove label from email |
| Reply to email |
| Send email |
| Update contact |

### Scope and permissions

This connector uses OAuth. When you connect your account, you will need to sign into your account and grant the required permissions:

| Scope | Purpose |
| --- | --- |
| user.read | See your basic account details |
| email | Identify your Microsoft email address |
| offline_access | Keep Sana connected between logins |
| openid | Secure sign-in and identity tokens |
| profile | Show your name and profile picture |
| Mail.ReadWrite | Read, organize, and edit your email |
| Mail.Send | Send emails on your behalf from Sana |
| MailboxSettings.ReadWrite | Manage time zone, rules, and signatures |
| IMAP.AccessAsUser.All | Sync mail via IMAP when needed |
| POP.AccessAsUser.All | Fetch mail via POP if configured |
| SMTP.Send | Send mail through your SMTP server |
| Calendars.ReadWrite | Read and update your calendars |
| Contacts.ReadWrite | Read and update your contacts |
| User.ReadBasic.All | See basic details of coworkers |

### Known limitations

- Attachment formats: The connector can only read the following formats in attachments: pdf, jpeg, jpg, png, gif, webp, txt, html, docx. Other file types cannot currently be opened, read, or summarized.
- Message flags and categories: The connector does not modify label/category definitions and cannot mark emails as read or unread.
- Folders: The connector cannot create, rename, or delete folders. It can only see and work with top-level folders — it can tell you whether a top-level folder contains sub-folders, but cannot list those sub-folders or act on them.

---

## #4: Salesforce

*Source: https://support.sana.ai/en/articles/563350-connector-guide-salesforce*

### Introduction

Connect Salesforce to Sana to find, create and update accounts, leads, contacts, and opportunities. Research, enrich and keep your customer data up-to-date with context from your connected apps to close more deals.

In summary, the connector has the following key characteristics:

- Category: Sales
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

This connector is able to do the following:

| Capability |
| --- |
| Find accounts |
| Create accounts |
| Update accounts |
| Find leads |
| Create leads |
| Update leads |
| Find contacts |
| Create contacts |
| Update contacts |
| Find opportunities |
| Create opportunities |
| Update opportunities |
| Find notes |
| Create notes |
| Update notes |

### Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Salesforce. In practice, the agent may call one or more tools to achieve a single capability.

| Tool |
| --- |
| Create crm record |
| Delete crm record |
| Describe object |
| Get related records |
| Get user info |
| List objects |
| Soql query |
| Text search |
| Update crm record |

### Scope and permissions

This connector uses OAuth. When you connect your account, you will need to sign into your account and grant the required permissions.

---

## #5: Outlook Calendar

*Source: https://support.sana.ai/en/articles/563344-connector-guide-outlook-calendar*

### Introduction

Connect Outlook Calendar to Sana to quickly find events, check availability, and create or update meetings with a simple prompt. Prepare for upcoming calls, clean up conflicts, and revisit past events when you need a quick recap.

In summary, the connector has the following key characteristics:

- Category: Productivity
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

This connector is able to do the following:

| Capability |
| --- |
| Find events |
| Check availability |
| Find meeting times |
| Create events |
| Update events |

### Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Outlook Calendar. In practice, the agent may call one or more tools to achieve a single capability.

| Tool |
| --- |
| Create calendar event |
| Delete calendar event |
| Delete recurring event instance |
| Find meeting times |
| Get current user |
| Get event |
| Get schedule |
| List events |
| Search contacts |
| Search people |
| Update calendar event |
| Update recurring event instance |

### Scope and permissions

This connector uses OAuth. When you connect your account, you will need to sign into your account and grant the required permissions:

| Scope | Purpose |
| --- | --- |
| user.read | See your basic account details |
| email | Identify your Microsoft email address |
| offline_access | Keep Sana connected between logins |
| openid | Secure sign-in and identity tokens |
| profile | Show your name and profile picture |
| calendars.readwrite | Read and update your calendars |
| people.read | See people you work and meet with |

### Known limitations

- Contacts: The connector does not have access to your contacts, so other participants must be specified by their email address rather than by name.

---

## #6: Google Drive

*Source: https://support.sana.ai/en/articles/563347-google-drive*

### Introduction

Connect Google Drive to Sana to search, read, create, and manage files across drives and folders. Manage access, organize folders and review comments across your organization's knowledge.

In summary, the connector has the following key characteristics:

- Categories: File storage, Documents
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

This connector is able to do the following:

| Capability |
| --- |
| List drives |
| Find files |
| Read files |
| Create files |
| Update files |
| Copy files |
| Find folders |
| Create folders |
| Update folders |
| List comments |
| Create comments |
| Update comments |

### Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Google Drive. In practice, the agent may call one or more tools to achieve a single capability.

| Tool |
| --- |
| Add comment |
| Copy file |
| Create file from template |
| Create file from text |
| Create folder |
| Create shared drive |
| Delete comment |
| Delete file |
| Delete reply |
| Delete shared drive |
| Download file |
| Find file |
| Find folder |
| Find forms |
| Find spreadsheets |
| Get comment |
| Get current user |
| Get file by id |
| Get folder id for path |
| Get reply |
| Get shared drive |
| List access proposals |
| List comments |
| List files |
| List replies |
| Move file |
| Move file to trash |
| Reply to comment |
| Resolve access proposal |
| Resolve comment |
| Search shared drives |
| Update comment |
| Update file |
| Update reply |
| Update shared drive |

### Scope and permissions

This connector uses OAuth. When you connect your account, you will need to sign into your account and grant the required permissions:

| Scope | Purpose |
| --- | --- |
| https://www.googleapis.com/auth/drive | Read, create and manage Drive files |

### Known limitations

- File formats: The connector can only read the following file formats in your Google Drive: Google Docs, Google Sheets, Google Slides, Google Drawing, PDF, JPEG, PNG, GIF, WEBP.
- Folder metadata: The connector cannot edit folder metadata (such as name or location); it can only delete folders.
- Comments: The connector cannot determine which specific element (text, cell, object, etc.) a comment is attached to — it can only list comments in a file.
- Version history: The connector cannot access version history, so it cannot answer questions like "What changed recently in this doc, and who made the changes?".

---

## #7: Microsoft Teams

*Source: https://support.sana.ai/en/articles/634147-connector-guide-microsoft-teams*

### Introduction

Connect Microsoft Teams to Sana to send messages and search conversations across direct messages and channels. Send updates to channels and chats, search across messages and view shifts directly from Sana.

In summary, the connector has the following key characteristics:

- Category: Communication
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

This connector is able to do the following:

| Capability |
| --- |
| Search messages |
| Send messages |
| Create channels |
| List channels |

### Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Microsoft Teams. In practice, the agent may call one or more tools to achieve a single capability.

| Tool |
| --- |
| Create channel |
| Get chat message |
| Get current user |
| List channel messages |
| List channels |
| List chats |
| List messages in chat |
| List shifts |
| List teams |
| Search messages |
| Send channel message |
| Send chat message |

### Scope and permissions

This connector uses OAuth. When you connect your account, you will need to sign into your account and grant the required permissions:

| Scope | Purpose |
| --- | --- |
| User.Read | Read basic profile information for the signed-in user. |
| email | Read the user's primary email address. |
| offline_access | Maintain access to Microsoft Teams data when you are not actively signed in. |
| openid | Sign you in and identify you using the OpenID Connect protocol. |
| profile | Read additional basic profile details (name, picture, locale). |
| Chat.Read | Read 1:1 and group chat messages you have access to. |
| Chat.ReadWrite | Read and send or edit chat messages you have access to. |
| ChatMessage.Send | Send new messages in chats on your behalf. |
| Channel.ReadBasic.All | Read basic information about all Teams channels (name, description, membership). |
| ChannelMessage.Read.All | Read all messages in all Teams channels you have permission to access. |
| ChannelMessage.Send | Send new messages in Teams channels on your behalf. |
| Team.ReadBasic.All | Read basic information about all Teams (name, description, membership). |
| Schedule.Read.All | Read calendar and scheduling information across Teams and Outlook for your tenant. |

---

## #8: ServiceNow

*Source: https://support.sana.ai/en/articles/600476-connector-guide-servicenow*

### Introduction

Connect ServiceNow to Sana to quickly explore, search, and manage your table records. Handle incidents, manage your service catalog, and keep your ServiceNow data clean and up to date without leaving Sana.

In summary, the connector has the following key characteristics:

- Category: Support
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

This connector is able to do the following:

| Capability |
| --- |
| List tables |
| Find table records |
| Search records |
| Create table records |
| Update table records |
| Delete table records |

### Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about ServiceNow. In practice, the agent may call one or more tools to achieve a single capability.

| Tool |
| --- |
| Create table record |
| Delete table record |
| Get current user |
| Get record counts by field |
| Get table record by id |
| Get table records |
| List tables |
| Search records by keyword |
| Update table record |

### Scope and permissions

This connector uses OAuth. When you connect your account, you will need to sign into your account and grant the required permissions.

### Known limitations

- Admin pre-setup required: ServiceNow's OAuth flow requires a workspace admin to register custom OAuth applications inside your ServiceNow instance and share the resulting Client ID and Client Secret with each user who needs to connect. The OAuth callback must point at https://api.pipedream.com/connect/oauth/oa_g2oiqA/callback (Sana connects via Pipedream). Refer to ServiceNow's own docs on OAuth Application Registry for the in-product setup steps.
- No granular scopes: ServiceNow's OAuth implementation does not support resource-level scopes. Access is gated by the roles assigned to the connecting user (e.g. itil, admin, read_only_admin) and by table-level ACLs in your instance. Admins must ensure the connecting user has the right roles and that the relevant tables have GET/POST/PATCH/DELETE/PUT methods enabled for the operations Sana should perform.

---

## #9: Slack

*Source: https://support.sana.ai/en/articles/598448-connector-guide-slack*

### Introduction

Connect Slack to Sana to search conversations and send messages in Slack channels. Find important threads, send updates, manage channels, and stay on top of your team communication without leaving Sana.

In summary, the connector has the following key characteristics:

- Category: Communication
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

This connector is able to do the following:

| Capability |
| --- |
| List channels |
| Create channels |
| Search messages |
| Send messages |
| Update messages |
| Browse files |
| Find users |

### Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Slack. In practice, the agent may call one or more tools to achieve a single capability.

| Tool |
| --- |
| Add reaction |
| Browse files |
| Create channel |
| Edit message |
| Find user by email |
| Get channel history |
| Get thread replies |
| Get user details |
| List channels |
| Post message |
| Search |

### Scope and permissions

This connector uses OAuth. When you connect your account, you will need to sign into your account and grant the required permissions:

| Scope | Purpose |
| --- | --- |
| chat:write | Send and update messages in channels the app is a member of |
| chat:write.customize | Customize the appearance of messages sent to channels |
| chat:write.public | Send messages to public channels the user is not yet a member of (the app is auto-joined) |
| files:read | Read files shared in channels the app has access to (e.g. previews and content) |

### Known limitations

- Direct messages: The connector only works with messages in channels — it cannot search, read, or send direct messages or group DMs.
- User search: The "find users" capability only matches by exact email. As a workaround you can list all users to locate the right one, but this is impractical in large workspaces (the list is paginated).
- Channel search: The connector lists channels and searches within those results in batches of 250 — it cannot search channels by title or metadata directly. Search quality drops in workspaces with many channels, so naming the exact channel works best.

---

## #10: Jira

*Source: https://support.sana.ai/en/articles/596247-connector-guide-jira*

### Introduction

Connect Jira to Sana to search and manage issues. Track work, transition issues, assign issues, and stay on top of your team's progress with context from your connected apps.

In summary, the connector has the following key characteristics:

- Category: Project management
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

This connector is able to do the following:

| Capability |
| --- |
| List users |
| List spaces |
| Find issues |
| List comments |
| Create comments |
| Update comments |
| Manage boards |
| Manage sprints |
| List epics |

### Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Jira. In practice, the agent may call one or more tools to achieve a single capability.

| Tool |
| --- |
| Add comment to issue |
| Add watcher to issue |
| Assign issue |
| Check issues against jql |
| Count issues using jql |
| Create custom field options context |
| Create future sprint |
| Create version |
| Delete project |
| Get all projects |
| Get board |
| Get cloud id |
| Get current user |
| Get issue |
| Get issue picker suggestions |
| Get issue types |
| Get sprint |
| Get task |
| Get transitions |
| Get user |
| Get users |
| List board issues |
| List boards |
| List epic issues |
| List epics |
| List issue comments |
| List sprint issues |
| List sprints |
| Move issues to sprint |
| Search issues with jql |
| Search issues with jql post |
| Transition issue |
| Update comment |

### Scope and permissions

This connector uses OAuth. When you connect your account, you will need to sign into your account and grant the required permissions:

| Scope | Purpose |
| --- | --- |
| read:jira-work | Read Jira work data like spaces and issues |
| manage:jira-project | Create and configure projects, roles, and settings |
| read:jira-user | Read Jira user profiles and basic account details |
| write:jira-work | Create, edit, transition, and comment on issues |
| read:me | Read information about the currently authenticated user |
| offline_access | Refresh access tokens when the user is offline |
| read:issue-details:jira | Read detailed issue content, history, and comments |
| read:field:jira | Read field definitions, metadata, and field values |
| read:project:jira | Read project metadata, categories, and configurations |
| write:field.option:jira | Create and update options for custom select fields |
| read:custom-field-contextual-configuration:jira | Read context-specific custom field configs per project |
| read:jql:jira | Validate and inspect JQL queries and search metadata |
| manage:jira-webhook | Create, update, and delete Jira webhooks for events |

### Known limitations

- Attachments: The connector cannot read or write attachments in Jira.
- Managed Jira only: The connector only supports managed (cloud) Jira — self-hosted instances are not supported.
- One app at a time: The connector supports a single connected Jira app, selected during set up.
- Deletion: The connector cannot delete users, issues, or comments.
- Custom objects and fields: Limited support for writing and updating custom objects and fields.

---
