# Net_Practice

![Alt Text](networking1.jpg)


* **what is a Network:**
    is a connection between tow or more devices.


* **how two computers connect:**


* **what is data:**


* **how the data sends and receives over the network:**


* **why we need subneting:**

* **What is an IP Address:**


* **What is a Router:**
    + a Router is a hardware component that takes care of routing packets.
    + It determines which node the packet came from and which destination node the sender node want to send it to.
    + Routers have a specific “Routing Protocol” which defines how routers communicate with each other.
    + Routers build up a “Routing Table” which identifies the most optimized paths to be taken in the network while sending packets.
    

* **What is a Routing Table:**
    + Is a table with the list of **routes** from one router to other.
    + Each route consists of the address of the other routers/nodes in the network and how to reach them.
    + A "Routing Table" has : Destination IP Address, Gateway, Genmask/Subnet mask, Flags, Iface (Network interface).
    + The main purpose of a routing table is to help routers make effective routing decisions.
    + Whenever a packet is sent through a router to be forwarded to a host on another network, the router consults the routing table
        to find the IP address of the **destination device** and the best path to reach it. 



* **What is a Gateway:**
    + A Gateway is the component which connects two networks.
    + Usually, the gateways are nothing but the routers.


* **What is Genmask/Subnet mask:**
    + A subnet mask is a number which when combined with an IP address allows you to divide
        the IP space into smaller and smaller chunks for use in both physical and logical networks.


* **NAT (Network Address Translation):**
    + It is a fundamental networking technique used to allow multiple devices within a local network
    to share a single public IP address when connecting to the internet. 
    + It serves several purposes in networking: 
        + Address Conservation: allowing multiple devices on a network to share a single public IP helps conserve the limited pool of available IPv4 addresses.
        + Security: NAT acts as a basic firewall by hiding the internal IP addresses of devices on the local network. 


* **Dynamic Host Configuration Protocol (DHCP):**
    Is responsible for assigning dynamic IP addresses to the hosts.


* **Domain Name System/Server (DNS):**
    Is a server having huge records of domain name mapping IP addresses which searches for the domain
        input and returns the respective IP address of the machine on which the website you want to access is hosted.


* **Internet Service Providers (ISPs):**
    + Are the companies that provide everyone Internet.
    + ISPs provide internet, handle routing your requests to the correct destination, resolve domain names with the help of DNS cache that they maintain,
        and handle all this network infrastructure which enables us to use the internet.


* **OSI (Open Systems Interconnection) Module:**

    ![Alt Text](osi_model.jpg)

    OSI Module used to understand how data is transford from one computer to anouthe in a computer network.
    + **Application layer:**
    + **Presentation Layer:**
    + 
    + 
    + 
    + 
    + 

* **IP/TCP Module:**
    ![Alt Text](tcp_ip.png)   

    The TCP/IP model is a set of protocols used for communication on the internet
    + Application layer:

    + Transpot Layer:

    + Network Layer :

    + Physical Layer : 

* **TCP vs UDP:**
    + TCP:
    + UDP:

This project is a general practical exercise to let you discover networking.

* **youtube playlists to whatch:**
    + Networking 101 series https://www.youtube.com/playlist?list=PLMTCTd3b8IdLkjpCLrxbFKTY6CTlaMPco
    + Free ccna playlist https://www.youtube.com/playlist?list=PLIhvC56v63IJVXv0GJcl9vO5Z6znCVb1P
    + Networking tutorial https://www.youtube.com/playlist?list=PLowKtXNTBypH19whXTVoG3oKSuOcw_XeW
