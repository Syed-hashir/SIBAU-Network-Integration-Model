# SIBAU Network Integration Model

## Project Overview  
The **SIBAU Network Integration Model** demonstrates the design and implementation of a secure and scalable campus network connecting **Sukkur IBA University's Main Campus** and **Khairpur Campus**. This project is built using **Cisco Packet Tracer** to simulate network configurations, routing, and security measures, providing a comprehensive solution for inter-campus connectivity, security, and efficiency.

## Objectives  
- **Inter-campus connectivity:** Establish seamless communication between Sukkur and Khairpur campuses.  
- **Security:** Implement network segmentation using **VLANs**, apply security protocols (such as **ACLs**), and ensure data confidentiality.  
- **Dynamic IP allocation:** Configure **DHCP** for automatic IP assignment to devices.  
- **Routing protocols:** Use **RIP v2** for dynamic routing across campus networks.  

## Features  
- **VLANs:** The network is segmented into VLANs for different departments, such as HR, IT, and academic departments, to ensure organized and secure traffic flow.  
- **RIP v2:** Utilized for internal routing between routers across the campuses, ensuring efficient data transmission.  
- **Dynamic IP Allocation:** Devices in all buildings acquire dynamic IPv4 addresses from the router-based DHCP server.  
- **Wireless Connectivity:** All departments are equipped with wireless access points to provide connectivity for mobile devices.  
- **Network Security:** ACLs are configured to restrict access between departments (e.g., blocking academic departments from accessing the Finance department).

## Tools and Technologies Used  
- **Cisco Packet Tracer**  
- **VLAN Configuration**  
- **RIP v2** Routing Protocol  
- **DHCP**  
- **Access Control Lists (ACLs)**  
- **Wireless Access Points**  

## Topology Diagram
![image](https://github.com/user-attachments/assets/0268e3c3-d8ed-4ce7-9663-e3897abc1b45)



## Getting Started  
### Prerequisites  
- **Cisco Packet Tracer** software is required to view and interact with the project file.  
  You can download Cisco Packet Tracer from the official Cisco Networking Academy website:  
  [Cisco Networking Academy](https://www.netacad.com)

### How to Run the Project  
1. **Download Cisco Packet Tracer** and install it on your system.  
2. **Clone the repository** or **download the ZIP** file.  
3. Open the `project.pkt` file in **Cisco Packet Tracer** to view the network design.  
4. You can simulate and modify the configuration to explore different network behaviors.

