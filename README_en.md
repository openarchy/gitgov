[🇧🇷 Português](README.md) · [🇬🇧 English](README.en.md) · [🇪🇸 Español](README.es.md)

---

# GitGov — Governance as Versioning

[![CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

**335 years of thought. 29 authors. 21 steps.**

Site: [openarchy.github.io/gitgov](https://openarchy.github.io/gitgov)  
Mirror: [openarchy.codeberg.page/gitgov](https://openarchy.codeberg.page/gitgov)

---

## What is this

A series of 21 articles applying Git concepts — the version control system used
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

```bash
pip install mkdocs-material mkdocs-static-i18n
mkdocs serve
```

Open `http://localhost:8000` in your browser.

## License

[Creative Commons Attribution-ShareAlike 4.0 International](LICENSE.md)

You are free to copy, adapt and redistribute this material for any purpose,
including commercially, as long as you give appropriate credit to the original
author and distribute your contributions under the same license.
