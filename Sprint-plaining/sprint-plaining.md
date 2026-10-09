# Sprint Planning

## Nombre del Sprint

**Sprint 1: Modelado del Dominio, Persistencia de Datos y Preparación de la Interfaz**

---

## Objetivo del Sprint

Construir la base estructural de la aplicación mediante la creación de las clases del dominio, la implementación de la persistencia local utilizando LocalStorage y la preparación del controlador de interfaz para futuras integraciones.

---

## Duración

**2 semanas**

---

## Equipo de Desarrollo

### Integrante 1 - Tifanny M. Arroyave
**Rama:** `feature/modelos-uml`

**Responsabilidades:**

- Diseñar e implementar las clases del dominio.
- Crear la estructura de los modelos del sistema.
- Garantizar la correcta representación de las entidades del negocio.

**Entregable:**

- Archivo `models.js`

---

### Integrante 2 - Santiago Restrepo G.
**Rama:** `feature/local-storage`

**Responsabilidades:**

- Implementar la persistencia de datos mediante LocalStorage.
- Desarrollar los métodos para almacenar y recuperar información.
- Asegurar la disponibilidad de los datos durante la ejecución de la aplicación.

**Entregable:**

- Archivo `Datos.js`

---

### Integrante 3 - Jefersson S. Restrepo
**Rama:** `feature/controlador-ui o mi-primera-rama-formulario-pago`

**Responsabilidades:**

- Crear la estructura inicial del controlador de la aplicación.
- Preparar la captura de eventos del DOM.
- Definir la base para la integración del carrito y de los módulos desarrollados por los demás integrantes.

**Entregable:**

- Archivo `java.js y actualizacion de index.html`

---

## Historias de Usuario Seleccionadas

### HU-01

**Como** sistema,  
**quiero** contar con clases que representen los servicios, clientes, pagos y reservas,  
**para** gestionar adecuadamente la información del negocio.

---

### HU-02

**Como** usuario,  
**quiero** que la información se almacene localmente,  
**para** conservar los datos durante el uso de la aplicación.

---

### HU-03

**Como** usuario,  
**quiero** interactuar con una interfaz preparada para gestionar eventos y futuras funcionalidades del carrito de servicios,  
**para** facilitar la interacción con la aplicación.

---

## Tareas Planificadas

### Integrante 1 - Modelos UML


- Crear rama `feature/modelos-uml`.
- Crear archivo `models.js`.
- Implementar clase `Servicio`.
- Implementar clase `Cliente`.
- Implementar clase `Pago`.
- Implementar clase `Reserva`.
- Validar funcionamiento de las clases.
- Realizar commit y push al repositorio.

---

### Integrante 2 - Persistencia LocalStorage

- Crear rama `feature/local-storage`.
- Crear archivo `Datos.js`.
- Implementar clase `GestorAlmacenamiento`.
- Desarrollar método para guardar datos.
- Desarrollar método para consultar datos.
- Desarrollar método para eliminar datos.
- Realizar pruebas de persistencia.
- Realizar commit y push al repositorio.

---

### Integrante 3 - Controlador de Interfaz

- Crear rama `feature/controlador-ui o mi-primera-rama-formulario-pago`.
- Crear archivo `java.js`.
- Implementar clase `AppSpa`.
- Configurar captura de eventos del DOM.
- Preparar integración con los modelos.
- Preparar integración con LocalStorage.
- Realizar pruebas iniciales.
- Realizar commit y push al repositorio.

---

## Criterios de Aceptación

- Las clases de dominio deben estar implementadas correctamente.
- La persistencia mediante LocalStorage debe funcionar sin errores.
- La estructura inicial del controlador debe permitir futuras integraciones.
- Los entregables deben estar almacenados en sus respectivas ramas.
- El código debe ser integrado al repositorio mediante Pull Requests.

---

## Resultado Esperado

Al finalizar el Sprint 1 se espera contar con:

- Una estructura de modelos funcional en `models.js`.
- Un sistema de persistencia local implementado en `Datos.js`.
- Un controlador base desarrollado en `java.js`.
- Una arquitectura modular preparada para la integración de funcionalidades en los siguientes sprints.