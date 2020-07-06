# EventosdelMouse-C9

Proyecto Grupo de Trabajo Interface Grafica 
Diana Valentina Uscategui Tobo - 20172020063

Se le agrego interactividad al proyecto por medio de los eventos del mouse, se reconoció el enfoque de discriminación por tipo de clases para manejar la interactividad con diferentes objetos gráficos a la vez desde un método implementado de eventos.

# Implementacion de Eventos del mouse 

En todas las clases que se requeria el uso de eventos del mouse se implemento MouseActionListener, como en la imagen:

![implementacionmo]()


# Representación única para objetos gráficos de una misma Clase

En los metodos implementados por la interface MouseActionListener para que los objetos escucharan la acción que se desea, se hizo una representción unica para todos los objetos gráficos que escuchan la acción de la misma clase

![imagenmetodos](https://github.com/valentinatobo/EventosdelMouse-C9/blob/master/Proy_Twitter/imagenes/implementacionmouse.PNG)

Lo que se hizo es que al dar click en el panel para hacer tweet se borre la frase ¿Qué esta pasandp? 

![contexto](https://github.com/valentinatobo/EventosdelMouse-C9/blob/master/Proy_Twitter/imagenes/contexto.PNG)

![sintexto](https://github.com/valentinatobo/EventosdelMouse-C9/blob/master/Proy_Twitter/imagenes/sintexto.PNG)

# Discriminación de Clases

![ejemplodiscriminacion](https://github.com/valentinatobo/EventosdelMouse-C9/blob/master/Proy_Twitter/imagenes/objetoscombinados.PNG)

# Efectos hacia otros objetos Gráficos

En este caso se dio la interactividad entre la escucha de varios objetos graficos y como estos tienen efectos en otros

![codigo](https://github.com/valentinatobo/EventosdelMouse-C9/blob/master/Proy_Twitter/imagenes/objetoscombinados.PNG)

Al dar click en los label del login la letra y el borde cambian de color y al quedar vacio y dar clic en el otro vuelve a gris el borde y la letra a gris oscuro 

![imagenejemplolabel](https://github.com/valentinatobo/EventosdelMouse-C9/blob/master/Proy_Twitter/imagenes/inicio.PNG)

# Uso combinado de varios Métodos implementados de eventos

Se implemento la interface MouseMotionListener que a la vez se convino con eventos del mouse lintener 

![codigomousemotion](https://github.com/valentinatobo/EventosdelMouse-C9/blob/master/Proy_Twitter/imagenes/minimizar.PNG)

# Se agrego el boton minimizar junto con cerrar 

![codigo]()

![panelbotones]()