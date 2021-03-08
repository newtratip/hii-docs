# Ecosoft MKDocs Document Template

## What is MKDocs?

* This document template is based https://www.mkdocs.org with PDF export extension https://pypi.org/project/mkdocs-with-pdf/
* Based on `.md` format, this can generate a beautiful document website and PDF.

To understand how mkdocs works, following few line of code (in linux) will do.

```
$ pip3 install mkdocs               # Install the package
$ cd ~                              # Go to home directory
$ mkdocs new my-doc-project         # Initial the document project folder
$ cd my-doc-project                 # Do to project directory, now a sample index.md is created
$ mkdocs build                      # OR build the site folder, which can be deployed in a web server
$ mkdocs serve                      # Start the test server, to see how it looks at http://localhost:8000/
```

For more detail, please visit https://www.mkdocs.org

## Installation

1. Install mkdocs and mkdocs-with-pdf plugin
    ```
    $ pip3 install mkdocs
    $ pip3 install mkdocs-with-pdf
    ```
2. Clone this repo for your project documentation
    ```
    $ git clone https://github.com/ecosoft-odoo/eco_mkdocs my-doc-project
    ```

## Using this template

Use `.md` files as sample, it should be easy enough to get started. Just a few notes that,

* `mkdocs.yaml` is the configuration file (enough for Ecosoft). More detailed here, https://www.mkdocs.org/user-guide/configuration/
* All `.md` source files will be in `docs` folder, this is where you add content.
* To build all `.md` files into a `site` folder, run command, `> mkdocs build`. Note that PDF file will be created into `site/pdf`
* To test, run command, `> mkdocs build` and go to http://localhost:8000/

Markdown Cheatsheet:
* https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

**Note:**

* The `site` folder is ignored by `.gitignore`
* Just push to master barnch, github action in `.github/workflows/ci.yml` will auto generate `site` folder into branch `gh-pages`.
* If you enable **Github Pages** on branch `gh-pages`, you will get the document site at `https://<my_account>.github.io/<my_project>`

**Remarks:**

This document template can be viewed here -> https://ecosoft-odoo.github.io/eco_mkdocs/
# hii-docs
