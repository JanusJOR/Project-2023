# The Services Infrastructure # 

At the start of any new system build, a minimum service infrastructure is required to bootstrap. 
Where performance is not a requirement, it is convenient to create servers and services in virtual environments. 
At time of installation, this was based on available hardware in the University teaching data center. 
The Kay McNulty data center (kmn.ie) is located at room PR2294, ATU Letterkenny. 
The physical cabinet layout is described in the section, ![Physical Location](PhysicalLocation.md). 
The racks are two rows of five 19” cabinets, bayed together, with hot-aisle containment.
An existing Dell R440 has been reallocated to provide the services infrastructure for this project. 
Windows Server 2019 has been installed with hyper V, and this is described in the section, Virtualization Infrastructure.
At the security core of any infrastructure, centralized authentication authorization and accounting (AAA) is generally specified. 
After discussions relating to the PowerScale infrastructure, it was decided to add an Active Directory domain for the project. 
A series of virtual machines has been created to provide the necessary services. 
These are detailed in the section Authentication Authorization and Accounting.

A PC has been allocated as a jump server, connected to a plasma screen at the data centre.
This is bigscreen.janus.kmn.ie
