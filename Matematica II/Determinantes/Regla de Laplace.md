Esta regla puede ser utilizada para sacar determinantes de matrices de cualquier orden.

#### Pasos
1. Se elije una linea cualquiera(fila o columna)
2. Se sacan los adjuntos de esa linea(se elije la linea con mas 0 para optimizar el proceso)
3. Se multiplica $a_(ij)$(numero en la posicion $ij$) por $-1^(i+j)$ por el [[Metodo de Adjuntas o Cofactores |cofactor]]   $adj(a_(ij))$

### Ejemplo
Dada la matriz $A=\begin{bmatrix}3&5&-4\cr-2&1&0\cr0&2&-1\end{bmatrix}$

se elige la tercera fila
$\begin{pmatrix}0&2&-1\end{pmatrix}$
![[Pasted image 20240626185557.png]]

El primer numero es un 0, entonces se **cancela**, se calcula el determinante de los otros numeros
![[Pasted image 20240626185654.png]]
se resuelve
$= 2.(-1).(-8)+(-1).1.(-13)$
$= 16+13$
$= 3$

