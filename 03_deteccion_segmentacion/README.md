# Tema 3 · Detección y segmentación

Sesión de 150 minutos con seis actividades intercaladas.

- [Presentación PDF](03_deteccion_segmentacion.pdf).
- [Notebook de actividades](03_deteccion_segmentacion.ipynb).
- [Abrir en Colab](https://colab.research.google.com/github/afalco/vision-ia-producto/blob/main/03_deteccion_segmentacion/03_deteccion_segmentacion.ipynb) (tras subir los cambios).

## Objetivos

Distinguir etiqueta, caja, máscara semántica e instancias; ajustar umbrales en validación; obtener componentes y cajas; interpretar IoU, precisión y recall; analizar piezas en contacto y cambios de color.

## Requisitos y alcance

CPU; NumPy, Matplotlib, scikit-learn y scikit-image del entorno del curso. Sin descargas. Las escenas y referencias se generan por código. El modelo aprende pieza/fondo a partir de RGB y después se agrupan píxeles para obtener cajas. No es un detector profundo ni un modelo de instancias. La presentación introduce estas familias de forma conceptual. Las imágenes sintéticas no validan un sistema industrial.

## Entrega

Tres escenas anotadas, tabla de métricas y dos errores explicados. El notebook guarda `tema3_resultados.png`; descárgalo antes de cerrar Colab. La evaluación de cajas es docente, a IoU mínima 0,5, sin cálculo de AP/mAP.
