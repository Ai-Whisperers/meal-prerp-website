# Sitio Web — plan operativo

> **Última actualización:** Mayo 2026  
> **Índice carpeta:** [`00_README.md`](00_README.md)  
> **Índice proyecto:** [`docs/indice/INDEX.md`](../docs/indice/INDEX.md)

---

## Repositorio y deploy

| Item | Valor |
|------|--------|
| **Repo canónico** | [Ai-Whisperers/meal-prerp-website](https://github.com/Ai-Whisperers/meal-prerp-website) |
| **Código sitio** | Raíz del repo — `web/app/`, `npm run dev` → `http://localhost:3000` |
| **Deploy** | [prep.paragu-ai.com](https://prep.paragu-ai.com) · Docker `deploy/docker-compose.yml` puerto 3010 |
| **Repo archivado** | `prep-website` (fusionado mayo 2026) |
| **Repo hermano** | [de-abasto-a-casa](https://github.com/Ai-Whisperers/de-abasto-a-casa) — sitio grocery extendido |

---

## Estrategia de producto en el sitio

**Una URL, dos marcas:**

| Marca | Rol en web |
|-------|------------|
| **Fuego Lento** | Hero + producto estrella (freezer / Tier 2) |
| **De Abasto a Casa** | Mise + compras (Tier 1–2) |

**Checkout:** WhatsApp únicamente (Fase 1–2). Ver funnel en [`04_Layout_Plan_UX_Marketing.md`](04_Layout_Plan_UX_Marketing.md).

**Precios públicos:** [`negocio/precios/tiers-2026.md`](../negocio/precios/tiers-2026.md)

---

## Estado código vs documentación

| | Documentación (objetivo) | Código `web/app/page.tsx` (hoy) |
|--|-------------------------|----------------------------|
| Hero | Fuego Lento | Mise “heladera organizada” |
| Secciones | 17 bloques — ver layout plan | ~8 bloques mise-focused |
| Fuentes | Fraunces + Inter | Playfair + Lato |
| Menú semanal | Bloque `#fuego-lento` | Pendiente |

**Regla:** actualizar [`01_Copy_ES_Spanish.md`](01_Copy_ES_Spanish.md) primero, luego código.

---

## Secciones — MVP ampliado (objetivo)

Plan detallado: [`04_Layout_Plan_UX_Marketing.md`](04_Layout_Plan_UX_Marketing.md)

| # | Sección | Copy source |
|---|---------|-------------|
| 1 | Header + nav | `01_Copy` |
| 2 | Hero Fuego Lento | `01_Copy` § Hero |
| 3 | Problema (story) | `04_Story_Sales_Narrative` |
| 4 | Product picker (3 paths) | `01_Copy` § Productos |
| 5 | Fuego Lento (menú, packs, reheat) | `01_Copy` § Fuego Lento |
| 6 | Cómo funciona | `01_Copy` |
| 7 | Servicios / precios (tabs 3 tiers) | `01_Copy` + `09_Tiers_Pricing` |
| 8 | Calculadora | `01_Copy` + lógica existente en `web/app/` |
| 9 | Comparativa | `01_Copy` |
| 10 | Calidad / sourcing | `01_Copy` |
| 11 | Galería | `03_Image_Curation` |
| 12 | Equipo (Edu) | `01_Copy` § Equipo |
| 13 | Testimonios | `01_Copy` |
| 14 | FAQ | `01_Copy` |
| 15 | Zona y entrega | `01_Copy` § Contacto |
| 16 | CTA + WhatsApp float | `01_Copy` |
| 17 | Footer | `01_Copy` |

### MVP original (Fase 1 — parcialmente en código)

Las 10 secciones del MVP inicial siguen válidas; se **reordenan** y se añade bloque Fuego Lento + picker según layout plan.

---

## Calculadora de ahorro

Inputs (mensuales, Gs.): súper + carnicería + feria · delivery + afuera · tirada + impulsos · gas/luz · personas · valor hora · horas/mes · tier a comparar.

Outputs en vivo: plata real · valor tiempo · total hoy · nuestro servicio · ahorro · horas recuperadas.

- Ahorro &gt; 0 → CTA WhatsApp con números  
- Ahorro ≤ 0 → “Hoy ya sos eficiente” (honesto)

Plantilla mensajes: [`marketing/ventas/mensaje-valor-cliente-template.md`](../marketing/ventas/mensaje-valor-cliente-template.md)

---

## Branding

| Item | Valor |
|------|--------|
| De Abasto tagline | Mercado, prep y comidas listas. Puerta a puerta, en San Lorenzo. |
| Fuego Lento tagline | Lo que tarda horas en olla, vos lo comés en quince minutos. |
| Paleta | Verde `#3a6b4a` + terracota `#c2663a` / brasa `#C4622D` + crema `#f6f1e7` |
| Tipografías | Fraunces + Inter |

Detalle: [`02_Brand_Guidelines.md`](02_Brand_Guidelines.md)

---

## Pendientes operativos

1. Número WhatsApp real (placeholder en copy y código)  
2. Autorización testimonios Fran, Junior, Emilio & Lucía  
3. Fotos galería reales — [`03_Image_Curation.md`](03_Image_Curation.md)  
4. Bio + foto **Eduardo Cano Galeano** en § Equipo  
5. Logo SVG final  
6. Email contacto real  
7. Cobertura barrios explícita  
8. Implementar layout plan en `web/app/page.tsx`  
9. INAN — marcar Nivel 3 activo solo cuando corresponda  

---

## Verificación local

```bash
npm install
npm run lint
npm run build
npm run dev    # http://localhost:3000
```

Sitio grocery extendido: clonar `de-abasto-a-casa` por separado.

---

## Fase 2–3 (no en scope MVP)

- `/menu` semanal JSON  
- Subrutas `/fuego-lento`, `/prep`  
- Formulario email (solo si se usa)  
- Panel cliente / tracking  
- Calendario estacional  

Changelog decisiones: [`05_Planning_Changelog_2026-05.md`](05_Planning_Changelog_2026-05.md)
