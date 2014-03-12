# Clase Uno
* Introduccion Profesor
* Introduccion materiales
* Creacion Usuario e Instalacion Basica Oracle 11g y SQL Developer
* Demostracion basica de SQL Developer

* SELECT
* JOIN
* GROUP BY y HAVING
* Sub-selects
* Variables de Sustitucion `&` (interactivo)
* UNDEFINE

> Para variables VARCHAR rodear por commillas simples

Ej:
`SELECT * FROM bleh WHERE name = '&name';`

## Tipos de datos:
* Number
* Char
* Varchar
* Varchar2
* Date
* Boolean
* Timestamp
* Long

## Operadores
* Aritmeticos: `+ - / *`
* Logicos: `AND OR NOT` y `IS NULL`/`IS NOT NULL`
* Comparacion: `= != > < >= <= BETWEEN IN`

# Clase Dos
## Funciones de Caracteres
* `UPPER`
* `LOWER`
* `INITCAP` (capitalize)

## Funciones de manipulacion de caracteres
* `CONCAT` (a, b) *Solo de a 2* 
* `SUBSTR` (field, n, m) *indice inicial 1*
* `LENGTH`

## Funciones numericas
* `ROUND`
* `MOD`
* `ABS`

## Funciones de fecha
* `MONTHS_BETWEEN`
* `ADD_MONTHS`
* `TRUNC` *trunca el formato de fecha a YYYY-MM-DD*

## Funciones de conversion de datos
* `TO_CHAR`
* `TO_NUMBER`
* `NVL`

## Funcion DECODE/CASE
* `DECODE` (field, value_1, exp_1, value_2, exp_2, ..., value_n, exp_n, default_field)
* `CASE WHEN ... WHEN ... ELSE ... END`

## Funciones de grupo
* `AVG`
* `MAX`
* `SUM`
* `MIN`
