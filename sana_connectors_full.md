# Sana Connector Knowledge Base — Full Content

**Last updated:** 2026-05-26
**Total connectors:** 105
**Source:** https://intercom-help.eu/workday-sana/en/collections/1389607-connector-guides

This file contains the full article text for all 105 Sana connectors.
Each connector section includes setup requirements, OAuth scopes, synced content types,
search capabilities, and any connector-specific limitations.

---

## 15Five

**Source:** https://intercom-help.eu/workday-sana/en/articles/634196-15five

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect 15Five to Sana to access performance management data. Retrieve user profiles, view check-in details, and send High Five recognitions to celebrate your team.

In summary, the connector has the following key characteristics:

-

Category: HR

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Get user profiles

View check-ins

Send High Fives

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about 15Five. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create high five

Get checkin details

Get user

List user options

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in 15Five when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find 15Five in the list of available connectors

Scroll to the Available connectors section and locate 15Five.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the 15Five card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your 15Five credentials

You&#x27;ll be asked to paste the credentials for 15Five so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your 15Five account. Click Continue to complete the setup and start using the connector.

Related Articles Visualping Postman Airbyte Swagger DealCloud

---

## AWS

**Source:** https://intercom-help.eu/workday-sana/en/articles/636404-aws

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect AWS to Sana to query DynamoDB tables, Redshift databases, S3 files, invoke Lambda functions, and send messages through SQS, SNS, and EventBridge.

In summary, the connector has the following key characteristics:

-

Category: Engineering

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Query DynamoDB

Read S3 files

Invoke Lambda functions

Query Redshift

Send SQS messages

Send SNS messages

Send EventBridge events

Write CloudWatch logs

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about AWS. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Cloudwatch logs put log event

Dynamodb create table

Dynamodb execute statement

Dynamodb query

Dynamodb scan

Eventbridge send event

Lambda create function

Lambda invoke function

List region options

Redshift create rows

Redshift delete rows

Redshift query database

Redshift update rows

S3 download file to tmp

S3 generate presigned url

Sns send message

Sqs send message

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in AWS when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find AWS in the list of available connectors

Scroll to the Available connectors section and locate AWS.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the AWS card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your AWS credentials

You&#x27;ll be asked to paste the credentials for AWS so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your AWS account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

S3 search : File search is limited — the connector can only list files in a bucket, not run a filtered search.

-

S3 file formats : Sana can only read the following file formats stored in S3: doc , docx , dot , dotx , dotm , xls , xlsm , xlsx , pps , ppsx , ppt , pptx , odp , ods , odt , rtf , eml , msg , htm , html , markdown , md , epub , tif , tiff , pdf , jpeg , jpg , png , gif , webp , loop , fluid , fluidframework , whiteboard , wbtx , form , note , task , page , pulse , loot , dwg , dsn .

Related Articles Shortcut Postman Procore Swagger DealCloud

---

## Airbyte

**Source:** https://intercom-help.eu/workday-sana/en/articles/634168-airbyte

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Airbyte to Sana to manage your data integration workspaces. List, create, update, and delete workspaces to keep your data pipelines organized and running smoothly.

In summary, the connector has the following key characteristics:

-

Category: Engineering

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List workspaces

Create workspaces

Update workspaces

Delete workspaces

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Airbyte. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create workspace

Delete workspace

List workspace id options

List workspaces

Update workspace

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Airbyte when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Airbyte in the list of available connectors

Scroll to the Available connectors section and locate Airbyte.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Airbyte card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Airbyte credentials

You&#x27;ll be asked to paste the credentials for Airbyte so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Airbyte account. Click Continue to complete the setup and start using the connector.

Related Articles Shortcut Visualping Postman Swagger DealCloud

---

## Airtable

**Source:** https://intercom-help.eu/workday-sana/en/articles/606510-airtable

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Airtable to Sana to browse, create, and manage records across your bases and tables. Look up information, add new entries, and keep your data up to date without leaving Sana.

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

List bases

List tables

Create tables

Search records

Create records

Delete records

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Airtable. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create comment

Create field

Create multiple records

Create table

Delete record

Get record

List bases

List records

List records in view

List tables

Update comment

Update field

Update table

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

data.records:read

Read existing records from connected bases

data.records:write

Create, update, and delete records

data.recordComments:read

View comments on records

data.recordComments:write

Add or edit record comments

schema.bases:read

Inspect base schemas to understand fields and tables

schema.bases:write

Modify base schema

webhook:manage

Create, update, and delete webhooks

user.email:read

Identify the signed in user for personalization

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Airtable in the list of available connectors

Scroll to the Available connectors section and locate Airtable.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Airtable card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Airtable and approve the requested scopes

You&#x27;ll be redirected to Airtable to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Airtable account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Updating content : The connector can&#x27;t update bases and/or records.

-

Users : The connector can&#x27;t fetch detailed user data in the workspace, only user IDs.

Related Articles Salesforce ServiceNow Attio Gong Google Slides

---

## Asana

**Source:** https://intercom-help.eu/workday-sana/en/articles/627470-asana

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Asana to Sana to manage your tasks and projects. Search, create, and update tasks, organize work into projects and sections, and track progress — all without leaving Sana.

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

Search tasks

List users

List teams

List workspaces

Create tasks

Update tasks

Delete tasks

Create projects

Manage subtasks

Add comments

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Asana. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add task to section

Create project

Create subtask

Create task

Create task comment

Create task from template

Delete task

Find task by id

Get tasks from task list

List organizations options

List task stories

List teams

List users

List workspaces

Search projects

Search sections

Search tasks

Search tasks premium

Search user projects

Update task

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

## Step 2: Find Asana in the list of available connectors

Scroll to the Available connectors section and locate Asana.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Asana card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Asana and approve the requested scopes

You&#x27;ll be redirected to Asana to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Asana account. Click Continue to complete the setup and start using the connector.

Related Articles Linear Shortcut Todoist Harvest Attio

---

## Ashby

**Source:** https://intercom-help.eu/workday-sana/en/articles/625419-ashby

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Ashby to Sana to manage your recruiting pipeline. View applications, create candidates and applications, manage offers, and schedule interviews directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: HR

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List jobs

List applications

Find candidates

Create candidates

Create applications

Create offers

Schedule interviews

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Ashby. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create application

Create candidate

Create interview schedule

Create offer

Get candidate

List applications

Search candidates

Start offer

Start offer process

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Ashby when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Ashby in the list of available connectors

Scroll to the Available connectors section and locate Ashby.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Ashby card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Ashby credentials

You&#x27;ll be asked to paste the credentials for Ashby so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Ashby account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Applications : The connector can only list metadata about applicants (name, email, created date, status, source, job, archive reason, etc.), not details like resume content, notes, or interview feedback.

-

Jobs : The connector can only list jobs, not read details such as job descriptions.

Related Articles Sentry BambooHR Visualping Greenhouse Databricks

---

## Attio

**Source:** https://intercom-help.eu/workday-sana/en/articles/627174-attio

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Attio to Sana to manage your CRM data. Look up records, create and update people, and manage notes without leaving Sana.

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

List companies

List deals

List users

List people

Create person

Update person

Create notes

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Attio. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create note

Create person

Delete list entry

Get record

Update person

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

## Step 2: Find Attio in the list of available connectors

Scroll to the Available connectors section and locate Attio.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Attio card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Attio and approve the requested scopes

You&#x27;ll be redirected to Attio to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Attio account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Search : The connector&#x27;s ability to search for companies, deals, people, and records is limited — it lists objects and scans the list rather than running a filtered search. Broad searches are noisy; the more specific you are (e.g. naming the record), the better the results.

-

Notes : The connector can only create new notes — not search, read, or update existing ones.

-

Tasks : The connector cannot manage tasks.

Related Articles Intercom Harvest PagerDuty Calendly Procore

---

## Azure SQL Database

**Source:** https://intercom-help.eu/workday-sana/en/articles/636294-azure-sql-database

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Azure SQL Database to Sana to query your cloud databases and work with your data directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Engineering

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Query databases

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Azure SQL Database. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Execute query

Execute raw query

List table options

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Azure SQL Database when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Azure SQL Database in the list of available connectors

Scroll to the Available connectors section and locate Azure SQL Database.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Azure SQL Database card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Azure SQL Database credentials

You&#x27;ll be asked to paste the credentials for Azure SQL Database so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Azure SQL Database account. Click Continue to complete the setup and start using the connector.

Related Articles Firebase Supabase Swagger Snowflake Databricks

---

## Bamboohr

**Source:** https://intercom-help.eu/workday-sana/en/articles/629043-bamboohr

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect BambooHR to Sana to manage your applicant tracking workflow. Review job applications, update statuses and add comments directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: HR

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List jobs

List applications

Update application status

Add application comments

View resumes

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about BambooHR. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add application comment

Download resume

Get application

List applications

List application id options

List job id options

Update application status

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in BambooHR when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find BambooHR in the list of available connectors

Scroll to the Available connectors section and locate BambooHR.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the BambooHR card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your BambooHR credentials

You&#x27;ll be asked to paste the credentials for BambooHR so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your BambooHR account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Jobs : The connector can&#x27;t read job descriptions and can&#x27;t filter jobs by status — it returns all jobs, including filled or cancelled ones.

Related Articles Sentry Ashby Visualping Greenhouse Databricks

---

## Bitbucket

**Source:** https://intercom-help.eu/workday-sana/en/articles/624341-bitbucket

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Bitbucket to Sana to manage issues, browse repository files, and collaborate on snippets.

In summary, the connector has the following key characteristics:

-

Category: Engineering

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List repositories

List snippets

Manage issues

Get files

Comment on issues

Comment snippets

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Bitbucket. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create issue

Create issue comment

Create snippet comment

Get file from repository

Get issue

Get snippet

List workspace options

Update issue comment

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

account

Read basic account information for the authenticated Bitbucket user (profile, username, UUID, etc.).

account:write

Update or modify the connected user&#x27;s Bitbucket account data and settings.

team:write

Create and modify Bitbucket teams and team-level settings the user has permission to manage.

repository:write

Create, update, and delete repositories and their settings, including pushing changes and managing repo-level configuration.

pullrequest:write

Create, update, merge, and decline pull requests, as well as manage their comments and approvals.

snippet:write

Create, edit, and delete Bitbucket snippets owned by the user or teams they can write to.

issue:write

Create, edit, and delete issues and issue comments in repositories the user can access.

email

Read the primary and secondary email addresses associated with the connected Bitbucket account.

wiki

Create, edit, and delete wiki content for repositories the user can access.

webhook

Create, edit, and delete webhooks on repositories and/or teams that the user can manage.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Bitbucket in the list of available connectors

Scroll to the Available connectors section and locate Bitbucket.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Bitbucket card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Bitbucket and approve the requested scopes

You&#x27;ll be redirected to Bitbucket to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Bitbucket account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Repositories : The connector can list repositories, but can&#x27;t read their metadata.

-

Reading snippets : The connector can list snippets and add comments, but can&#x27;t read the actual content of a snippet.

Related Articles Jira Linear ClickUp GitHub Jira Data Center

---

## Box

**Source:** https://intercom-help.eu/workday-sana/en/articles/597927-box

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Box to Sana to search and summarize files across your Box account. Browse folders, extract text, view comments, request signatures, and bring together content across multiple files scattered across your company&#x27;s knowledge.

In summary, the connector has the following key characteristics:

-

Category: File storage

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Search files

Search folders

Browse folders

Read files

View comments

Request signatures

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Box. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create sign request

Download file

Get comments

Get file text

List folder items

Search content

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

## Step 2: Find Box in the list of available connectors

Scroll to the Available connectors section and locate Box.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Box card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Box and approve the requested scopes

You&#x27;ll be redirected to Box to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Box account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Search : The connector can only find files and folders by name. It can&#x27;t search by metadata (e.g. last modified) or by content inside files.

-

Folders : The connector can find folders by name, but can&#x27;t list the files inside a folder yet.

-

File formats : The connector can only read the following file formats: pdf , jpeg , jpg , and png .

Related Articles SharePoint Google Drive Dropbox OneDrive Egnyte

---

## Calendly

**Source:** https://intercom-help.eu/workday-sana/en/articles/629786-calendly

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Calendly to Sana to manage your scheduling. View upcoming events and invitees, check your availability schedules and create one-time booking links.

In summary, the connector has the following key characteristics:

-

Category: Productivity

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List events

Check availability

Create scheduling links

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Calendly. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create invitee no show

Create scheduling link

Get event

List event invitees

List user availability schedules

List webhook subscriptions

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

## Step 2: Find Calendly in the list of available connectors

Scroll to the Available connectors section and locate Calendly.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Calendly card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Calendly and approve the requested scopes

You&#x27;ll be redirected to Calendly to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Calendly account. Click Continue to complete the setup and start using the connector.

Related Articles Outlook Calendar PagerDuty Gong Procore Dynamics 365 Sales

---

## Canva

**Source:** https://intercom-help.eu/workday-sana/en/articles/617323-canva

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Canva to Sana to pull design content into your context. Review, summarize, and analyze designs in Canva without leaving Sana.

In summary, the connector has the following key characteristics:

-

Category: Design

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List designs

Read designs

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Canva. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Export design

List designs

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

profile:read

Read basic information about your Canva user profile

asset:read

View existing assets in your Canva account (images, uploads, media)

asset:write

Create or update assets in your Canva account

brandtemplate:content:read

View the full content of brand templates (layouts and elements)

brandtemplate:meta:read

View metadata about brand templates (names, IDs, details)

design:content:read

View the full content of your designs (pages, elements, text, images)

design:content:write

Create new designs or change the content of existing designs

design:meta:read

View metadata for designs (titles, IDs, status, timestamps)

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Canva in the list of available connectors

Scroll to the Available connectors section and locate Canva.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Canva card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Canva and approve the requested scopes

You&#x27;ll be redirected to Canva to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Canva account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Read-only : The connector can only access and read your design content. It cannot create or update designs in Canva.

Related Articles Strava WordPress Calendly Procore Mural

---

## Clickup

**Source:** https://intercom-help.eu/workday-sana/en/articles/617979-clickup

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect ClickUp to Sana to manage tasks, track time, and organize your workspace. Create and update tasks, manage checklists, add comments, and navigate spaces, folders, and lists — all without leaving Sana.

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

Get tasks

Create tasks

Update tasks

Delete tasks

Manage checklists

Track time

Manage comments

Manage spaces and folders

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about ClickUp. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create chat view comment

Create checklist

Create checklist item

Create folder

Create list

Create list comment

Create space

Create task

Create task comment

Create task from template

Create threaded comment

Create time entry

Create view comment

Delete checklist

Delete checklist item

Delete comment

Delete folder

Delete list

Delete space

Delete task

Get custom fields

Get folder

Get folder views

Get folders

Get list

Get list comments

Get list views

Get lists

Get space

Get space views

Get spaces

Get task

Get task comments

Get task templates

Get tasks

Get team views

Get view

Get view comments

Get view tasks

List authorized team id options

List workspaces options

Remove task custom field

Start time entry

Stop time entry

Update checklist

Update checklist item

Update comment

Update folder

Update list

Update space

Update task

Update task custom field

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

## Step 2: Find ClickUp in the list of available connectors

Scroll to the Available connectors section and locate ClickUp.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the ClickUp card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to ClickUp and approve the requested scopes

You&#x27;ll be redirected to ClickUp to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your ClickUp account. Click Continue to complete the setup and start using the connector.

Related Articles Google Drive Jira Todoist Trello Asana

---

## Coda

**Source:** https://intercom-help.eu/workday-sana/en/articles/608656-coda

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Coda to Sana to list documents, read pages and tables, create and copy documents, and manage table rows directly in Sana.

In summary, the connector has the following key characteristics:

-

Category: Documents

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List documents

Read pages

Read tables

Create documents

Delete rows

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Coda. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Copy doc

Create doc

Delete row

Find row

Get page

Get page content

Get row

List columns

List docs

List formulas

List pages

List tables

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Coda when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Coda in the list of available connectors

Scroll to the Available connectors section and locate Coda.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Coda card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Coda credentials

You&#x27;ll be asked to paste the credentials for Coda so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Coda account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Search : The connector can only list documents you have access to; it cannot run a filtered search.

-

Tables-only : Within a document, the connector only reads tables. Only basic doc metadata is exposed for the doc itself — non-table content is not accessible.

Related Articles ServiceNow Google Sheets Google Docs AWS Google Slides

---

## Confluence

**Source:** https://intercom-help.eu/workday-sana/en/articles/597932-confluence

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Confluence to Sana to search, read, create, and manage your Confluence pages and blog posts. Get instant answers, derive insights, and summarize complex material from your spaces.

In summary, the connector has the following key characteristics:

-

Category: Documents

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Find pages

Read pages

Create pages

Create blog posts

Update blog posts

Delete blog posts

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Confluence. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create page

Create post

Delete post

Get current user

Get page by id

Get pages

Get pages in space

List post id options

List spaces

Search content

Update post

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

read:confluence-content.all

Read all Confluence content the user has access to

search:confluence

Perform search queries across Confluence content

read:me

Read basic profile details of the current user

offline_access

Refresh access tokens when the user is offline

read:space:confluence

Read metadata and settings for Confluence spaces

read:blogpost:confluence

Read Confluence blog posts

write:blogpost:confluence

Create and update Confluence blog posts

delete:blogpost:confluence

Delete Confluence blog posts

read:page:confluence

Read Confluence pages

write:page:confluence

Create and update Confluence pages

write:confluence-content

Create, update, and delete Confluence content generally

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Confluence in the list of available connectors

Scroll to the Available connectors section and locate Confluence.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Confluence card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Confluence and approve the requested scopes

You&#x27;ll be redirected to Confluence to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Confluence account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Content types : The connector can only fully read Pages . Other content types (Databases, Blogs, Whiteboards) appear in search results but only as brief metadata — Sana cannot fetch their full content.

Related Articles Notion WordPress LinkedIn Shopify Confluence Data Center

---

## Confluence Data Center

**Source:** https://intercom-help.eu/workday-sana/en/articles/667643-confluence-data-center

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect your self-hosted Confluence Data Center instance to Sana to search, read, create, and manage pages and blog posts. Get instant answers and summaries from your spaces.

In summary, the connector has the following key characteristics:

-

Category: Documents

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Search content

Read pages

Create pages

Update pages

Delete pages

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Confluence Data Center. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create content

Delete content

Get page by id

Get pages

List space key options

List type options

Search content

Update content

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Confluence Data Center when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Confluence Data Center in the list of available connectors

Scroll to the Available connectors section and locate Confluence Data Center.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Confluence Data Center card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Confluence Data Center credentials

You&#x27;ll be asked to paste the credentials for Confluence Data Center so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Confluence Data Center account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Content types : This connector primarily reads and writes Pages and Blog posts. Other content types (Databases, Whiteboards) are not supported.

-

Network access : Sana must be able to reach your Confluence Data Center API URL over the public internet.

Related Articles Confluence Coda Ashby Swagger Jira Data Center

---

## Databricks

**Source:** https://intercom-help.eu/workday-sana/en/articles/636394-databricks

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Databricks to Sana to manage jobs, runs, SQL warehouses, serving endpoints, and vector search indexes. Monitor your data platform and trigger workflows directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Engineering

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List jobs

Create jobs

Run jobs

Manage SQL warehouses

List endpoints

Create endpoints

Query vector indexes

Manage vector indexes

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Databricks. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Cancel all runs

Cancel run

Create endpoint

Create job

Create sql warehouse

Create vector search index

Delete endpoint

Delete job

Delete run

Delete sql warehouse

Delete vector search index

Delete vector search index data

Edit sql warehouse

Export run

Get endpoint

Get job

Get job permissions

Get run

Get run output

Get sql warehouse

Get sql warehouse config

Get sql warehouse permissions

Get vector search index

List endpoints

List jobs

List runs

List sql warehouses

List vector search indexes

Query vector search index

Repair run

Reset job

Run job now

Scan vector search index

Set job permissions

Set sql warehouse config

Set sql warehouse permissions

Start sql warehouse

Stop sql warehouse

Sync vector search index

Update job

Upsert vector search index data

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Databricks when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Databricks in the list of available connectors

Scroll to the Available connectors section and locate Databricks.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Databricks card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Databricks credentials

You&#x27;ll be asked to paste the credentials for Databricks so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Databricks account. Click Continue to complete the setup and start using the connector.

Related Articles Zoom Ashby Azure SQL Database Snowflake Google Cloud

---

## Datadog

**Source:** https://intercom-help.eu/workday-sana/en/articles/629166-datadog

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Datadog to Sana to search logs, query metrics, investigate incidents, and monitor your infrastructure. Get insights from your observability data directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Analytics

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Find services

Find monitors

Find metrics

Find logs

Find incidents

Find hosts

Find dashboards

Add metric data

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Datadog. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Get account info

Get metric data

Post metric data

Search dashboards

Search events

Search hosts

Search incidents

Search logs

Search metrics

Search monitors

Search services

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Datadog when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Datadog in the list of available connectors

Scroll to the Available connectors section and locate Datadog.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Datadog card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Datadog credentials

You&#x27;ll be asked to paste the credentials for Datadog so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Datadog account. Click Continue to complete the setup and start using the connector.

Related Articles Shortcut Coda Jotform Slab DealCloud

---

## Dealcloud

**Source:** https://intercom-help.eu/workday-sana/en/articles/634796-dealcloud

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect DealCloud to Sana to list your records and get details about them directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Sales

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Get records

Create records

Update records

Delete records

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about DealCloud. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Delete records

Get records

List entry type id options

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in DealCloud when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find DealCloud in the list of available connectors

Scroll to the Available connectors section and locate DealCloud.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the DealCloud card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your DealCloud credentials

You&#x27;ll be asked to paste the credentials for DealCloud so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your DealCloud account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Search : The connector can only list records — it cannot run a filtered search to find records by specific conditions.

-

Updates : The connector can read and delete records, but cannot create or update them.

Related Articles Postman Firebase Supabase Swagger Snowflake

---

## Docusign

**Source:** https://intercom-help.eu/workday-sana/en/articles/624168-docusign

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect DocuSign to Sana to find, read, and send envelopes. Summarize signed agreements, create new envelopes for signature, and manage in-flight signing workflows.

In summary, the connector has the following key characteristics:

-

Category: Documents

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Search envelopes

Read envelopes

Read documents

Create envelopes

Send envelopes

Void envelopes

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Docusign. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create envelope

Create recipient view

Download documents

Get envelope

List documents

List envelopes

List recipients

Send envelope

Void envelope

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

signature

Create, send, and manage envelopes and signatures on your behalf in DocuSign

extended

Access additional DocuSign account data and features beyond basic signing (templates, users, advanced envelope settings)

openid

Confirm your identity using DocuSign (single sign-on / user profile information)

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Docusign in the list of available connectors

Scroll to the Available connectors section and locate Docusign.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Docusign card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Docusign and approve the requested scopes

You&#x27;ll be redirected to Docusign to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Docusign account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Templates : The connector does not directly support creating envelopes from DocuSign templates; use Create Envelope with a composite template definition for advanced flows.

-

File upload : The connector cannot upload local files to DocuSign; envelopes can only be created from a JSON envelope definition.

Related Articles Harvest WordPress Webex Calendly Procore

---

## Dropbox

**Source:** https://intercom-help.eu/workday-sana/en/articles/606520-dropbox

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Dropbox to Sana to search, browse, read, and manage files across your folders. Summarize documents, create and organize files, and find information without leaving Sana.

In summary, the connector has the following key characteristics:

-

Category: File storage

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Search files

Search folders

Read files

Create files

Create folders

Move files

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Dropbox. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create a text file

Create folder

Create or append to a text file

Delete file folder

Download and export

Download file preview

Download file to tmp

Get shared link file

Get shared link metadata

List file folders in a folder

List file revisions

List shared links

Move file folder

Rename file folder

Restore a file

Search files folders

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

## Step 2: Find Dropbox in the list of available connectors

Scroll to the Available connectors section and locate Dropbox.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Dropbox card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Dropbox and approve the requested scopes

You&#x27;ll be redirected to Dropbox to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Dropbox account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

File formats : Sana can only read the following file formats from your Dropbox: pdf , jpg , jpeg , png , gif .

-

Search : Search runs against file titles and metadata only — there is no full-text search inside file contents. Sana can locate a file by name and then read its contents once found.

Related Articles SharePoint Google Drive Box OneDrive Egnyte

---

## Dynamics 365 Business Central

**Source:** https://intercom-help.eu/workday-sana/en/articles/634821-dynamics-365-business-central

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Dynamics 365 Business Central to Sana to manage your business data. Create and update customers, and retrieve sales orders directly from Sana.

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

Create customers

Update customers

List sales orders

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Dynamics 365 Business Central. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create customer

Get sales order

List company id options

Update customer

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

user.Read

Read basic information about the signed-in user in Azure AD

email

Access the signed-in user&#x27;s primary email address

offline_access

Refresh tokens so the connector can access Business Central when you&#x27;re not signed in

openid

Sign you in using OpenID Connect and identify your Azure AD account

profile

Read additional profile details (name, tenant info) for the signed-in user

financials.readwrite.all

Read and write financial data in Dynamics 365 Business Central, including customers and orders

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Dynamics 365 Business Central in the list of available connectors

Scroll to the Available connectors section and locate Dynamics 365 Business Central.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Dynamics 365 Business Central card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Dynamics 365 Business Central and approve the requested scopes

You&#x27;ll be redirected to Dynamics 365 Business Central to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Dynamics 365 Business Central account. Click Continue to complete the setup and start using the connector.

Related Articles Microsoft Planner Microsoft Entra ID Calendly Procore Dynamics 365 Sales

---

## Dynamics 365 Sales

**Source:** https://intercom-help.eu/workday-sana/en/articles/634815-dynamics-365-sales

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Microsoft Dynamics 365 Sales to Sana to manage your sales data. Find contacts, look up accounts, schedule appointments, and create custom entities directly from Sana.

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

Find contacts

List accounts

Search accounts

List appointments

Create appointments

Update appointments

Create entities

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Dynamics 365 Sales. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create appointment

Create custom entity

Find contact

Get account

List accounts

List appointment categories

List appointment category options

List appointments

List solution id options

Search accounts

Update appointment

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

email

Read the signed-in user&#x27;s primary email address from Azure AD.

offline_access

Allow the app to refresh access tokens so it can access Dynamics 365 Sales when you&#x27;re offline.

openid

Sign you in using OpenID Connect and identify your Azure AD account.

profile

Read basic profile information (name, tenant, ID, etc.) for the signed-in user.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Dynamics 365 Sales in the list of available connectors

Scroll to the Available connectors section and locate Dynamics 365 Sales.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Dynamics 365 Sales card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Dynamics 365 Sales and approve the requested scopes

You&#x27;ll be redirected to Dynamics 365 Sales to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Dynamics 365 Sales account. Click Continue to complete the setup and start using the connector.

Related Articles Salesforce Microsoft Planner DealCloud Dynamics 365 Business Central Upsales

---

## Egnyte

**Source:** https://intercom-help.eu/workday-sana/en/articles/629041-egnyte

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Egnyte to Sana to search, browse, read files, and create folders in your Egnyte workspace.

In summary, the connector has the following key characteristics:

-

Category: File storage

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Find files

Find folders

Read files

Create folders

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Egnyte. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create folder

Download file

List documents

List folders

Search

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

user

Read basic user and account information for the authenticated Egnyte user

link

Create and manage shared links to files and folders

webhooks

Create and manage webhooks to receive change notifications from Egnyte

filesystem

Read and write files and folders in the Egnyte file system

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Egnyte in the list of available connectors

Scroll to the Available connectors section and locate Egnyte.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Egnyte card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Egnyte and approve the requested scopes

You&#x27;ll be redirected to Egnyte to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Egnyte account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Read-only : The connector can only read Egnyte metadata — it cannot create, update, or delete data in Egnyte.

Related Articles SharePoint Google Drive Box Dropbox OneDrive

---

## Evernote

**Source:** https://intercom-help.eu/workday-sana/en/articles/634458-evernote

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Evernote to Sana to read, create, and manage your notes and notebooks. Capture ideas, look up existing notes, update them, and organize your work without leaving the conversation.

In summary, the connector has the following key characteristics:

-

Category: Productivity

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List notes

Read notes

List notebooks

Create notes

Update notes

Create notebooks

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Evernote. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create note

Create notebook

Get note

List note id options

List notebook guid options

List notebooks

List notes

List tag guids options

Update note

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Evernote when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Evernote in the list of available connectors

Scroll to the Available connectors section and locate Evernote.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Evernote card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Evernote credentials

You&#x27;ll be asked to paste the credentials for Evernote so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Evernote account. Click Continue to complete the setup and start using the connector.

Related Articles Sentry Microsoft OneNote Postman Tableau Swagger

---

## Firebase

**Source:** https://intercom-help.eu/workday-sana/en/articles/634664-firebase

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Firebase to Sana to manage your Firestore documents and Realtime Database records. Create, read, update, and list documents in your collections directly from the conversation.

In summary, the connector has the following key characteristics:

-

Category: Engineering

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List documents

Read documents

Create documents

Update documents

Create Realtime records

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Firebase. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create document

Create realtime db record

Get document

List documents

Replicate event firestore

Update document

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Firebase when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Firebase in the list of available connectors

Scroll to the Available connectors section and locate Firebase.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Firebase card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Firebase credentials

You&#x27;ll be asked to paste the credentials for Firebase so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Firebase account. Click Continue to complete the setup and start using the connector.

Related Articles Coda Postman Slab Guru Swagger

---

## Freshdesk

**Source:** https://intercom-help.eu/workday-sana/en/articles/634462-freshdesk

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Freshdesk to Sana to manage your support tickets, contacts, agents, and knowledge base. Create, update, and track tickets, assign to agents, manage solution articles, and streamline your customer support workflow.

In summary, the connector has the following key characteristics:

-

Category: Support

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Create tickets

Create messages

Create solution articles

Create contacts

Create companies

Create agents

Update tickets

Update solution articles

Update agents

List articles

List messages

List solution articles

List contacts

List tickets

List folders

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Freshdesk. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add note to ticket

Add ticket tags

Assign ticket to agent

Assign ticket to group

Close ticket

Create agent

Create company

Create contact

Create message for thread

Create reply

Create solution article

Create thread

Create ticket

Create ticket field

Delete solution article

Download attachment

Forward ticket

Get agent

Get canned response

Get contact

Get folder canned responses

Get solution article

Get ticket

List agents

List all folders

List all tickets

List category folders

List agent id options

List canned response folder id options

List company id options

List folder articles

List folder canned responses

List from email options

List group id options

List role ids options

List skill ids options

List solution categories

List ticket conversations

List ticket field id options

List ticket fields

List ticket id options

Remove ticket tags

Reply to forward

Search solution article

Set ticket priority

Set ticket status

Set ticket tags

Update agent

Update contact

Update solution article

Update ticket

Update ticket field

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Freshdesk when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Freshdesk in the list of available connectors

Scroll to the Available connectors section and locate Freshdesk.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Freshdesk card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Freshdesk credentials

You&#x27;ll be asked to paste the credentials for Freshdesk so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Freshdesk account. Click Continue to complete the setup and start using the connector.

Related Articles Google Drive Zendesk ClickUp Intercom Freshservice

---

## Freshservice

**Source:** https://intercom-help.eu/workday-sana/en/articles/634465-freshservice

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Freshservice to Sana to manage IT service tickets and knowledge base articles. Create and update tickets, browse solution articles, and streamline your IT service management workflow.

In summary, the connector has the following key characteristics:

-

Category: Support

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List tickets

Create tickets

Update tickets

List solution articles

Create solution articles

Update solution articles

Delete solution articles

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Freshservice. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create solution article

Create ticket

Delete solution article

Get solution article

Get ticket

List solution articles

List solution categories

List solution category id options

List ticket id options

Update solution article

Update ticket

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Freshservice when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Freshservice in the list of available connectors

Scroll to the Available connectors section and locate Freshservice.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Freshservice card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Freshservice credentials

You&#x27;ll be asked to paste the credentials for Freshservice so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Freshservice account. Click Continue to complete the setup and start using the connector.

Related Articles Zendesk Intercom Postman Freshdesk Swagger

---

## Github

**Source:** https://intercom-help.eu/workday-sana/en/articles/624268-github

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect GitHub to Sana to search and manage issues, pull requests, repositories, and workflows. Stay on top of your development work with context from your connected apps.

In summary, the connector has the following key characteristics:

-

Category: Engineering

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List repositories

Create repositories

Find issues

Comment issues

Find pull requests

Create pull requests

Create branches

List branches

List releases

List commits

Read files

Create files

Update files

Manage gists

List workflows

Toggle workflows

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about GitHub. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create branch

Create gist

Create issue comment

Create or update file contents

Create pull request

Create repository

Create workflow dispatch

Disable workflow

Enable workflow

Get commit

Get current user

Get issue

Get issue assignees

Get repository

Get repository content

Get workflow run

List branches

List commits

List gist id options

List org name options

List organization repositories

List organizations

List releases

List repositories

List team id options

List workflow runs

Search issues and pull requests

Star repo

Sync fork branch with upstream

Update gist

Update project v2 item status

Update pull request

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

repo

Read and write access to repositories

read:org

Read organization membership and teams

admin:org_hook

Manage organization webhooks

gist

Create and update your gists

project

Manage and update GitHub Projects

notifications

Read and mark notifications

read:user

Read your public and profile information

write:discussion

Create and edit GitHub Discussions

admin:repo_hook

Manage repository webhooks

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find GitHub in the list of available connectors

Scroll to the Available connectors section and locate GitHub.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the GitHub card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to GitHub and approve the requested scopes

You&#x27;ll be redirected to GitHub to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your GitHub account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Issues : The connector cannot change the status of an issue, only edit other metadata.

-

Branches : The connector can list branches but searching them is limited.

Related Articles Linear GitLab Bitbucket Ironclad Jira Data Center

---

## Gitlab

**Source:** https://intercom-help.eu/workday-sana/en/articles/624270-gitlab

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect GitLab to Sana to search and manage issues, epics, branches, and commits. Stay on top of your development work with context from your connected apps.

In summary, the connector has the following key characteristics:

-

Category: Engineering

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Search issues

Create issues

Update issues

Manage epics

List groups

List branches

Create branches

List commits

List members

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about GitLab. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create branch

Create epic

Create issue

Get issue

Get repo branch

List commits

List group id options

List group path options

List groups

List project id options

List project members

List repo branches

Search issues

Update epic

Update issue

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

api

Full access to GitLab API (all resources this user can reach)

read_user

Read basic user profile and groups/memberships

read_repository

Read code, branches, tags, and repo metadata

write_repository

Push commits, create branches, tags, and MR-related changes

read_registry

Pull/view images and metadata from GitLab Container Registry

sudo

Act on behalf of other users with elevated admin powers

openid

Use GitLab as an OpenID Connect identity provider

profile

Read standard OpenID profile info (name, username, avatar)

email

Read verified email address(es) for the user

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find GitLab in the list of available connectors

Scroll to the Available connectors section and locate GitLab.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the GitLab card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to GitLab and approve the requested scopes

You&#x27;ll be redirected to GitLab to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your GitLab account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Files : The connector cannot read, create, or update files.

Related Articles Jira GitHub Bitbucket Dynamics 365 Sales Jira Data Center

---

## Gmail

**Source:** https://intercom-help.eu/workday-sana/en/articles/563351-gmail

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Gmail to Sana to find, send and manage your emails. Revisit old conversations, capture action items, summarize attachments, prepare drafts and send follow-ups based on your context instead of starting from scratch.

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

Draft emails

Send emails

Delete emails

Read attachments

List labels

Create labels

Update labels

Manage signatures

Manage send-as aliases

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Gmail. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add label to email

Approve workflow

Archive email

Bulk archive emails

Create draft

Create label

Delete email

Download attachment

Find email

Get current user

Get send as alias

List delegate options

List labels

List send as aliases

List signature options

List thread messages

Remove label from email

Send email

Update org signature

Update primary signature

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

email

Identify your Google account email address

profile

Show your name and profile picture

openid

Secure sign-in and session identity

gmail.labels

Read and manage Gmail labels

gmail.send

Send emails on your behalf from Sana

gmail.modify

Read, label, and archive messages

gmail.compose

Create draft emails from Sana

gmail.settings.basic

Understand your custom configurations

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Gmail in the list of available connectors

Scroll to the Available connectors section and locate Gmail.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Gmail card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Gmail and approve the requested scopes

You&#x27;ll be redirected to Gmail to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Gmail account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Attachment formats : Sana can only read the following file formats in attachments: pdf , jpeg , jpg , png , gif , webp , txt , html , docx . Other file types cannot be opened, read, or summarized.

-

Contacts : The connector does not search Google Contacts — you need to provide email addresses explicitly.

-

Label deletion : The connector can create labels and add or remove them from emails, but cannot delete label definitions from Gmail.

Related Articles Outlook Email Box Trello Intercom Docusign

---

## Gong

**Source:** https://intercom-help.eu/workday-sana/en/articles/629834-gong

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Gong to Sana to access your recorded sales calls and meetings. Browse call recordings, read transcripts, analyze detailed call data, and log new calls directly from Sana

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

List calls

Read transcripts

Add calls

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Gong. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add new call

Get extensive data

List calls

List workspace id options

Retrieve transcripts of calls

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

api:calls:read:basic

Read basic metadata for Gong calls and meetings

api:calls:create

Create new call records and upload external call data

api:users:read

Read Gong user profiles and IDs

api:crm:integrations:read

View CRM integration configuration and mapping in Gong

api:library:read

Read items in the Gong content library (clips, playlists, etc.)

api:data-privacy:read

View data-privacy settings and objects (e.g. privacy requests)

api:meetings:user:create

Schedule or register user meetings in Gong

api:engagement-data:write

Write engagement events (emails, calls, meetings) into Gong

api:workspaces:read

Read Gong workspaces and their configuration

api:calls:read:transcript

Access full transcripts and conversation text for calls

api:calls:read:extensive

Read detailed call data, including speakers, tracks, and analytics

api:calls:read:media-url

Get secure URLs to stream or download call audio/video media

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Gong in the list of available connectors

Scroll to the Available connectors section and locate Gong.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Gong card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Gong and approve the requested scopes

You&#x27;ll be redirected to Gong to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Gong account. Click Continue to complete the setup and start using the connector.

Related Articles Zoom Shortcut Zulip Twilio Tableau

---

## Google Calendar

**Source:** https://intercom-help.eu/workday-sana/en/articles/563348-google-calendar

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Google Calendar to Sana to quickly find events, check availability, and create or update meetings with a simple prompt. Prepare for upcoming calls, clean up conflicts, and revisit past events when you need a quick recap.

In summary, the connector has the following key characteristics:

-

Category: Productivity

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Find events

Check availability

Create events

Update events

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Google Calendar. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add attendees to event

Create event

Delete event

Get calendar

Get current user

Get date time

Get event

List calendars

List color id options

List event instances

List events

Quick add event

Query free busy calendars

Update event

Update event instance

Update following instances

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

calendar.events

Read and create calendar events

calendar.readonly

Read calendars and event details only

calendar.settings.readonly

Read calendar settings and time zone

email

Identify your Google account email

profile

Show your name and profile picture

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Google Calendar in the list of available connectors

Scroll to the Available connectors section and locate Google Calendar.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Google Calendar card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Google Calendar and approve the requested scopes

You&#x27;ll be redirected to Google Calendar to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Google Calendar account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Contacts : The connector cannot look up your Google Contacts — participants must be specified by email address rather than by name.

Related Articles Outlook Calendar Google Contacts Google Tasks Google Docs Google Chat

---

## Google Chat

**Source:** https://intercom-help.eu/workday-sana/en/articles/636270-google-chat

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Google Chat to Sana to send messages, browse spaces, and look up members. Stay connected with your team directly from Sana.

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

List spaces

Send messages

Read messages

List members

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Google Chat. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create message

Get member

Get message

Get space

List members

List messages

List spaces

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

email

Read the signed-in user&#x27;s primary email address

profile

Read basic profile information for the signed-in user (name, avatar, etc.)

chat.memberships.app

Manage the app&#x27;s memberships in Google Chat spaces (add or remove the app from spaces)

chat.messages.reactions

View and manage reactions on messages in Google Chat spaces the app has access to

chat.messages.create

Create and send new messages in Google Chat spaces on behalf of the app

chat.messages.reactions.create

Add reactions to messages in Google Chat spaces on behalf of the app

chat.spaces

View and manage Google Chat spaces where the app is installed (metadata and basic settings)

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Google Chat in the list of available connectors

Scroll to the Available connectors section and locate Google Chat.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Google Chat card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Google Chat and approve the requested scopes

You&#x27;ll be redirected to Google Chat to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Google Chat account. Click Continue to complete the setup and start using the connector.

Related Articles Google Calendar Google Contacts Google Tasks Google Sheets Google Docs

---

## Google Cloud

**Source:** https://intercom-help.eu/workday-sana/en/articles/636416-google-cloud

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Google Cloud to Sana to run BigQuery queries, list Cloud Storage buckets, control Compute Engine instances, and write Cloud Logging entries directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Engineering

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Run BigQuery queries

Insert BigQuery rows

List buckets

Search objects

Create buckets

Manage instances

Write logs

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Google Cloud. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Bigquery insert rows

Create bucket

Create scheduled query

Get bucket

Get object

List bucket name options

List buckets

List dataset id options

List zone name options

Logging write log

Run query

Search objects

Switch instance boot status

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Google Cloud when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Google Cloud in the list of available connectors

Scroll to the Available connectors section and locate Google Cloud.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Google Cloud card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Google Cloud credentials

You&#x27;ll be asked to paste the credentials for Google Cloud so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Google Cloud account. Click Continue to complete the setup and start using the connector.

Related Articles Google Contacts Google Tasks Google Sheets Google Docs Google Chat

---

## Google Contacts

**Source:** https://intercom-help.eu/workday-sana/en/articles/597891-google-contacts

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Google Contacts to Sana to quickly find your contacts directly from Sana. Use this contact information when working in other apps connected to Sana, so you can reference and reuse accurate people data without leaving your workflow.

In summary, the connector has the following key characteristics:

-

Category: Productivity

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Search contacts

View contact details

Delete contacts

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Google Contacts. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Delete contact

Get contact

List contacts

List directory contacts

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

profile

Read basic profile info for the signed-in user (e.g. name, profile picture, language)

email

View the user&#x27;s primary email address to identify them

contacts

Full read/write access to the user&#x27;s Google Contacts

contacts.readonly

Read-only access to the user&#x27;s Google Contacts

contacts.other.readonly

Read-only access to "Other contacts"

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Google Contacts in the list of available connectors

Scroll to the Available connectors section and locate Google Contacts.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Google Contacts card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Google Contacts and approve the requested scopes

You&#x27;ll be redirected to Google Contacts to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Google Contacts account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Update : The connector does not support updating contacts in Google Contacts.

Related Articles Google Calendar Google Tasks Google Sheets Google Docs Google Chat

---

## Google Docs

**Source:** https://intercom-help.eu/workday-sana/en/articles/624199-google-docs

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Google Docs to Sana to search, read, create and edit documents. Create new documents, insert and replace content, and manage your documents directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Documents

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Find documents

Read documents

Create documents

Update documents

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Google Docs. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create document from template

Replace text

Replace image

Insert text

Insert table

Insert page break

Get tab content

Get document

Find document

Create document

Append text

Append image

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

https://www.googleapis.com/auth/drive

Find, read, create, and update Google Docs on your behalf

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Google Docs in the list of available connectors

Scroll to the Available connectors section and locate Google Docs.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Google Docs card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Google Docs and approve the requested scopes

You&#x27;ll be redirected to Google Docs to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Google Docs account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Formatting : Inserted or updated content can sometimes inherit existing formatting from the document rather than applying a completely new style.

-

Sharing : The connector cannot manage sharing permissions on documents.

-

Comments : The connector does not support reading, creating, or updating comments.

Related Articles Google Drive Google Contacts Google Tasks Google Sheets Google Slides

---

## Google Drive

**Source:** https://intercom-help.eu/workday-sana/en/articles/563347-google-drive

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

Related Articles Box OneDrive Google Sheets Google Docs Google Slides

---

## Google Sheets

**Source:** https://intercom-help.eu/workday-sana/en/articles/618409-google-sheets

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Google Sheets to Sana to read, write and manage your spreadsheets. Look up data, add or update rows, create new spreadsheets and worksheets, and keep your data organized.

In summary, the connector has the following key characteristics:

-

Category: Documents

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List spreadsheets

Read spreadsheets

Create spreadsheets

Add worksheets

Find rows

Add rows

Update rows

Generate formulas

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Google Sheets. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add rows

Add worksheet

Find rows

Get spreadsheet info

List spreadsheets

New spreadsheet

Read rows

Update rows

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

email

Know which Google account you use

profile

See your basic account info

https://www.googleapis.com/auth/drive

Access and update your Google Sheets in Drive

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Google Sheets in the list of available connectors

Scroll to the Available connectors section and locate Google Sheets.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Google Sheets card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Google Sheets and approve the requested scopes

You&#x27;ll be redirected to Google Sheets to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Google Sheets account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Spreadsheet operations : The connector cannot change spreadsheet settings or delete spreadsheets — it can only read and edit cells within an existing spreadsheet.

-

Comments : The connector cannot attach comments to individual cells; comments can only be added at the spreadsheet level.

Related Articles Google Drive Google Contacts Microsoft Excel Google Cloud Google Slides

---

## Google Slides

**Source:** https://intercom-help.eu/workday-sana/en/articles/667646-google-slides

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Google Slides to Sana to create new presentations, generate decks from templates, and edit slides.

In summary, the connector has the following key characteristics:

-

Category: Documents

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Find presentations

Create presentations

Update slides

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Google Slides. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create image

Create page element

Create presentation

Create slide

Create table

Delete page element

Delete slide

Delete table column

Delete table row

Find presentation

Insert table columns

Insert table rows

Insert text

Insert text into table

Merge data

Refresh chart

Replace all text

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

https://www.googleapis.com/auth/presentations

Read and edit your Google Slides presentations

https://www.googleapis.com/auth/drive

Find presentations, duplicate templates, and access linked images

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Google Slides in the list of available connectors

Scroll to the Available connectors section and locate Google Slides.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Google Slides card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Google Slides and approve the requested scopes

You&#x27;ll be redirected to Google Slides to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Google Slides account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Reading slide content : This connector can create and edit slides but does not return the full text content of an existing presentation back to the agent.

-

Sharing : This connector cannot manage sharing permissions on presentations.

-

Comments : Reading, creating, and updating comments is not supported.

Related Articles Google Drive Google Contacts Google Tasks Google Sheets Google Docs

---

## Google Tasks

**Source:** https://intercom-help.eu/workday-sana/en/articles/597920-google-tasks

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Google Tasks to Sana to manage your tasks and to-do lists. Create, update, and complete tasks, organize them into lists, and keep track of what needs to get done.

In summary, the connector has the following key characteristics:

-

Category: Productivity

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List task lists

Create task lists

Update task lists

Delete task lists

List tasks

Create tasks

Update tasks

Delete tasks

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Google Tasks. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create task

Create task list

Delete task

Delete task list

List task lists

List tasks

Update task

Update task list

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

https://www.googleapis.com/auth/tasks

Access and manage your Google Tasks lists and individual items

email

Read your primary Google email address for user identification

profile

Read basic profile details like your name and avatar for display

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Google Tasks in the list of available connectors

Scroll to the Available connectors section and locate Google Tasks.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Google Tasks card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Google Tasks and approve the requested scopes

You&#x27;ll be redirected to Google Tasks to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Google Tasks account. Click Continue to complete the setup and start using the connector.

Related Articles Google Calendar Google Contacts Google Sheets Google Docs Google Chat

---

## Greenhouse

**Source:** https://intercom-help.eu/workday-sana/en/articles/634466-greenhouse

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Greenhouse to Sana to manage your recruiting pipeline. Create new candidates and prospects, and add attachments to candidates directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: HR

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List jobs

Create candidates

Create prospects

Add attachments

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Greenhouse. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add attachment to candidate

Create candidate

Create prospect

List candidate id options

List educations options

List job ids options

List user id options

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Greenhouse when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Greenhouse in the list of available connectors

Scroll to the Available connectors section and locate Greenhouse.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Greenhouse card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Greenhouse credentials

You&#x27;ll be asked to paste the credentials for Greenhouse so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Greenhouse account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Reading jobs : The connector can list available jobs (so you can pick one when creating a candidate or prospect), but it cannot read job details such as the job description.

Related Articles RocketReach Ashby BambooHR Visualping Databricks

---

## Guru

**Source:** https://intercom-help.eu/workday-sana/en/articles/634724-guru

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Guru to Sana to manage your knowledge base. Create cards, organize with tags, and read cards directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Documents

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List cards

Create cards

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Guru. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add tag to card

Create card

Export card to pdf

List collection options

List folder ids options

List tags options

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Guru when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Guru in the list of available connectors

Scroll to the Available connectors section and locate Guru.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Guru card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Guru credentials

You&#x27;ll be asked to paste the credentials for Guru so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Guru account. Click Continue to complete the setup and start using the connector.

Related Articles Visualping Postman Airbyte Swagger DealCloud

---

## Harvest

**Source:** https://intercom-help.eu/workday-sana/en/articles/624155-harvest

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Harvest to Sana to manage your time tracking directly from your workflow. Create time entries, start and stop timers, and review project details without leaving Sana.

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

Track time entries

View projects

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Harvest. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Get projects

List account id options

Start timer

Stop timer

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

## Step 2: Find Harvest in the list of available connectors

Scroll to the Available connectors section and locate Harvest.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Harvest card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Harvest and approve the requested scopes

You&#x27;ll be redirected to Harvest to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Harvest account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Time entries : When creating a time entry, only starting a timer is supported — you cannot specify a duration for a past task. Existing or ongoing time entries cannot be listed; the connector only supports creating new ones.

Related Articles Airtable ClickUp Attio Calendly Procore

---

## Hubspot

**Source:** https://intercom-help.eu/workday-sana/en/articles/627538-hubspot

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect HubSpot to Sana to manage your CRM, track your pipeline and keep your sales data up to date. Search and update contacts, companies and deals without leaving Sana.

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

Find contacts

Create contacts

Update contacts

Find companies

Create companies

Update companies

Find deals

Create deals

Update deals

Find leads

Create leads

Update leads

Create activities

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about HubSpot. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Get user details

Search properties

Get properties

Search crm objects

Get crm objects

Create crm object

Update crm object

Create association

List owners

List pipelines and stages

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

business-intelligence

Access analytics and reporting data in HubSpot

crm.lists.read

View static and active lists of records

crm.lists.write

Create and update static and active lists

crm.objects.companies.read

Read company records and their properties

crm.objects.companies.write

Create, update, and delete company records

crm.objects.contacts.read

Read contact records and their properties

crm.objects.contacts.write

Create, update, and delete contact records

crm.objects.deals.read

Read deal records, stages, and amounts

crm.objects.deals.write

Create, update, and delete deals

crm.objects.quotes.read

Read quote records and details

crm.objects.quotes.write

Create, update, and delete quotes

crm.objects.owners.read

Read CRM owner records (users who own objects)

crm.objects.listings.read

Read custom "listing" CRM objects and their data

crm.objects.listings.write

Create, update, and delete "listing" CRM objects

crm.objects.feedback_submissions.read

Read feedback and survey submission records

crm.schemas.companies.read

View the schema for company objects and properties

crm.schemas.companies.write

Modify company schema, including custom properties

crm.schemas.contacts.read

View the schema for contact objects and properties

crm.schemas.contacts.write

Modify contact schema, including custom properties

crm.schemas.deals.read

View the schema for deal objects and properties

crm.schemas.deals.write

Modify deal schema, including custom properties

crm.schemas.quotes.read

View the schema for quote objects and properties

crm.schemas.listings.read

View the schema for listing objects and properties

crm.schemas.listings.write

Modify listing schema, including custom properties

crm.import

Import data into HubSpot CRM in bulk

files

Access and manage files stored in HubSpot file manager

forms

Access and manage HubSpot forms and submissions

forms-uploaded-files

Access files uploaded through HubSpot forms

oauth

Authenticate using OAuth and manage access tokens

timeline

Create and manage custom timeline events on records

integration-sync

Configure and manage data sync between HubSpot and external systems

conversations.read

Read conversations such as inbox threads and messages

conversations.write

Create and update conversations and messages

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find HubSpot in the list of available connectors

Scroll to the Available connectors section and locate HubSpot.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the HubSpot card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to HubSpot and approve the requested scopes

You&#x27;ll be redirected to HubSpot to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your HubSpot account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Activities : The connector can detect and count activities on a record but cannot read their content (e.g. it can tell you a note exists, but not read the note). It can create activities such as notes, but cannot update existing ones.

Related Articles Salesforce Pipedrive Attio Ironclad Zoho CRM

---

## Intercom

**Source:** https://intercom-help.eu/workday-sana/en/articles/620363-intercom

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Intercom to Sana to retrieve and review conversations. Stay on top of customer conversations without leaving Sana.

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

List contacts

List conversations

Read conversations

Send messages

Manage contacts

Create notes

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Intercom. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add tag to contact

Create note

List admin id options

List tag id options

List team assignee id options

Retrieve conversation

Send incoming message

Send message to contact

Upsert contact

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

People

View and manage Intercom users and leads

Companies

View and manage company records in Intercom

Conversations

View and update Inbox conversations

Teams and teammates

View teams, teammates and away status

Tags

View and manage people, company and conversation tags

People activity

View and create people activity events

Workspace counts

View numerical workspace usage counts

Data attributes

Manage customer and company attributes

Tickets

View and manage support tickets

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Intercom in the list of available connectors

Scroll to the Available connectors section and locate Intercom.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Intercom card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Intercom and approve the requested scopes

You&#x27;ll be redirected to Intercom to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Intercom account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Search : The connector can only list contacts and conversations — it cannot run a filtered search, which limits search quality.

-

Attachments : The connector cannot process attachments in conversations.

Related Articles Gong Evernote Keycloak Slab Firebase

---

## Ironclad

**Source:** https://intercom-help.eu/workday-sana/en/articles/634160-ironclad

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Ironclad to Sana to manage your workflows. Launch new workflows and comment existing workflows to streamline your contract lifecycle management directly from Sana

In summary, the connector has the following key characteristics:

-

Category: Productivity

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Ironclad. In practice, the agent may call one or more tools to achieve a single capability.

Tool

List properties options

List record id options

List record type options

List selected events options

List template id options

List workflow id options

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

scim.users.readUsers

Read Ironclad user identities via SCIM (for mapping and assignments)

public.workflows.readWorkflows

View existing workflows and their current status

public.workflows.readSchemas

Read workflow schemas / templates to know available fields and configuration

public.workflows.createWorkflows

Start new workflows based on available templates

public.workflows.updateWorkflows

Update properties or state of existing workflows

public.records.readSchemas

Read record schemas to understand record types and fields

public.records.readRecords

View existing records linked to workflows or contracts

public.records.createRecords

Create new records in Ironclad (e.g. counterparties, contracts)

public.webhooks.createWebhooks

Register new webhooks to receive Ironclad event callbacks

public.webhooks.deleteWebhooks

Remove existing webhook registrations

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Ironclad in the list of available connectors

Scroll to the Available connectors section and locate Ironclad.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Ironclad card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Ironclad and approve the requested scopes

You&#x27;ll be redirected to Ironclad to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Ironclad account. Click Continue to complete the setup and start using the connector.

Related Articles Salesforce ServiceNow Airtable Harvest Attio

---

## Jira

**Source:** https://intercom-help.eu/workday-sana/en/articles/596247-jira

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

## Jira Data Center

**Source:** https://intercom-help.eu/workday-sana/en/articles/667642-jira-data-center

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

## Jira Service Desk

**Source:** https://intercom-help.eu/workday-sana/en/articles/667644-jira-service-desk

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

Related Articles Google Drive Jira PagerDuty Datadog Jira Data Center

---

## Jotform

**Source:** https://intercom-help.eu/workday-sana/en/articles/623920-jotform

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Jotform to Sana to browse, review and analyze form submissions. Quickly summarize feedback, find specific answers and monitor submission volumes without leaving Sana.

In summary, the connector has the following key characteristics:

-

Category: Marketing

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List forms

Read form responses

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Jotform. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Get form submissions

Get monthly user usage

Get user submissions

List forms

List team id options

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Jotform when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Jotform in the list of available connectors

Scroll to the Available connectors section and locate Jotform.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Jotform card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Jotform credentials

You&#x27;ll be asked to paste the credentials for Jotform so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Jotform account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Read-only : The connector only reads forms and form submissions — it cannot create, update, or delete data in Jotform.

-

Search : The connector can only list your forms; it cannot run a filtered search.

Related Articles Shortcut Postman Zulip Swagger DealCloud

---

## Keycloak

**Source:** https://intercom-help.eu/workday-sana/en/articles/634660-keycloak

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Keycloak to Sana to manage users in your identity provider. Create, retrieve, update, and delete users directly from the conversation.

In summary, the connector has the following key characteristics:

-

Category: Identity

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Create users

Get user details

Update users

Delete users

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Keycloak. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create user

Delete user

Get user

List realm options

Update user

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Keycloak when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Keycloak in the list of available connectors

Scroll to the Available connectors section and locate Keycloak.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Keycloak card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Keycloak credentials

You&#x27;ll be asked to paste the credentials for Keycloak so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Keycloak account. Click Continue to complete the setup and start using the connector.

Related Articles Postman Onelogin Airbyte 15Five Swagger

---

## Linear

**Source:** https://intercom-help.eu/workday-sana/en/articles/601562-linear

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Linear to Sana to search, create, and manage issues, initiatives, views, and comments across your teams and projects. Triage bugs and track progress without leaving Sana.

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

List teams

List projects

Create projects

Search issues

Create issues

Update issues

Manage initiatives

List views

Comment on issues

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Linear. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create comment

Create initiative

Create issue

Create project

Get current user

Get issue

Get teams

Get view issues

List comments

List initiatives

List projects

List views

List workflow states

Remove label from issue

Search issues

Update initiative

Update issue

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

admin

Read configs of custom workspace-level settings

read

Read teams, projects, and issues

write

Update existing issues

issues:create

Create new issues

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Linear in the list of available connectors

Scroll to the Available connectors section and locate Linear.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Linear card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Linear and approve the requested scopes

You&#x27;ll be redirected to Linear to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Linear account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Projects : The connector cannot update or delete projects. Listing exposes only key fields (id, name, lead, status, progress, url). Project creation only sets team, name, and description.

-

Search : Teams and projects can only be listed — no filtered search. Issue search is limited to filtering by team, project, assignee, label, and title.

-

Users : The connector cannot look up users by name or email — only by ID.

Related Articles Sentry Asana Tableau Procore Jira Data Center

---

## Linkedin

**Source:** https://intercom-help.eu/workday-sana/en/articles/629774-linkedin

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect LinkedIn to Sana to manage your professional presence. Create and publish posts as yourself or your organization, engage with comments and likes, look up member profiles and organizations, and manage your LinkedIn activity from one place.

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

Create posts

Search organizations

Delete posts

View profiles

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about LinkedIn. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create comment

List ad account id options

List campaign id options

List organization id options

Create image post organization

Create image post user

Create like on share

Create text post organization

Create text post user

Delete post

Fetch ad account

Get current member profile

Get member organization access control

Get member profile

Get multiple member profiles

Get org member access

Get organization access control

Get organization administrators

Get profile picture fields

Retrieve comments on comments

Retrieve comments shares

Search organization

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

r_1st_connections_size

Read the size of your 1st-degree LinkedIn network

r_basicprofile

Read your basic profile (name, headline, photo, etc.)

r_ads

Read LinkedIn Ads accounts, campaigns, and creatives

rw_ads

Create and manage LinkedIn Ads campaigns and creatives

r_ads_reporting

Read reporting and analytics for your LinkedIn Ads

rw_organization_admin

Manage LinkedIn organization pages and their admin settings

r_organization_social

Read posts and social activity from your organization pages

w_organization_social

Create and manage posts on behalf of your organization pages

r_organization_social_feed

Read your organization&#x27;s social feed and related engagement data

w_organization_social_feed

Publish and manage content in your organization&#x27;s social feed

w_member_social

Create posts, comments, and reactions on your personal LinkedIn account&#x27;s behalf

w_member_social_feed

Publish content and interact with your personal LinkedIn feed programmatically

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find LinkedIn in the list of available connectors

Scroll to the Available connectors section and locate LinkedIn.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the LinkedIn card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to LinkedIn and approve the requested scopes

You&#x27;ll be redirected to LinkedIn to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your LinkedIn account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

People search : The connector cannot search for people — it can only fetch a profile by ID.

Related Articles Zendesk Trello GitHub Microsoft Entra ID Asana

---

## Mailchimp

**Source:** https://intercom-help.eu/workday-sana/en/articles/624529-mailchimp

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Mailchimp to Sana to manage your email marketing audiences, campaigns, and subscribers. Search for contacts, view campaign performance reports, manage tags and segments, and create or send campaigns without leaving Sana.

In summary, the connector has the following key characteristics:

-

Category: Marketing

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Search lists

Search members

Search campaigns

View campaign reports

Create campaigns

Update campaigns

Delete campaigns

Send campaigns

Manage audience lists

Unsubscribe emails

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Mailchimp. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add note to subscriber

List campaign id options

List list id options

List store id options

Add or update subscriber

Add remove member tags

Add segment member

Add subscriber to tag

Create campaign

Create list

Delete campaign

Delete list

Delete list member

Edit campaign template content

Get campaign

Get campaign report

Get list

Get list activities

Get list member activity

Get list member tags

List segment member

Remove segment member

Search campaign

Search lists

Search member

Send campaign

Unsubscribe email

Update campaign

Update list

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

## Step 2: Find Mailchimp in the list of available connectors

Scroll to the Available connectors section and locate Mailchimp.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Mailchimp card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Mailchimp and approve the requested scopes

You&#x27;ll be redirected to Mailchimp to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Mailchimp account. Click Continue to complete the setup and start using the connector.

Related Articles Slack Trello GitLab Microsoft Entra ID LinkedIn

---

## Microsoft Entra ID

**Source:** https://intercom-help.eu/workday-sana/en/articles/627164-microsoft-entra-id

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Microsoft Entra ID to Sana to look up users, view profiles and managers, list and search groups, manage group membership, and create, update, or delete groups directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Identity

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

Get user profiles

Get managers

Search groups

List organization groups

Create groups

Update groups

Update group members

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Microsoft Entra ID. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add member to group

Create group

Delete group

Get manager

Get ms365 groups

Get organization groups

Get organization users

Get profile

Remove member from group

Search groups

Update group

Update user

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

User.Read

Read your basic account info and sign you in.

email

View the email addresses on your account.

offline_access

Stay connected and refresh access when you&#x27;re offline.

openid

Verify your identity when signing in with Entra ID.

profile

View your basic profile details (name, picture, etc.).

Directory.ReadWrite.All

Read and update directory data across the tenant (admin consent).

Group.ReadWrite.All

Read and manage Microsoft 365 groups in the directory (admin consent).

User.ReadWrite

Read and update user profile information.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Microsoft Entra ID in the list of available connectors

Scroll to the Available connectors section and locate Microsoft Entra ID.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Microsoft Entra ID card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Microsoft Entra ID and approve the requested scopes

You&#x27;ll be redirected to Microsoft Entra ID to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Microsoft Entra ID account. Click Continue to complete the setup and start using the connector.

Related Articles Microsoft Planner Microsoft To Do Microsoft Excel Microsoft OneNote Microsoft Teams

---

## Microsoft Excel

**Source:** https://intercom-help.eu/workday-sana/en/articles/624201-microsoft-excel

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Microsoft Excel to Sana to read, write and manage your sheets. Look up data, add or update cells and keep your data up to date and organized.

In summary, the connector has the following key characteristics:

-

Category: Documents

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List spreadsheets

Read spreadsheets

Update cells

Generate formulas

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Microsoft Excel. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add row

Find row

Get columns

Get spreadsheet

Get table rows

List folder id options

Update cell

Update worksheet tablerow

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

User.Read

Sign in the user and read their basic profile information (name, ID, tenant, etc.).

email

View the user&#x27;s primary email address.

offline_access

Maintain access to data you&#x27;ve been granted by using refresh tokens, even when the user is not actively signed in.

openid

Sign in the user with Microsoft identity (OpenID Connect) and receive a unique user identifier.

profile

Read basic profile information such as name, preferred username, and avatar.

Files.ReadWrite

Read, create, update, and delete files the signed-in user can access in OneDrive and SharePoint.

Files.Read.All

Read all files the signed-in user can access across OneDrive and SharePoint, including files the user didn&#x27;t create.

CrossTenantInformation.ReadBasic.All

Read basic information about cross-tenant relationships and external tenants for the organization.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Microsoft Excel in the list of available connectors

Scroll to the Available connectors section and locate Microsoft Excel.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Microsoft Excel card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Microsoft Excel and approve the requested scopes

You&#x27;ll be redirected to Microsoft Excel to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Microsoft Excel account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Search : The connector can only list spreadsheets — it cannot run a filtered search.

-

Creating workbooks : The connector can read and edit Excel workbooks you already have access to, but it cannot create a brand-new workbook.

-

Formatting : The connector cannot change cell formatting.

Related Articles Microsoft Planner Google Sheets Microsoft To Do Microsoft OneNote Microsoft Teams

---

## Microsoft Onenote

**Source:** https://intercom-help.eu/workday-sana/en/articles/627287-microsoft-onenote

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Microsoft OneNote to Sana to search and manage your notebooks. Find pages and sections, create new notebooks and pages, and access your notes without leaving Sana.

In summary, the connector has the following key characteristics:

-

Category: Documents

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Search notebooks

Create notebooks

Create sections

Search pages

Read pages

Create pages

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Microsoft OneNote. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create notebook

Create page

Create section

Get page

Get page content

List notebook id options

List page id options

List section id options

Search notebooks

Search pages

Search sections

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

User.Read

Read your basic Microsoft account profile (name, tenant, ID) to identify you and connect to the correct OneNote account

Email

Read your primary email address to associate the OneNote connection with your user in Sana

Offline_access

Maintain the connection and refresh tokens so Sana can keep working with OneNote without you re-authorizing every time

Openid

Use OpenID Connect for secure sign-in and identity verification with your Microsoft account

Profile

Read basic profile details (e.g. display name, avatar) to personalize the integration

Notes.Create

Create new OneNote pages and other note objects in your notebooks

Notes.ReadWrite.All

Read and edit all OneNote content you have access to (notebooks, sections, pages) so Sana can search, update, and create notes

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Microsoft OneNote in the list of available connectors

Scroll to the Available connectors section and locate Microsoft OneNote.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Microsoft OneNote card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Microsoft OneNote and approve the requested scopes

You&#x27;ll be redirected to Microsoft OneNote to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Microsoft OneNote account. Click Continue to complete the setup and start using the connector.

Related Articles Microsoft To Do Microsoft Excel Microsoft Entra ID Microsoft Teams Evernote

---

## Microsoft Planner

**Source:** https://intercom-help.eu/workday-sana/en/articles/617274-microsoft-planner

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Microsoft Planner to Sana to create, update, and manage tasks, plans, and buckets. Stay on top of your work without leaving Sana.

In summary, the connector has the following key characteristics:

-

Category: Productivity

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List tasks

Create tasks

Update tasks

Create plans

Create buckets

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Microsoft Planner. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create bucket

Create plan

Create task

List user tasks

Update task

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

email

Read your primary email address to identify you and use it in notifications, logs, etc.

offline_access

Keep a refresh token so the connector can continue to call Microsoft 365 on your behalf even when you&#x27;re not actively logged in.

openid

Use Microsoft identity as the authentication provider (basic sign-in).

profile

Read basic profile info (name, avatar, tenant, etc.) to associate Microsoft 365 actions with your user.

Group.ReadWrite.All

Read and modify all Microsoft 365 Groups, including creating/updating Planner plans and buckets that are attached to groups.

Files.ReadWrite

Read, create, update, and delete files you have access to (e.g., attachments linked from Planner tasks).

Files.Read.All

Read all files you have permission to see across SharePoint/OneDrive, even if you didn&#x27;t create them (needed to fetch attachments or related documents).

MailboxSettings.Read

Read your mailbox settings (time zone, language, etc.) so scheduled/notification times and formats match your Outlook configuration.

Tasks.ReadWrite

Read, create, update, and delete your tasks across Microsoft To Do / Planner, which is the core functionality of the Planner connector.

User.Read

Allow the signed-in user to read their own account info and verify identity (standard "sign in and read user profile" permission).

User.Read.All

Read basic profile information for other users in the organization so the connector can look up assignees, owners, and collaborators for Planner tasks and plans.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Microsoft Planner in the list of available connectors

Scroll to the Available connectors section and locate Microsoft Planner.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Microsoft Planner card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Microsoft Planner and approve the requested scopes

You&#x27;ll be redirected to Microsoft Planner to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Microsoft Planner account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Tasks : The connector can only list tasks assigned to the signed-in user, not tasks assigned to someone else or tasks that are unassigned.

Related Articles Microsoft To Do Microsoft Excel Microsoft Entra ID Microsoft OneNote Microsoft Teams

---

## Microsoft Power BI

**Source:** https://intercom-help.eu/workday-sana/en/articles/627504-microsoft-power-bi

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Microsoft Power BI to Sana to explore your workspaces, reports, dashboards, and datasets. Query data with DAX, export reports as PDF or PPTX, manage dataset refreshes, and push rows to streaming datasets without leaving Sana.

In summary, the connector has the following key characteristics:

-

Category: Analytics

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List workspaces

List reports

List datasets

Run DAX queries

Export reports

Refresh datasets

Push data to datasets

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Microsoft Power BI. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add rows dataset table

Add rows to push dataset

Cancel refresh

Create dataset

Execute dax query

Export report

Get dataset refresh

Get refresh history

Get reports

Get reports by id

List dashboards

List datasets

List reports

List workspaces

Refresh dataset

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

offline_access

Keep the Power BI connection active and refresh tokens without repeated sign-in.

App.Read.All

Read all Power BI apps the user can access.

Dashboard.Read.All

Read all dashboards and their tiles.

Workspace.Read.All

List and read all accessible workspaces and their contents.

Dataset.ReadWrite.All

Read and modify datasets, including triggering refreshes.

Report.Read.All

Read reports and related metadata.

Report.ReadWrite.All

Create, copy, and update reports.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Microsoft Power BI in the list of available connectors

Scroll to the Available connectors section and locate Microsoft Power BI.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Microsoft Power BI card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Microsoft Power BI and approve the requested scopes

You&#x27;ll be redirected to Microsoft Power BI to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Microsoft Power BI account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Reading reports : The connector can list reports and read metadata about them, but cannot read the actual data inside a report.

Related Articles Microsoft Planner Microsoft To Do Microsoft Excel Microsoft Entra ID Microsoft OneNote

---

## Microsoft Teams

**Source:** https://intercom-help.eu/workday-sana/en/articles/634147-microsoft-teams

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

Related Articles Slack Microsoft Planner Microsoft To Do Microsoft OneNote Google Chat

---

## Microsoft To Do

**Source:** https://intercom-help.eu/workday-sana/en/articles/618801-microsoft-to-do

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Microsoft To Do to Sana to manage your tasks and to-do lists. Create, update, and organize tasks into lists so you can keep track of what needs to get done.

In summary, the connector has the following key characteristics:

-

Category: Productivity

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List task lists

Create task lists

List tasks

Create tasks

Update tasks

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Microsoft To Do. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create list

Create task

List task lists

List tasks

List time zone options

Update task

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

Tasks.ReadWrite

Read and modify your Microsoft To Do tasks

User.Read

Read basic information about your account

email

Access your primary email address

offline_access

Refresh access when you&#x27;re not signed in

openid

Sign you in using your Microsoft identity

profile

Read basic profile details like name and photo

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Microsoft To Do in the list of available connectors

Scroll to the Available connectors section and locate Microsoft To Do.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Microsoft To Do card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Microsoft To Do and approve the requested scopes

You&#x27;ll be redirected to Microsoft To Do to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Microsoft To Do account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Status : The connector cannot mark or unmark tasks as complete.

-

Deletion : The connector cannot delete task lists or tasks.

Related Articles Microsoft Planner Microsoft Entra ID Microsoft OneNote Microsoft Power BI Microsoft Teams

---

## Miro

**Source:** https://intercom-help.eu/workday-sana/en/articles/602661-miro

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Miro to Sana to search, read, create, update, and delete your Miro boards and board items. Manage sticky notes, shapes, and cards directly from Sana chats.

In summary, the connector has the following key characteristics:

-

Category: Design

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

Read board items

Create boards

Create sticky notes

Create cards

Update boards

Update items

Delete boards

Delete items

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Miro. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create board

Create card item

Create shape

Create sticky note

Delete board

Delete item

Get board

Get items

Get specific item

List boards

Update board

Update card item

Update shape

Update sticky note

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Miro when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Miro in the list of available connectors

Scroll to the Available connectors section and locate Miro.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Miro card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Miro credentials

You&#x27;ll be asked to paste the credentials for Miro so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Miro account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Board search : The connector can list and open boards, but advanced search and filtering (by owner, date, tags, etc.) is not supported. To find a specific board, list your boards first and let the agent narrow it down from there.

Related Articles Trello Monday Guru Mural Jira Data Center

---

## Monday

**Source:** https://intercom-help.eu/workday-sana/en/articles/627509-monday

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Monday to Sana to find and read board items, create boards and groups, and post updates. Keep track of your work and bring your context from Monday to Sana.

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

Find boards

Read board items

Create boards

Post updates

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Monday. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create board

List board id options

List board ids options

Create group

Create update

Get board items page

Get column values

List boards

List workspace id options

List workspace ids options

Update item name

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Monday when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Monday in the list of available connectors

Scroll to the Available connectors section and locate Monday.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Monday card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Monday credentials

You&#x27;ll be asked to paste the credentials for Monday so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Monday account. Click Continue to complete the setup and start using the connector.

Related Articles Miro Postman Airbyte Swagger Jira Data Center

---

## Mural

**Source:** https://intercom-help.eu/workday-sana/en/articles/636282-mural

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Mural to Sana to create murals and add sticky notes to your collaborative workspaces. Kick off brainstorming sessions and workshops directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Design

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Create murals

Add sticky notes

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Mural. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create mural

Create sticky

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

workspaces:read

Read information about Mural workspaces the user has access to

users:read

Read basic profile details for Mural users in the account

murals:write

Create and modify murals and their content (stickies, shapes, etc.)

murals:read

View murals, including their structure and content

rooms:read

Read rooms and their metadata to locate murals and workspaces

identity:read

Read the authenticated user&#x27;s identity and permissions in Mural

templates:read

View available mural templates and their details

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Mural in the list of available connectors

Scroll to the Available connectors section and locate Mural.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Mural card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Mural and approve the requested scopes

You&#x27;ll be redirected to Mural to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Mural account. Click Continue to complete the setup and start using the connector.

Related Articles Google Contacts Notion Miro Egnyte Webex

---

## Notion

**Source:** https://intercom-help.eu/workday-sana/en/articles/597924-notion

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Notion to Sana to search, read, and summarize your Notion pages and databases. Get instant answers from your workspace and use Notion content directly in Sana chats.

In summary, the connector has the following key characteristics:

-

Category: Documents

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Search pages

Read pages

Update pages

Search databases

Read databases

Create databases

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Notion. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create comment

Create database

Delete block

Duplicate page

Get current user

List all users

Query database

Retrieve block

Retrieve database content

Retrieve database schema

Retrieve page

Retrieve page property item

Retrieve user

Search

Update block

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

## Step 2: Find Notion in the list of available connectors

Scroll to the Available connectors section and locate Notion.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Notion card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Notion and approve the requested scopes

You&#x27;ll be redirected to Notion to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Notion account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Teamspaces : You can select pages from multiple teamspaces during set up, but once connected, the agent has no awareness of which teamspaces you&#x27;ve connected.

-

Search : The connector searches by page title only, not by content inside pages.

Related Articles 15Five Firebase Supabase Azure SQL Database Snowflake

---

## Okta

**Source:** https://intercom-help.eu/workday-sana/en/articles/624158-okta

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Okta to Sana to manage user identities. Look up user profiles, create new users, and update account details directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Identity

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List users

Create users

Update users

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Okta. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create user

Get user

List type id options

Update user

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Okta when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Okta in the list of available connectors

Scroll to the Available connectors section and locate Okta.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Okta card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Okta credentials

You&#x27;ll be asked to paste the credentials for Okta so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Okta account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Admin-only : The connector is only intended for Okta admins.

-

Users-only : The connector can only manage users — no other Okta objects (groups, applications, etc.) are exposed.

-

Search : The connector can only list users, not run a filtered search on metadata.

-

Field restrictions : When updating a user, only first name, last name, email, login, and mobile phone can be changed. When creating a user, only first name, last name, username, email, activated, and mobile can be set.

Related Articles Postman Onelogin Airbyte Keycloak Swagger

---

## Onedrive

**Source:** https://intercom-help.eu/workday-sana/en/articles/606527-onedrive

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect OneDrive to Sana to search, browse, read files, create folders, share links, and read Excel tables. Summarize documents, extract key points, and find information without leaving Sana.

In summary, the connector has the following key characteristics:

-

Category: File storage

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Search files

Browse folders

Read files

Create folders

Create sharing links

Read Excel tables

List drives

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about OneDrive. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create folder

Create link

Download file

Find file by name

Get excel table

Get file by id

List files in folder

List my drives

List shared folder reference options

Search files

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

User.Read

Identify your account

email

Identifies your OneDrive user

offline_access

Keeps sync and automations running

openid

Confirms your identity during sign-in

profile

Get information about your user in OneDrive

Files.Read

Allows browsing and previewing your stored files

Files.Read.All

Includes shared and team files in file search and lists

Files.ReadWrite

Enables creating, editing, and organizing your files

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find OneDrive in the list of available connectors

Scroll to the Available connectors section and locate OneDrive.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the OneDrive card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to OneDrive and approve the requested scopes

You&#x27;ll be redirected to OneDrive to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your OneDrive account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Private drive only: The connector can only find and read files in your private drives, not shared drives. If you want to use shared drives, use the SharePoint connector.

-

Protected files: The connector can not read Microsoft Purview information protected files in OneDrive.

-

File formats : The connector can read the following file formats in your OneDrive: pdf, png, jpg, doc, docx, dot, dotx, dotm, dsn, dwg, eml, epub, fluidframework, form, htm, html, loop, loot, markdown, md, msg, note, odp, ods, odt, page, pps, ppsx, ppt, pptx, pulse, rtf, task, tif, tiff, wbtx, whiteboard, xls, xlsm, xlsx.

-

Search : The connector does not support full-text search inside files. It can only locate files by their title or metadata, then read the file once it has been found — so search is limited for content-discovery use cases.

Related Articles SharePoint Google Drive Box Dropbox Microsoft Excel

---

## Onelogin

**Source:** https://intercom-help.eu/workday-sana/en/articles/629214-onelogin

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect OneLogin to Sana to manage user identities. Create users, update details, and revoke sessions directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Identity

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List users

Create users

Update users

Revoke sessions

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Onelogin. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create user

List event type options

List user id options

Revoke user sessions

Update user

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Onelogin when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Onelogin in the list of available connectors

Scroll to the Available connectors section and locate Onelogin.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Onelogin card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Onelogin credentials

You&#x27;ll be asked to paste the credentials for Onelogin so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Onelogin account. Click Continue to complete the setup and start using the connector.

Related Articles Postman Airbyte 15Five Keycloak Swagger

---

## Opsgenie

**Source:** https://intercom-help.eu/workday-sana/en/articles/634603-opsgenie

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Opsgenie to Sana to manage your alerts and incident response. Create and track alerts, add notes, and stay on top of your on-call operations directly from the conversation.

In summary, the connector has the following key characteristics:

-

Category: Engineering

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Create alerts

Check alert status

Add notes to alerts

Delete alerts

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Opsgenie. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add note alert

Create alert

Delete alert

Get alert status

List alert id options

List user options

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Opsgenie when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Opsgenie in the list of available connectors

Scroll to the Available connectors section and locate Opsgenie.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Opsgenie card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Opsgenie credentials

You&#x27;ll be asked to paste the credentials for Opsgenie so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Opsgenie account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Search : The connector can only fetch alert statuses when you already know the alert&#x27;s ID. Searching alerts by other attributes is not supported.

Related Articles Visualping Postman Airbyte Swagger DealCloud

---

## Outlook Calendar

**Source:** https://intercom-help.eu/workday-sana/en/articles/563344-outlook-calendar

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Outlook Calendar to Sana to quickly find events, check availability, and create or update meetings with a simple prompt. Prepare for upcoming calls, clean up conflicts, and revisit past events when you need a quick recap.

In summary, the connector has the following key characteristics:

-

Category: Productivity

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Find events

Check availability

Find meeting times

Create events

Update events

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Outlook Calendar. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create calendar event

Delete calendar event

Delete recurring event instance

Find meeting times

Get current user

Get event

Get schedule

List events

List time zone options

Search contacts

Search people

Update calendar event

Update recurring event instance

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

calendars.readwrite

Read and update your calendars

people.read

See people you work and meet with

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Outlook Calendar in the list of available connectors

Scroll to the Available connectors section and locate Outlook Calendar.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Outlook Calendar card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Outlook Calendar and approve the requested scopes

You&#x27;ll be redirected to Outlook Calendar to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Outlook Calendar account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Contacts : The connector does not have access to your contacts, so other participants must be specified by their email address rather than by name.

Related Articles Google Calendar Outlook Email Calendly Microsoft Teams Procore

---

## Outlook Email

**Source:** https://intercom-help.eu/workday-sana/en/articles/563349-outlook-email

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

Related Articles Outlook Calendar SharePoint Gmail Dropbox Egnyte

---

## Pagerduty

**Source:** https://intercom-help.eu/workday-sana/en/articles/624203-pagerduty

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect PagerDuty to Sana to manage incidents and find users on-call. Trigger, acknowledge, and resolve incidents, and find out who is currently on call.

In summary, the connector has the following key characteristics:

-

Category: Engineering

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Trigger incidents

Acknowledge incidents

Resolve incidents

Find on-call users

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about PagerDuty. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Acknowledge incident

Find oncall user

List escalation policy id options

List oncall schedule id options

List service id options

List user id options

Resolve incident

Trigger incident

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

## Step 2: Find PagerDuty in the list of available connectors

Scroll to the Available connectors section and locate PagerDuty.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the PagerDuty card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to PagerDuty and approve the requested scopes

You&#x27;ll be redirected to PagerDuty to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your PagerDuty account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Incident details : The connector can list incidents, but it cannot read detailed information about them.

-

Active incidents only : The connector can only list active incidents — past or resolved incidents are not retrievable.

Related Articles ServiceNow Harvest WordPress Calendly Procore

---

## Pipedrive

**Source:** https://intercom-help.eu/workday-sana/en/articles/617091-pipedrive

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Pipedrive to Sana to manage your sales pipeline. Search and create deals, leads, contacts and notes, and keep your CRM up to date with context from your connected apps.

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

List deals

Create deals

Update deals

Search leads

Create leads

Update leads

Search contacts

Create contacts

Update contacts

Search notes

Create notes

Create activities

Create organizations

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Pipedrive. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add activity

Add deal

Add lead

Add note

Add organization

Add person

Get all leads

Get deal

Get lead by id

Get person details

List deals

List lead label ids options

List organization label ids options

List person label ids options

List user id options

Merge deals

Merge persons

Remove duplicate notes

Search leads

Search notes

Search persons

Update deal

Update lead

Update person

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

Access to basic information

Read settings of the authorized user and currencies in an account. This is the default permission, always enabled for all apps.

Deals: Full access

Create, read, update and delete deals, their participants, followers, files, notes, and filters. Read access to deal fields, pipelines, stages, and statistics.

Mail: Full access

Read, update, and delete mail threads. Also grants read access to mail messages.

Activities: Full access

Create, read, update, and delete activities and all related files and filters. Includes read access to activity fields and types.

Contacts: Full access

Create, read, update, and delete persons and organizations and their followers, along with related notes, files, and filters.

Products: Full access

Create, read, update, and delete products and their fields; add products to deals.

Read users data

Read data about users (people with access to the Pipedrive account), their permissions, roles, and followers.

See recent account activity

Read all recent changes in the account, including activities, deals, files, notes, persons, organizations, pipelines, stages, products, and users.

Search for all data

Search across the account for deals, persons, organizations, files, and products.

Leads: Full access

Create, read, update, and delete leads and lead labels.

Webhooks: Full access

Create, read, and delete webhooks.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Pipedrive in the list of available connectors

Scroll to the Available connectors section and locate Pipedrive.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Pipedrive card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Pipedrive and approve the requested scopes

You&#x27;ll be redirected to Pipedrive to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Pipedrive account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Organizations : Searching, reading, and creating organizations are not supported.

-

Deletion : Deleting records is not supported.

-

Notes : Notes can be searched and created, but not updated or deleted.

Related Articles Salesforce Zendesk Attio HubSpot Zoho CRM

---

## Postman

**Source:** https://intercom-help.eu/workday-sana/en/articles/629172-postman

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Postman to Sana to manage your API environments and monitors. Run monitors directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Engineering

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Create environments

Run monitors

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Postman. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create environment

List workspace id options

Run monitor

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Postman when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Postman in the list of available connectors

Scroll to the Available connectors section and locate Postman.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Postman card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Postman credentials

You&#x27;ll be asked to paste the credentials for Postman so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Postman account. Click Continue to complete the setup and start using the connector.

Related Articles Jotform Sentry Visualping Datadog Swagger

---

## Procore

**Source:** https://intercom-help.eu/workday-sana/en/articles/634716-procore

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Procore to Sana to manage construction project data. Create RFIs, submittals, incidents, timesheets, and manpower logs directly from Sana.

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

Create RFIs

Create submittals

Log incidents

Track timesheets

Log manpower

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Procore. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create incident

Create manpower log

Create rfi

Create submittal

Create timesheet

List company id options

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

## Step 2: Find Procore in the list of available connectors

Scroll to the Available connectors section and locate Procore.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Procore card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Procore and approve the requested scopes

You&#x27;ll be redirected to Procore to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Procore account. Click Continue to complete the setup and start using the connector.

Related Articles Strava Harvest PagerDuty WordPress Calendly

---

## Rocketreach

**Source:** https://intercom-help.eu/workday-sana/en/articles/608654-rocketreach

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect RocketReach to Sana to look up professional contact information, find decision-makers at target companies, and research company details. Enrich your outreach with verified emails, phone numbers, and professional profiles to accelerate prospecting and relationship-building.

In summary, the connector has the following key characteristics:

-

Category: Sales

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Look up people

Look up companies

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about RocketReach. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Lookup profile

Lookup company

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in RocketReach when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find RocketReach in the list of available connectors

Scroll to the Available connectors section and locate RocketReach.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the RocketReach card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your RocketReach credentials

You&#x27;ll be asked to paste the credentials for RocketReach so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your RocketReach account. Click Continue to complete the setup and start using the connector.

Related Articles Visualping Postman Airbyte Swagger DealCloud

---

## Salesforce

**Source:** https://intercom-help.eu/workday-sana/en/articles/563350-salesforce

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

Related Articles Visualping Onelogin Airbyte DealCloud Upsales

---

## Sentry

**Source:** https://intercom-help.eu/workday-sana/en/articles/624658-sentry

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Sentry to Sana to monitor and manage your application errors. List project issues and events, and update issue status directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Engineering

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List project issues

List project events

List issue events

Update issues

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Sentry. In practice, the agent may call one or more tools to achieve a single capability.

Tool

List issue events

List project events

List project issues

Update issue

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Sentry when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Sentry in the list of available connectors

Scroll to the Available connectors section and locate Sentry.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Sentry card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Sentry credentials

You&#x27;ll be asked to paste the credentials for Sentry so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Sentry account. Click Continue to complete the setup and start using the connector.

Related Articles Postman Evernote Guru Swagger Jira Data Center

---

## Servicenow

**Source:** https://intercom-help.eu/workday-sana/en/articles/600476-servicenow

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

Related Articles Salesforce Airtable Intercom Attio Google Slides

---

## Sharepoint

**Source:** https://intercom-help.eu/workday-sana/en/articles/563345-sharepoint

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

## Shopify

**Source:** https://intercom-help.eu/workday-sana/en/articles/634203-shopify

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Shopify to Sana to manage your online store. Search orders and products, view customer details, manage collections and pages, update inventory levels, and create new products directly from Sana.

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

Search orders

Search products

Get customers

Create products

Update products

Update orders

Update inventory

Create collections

Create pages & blogs

Delete pages & blogs

Create metafields

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Shopify. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add product to custom collection

Bulk import

Create article

Create blog

Create custom collection

Create metafield

Create page

Create product

Create product variant

Delete article

Delete blog

Delete page

Get articles

Get assigned fulfillment orders

Get customer

Get customers

Get draft order

Get draft orders

Get fulfillment

Get fulfillment order

Get fulfillment orders

Get metaobjects

Get pages

Search custom collection by name

Search orders

Search product variant

Search products

Update article

Update inventory level

Update order

Update page

Update product

Update product variant

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

## Step 2: Find Shopify in the list of available connectors

Scroll to the Available connectors section and locate Shopify.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Shopify card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Shopify and approve the requested scopes

You&#x27;ll be redirected to Shopify to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Shopify account. Click Continue to complete the setup and start using the connector.

Related Articles Salesforce Confluence WordPress Confluence Data Center Upsales

---

## Shortcut

**Source:** https://intercom-help.eu/workday-sana/en/articles/605748-shortcut

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Shortcut to Sana to search, read, and create stories. Track work and stay on top of your team&#x27;s progress without leaving Sana.

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

Search stories

Read stories

Create stories

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Shortcut. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create story

List label ids options

List workflow state id options

Search stories

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Shortcut when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Shortcut in the list of available connectors

Scroll to the Available connectors section and locate Shortcut.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Shortcut card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Shortcut credentials

You&#x27;ll be asked to paste the credentials for Shortcut so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Shortcut account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Stories only : The connector can only search and read Shortcut stories — not epics, users, roadmaps, or other entity types.

Related Articles Visualping Postman Airbyte Swagger DealCloud

---

## Slab

**Source:** https://intercom-help.eu/workday-sana/en/articles/634662-slab

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Slab to Sana to search and browse your team documentation. Find posts, explore your knowledge base, and surface relevant information directly from the conversation.

In summary, the connector has the following key characteristics:

-

Category: Documents

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Search posts

Get post details

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Slab. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Get posts

List posts

Search posts

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Slab when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Slab in the list of available connectors

Scroll to the Available connectors section and locate Slab.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Slab card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Slab credentials

You&#x27;ll be asked to paste the credentials for Slab so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Slab account. Click Continue to complete the setup and start using the connector.

Related Articles Monday Datadog Postman Swagger Confluence Data Center

---

## Slack

**Source:** https://intercom-help.eu/workday-sana/en/articles/598448-slack

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Slack to Sana to search conversations and send messages in Slack channels. Find important threads, send updates, manage channels, and stay on top of your team communication without leaving Sana.

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

List channels

Create channels

Search messages

Send messages

Update messages

Browse files

Find users

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Slack. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add reaction

Browse files

Create channel

Edit message

Find user by email

Get channel history

Get thread replies

Get user details

List channels

Post message

Search

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

chat:write

Send and update messages in channels the app is a member of

chat:write.customize

Customize the appearance of messages sent to channels

chat:write.public

Send messages to public channels the user is not yet a member of (the app is auto-joined)

files:read

Read files shared in channels the app has access to (e.g. previews and content)

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Slack in the list of available connectors

Scroll to the Available connectors section and locate Slack.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Slack card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Slack and approve the requested scopes

You&#x27;ll be redirected to Slack to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Slack account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Direct messages : The connector only works with messages in channels — it cannot search, read, or send direct messages or group DMs.

-

User search : The "find users" capability only matches by exact email. As a workaround you can list all users to locate the right one, but this is impractical in large workspaces (the list is paginated).

-

Channel search : The connector lists channels and searches within those results in batches of 250 — it cannot search channels by title or metadata directly. Search quality drops in workspaces with many channels, so naming the exact channel works best.

Related Articles Zoom Intercom Webex Zulip Microsoft Teams

---

## Snowflake

**Source:** https://intercom-help.eu/workday-sana/en/articles/636299-snowflake

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Snowflake to Sana to run SQL queries and insert data into your data warehouse. Get insights from your data and manage records directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Engineering

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Run SQL queries

Insert rows

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Snowflake. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Execute sql query

Insert multiple rows

List database options

List users options

List warehouses options

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Snowflake when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Snowflake in the list of available connectors

Scroll to the Available connectors section and locate Snowflake.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Snowflake card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Snowflake credentials

You&#x27;ll be asked to paste the credentials for Snowflake so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Snowflake account. Click Continue to complete the setup and start using the connector.

Related Articles Postman Airbyte Swagger Azure SQL Database Databricks

---

## Strava

**Source:** https://intercom-help.eu/workday-sana/en/articles/610563-strava

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Strava to Sana to view, create, and manage your activities and training data. Review recent workouts, analyze performance stats, log manual activities, and get summaries of your training directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Lifestyle

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

View activities

Activity details

Your training stats

Create activities

Update activities

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Strava. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create activity

Get activity by id

Get activity list

Get stats

Update activity

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

read

View data about your public profile (required)

activity:read

View data about your activities

activity:read_all

View data about your private activities

activity:write

Upload or edit activities on your behalf

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Strava in the list of available connectors

Scroll to the Available connectors section and locate Strava.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Strava card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Strava and approve the requested scopes

You&#x27;ll be redirected to Strava to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Strava account. Click Continue to complete the setup and start using the connector.

Related Articles Harvest PagerDuty WordPress Calendly Procore

---

## Stripe

**Source:** https://intercom-help.eu/workday-sana/en/articles/629387-stripe

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Stripe to Sana to manage your payments, customers, invoices, and subscriptions. Search customers, process refunds, create invoices, and monitor your balance directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Finance

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List refunds

Create refunds

Update refunds

List payouts

Create payouts

Update payouts

List payment intents

Create payment intents

Update payment intents

List balance history

Find customers

Create customers

Update customers

List invoices

Create invoices

Update invoices

Find subscriptions

Create subscription

Cancel subscription

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Stripe. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Cancel or reverse payout

Cancel payment intent

Cancel subscription

Capture payment intent

Confirm payment intent

Create billing meter

Create customer

Create invoice

Create invoice item

Create payout

Create payment intent

Create price

Create product

Create refund

Create subscription

Create usage record

Delete customer

Delete invoice item

Delete or void invoice

Finalize invoice

List balance history

List customers

List invoices

List payment intents

List payouts

List refunds

Retrieve balance

Retrieve checkout session

Retrieve checkout session line items

Retrieve customer

Retrieve invoice

Retrieve invoice item

Retrieve payout

Retrieve payment intent

Retrieve price

Retrieve product

Retrieve refund

Search customers

Search subscriptions

Send invoice

Update customer

Update invoice

Update invoice item

Update payout

Update payment intent

Update refund

Void invoice

Write off invoice

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Stripe when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Stripe in the list of available connectors

Scroll to the Available connectors section and locate Stripe.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Stripe card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Stripe credentials

You&#x27;ll be asked to paste the credentials for Stripe so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Stripe account. Click Continue to complete the setup and start using the connector.

Related Articles Notion Intercom LinkedIn Calendly Zoho CRM

---

## Supabase

**Source:** https://intercom-help.eu/workday-sana/en/articles/634667-supabase

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Supabase to Sana to manage your database directly. Query, insert, update, and delete rows, count records, and call remote procedures from the conversation.

In summary, the connector has the following key characteristics:

-

Category: Engineering

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Find rows

Insert rows

Update rows

Delete rows

Call procedures

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Supabase. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Count rows

Delete row

Insert row

Remote procedure call

Select row

Update row

Upsert row

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Supabase when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Supabase in the list of available connectors

Scroll to the Available connectors section and locate Supabase.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Supabase card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Supabase credentials

You&#x27;ll be asked to paste the credentials for Supabase so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Supabase account. Click Continue to complete the setup and start using the connector.

Related Articles Coda Postman Swagger Snowflake Google Cloud

---

## Swagger

**Source:** https://intercom-help.eu/workday-sana/en/articles/634728-swagger

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Swagger to Sana to manage your API definitions. Clone and manage API versions directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Engineering

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Clone API versions

Delete API versions

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Swagger. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Clone api version

Delete api version

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Swagger when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Swagger in the list of available connectors

Scroll to the Available connectors section and locate Swagger.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Swagger card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Swagger credentials

You&#x27;ll be asked to paste the credentials for Swagger so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Swagger account. Click Continue to complete the setup and start using the connector.

Related Articles Shortcut Visualping Postman Airbyte DealCloud

---

## Tableau

**Source:** https://intercom-help.eu/workday-sana/en/articles/634605-tableau

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Tableau to Sana to manage your analytics projects and access workbooks. Browse projects, create new ones, and read workbooks directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Analytics

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Find projects

Create projects

List sites

List workbooks

Read workbooks

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Tableau. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create project

Download pdf

List sites

List workbooks

Query projects

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Tableau when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Tableau in the list of available connectors

Scroll to the Available connectors section and locate Tableau.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Tableau card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Tableau credentials

You&#x27;ll be asked to paste the credentials for Tableau so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Tableau account. Click Continue to complete the setup and start using the connector.

Related Articles Shortcut Sentry Monday Postman Swagger

---

## Todoist

**Source:** https://intercom-help.eu/workday-sana/en/articles/606516-todoist

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Todoist to Sana to search, create, and manage tasks across your projects. Stay on top of your to-do list and complete tasks without leaving Sana.

In summary, the connector has the following key characteristics:

-

Category: Productivity

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List projects

Create projects

Update projects

Search tasks

Create tasks

Update tasks

Complete tasks

Import tasks

List comments

Add comments

Update comments

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Todoist. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create filter

Create label

Create project

Create project comment

Create section

Create task

Create task comment

Delete comment

Delete filter

Delete label

Delete project

Delete section

Delete task

Export tasks

Find project

Find task

Find user

Get label

Get project

Get project comment

Get section

Get task

Get task comment

Import tasks

Invite user to project

List filters

List include resource types options

List label string options

List labels

List project comments

List projects

List sections

List select projects options

List task comments

List uncompleted tasks

Mark task completed

Move task to section

Search tasks

Uncomplete task

Update comment

Update filter

Update label

Update project

Update section

Update task

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

task:add

Allow creating new tasks within your projects

data:read_write

Read and modify task data

data:delete

Permanently delete tasks, comments, or other stored Todoist data

project:delete

Remove entire projects and all associated tasks from your account

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Todoist in the list of available connectors

Scroll to the Available connectors section and locate Todoist.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Todoist card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Todoist and approve the requested scopes

You&#x27;ll be redirected to Todoist to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Todoist account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Completed tasks : The connector can only retrieve active, incomplete tasks.

-

Search : Search is basic — for best results, search within a specific project rather than across all projects.

Related Articles Jira Linear Trello ClickUp Asana

---

## Trello

**Source:** https://intercom-help.eu/workday-sana/en/articles/617468-trello

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Trello to Sana to search, create, and manage boards, lists and cards. Stay on top of your projects, move cards between lists and collaborate with your team without leaving Sana.

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

Search boards

Create boards

Search lists

Create lists

Update lists

Search cards

Create cards

Update cards

Add comments

List labels

Create labels

Manage checklists

Search members

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Trello. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add attachment to card

Add checklist

Add comment

Add existing label to card

Add member to card

Archive card

Complete checklist item

Create board

Create card

Create checklist item

Create label

Create list

Delete checklist

Find labels

Find list

Get board

Get card

Get cards in list

Get cards on board

Get list

Get member

List boards

List id organizations options

Move card to list

Remove label from card

Rename list

Search boards

Search cards

Search members

Update card

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

read

Read your data in Trello

write

Write data to your Trello

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Trello in the list of available connectors

Scroll to the Available connectors section and locate Trello.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Trello card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Trello and approve the requested scopes

You&#x27;ll be redirected to Trello to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Trello account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Boards : The connector can create and read boards but cannot update them.

-

Labels : Label definitions can be created, but not updated or deleted. Labels can be removed from cards.

-

Checklists : Checklists are not supported.

-

Comments : Comments can only be added — existing comments cannot be edited or deleted.

Related Articles Jira Miro Todoist ClickUp Monday

---

## Twilio

**Source:** https://intercom-help.eu/workday-sana/en/articles/629870-twilio

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Twilio to Sana to manage your cloud communications. Send and receive SMS messages, look up phone numbers, access call recordings and transcripts directly from Sana

In summary, the connector has the following key characteristics:

-

Category: Communication

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List messages

Send messages

Delete messages

List calls

Delete calls

Look up phone numbers

Read recordings

List transcripts

SMS verification

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Twilio. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Check verification token

Create verification service

Delete call

Delete message

Download recording media

Get call

Get message

Get transcripts

List application sid options

List calls

List from options

List incoming phone number options

List message media

List messages

List parent call sid options

List recording i d options

List service sid options

List sid options

List transcript sids options

List transcripts

Phone number lookup

Send message

Send sms verification

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Twilio when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Twilio in the list of available connectors

Scroll to the Available connectors section and locate Twilio.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Twilio card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Twilio credentials

You&#x27;ll be asked to paste the credentials for Twilio so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Twilio account. Click Continue to complete the setup and start using the connector.

Related Articles Zoom Webex Zulip Gong Google Chat

---

## Typeform

**Source:** https://intercom-help.eu/workday-sana/en/articles/608079-typeform

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Typeform to Sana to create, manage, and analyze your forms. Browse responses, summarize feedback, duplicate forms, and update questions without leaving Sana.

In summary, the connector has the following key characteristics:

-

Category: Marketing

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List forms

Create forms

Update forms

Duplicate forms

Delete forms

View form details

List responses

Look up responses

Manage images

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Typeform. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create form

Create image

Delete form

Delete image

Duplicate form

Get form

List form id options

List forms

List images

List workspace href options

List workspace id options

List responses

Lookup responses

Update dropdown multiple choice ranking

Update form title

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

offline

Allow Sana to stay connected to Typeform when the user is offline

accounts:read

See account details to tailor actions per workspace

forms:read

List and inspect forms to understand their fields

forms:write

Create or update forms based on user prompts

images:read

Fetch images stored in Typeform for richer answers

images:write

Upload images used in questions or responses

themes:read

View themes so generated forms match the existing look

themes:write

Apply or create themes for new AI-made forms

responses:read

Analyze form submissions to answer user questions

responses:write

Submit responses when filling forms for users

webhooks:read

Inspect existing webhooks to align automation flow

webhooks:write

Create or edit webhooks for real-time syncing

workspaces:read

Discover workspaces to correctly place new assets

workspaces:write

Organize forms and assets across workspaces

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Typeform in the list of available connectors

Scroll to the Available connectors section and locate Typeform.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Typeform card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Typeform and approve the requested scopes

You&#x27;ll be redirected to Typeform to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Typeform account. Click Continue to complete the setup and start using the connector.

Related Articles Canva Jotform Google Docs Airbyte Opsgenie

---

## Upsales

**Source:** https://intercom-help.eu/workday-sana/en/articles/667647-upsales

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Upsales to Sana to look up and update companies, contacts, opportunities, and orders. Review your pipeline, log activities, and keep your CRM data up-to-date with context from your connected apps.

In summary, the connector has the following key characteristics:

-

Category: Sales

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

List companies

Create companies

Update companies

List contacts

Create contacts

Update contacts

List opportunities

Create opportunities

Update opportunities

List orders

Create orders

Manage appointments

List activities

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Upsales. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create appointment

List activity id options

List activity type id options

List company id options

List contact id options

List nps id options

List opportunity id options

List order id options

List product id options

List stage id options

List user id options

Create company

Create contact

Create opportunity

Create order

Create stage

Create user

Deactivate user

Get activity

Get activity list

Get appointment list

Get company

Get company list

Get contact

Get contact list

Get nps

Get nps list

Get opportunity

Get opportunity list

Get order

Get order list

Get phone call list

Get product

Get product list

Get stage

Get stage list

Get user

Get user list

Update appointment

Update company

Update contact

Update opportunity

Update order

Update stage

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Upsales when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Upsales in the list of available connectors

Scroll to the Available connectors section and locate Upsales.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Upsales card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Upsales credentials

You&#x27;ll be asked to paste the credentials for Upsales so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Upsales account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Search : This connector lists records but does not yet support free-text or filtered search — narrow down by listing and inspecting results.

-

Deletion : Records cannot be deleted through this connector; users can only be deactivated.

-

Custom fields : Reading and writing arbitrary custom fields is limited.

Related Articles Salesforce Mailchimp Microsoft Entra ID Monday Freshdesk

---

## Visualping

**Source:** https://intercom-help.eu/workday-sana/en/articles/629053-visualping

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Visualping to Sana to manage your website monitoring jobs. Check on existing jobs and update monitoring settings directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Productivity

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Find monitor jobs

Update monitor jobs

Delete monitor jobs

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Visualping. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Delete job

Find jobs

Get job

List workspace id options

Update job

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Visualping when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Visualping in the list of available connectors

Scroll to the Available connectors section and locate Visualping.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Visualping card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Visualping credentials

You&#x27;ll be asked to paste the credentials for Visualping so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Visualping account. Click Continue to complete the setup and start using the connector.

Related Articles Ashby BambooHR Postman Greenhouse Databricks

---

## Webex

**Source:** https://intercom-help.eu/workday-sana/en/articles/629059-webex

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Cisco Webex to Sana to send messages, create rooms, and read conversations. Stay on top of your team communication directly from Sana.

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

List rooms

List messages

Send messages

Create rooms

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Webex. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create message

Create room

List messages

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

spark:all

Full access to your Webex account resources

spark-admin:people_read

Read organisation users and their basic details

spark-admin:people_write

Update organisation user details and settings

spark:devices_read

Read information about Webex devices in your organisation

spark:devices_write

Manage and update Webex device settings

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Webex in the list of available connectors

Scroll to the Available connectors section and locate Webex.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Webex card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Webex and approve the requested scopes

You&#x27;ll be redirected to Webex to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Webex account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Sender attribution : Messages sent through the connector appear as "Pipedream" rather than the signed-in user. The signed-in user is referenced in the message metadata, but it won&#x27;t look like a normal user sent it.

Related Articles Slack Intercom Procore Google Chat Mural

---

## Wordpress

**Source:** https://intercom-help.eu/workday-sana/en/articles/629049-wordpress

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect WordPress to Sana to create posts on your site. Draft blog posts, publish content and manage your WordPress.com site directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Documents

-

Connector type: Real-time

-

Auth type: OAuth

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Create posts

Delete posts

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about WordPress. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Create post

Delete post

List site id options

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

global

Access WordPress.com sites and content your account can manage

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find WordPress in the list of available connectors

Scroll to the Available connectors section and locate WordPress.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the WordPress card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to WordPress and approve the requested scopes

You&#x27;ll be redirected to WordPress to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your WordPress account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Posts : The connector can create and delete posts, but it cannot list, read, or update existing posts.

Related Articles Confluence ServiceNow Calendly Procore Jira Service Desk

---

## Workday

**Source:** https://intercom-help.eu/workday-sana/en/articles/563343-workday

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

Data access is governed by Workday&#x27;s internal permission system. This means:

-

Users can only access data they&#x27;re authorized to see in Workday

-

Permissions mirror what the user can already do in Workday directly

-

No additional scope configuration is needed in Sana

# Known limitations

-

Human-in-the-loop: For the Workday connector, Sana does not directly handle read or write actions. When a user wants to update something, Sana hands the request over to Workday’s self-service agent (WSSA), which completes the change on its own. As a result, there is no approval or “human-in-the-loop” step shown in the Sana UI for these actions.

-

Speed: As Sana hands the action over to Workday’s self-service agent (WSSA) to complete, the overall speed is dependent on how quickly Workday&#x27;s agent processes the request, so results may arrive more slowly than for actions handled directly in Sana or via other 3rd party connectors.

# FAQ

Q: How do I connect to Workday?

A: You don&#x27;t need to connect to Workday - it&#x27;s automatically available when you log in to Sana through SSO. No additional setup required.

Q: What permissions does Workday require in Sana?

A: Your existing Workday permissions determine what you can access in Sana. You can only see and do what you&#x27;re already authorized for in Workday.

Related Articles Manage your Sana account profile About connectors Frequently Asked Questions (FAQ) What is Sana Getting started for admins

---

## Zendesk

**Source:** https://intercom-help.eu/workday-sana/en/articles/608599-zendesk

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Zendesk to Sana to search, create and manage support tickets and browse help center articles. Triage issues without leaving Sana.

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

Search tickets

Create tickets

Update tickets

Delete tickets

Manage ticket tags

Browse help center articles

Search community posts

View macros

Look up users

View side conversations

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Zendesk. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add ticket tags

Create ticket

Delete ticket

Get article

Get side conversation

Get macro

Get ticket info

Get user info

List active macros

List side conversations

List articles

List fields options

List locales

List macro category options

List macros

List ticket comments

List tickets

Remove ticket tags

Search articles

Search community posts

Search help center

Search macros

Search tickets

Set custom ticket fields

Set ticket tags

Update ticket

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

triggers:write

Create and update Zendesk triggers

webhooks:write

Create and manage Zendesk webhooks

read

Read Zendesk data

tickets:write

Create and update support tickets

tickets:read

Read existing support tickets

users:write

Create and update Zendesk users

organizations:read

Read organization records

organizations:write

Create and update organization records

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Zendesk in the list of available connectors

Scroll to the Available connectors section and locate Zendesk.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Zendesk card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Zendesk and approve the requested scopes

You&#x27;ll be redirected to Zendesk to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Zendesk account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Users : The connector can&#x27;t fetch detailed user data in your Zendesk workspace, only user IDs.

-

Article search : The connector can only list help-center articles; it cannot run a filtered search.

Related Articles Intercom Asana Freshdesk Freshservice Jira Service Desk

---

## Zoho CRM

**Source:** https://intercom-help.eu/workday-sana/en/articles/636288-zoho-crm

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Zoho CRM to Sana to search, list and get details about records in modules. Convert leads, read attachments, and handle your CRM data without leaving Sana.

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

Search records

Convert leads

Read attachments

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Zoho CRM. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Convert lead

Download attachment

Get object

List fields

List modules

List objects

Search objects

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

ZohoCRM.settings.all

Read and manage all CRM configuration and settings

ZohoCRM.users.all

Read and manage CRM users and their details

ZohoCRM.org.all

Access organisation-level information for the Zoho CRM account

ZohoCRM.modules.all

Read and write data in all CRM modules (Leads, Contacts, Deals, etc.)

ZohoCRM.bulk.all

Run bulk read/write operations on CRM records

ZohoCRM.notifications.read

Read existing CRM notifications and webhook subscriptions

ZohoCRM.notifications.create

Create new CRM notification / webhook subscriptions

ZohoCRM.notifications.update

Update existing CRM notification / webhook subscriptions

ZohoCRM.notifications.delete

Delete CRM notification / webhook subscriptions

ZohoCRM.coql.READ

Run COQL queries to read CRM data using the Zoho query language

ZohoCRM.functions.execute.CREATE

Execute custom Zoho CRM serverless functions that create or modify data

ZohoCRM.functions.execute.READ

Execute custom Zoho CRM serverless functions that read data

ZohoCRM.templates.email.READ

Read and list email templates stored in Zoho CRM

ZohoCRM.templates.inventory.READ

Read and list inventory templates (quotes, invoices, etc.) in Zoho CRM

ZohoCRM.signals.ALL

Access and manage all Zoho CRM Signals (real-time engagement events and notifications)

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Zoho CRM in the list of available connectors

Scroll to the Available connectors section and locate Zoho CRM.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Zoho CRM card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Zoho CRM and approve the requested scopes

You&#x27;ll be redirected to Zoho CRM to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Zoho CRM account. Click Continue to complete the setup and start using the connector.

Related Articles Pipedrive Bitbucket HubSpot Egnyte Ironclad

---

## Zoom

**Source:** https://intercom-help.eu/workday-sana/en/articles/602718-zoom

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Zoom to Sana to create and manage meetings, read transcripts, view recordings, manage webinars, send chat messages, and handle users. Summarize previous discussions and follow up on action items so nothing gets lost.

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

Find meetings

Create meetings

Update meetings

Read transcripts

Summarize meetings

List recordings

Manage webinars

Send chat messages

Manage users

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Zoom. In practice, the agent may call one or more tools to achieve a single capability.

Tool

Add meeting registrant

Add webinar registrant

Create meeting

Create user

Delete meeting

Delete user

Get current user

Get meeting details

Get meeting recordings

Get meeting summary

Get meeting transcript

Get webinar details

List all recordings

List call recordings

List channels

List meetings

List past meeting participants

List past webinar qa

List user call logs

List webinar participants report

Send chat message

Update meeting

Update webinar

View user

# Scope and permissions

This connector uses OAuth . When you connect your account, you will need to sign into your account and grant the required permissions:

Scope

Purpose

chat_channel:read

Read Zoom chat channels to sync spaces with Sana

chat_message:read

Read chat messages to power search and insights in Sana

chat_message:write

Post messages into Zoom chat from Sana workflows or actions

meeting:read

Read meeting details and participants for context in Sana

meeting:write

Schedule and update Zoom meetings initiated from Sana

phone:read

Read call logs to analyze phone interactions inside Sana

recording:read

Access cloud recordings to index and surface in Sana

user:read

Read user profiles to map Zoom users to Sana accounts

user:write

Update user settings or mappings needed by the Sana integration

webinar:read

Read webinar details and attendance for insights in Sana

webinar:write

Create or update webinars from Sana for scheduling and management

zoom_events_basic:read

Read Zoom Events data to show sessions and registrations in Sana

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Zoom in the list of available connectors

Scroll to the Available connectors section and locate Zoom.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Zoom card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Zoom and approve the requested scopes

You&#x27;ll be redirected to Zoom to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Zoom account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Search : The connector can only list meetings; it cannot run a filtered search across all meeting content. To search inside a meeting, locate the meeting first, then search within it.

-

Recurring meetings : The connector cannot find past meetings within a recurring series.

-

Scheduled meetings only : Transcripts are only generated for meetings scheduled in advance — instant meetings are not supported.

-

Host access : You must be the host of the meeting to access it (and its transcript) in Sana.

-

Manual recording : As host, you must click Record and select Cloud recording in Zoom for the transcript to be created.

-

Zoom plan : Recording and transcription require a Pro, Business, Education, or Enterprise plan.

Related Articles HubSpot Gong Twilio Ironclad DealCloud

---

## Zulip

**Source:** https://intercom-help.eu/workday-sana/en/articles/629436-zulip

Prerequisite : Third-party connectors are available only on the Sana Enterprise tier, with one exception: the Workday connector is included for both Sana Core and Sana Enterprise.

# Introduction

Connect Zulip to Sana to send messages to channels and individuals. Communicate with your team directly from Sana.

In summary, the connector has the following key characteristics:

-

Category: Communication

-

Connector type: Real-time

-

Auth type: API keys

-

Hosting type: Managed

# Capabilities

This connector is able to do the following:

Capability

Send messages

# Tools

While the capabilities above describe what the connector can do at a high level, the underlying tools show exactly which operations the agent can use when you ask Sana about Zulip. In practice, the agent may call one or more tools to achieve a single capability.

Tool

List channel id options

List user id options

Send message

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector&#x27;s APIs. The scopes for this connector depends on the scopes you assign your API key in Zulip when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won&#x27;t appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Zulip in the list of available connectors

Scroll to the Available connectors section and locate Zulip.

Note : If you can&#x27;t find a connector in this list, it means one of the following:

-

You&#x27;ve already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Zulip card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you&#x27;ll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Zulip credentials

You&#x27;ll be asked to paste the credentials for Zulip so Sana can store them securely and use them to call the connector&#x27;s APIs on your behalf.

## Step 6: Complete the set up

You&#x27;ve successfully connected your Zulip account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Reading messages : The connector can send messages to Zulip but cannot find or read existing messages.

Related Articles Visualping Postman Twilio Airbyte Swagger

---
