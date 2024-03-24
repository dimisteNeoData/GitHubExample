## NeoSala v2.7.162 (20240229) - WS_Default = v2.1.102 (EcoSistema NeoMeat: WS_Planta_v1.0.2.40) - NeoDataCoreDll = v1.1.0.86 - NeoDataSalaDll - 1.1.0.113		

### Recepción 
	(muchos de los procesos recuperan los datos de las tablas NeoCore o directamente desde AX de acuerdo con el check: 
	Configuración - Datos de conexión - Usar WS Planta. En un futuro iremos aplicando este cambio a todo el software aplicativo)
<ol>
 	<li>líneas - comprobar la obligatoriedad de las dimensiones de almacenamiento de acuerdo con: "Recepción en Blanco"</li>
 	<li>pantalla pesaje manual - Divisor - ajustes texto</li>
 	<li>líneas - datos trazables - mostrar la etiqueta de las dimensiones en rojo/gris de acuerdo con la propiedad: "Recepción en Blanco"</li>
 	<li>al hacer pesada - refactorizar lógica de comprobar si se han entrado todas las variantes</li>
 	<li>atributos de lote - comportamiento fecha límite inferior => igualmente avisa si la fecha es inferior a la de día de hoy, pero deja le fecha que ha puesto el operario</li>
 	<li>borrar pesadas - pasar como cantidades para borrar: cantidad Inventario y cantidad PC (WS_Default)</li>
 	<li>btn "Configuración Etiquta" - check emitir etiqueta - relacionarlo con las configuraciones generales</li>
	</ol>

### Conciliar
<ol>
 	<li>Conciliar - No permitir que se finalice con precio de compra 0</li>
 	<li>Conciliar - ajustar Decimal converter</li>
 	<li>Conciliar - Precios - añadir columnas: PrecioEstimado y Totales</li>
	</ol>
 
### Entrada
<ol>
 	<li>descargar ristra - imprimir etiqueta original (etiqueta de lista de selección) si tenemos el check "Emitir etiq. Original"</li>
	<li>descargar ristra - imprimir etiqueta deshuese (etiqueta de posibles coProductos) si tenemos el check "Emitir etiq. Deshuese"</li>
	<li>descargar ristra - considerar ristra como impresa si como mínimo se ha impreso a la etiqueta del diario de lista de selección o los posibles coProductos</li>
	<li>btn "Emitir etiqueta orden" - avisar si no hay configuración de la etiqueta de Deshuese (coProductos)</li>
	<li>si btn "Emitir etiqueta orden" visible y no tenemos la etiqueta de Deshuese (coProductos) configurada => colorear el boton de color rojo</li>
	</ol>

### Salida
<ol>
 	<li>btn "Configuración Etiquta" - check emitir etiqueta - relacionarlo con las configuraciones generales</li>
	</ol>

### Producir
<ol>
 	<li>btn "Configuración Etiquta" - check emitir etiqueta - relacionarlo con las configuraciones generales</li>
	</ol>

### Asociar Caja
<ol>
 	<li>productos entrados - botón "Cambiar producto"</li>
 	<li>productos entrados - pantalla "Acciones de Productos"</li>
	</ol>

### Configuración
<ol>
 	<li>Entrada - sección Ristra - refactorizar labels</li>
	</ol>


 ## NeoSala v2.7.160 (20240216) - WS_Default = v2.1.98 (EcoSistema NeoMeat: WS_Planta_v1.0.2.38) - NeoDataCoreDll = v1.1.0.84 - NeoDataSalaDll - 1.1.0.111	

### Entrada (tablas NeoCore)
<ol>
 	<li>Registrar pesada - insertar posibles coProductos en Neo_deshuese de acuerdo con el check "Emitir etiqueta orden" en: Sala - Configuración - Entrada</li>
  	<li>DesRegistrar pesada - eliminar posibles coProductos en Neo_deshuesede acuerdo con el check "Emitir etiqueta orden" en: Sala - Configuración - Entrada</li>
  	<li>Entrada - Imprimir etiqueta Ristra Original - añadir parámetros: usuario, terminal</li>
	<li>Entrada - Imprimir etiqueta Ristra coProductos - añadir parámetros: usuario, terminal</li>
	</ol>

### Salida
<ol>
 	<li>PESADA - al hacer una pesada si esta en el rango de peso cambiar un producto por otro si esta habilitado la opcion producto generico y la formula tiene productos genericos</li>
	</ol>
 
### Configuración
<ol>
 	<li>Datos Conexión - incorporar WS principal y WS Secundario</li>
	<li>Salida - añadir opcion producto generico</li>
	</ol>

