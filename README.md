# -Periodic-Table-Database
# Periodic Table Database  
Proyecto del curso *Relational Database* de FreeCodeCamp.

Este proyecto consiste en construir una base de datos relacional que almacena información de la tabla periódica, normalizar sus tablas, añadir restricciones, crear una tabla de tipos, limpiar datos, insertar nuevos elementos y desarrollar un script en Bash para consultar la información de un elemento a través del terminal.

---

## 📂 Archivos incluidos

- **periodic_table.sql**  
  Dump completo de la base de datos, incluyendo:
  - Tablas `elements`, `properties` y `types`
  - Llaves primarias y foráneas
  - Restricciones `UNIQUE` y `NOT NULL`
  - Inserción de elementos 1–10
  - Normalización completa según las instrucciones del proyecto

- **element.sh**  
  Script en Bash que permite consultar un elemento de la tabla periódica utilizando:
  - Número atómico  
  - Símbolo  
  - Nombre  
