*Use the [Incident Management In-a-Box](https://thehubat.ford.com/docs/DOC-19166) for help with designing and building your incident management process*

*See an [example](IncidentManagementExample.md) of this document filled out*

# Incident Management
The first goal of the incident management process is to restore the service to  normal operation as quickly as possible and to minimize the impact on business operations, thus ensuring that the best possible levels of service quality and availability are maintained. 'Normal service operation' is defined here as service operation within the Service Level Agreement (SLA).

*Team Name* will serve as a single support team made up of Planning, Engineering, and Operations that provides support for the <service/product name>. The support group for this team, within the incident management system, is *support group name*.  

## Table of Contents
[Reporting Incidents](#reporting-incidents) 

[On-call Support for Critical Incidents](#oncall)

[Service Level Agreement (SLA)](#SLA)

[Incident Support Model](#incident-model)

[SACM Requirements](#sacm)

[Incident Management KPIs](#kpi)

[Incident Management Desk Procedures](#desk-procedures)
   - [Desk Procedure 1](#dp1 Anchor)
   - [Desk Procedure 2](#dp2 Anchor)
   - [Desk Procedure N](#dpN Anchor)
	
	

<a name="reporting-incidents"></a>
## Reporting Incidents
Typically, `enter cutomer group here` utilizing the `service/product name` will be the first to raise incidents in case of any failures. 

To report an incident related to <service name> use the [Name of Incident Form](http://www.url-of-incident-form.ford.com) form.
`include any other information related to submitting an incident ticket`

<a name="oncall"></a>
## On-call Support

`service/product team name` team members may be contacted via [CMOS](http://www.tcs.ford.com/cmos/cmos.asp) as needed for warm handoff situations and/or for escalation purposes (e.g. called to support critical incidents).  The call list name is **`CMOS List Name`** and can be found under `CMOS Group/Function Name` -> `CMOS Product/Service Name`.

`Use the following text if it applies to your Service/Product: For weekend critical tickets, which are ONLY for production outages, you may call ITSD or Skype at gsdictrl@ford.com.  ITSD will then contact the On-call Engineer as per CMOS schedule.`

<a name="SLA"></a>
## Service Level Agreement (SLA)
| Priority | TRT* | Coverage| Comments|
| :--- | :--- |:--- |  :--- | 
| Critical| 2 hours |24/7 | `example: Weekends - Oncall Support`|
| High | 24 hours (1 Day)|24/5 (Mon-Fri)|
| Medium | 7 Days|24/5 (Mon-Fri)|
| Low |28 Days |24/5 (Mon-Fri)|

*TRT - Target Resolution Time

<a name="common"></a>
## Common Incidents / Failures
- List out common incidents/failures
- List out common incidents/failures
- List out common incidents/failures

<a name="incident-model"></a>
## Incident Management Support Model
`Provide link to your incident support model process flow and/or include image here`
The [Incident Management Support Model](http://www.url-of-incident-process-flow.ford.com) is a process flow that represents how incidents will be processed, including interactions with other teams as needed.

![alt text](https://link to image file if one exists)

<a name="sacm"></a>
## SACM Requirements
(Coming soon)


<a name="kpi"></a>
## Incident Management KPIs

|KPI|Definition/Measurement|Target: Green|Target: Yellow|Target: Red|
|---|----------------------|:-----------:|:------------:|:----------:|
|% Critical Incidents within TRT|**# of Critical Incidents resolved within TRT** divided by **# Total Critical Incidents**|>=80%|>=70%|<70%|
|% High Incidents within TRT|**# of High Incidents resolved within TRT** divided by **# Total High Incidents**|>=90%|>=80%|<80%|
|% Medium Incidents within TRT|**# of Medium Incidents resolved within TRT** divided by **# Total Medium Incidents**|>=85%|>=75%|<75%|
|% Low Incidents within TRT|**# of Low Incidents resolved within TRT** divided by **# Total Low Incidents**|>=85%|>=75%|<75%|


<a name="desk-procedures"></a>
## Incident Management Desk Procedures
`Link to or include various desk procedures or operating procedures related to incident management.  If you include content, create sub-titles for each procedures`
