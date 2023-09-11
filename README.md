# Connecting-UE-to-5G-of-Open5GS-using-UERANSIM
One of the prominent open-source initiatives in the realm of 5G technology is the Open5GS project, a comprehensive framework that has successfully implemented the core functionalities of 5G through a variety of network functions. In this project, our primary objective is to initiate and visualize the communication flow between these network functions (NFs) in the context of two specific processes, portrayed as a call flow.

In traditional mobile networks, connectivity to the network core typically occurs via the radio access network (RAN). However, due to hardware limitations and constraints, there is a need for a software-based alternative solution.

UERANSIM emerges as a valuable tool within this context, as it adeptly simulates two essential components: the gNB (gNodeB) and UE (User Equipment) by manifesting them as software processes. In this project, we established a connection between a UE and the 5G core infrastructure of Open5GS using the UERANSIM tool. This connection establishment encompasses two critical phases: authentication and PDU (Packet Data Unit) session formation.

To comprehensively validate and monitor these processes, including all network connections established during these phases, spanning from the RAN network to the core infrastructure and among the NFs themselves, it is imperative to leverage network analysis tools, such as WireShark. We visualized these connections in the form of a detailed call flow diagram.
