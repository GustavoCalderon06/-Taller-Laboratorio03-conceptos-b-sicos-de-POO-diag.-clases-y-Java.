Caso i:

Clases:
Jugador
Partido
Gol

Relaciones
Jugador y partido asociacion
Partido y gol composicion
Jugador y gol agreagacion

Multiplicidad:
Jugador y partido muchos es a muchos
Partido y goles 1 es a muchos goles
Entre jugador y goles pueden haber 0 o mas goles por jugador

Atributos y metodos:
Jugador tiene atributoos de nombre y posicion, con metodo de golesMarcados
Partido tiene arreglo de jugadores

----------------------------------
Caso ii:

Clases:
Empresa
Buque
Astillero

Relaciones:
Agregacion entre la empresa y el buque
Y asociacion entre empresa y astillero

Multiplicidad:
1 es a 10 en empresa y buque
Y 1 es a 1 en emresa y astillero

Atributos y metodos:
Empresa tiene metodos agregarBuque, eliminarBuque 
Buque tiene atributos de marca y arreglo de asientos


----------------------------------
Caso iii:

Clases:
Pedido
Mesero

Relaciones:
Composicion

Multiplicadad:
1 es a muchos pedidos

Atributos y metodos:
Mesero tiene atributos de nombre y rut y, y metodo de pedidosRealizados
Pedido tiene atributo date

-----------------------------------
Caso iv:

Clases:
Equipo
Jugador

Relacion:
De agregacion

Rol de jugador es "capitan"

Multiplicidad:
1 es a 1

Atributos y metodos:
Equipo puede tener nombre y metodos de asignarPosicion y mostrarListaJugadores.
Jugador puede tener atributos de nombre edad o posicion, y tener getter and setter.


-----------------------------------
Caso v:


Clases:
Evento

Relacion de agregacion
Con rol de eventos en un lado

Multiplicidad:

1 en un lado y 1 es a muchos por otro lado

Atributos y metodos:
para ver la fecha de evento un atributo Date
