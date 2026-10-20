# Tema 4 · Inspección y detección de anomalías

Sesión de 150 minutos con seis actividades intercaladas.

- [Presentación PDF](04_inspeccion_anomalias.pdf).
- [Notebook de actividades](04_inspeccion_anomalias.ipynb).
- [Abrir en Colab](https://colab.research.google.com/github/afalco/vision-ia-producto/blob/main/04_inspeccion_anomalias/04_inspeccion_anomalias.ipynb) (tras subir los cambios).

## Objetivos

Distinguir normalidad y conformidad, aprender una referencia con piezas correctas, elegir un umbral en validación e interpretar falsas alarmas y omisiones. Analizar mapas, cambios de captura y la frecuencia de defectos.

## Requisitos y alcance

CPU; NumPy, pandas, Matplotlib y scikit-learn del entorno del curso. Sin descargas. Se generan superficies sintéticas alineadas y defectos simulados. El modelo aprende media y variación por posición, produce mapas de desviación y una puntuación por imagen. No ejecuta autoencoders ni modelos profundos; se presentan conceptualmente en el PDF. La ROI es fija, y la evaluación es por imagen, no de segmentación de defectos. Los resultados no validan inspección industrial.

## Entrega

Tabla y justificación del umbral, matriz y tasas de prueba, errores comentados y diagnóstico de desplazamiento. Descarga `tema4_errores.png` antes de cerrar Colab. Si un tipo de error no aparece, documéntalo sin inventar ejemplos.
