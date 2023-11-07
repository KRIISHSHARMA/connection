# COMPUTATION :
- **HOST** : provides the functionality to start and control vms and containers
- **HYPERVISOR** : a program used to run and manage vms on a computer

        - TYPE 1 : RUNS ON BARE METAL
           - XEN
           - KVM
        - TYPE 2 : RUNS ON HOST OS
           - VMWARE
           - ORACLE
 - **VMs** : is a compute resouce that uses software instead of a physical computer 
- **CONTAINERS**
   1. DOCKER
   2. RKT
   3. LXC
   4. PODMAN
  - 
 # NETWORIKNG
 - **OVS**
   - ovs-vswitchd
   - ovsdb-server
 - **LOADBALANCER**
   - LAYER 4 : load balancers act upon data found in network and transport layer protocols (IP, TCP, FTP, UDP).
   - LAYER 7 : load balancers distribute requests based upon data found in application layer protocols such as HTTP.
- **OSI LAYER**
  1. PHYSICAL LAYER
  2. DATA LINK LAYER
  3. NETWORK LAYER
  4. TRANSPORT LAYER
  5. SESSION LAYER
  6. PRESENTATION LAYER
  7. APPLICATION LAYER 
-  **DNS** : turns domain names into IP addresses, which allow browsers to get to websites and other internet resources.
-   **IP Addresss**- Internet Protcol (IPv4,IPv6)
 - Public IP - B/W Internet and Device, assigned by internet service provider to the device
 - Private IP - in a private network [starts with 10., 172.16, 192.168]
 - Local IP - [starts with 127.00.0]
- **Port No.** - a way to identify a specific process to which an internet or other network message is to be forwarded when it arrives at a server.[for http - 80
 - SSH(Secure Shell) - 22
 - SMTP - 25  
 - Telnet - 23
 - https - 443
 - DNS - 53
-  **SSL**- Secure Socket Layer - IP Address + Port Number
-  **overlay network**- An overlay network is a network that is built on top of another network and is supported by its infrastructure. An overlay network decouples network services from the underlying infrastructure by encapsulating one network packet inside of another packet.
-  **underlay network** -the underlay network means all the physical infrastructure that enables frames and packets to be forwarded from o one point to another. In other words, we can understand the underlay networks as the “place” on which it is possible to connect and communicate with networking devices.
-  **cni**- CNI stands for container network interface and it's a specification to configure network interfaces in Linux containers. And it is concerned mainly with adding, connecting and deleting disconnecting containers to networks.
-  **funnel**-Flannel, a project developed by the CoreOS, is perhaps the most straightforward and popular CNI plugin available. It is one of the most mature examples of networking fabric for container orchestration systems, intended to allow for better inter-container and inter-host networking. Flannel is a simple and easy way to configure a layer 3 network fabric designed for Kubernetes.
-  **TUN && TAP**- In computer networking, TUN and TAP are kernel virtual network devices. Being network devices supported entirely in software, they differ from ordinary network devices which are backed by physical network adapters.
  - ***TUN*** :carries ip packets 
  - ***TAP*** :carries ethernet frames
- **veth**- The veth devices are virtual Ethernet devices. They can act as tunnels between network namespaces to create a bridge to a physical network device in another namespace, but can also be used as standalone network devices

# STORAGE :
- **PRIMARY**
  - **RAM**
  - **ROM**
  - **CACHE MEMO**
- **SECONDARY**
  - **HDD**
  - **SDD**
  - **OPTICAL DISK**

# ARCHITECTURE
- **RISC** - Reduced Instruction Set Computer- Closed source - ARM
-  **CISC** - Complex Instruction Set Computer- Closed source - intel, AMD
-  **Von Neumann Architecture**
-  **Hagward Architecture** 
- **ISA** - Instruction Set Architecture - An Instruction Set Architecture (ISA) is part of the abstract model of a computer that defines how the CPU is controlled by the software. The ISA acts as an interface between the hardware and the software, specifying both what the processor is capable of doing as well as how it gets done.
- **system design**
  - **cap theorem** ( consistency , availability , patition tolerance ) : all 3 of them cant be achieved at the same time , 2 have to be chosen based on the requirements
  - **redudancy and replication**
    - makes sure that data has its backup in case of emergency
    - increases reliability

# DATABASE 
- **SQL**
  - structured
  - predefined schema
  - data in rows and column
- **NoSQL**
  - unstructured
  - distributed
  - dynamic schema
-  **HCI**- Hyperconverged infrastructure (HCI) is a software-defined, unified system that combines all the elements of a traditional data center: storage, compute, networking and management.
-  **HCI**- Hyperconverged infrastructure (HCI) is a software-defined, unified system that combines all the elements of a traditional data center: storage, compute, networking and management.

# CACHING
- **application server cache** 





     
