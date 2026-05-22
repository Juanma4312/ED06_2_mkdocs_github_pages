# Despliegue en GitHub Pages

Este proyecto está configurado para publicarse de forma automática en **GitHub Pages**.

## Automatización con GitHub Actions

No es necesario compilar el sitio web manualmente. Hemos configurado un flujo de trabajo (workflow) en la ruta `github/workflows/deploy.yml`.

### ¿Cómo funciona?

1. Cada vez que realizamos un `git push` a la rama `main`, GitHub Actions detecta el cambio.
2. Se levanta un entorno virtual en la nube (Ubuntu).
3. Se instalan Python, MkDocs y las dependencias necesarias.
4. El comando `mkdocs gh-deploy --force` compila los archivos Markdown a HTML y los sube a la rama `gh-pages`.
5. GitHub Pages toma esa rama y actualiza el sitio web público en cuestión de segundos.
