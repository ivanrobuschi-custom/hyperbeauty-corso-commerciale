# Corso Commerciale HyperBeauty

Portale di formazione commerciale per concessionari e installatori HyperBeauty — Custom S.p.A.

Costruito con [MkDocs Material](https://squidfunk.github.io/mkdocs-material/), stesso stack del corso Edge N.

## Setup

```bash
pip install mkdocs-material
```

## Sviluppo locale

```bash
mkdocs serve
```

## Deploy su GitHub Pages

```bash
mkdocs gh-deploy
```

## Struttura

```
docs/
├── index.md              # Home — introduzione e programma
├── mercato/index.md      # Modulo 1 — Contesto di mercato
├── prodotto/index.md     # Modulo 2 — Il prodotto HyperBeauty
├── piani/index.md        # Modulo 3 — I piani di abbonamento
├── cliente/index.md      # Modulo 4 — Il cliente tipo
├── argomentario/index.md # Modulo 5 — Argomentario di vendita
├── risorse/index.md      # Materiali e risorse
└── assets/
    ├── icons/logo.png
    └── resources/brochure-hyperbeauty.pdf
```

## Note

- Aggiungere il logo HyperBeauty in `docs/assets/icons/logo.png`
- Aggiungere la brochure PDF in `docs/assets/resources/`
- Aggiornare `site_url` in `mkdocs.yml` con il tuo username GitHub
