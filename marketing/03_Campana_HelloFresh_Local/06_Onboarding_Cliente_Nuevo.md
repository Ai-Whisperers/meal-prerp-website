# 🛫 Onboarding de Cliente Nuevo

> Flujo desde "me interesa" hasta "primera entrega exitosa".
> Meta: **cliente nuevo sin fricción + queda con la sensación de servicio profesional**.

---

## 🗺️ Mapa del flujo completo

```
Contacto  →  Propuesta  →  Diagnóstico  →  Registro  →  Primer Menú
   │            │              │             │              │
   │            │              │             │              ▼
   │            │              │             │         Primer Pedido
   │            │              │             │              │
   │            │              │             │              ▼
   │            │              │             │         Primera Entrega
   │            │              │             │              │
   │            │              │             │              ▼
   │            │              │             │         Follow-up
   │            │              │             │              │
   │            │              │             │              ▼
   └────────────┴──────────────┴─────────────┴───────► Cliente Fidelizado
```

---

## 📝 Paso 1 — Registro del cliente nuevo

Cuando el cliente dice **"Dale, probemos"**, recolectar:

### Datos mínimos (obligatorios)

| Dato | Ejemplo |
|---|---|
| Nombre completo | María López |
| WhatsApp | +595 981 123 456 |
| Dirección de entrega | Av. Mcal. López 123, Asunción |
| Entre qué calles / punto de referencia | Entre Brasilia y España, frente a la escuela X |
| Composición del hogar | "Pareja + 1 hijo 6 años" |

### Datos útiles (si el cliente quiere compartir)

| Dato | Uso |
|---|---|
| Aversiones / no come | Para avisar si el menú de la semana no le sirve |
| Alergias severas | NUNCA exponer al cliente a riesgo; si tiene celiaquía, desalentar |
| Cumpleaños / aniversarios | Para saludar en la fecha (fidelización) |
| Cómo nos conoció | Para saber qué canal funciona |

### Cómo recolectarlo

**Opción A — Mensaje directo de WhatsApp** (cliente casual, referido):

```
¡Bienvenido [NOMBRE]! Para armar tu ficha rápido, mandame:

1. Tu dirección con entre calles
2. Cuántas personas son en casa
3. Algo que NO comen (si hay algo)

Con eso te agrego a la lista del menú y el próximo domingo a las 20 te
llega el primer.
```

**Opción B — Formulario de Google Form / Typeform** (cliente más premium):

Armar un form de 6 preguntas (2-3 minutos de completar), pegarlo en el
mensaje inicial. Usa el template del repo:
[`crm/01_Formulario_Onboarding.md`](../../crm/01_Formulario_Onboarding.md).

**Regla:** usar Form solo si el cliente ya dijo "sí, me interesa". No
mandar form al primer mensaje (filtra demasiado).

---

## 🗂️ Paso 2 — Ficha interna del cliente

Crear **una entrada por cliente** en una hoja de Google Sheets o Notion.

### Campos (formato tabla del CRM)

| Campo | Obligatorio |
|---|---|
| ID | ✅ (consecutivo 001, 002, …) |
| Nombre | ✅ |
| WhatsApp | ✅ |
| Dirección | ✅ |
| Zona | ✅ (Lambaré / Asunción / etc.) |
| Composición hogar | ✅ |
| Estado | ✅ (Prospecto / Activo / Pausa / Churn) |
| Tipo | ✅ (Público / Ancla / Familiar) |
| Semana que ingresó | ✅ |
| Canal de adquisición | ✅ (Referido / IG / Directo) |
| Fecha de último pedido | — |
| Total pedidos históricos | — |
| Total facturado histórico | — |
| Aversiones | Si aplica |
| Referidos traídos | — |
| Notas libres | — |

**Ejemplo:** ver ficha de clientes actuales en [`clientes/activos/`](../../clientes/activos/).

---

## 🎁 Paso 3 — Primer Menú (el más importante)

### Preparación (antes del primer domingo)

1. Confirmar dirección y horario.
2. Mandar **lista de 3 platos disponibles esa semana** con un texto un poco más explicativo (es la primera vez que ve el formato).
3. Recomendarle **empezar con 3-4 porciones** (no 10 porque puede no gustar el formato).
4. Aplicar **-15% primera semana automáticamente**.

### Mensaje al cliente nuevo junto con el primer menú

```
Hola [NOMBRE], bienvenido oficial! 🎉

Te paso el menú de esta semana. Como es tu primer pedido:

• -15% automático sobre el total
• Te recomiendo arrancar con 3-4 porciones para que pruebes el formato
• Elegí preferentemente 2 platos distintos así comparás

🍽️ MENÚ [SEMANA]:
[...menú estándar...]

Confirmame qué llevás y cuántas porciones antes del miércoles 20 hs.
El domingo entre 9-12 te llego a [DIRECCIÓN].

Al recibir te dejo un papel pequeño con instrucciones de regeneración.
```

---

## 🎁 Paso 4 — Primera Entrega (experiencia wow)

### Qué lleva la bolsa del primer cliente

1. **Las porciones pedidas**, en bolsas al vacío, etiquetadas.
2. **1 papel impreso o WhatsApp con instrucciones rápidas** (cómo calentar cada plato).
3. **1 detalle sorpresa** pequeño:
   - Frasquito mini de condimento casero (ajiaceite, chimichurri, finas hierbas secas).
   - Postre chico (dulce de mamón, dulce de leche casero).
   - Handwritten "Gracias [NOMBRE]" en un papel.
4. **Factura/recibo** si el cliente lo pide.

**Costo del detalle:** Gs. 3.000-5.000. No rompe márgenes, rompe
expectativas.

### Guion de entrega (puerta a puerta, 2 minutos)

```
Hola [NOMBRE]! Te traigo tu primera bolsa.

Mirá, te explico rápido:

[abrir bolsa]

• Esto es [plato 1], dura 7 días heladera o 30 freezer.
• Esto es [plato 2], lo mismo.
• Las instrucciones están en la etiqueta, igual te mando un WhatsApp
  por si se borra.

Como es la primera vez, cualquier cosa — sabor, textura, lo que sea —
mandame mensaje. Es como aprendo.

¡Gracias por confiar! 🙏
```

**Duración:** 2-3 minutos máximo en la puerta. No entrar, no sentarse.
Profesional, cordial, breve.

---

## 📲 Paso 5 — Follow-up (las primeras 48 hs)

### Al día siguiente de la entrega (domingo tarde)

```
Hola [NOMBRE]!

¿Todo llegó bien? ¿Bolsas intactas? ¿Freezer con lugar?

Si algo no cuadra, avisame y lo resuelvo ya.
```

### A los 2-3 días (miércoles)

```
Hola [NOMBRE]!

¿Ya probaste algún plato? ¿Qué tal te fue con el calentado?

Y el sabor — sin piedad, bueno y malo. Acá aprendo más con lo que NO te
gustó que con lo que sí.
```

### A los 7 días (domingo siguiente, con el próximo menú)

```
Hola [NOMBRE]! Primera semana cerrada 🎉

¿Cómo te fue?

Te paso el menú de esta semana. Si querés seguir, decime qué pedís.
Si querés pausar, avisame y te saco de la lista de difusión (te puedo
volver a sumar cuando quieras).

Sin presión.
```

---

## 🔄 Paso 6 — Conversión a Cliente Ancla (semana 4-8)

Si el cliente pidió 4 semanas seguidas con volumen bueno (≥4 porciones /
semana), **ofrecerle Cliente Ancla** proactivamente:

```
Hola [NOMBRE]!

Veo que venís pidiendo parejo hace un mes ya 🙏

Si te querés asegurar el precio fijo, puedo pasarte a Cliente Ancla:

• Te cobro Gs. 24.000 por porción (vs. Gs. 28k público actual).
• Te garantizo ese precio por 3 meses (pase lo que pase con costos).
• Requisito: mantenés pedido mínimo 6 porciones por semana.

Si te cierra, lo activo desde el próximo pedido. No hay compromiso
más allá de los 3 meses.

¿Te sirve?
```

---

## 📊 Métricas del onboarding

Medir por cliente nuevo:

| Métrica | Meta |
|---|---|
| Tiempo del primer mensaje al primer pedido | < 10 días |
| Tasa de segunda semana (cliente que repite) | > 70% |
| Tasa de cliente ancla a los 2 meses | > 40% |
| Feedback escrito después de primera entrega | > 60% |
| Referido que trae antes del mes 3 | > 20% |

Revisar mensualmente. Si la tasa de segunda semana baja, algo en la
experiencia falla (llega tarde, packaging, sabor, precio).

---

## 🚧 Errores comunes al onboardear

1. **Mandar demasiada info al primer contacto.** Abruma. Mandar *lo mínimo* y dejar al cliente pedir más.
2. **No entregar el detalle sorpresa.** Se pierde la oportunidad del "wow".
3. **No hacer follow-up.** Cliente queda con dudas y no vuelve.
4. **Aplicar el -15% como si fuera descuento perpetuo.** Aclarar: "solo primera semana".
5. **Entregar en horario distinto al pactado sin avisar.** Destruye confianza.
6. **Pedir testimonio antes de que el cliente tenga experiencia.** Esperar al mes 2 mínimo.

---

## 📎 Referencias

- Formulario de onboarding base: [`../../crm/01_Formulario_Onboarding.md`](../../crm/01_Formulario_Onboarding.md)
- Manual de bienvenida (regeneración): [`../../crm/02_Manual_Bienvenida_Cliente.md`](../../crm/02_Manual_Bienvenida_Cliente.md)
- Fichas de clientes activos: [`../../clientes/activos/`](../../clientes/activos/)
- Guión de ventas: [`03_Guion_Ventas_WhatsApp.md`](03_Guion_Ventas_WhatsApp.md)
