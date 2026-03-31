[🇧🇷 Português](README.md) · [🇬🇧 English](README.en.md) · [🇪🇸 Español](README.es.md)

---

# GitGov — Gobernanza como Versionamiento

[![CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

**335 años de pensamiento. 29 autores. 21 pasos.**

Sitio: [https://codeberg.org/openarchy](https://codeberg.org/openarchy)   
Espejo: [https://github.com/openarchy/gitgov](https://github.com/openarchy/gitgov)

---

## Qué es esto

Una serie de 21 artículos que aplica los conceptos de Git — el sistema de
control de versiones usado por programadores en todo el mundo — como modelo
de gobernanza descentralizada para cualquier grupo humano, con o sin tecnología.

La tesis cabe en una frase: **gobernar es versionar. Errar es registrar.
Corregir es integrar. La autoridad es revisión por pares.**

## Estructura del repositorio

```
articles/
  pt-BR/          # Português — Artigos Originais.  OBS: já finalizados.
  en-US/          # English — translation in progress.
  es-419/         # Castellano / Español — traducción en curso.
mkdocs.yml        # Configuración del sitio
.github/          # GitHub Actions (despliegue automático)
.forgejo/         # Forgejo Actions (despliegue en Codeberg)
```

## Cómo contribuir

1. Abre un **issue** para reportar errores, sugerir mejoras o proponer traducciones
2. Haz un **fork**, edita y abre un **pull request**
3. Mantén la atribución: `Gobernanza como Versionamiento — Gustavo Alessandri`
4. Los derivados deben usar la misma licencia **CC BY-SA 4.0**

## Cómo ejecutar localmente

```bash
pip install mkdocs-material mkdocs-static-i18n
mkdocs serve
```

Abre `http://localhost:8000` en tu navegador.

## Licencia

[Creative Commons Atribución-CompartirIgual 4.0 Internacional](LICENSE.md)

Eres libre de copiar, adaptar y redistribuir este material para cualquier
propósito, incluso comercialmente, siempre que des el crédito apropiado al
autor original y distribuyas tus contribuciones bajo la misma licencia.
