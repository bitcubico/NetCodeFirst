# Glosario Code First .Net Framework

## A
- **`add-migration <name_migration>`**: Agrega una migración
- **`add-migration <name_migration> -o <path>`**: Agrega una migración indicando el directorio donde se desea ubicar esta

## R
- **`remove-migration`**: Elimina la última migración de la lista, si esta ya fue ejecutada en la base de datos, no se puede eliminar. Debe primero actualizar la base de datos a la versión anterior a esta e intentar nuevamente

## U
- **`update-database`**: Actualiza a la última versión la base de datos
- **`update-database -migration <nombre_migracion>`**: Actualiza la base de datos a una migración específica
