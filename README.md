# Bruno

## A simple and minimal jekyll remote theme

### How to get started

1. Create folder `_chapters`
2. In this folder create one or more markdown files
3. Create `_config.yml`

```yaml
remote_theme: werktat/bruno

collections:
  chapters:
    output: true
```

### Layouts

In markdown files create frontmatter and use
one of the following layouts:

* home
* article
* codearticle

For example `file.md`

```markdown
---
layout: article
---

# My markdown title

```
