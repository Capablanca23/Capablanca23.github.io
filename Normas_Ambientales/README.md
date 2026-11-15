# Normas Ambientales Perú – Agua y Aire (PWA)

## Contenido
- `index.html`: aplicación original adaptada para instalación.
- `manifest.webmanifest`: identidad y configuración PWA.
- `sw.js`: caché del núcleo de la aplicación y caché en tiempo de ejecución de Chart.js.
- `icons/`: iconos de instalación.

## Publicación
La PWA requiere HTTPS (GitHub Pages sirve HTTPS automáticamente) o `localhost`.
1. Sube el contenido de esta carpeta a la raíz de un repositorio o a una carpeta publicada.
2. Activa GitHub Pages desde Settings → Pages, si corresponde.
3. Abre la URL publicada en Chrome/Edge/Android o Safari en iOS.
4. Usa «Instalar aplicación» cuando aparezca, o el menú del navegador → «Añadir a pantalla de inicio».

## Uso sin conexión
El HTML, los datos normativos y las funciones principales se guardan en caché después de la primera visita en línea. Chart.js se almacena tras cargarse correctamente una vez; si nunca se cargó antes de quedar sin conexión, el gráfico de evaluación no estará disponible, pero las tablas y demás funciones locales seguirán funcionando.

Nota: la PWA conserva el contenido y los datos del HTML de origen; no constituye una validación jurídica de la vigencia de las normas.
