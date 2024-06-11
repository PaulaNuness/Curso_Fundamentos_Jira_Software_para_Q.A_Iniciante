# Curso_Fundamentos_Jira_Software_para_Q.A_Iniciante
* Curso hecho en la plataforma OpenWebinars
******************************************************************************************
## Inicio curso
* Creamos una cuenta en Jira ( para gestionar los pryectos)
* En el curso vamos utilizar SCRUM, Kanban no.
*****************************************************************************************
## Tarea 01
* Crear un proyecto utilizando  Scrum
* Utilizar os requerimientos abajo:
   * US01 - Registro de usuarios
   * Creación: Romina Bello
   * Última actualización: abr 01, 2023
   * Como usuario del sitio
   * Quiero poder registrarme con mi usuario y mi clave
   * Para poder ingresar con mis credenciales y disfrutar de la página web
 * Requisitos
   * El registro del usuario debe solicitar:
   * -Login (nombre que va a usar para iniciar sesión)
   * -First name
   * -Last name
   * -Password (mínimo 6 caracteres alfanuméricos, con una letra mayúscula y un
   * caracter especial)
   * Todos los campos son obligatorios.
   * Si el usuario no completa uno o más campos correctamente, aparecerá mensaje de
   * error y no se podrá continuar con el registro.
   * Mensajes de error:
   * Campo login vacío: “Login is required”
   * Campo First name vacío: “First Name is required”
   * Campo Last name vacío: “Last Name is required”
   * Campo Password vacío: “Password is required”
   * Si en el campo “confirm password” se introduce una contraseña diferente a la que
   * está en “Password” aparece el mensaje: “Passwords do not match”
   * Si se introduce una contraseña menor a 6 dígitos: “InvalidParameter: 1 validation
   error(s) found. - minimum field size of 6, SignUpInput.Password.”
*  Criterios de aceptación
   * El usuario debe poder registrarse al ingresar todos los campos obligatorios
   * Mostrar mensajes de error si hay algún campo sin completar/erróneo
   * No permitir registrarse con mismos datos, dos veces
   * No permitir registrarse sin completar datos obligatorios
******************************************************************************************************************
