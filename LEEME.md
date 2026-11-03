# Notas: paquete PWA

Contenido: `index.html` (la app), `manifest.json`, `sw.js` (modo sin conexión) y la carpeta `icons/`.

## Publicarlo (elige una opción)
- **Netlify Drop:** entra en https://app.netlify.com/drop y arrastra esta carpeta (descomprimida). Te da una dirección https al momento.
- **GitHub Pages:** crea un repositorio, sube estos archivos a la raíz y activa Settings > Pages.

La app necesita https (o localhost) para que funcione el service worker.

## Instalarla en el móvil
- **Android (Chrome):** abre la dirección > menú de tres puntos > "Instalar aplicación".
- **iPhone (Safari):** Compartir > "Añadir a pantalla de inicio".
- **Ordenador (Chrome/Edge):** icono de instalar en la barra de direcciones.

## Convertirla en APK
Con la web ya publicada, entra en https://www.pwabuilder.com, pega la dirección y elige "Package for stores" > Android. Descarga el APK/AAB firmado.

## Notas importantes
- Las notas se guardan en el navegador de cada dispositivo y dirección. Para pasar las que ya tienes de otra versión, usa "Exportar copia" allí e "Importar copia" aquí.
- Al cambiar archivos, sube la versión de `CACHE` en `sw.js` (por ejemplo `notas-v2`).
