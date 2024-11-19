# Desafíos del Sistema de Salud Pública en Chile: Un Análisis de Fonasa y la Demanda por Servicios de Atención Médica

## Integrantes
- Bárbara Canales
- Benjamin Cheuquian
- Mark von Riegen
- Felipe Villavicencio
- Giuliana Tirachini

## Profesor
Rodrigo Carrasco

## 1. Contexto y Motivación

Elegimos desarrollar el proyecto sobre Fonasa con el objetivo de mejorar la administración de recursos en las instituciones de salud pública, priorizando las áreas que más lo necesitan. Dado el aumento en la demanda de atención médica, especialmente en algunas especialidades y servicios, es esencial redistribuir los recursos para garantizar un acceso oportuno y adecuado.

La motivación del proyecto proviene de la evidencia que muestra deficiencias en la atención primaria, exámenes de diagnóstico y consultas especializadas, donde la alta demanda supera la disponibilidad de recursos, generando largas esperas y dificultades de acceso con impacto en la salud de las personas. Nuestro análisis del sistema de Fonasa busca identificar oportunidades para redirigir recursos a estas áreas críticas, reflejando las necesidades y desafíos de la población.

El proyecto está dirigido a tomadores de decisiones en salud pública, como el Ministerio de Salud y administradores de centros públicos, y tiene como propósito informar políticas que optimicen la distribución de recursos y mejoren la equidad y eficacia del sistema de salud.


## 2. Objetivos

**Objetivos científicos y de inferencia:**
El proyecto tiene como objetivo conocer, a través de distintos factores, las necesidades de atención médica de los beneficiarios de FONASA. Además, se busca identificar patrones y correlaciones entre las diferentes variables.


**Preguntas que esperamos responder y para qué:**
El análisis espera responder cómo varían las necesidades de atención médica y sus costos en el sistema de salud público según factores demográficos, socioeconómicos y geográficos. Las respuestas permitirán realizar inferencias sobre las necesidades médicas de los beneficiarios y proponer mejoras tanto en la atención del sistema público como en el privado.


**Beneficios accionables que podríamos lograr mediante este proyecto:**
El proyecto podría resultar en beneficios como la redistribución de recursos hacia las áreas de mayor demanda, de forma estacional o más general, sin debilitar otras áreas menos demandadas. Esto permitiría una atención más focalizada en necesidades menos cubiertas o en servicios con alta frecuencia demográfica o estacional.

**Audiencia objetivo de nuestro análisis:**
La audiencia principal incluye al Ministerio de Salud y a los administradores de centros de salud pública, quienes tienen la responsabilidad de optimizar los recursos para mejorar la atención a la población.


## 3. Datos
Utilizamos dos bases de datos principales:
1. **Población Beneficiaria 2023 Diciembre**: Información demográfica y clasificación de los beneficiarios de Fonasa.
2. **Modalidad Libre Elección 2023 Diciembre**: Datos de uso de prestaciones en la modalidad de libre elección.

Ambas bases están disponibles [aquí](https://www.fonasa.cl/sites/fonasa/datos-abiertos/estadisticas-anuales). Pese a ello creamos una muestra de 100 filas de cada archivo en la carpeta data/ .

3.  **Arancel de Prestaciones de Salud año 2024**: Servicios médicos, sus códigos y los costos asociados a diferentes niveles de cobertura en la modalidad de libre elección.

## 4. Preguntas de Investigación
1. ¿Qué tipos de prestación médica son más frecuentes entre diferentes tramos de edad y géneros?
2. ¿Cómo varía la cantidad y tipo de prestaciones emitidas según el mes del año? ¿Existen patrones estacionales?
3. ¿Qué tipos de prestación médica son más frecuentes en cada región?
4. ¿Cómo se relacionan los distintos tramos de Fonasa con la frecuencia y el tipo de prestaciones recibidas?
5. ¿Cómo cambia el gasto promedio en copagos a medida que los beneficiarios envejecen?

## 5. Metodología
- **Limpieza de datos:** Realizada con `pandas`.
- **Visualización:** Utilizando `Matplotlib` y `Seaborn`.
- **Análisis estadístico:** Se utilizarán modelos de regresión y análisis descriptivo para explorar patrones en los datos.




