# ***Métricas***

## Cycle Time

La métrica seleccionada fue **Cycle Time**, utilizada para analizar cuánto tiempo tarda una tarea desde que comienza su ejecución hasta que se considera terminada.

Debido a que el proyecto corresponde a una simulación, los valores utilizados representan un escenario simulado de ejecución.

“El Cycle Time permite conocer cuánto tiempo tarda una tarea desde que comienza a trabajarse hasta que finaliza. Esta métrica nos permite analizar si existen demoras durante la ejecución de las tareas. Un Cycle Time elevado puede indicar que existen dificultades, esperas, bloqueos o que las tareas son demasiado grandes. En nuestro tablero, observar el recorrido de las tareas nos permite identificar posibles puntos de espera y analizar dónde se podría mejorar el flujo de trabajo”

| **Tarea**                 | **Estimación** | **Cycle Time simulado** |
| ------------------------- | -------------- | ----------------------- |
| T1 — Definir estructura   | 2 h            | 2 h                     |
| T2 — Preparar información | 4 h            | 5 h                     |
| T3 — Documentar pruebas   | 6 h            | 8 h                     |
| T4 — Incorporar evidencia | 4 h            | 4 h                     |
| T5 — Construir / maquetar | 8 h            | 10 h                    |
| **Total**                 | **24 h**       | **29 h**                |

El **Cycle Time total simulado fue de 29 horas**, con un promedio de:

**29 ÷ 5 = 5,8 horas por tarea.**

### Análisis

Al comparar las estimaciones iniciales con el Cycle Time simulado, se observa que algunas tareas requirieron más tiempo del inicialmente previsto.

Las principales diferencias se produjeron en:

- **T2**, que requirió una revisión adicional.
- **T3**, que presentó una demora relacionada con información faltante.
- **T5**, que necesitó ajustes durante la revisión.

La métrica permitió identificar que las etapas de preparación de información y revisión pueden generar demoras cuando existen dependencias, información incompleta o modificaciones posteriores.
