# BUG-001 - El sistema rechaza credenciales validas al iniciar sesión

**Tipo:** Bug simulado (ejercicio educativo)

## Descripcion

Al intentar iniciar sesión con un correo electrónico y una contraseña validos, el sistema muestra un mensaje de error y no permite al usuario acceder a su cuenta.

## Precondiciones

-El usuario debe de tener una cuenta registrada y activa.
-El usuario debe contar con un correo electronico y una contraseña validos.
-El usuario debe encontrarse en la pagina de inicio de sesion.

## Pasos para reproducir

1. Abrir la pagina de la tienda online.
2. Hacer clic en el botón "Login".
3. Ingresar un correo electronico valido.
4. Ingresar la contraseña correcta del usuario.
5. Hacer clic en el botón "Ingresar".

## Resultado esperado (Expected Result)

El sistema debe permitir que el usuario inicie sesión correctamente con sus credenciales validas y acceda a su cuenta.

## Resultado real (Actual Result)

Al hacer clic en el botón "Ingresar", el sistema muestra el mensaje "No se pudo iniciar sesión. Inténtalo nuevamente" y no permite al usuario acceder a su cuenta.

## Entorno de pruebas (Test Environment)

-Aplicacion: Tienda online ficticia
-Entorno: Simulado (sin ejecución real)

## Severidad (Severity)

High

Justificacion: El defecto impide que un usuario con credenciales validas acceda a su cuenta, afectando una funcionalidad esencial de la aplicacion.

Nota: Severidad estimada para un escenario simulado.

## Prioridad (Priority)

High

Justificación: El defecto impide al usuario acceder a su cuenta, lo que puede afectar sus compras y su experiencia en la aplicación. Se recomienda investigar y solucionar el problema lo antes posible.

Nota: Prioridad estimada para un escenario simulado.

## Evidencias (Evidence)

No se adjuntan evidencias porque este reporte corresponde a un escenario simulado con fines educativos.
