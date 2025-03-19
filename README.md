# Login Signup Forms

## Descripción del Proyecto
Este laboratorio consistió en el diseño e implementación de formularios para el registro (signup) y autenticación (login) de usuarios en una aplicación móvil orientada a la priorización de propuestas de proyectos de gestión del espacio público.

## Tecnologías Utilizadas
- **Android Studio** para el desarrollo de la aplicación.
- **Kotlin/Java** como lenguaje de programación.
- **Material Design Components** para mejorar la interfaz de usuario.
- **Google Maps API** para la geolocalización.
- **Firebase Authentication** (opcional) para el manejo de usuarios.

## Funcionalidades Implementadas
### Formulario de Registro (Signup)
Se desarrolló un formulario de registro con los siguientes campos y funcionalidades:
- **Campos de entrada de texto**:
  - Nombre completo
  - Usuario
  - Correo electrónico (email)
  - Dirección física (con geolocalización usando latitud/longitud o dirección estructurada de Google Maps)
  - Contraseña y confirmación de contraseña
- **Selector de rol** con las opciones: ciudadano, planeador o decisor (Spinner).
- **Selector de género** con opciones: masculino, femenino o binario (RadioGroup y RadioButton).
- **Selector de fecha de nacimiento** con validación para aceptar solo usuarios mayores de 18 años.
- **Botón de registro** que almacena los datos ingresados.

### Formulario de Inicio de Sesión (Login)
- **Campos de entrada**:
  - Usuario
  - Contraseña
- **Botones**:
  - Iniciar sesión
  - Registrarse (redirecciona al formulario de signup si el usuario no está registrado).
- **Configuración como pantalla principal**: Este formulario se muestra como la pantalla inicial de la aplicación.

Este laboratorio permitió afianzar conocimientos en la implementación de formularios en Android, validaciones de entrada, uso de componentes de Material Design y geolocalización, proporcionando una base sólida para futuras aplicaciones móviles.

