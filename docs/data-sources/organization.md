---
page_title: "hcp_organization Data Source - terraform-provider-hcp"
subcategory: "Cloud Platform"
description: |-
  The organization data source retrieves the HCP organization the provider is configured for.
---

# hcp_organization (Data Source)

The organization data source retrieves the HCP organization the provider is configured for.

## Example Usage

```terraform
data "hcp_organization" "example" {
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Read-Only

- `name` (String) The organization's name.
- `resource_id` (String) The organization's unique identitier
- `resource_name` (String) The organization's resource name in format "organization/<resource_id>"