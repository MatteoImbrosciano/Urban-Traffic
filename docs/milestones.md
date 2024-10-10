# Gestión de Medicamentos - Hitos

## **[M0] Milestone 0: Modelado y planificación del dominio del problema**
**Objetivo**:  
Analizar las historias de los usuarios e identificar los conceptos clave necesarios para abordar el problema en el desarrollo del MVP. Estructurar los conceptos principales basados en las necesidades y expectativas de los usuarios, utilizando la metodología de Diseño Guiado por el Dominio (DDD).

**Entregable**:  
- Un modelo de dominio que describa los conceptos clave y sus relaciones, tales como medicamentos, tickets electrónicos (soportando varios formatos como PDF, XML) 
  y el inventario.
  
**Factibilidad**:  
Completado cuando el modelo de dominio haya sido validado por el equipo de desarrollo y las partes interesadas, con un claro alineamiento con las historias de los usuarios y los requisitos para la gestión de tickets.

**Historias de usuario asociadas**:  
[HU1], [HU2], [HU3].

---

## **[M1] Milestone 1: Gestión completa del inventario**
**Objetivo**:  
Implementar un sistema que permita mantener un registro completo del inventario de medicamentos, estableciendo un intervalo de existencias mínimas y máximas para cada medicamento, además de otros datos relevantes como la fecha de caducidad y el ritmo de uso. El sistema será capaz de monitorear automáticamente las existencias y enviar alertas cuando estas caigan por debajo del nivel mínimo o superen el máximo.

**Entregable**:  
- Código que permita mantener un registro completo del inventario de medicamentos, con la posibilidad de agregar, actualizar y visualizar manualmente la 
  información.
- Función que permita establecer niveles de existencias mínimas y máximas para cada medicamento.
- Monitoreo de las fechas de caducidad.

**Factibilidad**:  
Completado cuando el sistema permita mantener un inventario completo y estructurado, monitoree automáticamente las existencias y las fechas de caducidad. Verificado mediante pruebas funcionales de aceptación.

**Historias de usuario asociadas**:  
[HU1], [HU3].

---

## **[M2] Milestone 2: Carga de tickets electrónicos y actualización automática del inventario**
**Objetivo**:  
Implementar una funcionalidad que permita a los usuarios cargar tickets electrónicos (como recibos de la farmacia) y actualizar automáticamente el inventario con la información extraída (nombre del medicamento, cantidad, fecha de compra). Soportar varios formatos de tickets (PDF, XML).

**Entregable**:  
- Sistema que permita la carga y el reconocimiento de tickets electrónicos en diferentes formatos (PDF, XML).
- Actualización automática del inventario con la información extraída de los tickets.

**Factibilidad**:  
Completado cuando el inventario se actualice automáticamente de manera correcta utilizando los datos extraídos de los tickets electrónicos, verificado mediante pruebas funcionales de aceptación.

**Historias de usuario asociadas**:  
[HU2].

---

## **[M3] Milestone 3: Sistema de notificaciones inteligentes**
**Objetivo**:  
Implementar un sistema de notificaciones que alerte al usuario sobre diferentes aspectos del inventario de medicamentos. Las notificaciones incluirán alertas sobre:
- Cuando un medicamento esté por debajo de un nivel mínimo de existencias configurado por el usuario.
- Cuando un medicamento esté por caducar (según la fecha de caducidad).

**Entregable**:  
- Código que permita el envío de notificaciones inteligentes y configurables basadas en existencias mínimas y fechas de caducidad inminentes.

**Factibilidad**:  
Completado cuando el sistema envíe correctamente notificaciones basadas en criterios configurables y personalizables por el usuario, verificado mediante pruebas de aceptación.

**Historias de usuario asociadas**:  
[HU3].

---
# Milestones adicionales

## **[M4] Milestone 4: Panel de visualización del inventario**
**Objetivo**:  
Implementar un panel de control interactivo que permita al usuario visualizar el inventario de medicamentos en tiempo real, con información como el nombre del medicamento, la cantidad disponible, la fecha de compra y la proximidad de la caducidad.

**Entregable**:  
- Panel interactivo que visualice el inventario en tiempo real con información completa (nombre, cantidad, fecha de compra, caducidad).

**Factibilidad**:  
Completado cuando el inventario sea visible de manera clara a través del panel, con comentarios positivos de los usuarios durante las pruebas de usabilidad y pruebas funcionales.

**Historias de usuario asociadas**:  
[HU4].
