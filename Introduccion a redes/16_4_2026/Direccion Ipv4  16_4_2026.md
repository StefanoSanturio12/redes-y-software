
Ipv4

- Notacion Decimal
- 32 bits de longitud
- Separador (.) de octetos (8 bits)


									
										 ( BIT )

| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   | Valor Decimal |
| --- | --- | --- | --- | --- | --- | --- | --- | ------------- |
|     |     |     |     |     |     |     |     | X             |
'''''''''''''''''''''''''''''''''''''''''''''''''''''   ¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡¡
	Nibble Alto                                        Nibble Bajo                                    

.........................................................................................................................
					Octeto




## Modelo OSI (Referencia. Open System comunication)

(192.168.1.0)

El 0 al final indica que es el nombre de la red
Es una Red lan

para conseguirlos numeros que componen los octetos de una ip(osea los binarios)
hay que hallar que numeros en el octeto de 32 bits (1 - 225) que lo forman en una suma. Esos numeros estaran como 1 y los que no participen en la suma quedan en 0 formando el binarrio


Las redes lan son clase C



---------------------

Declaracion de la red = Direccion de red
						"      "  Gateway  (Puerto de enlace)
						"       " Brodcast   (multidsifuncion)
						"       " Mascara (Conjuncion logica (AND))


Clase
               
A = 0.0.0.0 = 126.225.225.225

B = 128.0.0.0 = 191.225.225.225

C =  172.0.0.0 = 223.....



# CIDR


El numero luego del slash del ip, muestra el numero de bits en alto de la mascara. 

Este numero tambien sirve para diferenciar redes con el mismo conjunto de numeros, ya que pueden ser de diferentes tipos.

El CIDR tambien determina que tantos dispositivos se pueden conectar a esa red.



### VLSM (Mascara de longitud variable)
todo
Limita los tipos de redes que pueden conectarse.  Es decir puede permitir B Y C pero no A
Esto es sobre todo para seguridad

