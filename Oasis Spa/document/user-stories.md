# Historias de Usuario - Oasis Spa

## Descripción

Las historias de usuario representan las necesidades y funcionalidades esperadas por los usuarios del sistema Oasis Spa. Estas historias sirven como base para la construcción del Product Backlog y la planificación de los Sprints.

---

# Épica 1: Reserva de Servicios

## HU-1.1.1 Registro de Datos

**Como** cliente  
**Quiero** ingresar mi nombre completo y número de identificación  
**Para** registrar mis datos al momento de realizar una reserva.

### Criterios de Aceptación

- El sistema solicita nombre completo.
- El sistema solicita número de identificación.
- Los campos son obligatorios.
- La información se almacena correctamente.

---

## HU-1.1.2 Aceptación de Términos y Condiciones

**Como** cliente  
**Quiero** aceptar los términos y condiciones  
**Para** poder continuar con mi reserva.

### Criterios de Aceptación

- Se muestra el documento de términos y condiciones.
- El usuario debe aceptar antes de continuar.
- La aceptación queda registrada.

---

## HU-1.1.3 Validación Captcha

**Como** cliente  
**Quiero** ingresar un código Captcha  
**Para** verificar que soy una persona y continuar con la reserva.

### Criterios de Aceptación

- El Captcha es obligatorio.
- El sistema valida el código ingresado.
- Si es incorrecto, solicita un nuevo intento.

---

## HU-1.2.1 Seleccionar Servicio

**Como** cliente  
**Quiero** seleccionar el tipo de servicio que deseo  
**Para** reservar el tratamiento que necesito.

### Criterios de Aceptación

- Se muestran los servicios disponibles.
- El cliente puede seleccionar uno o varios servicios.
- El sistema registra la selección.

---

## HU-1.2.2 Seleccionar Fecha y Hora

**Como** cliente  
**Quiero** seleccionar el día, fecha y hora de mi cita  
**Para** reservar un horario disponible.

### Criterios de Aceptación

- El sistema muestra horarios disponibles.
- No permite reservar horarios ocupados.
- La fecha seleccionada queda asociada a la reserva.

---

## HU-1.3.1 Validación de Reserva

**Como** cliente  
**Quiero** que el sistema valide mis datos y la disponibilidad de la cita  
**Para** evitar errores al realizar mi reserva.

### Criterios de Aceptación

- Se validan campos obligatorios.
- Se verifica disponibilidad.
- El sistema informa errores encontrados.

---

## HU-1.4.1 Confirmación de Reserva

**Como** cliente  
**Quiero** recibir la confirmación de mi reserva  
**Para** saber que mi cita quedó registrada correctamente.

### Criterios de Aceptación

- El sistema genera un comprobante.
- Se informa el número de reserva.
- La reserva queda almacenada.

---

# Épica 2: Gestión de Pagos

## HU-2.1.1 Seleccionar Método de Pago

**Como** cliente  
**Quiero** seleccionar mi método de pago entre efectivo, transferencia, crédito o débito  
**Para** elegir la forma de pago que prefiero.

### Criterios de Aceptación

- El sistema muestra los métodos disponibles.
- El cliente puede seleccionar uno.
- La opción queda registrada.

---

## HU-2.2.1 Pago de Anticipo

**Como** cliente  
**Quiero** realizar el pago del 50% del valor del servicio  
**Para** confirmar mi reserva.

### Criterios de Aceptación

- El sistema calcula el 50% del valor.
- Permite registrar el pago.
- La reserva queda confirmada.

---

## HU-2.2.2 Consulta de Saldo Pendiente

**Como** cliente  
**Quiero** conocer el valor que queda pendiente después del anticipo  
**Para** saber cuánto debo pagar posteriormente.

### Criterios de Aceptación

- El sistema muestra el valor total.
- Muestra el anticipo pagado.
- Calcula automáticamente el saldo pendiente.

---

## HU-2.3.1 Aplicar Código de Descuento

**Como** cliente  
**Quiero** ingresar un código de descuento  
**Para** obtener el beneficio correspondiente en el valor de mi reserva.

### Criterios de Aceptación

- El sistema valida el código.
- Aplica el descuento cuando es válido.
- Informa cuando el código no es válido.

---

## HU-2.4.1 Confirmación de Pago

**Como** cliente  
**Quiero** recibir la confirmación de mi pago  
**Para** verificar que el sistema registró correctamente la transacción.

### Criterios de Aceptación

- Se genera un comprobante de pago.
- Se actualiza el estado de la reserva.
- Se registra la transacción.

---

## HU-2.5.1 Reprogramación de Cita

**Como** cliente  
**Quiero** solicitar la reprogramación de mi cita con al menos 24 horas de anticipación  
**Para** poder cambiar la fecha o el horario de mi reserva.

### Criterios de Aceptación

- Solo permite reprogramar con 24 horas de anticipación.
- Se muestran horarios disponibles.
- La nueva cita queda registrada.

---

## HU-2.5.2 Consulta de Políticas de Cancelación

**Como** cliente  
**Quiero** conocer las condiciones de cancelación y devolución  
**Para** saber qué sucede con mi anticipo si cancelo la cita.

### Criterios de Aceptación

- Las políticas se muestran claramente.
- El usuario puede consultarlas antes de cancelar.
- La información es accesible en cualquier momento.

---

## HU-2.5.3 Consulta de Valor a Devolver

**Como** cliente  
**Quiero** conocer el valor que puedo recibir en caso de cancelación  
**Para** saber si tengo derecho a devolución del anticipo según las condiciones establecidas.

### Criterios de Aceptación

- El sistema calcula el valor de devolución.
- Aplica las políticas definidas.
- Muestra el resultado al usuario.

---