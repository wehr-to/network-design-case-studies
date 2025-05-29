# 🌐 Network & Design

This repository documents network design patterns, case studies, and reference architectures with a focus on real-world enterprise infrastructure. It blends the perspective of a **network engineer** and a **security engineer** — asking not only “how do packets flow?” but also “how do we protect them?”

## 🎯 Purpose

To demonstrate fluency in:
- Designing scalable, segmented, and secure networks
- Understanding the trade-offs between availability, simplicity, and control
- Applying security principles at every layer of the network

This is not just a topology gallery — it's an engineer's thought process on **why designs matter**.

## 📁 Key Sections

| Folder | Purpose |
|--------|---------|
| `enterprise-topologies/` | Classic designs (3-tier, hub-spoke, hybrid cloud, VPN edge) |
| `security-perspective/` | Isolation, segmentation, least privilege enforcement |
| `design-principles/` | HA, QoS, load balancing, redundancy patterns |
| `case-studies/` | Real-world design breakdowns with constraints + decisions |
| `tools-and-methods/` | Diagramming tools, IP templates, subnetting aids |

## 🧠 Sample Case Studies

- 🏭 **Manufacturing Plant LAN**  
  Designed for high-availability across PLC zones, with VLAN segmentation and fiber uplinks.

- 🏫 **School Campus Wi-Fi**  
  RF-aware WLAN design with student/staff separation, RADIUS auth, and rogue AP detection.

- 🌩️ **Hybrid DC + Cloud Extension**  
  BGP peering, IPsec tunnels, flow logging, and service isolation between on-prem and cloud workloads.

## 🔐 Security-First Lens

Each design addresses questions like:
- Where do you enforce least privilege?
- What is the failure domain if X device goes down?
- Can attackers move laterally from guest VLANs?
- How does logging, monitoring, and detection fit in?

## 🛠 Tools Used

- Lucidchart / draw.io / Excalidraw for diagrams
- Markdown + `.md` case reviews
- Excel for IP schema templates
- Wireshark and VLAN schemas for validation

## 🧰 Ideal Use Cases

- Studying for interviews or design-based certifications (CCNA/CCNP/AWS)
- Reviewing architecture trade-offs
- Documenting your thought process as a future network architect
- Creating red vs blue views of enterprise traffic paths
