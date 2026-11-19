## What is the difference between a server and a client?

So client is a device or a program who asks for a service or information and server is a device who receives information, checks it and sends back information.

### Part 1 - Building a topology : 
Below is an example of a connection of two PC namely PC0 and PC1 which are connected via a **Copper Straight-Through** cable to a **Switch 2960** and from there to a **Server**

Below is the first party of the how i connected them : 
- PC0 `FastEthernet0` → Switch `FastEthernet0/1`
- PC1 `FastEthernet0` → Switch `FastEthernet0/2`
- Server0 `FastEthernet0` → Switch `FastEthernet0/3`
- I waited alittle so that the lights become green from red.


![[Screenshot 2026-11-19 092314.png]]

### Part 2 - Configuration of the IP addresses :

In to build a functioning LAN or Network I configured and gave IPs to all the PCs and the Server, I used a **Static** IP configuration.

In order to give an IP to the PCs or the server I clicked on them and went to the **Desktop tab** and selected **IP configuration** and choose **Static**

#### Configuration de PC0

![[Screenshot 2026-11-19 092336.png]]
#### Configuration de PC1

![[Screenshot 2026-11-19 092348.png]]
#### Configuration de Server0

![[Screenshot 2026-11-19 092404.png]]

![[Screenshot 2026-11-19 092336.png]]


![[Screenshot 2026-11-19 093036.png]]

![[Screenshot 2026-11-19 093027.png]]

![[Screenshot 2026-11-19 092803.png]]

![[Screenshot 2026-11-19 092459.png]]

![[Screenshot 2026-11-19 092445.png]]

![[Screenshot 2026-11-19 092422.png]]





