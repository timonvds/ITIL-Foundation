# Introduction

ITIL enables organizations to:
- Add **value** to work more costefficient
- Improve process **quality** and lower their **cost**
- Manage investments, budget, risk, knowledge,...

**ITIL** = IT Infrastructure Library  
**ITSM** = IT Serivce management is the implementation and management of quality services based on the needs of businesses by a service provider.  
Service = a mean way to deliver value, by delivering outcomes to customers without specific ownership of risks and costs.  
Outcome = the result of carrying out an activity, following a process, or delivering an IT service.
VB Netflix: Outcome = Movies(content) and value = the possibility to watch content everywhere and being independant from local tv stations.  

4 Actions of responses:
1. Accept:
	Acknowledging the risk and accepting the consequences. Has a small chance of happening.
2. Avoid:
	Making sure it will never happen
3. Tranfser:
	Passing on the riks -> Car insurance
4. Mitigate:
	Impact or probability will reduce. Making sure it will do a minimal harm, or a minimal chance of happening.

![Impact and probability matrix](https://www.mindtools.com/media/Diagrams/ImpactProbabilityMatrix.jpg)

Proximity: How far is the risk away of reaching us? Should we act now or do we have some spare time?  

![Service Strategy](https://image.slidesharecdn.com/anintroductiontoservicemanagementitil-110221200422-phpapp02/95/an-introduction-to-service-management-itil-4-728.jpg?cb=1298318694)

**Value:**
Value is created through both: 
- Utility: Fucntionality offered by a service to meet a particular need or achieve a particular outcome. Improving services without having the risk -> AWS: No need to worry about the infrastructure
- Warranty: Assurance that a service will meet its agreed requirements.
		1. Is it available enough?
		2. Has it enough capacity to support desired performance?
		3. Continuous enough?
		4. Secure enough?
		
### Types of services:

- Customer Facing Services = IT Services that are visible to the customer
- Suporting Services = IT Services that support or underpin the customer-facing services

vs

- Core service -> the core feature of the service
- Enabling service -> what enables the core service
- Enhancing service -> What makes the core service more beautiful or attractive

IT service provider = Resources (servers,money,...) + Capabilities(Skills,...) to deliver services.  

### Types of IT Service providers:
	
- Type I: Internal Service Provider
	- Deliver services for one business unit
- Type II: Shared Service Provider
	- Deliver services for multiple business units
- Type III: External Service Provider
	- External party delivering services for one or multiple business units

RACI tabel (Responsible Accountable Consulted Informed)  
![RACI Roles](http://itsmtransition.com/wp-content/uploads/2014/07/Basic-RACI-Roles.jpg)
One person is accountable and one person is being responsible, never multiple of these categories. Combining these categories is possible.  
[RACI Table](RACI.xlsx)

### Generic roles in Service Managemant:

- Service Owner: Person accountable for the service
- Process Owner: Person accountable for the process
- Process Manager: Reviews the process on a daily basis
- Process Practioner: Executes the process

### Stakeholders:

- IT Service Provider
- Customer: Those who buy or fund the service
	1. Internal customers: Within the same business as the IT service provider.
	2. External customers: Outside the IT service provider's business
- User: use the service on a day-to-day basis
- Supplier: Third parties supplying goods or services

### Assets:  

Any resource or capability:
- Resources: 
	- Tangible and direct inputs for production
	- Includes IT infrastructure, people, money or anything else that might help to deliver an IT service
- Capabilities:
	- Intangible and represent an organization's ability to coordinate, control and deploy resources to produce values.
	
Customer asset: Any resource or capability used by a customer to achieve a business outcome
Service asset: Any resource or capability used by a service provider to deliver services to a customer

### Processen:
A structured set of activities designed to accomplish a specific objective.
- Measureable
- Specific result
- Trigger
- Customer

Governance = Instance creating the rules.

### Service management

Process roles:
- Process owner: held accountable for ensuring that a process is fit for purpose. The owner's responsibilities include sponsorship, design, change management and continual improvement of the process. 
- Process manager: Responsible for operational management of a process. Responsibilities include planning and coordination of all activities required to carry out, monitor and report on the process.
- CSI manager: Accountable and responsible for continual service improvement within the organization.
- Service owner: Responsible for managing one or more services throughout the entire lifecycle.

The service lifecycle has:
	- Service Strategy
	- Service Design
	- Service Transition
	- Service Operation
	- Continual Service Improvement

## Why ITIL?
- Best practice
- Non prescriptive
- Vendor neutral

# 2. Service Strategy
- Perspective: covers the overall vision and direction of the organization
- Position: defines how the service provider deals with competition from other players in the market. Specifically, position explains what capabilities and attributes make this service provider unique
- Plans: How the service provider will move from its current state to its desired state. Activities that must be accomplished for a service provider to realize its perspective and positions
- Patterns: Describe repeatable actions that the service provider performs in order to keep progressing towards it strategic objectives
![the four P's service strategy](https://i2.wp.com/www.certguidance.com/wp-content/uploads/2018/02/ITLR0031-ITIL-4ps-of-service-strategy.png?fit=450%2C450&ssl=1)

Types of services: 
- Core: Delivers the basic outcomes desired by one or more customers. Specific level of utility and warranty.
- Enabling: Needed in order to deliver a core service. May or may not be visible to the customer.
- Enhancing: Added to a core service to make it more attractive to the customer.

## Service portfolio management
Value creation
Making sure we have the right mix of services.

1. Service pipeline
	Contains supporting information for all services that are under consideration and might be offered if the organization had unlimited resources, capabilities and funding.
2. Service catalog
	Contains information on the services that are offered or available for deployment.
3. Retired services
	Contains information related to services that were once offered but have now been phased out or retired, as they were no longer necessary or generating value.

## Business relationship management

*'Establish and maintain the relationship between the service provider and the customer.'*  
*'Identify the customer needs and ensure the service provider can meet those needs over time.'*

...

Accounting: Boekhouding
Budgetting: Voldoende geld hebben om de service te kunnen uitvoeren
Charging: Factureren -> Notional charging

## Demand management

Pattern of business activity

# 3. Service Design

Has to be future proof and cost efficient.

- People
- Processes
- Products
- Partners

![the four P's service design](https://image.slidesharecdn.com/itilservicedesign-150314070554-conversion-gate01/95/itil-service-design-3-638.jpg?cb=1426317315)

Five major aspects of design:

1. S - Service solutions
2. T - Tools and technology
3. A - Architecture
4. M - Measurements and metrics
5. P - Processes

## Service design package

Made for every big new addition, modification or removal.
Contains:

	-Requirements
	-Service design
	-Organizational readiness assessment
	-Service lifecycle plan

## Processes in service design

### +.1 Design coordination
...
### +.2 Service catalog management
Ensure the service catalog supports the evolving needs of the other service management processes.
Manage the information in the service catalog.
Ensure the accuracy of the service catalog.
Ensure the availability of the service catalog.

### +.3 Service level management
Management omtrent SLA(Service Level Agreement).
SLA bevat:
-Availability
-Capacity
-Coninuity
-Security
...

SLAM
SLA Monitoring (cursus p3-39)

Conracten binnen(intern) IT service provider = OLA (Operational Level Agreement)

SLA's moeten afgedekt worden door OLA's.
SLA's categoriseren op 3 manieren:
- Service
- Customer
- Multilevel between service and customer

### +.4 Supplier management
Value for money
Manage relationships with suppliers
Manage suppliers performance
Negotiate and agree contracts with suppliers
Maintain a supplier policy
Maintain an SCMIS = Supplier and Contract Management information system
Maakt gebruik van een underpinning contract

![Supplier categorization](https://advisera.com/wp-content/uploads//sites/6/2015/07/Supplier_categorization.png)

### +.5 Availability management
Ensure that the level of availibility delivered matches the agreed availability needs of the business
Doen we op service niveau of op component niveau.

### +.6 Capacity management
Ensures that the level of capacity delivered matches the agreed capacity needs of the business
1. Business capacity management
	How many deals are sold? How many billable hours?
2. Service capacity management
	How many invoices per month?
3. Component capacity management
	Translate the components into invoices.
Proactive vs Reactive

### +.7 IT service continuity management
What if a disaster happens? By nature, fire, black-out,...
DRP = Disaster Recovery Plan
Risk assesments
Business impact analysis

### +.8 Information security management
Ensure CIA of information
Ensure authenticity of business transactions and exchanges

# 4. Service transition
zo hoog mogelijke value voor zo laag mogelijk risico.

## Transition planning and support (TPS)
Provide overall planning for service transitions.
Coordinate the resources that service transitions require.

## Service asset and configuration management (SACM)
Ensure assets required to deliver services are properly controlled.
Ensure accurate and reliable information about service assets exists and is available when and where it is needed.
Understand the relationship between service assets.

Informatie over CI's gaan bijhouden en linken met elkaar.

### Configuration management system (CMS)

Zijn 1 of meerdere cmdb's die op een logische manier met elkaar vebonden zijn.
CMS forms a part of the SKMS (Service knowledge management system) 

Definitive media library: secure storage place.

## Change Management Process
Control the lifecycle of all changes.
Enable beneficial changes.
Minimize the disruption associated with changes.

Types of changes:
1. Normal change
2. Standard change: pre-authorized changes that are low in risk and relatively common.
3. Emergency change: implemented in response to a disruption in service or a potential disruption to services. Greater risk.

**CAB**(change advisory board): Group of people that advise the change manager in the assessment, prioritization and scheduling of changes.  
**ECAB** Emergency advisory board  
**Remediaton planning**: Actions taken to recover after a failed change or release.  

## Release management

Bundelen van changes.  
Pilot release has a release package that has multiple release untis.
...

Early life support: Extra support right after going live with new processes.
Definitive spares: Back-up material.

## Knowledge management
Share perspectives, ideas, experience and information.  
Ensure information assets are available in the right place at the right time.  
Enable informed decision making.  
Reduce the need to rediscover knowledge.  

Aiding in making the right decissions.  
Data becomes information.  
Information becomes knowledge.  
Knowledge becomes wisdom.  

### Service knowledge management system
Has cms's and those cms's has cmdb's.


# 5. Service operation

Can we provide what we agreed upon?
Coordinate and carry out the activity and processes required to deliver and manage services at the agreed-upon levels.
Provide ongoing management of the technology that is used to deliver and support services.

## Event management
**Event**: Any change of state that segnificance for the management of CI or an IT service.
Manage events through their lifecycle.  
Provide the basis for operational monitoring and control.  

Control and automate:
- CI/Service
- Environment
- Licenses
- Security
- Normal activity

Types of events:
1. Informational: Indicating information that can be used for trending and analysis to inform service provider decision making.
2. Warning: Indicating early warning information that can often be leveraged to minimize or prevent any user or business impact.
3. Exception: Indicating abnormal situations or failures that require additional follow-up actions.

**Alert**: When a threshold is passed. Transition from informational to warning. Or from warning to exception. Something happened, failure occured,...

## Incident management
Restore normal service operation asap.  
Minimize the adverse impact on business operations.  

**Incident**: Unplanned interruption to an IT service, or Reduction in the quality of an IT service, or Failure of a CI that has not yet impacted a service.  
**Normal service operation**: The operational state where services and CIs are performing within their agreed service and operational levels.  

Escalation:
	- Fucnctional escalation: Who has the knowladge to fix this issue?
	- Hyrarchical escalation: Who can decide about what we have to do? I need more time, budget,...

## Problem management
Manage the lifecycle of all problems from identification to removal.  
Understand,document and communicate known errors and initiate actions to improve or correct the situation.  
Reactively minimize the adverse impacts of incidents and problems.  
Proactively prevent recurrence of incidents related to errors.  
**Problem**: Underlying cause of one or more incidents.  
