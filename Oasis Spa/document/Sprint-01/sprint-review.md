# Sprint Review - Sprint 01

## Información General

**Sprint:** Sprint 01 – Modelado del Dominio, Persistencia de Datos y Preparación de la Interfaz

**Duración:** 2 semanas

**Objetivo del Sprint:**

Desarrollar la estructura base de la aplicación mediante la implementación de las clases del modelo de negocio, la persistencia de datos con LocalStorage y la preparación del controlador de interfaz para futuras integraciones.

---

## Historias de Usuario Completadas

### ✅ HU-01: Implementar Modelo de Dominio

**Responsable:** Integrante 1 - Tifanny M. Arroyave

#### Resultado

Se elaboró correctamente el archivo `models.js`, donde se definieron las entidades principales del sistema y sus relaciones.

El diagrama UML incluyó las siguientes clases:

- Servicio
- Cliente
- Pago
- Reserva

Además, se identificaron los atributos y asociaciones necesarias para representar la lógica del negocio, permitiendo establecer una base sólida para el desarrollo posterior del archivo `models.js`.

El documento UML sirvió como guía para la implementación de la estructura del sistema y facilitó la organización del trabajo durante el Sprint.
---

### ✅ HU-02: Implementar Persistencia LocalStorage

**Responsable:** Integrante 2 - Santiago Restrepo

#### Resultado

Se desarrolló el archivo `Datos.js`, incorporando la clase `GestorAlmacenamiento` con funcionalidades para:

- Guardar información.
- Recuperar información almacenada.
- Eliminar registros.
- Gestionar la persistencia de datos mediante LocalStorage.

Esto permite mantener la información disponible durante el uso de la aplicación.

---

### ✅ HU-03: Preparar Controlador de Interfaz

**Responsable:** Integrante 3 - Jefersson S. Restrepo

#### Resultado

Se desarrolló el archivo `java.js`, implementando la estructura inicial de la clase `AppSpa`.

Se configuró:

- La captura básica de eventos del DOM.
- La estructura del controlador principal.
- La preparación para integrar el carrito de servicios.
- La conexión futura con los modelos y el almacenamiento local.

---

## Incremento Entregado

Al finalizar el Sprint 01 se obtuvo:

- ✅ Archivo `model.js` con las entidades del negocio.
- ✅ Archivo `Datos.js` para la gestión de almacenamiento local.
- ✅ Archivo `Java.js` con la estructura inicial del controlador de interfaz.
- ✅ Arquitectura modular distribuida en ramas independientes.
- ✅ Componentes preparados para su integración en los siguientes sprints.

---

## Demostración Realizada

Durante la revisión del Sprint se presentaron los siguientes avances:

- Creación e instanciación de las clases de dominio.
- Pruebas de almacenamiento y recuperación de datos utilizando LocalStorage.
- Estructura funcional de la clase `AppSpa`.
- Organización del proyecto mediante ramas Git para trabajo colaborativo.
- Integración inicial de los componentes desarrollados por cada integrante.

---

## Retroalimentación del Product Owner

### Aspectos Positivos

- Correcta separación de responsabilidades entre los integrantes.
- Código organizado de forma modular.
- Uso adecuado de ramas para el desarrollo colaborativo.
- Funcionalidades entregadas dentro del alcance definido para el Sprint.

### Oportunidades de Mejora

- Incorporar validaciones en los modelos de negocio.
- Mejorar el manejo de errores en LocalStorage.
- Implementar completamente la lógica del carrito de servicios.
- Integrar los módulos desarrollados en una única interfaz funcional.
- Optimizar la experiencia de usuario durante la interacción con la aplicación.

---

## Objetivos para el Próximo Sprint

- Integrar los modelos con la interfaz de usuario.
- Implementar completamente el carrito de servicios.
- Conectar la persistencia de datos con las funcionalidades del sistema.
- Desarrollar nuevas funcionalidades orientadas al usuario final.
- Realizar pruebas integrales de funcionamiento.

---

## Conclusión

El Sprint 01 fue completado exitosamente, cumpliendo los objetivos definidos en la planificación. Los tres integrantes entregaron los componentes asignados (`model.js`, `Datos.js` y `Java.js`), dejando preparada la arquitectura base del proyecto para continuar con el desarrollo e integración de funcionalidades en los siguientes sprints.