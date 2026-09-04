# Adding Book Covers

Each book folder has an `index.md` file. To add a cover thumbnail, put the image in that same folder and add a `cover` block inside the top YAML section.

Good example:

```yaml
---
title: "Philological Investigations: Studies in Early and Medieval China"
date: 2026-01-01
tags: ["philology","early China","medieval China"]
author: ["Nicholas Morrow Williams","Timothy O'Neill"]
description: "An edited volume of studies in early and medieval China."
summary: "Co-edited with Timothy O'Neill, this volume gathers studies in early and medieval China."
cover:
    image: "cover.png"
    alt: "Philological Investigations"
    relative: true
showToc: false
disableAnchoredHeadings: false
---

#### Publication Details

Co-edited with Timothy O'Neill. Leiden: Brill, 2026.
```

Important:

- The `cover:` block must be above the closing `---`.
- The image filename must match exactly, including `.jpg`, `.jpeg`, or `.png`.
- Do not paste backslashes before YAML characters. Use `---`, not `\---`; use `["tag"]`, not `\["tag"]`.
- The lines under `cover:` must be indented.
