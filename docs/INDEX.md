# Índice del proyecto — meal prep / De Abasto a Casa

**Repo:** [Ai-Whisperers/meal-prerp-website](https://github.com/Ai-Whisperers/meal-prerp-website)  
**Sitio en vivo:** [prep.paragu-ai.com](https://prep.paragu-ai.com) (`app/` en la raíz)  
**Última reorganización:** Mayo 2026

---

## Estructura del repositorio

| Carpeta | Qué contiene |
|---------|----------------|
| [`app/`](../app/) | Código Next.js del sitio público |
| [`negocio/`](../negocio/) | Plan maestro, programa operador, precios, contrato |
| [`operaciones/`](../operaciones/) | Cocina, compras, logística, ciclo semanal |
| [`marketing/`](../marketing/) | Ventas, campaña HelloFresh Local, posicionamiento |
| [`sitio-web/`](../sitio-web/) | Copy, marca, UX — fuente para `app/` |
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
| Ciclo semanal | [`operaciones/ciclo-semanal.md`](../operaciones/ciclo-semanal.md) |
| Propuesta de valor | [`negocio/programa-operador/01_Propuesta_de_Valor.md`](../negocio/programa-operador/01_Propuesta_de_Valor.md) |
| Catálogo y rotación | [`negocio/programa-operador/03_Catalogo_Menu_y_Rotacion.md`](../negocio/programa-operador/03_Catalogo_Menu_y_Rotacion.md) |
| Economía unitaria | [`negocio/programa-operador/05_Economia_Unitaria.md`](../negocio/programa-operador/05_Economia_Unitaria.md) |

### Precios (2026)

| Tema | Archivo |
|------|---------|
| Tres tiers comerciales | [`negocio/precios/tiers-2026.md`](../negocio/precios/tiers-2026.md) |
| Precios por plato (catálogo) | [`negocio/programa-operador/04_Estructura_Precios.md`](../negocio/programa-operador/04_Estructura_Precios.md) |
| Contrato de servicio | [`negocio/contrato-servicios-pago.md`](../negocio/contrato-servicios-pago.md) |
| Comparativa valor cliente | [`negocio/precios/comparativa-valor-cliente.md`](../negocio/precios/comparativa-valor-cliente.md) |

### Logística y empaque

| Tema | Archivo |
|------|---------|
| Especificaciones empaque | [`operaciones/logistica-empaque/especificaciones-empaque.md`](../operaciones/logistica-empaque/especificaciones-empaque.md) |
| Cadena de frío | [`operaciones/logistica-empaque/02_Protocolo_Cadena_Frio.md`](../operaciones/logistica-empaque/02_Protocolo_Cadena_Frio.md) |
| Entrega y regeneración | [`operaciones/logistica-empaque/metodos-entrega-regeneracion.md`](../operaciones/logistica-empaque/metodos-entrega-regeneracion.md) |

### Marketing y ventas

| Tema | Archivo |
|------|---------|
| Narrativa de venta | [`marketing/04_Story_Sales_Narrative.md`](../marketing/04_Story_Sales_Narrative.md) |
| Posicionamiento | [`marketing/05_Posicionamiento_Comercial.md`](../marketing/05_Posicionamiento_Comercial.md) |
| Campaña HelloFresh Local | [`marketing/03_Campana_HelloFresh_Local/`](../marketing/03_Campana_HelloFresh_Local/) |
| Plantilla calculadora WhatsApp | [`marketing/Mensaje_Valor_Cliente_Template.md`](../marketing/Mensaje_Valor_Cliente_Template.md) |

### Sitio web

| Tema | Archivo |
|------|---------|
| Índice sitio | [`sitio-web/README.md`](../sitio-web/README.md) |
| Plan y gaps | [`sitio-web/plan-sitio.md`](../sitio-web/plan-sitio.md) |
| Copy español (master) | [`sitio-web/copy-espanol.md`](../sitio-web/copy-espanol.md) |
| Layout, UX, funnel | [`sitio-web/layout-ux-marketing.md`](../sitio-web/layout-ux-marketing.md) |
| Changelog mayo 2026 | [`sitio-web/changelog-2026-05.md`](../sitio-web/changelog-2026-05.md) |

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
| `WEEKLY_CYCLE_SUMMARY.md` | `operaciones/ciclo-semanal.md` |
| `04_Business_Model/07_Meal_Prep_Pricing_Model/` | `_archivo/pricing-model-v3/` |
| `docs/PROJECT_SOURCE_OF_TRUTH.md` | `docs/INDEX.md` |

---

## Repos relacionados

| Repo | Rol |
|------|-----|
| `meal-prerp-website` | **Canónico** — docs + sitio prep |
| `prep-website` | Archivado (fusionado aquí) |
| `de-abasto-a-casa` | Sitio grocery extendido (hermano) |

Carpeta local Edu: ver [Easyprep](https://github.com/) workspace `Easyprep/README.md`.
