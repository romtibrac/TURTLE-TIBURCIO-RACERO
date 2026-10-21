# EJERCICIO M1

El ejercicio M1 ha sido realizado individualmente por Roman Libertad Tiburcio Racero (Grupo 1).

Se ha utilizado la IA exclusivamente como fuente de información sobre la libreria Turtle y de las 
funciones predefinidas dentro de la libreria, como .xcor(), pero no para escribir ninguna linea de código.

### Pruebas




- Ambas velocidades positivas: termina y anuncia una ganadora:

    Al establecer una velocidad RED_SPEED = 10 y BLUE_SPEED = 5, donde ambas son positivas y la velocidad 
    de la roja es el doble que la de la tortuga azul. Al iniciarse, el juego se ejecuta, anunciando la
    victoria de la tortuga roja con el mensaje: "¡Ha ganado la tortuga roja!".

    Si invertimos las velocidades, siendo la azul el doble, el juego se ejecuta igual con la diferencia de que el azul gana,
    saltando el mensaje: "¡Ha ganado la tortuga azul!".

    En ambos casos, al ser velocidades positivas anuncian una ganadora.

- Roja más rápida: gana la roja:

    Aunque esta parte se ha comprobado en el apartado anterior, si establecemos la diferencia mínima, con las 
    velocidades RED_SPEED = 11 y BLUE_SPEED = 10, el mensaje de victoria de la roja se imprime.

- Azul más rápida: gana la azul:

    Al igual que en los apartados anteriores, si la tortuga azul lleva una velocidad mayor salta el mensaje 
    de victoria de la azul. Incluso probando el ejemplo anterior con la superioridad del azul, esta se lleva
    la victoria.

- Velocidades iguales: anuncia un empate (no puede ganar siempre la roja):

    Al establecer velocidades iguales, por ejemplo 10, salta el mensaje "¡Empate! Las dos tortugas llegan a la vez". 
    Incluso probando velocidades como 100, o incluso 10000(la cual rompe con el juego, saliendose las tortugas 
    de las pantalla), salta este mismo mensaje.

- Alguna velocidad igual a cero o negativa: muestra el aviso y no inicia la carrera:

    Probando RED_SPEED = 0, el juego se detiene y se imprime el mensaje "Las velocidades deben de ser positivas."
    Si sustituimos la velocidad por una negativa, pasa exactamente lo mismo.

    Al igual que con la tortuga roja, si establecemos una velocidad de la tortuga azul 0 o negativa salta el mismo
    mensaje. Si se establecen ambas negativas o 0, salta el mismo mensaje y se para el juego.


# PRUEBAS

- RED_SPEED = 10 y BLUE_SPEED = 5: Al ser la velocidad de la roja mayor, esta ganará. Gana la tortuga roja, 
saltando el mensaje de victoria de la roja.

- RED_SPEED = 5 y BLUE_SPEED = 10: Al ser la velocidad de la azul mayor, esta ganará. Gana la tortuga azul, 
saltando el mensaje de victoria de la azul.

- RED_SPEED = 5 y BLUE_SPEED = 5: Al ser las velocidades iguales, será un empate. En efecto, salta el mensaje
de empate.

- Probando RED_SPEED = 0 y BLUE_SPEED = 5. El juego se detendrá. En efecto, el juego se detiene y se imprime el mensaje "Las velocidades deben de ser positivas."
- Probando RED_SPEED = 5 y BLUE_SPEED = -5. El juego se detendrá. En efecto, el juego se detiene y se imprime el mensaje "Las velocidades deben de ser positivas."