uSavings - User Manual
======================

Imagem 01

Information technology solutions that make it possible to implement a scalable, solid and reliable computing architecture in a hybrid cloud.

Introduction
==================
This document aims to introduce the main characteristics and functionalities related to the uSavings application.

In this Manual are introduced concepts, screens, functionalities and commands for this product usage.

Vision and positioning
======================

This document describes the uSavings application, the vision and the product positioning. It’s important to clarify that it’s found in constant development and evolution, because of that, the screens shown in this document may change at any moment, due to the software evolution.

The present trend, increasingly stronger, from computacional resources migration of private clouds or co-location environment, to the provider’s environment in public cloud, represents one of the greatest challenge of organizations that is the Cost Governance originated from the high use of those computacional resources and, consequently, the companies can’t obtain the due visualization of those costs in the future.

Nowadays, almost the entirety of the Cloud Service Broker (CSB) platforms can present cost reduction suggestions, however, obtaining some values is dependent on a human service (or action), to obtain such values.

The public cloud’s service providers, continually and uninterruptedly, make new hardware configurations (flavors) available with similar characteristics, but values, sometimes, very different. At this point, it is up to the architecture specialist to search for possible and compatible hardware configurations.

The uSavings Platform completes these activities automatically so that the hardware comparison configurations and/or recurring costs can be presented in a clearer way to this platform user.

The uSavings Platform, obtains the inventory of all the public cloud computational resources through its interaction with the uCloud Platform. Therefore, the list of server computational resources presented in the uSavings Platform interface is a faithful representation of your environment found in the public cloud service provider, thus, the existing reality in your environment.

All the alternative options of hardware configurations are informed as **suggestions**, as it is up to the user to change (reconfigure) the hardware of the computational resource (flavor) at the best time for their environment.

It’s important to highlight that the uSaving Platform will only present **suggestions**, since any change of hardware configuration (flavor) can only be effectuated with the turned off infrastructure (cold), that way, the user must manage the best moment (day and time) to act in that configuration change.

The integration with the uCloud Platform allows the user to visualize the suggestions presented in the uSavings Platform interface, so it is possible to correctly identify the computacional resource, and, through the uCloud Platform, execute the task of changing hardware configuration (flavor) directly in the public cloud provider’s environment, without the user needing to be logged into the public cloud provider’s console.

What is uSavings?
-----------------

The uSavings is a tool that analyzes the computacional resources infrastructure consumption in real time (of Virtual Machines - VMs) in different clouds, it is through this analysis that the application recommends changes. In case an organization supports this suggestion, such a decision could generate the maximum financial economy and optimization of resources created and/or executed. The application uSavings is a cost advisor, that is, a cost consultant that allows to advise the user how to reduce the costs in its infrastructure, ticketed through uCloud Platform, in the multiple cloud services providers - AWS, Azure, Google, IBM and VMWare. 

How does it work?
-----------------

The uSavings Platform, besides obtaining data from several clouds, extracts information from the historical data of the Virtual Machine itself and from the ticketing of each public cloud provider - this data gathering is started by the integration to the uCloud Platform. The application presents a consolidated panel and customer spending suggestions in each cloud provider, delivering precise information for the best decision making on the allocated costs of organization’s infrastructure resources. 

Imagem 2

The figure above represents the uSavings organizational chart: there, the uCloud Virtual Machine, is one of the main elements in this flow, according to the diagram above. The following element is introduced as Flavor, it makes it possible to know how much memory, vCPU and other resources are used by the machine. Therefore, according to Flavor we know how much a certain machine will cost at the end of the month. With this data, it is possible for the uSavings Platform to suggest the customer resources economy to the monthly invoice.

Imagem 3

The cutout in the organogram highlights the relevant part of the diagram, it represents the uSavings application’s suggestive form. There are two ways to recommend improvements to certain Virtual Machines: (i) by Flavor and (ii) by Billing.

* **By Flavor** - The uSavings checks the allocated Flavor in the machine and suggests an upgrade possibility - this improvement is related to cost benefit - the application publishes the results in several formats (graphs or percentage) and it shows which will be the best cloud to be used to save resources, for the VM. This parameter, by deduction, understands that the machine is on all the time.

* **By Billing** - The ticketing from the uCloud database supports several clouds, it differs from the scope of uSavings application. The uCloud database can support all types of billing available. In the uSavings business rule, though, it’s only possible to make an assertive suggestion with the billing for AWS and AZURE, as shown in the diagram, in the figure cutout of the organizational chart, shown above this paragraph.

How to save resources?
----------------------

The advantage of implementing uSavings in the organizations is the possibility of receiving information about ocious resources that were created, and even, previously executed, currently not used. Information that can make it possible to save resources.

The fact that the uSavings application is a tool that analyzes the computacional resources infrastructure consumption in real time in the different clouds, the uSavings application shows the ocious resources created.

The tool is relevant for decision making in organizations, because when analyzing the information obtained by the application, it delivers real results. This contributes to an organizational decision capable of generating the financial economy and optimization of resources created and/or executed.

The uSavings can referenciate to configuration reduction suggestions - rightsizing of virtual machines, in case they were previously created with “super configurations” and/or present a low consumption in the performance history. It **directs** the possibility of increasing the cost-consumption ratio, the application does **not execute it**. The uSavings Platform implementation objective is to indicate to the organization the possibility and/or the path to increase its cost savings, in the next charge period of the cloud service provider.

.. attention:: The information equipped organization, delivered by the uSavings application, must be in touch with the service cloud provider about “rightsizing”.

By acquiring the uSavings Platform, the organizations can have in hands a valuable strategic and Business Intelligence (BI) tool that indicates the best way to enlarge the relation cost-benefit of its virtual infrastructures and, also, the best way to maximize the resources of virtual machines created in the service cloud providers.

Optimizations recommended after monitoring
------------------------------------------

The following four optimizations can be proposed based on suggestions of:

Rightsizing:
------------

It consists of suggesting the best combination of CPU and memory, with the objective to minimize the costs and maximize the performance. The tool collects performance metrics to determine the average and maximum resources consumption of an instance over a configurable time period and recommends a modification for a configuration of a virtual machine configuration or of appropriate configuration for the project.

Comparative Costs:
------------------

