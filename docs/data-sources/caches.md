---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "momento_caches Data Source - terraform-provider-momento"
subcategory: ""
description: |-
  A list of Momento serverless caches.
---

# momento_caches (Data Source)

A list of Momento serverless caches.

## Example Usage

```terraform
# List all Momento serverless caches.
data "momento_caches" "all" {}
```

## Argument Reference

- `caches` (Attributes List) List of caches. (see [below for nested schema](#nestedatt--caches))
- `id` (String) Placeholder identifier attribute.

<a id="nestedatt--caches"></a>
### Nested Schema for `caches`

## Attribute Reference

- `name` (String) Name of the cache.
