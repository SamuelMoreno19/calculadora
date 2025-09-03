 # Guía de Git y GitHub sobre la gestión de ramas y sincronización con repositorios remotos
 Una rama es una línea de desarrollo independiente dentro del repositorio.
Y para crear una nueva rama es este comando:
git branch nombre-rama

Para Cambiar a otra rama:
git checkout nombre-rama

Si en un solo paso quieres crear la rama y cambiar directamente a ella:
git checkout -b nombre-rama

Para ver todas las ramas que tienes creadas:
git branch

Para Mezclar ramas
Cuando terminas el trabajo en una rama, puedes fusionarla con otra (ya sea con main o develop):
git checkout main - para entrar a la rama main
git merge nombre-rama - para mezclar tu rama creada con main

Agregar cambios al área de preparación
Para añadir los cambios hechos en los archivos:
git add .

Confirmar cambios (commit)
El commit nos guarda el estado de los archivos en el repositorio:
git commit -m "Mensaje descriptivo del cambio"

Ver estado actual

Para saber en qué estado están los archivos (si fueron modificados, añadidos o confirmados):
git status
Esto nos ayuda a identificar qué cambios faltan por confirmar.
