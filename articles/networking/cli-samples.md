---
title: Azure CLI Samples - Networking
description: Learn about Azure CLI samples for networking, including samples for connectivity between Azure resources and samples for load balancing and traffic direction.
services: virtual-network
documentationcenter: virtual-network
author: mbender-ms
manager: kumudD

tags:
ms.assetid:
ms.service: virtual-network
ms.topic: article
ms.tgt_pltfrm:
ms.workload: infrastructure
ms.date: 04/25/2017
ms.author: kumud 
ms.custom: devx-track-azurecli

---
# Azure CLI Samples for networking

The following table includes links to bash scripts built using the Azure CLI.

| Script | Description |
|-|-|
|**Connectivity between Azure resources**||
| [Create a virtual network for multi-tier applications](./scripts/virtual-network-cli-sample-multi-tier-application.md?toc=%2fazure%2fnetworking%2ftoc.json) | Creates a virtual network with front-end and back-end subnets. Traffic to the front-end subnet is limited to HTTP and SSH, while traffic to the back-end subnet is limited to MySQL, port 3306. |
| [Peer two virtual networks](./scripts/virtual-network-cli-sample-peer-two-virtual-networks.md?toc=%2fazure%2fnetworking%2ftoc.json) | Creates and connects two virtual networks in the same region. |
| [Route traffic through a network virtual appliance](./scripts/virtual-network-cli-sample-route-traffic-through-nva.md?toc=%2fazure%2fnetworking%2ftoc.json) | Creates a virtual network with front-end and back-end subnets and a VM that is able to route traffic between the two subnets. |
| [Filter inbound and outbound VM network traffic](./scripts/virtual-network-filter-network-traffic.md?toc=%2fazure%2fnetworking%2ftoc.json) | Creates a virtual network with front-end and back-end subnets. Inbound network traffic to the front-end subnet is limited to HTTP, HTTPS and SSH. Outbound traffic to the Internet from the back-end subnet is not permitted. |
|**Load balancing and traffic direction**||
| [Load balance multiple websites on VMs](./scripts/load-balancer-linux-cli-load-balance-multiple-websites-vm.md?toc=%2fazure%2fnetworking%2ftoc.json) | Creates two VMs with multiple IP configurations, joined to an Azure Availability Set, accessible through an Azure Load Balancer. |
| [Direct traffic across multiple regions for high application availability](./scripts/traffic-manager-cli-websites-high-availability.md?toc=%2fazure%2fnetworking%2ftoc.json) |  Creates two app service plans, two web apps, a traffic manager profile, and two traffic manager endpoints. |
| | |
