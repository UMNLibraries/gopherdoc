---
title: Editing Goldydoc
date: 2022-09-12
slug: workflow
---

Goldydoc is created using [`hugo`](https://gohugo.io), a static site generator written in `go`. This means it generates HTML pages with minimal bloat from simple text files written using [Markdown](https://docs.github.com/en/get-started/writing-on-github).

## Editing an existing page

### From any page on Goldydoc

- Click the "Edit Page" link in the top right to be taken directly to the file for the page in question on github.umn.edu
- Click "edit"

{{< hint icon=gdoc_heart title=Theming >}}

Depending on how we might want to manage revisions, we could change the Edit Page link to the Github repo issues page

{{< /hint  >}}

### Using github.umn.edu

1. Navigate to the appropriate directory in the [repository](https://github.umn.edu/libraries/foo)
2. click the edit button in the markdown file.
3. make your changes 
4. add a commit message
5. foo bar baz

### using the commandline/editing on your computer

1. clone the repository with `git clone git@github.umn.edu:libraries/goldydoc.git`
2. find the appropriate file 
3. type `emacs foo.md`

## Adding new content

### Using github.umn.edu
1. copy the template from this page (link to raw version of a page template file)


### using the commandline
1. copy the template file to the appropriate place and name in the `docs` directory
2. edit as appropriate
3. commit file
4. etc. etc. 

