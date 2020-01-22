---
title: "Theme Overview"
menu: "styleguide"
weight: 6
---

This page will include information on the CSS selectors used in your stylesheets.

The assumption is you are following the pattern of:

```
.n-hopin-c-my-component__sub-section--fancy
|_______|_|___________|____________|_______|
    |     |      |           |         |
Namespace |      |           |         |
        Type     |           |         |
                Body         |         |
                          Element      |
                                    Modifier
```

The namespace, element and modifier are optional, so you can
have names such as:

.c-header
.c-header--larger
.c-header__link

The `type` of a selector should be one of the following:

- `c` Component
- `l` Layout
- `u` Utility

{{< load-partial "components/styleguide-overview-classnames.html" >}}
