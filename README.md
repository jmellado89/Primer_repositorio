# Creando un nuevo repositorio

## Repositorio local (en mi computador)

1. `git init` para inicializar repositorio
2. `git add .` o `git add <nombre-archivo>` para agregar cambios al área de preparación
3. `git commit -m "mensaje descriptivo"` para guardar (confirmar) los cambios en el historial del repositorio

## Repositorio remoto (en GitHub)

1. `git push origin main` `git push <repositorio-remoto> <rama-para-enviar>` Envía los cambios desde el repositorio local al remoto

## Me arrepentí...

1. `git checkout -- <nombre-archivo-a-restaurar>` Descarta los cambios hechos en un archivo del directorio de trabajo y lo devuelve al estado exacto del último commit
