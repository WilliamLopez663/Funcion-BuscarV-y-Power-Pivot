# :bookmark_tabs: Función BuscarV y Power Pivot
Este proyecto tiene como objetivo desarrollar una solución de análisis de datos en Excel utilizando la función BUSCARV y Power Pivot para relacionar información entre tablas. 
<br>

## BuscarV
- **Valor buscado**: ¿Que valor vamos a buscar?
- **Matriz tabla**: ¿Donde vamos a buscar?
- **Indicador de columnas**: ¿En que columna de la matriz se encuentra el dato que queremos buscar?
- **Rango**: **Verdadero**: Busqueda aproximada o **Falso**: Busqueda exacta.

Como ejemplode haré uso de la función `BuscarV` para traer la información de mi tabla país a mi tabla de datos pricipal:
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/base-de-datos.PNG">
</div>

:one: Crear el encabezado de nuestra tabla y justo debajo indicar la función =BuscarV y presionando en Fx se nos abre el siguiente cuadro:
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/insertar-funcion.PNG">
</div>
<br>

:two: Seleccionar el valor buscado, para este caso es el código del país:
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/valor-buscado.PNG">
</div>
<br>

:three: Seleccionar la Matriz donde hará la busqueda, tener en cuenta pulsa F4 para fijarla:
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/seleccionar-matriz.PNG">
</div>
<br>

:four: Colocamos el indicador de columna, para este caso es 2:
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/indicador-columna.PNG">
</div>
<br>

:five: En el rango indicamos Falso por que queremos una coincidecia exacta:
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/rango-falso.PNG">
</div>
<br>

:six: Por ultimo pulsamos aceptar y arrastramos la fórmula:
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/buscarv-final.PNG">
</div>

:link: **[FuncionBuscarV.xlsx](https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/docs/buscarv-final.xlsx)**
<br><br>


## Power Pivot
Es una tecnología de modelado de datos que permite crear modelos, establecer relaciones y crear cálculos.
Para este caso la usaremos para establecer relación entre nuestra tabla Datos y nuestra tabla País.

:one: Añadir la función Power Pivot a nuestro excel porque por defecto no viene:
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/añadir-funcion-power-pivot.PNG">
</div>
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/añadir-funcion-power-pivot2.PNG">
</div>
<br>

:two: Tener en cuenta que para poder realizar la conexión es necesario primero nombrar las tablas en el apartado de diseño:
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/nombrar-tabla.PNG">
</div>
<br>

:three: Ir al apartado de Datos y dar en la opción relaciones:
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/datos-relaciones.PNG">
</div>
<br>

:four: Se abre un cuadro para administrar nuestras relaciones y pulso nuevo luego selecciono las tablas que quiero relacionar y columna por la cual se relacionan:
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/administrar-relaciones.PNG">
</div>
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/crear-relacion.PNG">
</div>
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/relacion-creada.PNG">
</div>
<br>

- En la opción administrar de Power Pivot y vista de diagrama se puede visualizar la conexión de una forma mas gráfica.
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/power-pivot-administrar.PNG">
</div>
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/vista-diagrama.PNG">
</div>
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/vista-diagrama2.PNG">
</div>
<br>

:five: Voy a la opción tabla dinámica y selecciono usar modelo de datos:
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/insertar-tabla-dinamica.PNG">
</div>
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/usar-modelo-datos.PNG">
</div>
<br>

:six: Seleccionar los valores que queremos visualizar en nuestra tabla gracias a la conexión:
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/seleccionar-valores.PNG">
</div>
<div align="center">
  <img  src="https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/images/power-pivot-final.PNG">
</div>

:link: **[PowerPivotRelaciones.xlsx](https://raw.githubusercontent.com/WilliamLopez663/Funcion-BuscarV-y-Power-Pivot/main/assets/docs/power-pivot-final.xlsx)**
<br><br>
