# Introduction

Adding **value** to work more costefficient.  
Improve process **quality** and lower their **cost**.  

**ITIL** = IT Infrastructure Library  
**ITSM** = IT Serivce management is the implementation and management of quality services based on the needs of businesses by a service provider.  
Service = a mean way to deliver value, by delivering outcomes to customers without specific ownership of risks and costs.  
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
	Utility: improving services without having the risk -> AWS: No need to worry about the infrastructure
	Warranty: 
		1. Is it available enough?
		2. Has it enough capacity to support desired performance?
		3. Continuous enough?
		4. Secure enough?

### Types of services:

- Customer Facing Services and Suporting Services

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
- Customer
- User
- Supplier

### Processen:

- Measureable
- Specific result
- Trigger
- Customer

Governance = Instantie die de regels oplegt.

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

- Perspective
- Position
- Plans
- Patterns
![the four P's service strategy](https://i2.wp.com/www.certguidance.com/wp-content/uploads/2018/02/ITLR0031-ITIL-4ps-of-service-strategy.png?fit=450%2C450&ssl=1)

## Service portfolio management
	
Value creation
Zorgen dat we de juiste mix van services hebben.

1. Service pipeline
2. Service catalog
3. Retired services

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

