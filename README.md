## Guía de Ejemplo en Markdown

Este es un **texto de prueba** redactado en formato _Markdown_. Sirve para estructurar y dar formato a documentos de texto de manera sencilla, rápida y legible.

---

### Elementos de Formato Básico

- **Texto en negrita:** Se usa para resaltar palabras clave o conceptos principales.
- _Texto en cursiva:_ Ideal para términos en otros idiomas o énfasis secundario.
- ~~Texto tachado:~~ Útil para indicar correcciones o elementos obsoletos.
- `Código en línea:` Perfecto para comandos, archivos o nombres de variables.

> **Nota destacada:** Markdown se convierte automáticamente a HTML limpio, lo que lo hace perfecto para documentación web, notas personales y blogs.

### Pasos para Publicar un Documento

1. Escribir el contenido en un editor de texto plano usando sintaxis Markdown.
2. Validar la vista previa del archivo para verificar el formato.
3. Exportar a formato PDF, HTML o publicarlo directamente en la plataforma.

### Estructura de Datos en Tabla

| Elemento    | Sintaxis Markdown | Resultado Visual      |
| ----------- | ----------------- | --------------------- |
| **Negrita** | `**Texto**`       | **Texto**             |
| _Cursiva_   | `*Texto*`         | _Texto_               |
| Cita        | `> Texto`         | Bloque de cita visual |

```python
# Bloque de código de ejemplo
def verificar_markdown():
    estado = "Funcionando"
    return f"El entorno Markdown está: {estado}"

print(verificar_markdown())
```

---

## Guía Rápida de Comandos Git

A continuación se explica la función de los comandos principales de Git utilizando términos sencillos del día a día:

- **`git init`**: Inicializa el repositorio de manera local
- **`git add`**: Pone los archivos que modificaste en una "bandeja de salida" o lista de espera. Prepara todo lo que quieres guardar en el siguiente paso.
- **`git commit`**: Toma una "foto" del estado actual de tus archivos preparados y le agrega una nota pequeña explicando qué cambios hiciste.
- **`git push`**: Sube las "fotos" guardadas desde tu computadora hacia un servidor en internet (como GitHub) para que tengas una copia de respaldo en la nube.
- **`git status`**: Funciona como un tablero informativo que te dice en qué estás trabajando, qué archivos modificaste y cuáles no has guardado aún.
- **`git diff`**: Compara tus archivos actuales con la última "foto" guardada y te muestra línea por línea qué agregaste, borraste o cambiaste.
- **`git log`**: Es el álbum de recuerdos o historial completo que muestra todas las "fotos" (commits) que has tomado desde el inicio del proyecto.
- **`git restore`** _(Deshacer cambios)_: Funciona como un botón de "deshacer" (Ctrl+Z). Borra los cambios que hiciste recientemente en un archivo y lo regresa a como estaba en la última foto guardada.
