# CONTEXTO_BOT.md
**Actualizado:** 2026-09-08 · America/Santiago  
**Dueño del contexto:** Giacomo Lagomarsino  
**Ejecución técnica:** JACK NEUTRON

## Fuente única
Drive `00_CENTRO`: https://drive.google.com/drive/folders/1dO1ITzxaPXFQdvsBjLLuEo6z5_jLPp9D

**Regla canónica Drive ↔ GitHub:** Drive manda, GitHub obedece. GitHub es espejo; se actualiza **solo** cuando Giacomo cambia Drive y pide «sincroniza». **Nunca** editar GitHub directo.

Estructura:
- `00_Sistema` — reglas, Canva, GitHub, Vercel, enlaces globales
- `01_Santander` — Estado / Documentos / Enlaces
- `02_Vina` — Estado / Documentos / Enlaces
- `03_SII` — Estado / Documentos / Enlaces
- `04_Seguro` — Estado / Documentos / Enlaces

## Guías Canva (no cambiar)
- Empieza Aquí (computador): https://www.canva.com/d/EH2c3Y2GyGe1-g8
- Índice de enlaces: https://www.canva.com/d/ARYJJj-QLhE5EXS

## Cruce SII (regla 8-sep)
1. JACK **no** hace el cruce SII. Lo deriva al especialista del equipo (oficio DA-SII).
2. El especialista cruza **contra el sitio del SII**.
3. Solo entra lo **100% verificable**: RUT + fecha + monto coinciden.
4. Lo que no cuadre = **pendiente, aparte**. No se mezcla con lo verificable.
5. Nada se adopta ni se presenta ni se cruza con Santander hasta que Giacomo diga **OK**.
6. Cifras: ninguna adoptada. 51 descartada. 52 por verificar. Hasta OK, solo maestro.

## Cifras SII (HOLD duro)
- **Ninguna cifra SII adoptada** hasta confirmación expresa de Giacomo.
- **51 ops: descartada.**
- **52 ops: por verificar** (no usar como canónica).
- Mientras tanto: se mantiene solo lo que diga el maestro (`Contexto-Maestro` / Estado en `03_SII`) sin adoptar totales de packs intermedios.
- No inventar montos ni conteos. Si hay duda → VACÍO / por verificar / pendiente aparte.

## Reglas de operación (bots)
1. Leer primero este archivo + `REGISTRO_HISTORICO.md` + `01_Estado` del frente.
2. Cualquier cambio nuevo se anota **primero** en `00_CENTRO` (Estado del frente o Sistema).
3. Integrar mejoras **sin borrar** lo viejo: el original queda en su lugar; el cambio se registra en histórico.
4. Giacomo maneja contexto y decisiones. JACK/bots ejecutan técnica.
5. HOLD de ingreso / envío / presentación hasta «dale» / OK explícito (vía JACK).
6. Preparar siempre en paralelo · disparar solo con dale · avanzar siempre.
7. Todo en español.
8. HTML al usuario = enlace https permanente (here.now); nunca adjuntar `.html`.
9. No inventar cifras ni piezas. Si falta, marcar VACÍO.
10. Workspace local (`/workspace/...`) es copia de trabajo; la fuente de verdad compartida es `00_CENTRO`.
11. Drive manda · GitHub espejo · sync solo con «sincroniza» · nunca editar GitHub directo.
12. Cruce SII: solo especialista · sitio SII · 100% verificable · pendientes aparte · cero adopción/presentación/cruce Santander sin OK.

## Mapa rápido de frentes → carpeta
| Frente | Carpeta Drive |
|---|---|
| Mesa Santander / JPL / portabilidad / prensa | `01_Santander` |
| Fellini / 3 Norte / Maral / Depto 202 / ventas Viña | `02_Vina` |
| DA-SII CHICOS / DTE / multa | `03_SII` |
| Seguro C-4 / garantía / leaseback | `04_Seguro` |

## Archivos hermanos
- `REGISTRO_HISTORICO.md` — bitácora; no borrar entradas
- `Contexto-Maestro-Grok.md` (legado) — no borrar; preferir Estado de cada frente; cifras SII no adoptadas hasta OK Giacomo
