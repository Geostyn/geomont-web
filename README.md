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

## Email de contacto

`geostyn.app@outlook.com` — aparece 2 veces en cada uno de los 4 archivos HTML
(apartado "responsable" y apartado "contacto").

⚠️ Tiene que ser una dirección que **funcione de verdad**: Google la puede comprobar y los
usuarios la usarán para reclamaciones de GDPR. Si se cambia, cambiarla en los 4 HTML
y también en la ficha de Play Console.

## Por qué este repo está separado de la app

El proyecto Flutter (`Desktop\montaje-app`) contiene `android/app/geomont-release.jks` y
`android/key.properties` **con las contraseñas de firma**. Ese material no puede acabar nunca
en un repositorio público. Por eso el sitio web vive aquí, en un repo aparte que solo tiene HTML.

## Cambiar algo

Edita el HTML, `git commit` y `git push`. GitHub Pages redespliega solo en ~1 minuto.
