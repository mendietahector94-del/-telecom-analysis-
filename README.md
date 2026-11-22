# -telecom-analysis-
# Análisis de Clientes de ConnectaTel
## Descripción del proyecto

Este proyecto tiene como objetivo analizar el comportamiento de los clientes de una empresa de telecomunicaciones llamada **ConnectaTel** mediante técnicas de análisis exploratorio de datos (EDA). El propósito es identificar patrones de uso, segmentar usuarios y generar recomendaciones de negocio que permitan optimizar la oferta de planes y mejorar la toma de decisiones comerciales.

El análisis se enfoca en variables relacionadas con la edad de los usuarios, el tipo de plan contratado, la cantidad de llamadas realizadas, la cantidad de mensajes enviados y la duración de las llamadas.

## Objetivos

- Evaluar la calidad y consistencia de los datos.
- Analizar los patrones de uso de los servicios de telecomunicaciones.
- Identificar segmentos de clientes según edad y nivel de uso.
- Detectar y evaluar valores atípicos (outliers).
- Generar recomendaciones basadas en evidencia para mejorar la oferta comercial.

## Dataset utilizado

El proyecto utiliza información de clientes de ConnectaTel con variables como:

| Variable | Descripción |
| user_id | Identificador único del usuario |
| age | Edad del cliente |
| plan | Tipo de plan contratado (Básico o Premium) |
| cant_llamadas | Cantidad de llamadas realizadas |
| cant_mensajes | Cantidad de mensajes enviados |
| cant_minutos_llamada | Minutos consumidos en llamadas |

## Etapas del análisis

### 1. Exploración inicial de datos

- Inspección de la estructura del dataset.
- Revisión de tipos de datos.
- Identificación de valores faltantes.
- Detección de registros duplicados.
- Validación de consistencia de las variables.

### 2. Limpieza y preparación de datos

- Corrección de tipos de datos cuando fue necesario.
- Tratamiento de inconsistencias.
- Revisión y validación de valores extremos.

### 3. Análisis y exploracion de datos

Se realizaron análisis descriptivos y visuales sobre:

- Distribución de edades.
- Distribución por tipo de plan.
- Cantidad de mensajes.
- Cantidad de llamadas.
- Minutos por llamada.
- Comparaciones entre planes.

### 4. Segmentación de clientes

#### Segmentación por edad

- Joven (< 30 años)
- Adulto (30 a 59 años)
- Adulto Mayor (60 años o más)

#### Segmentación por nivel de uso

- Bajo uso: menos de 5 llamadas y menos de 5 mensajes.
- Uso medio: menos de 10 llamadas y menos de 10 mensajes.
- Alto uso: 10 o más llamadas o mensajes.

### 5. Detección de outliers

Se identificaron valores extremos en:

- Cantidad de mensajes.
- Cantidad de llamadas.
- Duración de llamadas.

Los outliers se conservaron debido a que representan comportamientos reales de clientes con uso intensivo de los servicios.

### 6. Generación de insights de negocio

A partir de los hallazgos se desarrollaron conclusiones relacionadas con:

- Segmentación de clientes.
- Patrones de consumo.
- Usuarios de alto valor.
- Oportunidades de mejora en los planes actuales.
- Recomendaciones estratégicas para ConnectaTel.

## Principales hallazgos

- La mayoría de los usuarios presenta un nivel de uso medio.
- Los patrones de llamadas y mensajes son similares entre los planes Básico y Premium.
- La edad no parece influir significativamente en la elección del plan.
- Existe un grupo reducido de usuarios con consumos significativamente superiores al promedio.
- La segmentación por nivel de uso aporta más valor estratégico que la segmentación exclusivamente por edad.

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Cómo ejecutar el proyecto

5. Busca el repositorio y abre el notebook principal.

6. Ejecuta las celdas en orden.

## Autor

Hector Mendieta

Proyecto desarrollado como parte del programa de Análisis de Datos de TripleTen.
