
# Welcome to OpenPecha R&D


## Q2/2022


## Introduction {#introduction}

The purpose of this document is to provide a sufficiently detailed yet concise overview of the OpenPecha Research and Development (R&D) Department. 

The document starts by explaining the roles, responsibilities, and communication lines of R&D management personnel. It then continues to provide the same details for the various teams inside OpenPecha R&D, such as Application Engineering and Data Engineering and provides a detailed team composition for each team. 

The document then moves on to explain resource allocation principles and processes. The section starts by defining specific terminology used with respect to resource allocation and then explains the types of work where R&D resources can be allocated. Then follows an explanation of the engineering cycle, a period of time during which given work is fulfilled. Next, a detailed description of the various stages from an initial request for work to a fulfilled work order and the aspect of timing is provided. The section ends with an explanation of the way in which the R&D department is assessed.

More information can be requested from [mikko@openpecha.com](mailto:mikko@cavai.com). 


## 1. Management {#1-management}

The team composition of R&D management is as follows: 



* CTO  [Name]
* SVP of Engineering [Name]
* VP of Engineering 
* Add VPs of Engineering as needed


### 1.1. CTO {#1-1-cto}


#### 1.1.1. Responsibilities {#1-1-1-responsibilities}

The CTO’s job can be summarized as “supporting economically viable value creation by means of science and technology”. 

A detailed list of CTO’s responsibilities:



* Application development technology and methodology
* Infrastructure scalability, economics, and integrity
* Data practices, economics, and integrity
* Application, infrastructure, and data security
* Platform integration
* Future solutions discovery and prototyping
* Platform environmental impact
* Research and technology partnerships
* Developer experience
*  R&D staff well-being
*  R&D staff personal/professional development
*  R&D staffing
*  R&D budgeting and relevant financial modeling

The above responsibilities make up the entirety of the responsibilities of the R&D department. In addition, there are CTO-specific responsibilities such as regularly participating in various whole-company activities such as management team meetings and seasonal planning.


#### 1.1.2. Communication {#1-1-2-communication}

The CTO reports to the CEO with additional direct lines to the [Product Owner] and various R&D department participants. The intra-department communication lines are described in the corresponding sections for each team in the R&D department.

Leads of individual R&D teams report to the SVP of Engineering.  [If the CTO acts as the lead of a given R&D team, mention it here]. 


### 1.2. SVP of Engineering {#1-2-svp-of-engineering}


#### 1.2.1. Responsibilities {#1-2-1-responsibilities}

The responsibilities of the SVP of Engineering can be understood in contrast with those of the CTO. For example, whereas the CTO is responsible for the direction, the SVP of Engineering is responsible for overseeing the fulfillment of the direction. Whereas the CTO is responsible for building the team, the SVP of Engineering is responsible for overseeing the team’s activity. And so forth.


#### 1.2.2. Communication {#1-2-2-communication}

The SVP of Engineering has direct lines to the CTO and everyone else in the engineering team. In addition, the SVP of Engineering has direct lines with product team counterparts.


### 1.3. VPs of Engineering {#1-3-vps-of-engineering}


#### 1.2.1. Responsibilities {#1-2-1-responsibilities}

[Here choose between a) Each VP of Engineering is responsible and the owner of the engineering aspect of individual product lines of OpenPecha, or b) VPs of Engineering share the responsibilities of the SVP of Engineering.]


#### 1.2.2. Communication {#1-2-2-communication}

The main direct communication lines of VPs are with their Product Team counterparts, R&D team leads, and the SVP of Engineering.


## 2. R&D Teams {#2-r&d-teams}

Responsibilities are explained below as the main items through which economically viable value creation is supported. Each R&D team is described concerning their specialized responsibilities. \


Currently, the R&D department in OpenPecha consists of [three] teams with their respective functions.



* Application Engineering
* Data Engineering


### 2.1. Application Engineering (4 people) {#2-1-application-engineering-4-people}


#### 2.1.1. Team Composition  {#2-1-1-team-composition}



* Application Engineering Lead (Tenzin)
* Backend Engineer A (Kaldan)
* Backend Engineer B (Lungzang)
* Frontend Engineer A (Kunzang)


#### 2.1.2. Responsibilities {#2-1-2-responsibilities}

The Application Engineering team is responsible for all development and engineering work that directly relates to OpenPecha’s solutions, both visible and not visible. 



* Increase the variety across OpenPecha’s solutions 
* Increase the quality across OpenPecha’s solutions 
* Increase the ease of use across OpenPecha’s solutions 
* Improve the overall experience across OpenPecha’s solutions 
* Improve the energy efficiency across OpenPecha’s solutions 

The Application Engineering team may be split later into separate frontend and backend teams. In which case, it would become Frontend Application Engineering and Backend Application Engineering.


#### 2.1.3. Communication {#2-1-3-communication}

Communication is primarily intra-department, for example, with Infrastructure Engineering (for infra needs) and with VPs of Engineering and the SVP of Engineering. Communication with Product Team counterparts is limited to Request-for-Work (RFW) and  Request-for-Comment (RFC) purposes.


### 2.2. Data Engineering (2 people) {#2-2-data-engineering-2-people}


#### 2.2.1. Team Composition {#2-2-1-team-composition}



* Data Engineering Lead [Tashi Tsering]
* Data Engineer [Topjor]


#### 2.2.2. Responsibilities {#2-2-2-responsibilities}

The Data Engineering team is responsible for all things that relate to data.



* Data integrity
* Increase overall resiliency of data systems
* Maintain data collection and preprocessing integrity
* Increase availability of data throughout the organization
* Increase the ability to recover from catastrophic failures
* Improve the energy efficiency of all data related systems and processes

2.2.3. Communication

Communication is intra-department only. The Data Engineering team resources are allocated through Application engineering. There are no inter-department communication lines, except for exceptional cases when it is necessary and justified. Requests for inter-department communication must go through the SVP of Engineering.


## 3. Resource Allocation {#3-resource-allocation}


### 3.1. Definitions {#3-1-definitions}

Engineering Stages are stages that describe the phase in which a particular product specification is in. There are three stages in total:



* Request for Work (RFW)
* Request for Comments (RFC)
* Work Order (WO)

**Request for Work** is a detailed product specification, which the Product Department submits following a standard template. The shorthand is RFW.

**Request for Comments** is a detailed engineering specification, which R&D Department submits following a standard template, based on the underlying RFW. The shorthand is RFC.

**Work Order** is the final stage before an engineering specification described in the underlying RFC becomes allocated in the next starting Engineering Cycle. The shorthand is WO.

**Work ID** is a single ID that is used to identify connections between various stages in the resource allocation process. The shorthand is WID.

**Engineering Cycle** is a 3-month period during which allocated WOs are fulfilled.

**Stream** is an internal resource allocation observability dashboard. 


### 3.2. Overview  {#3-2-overview}

The R&D Department's resource allocation falls into four categories: 



* Work Orders
* Issue Resolution
* Maintenance and Process Automation
* Experiments


#### 3.2.1 Work Orders {#3-2-1-work-orders}

In any given time window, the great majority of available R&D resources are allocated based on product specifications making their way from an RFW to RFC and reaching the WO  stage. 100% of material changes to OpenPecha solutions result from a given product specification reaching the WO stage. There are no other means to cause material changes to OpenPecha solutions.  As outlined elsewhere in this document, the R&D Department depends on the Product Department for WOs. Related approaches are explained in the below sections.

Any task that is expected to take more than 4 hours to complete, which is most tasks, must be independent RFWs. Smaller tasks are bundled meaningfully into a single thematically consistent RFW. Thematic consistency here refers to how the specifications can be fulfilled by an engineer by working on one part of the system. Specifications for different parts of the system must generally be their own RFW.

There are two acceptable types of RFWs: 



* Type-A which re-arranges or extends something that is already built
* Type-B which creates something entirely new

Mixing the two types of RFWs is strictly prohibited, and RFWs mixing the two types are automatically disqualified from progressing to the RFC stage. It is also not allowed to have two separate RFWs of two different types depending on each other, as that would be the same as having one RFW that mixes two types.

In Type-B RFWs, it’s strictly prohibited to introduce something conceptually new that depends on something else conceptually new, where the concept is not the same for the two new things. Such a case will have to be handled in two separate RFWs, which will be fulfilled one after the other, and the one fulfilled prior to the second one can’t have any dependency, functional, conceptual, or otherwise, with the second one.

A very simple way to think about both types is that they have to be "self-sustained". Each RFW, before it is moved to RFC, has to be able to stand on its own without any other Request being fulfilled.

RFWs must focus on either frontend or backend but can’t be focused on both; when major changes are required in both frontend and backend for a particular product specification, it must be split to separate RFWs (one for frontend and one for backend). In such cases, the frontend-focused RFW can’t be submitted earlier than the underlying non-Frontend RFWs have been processed into RFC.


#### 3.2.2. Issue Resolution {#3-2-2-issue-resolution}

When issues arise and they warrant prompt unplanned action, these will be handled accordingly. Support channels are provided for the purpose of notifying the R&D Department of issues. There are two kinds of issues: 



* Regular issues
* Fires


##### 3.2.2.1. Regular Issues {#3-2-2-1-regular-issues}

Regular issues are handled periodically through the standard resource allocation process described in this section. 


##### 3.2.2.2. Fires {#3-2-2-2-fires}

Fires are issues that require immediate attention. There are three ratings for fires with respect to the severity of the issue: 



* The most severe, marked as: 🔥🔥🔥
* Moderate severity, marked as: 🔥🔥
* Minor severity, marked as: 🔥

The meaning of the severity ratings can be understood as:

- In the case of 🔥, action must be taken promptly, but there is a low probability of an adverse effect on business 

- In the case of 🔥🔥, there is a medium probability of an adverse effect on business 

- In the case of 🔥🔥🔥,  there is a critical threat to the business or imminent threat to one 

Some specific examples of the way in which severity is assessed:

- Any interruption in business-critical services is 🔥🔥🔥

- Any data integrity issue results is 🔥🔥

- Any interruption in data collection results is 🔥🔥🔥

- Any interruption in data integrity monitoring results is 🔥🔥🔥

- Any data leak or other critical security issue results is 🔥🔥🔥

- Any interruption limiting login access to OpenPecha solutions is 🔥🔥

Status updates for fires  are available for fires through [https://status.openpecha.com](https://status.acme.com)


#### 3.2.3. Maintenance and Process Automation {#3-2-3-maintenance-and-process-automation}

R&D Department resources are regularly allocated to various maintenance activities, as well as process automation-related activities. Process Automation allocations mainly focus on improving system visibility and stability, reducing overall operational risk and cost, as well as removing dependency on humans. 

Maintenance and Process Automation priorities are expressed in individual production repositories and the Housekeeping repository in an issue titled “Non-Request Priorities”, each repository having its own issue with this title.


#### 3.2.4. Experiments {#3-2-4-experiments}

R&D Department resources are occasionally allocated to experimenting with new technologies and methods, such as delivery mechanisms, datastores, and other approaches that support the scope of R&D responsibilities.


### 3.3. Engineering Cycle  {#3-3-engineering-cycle}

 \
The Engineering Cycle follows “tik-tok-tik-tok…” model, where each “tik” involves a major fulfillment of something new, and “tok” focuses on improving what has been previously fulfilled. Each cycle lasts three months, following the quarterly calendar. For example, if Q1/2022 is “tok” and focuses on improving previous fulfillments, Q2/2022 will be “tik” focused on fulfilling something entirely new,  or otherwise major thing. 


### 3.4. Process Outline {#3-4-process-outline}


#### 3.4.1. Request Process



1. RFW is submitted on Github (by Product)
2. RFW is evaluated, and various communications may take place
3. RFC is created with a corresponding WID
4. RFC is evaluated, and various communications may take place (by Product)

NOTE: Any changes that result in the evaluation process and various related communications are recorded in the request only if it changes the specification. Both RFW and RFC are for the purpose of a self-contained record of specification and its evolution, not a record of various related communications. 


#### 3.4.2. Work Order Process {#3-4-2-work-order-process}



5. Work becomes mutually agreed (by Product & R&D)
6. There is a seven-day cooling period, during which nothing happens
7. The specification becomes WO is sealed to prevent any alteration
8. WO becomes visible with  stage labeling in Stream

NOTE: Changes beyond the 5th step should be used very sparingly. For most requests, it should never happen. It is there as a fail-safe to avoid serious negative consequences resulting from negligence in the previous steps of the process. 


### 3.5. Timing {#3-5-timing}

It is very difficult to estimate how long a given WO takes to fulfill, and ample time should be reserved for all engineering work. This is particularly true for requests that have a large scope or scope where something that has not been done previously is within the scope. 

The total throughput of the R&D Department can be accelerated by investing in more resources (people) for future WOs, but not outstanding ones. Total throughput can never be accelerated by making more RFWs. This is very important to understand: 

**<span style="text-decoration:underline;">R&D throughput will not increase as a result of making more Requests for Work</span>**

RFWs for the subsequent Engineering Cycle must be submitted at least 45 days before the start of the cycle. So for example, any RFWs that arrive before the 15th of November 2022, will be processed as fulfillment candidates for the Q1/2023 Engineering Cycle.


### 3.6. Quality Assessment {#3-6-quality-assessment}

 \
The efficiency of resource allocation in the R&D department can be objectively evaluated through quality assessment. This is primarily done through the evaluation of two aspects:



* Specification Fulfillment Rate (%)
* Defect Rate (#)


#### 3.6.1. Specification Fulfillment Rate {#3-6-1-specification-fulfillment-rate}

This is to be understood as the overlap between the agreed-up specification, and the completed work. 


#### 3.6.2. Defect Rate {#3-6-2-defect-rate}

This is to be understood in two ways; the number of fulfilled WOs with defects, and the total number of defects per WO. 


## 4. Observability {#4-observability}

The observability of R&D resource allocation can be understood through units of work, which are called **Commits**. Commits are the footprint of the actual work, made at least daily to origin/remote by each developer, and represent everything that has been produced. One or more 

Commits make up **Pull Requests**, which are material changes to the codebase and go through various quality control and other procedures.

 Pull Requests** **make up completed **Work Orders**, which are the actually fulfilled specifications, received from the Product Team. 

The **Engineering Cycle **is made up of Work Orders. The Engineering Cycle consists of works described in Section 3.2. above. 


### 

<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")



### 4.1. Observation Horizons {#4-1-observation-horizons}

Several observation horizons are provided for observability of resource allocation in R&D. The horizons differ mainly in terms of the time window each associates with - from yearly to daily - and in the granularity, each horizon provides - from rough grain to highly granular. The five observation horizons, from the broadest to the most specific are provided below.



* Roadmap
* Engineering Cycle
* Word Order
* Pull Request
* Commit


#### 4.1.1. Roadmap {#4-1-1-roadmap}

The **Roadmap Horizon** provides an annual view of resource allocation. The level of granularity is rough, for example, “[solution] implementation to support [strategic objective]”.

The Product Team maintains the product roadmap.


#### 4.1.2. Engineering Cycle {#4-1-2-engineering-cycle}

The **Engineering Cycle  Horizon** provides a quarterly view of resource allocation. The level of granularity is somewhat more refined than Roadmap Horizon i.e., Engineer Cycle items may be further broken down into Work Orders.

The Engineering Cycle Horizon is visible in Stream. In addition, canonical information about the related Work Orders is available in the corresponding RFWs and RFCs.


#### 4.1.3. Work Order {#4-1-3-work-order}

The **Work Order  Horizon** in terms of the time window it represents depends on the particular Work Order. But generally speaking, the horizon provides a month-to-month view of resource allocation. The level of granularity is somewhat more refined than Engineering Cycle Horizon i.e. Work Order items may be further broken down into Pull Requests.

The Work Order Horizon is visible in Stream. In addition, canonical information about the related Work Orders is available in the corresponding RFWs and RFCs.


#### 4.1.4. Pull Request {#4-1-4-pull-request}

The **Pull Request  Horizon** in terms of the time window it represents depends on the particular Pull Request. But generally speaking, the horizon provides a week-to-week view into resource allocation. The level of granularity is somewhat more refined than Work Order Horizon, i.e., Pull Request items may be further broken down into Commits.

The Pull Request Horizon is visible in Stream. In addition, canonical information about the related Work Orders is available in the corresponding RFWs and RFCs.


#### 4.1.5. Commit {#4-1-5-commit}

The **Commit  Horizon **represents a daily time horizon; developers commit code at least once per day on the Work Orders they are working on. The level of granularity is the highest attainable; Commit items may be further broken down into their actual contents, i.e., the material code contributions associated with the commit.

The Commit Horizon is visible in Stream. In addition, canonical information about the related Work Orders is available in the corresponding RFWs and RFCs.
