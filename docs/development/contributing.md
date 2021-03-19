---
title: Contributing
description: Information for anyone interested in developing or forking this extension.
authors:
	- CouldBeThis
date: 2021-03-15
# use for root-level document:
#typora-copy-images-to: /images
# use for 2ndary level document:
typora-copy-images-to: ../images
---

# Contributing

## Introduction

TODO: What is this page about?

## DuckDuckLib Firefox extension

TODO

## website

[note](https://www.mkdocs.org/user-guide/deploying-your-docs/#organization-and-user-pages):

> Warning
>
> You should never edit files in your pages repository by hand if you're using the `gh-deploy` command because you will lose your work the next time you run the command.

Question: if this is the case what is the purpose of `edit_uri` in mkdocs.yml? [see docs](https://www.mkdocs.org/user-guide/configuration/#edit_uri)

### mkDocs

See [mkdocs.yml](https://github.com/DuckDuckLib/DuckDuckLib.github.io/blob/main/mkdocs.yml) in the github repo for all enabled configuration options

#### Environment

In addition to `mkdocs`, the following 3rd party plugins are required to build the website:

n/a

#### Building

```zsh
#cd ../DuckDuckLib.github.io
mkdocs gh-deploy --config-file ./mkdocs.yml --remote-branch main

mkdocs gh-deploy --config-file mkdocs.yml --remote-branch main
```



### Writing

#### Template

use template 

#### Admonitions

The [Admonition](https://python-markdown.github.io/extensions/admonition/) plugin is enabled. 

```markdown
!!! type "optional explicit title within double quotes"
    Any number of other indented markdown elements.

    This is the second paragraph.
```





























