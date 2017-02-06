# Azure Site Recovery
This repository contains an updated session around Azure Site Recovery, recorded Jan 2017. 

Azure Site Recovery can protect Hyper-V, VMware and physical servers and you can use Azure or your secondary datacenter as your recovery site.
Your environment can be protected by automating the replication of the virtual machines based on policies that you set and control. Site Recovery coordinates and manages the ongoing replication of data by integrating with existing technologies including System Center and SQL Server AlwaysOn. 
Automate the orderly recovery of services in the event of a site outage at the primary datacenter with Site Recovery. Bring over applications in an orchestrated way to help restore service quickly, even for complex multi-tier workloads. Easily create disaster recovery plans in the Microsoft Azure classic portal, where they are stored. 
The disaster recovery plans can be as simple or as advanced as your business requirements demand, including the execution of custom Windows PowerShell scripts and Azure Automation Runbooks, and pauses for manual interventions. Customize networks by mapping virtual networks between the primary and recovery sites, and test disaster recovery plans whenever you want without disrupting the services at your primary location.
Replicating your workloads to Azure enables new capabilities. Applications can be Migrated to Azure with just a few clicks, or burst to Azure temporarily when you encounter a surge in demand. Run reports and analytics on copies of production workloads in Azure without impacting users. DevTest new versions of applications with copies of live data, and then seamlessly put the new version into production in your datacenter.Site Recovery monitors the state of your protected instances continuously and remotely from Azure. When replicating between two sites you control, your virtual machines’ data and replication remains on your networks. All communication with Azure is encrypted. When replicating to Azure as the secondary site, your data is encrypted and you can also select encryption for data at-rest.

## Presentation
Download the [PowerPoint](https://github.com/AzureCAT-GSI/AzureSiteRecovery/ASR_v012017.pptx)
The PowerPoint includes full speaker notes helping you understand the slides, and everything you need to deliver the session.

    
## Demos
* In the session video recording, we walk you through the initial configuration of Azure Site Recovery Vault, how to enable VM protection on Hyper-V hosts, how to execute a planned and/or unplanned failover. We end the session with sharing some insights on Protection Plans.
[[video](https://azurecatgsicontent.blob.core.windows.net/asr/ASR_Session_Recording.mp4)]

## Session Objectives
In this module, we will cover:

* What is Disaster Recovery, and why it matters 
* What Disaster Recovery features are available in Azure
* Integrating Azure Disaster Recovery features in a typical infrastructure
* Azure Site Recovery in-depth


## Session Prerequisites
* None

## Azure Services Covered
* [Azure Site Recovery](https://www.microsoft.com/OMS)
* [Operations Management Suite - OMS](https://www.microsoft.com/OMS)

## Code of Conduct
This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.


