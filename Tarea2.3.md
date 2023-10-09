# PSEUDOCÓDIGO

Un pseudocódigo es una representación de alto nivel de un algoritmo o programa informático. Es un lenguaje intermedio entre el lenguaje humano y el lenguaje de programación real, diseñado para expresar la lógica de un algoritmo de manera comprensible y cercana al lenguaje humano.
El objetivo principal del pseudocódigo es facilitar la comprensión y la comunicación de la lógica de un algoritmo entre programadores y diseñadores sin preocuparse por los detalles de la sintaxis de un lenguaje de programación específico. 

--

***EJEMPLO***


INICIO

   LEER limite_superior
   LEER limite_inferior

   ESCRIBIR "Números primos en el rango [", limite_inferior, ",", limite_superior, "]:"

   PARA numero DESDE limite_inferior HASTA limite_superior HACER
      es_primo = VERDADERO

      PARA divisor DESDE 2 HASTA (numero / 2) HACER
         SI numero MOD divisor == 0 ENTONCES
            es_primo = FALSO
            SALIR DEL BUCLE
         FIN SI
      FIN PARA

      SI es_primo ENTONCES
         ESCRIBIR numero
      FIN SI
   FIN PARA

FIN

--

En este pseudocódigo:

Se solicita al usuario que ingrese un límite superior e inferior para el rango en el cual se buscarán números primos.

Se utiliza un bucle "PARA" para iterar a través de cada número en el rango especificado.

Para cada número en el rango, se realiza una comprobación para determinar si es primo o no. Esto se hace mediante otro bucle "PARA" que verifica si el número es divisible por cualquier número entre 2 y la mitad del número. Si se encuentra un divisor, se establece la variable es_primo en FALSO y se sale del bucle.

Si la variable es_primo sigue siendo VERDADERA después de la verificación de divisibilidad, significa que el número es primo y se muestra en la salida.

Este pseudocódigo describe un algoritmo para encontrar números primos en un rango específico y proporciona una representación clara de los pasos involucrados en el proceso. Es importante destacar que este es solo un ejemplo, y los algoritmos reales de búsqueda de números primos pueden ser más eficientes, pero este pseudocódigo ilustra los conceptos básicos involucrados en el proceso.





