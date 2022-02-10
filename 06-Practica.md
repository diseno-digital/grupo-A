---
tema: Setup de página web
fecha: 11 Febrero 2022
sesion: 6
---

# Setup inicial de página web

Vamos a crear de manera individual una página web ligada a nuestro perfil de Github para entender el proceso de cómo configurar una página hospedada en Github Pages con un formato de **autor** predeterminado en lugar del formato de **user agent default**.

Pasos:

1. Vamos a [crear un repositorio](https://repo.new).
2. Vamos a poner de nombre al repositorio nuestro nombre de usuario. ![Nombre de repositorio](https://res.cloudinary.com/pmichventura/image/upload/v1644504387/CENTRO/nombre.png) y dar clic en el botón verde que dice `Crear repositorio`.
3. Vamos a dar clic en crear un nuevo archivo para crear el documento `index.html` ![Nuevo documento](https://res.cloudinary.com/pmichventura/image/upload/v1644505045/CENTRO/nuevo.png)
4. Vamos a nombrar nuestro documento y guardar nuestros cambios con el mensaje default ![index](https://res.cloudinary.com/pmichventura/image/upload/v1644505506/CENTRO/index.jpg)
5. Vamos a abrir nuestro proyecto en la version web de VSCode ![VSCode web](https://res.cloudinary.com/pmichventura/image/upload/v1644506107/CENTRO/vscodedev.png)
6. Vamos a abrir los ajustes de de configuración con `cmd+,` y abrir los ajustes en formato json ![Ajutstes](https://res.cloudinary.com/pmichventura/image/upload/v1644506597/CENTRO/settings.png)
7. Vamos a pegar los siguientes ajustes:
```json
{
  "editor.lightbulb.enabled": true,
  "workbench.editor.enablePreview": true,
  "workbench.editor.enablePreviewFromQuickOpen": false,
  "workbench.settings.editor": "json",
  "editor.parameterHints.enabled": true,
  "editor.wordWrap": "on",
  "editor.cursorSmoothCaretAnimation": true,
  "workbench.sideBar.location": "right",
  "window.openFilesInNewWindow": "off",
  "editor.snippetSuggestions": "top",
  "editor.semanticTokenColorCustomizations": {
    "enabled": true
  },
  "editor.codeLens": true,
  "editor.detectIndentation": true,
  "editor.semanticHighlighting.enabled": true,
  "editor.tabSize": 2,
  "editor.inlineSuggest.enabled": true,
  "editor.scrollBeyondLastLine": true,
  "editor.formatOnPaste": true,
  "editor.cursorBlinking": "solid",
  "editor.quickSuggestionsDelay": 30,
  "editor.useTabStops": true,
  "problems.decorations.enabled": true,
  "diffEditor.renderIndicators": false,
  "explorer.confirmDragAndDrop": false,
  "workbench.tips.enabled": true,
  "files.insertFinalNewline": true,
  "editor.renderLineHighlightOnlyWhenFocus": false,
  "editor.find.seedSearchStringFromSelection": "never",
  "explorer.confirmDelete": false,
  "editor.lineHeight": 30,
  "editor.glyphMargin": false,
  "workbench.enableExperiments": true,
  "editor.formatOnSave": true,
  "editor.cursorStyle": "line",
  "workbench.fontAliasing": "antialiased",
  "html.format.enable": true,
  "diffEditor.ignoreTrimWhitespace": false,
  "editor.letterSpacing": 0.5,
  "workbench.editor.tabSizing": "shrink",
  "editor.smoothScrolling": true,
  "editor.accessibilitySupport": "off",
  "workbench.editor.highlightModifiedTabs": true,
  "html.format.preserveNewLines": true,
  "editor.suggestFontSize": 20,
  "editor.minimap.enabled": false,
  "editor.overviewRulerBorder": false,
  "editor.tabCompletion": "on",
  "editor.selectionHighlight": true,
  "editor.suggestLineHeight": 30,
  "workbench.editor.untitled.hint": "hidden",
  "editor.fontSize": 17,
  "files.trimTrailingWhitespace": true,
  "files.trimFinalNewlines": true,
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "workbench.startupEditor": "none",
  "diffEditor.renderSideBySide": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.suggestSelection": "first",
  "editor.lineNumbers": "on"
}
```
8. Vamos a abrir nuestro documento index.html y crear la base del documento como lo hicimos la clase pasada.
9. Vamos a cambiar el título del documento y vamos a poner `Trabajo individual Minombre`.
10. Vamos a tomar un screenshot del diseño para poderlo analizar desde nuestro editor de código.
11. Vamos a buscar el tab que dice `Outline` para visualizar la estructura de nuestro documento ![Outline](https://res.cloudinary.com/pmichventura/image/upload/v1644507215/CENTRO/outline.png)
12. Vamos a copiar lo siguiente y pegarlo dentro de las etiquetas `<body></body>`
```html
<!--
  TODO:
  1. Crear un archivo style.css
  2. Crear una etiqueta link:css dentro dentro de la información meta del documento.
  3. Dar clic en https://tinyurl.com/mrx9rcdz para copiar los reset del gist y pegarlo en el archivo style.css.
  4. Crear el markup apartir de la imagen/screenshot (ayudarnos con la tabla periódica ubicada al final del documento en enlaces útiles).
  5. Analizar las propiedades de formato que vemos en nuestra imagen y utilizar nuestro documento style.css para visualizar nuestros cambios (Tip: Utilizar Visbug para analizar cualquier página web y ver que propiedades podemos aplicarle a nuestro diseño).
-->
```
13. Vamos a instalar la extensión Live Share para crear un enlace de colaboración y pegarlo en el chat de Zoom. ![Live Share](https://res.cloudinary.com/pmichventura/image/upload/v1644506258/CENTRO/liveshare.png)

## Publicación de nuestro avance

Para publicar lo que trabajamos durante la sesión y ver nuestros cambios en un URL público vamos a realizar lo siguiente:

1. Vamos a asegurarnos de guardar nuestros cambios en la versión web de VSCode con un mensaje de commit `Setup inicial web` y vamos a regresar al repositorio inicial.
2. Vamos a dar clic en `Settings` ![Settings](https://res.cloudinary.com/pmichventura/image/upload/v1644508465/CENTRO/settings_btn.png) .
3. Vamos a dar clic en `Pages` ![Pages](https://res.cloudinary.com/pmichventura/image/upload/v1644508465/CENTRO/pages.png).
4. Vamos a activar nuestra página seleccionando la rama/branch `main` que es donde esta nuestro documento index y vamos a guardar nuestros cambios. ![Source](https://res.cloudinary.com/pmichventura/image/upload/v1644508465/CENTRO/source.png).

<br>

## Aplicándolo a nuestro proyecto

Ejercicio:

1. Vamos a compartir y comparar lo que realizamos individualmente con nuestro equipo para elegir la solución que nos sea de mayor utilidad.
2. Vamos a guardar nuestros cambios, editando el documento que nos fue asignado como equipo la clase anterior.

<br>

**Enlaces útiles:**

* [Documentación de HTML](https://mdn.io/html/es)
* [Tabla periódica de elementos HTML](https://madebymike.github.io/html5-periodic-table/)
* [Browser Default Styles](https://browserdefaultstyles.com)
* [Vscode web](https://vscode.dev)
* [Github Pages](https://pages.github.com)
* [Cloudinary](https://cloudinary.com)
* [VisBug](https://chrome.google.com/webstore/detail/visbug/cdockenadnadldjbbgcallicgledbeoc)
