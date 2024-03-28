# Bootstrap + Sass

@codewithleader

## Personaliza los colores de bootstrap con sass

Requisitos:

1. Instalar las extensiones `Live Sass Compiler` y `Live Server` en VSCode.
2. Agregar en `settings.json` las configuraciones para `Live Sass Compiler`:

```json
"liveSassCompile.settings.autoprefix": ["> 1%", "last 2 versions"],
  "liveSassCompile.settings.excludeList": [
    "/**/node_modules/**",
    "/.vscode/**",
    "/libs/**"
  ],
  "liveSassCompile.settings.formats": [
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "/css"
    }
  ],
```

3. Ejectutar desde la barra de status el boton `👁 Watch Sass`.
4. Modificar el archivo `/scss/styles.scss` con los nuevos colores deseados.
5. Se creará el nuevo archivo compilado de bootstrap en la carpeta `/css/styles.css`.
6. Ejecutar Live server en el `index.html` desde la barra de status `Go to live`.