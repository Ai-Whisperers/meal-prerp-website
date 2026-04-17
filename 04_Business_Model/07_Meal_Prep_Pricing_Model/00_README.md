# 🍱 Meal Prep & Freezer Meals — Pricing Model v1

> **Propósito:** Transicionar el negocio de "compras + prep a pedido" a un servicio
> recurrente de **meal prep + freezer meals** con 5 hogares clientes, operado por
> un equipo de **2 personas** (1 Chef + 1 Comprador con auto), usando filosofía
> **whole-animal + bulk buying** para maximizar margen y pagar un salario justo.

---

## 📚 Índice

1. **[01_Operacion_y_Ciclo.md](./01_Operacion_y_Ciclo.md)** — Cómo funciona el ciclo quincenal (compra → carneo → prep → cocción → entrega).
2. **[02_Costos_Unidad.md](./02_Costos_Unidad.md)** — Costo real de un ciclo completo: carnes, verduras, packaging, gas, luz.
3. **[03_Salarios_y_Comisiones.md](./03_Salarios_y_Comisiones.md)** — Salario base por hora + comisión sobre margen, por rol. Salario digno en Paraguay 2026.
4. **[04_Precios_Cliente.md](./04_Precios_Cliente.md)** — Precio final por comida, por cliente, con desglose 100% transparente.
5. **[05_Yield_Animal_Entero.md](./05_Yield_Animal_Entero.md)** — Rendimiento real de cerdo/cordero/pollo entero. Qué es carne, qué es BARF, qué es caldo.
6. **[06_Bulk_Sourcing_Playbook.md](./06_Bulk_Sourcing_Playbook.md)** — Dónde comprar, cuánto pedir, cómo negociar para bajar costo 30-50%.
7. **[07_P_and_L_Mensual.md](./07_P_and_L_Mensual.md)** — Estado de resultados mensual consolidado (ingresos, costos, salarios, margen empresa).

---

## 🎯 Decisiones de Diseño (Resumen Ejecutivo)

| Decisión | Valor | Justificación |
|---|---|---|
| **Moneda** | Guaraní (PYG / Gs.) | Paraguay. Referencia USD: 1 USD ≈ 6.787 Gs. (Ene 2026) |
| **Ciclo operativo** | Quincenal (cada 14 días) | Compra 1 animal entero + stock quincenal. 2 ciclos/mes. |
| **Cantidad de comidas/ciclo** | **70 porciones** | 5 hogares, ~14 días de autonomía |
| **Precio promedio/comida** | **Gs. 63.600** (~USD 9,37) | Premium artesanal, menor que restaurant, mayor que supermercado |
| **Margen bruto empresa** | ~20% sobre costo total | Pagar salarios justos + reinversión (freezer, sellador, marketing) |
| **% que va a salarios** | **~22%** del ingreso | Salario por hora + comisión sobre margen |
| **% que va a ingredientes** | **~54%** del ingreso | Whole-animal + mayorista |
| **Salario efectivo Chef** | ~Gs. 49.850/hora | Muy por encima del mínimo legal (~13.900/hr) |
| **Salario efectivo Comprador** | ~Gs. 45.300/hora | Incluye uso del auto |

---

## 👥 Equipo

| Rol | Persona | Horas/ciclo | Responsabilidad |
|---|---|---|---|
| **Chef** | 1 persona | ~20 hrs | Carneo (despostar animal entero), mise en place, cocción, envasado al vacío, etiquetado, control de calidad |
| **Comprador + Auto** | 1 persona | ~11 hrs | Runs a Mercado de Abasto + Frigorífico, selección/negociación, logística en frío, entrega a domicilio a los 4 hogares |

Ambos son **socios operativos**. Cobran sueldo por hora + comisión sobre el margen neto del ciclo.

---

## 🏠 Clientes (5 Hogares, 8 Personas)

| ID | Hogar | Personas | Porciones/Ciclo | Notas |
|---|---|---|---|---|
| 001 | **Iván, Kiki, Ale** | 3 | 30 | Casa ancla. Whole-animal, nose-to-tail, BARF para mascotas incluido |
| 002 | **Fran** | 1 | 10 | Solo. Alta rotación, proteína magra |
| 003 | **Junior** | 1 | 10 | Solo. Volumen alto, calorías, gimnasio |
| 004 | **Emilio y Lucia** | 2 | 20 | Pareja. Balance proteína/vegetales |
| — | — | **7** | **70** | **Total por ciclo quincenal** |

---

## 💡 Filosofía de Pricing

1. **Transparencia total:** Cada cliente ve el desglose — cuánto es ingrediente, cuánto labor, cuánto vehículo, cuánto margen empresa.
2. **Pro-rata por porción:** Todos los costos compartidos (animal entero, viaje al mercado, gas de cocina) se dividen por las 70 porciones. El cliente paga solo lo suyo.
3. **Salario justo primero:** Salario digno garantizado por hora para Chef y Comprador, **antes** de calcular el margen del negocio.
4. **Comisión como incentivo:** 70% del margen neto se reparte entre los 2 socios operativos. 30% queda como reserva/reinversión del negocio.
5. **Whole-animal como ventaja competitiva:** Comprar un cerdo entero a 25.000 Gs/kg vs. cortes premium a 45.000 Gs/kg genera ~40% de ahorro. Ese ahorro se reparte: mitad al cliente (precio más accesible), mitad a salarios.

---

## 🔗 Referencias Cruzadas

- Estructura de servicio original: `04_Business_Model/Service_Contract_and_Payment.md`
- Rentabilidad del núcleo (20 clientes): `04_Business_Model/01_Core_Business/02_Rentabilidad_Nucleo.md`
- Precios mayoristas: `02_Shopping_Guide/Referencia_Precios_Mayorista.md`
- Compra de animales enteros: `02_Shopping_Guide/Compra_Animales_Enteros.md`
- Cadena de frío: `08_Logistics_and_Packaging/02_Protocolo_Cadena_Frio.md`
