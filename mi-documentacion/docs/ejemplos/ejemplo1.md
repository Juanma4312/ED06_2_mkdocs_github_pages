# Ejemplo de Código y Componentes

El tema Material de MkDocs nos permite mostrar bloques de código de forma muy elegante y legible.

## Código en Python

Gracias a las extensiones que hemos habilitado, los bloques de código incluyen resaltado de sintaxis y un botón integrado para copiar el contenido directamente al portapapeles.

```python
def procesar_datos(datos):
    """
    Esta función procesa una lista de datos.
    """
    for elemento in datos:
        print(f"Procesando: {elemento}")
        
lista = ["MkDocs", "GitHub Actions", "Markdown"]
procesar_datos(lista)
