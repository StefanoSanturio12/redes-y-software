
Php es un lenguaje de programaciòn interpretado del lado del servidor.

"xAMP"
- x (Cross platform)
- apache
- mySQL
- PHP

el resultado de interpretar php es html

# XAMPP


instalar en C:/xampp/htadocs (Document root)

http://localhost/C:/xampp/htadocs
aqui estàn los archivos que vamos a programar.
(hay que tener encendido el Xampp para que funcione.)



----
instalacion en linux

# apt install apache2
# apt install php 7.2
# apt install mariadb-server





-------
# caracteristicas de PHP

Documentaciòn:
https://www.php.net/docs.php

En php las variables se definen con $ y en minusculas.
- $variable
las constantes son un tipo de variable que se mantienen en el tiempo con el mismo valor 

-todas las lineas deben terminar en ; 

# Ejemplo de codigo

Cosas básicas:
[[ejemplo01.php]]

A la hora de recargar la pagina para hacer cabios, hay que recargar la cache.


# Buscar mas tarde

# Variables php


Las variables en php se puede utilizar variables sin la necesidad de antes definirlas o inicializarlas, aun que es muy buena practica. estas siempre se definen y se utilizan poniendo primero el caracter "$".

Existen 4 tipos principales de variables, Integrales, flotantes, cadenas y booleanos (integer, float, strings y bool).
Las integer hacen referencia a numeros enteros con los cuales se pueden realizar operaciones. 
Las float son como los integer, pero acepta numeros decimales.
Y los strings hacen referencia a cadenas de texto, es decir, simplemente texto.
Los booleanos son "true" o "false", que sirven para utilizar en estructuras logicas. Estos tmabien se pueden interpretar como 0 y 1, siendo false y true respectivamente. 
Otra cosa a tener encuenta es que una variable vacia en una operacion logica siempre tendrà valor false.
Las variables tambien pueden tener de contenido otras variables u operaciones matematicas.  *Ej: $variable = $variable2 + $Variable1 * 4*

Hay que tener en cuenta que en PHP las variables son sensibles a mayúsculas, es decir, que pueden existir 2 variables llamadas pepe y PEPE, teniendo las dos distintos valores.
Tambien es imposible crear variables que comiencen con algun numero, y es importante no usar caracteres especiales o espacios a la hoira de nombrar variables, pudiendo usar "-" o "_" para separar palabras enel nombre de una variable. 

Ej: $Numero_1



# Estructuras logicas
