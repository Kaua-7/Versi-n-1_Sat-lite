(header)

# Proyecto grupo 9
Repositorio con los códigos del grupo 9 formado por: Jan Fernández, Kaua Vieira e Ingrid Rojano.

Última versión publicada: versión 3 del proyecto.

## Funciones disponibles en la versión 4:


## Arduino satélite:
**1.** El satélite recoge y envía los valores de temperatura y humedad desde el sensor DHT y los valores de distancia medidos por el sensor de ultrasonidos, que se encuentra en movimiento por el servomotor. 

**2.** Incluye un mecanismo de checksum que permite descartar los mensajes que han sufrido alteraciones durante la transmisión.

**3.** Existe comunicación inalámbrica entre el satélite y la estación de tierra.


## Estación de tierra:
**1.** Incluye LED's de diferentes colores, verde y rojo, el primero se ilumina reiteradamente cada vez que la estación reciba datos en caso de fallos de comunicación el LED que se iluminará será el rojo y verde dejará de hacerlo.



## Interfaz gráfica:
**1.** Los datos registrados se reciben en la estación de tierra y estos se presentan en una interfaz gráfica.

**2.** Tres gráficas representan la evolución de la temperatura, su media y la humedad.

**3.** En la interfaz el usuario puede controlar: el intervalo de envío de datos, de cuantos valores hacer la media de temperatura si esta se calcula en el Arduino o en Python. Seleccionar además un valor máximo de temperatura, y en caso de que las últimas tres medias lo superen hacer sonar una alarma.

**4.** En lo referente al servo, el usuario puede pedir un barrido continuo o un ángulo determinado.

**5.** Se incluye también un fichero que registra todos los datos, errores, cambios realizados y observaciones del usuario. Junto con la fecha y hora que estos se realizan. 

**6.**  Una simulación del período orbital del satélite en 3D.

**7.** 

## Vídeos de las versiones:
-Versión 1

-Versión 2

-Versión 3

-Versión 4


