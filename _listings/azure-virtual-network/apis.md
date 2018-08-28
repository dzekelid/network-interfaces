---
name: Azure Virtual Network
x-slug: azure-virtual-network
description: Azure Virtual Network lets you create private networks in the cloud with
  full control over IP addresses, DNS servers, security rules, and traffic flows.
  Securely connect a virtual network to on-premises networks by using a VPN tunnel,
  or connect privately by using the ExpressRoute service.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Network Interfaces
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/apis.md
specificationVersion: "0.14"
apis:
- name: NetworkManagementClient - Network Interfaces Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworkinterfacesnetworkinterfacename-delete
  description: Deletes the specified network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworkinterfacesnetworkinterfacename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworkinterfacesnetworkinterfacename-delete-openapi.md
- name: NetworkManagementClient - Network Interfaces Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworkinterfacesnetworkinterfacename-get
  description: Gets information about the specified network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworkinterfacesnetworkinterfacename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworkinterfacesnetworkinterfacename-get-openapi.md
- name: NetworkManagementClient - Network Interfaces Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworkinterfacesnetworkinterfacename-put
  description: Creates or updates a network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworkinterfacesnetworkinterfacename-put-openapi.md
- name: NetworkManagementClient - Network Interfaces List All
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-networknetworkinterfaces-get
  description: Gets all network interfaces in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoft-networknetworkinterfaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidprovidersmicrosoft-networknetworkinterfaces-get-openapi.md
- name: NetworkManagementClient - Network Interfaces List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworkinterfaces-get
  description: Gets all network interfaces in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworkinterfaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworkinterfaces-get-openapi.md
- name: NetworkManagementClient - Network Interfaces Get Effective Route Table
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworkinterfacesnetworkinterfacenameeffectiveroutetable-post
  description: Gets all route tables applied to a network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworkinterfacesnetworkinterfacenameeffectiveroutetable-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworkinterfacesnetworkinterfacenameeffectiveroutetable-post-openapi.md
- name: NetworkManagementClient - Network Interfaces List Effective Network Security
    Groups
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworkinterfacesnetworkinterfacenameeffectivenetworksecuritygroups-post
  description: Gets all network security groups applied to a network interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworkinterfacesnetworkinterfacenameeffectivenetworksecuritygroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworkinterfacesnetworkinterfacenameeffectivenetworksecuritygroups-post-openapi.md
- name: NetworkManagementClient - Network Interfaces List Virtual Machine Scale Set
    VMNetwork Interfaces
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-computevirtualmachinescalesetsvirtualmachinescalesetnamevirtualmachinesvirtualmachineindexnetworkinterfaces-get
  description: Gets information about all network interfaces in a virtual machine
    in a virtual machine scale set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-computevirtualmachinescalesetsvirtualmachinescalesetnamevirtualmachinesvirtualmachineindexnetworkinterfaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-computevirtualmachinescalesetsvirtualmachinescalesetnamevirtualmachinesvirtualmachineindexnetworkinterfaces-get-openapi.md
- name: NetworkManagementClient - Network Interfaces List Virtual Machine Scale Set
    Network Interfaces
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-computevirtualmachinescalesetsvirtualmachinescalesetnamenetworkinterfaces-get
  description: Gets all network interfaces in a virtual machine scale set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-computevirtualmachinescalesetsvirtualmachinescalesetnamenetworkinterfaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-computevirtualmachinescalesetsvirtualmachinescalesetnamenetworkinterfaces-get-openapi.md
- name: NetworkManagementClient - Network Interfaces Get Virtual Machine Scale Set
    Network Interface
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-computevirtualmachinescalesetsvirtualmachinescalesetnamevirtualmachinesvirtualmachineindexnetworkinterfacesnetworkinterfacename-get
  description: Get the specified network interface in a virtual machine scale set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Profiles, Relative
    Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-computevirtualmachinescalesetsvirtualmachinescalesetnamevirtualmachinesvirtualmachineindexnetworkinterfacesnetworkinterfacename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/network-interfaces/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-computevirtualmachinescalesetsvirtualmachinescalesetnamevirtualmachinesvirtualmachineindexnetworkinterfacesnetworkinterfacename-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.traffic.manager.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.virtual.network.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/virtual-network/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/virtual-network/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/virtual-network/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---