# Service Provider Network Labs

Practical hands-on scenarios for Service Provider infrastructure design and configuration, simulated in GNS3 using Cisco IOS and IOS-XR.

---

## Technical Notes

* **IP Addressing Scheme:** All link subnets are configured using `/24` masks for clarity, convenience, and lab visualization (rather than production `/30` or `/31` point-to-point subnets).
* **Platforms & Platforms Version:** Tested on Cisco IOS-XE and Cisco IOS-XR images.
* **Diagrams:** High-resolution network topologies generated using Draw.io with 2D Cisco icons.

---

## Repository Structure

```text
service-provider-labs/
├── lab-001-mpls-l3vpn-inter-as-option-a/
│   ├── topology.png
│   └── configs/
│       ├── CE1.txt
│       ├── PE2.txt
│       └── ...