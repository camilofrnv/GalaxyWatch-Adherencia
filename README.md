# GalaxyWatch Adherencia

## Descripción del proyecto

Proyecto académico desarrollado en el marco de la colaboración entre Duoc UC y Samsung.

El objetivo es desarrollar una aplicación para Galaxy Watch orientada a mejorar la adherencia a tratamientos farmacológicos mediante recordatorios, confirmación de tomas y registro de medicamentos.

El prototipo está orientado a dispositivos Galaxy Watch compatibles con Wear OS.

## Tecnologías utilizadas

- **Android Studio:** entorno de desarrollo.
- **Kotlin:** lenguaje de programación.
- **Wear OS:** plataforma para relojes inteligentes.
- **Jetpack Compose:** desarrollo de interfaces.
- **Gradle:** gestión de compilación y dependencias.
- **Git y GitHub:** control de versiones.

## Estructura del proyecto

- `mobile/`: aplicación Android para teléfonos.
- `wear/`: aplicación Wear OS para el reloj.
- `gradle/`: configuración de herramientas de compilación.
- `settings.gradle.kts`: configuración de los módulos del proyecto.

## Configuración del entorno

Se realizó la configuración inicial de Android Studio y el SDK de Android.

Se creó un emulador Wear OS Small Round y se comprobó el funcionamiento de la aplicación de ejemplo, que muestra el mensaje "Hello, Android!" y botones de prueba.

La aplicación se ejecutó correctamente en el emulador.

## Evaluación de Samsung Health SDK

Se revisaron las siguientes tecnologías:

**Samsung Health Data SDK**

Permite consultar datos compatibles almacenados en Samsung Health desde una aplicación Android.

Durante la preparación del entorno se intentó acceder a su descarga desde Samsung Developers. Sin embargo, el portal presentó el error `401 Unauthorized`, impidiendo completar la descarga e integración.

**Samsung Health Sensor SDK**

Permite acceder a determinados sensores de dispositivos Galaxy Watch compatibles. Se identificó como una alternativa para futuras funcionalidades relacionadas con mediciones fisiológicas, pero no se integró en esta etapa.

**Health Connect**

Se identificó como una alternativa para consultar datos de salud compatibles mediante permisos del usuario. Su integración queda pendiente de implementación y pruebas.

## Estado del desarrollo

- [x] Crear el proyecto Android Studio.
- [x] Configurar el entorno Kotlin y Wear OS.
- [x] Crear los módulos de teléfono y reloj.
- [x] Configurar el emulador Wear OS.
- [x] Ejecutar la aplicación de ejemplo.
- [x] Inicializar Git y crear una rama de trabajo.
- [x] Publicar el proyecto en GitHub.
- [x] Evaluar las opciones de integración con Samsung Health.
- [ ] Integrar un SDK o mecanismo de acceso a datos de salud.
- [ ] Implementar recordatorios de medicamentos.
- [ ] Implementar confirmación y registro de tomas.
- [ ] Calcular indicadores de adherencia.

## Limitaciones actuales

La aplicación se encuentra en una etapa inicial de configuración.

La ejecución en el emulador confirma el funcionamiento básico de Wear OS, pero no demuestra compatibilidad con los servicios propietarios de Samsung Health.

Será necesario realizar pruebas adicionales en dispositivos físicos compatibles.

La aplicación todavía no está destinada al uso clínico ni permite verificar la ingesta real de medicamentos.

## Control de versiones

**Rama de desarrollo:** `feature/configuracion-inicial`

El desarrollo inicial se mantiene en una rama independiente para facilitar la revisión del equipo y la integración posterior de cambios.