# 💼 Portal Comercial y Ventas — Creamos Tu Empresa Digital / Gravity Studio

¡Bienvenido al repositorio central de operación comercial! Este es el sistema operativo comercial, diseñado para albergar guiones de venta, tabuladores de comisiones, políticas para asesores, KPIs y herramientas de seguimiento de prospectos.

---

## 🎯 1. Propósito del Repositorio

Este espacio tiene como fin **estructurar, automatizar y auditar** todo el proceso comercial de **Creamos Tu Empresa Digital** y **Gravity Studio**. 
Sirve como el cerebro de ventas unificado para:
1. **Vendedores y Asesores**: Acceder a guiones listos para usar, tabuladores de precios, flujos de trabajo claros y políticas de comisiones.
2. **Coordinadores y Gerencia (Adolfo)**: Auditar el desempeño del pipeline en tiempo real y validar la viabilidad comercial.
3. **Modelos de IA (ChatGPT y Antigravity)**: Leer el estado operativo, interpretar las políticas comerciales autorizadas y apoyar en la optimización de los flujos de leads.

---

## 📂 2. Estructura General del Sistema

El repositorio está organizado de forma jerárquica para permitir una fácil navegación tanto en local como desde Obsidian:

```
ventas/
├── README.md                           # Esta guía maestra de navegación y políticas
├── 00_indice_operativo/                # Mapa general de archivos del repositorio
│   └── indice_ventas.md
├── 01_oferta_comercial/                # Portafolio oficial, precios e infraestructura BlueJax
│   ├── oferta_principal.md
│   ├── paquetes_y_precios.md
│   └── propuesta_de_valor.md
├── 02_guiones_de_venta/                # Scripts listos para WhatsApp, llamadas y seguimiento
│   ├── guion_primer_contacto.md
│   ├── guion_whatsapp.md
│   ├── guion_llamada.md
│   └── seguimiento_post_contacto.md
├── 03_objeciones/                      # Respuestas autorizadas ante fricciones del prospecto
│   └── objeciones_y_respuestas.md
├── 04_vendedores/                      # Flujos, comisiones, KPIs y reglamento comercial
│   ├── flujo_del_vendedor.md
│   ├── reglas_para_vendedores.md
│   ├── politica_de_comisiones.md
│   └── kpis_por_vendedor.md
├── 05_prospectos/                      # Estructura del lead y expedientes del CRM
│   ├── estructura_lead.md
│   ├── estados_del_lead.md
│   └── checklist_expediente_cliente.md
├── 06_formularios/                     # Cuestionarios oficiales de diagnóstico y perfilamiento
│   ├── diagnostico_gratuito.md
│   ├── cuestionario_basico.md
│   ├── cuestionario_comercial.md
│   └── cuestionario_premium.md
├── 07_materiales_publicitarios/        # Copys y recursos de atracción listos para compartir
│   ├── flyer_contratacion.md
│   ├── flyers_oficina.md
│   └── copy_redes.md
├── 08_kpis/                            # Dashboards y métricas de salud comercial
│   ├── kpis_comerciales.md
│   └── tablero_sugerido.md
├── 09_procesos/                        # Flujos operativos completos de la fase comercial
│   ├── proceso_comercial_completo.md
│   ├── proceso_cierre_venta.md
│   └── proceso_postventa.md
└── 10_prompts_antigravity/             # Instrucciones de IA para soporte en ventas
    └── prompt_maestro_ventas.md
```

---

## 🛡️ 3. Reglas Críticas de Seguridad y Privacidad

Para mantener la integridad corporativa y de conformidad con el diseño de seguridad, se establecen las siguientes directrices:

> [!CAUTION]
> **LÍNEA ROJA DE SEGURIDAD COMERCIAL**
> * **Cero Información Sensible**: Queda estrictamente prohibido guardar contraseñas, llaves de API, tokens `service_role` o accesos bancarios en este repositorio.
> * **Aislamiento Financiero Central**: Este espacio trata exclusivamente sobre precios de venta al público y comisiones brutas de asesores. Bajo ninguna circunstancia se importarán registros de costos de infraestructura internos de BlueJax ni flujos de margen neto de la agencia.
> * **Sin Datos Sensibles de Clientes Reales**: No almacenes números de tarjetas, identificaciones oficiales o bases de datos crudas de clientes en estas notas. El CRM en Supabase es el único repositorio seguro para ello.

---

## 🔗 4. Relación con `gravity-studio-system`

Este repositorio (`ventas`) funciona de manera coordinada pero desacoplada con el core operativo de la agencia (`gravity-studio-system`).
* **gravity-studio-system**: Contiene los manuales técnicos, infraestructura de fábrica de software, checklist de control de calidad responsivo y de código, y flujos de dirección ejecutiva a cargo de Humberto Robles Quezada.
* **ventas**: Es un espacio ágil, dedicado al 100% a la aceleración, comisiones, guiones e inventario de leads en fase comercial. Los asesores comerciales interactúan principalmente con este repositorio para agilizar sus cierres.

---

## 🤖 5. Guía de Interacción para Modelos de IA (ChatGPT / Antigravity)

* **Lectura Operativa**: Antes de proponer modificaciones comerciales o interactuar con un lead, lee siempre [indice_ventas.md](00_indice_operativo/indice_ventas.md) para contextualizar el pipeline.
* **Integridad del Onboarding**: Al guiar a un vendedor o auditar un cuestionario de lead nuevo, cerciórate de que se cumplan estrictamente las reglas en [reglas_para_vendedores.md](04_vendedores/reglas_para_vendedores.md).
* **Cumplimiento de SLAs**: No inventes promesas de resultados (SLAs falsas). Utiliza estrictamente la oferta estandarizada de [oferta_principal.md](01_oferta_comercial/oferta_principal.md).
