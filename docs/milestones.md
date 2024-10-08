# Milestones 

## [M0] Milestone 0: Modelado y planificación del dominio del problema  
**Objetivo:** Analizar las historias de usuario e identificar los conceptos clave necesarios para abordar el problema en el desarrollo del MVP. Estructurar los conceptos principales basados en las necesidades y expectativas de los usuarios, utilizando la metodología Domain-Driven Design (DDD).  
**Entregable:** Un modelo inicial del dominio que describa los conceptos clave y sus relaciones, tales como medicamentos, tickets electrónicos, inventario y notificaciones.  
**Factibilidad:** Completado cuando el modelo del dominio ha sido validado por el equipo de desarrollo y las partes interesadas, con un claro alineamiento con las historias de usuario.  
**Historias de Usuario asociadas:** [HU1], [HU2], [HU3].

---

## [M1] Milestone 1: Creación y gestión  del inventario  
**Objetivo:** Crear un sistema que permita la gestión de un inventario de medicamentos, donde el usuario pueda agregar y visualizar los medicamentos manualmente (nombre, cantidad, fecha de compra). Este sistema será la base para futuras iteraciones.  
**Entregable:** Código que permita al usuario gestionar un inventario de medicamentos, con la capacidad de agregar, actualizar y visualizar los datos manualmente.  
**Factibilidad:** Completado cuando el sistema de inventario esté operativo y verificado a través de pruebas funcionales.  
**Historias de Usuario asociadas:** [HU1].

---

## [M2] Milestone 2: Carga de tickets electrónicos y actualización automática del inventario  
**Objetivo:** Implementar una funcionalidad que permita a los usuarios cargar un ticket electrónico (por ejemplo, recibo de farmacia) y actualizar automáticamente el inventario con la información extraída (nombre del medicamento, cantidad, fecha de compra).  
**Entregable:** Código que permita la carga y procesamiento de tickets electrónicos para actualizar el inventario de manera automática.  
**Factibilidad:** Completado cuando el inventario se actualice correctamente utilizando los datos extraídos de los tickets electrónicos, con éxito verificado mediante pruebas de aceptación.  
**Historias de Usuario asociadas:** [HU2].

---

## [M3] Milestone 3: Sistema de notificaciones inteligentes  
**Objetivo:** Implementar un sistema que notifique al usuario cuando las existencias de un medicamento estén a punto de agotarse o cuando sea necesario comprar un nuevo lote de medicamentos. Las notificaciones deben ser configurables según umbrales personalizables por el usuario.  
**Entregable:** Código que permita el envío de notificaciones basadas en los niveles de existencias de los medicamentos y configurables por el usuario.  
**Factibilidad:** Completado cuando el sistema envíe correctamente notificaciones inteligentes, basadas en umbrales predefinidos o personalizados por el usuario, con pruebas de aceptación que validen su funcionamiento.  
**Historias de Usuario asociadas:** [HU3].

---
# Milestones adicionales

## [M4] Milestone 4: Dashboard de visualización del inventario  
**Objetivo:** Implementar un panel de control que permita al usuario visualizar fácilmente el inventario de medicamentos en tiempo real, con información como el nombre del medicamento, la cantidad disponible y la fecha de compra.  
**Entregable:** Código que permita visualizar el inventario en un panel intuitivo y fácil de usar, que ofrezca una visión clara y actualizada de los medicamentos.  
**Factibilidad:** Completado cuando el inventario sea visible de manera clara a través del panel, con retroalimentación positiva de los usuarios en las pruebas de usabilidad.  
**Historias de Usuario asociadas:** [HU4].
