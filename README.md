# Introduccion a Git y Markdown los numerales son como titulos

## Comandos del dia
```bash
git init
git status
# creamos un archivo nuevo
git add .
# hasta aca no se guardaron los cambios, para hacerlo tengo que crear un commit
git commit -m "IMPORTANTE: aca va la descripcion del commit"
# hicimos algun  commit mas y revisamos el historial de commits con git log
```

## Markdown y README.md
Markdown es una tecnologia que permite escribir texto con un formato especial y nos
permite por ejemplo crear archivos de texto que puedan tener titulos, codigos e imagenes (similar a HTML pero sin etiquetas)

## README.md
El archivo README.md es un archivo de Markdown (extension.md) y ese archivo es la portada de nuestro repositorio en GitHub.

## Gitignore
Si creamos un archivo llamado `.gitignore` podemos avisarle a git que archivos queremos ignorar.
Dentro del archivo .gitignore podemos tener algo como esto:

```bash
contrasenas.txt
*.pdf # con esta instruccion le indico que 
``` 