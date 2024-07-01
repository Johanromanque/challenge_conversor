Mi nombre es Johan.

Este programa es una aplicación de consola en Java para convertir entre diferentes monedas. Utiliza un menú interactivo para permitir al usuario seleccionar el tipo de conversión que desea realizar. Las opciones incluyen conversiones entre dólares estadounidenses (USD), pesos chilenos (CLP), reales brasileños (BRL) y pesos colombianos (COP), así como la posibilidad de convertir a otras monedas no listadas en el menú principal.

El programa funciona de la siguiente manera:

Se inicializa un Scanner para leer la entrada del usuario y una instancia de ConsultarMoneda para manejar las consultas de tasas de cambio.
Se muestra un menú con varias opciones de conversión.
El usuario selecciona una opción, que se lee y procesa en un bucle while.
Dependiendo de la opción seleccionada, se llama al método correspondiente en la clase ConvertirMoneda para realizar la conversión.
El programa continúa mostrando el menú hasta que el usuario selecciona la opción de salir.
Las conversiones se manejan a través de métodos estáticos en la clase ConvertirMoneda, que interactúan con la instancia de ConsultarMoneda para obtener las tasas de cambio necesarias