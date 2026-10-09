# Sprint Review - Sprint 03

## 1. Información General del Sprint
* **Proyecto:** OasisSpa
* **Sprint:** 03
* **Objetivo del Sprint:** Finalizar la implementación del módulo de reservas y el flujo de métodos de pago con sus validaciones y reglas de cancelación.
* **Resultado del Objetivo:** Cumplido exitosamente.

---

## 2. Historias de Usuario Entregadas (Incremento de Producto)

| Cód. HU | Historia de Usuario | Estado | Observaciones / Demostración |
| :---: | :--- | :---: | :--- |
| **HU 1.1.1** | Ingresar nombre e identificación | **Completado** | Formulario valida campos obligatorios. |
| **HU 1.1.2** | Aceptar términos y condiciones | **Completado** | Checkbox integrado en el registro. |
| **HU 1.1.3** | Validación de código Captcha | **Completado** | Mecanismo de seguridad operativo. |
| **HU 1.2.1** | Selección del tipo de servicio | **Completado** | Listado de servicios dinámico. |
| **HU 1.2.2** | Selección de día, fecha y hora | **Completado** | Calendario con bloques de tiempo. |
| **HU 1.3.1** | Validación de disponibilidad | **Completado** | Previene cruce de citas. |
| **HU 1.4.1** | Confirmación de reserva | **Completado** | Pantalla de resumen de cita lista. |
| **HU 2.1.1** | Selección de método de pago | **Completado** | Opciones: Efectivo, Transferencia, Tarjeta. |
| **HU 2.2.1** | Pago del 50% de anticipo | **Completado** | Lógica de cobro inicial del 50%. |
| **HU 2.2.2** | Cálculo de saldo pendiente | **Completado** | Muestra saldo a pagar en instalaciones. |
| **HU 2.3.1** | Aplicar código de descuento | **Completado** | Aplica cupones promocionales. |
| **HU 2.4.1** | Confirmación de transacción | **Completado** | Comprobante digital generado. |
| **HU 2.5.1** | Solicitar reprogramación (24h) | **Completado** | Validación del límite de 24 horas. |
| **HU 2.5.2** | Consulta condiciones devolución | **Completado** | Vista con políticas de cancelación. |
| **HU 2.5.3** | Cálculo de devolución del 50% | **Completado** | Cálculo del reembolso según condiciones. |

> **Puntos de Historia Completados:** 53 / 53 Story Points.

---

## 3. Demostración y Feedback de Stakeholders
* **Demostración:** Se realizó la demostración del medio de pagos y reservas llevando informacion correctamente 
* **Retroalimentación recibida:**
  * El flujo de reserva es intuitivo y cumple con los requerimientos.
  * Se sugiere en futuros desarrollos enviar un correo de recordatorio 24 horas antes de la cita.