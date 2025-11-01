# Connect-Two-PCs-Using-Cross-Cable.md
To understand and demonstrate how to connect two computers directly using a cross (Ethernet) cable and enable communication between them.

Objective:
1)To learn peer-to-peer network connection setup.
2)To assign IP addresses manually.
3)To test network connectivity using the ping command.

Theory:
In a small network setup or lab environment, two computers can communicate directly without using a switch or router.
This type of connection is called a peer-to-peer connection.
A cross cable (Ethernet Crossover Cable) is used because it swaps the transmit (Tx) and receive (Rx) wires, allowing both devices to send and receive data correctly.

Component                        	Description
2 PCs	                          Computers with Ethernet ports
1 Cross Cable	                  To connect both PCs
Operating System    	          Windows / Linux
Command Prompt / Terminal	      For testing connectivity

IP Address Configuration Example:
Device	        IP Address      Subnet Mask
PC1             192.168.1.1      255.255.255.0
PC2             192.168.1.2	     255.255.255.0

Steps:
1) Connect both PCs using the cross cable through Ethernet ports.
2) On each PC:
     a)Go to Network Settings → Change Adapter Options.
     b)Right-click on Ethernet → Properties → IPv4 Settings.
     c)Manually assign IP addresses as shown above.
3) After assigning IPs, open Command Prompt (Windows) or Terminal (Linux).
4) Use the command:
    ping 192.168.1.2     (from PC1 to PC2)
5) If you get a Reply from 192.168.1.2, your connection is successful!

Result:
Both PCs are successfully connected using a cross cable and can communicate directly using IP addresses.

Learning Outcome:
1) Understood peer-to-peer connection concept.
2) Learned to assign manual IP addresses.
3) Verified connectivity using ping command.
4) Gained practical knowledge of cross cable use in networking.
