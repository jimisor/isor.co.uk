---
layout: default
title: Work log
---

# Work log

This is a high level log of the recent technical work I've completed.

## 2024

- Extended an error/log reporting tool to support Log4Net events
  originating from Azure WebJobs. Included amending a dotnet core
  rest api and [Mithril.js](https://mithril.js.org) front end.

- Migrated Windows Service code base to Azure Web Job.

## 2023

- Designed multi-app Azure Application Gateway architecture. Including
  WAF Policy hierarchy, logging and reporting.

- Bug fixes and small UI improvements to React Native mobile application.

- Migrated .Net WCF service from on-prem to Azure App Service.

- Migrated multiple on-prem .Net applications and associated databases
  to Azure App Services and Sql Managed Instance.

- Investigated an intermittent bug in an Android Java app. Added
  improved validation, assertion, logging, and error handling code to
  the problematic SOAP client.

- Wrote [Kusto Query
  Language](https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/)
  queries for common Application Gateway firewall investigations.

- Ported a legacy application from a Windows Service to Azure
  Webjob. With new config management, scheduling, and logging. Built
  and released via Azure Devops pipeline.

- Implemented team code review and automated build, test, release and
  deploy of existing software using Azure Devops.

- Implemented a single sign on integration using Azure AD. Used OAuth
  2.0 authorisation code flow.

- Implemented a software integration importing ITSO HOPS transactions
  from Amazon S3 into a Sql Server database.

- Implemented an Android and ios age verification app for local
  authorities. Used React Native talking to a json back end.

- Attended qCon software architecture conference.

- Migrated on-premise applications to Azure hosted solution based on
  Application Gateway, App Services and Web Jobs.

- Implemented an upgrade of an older api. Adding paging, filtering,
  automated tests and Open Api documentation. Maintained existing
  soap/http endpoints.

- Built an internal reporting tool for ELMAH error logging data. .Net
  Core 6 Web Api; rest api with Open Api docs; unit tested; automated
  build and deployment using Azure Devops; hosted on an Azure App
  Service connected to SQL Managed Instance; Front End SPA built using
  Mithril JS UI framework; minimal style based on Water CSS using
  SCSS; No available solutions provided simple multi-application
  reporting so we built our own.

- Migrated 17 databases (~1TB combined data) from an on-prem Sql
  Server instance to Azure Managed Instance. Built a simple setup
  using a site to site vpn to connect on-prem apps with the new
  database server.

- Designed and implemented a new cloud hosting environment in Azure to
  migrate on-prem solutions to. Including Azure Sql Server Managed
  Instance, virtual networks and machines, site to site VPN, blob
  storage, App Services, Azure Front Door and web application
  firewall.

- Added database transactions support to a legacy application that
  previously didn't support them.

- Took over the maintenance of an existing Android phone app. Managed
  small changes and releases.

- Developed rest api to allow third parties to integrate with core
  business application. Replaced an existing Soap/XML web
  service. Used jwt auth, automated Open Api spec and docs,
  implemented a varied set of GET, POST, PATCH and DELETE operations.

- Developed a rest api and iPhone app to facilitate access to high
  security building and grounds.

- Migrated source control from Subversion to Git/Azure
  Devops. Automating builds and unit test runs.

- Delivered React Native introduction and knowledge share to
  colleagues.

- Implemented an in-app, Tap & Pay compatible, NFC virtual card for
  Android.

- Released app through the Apple Store.

- Implemented Apple Pay iPhone integration.

- Implemented Swift glue code to enable NFC card read and update from
  third party NFC library to our React Native application on iPhone.

- Automated XCode builds of an iPhone app using Azure DevOps
  pipelines.

- Released an app through the Play Store, including a Google Pay
  integration and associated verification and promotion process.

- Developed an automated release pipeline that uses Azure Devops to
  build and sign an Android application and push directly into the
  Google Play Store.

- Implemented Google Pay with NMI Payment gateway integration to
  support in-app purchases.

- Developed a set of unit tests for a legacy monolith that didn't have
  any automated testing.

- Developed a rest api to expose existing business logic and
  data. Used .Net Framework Web Api. Implemented Swagger
  documentation, Jwt authentication, and unit tests on top of the
  core.

- Setup development environment for the team to develop mobile apps,
  using React Native for cross platform development. Including
  automated builds and release via Azure Devops.
