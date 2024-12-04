# **Happy Path para Ingresar la CURP**


 -  **Inicio en caso de no conocer la CURP:**



	-   Si el usuario no conoce su CURP, selecciona la opción "¿No conoces tu CURP? Dale click aquí".

	-   La aplicación redirige al usuario a una página o formulario para ingresar sus datos personales.



 -  **Ingreso de Datos Personales:**



	-   El usuario ve la pantalla para ingresar sus datos personales.

	-   El usuario introduce su(s) nombre(s), primer apellido y segundo apellido en los campos correspondientes.

	-   El usuario presiona el botón "Siguiente".

	-   La aplicación utiliza los datos ingresados para buscar o generar la CURP del usuario.



 -  **Ingreso de Fecha de Nacimiento y Selección de Género:**



	-   El usuario ve la pantalla para ingresar su fecha de nacimiento y seleccionar su género.

	-   El usuario introduce el día, mes y año de nacimiento en los campos correspondientes.

	-   El usuario selecciona su género marcando la casilla correspondiente (Masculino, Femenino, No Binario).

	-   El usuario presiona el botón "Siguiente".



 -  **Selección del Estado Federativo:**



	-   El usuario ve la pantalla para seleccionar su estado federativo.

	-   El usuario elige su estado de la lista desplegable.

	-   El usuario presiona el botón "Siguiente".



 -  **Ingreso de Homoclave:**



	-   El usuario ve la pantalla para ingresar su homoclave.

	-   El usuario introduce la homoclave en el campo de texto correspondiente.

	-   La interfaz proporciona un ejemplo de cómo encontrar la homoclave en una tarjeta de identificación de elector (CIC y OCR).

	-   El usuario presiona el botón "Siguiente".



 -  **CURP Generada:**



	- El usuario ve la pantalla final donde se presenta su CURP generada.

	- La aplicación muestra la CURP junto con todos los datos personales que se utilizaron para generarla.

	- El usuario puede ver, guardar o copiar su CURP desde esta pantalla.

	- La aplicación confirma que la CURP ha sido generada exitosamente.



 - **Flujo Alternativo (Por si acaso):**



	- Si el usuario ingresa una CURP incorrecta:

	- La aplicación muestra un mensaje de error indicando que el formato de la CURP es incorrecto y permite al usuario intentar de nuevo.de error indicando que el formato de la CURP es incorrecto y permite al usuario intentar de nuevo.



# **Documentación**



**La idea de cambiar él UI y hacer uno diferente se tomó con base en las observaciones que realizamos como equipo, pues logramos identificar dos puntos clave al momento de comparar la aplicación con el contexto en el cual se utilizó.**



**En primer lugar, suponemos que la manera en la cual se pedían los datos a los adultos mayores era de forma “brusca”, es decir, solicitaban mucha información de golpe y eso provocaba que los usuarios se agobiaran e incluso frustraran al momento de proporcionar los datos. Por lo que, optamos por dividir en secciones distintas la información que se necesita ingresar con el fin de mejorar la comodidad visual.**



**Como segundo punto, el cual puede parecer muy trivial, en realidad es de suma importancia. El tamaño del texto con el cual se pedía cada apartado era algo reducido y esto para personas de la tercera edad que, en su mayoría, por no decir en su totalidad tienen problemas de la vista. Lo que los obligaba a hacer un esfuerzo extra para poder entender que era lo que les pedían. Es por esa razón que agrandamos más el tamaño de cada texto.**
