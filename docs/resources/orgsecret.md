---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "drone_orgsecret Resource - terraform-provider-drone"
subcategory: ""
description: |-
  
---

# drone_orgsecret (Resource)



## Example Usage

```terraform
resource "drone_orgsecret" "example" {
  namespace = "example"
  name      = "example"
  data      = "example"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **data** (String, Sensitive)
- **name** (String)
- **namespace** (String)

### Optional

- **id** (String) The ID of this resource.


