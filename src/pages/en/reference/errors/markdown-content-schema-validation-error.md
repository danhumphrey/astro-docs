---
# NOTE: This file is auto-generated from 'scripts/error-docgen.mjs'
# Do not make edits to it directly, they will be overwritten.
# Instead, change this file: https://github.com/withastro/astro/blob/main/packages/astro/src/core/errors/errors-data.ts
# Translators, please remove this note and the <DontEditWarning/> component.

layout: ~/layouts/MainLayout.astro
title: Content collection frontmatter invalid.
i18nReady: true
githubURL: https://github.com/withastro/astro/blob/main/packages/astro/src/core/errors/errors-data.ts
setup: |
  import DontEditWarning from '../../../../components/DontEditWarning.astro';
---

<DontEditWarning />


> **Example error message:**<br/>
Could not parse frontmatter in **blog** → **post.md**<br/>
"title" is required.<br/>
"date" must be a valid date. (E06002)

## What went wrong?
A Markdown document's frontmatter in `src/content/` does not match its collection schema.
Make sure that all required fields are present, and that all fields are of the correct type.
You can check against the collection schema in your `src/content/config.*` file.
See the [Content collections documentation](/en/guides/content-collections/) for more information.



