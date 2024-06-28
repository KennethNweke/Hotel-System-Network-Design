# Hotel System Network Design
![NH](https://github.com/KennethNweke/NetworkHardening/assets/88651458/e312b440-647a-4155-8c35-fb4cf460206b)

## Objective








As a part of your end year networking project, you are required to design and implement Vic Modern Hotel network. The hotel has three floors; in the first floor there three departments (Reception, store and Logistics), in the second floor there are three departments (Finance, HR and Sales/Marketing), while the third floor hosts the IT and Admin. Therefore, the following are part of the considerations during the design and implementation;
There should be three routers connecting each floor (all placed in the server room in IT department).
All routers should be connected to each other using serial DCE cable.
The network between the routers should be 10.10.10.0/30,10.10.10.4/30 and 10.10.10.8/30.
Each floor is expected to have one switch (placed in the respective floor).
Each floor is expected to have WIFI networks connected to laptops and phones.
Each department is expected to have a printer.
Each department is expected to be in different VLAN with the following details;
1st Floor;
- Reception- VLAN 80, Network of 192.168.8.0/24
- Store- VLAN 70, Network of 192.168.7.0/24
- Logistics- VLAN 60, Network of 192.168.6.0/24
2nd Floor;
- Finance- VLAN 50, Network of 192.168.5.0/24
- HR- VLAN 40, Network of 192.168.4.0/24
- Sales- VLAN 30, Network of 192.168.3.0/24
3rd Floor;
- Admin- VLAN 20, Network of 192.168.2.0/24
- IT- VLAN 10, Network of 192.168.1.0/24

Use OSPF as the routing protocol to advertise routes.
All devices in the network are expected to obtain IP address dynamically with their respective router configured as the DHCP server.
All the devices in the network are expected to communicate with each other.
Configure SSH in all the routers for remote login.
In IT department, add PC called Test-PC to port fa0/1 and use it to test remote login.
Configure port security to IT-dept switch to allow only Test-PC to access port fa0/1 (use sticky method to obtain mac-address with violation mode of shutdown.)









































## Skills Learned

- **Vulnerability Assessment**:
  - Conducting thorough vulnerability scans and preliminary tests on commandline.
  - Analyzing scan results to identify and prioritize network vulnerabilities.



## Tools Used
- Network Simulation
- Packet Tracer



## Resources
Full PT File and Documentation below.
  - [Kenneth Nweke - Network Hardening PT File](https://drive.google.com/file/d/1ZIx2nJbQ4dz31UHAGyo1UcuZNtdKV9jN/view?usp=sharing)
  -  [Kenneth Nweke - Network Hardening.pdf](https://github.com/user-attachments/files/15987380/Kenneth.Nweke.-.Network.Hardening.pdf)
  -  [Config.txt](https://github.com/user-attachments/files/16028626/Config.txt)
