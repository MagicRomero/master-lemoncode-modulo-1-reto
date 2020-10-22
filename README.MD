# Master Front End IX - Laboratorio - Módulo 1 - Reto opcional

### Antes de empezar

Se ha importado `normalize.css` para renderizar los elementos html de una manera mas estándar y consistente entre navegadores.

Se ha usado [PostCSS](https://postcss.org/) para generar las reglas CSS acordes a la mayoría de navegadores y corregir inconsistencias para conseguir que el proyecto funcione sin comportamientos inesperados a nivel de estilos. También nos permite usar las nuevas funcionalidades de versiones css posteriores.

El `CSS` final ya ha sido generado para el proyecto pero si se quisiera volver a recompilar se debe tener instalado `node + npm` en su maquina y ejecutar en la raíz del proyecto:

```sh
npm install
```

Esto instalara las dependencias de desarrollo que nos permitirá usar `postcss` correctamente, el proyecto ya contiene los scripts necesarios:

```json
{
  "scripts": {
    "postcss-build": "postcss styles/index.css --use cssnano postcss-import postcss-cssnext --o public/css/main.css",
    "postcss-watch": "postcss styles/index.css --use cssnano postcss-import postcss-cssnext --o public/css/main.css -w"
  }
}
```

# [Ir a la demo](https://magicromero.github.io/master-lemoncode-modulo-1-reto/index.html)
