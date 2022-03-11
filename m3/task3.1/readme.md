1. Create networks as shown in Figure 1. The recommended switch models are Catalyst 2960, the wireless router is WRT300N. In the Data Center network, connect the servers to the ports according to Fig. 1.
![]()
2. In the Enterprise network assign static addresses, formed according to the following rule: Network address 10.Y.D.0/24, where Y is the last two digits of your year of birth, D is your date of birth. The host part of the Client 1 address is 10, Client 2 is 20, DHCP Server is 100. For example, if you were born on April 25, 1999, your network address would be 10.99.25.0/24, and Client 1 would be 10.99.25.10/24
3. Check the connection with ping
4. In the Data Center network assign static addresses, formed according to the following rule: M.D.Y.0/24, where M is the number of the month of birth, D and Y are the same as the previous one. Web Server 1 host part is 50, Web Server 2 host part is 100, DNS Server is 150. So DNS Server address will be 4.25.99.150.
5. Check the connection by using the ping command
6. On the Client 3 computer, replace the Ethernet network adapter with the Wi-Fi module PT-HOST-NM-1W. The result of the successful substitution is the appearance of a wireless connection.
7. Assign a static address of 192.168.0.(D+10) to the Client3. For our example this will be 192.168.0.35.
8. Check the connection to the router using the ping command 192.168.0.1
Additional task: Examination of the packet structure using Wireshark packet analyzer
1. Install and run the Wireshark application.
2. Select the interface to capture traffic (Capture/Interface menu) and
activate capture mode.
3. Copy a file of several tens of Mbytes in size through the network.
4. Finish capturing traffic and switch to analysis mode.
5. Find TCP segment in the captured stream. Make a screenshot of it.
6. In this segment find the headers of the data link, network and transport levels. Highlight them in the screenshot.
7. In each of these headers, find the sender and recipient, the IP addresses of the sender and the recipient, and the port numbers of the sender and
recipient.

