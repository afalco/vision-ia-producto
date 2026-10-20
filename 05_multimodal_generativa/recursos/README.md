# Procedencia de recursos

Seis ilustraciones procedimentales originales (tazas azul/roja, lámpara, silla, arandela y escuadra) y dos renders generados para el curso (conceptos A/B). No se incluyen fotografías de terceros. Los identificadores y los nombres de archivo no se suministraron a CLIP: se procesaron píxeles y las frases del catálogo.

`clip_vectores.npz` contiene embeddings reales de imagen/texto normalizados y el factor de escala de logits de `openai/clip-vit-base-patch32`. `procedencia_clip.json` identifica revisión, versiones, procesador y huellas SHA-256. No se distribuyen pesos del modelo. Para recalcular usa la ampliación en vivo.

`prompts_generacion.json` conserva las instrucciones completas utilizadas con la herramienta integrada `image_gen`, fecha y límites de reproducibilidad. La herramienta no expuso modelo exacto ni semilla. A y B son generaciones independientes, sin control de variables; su comparación es ilustrativa.

Los textos y figuras del curso mantienen el régimen de uso indicado en el README general. Revisa las condiciones y limitaciones del modelo antes de reutilizarlo: [tarjeta de CLIP](https://huggingface.co/openai/clip-vit-base-patch32). Los renders no demuestran dimensiones, rendimiento mecánico ni fabricabilidad.
