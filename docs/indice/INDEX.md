# Índice del proyecto — meal prep / De Abasto a Casa

**Repo:** [Ai-Whisperers/meal-prerp-website](https://github.com/Ai-Whisperers/meal-prerp-website)  
**Sitio en vivo:** [prep.paragu-ai.com](https://prep.paragu-ai.com) — código en [`web/`](../web/)  
**Última reorganización:** Mayo 2026

---

## Estructura del repositorio

| Carpeta | Qué contiene |
|---------|----------------|
| [`web/`](../web/) | Next.js (`app/`, `package.json`) |
| [`deploy/`](../deploy/) | Docker Compose / Traefik |
| [`docs/`](../docs/) | Índice, agentes IA, README proyecto |
| [`negocio/`](../negocio/) | Plan maestro, programa operador, precios, contrato |
| [`operaciones/`](../operaciones/) | Cocina, compras, logística, ciclo semanal |
| [`marketing/`](../marketing/) | Ventas, campaña HelloFresh Local, posicionamiento |
| [`sitio-web/`](../sitio-web/) | Copy, marca, UX — fuente para `web/app/` |
| [`clientes/`](../clientes/) | Perfiles y planes de clientes activos |
| [`crm/`](../crm/) | Onboarding y bienvenida |
| [`mercado/`](../mercado/) | Inteligencia de mercado |
| [`operador-edu/`](../operador-edu/) | Manuales hiring + carpeta Edu (activo/archivo) |
| [`_archivo/`](../_archivo/) | Docs históricos — no usar para decidir |

---

## Lectura recomendada (orden)

### Operación y producto

| Tema | Archivo |
|------|---------|
| Ciclo semanal | [`operaciones/ciclo/ciclo-semanal.md`](../operaciones/ciclo/ciclo-semanal.md) |
| Propuesta de valor | [`negocio/programa-operador/propuesta/propuesta-de-valor.md`](../negocio/programa-operador/propuesta/propuesta-de-valor.md) |
| Catálogo y rotación | [`negocio/programa-operador/catalogo/catalogo-menu-rotacion.md`](../negocio/programa-operador/catalogo/catalogo-menu-rotacion.md) |
| Economía unitaria | [`negocio/programa-operador/economia/economia-unitaria.md`](../negocio/programa-operador/economia/economia-unitaria.md) |

### Precios (2026)

| Tema | Archivo |
|------|---------|
| Tres tiers comerciales | [`negocio/precios/tiers-2026.md`](../negocio/precios/tiers-2026.md) |
| Precios por plato (catálogo) | [`negocio/programa-operador/precios/estructura-precios.md`](../negocio/programa-operador/precios/estructura-precios.md) |
| Contrato de servicio | [`negocio/plan/contrato-servicios-pago.md`](../negocio/plan/contrato-servicios-pago.md) |
| Comparativa valor cliente | [`negocio/precios/comparativa-valor-cliente.md`](../negocio/precios/comparativa-valor-cliente.md) |

### Logística y empaque

| Tema | Archivo |
|------|---------|
| Especificaciones empaque | [`operaciones/logistica-empaque/empaque/especificaciones-empaque.md`](../operaciones/logistica-empaque/empaque/especificaciones-empaque.md) |
| Cadena de frío | [`operaciones/logistica-empaque/frio/protocolo-cadena-frio.md`](../operaciones/logistica-empaque/frio/protocolo-cadena-frio.md) |
| Entrega y regeneración | [`operaciones/logistica-empaque/entrega/metodos-entrega-regeneracion.md`](../operaciones/logistica-empaque/entrega/metodos-entrega-regeneracion.md) |

### Marketing y ventas

| Tema | Archivo |
|------|---------|
| Narrativa de venta | [`marketing/ventas/story-sales-narrative.md`](../marketing/ventas/story-sales-narrative.md) |
| Posicionamiento | [`marketing/ventas/posicionamiento-comercial.md`](../marketing/ventas/posicionamiento-comercial.md) |
| Campaña HelloFresh Local | [`marketing/campana-hellofresh-local/`](../marketing/campana-hellofresh-local/) |
| Plantilla calculadora WhatsApp | [`marketing/ventas/mensaje-valor-cliente-template.md`](../marketing/ventas/mensaje-valor-cliente-template.md) |

### Sitio web

| Tema | Archivo |
|------|---------|
| Índice sitio | [`sitio-web/README.md`](../sitio-web/README.md) |
| Plan y gaps | [`sitio-web/ux/plan-sitio.md`](../sitio-web/ux/plan-sitio.md) |
| Copy español (master) | [`sitio-web/copy/copy-espanol.md`](../sitio-web/copy/copy-espanol.md) |
| Layout, UX, funnel | [`sitio-web/ux/layout-ux-marketing.md`](../sitio-web/ux/layout-ux-marketing.md) |
| Changelog mayo 2026 | [`sitio-web/ux/changelog-2026-05.md`](../sitio-web/ux/changelog-2026-05.md) |

---

## Mapa de rutas antiguas → nuevas

| Ruta anterior | Ruta nueva |
|---------------|------------|
| `01_Admin_Hiring/` | `operador-edu/` |
| `02_Shopping_Guide/` | `operaciones/compras/` |
| `03_Kitchen_Manual/` | `operaciones/cocina/` |
| `04_Business_Model/` | `negocio/` |
| `05_Market_Intelligence/` | `mercado/` |
| `06_Marketing_and_Brand/` | `marketing/` |
| `07_Client_Experience_CRM/` | `crm/` |
| `08_Logistics_and_Packaging/` | `operaciones/logistica-empaque/` |
| `09_Website/` | `sitio-web/` |
| `09_Active_Clients/` | `clientes/activos/` |
| `WEEKLY_CYCLE_SUMMARY.md` | `operaciones/ciclo/ciclo-semanal.md` |
| `04_Business_Model/07_Meal_Prep_Pricing_Model/` | `_archivo/pricing-model-v3/` |
| `docs/PROJECT_SOURCE_OF_TRUTH.md` | `docs/indice/INDEX.md` |
| Raíz (`app/`, `package.json`) | `web/` |

---

## Repos relacionados

| Repo | Rol |
|------|-----|
| `meal-prerp-website` | **Canónico** — docs + sitio prep |
| `prep-website` | Archivado (fusionado aquí) |
| `de-abasto-a-casa` | Sitio grocery extendido (hermano) |

Carpeta local Edu: ver [Easyprep](https://github.com/) workspace `Easyprep/README.md`.
