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
| 1 | Imágenes como datos | [PDF y práctica](01_imagenes_como_datos/README.md) | PDF y seis actividades preparados |
| 2 | Clasificación | [PDF y práctica](02_clasificacion/README.md) | PDF y seis actividades preparados |
| 3 | Detección y segmentación | [PDF y práctica](03_deteccion_segmentacion/README.md) | PDF y seis actividades preparados |
| 4 | Inspección y anomalías | [PDF y práctica](04_inspeccion_anomalias/README.md) | PDF y seis actividades preparados |
| 5 | Modelos multimodales y generativos | [PDF y prácticas](05_multimodal_generativa/README.md) | PDF, seis actividades y ampliación CLIP preparados |
| 6 | Proyecto aplicado | [PDF, notebook y rúbrica](06_proyecto/README.md) | Taller y materiales preparados |

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

El entorno cubre las rutas principales de los seis temas y no requiere GPU. La ampliación opcional de CLIP del tema 5 instala dependencias adicionales en un entorno separado o Colab. Las versiones tienen límites de compatibilidad, pero este archivo no es un bloqueo exacto de versiones. Falta validar una instalación limpia tanto en Mac como en Windows y ejecutar los notebooks en Colab.

## Material y entregas

Las primeras prácticas generan imágenes mediante código. El tema 5 incluye ilustraciones, conceptos generados y vectores reales de CLIP con procedencia registrada; en Colab descarga estos recursos pequeños del repositorio. Guarda tus experimentos en `trabajo_alumno/` y los resultados en `resultados/`; ambas carpetas quedan fuera del seguimiento de Git. Las entregas se realizarán por el canal que indique el profesor.

## Uso y publicación

Los seis temas disponen de presentación PDF y práctica o taller guiado. Falta validar el recorrido completo en Colab y en instalaciones limpias de los sistemas previstos. Los fuentes de las presentaciones y las guías docentes se conservan fuera del repositorio público. No incorpora libros, presentaciones ni materiales de otras ediciones. Los modelos y datos externos que se añadan deberán documentar su origen y condiciones de uso. Por ahora no se concede una licencia de redistribución; el docente deberá elegirla antes de promover la reutilización del material.

Para publicar desde el Mac, consulta [las instrucciones de GitHub Desktop](docs/publicar_github.md).
