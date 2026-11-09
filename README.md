# Clínica del Dengue · Proyecto 2026

**Seminario de Integración de Desarrollo · CUCEI · Universidad de Guadalajara**

> **Estado:** documentación y backlog en construcción. Las funcionalidades descritas en el alcance no se consideran implementadas sin código y pruebas verificables.

## Equipo
- Fernando Emiliano Cadenas Montes
- Sergio René Urzúa Secada
- Giancarlo Rodríguez Madrigal

**Profesor:** JORGE ERNESTO LOPEZ ARCE DELGADO

## Problema
Los brotes de dengue pueden aumentar rápidamente la demanda de atención y recursos. Gestionar pacientes, medicamentos, inventarios y transacciones, por una parte, y analizar escenarios de propagación por otra, suelen ser procesos separados. La dificultad que aborda este proyecto es integrar la información clínica básica con el análisis académico de escenarios, para mejorar la organización y el estudio de posibles condiciones.

## Objetivo general (Actividad 03 — versión revisada)
> Desarrollar e integrar una plataforma en MATLAB para apoyar la gestión clínica básica relacionada con el dengue y el análisis de posibles escenarios de propagación, mediante módulos de administración, simulaciones configurables, almacenamiento de resultados y análisis de tendencias, con el fin de organizar la información y facilitar la preparación y comprensión ante diferentes escenarios.

### Objetivos particulares
1. **Analizar** los procesos de gestión clínica y las variables necesarias para la simulación del dengue, con el fin de definir los datos, reglas y relaciones que deberá manejar la plataforma.
2. **Diseñar** la estructura funcional y el flujo de información de la Clínica del Dengue, integrando los módulos clínicos con el registro, consulta y análisis de simulaciones.
3. **Implementar e integrar** los módulos de gestión clínica, simulación configurable, almacenamiento de resultados y análisis de tendencias mediante regresión lineal en una aplicación funcional en MATLAB.
4. **Validar** el funcionamiento e integración de la plataforma mediante pruebas de los módulos y de los flujos principales, verificando la persistencia de datos, las validaciones y la generación correcta de resultados de simulación y análisis.

## Alcance previsto
- Administración básica: pacientes, inventario de medicamentos, cálculo académico de dosis y transacciones.
- Dashboard con indicadores operativos.
- Simulación 2D configurable de dengue (humanos, mosquitos y duración).
- Almacenamiento, consulta y comparación de resultados.
- Análisis de tendencias mediante regresión lineal.
- Pruebas, validación, documentación y gestión del trabajo.

**Esta lista describe el alcance; no constituye una declaración de funciones implementadas.**

## Fuera de alcance
- Diagnóstico, tratamientos ni prescripciones para pacientes reales.
- Pronóstico epidemiológico o médico validado con datos sanitarios reales.
- Despliegue hospitalario de producción ni sustitución de expedientes clínicos oficiales.
- Datos personales reales de pacientes para demostraciones.

## MVP
1. Registrar y consultar información clínica básica.
2. Configurar y ejecutar una simulación con humanos, mosquitos y duración modificables.
3. Guardar los resultados y consultarlos posteriormente.
4. Visualizar los resultados y analizar tendencias.

**Demostración del MVP:** registro → simulación → guardado → consulta → análisis, utilizando datos ficticios y evidencias reproducibles.

## Evolución del objetivo (Actividad 03)
**Primera versión:** «Desarrollar una aplicación para una Clínica del Dengue que integre la gestión de pacientes, inventario, medicamentos y transacciones con un simulador configurable y herramientas de análisis, con el fin de organizar la información y estudiar posibles comportamientos de un brote».

**Versión revisada:** el objetivo general transcrito arriba. Se revisó para precisar la integración y el resultado esperado, relacionar explícitamente el proyecto con el problema y clarificar su utilidad. Estos son ajustes **internos del equipo**: todavía no se ha recibido retroalimentación de las actividades 02 y 03.

## Organización y seguimiento
- [Issues del proyecto](../../issues): tareas priorizadas con responsable previsto y Definition of Done. Todas comienzan abiertas, a la espera de pruebas que respalden cierres.
- Estados requeridos del tablero: **Backlog · To Do · In Progress · Done**.
- Primer ciclo sugerido: repositorio y documentación → estructura y persistencia → organización del tablero → módulos clínicos y simulación. Ajustar al progreso comprobado.
- Cada cierre requiere criterios de aceptación y evidencia vinculada.
- [Actividad 02](docs/ACTIVIDAD_02.md) · [Actividad 03](docs/ACTIVIDAD_03.md) · [Estado y evidencias](docs/ESTADO_Y_EVIDENCIAS.md) · [Exposición de 5 minutos](docs/EXPOSICION_5_MINUTOS.md).
- [Organización del tablero](docs/ORGANIZACION_TABLERO.md) y [plantilla de minuta](docs/PLANTILLA_MINUTA.md).

## Procedencia y límites
Proyecto reformulado en **septiembre–octubre de 2026**, a partir de la Clínica del Dengue desarrollada en MATLAB durante 2025. Ni las funcionalidades ni las pruebas de 2025 cuentan automáticamente como avances verificados en 2026.

El repositorio anterior [Proyecto-Equipo](https://github.com/fernandocadenas8633/Proyecto-Equipo) tenía 28 Issues (6 cerrados y 22 abiertos) al revisarlo el 9-nov-2026, pero no tenía código publicado. Aquí se conserva la planificación y se agregan tareas para evidencias, demostración y retroalimentación, **sin copiar estados Done no verificados**.

**Pendiente:** publicar el código MATLAB real si el equipo autoriza su distribución, adjuntar dos evidencias de reunión con minuta, verificar el tablero GitHub Projects y registrar observaciones reales del profesor.
