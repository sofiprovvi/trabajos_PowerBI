En este trabajo me encargué de limpiar la base de datos "ventas.xlsx", con el archivo pbix "negocio":

1)Descargué el recurso de la clase e importé el archivo con conjunto de datos proporcionado a Power BI utilizando Power Query.

2)Eliminé todos los registros que no contenían información de ventas (o sea, ventas iguales a 0).

3)Ordené los datos por fecha de venta de más reciente a más antigua.

4)Identifiqué y eliminé los registros duplicados basados en la combinación de ID de producto y fecha de venta.

5)Aseguré los tipos de datos. Por ejemplo, que la columna de 'Cantidad Vendida' esté configurada como entero y la columna de 'Precio' como decimal.

6)Agregué una tabla nueva con cada producto y su cantidad total vendida.
