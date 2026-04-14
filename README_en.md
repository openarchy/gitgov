[🇧🇷 Português](README.md) · [🇬🇧 English](README.en.md) · [🇪🇸 Español](README.es.md)

---

# GitGov — Governance as Versioning

[![CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

**335 years of thought. 29 authors. 21 steps.**

Site: [https://codeberg.org/openarchy/gitgov](https://codeberg.org/openarchy/gitgov)   
Mirror: [https://github.com/openarchy/gitgov](https://github.com/openarchy/gitgov)


---

## What is this

A series of more than 25 articles applying Git concepts — the version control system used
by software developers worldwide — as a model for decentralized governance in
any human group, with or without technology.

The thesis fits in one sentence: **governing is versioning. Erring is
registering. Correcting is merging. Authority is peer review.**

## Repository structure

```
articles/
  pt-BR/          # Português — Artigos Originais.  OBS: já finalizados.
  en-US/          # English — translation in progress.
  es-419/         # Castellano / Español — traducción en curso.
mkdocs.yml        # Site configuration
.github/          # GitHub Actions (automatic deployment)
.forgejo/         # Forgejo Actions (Codeberg deployment)
```

## How to contribute

1. Open an **issue** to report errors, suggest improvements or propose translations
2. **Fork** the repo, make your changes and open a **pull request**
3. Keep attribution: `Governance as Versioning — Gustavo Alessandri`
4. Derivatives must use the same **CC BY-SA 4.0** license

## How to run locally

1. Step Zero: Installing the "Engine" (Python)
You need Python installed first. Think of it as the electricity required to run your digital tools.

Windows:

Download the installer from `python.org`.

CRITICAL: On the first screen, check the box `"Add Python to PATH"`. If you skip this, your computer won't find Python later.

Click `"Install Now."`

Mac:

Open Terminal (Command + Space, type "Terminal").

Type 
```python3 --version```. 
If you see a version number, you're set. If not, download the macOS installer from the official site.

Linux (Pop!_OS / Ubuntu):

Open terminal and type: 
```sudo apt update && sudo apt install python3 python3-pip```

Enter your password (it will remain invisible) and hit Enter.

2. Running the Project Locally
Once Python is ready, use these commands in your Terminal:

Navigate to the folder: Type cd, add a space, drag the project folder into the terminal, and hit Enter.

Install the tools: Copy and paste the following:
```pip install mkdocs-material mkdocs-static-i18n```

Start the server: Type:
```mkdocs serve```

View it: Open your browser and go to: ```http://localhost:8000```.

Open `http://localhost:8000` in your browser.

## License

[Creative Commons Attribution-ShareAlike 4.0 International](LICENSE.md)

You are free to copy, adapt and redistribute this material for any purpose,
including commercially, as long as you give appropriate credit to the original
author and distribute your contributions under the same license.
