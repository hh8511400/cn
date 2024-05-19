VLan 3 Networks 

3 Networks 1 switch 1 Router

in Pc assign gateway and Ip address

in switch create an 3 vlan and add ports

interface fa0/1
switchport mode access 
switchport access vlan 10

in router no sh for port 

then enter these commands for each vlan:
interface GigabitEthernet 0/0.10 
encapsulation dot1Q 10
ip address 192.168.1.5 255.255.255.0
192 is gateway 

Router : Router pt
Switch : 2950 24


RIP
RIP

2 router 
2 switch
4 pc

switch nothing 2950-24

Router : 
no sh all interfaces
router rip
Router to Router interface
interface Serial2/0
network 192.168.2.0 now:next router change according to it
network 10.0.0.0 

Assign ip to serial

interface Serial2/0
ip address 10.0.0.2 255.0.0.0
2 replace with 3 in next router



Assign ip to interface

interface fastEthernet 0/0
ip address 192.168.2.1 255.255.255.0

OSPF
OSPF

assign gateway and ip to pc

command : router rip
 
in router ip add all networks in topologies: 
commands :
network 192.168.2.1 
network 192.168.1.1
network 192.168.3.1
network 10.0.0.0
network 20.0.0.0


in 3 routers we need three networks
10.0.0.0
20.0.0.0
30.0.0.0

assing ip all interfacs in router
commands:  
interface Serial2/0 
ip address 10.0.0.9 255.0.0.0
 







OSPF
 commands
router ospf 1 
 network 10.0.0.0 0.255.255.255 area 0
network 192.168.1.0 0.0.0.255 area 0

Like that add all networks in subnet mask replace binary 0 with 1 and 1 with 0

