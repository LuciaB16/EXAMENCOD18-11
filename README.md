# examenDAM
Para utilizarlo en el examen


## Pasos a seguir:
**1º:** Creamos nuestro repositorio nuevo en GItHub, escogiendo la opción de que sea privado.

**2º:** Vamos a la terminal y usamos el comando `git clone` seguido del enlace del repositorio ajeno [Enlace GitHub](https://github.com/damiancastelao/examenDAM) .

**3º:** Una vez clonado, modificamos el readme.md en IntelliJ

**4º:** Copio un programa ya hecho en el repositorio creado.

**5º:** Cambio el nombre del autor del commit usando el comando `git config user.name "Lu"`.

**6º:** Vemos el nombre del autor del commit usando el comando `git log`.

***DIAGRAMA DE FLUJO***
```mermaid
graph TD;
    A([Inicio]);
    A-->B[\ Introducir num1,num2\];
    B-->C[suma= num1+num2];
    C-->D[resta= num1-num2];
    D-->E[producto= num1*num2];
    E-->F[cociente= num1/num2];
    F-->G[/mostrar suma, resta, producto, cociente/];
    G-->H([Fin]);

