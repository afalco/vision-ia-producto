# Proyecto aplicado · Enunciado

Trabaja en pareja durante la sesión de 150 minutos. Elige una ruta y formula un problema acotado de producto o fabricación. Reutiliza las prácticas del curso; no se requiere adquirir datos, contratar servicios ni instalar nuevos modelos. Puedes trabajar con datos sintéticos, siempre que lo declares y limites las conclusiones.

## Rutas

| Ruta | Punto de partida | Comparación posible | Evidencia mínima |
|---|---|---|---|
| A · Clasificación | Tema 2 o ejemplo del notebook del tema 6 | Resolución, regularización o número de piezas de entrenamiento | Comparación en validación, matriz de prueba y dos errores o límites |
| B · Detección/segmentación | Tema 3 | Limpieza, área mínima o criterio de decisión | IoU o evaluación de cajas con protocolo, tres imágenes anotadas y fallos |
| C · Anomalías | Tema 4 | Criterios de umbral o agregación del mapa | FP/FN, tasas con denominadores, resultados por tipo y dos casos |
| D · Búsqueda visual | Tema 5 | Referencia de orden fijo y ranking CLIP; consultas de desarrollo/evaluación | Relevancia definida antes, aciertos de primera posición y dos fallos literales |

En B y C, cualquier parámetro nuevo se elige en validación. En D, el catálogo reducido solo permite una exploración inicial; no atribuyas un rendimiento general al modelo. El análisis de conceptos generados puede complementar una ruta, pero no sustituye la evaluación de visión artificial.

## Trabajo

1. Define usuario, decisión, salida, hipótesis y criterio de éxito.
2. Documenta datos, etiquetas y unidad independiente. Separa antes de experimentar.
3. Compara una referencia con una propuesta e introduce un cambio justificado. Registra los intentos en validación.
4. Cierra las decisiones y aplica el procedimiento fijado a prueba. Si reajustas después, necesitarás nuevos datos para una estimación independiente.
5. Analiza dos errores o límites y escribe una conclusión proporcional a la evidencia.
6. Defiende la propuesta y revisa el trabajo de otro equipo.

## Entrega

Notebook con salidas y respuestas propias; informe de una página aproximadamente; tablas, figuras o registros necesarios. Reinicia y ejecuta en orden antes de entregar. Los archivos exportados automáticamente son borradores, no respuestas finales. No es necesario crear diapositivas adicionales.

## Defensa

Cinco minutos: problema/datos 1 min; método/comparación 1 min; resultados/errores 2 min; conclusión 1 min. El bloque de 35 minutos admite hasta cinco equipos con dos minutos de preguntas cada uno. Para grupos mayores habrá estaciones simultáneas con dos rondas de 15 min y cinco minutos de puesta en común. El profesor asignará las revisiones.

## Evaluación

[Rúbrica](rubrica.md): problema/datos 25 %, método 25 %, evaluación/errores 30 %, claridad/reproducibilidad 20 %. Un proyecto que demuestra una limitación de forma rigurosa puede estar bien resuelto. La nota no depende solo de que el acierto sea alto. La coordinación docente determina la ponderación en la asignatura.
