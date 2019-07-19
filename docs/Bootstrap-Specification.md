Organizational Bootstrapping 

This document serves as a transcript for organizational bootstrapping. All applications, services and software serve only a single responsibility that each of the others do not. Apply the logic of each section of this document in chronological order. Once these sections have been applied, all possible uses cases should be defeated. 

Domain Name Email Initialization 

Sign up Office365 for business or Google G-suite to register for an organization domain extension. Then use the organization email with your organization name as the suffix. Create organization service accounts for Microsoft Office, Youtrack and github. 

Administration 

Create an Office365 Business account, then if not already set, set the organizations domain name as the email address extension. This is the only way to interface internally within the organization. 

 

Jetbrains – The HUB, TeamCity & Youtrack are Universally free. 

Master Admin Portal – Jetbrains Hub 

Project Management - Youtrack 

Email integration 

Report Generation 

Version Control 

Associating Projects boards to repositories 

Installation Types 

Youtrack can be used both on the cloud and as system software, or a docker container.  Choose from the following 

Cloud 

Create a Youtrack instance. Your domain-name will be the subdomain 

Host the application on your own server as a docker container from the base image. Make sure to apply volumes 

Machine Local 

Download & run as a jar file 

Run Youtracks image as a docker container 

 

Environmental Images 

Youtrack 

The Hub 

TeamCity 

 

System Services 

There are external services internally within the organization to interface among persons a-like. 

Office (optional) 

Youtrack  

Rider 

Github 

Docker 

Heroku 

Docfx 

Cloud Services 

The Hub – Master busines Dashboard 

Office – Business software communication and application. 

Youtrack – Project board & Tasks 

Github – Remote repository 

Docker – Software Distribution Bundles 

Heroku – Web Server 

Users Account Registration 

As a representatives everyone requires credentials for Microsoft Office, Jetbrains.com and Github.  

 

Internal interfacing is done through... 

The Hub – Administration 

Youtrack – Project management 

Teamcity – Version Control System 

Software Maintenance, Service Credentials & Command-Line Interfaces. 

Docfx 

Git 

Dotnet 

Npm 

Docker 

Compodoc 

Repository Root Configuration Files 

.gitignore 

Docfx.json 

Dockerfile 

docker-compose.yml 

Command Line Tools 

Dotnet 

Docker 

Angular-Cli 

Software Documentation 

Documentation for API’s - Docfx 

Rest Api documentation – Swagger 

Master UI Library 

Semantic-ui-css 

Semantic-ui-React  

Primeng (Charting Components) 

Constituting Consistent Style by Customized Themes 

Use the base stylessheet semantic-ui as the master css across all page layouts. 

Documentation -  Docfx produces static documentation & pdf’s. It produces markdown and yml files from project roots (package.json, csproj.json). 

Pages Themes 