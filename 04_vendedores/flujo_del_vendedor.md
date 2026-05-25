# 🔄 Flujo de Trabajo Diario del Asesor Comercial

El éxito en ventas radica en la consistencia de la ejecución. Este manual establece el protocolo operativo paso a paso que todo vendedor de **Creamos Tu Empresa Digital** y **Gravity Studio** debe seguir desde que se le asigna un prospecto hasta el cierre y entrega de la solución.

---

## 🗺️ 1. El Embudo del Asesor Comercial (Paso a Paso)

```
[Filtro 1: Speed-to-Lead] ──► [Filtro 2: Perfilamiento] ──► [Llamada Diagnóstico] ──► [Envío Propuesta] ──► [Hito Cierre]
```

### Paso 1: Onboarding del Lead (`nuevo_brief` ──► `contacto_iniciado`)
1. **Asignación del Lead**: Al asignársele un prospecto en el portal, el vendedor recibe los datos del cotizador inteligente en Supabase.
2. **Speed-to-Lead (< 4 Horas)**: Copia la plantilla de primer contacto en [Guion de WhatsApp](../02_guiones_de_venta/guion_whatsapp.md) y abre la conversación.
3. **Actualización en CRM**: Pulsa *"Iniciar Seguimiento"* en el panel comercial para cambiar el estado a `contacto_iniciado`. 
   > [!IMPORTANT]
   > El cambio a `contacto_iniciado` debe ocurrir en menos de 4 horas hábiles. Cumplir esta métrica de tiempo es vital para auditar el desempeño de los vendedores.

---

### Paso 2: Perfilamiento y Diagnóstico (`contacto_iniciado` ──► Agendamiento)
1. **Filtro de Calidad Comercial**: Aplica el cuestionario básico y diagnóstico de presencia digital del prospecto en menos de 24 horas hábiles utilizando las guías del [diagnostico_gratuito.md](../06_formularios/diagnostico_gratuito.md).
2. **Calificación del Lead**: Determina si el cliente tiene un negocio operativo, presupuesto básico o presencia previa.
3. **Agendamiento**: Mueve al cliente a una llamada de diagnóstico rápida de 15 minutos en Calendly.

---

### Paso 3: Llamada y Selección de Solución (Perfilamiento ──► `propuesta_enviada`)
1. **Llamada de 15 Minutos**: Escucha activamente los dolores del cliente. No intentes vender la página de inmediato, enfócate en auditar lo que hoy frena su conversión.
2. **Definición de Paquete**:
   * Si requiere validar una oferta rápido sin integraciones: **Paquete 1 ($3,499 MXN)**.
   * Si requiere autoridad y estatus corporativo multipágina: **Paquete 2 ($5,899 MXN)**.
   * Si requiere automatización y seguimiento por email y WhatsApp: **Paquete 3 ($13,499 MXN)**.
   * Si requiere sistemas a la medida con integraciones complejas: **Vende la Auditoría de Automatización ($5,000 MXN) de forma obligatoria**.
3. **Envío de Propuesta**: Envía la propuesta formal en PDF y cambia el estado en el CRM a `propuesta_enviada`.

---

### Paso 4: Cierre de Venta y Cobro de Anticipo (`propuesta_enviada` ──► `anticipo_pagado`)
1. **Seguimiento Estructurado**: Realiza el seguimiento sin hostigar cada 48 horas (máximo 3 contactos).
2. **Recepción del Anticipo**: Solicita el 50% de anticipo (o 100% por adelantado en P1 y P2).
3. **Carga en el CRM**: Carga el comprobante en el portal de ventas. Una vez verificado por administración, el estado pasa a `anticipo_pagado`.
4. **Registro Comercial**: Tu venta queda registrada en estado de **"Pendiente de Entrega"** en Supabase para el seguimiento administrativo.
5. **Creación del Expediente**: La Ficha del Cliente se transfiere a la Fila de Desarrollo de la fábrica de software.

---

### Paso 5: Entrega y Liquidación (`anticipo_pagado` ──► `entregado`)
1. **Acompañamiento en Sprint**: Mantente disponible para recopilar logotipos o imágenes del cliente si la fábrica lo requiere.
2. **Validación de Calidad**: Una vez que **Antigravity** realiza el QA responsivo de 360px-430px y de optimización técnica del sitio, se le presenta la demo al cliente.
3. **Cobro de Liquidación**: El cliente realiza el pago del 50% restante o el monto acordado.
4. **Despliegue y Apuntado**: La fábrica apunta el dominio del cliente, y el estado de la venta pasa a **"Entregado"** en Supabase de forma definitiva.

---

## 📅 2. Horarios y Ritmo de Trabajo Recomendado

*   **09:00 - 10:00**: Revisión de nuevos leads asignados (`nuevo_brief`) y envío inmediato de Speed-to-Lead por WhatsApp.
*   **10:00 - 13:00**: Llamadas de diagnóstico rápidas agendadas en Calendly.
*   **13:00 - 14:00**: Preparación y envío de propuestas personalizadas en PDF de las llamadas de la mañana.
*   **16:00 - 18:00**: Seguimiento a propuestas enviadas en las últimas 48-72 horas y reactivación de leads fríos de la quincena.
