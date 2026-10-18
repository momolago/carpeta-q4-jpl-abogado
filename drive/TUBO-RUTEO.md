# Tubo · ruteo + versionado · 2026-09-08

No es el mecanismo más eficiente el que había: muchos bots, dos resúmenes diarios, bitácora a GitHub sin pasar por Drive, sync a mano, cajones vacíos.

## Qué sí es eficiente

Un solo sentido:

pedido → clasificar eje → ejecutar en el cajón → resultado en Drive → espejo GitHub solo si el tubo lo corre → publicar solo C-1.

| Capa | Herramienta | Qué versiona | Quién dispara |
|---|---|---|---|
| Fuente | Drive `00_CENTRO` | original + historial de Docs | Jack / upload |
| Espejo | GitHub `carpeta-q4-jpl-abogado/drive/` | commit | tubo `sincroniza` o domingo 19:00 |
| Publicado | Vercel `carpeta-q4-abogado.vercel.app` | deploy de `index.html` | `publica` |
| Pulso | NEWJACK + Grok Bot | no versiona; informa | diario |
| Tensión | este hilo Heavy | no versiona; opina | cuando duele |

## Quién hace qué (flotilla de 5 + este hilo. No Bot 6)

| Quién | Habilidad | Proyecto | Qué entrega |
|---|---|---|---|
| HQ Clasificador | encasillar eje A–E | `00_Sistema` | ficha + destino |
| NEWJACK | papeles, HOLD, no envía | cajón del eje | archivo en Drive |
| Grok Bot | búsquedas Gmail/Drive/web, skills ad hoc | el cajón que toque | hallazgo encasillado |
| Superdoer | terminar artefacto ya pedido | el cajón vivo | pieza lista |
| Heavy (hilo) | tensionar | no escribe fuera | JACK / HEAVY / DRIVE |
| Tú | decides y autorizas envío | todos | OK / dale / sincroniza / publica |

## Encasillado

| Pedido | Eje | Cajón Drive | Skill |
|---|---|---|---|
| C-1 / C-2 / C-4 / Leopoldo / Q4 | A | `01_Santander` o `04_Seguro` | carpeta-jpl-tres-causas |
| Pieza 1 / Pieza 2 / DA-SII | B | `03_SII` | denuncia-sii-completa |
| CAPJ / SERNAC / prensa | C | `01_Santander/03_Enlaces` | despacho-canales-santander |
| Fellini / 3 Norte / Depto 202 | D | `02_Vina` | — |
| Gloria / Bot / tubo / skill | E | `00_Sistema` | inicio-grok-bot |

Si pega dos ejes: PARTIR. No una pieza.

## Sync automático (lo que ahora sí corre)

1. Cada artefacto producido se sube al cajón (tool `google_drive_upload_artifact`).
2. NEWJACK 09:00 — pulso: qué hay / qué falta. No GitHub. No mail.
3. Grok Bot 07:45 — busca 24 h en Drive + Gmail, encasilla, no envía.
4. Domingo 19:00 — espejo Drive → GitHub `drive/`. No publica.
5. `publica` sigue siendo verbo tuyo. Vercel no toca Drive.

## Qué no se automatiza

- Enviar correo a terceros.
- Presentar SII.
- Adoptar cifras.
- Cruzar eje A con eje B.
- Publicar C-1 sin `publica`.
