# BGP Route-Reflector and Confederation
This lab explore the fundamentals of Route Reflector and Confederation in BGP to help reduce the mesh overhead in iBGP.

## Route Reflector
Implementing Route Reflector is not a straight-forward method. You need to consider several rules when implementing Route Reflector such as:
* Update received by Route Reflector



![alt text](https://github.com/meorkamalmeorsulaiman/BGP-Route-Reflector-and-Confederation/blob/main/Topology.PNG)

## Lab Details:
* BGP
  * Transit ASs are AS200 and 300.
  * Route-reflector implemented in AS200.
  * BGP Confederation implemented in AS300.
  * AS65200 is a mesh iBGP.
 
* Overlay Routing
  * EIGRP - AS200
  * OSPF - AS300
