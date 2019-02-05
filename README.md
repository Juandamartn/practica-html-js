# Almacén

Al efectuar una compra en un cierto almacén, si adquirimos más de 100 unidades de un mismo artículo, nos hacen un descuento de un 35%; entre 60 y 100 un 25%; y no hay descuento para una adquisición de menos de 60 unidades. Realizar un programa que pida la cantidad comprada, pida el precio unitario y calcule y muestre el descuento y el total a pagar.

# Calificaciones

Realizar un programa que pregunte al usuario por un número X de calificaciones (escala 0-100), calcule su promedio e imprima el promedio y el equivalente acorde a lo siguiente:

menos de 70 = Reprobado

- 70 = Aprobado
- mayor de 70 y hasta 80 = Suficiente
- mayor de 80 y hasta 90 = Bien
- mayor de 90 y menor que 100 = Muy Bien
- 100 = Excelente.

# Esfera

Algoritmo que:

- Pida al usuario el radio de una esfera.
- En el caso de que el radio sea menor o igual a cero, mostrar el mensaje “ERROR: El radio debe ser mayor que cero”.
- Calcular el área de la esfera (4 * PI * radio2) y mostrar el resultado en el formato: “El área de una esfera de radio <radio> es: <área> ”.

# Ordenamiento

Realizar un programa que pida una serie de números enteros (pedir por uno y preguntar al usuario si desea agregar otro y así sucesivamente) y al final se impriman en orden ascendente y descendente.

# Máquina de sodas

Considere un programa que modela el funcionamiento de una máquina de sodas, la cual tiene las siguientes características:

- Precio de las sodas: $0.45 c/u.
- Acepta sólo monedas de $0.10 y de $0.25.
- Se traga las monedas si no se introduce el cambio correcto, es decir, si por ejemplo ya tiene $0.25 de crédito e introduce $0.25, se tragaría la segunda moneda.

El programa deberá mostrar el saldo actual y un menú con el valor de las monedas aceptadas y opción para reiniciar, similar al siguiente:

Saldo: 0c

- 10c
- 25c
- Reiniciar
- Salir

Estado: EN ESPERA

Considere que:

Se muestra el menú y el usuario elige la opción deseada, entonces se debe mostrar de nuevo con los valores de saldo y estado actualizados y preguntar de nuevo la opción.
Si el usuario introduce el cambio exacto el estado deberá ser SODA ENTREGADA y se deberá reiniciar el saldo a cero.
Si la moneda es tragada el estado deberá ser MONEDA TRAGADA y el saldo permanecer sin modificaciones.
Si al simular el depósito de una moneda el saldo es menor que el precio entonces el estado deberá ser EN ESPERA.
La opción reiniciar pone el saldo de nuevo en cero.
