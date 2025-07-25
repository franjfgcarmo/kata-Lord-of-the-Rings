# El Señor de los Anillos - Kata

## Descripción

El objetivo principal de este kata es refactorizar el código que tenemos para obtener una base de código más fácil de mantener y sin romper los test (código producción) en cada iteración.
La idea es refactorizar poco a poco entre todos y no diseñar o pensar en una idea super compleja de primeras. Seguramente, una vez el código este refactorizado, podremos hablar de siguientes pasos.

## Lo que necesitamos

- [.NET 8](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- Visual Studio / Rider

## Requisitos

- Las clases del `Dominio` y los enums pueden cambiar (de hecho, deberían)
- Las clases de `Aplicación` no deben cambiar, hasta el paso 4
- Las pruebas en `TheseTestsShouldNotBeChanged.cs` no deben ser cambiadas
- Las pruebas en `SomeOfTheseTestsMayChange.cs` deben ser cambiadas en los pasos 3 y 4

## Lo que estamos tratando de resolver

1. Se nos ha pedido agregar una nueva raza: `Dwarf`. Tienen nombre, pero no pueden poseer El Anillo Único y son de los buenos. Su fuerza será 20. La clase actual `Character.cs` está bastante desordenada y has notado que rompe todos los principios SOLID. Refactorízala, para que no necesites agregar más `if/switch` al código.
2. ¿Podrías eliminar todas las declaraciones `if` y `switch`?
3. El Anillo Único es precisamente eso: único. Trata de refactorizar el código, para asegurar que no pueda haber más de uno
4. ¿Cómo asegurarías que un ejército esté formado solo por la misma alineación?

