# Constructor de moléculas — PWA

Aplicación web progresiva lista para publicar en GitHub Pages.

## Publicación en GitHub Pages

1. Descomprime este paquete.
2. Sube **todos** los archivos y la carpeta `icons` a la raíz de un repositorio de GitHub.
3. En GitHub, entra en **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/(root)`, y guarda.
6. Espera a que GitHub Pages publique el sitio. Debe abrirse mediante `https://`.

## Instalación en Android

1. Abre la dirección de GitHub Pages con Chrome.
2. Pulsa **Instalar aplicación** dentro del programa.
3. Confirma la instalación cuando Chrome muestre el aviso.

El botón está incorporado en `index.html`. Si el navegador aún no ofrece el evento de instalación, el botón muestra instrucciones para instalar desde el menú del navegador.

## Instalación en iPhone/iPad

Abre la página con Safari → **Compartir** → **Añadir a pantalla de inicio**.

## Funcionamiento sin conexión

El Service Worker (`sw.js`) guarda la aplicación y sus recursos principales para permitir su apertura posterior sin conexión. La primera carga requiere Internet.

## Archivos

- `index.html`: aplicación original con el botón de instalación y registro del Service Worker.
- `manifest.webmanifest`: nombre, iconos y configuración PWA.
- `sw.js`: caché y funcionamiento sin conexión.
- `icons/`: iconos de la aplicación.
