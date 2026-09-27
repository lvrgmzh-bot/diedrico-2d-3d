# Diédrico 2D ⇄ 3D

Aplicación web estática para crear construcciones de geometría diédrica en 2D y 3D.

## Publicar en GitHub Pages

Sube el contenido de esta carpeta a la raíz de un repositorio de GitHub y activa **Settings → Pages → Deploy from a branch**, seleccionando la rama `main` y la carpeta `/ (root)`. La página será `https://TU_USUARIO.github.io/TU_REPOSITORIO/`.

No necesita servidor ni proceso de compilación. Three.js se carga desde cdnjs, así que la vista 3D requiere conexión a Internet.

## Progreso

Las construcciones se guardan automáticamente en `localStorage` del navegador. Al volver a abrir la página en el mismo perfil del mismo navegador, se restaura el trabajo. Cada perfil de navegador tiene su propio progreso; no se envían datos a un servidor ni se sincronizan entre dispositivos. Borrar los datos del sitio también borra el progreso.
