As part of an academic assignment, I gained practical proficiency in network emulation using Mininet, a powerful tool for creating custom virtual networks. 
This hands-on project allowed me to understand the principles of Software Defined Networking (SDN) by configuring virtual networks with Open vSwitch (OVS) and an SDN controller, POX. Key tasks included:

 - Setting up a custom network topology using Mininet, replicating real-world scenarios.
 - 
 -Configuring network bottlenecks and generating TCP traffic between hosts using tools like "tc" and iperf.

 -Utilizing Wireshark/tcpdump to capture and analyze packet traffic within the virtual network.


(1) custom_topology.py code file creates a custom network topology consisting of hosts, switches, and links, defining the structure of the virtual network environment that can be instantiated and manipulated using Mininet.

(2) script_cwnd_plot.py does the analysis and visualization of congestion window behavior over time for multiple senders, providing insights into network congestion dynamics.

(3) script_pcaps.py analyzes and visualizes the congestion window behavior from TCP packets captured in a pcap file.
