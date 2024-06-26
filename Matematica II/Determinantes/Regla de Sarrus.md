### Pasos:
1. Duplicar las dos primeras columnas/filas
2. Multiplicar todos los numeros de las diagonales, empezando por la diagonal principal y bajando hasta la ultima
3. Sumar todos estos numeros
4. Multiplicar todos los numeros de la diagonal secundaria
5. Sumarlos
6. A la suma de la multiplicación de los números de la diagonal principal y las de abajo, restarle las de la diagonal secundaria

#### Ejemplo
Dada la matriz: ![[Pasted image 20240625211745.png]]

1. numeros de las diagonales "principales" 
   `(3.1.2+10.(-1).4+2.0.(-8))` 
   `(6+(-40)+0)`
   `-34`
2. de las diagonales "secundarias" 
   `(2.1.4+(-1).(-8).3+2.10.0)`
   `(8+24+0)`
   `32`
3. Restarlos: `|A|= -34-32`
`