# 🔄 Ciclo Operativo Quincenal

> **1 ciclo = 14 días = 70 porciones entregadas a 5 hogares.**
> **2 ciclos por mes = 140 porciones/mes.**

---

## 📅 Cronograma del Ciclo (5 días de trabajo concentrado)

### Día 1 (Domingo / Lunes temprano) — Abastecimiento
**Responsable:** Comprador

| Hora | Actividad | Lugar | Duración |
|---|---|---|---|
| 04:00 | Salida a Mercado de Abasto | San Lorenzo | — |
| 04:30 | Verduras + frutas + secos | Mercado Abasto | 2,5 hrs |
| 07:00 | Frigomas / FrigoChorti (carnes bulk) | Ruta | 2 hrs |
| 09:00 | Retorno a cocina base, recepción con Chef | Cocina | 0,5 hrs |
| — | **Total comprador día 1** | | **5 hrs** |

**Inversión estimada:** Gs. 2.405.000 (ingredientes + packaging + insumos)

### Día 2 — Carneo y Mise en Place
**Responsable:** Chef

| Actividad | Duración |
|---|---|
| Despostar cerdo entero (30 kg) | 2,5 hrs |
| Despostar cordero/cabra (12 kg) | 1,5 hrs |
| Despresar 10 pollos | 1 hr |
| Separar: cortes nobles / cortes 2da / huesos / grasa / vísceras | 1 hr |
| Lavado, pelado, cortado de verduras (mise en place) | 2 hrs |
| **Total Chef día 2** | **8 hrs** |

### Día 3 — Cocción Batch
**Responsable:** Chef

| Actividad | Duración |
|---|---|
| Cocción de 70 porciones (4 menús principales + proteínas) | 6 hrs |
| Caldos / huesos al fuego (pasivo, no cuenta como labor) | — |
| Rendering de grasa (chicharrón + manteca) | 1 hr |
| **Total Chef día 3** | **7 hrs** |

### Día 4 — Enfriado, Envasado, Etiquetado
**Responsable:** Chef + Comprador (apoyo)

| Actividad | Responsable | Duración |
|---|---|---|
| Crash cooling (90°C → 20°C en <20 min) | Chef | 1 hr |
| Envasado al vacío + sellado + etiquetado | Chef | 3 hrs |
| Organización de pedidos por hogar (bolsas térmicas) | Comprador | 2 hrs |
| **Total día 4** | | **3 hrs Chef + 2 hrs Comprador** |

### Día 5 — Entrega Puerta a Puerta
**Responsable:** Comprador

| Hogar | Tiempo | Acumulado |
|---|---|---|
| 001 Iván/Kiki/Ale (casa ancla) | 1 hr | 1 hr |
| 002 Fran | 1 hr | 2 hrs |
| 003 Junior | 1 hr | 3 hrs |
| 004 Emilio/Lucia | 1 hr | 4 hrs |
| **Total Comprador día 5** | | **4 hrs** |

---

## ⏱️ Resumen de Horas por Ciclo

| Rol | Horas | Tarifa Base | Sub-total Salario Base |
|---|---|---|---|
| **Chef** | 20 hrs | Gs. 35.000/hr | **Gs. 700.000** |
| **Comprador** | 11 hrs | Gs. 25.000/hr | **Gs. 275.000** |
| **Total labor base** | **31 hrs** | | **Gs. 975.000** |

> Ver `03_Salarios_y_Comisiones.md` para el cálculo completo incluyendo comisiones.

---

## 📦 Output del Ciclo (70 Porciones Estándar)

Cada porción es ~350-450g de comida lista para descongelar y calentar.

### Distribución de Menús (ejemplo rotativo)

| Menú | Porciones | Proteína principal |
|---|---|---|
| Guiso de cerdo con mandioca | 20 | Cerdo (paleta/bondiola) |
| Pollo al horno con vegetales asados | 18 | Pollo (pechuga + pierna) |
| Estofado de cordero con arroz | 14 | Cordero (pierna/costilla) |
| Albóndigas de cerdo en salsa | 10 | Cerdo (carne molida de recortes) |
| Caldo hueso-médula concentrado (250ml) | 8 jars | Huesos (todos) |
| **Total porciones principales** | **70** | |

### Subproductos "Gratis" (Verticales)

| Producto | Cantidad | Destino | Valor retail |
|---|---|---|---|
| BARF (mascotas) | ~3 kg | Iván (incluido) o venta | Gs. 60.000 |
| Manteca/grasa rendereada | ~2 kg | Caldos, cocina siguiente | Gs. 80.000 |
| Caldo de huesos concentrado | 8 frascos | Clientes premium | Gs. 240.000 |
| Chicharrón | ~1 kg | Regalo/snack clientes | Gs. 50.000 |
| **Total valor subproductos** | | | **Gs. 430.000** |

Estos subproductos **no** se cobran directamente (mejoran retención) pero
justifican el premium del servicio vs. supermercado.

---

## 🧊 Cadena de Frío (Crítico)

- Cocina base → enfriado rápido (ice bath invertido) → -18°C en freezer comercial.
- Transporte en conservadora con geles congelados (NO hielo suelto).
- Máx. 3 minutos desde puerta del cliente hasta su freezer.
- Etiqueta obligatoria en cada bolsa: **nombre del plato + fecha de producción + fecha vence + instrucciones de regeneración**.

Ver protocolo completo en `operaciones/logistica-empaque/02_Protocolo_Cadena_Frio.md`.

---

## 🔁 Frecuencia y Escalabilidad

| Escenario | Ciclos/mes | Comidas/mes | Horas Chef/mes | Horas Comprador/mes |
|---|---|---|---|---|
| **Baseline (5 clientes)** | 2 | 140 | 40 | 22 |
| Expansión (+2 clientes) | 2 | ~195 | 55 | 28 |
| Saturación (equipo actual) | 2 | ~250 | 70 | 35 |

A partir de 250 comidas/mes, el equipo actual satura y hace falta sumar un 2do chef
o pasar a ciclo semanal. Ese es el techo del modelo v1.
