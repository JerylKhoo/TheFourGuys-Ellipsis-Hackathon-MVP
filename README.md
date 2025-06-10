# Ellipsis-Hackathon-MVP

This is a Minimum Viable Product for the Ellipsis Hackathon 2024. It is a website written in HTML, using proprietaries from OneMap and Looker Studio. 

### TheFourGuys

Thank you for checking out our project and we hope that it has displayed the team spirit of this team!

This [README](README.md) file contains the information you need to get started with the project.

## Project Introduction
We would like to formerly introduce our project called TheFourGuys and we decided to tackle the issue of crowd control and public security. Crowd control and public security are essential for ensuring safety, maintaining order, and preventing crime in various settings. Effective management helps avoid accidents, emergencies, and violence while creating a positive experience for people. By coordinating responses to crises, deterring criminal activities, and fulfilling legal and ethical responsibilities, these measures protect individuals and enhance overall public well-being.

To tackle the issues stated above, our solution includes a web application with a live map with crowd traffic, live dashboard with crowd traffic statistics and best route calculation with crowd traffic. We are able to calculate live traffic using routers to generate a rough model of people walking around. The routers combined with MegaMIMO can provide unlimited wireless scaling catering to the needs of the attendees and fixing the spectrum crunch issue. Our live dashboard converts critical information from the routers into comprehensive data for the stakeholders. A live heat map will provide the user with an easier understanding of the current situation. Using OneMap API in conjunction with the data obtained, we can do a real-time generation of the best path.

## Network Architecture and Diagram
### Traditional Network Architecture (Refer to Traditional Network Architecture.jpg)
In the traditional network architecture, we are able to see 2 client computers connected to the switch, router and to the cloud which is an internal network. The cloud is connected to a database and the 3 routers above. The 3 routers are connected to 3 switches, which are connected to 3 wireless routers and each wireless router is connected to 3 cellular phones.

The number of connections that the cellular phones connect to the wireless router are limited and performance depletes when more and more users are connected to the wireless router.

### MegaMINO Network Architecture (Refer to MegaMINO Technology Network Architecture.jpg)
However, MegaMINO network technology takes a different approach when connected to the users. The MegaMINO configured wireless routers are interconnected and work together to support the cellular devices. The cellular devices are not limited to certain wireless routers and are able to connect to the internet through multiple channels. This drastically improves the speed and number of users that are able to gain connectivity to the internet.

### MegaMINO Advantages
MegaMINO presents multiple advantages compared to traditional networks.

The 2 most significant advantages are user capacity and network scalability. User capacity in traditional networks are limited in number of simultaneus users it can support effectively. As more users connect, individual performance can degrade due to shared bandwidth and increased interference. MegaMINO networks however support a higher number of simultaneous users with minimal degradation in performance. It also has enhanced capacity and ability to serve multiple users more efficiently due to increased data rates and reduced interference.

Scaling up in traditional networks require increasing bandwidth or adding more access points, which can be costly and complex. Additionally, performance can diminish as network load increases. MegaMINO increases scalability by adding more antennas or leveraging advanced MIMO configurations. It has more robust performance under increased load, making it easier to scale without compromising quality.

In summary, MIMO technology represents a significant advancement over traditional wireless networking methods by enhancing data throughput, reliability, coverage, spectral efficiency, and user capacity. While MIMO networks are more complex and require advanced technology, the benefits they provide make them a superior choice for modern wireless communication needs.

## Limitations
### 1. Hosting the website locally
Since this is just our prototype, we are unable to host the webpage on a server, which brought about some functions that we are unable to utilize. Firstly we are unable to call some of the API that we intended to use. Therefore, our route planner was unable to work properly adn would only be able to show a moveable map proudced by OneMAP API. Furthermore, we were also unable to make use of an SQL server as looker studio was an online service that was uncompatiable with our local host. However we had a workaround for this case which is by using Google Sheets for the scenario.

### 2. Hardware
We were unable to get the resources for the hardware portion of the project such as the routers for the routing part of the project, therefore, we only managed to come up with our software, the webpage.

## Setting Up
Download the zip file and extract all the files and folders into a designated folder. From there you can run the index.html file to start our webpage up. Please also do ensure that your internet browser has been logged into SMU's google email for the dashboard to work.
