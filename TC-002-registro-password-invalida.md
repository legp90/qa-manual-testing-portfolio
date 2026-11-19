# TC-002 - Registro de usuario con contraseña invalida

## Objetivo

Verificar que el sistema rechace el registro cuando la contraseña tenga menos de 8 caracteres.

## Precondiciones

-La aplicacion debe estar disponible
-El formulario de registro de usuarios debe estar accesible
-El correo de prueba no debe estar asociado a una cuenta existente
-El usuario no debe de tener una sesion iniciadoa.

## Datos de Prueba (Test Data)

-Correo electronico: luchoperez@gmail.com
-Contraseña: elexito
-Longitud de contraseña: 7 caracteres
-Tipo de prueba: Negative Test

## Pasos de prueba (Test Steps)

1-Abrir la pagina de la tienda online
2-Acceder al formulario de registro de usuarios
3-Ingresar el correo electronico: luchoperez@gmail.com
4-Ingresar la contraseña: elexito
5-Hacer clic en el boton "Registrarse"

