---
title: Content Hierarchy
date: 2022-09-12
slug: content
---
<!---or, if you would, hier(7)-->
## Where's my stuff?

For most people, the two most important folders are `/content` (where actual pages are written) and `/static` where static files (like images or PDFs) are stored.


## How does the content folder work?

All Hugo sites are generated from the markdown files located in `content/`. For example, this repository's `content/` folder looks like:

{{< highlight Shell >}}
content/
├── _index.md # site homepage
├── about 
│   ├── _index.md # /about top-level page
│   ├── hierarchy.md # this page, hi!
│   ├── why.md 
│   └── workflow.md
├── platforms
│   ├── _index.md
│   └── geoportal.md
├── policies
│   ├── _index.md
│   └── log-retention.md
├── projects
│   ├── _index.md
│   └── experts # we could add further levels, including additional subfolders
│       └── _index.md # the page for /projects/experts (we could just call it experts.md too)
└── services
    ├── _index.md
    └── ssl.md
{{< /highlight >}}


