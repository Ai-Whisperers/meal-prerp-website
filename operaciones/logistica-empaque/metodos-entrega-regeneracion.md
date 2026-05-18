# Métodos de entrega, empaque y regeneración

**Fuente de verdad** para operaciones de packaging y instrucciones al cliente.  
Complementa [`01_Especificaciones_Empaque.md`](01_Especificaciones_Empaque.md) y [`02_Protocolo_Cadena_Frio.md`](02_Protocolo_Cadena_Frio.md).

---

## Modelos de entrega (resumen)

| Modelo | Producto | Empaque | Entrega | Regeneración |
|--------|----------|---------|---------|--------------|
| Mise (Tier 1) | Crudo preparado | Tuppers PP/vidrio | Frío semanal | Cliente cocina |
| Freezer (Tier 2) | Cocido | Vacío (+ dual bag pasta) | Congelado domingo | Baño maría / micro / horno |
| Caliente (Tier 3) | Cocido mismo día | Térmico | Hot &lt;30 min | Inmediato |

**Recomendación operativa:** Tier 2 como default del negocio.

---

## Freezer (Tier 2) — stack recomendado

1. Cocinar batch (sábado)
2. **Crash cool** 90°C → 20°C en &lt;20 min (baño maría inverso)
3. Porcionar y pesar; **separar** pasta/salsa cuando el catálogo lo indique
4. Envasar al vacío (bolsa gofrada 20×25 cm según gramaje)
5. Etiquetar (ver plantilla abajo)
6. Congelar plano
7. Entregar domingo con bolsa térmica + geles; A/C en habitáculo

**Líquidos (caldo, crema):** bolsa HDPE “ice brick”, congelar acostado — ver `01_Especificaciones_Empaque.md`.

---

## Clases de regeneración (etiqueta)

Asignar **una primaria + una secundaria** por SKU.

| Código | Tipo | Primaria | Secundaria |
|--------|------|----------|------------|
| **G** | Guiso / estofado | Baño maría 15 min | Micro 6 min (pinchar bolsa) |
| **P** | Pasta + salsa aparte | Salsa: baño maría; pasta: agua 3 min | — |
| **H** | Gratin / horneado | Horno 200°C 18 min (en fuente) | — |
| **S** | Sopa / brick | Descongelar + olla 8 min | Micro en bowl |
| **R** | Terminar en olla | Olla + caldo indicado 5–7 min | — |

---

## Plantilla de etiqueta (por bolsa)

```text
[LOGO] Fuego Lento · De Abasto a Casa
PLATO: [nombre]
PESO: ~400 g
PROD: DD/MM/AAAA
FRÍO: consumir antes DD/MM
FREEZER: consumir antes DD/MM
REGENERAR:
  ① [método primario]
  ② [método secundario]
NO descongelar >2 h a temperatura ambiente
WhatsApp: [número]
```

---

## Inserto A5 por entrega (cliente)

1. Al recibir → freezer en ≤3 min  
2. No recalentar dos veces  
3. Descongelar preferir 24 h en heladera  
4. Bolsa inflada / olor raro / &gt;2 h fuera de frío → no consumir, avisar  

---

## Qué evitar

- Comida caliente al freezer o al vacío
- Vacío con comida tibia (cristales de hielo, quejas de “descongelado”)
- Pasta y salsa en una sola bolsa
- Prometer crocante post-freezer (milanesa, empanadas, etc.)
- Entrega a temperatura ambiente en verano sin geles

---

## MAP / sous vide / tuppers

| Método | Cuándo |
|--------|--------|
| Vacío | **Default** freezer subscription |
| Tuppers | Mise Tier 1 |
| MAP trays | Escala retail &gt;200 porc./sem — no ahora |
| Sous vide cook-in-bag | Opcional upgrade proteínas; misma bolsa para regenerar |

---

## Referencias

- Catálogo (envase por plato): [`negocio/programa-operador/03_Catalogo_Menu_y_Rotacion.md`](../negocio/programa-operador/03_Catalogo_Menu_y_Rotacion.md)
- Ciclo semanal: [`operaciones/ciclo-semanal.md`](../operaciones/ciclo-semanal.md)
