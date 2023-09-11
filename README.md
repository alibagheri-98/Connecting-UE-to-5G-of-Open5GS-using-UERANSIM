# Connecting-UE-to-5G-of-Open5GS-using-UERANSIM
One of the prominent open-source initiatives in the realm of 5G technology is the Open5GS project, a comprehensive framework that has successfully implemented the core functionalities of 5G through a variety of network functions. In this project, our primary objective is to initiate and visualize the communication flow between these network functions (NFs) in the context of two specific processes, portrayed as a call flow.

In traditional mobile networks, connectivity to the network core typically occurs via the radio access network (RAN). However, due to hardware limitations and constraints, there is a need for a software-based alternative solution.

UERANSIM emerges as a valuable tool within this context, as it adeptly simulates two essential components: the gNB (gNodeB) and UE (User Equipment) by manifesting them as software processes. In this project, we established a connection between a UE and the 5G core infrastructure of Open5GS using the UERANSIM tool. This connection establishment encompasses two critical phases: authentication and PDU (Packet Data Unit) session formation.

To comprehensively validate and monitor these processes, including all network connections established during these phases, spanning from the RAN network to the core infrastructure and among the NFs themselves, it is imperative to leverage network analysis tools, such as WireShark. We visualized these connections in the form of a detailed call flow diagram.

In 'ZSteps.pdf', we will first delve into the preparation of the Open5Gs project. This project aims to create an implementation of the core network for 5G, enabling the establishment of a 5G network. To evaluate the progress of this project, access to the network access radio (Network Access Radio) is essential, which is achieved through the use of the UERANSIM simulator, transforming it into a 5G network RAN.

The operating system employed in these projects is Ubuntu, with Open5Gs mandating version 16.04 and higher. At this stage, the implementation involves the use of two distinct virtual machines (VMs) for the Core and RAN components. In cases where your system lacks sufficient RAM to support both VMs concurrently, it is advisable to consider utilizing Lubuntu as an alternative to Ubuntu, as it consumes significantly fewer system resources. Please note that when installing Lubuntu, you may encounter an issue where the screen is not displayed in full size. To resolve this, you can search for 'VM install tools' on the internet and follow the provided instructions to address the problem.

Based on these definitions, we will set up two Lubuntu 18.04 virtual machines, named VM1 and VM2. VM1 will host the network core (Open5Gs), while VM2 will host the access network (UERANSIM). Initially, allocate 2 GB of memory to each VM during the operating system and tools installation process. Start by installing them sequentially, one at a time, and subsequently run both VMs simultaneously. Afterward, you can reduce the memory allocation for each VM to 1GB. Additionally, allocate 20GB of storage space for VM1 and 40GB for VM2.

Using these definitions, we will create two Lubuntu 18.04 virtual machines named VM1 and VM2. VM1 is designated to host the network core using Open5Gs, while VM2 serves as the access network running UERANSIM. During the initial setup, allocate 2 GB of memory to each VM. Follow these steps for installation: set up the operating system and tools individually on each VM, and then proceed to run both VMs simultaneously.
