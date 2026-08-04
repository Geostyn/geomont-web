# geomont-web

Sitio público de **GeoMont** — por ahora solo la política de privacidad, obligatoria para publicar en Google Play.

Alojado gratis en GitHub Pages.

## URLs (las que hay que pegar en Play Console)

| Idioma de la ficha | URL de la política de privacidad |
|---|---|
| English (default) | https://geostyn.github.io/geomont-web/ |
| Español | https://geostyn.github.io/geomont-web/es.html |
| Nederlands | https://geostyn.github.io/geomont-web/nl.html |
| Français | https://geostyn.github.io/geomont-web/fr.html |

## ⚠️ ANTES de enviar la app a revisión

El email de contacto es un **marcador de posición**: `geomont.app@outlook.com`

Si no vas a usar exactamente esa dirección, créala o cámbiala en los **4 archivos HTML**
(aparece 2 veces en cada uno: en el apartado "responsable" y en el de "contacto").

Debe ser una dirección que **funcione de verdad** — Google la puede comprobar y los usuarios
la usarán para reclamaciones de GDPR.

## Por qué este repo está separado de la app

El proyecto Flutter (`Desktop\montaje-app`) contiene `android/app/geomont-release.jks` y
`android/key.properties` **con las contraseñas de firma**. Ese material no puede acabar nunca
en un repositorio público. Por eso el sitio web vive aquí, en un repo aparte que solo tiene HTML.

## Cambiar algo

Edita el HTML, `git commit` y `git push`. GitHub Pages redespliega solo en ~1 minuto.
