# Sana All Connectors Reference

**Generated:** 2026-05-20  
**Source:** [Sana Help Center](https://intercom-help.eu/workday-sana/en/collections/1389607-connector-guides)  
**Maintained by:** Hephaestus Systems  
**Connectors:** 100 total

> All connectors updated by Sana on 2026-05-12 (mass Pipedream architecture migration). ⭐ = Top 10 recommendation by Hephaestus Systems.

---

## 15Five

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634196-connector-guide-15five>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: HR
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Get user profiles |
| View check-ins |
| Send High Fives |

### Tools

| Tool |
| --- |
| Create high five |
| Get checkin details |
| Get user |

---

## Airbyte

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634168-connector-guide-airbyte>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Engineering
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List workspaces |
| Create workspaces |
| Update workspaces |
| Delete workspaces |

### Tools

| Tool |
| --- |
| Create workspace |
| Delete workspace |
| List workspaces |
| Update workspace |

---

## Airtable

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/606510-connector-guide-airtable>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Project management
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List bases |
| List tables |
| Create tables |
| Search records |
| Create records |
| Delete records |

### Tools

| Tool |
| --- |
| Create comment |
| Create field |
| Create multiple records |
| Create table |
| Delete record |
| Get record |
| List bases |
| List records |
| List records in view |
| List tables |
| Update comment |
| Update field |
| Update table |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| data.records:read | Read existing records from connected bases |
| data.records:write | Create, update, and delete records |
| data.recordComments:read | View comments on records |
| data.recordComments:write | Add or edit record comments |
| schema.bases:read | Inspect base schemas to understand fields and tables |
| schema.bases:write | Modify base schema |
| webhook:manage | Create, update, and delete webhooks |
| user.email:read | Identify the signed in user for personalization |

### Known limitations

- Updating content: The connector can't update bases and/or records.
- Users: The connector can't fetch detailed user data in the workspace, only user IDs.

---

## Asana

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/627470-asana>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Project management
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Search tasks |
| Create tasks |
| Update tasks |
| Delete tasks |
| Create projects |
| Manage subtasks |
| Add comments |

### Tools

| Tool |
| --- |
| Add task to section |
| Create project |
| Create subtask |
| Create task |
| Create task comment |
| Create task from template |
| Delete task |
| Find task by id |
| Get tasks from task list |
| List task stories |
| Search projects |
| Search sections |
| Search tasks |
| Search tasks premium |
| Search user projects |
| Update task |

---

## Ashby

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/625419-connector-guide-ashby>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: HR
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List jobs |
| List applications |
| Create candidates |
| Create applications |
| Create offers |
| Schedule interviews |

### Tools

| Tool |
| --- |
| Create application |
| Create candidate |
| Create interview schedule |
| Create offer |
| List applications |
| Start offer |
| Start offer process |

### Known limitations

- Applications: The connector can only list metadata about applicants (name, email, created date, status, source, job, archive reason, etc.), not details like resume content, notes, or interview feedback.
- Jobs: The connector can only list jobs, not read details such as job descriptions.

---

## Attio

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/627174-connector-guide-attio>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Sales
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List companies |
| List deals |
| List users |
| List people |
| Create person |
| Update person |
| Create notes |

### Tools

| Tool |
| --- |
| Create note |
| Create person |
| Delete list entry |
| Get record |
| Update person |

### Known limitations

- Search: The connector's ability to search for companies, deals, people, and records is limited — it lists objects and scans the list rather than running a filtered search. Broad searches are noisy; the more specific you are (e.g. naming the record), the better the results.
- Notes: The connector can only create new notes — not search, read, or update existing ones.
- Tasks: The connector cannot manage tasks.

---

## AWS

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/636404-connector-guide-aws>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Engineering
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Query DynamoDB |
| Read S3 files |
| Invoke Lambda functions |
| Query Redshift |
| Send SQS messages |
| Send SNS messages |
| Send EventBridge events |
| Write CloudWatch logs |

### Tools

| Tool |
| --- |
| Cloudwatch logs put log event |
| Dynamodb create table |
| Dynamodb execute statement |
| Dynamodb query |
| Dynamodb scan |
| Eventbridge send event |
| Lambda create function |
| Lambda invoke function |
| Redshift create rows |
| Redshift delete rows |
| Redshift query database |
| Redshift update rows |
| S3 download file to tmp |
| S3 generate presigned url |
| Sns send message |
| Sqs send message |

### Known limitations

- S3 search: File search is limited — the connector can only list files in a bucket, not run a filtered search.
- S3 file formats: Sana can only read the following file formats stored in S3: doc, docx, dot, dotx, dotm, xls, xlsm, xlsx, pps, ppsx, ppt, pptx, odp, ods, odt, rtf, eml, msg, htm, html, markdown, md, epub, tif, tiff, pdf, jpeg, jpg, png, gif, webp, loop, fluid, fluidframework, whiteboard, wbtx, form, note, task, page, pulse, loot, dwg, dsn.

---

## Azure SQL Database

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/636294-connector-guide-azure-sql-database>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Engineering
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Query databases |

### Tools

| Tool |
| --- |
| Execute query |
| Execute raw query |

---

## BambooHR

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/629043-connector-guide-bamboohr>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: HR
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List jobs |
| List applications |
| Update application status |
| Add application comments |
| View resumes |

### Tools

| Tool |
| --- |
| Add application comment |
| Download resume |
| Get application |
| List applications |
| Update application status |

### Known limitations

- Jobs: The connector can't read job descriptions and can't filter jobs by status — it returns all jobs, including filled or cancelled ones.

---

## Bitbucket

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/624341-connector-guide-bitbucket>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Engineering
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List repositories |
| List snippets |
| Manage issues |
| Get files |
| Comment on issues |
| Comment snippets |

### Tools

| Tool |
| --- |
| Create issue |
| Create issue comment |
| Create snippet comment |
| Get file from repository |
| Get issue |
| Get snippet |
| Update issue comment |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| account | Read basic account information for the authenticated Bitbucket user (profile, username, UUID, etc.). |
| account:write | Update or modify the connected user's Bitbucket account data and settings. |
| team:write | Create and modify Bitbucket teams and team-level settings the user has permission to manage. |
| repository:write | Create, update, and delete repositories and their settings, including pushing changes and managing repo-level configuration. |
| pullrequest:write | Create, update, merge, and decline pull requests, as well as manage their comments and approvals. |
| snippet:write | Create, edit, and delete Bitbucket snippets owned by the user or teams they can write to. |
| issue:write | Create, edit, and delete issues and issue comments in repositories the user can access. |
| email | Read the primary and secondary email addresses associated with the connected Bitbucket account. |
| wiki | Create, edit, and delete wiki content for repositories the user can access. |
| webhook | Create, edit, and delete webhooks on repositories and/or teams that the user can manage. |

### Known limitations

- Repositories: The connector can list repositories, but can't read their metadata.
- Reading snippets: The connector can list snippets and add comments, but can't read the actual content of a snippet.

---

## Box

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/597927-connector-guide-box>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: File storage
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Search files |
| Search folders |
| Browse folders |
| Read files |
| View comments |
| Request signatures |

### Tools

| Tool |
| --- |
| Create sign request |
| Download file |
| Get comments |
| Get file text |
| List folder items |
| Search content |

### Known limitations

- Search: The connector can only find files and folders by name. It can't search by metadata (e.g. last modified) or by content inside files.
- Folders: The connector can find folders by name, but can't list the files inside a folder yet.
- File formats: The connector can only read the following file formats: pdf, jpeg, jpg, and png.

---

## Calendly

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/629786-connector-guide-calendly>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Productivity
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List events |
| Check availability |
| Create scheduling links |

### Tools

| Tool |
| --- |
| Create invitee no show |
| Create scheduling link |
| Get event |
| List event invitees |
| List user availability schedules |
| List webhook subscriptions |

---

## Canva

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/617323-connector-guide-canva>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Design
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List designs |
| Read designs |

### Tools

| Tool |
| --- |
| Export design |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| profile:read | Read basic information about your Canva user profile |
| asset:read | View existing assets in your Canva account (images, uploads, media) |
| asset:write | Create or update assets in your Canva account |
| brandtemplate:content:read | View the full content of brand templates (layouts and elements) |
| brandtemplate:meta:read | View metadata about brand templates (names, IDs, details) |
| design:content:read | View the full content of your designs (pages, elements, text, images) |
| design:content:write | Create new designs or change the content of existing designs |
| design:meta:read | View metadata for designs (titles, IDs, status, timestamps) |

### Known limitations

- Read-only: The connector can only access and read your design content. It cannot create or update designs in Canva.
- Search: The connector can list your available designs but does not support filtered or advanced search.

---

## ClickUp

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/617979-connector-guide-clickup>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Project management
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Get tasks |
| Create tasks |
| Update tasks |
| Delete tasks |
| Manage checklists |
| Track time |
| Manage comments |
| Manage spaces and folders |

### Tools

| Tool |
| --- |
| Create chat view comment |
| Create checklist |
| Create checklist item |
| Create folder |
| Create list |
| Create list comment |
| Create space |
| Create task |
| Create task comment |
| Create task from template |
| Create threaded comment |
| Create time entry |
| Create view comment |
| Delete checklist |
| Delete checklist item |
| Delete comment |
| Delete folder |
| Delete list |
| Delete space |
| Delete task |
| Get custom fields |
| Get folder |
| Get folder views |
| Get folders |
| Get list |
| Get list comments |
| Get list views |
| Get lists |
| Get space |
| Get space views |
| Get spaces |
| Get task |
| Get task comments |
| Get task templates |
| Get tasks |
| Get team views |
| Get view |
| Get view comments |
| Get view tasks |
| Remove task custom field |
| Start time entry |
| Stop time entry |
| Update checklist |
| Update checklist item |
| Update comment |
| Update folder |
| Update list |
| Update space |
| Update task |
| Update task custom field |

---

## Coda

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/608656-connector-guide-coda>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Documents
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List documents |
| Read pages |
| Read tables |
| Create documents |
| Delete rows |

### Tools

| Tool |
| --- |
| Copy doc |
| Create doc |
| Delete row |
| Find row |
| Get page |
| Get page content |
| Get row |
| List columns |
| List docs |
| List formulas |
| List pages |
| List tables |

### Known limitations

- Search: The connector can only list documents you have access to; it cannot run a filtered search.
- Tables-only: Within a document, the connector only reads tables. Only basic doc metadata is exposed for the doc itself — non-table content is not accessible.

---

## Confluence ⭐

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/597932-connector-guide-confluence>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Documents
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Find pages |
| Read pages |
| Create pages |
| Create blog posts |
| Update blog posts |
| Delete blog posts |

### Tools

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

- Content types: The connector can only fully read Pages. Other content types (Databases, Blogs, Whiteboards) appear in search results but only as brief metadata — Sana cannot fetch their full content.

---

## Connector guide: Shopify

**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Sales
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Search orders |
| Search products |
| Get customers |
| Create products |
| Update products |
| Update orders |
| Update inventory |
| Create collections |
| Create pages & blogs |
| Delete pages & blogs |
| Create metafields |

### Tools

| Tool |
| --- |
| Add product to custom collection |
| Bulk import |
| Create article |
| Create blog |
| Create custom collection |
| Create metafield |
| Create page |
| Create product |
| Create product variant |
| Delete article |
| Delete blog |
| Delete page |
| Get articles |
| Get assigned fulfillment orders |
| Get customer |
| Get customers |
| Get draft order |
| Get draft orders |
| Get fulfillment order |
| Get fulfillment orders |
| Get metaobjects |
| Get pages |
| Search custom collection by name |
| Search orders |
| Search product variant |
| Search products |
| Update article |
| Update inventory level |
| Update order |
| Update page |
| Update product |
| Update product variant |

---

## Databricks

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/636394-connector-guide-databricks>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Engineering
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List jobs |
| Create jobs |
| Run jobs |
| Manage SQL warehouses |
| List endpoints |
| Create endpoints |
| Query vector indexes |
| Manage vector indexes |

### Tools

| Tool |
| --- |
| Cancel all runs |
| Cancel run |
| Create endpoint |
| Create job |
| Create sql warehouse |
| Create vector search index |
| Delete endpoint |
| Delete job |
| Delete run |
| Delete sql warehouse |
| Delete vector search index |
| Delete vector search index data |
| Edit sql warehouse |
| Export run |
| Get endpoint |
| Get job |
| Get job permissions |
| Get run |
| Get run output |
| Get sql warehouse |
| Get sql warehouse config |
| Get sql warehouse permissions |
| Get vector search index |
| List endpoints |
| List jobs |
| List runs |
| List sql warehouses |
| List vector search indexes |
| Query vector search index |
| Repair run |
| Reset job |
| Run job now |
| Scan vector search index |
| Set job permissions |
| Set sql warehouse config |
| Set sql warehouse permissions |
| Start sql warehouse |
| Stop sql warehouse |
| Sync vector search index |
| Update job |
| Upsert vector search index data |

---

## Datadog

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/629166-connector-guide-datadog>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Analytics
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Find services |
| Find monitors |
| Find metrics |
| Find logs |
| Find incidents |
| Find hosts |
| Find dashboards |
| Add metric data |

### Tools

| Tool |
| --- |
| Get account info |
| Get metric data |
| Post metric data |
| Search dashboards |
| Search events |
| Search hosts |
| Search incidents |
| Search logs |
| Search metrics |
| Search monitors |
| Search services |

---

## DealCloud

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634796-connector-guide-dealcloud>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Sales
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Get records |
| Create records |
| Update records |
| Delete records |

### Tools

| Tool |
| --- |
| Delete records |
| Get records |

### Known limitations

- Search: The connector can only list records — it cannot run a filtered search to find records by specific conditions.
- Updates: The connector can read and delete records, but cannot create or update them.

---

## Docusign

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/624168-connector-guide-docusign>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Documents
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List documents |
| Read documents |

### Tools

| Tool |
| --- |
| Download documents |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| signature | Create, send, and manage envelopes and signatures on your behalf in DocuSign |
| extended | Access additional DocuSign account data and features beyond basic signing (templates, users, advanced envelope settings) |
| openid | Confirm your identity using DocuSign (single sign-on / user profile information) |

### Known limitations

- Read-only: The connector can only read documents — it cannot create or send them.
- Documents: Only documents you created in DocuSign are accessible. Documents you received from others are not.
- Search: The connector can only list your documents, not run a filtered search to find them.

---

## Dropbox

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/606520-connector-guide-dropbox>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: File storage
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Search files |
| Search folders |
| Read files |
| Create files |
| Create folders |
| Move files |

### Tools

| Tool |
| --- |
| Create a text file |
| Create folder |
| Create or append to a text file |
| Delete file folder |
| Download and export |
| Download file preview |
| Download file to tmp |
| Get shared link file |
| Get shared link metadata |
| List file folders in a folder |
| List file revisions |
| List shared links |
| Move file folder |
| Rename file folder |
| Restore a file |
| Search files folders |

### Known limitations

- File formats: Sana can only read the following file formats from your Dropbox: pdf, jpg, jpeg, png, gif.
- Search: Search runs against file titles and metadata only — there is no full-text search inside file contents. Sana can locate a file by name and then read its contents once found.

---

## Dynamics 365 Business Central

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634821-dynamics-365-business-central>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Sales
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Create customers |
| Update customers |
| List sales orders |

### Tools

| Tool |
| --- |
| Create customer |
| Get sales order |
| Update customer |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| user.Read | Read basic information about the signed-in user in Azure AD |
| email | Access the signed-in user's primary email address |
| offline_access | Refresh tokens so the connector can access Business Central when you're not signed in |
| openid | Sign you in using OpenID Connect and identify your Azure AD account |
| profile | Read additional profile details (name, tenant info) for the signed-in user |
| financials.readwrite.all | Read and write financial data in Dynamics 365 Business Central, including customers and orders |

---

## Dynamics 365 Sales

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634815-connector-guide-dynamics-365-sales>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Sales
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Find contacts |
| List accounts |
| Search accounts |
| List appointments |
| Create appointments |
| Update appointments |
| Create entities |

### Tools

| Tool |
| --- |
| Create appointment |
| Create custom entity |
| Find contact |
| Get account |
| List accounts |
| List appointment categories |
| List appointments |
| Search accounts |
| Update appointment |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| email | Read the signed-in user's primary email address from Azure AD. |
| offline_access | Allow the app to refresh access tokens so it can access Dynamics 365 Sales when you're offline. |
| openid | Sign you in using OpenID Connect and identify your Azure AD account. |
| profile | Read basic profile information (name, tenant, ID, etc.) for the signed-in user. |

---

## Egnyte

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/629041-connector-guide-egnyte>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: File storage
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Introduction

- Read-only: The connector can only read Egnyte metadata — it cannot create, update, or delete data in Egnyte.

### Capabilities

| Capability |
| --- |
| Find files |
| Find folders |
| Read files |
| Create folders |

### Tools

| Tool |
| --- |
| Create folder |
| Download file |
| List documents |
| List folders |
| Search |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| user | Read basic user and account information for the authenticated Egnyte user |
| link | Create and manage shared links to files and folders |
| webhooks | Create and manage webhooks to receive change notifications from Egnyte |
| filesystem | Read and write files and folders in the Egnyte file system |

---

## Evernote

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634458-connector-guide-evernote>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Productivity
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List notes |
| List notebooks |
| Create notes |
| Update notes |
| Create notebooks |

### Tools

| Tool |
| --- |
| Create note |
| Create notebook |
| Update note |

### Known limitations

- Reading note content: The connector can list notes and create new ones, but it cannot read the content of existing notes.

---

## Firebase

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634664-connector-guide-firebase>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Engineering
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List documents |
| Read documents |
| Create documents |
| Update documents |
| Create Realtime records |

### Tools

| Tool |
| --- |
| Create document |
| Create realtime db record |
| Get document |
| List documents |
| Replicate event firestore |
| Update document |

---

## Freshdesk

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634462-connector-guide-freshdesk>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Support
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Create tickets |
| Create messages |
| Create solution articles |
| Create contacts |
| Create companies |
| Create agents |
| Update tickets |
| Update solution articles |
| Update agents |
| List articles |
| List messages |
| List solution articles |
| List contacts |
| List tickets |
| List folders |

### Tools

| Tool |
| --- |
| Add note to ticket |
| Add ticket tags |
| Assign ticket to agent |
| Assign ticket to group |
| Close ticket |
| Create agent |
| Create company |
| Create contact |
| Create message for thread |
| Create reply |
| Create solution article |
| Create thread |
| Create ticket |
| Create ticket field |
| Delete solution article |
| Download attachment |
| Forward ticket |
| Get agent |
| Get canned response |
| Get contact |
| Get folder canned responses |
| Get solution article |
| Get ticket |
| List agents |
| List all folders |
| List all tickets |
| List category folders |
| List folder articles |
| List folder canned responses |
| List solution categories |
| List ticket conversations |
| List ticket fields |
| Remove ticket tags |
| Reply to forward |
| Search solution article |
| Set ticket priority |
| Set ticket status |
| Set ticket tags |
| Update agent |
| Update contact |
| Update solution article |
| Update ticket |
| Update ticket field |

---

## Freshservice

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634465-connector-guide-freshservice>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Support
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List tickets |
| Create tickets |
| Update tickets |
| List solution articles |
| Create solution articles |
| Update solution articles |
| Delete solution articles |

### Tools

| Tool |
| --- |
| Create solution article |
| Create ticket |
| Delete solution article |
| Get solution article |
| Get ticket |
| List solution articles |
| List solution categories |
| Update solution article |
| Update ticket |

---

## GitHub

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/624268-connector-guide-github>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Engineering
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List repositories |
| Create repositories |
| Find issues |
| Comment issues |
| Find pull requests |
| Create pull requests |
| Create branches |
| List releases |
| List commits |
| Read files |
| Create files |
| Update files |
| Manage gists |
| List workflows |
| Toggle workflows |

### Tools

| Tool |
| --- |
| Create branch |
| Create gist |
| Create issue comment |
| Create or update file contents |
| Create pull request |
| Create repository |
| Create workflow dispatch |
| Disable workflow |
| Enable workflow |
| Get commit |
| Get current user |
| Get issue |
| Get issue assignees |
| Get repository |
| Get repository content |
| Get workflow run |
| List commits |
| List organization repositories |
| List organizations |
| List releases |
| List repositories |
| List workflow runs |
| Search issues and pull requests |
| Star repo |
| Sync fork branch with upstream |
| Update gist |
| Update project v2 item status |
| Update pull request |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| repo | Read and write access to repositories |
| read:org | Read organization membership and teams |
| admin:org_hook | Manage organization webhooks |
| gist | Create and update your gists |
| project | Manage and update GitHub Projects |
| notifications | Read and mark notifications |
| read:user | Read your public and profile information |
| write:discussion | Create and edit GitHub Discussions |
| admin:repo_hook | Manage repository webhooks |

### Known limitations

- Issues: The connector cannot change the status of an issue, only edit other metadata.
- Branches: The connector cannot list or search branches.

---

## GitLab

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/624270-connector-guide-gitlab>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Engineering
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Search issues |
| Create issues |
| Update issues |
| Manage epics |
| List groups |
| List branches |
| Create branches |
| List commits |

### Tools

| Tool |
| --- |
| Create branch |
| Create epic |
| Create issue |
| Get issue |
| Get repo branch |
| List commits |
| List groups |
| List repo branches |
| Search issues |
| Update epic |
| Update issue |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| api | Full access to GitLab API (all resources this user can reach) |
| read_user | Read basic user profile and groups/memberships |
| read_repository | Read code, branches, tags, and repo metadata |
| write_repository | Push commits, create branches, tags, and MR-related changes |
| read_registry | Pull/view images and metadata from GitLab Container Registry |
| sudo | Act on behalf of other users with elevated admin powers |
| openid | Use GitLab as an OpenID Connect identity provider |
| profile | Read standard OpenID profile info (name, username, avatar) |
| email | Read verified email address(es) for the user |

### Known limitations

- Files: The connector cannot read, create, or update files.

---

## Gmail

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/563351-connector-guide-gmail>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Communication
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Find emails |
| Draft emails |
| Send emails |
| Delete emails |
| Read attachments |
| List labels |
| Create labels |
| Update labels |
| Manage signatures |
| Manage send-as aliases |

### Tools

| Tool |
| --- |
| Add label to email |
| Approve workflow |
| Archive email |
| Bulk archive emails |
| Create draft |
| Create label |
| Delete email |
| Download attachment |
| Find email |
| Get current user |
| Get send as alias |
| List labels |
| List send as aliases |
| List thread messages |
| Remove label from email |
| Send email |
| Update org signature |
| Update primary signature |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| email | Identify your Google account email address |
| profile | Show your name and profile picture |
| openid | Secure sign-in and session identity |
| gmail.labels | Read and manage Gmail labels |
| gmail.send | Send emails on your behalf from Sana |
| gmail.modify | Read, label, and archive messages |
| gmail.compose | Create draft emails from Sana |
| gmail.settings.basic | Understand your custom configurations |

### Known limitations

- Attachment formats: Sana can only read the following file formats in attachments: pdf, jpeg, jpg, png, gif, webp, txt, html, docx. Other file types cannot be opened, read, or summarized.
- Contacts: The connector does not search Google Contacts — you need to provide email addresses explicitly.
- Label deletion: The connector can create labels and add or remove them from emails, but cannot delete label definitions from Gmail.

---

## Gong

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/629834-connector-guide-gong>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Sales
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List calls |
| Read transcripts |
| Add calls |

### Tools

| Tool |
| --- |
| Add new call |
| Get extensive data |
| List calls |
| Retrieve transcripts of calls |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| api:calls:read:basic | Read basic metadata for Gong calls and meetings |
| api:calls:create | Create new call records and upload external call data |
| api:users:read | Read Gong user profiles and IDs |
| api:crm:integrations:read | View CRM integration configuration and mapping in Gong |
| api:library:read | Read items in the Gong content library (clips, playlists, etc.) |
| api:data-privacy:read | View data-privacy settings and objects (e.g. privacy requests) |
| api:meetings:user:create | Schedule or register user meetings in Gong |
| api:engagement-data:write | Write engagement events (emails, calls, meetings) into Gong |
| api:workspaces:read | Read Gong workspaces and their configuration |
| api:calls:read:transcript | Access full transcripts and conversation text for calls |
| api:calls:read:extensive | Read detailed call data, including speakers, tracks, and analytics |
| api:calls:read:media-url | Get secure URLs to stream or download call audio/video media |

---

## Google Calendar

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/563348-connector-guide-google-calendar>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Productivity
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Find events |
| Check availability |
| Create events |
| Update events |

### Tools

| Tool |
| --- |
| Add attendees to event |
| Create event |
| Delete event |
| Get calendar |
| Get current user |
| Get date time |
| Get event |
| List calendars |
| List event instances |
| List events |
| Quick add event |
| Query free busy calendars |
| Update event |
| Update event instance |
| Update following instances |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| calendar.events | Read and create calendar events |
| calendar.readonly | Read calendars and event details only |
| calendar.settings.readonly | Read calendar settings and time zone |
| email | Identify your Google account email |
| profile | Show your name and profile picture |

### Known limitations

- Contacts: The connector cannot look up your Google Contacts — participants must be specified by email address rather than by name.

---

## Google Chat

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/636270-connector-guide-google-chat>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Communication
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List spaces |
| Send messages |
| Read messages |
| List members |

### Tools

| Tool |
| --- |
| Create message |
| Get member |
| Get message |
| Get space |
| List members |
| List messages |
| List spaces |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| email | Read the signed-in user's primary email address |
| profile | Read basic profile information for the signed-in user (name, avatar, etc.) |
| chat.memberships.app | Manage the app's memberships in Google Chat spaces (add or remove the app from spaces) |
| chat.messages.reactions | View and manage reactions on messages in Google Chat spaces the app has access to |
| chat.messages.create | Create and send new messages in Google Chat spaces on behalf of the app |
| chat.messages.reactions.create | Add reactions to messages in Google Chat spaces on behalf of the app |
| chat.spaces | View and manage Google Chat spaces where the app is installed (metadata and basic settings) |

---

## Google Cloud

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/636416-connector-guide-google-cloud>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Engineering
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Run BigQuery queries |
| Insert BigQuery rows |
| List buckets |
| Search objects |
| Create buckets |
| Manage instances |
| Write logs |

### Tools

| Tool |
| --- |
| Bigquery insert rows |
| Create bucket |
| Create scheduled query |
| Get bucket |
| Get object |
| List buckets |
| Logging write log |
| Run query |
| Search objects |
| Switch instance boot status |

---

## Google Contacts

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/597891-connector-guide-google-contacts>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Productivity
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Search contacts |
| View contact details |
| Delete contacts |

### Tools

| Tool |
| --- |
| Delete contact |
| Get contact |
| List contacts |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| profile | Read basic profile info for the signed-in user (e.g. name, profile picture, language) |
| email | View the user's primary email address to identify them |
| contacts | Full read/write access to the user's Google Contacts |
| contacts.readonly | Read-only access to the user's Google Contacts |
| contacts.other.readonly | Read-only access to "Other contacts" |

### Known limitations

- Update: The connector does not support updating contacts in Google Contacts.
- Saved contacts only: The connector can only find your saved contacts — not contacts available in your organization's directory.

---

## Google Docs

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/624199-connector-guide-google-docs>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Documents
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Find documents |
| Read documents |
| Create documents |
| Update documents |

### Tools

| Tool |
| --- |
| Create document from template |
| Replace text |
| Replace image |
| Insert text |
| Insert table |
| Insert page break |
| Get tab content |
| Get document |
| Find document |
| Create document |
| Append text |
| Append image |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| https://www.googleapis.com/auth/drive | Find, read, create, and update Google Docs on your behalf |

### Known limitations

- Formatting: Inserted or updated content can sometimes inherit existing formatting from the document rather than applying a completely new style.
- Sharing: The connector cannot manage sharing permissions on documents.
- Comments: The connector does not support reading, creating, or updating comments.

---

## Google Drive ⭐

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/563347-connector-guide-google-drive>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Categories: File storage, Documents
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

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

| Scope | Purpose |
| --- | --- |
| https://www.googleapis.com/auth/drive | Read, create and manage Drive files |

### Known limitations

- File formats: The connector can only read the following file formats in your Google Drive: Google Docs, Google Sheets, Google Slides, Google Drawing, PDF, JPEG, PNG, GIF, WEBP.
- Folder metadata: The connector cannot edit folder metadata (such as name or location); it can only delete folders.
- Comments: The connector cannot determine which specific element (text, cell, object, etc.) a comment is attached to — it can only list comments in a file.
- Version history: The connector cannot access version history, so it cannot answer questions like "What changed recently in this doc, and who made the changes?".

---

## Google Sheets

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/618409-connector-guide-google-sheets>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Documents
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List spreadsheets |
| Read spreadsheets |
| Create spreadsheets |
| Add worksheets |
| Find rows |
| Add rows |
| Update rows |
| Generate formulas |

### Tools

| Tool |
| --- |
| Add rows |
| Add worksheet |
| Find rows |
| Get spreadsheet info |
| List spreadsheets |
| New spreadsheet |
| Read rows |
| Update rows |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| email | Know which Google account you use |
| profile | See your basic account info |
| https://www.googleapis.com/auth/drive | Access and update your Google Sheets in Drive |

### Known limitations

- Spreadsheet operations: The connector cannot change spreadsheet settings or delete spreadsheets — it can only read and edit cells within an existing spreadsheet.
- Comments: The connector cannot attach comments to individual cells; comments can only be added at the spreadsheet level.

---

## Google Tasks

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/597920-connector-guide-google-tasks>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Productivity
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List task lists |
| Create task lists |
| Update task lists |
| Delete task lists |
| List tasks |
| Create tasks |
| Update tasks |
| Delete tasks |

### Tools

| Tool |
| --- |
| Create task |
| Create task list |
| Delete task |
| Delete task list |
| List task lists |
| List tasks |
| Update task |
| Update task list |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| https://www.googleapis.com/auth/tasks | Access and manage your Google Tasks lists and individual items |
| email | Read your primary Google email address for user identification |
| profile | Read basic profile details like your name and avatar for display |

---

## Greenhouse

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634466-connector-guide-greenhouse>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: HR
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List jobs |
| Create candidates |
| Create prospects |
| Add attachments |

### Tools

| Tool |
| --- |
| Add attachment to candidate |
| Create candidate |
| Create prospect |

### Known limitations

- Reading jobs: The connector can list available jobs (so you can pick one when creating a candidate or prospect), but it cannot read job details such as the job description.

---

## Guru

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634724-connector-guide-guru>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Documents
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List cards |
| Create cards |

### Tools

| Tool |
| --- |
| Add tag to card |
| Create card |
| Export card to pdf |

---

## Harvest

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/624155-connector-guide-harvest>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Project management
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Track time entries |
| View projects |

### Tools

| Tool |
| --- |
| Get projects |
| Start timer |
| Stop timer |

### Known limitations

- Time entries: When creating a time entry, only starting a timer is supported — you cannot specify a duration for a past task. Existing or ongoing time entries cannot be listed; the connector only supports creating new ones.

---

## HubSpot ⭐

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/627538-connector-guide-hubspot>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Sales
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

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

- Activities: The connector can detect and count activities on a record but cannot read their content (e.g. it can tell you a note exists, but not read the note). It can create activities such as notes, but cannot update existing ones.

---

## Intercom

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/620363-connector-guide-intercom>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Support
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List contacts |
| List conversations |
| Read conversations |
| Send messages |
| Manage contacts |
| Create notes |

### Tools

| Tool |
| --- |
| Add tag to contact |
| Create note |
| Retrieve conversation |
| Send incoming message |
| Send message to contact |
| Upsert contact |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| People | View and manage Intercom users and leads |
| Companies | View and manage company records in Intercom |
| Conversations | View and update Inbox conversations |
| Teams and teammates | View teams, teammates and away status |
| Tags | View and manage people, company and conversation tags |
| People activity | View and create people activity events |
| Workspace counts | View numerical workspace usage counts |
| Data attributes | Manage customer and company attributes |
| Tickets | View and manage support tickets |

### Known limitations

- Search: The connector can only list contacts and conversations — it cannot run a filtered search, which limits search quality.
- Attachments: The connector cannot process attachments in conversations.

---

## Ironclad

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634160-connector-guide-ironclad>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Productivity
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List workflows |
| Launch workflows |
| Comment workflows |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| scim.users.readUsers | Read Ironclad user identities via SCIM (for mapping and assignments) |
| public.workflows.readWorkflows | View existing workflows and their current status |
| public.workflows.readSchemas | Read workflow schemas / templates to know available fields and configuration |
| public.workflows.createWorkflows | Start new workflows based on available templates |
| public.workflows.updateWorkflows | Update properties or state of existing workflows |
| public.records.readSchemas | Read record schemas to understand record types and fields |
| public.records.readRecords | View existing records linked to workflows or contracts |
| public.records.createRecords | Create new records in Ironclad (e.g. counterparties, contracts) |
| public.webhooks.createWebhooks | Register new webhooks to receive Ironclad event callbacks |
| public.webhooks.deleteWebhooks | Remove existing webhook registrations |

---

## Jira ⭐

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/596247-connector-guide-jira>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Project management
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

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

## Jotform

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/623920-connector-guide-jotform>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Marketing
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List forms |
| Read form responses |

### Tools

| Tool |
| --- |
| Get form submissions |
| Get monthly user usage |
| Get user submissions |

### Known limitations

- Read-only: The connector only reads forms and form submissions — it cannot create, update, or delete data in Jotform.
- Search: The connector can only list your forms; it cannot run a filtered search.

---

## Keycloak

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634660-connector-guide-keycloak>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Identity
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Create users |
| Get user details |
| Update users |
| Delete users |

### Tools

| Tool |
| --- |
| Create user |
| Delete user |
| Get user |
| Update user |

---

## Linear

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/601562-connector-guide-linear>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Project management
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List teams |
| List projects |
| Create projects |
| Search issues |
| Create issues |
| Update issues |
| Manage initiatives |
| List views |
| Comment on issues |

### Tools

| Tool |
| --- |
| Create comment |
| Create initiative |
| Create issue |
| Create project |
| Get current user |
| Get issue |
| Get teams |
| Get view issues |
| List comments |
| List initiatives |
| List projects |
| List views |
| Remove label from issue |
| Search issues |
| Update initiative |
| Update issue |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| admin | Read configs of custom workspace-level settings |
| read | Read teams, projects, and issues |
| write | Update existing issues |
| issues:create | Create new issues |

### Known limitations

- Issue status: The connector can read the current status of an issue but cannot change it.
- Projects: The connector cannot update or delete projects. Listing exposes only key fields (id, name, lead, status, progress, url). Project creation only sets team, name, and description.
- Search: Teams and projects can only be listed — no filtered search. Issue search is limited to filtering by team, project, assignee, label, and title.
- Users: The connector cannot look up users by name or email — only by ID.

---

## LinkedIn

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/629774-connector-guide-linkedin>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Communication
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Create posts |
| Search organizations |
| Delete posts |
| View profiles |

### Tools

| Tool |
| --- |
| Create comment |
| Create image post organization |
| Create image post user |
| Create like on share |
| Create text post organization |
| Create text post user |
| Delete post |
| Fetch ad account |
| Get current member profile |
| Get member organization access control |
| Get member profile |
| Get multiple member profiles |
| Get org member access |
| Get organization access control |
| Get organization administrators |
| Get profile picture fields |
| Retrieve comments on comments |
| Retrieve comments shares |
| Search organization |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| r_1st_connections_size | Read the size of your 1st-degree LinkedIn network |
| r_basicprofile | Read your basic profile (name, headline, photo, etc.) |
| r_ads | Read LinkedIn Ads accounts, campaigns, and creatives |
| rw_ads | Create and manage LinkedIn Ads campaigns and creatives |
| r_ads_reporting | Read reporting and analytics for your LinkedIn Ads |
| rw_organization_admin | Manage LinkedIn organization pages and their admin settings |
| r_organization_social | Read posts and social activity from your organization pages |
| w_organization_social | Create and manage posts on behalf of your organization pages |
| r_organization_social_feed | Read your organization's social feed and related engagement data |
| w_organization_social_feed | Publish and manage content in your organization's social feed |
| w_member_social | Create posts, comments, and reactions on your personal LinkedIn account's behalf |
| w_member_social_feed | Publish content and interact with your personal LinkedIn feed programmatically |

### Known limitations

- People search: The connector cannot search for people — it can only fetch a profile by ID.

---

## Mailchimp

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/624529-connector-guide-mailchimp>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Marketing
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Search lists |
| Search members |
| Search campaigns |
| View campaign reports |
| Create campaigns |
| Update campaigns |
| Delete campaigns |
| Send campaigns |
| Manage audience lists |
| Unsubscribe emails |

### Tools

| Tool |
| --- |
| Add note to subscriber |
| Add or update subscriber |
| Add remove member tags |
| Add segment member |
| Add subscriber to tag |
| Create campaign |
| Create list |
| Delete campaign |
| Delete list |
| Delete list member |
| Edit campaign template content |
| Get a campaign report |
| Get campaign |
| Get campaign report |
| Get list |
| Get list activities |
| Get list member activity |
| Get list member tags |
| List segment member |
| Remove segment member |
| Search campaign |
| Search lists |
| Search member |
| Send campaign |
| Unsubscribe email |
| Update campaign |
| Update list |

---

## Microsoft Entra ID

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/627164-connector-guide-microsoft-entra-id>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Identity
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List users |
| Get user profiles |
| Get managers |
| Search groups |
| List organization groups |
| Create groups |
| Update groups |
| Update group members |

### Tools

| Tool |
| --- |
| Add member to group |
| Create group |
| Delete group |
| Get manager |
| Get ms365 groups |
| Get organization groups |
| Get organization users |
| Get profile |
| Remove member from group |
| Search groups |
| Update group |
| Update user |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| User.Read | Read your basic account info and sign you in. |
| email | View the email addresses on your account. |
| offline_access | Stay connected and refresh access when you're offline. |
| openid | Verify your identity when signing in with Entra ID. |
| profile | View your basic profile details (name, picture, etc.). |
| Directory.ReadWrite.All | Read and update directory data across the tenant (admin consent). |
| Group.ReadWrite.All | Read and manage Microsoft 365 groups in the directory (admin consent). |
| User.ReadWrite | Read and update user profile information. |

---

## Microsoft Excel

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/624201-connector-guide-microsoft-excel>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Documents
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List spreadsheets |
| Read spreadsheets |
| Update cells |
| Generate formulas |

### Tools

| Tool |
| --- |
| Add row |
| Find row |
| Get columns |
| Get spreadsheet |
| Get table rows |
| Update cell |
| Update worksheet tablerow |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| User.Read | Sign in the user and read their basic profile information (name, ID, tenant, etc.). |
| email | View the user's primary email address. |
| offline_access | Maintain access to data you've been granted by using refresh tokens, even when the user is not actively signed in. |
| openid | Sign in the user with Microsoft identity (OpenID Connect) and receive a unique user identifier. |
| profile | Read basic profile information such as name, preferred username, and avatar. |
| Files.ReadWrite | Read, create, update, and delete files the signed-in user can access in OneDrive and SharePoint. |
| Files.Read.All | Read all files the signed-in user can access across OneDrive and SharePoint, including files the user didn't create. |
| CrossTenantInformation.ReadBasic.All | Read basic information about cross-tenant relationships and external tenants for the organization. |

### Known limitations

- Search: The connector can only list spreadsheets — it cannot run a filtered search.
- Creating workbooks: The connector can read and edit Excel workbooks you already have access to, but it cannot create a brand-new workbook.
- Formatting: The connector cannot change cell formatting.

---

## Microsoft OneDrive

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/606527-connector-guide-microsoft-onedrive>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: File storage
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Search files |
| Browse folders |
| Read files |
| Create folders |
| Create sharing links |
| Read Excel tables |
| List drives |

### Tools

| Tool |
| --- |
| Create folder |
| Create link |
| Download file |
| Find file by name |
| Get excel table |
| Get file by id |
| List files in folder |
| List my drives |
| Search files |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| User.Read | Identify your account |
| email | Identifies your OneDrive user |
| offline_access | Keeps sync and automations running |
| openid | Confirms your identity during sign-in |
| profile | Get information about your user in OneDrive |
| Files.Read | Allows browsing and previewing your stored files |
| Files.Read.All | Includes shared and team files in file search and lists |
| Files.ReadWrite | Enables creating, editing, and organizing your files |

### Known limitations

- File formats: The connector can only read the following file formats in your OneDrive: pdf, jpg, jpeg, png, gif. More formats coming soon.
- Search: The connector does not support full-text search inside files. It can only locate files by their title or metadata, then read the file once it has been found — so search is limited for content-discovery use cases.

---

## Microsoft OneNote

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/627287-connector-guide-microsoft-onenote>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Documents
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Search notebooks |
| Create notebooks |
| Create sections |
| Search pages |
| Create pages |

### Tools

| Tool |
| --- |
| Create notebook |
| Create page |
| Create section |
| Get page |
| Search notebooks |
| Search pages |
| Search sections |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| User.Read | Read your basic Microsoft account profile (name, tenant, ID) to identify you and connect to the correct OneNote account |
| Email | Read your primary email address to associate the OneNote connection with your user in Sana |
| Offline_access | Maintain the connection and refresh tokens so Sana can keep working with OneNote without you re-authorizing every time |
| Openid | Use OpenID Connect for secure sign-in and identity verification with your Microsoft account |
| Profile | Read basic profile details (e.g. display name, avatar) to personalize the integration |
| Notes.Create | Create new OneNote pages and other note objects in your notebooks |
| Notes.ReadWrite.All | Read and edit all OneNote content you have access to (notebooks, sections, pages) so Sana can search, update, and create notes |

### Known limitations

- Reading page content: The connector can search OneNote pages and fetch their metadata, but it cannot read the page contents.

---

## Microsoft Planner

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/617274-connector-guide-microsoft-planner>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Productivity
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List tasks |
| Create tasks |
| Update tasks |
| Create plans |
| Create buckets |

### Tools

| Tool |
| --- |
| Create bucket |
| Create plan |
| Create task |
| List user tasks |
| Update task |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| email | Read your primary email address to identify you and use it in notifications, logs, etc. |
| offline_access | Keep a refresh token so the connector can continue to call Microsoft 365 on your behalf even when you're not actively logged in. |
| openid | Use Microsoft identity as the authentication provider (basic sign-in). |
| profile | Read basic profile info (name, avatar, tenant, etc.) to associate Microsoft 365 actions with your user. |
| Group.ReadWrite.All | Read and modify all Microsoft 365 Groups, including creating/updating Planner plans and buckets that are attached to groups. |
| Files.ReadWrite | Read, create, update, and delete files you have access to (e.g., attachments linked from Planner tasks). |
| Files.Read.All | Read all files you have permission to see across SharePoint/OneDrive, even if you didn't create them (needed to fetch attachments or related documents). |
| MailboxSettings.Read | Read your mailbox settings (time zone, language, etc.) so scheduled/notification times and formats match your Outlook configuration. |
| Tasks.ReadWrite | Read, create, update, and delete your tasks across Microsoft To Do / Planner, which is the core functionality of the Planner connector. |
| User.Read | Allow the signed-in user to read their own account info and verify identity (standard "sign in and read user profile" permission). |
| User.Read.All | Read basic profile information for other users in the organization so the connector can look up assignees, owners, and collaborators for Planner tasks and plans. |

### Known limitations

- Tasks: The connector can only list tasks assigned to the signed-in user, not tasks assigned to someone else or tasks that are unassigned.

---

## Microsoft Power BI

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/627504-connector-guide-microsoft-power-bi>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Analytics
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List workspaces |
| List reports |
| List datasets |
| Run DAX queries |
| Export reports |
| Refresh datasets |
| Push data to datasets |

### Tools

| Tool |
| --- |
| Add rows dataset table |
| Add rows to push dataset |
| Cancel refresh |
| Create dataset |
| Execute dax query |
| Export report |
| Get dataset refresh |
| Get refresh history |
| Get reports |
| Get reports by id |
| List dashboards |
| List datasets |
| List reports |
| List workspaces |
| Refresh dataset |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| offline_access | Keep the Power BI connection active and refresh tokens without repeated sign-in. |
| App.Read.All | Read all Power BI apps the user can access. |
| Dashboard.Read.All | Read all dashboards and their tiles. |
| Workspace.Read.All | List and read all accessible workspaces and their contents. |
| Dataset.ReadWrite.All | Read and modify datasets, including triggering refreshes. |
| Report.Read.All | Read reports and related metadata. |
| Report.ReadWrite.All | Create, copy, and update reports. |

### Known limitations

- Reading reports: The connector can list reports and read metadata about them, but cannot read the actual data inside a report.

---

## Microsoft Teams ⭐

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634147-connector-guide-microsoft-teams>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Communication
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Search messages |
| Send messages |
| Create channels |
| List channels |

### Tools

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

## Microsoft To Do

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/618801-connector-guide-microsoft-to-do>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Productivity
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List task lists |
| Create task lists |
| List tasks |
| Create tasks |
| Update tasks |

### Tools

| Tool |
| --- |
| Create list |
| Create task |
| List task lists |
| List tasks |
| Update task |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| Tasks.ReadWrite | Read and modify your Microsoft To Do tasks |
| User.Read | Read basic information about your account |
| email | Access your primary email address |
| offline_access | Refresh access when you're not signed in |
| openid | Sign you in using your Microsoft identity |
| profile | Read basic profile details like name and photo |

### Known limitations

- Status: The connector cannot mark or unmark tasks as complete.
- Deletion: The connector cannot delete task lists or tasks.

---

## Miro

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/602661-connector-guide-miro>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Design
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List boards |
| Read board items |
| Create boards |
| Create sticky notes |
| Create cards |
| Update boards |
| Update items |
| Delete boards |
| Delete items |

### Tools

| Tool |
| --- |
| Create board |
| Create card item |
| Create shape |
| Create sticky note |
| Delete board |
| Delete item |
| Get board |
| Get items |
| Get specific item |
| List boards |
| Update board |
| Update card item |
| Update shape |
| Update sticky note |

### Known limitations

- Board search: The connector can list and open boards, but advanced search and filtering (by owner, date, tags, etc.) is not supported. To find a specific board, list your boards first and let the agent narrow it down from there.

---

## Monday

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/627509-connector-guide-monday>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Project management
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Find boards |
| Read board items |
| Create boards |
| Post updates |

### Tools

| Tool |
| --- |
| Create board |
| Create group |
| Create update |
| Get board items page |
| Get column values |
| Update item name |

---

## Mural

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/636282-connector-guide-mural>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Design
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Create murals |
| Add sticky notes |

### Tools

| Tool |
| --- |
| Create mural |
| Create sticky |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| workspaces:read | Read information about Mural workspaces the user has access to |
| users:read | Read basic profile details for Mural users in the account |
| murals:write | Create and modify murals and their content (stickies, shapes, etc.) |
| murals:read | View murals, including their structure and content |
| rooms:read | Read rooms and their metadata to locate murals and workspaces |
| identity:read | Read the authenticated user's identity and permissions in Mural |
| templates:read | View available mural templates and their details |

---

## Notion

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/597924-connector-guide-notion>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Documents
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Search pages |
| Read pages |
| Update pages |
| Search databases |
| Read databases |
| Create databases |

### Tools

| Tool |
| --- |
| Create comment |
| Create database |
| Delete block |
| Duplicate page |
| Get current user |
| List all users |
| Query database |
| Retrieve block |
| Retrieve database content |
| Retrieve database schema |
| Retrieve page |
| Retrieve page property item |
| Retrieve user |
| Search |
| Update block |

### Known limitations

- Teamspaces: You can select pages from multiple teamspaces during set up, but once connected, the agent has no awareness of which teamspaces you've connected.
- Search: The connector searches by page title only, not by content inside pages.

---

## Okta

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/624158-connector-guide-okta>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Identity
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List users |
| Create users |
| Update users |

### Tools

| Tool |
| --- |
| Create user |
| Get user |
| Update user |

### Known limitations

- Admin-only: The connector is only intended for Okta admins.
- Users-only: The connector can only manage users — no other Okta objects (groups, applications, etc.) are exposed.
- Search: The connector can only list users, not run a filtered search on metadata.
- Field restrictions: When updating a user, only first name, last name, email, login, and mobile phone can be changed. When creating a user, only first name, last name, username, email, activated, and mobile can be set.

---

## OneLogin

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/629214-connector-guide-onelogin>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Identity
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List users |
| Create users |
| Update users |
| Revoke sessions |

### Tools

| Tool |
| --- |
| Create user |
| Revoke user sessions |
| Update user |

---

## Opsgenie

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634603-connector-guide-opsgenie>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Engineering
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Create alerts |
| Check alert status |
| Add notes to alerts |
| Delete alerts |

### Tools

| Tool |
| --- |
| Add note alert |
| Create alert |
| Delete alert |
| Get alert status |

### Known limitations

- Search: The connector can only fetch alert statuses when you already know the alert's ID. Searching alerts by other attributes is not supported.

---

## Outlook Calendar ⭐

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/563344-connector-guide-outlook-calendar>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Productivity
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Find events |
| Check availability |
| Find meeting times |
| Create events |
| Update events |

### Tools

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

## Outlook Email ⭐

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/563349-connector-guide-outlook-email>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Communication
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

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

## PagerDuty

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/624203-connector-guide-pagerduty>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Engineering
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Trigger incidents |
| Acknowledge incidents |
| Resolve incidents |
| Find on-call users |

### Tools

| Tool |
| --- |
| Acknowledge incident |
| Find oncall user |
| Resolve incident |
| Trigger incident |

### Known limitations

- Incident details: The connector can list incidents, but it cannot read detailed information about them.
- Active incidents only: The connector can only list active incidents — past or resolved incidents are not retrievable.

---

## Pipedrive

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/617091-connector-guide-pipedrive>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Sales
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List deals |
| Create deals |
| Update deals |
| Search leads |
| Create leads |
| Update leads |
| Search contacts |
| Create contacts |
| Update contacts |
| Search notes |
| Create notes |
| Create activities |
| Create organizations |

### Tools

| Tool |
| --- |
| Add activity |
| Add deal |
| Add lead |
| Add note |
| Add organization |
| Add person |
| Get all leads |
| Get deal |
| Get lead by id |
| Get person details |
| List deals |
| Merge deals |
| Merge persons |
| Remove duplicate notes |
| Search leads |
| Search notes |
| Search persons |
| Update deal |
| Update lead |
| Update person |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| Access to basic information | Read settings of the authorized user and currencies in an account. This is the default permission, always enabled for all apps. |
| Deals: Full access | Create, read, update and delete deals, their participants, followers, files, notes, and filters. Read access to deal fields, pipelines, stages, and statistics. |
| Mail: Full access | Read, update, and delete mail threads. Also grants read access to mail messages. |
| Activities: Full access | Create, read, update, and delete activities and all related files and filters. Includes read access to activity fields and types. |
| Contacts: Full access | Create, read, update, and delete persons and organizations and their followers, along with related notes, files, and filters. |
| Products: Full access | Create, read, update, and delete products and their fields; add products to deals. |
| Read users data | Read data about users (people with access to the Pipedrive account), their permissions, roles, and followers. |
| See recent account activity | Read all recent changes in the account, including activities, deals, files, notes, persons, organizations, pipelines, stages, products, and users. |
| Search for all data | Search across the account for deals, persons, organizations, files, and products. |
| Leads: Full access | Create, read, update, and delete leads and lead labels. |
| Webhooks: Full access | Create, read, and delete webhooks. |

### Known limitations

- Organizations: Searching, reading, and creating organizations are not supported.
- Deletion: Deleting records is not supported.
- Notes: Notes can be searched and created, but not updated or deleted.

---

## Postman

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/629172-connector-guide-postman>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Engineering
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Create environments |
| Run monitors |

### Tools

| Tool |
| --- |
| Create environment |
| Run monitor |

---

## Procore

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634716-connector-guide-procore>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Project management
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Create RFIs |
| Create submittals |
| Log incidents |
| Track timesheets |
| Log manpower |

### Tools

| Tool |
| --- |
| Create incident |
| Create manpower log |
| Create rfi |
| Create submittal |
| Create timesheet |

---

## RocketReach

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/608654-connector-guide-rocketreach>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Sales
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Look up people |
| Look up companies |

### Tools

| Tool |
| --- |
| Lookup profile |
| Lookup company |

---

## Salesforce ⭐

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/563350-connector-guide-salesforce>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Sales
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Introduction

- Production — your live Salesforce environment, where your real data lives. This is the right choice for almost all users.
- Sandbox — a non-production environment, useful for testing the connector without touching production data.

### Capabilities

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

---

## Sentry

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/624658-connector-guide-sentry>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Engineering
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List project issues |
| List project events |
| List issue events |
| Update issues |

### Tools

| Tool |
| --- |
| List issue events |
| List project events |
| List project issues |
| Update issue |

---

## ServiceNow ⭐

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/600476-connector-guide-servicenow>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Support
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Introduction

- Instance Name — your ServiceNow subdomain (the part before .service-now.com).
- Client ID and Client Secret — generated by your ServiceNow admin from a custom OAuth application registered in your ServiceNow instance (see the limitation below).

### Capabilities

| Capability |
| --- |
| List tables |
| Find table records |
| Search records |
| Create table records |
| Update table records |
| Delete table records |

### Tools

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

### Known limitations

- Admin pre-setup required: ServiceNow's OAuth flow requires a workspace admin to register custom OAuth applications inside your ServiceNow instance and share the resulting Client ID and Client Secret with each user who needs to connect. The OAuth callback must point at https://api.pipedream.com/connect/oauth/oa_g2oiqA/callback (Sana connects via Pipedream). Refer to ServiceNow's own docs on OAuth Application Registry for the in-product setup steps.
- No granular scopes: ServiceNow's OAuth implementation does not support resource-level scopes. Access is gated by the roles assigned to the connecting user (e.g. itil, admin, read_only_admin) and by table-level ACLs in your instance. Admins must ensure the connecting user has the right roles and that the relevant tables have GET/POST/PATCH/DELETE/PUT methods enabled for the operations Sana should perform.

###

---

## Sharepoint

**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Categories: File storage, Documents
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List sites |
| Find files |
| Find folders |
| Read files |
| Create folders |
| Share files |

### Tools

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

## Shortcut

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/605748-connector-guide-shortcut>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Project management
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Search stories |
| Read stories |
| Create stories |

### Tools

| Tool |
| --- |
| Create story |
| Search stories |

### Known limitations

- Stories only: The connector can only search and read Shortcut stories — not epics, users, roadmaps, or other entity types.

---

## Slab

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634662-connector-guide-slab>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Documents
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Search posts |
| Get post details |

### Tools

| Tool |
| --- |
| Get posts |
| List posts |
| Search posts |

---

## Slack ⭐

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/598448-connector-guide-slack>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Communication
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

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

## Snowflake

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/636299-connector-guide-snowflake>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Engineering
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Run SQL queries |
| Insert rows |

### Tools

| Tool |
| --- |
| Execute sql query |
| Insert multiple rows |

---

## Strava

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/610563-connector-guide-strava>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Lifestyle
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| View activities |
| Activity details |
| Your training stats |
| Create activities |
| Update activities |

### Tools

| Tool |
| --- |
| Create activity |
| Get activity by id |
| Get activity list |
| Get stats |
| Update activity |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| read | View data about your public profile (required) |
| activity:read | View data about your activities |
| activity:read_all | View data about your private activities |
| activity:write | Upload or edit activities on your behalf |

---

## Stripe

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/629387-connector-guide-stripe>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Finance
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List refunds |
| Create refunds |
| Update refunds |
| List payouts |
| Create payouts |
| Update payouts |
| List payment intents |
| Create payment intents |
| Update payment intents |
| List balance history |
| Find customers |
| Create customers |
| Update customers |
| List invoices |
| Create invoices |
| Update invoices |
| Find subscriptions |
| Create subscription |
| Cancel subscription |

### Tools

| Tool |
| --- |
| Cancel or reverse payout |
| Cancel payment intent |
| Cancel subscription |
| Capture payment intent |
| Confirm payment intent |
| Create billing meter |
| Create customer |
| Create invoice |
| Create invoice item |
| Create payout |
| Create payment intent |
| Create price |
| Create product |
| Create refund |
| Create subscription |
| Create usage record |
| Delete customer |
| Delete invoice item |
| Delete or void invoice |
| Finalize invoice |
| List balance history |
| List customers |
| List invoices |
| List payment intents |
| List payouts |
| List refunds |
| Retrieve balance |
| Retrieve checkout session |
| Retrieve checkout session line items |
| Retrieve customer |
| Retrieve invoice |
| Retrieve invoice item |
| Retrieve payout |
| Retrieve payment intent |
| Retrieve price |
| Retrieve product |
| Retrieve refund |
| Search customers |
| Search subscriptions |
| Send invoice |
| Update customer |
| Update invoice |
| Update invoice item |
| Update payout |
| Update payment intent |
| Update refund |
| Void invoice |
| Write off invoice |

---

## Supabase

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634667-connector-guide-supabase>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Engineering
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Find rows |
| Insert rows |
| Update rows |
| Delete rows |
| Call procedures |

### Tools

| Tool |
| --- |
| Count rows |
| Delete row |
| Insert row |
| Remote procedure call |
| Select row |
| Update row |
| Upsert row |

---

## Swagger

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634728-connector-guide-swagger>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Engineering
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Clone API versions |
| Delete API versions |

### Tools

| Tool |
| --- |
| Clone api version |
| Delete api version |

---

## Tableau

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/634605-connector-guide-tableau>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Analytics
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Find projects |
| Create projects |
| List workbooks |
| Read workbooks |

### Tools

| Tool |
| --- |
| Create project |
| Download pdf |
| Query projects |

---

## Todoist

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/606516-connector-guide-todoist>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Productivity
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List projects |
| Create projects |
| Update projects |
| Search tasks |
| Create tasks |
| Update tasks |
| Complete tasks |
| Import tasks |
| List comments |
| Add comments |
| Update comments |

### Tools

| Tool |
| --- |
| Create filter |
| Create label |
| Create project |
| Create project comment |
| Create section |
| Create task |
| Create task comment |
| Delete comment |
| Delete filter |
| Delete label |
| Delete project |
| Delete section |
| Delete task |
| Export tasks |
| Find project |
| Find task |
| Find user |
| Get label |
| Get project |
| Get project comment |
| Get section |
| Get task |
| Get task comment |
| Import tasks |
| Invite user to project |
| List filters |
| List labels |
| List project comments |
| List projects |
| List sections |
| List task comments |
| List uncompleted tasks |
| Mark task completed |
| Move task to section |
| Search tasks |
| Uncomplete task |
| Update comment |
| Update filter |
| Update label |
| Update project |
| Update section |
| Update task |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| task:add | Allow creating new tasks within your projects |
| data:read_write | Read and modify task data |
| data:delete | Permanently delete tasks, comments, or other stored Todoist data |
| project:delete | Remove entire projects and all associated tasks from your account |

### Known limitations

- Completed tasks: The connector can only retrieve active, incomplete tasks.
- Search: Search is basic — for best results, search within a specific project rather than across all projects.

---

## Trello

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/617468-connector-guide-trello>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Project management
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Search boards |
| Create boards |
| Search lists |
| Create lists |
| Update lists |
| Search cards |
| Create cards |
| Update cards |
| Add comments |
| List labels |
| Create labels |
| Manage checklists |
| Search members |

### Tools

| Tool |
| --- |
| Add attachment to card |
| Add checklist |
| Add comment |
| Add existing label to card |
| Add member to card |
| Archive card |
| Complete checklist item |
| Create board |
| Create card |
| Create checklist item |
| Create label |
| Create list |
| Delete checklist |
| Find labels |
| Find list |
| Get board |
| Get card |
| Get cards in list |
| Get cards on board |
| Get list |
| Get member |
| List boards |
| Move card to list |
| Remove label from card |
| Rename list |
| Search boards |
| Search cards |
| Search members |
| Update card |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| read | Read your data in Trello |
| write | Write data to your Trello |

### Known limitations

- Boards: The connector can create and read boards but cannot update them.
- Labels: Label definitions can be created, but not updated or deleted. Labels can be removed from cards.
- Checklists: Checklists are not supported.
- Comments: Comments can only be added — existing comments cannot be edited or deleted.

---

## Twilio

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/629870-connector-guide-twilio>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Communication
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List messages |
| Send messages |
| Delete messages |
| List calls |
| Delete calls |
| Look up phone numbers |
| Read recordings |
| List transcripts |
| SMS verification |

### Tools

| Tool |
| --- |
| Check verification token |
| Create verification service |
| Delete call |
| Delete message |
| Download recording media |
| Get call |
| Get message |
| Get transcripts |
| List calls |
| List message media |
| List messages |
| List transcripts |
| Phone number lookup |
| Send message |
| Send sms verification |

---

## Typeform

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/608079-connector-guide-typeform>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Marketing
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List forms |
| Create forms |
| Update forms |
| Duplicate forms |
| Delete forms |
| View form details |
| List responses |
| Look up responses |
| Manage images |

### Tools

| Tool |
| --- |
| Create form |
| Create image |
| Delete form |
| Delete image |
| Duplicate form |
| Get form |
| List forms |
| List images |
| List responses |
| Lookup responses |
| Update dropdown multiple choice ranking |
| Update form title |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| offline | Allow Sana to stay connected to Typeform when the user is offline |
| accounts:read | See account details to tailor actions per workspace |
| forms:read | List and inspect forms to understand their fields |
| forms:write | Create or update forms based on user prompts |
| images:read | Fetch images stored in Typeform for richer answers |
| images:write | Upload images used in questions or responses |
| themes:read | View themes so generated forms match the existing look |
| themes:write | Apply or create themes for new AI-made forms |
| responses:read | Analyze form submissions to answer user questions |
| responses:write | Submit responses when filling forms for users |
| webhooks:read | Inspect existing webhooks to align automation flow |
| webhooks:write | Create or edit webhooks for real-time syncing |
| workspaces:read | Discover workspaces to correctly place new assets |
| workspaces:write | Organize forms and assets across workspaces |

---

## Visualping

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/629053-connector-guide-visualping>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Productivity
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Find monitor jobs |
| Update monitor jobs |
| Delete monitor jobs |

### Tools

| Tool |
| --- |
| Delete job |
| Find jobs |
| Get job |
| Update job |

---

## Webex

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/629059-connector-guide-webex>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Communication
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List rooms |
| List messages |
| Send messages |
| Create rooms |

### Tools

| Tool |
| --- |
| Create message |
| Create room |
| List messages |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| spark:all | Full access to your Webex account resources |
| spark-admin:people_read | Read organisation users and their basic details |
| spark-admin:people_write | Update organisation user details and settings |
| spark:devices_read | Read information about Webex devices in your organisation |
| spark:devices_write | Manage and update Webex device settings |

### Known limitations

- Sender attribution: Messages sent through the connector appear as "Pipedream" rather than the signed-in user. The signed-in user is referenced in the message metadata, but it won't look like a normal user sent it.

---

## WordPress

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/629049-connector-guide-wordpress>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Documents
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Create posts |
| Delete posts |

### Tools

| Tool |
| --- |
| Create post |
| Delete post |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| global | Access WordPress.com sites and content your account can manage |

### Known limitations

- Posts: The connector can create and delete posts, but it cannot list, read, or update existing posts.

---

## Workday ⭐

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/563343-connector-guide-workday>
**Last updated:** 2026-05-18

### Capabilities

| Capability | Description |
| --- | --- |
| Personal Information & Benefits | View your compensation, benefits, and personal information |
| Time & Attendance | Manage time off requests, view balances, and submit time entries |
| Performance & Development | Manage performance reviews, feedback, and goals |
| Team & Organization | View your org structure, team information, and coworker details |
| Talent & Recruitment | Create referrals, view candidate status, and find job openings |
| Payroll | View pay information, direct deposit, and tax forms |
> Data access is governed by Workday's internal permission system. This means:- Users can only access data they're authorized to see in Workday
- Permissions mirror what the user can already do in Workday directly
- No additional scope configuration is needed in Sana

### Known limitations

- Human-in-the-loop: For the Workday connector, Sana does not directly handle read or write actions. When a user wants to update something, Sana hands the request over to Workday’s self-service agent (WSSA), which completes the change on its own. As a result, there is no approval or “human-in-the-loop” step shown in the Sana UI for these actions.
- Speed: As Sana hands the action over to Workday’s self-service agent (WSSA) to complete, the overall speed is dependent on how quickly Workday's agent processes the request, so results may arrive more slowly than for actions handled directly in Sana or via other 3rd party connectors.

###

---

## Zendesk

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/608599-connector-guide-zendesk>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Support
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Search tickets |
| Create tickets |
| Update tickets |
| Delete tickets |
| Manage ticket tags |
| Browse help center articles |
| Search community posts |
| View macros |
| Look up users |

### Tools

| Tool |
| --- |
| Add ticket tags |
| Create ticket |
| Delete ticket |
| Get article |
| Get macro |
| Get ticket info |
| Get user info |
| List active macros |
| List articles |
| List locales |
| List macros |
| List ticket comments |
| List tickets |
| Remove ticket tags |
| Search articles |
| Search community posts |
| Search help center |
| Search macros |
| Search tickets |
| Set custom ticket fields |
| Set ticket tags |
| Update ticket |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| triggers:write | Create and update Zendesk triggers |
| webhooks:write | Create and manage Zendesk webhooks |
| read | Read Zendesk data |
| tickets:write | Create and update support tickets |
| tickets:read | Read existing support tickets |
| users:write | Create and update Zendesk users |
| organizations:read | Read organization records |
| organizations:write | Create and update organization records |

### Known limitations

- Users: The connector can't fetch detailed user data in your Zendesk workspace, only user IDs.
- Article search: The connector can only list help-center articles; it cannot run a filtered search.

---

## Zoho CRM

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/636288-connector-guide-zoho-crm>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Sales
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Search records |
| Convert leads |
| Read attachments |

### Tools

| Tool |
| --- |
| Convert lead |
| Download attachment |
| Get object |
| List fields |
| List modules |
| List objects |
| Search objects |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| ZohoCRM.settings.all | Read and manage all CRM configuration and settings |
| ZohoCRM.users.all | Read and manage CRM users and their details |
| ZohoCRM.org.all | Access organisation-level information for the Zoho CRM account |
| ZohoCRM.modules.all | Read and write data in all CRM modules (Leads, Contacts, Deals, etc.) |
| ZohoCRM.bulk.all | Run bulk read/write operations on CRM records |
| ZohoCRM.notifications.read | Read existing CRM notifications and webhook subscriptions |
| ZohoCRM.notifications.create | Create new CRM notification / webhook subscriptions |
| ZohoCRM.notifications.update | Update existing CRM notification / webhook subscriptions |
| ZohoCRM.notifications.delete | Delete CRM notification / webhook subscriptions |
| ZohoCRM.coql.READ | Run COQL queries to read CRM data using the Zoho query language |
| ZohoCRM.functions.execute.CREATE | Execute custom Zoho CRM serverless functions that create or modify data |
| ZohoCRM.functions.execute.READ | Execute custom Zoho CRM serverless functions that read data |
| ZohoCRM.templates.email.READ | Read and list email templates stored in Zoho CRM |
| ZohoCRM.templates.inventory.READ | Read and list inventory templates (quotes, invoices, etc.) in Zoho CRM |
| ZohoCRM.signals.ALL | Access and manage all Zoho CRM Signals (real-time engagement events and notifications) |

---

## Zoom

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/602718-connector-guide-zoom>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Communication
- Connector type: Real-time
- Auth type: OAuth
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| Find meetings |
| Create meetings |
| Update meetings |
| Read transcripts |
| Summarize meetings |
| List recordings |
| Manage webinars |
| Send chat messages |
| Manage users |

### Tools

| Tool |
| --- |
| Add meeting registrant |
| Add webinar registrant |
| Create meeting |
| Create user |
| Delete meeting |
| Delete user |
| Get current user |
| Get meeting details |
| Get meeting recordings |
| Get meeting summary |
| Get meeting transcript |
| Get webinar details |
| List all recordings |
| List call recordings |
| List channels |
| List meetings |
| List past meeting participants |
| List past webinar qa |
| List user call logs |
| List webinar participants report |
| Send chat message |
| Update meeting |
| Update webinar |
| View user |

### Scope and permissions

| Scope | Purpose |
| --- | --- |
| chat_channel:read | Read Zoom chat channels to sync spaces with Sana |
| chat_message:read | Read chat messages to power search and insights in Sana |
| chat_message:write | Post messages into Zoom chat from Sana workflows or actions |
| meeting:read | Read meeting details and participants for context in Sana |
| meeting:write | Schedule and update Zoom meetings initiated from Sana |
| phone:read | Read call logs to analyze phone interactions inside Sana |
| recording:read | Access cloud recordings to index and surface in Sana |
| user:read | Read user profiles to map Zoom users to Sana accounts |
| user:write | Update user settings or mappings needed by the Sana integration |
| webinar:read | Read webinar details and attendance for insights in Sana |
| webinar:write | Create or update webinars from Sana for scheduling and management |
| zoom_events_basic:read | Read Zoom Events data to show sessions and registrations in Sana |

### Known limitations

- Search: The connector can only list meetings; it cannot run a filtered search across all meeting content. To search inside a meeting, locate the meeting first, then search within it.
- Recurring meetings: The connector cannot find past meetings within a recurring series.
- Scheduled meetings only: Transcripts are only generated for meetings scheduled in advance — instant meetings are not supported.
- Host access: You must be the host of the meeting to access it (and its transcript) in Sana.
- Manual recording: As host, you must click Record and select Cloud recording in Zoom for the transcript to be created.
- Zoom plan: Recording and transcription require a Pro, Business, Education, or Enterprise plan.

---

## Zulip

**Guide:** <https://intercom-help.eu/workday-sana/en/articles/629436-connector-guide-zulip>
**Last updated:** 2026-05-18

Prerequisite: Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

- Category: Communication
- Connector type: Real-time
- Auth type: API keys
- Hosting type: Managed

### Capabilities

| Capability |
| --- |
| List users |
| List channels |
| Send messages |

### Tools

| Tool |
| --- |
| Send message |

### Known limitations

- Reading messages: The connector can send messages to Zulip but cannot find or read existing messages.

---

