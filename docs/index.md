---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "sendgrid Provider"
subcategory: ""
description: |-
  
---

# sendgrid Provider



## Example Usage

```terraform
terraform {
  required_providers {
    sendgrid = {
      source = "registry.terraform.io/kenzo0107/sendgrid"
    }
  }
}

provider "sendgrid" {
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `api_key` (String, Sensitive) Username for Sendgrid API. May also be provided via SENDGRID_SUBUSER environment variable.
- `subuser` (String) Subuser for Sendgrid API. May also be provided via SENDGRID_SUBUSER environment variable.
