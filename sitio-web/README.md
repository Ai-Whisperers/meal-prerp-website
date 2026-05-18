# Documentación del sitio web

Fuente de verdad para copy, layout y UX. El código está en la raíz del repo (`app/`).

**Deploy:** [prep.paragu-ai.com](https://prep.paragu-ai.com)

---

## Archivos

| Archivo | Propósito |
|---------|-----------|
| [`plan-sitio.md`](plan-sitio.md) | MVP vs fases, checklist de secciones |
| [`copy-espanol.md`](copy-espanol.md) | **Copy master** — textos en español |
| [`guia-marca.md`](guia-marca.md) | Colores, fuentes, tono |
| [`curacion-imagenes.md`](curacion-imagenes.md) | Galería desde imágenes de compras |
| [`layout-ux-marketing.md`](layout-ux-marketing.md) | Orden de secciones, funnel, métricas |
| [`changelog-2026-05.md`](changelog-2026-05.md) | Decisiones mayo 2026 |

---

## Docs relacionados

- Precios en sitio: `negocio/precios/tiers-2026.md`
- Narrativa de venta: `marketing/04_Story_Sales_Narrative.md`
- Índice del proyecto: `docs/INDEX.md`

---

## Flujo: cambiar copy en producción

1. Editar `copy-espanol.md`
2. Actualizar `plan-sitio.md` si cambian secciones
3. Implementar en `app/page.tsx` (ver `layout-ux-marketing.md`)
4. `npm run build` && `npm run lint`
5. Deploy Docker / Swarm
