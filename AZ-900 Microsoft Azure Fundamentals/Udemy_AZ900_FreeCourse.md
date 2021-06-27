## Microsoft Azure 900 Fundamentals ##

URL: https://www.udemy.com/course/az-900-azure-tutorial/?ranMID=39197&ranEAID=JVFxdTr9V80&ranSiteID=JVFxdTr9V80-cIxhOU_9IOM25pJZVKK38A&utm_source=aff-campaign&utm_medium=udemyads&LSNPUBID=JVFxdTr9V80

Broken into 3 different parts:

1.  Iaas - infrastructure as a service
2.  Paas - platform as a service
3.  Saas - software as a service

Cloud has extra features that are not available on a normal server

What will be covered:

1.  Scalability 
2.  Performance Improvement
3.  Security
4.  Monitoring

Cloud Computing is an approach to computing that's about having the right resources at the right time, and connecting to a variety of devices and endpoints

Key Concepts of the cloud:

1.  High Availability 
2.  Fault tolerance 
3.  Scalability
4.  Elasticity
5.  Global Reach
6.  Customer Latency Capabilities
7.  Agility
8.  Predictive Cost Considerations
9.  Disaster Recovery
10. Security

There are three different cloud models that organizations can implement from

-   Public cloud

-   This is basically going fully Azure, AWS etc.

-   Private cloud

-   This is where an org has multiple datacenters across multiple geographical locations

-   Hybrid cloud

-   An org having their own datacenters but expanding using Azure, AWS etc.

To understand the public cloud model, you must understand the three types of services (Iaas,Paas,Saas)

Here is a look at who is responsible for what in each model:

**Iaas

You manage:

-   Applications
-   Data
-   Runtime
-   Middleware
-   O/S

Vendor Managers:

-   Virtualization
-   Servers
-   Storage
-   Networking

**Paas

You manage:

-   Applications 
-   Data

Vendor Manages:

-   Runtime
-   Middleware
-   O/S
-   Virtualization
-   Servers
-   Storage
-   Networking

**Saas

You manage:

-   Nothing

Vendor Manages all:

-   Applications
-   Data
-   Runtime
-   Middleware
-   O/S
-   Virtualization
-   Servers
-   Storage
-   Networking

Less control you have, the cheaper it is (Saas cheapest, Iaas most expensive).

---

## Resource Groups

Relies on logical grouping instead of type grouping

When creating a resource group, we can title them with a project name or a client name in order to group them

One project named resource group can have multiple things that are used in the project within it

In RGM - these groupings make it easy to move a RG to another RG or to another subscription

When you delete a RG, it all delete all of the resources that are inside. The delete feature also takes cares of dependancies. So you don't have to delete a database before deleting the full SQL Server.

In the Access Control section, we can associate resource groups to security. I.E. you can provision a user/group to only haves access to certain RGs.

---

## Azure Portal and Cloud Shell

Here is where you can create a resource. You can create just about any resource type possible within the Azure Marketplace.

On the Dashboard page - you can configure it to customize viewing experience to show different meta data about resources.

You can create multiple dashboard views

On the Home view - it gives you options to deal with certain aspects of your services such as viewing/editing subscriptions

Anything with the (classic) text at the end was a legacy item that was brought over from their old cloud model

All resources view - lets you see data in a table such as which group a resource belongs to or which region it is located in.

Azure portal is ultimately a website

Cloud shell - there is an icon at the top that will pop up a terminal like interface where you can use powershell or bash to write scripts

First time opening the cloud shell it will tell you to mount storage. You must first setup Azure storage - this is where you can keep files in the cloud.

You can script anything that can be done by hand in the Azure portal

You can go to [shell.azure.com](http://shell.azure.com) to get a fullscreen view of the cloud shell

---

## Subscriptions and Accounts

Subscriptions - The sum of all Azure services linked to an account

You can view your subscriptions and the meta data like spending limit/usage stats

Multiple RGs are in a subscription

Subscriptions also include accounts like identities in Azure AD, or school or org directory - you can associate these ADs with Azure AD

Azure Subscription can have association with multiple AD

---

## Azure AD

What is it: Universal platform to manage and secure identities

Microsoft has broken down identity into four different sections

1.  Authentication 
2.  Authorization
3.  Administration
4.  Auditing