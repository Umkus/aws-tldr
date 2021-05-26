Abstract
This is the summary of the respective AWS white paper, simplified for wider circle of readers.

It goes through the observations of AWS on how cloud was being adopted in multiple companies in the past.

It shares the common actions that led to the effort's success, as well as things to avoid.

AWS Online Tech Talks: How to Build Your Cloud Enablement Engine with the People You Already Have

Establishing CEE
Key goal: transforming the IT organisation from an on-premise operating model to a Cloud Operating Model.

Main focus: Needs of business

Key focus areas:

operations
security and control
platform architecture
governance
provisioning
configuration management
The process is iterative and takes time.

Typical starting point: A lab AWS environment with a handful of applications, to be scaled out as confidence comes.

The first cloud adoption can be achieved within three months.

The whole process can take a year or more.

In the head of the CEE there’s a Cloud Sponsor (executive level).

Required CEE activities
Building the Team
Team should not just have deep technical know-how, but also enough internal political capital.

Typical team size should stay agile: 3-5 people (2-pizza team).

Typical setup:

Operations/cloud architect
Security/network specialist
Cloud Platform Engineer/Scripting
Leader, respected hands-on person
Identify core services that the team will offer (up to 6).

Set goals/metrics/KPIs.

Training and Coaching
This one should be conducted before any other activity below

Identify training gaps

Train internally or using training partners

Workshops, hackathons, immersion days, lunch and learns help

Udemy all the way

Pilot Projects
Select and experiment with a pilot project in a lab environment.

Apply AWS Well Architected Framework

Experiment with with AWS reference architectures, AWS Quickstarts, and AWS Solutions

Document lessons learned into best practice policies

Architecting for the Cloud
Define end state for all AWS environments (dev, test, prod, etc.):

Accounts structure
IAM roles
billing/financial processes
Governance/security/service limits
Refer to AWS Landing Zone and AWS Control Tower

Operating in the Cloud
Define how company should operate:

Infrastructure as code
Version control
Monitoring
Alerting
Notifications
Reporting
Escalation
Financial tracking/auditing
Deployment
Exploring opportunities of other DevOps practices
Refer to the Building a Cloud Operating Model white paper.

Continuous improvement
Project/KPI reviews

Post mortems

Keeping up to date

Automate everything (NoOps) 

Tracking costs

ML for operations, provisioning, alerting and management

Getting Started: Service Offerings
The primary function of the CEE team is to provide an enterprise ready AWS platform that is easily consumable by end-users.

Define security elements:

Standard IAM roles/policies
Security evaluation and enablement
SSO/AD federation
Security groups
Standard AMIs
Account strategy and management
Billing/cost optimisation
VPC
CI/CD toolchain
API platform
Onboarding
Core services
These services should be offered in the first 6 months of CEE team establishment

FinOps
This service offers processes for financial forecasting, monitoring, reporting, optimisation and allocation

Evaluate and recommend most cost-efficient solution

Provide reporting and forecasting dashboards (self-service)

Analyse cloud invoices

Ensure maximum business benefit for minimum cost

Cloud Governance
This service provide policies and practices to help with:

Planning
Architecture
Acquisition
Deployment
Operation
Cloud management
Main focus:

Service Level Objectives
Security policies
Account management
Billing and cost controls
Metrics and KPIs
Compliance to industry standards (PCI-DSS, HIPPA, FedRAMP)
Relevant workloads to be audited from both technical and business side

CEE reports to executives and the board

Migrations
This service provides strategy, methodology and best practices for AWS migration.

Recommends when to do apply 6 REs

Resulted strategy will include:

Portfolio assessment
Architecture review
Security review/strategy
Application migration planning
TCO analysis
Application integration
Deployment
On-going operations
Frameworks to apply:

AWS Migration Portfolio Assessment (MPA)
Experienced Based Accelerators (EBA)
Customer Success Matrix (CSMatrix) framework
Platform Configuration and Optimisation
This service provides guidance to the company of the direction of the overall platform

Typical tasks:

Provision initial AWS environments
Initial account/billing structure
Security, identity and assessment
Logging
Monitoring
Network structure
Create golden-image AMIs
Automate infrastructure deployments
Deploy reference architectures
Use the Well-Architected Framework to provide guidance and drive architecture using data.

Main goals:

Detect recurring architecture patterns
Build up a collection of most effective reference architectures
Promote reuse
Operations
This service is offered for support, maintenance, monitoring and incident management of the cloud platform.

Connect the dots between business and cloud tools/assets.

Responsibilities:

Manage business continuity plan (BCP) and disaster recovery (DR) scenarios
Automate BCP and DR together with Cloud Platform team
Establish support structure/model 
Drive automation and change to existing processes
Create initial on-boarding support
Troubleshoot issues
Help addressing support issues with crowd sourcing
Process and Organisational Change Management
This service drives change across the organisation in a carefully orchestrated manner.

Main focus:

People
Process
Organisational transformation
Create opportunities to organise more efficiently by creating cross-functional DevOps product teams.

Remap organisational structure to take full advantage of the cloud.

Work with stakeholders to plan and rollout the structural changes.

Provide timely and targeted communication of the changes made across the organisation.

Additional Services
The second phase of the CEE typically provides additional services such as:

DevOps Engineering
Site Readability Engineering (SRE)
Automated application deployment and CI/CD tool chain specialist
Cloud Operational Readiness and Cloud ORR support
Pilot/proof of value support
A mature CEE should contain two distinct teams:

CEE - Cloud Business Office (CBO)
PMO
Governance and process
Organisational change management
Connect solutions delivered by CPE with customers (Biz, Dev, Ops) and stakeholders (Fin, HR, EA, Sec)
Cloud Platform Engineering (CPE)
Hands-on doers
Standards as self-service
Enable dev teams to meet governance requirements while accelerating adoption
In the initial creation of the CEE, there will be one CEE organisation.

Considerations
The whole process is not an easy task, it is usually iterative, and typically starts smalls and scales over time

Accelerate with:

Build the correct foundation and processes
Experiment
Fix
Train
Don't overcommit:

Verify that the customers and senior managers have a clear understanding of the timeline.
Define requirements, build, test, and review with key stake holders before committing to migrations/go live.
Patterns for success
Focus on the following for the first 3 months

Executive leadership
Essential to secure right level of organisational support.

Create an Executive Steering Committee:

Made up of C-level executives
Not part of the CEE
Provides guidance
Removes impediments
Ensures CEE creates value
Ensures board-level goals and objectives are targeted
Cloud Steering Committee
Main objectives:

Ensure progress
Remove roadblocks
Challenge status quo
The committee should meet on a weekly/biweekly basis initially.

As the team and processes mature, the meetings can be reduced and eventually eliminated.

Project Management Office (PMO)
Communicate, communicate and then communicate again.

Should not over engineer the communication and information sharing processes.

Goals:

Communicate executive updates across all verticals
Establish cloud communities
Contribute to IT newsletters, lunch-n-learns, internal articles
Communicate best practices
Communicate technical/end-user documentation
Engage in issue resolution across all verticals
Composure: 

Technical scrum masters
Project managers
Inspirations:

Cloud Computing Manifesto
The Enterprise Transformation Community of Practice
Training
The CEE members are the mentors, champions, and key enablers of AWS and cloud awareness and knowledge.

Collaborate with internal training organisations to ensure completion of training of all involved.

Main focus:

Mass awareness
Certifications
Custom workshops
Just in Time (JIT) training
Inspirations:

AWS 100-200 level webinars
AWS Online Tech Talks
AWS Solution Architect certifications
Training executives is critical.

Executives that are part of the steering committee, in particular, need to understand cloud capabilities, services, processes, and tools and methodologies so that they can provide effective support and guidance.

Core CEE team dynamics
CEE team members are:

openminded change agents
tasked with initiating and implementing a fundamental organisational shift
wide spectrum specialists across networking, security, database, development, operations, and program management
hands on
big picture thinkers
utilising cloud services, tools, and technologies to lead business transformation
reporting to one leader (centralised model)
embedded in the lines of business and connected to IT organisation (decentralised model)
Pragmatic, Practical governance
Main focus:

Tagging strategy from day one
Cost optimisation standards
Show back/chargeback,
Identifying and measuring metrics and KPIs
Employ optimisation tools (AWS Trusted Advisor, CloudHealth, CloudCheckr, Cloudability, etc.)
Main tasks:

Compliance through configuration management
Software license management
AWS account management, and billing
IAM policy definition
Implement service limit increase processes
Provide early value
Deliver 2-3 tangible results that drive business value and outcomes in the first 3 months.

Deliver 3-5 small applications:

Drupal, LAMP, or AWS supported ISV SaaS application
Lift-and-shift migrations to AWS that reduce run time and operational costs
Infrastructure-as-code system for AWS
Alternative value demonstration:

Certifications
Creating a FinOps model
Gamification helps

Mandate Well-architected Reviews (WARs)
WARs should be mandatory for all applications running on AWS.

WARs can be executed for on-premises workloads as well.

Practice Operations
Practice incident responses:

AWS GameDays
Netflix Days of Chaos
Community of practice
A.k.a "Guilds" in Spotify and "TFCs" in Amazon/AWS.

Identifies and shares best practices, and supports upskilling and crowdsourcing efforts.

Goals:

Evolve the culture
Federate expertise across silos
Provide safe zones for finding help and sharing issues
Prevent CEE effort stalling
Anti-patterns – Actions to avoid
Believe in build it and they will come
Building the perfect AWS landing zone or cloud monitoring platform does not ensure cloud adoption.

Understand the needs of your clients and provide the services and tools that support those needs.

Ensure CEE backlog is driven by the internal customer’s clearly defined needs and requirements.

Under-estimate the power of middle management
Many decisions during a cloud transformation are made because of political reasons.

The biggest blocker to change, and cloud adoption is buy-in from leaders one level down from executives.

Organisational and culture change
Organisational change is difficult and disruptive, and cultural change takes long to settle.

Do not change your organisational structure without launching cloud projects (e.g. implement a CI/CD pipeline).

This change will force changes to tooling, architecture and technology, and processes, which will focus organisational structure and culture to change.

It took Amazon over 10+ years to change fully change organisational structure and architecture/technology to move to cloud.

Mismatched guardrails
Building too much security for workloads that don’t need it (or the other way around).

Minimal guardrails must always be established at the beginning and are difficult to redo.

Lack of or incomplete upskilling strategy
Common anti-patterns:

Trainings without a hands on experience, leading to illusion of expertise
No trainings
No formal way to share best practices
Increase employee skills via:

meetups
summits
communities of practice
Cloud agnostic tool chains
Over-investment into multi-cloud orchestration.

Just go with AWS head-on.

Build an ivory tower
CEE should be composed with both thinkers and hands-on builders.

All members of CEE team should have direct access to their customers, listen to their needs and build CEE’s backlog based on business requirements.

Staffing the CEE with Enterprise Architects
CEE should not consist just of Enterprise Architects.

Number of Enterprise Architects has a negative correlation to the success of the effort.

Personal credit card usage
This is both a cost and an IP issue.

AWS account must be owned by the company.

Keep the same processes and tools
All cloud consumers are interested in keeping their tools.

Management, audit, compliance teams desire to keep their processes in place.

CEE must communicate to everyone that without process/tooling change the full benefit of the cloud will not be utilised.

Let the CEE become a blocker to cloud adoption
CEE is intended to be an enabler of cloud adoption.

However CEE will become a blocker to cloud adoption if it:

does not produce results
retains the same on-premises operating model processes
becomes the single point of validation for all AWS deployments
Conclusion
A minimal viable product (MVP) approach should be taken to building the CEE team, and its offerings.

Although a fully automated infrastructure and application deployment using CI/CD supported by DevOps engineers may be the ultimate objective, the CEE needs to first establish a foundation architecture with the appropriate security, logging and monitoring, AWS service tagging, infrastructure as code, and a resilient network in place.

The CEE needs to put guard rails in place for the operations of the AWS environment, and establish and govern the metrics and KPIs used to ensure operational excellence.

The service level objectives (SLO) and service level indicators (SLIs) will enable the portfolio companies to measure success, and establish a baseline for continuous improvement.

The CEE will learn, iterate, and provide more capabilities.

There is no compression algorithm for experience.
