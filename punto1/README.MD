Se implementó un programa en Python que con base a una gramática y una cadena, construye y muestra su árbol de sintaxis de forma gráfica utilizando matplotlib.
## Gramatica
E → E + T | T
T → T * F | F
F → num | (E)

Gracias a la gramatica permite analizar cadenas como:
- 10+5*2
- 3*(4+5)
- 100*(20+3)

- El programa lee una o varias expresiones desde un archivo de texto.
- Construye el árbol sintáctico correspondiente.
- Dibuja el árbol gráficamente con matplotlib.
En el archivo de entrada se encuentra el ejemplo 5+15*2


