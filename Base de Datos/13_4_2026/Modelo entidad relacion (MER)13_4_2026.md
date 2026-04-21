




MER es un diagrama
Es un modelo conceptual que se basa en la modelacion del mundo real en entidades y relaciones entre las entidades. 
este modelo tiene un lenguaje grafico para el diseño del esquema y puede tener diferentes variantes, al momento de representar algunos elementos. existen erramientas "CASE" que permiten diseñar conceptualmente  una base de datos utilizando modelos del MER original.


# Elementos de MER

	- Entidades
		Son los elementos que permiten representar objetos  que tenga existencia fisica o conceptual. Ese objeto es algo de la realidad que queremos resolver. Se representa con un rectangulo y con el nombre del elemento que queremos representar.

	-Relaciones
		se trata de la asociacion queva a existir entre las distintas entidadesm.
				Una relacion se representa con unr rombo y dentro se le identifica con la funcion que representara entre las dos entidades. una relacion sirve para conectar entidadesy modelar las asociaciones entre los ibjetis
por lo tanto el nombre debe representar esa funcon o asociacion entre entidades. Por lo generalmente son este tipo, en duplas
		-Atributos
			Datos o caracteristicas de una entidad. Se representa con una linea al costado de una entidad.



# Atributos

  -Estructurados/Compuestos
	  pueden ser sub elementos que dan informacion extra
  - Los atributo multivaluado son atributo con mas de un valor. Se representan con un asterisco asi*

-Atributos determinantes
	son atributos que definen que un elemento sea distinto a los demas por un atributo unico. Se representa con un subrayado. Toda entidad tiene que tener un atributo determinante.
	Estos tambien se consideran restricciones de integridad
-Atributos en la relacion
	se pueden colocar atributos en la realacion


# Cardinalidad

Es lo que indica cuantos elementos de una entidad pueden asociarse a elementos de la otra entidad relacionada.
A la cardinalidad se le denomina como una restricion e integridad

hay distintos tipos de cardinalidad

1:1
	Un elemento del origen puede estar relacionado con hasta 1 elemento del destino
	(un director Dirige un instituto)

	A= (a1,a2,a3)
	B= (b1,b2,b3)
	
	ARB= ({a1,b1}, {a3,b2}, {a2, b3})
	
1:N
	Un elemento se relaciona con varios

	ARB = ({a1, b1}, {a1,b2}, {a3, b3})

N:N

	varios elementos del origen pueden estar relacionados con varios elementos del destino
	
	ARB =({a1,b1},{a1,b2}, {b2,a3})


-------------------------------

# Agregaciones

![[Cardinalidad Agregaciones.canvas]]

# Categorizaciones o especializacion de entidades


Una entidad principal obserba los datos en comun

