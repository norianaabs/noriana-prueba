# noriana-prueba

Ha llegado el momento de que pongas en práctica lo visto en clase. Para hacer esto, sigue los pasos que se enumeran a continuación.

1) En la terminal (o Git Bash, en Windows) navega hasta la carpeta recién creada (usa el comando cd para navegar entre carpetas);

2) Ejecuta el comando git add index.html para marcar el archivo para ser guardado (commiteado);

3) Ejecuta git status y verifica que el archivo haya cambiado de estado y esté listo para ser guardado (commiteado);

4) Después de agregarlo, ejecuta el comando git commit -m "Creando archivo index.html con lista de cursos". Puedes cambiar el mensaje de commit si quieres;

5) Cambia el archivo index.html. Agrega el acento en "Integración continua", por ejemplo;

6) Agrega el archivo a guardar con git add .;

7) Ejecuta el comando git commit -m "Acento agregado en el curso de Integración Continua". Puedes cambiar el mensaje de commit si quieres;

8) Ejecuta el comando git log y analiza su salida. También ejecuta git log --oneline, git log -p y otras alternativas que desees probar;

9) Crea un archivo vacío con el nombre que desees, por ejemplo, ide-config;

10) Crea el archivo .gitignore y agrega una línea con el nombre del archivo recién creado (ide-config, en el ejemplo anterior);

11) Ejecuta git status y verifica que el archivo ide-config no esté en la lista para ser agregado;

12) Agrega (con git add .gitignore) y confirma (con git commit -m "Adding .gitignore") el archivo .gitignore.
