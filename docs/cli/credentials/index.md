---
title: eg credentials
layout: doc-section
doc-order: 4.4
---

### Description

Manage credentials

### Usage

```shell
eg credentials <command> [options]
```

### Child commands

| Command                  | Description                                            | Alias |
| ---                      | ---                                                    | ---   |
| [create][create]         | Create credentials for user or app with specified type |       |
| [activate][activate]     | Activates a credential by id or keyid                  |       |
| [deactivate][deactivate] | Deactivates a credential by id or keyid                |       |
| [info][info]             | Show details for a single credential                   |       |
| [list][list]             | Show all credentials for consumer                      |       |

[create]: {{ site.baseurl }}{% link docs/cli/credentials/create.md %}
[activate]: {{ site.baseurl }}{% link docs/cli/credentials/activate.md %}
[deactivate]: {{ site.baseurl }}{% link docs/cli/credentials/deactivate.md %}
[info]: {{ site.baseurl }}{% link docs/cli/credentials/info.md %}
[list]: {{ site.baseurl }}{% link docs/cli/credentials/list.md %}
