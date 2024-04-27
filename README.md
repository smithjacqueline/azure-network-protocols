# azure-network-protocols
<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
We observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />





<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Creating Resources
- Using Remote Desktop
- Performing Activities on the Network
- Connecting Azure Virtual Machines

<h2>Actions and Observations</h2>

<p>
<img src= https://i.imgur.com/wX0q4nF.jpg height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p> A resource group sets up two virtual computers running Linux and Windows 10, as well as a virtual network and subnet inside of it. A network security group, or NSG, will be connected to the network adapter on Vm1 and Vm2 to ensure that a firewall can examine traffic.
<p>

</p>
<br />

<p>
<img src= https://i.imgur.com/cXXgr1M.jpg  height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>create Windows 10 virtual machine (VM1), use an existing resource group, and confirm that the virtual machines and network are located in the same region. When dealing with the virtual machines, make notes so you remember vital information. Put your login and password, for example, on a notepad.
<p>

</p>
<br />

<p>
<img src=  https://i.imgur.com/1iZFZDe.jpg height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>Your virtual machine (VM) will be tested and used to communicate from the two VMs using its public and private IP addresses. Examine VM1, also utilize the current network for VM 2.
<p>

<p>

</p>
<br />
