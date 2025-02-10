---
layout: default
title: Work log
---

# Work log

This is a log of the technical work I've completed.

## 2025

- Moved a component of a monolithic web app into a rest api architecture. To
  support development of an external React application. Including
  automated tests, auth, integration with 3rd party applications
  (credit check, payments, [ITSO HOPS](https://www.itso.org.uk/)),
  OpenApi documentation.
  
## 2024

- Migrated on-prem .Net application and database to Azure App Service
  and Sql Managed Instance.

- JWT refresh token implementation. 

- CORS configuration of rest apis to support SPA.  

- Configuration and deployment of a [NextJS](https://nextjs.org/) SPA. Static export deployment to Azure.

- Migrated on-prem .Net application and database to Azure App Service
  and Sql Managed Instance. Handles ~1M requests per day.
  
- Built Azure monitoring dashboard to monitor: costs, total requests, response status, total requests (by backend), last byte response time (by backend), App Service Plan CPU/Memory, SQL Managed Instances CPU.
  
- Upgraded Azure App Services from P1V2 to P1V3. Scaled Azure Sql Managed Instance to support additional load.

- Diagnosis and resolution of high SQL Server CPU usage. https://learn.microsoft.com/en-us/troubleshoot/sql/database-engine/performance/troubleshoot-high-cpu-usage-issues

- On-boarding of a new developer onto team.

- Improved performance of web application by precompilation of .Net views using MvcBuildViews.

- Resolved security vulnerabilities in .Net web application. XSS, auth, and firewall compatibility.

- Solved Azure App Service Plan performance issue.

- Developed Redis cache session state management solution.

- Migrated on-prem .Net web application and database to Azure App Service and Sql Managed Instance.

- SSL certificate deployment into Azure infrastructure.

- Migrated on-prem .Net application to Azure WebJob.

(April to May time off to walk the [Camino Frances](https://en.wikipedia.org/wiki/French_Way))

- Azure App Service capacity and scale planning.

- Configured WebJob release pipeline in Azure Devops to deploy to multiple
  App Services. Using custom log4net.Appender.AdoNetAppender parameters.

- Front end development. Server side rendered html/cshtml, js and css.

- On-boarded third party developers building integrations against rest
  apis.  

- Sql Server admin; improved migration procedure by using differential
  backups for faster excution; used Sql Server [DBCC SHRINKDATABASE](https://learn.microsoft.com/en-us/sql/t-sql/database-console-commands/dbcc-shrinkdatabase-transact-sql?view=sql-server-ver16)
  to recover 400GB of stoage; performance monitoring and query execution investigations.

- Migrated on-prem .Net application and database to Azure App Service
  and Sql Managed Instance.

- Extended an error/log reporting tool to support Log4Net events
  originating from Azure WebJobs. Amended dotnet core
  rest api and [Mithril.js](https://mithril.js.org) front end.

- Migrated Windows Service code base to Azure Web Job.

## 2023 and prior

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
