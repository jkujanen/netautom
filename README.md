# Lab Setup
Simple lab for testing ansible
### Equipment:
R1,R2,R3 Cisco CSR1000v, group "ios_devices"
R4, R5 Cumulus Linux,  group "cl_devices"

### Topology:

          R1
         /  \
       R2----R3
       |     |
       R4----R5

 
### Access and Addressing:
Access by SSH: ansible/ansible
#### Management Addresses:
R1: 192.168.122.11

R2: 192.168.122.12

R3: 192.168.122.13

R4: 192.168.122.14

R5: 192.168.122.15

#### Link addresses:
192.168.RouterlowRouterhigh.router/24
for example R2-R3:
R2: 192.168.0.2/24
R3: 192.168.0.3/24

### 
