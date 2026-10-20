# Visión artificial aplicada al desarrollo de producto y la fabricación aditiva

Material docente para **6 clases de 2,5 horas (15 horas)**. Nivel: Python de usuario y matemáticas básicas. El entorno principal es **Google Colab**; Jupyter con conda es la alternativa local para Mac y Windows.

## Empezar en Colab

1. Abre [Google Colab](https://colab.research.google.com/).
2. Selecciona **Abrir notebook → GitHub** y pega la URL de este repositorio una vez publicado.
3. Abre `00_preparacion/00_comprobar_entorno.ipynb`.
4. Guarda una copia en tu Drive para conservar los ejercicios.
5. Ejecuta las celdas por orden. Continúa con la sesión 1.

No necesitas instalar Git ni tener cuenta de GitHub para descargar un repositorio público. También puedes usar **Code → Download ZIP** en GitHub. Los archivos de la sesión de Colab son temporales: descarga los resultados que quieras conservar.

## Sesiones y estado del material

| Sesión | Tema | Material | Estado |
|---|---|---|---|
| 0 | Preparación | [Comprobar entorno](00_preparacion/00_comprobar_entorno.ipynb) | Notebook inicial preparado |
| 1 | Imágenes como datos | [Práctica](01_imagenes_como_datos/01_imagenes_como_datos.ipynb) | Notebook inicial preparado |
| 2 | Clasificación | [Guía](02_clasificacion/README.md) | Pendiente de desarrollar |
| 3 | Detección y segmentación | [Guía](03_deteccion_segmentacion/README.md) | Pendiente de desarrollar |
| 4 | Inspección y anomalías | [Guía](04_inspeccion_anomalias/README.md) | Pendiente de desarrollar |
| 5 | Modelos multimodales y generativos | [Guía](05_multimodal_generativa/README.md) | Pendiente de desarrollar |
| 6 | Proyecto aplicado | [Enunciado inicial](06_proyecto/README.md) | Propuesta para revisión docente |

Consulta el [programa detallado](docs/programa.md).

## Trabajar en local

Instala una distribución de conda adecuada a tu sistema. En Windows utiliza su terminal de conda; en Mac, Terminal. Descarga o clona el repositorio, entra en su carpeta y ejecuta:

```bash
conda env create -f environment.yml
conda activate vision-ia-producto
python -m ipykernel install --user --name vision-ia-producto --display-name "Python (vision-ia-producto)"
jupyter lab
```

Selecciona el núcleo **Python (vision-ia-producto)**. Para actualizar el entorno tras cambios:

```bash
conda env update -f environment.yml --prune
```

El entorno cubre los notebooks iniciales y no requiere GPU. Las dependencias específicas de modelos de sesiones posteriores se incorporarán al desarrollar esas prácticas. Las versiones tienen límites de compatibilidad, pero este archivo no es un bloqueo exacto de versiones. Falta validar una instalación limpia tanto en Mac como en Windows y ejecutar los notebooks en Colab.

## Material y entregas

Las imágenes iniciales se generan mediante código, sin descargar archivos externos. Guarda tus experimentos en `trabajo_alumno/` y los resultados en `resultados/`; ambas carpetas quedan fuera del seguimiento de Git. Las entregas se realizarán por el canal que indique el profesor.

## Uso y publicación

Esta es una base de trabajo del curso, no las seis clases terminadas. No incorpora libros, presentaciones ni materiales de otras ediciones. Los modelos y datos externos que se añadan deberán documentar su origen y condiciones de uso. Por ahora no se concede una licencia de redistribución; el docente deberá elegirla antes de promover la reutilización del material.

Para publicar desde el Mac, consulta [las instrucciones de GitHub Desktop](docs/publicar_github.md).
