# Sana Connector Knowledge Base - Full Content

**Last updated:** 2026-06-29 (Full Restore)
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

# Triggers

While tools are the actions an agent takes on your behalf, triggers are the events that can start an agent automatically. When you build an agent, you can choose one of the triggers below as its starting point. For example, having the agent run every time something new happens in 15Five.

Trigger

New 1-on-1 Created

New Checkin Created

New High Five Received

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector's APIs. The scopes for this connector depends on the scopes you assign your API key in 15Five when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won't appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find 15Five in the list of available connectors

Scroll to the Available connectors section and locate 15Five.

Note : If you can't find a connector in this list, it means one of the following:

-

You've already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the 15Five card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you'll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your 15Five credentials

You'll be asked to paste the credentials for 15Five so Sana can store them securely and use them to call the connector's APIs on your behalf.

## Step 6: Complete the set up

You've successfully connected your 15Five account. Click Continue to complete the setup and start using the connector.

Related Articles Visualping Onelogin Guru Swagger Azure SQL Database

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

# Triggers

While tools are the actions an agent takes on your behalf, triggers are the events that can start an agent automatically. When you build an agent, you can choose one of the triggers below as its starting point. For example, having the agent run every time something new happens in AWS.

Trigger

New Deleted S3 File

New DynamoDB Stream Event

New Inbound SES Emails

New Records Returned by CloudWatch Logs Insights Query

New Restored S3 File

New S3 Event

New S3 File

New Scheduled Tasks

New SNS Messages

New Update to AWS RDS Database (Instant)

Redshift - New Row

Redshift - Updated Row

# Scope and permissions

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector's APIs. The scopes for this connector depends on the scopes you assign your API key in AWS when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won't appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find AWS in the list of available connectors

Scroll to the Available connectors section and locate AWS.

Note : If you can't find a connector in this list, it means one of the following:

-

You've already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the AWS card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you'll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your AWS credentials

You'll be asked to paste the credentials for AWS so Sana can store them securely and use them to call the connector's APIs on your behalf.

## Step 6: Complete the set up

You've successfully connected your AWS account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

S3 search : File search is limited — the connector can only list files in a bucket, not run a filtered search.

-

S3 file formats : Sana can only read the following file formats stored in S3: doc , docx , dot , dotx , dotm , xls , xlsm , xlsx , pps , ppsx , ppt , pptx , odp , ods , odt , rtf , eml , msg , htm , html , markdown , md , epub , tif , tiff , pdf , jpeg , jpg , png , gif , webp , loop , fluid , fluidframework , whiteboard , wbtx , form , note , task , page , pulse , loot , dwg , dsn .

Related Articles What is Sana Privacy and permissions Azure SQL Database Snowflake Google Cloud

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

This connector uses API keys . When you connect your account, we securely store your keys to connect to this connector's APIs. The scopes for this connector depends on the scopes you assign your API key in Airbyte when generating the key.

# Set up instructions

Prerequisites :

-

You are a Sana Enterprise user – all third-party connectors except the Workday connector are available only for users on the Sana Enterprise tier.

-

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won't appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Airbyte in the list of available connectors

Scroll to the Available connectors section and locate Airbyte.

Note : If you can't find a connector in this list, it means one of the following:

-

You've already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Airbyte card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you'll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Provide your Airbyte credentials

You'll be asked to paste the credentials for Airbyte so Sana can store them securely and use them to call the connector's APIs on your behalf.

## Step 6: Complete the set up

You've successfully connected your Airbyte account. Click Continue to complete the setup and start using the connector.

Related Articles RocketReach Zulip Slab Swagger DealCloud

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

# Triggers

While tools are the actions an agent takes on your behalf, triggers are the events that can start an agent automatically. When you build an agent, you can choose one of the triggers below as its starting point. For example, having the agent run every time something new happens in Airtable.

Trigger

New Field Created (Instant)

New or Modified Field (Instant)

New or Modified Records (Instant)

New or Modified Records in View

New Record Created, Updated or Deleted (Instant)

New Record(s) Created (Instant)

New Records in View

New, Modified or Deleted Records

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

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won't appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Airtable in the list of available connectors

Scroll to the Available connectors section and locate Airtable.

Note : If you can't find a connector in this list, it means one of the following:

-

You've already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Airtable card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you'll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Airtable and approve the requested scopes

You'll be redirected to Airtable to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You've successfully connected your Airtable account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Updating content : The connector can't update bases and/or records.

-

Users : The connector can't fetch detailed user data in the workspace, only user IDs.

Related Articles Salesforce Zoom Attio Asana Procore

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

Your Sana workspace owner has enabled this connector – if the workspace owner has disabled the connector it won't appear in the list of available connectors.

## Step 1: Go to the connectors page in Sana

In Sana, click on your profile icon and name in the bottom left corner and select Connectors .

## Step 2: Find Canva in the list of available connectors

Scroll to the Available connectors section and locate Canva.

Note : If you can't find a connector in this list, it means one of the following:

-

You've already connected it — check the ”Active connectors” section at the top of the connectors page, or

-

Your workspace owner has disabled this connector for your workspace — reach out to them for more information or to request that it be enabled.

## Step 3: Hover the connector card and click the connect button

Hover the Canva card and click the Connect button.

Tip : If you click the card itself instead of the Connect button, you'll open a connector detail page with more information about its capabilities.

## Step 4: Initialize the Pipedream connection

When clicking Connect in the previous step, a pop-up will appear powered by Pipedream. Click the Continue button in the pop-up to initialize the set up.

Note : Sana uses Pipedream to connect your account. Pipedream is a Workday product, trusted by millions of people to keep their data secure.

## Step 5: Sign in to Canva and approve the requested scopes

You'll be redirected to Canva to go through their OAuth flow. Sign in and approve the scopes Sana needs to operate the connector.

## Step 6: Complete the set up

You've successfully connected your Canva account. Click Continue to complete the setup and start using the connector.

# Known limitations

-

Read-only : The connector can only access and read your design content. It cannot create or update designs in Canva.

Related Articles ServiceNow Harvest WordPress Calendly Mural

---
