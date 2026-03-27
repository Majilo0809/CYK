<img width="800" height="386" alt="image" src="https://github.com/user-attachments/assets/f08b8f05-2a53-4d3d-8d83-fd191ba9936b" />En este ejercicio se compara el comportamiento, eficiencia y resultados obtenidos al analizar cadenas aritméticas. el pro
En el programa se generan expresiones aleatorias, se aplica el algoritmo CYK para medir el tiempo de ejecución y el uso de memoria
Permitiendo analizar el comportamiento del algoritmo cuando el tamaño de la cadena aumenta. Cabe resaltar que ambos cuentan con la misma gramatica

<img width="800" height="386" alt="image" src="https://github.com/user-attachments/assets/f1499e81-f59b-4307-8d1b-db664bf176ef" />

En este proyecto se comparó el algoritmo CYK con el analizador generado por ANTLR4. El algoritmo CYK tiene una complejidad temporal 
O(n3) porque utiliza programación dinámica y construye una tabla de tamaño al cuadrado
, donde cada posición requiere probar múltiples particiones de la cadena.
En cambio, ANTLR utiliza un algoritmo que analiza la entrada de izquierda a derecha sin construir una tabla cuadrada, lo que permite un comportamiento cercano a tiempo lineal en la mayoría de los casos. Los resultados obtenidos en las pruebas realizadas demuestran claramente que el tiempo de ejecución y el uso de memoria de CYK crecen mucho más rápido que los de ANTLR cuando aumenta el tamaño de la entrada.
