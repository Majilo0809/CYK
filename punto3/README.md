
Primero se crearon dos gramáticas diferentes para la expresión 4-3-2. En una de ellas la regla principal comienza con expr : expr '-' expr, lo que hace que la evaluación se realice de izquierda a derecha. En la otra gramática se invierte el orden y se utiliza expr : expr '-' expr pero estructurada de forma que el árbol sintáctico se construye de derecha a izquierda. Aunque la cadena es exactamente la misma, el árbol generado es diferente y por lo tanto el resultado también cambia.

<img width="763" height="386" alt="image" src="https://github.com/user-attachments/assets/15653380-6dcb-44c9-82fe-6881db46054e" />

Después se realizó pero con la precedencia de operadores. En la gramática de precedencia normal se definió primero la expresión y luego el término, lo que hace que el operador * tenga mayor prioridad que +. Sin embargo, en la gramática de precedencia invertida se cambió el orden de las reglas: primero se evaluó la suma y después la multiplicación. Este simple cambio en el orden de las reglas provoca que la misma cadena aritmética produzca un resultado distinto.

<img width="767" height="410" alt="image" src="https://github.com/user-attachments/assets/f829b0cb-b976-4022-9618-32b72c721b41" />


<img width="816" height="222" alt="image" src="https://github.com/user-attachments/assets/bc4e4a47-096a-4af6-9481-16ea9e322c10" />

Esto demuestra que en los lenguajes de programación la precedencia y la asociatividad no dependen únicamente de los operadores, sino de cómo están definidas las reglas dentro de la gramática. Al modificar el orden en el que aparecen las expresiones y los términos, cambia la forma en la que se construye el árbol sintáctico y el resultado final de la expresión.
