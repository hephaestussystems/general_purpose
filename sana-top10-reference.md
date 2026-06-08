# Sana Top 10 Enterprise Connector Reference

**Generated:** 2026-06-08  
**Source:** [Sana Help Center](https://intercom-help.eu/workday-sana/en/collections/1389607-connector-guides)  
**Maintained by:** Hephaestus Systems

> Top 10 ranked by enterprise adoption, indexing depth, and ROI clarity for Workday shops.
> Scored from 106 total connectors as of 2026-06-08.

---

## #1 Salesforce

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/563350-salesforce>  
**Last checked:** 2026-06-08  
**Score:** 18

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Salesforce to Sana to find, create and update accounts, leads, contacts, and opportunities. Research, enrich and keep your customer data up-to-date with context from your connected apps to close more deals.

In summary, the connector has the following key characteristics:

-

Category: Sales

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Find accounts

Create accounts

Update accounts

Find leads

Create leads

Update leads

Find contacts

Create contacts

Update contacts

Find opportunities

Create opportunities

Update opportunities

Find notes

Create notes

Update notes

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Salesforce. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create crm record

Delete crm record

Describe object

Get related records

Get user info

List objects

Soql query

Text search

Update crm record

# Triggers

While tools are the actions an agent takes on your behalf, triggers are the events that can start an agent automatically. When you build an agent, you can choose one of the triggers below as its starting point. For example, having the agent run every time something new happens in Salesforce.

Trigger

Case Updated (Instant, of Selectable Type)

Email Template Updated (Instant, of Selectable Type)

Knowledge Article Updated (Instant, of Selectable Type)

New Case (Instant, of Selectable Type)

New Deleted Record (Instant, of Selectable Type)

New Email Template (Instant, of Selectable Type)

New Knowledge Article (Instant, of Selectable Type)

New Outbound Message (Instant)

New Record (Instant, of Selectable Type)

New Updated Record (Instant, of Selectable Type)

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Salesforce in the list of available connectors

Scroll to the Available connectors section and locate Salesforce.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Salesforce card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Select your Salesforce instance

In the Pipedream pop-up, choose the Salesforce instance you want to connect to:

-

Production — your live Salesforce environment, where your real data lives. This is the right choice for almost all users.

-

Sandbox — a non-production environment, useful for testing the connector without touching production data.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Salesforce account. Click Continue to complete the setup and start using the connector.

Related Articles Zoom Airtable Attio Monday Ironclad

---

## #2 Sharepoint

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/563345-sharepoint>  
**Last checked:** 2026-06-08  
**Score:** 18

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect SharePoint to Sana to search, read, and manage files across sites, drives, and folders. Summarize complex material, extract key points, create folders, and bring together content across your company&#x27;s knowledge.

In summary, the connector has the following key characteristics:

-

Categories: File storage, Documents

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List sites

List drives

Find files

Find folders

Read files

Create folders

Share files

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about SharePoint. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create folder

Create link

Create list

Download file

Download files

Find file by name

Find files with metadata

Get current user

Get excel table

Get file by id

Get site

List drives

List files in folder

List sites

Retrieve file metadata

Search and filter files

Search files

Search sites

Select files

# Triggers

While tools are the actions an agent takes on your behalf, triggers are the events that can start an agent automatically. When you build an agent, you can choose one of the triggers below as its starting point. For example, having the agent run every time something new happens in SharePoint.

Trigger

File Updated or Deleted (Instant)

New File Created

New Folder Created

New List Item

Updated List Item

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

offline_access

Keep Sana connected without re-login

email

Identify your Microsoft account email

openid

Secure sign-in and basic identity

Site.Manage.All

Configure SharePoint sites and settings

Sites.Read.All

Let Sana read all SharePoint content

Sites.ReadWrite.All

Read and update SharePoint files and lists

User.Read.All

Read organisation users for permissions

Group.Read.All

Read Microsoft 365 groups for access

Sites.FullControl.All

Allow Sana to manage sites

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find SharePoint in the list of available connectors

Scroll to the Available connectors section and locate SharePoint.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the SharePoint card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to SharePoint and approve the requested scopes

You&#x27;ll be redirected to SharePoint to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your SharePoint account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

File formats : Sana can only read the following file formats stored in SharePoint: doc , docx , dot , dotx , dotm , xls , xlsm , xlsx , pps , ppsx , ppt , pptx , odp , ods , odt , rtf , eml , msg , htm , html , markdown , md , epub , tif , tiff , pdf , jpeg , jpg , png , gif , webp , loop , fluid , fluidframework , whiteboard , wbtx , form , note , page , pulse , loot , dwg , dsn .

-

Search : The connector does not support full-text search inside files. It can only locate files by title or metadata, then read the file once it has been found — broad content-discovery searches are limited.

Related Articles Box Dropbox OneDrive Microsoft Excel Egnyte

---

## #3 Google Drive

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/563347-google-drive>  
**Last checked:** 2026-06-08  
**Score:** 17

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Google Drive to Sana to search, read, create, and manage files across drives and folders. Manage access, organize folders and review comments across your organization&#x27;s knowledge.

In summary, the connector has the following key characteristics:

-

Categories: File storage, Documents

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List drives

Find files

Read files

Create files

Update files

Copy files

Find folders

Create folders

Update folders

List comments

Create comments

Update comments

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Google Drive. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add comment

Copy file

Create file from template

Create file from text

Create folder

Create shared drive

Delete comment

Delete file

Delete reply

Delete shared drive

Download file

Find file

Find folder

Find forms

Find spreadsheets

Get comment

Get current user

Get file by id

Get folder id for path

Get reply

Get shared drive

Is folder ancestor

List access proposals

List comments

List files

List mime type options

List replies

List theme id options

Move file

Move file to trash

Reply to comment

Resolve access proposal

Resolve comment

Search shared drives

Update comment

Update file

Update reply

Update shared drive

# Triggers

While tools are the actions an agent takes on your behalf, triggers are the events that can start an agent automatically. When you build an agent, you can choose one of the triggers below as its starting point. For example, having the agent run every time something new happens in Google Drive.

Trigger

Changes to Files in Drive

Changes to Specific Files

Changes to Specific Files (Shared Drive)

New Access Proposal

New Files (Instant)

New Files (Polling)

New Files (Shared Drive)

New or Modified Comments (Instant)

New or Modified Comments (Polling)

New or Modified Files (Instant)

New or Modified Files (Polling)

New or Modified Folders (Instant)

New or Modified Folders (Polling)

New Presentation (Instant)

New Shared Drive

New Spreadsheet (Instant)

New Spreadsheet (Polling)

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

https://www.googleapis.com/auth/drive

Read, create and manage Drive files

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Google Drive in the list of available connectors

Scroll to the Available connectors section and locate Google Drive.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Google Drive card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Google Drive and approve the requested scopes

You&#x27;ll be redirected to Google Drive to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Google Drive account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

File formats : The connector can only read the following file formats in your Google Drive: Google Docs, Google Sheets, Google Slides, Google Drawing, PDF, JPEG, PNG, GIF, WEBP.

-

Folder metadata : The connector cannot edit folder metadata (such as name or location); it can only delete folders.

-

Comments : The connector cannot determine which specific element (text, cell, object, etc.) a comment is attached to — it can only list comments in a file.

-

Version history : The connector cannot access version history, so it cannot answer questions like "What changed recently in this doc, and who made the changes?".

Related Articles Google Calendar ClickUp Google Sheets Google Docs Google Slides

---

## #4 Microsoft Teams

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634147-microsoft-teams>  
**Last checked:** 2026-06-08  
**Score:** 17

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Microsoft Teams to Sana to send messages and search conversations across direct messages and channels. Send updates to channels and chats, search across messages and view shifts directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Communication

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Search messages

Send messages

Create channels

List channels

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Microsoft Teams. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create channel

Get chat message

Get current user

List channel messages

List channels

List chats

List messages in chat

List shifts

List teams

Search messages

Send channel message

Send chat message

# Triggers

While tools are the actions an agent takes on your behalf, triggers are the events that can start an agent automatically. When you build an agent, you can choose one of the triggers below as its starting point. For example, having the agent run every time something new happens in Microsoft Teams.

Trigger

New Channel

New Channel Message

New Chat

New Chat Message

New Team

New Team Member

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

User.Read

Read basic profile information for the signed-in user.

email

Read the user&#x27;s primary email address.

offline_access

Maintain access to Microsoft Teams data when you are not actively signed in.

openid

Sign you in and identify you using the OpenID Connect protocol.

profile

Read additional basic profile details (name, picture, locale).

Chat.Read

Read 1:1 and group chat messages you have access to.

Chat.ReadWrite

Read and send or edit chat messages you have access to.

ChatMessage.Send

Send new messages in chats on your behalf.

Channel.ReadBasic.All

Read basic information about all Teams channels (name, description, membership).

ChannelMessage.Read.All

Read all messages in all Teams channels you have permission to access.

ChannelMessage.Send

Send new messages in Teams channels on your behalf.

Team.ReadBasic.All

Read basic information about all Teams (name, description, membership).

Schedule.Read.All

Read calendar and scheduling information across Teams and Outlook for your tenant.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Microsoft Teams in the list of available connectors

Scroll to the Available connectors section and locate Microsoft Teams.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Microsoft Teams card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Microsoft Teams and approve the requested scopes

You&#x27;ll be redirected to Microsoft Teams to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Microsoft Teams account. Click Continue to complete the setup and start using the connector.

Related Articles Microsoft Planner Microsoft To Do Microsoft Excel Microsoft OneNote Google Chat

---

## #5 Outlook Email

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/563349-outlook-email>  
**Last checked:** 2026-06-08  
**Score:** 17

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Outlook Email to Sana to find, send and manage your emails. Revisit old conversations, capture action items, summarize attachments, prepare drafts and send follow-ups based on your context instead of starting from scratch.

In summary, the connector has the following key characteristics:

-

Category: Communication

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Find emails

List important mail

Draft emails

Draft replies

Send emails

Read attachments

List labels

Update labels

List folders

List contacts

Create contacts

Update contacts

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Outlook Email. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add label to email

List contact options

List folder ids options

Approve workflow

Create contact

Create draft email

Create draft reply

Download attachment

Find contacts

Find email

Find shared folder email

Get current user

Get message

List contacts

List folders

List important mail

List labels

Move email to folder

Remove label from email

Reply to email

Send email

Update contact

# Triggers

While tools are the actions an agent takes on your behalf, triggers are the events that can start an agent automatically. When you build an agent, you can choose one of the triggers below as its starting point. For example, having the agent run every time something new happens in Outlook Email.

Trigger

New Attachment Received (Instant)

New Contact Event (Instant)

New Email Event (Instant)

New Email in Shared Folder Event

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

user.read

See your basic account details

email

Identify your Microsoft email address

offline_access

Keep Sana connected between logins

openid

Secure sign-in and identity tokens

profile

Show your name and profile picture

Mail.ReadWrite

Read, organize, and edit your email

Mail.Send

Send emails on your behalf from Sana

MailboxSettings.ReadWrite

Manage time zone, rules, and signatures

IMAP.AccessAsUser.All

Sync mail via IMAP when needed

POP.AccessAsUser.All

Fetch mail via POP if configured

SMTP.Send

Send mail through your SMTP server

Calendars.ReadWrite

Read and update your calendars

Contacts.ReadWrite

Read and update your contacts

User.ReadBasic.All

See basic details of coworkers

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Outlook Email in the list of available connectors

Scroll to the Available connectors section and locate Outlook Email.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Outlook Email card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Outlook Email and approve the requested scopes

You&#x27;ll be redirected to Outlook Email to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Outlook Email account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Attachment formats : The connector can only read the following formats in attachments: pdf , jpeg , jpg , png , gif , webp , txt , html , docx . Other file types cannot currently be opened, read, or summarized.

-

Message flags and categories : The connector does not modify label/category definitions and cannot mark emails as read or unread.

-

Folders : The connector cannot create, rename, or delete folders. It can only see and work with top-level folders — it can tell you whether a top-level folder contains sub-folders, but cannot list those sub-folders or act on them.

Related Articles Outlook Calendar Gmail Microsoft Planner Trello Freshdesk

---

## #6 Servicenow

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/600476-servicenow>  
**Last checked:** 2026-06-08  
**Score:** 17

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect ServiceNow to Sana to quickly explore, search, and manage your table records. Handle incidents, manage your service catalog, and keep your ServiceNow data clean and up to date without leaving Sana.

In summary, the connector has the following key characteristics:

-

Category: Support

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List tables

Find table records

Search records

Create table records

Update table records

Delete table records

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about ServiceNow. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create table record

Delete table record

Get current user

Get record counts by field

Get table record by id

Get table records

List tables

Search records by keyword

Update table record

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find ServiceNow in the list of available connectors

Scroll to the Available connectors section and locate ServiceNow.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the ServiceNow card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your ServiceNow instance, Client ID, and Client Secret

In the Pipedream pop-up you&#x27;ll be asked for three values for your ServiceNow account:

-

Instance Name — your ServiceNow subdomain (the part before .service-now.com ).

-

Client ID and Client Secret — generated by your ServiceNow admin from a custom OAuth application registered in your ServiceNow instance (see the limitation below).

## Step 6: Complete the set up

You&#x27;ve successfully connected your ServiceNow account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Admin pre-setup required : ServiceNow&#x27;s OAuth flow requires a workspace admin to register custom OAuth applications inside your ServiceNow instance and share the resulting Client ID and Client Secret with each user who needs to connect. The OAuth callback must point at https://api.pipedream.com/connect/oauth/oa_g2oiqA/callback (Sana connects via Pipedream). Refer to ServiceNow&#x27;s own docs on OAuth Application Registry for the in-product setup steps.

-

No granular scopes : ServiceNow&#x27;s OAuth implementation does not support resource-level scopes. Access is gated by the roles assigned to the connecting user (e.g. itil , admin , read_only_admin ) and by table-level ACLs in your instance. Admins must ensure the connecting user has the right roles and that the relevant tables have GET/POST/PATCH/DELETE/PUT methods enabled for the operations Sana should perform.

# Frequently asked questions

Q: If a ServiceNow admin generates the Client ID and Secret, can they be shared with non-admin ServiceNow users — and will those users get admin access?

A: Yes, the Client ID and Secret can be shared with non-admin users — sharing them does not grant admin access. The Client ID and Secret only identify the OAuth application that lets the OAuth flow start. The actual access level is determined by each user&#x27;s own permissions in ServiceNow: when they connect, they authenticate with their own ServiceNow credentials and the connector mirrors their individual access.

Related Articles Airtable Intercom Attio Ironclad Google Slides

---

## #7 Workday

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/563343-workday>  
**Last checked:** 2026-06-08  
**Score:** 17

# Introduction

Sana connects directly to Workday through the Self-Service Agent, giving you access to a wide range of HR, Finance, and Payroll actions without leaving the chat.

# Capabilities

Capability

Description

Personal Information & Benefits

View your compensation, benefits, and personal information

Time & Attendance

Manage time off requests, view balances, and submit time entries

Performance & Development

Manage performance reviews, feedback, and goals

Team & Organization

View your org structure, team information, and coworker details

Talent & Recruitment

Create referrals, view candidate status, and find job openings

Payroll

View pay information, direct deposit, and tax forms

Click here to view the full list of capabilities offered by the Self-Service Agent.

Data access is governed by Workday&#x27;s internal permission system. This means:

-

Users can only access data they&#x27;re authorized to see in Workday

-

Permissions mirror what the user can already do in Workday directly

-

No additional scope configuration is needed in Sana

## Known limitations

-

Speed: As Sana hands the action over to Workday’s self-service agent (WSSA) to complete, the overall speed is dependent on how quickly Workday&#x27;s agent processes the request, so results may arrive more slowly than for actions handled directly in Sana or via other 3rd party connectors.

## FAQ

Q: How do I connect to Workday?

A: You don&#x27;t need to connect to Workday - it&#x27;s automatically available when you log in to Sana through SSO. No additional setup required.

Q: What permissions does Workday require in Sana?

A: Your existing Workday permissions determine what you can access in Sana. You can only see and do what you&#x27;re already authorized for in Workday.

Related Articles Frequently Asked Questions (FAQ) What is Sana Privacy and permissions Mural Navigational search

---

## #8 Jira

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/596247-jira>  
**Last checked:** 2026-06-08  
**Score:** 16

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Jira to Sana to search and manage issues. Track work, transition issues, assign issues, and stay on top of your team&#x27;s progress with context from your connected apps.

In summary, the connector has the following key characteristics:

-

Category: Project management

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List users

List spaces

Find issues

List comments

Create comments

Update comments

Manage boards

Manage sprints

List epics

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Jira. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add comment to issue

Add watcher to issue

Assign issue

Check issues against jql

Count issues using jql

Create custom field options context

Create future sprint

Create version

Delete project

Get all projects

Get board

Get cloud id

Get current user

Get issue

Get issue picker suggestions

Get issue types

Get sprint

Get task

Get transitions

Get user

Get users

List board issues

List boards

List epic issues

List epics

List issue comments

List labels options

List sprint issues

List sprints

Move issues to sprint

Search issues with jql

Search issues with jql post

Transition issue

Update comment

# Triggers

While tools are the actions an agent takes on your behalf, triggers are the events that can start an agent automatically. When you build an agent, you can choose one of the triggers below as its starting point. For example, having the agent run every time something new happens in Jira.

Trigger

New Event

New Issue Created Event (Instant)

New Issue Deleted Event (Instant)

New Issue Updated Event (Instant)

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

read:jira-work

Read Jira work data like spaces and issues

manage:jira-project

Create and configure projects, roles, and settings

read:jira-user

Read Jira user profiles and basic account details

write:jira-work

Create, edit, transition, and comment on issues

read:me

Read information about the currently authenticated user

offline_access

Refresh access tokens when the user is offline

read:issue-details:jira

Read detailed issue content, history, and comments

read:field:jira

Read field definitions, metadata, and field values

read:project:jira

Read project metadata, categories, and configurations

write:field.option:jira

Create and update options for custom select fields

read:custom-field-contextual-configuration:jira

Read context-specific custom field configs per project

read:jql:jira

Validate and inspect JQL queries and search metadata

manage:jira-webhook

Create, update, and delete Jira webhooks for events

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Jira in the list of available connectors

Scroll to the Available connectors section and locate Jira.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Jira card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Jira and approve the requested scopes

You&#x27;ll be redirected to Jira to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Jira account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Attachments : The connector cannot read or write attachments in Jira.

-

Managed Jira only : The connector only supports managed (cloud) Jira — self-hosted instances are not supported.

-

One app at a time : The connector supports a single connected Jira app, selected during set up.

-

Deletion : The connector cannot delete users, issues, or comments.

-

Custom objects and fields : Limited support for writing and updating custom objects and fields.

Related Articles Linear Todoist GitHub Jira Data Center Jira Service Desk

---

## #9 Jira Data Center

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/667642-jira-data-center>  
**Last checked:** 2026-06-08  
**Score:** 16

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect your self-hosted Jira Data Center instance to Sana to manage boards, sprints, and epics, and move issues between sprints and the backlog without leaving your chat.

In summary, the connector has the following key characteristics:

-

Category: Project management

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List boards

Update sprints

List epics

List issues

Move issues

List worklogs

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Jira Data Center. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create board

Create filter

Create future sprint

Delete sprint

Get board

Get issues from backlog

Get resolution

Get server info

Get sprint

Get updated work logs

Get worklogs by id

List board issues

List boards

List epic issues

List epics

List filter id options

List issues without epic

List project id options

List resolutions

List sprint issues

List sprints

List worklog ids actions

Move issues to backlog

Move issues to sprint

Update sprint fully

Update sprint partially

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Jira Data Center when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Jira Data Center in the list of available connectors

Scroll to the Available connectors section and locate Jira Data Center.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Jira Data Center card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Jira Data Center credentials

You&#x27;ll be asked to paste the credentials for Jira Data Center so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Jira Data Center account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Issues : This connector focuses on agile entities (boards, sprints, epics, backlog) and cannot create, transition, or comment on individual issues — use the Jira connector for that.

-

Network access : Sana must be able to reach your Jira Data Center API URL over the public internet.

Related Articles Jira Miro GitLab Confluence Data Center Jira Service Desk

---

## #10 Jira Service Desk

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/667644-jira-service-desk>  
**Last checked:** 2026-06-08  
**Score:** 16

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Jira Service Desk to Sana to reply to customer service requests directly from your chat. Draft and post replies on customer tickets with context from your other connected apps.

In summary, the connector has the following key characteristics:

-

Category: Support

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Reply to requests

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Jira Service Desk. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create comment on request

List cloud id options

# Triggers

While tools are the actions an agent takes on your behalf, triggers are the events that can start an agent automatically. When you build an agent, you can choose one of the triggers below as its starting point. For example, having the agent run every time something new happens in Jira Service Desk.

Trigger

New Request Created

Request Status Updated

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

read:servicedesk-request

Read customer service requests and their comments

write:servicedesk-request

Reply to customer service requests on your behalf

offline_access

Refresh access tokens when the user is offline

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Jira Service Desk in the list of available connectors

Scroll to the Available connectors section and locate Jira Service Desk.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Jira Service Desk card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Jira Service Desk and approve the requested scopes

You&#x27;ll be redirected to Jira Service Desk to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Jira Service Desk account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Scope : This connector currently only supports adding comments to existing customer requests. Searching, transitioning, or creating requests is not yet supported.

Related Articles Google Drive Jira Intercom Datadog Jira Data Center

---
