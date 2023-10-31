# VC_P4

1. La primera aproximación que hemos realizado es un filtro que pinta un bigote sobre la cara detectada.

2. Otra idea ha sido coger distintas partes de la cara y trasladarlas a otras posiciones.

3. Por otro lado, hemos tenido la idea de dividir la cara en cuatro subframes y desordenarlos, de manera que haciendo uso del teclado podamos ordenarlos tal y como si fuera un puzzle. Con las teclas '1', '2', '3' y '4' seleccionamos uno de los frames empezando desde la esquina superior izquierda y acabando en la inferior derecha y una vez seleccionado un frame, pulsando las teclas 'a', 'w', 'd' y 's' podemos intercambiarlo de posición empezando de la misma manera desde la esquina superior izquierda hasta la inferior derecha.

4. Por último, hemos elaborado un filtro en el que una hamburguesa cae desde la parte superior de la pantalla en una coordenada x pseudoaleatoria haciendo uso de la librería random de python. El objetivo es comerse la hamburguesa, es decir una vez la separación entre tu labio superior y tu labio inferior sea mayor que 20, puedes comerte la hambuguesa, que una vez comida, hace respawn otra vez arriba. Además hemos añadido una puntuación para saber cuantas hamburguesas se han comido.
