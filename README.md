# CALIDAD-DEL-AIRE-EN-PUEBLA-ANALISIS
Este informe documenta el análisis de un conjunto de datos sobre la calidad del aire en Puebla. La base de datos proporciona información crucial para comprender los niveles de contaminantes y las condiciones ambientales en la región.

Se analizó la base extraida de plataformas de pertenencia y gestión gubernamental.

## Problemas principales que presentaba la base de datos:
La base de datos original presentaba varios desafíos comunes en el preprocesamiento de datos. Entre los problemas más significativos se encontraban:

Valores faltantes: Existían múltiples celdas sin datos en columnas clave, lo que podía sesgar el análisis.
Filas duplicadas: Se encontraron registros idénticos que podían inflar artificialmente el tamaño del dataset y distorsionar las estadísticas.
Inconsistencias en los tipos de datos: Algunas columnas numéricas o de fecha estaban almacenadas como texto, impidiendo operaciones matemáticas o temporales directas.
Posibles errores tipográficos o valores atípicos: En algunas columnas categóricas se observaron variaciones en la escritura que representaban la misma categoría.
Nombres de columnas poco descriptivos: Algunos nombres de columnas no reflejaban claramente el contenido que representaban, dificultando la comprensión del dataset.

## Técnicas aplicadas para solucionarlos
Para abordar los problemas identificados, se aplicaron las siguientes técnicas de limpieza y preprocesamiento de datos:

Manejo de valores faltantes: Se optó por [describir método, ej: imputar con la media/mediana/moda, o eliminar filas/columnas según el contexto y el porcentaje de nulos].
Corrección de valores atípicos/inconsistentes: Se utilizaron [describir método, ej: análisis estadísticos y visualizaciones (boxplots) para identificar atípicos, y se corrigieron reemplazándolos por la mediana/límites del rango intercuartílico].
Estandarización de textos: Se revisaron las columnas de texto para corregir errores tipográficos y se unificaron las etiquetas en las columnas categóricas.
Renombramiento de columnas: Se asignaron nombres más claros y concisos a las columnas para mejorar la legibilidad y facilitar el trabajo con el dataset.
