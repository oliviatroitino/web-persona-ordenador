# web-persona-ordenador

Proyecto final de la asignatura, web de técnicas de IPO.

## Plan a priori
```
src/
|__ html/
    |__ techniques/
        |__ card-sorting.html
        |__ affinity-diagram.html
        |__ human-computer-io-devices.html
    |__ concepts/
        |__ usability.html
    |__ index.html
|__ scss/
    |__ main.scss
    |__ abstracts/
        |__ _mixins.scss
        |__ _variables.scss
    |__ base/
        |__ _base.scss
        |__ _reset.scss
        |__ _typography.scss
    |__ layout/
        |__ _footer.scss
        |__ _header.scss
        |__ _navbar.scss
    |__ pages/
        |__ _home.scss
        |__ _techniques.scss
        |__ _concepts.scss
```

### Teoría Web
#### SCSS
- `main.scss`: Raiz donde se juntan todos los ficheros de estilo antes de compilar a css.
- `abstracts/_mixins.scss`: Lógica de estilo reutilizable (mixins, funciones)
- `abstracts/_variables.scss`: Variables reutilizables (color, espacios, breakpoints, etc.)
- `base/_base.scss`: Elementos "core" como `body`, `a`, `img`, etc.
- `base/_reset.scss`: Reglas para reducir inconsistencias de browsers.
- `base/_typography.scss`: Reglas globales de texto.
- `layout/_footer.scss`, `layout/_header.scss`, `layout/_navbar.scss`: Estilo estructural de footer, header y barra de navegación.
- `pages/_home.scss`, `pages/_techniques.scss`, `pages/_concepts.scss`: Estilos únicos de las páginas.
