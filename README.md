# WindSensor
###### This repository explain the funtion of the Wind-Sensor module with two programs

##### El Windsensor Rev P es un módulo que mide la rapidez del viento, tiene integrado para compensación o ajuste, un sensor de temperatura, los códigos probados están en la carpeta **SRC** y son tres:

  1. [**windHuertero**](https://github.com/jwilliamsee/WindSensor/tree/main/SRC/windHuertero): código trabajado en el IER por Miguel Ángel Huertero
  2. [**windFabricante**](https://github.com/jwilliamsee/WindSensor/tree/main/SRC/windFabricante): código que ha sido trabajado por Rafael Moya y Daniel Prohaskycon, en donde realizaron pruebas prácticas en un mini tunel de viento con la intención de calibrarlo, mencionan que se conectaron hasta 6 Windsensor Rep P para sus pruebas.
  3. [**windMiniTunel**](https://github.com/jwilliamsee/WindSensor/tree/main/SRC/windMiniTunel): código de prueba proporcionado por el fabricante del Windsensor Rev P y que también fue probado.

##### Para la opción que se elija, encontrarán pequeñas diferencias, la que se ha trabajado en el IER por Miguel Huertero es con el que debería empezar o darle prioridad para usarlo, debido a que se hicieron pruebas según las condiciones y necesidades para las que realmente se ocupan y si se decide trabajar con otra de las 2 restantes, dependerá del rango de velocidad del viento que desea medir.

#### WindHuertero
##### En esta carpeta se encuentra el código trabajado por Miguel Ángel Huertero, con las condiciones requeridas en el IER, el rango de velocidad que se usó para las pruebas es de 2 a 3 (m/s), por lo que para esos rangos de velocidad funcionará este código, la información necesaria de todo el trabajo realizado por Miguel Huertero se encuentra en el PDF, para cualquier consulta y demás información que requiera en cuanto a las pruebas de calibración, algo a destacar en este trabajo, es que llegaron a la conclusión que para las lecturas de la rapidez del viento no es necesario la compensación por temperatura.

#### windFabricante
##### En esta carpeta se encuentra el código proporcionado por el fabricante del Wind Sensor Rev. P, los rangos de velocidad que se usaron para estas pruebas es de 0 a 150(MPH) o 0 a 67.056(m/s), muy elevado, pero puede llegar a usarse en algún momento, para exteriores, la información de la calibración entre otras cosas, se puede encontrar en la pág. del fabricante:
[**Pág. Fabricante**](https://moderndevice.com/product/wind-sensor-rev-p/)

#### windMiniTunel
##### En esta carpeta se encuentra el código trabajado por Rafael Moya & Daniel Prohasky, es una adaptación del fabricante, en donde se complementó el código para leer 6 Wind Sensor Rev. P al mismo tiempo, se pueden ir quitando parte del código hasta quedar a uno o 2 lecturas, según las necesidades, por ejemplo para esta prueba se quedó con lectura de 1 sólo sensor. Algo a destacar es que se hicieron puebas muy controladas, realmente no cambió con respecto a las variables y constantes usadas en el código del fabricante, es una adaptación para 6 sensores, pero pueden sacarse muchas conclusiones de el trabajo realizado por ellos.
##### El rango de velocidad usado en la prueba del Mini-Tunel es de 0 a 4.5 (m/s).

------------


##### Entre las cosas a destacar en lecturas de viento con el Wind Sensor Rev. P es, que lo ideal para trabarlo, es ponerlo en una caja con sólo la parte frontal del sensor a la entrada del viento o la direciión del viento, debido a que si afecta al momento de calibrarlo que le llegue viento por otras partes, para lecturas después de calibrarlo no es tan necesario pero igual puede ayudar a medir lo que realmente se necesita, una forma de usarlo puede ser en un tubo, para que el sensor realmente mida enla dirección del flujo de aire requerido, otra cosa a destacar es, que la forma correcta de que el wind sensor mida bien, es que el sensor reciba el flujo de aire como en una especie de cono a 30° si se pasa de esa inclinación o si se deja medir al aire sin cubrirlo medirá el flujo de aire al más movimiento mínimo que exista cerca.

##### Una muestra de como se colocó en un tubo improvisado es esto:

![](https://github.com/jwilliamsee/WindSensor/blob/main/Imagenes/windS1.jpg)


------------

![](https://github.com/jwilliamsee/WindSensor/blob/main/Imagenes/windS.jpg)

------------
##### El diagrama de conexión se encuentra en la carpeta **Diagramas**, el pin a donde se conecte dependerá del código o la placa que desea usar.
##### Diagrama de conexión en TinkerCAD
![](https://github.com/jwilliamsee/WindSensor/blob/main/Diagramas/PictogramaTinkerCAD.JPG)

##### Diagrama de conexión en Fritzing
![](https://github.com/jwilliamsee/WindSensor/blob/main/Diagramas/Pictograma.jpg?raw=true)

### A continuación se muestran las lecturas de cada código, la velocidad que se suministraba no se tiene controlado (no sé conoce), la diferencia entre uno y otro no debe variar mucho, pero la que se tiene que considerar es la de Miguel Huertero.

### Miguel Huertero
![](![image](https://user-images.githubusercontent.com/69220950/128098648-ccbc2380-e17e-481b-8f11-9b0b84fad788.png)
------------

### Fabricante
![](https://github.com/jwilliamsee/WindSensor/blob/main/Imagenes/windFabricante.JPG?raw=true)
------------

### Mini-Tunel
![](https://github.com/jwilliamsee/WindSensor/blob/main/Imagenes/windMiniTunel.JPG?raw=true)
------------


