---
bookCollapseSection: true
bookHidden: true
---

# Section

Section renders pages in section as definition list, using title and description. Optional param `summary` can be used to show or hide page summary

## Example

```tpl
{{</* section [summary] */>}}
```

> [!WARNING]
> The `section` shortcode is deprecated by the theme and will be removed. Link child pages directly instead:

- [First page]({{< relref "first-page" >}})
- [Second Page]({{< relref "second-page" >}})
