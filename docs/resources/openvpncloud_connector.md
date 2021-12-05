---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "openvpncloud_connector Resource - terraform-provider-openvpn-cloud"
subcategory: ""
description: |-
  
---

# openvpncloud_connector (Resource)

Use `openvpncloud_connector` to create an OpenVPN Cloud connector.

~> NOTE: This only creates the OpenVPN Cloud connector object. Additional manual steps are required to associate a host in your infrastructure with the connector. Go to https://openvpn.net/cloud-docs/connector/ for more information.



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **name** (String) The connector display name.
- **network_item_id** (String) The id of the network with which this connector is associated.
- **network_item_type** (String) The type of network item of the connector. Supported values are `HOST` and `NETWORK`.
- **vpn_region_id** (String) The id of the region where the connector will be deployed.

### Read-Only

- **id** (String) The ID of this resource.
- **ip_v4_address** (String) The IPV4 address of the connector.
- **ip_v6_address** (String) The IPV6 address of the connector.