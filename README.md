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
<br>


## Power Pivot
Es una tecnología de modelado de datos que permite crear modelos, establecer relaciones y crear cálculos.
