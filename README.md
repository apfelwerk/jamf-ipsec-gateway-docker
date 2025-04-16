# Jamf Quick Connect IPSec Gateway (Docker)

This repository contains the source for a Docker-based IPSec gateway designed to connect with **Jamf Security Cloud** using the **Quick Connect** integration.

It provides a lightweight, containerized solution based on **Ubuntu 24.04** and **strongSwan**, optimized for IKEv2 and NAT traversal.  
The gateway configuration is fully controlled via environment variables and is suitable for deployment in cloud, on-premise, or edge environments.

This project is developed and maintained by **Apfelwerk GmbH & Co. KG**, an Apple consulting and managed services provider based in Germany.

## Purpose

The goal of this project is to simplify the deployment of Quick Connect IPSec gateways for Jamf by providing a portable, reproducible container image.  
It eliminates the need to manually configure and maintain individual Linux VMs, and is intended for use in:

- Dedicated VPN gateway setups for Jamf Security Cloud
- Automated deployments via Docker, Compose or Portainer
- Testing and development of Jamf access policies

---

*This repository does not contain any proprietary Jamf code. It is intended to work with Jamf’s documented VPN integration options for use with Jamf Security Cloud.*
