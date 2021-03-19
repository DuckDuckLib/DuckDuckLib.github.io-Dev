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

In addition to `mkdocs`, the following 3rd party plugins are required to build the website. Install scripts listed first, all together, followed by details about what they are and why they are needed.

```zsh
# mkdcomments
pip3 pip install git+https://github.com/ryneeverett/python-markdown-comments.git
# mkdocs-material
pip3 install mkdocs-material # also available: docker and git
```

##### `mkdcomments`

github: [ryneeverett/python-markdown-comments](https://github.com/ryneeverett/python-markdown-comments)

> Removes triple-dashed html comments (`<!---comment-->`) in preprocessing.

required to fix (workaround) issue: [YAML frontmatter parsed totally wrong when published to github pages via gh-deploy · Issue #23 · DuckDuckLib/duckduckLib](https://github.com/DuckDuckLib/duckduckLib/issues/23)

##### `mkdocs-material`

github: [squidfunk/mkdocs-material: A Material Design theme for MkDocs](https://github.com/squidfunk/mkdocs-material)

docs/demo: [Getting started - Material for MkDocs](https://squidfunk.github.io/mkdocs-material/getting-started/)



> Create a branded static site from a set of Markdown files to host the  documentation of your Open Source or commercial project – customizable,  searchable, mobile-friendly, 40+ languages. Set up in 5 minutes.

#### Building

```zsh
cd ../DuckDuckLib.github.io
mkdocs gh-deploy --config-file mkdocs.yml
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





























