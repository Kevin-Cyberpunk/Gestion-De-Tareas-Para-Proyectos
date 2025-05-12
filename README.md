# 📋 Sistema de Gestión de Tareas

Este repositorio contiene el diseño e implementación de un sistema completo de gestión de tareas para proyectos colaborativos. Está enfocado en facilitar la organización del trabajo en equipo mediante la asignación de usuarios, estados, prioridades, entregables, revisiones y seguimiento histórico.

## 🧩 Características del sistema

- Gestión de **usuarios** con roles jerárquicos (Administrador, Manager, etc.)
- Organización de **proyectos** con estados dinámicos.
- Creación y seguimiento de **tareas** y **subtareas**.
- Asignación de **etiquetas**, **categorías** y **prioridades** a tareas.
- Control de **entregables** y proceso de **revisión**.
- Sistema de **archivos adjuntos**, **comentarios** y **notificaciones**.
- Registro de **historial de cambios** para trazabilidad.

## 🗃️ Modelo de Base de Datos

El modelo de datos está altamente normalizado y compuesto por múltiples entidades interrelacionadas, entre ellas:

- **Usuarios, Roles**
- **Proyectos, Estados**
- **Tareas, Subtareas**
- **Categorías, Prioridades, Etiquetas**
- **Entregables, Revisiones**
- **Archivos, Comentarios, Historial, Notificaciones**

Se incluyen relaciones como:

- Asignación de usuarios a proyectos y tareas
- Estados dinámicos para tareas, proyectos, entregables y revisiones
- Múltiples archivos por tarea y entregable
- Comentarios por usuario por tarea
- Historial por cada modificación

Puedes ver una descripción detallada de las relaciones en el archivo [`ModeloERD.pdf`](./ModeloERD.pdf).



