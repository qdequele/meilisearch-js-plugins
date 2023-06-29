# CommandBar

## Features
- [ ] Open the command bar with a cmd+k shortcut by default. (Can be changed in the settings)
- [ ] Search on a list of preset commands. Commands contain a name, a callback or a link to a page.
- [ ] Search into a Meilisearch index.
- [ ] Search into a multiples Meilisearch indexes at once.
- [ ] Define group of Meilisearch indexes that may be search separately.

```json
[
    {
    id: "blog",
    name: "Blog",
    shortcut: ["b"],
    keywords: "writing words",
    perform: () => (window.location.pathname = "blog"),
    },
    {
    id: "contact",
    name: "Contact",
    shortcut: ["c"],
    keywords: "email",
    perform: () => (window.location.pathname = "contact"),
    },
]
```
