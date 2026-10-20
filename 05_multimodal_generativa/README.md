# Tema 5 · Modelos multimodales y generativos

Sesión de 150 minutos con seis actividades intercaladas.

- [Presentación PDF](05_multimodal_generativa.pdf).
- [Notebook principal](05_multimodal_generativa.ipynb).
- [Abrir el principal en Colab](https://colab.research.google.com/github/afalco/vision-ia-producto/blob/main/05_multimodal_generativa/05_multimodal_generativa.ipynb).
- [Ampliación opcional: CLIP en vivo](05B_clip_en_vivo.ipynb).
- [Abrir la ampliación en Colab](https://colab.research.google.com/github/afalco/vision-ia-producto/blob/main/05_multimodal_generativa/05B_clip_en_vivo.ipynb).

Los enlaces de Colab mostrarán los nuevos archivos cuando se publiquen los cambios.

## Ruta principal

CPU y entorno básico del curso. Usa vectores reales de CLIP guardados para ocho imágenes y trece consultas. Los recursos pesan pocos MB y se descargan desde GitHub al abrir en Colab; con el repositorio completo funciona sin red en local. No descarga pesos, no necesita GPU, clave de API ni servicio de generación. Las consultas nuevas se ejecutan en la ampliación.

La práctica compara búsqueda por texto, clasificación con candidatas, límites de negación/cantidad, un experimento de añadir ruido y dos conceptos de soporte móvil previamente generados. El ruido es un proceso directo ilustrativo: no entrena ni ejecuta un generador. El análisis de los dos renders tampoco es una prueba causal controlada del efecto de las instrucciones.

## Ampliación en vivo

Usa un entorno separado o Colab. Instala las dependencias indicadas en el notebook y descarga varios cientos de MB del modelo CLIP público. Recalcula vectores y admite frases nuevas. CPU compatible; GPU opcional. No genera imágenes. No es necesaria para entregar el tema.

## Procedencia y alcance

Consulta [la procedencia de los vectores](recursos/procedencia_clip.json), [los prompts exactos](recursos/prompts_generacion.json) y [la descripción de recursos](recursos/README.md). La tarjeta de este CLIP delimita su uso al inglés. Los conceptos visuales no son CAD ni diseños fabricables validados.

## Entrega

Tres búsquedas comentadas, dos fallos, explicación del ruido y tabla de revisión con un prompt mejorado. Descarga `tema5_busquedas.csv` y `tema5_revision_conceptos.csv` antes de cerrar Colab.
