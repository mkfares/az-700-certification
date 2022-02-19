# AZ-700: Designing and Implementing Microsoft Azure Networking Solutions - Exam Study Guide
This exam study guide is based on the update of November 23, 2021.

---

## A. Design, implement, and manage hybrid networking (10-15%)

### 1. Design, implement, and manage a site-to-site VPN connection

#### 1.1. Design a site-to-site VPN connection for high availability
* [Highly Available cross-premises and VNet-to-VNet connectivity](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-highlyavailable)
* [About zone-redundant virtual network gateways in Azure Availability Zones](https://docs.microsoft.com/en-us/azure/vpn-gateway/about-zone-redundant-vnet-gateways)

#### 1.2. Select an appropriate virtual network (VNet) gateway SKU
* [Gateway SKUs](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpn-gateway-settings#gwsku)
* [Working with virtual network gateway SKUs (legacy SKUs)](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-skus-legacy)

#### 1.3. Identify when to use policy-based VPN versus route-based VPN
* [VPN types](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpn-gateway-settings#vpntype)

#### 1.4. Create and configure a local network gateway
* [Create a local network gateway](https://docs.microsoft.com/en-us/azure/vpn-gateway/tutorial-site-to-site-portal#LocalNetworkGateway)
* [Modify local network gateway settings using the Azure portal](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-modify-local-network-gateway-portal)

#### 1.5. Create and configure an IPsec/IKE policy
* [Configure IPsec/IKE policy for S2S VPN or VNet-to-VNet connections](https://docs.microsoft.com/en-us/azure/vpn-gateway/ipsec-ike-policy-howto)

#### 1.6. Create and configure a virtual network gateway
* [Create and manage a VPN gateway using Azure portal](https://docs.microsoft.com/en-us/azure/vpn-gateway/tutorial-create-gateway-portal)
* [About VPN Gateway configuration settings](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpn-gateway-settings)
* [Configure active-active VPN gateways using the portal](https://docs.microsoft.com/en-us/azure/vpn-gateway/active-active-portal)
* [Create a zone-redundant virtual network gateway in Azure Availability Zones](https://docs.microsoft.com/en-us/azure/vpn-gateway/create-zone-redundant-vnet-gateway)

#### 1.7. Diagnose and resolve virtual network gateway connectivity issues
* [Monitoring VPN Gateway](https://docs.microsoft.com/en-us/azure/vpn-gateway/monitor-vpn-gateway)
* [Troubleshoot VPN Gateway](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-troubleshoot)
* [Troubleshoot Azure VPN Gateway using diagnostic logs](https://docs.microsoft.com/en-us/azure/vpn-gateway/troubleshoot-vpn-with-azure-diagnostics)
* [Troubleshooting: An Azure site-to-site VPN connection cannot connect and stops working](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-troubleshoot-site-to-site-cannot-connect)
* [Troubleshooting: Azure Site-to-Site VPN disconnects intermittently](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-troubleshoot-site-to-site-disconnected-intermittently)

---

### 2. Design, implement, and manage a point-to-site VPN connection
* [About Point-to-Site VPN](https://docs.microsoft.com/en-us/azure/vpn-gateway/point-to-site-about)

#### 2.1. Select an appropriate virtual network gateway SKU
* [Gateway SKUs](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpn-gateway-settings#gwsku)

#### 2.2. Plan and configure RADIUS authentication
* [Configure a Point-to-Site connection to a VNet using RADIUS authentication](https://docs.microsoft.com/en-us/azure/vpn-gateway/point-to-site-how-to-radius-ps)
* [Point-to-Site - RADIUS authentication - FAQ](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-vpn-faq#P2SRADIUS)

#### 2.3. Plan and configure certificate-based authentication
* [Configure a Point-to-Site VPN connection using Azure certificate authentication](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-howto-point-to-site-resource-manager-portal)
* [Generate and export certificates for Point-to-Site using PowerShell](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-certificates-point-to-site)
* [Generate and export certificates for Point-to-Site using Linux CLI and strongSwan](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-certificates-point-to-site-linux)
* [Install client certificates for P2S certificate authentication connections](https://docs.microsoft.com/en-us/azure/vpn-gateway/point-to-site-how-to-vpn-client-install-azure-cert)
* [Generate and install VPN client profile configuration files for certificate authentication](https://docs.microsoft.com/en-us/azure/vpn-gateway/point-to-site-vpn-client-configuration-azure-cert)
* [Point-to-Site - Certificate authentication - FAQ](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-vpn-faq#P2S)

#### 2.4. Plan and configure OpenVPN authentication
* [Configure OpenVPN for Point-to-Site VPN gateways](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-howto-openvpn)
* [Configure OpenVPN clients for Azure VPN Gateway](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-howto-openvpn-clients)
* [Transition to OpenVPN protocol or IKEv2 from SSTP](https://docs.microsoft.com/en-us/azure/vpn-gateway/ikev2-openvpn-from-sstp)

#### 2.5. Plan and configure Azure Active Directory (Azure AD) authentication
* [Create an Azure Active Directory tenant for P2S OpenVPN protocol connections](https://docs.microsoft.com/en-us/azure/vpn-gateway/openvpn-azure-ad-tenant)

#### 2.6. Implement a VPN client configuration file
* [Generate and install VPN client profile configuration files for certificate authentication](https://docs.microsoft.com/en-us/azure/vpn-gateway/point-to-site-vpn-client-configuration-azure-cert)
* [Create and install VPN client configuration files for P2S RADIUS authentication](https://docs.microsoft.com/en-us/azure/vpn-gateway/point-to-site-vpn-client-configuration-radius)
* [Working with P2S VPN client profile files](https://docs.microsoft.com/en-us/azure/vpn-gateway/about-vpn-profile-download)
* [Create custom Intune profiles to deploy VPN client profiles](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-profile-intune)

#### 2.7. Diagnose and resolve client-side and authentication issues
* [Troubleshooting: Azure point-to-site connection problems](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-troubleshoot-vpn-point-to-site-connection-problems)
* [Troubleshoot Point-to-Site VPN connections from Mac OS X VPN clients](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-troubleshoot-point-to-site-osx-ikev2)
* [Troubleshoot an Azure AD authentication VPN client](https://docs.microsoft.com/en-us/azure/vpn-gateway/troubleshoot-ad-vpn-client)

---

### 3. Design, implement, and manage Azure ExpressRoute
* [What is Azure ExpressRoute?](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-introduction)
* [ExpressRoute FAQ - What is ExpressRoute?](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-faqs#what-is-expressroute)

#### 3.1. Choose between provider and direct model (ExpressRoute Direct)
* [About ExpressRoute Direct](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-erdirect-about)
* [ExpressRoute connectivity models](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-connectivity-models)
* [ExpressRoute FAQ - ExpressRoute Direct](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-faqs#expressRouteDirect)

#### 3.2. Design and implement Azure cross-region connectivity between multiple ExpressRoute locations
* [Cross-network connectivity](https://docs.microsoft.com/en-us/azure/expressroute/cross-network-connectivity)

#### 3.3. Select an appropriate ExpressRoute SKU and tier
* [About ExpressRoute virtual network gateways](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-about-virtual-network-gateways)
* [ExpressRoute FAQ - ExpressRoute Local](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-faqs#expressroute-local)
* [ExpressRoute FAQ - ExpressRoute Premium](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-faqs#expressroute-premium)

#### 3.4. Design and implement ExpressRoute Global Reach
* [About ExpressRoute Global Reach](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-global-reach)
* [ExpressRoute FAQ - Global Reach](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-faqs#globalreach)
* [Configure ExpressRoute Global Reach using the Azure portal](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-howto-set-global-reach-portal)

#### 3.5. Design and implement ExpressRoute FastPath
* [About ExpressRoute FastPath](https://docs.microsoft.com/en-us/azure/expressroute/about-fastpath)
* [Configure ExpressRoute FastPath](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-howto-linkvnet-portal-resource-manager#configure-expressroute-fastpath)

#### 3.6. Choose between private peering only, Microsoft peering only, or both
* [ExpressRoute circuits and peering](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-circuit-peerings)

#### 3.7. Configure private peering
* [Create and modify peering for an ExpressRoute circuit using the Azure portal - Private peering](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-howto-routing-portal-resource-manager#private)

#### 3.8. Configure Microsoft peering
* [Create and modify peering for an ExpressRoute circuit using the Azure portal - Microsoft peering](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-howto-routing-portal-resource-manager#msft)

#### 3.9. Create and configure an ExpressRoute gateway
* [About ExpressRoute virtual network gateways](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-about-virtual-network-gateways)
* [Configure a virtual network gateway for ExpressRoute using the Azure portal](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-howto-add-gateway-portal-resource-manager)

#### 3.10. Connect a virtual network to an ExpressRoute circuit
* [Connect a virtual network to an ExpressRoute circuit using the portal](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-howto-linkvnet-portal-resource-manager)

#### 3.11. Recommend a route advertisement configuration
* [ExpressRoute routing requirements](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-routing)

#### 3.12. Configure encryption over ExpressRoute
* [About ExpressRoute encryption](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-about-encryption)
* [Configure MACsec on ExpressRoute Direct ports](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-howto-macsec)
* [ExpressRoute encryption: IPsec over ExpressRoute for Virtual WAN](https://docs.microsoft.com/en-us/azure/virtual-wan/vpn-over-expressroute)
* [Configure a site-to-site VPN over ExpressRoute Microsoft peering](https://docs.microsoft.com/en-us/azure/expressroute/site-to-site-vpn-over-microsoft-peering)
* [Configure a Site-to-Site VPN connection over ExpressRoute private peering](https://docs.microsoft.com/en-us/azure/vpn-gateway/site-to-site-vpn-private-peering)

#### 3.13. Implement Bidirectional Forwarding Detection
* [Configure BFD over ExpressRoute](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-bfd)

#### 3.14. Diagnose and resolve ExpressRoute connection issues
* [Verifying ExpressRoute connectivity](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-troubleshooting-expressroute-overview)
* [Troubleshooting network performance](https://docs.microsoft.com/en-us/azure/expressroute/expressroute-troubleshooting-network-performance)
* [Reset a failed ExpressRoute circuit](https://docs.microsoft.com/en-us/azure/expressroute/reset-circuit)

---

## B. Design and implement core networking infrastructure (20-25%)

### 1. Design and implement private IP addressing for VNets
* [What is Azure Virtual Network?](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview)

#### 1.1. Create a VNet
* [Azure Virtual Network concepts and best practices](https://docs.microsoft.com/en-us/azure/virtual-network/concepts-and-best-practices)
* [Create a virtual network using the Azure portal](https://docs.microsoft.com/en-us/azure/virtual-network/quick-create-portal)
* [Create, change, or delete a virtual network](https://docs.microsoft.com/en-us/azure/virtual-network/manage-virtual-network)
* [Azure Virtual Network FAQ - Configuration](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-faq#configuration)

#### 1.2. Plan and configure subnetting for services, including VNet gateways, private endpoints, firewalls, application gateways, and VNet-integrated platform services
* [Azure networking services overview](https://docs.microsoft.com/en-us/azure/networking/fundamentals/networking-overview)
* [Add, change, or delete a virtual network subnet](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-manage-subnet)
* [Services that can be deployed into a virtual network](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-for-azure-services#services-that-can-be-deployed-into-a-virtual-network)
* [Azure Virtual Network FAQ](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-faq)

#### 1.3. Plan and configure subnet delegation
* [What is subnet delegation?](https://docs.microsoft.com/en-us/azure/virtual-network/subnet-delegation-overview)
* [Add or remove a subnet delegation](https://docs.microsoft.com/en-us/azure/virtual-network/manage-subnet-delegation)

#### 1.4. Plan and configure subnetting for Azure Route Server
* [What is Azure Route Server?](https://docs.microsoft.com/en-us/azure/route-server/overview)
* [Create and configure Route Server using the Azure portal](https://docs.microsoft.com/en-us/azure/route-server/quickstart-configure-route-server-portal)

---

### 2. Design and implement name resolution

#### 2.1. Design public DNS zones
* [What is Azure DNS?](https://docs.microsoft.com/en-us/azure/dns/dns-overview)
* [Overview of DNS zones and records](https://docs.microsoft.com/en-us/azure/dns/dns-zones-records)
* [Public DNS FAQ](https://docs.microsoft.com/en-us/azure/dns/dns-faq)

#### 2.2. Design private DNS zones
* [What is Azure Private DNS?](https://docs.microsoft.com/en-us/azure/dns/private-dns-overview)
* [Azure Private DNS FAQ](https://docs.microsoft.com/en-us/azure/dns/dns-faq-private)

#### 2.3. Design name resolution inside a VNet
* [Name resolution for resources in Azure virtual networks](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-name-resolution-for-vms-and-role-instances)

#### 2.4. Configure a public or private DNS zone
* [Create an Azure DNS zone and record using the Azure portal](https://docs.microsoft.com/en-us/azure/dns/dns-getstarted-portal)
* [Create an Azure private DNS zone using the Azure portal](https://docs.microsoft.com/en-us/azure/dns/private-dns-getstarted-portal)

#### 2.5 Link a private DNS zone to a VNet
* [What is a virtual network link?](https://docs.microsoft.com/en-us/azure/dns/private-dns-virtual-network-links)
* [What is the auto registration feature in Azure DNS private zones?](https://docs.microsoft.com/en-us/azure/dns/private-dns-autoregistration)

---

### 3. Design and implement cross-VNet connectivity

#### 3.1. Design service chaining, including gateway transit
* [Virtual network peering](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-peering-overview)
* [Hub-spoke network topology in Azure](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/hybrid-networking/hub-spoke)
* [Configure VPN gateway transit for virtual network peering](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-peering-gateway-transit)

#### 3.2. Design VPN connectivity between VNets
* [Configure a VNet-to-VNet VPN gateway connection by using the Azure portal](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-howto-vnet-vnet-resource-manager-portal)

#### 3.3. Implement VNet peering
* [Connect virtual networks with virtual network peering using the Azure portal](https://docs.microsoft.com/en-us/azure/virtual-network/tutorial-connect-virtual-networks-portal)
* [Create, change, or delete a virtual network peering](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-manage-peering)
* [Connect virtual networks with virtual network peering using PowerShell](https://docs.microsoft.com/en-us/azure/virtual-network/tutorial-connect-virtual-networks-powershell)
* [Create a virtual network peering - Resource Manager, different subscriptions and Azure Active Directory tenants](https://docs.microsoft.com/en-us/azure/virtual-network/create-peering-different-subscriptions)

---

### 4. Design and implement an Azure Virtual WAN architecture

#### 4.1. Design an Azure Virtual WAN architecture, including selecting types and services
* [What is Azure Virtual WAN?](https://docs.microsoft.com/en-us/azure/virtual-wan/virtual-wan-about)
* [Migrate to Azure Virtual WAN](https://docs.microsoft.com/en-us/azure/virtual-wan/migrate-from-hub-spoke-topology)

#### 4.2. Connect a VNet gateway to Azure Virtual WAN
* [Connect a VPN Gateway (virtual network gateway) to Virtual WAN](https://docs.microsoft.com/en-us/azure/virtual-wan/connect-virtual-network-gateway-vwan)

#### 4.3. Create a hub in Virtual WAN
* [Create a virtual hub (site-to-site)](https://docs.microsoft.com/en-us/azure/virtual-wan/virtual-wan-site-to-site-portal#hub)
* [Configure hub settings (point-to-site)](https://docs.microsoft.com/en-us/azure/virtual-wan/virtual-wan-point-to-site-portal#hub)
* [Configure hub settings (ExpressRoute)](https://docs.microsoft.com/en-us/azure/virtual-wan/virtual-wan-expressroute-portal#hub)

#### 4.4. Create a network virtual appliance (NVA) in a virtual hub
* [Network Virtual Appliances in the Virtual WAN hub](https://docs.microsoft.com/en-us/azure/virtual-wan/about-nva-hub)
* [How to create a Network Virtual Appliance in an Azure Virtual WAN hub](https://docs.microsoft.com/en-us/azure/virtual-wan/how-to-nva-hub)

#### 4.5. Configure virtual hub routing
* [About virtual hub routing](https://docs.microsoft.com/en-us/azure/virtual-wan/about-virtual-hub-routing)
* [How to configure virtual hub routing](https://docs.microsoft.com/en-us/azure/virtual-wan/how-to-virtual-hub-routing)

#### 4.6 Create a connection unit
* [What is a connection unit?](https://docs.microsoft.com/en-us/azure/virtual-wan/pricing-concepts#connection-unit)
* [What are Virtual WAN gateway scale units?](https://docs.microsoft.com/en-us/azure/virtual-wan/virtual-wan-faq?WT.mc_id=modinfra-33046-thmaure#what-are-virtual-wan-gateway-scale-units)
* [ExpressRoute scale units](https://docs.microsoft.com/en-us/azure/virtual-wan/virtual-wan-expressroute-portal#hub)
* [For User VPN (Point-to-site)- how many clients are supported?](https://docs.microsoft.com/en-us/azure/virtual-wan/virtual-wan-faq#for-user-vpn-point-to-site--how-many-clients-are-supported)

---

## C. Design and implement routing (25-30%)

### 1. Design, implement, and manage VNet routing

#### 1.1. Design and implement user-defined routes (UDRs)
* [Virtual network traffic routing](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-udr-overview)
* [Route network traffic with a route table using the Azure portal](https://docs.microsoft.com/en-us/azure/virtual-network/tutorial-create-route-table-portal)
* [Create, change, or delete a route table](https://docs.microsoft.com/en-us/azure/virtual-network/manage-route-table)

#### 1.2. Associate a route table with a subnet
* [Associate a route table to a subnet](https://docs.microsoft.com/en-us/azure/virtual-network/tutorial-create-route-table-portal#associate-a-route-table-to-a-subnet)

#### 1.3. Configure forced tunneling
* [Configure forced tunneling](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-forced-tunneling-rm)
* [Azure Firewall forced tunneling](https://docs.microsoft.com/en-us/azure/firewall/forced-tunneling)

#### 1.4. Diagnose and resolve routing issues
* [Diagnose a virtual machine routing problem](https://docs.microsoft.com/en-us/azure/virtual-network/diagnose-network-routing-problem)
* [Diagnose a virtual machine network routing problem using the Azure portal](https://docs.microsoft.com/en-us/azure/network-watcher/diagnose-vm-network-routing-problem)

#### 1.5. Design and implement Azure Route Server
* [What is Azure Route Server?](https://docs.microsoft.com/en-us/azure/route-server/overview)
* [Create and configure Route Server using the Azure portal](https://docs.microsoft.com/en-us/azure/route-server/quickstart-configure-route-server-portal)
* [Azure Route Server FAQ](https://docs.microsoft.com/en-us/azure/route-server/route-server-faq)

---

### 2. Design and implement an Azure Load Balancer
* [What is Azure Load Balancer?](https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-overview)
* [Azure Load Balancer components](https://docs.microsoft.com/en-us/azure/load-balancer/components)
* [Load Balancer FAQs](https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-faqs)

#### 2.1. Choose an Azure Load Balancer SKU (Basic versus Standard)
* [Azure Load Balancer SKUs](https://docs.microsoft.com/en-us/azure/load-balancer/skus)

#### 2.2. Choose between public and internal
* [What is Azure Load Balancer?](https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-overview)

#### 2.3. Create and configure an Azure Load Balancer (including cross-region)
* [Azure Load Balancer portal settings](https://docs.microsoft.com/en-us/azure/load-balancer/manage)
* [Create a public load balancer to load balance VMs using the Azure portal](https://docs.microsoft.com/en-us/azure/load-balancer/quickstart-load-balancer-standard-public-portal)
* [Create an internal load balancer to load balance VMs using the Azure portal](https://docs.microsoft.com/en-us/azure/load-balancer/quickstart-load-balancer-standard-internal-portal)
* [Create a cross-region Azure Load Balancer using the Azure portal](https://docs.microsoft.com/en-us/azure/load-balancer/tutorial-cross-region-portal)

#### 2.4. Implement a load balancing rule
* [Load Balancer rules](https://docs.microsoft.com/en-us/azure/load-balancer/components#load-balancer-rules)
* [Load-balancing rules](https://docs.microsoft.com/en-us/azure/load-balancer/manage-rules-how-to#load-balancing-rules)
* [Manage rules for Azure Load Balancer using the Azure portal](https://docs.microsoft.com/en-us/azure/load-balancer/manage-rules-how-to)

#### 2.5. Create and configure inbound NAT rules
* [Configure port forwarding in Azure Load Balancer using the Azure portal](https://docs.microsoft.com/en-us/azure/load-balancer/tutorial-load-balancer-port-forwarding-portal)

#### 2.6. Create explicit outbound rules for a load balancer
* [Outbound rules Azure Load Balancer](https://docs.microsoft.com/en-us/azure/load-balancer/outbound-rules)
* [Outbound-only load balancer configuration](https://docs.microsoft.com/en-us/azure/load-balancer/egress-only)

---

### 3. Design and implement Azure Application Gateway
* [What is Azure Application Gateway?](https://docs.microsoft.com/en-us/azure/application-gateway/overview)
* [Application Gateway FAQs](https://docs.microsoft.com/en-us/azure/application-gateway/application-gateway-faq)

#### 3.1. Recommend Azure Application Gateway deployment options
* [Application Gateway configuration overview](https://docs.microsoft.com/en-us/azure/application-gateway/configuration-overview)
* [Azure Application Gateway features](https://docs.microsoft.com/en-us/azure/application-gateway/features)
* [How an application gateway works](https://docs.microsoft.com/en-us/azure/application-gateway/how-application-gateway-works)

#### 3.2. Choose between manual and autoscale
* [Scaling Application Gateway v2 and WAF v2](https://docs.microsoft.com/en-us/azure/application-gateway/application-gateway-autoscaling-zone-redundant)
* [Create Application Gateway - Basics](https://docs.microsoft.com/en-us/azure/application-gateway/quick-create-portal#basics-tab)
* [Create an application gateway that improves web application access](https://docs.microsoft.com/en-us/azure/application-gateway/tutorial-autoscale-ps)

#### 3.3. Create a back-end pool
* [Application gateway components - Backend pools](https://docs.microsoft.com/en-us/azure/application-gateway/application-gateway-components#backend-pools)
* [Application Gateway configuration overview - Back-end pool](https://docs.microsoft.com/en-us/azure/application-gateway/configuration-overview#back-end-pool)
* [Create Application Gateway - Add backend targets](https://docs.microsoft.com/en-us/azure/application-gateway/quick-create-portal#add-backend-targets)

#### 3.4. Configure health probes
* [Application Gateway health monitoring overview](https://docs.microsoft.com/en-us/azure/application-gateway/application-gateway-probe-overview)
* [Create a custom probe for Application Gateway by using the portal](https://docs.microsoft.com/en-us/azure/application-gateway/application-gateway-create-probe-portal)

#### 3.5. Configure listeners
* [Application Gateway listener configuration](https://docs.microsoft.com/en-us/azure/application-gateway/configuration-listeners)

#### 3.6. Configure routing rules
* [Application Gateway request routing rules](https://docs.microsoft.com/en-us/azure/application-gateway/configuration-request-routing-rules)

#### 3.7. Configure HTTP settings
* [Application Gateway HTTP settings configuration](https://docs.microsoft.com/en-us/azure/application-gateway/configuration-http-settings)

#### 3.8. Configure Transport Layer Security (TLS)
* [Overview of TLS termination and end to end TLS with Application Gateway](https://docs.microsoft.com/en-us/azure/application-gateway/ssl-overview)
* [Configure an application gateway with TLS termination using the Azure portal](https://docs.microsoft.com/en-us/azure/application-gateway/create-ssl-portal)

#### 3.9. Configure rewrite sets
* [Rewrite HTTP headers and URL with Application Gateway](https://docs.microsoft.com/en-us/azure/application-gateway/rewrite-http-headers-url)
* [Rewrite HTTP request and response headers with Azure Application Gateway - Azure portal](https://docs.microsoft.com/en-us/azure/application-gateway/rewrite-http-headers-portal)
* [Rewrite URL with Azure Application Gateway - Azure portal](https://docs.microsoft.com/en-us/azure/application-gateway/rewrite-url-portal)

---

### 4. Implement Azure Front Door
* [What is Azure Front Door?](https://docs.microsoft.com/en-us/azure/frontdoor/front-door-overview)
* [Azure Front Door FAQs](https://docs.microsoft.com/en-us/azure/frontdoor/front-door-faq)

#### 4.1. Choose an Azure Front Door SKU
* [What is Azure Front Door Standard/Premium](https://docs.microsoft.com/en-us/azure/frontdoor/standard-premium/overview)
* [Overview of Azure Front Door Standard/Premium SKU](https://docs.microsoft.com/en-us/azure/frontdoor/standard-premium/tier-comparison)

#### 4.2. Configure health probes, including customization of HTTP response codes
* [Health probes](https://docs.microsoft.com/en-us/azure/frontdoor/front-door-health-probes)
* [Create an Azure Front Door Standard/Premium profile - Health Probes](https://docs.microsoft.com/en-us/azure/frontdoor/standard-premium/create-front-door-portal#create-a-front-door-standardpremium-preview-for-your-application)

#### 4.3. Configure SSL termination and end-to-end SSL encryption
* [End-to-end TLS with Azure Front Door](https://docs.microsoft.com/en-us/azure/frontdoor/concept-end-to-end-tls)
* [Configure HTTPS on a Front Door custom domain](https://docs.microsoft.com/en-us/azure/frontdoor/front-door-custom-domain-https)
* [Configure HTTPS on a Front Door Standard/Premium SKU custom domain using the Azure portal](https://docs.microsoft.com/en-us/azure/frontdoor/standard-premium/how-to-configure-https-custom-domain)

#### 4.4. Configure multisite listeners
* [Application Gateway listener configuration - Listener type](https://docs.microsoft.com/en-us/azure/application-gateway/configuration-listeners#listener-type)
* [Application Gateway multiple site hosting](https://docs.microsoft.com/en-us/azure/application-gateway/multiple-site-overview)
* [Create and configure an application gateway to host multiple web sites using the Azure portal](https://docs.microsoft.com/en-us/azure/application-gateway/create-multiple-sites-portal)

#### 4.5. Configure back-end targets
* [Backends and backend pools in Azure Front Door](https://docs.microsoft.com/en-us/azure/frontdoor/front-door-backend-pool)
* [Create a Front Door for a highly available global web application - Create a Front Door for your application](https://docs.microsoft.com/en-us/azure/frontdoor/quickstart-create-front-door#create-a-front-door-for-your-application)

#### 4.6. Configure routing rules, including redirection rules
* [Routing architecture overview](https://docs.microsoft.com/en-us/azure/frontdoor/front-door-routing-architecture)
* [How requests are matched to a routing rule](https://docs.microsoft.com/en-us/azure/frontdoor/front-door-route-matching)
* [Front Door routing methods](https://docs.microsoft.com/en-us/azure/frontdoor/front-door-routing-methods)
* [URL redirect](https://docs.microsoft.com/en-us/azure/frontdoor/front-door-url-redirect)
* [Create a Front Door with HTTP to HTTPS redirection using the Azure portal](https://docs.microsoft.com/en-us/azure/frontdoor/front-door-how-to-redirect-https)
* [Configure an Azure Front Door Standard/Premium Route](https://docs.microsoft.com/en-us/azure/frontdoor/standard-premium/how-to-configure-route)
* [URL redirect and URL rewrite with Azure Front Door Standard/Premium](https://docs.microsoft.com/en-us/azure/frontdoor/standard-premium/concept-rule-set-url-redirect-and-rewrite)

---

### 5. Implement an Azure Traffic Manager profile
* [What is Traffic Manager?](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-overview)
* [How Traffic Manager Works](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-how-it-works)
* [Traffic Manager FAQs](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-faqs)

#### 5.1. Configure a routing method (mode)
* [Traffic Manager routing methods](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-routing-methods)
* [Nested Traffic Manager profiles](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-nested-profiles)
* [Traffic Manager - Performance (Low latency) traffic routing method](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-configure-performance-routing-method)
* [Traffic Manager - Geographic traffic routing method](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-configure-geographic-routing-method)
* [Traffic Manager - Priority traffic routing method](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-configure-priority-routing-method)
* [Traffic Manager - Weighted endpoint routing method](https://docs.microsoft.com/en-us/azure/traffic-manager/tutorial-traffic-manager-weighted-endpoint-routing)
* [Traffic Manager - Subnet routing method](https://docs.microsoft.com/en-us/azure/traffic-manager/tutorial-traffic-manager-subnet-routing)

#### 5.2. Configure endpoints
* [Traffic Manager endpoints](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-endpoint-types)
* [Manage endpoints](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-manage-endpoints)
* [Create Traffic Manager profile - Add Traffic Manager endpoints](https://docs.microsoft.com/en-us/azure/traffic-manager/quickstart-create-traffic-manager-profile#add-traffic-manager-endpoints)

#### 5.3. Create HTTP settings
* [Traffic Manager endpoint monitoring](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-monitoring)

---

### 6. Design and implement an Azure Virtual Network NAT

#### 6.1. Choose when to use a Virtual Network NAT
#### 6.2. Allocate public IP or public IP prefixes for a NAT gateway
#### 6.3. Associate a Virtual Network NAT with a subnet

---

## D. Secure and monitor networks (15-20%)

### 1. Design, implement, and manage an Azure Firewall deployment

#### 1.1. Design an Azure Firewall deployment
#### 1.2. Create and implement an Azure Firewall deployment
#### 1.3. Configure Azure Firewall rules
#### 1.4. Create and implement Azure Firewall Manager policies
#### 1.5. Create a secure hub by deploying Azure Firewall inside an Azure Virtual WAN hub
#### 1.6. Integrate an Azure Virtual WAN hub with a third-party NVA

---

### 2. Implement and manage network security groups (NSGs)

#### 2.1. Create an NSG
#### 2.2. Associate an NSG to a resource
#### 2.3. Create an application security group (ASG)
#### 2.4. Associate an ASG to a NIC
#### 2.5. Create and configure NSG rules
#### 2.6. Interpret NSG flow logs
#### 2.7. Validate NSG flow rules
#### 2.8. Verify IP flow

---

### 3. Implement a Web Application Firewall (WAF) deployment

#### 3.1. Configure detection or prevention mode
#### 3.2. Configure rule sets for Azure Front Door, including Microsoft managed and user defined
#### 3.3. Configure rule sets for Application Gateway, including Microsoft managed and user defined
#### 3.4. Implement a WAF policy
#### 3.5. Associate a WAF policy

---

###  4. Monitor networks

#### 4.1. Configure network health alerts and logging by using Azure Monitor
#### 4.2. Create and configure a Connection Monitor instance
#### 4.3. Configure and use Traffic Analytics
#### 4.4. Configure NSG flow logs
#### 4.5. Enable and configure diagnostic logging
#### 4.6. Configure Azure Network Watcher

---

## E. Design and implement Private access to Azure Services (10-15%)

###  1. Design and implement Azure Private Link service and Azure Private Endpoint

#### 1.1. Create a Private Link service
#### 1.2. Plan private endpoints
#### 1.3. Create private endpoints
#### 1.4. Configure access to private endpoints
#### 1.5. Integrate Private Link with DNS
#### 1.6. Integrate a Private Link service with on-premises clients

---

### 2. Design and implement service endpoints

#### 2.1. Create service endpoints
#### 2.2. Configure service endpoint policies
#### 2.3. Configure service tags
#### 2.4. Configure access to service endpoints

---

### 3. Configure VNet integration for dedicated platform as a service (PaaS) services

#### 3.1. Configure App Service for regional VNet integration
#### 3.2. Configure Azure Kubernetes Service (AKS) for regional VNet integration
#### 3.3. Configure clients to access App Service Environment
