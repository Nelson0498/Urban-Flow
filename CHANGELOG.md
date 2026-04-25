# Changelog

Todas las modificaciones notables de este proyecto se documentarán en este archivo.

## [Día 1] - Ejercicio 01
- Inicialización del repositorio y configuración de Git.
- Creación de la rama Sprint_1.
- Estructuración de directorios (data/raw, data/interim, etc.).
- Creación de README.md y CHANGELOG.md.

## [Día 2] - Ejercicio 02 (Autor: Agustín Cuello)
- Subida de notebook individual.
- Análisis exploratorio de datos resuelto.

## [Día 3] - Ejercicio 03 (Autor: Nelson Castillo)
- Implementación de la función normalizar_datos_temporales.
- Normalización de fechas al formato 'YYYY-MM-DD' (errores a 1932-01-01).
- Normalización de horas al formato de 24hs (errores a 00:00).
- Limpieza inicial de ubicaciones y patentes.

## [Día 3] - Ejercicio 03 (Corrección: Manuel Lombardi)
- Optimización de la función normalizar_datos_temporales.
- Se agregó `dayfirst=True` para corregir la advertencia de ambigüedad en fechas.
- Se implementó `format='mixed'` para procesar horas en múltiples formatos.

## [Día 3] - Ejercicio 03 (Autor: Agustín Rojas)
- Normalización de formatos en columnas de Ubicaciones y Patentes.
- Tratamiento de Inconsistencias: Imputación y manejo de valores nulos.
- Detección y tratamiento de Outliers en el dataset.
