# Welcome to MkDocs

For full documentation visit [mkdocs.org](http://mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## fresh setup
 1.  run ``` mkdocs new tcprojWrapper ```
 2.  edit mkdocs.yml **site_name** to tcprojWrapper
 3.  ``` git add . ``` then git commit
 4.  Add a theme as a git submodule:    ```git submodule add https://github.com/emlid/docstheme.git```
