# grupomm.cl

Sitio de Grupo Matchmaking (Multi Family Office). HTML estático.

- Archivos del sitio: `public/`
- Publicación: Cloudflare Workers (cuenta de Grupo MM). Cada push a `main` se publica automáticamente mediante Workers Builds.
- Formulario de contacto: formsubmit.co → contacto@grupomm.cl
- El correo (@grupomm.cl) está en Google Workspace y no depende de este sitio. El DNS se administra en Cloudflare.

## Probar en local

```
npx wrangler dev
```
