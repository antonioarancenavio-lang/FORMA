# FORMA — Plataforma para gimnasios (demo)

Demo interactiva de una plataforma web para gimnasios: sitio público con landing, horario de clases reservable, y una vista de panel para el dueño (alta de miembros, personalización de marca/colores, etc.).

Todo el proyecto es un único archivo estático (`index.html`) con HTML, CSS y JavaScript embebidos — no requiere build ni dependencias.

## Ver la demo en local

Abre `index.html` directamente en el navegador, o sirve la carpeta con cualquier servidor estático:

```bash
python3 -m http.server 8000
```

y visita `http://localhost:8000`.

## Publicar con GitHub Pages

1. Sube este repositorio a GitHub.
2. Ve a **Settings → Pages**.
3. En "Source" selecciona la rama `main` (o `master`) y la carpeta `/ (root)`.
4. Guarda. En un par de minutos la demo estará publicada en `https://<tu-usuario>.github.io/<nombre-del-repo>/`.

## Estructura

```
.
├── index.html   # sitio completo (HTML + CSS + JS)
├── README.md
└── .gitignore
```
