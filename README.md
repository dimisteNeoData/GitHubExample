Q_SalaClasificar v1.04.58 - (20240129)
--------------------
(Caso: TCK-20201-Y4V9)

1. Nuevo
  Repetir etiqueta de caja desde el WinForms "Lista de pesadas" - asignamos (mediante consultas SQL) s�lo la posici�n de la caja en el pallet
	, no de todas las pesadas que haya hechas (nos proporciona optimizaci�n de recursos)
  Al cargar la partida => actualizar la lista de pesadas "�ltimas pesadas"

2. Modificar
  Tras borrar y cerrar el WinForms de las lista de pesadas => actualizar la lista de pesadas "�ltimas pesadas".
  Registrar pesada manualmente => hacer consultas para asignar el n�mero de caja en el pallet 

Q_SalaClasificar v1.04.56 - (20240129)
--------------------
(Caso: TCK-20111-D9Z5)

1. Nuevo
  Lista "Pallets en partida" - cerrar pallet (crear pallet y asociarlo a las pesadas (cajas))

2. Modificar
  Tras borrar una pesada de la lista "�ltimas pesadas" 
	=> actualizar la lista "Pallets en partida"
  Lista de "�ltimas pesadas" - actualizar informaci�n de �ltimas pesadas - mejoras 