# Sprint Backlog - Sprint 01

## Objetivo del Sprint

Desarrollar la estructura base de la aplicación mediante la implementación de los modelos de dominio, la persistencia de datos con LocalStorage y la preparación del controlador de interfaz.

---

## HU-01: Implementar Modelo de Dominio

**Responsable:** Integrante 1 - Tifanny M. Arroyave

### Descripción

Como sistema, quiero contar con clases que representen los servicios, clientes, pagos y reservas para gestionar adecuadamente la información del negocio.

### Tareas

- Crear la rama `feature/modelos-uml`.
- Crear el archivo `models.js`.
- Implementar la clase `Servicio`.
- Implementar la clase `Cliente`.
- Implementar la clase `Pago`.
- Implementar la clase `Reserva`.
- Validar la creación de objetos de cada clase.
- Realizar pruebas básicas de funcionamiento.
- Hacer commit y push al repositorio.

### Entregable

- Archivo `models.js`.

---

## HU-02: Implementar Persistencia LocalStorage

**Responsable:** Integrante 2 - Santiago Restrepo G

### Descripción

Como usuario, quiero que la información se almacene localmente para conservar los datos durante el uso de la aplicación.

### Tareas

- Crear la rama `feature/local-storage`.
- Crear el archivo `Datos.js`.
- Implementar la clase `GestorAlmacenamiento`.
- Desarrollar el método para guardar datos.
- Desarrollar el método para obtener datos.
- Desarrollar el método para eliminar datos.
- Realizar pruebas de persistencia.
- Verificar el almacenamiento en LocalStorage.
- Hacer commit y push al repositorio.

### Entregable

- Archivo `Datos.js`.

---

## HU-03: Preparar Controlador de Interfaz

**Responsable:** Integrante 3 - Jefersson S. Restrepo

### Descripción

Como usuario, quiero interactuar con una interfaz preparada para gestionar eventos y futuras funcionalidades del carrito de servicios.

### Tareas

- Crear la rama `feature/controlador-ui o mi-primera-rama-formulario-pago`.
- Crear el archivo `java.js`.
- Implementar la clase `AppSpa`.
- Configurar la captura de eventos del DOM.
- Preparar la integración con los modelos de dominio.
- Preparar la integración con LocalStorage.
- Realizar pruebas iniciales de funcionamiento.
- Hacer commit y push al repositorio.

### Entregable

- Archivo `java.js`.

---

## Resultado Esperado del Sprint

- ✅ Implementación de las clases de dominio en `models.js`.
- ✅ Implementación de la persistencia local en `Datos.js`.
- ✅ Estructura inicial del controlador de interfaz en `Java.js`.
- ✅ Código organizado en ramas independientes para facilitar la integración mediante Pull Requests.
- ✅ Base del proyecto lista para el desarrollo de funcionalidades en los siguientes sprints.