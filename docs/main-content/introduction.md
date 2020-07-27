
Introduction
============

We all believe that a safe, sustainable and well-understood environment
that makes best use of new and existing resources is a cornerstone of
progress.

From the management and use of natural resources to the safe creation,
regeneration and maintenance of the built environment, we understand
that high-quality site investigation coupled with conceptual geological
understanding is key. Software that enables you to interpret your data,
create models and communicate risks and insights can take things to the
next level, but such digital tools are often complex, highly specialised
and costly.

That\'s why we\'re developing **Groundhog Desktop**

We believe that you should have access to geological software which is
powerful, without it being complicated or expensive. Our software is
available in both no-cost \"Community\" and low-cost \"Professional\"
editions. With Groundhog, our mission is to provide you with a simple,
effective way of visualising and interpreting site data as well as
developing conceptual and 3D digital geological models.

To get started with the no-cost Community Edition of our software,
please go to <https://www.bgs.ac.uk/groundhog>

For Groundhog Professional license keys and trials please visit LQM -
<https://www.lqm.co.uk/csm>


Documenting the Documentation
=============================

```
pandoc -s Groundhog_User_Guide.docx -t gfm -o userguide.md --extract-media=.
```

This documentation is written in ReStructured Text hosted on GitHub
pages, built using Sphinx via Gitub Actions CI/CD.

To setup

-   follow Sphinx quickstart
-   save to GitHub repo
-   edit repo settings to enable GitHub pages from gh-pages branch.
-   Create .github/workflows/gh-pages.yml

``` {.bash}
name: github pages

on:
push:
branches:
  - master

jobs:
    make-pages:
      runs-on: ubuntu-latest
      steps:
      - uses: actions/checkout@v1

      - name: select python version
        uses: actions/setup-python@v1
        with:
          python-version: '3.7'

      - name: install dependencies
        run: |
          python -m pip install --upgrade pip
          python -m pip install sphinx
          python -m pip install sphinx_rtd_theme
      - name: build documentation
        run: |
          cd docs
          make html
          touch _build/html/.nojekyll
      - name: deploy
        uses: peaceiris/actions-gh-pages@v2
        env:
          ACTIONS_DEPLOY_KEY: ${{ secrets.ghpagesdk }}
          PUBLISH_BRANCH: gh-pages
          PUBLISH_DIR: docs/_build/html
```

-   Create SSH keys in Linux/Putty
-   In repo settings\>deploy add a=deply key such as \"ghpagesdk\" and
    copy/paste public key hash
-   In repo settings\>secrets add a secret key with same name
    \"ghpagesdk\" and copy/paste private key hash.
-   make a commit to the master brach and should all be working.
