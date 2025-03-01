Download link :https://programming.engineering/product/problem-set-2-solutions-network-fundamentals-routing-and-subnetting/

# Problem-Set-2-Solutions-Network-Fundamentals-Routing-and-Subnetting
Problem Set #2 Solutions | Network Fundamentals, Routing, and Subnetting
Problem 1 (6pts)

Explain collision domain and broadcast domain with respect to a hub, switch, and a router.



Problem 2 (5pts)

Consider the following networked computers connected by Bridge X and Y. Bridge X has interface 1,2 and3. Bridge Y has interface 1 and 2. Assume at the beginning the address tables of Bridge X and Y are all empty. Write down the address tables of Bridge X and Y after the following communication finished.

A send a packet to C
B send a packet to D
C send a packet to E
E send a packet to A
D send a packet to A

Figure 1

Bridge X Bridge Y

Address

Interface

 


Address

Interface




Problem 3 (5pts)

Given the extended LAN shown in Figure 2, indicate which ports are not selected by the spanning tree algorithm. Note that the bridge with the smallest ID becomes a root.




Figure 2


Problem 4 (5pts)

Still considering Figure 2. If Bridge B1 suffers catastrophic failure. Again indicate which ports are not selected by the spanning tree algorithm.



Problem 5 (6pts)

Draw a time line diagram for the sliding window algorithm with SWS = RWS = 3 frames, for the following situations. Use a timeout interval of about 2 × RTT. And assume 2 frames must be send ½ RTT apart which means if everything is normal Sender will receive ACK and then immediately send the next frame.

Frames 3 and 6 are lost on their first transmissions. Draw the algorithm with time line diagram till Frame 6 is sent. (6pts)









Problem 6 (6pts)

Consider the GBN protocol with a sender window size of N=4 and a sequence number range of 1,024. Suppose that at time t, the next in-order packet that the receiver is expecting has a sequence number of k. Assume that the medium does not reorder messages. Answer the following questions:


(a) What are the possible sets of sequence numbers inside the sender’s window

at time t? Justify your answer. (2 pts)



(b) What are all possible values of the ACK field in all possible messages currently

propagating back to the sender at time t? Justify your answer. (2 pts)



(c) With the Go-Back-N protocol, is it possible for the sender to receive an ACK for a packet that falls outside of its current window? Justify your answer with an example. (2 pts)



Problem 7 (10 points)

Is 10.72.0.255/255.255.254.0 a valid IP address for a host? [2pts]
Divide the 10.72.0.0/16 subnets into five large networks of 8192 IPs each, 8 medium-sized networks of 2048 IPs each, and 10 small sized networks of 128 IPs each. [6pts]
Is 192.168.2/23 and 192.168.3/23 representing the same subnet? Please justify your answer. [2pts]
Problem 8 (8 points)

An organization has been assigned the prefix 192.168.1.0/23 and wants to form subnets for 4 departments which have the following number of hosts:

Department A: 130 hosts

Department B: 120 hosts

Department C: 60 hosts

Department D: 31 hosts

Give a possible arrangement of subnet masks to make this possible. [5pts]
Suggest what the organization might do if department C grows to 65 hosts. [3pts]




Problem 9 (12 points)

For the network given below in Figure 3, give global distance-vector tables for each node when:


Figure 3

Each node knows only the distance of its immediate neighbors. [4pts]
Each node has reported the information it had in the first step (a) to its immediate neighbors. [4pts]
Repeat step (b) one more time. [4pts]





Problem 10 (8 points)

Again for the network graph in Figure. 3. Show how the link-state algorithm builds the routing table for node D.

Show the detailed steps with the link-state algorithm. [5pts]
Show the final routing table of node D. [3pts]

Problem 11 (6 points)

The network graph is shown in Figure. 4.


Figure 4

Host H1 sends a packet to the destination 128.96.34.126. Explain how this packet traverses in the network described below. You need to describe who received the packet and what are their reactions. [2pts]
Host H3 sends a packet to the destination 128.96.34.250. Explain how this packet traverses in the network. [2pts]

 

 

The subnet of H1 has now two different teams and would like to split it into two subnets. Please add one more subnet and add R3 and change the network configurations as you need. Note that you are allowed to modify the network as least disruptive as possible. [2pts]


Problem 12 (8 points)


Figure. 5


Above in Figure 5 is the network graph with 4 routers (R1, R2, R3, R4) and 4 hosts (A, B, C, D). Each router interfaces and hosts are labeled with both IP and MAC address, Routing is enabled so that any two hosts can communicate with each other and also the default gateway of each host is set to its gateway router.


Suppose that B send an IP packet to C through R3, R2, R4. Write down the IP packet’s content (src MAC, dst MAC, src IP, dst IP) along the path in the Table given below: [4pts]


src MAC

dst MAC

src IP

dst IP

B -> R3

R3 -> R2

R2 -> R4

R4 -> C

Table. 1


When A sends out an ARP query for its default gateway, what is the reply to that query? [2pts]

Suppose the routers use link-state routing protocol, what will be R3’s routing table entries? [2pts]




Problem 13 (6 points)

Suppose a computer just boot up, connected to wireless network and successfully obtained IP, gateway and DNS address. Now it wants to access www.yahoo.com from its browser. Describe the sequence of packets exchanged to and from this computer until the webpage starts to load. (include what kind of protocol is used and what is the content of the packets)



Problem 14 (9 points)

Consider the simple network in Figure 5 below. X, Y and Z are routers and their link costs are as specified. Assume the network uses a Distance Vector algorithm is used. Y’s and Z’s routing tables are look like Table 2.



Figure. 5

Node Y/Distance

Via X

Via Z

X

4

6

Node Z/Distance

Via X

Via Y

X

50

5

Table. 2



Now Let assume the cost of link X-Y suddenly changed to 100. Please write down the Y’s and Z’s routing table regarding distance to X, after Y updates this information to Z and then Z updates its information back. [3pts]

Please write down the Y’s and Z’s routing table regarding X after Y updates this information to Z again and then Z updates back again. [3pts]

How many updates did Y get until its distance to X have converged with Distance Vector algorithm? [3pts]


