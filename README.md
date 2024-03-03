Q_SalaClasificar v1.04.58 - (20240129)
--------------------
(Caso: TCK-20201-Y4V9)

1. Nuevo
  Repetir etiqueta de caja desde el WinForms "Lista de pesadas" - asignamos (mediante consultas SQL) sólo la posición de la caja en el pallet
	, no de todas las pesadas que haya hechas (nos proporciona optimización de recursos)
  Al cargar la partida => actualizar la lista de pesadas "Últimas pesadas"

2. Modificar
  Tras borrar y cerrar el WinForms de las lista de pesadas => actualizar la lista de pesadas "Últimas pesadas".
  Registrar pesada manualmente => hacer consultas para asignar el número de caja en el pallet 

Q_SalaClasificar v1.04.56 - (20240129)
--------------------
(Caso: TCK-20111-D9Z5)

1. Nuevo
  Lista "Pallets en partida" - cerrar pallet (crear pallet y asociarlo a las pesadas (cajas))

2. Modificar
  Tras borrar una pesada de la lista "Últimas pesadas" 
	=> actualizar la lista "Pallets en partida"
  Lista de "Últimas pesadas" - actualizar información de últimas pesadas - mejoras 