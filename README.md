# ARSW-ImmortalCase

# Integrantes:
Willson Melo Merchan  
Jeymar Vega

### PART 1
#
El comportamiento se mantiene casi constante debido a que el consumidor esta preguntando constantemente dependiendo de si la cola contiene algo.
# La clase responsable es StartProduction ya que es la que inicia la producción.
![alt text1](https://github.com/Stilink/ARSW-ImmortalCase/blob/master/img/producer-consumer.png)
#
Luego tratamos de mejorar el rendimiento con las condiciones de una producción lenta y un consumo rápido. Se visualiza un cambio gigante en el consumo.
![alt text1](https://github.com/Stilink/ARSW-ImmortalCase/blob/master/img/2-producter-consumer.png)
#
Por ultimo pasamos a hacer una producción rápida y un consumo lento, el consumo varía solo un poco me atrevería a decir que esos pequeños picos que se ven en la gráfica reflejan el momento en el cual se comienza a cosnumir
![alt text1](https://github.com/Stilink/ARSW-ImmortalCase/blob/master/img/3-producter-consumer.PNG)


### PART 2
InmortalCase
# 
Para N jugadores, asumiendo que el invariente se mantiene, al revisar la suma debería dar N*100.

Al ejecutar el programa y presionar el boton pause and check no solo no se detiene el programa, tampoco se mantiene el invariante.
![alt text1](https://github.com/Stilink/ARSW-ImmortalCase/blob/master/img/Confirmacion_salud.PNG)
![alt text1](https://github.com/Stilink/ARSW-ImmortalCase/blob/master/img/Confirmacion_salud_2.PNG)

#

Para solucionar el pause and check solo tuvimos que crear un booleano atomico que sirve para saber si los hilos deben continuar o detenerse, despues sincronizar la lista de inmortales para poder hacer una suma segura.
![alt text1](https://github.com/Stilink/ARSW-ImmortalCase/blob/master/img/Pause.PNG)
![alt text1](https://github.com/Stilink/ARSW-ImmortalCase/blob/master/img/pause2.PNG)

#

Despues de esto el pause and check quedó funcionando y también el invariante se mantiene.
![alt text1](https://github.com/Stilink/ARSW-ImmortalCase/blob/master/img/FuncPause.PNG)

#

Por ultimo implementamos el resume
![alt text1](https://github.com/Stilink/ARSW-ImmortalCase/blob/master/img/codeResume.PNG)

#

Imágen del funcionamiento
![alt text1](https://github.com/Stilink/ARSW-ImmortalCase/blob/master/img/funcResume.PNG)



