# CI/CD · carpeta-q4-jpl-abogado

Instaurado: 8 de septiembre de 2026.

## Tubo oficial
GitHub (`main`) → Vercel publica.
Sitio vivo: https://carpeta-q4-abogado.vercel.app

Cada cambio de **código de la página** en `main` se despliega solo. No se sube a mano.

## Ramas
- `main` — sitio vivo. Solo lo ya visto y autorizado.
- `prueba` — ensayo. Aquí se prueba sin tocar lo que ve el público.

Regla: nada pasa a `main` hasta que Giacomo diga «dale».

Si Vercel está conectado al repo, `prueba` arma una página de preview (otra URL). No reemplaza el sitio vivo.

## Qué no entra
- Drive `00_CENTRO` no se publica. Drive manda el caso, no la web.
- Sincronizar reglas (`CONTEXTO_BOT`, `REGISTRO`) no es publicar un caso ni cifras.
- Plugin Jack–Heavy: **no publicado**.
- Cifras SII: ninguna adoptada. 51 descartada. 52 por verificar. No se presentan.

## Publicar vs sincronizar vs probar
- «sincroniza» = copiar Drive → GitHub (texto).
- Probar = trabajar en `prueba`.
- Desplegar vivo = pasar a `main` + Vercel.
- Presentar un caso o una cifra = solo con «dale» / OK de Giacomo.

## Roles
Jack ejecuta el tubo. Heavy tensiona. Giacomo decide. Drive registra.
