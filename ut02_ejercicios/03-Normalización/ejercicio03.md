# Ejercicio 3

En una base de datos de una empresa de alquiler de vehículos, se tiene la siguiente tabla Alquileres que contiene información sobre los vehículos alquilados y sus conductores.

Normaliza la tabla Alquileres para que cumpla con 1FN, 2FN y 3FN. Identifica las dependencias funcionales y elimina las dependencias parciales y transitivas en cada paso.

## Primera forma Normal (1FN)

Para cumplir con la 1NF, el campo PrecioVehiculos y Vehiculos no es atómico, así que creamos la tabla Precios y Vehiculos.

+ Tabla __Precio__ y __Vehiculos__:
  
|AlquilerID|Precio|Vehiculos|
-----------------------
| 101 | 50 | Sedán|
| 101 | 70 | SUV|
| 102 | 80 | Convertible|
| 102 | 65 | Pickup|
| 103 | 70 | SUV|
| 103 | 60 | Van|
| 103 | 50 | Sedán|
| 104 | 50 | Sedán|

## Segunda forma normal (2FN)

