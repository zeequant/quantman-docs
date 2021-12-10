# Quantman

- Quantman DOCS / FAQ 
- We use [mkdocs](https://www.mkdocs.org/) static site generator.
- Theme: [material](https://github.com/squidfunk/mkdocs-material).


#### Branch Structure:

- We use two seperate branches.
- Master - For having mkdocs Config files to generate HTML content
- gh-pages - For having Actual generated HTML content.


#### New Setup.

```
pip install mkdocs

pip install mkdocs-material

mkdocs new quantman-docs
```

#### To Run in local:

To Install pip in OSX follow: https://www.geeksforgeeks.org/how-to-install-pip-in-macos/
```
pip install mkdocs

mkdocs serve
```

#### To Deploy in Github-Pages:

- Build command - Generate a HTML content for a site using a config files.

```
mkdocs build
```

- gh-deploy - Push the Generated HTML content to Remote Repo at the Branch (gh-pages).

```
mkdocs gh-deploy
```

- We configure the GihubPage to use HTML file from gh-pages branch under root directory.
