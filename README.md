# AZ-700: Designing and Implementing Microsoft Azure Networking Solutions - Study Guide
This study guide is based on the November 23, 2021 exam update

## A. Design, implement, and manage hybrid networking (10-15%)

### 1. Design, implement, and manage a site-to-site VPN connection

#### 1.1. design a site-to-site VPN connection for high availability
#### 1.2. select an appropriate virtual network (VNet) gateway SKU
#### 1.3. identify when to use policy-based VPN versus route-based VPN
#### 1.4. create and configure a local network gateway
#### 1.5 create and configure an IPsec/IKE policy
#### 1.6 create and configure a virtual network gateway
#### 1.7 diagnose and resolve virtual network gateway connectivity issues

### 2. Design, implement, and manage a point-to-site VPN connection

#### 2.1. select an appropriate virtual network gateway SKU
#### 2.2. plan and configure RADIUS authentication
#### 2.3. plan and configure certificate-based authentication
#### 2.4. plan and configure OpenVPN authentication
#### 2.5. plan and configure Azure Active Directory (Azure AD) authentication
#### 2.6. implement a VPN client configuration file
#### 2.7. diagnose and resolve client-side and authentication issues

### 3. Design, implement, and manage Azure ExpressRoute

#### 3.1. choose between provider and direct model (ExpressRoute Direct)
#### 3.2. design and implement Azure cross-region connectivity between multiple ExpressRoute locations
#### 3.3. select an appropriate ExpressRoute SKU and tier
#### 3.4. design and implement ExpressRoute Global Reach
#### 3.5. design and implement ExpressRoute FastPath
#### 3.6. choose between private peering only, Microsoft peering only, or both
#### 3.7. configure private peering
#### 3.8. configure Microsoft peering
#### 3.9. create and configure an ExpressRoute gateway
#### 3.10. connect a virtual network to an ExpressRoute circuit
#### 3.11. recommend a route advertisement configuration
#### 3.12. configure encryption over ExpressRoute
#### 3.13. implement Bidirectional Forwarding Detection
#### 3.14. diagnose and resolve ExpressRoute connection issues

## B. Design and implement core networking infrastructure (20-25%)

### 1. Design and implement private IP addressing for VNets

#### 1.1. create a VNet
#### 1.2. plan and configure subnetting for services, including VNet gateways, private endpoints, firewalls, application gateways, and VNet-integrated platform services
#### 1.3. plan and configure subnet delegation
#### 1.4. plan and configure subnetting for Azure Route Server

### 2. Design and implement name resolution

#### 2.1. design public DNS zones
#### 2.2. design private DNS zones
#### 2.3. design name resolution inside a VNet
#### 2.4. configure a public or private DNS zone
#### 2.5 link a private DNS zone to a VNet

### 3. Design and implement cross-VNet connectivity

#### 3.1. design service chaining, including gateway transit
#### 3.2. design VPN connectivity between VNets
#### 3.3. implement VNet peering

### 4. Design and implement an Azure Virtual WAN architecture

#### 4.1. design an Azure Virtual WAN architecture, including selecting types and services
#### 4.2. connect a VNet gateway to Azure Virtual WAN
#### 4.3. create a hub in Virtual WAN
#### 4.4. create a network virtual appliance (NVA) in a virtual hub
#### 4.5. configure virtual hub routing
#### 4.6 create a connection unit

## C. Design and implement routing (25-30%)

### 1. Design, implement, and manage VNet routing

#### 1.1. design and implement user-defined routes (UDRs)
#### 1.2. associate a route table with a subnet
#### 1.3. configure forced tunneling
#### 1.4. diagnose and resolve routing issues
#### 1.5. design and implement Azure Route Server

### 2. Design and implement an Azure Load Balancer

#### 2.1. choose an Azure Load Balancer SKU (Basic versus Standard)
#### 2.2. choose between public and internal
#### 2.3. create and configure an Azure Load Balancer (including cross-region)
#### 2.4. implement a load balancing rule
#### 2.5. create and configure inbound NAT rules
#### 2.6. create explicit outbound rules for a load balancer

### 3. Design and implement Azure Application Gateway

#### 3.1. recommend Azure Application Gateway deployment options
#### 3.2. choose between manual and autoscale
#### 3.3. create a back-end pool
#### 3.4. configure health probes
#### 3.5. configure listeners
#### 3.6. configure routing rules
#### 3.7. configure HTTP settings
#### 3.8. configure Transport Layer Security (TLS)
#### 3.9. configure rewrite sets

### 4. Implement Azure Front Door

#### 4.1. choose an Azure Front Door SKU
#### 4.2. configure health probes, including customization of HTTP response codes
#### 4.3. configure SSL termination and end-to-end SSL encryption
#### 4.4. configure multisite listeners
#### 4.5. configure back-end targets
#### 4.6. configure routing rules, including redirection rules

### 5. Implement an Azure Traffic Manager profile

#### 5.1. configure a routing method (mode)
#### 5.2. configure endpoints
#### 5.3. create HTTP settings

### 6. Design and implement an Azure Virtual Network NAT

#### 6.1. choose when to use a Virtual Network NAT
#### 6.2. allocate public IP or public IP prefixes for a NAT gateway
#### 6.3. associate a Virtual Network NAT with a subnet

## D. Secure and monitor networks (15-20%)

## E. Design and implement Private access to Azure Services (10-15%)
