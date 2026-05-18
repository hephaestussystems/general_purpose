# Sana Top 10 Enterprise Connector Reference

**Generated:** 2026-05-18  
**Source:** [Sana Help Center](https://intercom-help.eu/workday-sana/en/collections/1389607-connector-guides)  
**Maintained by:** Hephaestus Systems

> All 10 connectors updated by Sana on 2026-05-12 (mass Pipedream architecture migration). Workday and Jira additionally updated 2026-05-13.

---


## #1 Workday

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/563343-connector-guide-workday>  
**Last updated:** 2026-05-13


### Introduction

Sana connects directly to Workday through the Self-Service Agent, giving you access to a wide range of HR, Finance, and Payroll actions without leaving the chat.

### Capabilities

| Capability | Description |
| --- | --- |
| Personal Information &amp; Benefits | View your compensation, benefits, and personal information |
| Time &amp; Attendance | Manage time off requests, view balances, and submit time entries |
| Performance &amp; Development | Manage performance reviews, feedback, and goals |
| Team &amp; Organization | View your org structure, team information, and coworker details |
| Talent &amp; Recruitment | Create referrals, view candidate status, and find job openings |
| Payroll | View pay information, direct deposit, and tax forms |

Data access is governed by Workday's internal permission system. This means:


### Known limitations



---


## #2 SharePoint

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/563345-connector-guide-sharepoint>  
**Last updated:** 2026-05-12

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

### Introduction

Connect SharePoint to Sana to search, read, and manage files across sites, drives, and folders. Summarize complex material, extract key points, create folders, and bring together content across your company's knowledge.
In summary, the connector has the following key characteristics:


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



---


## #3 Google Drive

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/563347-connector-guide-google-drive>  
**Last updated:** 2026-05-12

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

### Introduction

Connect Google Drive to Sana to search, read, create, and manage files across drives and folders. Manage access, organize folders and review comments across your organization's knowledge.
In summary, the connector has the following key characteristics:


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



---


## #4 Salesforce

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/563350-connector-guide-salesforce>  
**Last updated:** 2026-05-12

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

### Introduction

Connect Salesforce to Sana to find, create and update accounts, leads, contacts, and opportunities. Research, enrich and keep your customer data up-to-date with context from your connected apps to close more deals.
In summary, the connector has the following key characteristics:


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


## #5 Jira

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/596247-connector-guide-jira>  
**Last updated:** 2026-05-12

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

### Introduction

Connect Jira to Sana to search and manage issues. Track work, transition issues, assign issues, and stay on top of your team's progress with context from your connected apps.
In summary, the connector has the following key characteristics:


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



---


## #6 Confluence

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/597932-connector-guide-confluence>  
**Last updated:** 2026-05-12

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

### Introduction

Connect Confluence to Sana to search, read, create, and manage your Confluence pages and blog posts. Get instant answers, derive insights, and summarize complex material from your spaces.
In summary, the connector has the following key characteristics:


### Capabilities

This connector is able to do the following:
| Capability |
| --- |
| Find pages |
| Read pages |
| Create pages |
| Create blog posts |
| Update blog posts |
| Delete blog posts |


### Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Confluence. In practice, the agent may call one or more tools to achieve a single capability.
| Tool |
| --- |
| Create page |
| Create post |
| Delete post |
| Get current user |
| Get page by id |
| Get pages |
| Get pages in space |
| Search content |
| Update post |


### Scope and permissions

This connector uses OAuth. When you connect your account, you will need to sign into your account and grant the required permissions:
| Scope | Purpose |
| --- | --- |
| read:confluence-content.all | Read all Confluence content the user has access to |
| search:confluence | Perform search queries across Confluence content |
| read:me | Read basic profile details of the current user |
| offline_access | Refresh access tokens when the user is offline |
| read:space:confluence | Read metadata and settings for Confluence spaces |
| read:blogpost:confluence | Read Confluence blog posts |
| write:blogpost:confluence | Create and update Confluence blog posts |
| delete:blogpost:confluence | Delete Confluence blog posts |
| read:page:confluence | Read Confluence pages |
| write:page:confluence | Create and update Confluence pages |
| write:confluence-content | Create, update, and delete Confluence content generally |


### Known limitations



---


## #7 Slack

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/598448-connector-guide-slack>  
**Last updated:** 2026-05-12

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

### Introduction

Connect Slack to Sana to search conversations and send messages in Slack channels. Find important threads, send updates, manage channels, and stay on top of your team communication without leaving Sana.
In summary, the connector has the following key characteristics:


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



---


## #8 ServiceNow

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/600476-connector-guide-servicenow>  
**Last updated:** 2026-05-12

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

### Introduction

Connect ServiceNow to Sana to quickly explore, search, and manage your table records. Handle incidents, manage your service catalog, and keep your ServiceNow data clean and up to date without leaving Sana.
In summary, the connector has the following key characteristics:


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



---


## #9 HubSpot

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/627538-connector-guide-hubspot>  
**Last updated:** 2026-05-12

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

### Introduction

Connect HubSpot to Sana to manage your CRM, track your pipeline and keep your sales data up to date. Search and update contacts, companies and deals without leaving Sana.
In summary, the connector has the following key characteristics:


### Capabilities

This connector is able to do the following:
| Capability |
| --- |
| Find contacts |
| Create contacts |
| Update contacts |
| Find companies |
| Create companies |
| Update companies |
| Find deals |
| Create deals |
| Update deals |
| Find leads |
| Create leads |
| Update leads |
| Create activities |


### Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about HubSpot. In practice, the agent may call one or more tools to achieve a single capability.
| Tool |
| --- |
| Get user details |
| Search properties |
| Get properties |
| Search crm objects |
| Get crm objects |
| Create crm object |
| Update crm object |
| Create association |
| List owners |
| List pipelines and stages |


### Scope and permissions

This connector uses OAuth. When you connect your account, you will need to sign into your account and grant the required permissions:
| Scope | Purpose |
| --- | --- |
| business-intelligence | Access analytics and reporting data in HubSpot |
| crm.lists.read | View static and active lists of records |
| crm.lists.write | Create and update static and active lists |
| crm.objects.companies.read | Read company records and their properties |
| crm.objects.companies.write | Create, update, and delete company records |
| crm.objects.contacts.read | Read contact records and their properties |
| crm.objects.contacts.write | Create, update, and delete contact records |
| crm.objects.deals.read | Read deal records, stages, and amounts |
| crm.objects.deals.write | Create, update, and delete deals |
| crm.objects.quotes.read | Read quote records and details |
| crm.objects.quotes.write | Create, update, and delete quotes |
| crm.objects.owners.read | Read CRM owner records (users who own objects) |
| crm.objects.listings.read | Read custom "listing" CRM objects and their data |
| crm.objects.listings.write | Create, update, and delete "listing" CRM objects |
| crm.objects.feedback_submissions.read | Read feedback and survey submission records |
| crm.schemas.companies.read | View the schema for company objects and properties |
| crm.schemas.companies.write | Modify company schema, including custom properties |
| crm.schemas.contacts.read | View the schema for contact objects and properties |
| crm.schemas.contacts.write | Modify contact schema, including custom properties |
| crm.schemas.deals.read | View the schema for deal objects and properties |
| crm.schemas.deals.write | Modify deal schema, including custom properties |
| crm.schemas.quotes.read | View the schema for quote objects and properties |
| crm.schemas.listings.read | View the schema for listing objects and properties |
| crm.schemas.listings.write | Modify listing schema, including custom properties |
| crm.import | Import data into HubSpot CRM in bulk |
| files | Access and manage files stored in HubSpot file manager |
| forms | Access and manage HubSpot forms and submissions |
| forms-uploaded-files | Access files uploaded through HubSpot forms |
| oauth | Authenticate using OAuth and manage access tokens |
| timeline | Create and manage custom timeline events on records |
| integration-sync | Configure and manage data sync between HubSpot and external systems |
| conversations.read | Read conversations such as inbox threads and messages |
| conversations.write | Create and update conversations and messages |


### Known limitations



---


## #10 Microsoft Teams

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634147-connector-guide-microsoft-teams>  
**Last updated:** 2026-05-12

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

### Introduction

Connect Microsoft Teams to Sana to send messages and search conversations across direct messages and channels. Send updates to channels and chats, search across messages and view shifts directly from Sana.
In summary, the connector has the following key characteristics:


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
