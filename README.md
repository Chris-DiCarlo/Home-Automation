

# Home Automation System with Proxmox & Home Assistant

This project showcases my ability to design, configure, and deploy a fully functional home automation environment to manage security cameras, lighting, and home/away automation themes. The solution integrates multiple smart devices into a centralized platform, improving convenience, security, and energy efficiency.

---

## Tools & Technologies Used
- **Mini PC** – Dedicated host for virtualization  
- **Proxmox VE** – Virtualization platform for managing virtual machines and containers  
- **Home Assistant** – Open-source home automation platform  
- **IP Security Cameras** – Network-based surveillance solution  
- **Smart Lights & Switches** – For automated lighting control  
- **Automation Scripts** – YAML- and Node-RED-based automation logic  
- **Router with VLAN Support** – Network segmentation for IoT security  
- **Cloud Backups** – Offsite configuration backups for disaster recovery  

---

## Steps Taken

1. **Planning & Design**  
   - Determined automation requirements (security monitoring, lighting control, themes)  
   - Designed network topology with VLANs to separate IoT devices from core devices  

2. **Hardware Setup**  
   - Prepared a mini PC as the primary host  
   - Installed **Proxmox Virtual Environment** for virtualization  

3. **Environment Deployment**  
   - Created a dedicated VM for **Home Assistant**  
   - Configured resource allocation to ensure smooth automation performance  

4. **Device Integration**  
   - Linked IP security cameras to Home Assistant for real-time monitoring  
   - Added smart lights, switches, and motion sensors for event-based triggers  
   - Configured home/away modes to adjust lighting and security states automatically  

5. **Automation & Scripting**  
   - Implemented lighting schedules and themes based on time of day and occupancy  
   - Integrated security alerts via mobile notifications  
   - Created automated responses for motion detection during away mode  

6. **Testing & Optimization**  
   - Conducted real-world testing for latency and device responsiveness  
   - Tuned automation rules for reliability and minimal false triggers  

---

## Lessons Learned
- Importance of **network segmentation** to protect IoT devices from potential threats  
- Resource management in virtualization to ensure all services run smoothly  
- The need for **redundant backups** to prevent loss of configurations  

---

## Skills Learned
- Virtualization and VM management with **Proxmox**  
- Smart home integration using **Home Assistant**  
- YAML and Node-RED automation scripting  
- Network security and **IoT isolation**  
- System optimization for performance and reliability  
