# Challenge ONE Java Backend -- Conversor De Monedas

Este 

## 1. Requisitos
- Tener instalado Java JDK: versión 11 en adelante.
- Tener instalado IDE (Entorno de Desarrollo Integrado) IntelliJ IDEA.
- Acceso a internet para realizar consulta a la API.

## 2. Pasos a seguir
a. Clona o descarga este repositorio de GitHub en tu equipo.
b. Abre el proyecto en IntelliJ IDEA.
c. Ejecuta la clase `Principal.java` para iniciar el programa la manera mas facil de ejecutarlo es con la combinacion de teclas `SHIFT + F10` o `Mayus + F10` esto depende de como este en su teclado.

## 3. Como utilizar el programa
a. Nos muestra el menu del programa despues de hacer correr el programa

![1.png](image%2F1.png)

b. Primero presionamos la tecla `C` o `c` seguido de enter para ingresar
   la opcion que escogimos despues de ingresar la opcion escogida 
   volvemos a presionar enter

![2.png](image%2F2.png)

c. Se vuelver a repetir los mismos pasos

![3.png](image%2F3.png)

d. Ingresamo el monto deseado a convertir y presionamos la tecla enter

![4.png](image%2F4.png)

e. Nos muestra la conversion y presionamos la tecla `S``s` o `N``n` si deseamos ver el historial de conversion

![5.png](image%2F5.png)

## 4. Estrura de carpetas
- **src**: Contiene los archivos fuente del programa Java.
    - `Menu.java`: Clase que maneja la interfaz de usuario y las opciones del menú.
    - `Conversion.java`: Clase que realiza las conversiones de moneda.
    - `ConsultaApi.java`: Se realiza la consulta a la "Exchange Rate API".
    - `Moneda.java`: Clase que representa una moneda en el sistema de conversión de moneda.
      Contiene atributos como el nombre de la moneda, su código ISO, y
      métodos para obtener y establecer estos atributos, así como cualquier
      funcionalidad relacionada con la moneda en el sistema.
    - `RegistroConversion.java`: Clase que registra las conversiones realizadas, incluyendo información
      sobre la moneda base, la moneda de destino, el valor convertido y la marca de tiempo.
    - `Principal.java`: Clase principal que inicia el programa y maneja el flujo principal de ejecución.

