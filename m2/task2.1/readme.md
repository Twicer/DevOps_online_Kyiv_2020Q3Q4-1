1. What are the most popular hypervisors for infrastructure virtualization?
There are a lot of different hypervisors nowdays with their pros and cons.
I want to list the most popular of them. According to the information that I find in the Internet
XenServer, Hyper-V, KVM and vSphere are the leaders of the virtualization market.

2. Briefly describe the main differences of the most popular hypervisors.
Here yet I want to write about their advantages between each other.
Althought some of them is aimed to specified field like RH KVM for RHEL products and Microsoft Hyper-V 
for Windows servers, there is competitiveness remains. 
I describe only the tip of the iceberg, so we have such results:

Features of Microsoft Hyper-V for Windows Server 2019:

    Persistent memory support.
    Shielded VM updates.
    Simple Two-Node clusters.
    ReFS Deduplication.
    Storage Spaces Direct improvements.
    Windows Admin Center.
    Encrypted subnets.

Features of Red Hat KVM:

    Container support
    Scalability
    Overcommit resources
    Disk I/O throttling
    Hot plug of virtual resources
    Low-cost virtualization solution
    Red Hat Enterprise Virtualization programming & API
    Live Migration & Storage Migration
    Assign any PCI device to virtual machines
    Red Hat Satellite integration
    Disaster Recovery support

Features of VMware vSphere:

    vCenter Server: A centralized management tool used to configure, provision and manage virtual IT environments.
    vSphere Client: vSphere 6.7 has the final version of Flash-based vSphere Web Client. Newer workflows in the updated vSphere Client release includes vSphere Update Manager, Content library, vSAN, Storage policies, Host profiles, VMware vSphere Distributed Switch topology diagram and Licensing.
    vSphere SDKs: Provides interfaces for third-party solutions to access vSphere.
    VM File System: Cluster file system for VMs.
    Virtual SMP: Enables a single VM to use multiple physical processors at a time.
    vMotion: Enables live migration with transaction integrity.
    Storage vMotion: Enables VM file migration from one place to other without service interruption.
    High Availability: If one server fails, VM is shifted to other server with spare capacity to enable business continuity.
    Distributed Resource Scheduler (DRS): Assigns and balances compute automatically across hardware resources available for VMs.
    Fault Tolerance: Generates copy of primary VM to ensure its continuous availability.
    Distributed Switch (VDS): Spans multiple ESXi hosts and enables considerable reduction of network maintenance activities.

Features of Citrix XenServer:

    Site Recovery
    Host Failure Protection
    Multi-server management
    Dynamic Memory Control
    Active Directory Integration
    Role-Based Administration and Control (RBAC)
    Mixed Resource Pools with CPU Masking
    Distributed Virtual Switch Controller
    In Memory read caching
    Live VM migration & Storage XenMotion 
