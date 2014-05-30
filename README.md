<h1>Trabajo Pr�ctico Final</h1>
<p>Integrantes:</p>, 
<p>Scalzotto Marcos</p>
<p>Barbieri Andr�s</p>
<p>Neri Paula</p>
<p>Tocci Natalia</p>
<h1>Consigna</h1>
<hr/>
<p>Una linea a�rea regional esta implementando un sistema de reservas, venta de pasajes y check-in en linea y hemos ganado la licitaci�n para realizarlo. 
La empresa esta radicada en Buenos Aires, pero vuela a todas las capitales de provincia la rep�blica argentina mas algunas ciudades importantes mas, para algunas de ellas hay una sola frecuencia diaria en otras la frecuencia es mayor.
Para realizar los vuelos la compa��a cuenta con una flota de 24 aviones de 4 tipos, los cuales realizan mas de un vuelos diario. En casi todos los aviones hay 2 categor�as, Primera y Economy, las distribuci�n de asientos para una u otra categor�a depende del destino y del avi�n:

Tipo de Avi�n		Pax		Primera		Economy
Tipo 1			25		0		25
Tipo 2			80		10		70
Tipo 3			125		20		105
Tipo 4			150		30		120

El sistema a desarrollar debe realizar los tres pasos principales de la transacci�n: 1 � Reservar el pasaje, 2 � Vender el Pasaje y 3 � Realizar el Check-in con asignaci�n de asiento.

1) Para la reserva el pasajero debe dar todos los datos personales requeridos (nombre, dni, fecnac, email) y se le reserva asiento en la categor�a seleccionada al destino requerido, siempre que exista lugar. Si no hay lugar, quedan en lista de espera los primeros 10 excedentes. La reserva debe posibilitar la selecci�n de viaje redondo, esto es ida y vuelta. Para la reserva se le debe entregar al usuario un c�digo univoco de reserva.
2) Una vez realizada la reserva el pasajero, con el c�digo de la misma, puede proceder a emitir el pasaje electr�nico, para ello debe realizar el pago (en esta etapa simulado). En el pasaje deben figurar todos los elementos identificatorios del viaje y debe ser descargable mediante un archivo PDF.
3) 48 hs. antes del vuelo y hasta 2 horas previas al despegue, el pasajero, habiendo pagado su pasaje, con el c�digo de reserva puede realizar el check-in en el cual selecciona gr�ficamente el asiento, y confirma el pasaje a partir del cual se emite un boarding-pass con un c�digo QR que contenga la informaci�n del pasaje y el c�digo de reserva. El boarding-pass debe ser impreso o descargado mediante un documento PDF.

A las 24 Horas de partir el vuelo, la compa��a realiza un chequeo de espacio vendido, si las reservas no han sido confirmadas, se informa a los pasajeros en lista de espera y se los habilita para realizar la compra del pasaje y el check-in. Siempre respetando el orden de llegada y para las cantidades m�ximas de pasajes a vender.

Semanalmente la compa��a emite informes de gesti�n que contengan la siguiente informaci�n:

Cantidad de pasajes vendidos
Cantidad de pasajes vendidos por categor�a y por destino
Ocupaci�n por avi�n y destino
Cantidad de reservas ca�das

La misma debe ser observada en gr�ficos estad�sticos e impresas nominalmente</p>

