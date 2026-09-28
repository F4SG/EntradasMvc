# EntradasMvc

Aplicacion web desarrollada con ASP.NET Core MVC en Visual Studio para Windows.

## Descripcion

Cotizador de entradas para un evento. El usuario ingresa su nombre y la cantidad de entradas que desea; el servidor valida los datos y muestra un desglose del precio.

- Cada entrada cuesta Bs 50.
- Desde 5 entradas se aplica un descuento del 10%.

## Estructura del proyecto

- `Models/Cotizacion.cs` - Modelo con las reglas de calculo y validacion.
- `Controllers/EntradasController.cs` - Controlador con las acciones Index y Calcular.
- `Views/Entradas/Index.cshtml` - Formulario de cotizacion.
- `Views/Entradas/Resultado.cshtml` - Pantalla con el desglose del precio.

## Requisitos

- .NET 10 SDK
- Visual Studio con la carga de trabajo ASP.NET y desarrollo web

## Ejecutar el proyecto

Abrir `EntradasMvc.slnx` en Visual Studio y presionar F5.
