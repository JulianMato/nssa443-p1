# <center>**Case Study #1**</center> <center> By Julian Mato-Hernandez & Evan Jurdan </center>
# Executive summary:
For this network the customer needed a nearly complete ground up design of their network. This network contains new equipment (PC, Laptops, Infrastructure, and security devices) along with a host of software (Email, Storage, Network Monitoring, and security). The customer needs these basic services to be as reliable and functional as possible. We will be providing a cloud based work environment centered around Microsoft Azure, this will provide AD, Storage, backups, email, notifications, and parts of security. Along with this cloud infrastructure we will be providing a Full unified wired and wireless network to both buildings. 
<br>
<br>
<br>

# Introduction:
    
## Project Outline
In this paper we will be discussing all components of the customers network that where addressable along with recommendations for next steps. This network has a breath of constraints including but not limited to needing to connect both buildings, providing inter department file transfer, internet access, wireless networking, reliability, budget in expandability, and all within $100,000. We chose a cloud hybrid solution to maximise reliability and expandability along with easing the cost of onsight IT with service contracts from a cloud provider.

## Document Outline
- [Executive summary](#executive-summary)
- [Introduction](#introduction)
    - [Project Outline](#project-outline)
    - [Document Outline](#document-outline) 
- [Requirements Analysis](#requirements-analysis)
    - [General Requirements](#general-requirements)
    - [Hardware Requirements](#hardware-requirements)
    - [Software Requirements](#software-requirements)
- [Customer Synopsis](#customer-synopsis)
- [Network Architecture](#network-architecture)
    -[Three tier architecture](#three-tier-architecture)
- [Network Maps](#network-maps)
    - [Building Scematic](#building-scematic)
    - [Drops And Host Names](#drops-and-host-names)
- [Populating the Network](#populating-the-network)
    - [Device Map](#device-map)
- [Budget / Justification](#budget--justification)
- [Scalability Considerations](#scalability-considerations)
- [Summary and Comments for Future Growt](#summary-and-comments-for-future-growt)
<br>
<br>
<br>

# Requirements Analysis:

## General Requirements     
This building had only a small network in acounting. The buisness needed to have Computers for employees and secure storage and trasfer of confidential records. They are a government buisness and need their data to be secure but they also needed to be able to share between certaint departments and better analize data. 
<br>
<br>

## Hardware Requirements    
The company needed an entire network from scratch. They needed a desktop computer per employee as well as a laptop per employee. There were also 54 micro computers to put in classroom labs. Each desktop and micro computer needed a monitor and periferals. We needed to design a network and purchase the hardware to put it in place so we had to buy switches, a support server, and access points to implement the network that they wanted. We planned all of the cat6 cable runs throughout the building as well as the fiber lines connecting our layer 3 switches and the fiber connection under the road to the other building. They wanted a lot of office printers and a larger printer/scanner/coppier, in order to better fit in the buget not everyone could get individual printers but the people we didn't give a printer to are in extream close proximity to the large comunal printer. We mapped where there should be power drops, each power drop would have 4 connections and each internet drop would have 2 connections. 
<br>
<br>

## Software Requirements    
Since it is a government organization they needed a secure network and a secure storage. the AZURE suite had all of the components needed to build a network that was secure and accessable. We have secure storage set up and backed up with a seperate storage for accounting for added security. AZURE also has active directory so our network has security that insures only people who are allowed to look at or edit something are allowed to view it. We also have office 365 for each person so that they have access to word prossesing, spreadsheet, and presentation software to aid in the recording of information, the analizing of data, and the formation of presentations.  
<br>
<br>
<br>

# Customer Synopsis:
The customer wanted a network that met the reuirements listed in the document. They were unsure what type of network and seemed to not be particular about how we structured it. They didn't have restrictions on hardware and their only request was that every employee needed a laptop as well as their desktop. 
<br>
<br>
<br>

# Network Architecture:

## Three tier architecture
![Figure 1](ThreeTeirArchitecture.png "Three tier architecture")
<br>
<br>
<br>

# Network Maps:
![Figure 2](NetworkMap.png "Three tier architecture")
<br>
<br>

## Building Scematic
![Figure 4](BuildingScematic.png "Room #'s")
<br>
<br>

## Drops And Host Names
![Figure 3](DropsAndHostNames.png "Power and Network Drops")
<br>
<br>
<br>

# Populating the Network:

## Device Map
![Figure 5](FullMap.png "All devices")
<br>
<br>
<br>

# Budget / Justification:

## Cloud
![Figure 6](Budget-cloud.png "Budget-spread sheet(only cloud)")

## Final
![Figure 6](Budget.png "Budget-spread sheet")
<br>
We went a little over budget and it was extreamly dificult to trim it down this much. we also feel that the security in the building is not up to the standards required by government buissnesses and have several plans to discuss further regaurding how to make things more secure. unfortunatly there was no budget to build a networking lab though if we could extend the buget a bit we could get together a rudimentary networking lab.
<br>
<br>
<br>

# Scalability Considerations:
With the spine and leaf topology you could add more switches to the network following how the existing switches are set up and easily expand to another building or use the AZURE suite to expand to more locations or to expand storage capacity. The wireless network is able to be added to in a similar way and you could add more access points or even other switches with access points connected to expand the network. We also secmented the network into vlans based on department and if nessisary other vlans could be added for incoming departments or more computers could be added to existing networks easily.  
<br>
<br>
<br>

# Summary and Comments for Future Growt:
in summary here is a layout, scematics, and price of a new network install. It is an incredibly secure network up to government standards and it turns this building with no technology in it into a very extensive network. There is a secure and redundant Lan with a desktop for each employee. There is a wifi network for all of the classroom computers that will help facilitate learning and that wifi also allows the employees to take their work from their desk to meetings or presentations securly with their secure laptop instead of a flash drive or some less secure medium. There is a guest wifi seperated from the other vlans to keep things secure. the secondary building has a direct connection to the network and the classroom there has micro computers to help learn as well. There is space on the switch to add more connections or even other close buildings and the AZURE suite lets there be other locations that securly connect to the same storage if more locations are founded in the future. 