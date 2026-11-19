# Clínica del Dengue · Proyecto 2026

**Seminario de Integración de Desarrollo · CUCEI · Universidad de Guadalajara**

> **Modalidad:** simulación académica de gestión de proyecto. Los 31 hitos T-001 a T-031 están cerrados en GitHub como parte del seguimiento docente; sus estados no acreditan por sí mismos una implementación nueva del software, pruebas reales ni la entrega de evidencias.

## Equipo
- Fernando Emiliano Cadenas Montes
- Sergio René Urzúa Secada
- Giancarlo Rodríguez Madrigal

**Profesor:** JORGE ERNESTO LOPEZ ARCE DELGADO

## Problema
Los brotes de dengue pueden aumentar rápidamente la demanda de atención y recursos. Gestionar pacientes, medicamentos, inventarios y transacciones, por una parte, y analizar escenarios de propagación por otra, suelen ser procesos separados. La dificultad que aborda este proyecto es integrar la información clínica básica con el análisis académico de escenarios, para mejorar la organización y el estudio de posibles condiciones.

## Objetivo general (Actividad 03 - versión revisada)
> Desarrollar e integrar una plataforma en MATLAB para apoyar la gestión clínica básica relacionada con el dengue y el análisis de posibles escenarios de propagación, mediante módulos de administración, simulaciones configurables, almacenamiento de resultados y análisis de tendencias, con el fin de organizar la información y facilitar la preparación y comprensión ante diferentes escenarios.

## Problema y objetivo

**Problema:** La información clínica básica (pacientes, medicamentos e inventario) y el análisis de escenarios de dengue suelen gestionarse por separado. Esta separación dificulta estudiar sus relaciones dentro de una herramienta académica.

**Objetivo verificable:** Plantear una plataforma integrada en MATLAB cuyo MVP permita demostrar cuatro capacidades: registrar datos ficticios, simular escenarios configurables, guardar y recuperar resultados, y analizar tendencias.

**Siguiente paso:** Relacionar las cuatro capacidades del MVP con las tareas y criterios de aceptación del Product Backlog para su evaluación académica.

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

**Demostración del MVP:** registro - simulación - guardado - consulta - análisis, utilizando datos ficticios y evidencias reproducibles.

## Evolución del objetivo (Actividad 03)
**Primera versión:** «Desarrollar una aplicación para una Clínica del Dengue que integre la gestión de pacientes, inventario, medicamentos y transacciones con un simulador configurable y herramientas de análisis, con el fin de organizar la información y estudiar posibles comportamientos de un brote».

**Versión revisada:** el objetivo general transcrito arriba. Se revisó para precisar la integración y el resultado esperado, relacionar explícitamente el proyecto con el problema y clarificar su utilidad. Estos son ajustes **internos del equipo**: todavía no se ha recibido retroalimentación de las actividades 02 y 03.

## GitHub Project (tablero real)

**[Abrir GitHub Project - Clínica del Dengue 2026](https://github.com/users/giancarlo8786-cpu/projects/1/views/1)**. Incluye las 31 tarjetas y los cuatro estados solicitados. Tanto repositorio como Project se encuentran privados; se requiere acceso para que el profesor pueda abrir los enlaces.


## Verificación del MVP

Para evaluar el cumplimiento del objetivo del proyecto, se establecen los siguientes criterios:

- La propuesta contempla el registro de información clínica básica.
- La simulación permite configurar diferentes escenarios de dengue.
- Los resultados pueden almacenarse y consultarse.
- El análisis permite identificar tendencias en los datos simulados.

Estos criterios forman parte de la planificación académica y sirven como referencia para el seguimiento del proyecto.

## Organización y seguimiento académico


- [31 Issues del proyecto](../../issues): tareas con descripción, responsable previsto, prioridad y Definition of Done.
- **31 de 31 Issues del backlog cerrados** (T-001 a T-031). Corresponden a hitos del ejercicio de gestión académica y no certifican por sí mismos la implementación de MATLAB.
- **Ningún Issue abierto:** también están cerradas las Issues individuales #32 y #34; en total, los **33 Issues del repositorio están cerrados**. El cierre de T-029, T-030 y T-031 no equivale por sí solo a verificar sus evidencias.
- [Tablero real de GitHub Projects](https://github.com/users/giancarlo8786-cpu/projects/1/views/1): existe con las cuatro columnas solicitadas. La distribución de su última captura es histórica; **revisar la columna Status de las 31 tarjetas** para que refleje los cierres actuales, dado que GitHub Projects y el estado de los Issues son campos distintos.
- [Backlog](backlog/README.md) con 31 fichas, CSV y JSON.

- Las mejoras individuales del README se fusionaron mediante [PR #33](https://github.com/giancarlo8786-cpu/Clinica-Dengue-2026/pull/33) y [PR #35](https://github.com/giancarlo8786-cpu/Clinica-Dengue-2026/pull/35); sus Issues #32 y #34 están cerradas.

## Evidencias de la asignatura

- [Actividad 02](docs/ACTIVIDAD_02.md) · [Actividad 03](docs/ACTIVIDAD_03.md).
- [Estado, alcance de la simulación y evidencias](docs/ESTADO_Y_EVIDENCIAS.md).
- [Exposición de cinco minutos](docs/EXPOSICION_5_MINUTOS.md).
- [Organización del tablero GitHub Projects](docs/ORGANIZACION_TABLERO.md).
- [Plantilla de minuta](docs/PLANTILLA_MINUTA.md) y [retroalimentación pendiente](docs/RETROALIMENTACION.md).

El curso se centra en el **planteamiento, gestión y defensa del proyecto**, por lo que se documenta una evolución simulada del backlog. No deben presentarse como reales pruebas, reuniones o desarrollos que no se hayan realizado.


## Comprobaciones de entrega (independientes del estado Closed)

- Verificar que la captura real del tablero se haya adjuntado en Classroom (y, si se desea, al repositorio).
- Confirmar que el profesor puede abrir **el repositorio y el Project** mediante los permisos correspondientes.
- Comprobar que las dos reuniones del equipo cuentan con **minutas y evidencias auténticas** accesibles; las plantillas disponibles no prueban por sí solas las reuniones.
- Confirmar las cuentas GitHub de los demás integrantes solo si se desean asignaciones directas; sus responsables previstos ya están documentados.
- Registrar o enlazar la retroalimentación del profesor **cuando efectivamente se haya recibido**; cerrar T-031 no demuestra por sí mismo que esa retroalimentación exista.

