# Cane Grosso Problema Piccolo

Gioco platformer 2D realizzato con [GDevelop 5](https://gdevelop.io/) (v5.6.0).

## Contenuto della repository

| Percorso | Descrizione |
| --- | --- |
| `Cane Grosso Problema Piccolo.json` | Progetto GDevelop — apribile direttamente nell'editor |
| `assets/` | Risorse del gioco: sprite, font, effetti sonori |
| `html export/` | Export HTML5 già pronto, giocabile nel browser |

## Come aprire il progetto

1. Installa [GDevelop 5](https://gdevelop.io/download).
2. Apri `Cane Grosso Problema Piccolo.json` da *File → Apri un progetto*.

## Come giocare all'export

L'export in `html export/` va servito tramite un web server (aprendo `index.html` direttamente
da disco il browser blocca il caricamento delle risorse). Ad esempio:

```bash
cd "html export" && python -m http.server 8000
```

poi apri <http://localhost:8000>.

## Licenza

Il motore di runtime incluso nell'export è distribuito da GDevelop secondo i termini indicati in
`html export/LICENSE.GDevelop.txt`.
