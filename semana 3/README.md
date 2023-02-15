# Taller de análisis automático de textos en Humanidades

## Clases semana 3 - Sin laptops! &#x1F640; Cómo? programación sin laptops? Sí! (bueno, puede servir para consulta de los contenidos que hemos visto).

Usen **materiales de oficina:** cartulinas, lápices; es decir, **programe en papel &#x1F640;!** **Grupos** de 2 o 3 personas (nadie solo :)).


### Ejercicio 1 &#x1F916;

- Construyan un resumen de las variables que hemos mencionado: números, strings y listas.
- En su resumen, ubiquen las variables de manera conveniente en el papel para que con flechas indique transformaciones entre variables. Por ejemplo, si aplicamos S.count('a') vamos
a transformar el string **S** en un número que indica el número de veces que aparece **'a'** en **S**. Recuerde, entre otras, las funciones **len**, **count**, **replace**, **lower**,
**upper**, **split**. Incluya el operador **+**. Entregue detalles de la **sintaxis.**
- Use un ejemplo que muestre todas las transformaciones. 
- Exponga al curso brevemente como si estuviera explicando estos contenidos a estudiantes de la clase. 
- **Tiempo:** 20 minutos

### Ejercicio 2: Códigos secretos 2 &#x1F916;!

#### Parte 1

- Defina un **string** para cada **nombre** de los integrantes del grupo.
- Recuerde que S.replace('old','new') cambia el substring 'old' de **S** en 'new'. Con esto, para cada par de nombres construya un pequeño código que transforme un nombre en otro.
- Solo puede cambiar substrings de largo 1, 2 o 3. 
- **Tiempo:** 20 + 10 minutos!

#### Parte 2

- Construya el nombre que concatene el nombre de todos los integrantes del grupo. Use espacios en blanco. LLamemos **grupo_X** al string. 
- Calcule el largo del string **grupo_X**.
- Reemplace las 'a''s por '(1)''s, las 'e''s por '(2)''s, y así sucesivamente para todas las vocales en **grupo_X**.  
- Reemplace las consonantes por cualquier número que elija el grupo. Por ejemplo, 'j' podría ser '(23)'. 
- Entregue ese código a otro grupo.
- Ustedes deben decodificar los nombres de sus compañeros con el código recibido. 
- **Tiempo:** 20 minutos

### Ejercicio 3: Índices &#x1F916;!

Los índices forman una parte esencial de **Python.** Con respecto a un texto, es natural pensar que está formado por secuencias de elementos (las **palabras**), que a su vez
están formados por otros elementos (los **caracteres**). El aspecto esencial de estas dos dimensiones de los textos es que los elementos **ESTÁN ORDENADOS.** &#x1F640;!

#### Parte 1

- Formen grupos.
- Los integrantes de cada grupo deben numerarse, comenzando desde 0.
- Defina **N** como el número de integrantes del grupo.
- Defina: (1) un string de largo **N**; y (2) una lista de largo **N.**
- En una hoja de papel, simule dos códigos: por cada integrante del grupo imprime un caracter del string y un elemento de la lista. Siga el orden de los números asignados. 
- Ahora, para el string repita el código con una condición: si el caracter es una vocal imprima 'vocal'; en cambio, si el caracter es una consonante imprima 'consonante'
- ¿Qué podemos concluir?

#### Parte 2

Explorar qué ocurre si usamos en el string **S**: S[0], S[1], S[2], S[3], S[4], S[-1]. ¿Por qué es posible hacer esto? Pruebe:

- Imprimir 'sí' cada vez que **S** termina en 'a'. 
- Ejecutar S[0], luego S[1] y así sucesivamente. ¿Qué puede observar?
- Definir un string vacío ''. Con esto, reconstruya **S** usando los índices. 

#### Parte 3

Considere el string **S = 'lima santiago'**. Define la variable **L** igual a la aplicación de split(' '). Explore L[0], L[1], L[2], L[3], L[4], L[-1]. ¿Por qué es posible hacer esto? 
Definir una lista vacía []. Con esto, reconstruya **L** usando los índices. 


