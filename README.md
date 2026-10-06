# ForestGuard

## Pipeline de datos para entrenamiento de modelos de aprendizaje automático

Proyecto integrador de sexto semestre orientado a diseñar, implementar y validar un pipeline que obtenga datos ambientales desde APIs, realice procesos ETL en Google Colab, compare alternativas de procesamiento y entrene modelos de Machine Learning para estimar el nivel de riesgo de incendios forestales. Los resultados se presentarán mediante visualizaciones y un dashboard, junto con una evaluación de seguridad y una propuesta de valor de negocio.

## Autores y roles Scrum

| Integrante | Rol | Responsabilidad |
| --- | --- | --- |
| Jose Villavicencio | Scrum Master | Facilitar Scrum, organizar seguimiento y resolver impedimentos. |
| Cesar Garnica | Product Owner | Definir visión, priorizar backlog y revisar criterios de aceptación. |
| Sebastian Haro | Equipo de Desarrollo | Diseñar, implementar, probar y documentar el pipeline. |

## Problema y objetivo

La preparación manual y fragmentada de datos dificulta reproducir análisis, comparar modelos y controlar riesgos en servicios externos. El objetivo es integrar adquisición, preparación, modelamiento y evaluación de seguridad en un flujo reproducible que apoye decisiones basadas en datos.

## Alcance del producto

- Consumo de al menos una API abierta y ETL en Google Colab.
- Limpieza, transformación, almacenamiento y validación de calidad.
- Implementación y comparación de al menos tres alternativas de procesamiento.
- Preparación de datos y comparación de al menos tres modelos de ML.
- Predicciones, métricas, visualizaciones y dashboard.
- Evaluación de APIs e infraestructura, matriz de riesgos y mitigaciones.
- Gestión Scrum, seguimiento de sprints y análisis de tecnologías y modelo de negocio.

Fuera del alcance: clústeres físicos, plataformas Big Data en producción, despliegue productivo de modelos, MLOps y pruebas avanzadas de penetración sobre sistemas reales.

## Sprint 0

Esta entrega contiene la planificación y estructura inicial. El pipeline y sus resultados todavía no están implementados. La API, el dominio de negocio, la variable objetivo, los algoritmos y los umbrales de aceptación serán definidos por el equipo antes del primer sprint de implementación.

### Definition of Ready

Historia con usuario y beneficio claros, criterios verificables, prioridad y dependencias definidas, fuente de datos evaluada y tarea suficientemente pequeña para el sprint.

### Definition of Done

Criterios satisfechos, ejecución reproducible validada, revisión de otro integrante, documentación actualizada, ausencia de secretos y cambios publicados en GitHub mediante commit y push. Para Sprint 0 también se exige un commit y un push local real de cada integrante.

## Organización

```text
docs/          alcance, backlog y acuerdos
notebooks/     futuros notebooks de Google Colab
src/           futuros componentes del pipeline
tests/         futuras pruebas
data/          instrucciones de manejo de datos
evidencias/    registro de aportes y capturas
```

## Colaboración

La rama principal será `main`. Cada integrante debe clonar el repositorio con su cuenta, configurar su propia identidad local y aportar un archivo en `evidencias/aportes/`. Los cambios funcionales posteriores se harán en ramas y se revisarán mediante pull requests.



