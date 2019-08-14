# stack-templates

Stack templates as described here https://docs.haskellstack.org/en/stable/GUIDE/#templates

## How-to create a new project using `protolude` template

* `stack new <project name> unisay/protolude -p "author-email:<email>" -p "author-name:<name>" -p "category:<category>" -p "copyright:<copy>" -p "github-username:<username>"`  

(Replace angle-bracketed placeholders by your own values)

Alternatively, specify placeholder values in the `~/.stack/config.yaml` like this:
```yaml
templates:
  params:
    author-email: unisay@users.noreply.github.com
    author-name: Yuriy Lazaryev
    copyright: 2019 Yuriy Lazaryev
    github-username: unisay
    category: development
```
and then you don't have to specify them in the command line parameters.
