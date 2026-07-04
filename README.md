# SQL Learning Journey: Guía y Ejercicios Prácticos

Este repositorio contiene una recopilación de notas, buenas prácticas y ejercicios resueltos sobre **SQL**, utilizando la base de datos de ejemplo *Sakila*.

## Contenido
- **Orden de ejecución de queries:** Entiende cómo procesa el motor de base de datos tus consultas.
- **Relaciones entre tablas:** Guía sobre cómo conectar datos (1:N, 1:1, M:N) y el uso correcto de tablas intermedias.
- **Cheat Sheet Mental:** Checklist para escribir consultas eficientes.
- **Ejercicios Prácticos:** Casos de uso reales que cubren desde `SELECT` básicos hasta `JOINs`, `GROUP BY`, `HAVING` y funciones avanzadas.

## El Orden de Ejecución de SQL
Para escribir mejores consultas, recuerda siempre este flujo:

1. **FROM / JOIN**: ¿De qué tablas saco los datos?
2. **WHERE**: ¿Qué filas individuales filtro?
3. **GROUP BY**: ¿Cómo agrupo los datos?
4. **HAVING**: ¿Qué grupos filtro después de agrupar?
5. **SELECT**: ¿Qué columnas muestro?
6. **ORDER BY**: ¿Cómo ordeno el resultado?
7. **LIMIT**: ¿Cuántas filas muestro?

## Conceptos Clave
- **WHERE vs HAVING**: Recuerda que `WHERE` filtra filas antes de agrupar, mientras que `HAVING` filtra los grupos una vez calculadas las funciones de agregación (`SUM`, `COUNT`, etc.).
- **Tablas Intermedias**: Indispensables para resolver relaciones Muchos a Muchos (M:N) y mantener la integridad de los datos.


*Este material es parte de mi proceso de aprendizaje y consolidación de conocimientos en SQL.*