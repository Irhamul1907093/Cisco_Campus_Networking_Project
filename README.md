# Campus Network Design & Implementation Project

This project involves designing and implementing a network topology for Albion University using Cisco Packet Tracer. The university consists of two campuses situated 20 miles apart, with students and staff distributed across four faculties: Health and Sciences, Business, Engineering/Computing, and Art/Design.

---

## Project Requirements

### Network Topology
- **Main Campus:**
  - **Building A:** Hosts administrative staff in the departments of management, HR, and finance, along with the Faculty of Business. VLAN configuration is expected for shared networking equipment.
  - **Building B:** Houses the Faculty of Engineering and Computing, and the Faculty of Art and Design.
  - **Building C:** Contains students' labs and the IT department, which hosts the University Web server and other servers. Additionally, an email server is hosted externally on the cloud.
- **Smaller Campus:**
  - Houses the Faculty of Health and Sciences, with staff and students' labs located on separate floors.

### Configuration Requirements
- Each department/faculty must operate on a separate IP network.
- VLANs must be configured on switches with appropriate security settings.
- RIP v2 is used for routing within the internal network, while static routing is configured for the external server.
- Devices in Building A should acquire dynamic IP addresses from a router-based DHCP server.

---

## Tasks

1. **Design and Plan:**  
   Develop a network topology prototype for Albion University using Cisco Packet Tracer.  
   *Formative feedback will be provided during Week 6.*

2. **Configuration:**  
   Implement and configure the network in Packet Tracer to meet the specified requirements, ensuring proper connectivity and functionality.

3. **Documentation:**  
   Produce a report (maximum **1500 words**) evaluating the network design and providing a critical appraisal. The evaluation should include:
   - Performance
   - Scalability
   - Reliability
   - Security

---

## Technologies Used
- Cisco Packet Tracer
- Networking protocols: VLANs, RIP v2, DHCP
- IP Networking and Routing

---

Feel free to explore the repository and provide feedback!
