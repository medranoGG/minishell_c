

Proyecto minishell en c.
Permite:
  - Ejecución uno o varios comandos enlazados con "|".
  - Redirecciones de entrada y salida desde o a ficheros.
  - Ejecución en "background" y listar procesos con jobs.

Compilar:
```
gcc -Wall -Wextra myshell.c libparser.a -o myshell -static
```

