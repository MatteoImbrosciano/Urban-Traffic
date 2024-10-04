# Milestones

## [M0] Milestone 0: Modelado y planificación del problema

- **Objetivo:** Analizar las historias de usuario y definir los requisitos clave del dominio del problema a abordar en el desarrollo del MVP. Organizar los conceptos clave de acuerdo con las necesidades del negocio, utilizando Domain-Driven Design (DDD) como metodología.
- **Entregable:** Un modelado inicial del dominio del problema con los conceptos clave y sus relaciones. Definir las entidades y agregados necesarios para desarrollar el MVP, basado en las historias de usuario.
- **Viabilidad:** El hito se completa cuando el modelado y la planificación del problema son validados por el revisor y comprensibles para el equipo de desarrollo. Las historias de usuario deben estar correctamente alineadas con los conceptos clave del dominio.
- **Historias de Usuario asociadas:** [HU001], [HU002], [HU003].

## [M1] Milestones 1: Adquisición de los tickets electrónicos

- **Objetivo:** Implementar la funcionalidad que permita al usuario cargar un ticket electrónico y extraer automáticamente los datos de los medicamentos.
- **Entregable:** Código que permita cargar un ticket electrónico y obtener información como el nombre del medicamento, cantidad y fecha de compra.
- **Viabilidad:** El hito se completa cuando el sistema es capaz de cargar exitosamente varios formatos de tickets electrónicos y extraer correctamente la información solicitada.
- **Historias de Usuario asociadas:** [HU001].

## [M2] Milestones 2: Actualización automática del inventario

- **Objetivo:** Implementar la funcionalidad que actualiza automáticamente el inventario de los medicamentos cada vez que se carga un ticket electrónico.
- **Entregable:** Código que permita la actualización automática del inventario en función de los datos extraídos de los tickets electrónicos.
- **Viabilidad:** El hito se completa cuando el sistema actualiza correctamente el inventario con la información extraída y puede ser verificado mediante pruebas de aceptación.
- **Historias de Usuario asociadas:** [HU002].

## [M3] Milestones 3: Sistema de notificaciones inteligentes

- **Objetivo:** Implementar un sistema de notificaciones que avise al usuario cuando el stock de un medicamento esté a punto de agotarse o cuando sea necesario comprar un nuevo lote de medicamentos.
- **Entregable:** Código que permita el envío de notificaciones inteligentes al usuario.
- **Viabilidad:** El hito se completa cuando el sistema envía correctamente notificaciones basadas en el nivel de stock de los medicamentos en inventario.
- **Historias de Usuario asociadas:** [HU003].

## [M4] Milestones 4: Interfaz de visualización del inventario

- **Objetivo:** Implementar un panel de control (dashboard) que permita al usuario visualizar el inventario actualizado de los medicamentos, incluyendo el nombre, la cantidad y la fecha de compra.
- **Entregable:** Código que permita la visualización del inventario en una interfaz fácil de usar.
- **Viabilidad:** El hito se completa cuando el inventario es visible en un formato claro y fácil de interpretar para el usuario.
- **Historias de Usuario asociadas:** [HU004].
