# aviones-
Una empresa comercial que se dedica a la creación y venta de vehículos como de aviones, está diseñando un nuevo sistema para manejar estos. De los vehículos se necesita saber: marca, color, cilindraje, número de puertas, velocidad. De los aviones se necesita saber lo siguiente: tipo (puede ser comercial, privado), número de matrícula, capacidad de tripulantes y de pasajeros, velocidad, altitud. Tanto los aviones como los vehículos tienen los siguientes métodos: disminuirVelocidad (), aumentarVelocidad (). En el caso del vehículo, el método aumentarVelocidad, valida que la velocidad no pase más de 150 km si este pasa la velocidad desplegar un mensaje que diga “El vehículo alcanzó la máxima velocidad”. Para los aviones, el método aumentarVelocidad deberá validar lo siguiente: Si la velocidad a aumentar está entre 200 y 250, deberá validar que la altitud sea encuentre entre 1200 y 1500. Si la altitud es menor que la cantidad mencionada deberá desplegar el mensaje “La altitud no es lo suficiente para la aceleración. Si la velocidad está entre 251 y 500, deberá validar que la altitud sea mayor que 1500 y menor que 1700. Si la altitud es menor que el rango mencionado deberá desplegar el mensaje “La altitud no es lo suficiente para la aceleración. Por último, si la velocidad está entre 501 y 700, deberá validar que la altitud sea mayor que 1700 y menor que 2000. Si la altitud es menor que el rango mencionado deberá desplegar el mensaje “La altitud no es lo suficiente para la aceleración. En el caso del vehículo, el método disminuirVelocidad, deberá validar que este no sea menor que 0, si se intenta disminuir la velocidad y está se pasa de 0 (es decir, un valor negativo). Deberá desplegar el mensaje “El vehículo está detenido, no se puede reducir la velocidad”. Para los aviones, el método disminuirVelocidad, deberá validar lo siguiente: Si la altitud está entre 2000 y 1700, la velocidad no deberá disminuir de 2000. Si la altitud está entre 1700 y 1500 la velocidad no deberá disminuir de 1500. Si no se cumple lo anterior deberá desplegar el mensaje siguiente: “La aeronave no puede disminuir la velocidad para la altitud actual”. Con lo anterior desarrolle: Tanto para los vehículos como los aviones genere el constructor, el método toString() deberá desplegar la información de cada uno de los objetos. Desarrolle e implemente una interfaz con los métodos aumentarVelovidad, disminuirVelocidad ambos deberán recibir como parámetros un objeto, y la velocidad a acelerar o disminuir. En cada método usted deberá validar el tipo de objeto que está recibiendo como parámetro. Cree dos objetos de cada tipo, almacenelos en un mismo arreglo, luego recorra el arreglo e imprima las características del objeto.    
