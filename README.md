# paper-template
> LaTeX paper template


## Requirements

Create a personal access token with all `repo` and `workflow` permissions. Add this as a secret named `PERSONAL_TOKEN`.

## Setup

This template supports automatic syncing of bibliographies and glossaries. The bibliographies and glossaries are stored in separate repositories, and synced between all papers using this template. To recieve updates from the bibliography db, this repository has to register. This is done by running the github workflows [`register_bibliography.yml`](.github/workflows/register_bibliography.yml) and [`register_glossary.yml`](.github/workflows/register_glossary.yml).

## Manuscript templates

Several common academic manuscript templates are available as submodules under `./templates`. Copy contents into root directory.

> [!NOTE]  
> Overleaf does not support submodules.
