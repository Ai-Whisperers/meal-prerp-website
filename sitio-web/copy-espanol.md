# Copy maestro del sitio — De Abasto a Casa + Fuego Lento

> **Source of truth** para todo el copy del sitio en [prep.paragu-ai.com](https://prep.paragu-ai.com).  
> Implementación: `app/page.tsx` (repo raíz).  
> Layout / UX: [`04_Layout_Plan_UX_Marketing.md`](04_Layout_Plan_UX_Marketing.md)  
> Precios: [`negocio/precios/tiers-2026.md`](../negocio/precios/tiers-2026.md)

**Nota código:** el MVP actual en `app/page.tsx` aún usa hero mise; al implementar, priorizar § Hero (Fuego Lento) abajo.

---

## Hero (Fuego Lento — objetivo)

**Headline:** El domingo que te devuelve el martes
**Subheadline:** Comida de olla, lista en 15 minutos. Un chef del IGA llena tu freezer cada domingo. Vos elegís del menú; te dura el mes.
**Precio desde:** Desde Gs. 25.400 por comida (suscriptor)
**CTA primario:** Ver menú de la semana
**CTA secundario:** Calcular mi ahorro
**CTA terciario:** Pedir por WhatsApp

### Hero alternativo (De Abasto — sub-hero o `/prep`)

**Headline:** Convertimos el caos del mercado en comida lista
**Subheadline:** Compras, prep y freezer meals puerta a puerta en San Lorenzo. Whole-animal, mayorista, sin conservantes.

---

## Problema (story hook)

**Titulo:** ¿Te suena el martes a las 19:45?
**Cuerpo:** Heladera a medias. "¿Qué hay?" PedidosYa otra vez. No te falta disciplina — te falta un sistema que te llene el freezer el domingo.

---

## Product picker (3 cards)

**Titulo:** Elegí cómo querés comer esta semana

| Card | Badge | Titulo | Sub | CTA |
|------|-------|--------|-----|-----|
| 1 | Mas pedido | Fuego Lento | Freezer lleno. Calentas 15 min. | Ver menú |
| 2 | | Cociná vos | Mise semanal. Vos cocinás. | Ver prep |
| 3 | | Solo mercado | Lista + compra. Sin prep. | Ver compras |

---

## Servicios

Titulo: **Nuestros Niveles de Servicio**
Subtitulo: Elegi lo que se adapta a tu semana. Precios referenciales, ajustables segun tu hogar.

### Nivel 1 - Compra por Lista (Raw)
Vos nos mandas la lista, nosotros traemos los ingredientes enteros desde Abasto y mercado. Vos cocinas.

- **Basico** - 250.000 Gs/semana. Lista corta, 1 proveedor. Hasta 15 productos. Delivery incluido. (120 min estimado)
- **Completo** - 400.000 Gs/semana. Lista completa + Abasto + mercado + almacen. Delivery y organizado en cocina. (180 min)

### Nivel 2 - Mise-en-Place Semanal (mas elegido)
Compramos, lavamos, porcionamos y organizamos tu heladera y freezer. Listo para cocinar en minutos.

- **Individual (1 persona)** - 400.000 Gs/semana. Prep basico. Proteina + carbos + vegetales porcionados y sellados al vacio. (240 min)
- **Pareja (2 personas)** - 650.000 Gs/semana. Prep completo para 2. Organizacion de heladera y freezer. (300 min)
- **Familia (3-4 personas)** - 900.000 Gs/semana. Prep familiar. Variedad, porciones y sustituciones incluidas. (360 min)

### Nivel 3 - Fuego Lento / Comidas listas (freezer)

Comidas cocinadas, selladas al vacio, congeladas. Listas para regenerar (baño maria / micro / horno). Ver [`operaciones/logistica-empaque/metodos-entrega-regeneracion.md`](../operaciones/logistica-empaque/metodos-entrega-regeneracion.md).

**Por porcion:** desde Gs. 24.000 (suscriptor 6+ porc./sem) · publico Gs. 28.000

**Packs semanales:**
- **Ligera** — 6 porciones: Gs. 168.000 publico / Gs. 144.000 suscriptor
- **Estandar** — 10 porciones + 1 frasco: Gs. 298.000 / Gs. 254.000
- **Familia** — 14 porciones + 2 frascos: Gs. 428.000 / Gs. 364.000

**Packs mensuales:** desde Gs. 560.000/mes (24 porciones, suscriptor)

**Ciclo:** publicamos menu domingo 20:00 · pedidos hasta miercoles 20:00 · entrega domingo 9:00-12:00

### Nivel 3b - Listo caliente diario (lista de espera)

Comidas calientes mismo dia. Requiere INAN + ruta densa. Desde Gs. 85.000/comida. Escribinos para lista de espera.

### Add-ons opcionales (sumables a cualquier nivel)
- **Desayunos** +400.000 Gs/mes
- **Postres** +200.000 Gs/mes
- **Bebidas / snacks** +300.000 Gs/mes

---

## Como funciona

**Titulo:** Como funciona

1. **Conversamos** - 10 min por WhatsApp. Armamos tu plan segun presupuesto, personas y dias que queres recibir.
2. **Planeamos tu semana** - Menu base, sustituciones, proveedores, horarios de compra y entrega.
3. **Compramos y prepeamos** - Martes y jueves en Abasto y mercado. Prep en cocina certificada. Sellado al vacio.
4. **Entregamos** - Puerta a puerta, con cadena de frio. Organizamos tu heladera y freezer si lo pedis.

---

## Calculadora de Ahorro

**Titulo:** Calcula tu ahorro real
**Subtitulo:** Numeros honestos. Si no te conviene, te lo decimos.

**Disclaimer:** Estimacion referencial. Precios finales se ajustan segun tu hogar y nivel de servicio.

**Copy cuando ahorro > 0:** Si tu ahorro es grande, tiene sentido probar 1 mes sin compromiso.

**Copy cuando ahorro <= 0:** Hoy ya sos muy eficiente. Probablemente no te conviene - pero si queres probar 1 mes sin compromiso, escribinos igual.

**CTA boton:** Seguir por WhatsApp con mis numeros

---

## Galeria

**Titulo:** Cortes y calidad
**Subtitulo:** Whole-animal, mayorista, lo mejor del mercado.

Categorias: Cortes de Carne - Mise en Place - Freezer Meals - Mercado

---

## Calidad y sourcing

**Titulo:** Como compramos

1. **Whole-animal** - Animales enteros, cortados y porcionados por nosotros. Mejor calidad, mejor precio por kilo.
2. **Mayorista Abasto** - Proveedores directos, sin intermediarios. Precios de mercado mayorista trasladados al cliente.
3. **Estacional** - Respetamos el calendario de Paraguay. Compramos lo que esta en temporada, mas barato y mas rico.
4. **Sin conservantes** - Congelamos al instante despues del prep. Nunca usamos aditivos ni conservantes.

---

## Fuego Lento (bloque dedicado)

**Titulo:** Menu de la semana
**Subtitulo:** 3 platos + 1 extra. Elegis porciones hasta el miercoles.

*(Platos: rotacion desde `negocio/programa-operador/03_Catalogo_Menu_y_Rotacion.md` — actualizar semanalmente)*

**Titulo secundario:** Como se ve en tu casa
- Bolsa al vacio etiquetada a mano
- Regenerar: bano maria 15 min (recomendado) o microondas (pinchar bolsa)
- 7 dias heladera / 30 dias freezer

**CTA:** Pedir por WhatsApp — menu esta semana

---

## Comparativa

**Titulo:** No es delivery. No es congelado de gondola.

| | PedidosYa | Congelado super | Fuego Lento |
|--|-----------|-----------------|-------------|
| Precio/comida | Gs. 55.000-85.000 | Gs. 20.000-30.000 | Gs. 25.000-28.000 |
| Tiempo | 45 min espera | 15 min micro | 15 min |
| Stock semana | No | Si | Si |
| Cocinado por | Restaurante variable | Fabrica | Chef IGA, batch |

---

## Equipo

**Titulo:** Quien cocina

**Eduardo Cano Galeano (Edu)** — Chef operador · IGA Alta Cocina
Cocina en batch cada semana: estofados, pepitoria, platos freezer-friendly. Fuego Lento es su servicio de comida casera premium para Lambaré y alrededores.

**De Abasto a Casa** — Sistema de mercado, prep y entrega. Mentoría y clientes ancla desde 2025.

*(Opcional mencionar: Ivan Weiss van der Pol — cliente fundador y mentor del programa.)*

---

## FAQ

1. **Que incluye el servicio?**
   Incluye: compras en Abasto + mercado, prep (lavado, cortado, porcionado), sellado al vacio, 2 entregas por mes puerta a puerta con cadena de frio, sustituciones hasta 3 menus por mes, precio fijo 6 meses y pausa de vacaciones. No incluye desayunos, bebidas ni postres (disponibles como add-on).

2. **Como son las entregas?**
   Compramos martes y jueves. Entregamos el mismo dia, puerta a puerta, con cadena de frio. Coordinamos horario por WhatsApp.

3. **Puedo pausar el servicio?**
   Si. Tenes 1 mes por ano de pausa sin costo (vacaciones, viajes, etc). Avisanos con 48 hrs.

4. **Que pasa si no me gusta una comida?**
   Garantia de satisfaccion: si algo sale mal, lo reemplazamos sin cargo en la proxima entrega.

5. **En que casos NO me conviene?**
   Honestidad total: si te encanta cocinar, si tu gasto actual es menor a Gs. 2M/mes para 3 personas, o si no tenes freezer. Mejor no te suscribas.

6. **Como pago?**
   Transferencia bancaria o efectivo. Sin compromiso en el primer mes. Precio fijo 6 meses al suscribirte.

7. **Atienden fuera de San Lorenzo?**
   Por ahora solo San Lorenzo (ciudad completa). Proximamente Asuncion centro.

8. **Tienen habilitacion INAN?**
   Nivel 1 y Nivel 2 no requieren habilitacion especial (solo compra y prep). Nivel 3 (comidas cocidas listas) esta en proceso de habilitacion INAN.

---

## Testimonios (placeholders ilustrativos)

> "Recupere 20+ horas al mes. No vuelvo a cocinar todos los dias." - *Remoto Global (cliente ilustrativo)*
> "La proteina sellada al vacio dura 4 meses en freezer sin perder sabor. Cambia todo." - *Profesional Medico (cliente ilustrativo)*
> "Primera vez que pago un servicio con numeros honestos. No me inflan, me muestran." - *Pareja Commuter (clientes ilustrativos)*

**Reemplazar con citas reales de Fran, Junior y Emilio & Lucia cuando se obtenga autorizacion.**

---

## Contacto

**Titulo:** Pedinos tu propuesta
**Subtitulo:** Cobertura en San Lorenzo

- **WhatsApp:** (placeholder - reemplazar con numero real)
- **Email:** hola@deabastoacasa.com.py (placeholder)
- **Cobertura:** San Lorenzo (ciudad completa)
- **Horarios de compra:** Martes y Jueves en Abasto + mercado
- **Entregas:** Sabado 09:00 - 14:00

---

## CTA Banner final + WhatsApp float

**Banner:** Pedi tu propuesta en 5 min por WhatsApp. Boton: "Escribir ahora"

**Float persistente (default):** "Hola! Vi Fuego Lento / De Abasto a Casa y quiero ver el menu de esta semana."

**Deep links WhatsApp:**

| Intent | Texto pre-fill |
|--------|----------------|
| Menu semana | `Hola! Quiero ver el menu de esta semana` |
| Calculadora | `Hola! Calcule mi ahorro en el sitio y quiero seguir` |
| Mise pareja | `Hola! Me interesa mise-en-place para pareja` |
| Lista espera caliente | `Hola! Quiero lista de espera para comidas calientes diarias` |

---

## Footer

Quick links: Servicios - Calculadora - Galeria - FAQ - Contacto
Copyright: 2026 De Abasto a Casa - San Lorenzo, Paraguay.
