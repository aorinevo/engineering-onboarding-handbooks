# Onboarding Handbook

### Welcome & Introductions

We would like to welcome you to Pager Inc. The purpose of this onboarding handbook is to provide you with comprehensive guidance and direction during your onboarding, familiarize you with Pager Inc. systems, designate a coding buddy, and generally set you up for success.

### Team Structure at Pager

Pager engineering consists of five squads, most of them specializing in a different Pager product:

| Squad Name | Slack Channel | Email distro | JIRA Board |
| ----- | ------ | ---- | ---- |
| Management Enterprise (ME) | #squad-management-enterprise | squad-management-enterprise@pager.com | [ME backlog](https://pagerinc.atlassian.net/secure/RapidBoard.jspa?rapidView=64&projectKey=ME&view=planning.nodetail&issueLimit=100) |
| Consumer Squad (CS) | #squad-consumer | squad-consumer@pager.com | [CS backlog](https://pagerinc.atlassian.net/secure/RapidBoard.jspa?rapidView=49&view=planning.nodetail&issueLimit=100) |    
| Users Enterprise (UE) | #squad-users-enterprise | squad-users-enterprise@pager.com | [UE backlog](https://pagerinc.atlassian.net/secure/RapidBoard.jspa?rapidView=79&projectKey=UE&view=planning&selectedIssue=UE-912&epics=visible&issueLimit=100) |    
| Professional Services Squad (PSS) | #squad-professional-services | squad-professional-services@pager.com | [PSS backlog](https://pagerinc.atlassian.net/secure/RapidBoard.jspa?rapidView=87&projectKey=PSS&view=planning&selectedIssue=PSS-18&issueLimit=100) |
| Platform Squad (PS) | #squad-platform | squad-platform@pager.com | [PS backlog](https://pagerinc.atlassian.net/secure/RapidBoard.jspa?rapidView=59&projectKey=PS&view=planning.nodetail&selectedIssue=PS-674&issueLimit=100) |

Except Platform Squad, each squad contains engineers from frontend (web and/or mobile), backend, machine learning/data as well as QA. Here is the [org chart](https://docs.google.com/drawings/d/14hRZNhhM9m_t88lR9jOoqDkvewiQDf3Rc0wW7n3iyDI/edit) for our squads.
If interested, see [this medium article](https://medium.com/scaled-agile-framework/exploring-key-elements-of-spotifys-agile-scaling-model-471d2a23d7ea) for more information about squad structure.

During your first week, you will be meeting your team members, as well as team leads, who will provide you with an important overview of their respective areas of expertise.

**Your Direct Manager:** [Insert name]\
Your manager will meet with you on your first day to welcome you to Pager, get to know you, understand your personal and professional goals. The purpose of the first meeting is to introduce you to this document, and set initial expectations. We value you and your experience at Pager. We plan to do everything at our disposal to help you grow  as you help grow us. Your manager will walk you through the [Engineering Career Ladder](https://docs.google.com/drawings/d/13-xyAbH8qmyRwgQu7hKC-5cnS6VUcb4pmUiMVIeKbYY) and your respective [Individual Contributor Performance Ruberic](https://docs.google.com/spreadsheets/d/1yoCXujJQ07FcHjKGPYO10RJM9nDKRyD9VLeJGpsZgGM/edit?usp=sharing0). You will have a second meeting with your manager at the end of your first week, to check-in on your onboarding progress and introduce you to your [30-60-90](https://docs.google.com/spreadsheets/d/1gQHA8cq6R8VS-mKz2Qe2OwoRHE8hGOsJPph4h9x9EfQ/edit?usp=sharing) day plan. Once you and your manager go through these you will also set up your weekly one on ones. 

**Coding Buddy:** [Insert name]\
One of the key figures during your first few weeks is your coding buddy. Your coding buddy will be your initial source of information about various systems, tools and practices at Pager. In addition to being your go-to person for code related questions, you can expect your coding buddy to help you pick up your first coding assignments. This will help you dive into coding as quickly as possible, without overwhelming you.

**Frontend Lead:** Mi Ji Kim\
Mi Ji will introduce you to our frontend code, talk about applications such as Command Center and Enterprise Admin. This is an opportunity for you to better understand one of the central applications of our ecosystem and how it ties in with the various backend services.

**Backend Leads:** Ryan Hall (ME), Elba Sanchez (CS), Diego Baquero (UE), Jugal Shah (PSS)\
Ryan will provide you with an overview of our application architecture, introduce you to various aspects of our microservices, and talk about the architectural vision and direction we would like to move towards.

**Mobile Lead:** Fabian Celdeiro\
Fabian will provide you with an overview of Android and iOS applications, as well as help you understand how to install a test application, how to login and test.

**Platform Lead:** Jeremiah Bowen\
Jeremiah will provide you with a high level overview of Pager’s infrastructure, environments and platform tools as they pertain to software engineering. This is a great opportunity for you to understand the operational environment that you will be placed in.

**QA Manager:** Jesmin Aktar\
Jesmin will introduce you to her team members, as well as go over the QA process. This is an excellent opportunity to make some friends in the QA team.

**Director of Engineering:** Shay Weiss\
Introductory meeting with Shay Weis. Shay will provide you with information about engineering vision and get to know you a little better.

### Tools and Processes

At Pager, we use a number of tools that help us keep track of our work, documentation, application metrics and logs. This section lists those tools, and how to access them.

Please make sure to enable 2FA where available.

**Github:** <https://github.com>\
You will need to create a new github account tied to your pager.com email.

**Jira and Confluence:** <https://pagerinc.atlassian.net>\
Use your Pager gmail account to login.

**GoogleCloud Dashboard:** <https://console.cloud.google.com>\
Use your Pager gmail account to login.

**Sentry:** <https://sentry.io/auth/login/pager-oj/>\
Follow instructions in the invitation email to set up your password. Please make sure to set up two factor authentication.

**NewRelic:** <https://login.newrelic.com/>\
Follow instructions in the invitation email to set up your password.

**SumoLogic:** <https://service.sumologic.com/ui/>\
Follow instructions in the invitation email to set up your password. Please make sure to set up two factor authentication.

**MixPanel:** <https://mixpanel.com/>\
Follow instructions in the invitation email to set up your password.

**PagerDuty:** <https://pagerinc.pagerduty.com/>\
Use your Pager credentials to login.

**Github:** <https://github.com>\
You will need to create a new github account tied to your pager.com email.

**Greenhouse:** <https://app.greenhouse.io/>\
Ask Gavin Clarke of the recruiting team


### Command line utilities

These are the command line utilities you will likely to need to do your job

**brew:** <https://brew.sh/>\
If you use Mac, you are likely to need brew to install other utilities

**node:** <https://nodejs.org/en/download/>\
Node js is the main platform we are using now

**git:**
Don't need to download anything, simply run brew install git , git will be installed

**gcloud:** <https://cloud.google.com/sdk/docs#install_the_latest_cloud_tools_version_cloudsdk_current_version>\
Google Cloud cli

**psql:** <https://www.postgresql.org/download/>\
You need the psql client to run SQL query, but you are welcome to use other GUI (e.g pgadmin) if you want

**mongo:** <https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/>\
You need the mongo shell client to run mongo query, but you are welcome to use other GUI (e.g Mongo 3T) if you want

**docker:** <https://docs.docker.com/docker-for-mac/install/>\
You need the docker to run our containers

**kubectl:** <https://kubernetes.io/docs/tasks/tools/install-kubectl/>\
You need the kubectl interact with the Kubernetes cluster

**sops:** <https://formulae.brew.sh/formula/sops>\
You need the sops  to encrypt/decrypt the passwords


### Documentation
Below you will find documentation that will help you gain quicker understanding about Pager, and how things are organized. If you have any questions, comments, or ideas please feel free to comment on the confluence documents, this will help us make the documentation better!

- [Pager Technology Overview](https://docs.google.com/presentation/d/1cPI4CoKAFByFV_KG2-F-eg1F6ZytK9iSaeSYDPL4Y6w) Overview of all Pager's engineering organization and technology
- [Release management](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/227180588/Release+Management): overview of Pager’s release process
- [Tech talks and training](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/161579009/Tech+Talks+and+Trainings): various tech talks, and training materials
- Environments and logins: documents containing links to various qa and staging environments, along with login information.
  - https://docs.google.com/spreadsheets/d/1rfgglp1RsgLZktJNXWiuAD2om0yjdva8S_KZvZu2F6E/
  - https://docs.google.com/spreadsheets/d/1K8Jcpuy5c7-GK1Zr0kdk3AUdKCZby4_pEu7cK3pxlcA/
  - https://docs.google.com/spreadsheets/d/1IxwdVQ4s799EqBr6TEN91OX8QtPcPmtqeCnneQ1Yx4s/
- [Backend dev process](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/101515522/Backend+Development+process): a lightweight document outlining the basics of the backend development process, branching and forking strategy and RFC process.
- [Tips on tickets and tasks](https://pagerinc.atlassian.net/wiki/spaces/EN/pages/154435585/Ticket+Creation+Process): some helpful tips about ticket creation and estimation

### What to expect and accomplish during first week

Starting a new job can be filled with the feeling of uncertainty. Below checklist is aimed at guiding you through your first week at Pager, and helping you keep track of all the things that need to happen during this important period.

**Meetings:**
- [ ] IT Orientation with Mike Bogart
- [ ] Security Orientation with Alexander Miller
- [ ] Pager Orientation with Ryon Burell
- [ ] Meet your Manager
- [ ] Meet your Coding Buddy
- [ ] Command Center shadowing
- [ ] Partake in backend-weekly and demo (Friday 10:45am - 11:30am EST)
- [ ] End of the first week meeting with your manager
- [ ] Platform overview with Jeremiah Bowen [self-scheduled]
- [ ] Application architecture overview with Ryan Hall [self-scheduled]
- [ ] Mobile applications overview with Fabian Celdeiro [self-scheduled]
- [ ] Introduction to QA Team with Jesmin Aktar [self-scheduled]
- [ ] Sprint Planning meeting
- [ ] Sprint Retrospective meeting

**Action items:**
- [ ] Set up NPM account and get access to Pager org (enable 2FA for Authorization and Publishing).
- [ ] Set up local environments
- [ ] Get access to (ask any manager in Engineering):
    - [ ] Jira
    - [ ] Greenhouse
    - [ ] GitHub
    - [ ] GoogleCloud dashboard (Terraform managed, create a PR [forking the repo], adding your email to the right team [here](https://github.com/pagerinc/infra/blob/d6da5570959a23a27fec32d22a17bd8387a8c67d/modules/teams/main.tf))
    - [ ] Sentry
    - [ ] NewRelic
    - [ ] SumoLogic
    - [ ] MixPanel
- [ ] Setup LastPass (IT)
- [ ] Review frontend specific documentation
- [ ] Download example pager app on your device (Reach out to mobile lead Fabian Celdeiro for instructions)
- [ ] Compile a document with questions that you have
- [ ] Make an improvement to the onboarding documentation
- [ ] Join the following Slack channels:
    - [ ] #chapter-backend
    - [ ] #squad-{{your squad's name}} (i.e. #squad-consumer)
    - [ ] #squad-mayday-{{your squad's name}} (i.e. #squad-mayday-consumer)
    - [ ] #eng-war-room
    - [ ] #skunkworks
    - [ ] #product-bugs
    - [ ] #eng-announcements
    - [ ] #engineering
    - [ ] #engineering-product
    - [ ] #status
    - [ ] #releases
    - [ ] #nyc-office
- [ ] Get yourself familiar with the high level architecture: https://whimsical.com/SB3cDuYsM689yMYNoTpGF2
- [ ] Make your Google Calendar visible to all colleagues: https://support.google.com/calendar/answer/37082?visit_id=637257138637539347-1003588718&rd=1


**Expectations for the first a couple months:**
- [ ] submit a PR in the first 2 weeks.
- [ ] release a Jira task/story in the first 2 weeks (board a release train).
- [ ] Get access to the demo app in first 2 weeks.(see instructions below)
- [ ] Get admin and non-admin CC user in all lower level environments in first 2 weeks.
- [ ] Serve as release captain in first 60 days.
- [ ] shadow 2 interviews in first 60 days.

**Download the mobile app:**\
Send your email address to Fabian Celdeiro, who is the mobile manager.
He will add you to the list. Once you get an invitation go to this website. https://appcenter.ms/apps
Download the test app according to you are iPhone or Android


We are excited that you are joining our team, and wish to provide you with an easy and productive onboarding experience. Should you encounter any questions or difficulties at any time, do not hesitate to reach out to your direct manager or designated coding buddy. We are here to help!

Welcome to Pager!
