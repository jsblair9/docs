---
id: 4b4bd7a7-6fc8-4457-b030-56d4474e20b0
types:
  - content
---
Get the URL to edit a the current page or entry in the Control Panel, if there is one (for example, there is no `edit_url` for a template route).

The user will need to login and have permissions, so it's probably best if used in conjunction with [permissions checks](/reference/tags/user-can).

```
<a href="{{ edit_url }}">Edit this page</a>
```

``` .language-output
<a href="/cp/pages/edit/about-ye-old-me">Edit this page</a>
```
