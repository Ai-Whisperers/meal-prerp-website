# Planning changelog — Mayo 2026

Consolidates decisions from the May 2026 planning session. Use with `docs/indice/INDEX.md`.

---

## 1. Repository consolidation

- **Canonical repo:** `Ai-Whisperers/meal-prerp-website`
- **Merged from:** `prep-website` (Next.js + Docker) into monorepo root
- **Archived:** `prep-website` — description: deprecated, use `meal-prerp-website`
- **Sibling (unchanged):** `de-abasto-a-casa` — extended grocery site

**Monorepo layout:** numbered doc folders + `web/app/` at root for the landing.

---

## 2. Product & packaging (delivery research)

**Recommended stack for freezer subscription (Nivel 3 / Fuego Lento):**

- Cook Sat batch → crash cool → vacuum seal → freeze → **frozen Sunday delivery**
- **Primary reheat on label:** baño maría 12–18 min; secondary: microwave (pinchar bolsa)
- **Split components** for pasta + sauce dishes (catalog already specifies)
- Liquids: “ice brick” HDPE bags (see `operaciones/logistica-empaque/empaque/especificaciones-empaque.md`)

**Do not merge** mise (Nivel 2) and freezer (Nivel 3) into one packaging or one reheat card.

Full analysis: `operaciones/logistica-empaque/entrega/metodos-entrega-regeneracion.md`

---

## 3. Commercial tiers & pricing (2026)

Three **customer-facing** tiers defined (see `negocio/precios/tiers-2026.md`):

| Tier | Name | Model |
|------|------|--------|
| 1 | Cociná vos | Mise en place — client cooks |
| 2 | Freezer semanal/mensual | Fuego Lento — cooked, frozen, reheat |
| 3 | Listo caliente | Hot daily — **waitlist / pilot only** until INAN + route density |

**Star product to sell:** Tier 2 (freezer). Tier 1 upsell. Tier 3 premium, not launch default.

---

## 4. Marketing & sales narrative

- **Selling points:** time recovered, one decision/week, price vs delivery, chef technique, freezer autonomy, radical honesty
- **Primary persona:** pareja ocupada, PedidosYa 3+/week, Lambaré/SL
- **Master story:** “El domingo que te devuelve el martes” — `marketing/ventas/story-sales-narrative.md`
- **Close mechanism:** honest calculator → WhatsApp with pre-filled numbers

---

## 5. Website strategy (layout & UX)

- **One site, two brands:** Fuego Lento (hero) + De Abasto a Casa (mise/grocery)
- **Funnel:** Instagram → web → calculator → WhatsApp → Sunday delivery
- **No checkout / no login** in Phase 1–2
- **Gap:** current `web/app/page.tsx` is mise-only; plan requires Fuego Lento hero + product picker

Full spec: `sitio-web/ux/layout-ux-marketing.md`

---

## 6. Copy & site updates pending

| Item | Target doc / code |
|------|------------------|
| Hero = Fuego Lento | `01_Copy_ES_Spanish.md`, `web/app/page.tsx` |
| Edu as operator face | `01_Copy_ES_Spanish.md` Equipo section |
| Freezer packs pricing | `01_Copy_ES_Spanish.md`, `09_Tiers_Pricing_2026.md` |
| WhatsApp deep links (menú / calc / mise) | `04_Layout_Plan_UX_Marketing.md` |
| Real phone number | Replace placeholder in copy + code |

---

## 7. Edu / Easyprep workspace

Local folder **Easyprep** mirrors Edu-specific candidate docs (`operador-edu/.../Edu_Cano_Galeano/`). Operational truth for the **business** lives in this repo after merge; Easyprep is the incubator working copy for Edu’s pivot.
