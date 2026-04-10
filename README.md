[🇧🇷 Português](README.md) · [🇬🇧 English](README_en.md) · [🇪🇸 Español](README_es.md)

---

# GitGov — Governança como Versionamento

[![CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

**335 anos de pensamento. 29 autores. 21 passos.**

Site: [https://codeberg.org/openarchy/gitgov](https://codeberg.org/openarchy/gitgov)   
Espelho: [https://github.com/openarchy/gitgov](https://github.com/openarchy/gitgov)


---

## O que é isto

Uma série de mais de 25 artigos que aplica os conceitos do Git — o sistema de controle
de versões usado por programadores — como modelo de governança descentralizada
para qualquer grupo humano, com ou sem tecnologia.

A tese: **governar é versionar. Errar é registrar. Corrigir é integrar.
Autoridade é revisão por pares.**

## Estrutura do repositório

```
articles/
  pt-BR/          # Português — Artigos Originais.  OBS: já finalizados.
  en-US/          # English — translation in progress.
  es-419/         # Castellano / Español — traducción en curso.
mkdocs.yml        # Configuração do site
.github/          # GitHub Actions (deploy automático)
.forgejo/         # Forgejo Actions (deploy no Codeberg)
```

## Como contribuir

1. Abre uma **issue** para reportar erros, sugerir melhorias ou propor traduções
2. Faz um **fork**, edita e abre um **pull request**
3. Mantém a atribuição: `Governança como Versionamento — Gustavo Alessandri`
4. Derivados devem usar a mesma licença **CC BY-SA 4.0**

## Como rodar localmente

```bash
pip install mkdocs-material mkdocs-static-i18n
mkdocs serve
```

Acessa `http://localhost:8000` no browser.

## Licença

[Creative Commons Attribution-ShareAlike 4.0 International](LICENSE.md)

Você pode copiar, adaptar e redistribuir este material para qualquer fim,
inclusive comercial, desde que dê crédito ao autor original e distribua
suas contribuições sob a mesma licença.
