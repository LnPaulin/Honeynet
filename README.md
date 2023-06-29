# Azure Honeynet & SOC Project: Cyber Attacks in Real Time

# <b>Introduction</b>

In this project, I simulate a small-scale honeynet that attracts real-world traffic from attackers around the world through Microsoft Azure. The goal throughout this project is to demonstrate best security practices, incident response tactics, and the effects of hardening your environment. We'll accomplish this by intentionally deploying virtual machines that have no safeguard from the public internet to attract attackers into our environment. Then after ingesting some log sources into Log Analytics Workspace, Microsoft Sentinel will come in to create attack maps, alerts, and incidents. In order to showcase metrics before and after hardening the environment based off the incidents generated from the 24 hour capture.

# Azure Components Utilized

- Azure Virtual Network (VNet)
- Azure Network Security Group (NSG)
- Virtual Machines (2x Windows, 1x Linux)
- Log Analytics Workspace with Kusto Query Language (KQL) Queries
- Azure Key Vault
- Azure Storage Account
- Microsoft Sentinel
- Microsoft Defender for Cloud
