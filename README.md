# Actividad-evaluable-casos-de-uso-Jaime-Muñoz-Vías-1ºDAM

## Descripción de los casos de uso: 

**1.Actores:**

**-Cajero**

**Cliente**

### Casos de uso del Cajero:

**-Validacíon sistema:** valida clave de inicio de la sesión.

**-Abre sesión de la cuenta:** abre la sesión si la validación es correcta y si es correcta y se abre la sesión se cargan o actualizan los datos del cliente.

**-Cerrar la sesión:** cierra la sesión de la cuenta si se ha abierto correctamente.

### Casos de uso del Cliente:

**-Introducir clave:** El cliente introduce una clave para que el sistema se valide.

**-Realizar operación:** Una vez que el sistema se inicia y la clave es correcta el sistema te pide realizar una operacion.

**-Ingresar dinero:** Una de las operaciones posibles la cual se encarga de recargar dinero en la cuenta para posteriormente actualizar los datos de esta.

**-Sacar dinero:** Se encarga de sacar dinero de la cuenta para posteriormente poder actualizar los datos, sin embargo no se podra sacar dinero si no hay en la cuenta por lo que se ejecutara un aviso.

**-Avisar saldo insuficiente:** Mensaje de error que se ejecuta si se quiere sacar dinero y no hay en la cuenta.

**-Hacer transferencia:** Es una de las tres operaciones disponibles la cual se encarga de traspasar dinero de una cuenta a otra.

**-Actualizar datos de la cuenta:** Se encarga de actualizar los datos de la cuenta y de cargar la sesión de la cuenta si se entra en ella o cada vez que se hace un movimiento dentro de esta.
