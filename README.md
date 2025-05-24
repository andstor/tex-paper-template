# tex-paper-template
> LaTeX paper template


## Requirements

Create a personal access token with all `repo` and `workflow` permissions. Add this as a secret named `PERSONAL_TOKEN`.

## Setup

This template supports automatic syncing of bibliographies and glossaries. The bibliographies and glossaries are stored in separate repositories, and synced between all papers using this template. To recieve updates from the bibliography db, this repository has to register. This is done by running the github workflows [`register_bibliography.yml`](.github/workflows/register_bibliography.yml) and [`register_glossary.yml`](.github/workflows/register_glossary.yml).

## Manuscript templates

To use common academic manuscript templates, simply copy the contents into root directory.

- [ACM Primary Article Template](https://github.com/andstor/acm-primary-article-template)
- [IEEE Conference Template](https://github.com/andstor/ieee-conference-template)
