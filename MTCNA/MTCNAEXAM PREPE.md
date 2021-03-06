SET 1

1. A network ready device is directly connected to a MikroTik RouterBOARD 750 with a correct U.T.P. RJ45 functioning cable. The device is configured with an IPv4 address of 192.168.100.70 using a subnet mask of 255.255.255.252. What will be a valid IPv4 address for the RouterBOARD 750 for a successful connection to the device?
```bash
a. 192.168.100.70/255.255.255.252
b. 192.168.100.69/255.255.255.252
c. 192.168.100.71/255.255.255.252
d. 192.168.100.68/255.255.255.252
````

2. In MikroTik RouterOS, Layer-3 communication between 2 hosts can be achieved by using an address subnet of:
```
a. /31
b. /29
c. /32
d. /30
```
3. Which computers would be able to communicate directly (without any routers involved)
a. 192.168.17.15/29 and 192.168.17.20/28
b. 192.168.0.5/26 and 192.168.0.100
c. 10.5.5.1/24 and 10.5.5.100/25
d. 10.10.0.17/22 and 10.10.1.30/23

4. How many IP addresses can one find in the header of an IP packet?
a. 1
b. 3
c. 2
d. 4

5. The network address is
a. The first usable address of the subnet
b. The last address of the subnet
c. The first address of the subnet

6. What is term for the hardware coded address found on an interface?
a. IP Address
b. MAC Address
c. FQDN Address
d. Interface Address

7. How many usable IP addresses are there in a 23-bit (255.255.254.0) subnet?
a. 512
b. 510
c. 508
d. 254

8. Is ARP used in the IPv6 protocol ?
False
True


9. Which of the following protocols / port s are used for SNMP. (Simple Network Management Protocol)
a. TCP 162
b. UDP 162
c. UDP 161
d. TCP 25
e. TCP 123
f. TCP 161

10. If ARP=reply-only is configured on an interface, what will this interface do
a. Accept all IP/MAC combinations listed in /ip arp as static entries
b. Accept all IP addresses listed in /ip arp as static entries
c. Add new MAC addresses in /ip arp list
d. Accept all MAC-addresses listed in /ip arp as static entries
e. Add new IP addresses in /ip arp list

11. Select which of the following are ‘Public IP addresses’:
a. 192.168.0.1
b. 172.168.254.2
c. 172.28.73.21
d. 10.110.50.37
e. 11.63.72.21

12. Which of the following IP addresses are publicly routable?
a. 127.34.155.3
b. 192.168.1.4
c. 172.16.13.23
d. 11.3.10.4

13. If ARP=reply-only is enabled on one router interface, router can add dynamic ARP entries for the particular interface.
False
True

14. The basic unit of a physical network (OSI Layer 1) is the:
a. Header
b. Byte
c. Bit
d. Frame

15. Which ones of the following are valid IP addresses?
a. 192.168.13.255
b. 10.10.14.0
c. 192.168.256.1
d. 1.27.14.254

16. How many usable IP addresses are there in a 20-bit subnet?
a. 2046
b. 2047
c. 4094
d. 4096
e. 2048

17. Which of the following is NOT a valid MAC Address?
a. 13:16:86:53:89:43
b. 80:GF:AA:67:13:5D
c. 88:0C:00:99:5F:EF
d. EA:BA:AA:EE:FF:CB
e. 95:B5:DD:EE:78:8A


18. MAC layer by OSI model is also known as
a. Layer 3
b. Layer 7
c. Layer 1
d. Layer 2
e. Layer 6

19. Select valid MAC-address
a. G2:60:CF:21:99:H0
b. 00:00:5E:80:EE:B0
c. AEC8:21F1:AA44:54FF:1111:DD
d. AE:0212:1201
e. 192.168.0.0/16

20. How many layers does Open Systems Interconnection model have?
a. 7
b. 6
c. 5
d. 12
e. 9 

------------------------------------------------------------------------------------- SET - 2 -------------------------------------------------------------------------------------
 

1. Action=redirect is applied in
a. chain=srcnat
b. chain=dstnat
c. chain=forward

2. You have 802.11b/g wireless card. What frequencies are available to you?
a. 5800MHz
b. 2412MHz
c. 5210MHz
d. 2422MHz
e. 2327MHz

3. Mark all correct statements about /export (rsc file).
a. Exports logs from /log print
b. Exports full configuration of the router
c. Exports only part of the configuration (for example /ip firewall)
d. Exports scripts from /system script
e. Exports files could not edited

4. What wireless card can we use to achieve 100 Mbps actual wireless throughput?
a. 802.11 b/g
b. 802.11 a/b/g
c. 802.11 a
d. 802.11 a/n
e. 802.11 a/b/g/n

5. It is possible to add user-defined chains in ip firewall mangle
True
False

6. Choose all valid hosts address range for subnet 15.242.55.62/27
a. 15.242.55.31-15.242.55.62
b. 15.242.55.32-15.242.55.63
c. 15.242.55.33-15.242.55.62
d. 15.242.55.33-15.242.55.63

7. Action=redirect allows you to make
a. Transparent DNS Cache
b. Forward DNS to another device IP address
c. Enable Local Service
d. Transparent HTTP Proxy

8. Which is correct masquerade rule for 192.168.0.0/24 network on the router with outgoing interface=ether1?
a. /ip firewall nat add action=masquerade chain=srcnat
b. /ip firewall nat add action=masquerade chain=srcnat src-address=192.168.0.0/24
c. /ip firewall nat add action=masquerade out-interface=ether1 chain=dstnat
d. /ip firewall nat add action=masquerade chain=srcnat out-interface=ether1

9. What letters appear next to a route, which is automatically created by RouterOS when user adds a valid address to an active interface?
a. I
b. D
c. A
d. S
e. C

10. Mark all features that are compatible with Nstreme
a. WDS between a device in station-wds mode and a device in station-wds mode
b. Encryption
c. WDS between a device in ap-bridge mode with a device in station-wds mode
d. Bridging a device in station mode with a device in ap-bridge mode

11. Can you manually add drivers to RouterOS in case your PCI Ethernet card is not recognized, and it’s a driver issue?
a. Yes
b. No

12. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package:
a. none
b. dhcp
c. routing
d. advanced-tools

13. Which are necessary sections in /queue simple to set bandwidth limitation?
a. target-address, max-limit
b. target-address, dst-address, max-limit
c. target-address, dst-address
d. max-limit

14. What protocol is used for Ping and Trace route?
a. DHCP
b. IP
c. TCP
d. ICMP - ping
e. UDP – trace route

15. From which of the following locations can you obtain Winbox?
a. Router’s webpage
b. Files menu in your router
c. Via the console cable
d. mikrotik.com

16. Two hosts, A and B, are connected to a broadcast LAN. Select all the answers showing pairs of IP address/mask which would allow IP connections to be established between the two hosts.
a. A: 10.1.2.66/25 and B: 10.1.2.109/26
b. A: 10.2.2.1/23 and B: 10.2.0.1/22
c. A: 10.1.2.192/24 and B: 10.1.2.129/26
d. A: 10.2.1.0/23 and B: 10.2.0.1/22

17. Why is it useful to set a Radio Name on the radio interface?
a. To identify a station in a list of connected clients
b. To identify a station in the Access List
c. To identify a station in Neighbor discovery

18. What kind of users are listed in the Secrets window of the PPP menu?
a. pptp users
b. l2tp users
c. winbox users
d. wireless users
e. pppoe users
f. hotspot users

19. Router A and B are both running as PPPoE servers on different broadcast domains of your network. Is it possible to set Router A to use “/ppp secret” accounts from Router B to authenticate PPPoE customers ?
Yes
No

20. MikroTik RouterOS DHCP client can receive following options
a. Byte limit
b. IP Gateway
c. Rate limit
d. Uptime limit
e. IP Address and Subnet

------------------------------------------------------------------------------------- SET - 3 -------------------------------------------------------------------------------------
 

1. If you need to make sure that one computer in your HotSpot network can access the Internet without HotSpot authentication, which menu allows you to do this?
a. Users
b. IP bindings
c. Walled-garden
d. Walled-garden IP

2. How many different priorities can be selected for queues in MikroTik RouterOS?
a. 8
b. 16
c. 0
d. 1

3. Which default route will be active? /ip route add disabled=no distance=10 dst-address=0.0.0.0/0 gateway=1.1.1.1 add disabled=no distance=5 dst-address=0.0.0.0/0 gateway=2.2.2.2
a. Route via gateway 1.1.1.1
b. Route via gateway 2.2.2.2

4. How long is level 1 (demo) license valid?
a. 24 hours
b. Infinite time
c. 1 month
d. 1 year


5. Is ARP used in the IPv6 protocol ?
True
False

6. In MikroTik RouterOS, Layer-3 communication between 2 hosts can be achieved by using an address subnet of:
a. /30
b. /29
c. /32
d. /31

7. A PC with IP 192.168.1.2 can access internet, and static ARP has been set for that IP address on gateway. When the PC Ethernet card failed, the user change it with a new card and set the same IP for it. What else should be done? [multiple answers]

a. Old static ARP entry on gateway has to be updated for the new card
b. Nothing – it will work as before
c. MAC-address of the new card has to be changed to MAC address of old card
d. Another IP has to be added for Internet access

8. How many usable IP addresses are there in a 20-bit subnet?
a. 2047
b. 4096
c. 2048
d. 2046
e. 4094

9. What is the default TTL (time to live) on a router that an IP packet can experience before it will be discarded ?
a. 60
b. 30
c. 1
d. 64

10. The network address is
a. The first usable address of the subnet
b. The last address of the subnet
c. The first address of the subnet

11. Which ones of the following are valid IP addresses? [multiple answers] 

a. 192.168.13.255
b. 1.27.14.254
c. 10.10.14.0
d. 192.168.256.1

12. Which of the following is NOT a valid MAC Address?
a. 95:B5:DD:EE:78:8A
b. 13:16:86:53:89:43
c. 80:GF:AA:67:13:5D
d. 88:0C:00:99:5F:EF
e. EA:BA:AA:EE:FF:CB

13. If ARP=reply-only is configured on an interface, what will this interface do
a. Add new IP addresses in /ip arp list
b. Accept all IP/MAC combinations listed in /ip arp as static entries
c. Accept all MAC-addresses listed in /ip arp as static entries
d. Add new MAC addresses in /ip arp list
e. Accept all IP addresses listed in /ip arp as static entries

14. What is term for the hardware coded address found on an interface?
a. IP Address
b. Interface Address
c. MAC Address
d. FQDN Address

15. Which of the following IP addresses are publicly routable?
a. 127.34.155.3
b. 192.168.1.4
c. 172.16.13.23
d. 11.3.10.4

16. What protocol does ping use?
a. UDP
b. TCP
c. ARP
d. ICMP

17. MAC layer by OSI model is also known as
a. Layer 3
b. Layer 7
c. Layer 2
d. Layer 6
e. Layer 1

18. How many layers does Open Systems Interconnection model have?
a. 12
b. 6
c. 9
d. 5
e. 7


19. How many IP addresses can one find in the header of an IP packet?
a. 3
b. 4
c. 1
d. 2

20. The basic unit of a physical network (OSI Layer 1) is the:
a. Byte
b. Frame
c. Bit
d. Header

------------------------------------------------------------------------------------- SET - 4 -------------------------------------------------------------------------------------
 

1. You have a router with configuration
- Public IP :202.168.125.45/24
- Default gateway:202.168.125.1
- DNS server: 248.115.148.136, 248.115.148.137
- Local IP: 192.168.2.1/24
Mark the correct configuration on client PC to access to the Internet
a. IP:192.168.0.1/24 gateway:192.168.2.1
b. IP:192.168.2.253/24 gateway:202.168.0.1
c. IP:192.168.1.223/24 gateway:248.115.148.136
d. IP:192.168.2.115/24 gateway: 192.168.2.1
e. IP:192.168.2.2/24 gateway:202.168.125.45

2. On the advanced menu of the wireless setup there is a parameter called “Area”, it works directly with:
a. Connect List
b. Access List
c. None of these
d. Security Profile

3. What menus should be used to allow certain websites to be accessed from behind a hotspot interface, without client authentication
a. ip hotspot ip-binding
b. ip hotspot profile
c. ip hotspot walled-garden
d. ip hotspot walled-garden ip

4. You want to use PCQ and allow 256k maximum download and upload for each client. Choose correct argument values for the required queue.
a. kind=pcq pcq-limit=1256000 pcq-classifier=dst-address
b. kind=pcq pcq-limit=256000 pcq-classifier=dst-address
c. kind=pcq pcq-limit=5000000 pcq-classifier=src-address
d. kind=pcq pcq-limit=256000 pcq-classifier=src-address
e. kind=pcq pcq-limit=5000000 pcq-classifier=dst-address

5. Which of the following is true for connection tracking
a. Enabling connection tracking reduces CPU usage in RouterOS
b. Connection tracking must be enabled for firewall to be effective
c. Connection tracking must be enable for NAT’ed network
d. Disable connection tracking for mangle to work

6. Which of these are possible solutions to bridge two networks over a wireless link:
a. Both devices in AP mode and enable WDS mode
b. One device in AP mode, another one in station-pseudobridge-clone
c. One device in AP mode, another one in station-pseudobridge
d. One device in AP mode, another one in station

7. When backing up your router by using the ‘Export’ command, the following happens:
a. Winbox usernames and passwords are backed up
b. The Export file can be edited with a standard text editor after its creation
c. You are requested to give the export file a name

8. You need to reboot a RouterBoard after importing a previously exported rsc file to activate the new configuration.
True
False

9. It is impossible to disable user “admin” at the menu “/user”
True
False

10. If a packet comes to a router and starts a new, previously unseen connection, which connection state would be applied to it?
a. no connection state would be applied to such packet
b. new
c. unknown
d. invalid
e. established

11. We have two radio cards in a point-to-point link with settings:
Card Nr 1.: mode=ap-bridge ssid=”office”
frequency=2447 band=2.4ghz-b/g default-authentication=yes default-forwarding=yes security-profile=wpa
Card Nr 2.: mode=station ssid=”office”
frequency=2412 band=2.4ghz-b/g default-authentication=yes default-forwarding=yes security-profile=wpa2
Is Card Nr2. able to connect to Card Nr 1.?
a. Yes, if Nstreme is enabled or disabled on both
b. Yes, when security profile settings are compatible with each other and Nstreme is enabled or disabled on both
c. No, because of the different frequencies
d. No, because of the different security profiles

12. If you need to make sure that one computer in your HotSpot network can access the Internet without HotSpot authentication, which menu allows you to do this?
a. Walled-garden IP
b. Walled-garden
c. Users
d. IP bindings

13. Consider the following network diagram. In R1, you have the following configuration:
/ip route
add dst-address=192.168.1.0/24 gateway=192.168.99.2
/ip firewall nat
add chain=srcnat out-interface=Ether1 action=masquerade

On R2, if you wish to prevent all access to a server located at 192.168.1.10 from LAN1 devices, which of the following rules would be needed?
a. /ip firewall filter add chain=forward src-address=192.168.99.1 dst-address=192.168.1.10 action=drop
b. /ip firewall filter add chain=input src-address=192.168.99.1 dst-address=192.168.1.10 action=drop
c. /ip firewall nat add chain=dstnat src-address=192.168.99.1 dst-address=192.168.1.10 action=drop
d. /ip firewall filter add chain=forward src-address=192.168.0.0/24 dst-address=192.168.1.10 action=drop

14. What is the default protocol/port of (secure) winbox?
a. UDP/5678
b. TCP/8291
c. TCP/22
d. TCP/8080

15. Mark the queue types that are available in RouterOS
a. SFQ – Stochastic Fairness Queuing
b. DRR – Deficit Round Robin
c. FIFO – First In First Out (for Bytes or for Packets)
d. LIFO – Last In First Out
e. PCQ – Per Connection Queuing
f. RED – Random Early Detect (or Drop)

16. A network ready device is directly connected to a MikroTik RouterBOARD 750 with a correct U.T.P. RJ45 functioning cable. The device is configured with an IPv4 address of 192.168.100.70 using a subnet mask of 255.255.255.252. What will be a valid IPv4 address for the RouterBOARD 750 for a successful connection to the device?
a. 192.168.100.70/255.255.255.252
b. 192.168.100.69/255.255.255.252
c. 192.168.100.71/255.255.255.252
d. 192.168.100.68/255.255.255.252

17. How many usable IP addresses are there in a 23-bit (255.255.254.0) subnet?
a. 512
b. 510
c. 508
d. 254

18. Is ARP used in the IPv6 protocol ?
True
False

19. Which of the following protocols / port s are used for SNMP. (Simple Network Managemnt Protocol)
a. TCP 162
b. UDP 162
c. UDP 161
d. TCP 25
e. TCP 123
f. TCP 161

20. Select which of the following are ‘Public IP addresses’:
a. 192.168.0.1
b. 172.168.254.2
c. 172.28.73.21
d. 10.110.50.37
e. 11.63.72.21

21. If ARP=reply-only is enabled on one router interface, router can add dynamic ARP entries for the particular interface.
False
True

22. MAC layer by OSI model is also known as
a. Layer 3
b. Layer 7
c. Layer 1
d. Layer 2
e. Layer 6

23. Select valid MAC-address
a. G2:60:CF:21:99:H0
b. 00:00:5E:80:EE:B0
c. AEC8:21F1:AA44:54FF:1111:DDAE:0212:1201
d. 192.168.0.0/16

24. Which computers would be able to communicate directly (without any routers involved)
a. 192.168.17.15/29 and 192.168.17.20/28
b. 192.168.0.5/26 and 192.168.0.100
c. 10.5.5.1/24 and 10.5.5.100/25
d. 10.10.0.17/22 and 10.10.1.30/2


------------------------------------------------------------------------------------- SET - 5 -------------------------------------------------------------------------------------


1. What kind of users are listed in the Secrets window of the PPP menu?

a. hotspot users
b. wireless users
c. l2tp users
d. pptp users
e. pppoe users
f. winbox users


2. What configuration is added by /ip hotspot setup command? (select all that apply)
a. /ip service
b. /ip hotspot user
c. /ip hotspot walled-garden
d. /ip dhcp-server
e. /queue tree 


3. Using wireless connect-list it’s possible to prioritize connection to one Access Point over another Access Point by changing the order of the entries. 

a.False
b. True


4. If ARP=reply-only is configured on an interface, what will this interface do
a. Add new MAC addresses in /ip arp list
b. Accept all MAC-addresses listed in /ip arp as static entries
c. Add new IP addresses in /ip arp list
d. Accept all IP addresses listed in /ip arp as static entries
e. Accept all IP/MAC combinations listed in /ip arp as static entries


5. Router A and B are both running as PPPoE servers on different broadcast domains of your network. It is possible to set Router A to use "/ppp secret" accounts from Router B to authenticate PPPoE customers.
a. False
b. True


6. Can you manually add drivers to RouterOS in case your PCI Ethernet card is not recognized, and you suspect it is a driver issue?

a. Yes

b. No


7. What can be used as ’target-address’ in the simple queue?
a. client’s address
b. client’s MAC address
c. server’s address
d. address list name


8. Which is the default port of IP-Winbox?
a. TCP 8291
b. TCP 80
c. UDP 8291
d. TCP 8192


9. MikroTik RouterOS is sending logs to an external syslog server. Which protocol and port is used by RouterOS for sending logs (by default)?
a. UDP 514
b. UDP 21
c. UDP 113
d. TCP 110


10. Which route will be used to reach host 192.168.1.55?

/ip route
add disabled=no distance=1 dst-address=192.168.1.0/24 gateway=1.1.1.1
add disabled=no distance=1 dst-address=192.168.1.0/25 gateway=2.2.2.2
add disabled=no distance=1 dst-address=192.168.0.0/16 gateway=3.3.3.3
 

a. Route via gateway 1.1.1.1

b. Route via gateway 3.3.3.3 

c. Route via gateway 2.2.2.2


11. In which situations can Netinstall NOT be used to install a RouterBOARD?
a. The router does not have an operating system
b. The router is connected only to a wireless network
c. You do not know the password of the router
d. The router is connected only to a secondary Ethernet port


12. To use masquerade, you need to specify
a. action=accept, out-interface, chain=src-nat
b. action=masquerade, out-interface, chain=src-nat
c. action=masquerade, in-interface, chain=src-nat
d. action=masquerade, out-interface, chain=dst-nat


13. Please select valid scan-list values in interface wireless configuration:
a. 5560,5620-5700
b. 5640~5680
c. default,5560,5600,5660-5700
d. 5540,5560,5620+5700


14. When adding a static route, you must always ensure that you add both the gateway and the interface.
False
True


15. You would like to allow multiple logins with one user name on a HotSpot server. How should this be configured?
a. Set "Shared Users" option at /ip hotspot user profile
b. It's not possible
c. Set "Shared Users" option at /ip hotspot
d. Set "only-one=no' at /ip hotspot


16. In which order are the entries in Access List and Connect List processed?
a. In sequence order
b. In a random order
c. By Signal Strength Range
d. By interface name


17. What protocol does ping use?
a. TCP
b. ICMP
c. UDP
d. ARP


18. Is it possible for a client to get an IP address but no gateway after a successful DHCP request?
a. False
b. True


19. Firewall configuration is the following:
1) /ip firewall filter add chain=input protocol=icmp action=jump jump-target=ICMP
2) /ip firewall filter add chain=input protocol=icmp action=log log-prefix=ICMP-DENY
3) /ip firewall filter add chain=input protocol=icmp action=drop
4) /ip firewall filter add chain=ICMP protocol=icmp action=log log-prefix=JUMP-ICMP-DENY
5) /ip firewall filter add chain=ICMP protocol=icmp action=drop

Client sends "ping" to router. What will the router do?

a. Router will drop the packet at ICMP (jump) chain drop rule (5th rule)
b. Router will log it with prefix: ICMP-DENY
c. Router will drop the packet at the Input drop rule (3rd rule)
d. Router will log it with prefix: JUMP-ICMP-DENY

20. /ip firewall nat
add chain=dstnat in-interface=ether1 protocol=tcp dst-port=3389 action=dst-nat to-address=192.168.1.2 to-ports=81

The command shown above:
a. Adds IP address 192.168.1.2 to the interface ether1
b. Forwards any TCP traffic incoming through ether1 port 3389 to the port 81 of the internal host 192.168.1.2
c. Forwards all TCP traffic from 192.168.1.2 to port 81 of the interface ether1
d. Forwards any TCP traffic incoming through ether1 port 81 to the port 3389 of the internal host 192.168.1.2


21. While troubleshooting a network from inside the network, you discover that you can ping the gateway reliably, but you cannot browse the Internet. Skype, however, works flawlessly. What is the most likely issue?
a. DNS is not available
b. The computer did not get an IP address
c. Network card and/or cable is not working
d. Masquerading rule is not applied

22. What is marked by connection-state=established matcher?
a. Packet begins a new TCP connection
b. Packet does not correspond to any known connection
c. Packet belongs to an existing connection,for example a reply packet or a packet which belongs to already replied connection
d. Packet is related to, but not part of an existing connection


23. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package:

a. routing
b. none
c. dhcp
d. advanced-tools


24. You are planning a migration from a wireless link using 802.11a on 5GHz (with no nstreme) to one using Nv2 on 5GHz. When you change the AP from 802.11a to Nv2, you do not wish a client to disconnect for more than a few seconds during the upgrade.

Assuming the client is capable of operating with Nv2 (correct hardware, correct encryption key and ROS version), which setting(s) for 'wireless-protocol' should be enabled on the client so that the client can auto-detect the protocol used by the AP and still make connection with 802.11a or Nv2 : (select all that apply)
a. Nv2
b. nv2-nstreme-802.11
c. any
d. unspecified

25. What does this simple queue do (check the image)?
a. Queue limits host 192.168.1.10 upload data rate to one megabit per second.
b. Queue guarantees download data rate of one megabit per second for host 192.168.1.10
c. Queue guarantees upload data rate of one megabit per second for host 192.168.1.10
d. Queue limits host 192.168.1.10 download data rate to one megabit per second.


------------------------------------------------------------------------------------- SET - 6 -------------------------------------------------------------------------------------


1. What can you do with Netinstall?
a. Reset password in RouterOS
b. Install Linux
c. Add configuration to RouterOS
d. Reinstall RouterOS


2. Consider the attached diagram:
In order for Router 1 to see all of the networks the following commands could be used (choose all answers that could work)


a. /routing add dst-address=0.0.0.0/0 gateway=10.10.0.2
b. /ip route add dst-address=0.0.0.0/0 gateway=10.10.0.2
c. /ip route add dst-address=172.16.0.0/24 gateway=10.10.0.2, /ip route add dst-address=172.32.0.0/24 gateway=10.10.0.2
d. /ip route add dst-address=172.16.0.0/24 gateway=10.10.0.2, /ip route add dst-address=172.32.0.0/24 gateway=10.50.0.2


3. Configuring HotSpot is possible on MikroTikRouterOS only with a wireless interface.

Yes

No


 4. What menus should be used to allow certain websites to be accessed from behind a hotspot interface, without client authentication
a. ip hotspot ip-binding
b. ip hotspot profile
c. ip hotspot walled-garden ip
d. ip hotspot walled-garden

5. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package:
a. none
b. routing
c. advanced-tools
d. dhcp

6. Netinstall can be used to
a. Install different software version (upgrade or downgrade)
b. Keep configuration, but reset a lost admin password
c. Reinstall software without losing licence
d. Install package for different hardware architecture

7. In which order are the entries in Access List and Connect List processed?
a. By interface name
b. In sequence order
c. By Signal Strength Range
d. In a random order

8. In Winbox, Hide Passwords unchecked shows passwords for the following
a. RouterOS user
b. Hotspot User
c. RADIUS shared secret
d. PPP secrets

9. Which options should be used when you want to prevent access from one specific address to your router web interface?
a. Firewall Filter Chain Forward
b. Firewall Filter Chain Input
c. Group settings for System users
d. WWW service from IP Services

10. Which of the following would prevent unknown clients from connecting to your AP? Choose the BEST answer.
a. Check the "Do not permit unknown client" box in the wireless configuration
b. Uncheck "Default Authenticate" in the wireless card configuration, and add each known client's MAC address to your access-list configuration ensuring that you enable "authenticate" in the entry
c. Add each known client's MAC address to your access-list configuration is the only step needed
d. Uncheck "Default Authenticate" in the wireless card configuration, and add each known client's MAC address to your connect-list configuration
e. Configure the radius server under "/radius"

11. Can you manually add drivers to RouterOS in case your PCI Ethernet card is not recognized, and you suspect it is a driver issue?
a. Yes
b. No

12. Mark the queue types that are available in RouterOS
a. SFQ – Stochastic Fairness Queuing
b. RED – Random Early Detect (or Drop)
c. FIFO - First In First Out (for Bytes or for Packets)
d. DRR - Deficit Round Robin
e. LIFO - Last In First Out
f. PCQ – Per Connection Queuing

13. Check the allowed input formats for wireless scan-list.
a. 5500 5700
b. 5500-5700
c. 5500,5700
d. 5500 - 5700
e. 5500/5700

14. Choose all valid hosts address range for subnet 15.242.55.62/27
a. 15.242.55.31-15.242.55.62
b. 15.242.55.33-15.242.55.63
c. 15.242.55.33-15.242.55.62
d. 15.242.55.32-15.242.55.63

15. After putting this rule: /ipfirewall add chain=input action=drop, you will still be able to access the Router using the mac-address.
Yes

16. You need to reboot a RouterBoard after importing a previously exported rsc file to activate the new configuration.

True
False

 
17. What is necessary for PPPoE client configuration?
a. ip firewall nat masquerade rule
b. Interface (on which PPPoE client is going to work)
c. Static IP address on PPPoE client interface

18. In order to use dynamic keys in your security profile for an AP, you MUST set up the dhcp server to provide the dynamic keys.

19. You have a router with configuration
- Public IP :202.168.125.45/24
- Default gateway:202.168.125.1
- DNS server: 248.115.148.136, 248.115.148.137
- Local IP: 192.168.2.1/24

Mark the correct configuration on client PC to access to the Internet
a. IP:192.168.0.1/24 gateway:192.168.2.1
b. IP:192.168.2.2/24 gateway:202.168.125.45
c. IP:192.168.1.223/24 gateway:248.115.148.136
d. IP:192.168.2.115/24 gateway: 192.168.2.1
e. IP:192.168.2.253/24 gateway:202.168.0.1

20. Router OS can set vlan-id value from - to :
a. 1-2049
b. 1-4096
c. 1-4095
d. 1-2048

21. Collisions are possible in full-duplex Ethernet networks

True
False

 
22. Where can you monitor (see addresses and ports) real-time connections which are processed by the router?
a. Queue Tree
b. Tool Torch
c. Firewall Counters
d. Firewall Connection Tracking

23. Action=redirect applies to
a. SRC-NAT rules
b. DST-NAT rules
c. Firewall Filter rules
d. Route rules

24. What does this simple queue do (check the image)?
a. Queue limits host 192.168.1.10 download data rate to one megabit per second.
b. Queue guarantees download data rate of one megabit per second for host 192.168.1.10
c. Queue guarantees upload data rate of one megabit per second for host 192.168.1.10
d. Queue limits host 192.168.1.10 upload data rate to one megabit per second.

25. Is it possible that the same IP address is included in multiple address lists and still be used by these multiple address lists?

a. Destination NAT rule is required to utilize transparent proxy facility
b. To deny access to a specific website, caching should be enabled
c. Controls domains or servers which are allowed to cache by Proxy
d. Can deny access to a specific domains or servers, but not specific web pages


------------------------------------------------------------------------------------- SET - 7 -------------------------------------------------------------------------------------


1. Choose correct statements for MikroTik proxy.
a. Destination NAT rule is required to utilize transparent proxy facility
b. To deny access to a specific website, caching should be enabled
c. Controls domains or servers which are allowed to cache by Proxy
d. Can deny access to a specific domains or servers, but not specific web pages

2. Collisions are possible in full-duplex Ethernet networks

True
False

 
3. Which of the following is NOT a valid MAC Address?
a. 13:16:86:53:89:43
b. 80:GF:AA:67:13:5D
c. 88:0C:00:99:5F:EF
d. EA:BA:AA:EE:FF:CB
e. 95:B5:DD:EE:78:8A

4. The default value of 'target-scope' for a static route is:
a. 30
b. 1
c. 10
d. 255

5. Which firewall chain would be used to block a client's MSN traffic on a router?
a. output
b. static
c. input
d. forward

6. Please select valid scan-list values in interface wireless configuration:
a. 5540,5560,5620+5700
b. 5560,5620-5700
c. 5640~5680
d. default,5560,5600,5660-5700

7. You want to limit bandwidth for your HotSpot users. HotSpot can create dynamic queues on user login to do the speed limitations.
a. Yes/ True
b. No/ False

8. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package:
a. dhcp
b. none
c. advanced-tools
d. routing

9. You start a scan for wireless networks on you access point. What will happen ?
a. All connected clients will disconnect
b. You'll see all connected clients
c. You'll see available frequencies

10. What kind of users are listed in the "/user" menu?
a. pptp users
b. wireless users
c. hotspot users
d. router users

11. Which is correct masquerade rule for 192.168.0.0/24 network on the router with outgoing interface=ether1?
a. /ip firewall nat add action=masquerade chain=srcnat out-interface=ether1
b. /ip firewall nat add action=masquerade chain=srcnat src-address=192.168.0.0/24
c. /ip firewall nat add action=masquerade out-interface=ether1 chain=dstnat
d. /ip firewall nat add action=masquerade chain=srcnat

12. Which firewall chain should you use to filter ICMP packets from the router itself?
a. input
b. forward
c. postrouting
d. output

13. Which software version can be installed onto the following RouterBoard types?
a. routeros-mipsbe-x.xx.npk on a RB433
b. routeros-powerpc-x.xx.npk on a RB333
c. routeros-mipsle-x.xx.npk on RB133
d. routeros-x86-x.xx.npk on a RB1100
e. routeros-mipsbe-x.xx.npk on a RB133

14. The highest queue priority is
a. 16
b. 8
c. 256
d. 1

15. Firewall configuration is the following:
1) /ip firewall filter add chain=input protocol=icmp action=jump jump-target=ICMP
2) /ip firewall filter add chain=input protocol=icmp action=log log-prefix=ICMP-DENY
3) /ip firewall filter add chain=input protocol=icmp action=drop
4) /ip firewall filter add chain=ICMP protocol=icmp action=log log-prefix=JUMP-ICMP-DENY
5) /ip firewall filter add chain=ICMP protocol=icmp action=drop

Client sends "ping" to router. What will the router do?
a. Router will drop the packet at the Input drop rule (3rd rule)
b. Router will log it with prefix: JUMP-ICMP-DENY
c. Router will drop the packet at ICMP (jump) chain drop rule (5th rule)
d. Router will log it with prefix: ICMP-DENY

16. MikroTik proxy features are:
a. POP3 caching
b. DNS name filtering
c. SMTP caching
d. HTTP caching
e. FTP caching

17. What does this simple queue do (check the image)?
a. Queue limits host 192.168.1.10 download data rate to one megabit per second.
b. Queue limits host 192.168.1.10 upload data rate to one megabit per second.
c. Queue guarantees download data rate of one megabit per second for host 192.16SID="WAN1"mode="ap-bridge" and a VirtualAP with SSID="VAP1" on the router. Is it possibl8.1.10
d. Queue guarantees upload data rate of one megabit per second for host 192.168.1.10

18. You have a wireless interface with Se to use nstreme protocol?
a. Yes, but Nstreme will be used for all SSID assigned for that physical interface
b. Yes, but Nstreme can be used only for SSID=WLAN1.
c. No, Nstreme can not be used on wireless interface if a VirtualAP is on it.
d. Yes, but Nstreme can be used only for SSID=VAP1.

19. /store allows you to save to external disk
a. User-Manager data
b. dude data
c. web-proxy data
d. system configuration

20. /ip route configuration on router,

/ip route add gateway=192.168.0.1
/ip route add dst-address=192.168.1.0/24 gateway=192.168.0.2
/ip route add dst-address=192.168.2.0/24 gateway=192.168.0.3
/ip route add dst-address=192.168.3.0/26 gateway=192.168.0.4

Router needs to send packets to 192.168.3.240. Which gateway will be used?

a. 192.168.0.2
b. 192.168.0.1
c. 192.168.0.3
d. 192.168.0.4

21. What is the meaning of letter "R" on an active session in the menu PPP Active Connections?
a. Running
b. Radius
c. Remote

22. A station can connect to AP if they both use different country regulation settings, but the frequency chosen is allowed in both countries


23. Hotspot ip-binding is used to allow access to remote host specifying the IP address of the remote host.


24. Router has Wireless and Ethernet client interfaces, all client interfaces are bridged.

To create a DHCP service for all clients you must configure DHCP server on
a. every bridge port
b. only on bridge interface
c. Ethernet and wireless interfaces
d. DHCP service is not possible in this setup

25. EoiP is:
a. MikroTik proprietary tunnel protocol
b. Layer-3 tunnel
c. Layer-2 tunnel, that can be bridged

------------------------------------------------------------------------------------- SET - 8 -------------------------------------------------------------------------------------


1. log messages are stored on disk by default


2. Router OS can set vlan-id value from - to :
a. 1-2048
b. 1-2049
c. 1-4096
d. 1-4095

3. Can you manually add drivers to RouterOS in case your PCI Ethernet card is not recognized, and you suspect it is a driver issue?
a. Yes
b. No

4. Which of the following is true for connection tracking
a. Enabling connection tracking reduces CPU usage in RouterOS
b. Disable connection tracking for mangle to work
c. Connection tracking must be enable for NAT'ed network
d. Connection tracking must be enabled for firewall to be effective

5. What letters appear next to a route, which is automatically created by RouterOS when user adds a valid address to an active interface?
a. I
b. S
c. C
d. D
e. A

6. Which is the default port of IP-Winbox?
a. TCP 8192
b. UDP 8291
c. TCP 8291
d. TCP 80

7. You want to use PCQ and allow 256k maximum download and upload for each client. Choose correct argument values for the required queue.
a. kind=pcqpcq-limit=5000000 pcq-classifier=dst-address
b. kind=pcqpcq-limit=256000 pcq-classifier=src-address
c. kind=pcqpcq-limit=256000 pcq-classifier=dst-address
d. kind=pcqpcq-limit=5000000 pcq-classifier=src-address
e. kind=pcqpcq-limit=1256000 pcq-classifier=dst-address

8. To limit wireless access for your HotSpot users
a. Create MAC Address restriction on PPP user login
b. Create IP Address restriction in the Wireless Access List
c. Create MAC Address restriction on HotSpot user login
d. Create MAC Address restriction in the Wireless Access List

9. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package:
a. routing
b. advanced-tools
c. none
d. dhcp

10. To avoid looping on this network, you need to:
a. Enable RSTP on AP1 and AP3
b. Enable RSTP on AP1
c. Enable RSTP on AP1, AP2 and AP3

11. To make the masquerading of the network 192.168.0.0/24, configured on the interface Ether1, you should add rule
a. /ip firewall nat add chain=dstnat in-interface=ether1 src-address=192.168.0.0/24 action=masquerade
b. /ip firewall nat add chain=srcnatsrc-address=192.168.0.0/24 action=masquerade
c. /ip firewall nat add chain=dstnat out-interface=ether1 src-address=192.168.0.0/24 action=masquerade
d. /ip firewall nat add chain=srcnat out-interface=ether1 src-address=192.168.0.0/24 action=masquerade

12. On the advanced menu of the wireless setup there is a parameter called "Area", it works directly with:
a. None of these
b. Connect List
c. Access List
d. Security Profile

13. The basic unit of a physical network (OSI Layer 1) is the:
a. Header
b. Bit
c. Byte
d. Frame

14. It is impossible to disable user "admin" at the menu "/user"

True
False
 

15.HotSpot is required on the interfaces ether2, ether3, wlan1 (in ap-bridge mode).
These interfaces are bridged in the bridge1 interface.
Which interface should the HotSpot server be configured on?
a. On ether2 interface
b. On ether3 interface
c. On wlan1 interface
d. On bridge1 interface

16. The highest queue priority is
a. 256
b. 1
c. 16
d. 8

17. What is necessary for PPPoE client configuration?
a. Static IP address on PPPoE client interface
b. ip firewall nat masquerade rule
c. Interface (on which PPPoE client is going to work)

18. To be able to do NAT the connection tracking does not need to be enabled.
a. True
b. False

19. Check the allowed input formats for wireless scan-list.
a. 5500,5700
b. 5500-5700
c. 5500/5700
d. 5500 - 5700
e. 5500 5700

20. To connect your MikroTik router to a wireless access point, you have to:
a. Use the same Radio Name
b. Use the same SSID as on accesspoint
c. Use the same Band (5 GHz, 2.4 GHz, ...)

21. Which default route will be active?
/ip route
add disabled=no distance=10 dst-address=0.0.0.0/0 gateway=1.1.1.1
add disabled=no distance=5 dst-address=0.0.0.0/0 gateway=2.2.2.2
a. Route via gateway 1.1.1.1
b. Route via gateway 2.2.2.2

22. An IP address pool can contain addresses from more than one subnet.
a. True
b. False

23. Is it possible to use the serial port of MikroTik to communicate with an external device connected by null-modem cable?
a. Yes, if port is not being used
b. Yes, when other is a MikroTik router.
c. Yes, it is always possible by /system serial-terminal command.

24. It is required to make a web server on a private LAN visible on the Public Internet. Only the web server port should be visible to the public. Which of the following configuration steps must be met. (select all that apply)

a. A route between the NAT Router and the webserver must exist
b. LAN address of the webserver should be routable on the internet
c. in ip firewall NAT there should be a dst-nat between the public ip of the router and the private ip of the webserver
d. Connection Tracking must be enabled on NAT router
e. Public IP address of the webserver must be installed on the NAT Router

25. Collisions are possible in full-duplex Ethernet networks

True
False


------------------------------------------------------------------------------------- SET - 9 -------------------------------------------------------------------------------------


1. Is it possible to have PPTP Client and PPTP server on one MikroTik router at the same time?
a. Yes/ True
b. No/ False

2. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package:
a. dhcp
b. none
c. advanced-tools
d. routing

3. What could be monitored by Torch?
a. Dst. Address
b. Dst. Port
c. None of the above is correct
d. Src. Address
e. Vlan ID
f. Protocol

4. The highest queue priority is
a. 16
b. 8
c. 1
d. 256

5. Wireless clients (mode=station) will work properly if bridged to ethernet


6. Which of the following Routes statuses are possible?
a. S = Static
b. C = Connected
c. D = Drop
d. A = Active

7. You have to connect to a RouterBOARD without any previous configuration. Select all possibilities to connect and do some basic configuration
a. Telnet
b. Attach monitor/keyboard
c. MAC-Winbox
d. Serial Connection

8. A network ready device is directly connected to a MikroTik RouterBOARD 750 with a correct U.T.P. RJ45 functioning cable. The device is configured with an IPv4 address of 192.168.100.70 using a subnet mask of 255.255.255.252. What will be a valid IPv4 address for the RouterBOARD 750 for a successful connection to the device?
a. 192.168.100.70/255.255.255.252
b. 192.168.100.68/255.255.255.252
c. 192.168.100.69/255.255.255.252
d. 192.168.100.71/255.255.255.252

9. Netinstall can be used to
a. Install package for different hardware architecture
b. Reinstall software without losing licence
c. Keep configuration, but reset a lost admin password
d. Install different software version (upgrade or downgrade)

10. Consider the following network diagram. In R1, you have the following configuration:
/ip route
add dst-address=192.168.1.0/24 gateway=192.168.99.2

/ip firewall nat
add chain=srcnat out-interface=Ether1 action=masquerade

On R2, if you wish to prevent all access to a server located at 192.168.1.10 from LAN1 devices, which of the following rules would be needed?
a. /ip firewall nat add chain=dstnat src-address=192.168.99.1 dst-address=192.168.1.10 action=drop
b. /ip firewall filter add chain=input src-address=192.168.99.1 dst-address=192.168.1.10 action=drop
c. /ip firewall filter add chain=forward src-address=192.168.0.0/24 dst-address=192.168.1.10 action=drop
d. /ip firewall filter add chain=forward src-address=192.168.99.1 dst-address=192.168.1.10 action=drop

11. /interface wireless access-list is used for
a. Contains the security profiles settings
b. Handles a list of Client's MAC Address to permit/deny connection to AP
c. Shows a list of Client's MAC Address that are already registered at AP
d. Authenticate Hotspot users

12. To make the masquerading of the network 192.168.0.0/24, configured on the interface Ether1, you should add rule
a. /ip firewall nat add chain=srcnat out-interface=ether1 src-address=192.168.0.0/24 action=masquerade
b. /ip firewall nat add chain=dstnat in-interface=ether1 src-address=192.168.0.0/24 action=masquerade
c. /ip firewall nat add chain=dstnat out-interface=ether1 src-address=192.168.0.0/24 action=masquerade
d. /ip firewall nat add chain=srcnat src-address=192.168.0.0/24 action=masquerade

13. RouterOS DHCP server is able to send any DHCP options (specified in RFCs) to DHCP clients
a. Yes
b. No

14. You would like to allow multiple logins with one user name on a HotSpot server. How should this be configured?
a. Set "only-one=no' at /ip hotspot
b. Set "Shared Users" option at /ip hotspot user profile
c. It's not possible
d. Set "Shared Users" option at /ip hotspot

15. You are planning a migration from a wireless link using 802.11a on 5GHz (with no nstreme) to one using Nv2 on 5GHz. When you change the AP from 802.11a to Nv2, you do not wish a client to disconnect for more than a few seconds during the upgrade.

Assuming the client is capable of operating with Nv2 (correct hardware, correct encryption key and ROS version), which setting(s) for 'wireless-protocol' should be enabled on the client so that the client can auto-detect the protocol used by the AP and still make connection with 802.11a or Nv2 : (select all that apply)
a. unspecified
b. any
c. Nv2
d. nv2-nstreme-802.11

16. Using wireless connect-list it’s possible to prioritize connection to one Access Point over another Access Point by changing the order of the entries.

a.False
b. True


17. The total-max-limit under Simple Queues will limit the combined upload and download of the target-address of your simple queue.

a. Yes
b. No

18. Two mangle rules defining different mangle marks for the same traffic type, will make it have both mangle marks.
a. Yes
b. No

19. Where are HotSpot authorized clients shown?
a. /ip hotspot host
b. /ip hotspot active
c. /ip hotspot
d. /ip hotspot user

20. A PC with IP 192.168.1.2 can access internet, and static ARP has been set for that IP address on gateway. When the PC Ethernet card failed, the user change it with a new card and set the same IP for it.


What else should be done?
a. Old static ARP entry on gateway has to be updated for the new card
b. MAC-address of the new card has to be changed to MAC address of old card
c. Another IP has to be added for Internet access
d. Nothing - it will work as before

21. Is it possible for a client to get an IP address but no gateway after a successful DHCP request?

a. False
b. True


22. Which RouterOS packages should be installed on router for SSH server support?
a. advanced-tools
b. system
c. ssh
d. security

23. There is an HTTP server 10.0.0.1 in your private network. You have made a DST-NAT rule that sends all HTTP traffic received on your router's address 80.232.50.100 to this server. If you make a firewall rule on the router to disallow address 159.148.20.30 to communicate with the server, how would you identify this communication in this rule?
a. src-address=159.148.20.30 dst-address=80.232.50.100
b. src-address=159.148.20.30 dst-address=10.0.0.1
c. src-address=80.232.50.100 dst-address=10.0.0.1
d. src-address=80.232.50.100 dst-address=159.148.20.30

24. Router A and B are both running as PPPoE servers on different broadcast domains of your network. It is possible to set Router A to use "/ppp secret" accounts from Router B to authenticate PPPoE customers.a. False
b. True


25. Define a routing loop (choose the most precise description)
a. situation where the packet is routed through the same sequence of routers until the TTL expires
b. Situation where the packet does not reach it\'s destination
c. situation where the TTL of the packet expires
d. situation where the packet is routed through the same router twice

------------------------------------------------------------------------------------- SET - 10 -------------------------------------------------------------------------------------


1. You start a scan for wireless networks on you access point. What will happen ?
a. All connected clients will disconnect
b. You'll see all connected clients
c. You'll see available frequencies

2. Is action=masquerade allowed in chain=dstnat?
a. no
b. yes
c. yes, but it works only for incoming connections
d. yes, but only if dst-addr is specified

3. Which route will be used to reach host 192.168.1.55?

/ip route
add disabled=no distance=1 dst-address=192.168.1.0/24 gateway=1.1.1.1
add disabled=no distance=1 dst-address=192.168.1.0/25 gateway=2.2.2.2
add disabled=no distance=1 dst-address=192.168.0.0/16 gateway=3.3.3.3
a. Route via gateway 2.2.2.2
b. Route via gateway 1.1.1.1
c. Route via gateway 3.3.3.3

4. Can you manually add drivers to RouterOS in case your PCI Ethernet card is not recognized, and you suspect it is a driver issue?
a. No
b. Yes

5. What is necessary for PPPoE client configuration?
a. ip firewall nat masquerade rule
b. Static IP address on PPPoE client interface
c. Interface (on which PPPoE client is going to work)

6. Mark all correct answers
a. Wireless access-list could allow and deny access to your AP
b. Default-Forwarding could be enabled for a specific clients by wireless access-list
c. /ip firewall filter allows to deny authentication to AP
d. The only way to prevent wireless clients connections - disable wireless interface

7. You want to limit bandwidth for your HotSpot users. HotSpot can create dynamic queues on user login to do the speed limitations.
a. Yes/ True
b. No/ False

8. A routing table has following entries:

0 dst-address=10.0.0.0/24 gateway=10.1.5.126
1 dst-address=10.1.5.0/24 gateway=10.1.1.1
2 dst-address=10.1.0.0/24 gateway=25.1.1.1
3 dst-address=10.1.5.0/25 gateway=10.1.1.2

Which gateway will be used for a packet with destination address 10.1.5.126?
a. 25.1.1.1
b. 10.1.1.1
c. 10.1.1.2
d. 10.1.5.126

9. Which is the default port of IP-Winbox?
a. TCP 8192
b. TCP 8291
c. TCP 80
d. UDP 8291

10. In case when router login password is lost, it is necessary to reinstall RouterOS or use hardware reset funcion.
a. Yes/ True
b. No/ False

11. On the advanced menu of the wireless setup there is a parameter called "Area", it works directly with:
a. Security Profile
b. Connect List
c. Access List
d. None of these

12. Is it possible that the same IP address is included in multiple address lists and still be used by these multiple address lists?

a. Destination NAT rule is required to utilize transparent proxy facility
b. To deny access to a specific website, caching should be enabled
c. Controls domains or servers which are allowed to cache by Proxy
d. Can deny access to a specific domains or servers, but not specific web pages

13. What protocol does ping use?
a. ICMP
b. ARP
c. TCP
d. UDP

14. Which firewall chain should you use to filter clients HTTP traffic going through the router?
a. prerouting
b. output
c. input
d. forward

15. Connection marks are stored in the connection tracking table.
a. Yes/ True
b. No/ False

16. MikroTik RouterOS commands can be run once a day by:
a. /system watchdog
b. /system scheduler
c. /system cron

17. What is term for the hardware coded address found on an interface?
a. FQDN Address
b. MAC Address
c. Interface Address
d. IP Address

18. For user in local ppp secrets/ppp profiles database, it is possible to
a. Allow/deny use of more than one login by this user
b. Allow only pppoe login
c. Allow login by pppoe and pptp, but deny login by l2tp
d. Deny services (like telnet) only for this user or for one group of users
e. Set max values for total transferred bytes (up- and download)

19. You have a DHCP server on your MikroTik router. The IP addresses 10.1.2.2-10.2.2.20 are distributed in the DHCP network. Additionally, 3 static IP address are defined for your servers: 10.1.2.31-10.1.2.33. After a while 20 more IP addresses need to be distributed in the network. Is it possible to distribute the extra IP address without adding another DHCP Server?


20. You wish to secure your RouterOS system. You do not want the RouterOS to be discoverable using MNDP or CDP locally. You also want to deny management via the MAC addresses on all interfaces. Select the correct actions to accomplish this.
a. Remove/Disable all interfaces under mac-server telnet
b. Remove/Disable all discovery interfaces
c. Place a proper forward firewall rule to block mac discovery
d. Remove/Disable the Interfaces
e. Place a proper input firewall rule to block mac discovery
f. Remove/Disable all interfaces under mac-Server winbox
g. Add a Deny All input firewall rule

21. What does this simple queue do (check the image)?
a. Queue guarantees download data rate of one megabit per second for host 192.168.1.10
b. Queue guarantees upload data rate of one megabit per second for host 192.168.1.10
c. Queue limits host 192.168.1.10 download data rate to one megabit per second.
d. Queue limits host 192.168.1.10 upload data rate to one megabit per second.

22. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package:
a. none
b. advanced-tools
c. routing
d. dhcp

23. You want to use PCQ and allow 256k maximum download and upload for each client. Choose correct argument values for the required queue.
a. kind=pcq pcq-limit=256000 pcq-classifier=src-address
b. kind=pcq pcq-limit=1256000 pcq-classifier=dst-address
c. kind=pcq pcq-limit=5000000 pcq-classifier=src-address
d. kind=pcq pcq-limit=5000000 pcq-classifier=dst-address
e. kind=pcq pcq-limit=256000 pcq-classifier=dst-address

24. To avoid looping on this network, you need to:
a. Enable RSTP on AP1, AP2 and AP3
b. Enable RSTP on AP1
c. Enable RSTP on AP1 and AP3

25. HotSpot server is installed on the router. All IP-phones are required to have access to outside networks without any HotSpot authentication. Select the configuration options you can use to achieve this setup.
a. /ip hotspot walled-garden ip
b. /ip hotspot service-ports
c. /ip hotspot ip-binding

------------------------------------------------------------------------------------- SET - 11 -------------------------------------------------------------------------------------


1. DHCP server is configured on a router’s ether1 interface. IP address 192.168.0.100/24 is assigned to the interface. Possible IP pools, that can be used by this DHCP server, are:
a. 192.168.0.1-192.168.0.255
b. 192.169.0.1-192.169.0.254
c. 192.168.0.1-192.168.0.14
d. 192.168.0.1-192.168.0.99,192.168.0.101-192.168.0.254
   
2. Collisions are possible in full-duplex Ethernet networksTrue
False 

3. What is possible with Netinstall?
a. MikroTikRouterOS reinstall
b. MikroTikRouterOS configuration reset
c. MikroTikRouterOS password reset with saving router's configuration
   
4. Action=redirect allows you to make
a. Transparent DNS Cache
b. Enable Local Service
c. Forward DNS to another device IP address
d. Transparent HTTP Proxy
   
5. Which software version can be installed onto the following RouterBoard types?
a. routeros-mipsle-x.xx.npk on RB133
b. routeros-x86-x.xx.npk on a RB1100
c. routeros-mipsbe-x.xx.npk on a RB433
d. routeros-powerpc-x.xx.npk on a RB333
e. routeros-mipsbe-x.xx.npk on a RB133
   
6. What does the firewall action "Redirect" do? Select all true statements.  
a. Redirects a packet to a specified IP
b. Redirects a packet to a specified port on a host in the network
c. Redirects a packet to a specified port on the router
d. Redirects a packet to the router
   
7. What does this simple queue do (check the image)?
a. Queue limits host 192.168.1.10 download data rate to one megabit per second.
b. Queue guarantees download data rate of one megabit per second for host 192.168.1.10
c. Queue guarantees upload data rate of one megabit per second for host 192.168.1.10
d. Queue limits host 192.168.1.10 upload data rate to one megabit per second.
   
8. What wireless modes can be used in a WDS setup?
a. bridge
b. nstreme-dual-slave
c. station-wds
d. ap-bridge
e. station
   
9. You want to use PCQ and allow 256k maximum download and upload for each client. Choose correct argument values for the required queue.
a. kind=pcqpcq-limit=256000 pcq-classifier=src-address
b. kind=pcqpcq-limit=1256000 pcq-classifier=dst-address
c. kind=pcqpcq-limit=5000000 pcq-classifier=dst-address
d. kind=pcqpcq-limit=256000 pcq-classifier=dst-address
e. kind=pcqpcq-limit=5000000 pcq-classifier=src-address
   
10. Firewall NAT rules process only the first packet of each connection.
   
   
11. Select all the RouterOS software packages required for configuring a wireless AP
a. wireless
b. advanced-tools
c. dhcp
d. routing
e. system
   
12. Router OS can set vlan-id value from - to : 
a. 1-2048
b. 1-4096
c. 1-2049
d. 1-4095
   
13. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package: 
a. none
b. advanced-tools
c. dhcp
d. routing
   
14. Please select valid scan-list values in interface wireless configuration:
a. 5540,5560,5620+5700
b. 5640~5680
c. 5560,5620-5700
d. default,5560,5600,5660-5700
   
15. Can you manually add drivers to RouterOS in case your PCI Ethernet card is not recognized, and you suspect it is a driver issue?
a. Yes
b. No
   
16. What configuration is added by /ip hotspot setup command? (select all that apply)
a. /queue tree
b. /ip hotspot walled-garden
c. /ipdhcp-server
d. /ip hotspot user
e. /ip service
   
17. Mark all correct answers: destination NAT will take place...
a. after ip firewall filter, chain forward
b. before ip firewall filter, chain forward
c. before routing decision
d. after routing decision
   
18. It is possible to access MikroTik Graphs on a different port than HTTP port 80.
a. Yes
b. No
 
19. HotSpot is required on the interfaces ether2, ether3, wlan1 (in ap-bridge mode).
These interfaces are bridged in the bridge1 interface.
Which interface should the HotSpot server be configured on?
a. On wlan1 interface
b. On ether3 interface
c. On bridge1 interface
d. On ether2 interface
   
20. Using wireless connect-list it’s possible to prioritize connection to one Access Point over another Access Point by changing the order of the entries.

a.False
b. True

    
21. MikroTik proxy features are:
a. HTTP caching
b. POP3 caching
c. SMTP caching
d. FTP caching
e. DNS name filtering
   
22. Which computers would be able to communicate directly (without any routers involved)
a. 192.168.0.5/26 and 192.168.0.100
b. 192.168.17.15/29 and 192.168.17.20/28
c. 10.10.0.17/22 and 10.10.1.30/23
d. 10.5.5.1/24 and 10.5.5.100/25
   
23. Is it possible to have PPTP Client and PPTP server on one MikroTik router at the same time?
a. Yes/ True
b. No/ False
24. Which default route will be active?

/ip route
add disabled=no distance=10 dst-address=0.0.0.0/0 gateway=1.1.1.1
add disabled=no distance=5 dst-address=0.0.0.0/0 gateway=2.2.2.2  
a. Route via gateway 1.1.1.1
b. Route via gateway 2.2.2.2
   
25. You can not use OSPF and RIP routing protocols simultaneously on the RouterOS.

a. Yes/ True
b. No/ False
 

------------------------------------------------------------------------------------- SET - 12 -------------------------------------------------------------------------------------


1. How many usable IP addresses are there in a 23-bit (255.255.254.0) subnet?
a. 254
b. 512
c. 510
d. 508

2. A network ready device is directly connected to a MikroTik RouterBOARD 750 with a correct U.T.P. RJ45 functioning cable. The device is configured with an IPv4 address of 192.168.100.70 using a subnet mask of 255.255.255.252. What will be a valid IPv4 address for the RouterBOARD 750 for a successful connection to the device?
a. 192.168.100.69/255.255.255.252
b. 192.168.100.71/255.255.255.252
c. 192.168.100.70/255.255.255.252
d. 192.168.100.68/255.255.255.252

3. Select valid subnet masks:
a. 192.0.0.0
b. 255.255.224.0
c. 255.255.192.255
d. 255.192.0.0

4. What protocol does ping use?
a. UDP
b. ICMP
c. ARP
d. TCP

5. Select valid MAC-address
a.192.168.0.0/16
b. 00:00:5E:80:EE:B0
d. AEC8:21F1:AA44:54FF:1111:DDAE:0212:1201
e. G2:60:CF:21:99:H0

6. Which computers would be able to communicate directly (without any routers involved)
a. 10.5.5.1/24 and 10.5.5.100/25
b. 192.168.0.5/26 and 192.168.0.100
c. 10.10.0.17/22 and 10.10.1.30/23
d. 192.168.17.15/29 and 192.168.17.20/28

7. How many IP addresses can one find in the header of an IP packet?
a. 4
b. 1
c. 2
d. 3

8. Which of the following protocols / port s are used for SNMP. (Simple Network Managemnt Protocol)
a. TCP 25
b. TCP 161
c. UDP 161
d. UDP 162
e. TCP 123
f. TCP 162

9. How many usable IP addresses are there in a 20-bit subnet?
a. 2046
b. 2047
d. 4094
e. 2048
f. 4096

10. A PC with IP 192.168.1.2 can access internet, and static ARP has been set for that IP address on gateway. When the PC Ethernet card failed, the user change it with a new card and set the same IP for it.

What else should be done?
a. Nothing - it will work as before
b. MAC-address of the new card has to be changed to MAC address of old card
c. Old static ARP entry on gateway has to be updated for the new card
d. Another IP has to be added for Internet access

11. You have a router with configuration
- Public IP :202.168.125.45/24
- Default gateway:202.168.125.1
- DNS server: 248.115.148.136, 248.115.148.137
- Local IP: 192.168.2.1/24

Mark the correct configuration on client PC to access to the Internet
a. IP:192.168.0.1/24 gateway:192.168.2.1
b. IP:192.168.2.115/24 gateway: 192.168.2.1
c. IP:192.168.2.2/24 gateway:202.168.125.45
d. IP:192.168.2.253/24 gateway:202.168.0.1
e. IP:192.168.1.223/24 gateway:248.115.148.136

12. Which ones of the following are valid IP addresses?
a. 192.168.13.255
b. 10.10.14.0
c. 1.27.14.254
d. 192.168.256.1

13. MAC layer by OSI model is also known as
a. Layer 7
b. Layer 2
c. Layer 3
d. Layer 6
e. Layer 1

14. Which of the following IP addresses are publicly routable?
a. 127.34.155.3
b. 11.3.10.4
c. 172.16.13.23
d. 192.168.1.4

15. The network address is
a. The first usable address of the subnet
b. The first address of the subnet
c. The last address of the subnet

16. Select which of the following are 'Public IP addresses':
a. 10.110.50.37
b. 11.63.72.21
c. 172.168.254.2
d. 172.28.73.21
e. 192.168.0.1

17. Is ARP used in the IPv6 protocol ? True
False  

18. What is term for the hardware coded address found on an interface?
a. MAC Address
b. Interface Address
c. IP Address
d. FQDN Address

19. How many layers does Open Systems Interconnection model have?
a. 12
b. 7
c. 6
d. 9
e. 5

20. In MikroTik RouterOS, Layer-3 communication between 2 hosts can be achieved by using an address subnet of:
a. /30
b. /31
c. /29
e. /32


------------------------------------------------------------------------------------- SET - 13 -------------------------------------------------------------------------------------


1. Action=redirect is applied in

a. chain=srcnat

b. chain=dstnat

c. chain=forward


2. You have 802.11b/g wireless card. What frequencies are available to you?

a. 5800MHz

b. 2412MHz

c. 5210MHz

d. 2422MHz

e. 2327MHz


3. Mark all correct statements about /export (rsc file).

a. Exports logs from /log print

b. Exports full configuration of the router

c. Exports only part of the configuration (for example /ip firewall)

d. Exports scripts from /system script

e. Exports files could not edited


4. What wireless card can we use to achieve 100 Mbps actual wireless throughput?

a. 802.11 b/g

b. 802.11 a/b/g

c. 802.11 a

d. 802.11 a/n

e. 802.11 a/b/g/n


5. It is possible to add user-defined chains in ip firewall mangle


6. Choose all valid hosts address range for subnet 15.242.55.62/27

a. 15.242.55.31-15.242.55.62

b. 15.242.55.32-15.242.55.63

c. 15.242.55.33-15.242.55.62

d. 15.242.55.33-15.242.55.63


7. Action=redirect allows you to make

a. Transparent DNS Cache

b. Forward DNS to another device IP address

c. Enable Local Service

d. Transparent HTTP Proxy


8. Which is correct masquerade rule for 192.168.0.0/24 network on the router with outgoing interface=ether1?

a. /ip firewall nat add action=masquerade chain=srcnat

b. /ip firewall nat add action=masquerade chain=srcnat src-address=192.168.0.0/24

c. /ip firewall nat add action=masquerade out-interface=ether1 chain=dstnat

d. /ip firewall nat add action=masquerade chain=srcnat out-interface=ether1


9. What letters appear next to a route, which is automatically created by RouterOS when user adds a valid address to an active interface?

a. I

b. D

c. A

d. S

e. C


10. Mark all features that are compatible with Nstreme

a. WDS between a device in station-wds mode and a device in station-wds mode

b. Encryption

c. WDS between a device in ap-bridge mode with a device in station-wds mode

d. Bridging a device in station mode with a device in ap-bridge mode


11. Can you manually add drivers to RouterOS in case your PCI Ethernet card is not recognized, and it’s a driver issue?

a. Yes

b. No


12. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package:

a. none

b. dhcp

c. routing

d. advanced-tools


13. Which are necessary sections in /queue simple to set bandwidth limitation?

a. target-address, max-limit

b. target-address, dst-address, max-limit

c. target-address, dst-address

d. max-limit


14. What protocol is used for Ping and Trace route?

a. DHCP

b. IP

c. TCP

d. ICMP

e. UDP


15. From which of the following locations can you obtain Winbox?

a. Router’s webpage

b. Files menu in your router

c. Via the console cable

d. mikrotik.com


16. Two hosts, A and B, are connected to a broadcast LAN. Select all the answers showing pairs of IP address/mask which would allow IP connections to be established between the two hosts.

a. A: 10.1.2.66/25 and B: 10.1.2.109/26

b. A: 10.2.2.1/23 and B: 10.2.0.1/22

c. A: 10.1.2.192/24 and B: 10.1.2.129/26

d. A: 10.2.1.0/23 and B: 10.2.0.1/22


17. Why is it useful to set a Radio Name on the radio interface?

a. To identify a station in a list of connected clients

b. To identify a station in the Access List

c. To identify a station in Neighbor discovery


18. What kind of users are listed in the Secrets window of the PPP menu?

a. pptp users

b. l2tp users

c. winbox users

d. wireless users

e. pppoe users

f. hotspot users


19. Router A and B are both running as PPPoE servers on different broadcast domains of your network. Is it possible to set Router A to use “/ppp secret” accounts from Router B to authenticate PPPoE customers ?



20. MikroTik RouterOS DHCP client can receive following options

a. Byte limit

b. IP Gateway

c. Rate limit

d. Uptime limit

e. IP Address and Subnet


21. The HotSpot feature can be used only on ethernet interfaces. You have to use a separate access point if you want to use this feature with wireless.


22. If you need to make sure that one computer in your HotSpot network can access the Internet without HotSpot authentication, which menu allows you to do this?

a. Users

b. IP bindings

c. Walled-garden

d. Walled-garden IP


23. How many different priorities can be selected for queues in MikroTik RouterOS?

a. 8

b. 16

c. 0

d. 1


24. Which default route will be active?

/ip route

add disabled=no distance=10 dst-address=0.0.0.0/0 gateway=1.1.1.1

add disabled=no distance=5 dst-address=0.0.0.0/0 gateway=2.2.2.2

a. Route via gateway 1.1.1.1

b. Route via gateway 2.2.2.2


25. How long is level 1 (demo) license valid?

a. 24 hours

b. Infinite time

c. 1 month

d. 1 year


------------------------------------------------------------------------------------- SET - 14 -------------------------------------------------------------------------------------


1. If you need to make sure that one computer in your HotSpot network can access the Internet without HotSpot authentication, which menu allows you to do this?

a. IP bindings

b. Walled-garden

c. Users

d. Walled-garden IP


2. Manakah fakta yang benar mengenai file backup?

a. Termasuk file yang tersimpan di /files

b. Bisa diedit

c. Termasuk username dan password dari /user

d. Mencakup seluruh konfigurasi router


3. NStreme works only on 40mhz channel width

true

false


4. To make all DNS requests coming from your network to resolve on your router (regardless of the clients’ configuration), which action would you specify for the DST-NAT rule?

a. masquerade

b. dst-nat

c. you can’t use DST-NAT to achieve this

d. redirect


5. Two hosts, A and B, are connected to a broadcast LAN. Select all the answers showing pairs of IP address/mask which would allow IP connections to be established between the two hosts.

a. A: 10.1.2.66/25 and B: 10.1.2.109/26

b. A: 10.1.2.192/24 and B: 10.1.2.129/26

c. A: 10.2.2.1/23 and B: 10.2.0.1/22

d. A: 10.2.1.0/23 and B: 10.2.0.1/22


6. The first two rules in the forward chain of the filter table are:

/ip firewall filter add chain=forward connection-state=established action=accept

/ip firewall filter add chain=forward connection-state=invalid action=drop

Connection-state=related packets are not filtered by the rules above.

true

false


7. /interface wireless access-list is used for

a. Shows a list of Client’s MAC Address that are already registered at AP

b. Authenticate Hotspot users

c. Handles a list of Client’s MAC Address to permit/deny connection to AP

d. Contains the security profiles settings


8. Possible actions of ip firewall filter are:

a. tarpit

b. tarp

c. bounce

d. add-to-address-list

e. log

f. accept


9. In case when router login password is lost, it is necessary to reinstall RouterOS or use hardware reset funcion.

a. Yes/ True

b. No/ False


10. Which software version can be installed onto the following RouterBoard types?

a. routeros-x86-x.xx.npk on a RB1100

b. routeros-mipsbe-x.xx.npk on a RB133

c. routeros-mipsle-x.xx.npk on RB133

d. routeros-powerpc-x.xx.npk on a RB333

e. routeros-mipsbe-x.xx.npk on a RB433


11. PPP Secrets are used for

a. L2TP clients

b. Router users

c. PPtP clients

d. IPSec clients

e. PPPoE clients

f. PPP clients


12. Choose all valid hosts address range for subnet 15.242.55.62/27

a. 15.242.55.32-15.242.55.63

b. 15.242.55.33-15.242.55.63

c. 15.242.55.33-15.242.55.62

d. 15.242.55.31-15.242.55.62


13. WPA 2 Pre-Shared Key (PSK) is enabled on AP, all your clients have to use the same PSK. Only Virtual AP could be used to allow clients to connect with a different PSK.

false

true


14. Router A and B are both running as PPPoE servers on different broadcast domains of your network. Is it possible to set Router A to use “/ppp secret” accounts from Router B to authenticate PPPoE customers ?

false

true


15. Which of the following actions are available for ‘/ip firewall mangle’ (select all valid actions)

a. change MSS

b. mark connection

c. accept

d. jump

e. drop

f. mark packet


16. OSFP area ID does not need to be unique within the AS.

true

false


17. What configuration is added by /ip hotspot setup command? (select all that apply)

a. /ip dhcp-server

b. /ip service

c. /queue tree

d. /ip hotspot user

e. /ip hotspot walled-garden


18. Mode wireless apakah yang bisa digunakan untuk mengkonfigurasikan WDS?

a. ap-bridge

b. nstreme-dual-slave

c. bridge

d. station-wds

e. station


19. Check all of the DHCP Server Options that are implemented for DHCP-Client and not Custom.

a. WINS Server

b. ntp server

c. DNS Server

d. subnet mask

e. tftp

f. gateway


20. Anda akan menyimpan website yang telah dikunjungi ke dalam sebuah log dari web proxy. Manakah konfigurasi yang benar ?

a. /system logging add topics=web-proxy,debug action=memory

b. /system logging add topics=web-proxy,!debug action=memory

c. /system logging add topics=web-proxy,!debug action=remote

d. /system logging add topics=web-proxy,!debug action=disk


21. You need to set up an E1(T1) connection with PPP configured.

Which License level is needed?

a. Level 4

b. It cannot be done in RouterOS

c. Level 5


22. You have a router with configuration

- Public IP :202.168.125.45/24

- Default gateway:202.168.125.1

- DNS server: 248.115.148.136, 248.115.148.137

- Local IP: 192.168.2.1/24

Mark the correct configuration on client PC to access to the Internet

a. IP:192.168.2.115/24 gateway: 192.168.2.1

b. IP:192.168.0.1/24 gateway:192.168.2.1

c. IP:192.168.2.2/24 gateway:202.168.125.45

d. IP:192.168.1.223/24 gateway:248.115.148.136

e. IP:192.168.2.253/24 gateway:202.168.0.1


23. Mark queue type that uses fairness principle between sub-queues, allows users to choose classifier for sub-queues, and apply a limit to each sub-queue

a. SFQ

b. RED

c. PCQ

d. BFIFO


24. How many different priorities can be selected for queues in MikroTik RouterOS?

a. 1

b. 8

b. 0

d. 16


25. An IP address pool can contain addresses from more than one subnet.

a. True

b. False


------------------------------------------------------------------------------------- SET - 15 -------------------------------------------------------------------------------------


1. Two hosts, A and B, are connected to a broadcast LAN. Select all the answers showing pairs of IP address/mask which would allow IP connections to be established between the two hosts.

a. A: 10.1.2.192/24 and B: 10.1.2.129/26

b. A: 10.1.2.66/25 and B: 10.1.2.109/26

c. A: 10.2.1.0/23 and B: 10.2.0.1/22

d. A: 10.2.2.1/23 and B: 10.2.0.1/22


2. Which features are removed when advanced-tools package is uninstalled?

a. neighbors

b. ip-scan

c. netwatch

d. LCD support

e. ping

f. bandwidth-test


3. Rate Flapping can be avoided by

a. Choose larger channels (40 MHz instead of 20 MHz)

b. Reduce supported rates

c. Change ap-bridge to bridge

d. Set basic rates to only one data rate like 24 Mbps


4. Mark possible connection states in the connection tracking table

a. Related

b. Invalid

c. Closed

d. Established

e. Syn

f. New


5. Can you manually add drivers to RouterOS in case your PCI Ethernet card is not recognized, and you suspect it is a driver issue?

a. Yes

b. No


6. You have a queue structure as follows:

queue “GP” max-limit=10M

- queue “M” parent=”GP” limit-at=4M max-limit=6M

- – queue “C1″ parent=”M” limit-at=1M max-limit=7M priority=4

- – queue “C2″ parent=”M” limit-at=1M max-limit=4M priority=1

- – queue “C3″ parent=”M” limit-at=3M max-limit=7M priority=8

- queue “F” parent=”GP” limit-at=5M max-limit=8M

- – queue “D1″ parent=”F” limit-at=3M max-limit=4M priority=5

- – queue “D2″ parent=”F” limit-at=2M max-limit=5M priority=2

If queues “C1″ and “D2″ will not require any traffic, how the total available traffic is going to be distributed in the worst case scenario?

a. queue “C2″ will get 3M, “C3″ 2M, “D1″ 4M

b. queue “C2″ will get 2M, “C3″ 5M, “D1″ 3M

c. queue “C2″ will get 4M, “C3″ 2M, “D1″ 4M

d. queue “C2″ will get 2M, “C3″ 3M, “D1″ 5M

e. queue “C2″ will get 3M, “C3″ 3M, “D1″ 4M


7. A MikroTik Router has the following configuration

/ip address

add address=1.1.1.2/30 interface=ether1

add address=2.2.2.2/30 interface=ether2

add address=192.168.10.1/24 interface=ether3

/ip firewall mangle

add action=mark-connection chain=prerouting

dst-port=80 new-connection-mark=web_c passthrough=yes protocol=tcp

add action=mark-routing chain=prerouting

connection-mark=web_c new-routing-mark=web passthrough=no

/ip firewall nat

add action=masquerade chain=srcnat

out-interface=ether3

/ip route

add gateway=1.1.1.1

add gateway=2.2.2.2 routing-mark=web

What can be said about the Web Access (port 80) by a customer connected at ether3 interface with IP 192.168.10.2/24, gateway 192.168.10.1 ?

a. The customer will access the Web using the gateway 2.2.2.2

b. The Customer is unable to access the Web.

c. The Customer will access the Web by ECMP, by using both gateways 1.1.1.1 and 2.2.2.2

d. The customer will access the Web using the gateway 1.1.1.1


8. For static routing functionality, additionally to the RouterOS system package, you will also need the following software package:

a. dhcp

b. advanced-tools

c. none

d. routing


9. Which options should be used when you want to prevent access from one specific address to your router web interface?

a. Group settings for System users

b. Firewall Filter Chain Input

c. Firewall Filter Chain Forward

d. WWW service from IP Services


10. Which MikroTik RouterOS version should you use for IEEE 802.11n standard support?

a. Versions 3.x

b. Versions 4.x

c. Versions 5.x


11. A station can connect to AP if they both use different country regulation settings, but the frequency chosen is allowed in both countries


12. How long is level 1 (demo) license valid?

a. 1 year

b. Infinite time

c. 24 hours

d. 1 month


13. Router A and B are both running as PPPoE servers on different broadcast domains of your network. Is it possible to set Router A to use “/ppp secret” accounts from Router B to authenticate PPPoE customers ?

True

False


14. You need to save visited web-pages to memory logs from web-proxy. Which is the correct configuration?

a. /system logging add topics=web-proxy,debug action=memory

b. /system logging add topics=web-proxy,!debug action=disk

c. /system logging add topics=web-proxy,!debug action=remote

d. /system logging add topics=web-proxy,!debug action=memory


15. By default info, error and warning messages are logged into memory of your RouterOS device. You can add logging of visited web-pages and other message topics


16. Netinstall can be used to

a. Keep configuration, but reset a lost admin password

b. Install different software version (upgrade or downgrade)

c. Reinstall software without losing licence

d. Install package for different hardware architecture


17. Which options are necessary to use the HotSpot Universal Client feature?

a. arp=enabled on the HotSpot interface

b. /ip dhcp-server configuration

c. address-pool configuration in /ip hotspot and /ip hotspot user profile

d. /ip firewall mangle rules


18. What is the correct action to be specified in the NAT rule to hide a private network when communicating to the outside world?

a. tarpit

b. masquerade

c. passthrough

d. allow


19. Mark all features that are compatible with Nstreme

a. WDS between a device in ap-bridge mode with a device in station-wds mode

b. Bridging a device in station mode with a device in ap-bridge mode

c. Encryption

d. WDS between a device in station-wds mode and a device in station-wds mode


20. PPP Secrets are used for

a. L2TP clients

b. IPSec clients

c. PPPoE clients

d. PPtP clients

e. Router users

f. PPP clients


21. What is term for the hardware coded address found on an interface?

a. MAC Address

b. Interface Address

c. FQDN Address

d. IP Address


22. Which default route will be active?

/ip route

add disabled=no distance=10 dst-address=0.0.0.0/0 gateway=1.1.1.1

add disabled=no distance=5 dst-address=0.0.0.0/0 gateway=2.2.2.2

a. Route via gateway 2.2.2.2

b. Route via gateway 1.1.1.1


23. You would like to allow multiple logins with one user name on a HotSpot server. How should this be configured?

a. Set “Shared Users” option at /ip hotspot user profile

b. Set “only-one=no’ at /ip hotspot

c. It’s not possible

d. Set “Shared Users” option at /ip hotspot


24. To assign specific traffic to the route – traffic must be identified by routing mark.Each packet can have only one routing mark.

true

false


25. What can be used as ’target-address’ in the simple queue?

a. client’s MAC address

b. address list name

c. client’s address

d. server’s address


------------------------------------------------------------------------------------- SET - 16 -------------------------------------------------------------------------------------


Networking Basics

1. How long is an IPv6 address?
a. 32 bits
b. 128 bytes
c. 64 bits
d. 128 bits

2. What flavor of Network Address Translation can be used to have one IP address allow many users to connect to the global Internet?
a. NAT
b. Static
c. Dynamic
d. PAT

3. What are the two main types of access control lists (ACLs)?
Standard
IEEE
Extended
Specialized
 

a. 1 and 3
b. 2 and 4
c. 3 and 4
c. 1 and 2

4. What command is used to create a backup configuration?
a. copy running backup
b. copy running-config startup-config
c. config mem
d. wr mem

5. You have 10 users plugged into a hub running 10Mbps half-duplex. There is a server connected to the switch running 10Mbps half-duplex as well. How much bandwidth does each host have to the server?
a. 100 kbps
b. 1 Mbps
c. 2 Mbps
d. 10 Mbps
 

6. Which WLAN IEEE specification allows up to 54Mbps at 2.4GHz?
a. A
b. B
c. G
d. N

7. Which of the following is the valid host range for the subnet on which the IP address 192.168.168.188 255.255.255.192 resides?
a. 192.168.168.129-190
b. 192.168.168.129-191
c. 192.168.168.128-190
d. 192.168.168.128-192

8. To back up an IOS, what command will you use?
a. backup IOS disk
b. copy ios tftp
c. copy tftp flash
d. copy flash tftp

9. What protocol does PPP use to identify the Network layer protocol?
a. NCP
b. ISDN
c. HDLC
d. LCP

10. Which of the following commands will allow you to set your Telnet password on a Cisco router?
a. line telnet 0 4
b. line aux 0 4
c. line vty 0 4
d. line con 0

11. Which protocol does DHCP use at the Transport layer?
a. IP
b. TCP
c. UDP
d. ARP

12. Which command is used to determine if an IP access list is enabled on a particular interface?
a. show access-lists
b. show interface
c. show ip interface
d. show interface access-lists

13. Where is a hub specified in the OSI model?
a. Session layer
b. Physical layer
c. Data Link layer
d. Application layer

14. What does the passive command provide to dynamic routing protocols?
a. Stops an interface from sending or receiving periodic dynamic updates.
b. Stops an interface from sending periodic dynamic updates but not from receiving updates.
c. Stops the router from receiving any dynamic updates.
d. Stops the router from sending any dynamic updates.

15. Which protocol is used to send a destination network unknown message back to originating hosts?
a. TCP
b. ARP
c. ICMP
d. BootP

16. How often are BPDUs sent from a layer 2 device?
a. Never
b. Every 2 seconds
c. Every 10 minutes
d. Every 30 seconds

17. How many broadcast domains are created when you segment a network with a 12-port switch?
a. 1
b. 2
c. 5
d. 12

18. What does the command routerA(config)#line cons 0 allow you to perform next?
a. Set the Telnet password.
b. Shut down the router.
c. Set your console password.
d. Disable console connections.

19. Which router command allows you to view the entire contents of all access lists?
a. show all access-lists
b. show access-lists
c. show ip interface
d. show interface

20. Which class of IP address has the most host addresses available by default?
a. A
b. B
c. C
d. A and B

21. In a network with dozens of switches, how many root bridges would you have?
a. 1
b. 2
c. 5
d. 12

22. What PPP protocol provides dynamic addressing, authentication, and multilink?
a. NCP
b. HDLC
c. LCP
d. X.25

23. What is a stub network?
a. A network with more than one exit point.
b. A network with more than one exit and entry point.
c. A network with only one entry and no exit point.
d. A network that has only one entry and exit point.

24. If your router is facilitating a CSU/DSU, which of the following commands do you need to use to provide the router with a 64000bps serial link?
a. RouterA(config)#bandwidth 64
b. RouterA(config-if)#bandwidth 64000
c. RouterA(config-if)#clock rate 64
d. RouterA(config-if)#clock rate 64000

25. Which one of the following is true regarding VLANs?
a. Two VLANs are configured by default on all Cisco switches.
b. VLANs only work if you have a complete Cisco switched internetwork. No off-brand switches are allowed.
c. You should not have more than 10 switches in the same VTP domain.
d. VTP is used to send VLAN information to switches in a configured VTP domain.

26. What does a VLAN do?
a. Acts as the fastest port to all servers.
b. Provides multiple collision domains on one switch port.
c. Breaks up broadcast domains in a layer 2 switch internetwork.
d. Provides multiple broadcast domains within a single collision domain.

27. What is the main reason the OSI model was created?
a. To create a layered model larger than the DoD model.
b. So application developers can change only one layer's protocols at a time.
c. So different networks could communicate.
d. So Cisco could use the model.

28. How many collision domains are created when you segment a network with a 12-port switch?
a. 1
b. 2
c. 5
d. 12

29. What command will display the line, protocol, DLCI, and LMI information of an interface?
a. sh pvc
b. show interface
c. show frame-relay pvc
d. show run

30. Which protocol does Ping use?
a. TCP
b. ARP
c. ICMP
d. BootP

31. Which command is used to upgrade an IOS on a Cisco router?
a. copy tftp run
b. copy tftp start
c. config net
d. copy tftp flash

32. If you wanted to delete the configuration stored in NVRAM, what would you type?
a. erase startup
b. erase nvram
c. delete nvram
d. erase running

33. What protocols are used to configure trunking on a switch?
VLAN Trunking Protocol
VLAN
802.1Q
ISL
 

a. 1 and 2
b. 3 and 4
c. 1 only
d. 2 only

TCP/IP

1. Which of the following services use TCP?
DHCP
SMTP
HTTP
TFTP
FTP

a. 1 and 2
b. 2, 3 and 5
c. 1, 2 and 4
d. 1, 3 and 4

2. What layer in the TCP/IP stack is equivalent to the Transport layer of the OSI model?
a. Application
b. Host-to-Host
c. Internet
d. Network Access

3. Which of the following describe the DHCP Discover message?
It uses FF:FF:FF:FF:FF:FF as a layer 2 broadcast.
It uses UDP as the Transport layer protocol.
It uses TCP as the Transport layer protocol.
It does not use a layer 2 destination address.

a. 1 only
b. 1 and 2
c. 3 and 4
d. 4 only

4. You want to implement a mechanism that automates the IP configuration, including IP address, subnet mask, default gateway, and DNS information. Which protocol will you use to accomplish this?
a. SMTP
b. SNMP
c. DHCP
d. ARP


5. Which of the following is private IP address?
a. 12.0.0.1
b. 168.172.19.39
c. 172.15.14.36
d. 192.168.24.43

6. Which of the following allows a router to respond to an ARP request that is intended for a remote host?
a. Gateway DP
b. Reverse ARP (RARP)
c. Proxy ARP
d. Inverse ARP (IARP)


7. The DoD model (also called the TCP/IP stack) has four layers. Which layer of the DoD model is equivalent to the Network layer of the OSI model?
a. Application
b. Host-to-Host
c. Internet
d. Network Access

8. Which of the following services use UDP?
DHCP
SMTP
SNMP
FTP
HTTP
TFTP

a. 1, 3 and 6
b. 2 and 4
c. 1, 2 and 4
d. All of the above

9. Which class of IP address provides a maximum of only 254 host addresses per network ID?
a. Class A
b. Class B
b. Class C
d. Class D

10. If you use either Telnet or FTP, which is the highest layer you are using to transmit data?
a. Application
b. Presentation
c. Session
d. Transport

11. Which of the following is the decimal and hexadecimal equivalents of the binary number 10011101?
a. 155, 0x9B
b. 157, 0x9D
c. 159, 0x9F
d. 185, 0xB9

12. Which statements are true regarding ICMP packets?
They acknowledge receipt of a TCP segment.
They guarantee datagram delivery.
They can provide hosts with information about network problems.
They are encapsulated within IP datagrams.

a. 1 only
b. 2 and 3
c. 3 and 4
.d 2, 3 and 4

13. Which of the following are layers in the TCP/IP model?
Application
Session
Transport
Internet
Data Link
Physical

a. 1 and 2
b. 1, 3 and 4
c. 2, 3 and 5
d. 3, 4 and 5

14. Which layer 4 protocol is used for a Telnet connection?
a. IP
b. TCP
c. TCP/IP
d. UDP

15. Which statements are true regarding ICMP packets?
ICMP guarantees datagram delivery.
ICMP can provide hosts with information about network problems.
ICMP is encapsulated within IP datagrams.
ICMP is encapsulated within UDP datagrams.

a. 1 only
b. 2 and 3
c. 1 and 4
b. All of the above


16. Which of the following are TCP/IP protocols used at the Application layer of the OSI model?

IP
TCP
Telnet
FTP
TFTP

a. 1 and 3
b. 1, 3 and 5
c. 3, 4 and 5
d. All of the above

17. What protocol is used to find the hardware address of a local device?
a. RARP
b. ARP
c. IP
d. ICMP

18. Which of the following protocols uses both TCP and UDP?
a. FTP
b. SMTP
c. Telnet
d. DNS

19. What is the address range of a Class B network address in binary?
a. 01xxxxxx
b. 0xxxxxxx
c. 10xxxxxx
d. 110xxxxx
