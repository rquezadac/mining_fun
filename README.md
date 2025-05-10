# Un repositorio de ejercicios de Python aplicados a la actividad minera y metalúrgica.
---
Buen día a todos. Mi nombre es René, soy ingeniero civil en minas, chileno, y he trabajado en los últimos 9~10 años en los más diversos proyectos de data analytics aplicados a la industria minera: Geociencias, minería subterránea, planificación, plantas concentradoras, plantas de hidrometalurgia, entre otras diversas áreas de negocio.

En este repositorio, iré publicando, mientras mi tiempo libre lo permita (no periódicamente, por desgracia), diversos casos de uso y ejercicios que han sido parte de mi experiencia en el mundo minero y metalúrgico, o bien, que han sido parte de alguna sesión en la cual, en mi tiempo libre, pienso como resolver algún problema de interés. Lo último no es tan recurrente (el tiempo libre es poco), pero, debido a que lo que más disfruto a nivel profesional es *resolver problemas*, a veces me da por imaginar cómo solucionar una que otra cosa en el ámbito minero. Y muchas veces sin siquiera estar trabajando en ese ámbito (pido perdón).

Mi objetivo es, de manera práctica, pero con un formalismo técnico adecuado, introducir soluciones programáticas a cuestiones mineras del día a día, incluso elementales. Si algún colega minero (o quizás de otra industria) comienza a leer un poco más de *cómo aprender* a solucionar problemas de esta forma, entonces me doy por pagado.

Todos los ejercicios se solucionan usando Python. Para reproducirlos, basta con clonar este repo y utilizar `pipenv` para instalar las correspondientes dependencias del archivo `Pipfile`, a fin de disponer de las librerías utilizadas en su resolución:

````
# Clonamos el repositorio en la carpeta donde trabajaremos.
git clone https://github.com/rquezadac/mining_fun.git

# Instalamos pipenv, en caso de no tenerlo.
pipenv install

# Iniciamos nuestro entorno virtual.
pipenv shell

# Instalamos las dependencias (librerías), y estamos listos.
pipenv install Pipfile
````

Los casos de uso que resolveremos serán los siguientes (esta lista estará siempre en construcción):

- [Determinación del pit final en 2D mediante la aplicación del algoritmo de máximo flujo](https://github.com/rquezadac/mining_fun/blob/main/Implementations%20(ESP)/Problema%20de%20pit%20final.ipynb)
- Extensión de la solución 2D de pit final para modelos en 3D.
- Visualización del campo de esfuerzos en la sección de un túnel usando modelos clásicos de geomecánica.
- Visualización de flujos de aire en distintas configuraciones de galerías subterráneas.
- Perfiles de eficiencia en flotación para distintas combinaciones de mineral.
- Un modelo prescriptivo para recomendar vectores de control óptimos en un circuito de conminución.

Los dejo cordialmente invitados a escribirme sus dudas, mejoras e, incluso, problemas que deseen resolver a rene.quezadac@gmail.com. No digo que podré resolverlo todo ¡Pero al menos puedo intentarlo!