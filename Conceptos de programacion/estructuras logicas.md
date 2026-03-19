Las estruturas logicas son maneras de controlar el flujo del codigo por medio de condiciones. Estas pueden tener el valor booleano de True o False, y determinaran que partes del codigo se leeran bajo condiciones y contextos.

Las disponibles en php son: if, switch, match. Tambien hay bucles condicionales, los cuales son for, foreach y while. 

En los procesos logicos se usan condiciones para cumplir con el codigo que se les asigna. 
EJ:  si variable "valor1" es TRUE, entonces ejecuta el codigo de abajo. 

Asi funciona literalmente el operador IF.


Los operadores logicos son formas de configurar el procesamiento de las estructuras logicas. 

==$v == true and $v1 == true ==  (and, &&)
- cumple la función de comparar dos factores para ejecutar la condicion.
==$v == true or $v1 == true== (or, ||)
- permite realizar la ejecucion del codigo en caso de que una de las condiciones se cumpla.
==!$v == false== (!)
- si la condicion especificada no se cumple, el codigo se ejecuta.
==$v xor $v1== (xor)
- Es como "or" pero solo ejecuta el codigo si una de las condiciones se cumple, pero no si las dos se cumplen.

