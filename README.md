# NeoSala v2.7.160 (20240216) - WS_Default = v2.1.98 (EcoSistema NeoMeat: WS_Planta_v1.0.2.38) - NeoDataCoreDll = v1.1.0.84 - NeoDataSalaDll - 1.1.0.111	

- Entrada (tablas NeoCore) 
		Registrar pesada - insertar posibles coProductos en Neo_deshuese de acuerdo con el check "Emitir etiqueta orden" en: Sala - Configuraci�n - Entrada
		DesRegistrar pesada - eliminar posibles coProductos en Neo_deshuesede acuerdo con el check "Emitir etiqueta orden" en: Sala - Configuraci�n - Entrada
		Entrada - Imprimir etiqueta Ristra Original - a�adir par�metros: usuario, terminal
		Entrada - Imprimir etiqueta Ristra coProductos - a�adir par�metros: usuario, terminal
- Salida
		PESADA - al hacer una pesada si esta en el rango de peso cambiar un producto por otro si esta habilitado la opcion producto generico y la formula tiene productos genericos	
- Configuraci�n
		Datos Conexi�n - incorporar WS principal y WS Secundario
		Salida - a�adir opcion producto generico