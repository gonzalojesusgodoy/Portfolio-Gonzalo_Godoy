# Plan de Pruebas y Testing Exploratorio | Módulo de Registro (Sign-Up)

Proyecto práctico de **Software Testing**, enfocado en la evaluación funcional del flujo de registro de usuarios (*Sign-Up*) de una aplicación web.

El trabajo contempla el diseño y ejecución de casos de prueba, la aplicación de técnicas de testing de caja negra, pruebas exploratorias y la documentación de defectos y oportunidades de mejora.

## Objetivo y alcance

Evaluar el funcionamiento del formulario de registro, prestando especial atención a las validaciones de entrada, el manejo de errores y el comportamiento del sistema ante diferentes escenarios.

El análisis busca identificar posibles defectos funcionales y aspectos de usabilidad que puedan afectar la experiencia del usuario.

**Características del proyecto:**

| Aspecto | Descripción |
|---|---|
| Módulo evaluado | Registro de usuarios (Sign-Up) |
| Enfoque | Testing de caja negra |
| Tipos de pruebas | Funcionales, negativas, de límites y exploratorias |
| Técnicas | Partición de equivalencia y análisis de valores límite (BVA) |
| Entorno contemplado | Aplicación web |
| Navegadores contemplados | Chrome y Firefox |
| Metodología exploratoria | Session-Based Test Management (SBTM) |

## Cobertura y escenarios evaluados

### 1. Validaciones de campos obligatorios

- Respuesta del sistema ante campos vacíos o incompletos.
- Manejo de espacios en blanco.
- Validación de caracteres no permitidos.

### 2. Formato y consistencia de datos

- Validación del formato de direcciones de correo electrónico.
- Evaluación de formatos incorrectos y dominios inexistentes.
- Verificación de políticas de seguridad de contraseñas.
- Evaluación de longitud mínima y máxima.
- Validación de combinación alfanumérica y caracteres especiales.
- Comprobación de coincidencia entre contraseña y confirmación.

### 3. Casos límite y negativos

- Ingreso de caracteres especiales y scripts simples para evaluar el comportamiento de los campos.
- Intentos de registro con direcciones de correo previamente registradas.
- Evaluación de respuestas ante datos inválidos o inesperados.

### 4. Testing exploratorio y usabilidad

- Navegación mediante teclado (`Tab`).
- Verificación del foco visual.
- Envío del formulario mediante `Enter`.
- Evaluación de la claridad y visibilidad de los mensajes de error.
- Análisis del feedback proporcionado al usuario.

## Metodología y ciclo de trabajo

El proceso de testing se organizó en las siguientes etapas:

**1. Análisis de requisitos**

Identificación de los criterios de aceptación y comportamientos esperados para el módulo de registro.

**2. Diseño de casos de prueba**

Elaboración de casos de prueba estructurados mediante:

- Precondiciones.
- Pasos de ejecución.
- Datos de prueba (*Test Data*).
- Resultados esperados.

**3. Ejecución y registro**

Ejecución de los escenarios y comparación entre los resultados esperados y los obtenidos.

**4. Gestión de defectos**

Documentación de los errores identificados mediante reportes que contemplan:

- Descripción del defecto.
- Pasos para reproducirlo.
- Resultado esperado y resultado actual.
- Severidad y prioridad.
- Evidencias correspondientes.

**5. Identificación de oportunidades de mejora**

Análisis de aspectos de usabilidad y experiencia del usuario, diferenciando las sugerencias de mejora de los defectos funcionales.

## Documentación y entregables

El repositorio contiene los siguientes materiales:

| Archivo | Descripción |
|---|---|
| `Plan de pruebas.md` | Planificación, alcance y estrategia de testing. |
| `Casos de pruebas.md` | Diseño y documentación de escenarios de prueba. |
| `Test Exploratorio.md` | Registro de las actividades de testing exploratorio. |
| `Reporte de errores.md` | Documentación de defectos identificados. |
| `Evidencias de errores.md` | Evidencias asociadas a los defectos reportados. |
| `Reporte de errores "Test exploratorio".md` | Reporte de hallazgos del testing exploratorio. |
| `Evidencias de errores "Test Exploratorio".md` | Evidencias de los hallazgos exploratorios. |
| `Reporte de mejoras.md` | Registro de oportunidades de mejora identificadas. |

## Resultados y aprendizajes

La práctica permitió trabajar sobre distintos aspectos del proceso de QA Manual:

- **Diseño de pruebas:** aplicación de técnicas de caja negra para construir escenarios con diferentes condiciones de entrada.
- **Documentación de defectos:** importancia de registrar los errores con información clara y pasos reproducibles.
- **Diferenciación de hallazgos:** distinción entre defectos funcionales y oportunidades de mejora relacionadas con la experiencia del usuario.
- **Trazabilidad:** organización de la documentación para relacionar los escenarios evaluados con los resultados y evidencias obtenidas.

## Reflexión final

Este proyecto permitió profundizar en la importancia de planificar y ejecutar pruebas de manera estructurada, combinando escenarios previamente definidos con exploración manual.

También reforzó la necesidad de documentar correctamente los hallazgos, aportar evidencias y analizar el comportamiento de una aplicación desde la perspectiva funcional y del usuario.

La experiencia representa una práctica de aplicación de conocimientos de QA Manual y una oportunidad para seguir desarrollando habilidades en análisis, diseño de pruebas y gestión de defectos.
