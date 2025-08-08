# MAGICC Lab Primary Website

Deployed website link: https://byu-magicc.github.io/

This is the location of the primary website for the MAGICC lab, focusing on the accomplishments and research areas of the lab.
This is what we want people to see when they are looking for a first introduction to the lab.
Guides and other less-important information should be placed in either the [public](https://github.com/byu-magicc/wiki) or [private](https://github.com/byu-magicc/wiki-private) wikis.

This website is built with Material for MkDocs. The guide below describes how to get the website up and running on a local machine for easy editing. For more extensive documentation, visit the [official documentation](https://squidfunk.github.io/mkdocs-material/).

## Adding a student or project page
To add a student page, navigate to [docs/directory/current_students.md](docs/directory/current_students.md) and follow the instructions found there.
To add a project page, navigate to [docs/research/current_projects.md](docs/research/current_projects.md) and follow the instructions there.
If you have any questions, reach out to one of the lab webmasters and they can assist you.

## Install mkdocs
``` bash
pip install -r requirements.txt
```
## Run the mkdocs Server
Type `mkdocs serve` in the root directory. It should report to you something like:

``` bash
[I 170728 07:49:47 server:271] Serving on http://127.0.0.1:8000
[I 170728 07:49:47 handlers:58] Start watching changes
```

This means that mkdocs is hosting a webpage for you on http://127.0.0.1:8000. Navigate to that page in your web browser.

Now, as you make changes to the documentation, you should be able to see it on your browser. Just hit reload from time to time to see your changes.

## Adding LaTeX
The syntax for adding LaTeX math inline is `\( x \)`, which renders as x. For adding a block, it's

``` latex
$$ E = mc^2 $$
```

## Publishing changes on website
Any changes that are pushed to the main branch will automatically be applied to the website. Just submit a pull request!
