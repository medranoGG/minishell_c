
<h3 align="center">Proyecto minishell en c.</h3>
<h1 align="center"><img src="./icon/C.svg" width="48"><img src="./icon/Linux-Dark.svg" width="48"></h1>
<h1 align="center"><img src="./icon/Linux-Dark.svg" width="48"></h1>

<h3>Permite</h3>
  - Ejecución uno o varios comandos enlazados con "|".
  - Redirecciones de entrada y salida desde o a ficheros.
  - Ejecución en "background" y listar procesos con jobs.

Compilar:
```
gcc -Wall -Wextra myshell.c libparser.a -o myshell -static
```

Ejecutar:

```
./myshell
```
