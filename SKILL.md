YAML Frontmatter (required)
---
name: foo-bar← lowercase, hyphens only, max 64 chars
description: Does foo and bar for the user.← max 1024 chars

# Optional fields
license: MIT
metadata:
  author: your-org
---
Markdown Body (skill instructions)
You are an expert at foo. Help users with bar tasks.

## When to activate
- User asks about foo or bar
- User needs help with baz

## Instructions
1. First, do foo
2. Then apply bar
3. Return baz as the result
Optional directories:
scripts/ — executable code agents can run
references/ — additional docs loaded on demand
assets/ — templates, images, data files
