1. Configuring routing tables on routers ISP1, ISP2 and ISP3. You should only enter routes to remote networks in the routing tables. For example, on Router ISP2 you must specify routes only to the 10.99.25.0/ and 4.25.99.0/24 networks. Network 192.168.0.0 network should not be included into routing table of routers ISP1, ISP2 and ISP3 because it is under NAT. Example configuration of the routing settings on the Router ISP2 is shown in Fig.2.

2. Configuring routing on the wireless Home Router by adding a Default route on Router ISP2, as shown in Fig. 3

3. Check the network operation using ping and tracert.
The last command will check the route of the packet. Figure 4 shows the results of tracert from Client 1 to Web Server 2.
Configuring dynamic routing (optional task)
From the routing tables of the routers ISP1, ISP2 and ISP3 delete the static entries.

5. On routers ISP1, ISP2, and ISP3, configure the RIP protocol by specifying a list of directly connected networks in class format, as shown in Figure 5 for ISP1.

6. Repeat step 3 to check if it works.

