<h1 align="center">🔡 Wordle 🎲</h1>

<p align="center">
  Proyecto del Curso de Programación Reactiva con RxJS
</p>

## Guía de instalación del proyecto

1. Instala las dependencias:

```console
npm i rxjs webpack webpack-dev-server
npm i -D webpack-cli
```

2. Genera un `webpack.config.js` dentro del proyecto:

```javascript
const path = require("path");

module.exports = {
  entry: "./src/index.js",
  output: {
    filename: "bundle.js",
    path: path.resolve(__dirname, "public"),
  },
  mode: "development",
};
```

3. Genera las siguientes carpetas y archivos como se muestra en esta estructura:

```console
public/
    index.html
    style.css
src/
    index.js
webpack.config.js
```

4. Añade la fuente JavaScript al `index.html`:

```html
<script src="./bundle.js"></script>
```

Y los estilos `.css`:

```html
<link rel="stylesheet" href="./style.css" />
```

## Ramas disponibles del curso

| **Clase**                       | **Rama**                      | **Cambio realizado**                                 |
| ------------------------------- | ----------------------------- | ---------------------------------------------------- |
| fromEvent en iWordle       | `9-fromEvent-iWordle`    | Implementamos observables con fromEvent              |
| Subject en iWordle         | `11-Subject-iWordle`     | Implementamos Subject en fromEvent                   |
| Finalizando iWordle        | `14-Finalizando-iWordle` | Realizamos algunos detalles en iWordle          |
| map y filter en iWordle    | `17-map-filter-iWordle`  | Reemplazamos código vanilla con map y filter         |
| takeUntil en iWordle       | `23-takeUntil-iWordle`   | Empleamos takeUntil                                  |
| Opción de reinicio iWordle | `28-reinicio-iWordle`    | Habilitamos la opción para reiniciar en iWordle |
