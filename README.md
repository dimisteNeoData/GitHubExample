# NeoSala v2.7.160 (20240216) - WS_Default = v2.1.98 (EcoSistema NeoMeat: WS_Planta_v1.0.2.38) - NeoDataCoreDll = v1.1.0.84 - NeoDataSalaDll - 1.1.0.111	

- Entrada (tablas NeoCore) 
--Registrar pesada - insertar posibles coProductos en Neo_deshuese de acuerdo con el check "Emitir etiqueta orden" en: Sala - Configuración - Entrada
--DesRegistrar pesada - eliminar posibles coProductos en Neo_deshuesede acuerdo con el check "Emitir etiqueta orden" en: Sala - Configuración - Entrada
--Entrada - Imprimir etiqueta Ristra Original - añadir parámetros: usuario, terminal
--Entrada - Imprimir etiqueta Ristra coProductos - añadir parámetros: usuario, terminal
- Salida
		PESADA - al hacer una pesada si esta en el rango de peso cambiar un producto por otro si esta habilitado la opcion producto generico y la formula tiene productos genericos	
- Configuración
		Datos Conexión - incorporar WS principal y WS Secundario
		Salida - añadir opcion producto generico
