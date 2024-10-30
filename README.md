# RoX TP5

## General Setup

Clone the repository

```bash
git clone git@github.com:rox-tp-5/docs.git
```

Create a Python Env and activate the env

```bash
python -m venv venv && source venv/bin/activate
```

Install mkdocs

```bash
pip install mkdocs mkdocs-material mkdocs-glossary
```

## Add content

Change / edit or contribute to markdown files in `docs/`.

Add changes to github

```bash
git add .

git commit -m "<...>"

git push
```

Add new files and content to menu structure. This done in `mkdocs.yml`.

Deploy changes

```bash
mkdocs gh-deploy
```


