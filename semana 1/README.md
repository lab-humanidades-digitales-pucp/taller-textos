# Introducción al análisis automático/cuantitativo de textos

## Github

Para trabajar en el curso, usaremos la plataforma [github](https://github.com/). Esta plataforma, con ciertas características de red social, permitirá compartir información,
almacenar datos, compartir códigos y crear un espacio digital para el taller (y el análisis computacional de textos).  

## Python

¿Cómo instalar **Python**? Usemos **Anaconda** :) Para esto sigamos los siguientes pasos (este [link](https://medium.com/saturdays-ai/empezando-a-usar-jupyter-notebook-para-python-parte-1-instalaci%C3%B3n-94e97b4c5f37) puede servir):

1. Ir a [link para instalar Anaconda](https://docs.anaconda.com/anaconda/install/) y elegir el sistema operativo.
2. Si es **Windows** o **Mac** es similar: deben bajar el instalador. Si es **linux** hay que bajar e instalar por terminal.
3. Supongamos que tenemos **Windows**. Elijan los bits de su pc, en **configuración** aparece esa información. Luego bajamos el instalador (un .exe) y lo instalamos.
4. Pongan **Next** y **I agree** a todo. Esperen un momento. Pueden hacerse un café o un té mientras esperan. Al final aprieten **Next**. Les recomiendo reiniciar el PC.
5. Ahora tenemos un programa que se llama **Anaconda**. En el menú, hacen click y en las opciones debería estar **jupyter notebook** o **jupyter lab**. Elijan el que más les guste. 
6. En una nueva ventana de su navegador, deberían aparecer las carpetas de su pc. Cree una nueva en su lugar favorito. Aprieten **new -> folder**. Dentro de la carpeta, creen un **new --> Python 3**. Y listo!!!

Un ejercicio interesante!!!

1. Mantengan **jupyter notebook** abierto!
2. Vayan a [link a repositorio](https://github.com/javiervz/analisis-datos-magister). Ahí aprieten **Code -> Download ZIP**. Luego de descomprimir, abran el **notebook** que está en la carpeta. Hagan esto desde el navegador donde abrieron **jupyter** (**no** haciendo doble click directamente en la carpeta descomprimida!!!). En **linux:** [link útil](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)
3. Vean si funciona :) Si funciona, pueden probar el código apretando el símbolo **play** o **run**. Vayan viendo qué entrega cada celda, eso puede servir mucho para partir.

**Pregunta fundamental del taller!** ¿Cómo aprendemos Python (en un contexto de Humanidades)?

## La RAE y cambios en el lenguaje

En 1815, la **Real Academia Española** (**RAE**, de ahora en adelante) introdujo una de tantas reformas de su historia. En esta, como ocurre cada cierto tiempo, la **RAE**
entregó una lista de **palabras incorrectas**, que debían usarse de una forma **correcta**. Por ejemplo, en la lista siguiente se muestra a la izquierda la palabra incorrecta, 
a la derecha como **debe decirse:**

- antiquario &#8594; anticuario 
- quaderno &#8594; cuaderno 
- quadro &#8594; cuadro 
- quando &#8594; cuando 
- quanto &#8594; cuanto 
- quarto &#8594; cuarto 
- quatro &#8594; cuatro 
- quociente &#8594; cociente 
- quota &#8594; cuota 
- quotidiano &#8594; cotidiano 
- Equador &#8594; Ecuador 
- iniquo &#8594; inicuo 
- obliquo &#8594; oblicuo 

**Preguntas!** ¿Cómo podríamos describir la influencia de ciertas instituciones, por ejemplo la RAE, en el uso de ciertas palabras en vez de otras? 
¿Qué materiales permitirían resolver este problema? ¿Qué técnicas (computacionales) podrían usarse?

¿Qué pasa cuando tenemos 1° un corpus representativo de los usos históricos de una lengua; y 3° una forma simple de acceder a la información? ¿Qué nuevas preguntas surgen? 
En este [paper](https://github.com/lab-humanidades-digitales-pucp/taller-textos/blob/main/bibliograf%C3%ADa/ngram_paper_2010.pdf), se proponen los **ngrams** de Google. 

**Problema!** Vayamos al link de [ngrams](https://books.google.com/ngrams/). Revise este pequeño [tutorial](https://books.google.com/ngrams/info) para hacer búsquedas interesantes. 

## El paper!

En este [paper](https://www.pnas.org/doi/10.1073/pnas.1721059115), se responden estas preguntas:

- ¿Qué ocurre cuando una nueva convención social reemplaza a una antigua? 
- ¿De qué forma influyen ciertas instituciones normativas? 
- ¿Es posible cuantificar este proceso? 

Para responder esta pregunta, se utiliza [Google ngrams!](https://books.google.com/ngrams/)


![alt text](https://github.com/lab-humanidades-digitales-pucp/taller-textos/blob/main/semana%201/pnas.1721059115fig01.jpeg?raw=true)


