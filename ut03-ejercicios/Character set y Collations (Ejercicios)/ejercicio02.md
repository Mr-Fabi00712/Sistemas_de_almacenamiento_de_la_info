# Ejercicio 2

## Muestra todos los collations disponibles para el conjunto de caracteres latin1. ¿Cuál es el collation predeterminado de latin1?

Nota: hay que generar dos consultas: una por cada pregunta.

- Comando 1: Mostrar todos los collations disponibles para el conjunto de caracteres _latin1_:

```
SHOW COLLATION WHERE Charset = 'latin1';
```

- Comando 2: Determinar el collation predeterminado para _latin1_:

```
SHOW CHARACTER SET LIKE 'latin1';
```