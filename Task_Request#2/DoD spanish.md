> # Definition Of Done
> El DoD define los criterios que cada historia de usuario debe cumplir para considerarse "hecha".

# Requerimientos funcionales

### 1.  Registro  en  el  sistema
**Definition  of  Done:**
 - El  formulario  de  registro  está  desarrollado  y  accesible  en   
   la  página  de  registro.
 -   El  formulario  permite  la  entrada  de  nombre  de  usuario,  correo  electrónico,  contraseña  y  selección  de  rol  (estudiante     o  tutor).
 -   Todos  los  campos  son  validados  (formato  de  correo  electrónico  correcto,  contraseña  segura,  etc.).
 -   Al  enviar,  los  datos  se  almacenan  correctamente  en  la  base  de  datos.
 -   Un  mensaje  de  confirmación  se  muestra  al  usuario  tras  el  registro  exitoso.
 -   Pruebas  unitarias  y  de  integración  están  completadas  y  aprobadas.
 - Documentación  actualizada  y  aprobada.


### 2.  Verificación  de  correo  electrónico
**Definition  of  Done:**
-   Después  del  registro,  el  sistema  envía  un  correo  de  verificación  al  usuario.
-   El  correo  contiene  un  enlace  único  y  seguro  para  la  verificación.
-   Al  hacer  clic  en  el  enlace,  la  cuenta  del  usuario  se  marca  como  verificada  en  la  base  de  datos.
-   Un  mensaje  de  confirmación  se  muestra  al  usuario  tras  la  verificación  exitosa.
-   Pruebas  unitarias  y  de  integración  están  completadas  y  aprobadas.
-   Documentación  actualizada  y  aprobada.
    

### 3.  Inicio  de  sesión

**Definition  of  Done:**

-   La  página  de  inicio  de  sesión  está  desarrollada  y  accesible.
-   Los  usuarios  pueden  ingresar  su  correo  electrónico  y  contraseña.
-   Las  credenciales  son  validadas  contra  los  registros  de  la  base  de  datos.
-   Acceso  exitoso  redirige  al  usuario  a  la  página  principal.
-   Un  mensaje  de  error  claro  y  específico  se  muestra  si  las  credenciales  no  son  válidas.
-   Pruebas  unitarias  y  de  integración  están  completadas  y  aprobadas.
-   Documentación  actualizada  y  aprobada.
  

### 4. **Recuperación de contraseña**

**Definition of Done:**

-   El formulario de recuperación de contraseña está desarrollado y accesible desde la página de inicio de sesión.
-   Los usuarios pueden ingresar su correo electrónico registrado para solicitar la recuperación de contraseña.
-   El sistema envía un correo con un enlace único y seguro para restablecer la contraseña.
-   Al hacer clic en el enlace, el usuario es redirigido a una página donde puede ingresar una nueva contraseña.
-   La nueva contraseña es validada (seguridad, longitud mínima, etc.) antes de ser aceptada.
-   Tras el restablecimiento exitoso, la contraseña se actualiza en la base de datos.
-   Un mensaje de confirmación se muestra al usuario tras el restablecimiento exitoso.
-   Pruebas unitarias y de integración completadas y aprobadas.
-   Documentación actualizada y aprobada.



### 5. **Mensajería en tiempo real**

**Definition of Done:**

-   El sistema permite enviar y recibir mensajes instantáneos entre usuarios (estudiantes y tutores).
-   Los mensajes se transmiten y muestran en tiempo real sin necesidad de recargar la página.
-   Los mensajes enviados son almacenados correctamente en la base de datos.
-   La interfaz muestra claramente cuándo un mensaje ha sido enviado, recibido y leído.
-   La conexión en tiempo real es estable y maneja adecuadamente la pérdida o reconexión.
-   Se han implementado medidas de seguridad para evitar el acceso no autorizado a los mensajes.
-   Pruebas de rendimiento y escalabilidad completadas, especialmente en carga alta.
-   Pruebas unitarias y de integración completadas y aprobadas.
-   Documentación actualizada y aprobada.


### 6. **Notificaciones de mensajes nuevos**

**Definition of Done:**

-   El sistema muestra notificaciones en tiempo real para nuevos mensajes recibidos, incluso si el usuario está en otra página del sistema.
-   Las notificaciones incluyen el nombre del remitente y un fragmento del mensaje.
-   El usuario puede acceder directamente al mensaje a través de la notificación.
-   Las notificaciones no leídas se almacenan y muestran hasta que el usuario las revise.
-   Se pueden personalizar las preferencias de notificaciones (habilitar/deshabilitar).
-   Pruebas de notificaciones realizadas en distintos navegadores y dispositivos.
-   Pruebas unitarias y de integración completadas y aprobadas.
-   Documentación actualizada y aprobada.


# Requerimientos no funcionales

### 1.  Compatibilidad  de  navegadores
**Definition  of  Done:**

-   El  sistema  se  ha  probado  en  Google  Chrome  y  otros  navegadores  basados  en  Chromium.
-   El  sistema  se  ha  probado  en  dispositivos  móviles  con  sistemas  operativos  Android  y  Windows.
-   Se  han  realizado  pruebas  de  usabilidad  en  todos  los  navegadores  y  sistemas  operativos  especificados.
-   Se  han  documentado  y  resuelto  todos  los  problemas  de  compatibilidad.
-   Pruebas  de  regresión  completadas  para  asegurar  que  las  actualizaciones  no  rompan  la  compatibilidad.
-   Documentación  actualizada  y  aprobada.
    

### 2.  Accesibilidad

**Definition  of  Done:**

-   El  sistema  es  accesible  desde  navegadores  modernos  sin  necesidad  de  descargar  aplicaciones.
-   El  sistema  se  ha  probado  en  varios  dispositivos  móviles  para  asegurar  la  accesibilidad.
-   Se  han  realizado  pruebas  de  rendimiento  para  asegurar  tiempos  de  carga  rápidos  en  dispositivos  móviles.
-   Pruebas  de  accesibilidad  completadas,  asegurando  conformidad  con  estándares  como  WCAG.
-   Todos  los  problemas  de  accesibilidad  identificados  se  han  resuelto.
-   Documentación  actualizada  y  aprobada.

  
### **3. Portabilidad**

**Definition of Done:**

-   El sistema es accesible y funcional en múltiples plataformas (PC, tabletas, teléfonos inteligentes) sin pérdida significativa de funcionalidad.
-   La interfaz de usuario se adapta correctamente a diferentes resoluciones de pantalla y tamaños de dispositivos (diseño responsivo).
-   Las principales funcionalidades (registro, inicio de sesión, mensajería, notificaciones) se mantienen consistentes en navegadores populares (Chrome, Firefox, Safari, Edge) y sus versiones más recientes.
-   Las aplicaciones nativas (si existen) funcionan correctamente en sistemas operativos comunes (Windows, macOS, Android, iOS).
-   Se han completado pruebas de compatibilidad en diversos dispositivos y navegadores.
-   El rendimiento del sistema no se ve comprometido en dispositivos de menor capacidad de procesamiento.
-   Documentación técnica de portabilidad actualizada y aprobada.
-   Pruebas de compatibilidad, rendimiento y usabilidad completadas y aprobadas.

