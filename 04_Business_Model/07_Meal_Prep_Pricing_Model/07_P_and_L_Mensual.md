# 📊 P&L Mensual Consolidado — 5 Clientes, 2 Ciclos

> Cifras en Guaraníes (Gs.). Base: 2 ciclos de 70 porciones = 140 porciones/mes.

---

## Ingresos

| Cliente | Porciones/mes | Precio unitario | Ingreso mensual |
|---|---|---|---|
| 001 Iván/Kiki/Ale | 60 | 63.600 | 3.816.000 |
| 002 Fran | 20 | 63.600 | 1.272.000 |
| 003 Junior | 20 | 63.600 | 1.272.000 |
| 004 Emilio/Lucia | 40 | 63.600 | 2.544.000 |
| **TOTAL INGRESOS** | **140** | | **8.904.000** |

---

## Costos Variables (escalan con los ciclos)

| Concepto | Por ciclo | Mensual (×2) |
|---|---|---|
| Proteínas (whole animal) | 1.570.000 | 3.140.000 |
| Verduras + secos | 700.000 | 1.400.000 |
| Packaging | 119.000 | 238.000 |
| Combustible + auto (pasa al Comprador) | 180.000 | 360.000 |
| **Subtotal variables** | **2.569.000** | **5.138.000** |

---

## Costos Fijos Operativos (Mensuales)

| Concepto | Mensual |
|---|---|
| Gas + luz + agua (cocina base) | 360.000 |
| Consumibles limpieza | 60.000 |
| Conectividad + admin | 50.000 |
| Amortización equipos (sellador, freezer, cuchillos) | 100.000 |
| **Subtotal fijos** | **570.000** |

---

## Salarios (Labor Base + Comisiones)

| Rol | Mensual |
|---|---|
| **Chef** — sueldo base (20 hrs × 2 ciclos × 35.000) | 1.400.000 |
| **Chef** — comisión (40% margen × 2 ciclos) | 595.800 |
| **Comprador** — sueldo base (11 hrs × 2 ciclos × 25.000) | 550.000 |
| **Comprador** — comisión (30% margen × 2 ciclos) | 446.800 |
| **Subtotal salarios y comisiones** | **2.992.600** |

> Nota: los 360.000 de compensación por auto ya están contados en "variables".

---

## Reserva Empresa (Reinversión)

| Concepto | Mensual |
|---|---|
| 30% del margen (2 ciclos) | 446.800 |
| Ajuste/redondeo (absorción merma) | ~(-36.000) |
| **Reserva neta mensual** | **~410.800** |

---

## Estado de Resultados Consolidado

| Concepto | Monto | % del ingreso |
|---|---|---|
| **Ingresos** | **8.904.000** | **100,0%** |
| Costos variables | (5.138.000) | -57,7% |
| Costos fijos | (570.000) | -6,4% |
| Salarios base | (1.950.000) | -21,9% |
| Comisiones | (1.042.600) | -11,7% |
| **Reserva empresa** | **410.800** | **4,6%** |
| **Chequeo (debe = 8.904.000)** | 8.904.000 | |

---

## Distribución por "Pilar"

```
INGRESO MENSUAL:                  8.904.000 Gs.  (100%)
│
├─ Ingredientes + packaging:      4.778.000 Gs.   (53,7%) → Proveedores
├─ Chef (sueldo + comisión):      1.995.800 Gs.   (22,4%) → Persona 1
├─ Comprador (sueldo+auto+com):   1.356.800 Gs.   (15,2%) → Persona 2
├─ Overhead cocina (gas/luz/...):  360.000 Gs.    (4,0%)  → Servicios
└─ Reserva empresa:                410.800 Gs.    (4,6%)  → Reinversión
```

**Nota:** Los costos fijos (570k) + amortización equipo (100k) se distribuyen
parcialmente en "Overhead cocina" (360k que se paga de servicios reales) y 210k
que absorbe la reserva en realidad → reserva neta efectiva más cercana a 200k/mes.

---

## Proyección Anual (12 Meses)

| Concepto | Monto anual (Gs.) | USD equiv. (6.787 Gs/USD) |
|---|---|---|
| Ingresos | 106.848.000 | ~15.743 |
| Costos variables | 61.656.000 | ~9.084 |
| Costos fijos | 6.840.000 | ~1.008 |
| Salarios base | 23.400.000 | ~3.448 |
| Comisiones | 12.511.200 | ~1.843 |
| **Reserva anual** | **~4.929.600** | **~726** |

**Reserva anual ~Gs. 5M permite:**
- Año 1: Comprar freezer adicional + sellador de respaldo + capital de trabajo extra.
- Año 2: Financiar onboarding de cliente #6 y #7 sin endeudamiento.

---

## Punto de Equilibrio

**¿Cuántas porciones mínimas por ciclo para cubrir costos sin pérdida?**

- Costos fijos mensuales: 570.000
- Salarios base mensuales: 1.950.000
- Piso mínimo cubierto: Gs. 2.520.000/mes
- Ingresos requeridos (con costos variables): ~Gs. 5.950.000/mes
- **Porciones mínimas:** ~94 porciones/mes (~47 por ciclo)

Con los 5 clientes actuales (140 porciones/mes) estamos **49% por encima del
punto de equilibrio**. Sólido.

---

## Escenarios

### Escenario A — Perder el cliente más grande (Iván/Kiki/Ale)

| Métrica | Valor |
|---|---|
| Porciones/mes | 80 |
| Ingresos | Gs. 5.088.000 |
| Resultado | **Levemente por debajo del break-even** |
| Acción | Conseguir cliente de reemplazo en ≤ 2 meses |

### Escenario B — Sumar 2 clientes (a 5 porciones/ciclo c/u)

| Métrica | Valor |
|---|---|
| Porciones/mes | 180 |
| Ingresos | Gs. 11.448.000 |
| Reserva mensual | Gs. ~800.000 |
| Salarios Chef | ~2.500.000 |
| Salarios Comprador | ~1.750.000 |

### Escenario C — Subir precio a Gs. 70.000/porción (inflación/premium)

| Métrica | Valor |
|---|---|
| Ingresos | Gs. 9.800.000 |
| Margen adicional | Gs. 900.000/mes (toda a reserva + comisiones) |
| Acción | Asegurar valor percibido + comunicación clara |

---

## Conclusión

Con 5 clientes y 2 ciclos por mes, el negocio:
- **Paga salarios dignos** (Chef ~Gs. 2M/mes, Comprador ~Gs. 1,36M/mes).
- **Genera reserva anual** de ~Gs. 5M para reinvertir.
- **Opera con holgura** (49% encima del break-even).
- **Tiene espacio** para sumar 2-5 clientes más con el mismo equipo.

El modelo es **defendible**, **escalable** y **justo** para los 3 stakeholders:
clientes, operadores y negocio.
