# TC-002 - Registro de usuario con contraseña invalida

## Objetivo

Verificar que el sistema rechace el registro cuando la contraseña tenga menos de 8 caracteres.

## Precondiciones

1. La aplicacion debe estar disponible
2. El formulario de registro de usuarios debe estar accesible
3. El correo de prueba no debe estar asociado a una cuenta existente
4. El usuario no debe de tener una sesion iniciadoa.

## Datos de Prueba (Test Data)

1. Correo electronico: luchoperez@gmail.com
2. Contraseña: elexito
3. Longitud de contraseña: 7 caracteres
4. Tipo de prueba: Negative Test

## Pasos de prueba (Test Steps)

1. Abrir la pagina de la tienda online
2. Acceder al formulario de registro de usuarios
3. Ingresar el correo electronico: luchoperez@gmail.com
4. Ingresar la contraseña: elexito
5. Hacer clic en el boton "Registrarse"

## Resultado esperado (Expected Result)

El sistema debe rechazar el registro por que la contraseña ingresada tiene 7 caracteres y no cumple con el mínimo requerido de 8 caracteres. No debe crearse una nueva cuenta de usuario.

## Estado de la prueba (Test Status)

Not Run - Pendiente de ejecucion.
