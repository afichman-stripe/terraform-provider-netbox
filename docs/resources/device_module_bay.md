---
# generated by https://github.com/fbreckle/terraform-plugin-docs
page_title: "netbox_device_module_bay Resource - terraform-provider-netbox"
subcategory: "Data Center Inventory Management (DCIM)"
description: |-
  From the official documentation https://docs.netbox.dev/en/stable/models/dcim/modulebay/:
  Module bays represent a space or slot within a device in which a field-replaceable module may be installed. A common example is that of a chassis-based switch such as the Cisco Nexus 9000 or Juniper EX9200. Modules in turn hold additional components that become available to the parent device.
---

# netbox_device_module_bay (Resource)

From the [official documentation](https://docs.netbox.dev/en/stable/models/dcim/modulebay/):

> Module bays represent a space or slot within a device in which a field-replaceable module may be installed. A common example is that of a chassis-based switch such as the Cisco Nexus 9000 or Juniper EX9200. Modules in turn hold additional components that become available to the parent device.



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `device_id` (Number)
- `name` (String)

### Optional

- `custom_fields` (Map of String)
- `description` (String)
- `label` (String)
- `position` (String)
- `tags` (Set of String)

### Read-Only

- `id` (String) The ID of this resource.

