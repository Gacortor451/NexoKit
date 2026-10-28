# NexoKit

**Tu espacio de herramientas digitales: textos, imágenes, PDF, diagramas, colores y más, directamente en el navegador.**

NexoKit reúne pequeñas utilidades con una interfaz coherente, en español y con diseño oscuro. Está pensado para abrirse de forma sencilla, sin instalación ni cuentas de usuario.

## Inicio rápido

1. Descarga o clona este repositorio.
2. Mantén todos los archivos `.html` juntos en la misma carpeta.
3. Abre **`index.html`** en tu navegador.
4. Utiliza el buscador o los filtros por categorías para encontrar una herramienta.

También puedes abrir cada herramienta directamente desde su archivo HTML.

> **Conexión:** muchas herramientas funcionan sin Internet, pero **QR Reader** y **PDF Toolkit** cargan bibliotecas externas y necesitan conexión si no están almacenadas en la caché del navegador. Algunas funciones, como la cámara y el portapapeles, pueden depender de los permisos y las restricciones de seguridad del navegador al abrir archivos locales.

## Herramientas activas

| Categoría | Herramienta | Función principal |
| --- | --- | --- |
| Textos y documentos | **Code2Docs** | Preparar código con resaltado de sintaxis para documentos. |
| Textos y documentos | **Markdown2Docs** | Convertir Markdown a contenido con formato. |
| Textos y documentos | **TextCompare** | Comparar dos versiones de texto o código. |
| Textos y documentos | **TextCleaner** | Limpiar espacios, saltos de línea y otros problemas del texto. |
| Imágenes y diseño | **ImageLab** | Recortar, redimensionar y convertir imágenes. |
| Imágenes y diseño | **ImageAnnotator** | Añadir anotaciones, flechas y resaltados a imágenes. |
| Imágenes y diseño | **ColorKit** | Crear paletas, convertir colores y comprobar contrastes. |
| PDF y páginas | **PDF Toolkit** | Unir, extraer, reordenar y girar páginas de PDF. |
| PDF y páginas | **PageSlice** | Dividir imágenes largas en fragmentos para páginas. |
| Datos y tablas | **Table2Docs** | Dar formato a datos tabulares para documentos. |
| Diagramas | **DiagramKit** | Crear diagramas de flujo y exportarlos. |
| Códigos QR | **QR Reader** | Leer y generar códigos QR. |

## Herramientas descartadas

La página **[`descartados.html`](descartados.html)** conserva herramientas que se han desarrollado pero que no han terminado de convencer o no encajan con el uso habitual del proyecto.

**Las herramientas descartadas probablemente no recibirán actualizaciones en el futuro**, incluidas nuevas funciones y correcciones de errores. Se mantienen accesibles para no perder el trabajo realizado; pueden contener fallos conocidos.

- **DocCover:** diseñador de portadas. Archivado porque su utilidad habitual todavía no está clara.
- **IconKit:** biblioteca de iconos. Archivado porque presenta errores pendientes de resolver.

## Organización del proyecto

```text
NexoKit/
├── index.html             # Menú, buscador y categorías
├── descartados.html       # Herramientas archivadas
├── README.md              # Documentación del proyecto
├── code2docs.html
├── pageslice.html
├── qr_reader.html
├── table2docs.html
├── imagelab.html
├── markdown2docs.html
├── pdf_toolkit.html
├── diagramkit.html
├── textcompare.html
├── textcleaner.html
├── imageannotator.html
├── colorkit.html
├── doccover.html          # Archivada
└── iconkit.html           # Archivada
```

## Privacidad y funcionamiento

Las herramientas están diseñadas para procesar el contenido en el navegador, sin subir los documentos a un servidor propio de NexoKit. Algunas bibliotecas JavaScript se descargan desde servicios externos cuando se necesitan. No se garantiza funcionamiento totalmente offline en la versión actual.

Los archivos originales no se modifican automáticamente: las operaciones de exportación generan archivos nuevos.

## Estado del proyecto

**En desarrollo.** Actualmente hay **12 herramientas activas y 2 archivadas**. Las funciones se han ido probando de forma manual; no existe todavía una batería completa de pruebas automatizadas ni una garantía de compatibilidad con todos los navegadores.

### Próximos pasos posibles

- Revisar la interfaz y la usabilidad de todas las herramientas.
- Estudiar una versión completamente offline sin perder características.
- Seguir incorporando herramientas útiles y organizar las categorías según crezca el proyecto.

## Uso

Colección de utilidades digitales. **No se incluye por ahora una licencia de código abierto**; si quieres permitir expresamente la reutilización, modificación y distribución por terceros, añade un archivo `LICENSE` con la licencia que elijas.
