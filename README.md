# Meal prep — De Abasto a Casa / Edu Cano Galeano

Monorepo: **documentación de negocio** (carpetas en español) + **sitio público** Next.js en la raíz.

| Parte | Ubicación | Propósito |
|-------|-----------|-----------|
| Negocio y operación | `negocio/`, `operaciones/`, `clientes/`, `crm/` | SOPs, precios, clientes, incubación |
| Marketing y sitio | `marketing/`, `sitio-web/` | Copy, ventas, UX (fuente del texto del sitio) |
| Código del sitio | `app/`, `public/`, `package.json` | [prep.paragu-ai.com](https://prep.paragu-ai.com) |
| Histórico | `_archivo/` | Modelos y planes reemplazados |

Repo hermano (grocery multi-página): [Ai-Whisperers/de-abasto-a-casa](https://github.com/Ai-Whisperers/de-abasto-a-casa).

## Desarrollo local

```bash
npm install
npm run dev      # http://localhost:3000
npm run build
npm run lint
```

## Docker

```bash
docker compose build
docker compose up -d
```

Puerto **3010** (`docker-compose.yml`).

## Documentación

**Empezar aquí:** [`docs/INDEX.md`](docs/INDEX.md)

| Tema | Doc |
|------|-----|
| Tres tiers + precios web | `negocio/precios/tiers-2026.md` |
| Story de venta | `marketing/04_Story_Sales_Narrative.md` |
| Layout / UX sitio | `sitio-web/layout-ux-marketing.md` |
| Empaque y regeneración | `operaciones/logistica-empaque/metodos-entrega-regeneracion.md` |
| Changelog mayo 2026 | `sitio-web/changelog-2026-05.md` |
