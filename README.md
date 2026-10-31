# SE7ENX — Local AI Smart Room & Building Automation System

**A local-first AI agent connecting human interaction with real-world smart environments.**

SE7ENX is an experimental AI-powered voice and text agent designed to understand user commands and interact with smart-room infrastructure through a locally orchestrated system.

The project explores how artificial intelligence, speech recognition, messaging protocols, automation platforms, virtualization, and physical devices can work together as one integrated environment.

## 🎥 System Demonstration

This video demonstrates SE7ENX processing a voice command locally and transmitting the resulting action through the system until it reaches a physical smart device.

**Watch the demonstration:**  
[SE7ENX — System Demo](https://www.youtube.com/shorts/yTcSScFVz6U)

**Project presentation:**  
[Explore SE7ENX](https://lnkd.in/dFBqQV2a)

## System Architecture

SE7ENX follows a layered architecture connecting human interaction to physical device control.

```text
             USER
       Voice / Text Input
               |
               v
      AI & Speech Processing
          Whisper
               |
               v
       Command Processing
               |
               v
          MQTT Broker
          Mosquitto
               |
               v
         Node-RED
      Automation Logic
               |
               v
        Home Assistant
        Device Integration
               |
               v
       Physical Devices
          Shelly / IoT
```

The infrastructure is hosted on a **ZimaBoard 832 running Proxmox VE**, providing a virtualization environment for the local services.

## Technology Stack

| Layer | Technologies |
|---|---|
| AI & Speech Recognition | Whisper |
| Messaging | MQTT / Mosquitto |
| Automation | Node-RED |
| Smart Home Platform | Home Assistant |
| Device Control | Shelly |
| Virtualization | Proxmox VE |
| Hardware Infrastructure | ZimaBoard 832 |
| Smart Building Lab | KNX |

KNX is also part of the broader SE7ENX Smart Building laboratory environment.

## Core Capabilities

- Local voice and text interaction.
- Speech recognition and command processing.
- MQTT-based communication between system components.
- Automation workflows through Node-RED.
- Smart-device integration through Home Assistant.
- Real-world lighting and device control.
- Locally hosted infrastructure and service orchestration.

## Local-First Approach

One of the main design principles behind SE7ENX is reducing dependency on external cloud services.

The project explores a local-first architecture where interaction, automation, messaging, and device communication operate within the local environment.

This approach provides a foundation for privacy-conscious smart environments, greater infrastructure control, and future offline capabilities.

## Development Roadmap

SE7ENX is an evolving engineering project. Current development focuses on expanding its capabilities toward a broader Building Automation System.

Planned development areas include:

- **Climate Control:** Temperature monitoring and HVAC automation.
- **Lighting Automation:** Advanced lighting scenes and intelligent control.
- **Arabic Language Processing:** Improving Arabic and Algerian Darija command recognition.
- **Accessibility:** More natural and accessible human-building interaction.
- **Smart Building Integration:** Expanding interoperability with KNX and other automation technologies.
- **System Intelligence:** More contextual and adaptive command processing.

## Project Status

SE7ENX is an ongoing experimental engineering project.

The demonstrated workflow connects local AI and automation services to physical smart devices. Additional integrations and capabilities remain under development.

This repository documents the project and its demonstrations. The implementation source code is not included in this public repository.

## Author

**Abdelkhalek Mammeri**

Electronics Engineering | IoT | Building Automation | Systems Integration

- GitHub: [@Ab40D](https://github.com/Ab40D)
- LinkedIn: [Abdelkhalek Mammeri](https://www.linkedin.com/in/abdelkhalekmammeri/)
- Portfolio: [SE7EN Bay](https://se7en-bay.vercel.app/)

---

**SE7ENX — Connecting Intelligence to the Physical World.**

*This is an independent engineering project developed through experimentation, integration, and continuous learning.*
