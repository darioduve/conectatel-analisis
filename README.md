# Proyecto 6: Análisis de una empresa de telecomunicaciones

## Descripción del proyecto

Este proyecto forma parte del Sprint 7 del programa de Data Analytics de TripleTen.

Analicé datos de ConectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia, para conocer mejor a sus clientes, identificar patrones de consumo y encontrar oportunidades para mejorar sus planes.

## Objetivo

Identificar cómo utilizan los servicios los clientes de ConectaTel, clasificarlos por edad y nivel de uso, detectar consumos extremos y proponer recomendaciones basadas en los resultados.

## Datos utilizados

Trabajé con dos conjuntos de datos:

- **Usuarios:** información de 4,000 clientes, incluyendo edad, ciudad, plan contratado y fechas de registro.
- **Uso del servicio:** 40,000 registros relacionados con llamadas y mensajes.

## Etapas del análisis

1. Exploré los datos para conocer su estructura e identificar problemas de calidad.
2. Revisé valores faltantes, edades incorrectas y fechas fuera del periodo analizado.
3. Preparé los datos y calculé indicadores de consumo por cliente.
4. Comparé el comportamiento de los usuarios de los planes Básico y Premium.
5. Analicé la distribución de los datos e identifiqué valores atípicos.
6. Clasifiqué a los clientes por edad y nivel de uso.
7. Elaboré un análisis ejecutivo con hallazgos y recomendaciones.

## Principales hallazgos

- El grupo de edad más numeroso fue el de adultos, con 2,018 clientes.
- La mayoría de los clientes presentó un nivel de uso medio, con 2,943 usuarios.
- Los clientes de los planes Básico y Premium tuvieron patrones de consumo bastante similares.
- Se identificaron algunos clientes con consumos considerablemente superiores al resto.

Estos resultados sugieren que ConectaTel podría revisar si sus planes actuales se adaptan a las diferentes necesidades de consumo de sus clientes.

## Herramientas utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Cómo revisar y ejecutar el proyecto

1. Descargar el archivo `.ipynb` disponible en este repositorio.
2. Abrirlo en Jupyter Notebook o Google Colab.
3. Tener disponibles los archivos de datos originales y las bibliotecas de Python utilizadas.
4. Revisar las rutas de lectura de los archivos y ajustarlas según el entorno.
5. Ejecutar las celdas en orden, desde el inicio hasta el análisis ejecutivo.

**Nota:** Los archivos de datos originales no están incluidos en este repositorio, por lo que son necesarios para volver a ejecutar el análisis completo.

## Conclusión

Este proyecto me permitió practicar la limpieza, preparación, exploración y segmentación de datos utilizando Python. También aprendí a interpretar los resultados y convertirlos en recomendaciones que podrían ayudar a una empresa a tomar mejores decisiones.
