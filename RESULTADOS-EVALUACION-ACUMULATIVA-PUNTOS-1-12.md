# Resultados — Evaluación acumulativa de los puntos 1–12

**Fecha de corrección:** 19 de septiembre de 2026  
**Evaluación original:** [EVALUACION-ACUMULATIVA-PUNTOS-1-12.md](EVALUACION-ACUMULATIVA-PUNTOS-1-12.md)  
**Criterio:** 1 punto por respuesta completa, 0,5 por respuesta parcialmente correcta y 0 por respuesta incorrecta o ausente  
**Resultado:** **14/24 (58,3 %)**

Esta nota es formativa. No equivale al sistema de puntuación oficial de AWS ni permite predecir por sí sola el resultado del examen. Se conserva separada de cualquier mejora obtenida durante el refuerzo.

## Resultado por punto

| Punto | Tema | Resultado |
|---:|---|---:|
| 1 | Fundamentos de IA | 1,5/2 |
| 2 | Aprendizaje y datos | 1,5/2 |
| 3 | Problemas de ML | 1,5/2 |
| 4 | Entrenamiento e inferencia | 1,5/2 |
| 5 | Ciclo de ML y métricas | 1/2 |
| 6 | Servicios especializados de AWS | 1/2 |
| 7 | Modelos fundacionales y representaciones | 1/2 |
| 8 | Bedrock, SageMaker AI y JumpStart | 0,5/2 |
| 9 | Selección de modelos y valor de negocio | 1,5/2 |
| 10 | Ingeniería de prompts | 1/2 |
| 11 | RAG y Bedrock Knowledge Bases | 1/2 |
| 12 | Personalización de modelos | 1/2 |
|  | **Total** | **14/24** |

## Estado de cada respuesta

| Pregunta | Puntaje | Evaluación breve |
|---:|---:|---|
| 1 | 0,5 | Reconoce la relación general y la generación de contenido, pero define deep learning de forma imprecisa. |
| 2 | 1 | Identifica correctamente la IA agéntica y la ejecución de pasos y acciones. |
| 3 | 0,5 | Identifica aprendizaje supervisado, pero no define con claridad etiquetas y características. |
| 4 | 1 | Clasifica correctamente las tres clases de datos y propone búsqueda de patrones sin etiquetas. |
| 5 | 0,5 | Elige regresión y clustering, pero afirma incorrectamente que la regresión no necesita datos. |
| 6 | 1 | Distingue correctamente pronóstico temporal y detección de anomalías. |
| 7 | 1 | Distingue correctamente entrenamiento e inferencia mediante el ejemplo. |
| 8 | 0,5 | Las cuatro modalidades son correctas, pero faltan las justificaciones solicitadas. |
| 9 | 0,5 | Menciona utilidad de negocio y entrenamiento, pero no explica las distintas causas posibles ni las comprobaciones necesarias. |
| 10 | 0,5 | Precision y recall son correctos; faltan F1, falsos positivos y falsos negativos, y se usa incorrectamente el término accuracy. |
| 11 | 0,5 | Los cuatro servicios son correctos, pero faltan sus justificaciones. |
| 12 | 0,5 | Tres servicios son correctos; para el chatbot conversacional especializado se esperaba Amazon Lex, y faltan justificaciones. |
| 13 | 0,5 | Reconoce que un FM es más amplio que un LLM y entiende multimodalidad, pero la relación entre ambos queda imprecisa. |
| 14 | 0,5 | Las tres definiciones son parcialmente correctas; el solapamiento no explica por qué un embedding puede representar una frase. |
| 15 | 0 | No compara los dos casos: correspondían principalmente a Amazon Bedrock y SageMaker AI, respectivamente. |
| 16 | 0,5 | Indica correctamente que no es obligatorio reentrenar y que JumpStart pertenece a SageMaker AI, pero no define JumpStart. |
| 17 | 1 | Considera correctamente latencia, integración, mantenimiento y necesidades del negocio. |
| 18 | 0,5 | Identifica modalidad y contexto total, pero faltan otros criterios técnicos y de negocio. |
| 19 | 0,5 | La familia zero/single/few-shot y la diferencia con fine-tuning son correctas; chain-of-thought y template requieren precisión. |
| 20 | 0,5 | Reconoce IAM, pero confunde delimitadores y describe Guardrails como un documento. Falta diseñar el enfoque completo. |
| 21 | 0,5 | La etapa de consulta está parcialmente ordenada, pero el chunking corresponde normalmente a los documentos durante la ingesta, no a la consulta. |
| 22 | 0,5 | Reconoce partes generales, pero las funciones de S3, Knowledge Bases, el FM y las dos operaciones quedan imprecisas. |
| 23 | 0,5 | Acertó qué métodos cambian parámetros y eligió RAG para información cambiante; faltó prompting y el caso persistente correspondía a fine-tuning. |
| 24 | 0,5 | Reconoce las tres técnicas, pero faltan los tipos de datos o señales y los objetivos completos. |

## Correcciones y respuestas esperadas

### Punto 1

**Pregunta 1.** La IA es el campo general. ML es una parte de la IA en la que los sistemas aprenden patrones a partir de datos. Deep learning es una parte de ML basada en redes neuronales de múltiples capas; no significa simplemente aprender durante más tiempo o “más profundamente”. La IA generativa produce contenido nuevo, mientras que un clasificador asigna categorías.

**Pregunta 2.** La respuesta es IA agéntica. El sistema interpreta un objetivo, planifica o selecciona pasos, utiliza herramientas autorizadas y puede ejecutar acciones. Un chatbot puede limitarse a generar texto sin actuar sobre sistemas externos.

### Punto 2

**Pregunta 3.** Es aprendizaje supervisado. `fraude` y `legítimo` son las etiquetas o resultados correctos que el modelo debe aprender a predecir. Las características podrían ser palabras, patrones, remitente, enlaces, metadatos o representaciones numéricas del correo.

**Pregunta 4.** Tabla con columnas fijas: estructurada. JSON: semiestructurada, porque tiene claves y organización pero no necesariamente una tabla rígida. Audio: no estructurado. El aprendizaje no supervisado podría agrupar llamadas por patrones o temas sin categorías previamente asignadas, después de representarlas con características adecuadas.

### Punto 3

**Pregunta 5.** Estimar una cantidad continua corresponde a regresión. Agrupar clientes sin categorías previas corresponde a clustering no supervisado. Una regresión sí necesita datos de entrenamiento; lo que no exige necesariamente es una serie temporal.

**Pregunta 6.** La demanda semanal basada en historial corresponde a pronóstico porque el orden temporal es decisivo. Las lecturas fuera del comportamiento habitual corresponden a detección de anomalías.

### Punto 4

**Pregunta 7.** Durante el entrenamiento se ajusta el modelo usando fotografías y resultados conocidos. Durante la inferencia, el modelo ya entrenado recibe una fotografía nueva y predice si existe daño.

**Pregunta 8.** Archivo con un millón de registros: batch, porque se procesa un conjunto. Respuesta web inmediata: tiempo real. Solicitud individual grande con respuesta posterior: asíncrona. Tráfico ocasional sin capacidad permanente: serverless.

### Punto 5

**Pregunta 9.** Una caída de desempeño puede deberse a deriva de datos, deriva del concepto, mala calidad de entrada, cambios del negocio, errores de la canalización o diferencias entre producción y entrenamiento. Antes de reentrenar hay que revisar datos y monitoreo, comparar con una referencia usando datos representativos no empleados para entrenar, revisar métricas técnicas y de negocio y aislar la causa. Reentrenar no garantiza mejorar.

**Pregunta 10.** Verdaderos positivos: 120. Falsos positivos: 160 − 120 = 40. Falsos negativos: 200 − 120 = 80. Precision = 120/160 = 75 %. Recall = 120/200 = 60 %. F1 = 2 × (0,75 × 0,60)/(0,75 + 0,60) = 66,7 %. No se puede calcular accuracy sin conocer también los verdaderos negativos y el total de casos legítimos.

### Punto 6

**Pregunta 11.** Amazon Transcribe convierte voz en texto; Amazon Polly convierte texto en voz; Amazon Translate traduce; Amazon Comprehend analiza lenguaje para extraer entidades, sentimiento y otros resultados.

**Pregunta 12.** Amazon Rekognition analiza imágenes y video; Amazon Textract extrae texto y estructura de documentos; Amazon Personalize crea recomendaciones; Amazon Lex construye interfaces conversacionales de voz y texto. Bedrock puede utilizarse para aplicaciones generativas conversacionales, pero no era el servicio especializado buscado en este ejercicio.

### Punto 7

**Pregunta 13.** Un modelo fundacional es un modelo preentrenado amplio que puede adaptarse a múltiples tareas y modalidades. Un LLM es un tipo de modelo fundacional centrado principalmente en lenguaje. No todos los FM trabajan exclusivamente con texto. Multimodal significa que el modelo procesa más de una modalidad, como texto e imágenes; las modalidades de entrada y salida dependen del modelo específico.

**Pregunta 14.** Un token es una unidad de texto procesada por el modelo. Un embedding es un vector numérico que representa propiedades semánticas de un elemento. La ventana de contexto limita los tokens que el modelo puede considerar, incluyendo instrucciones, conversación, documentos y espacio de salida según la interfaz. Un modelo de embeddings puede codificar una oración completa en un solo vector porque procesa la secuencia y representa su significado global; esto no se debe al solapamiento del chunking.

### Punto 8

**Pregunta 15.** Para integrar rápidamente FM administrados mediante API y construir una aplicación generativa con poca infraestructura, la elección principal es Amazon Bedrock. Para crear, entrenar y desplegar modelos con control detallado del ciclo de ML, la elección principal es SageMaker AI. No son excluyentes: ambos ofrecen capacidades administradas, personalización y despliegue, y pueden combinarse según los requisitos.

**Pregunta 16.** SageMaker JumpStart es un catálogo o hub dentro de SageMaker AI con modelos preentrenados, modelos fundacionales, algoritmos y recursos que facilitan evaluación, adaptación y despliegue. Si el modelo ya cumple los requisitos, puede desplegarse sin volver a entrenarlo; fine-tuning es opcional y depende de la necesidad.

### Punto 9

**Pregunta 17.** La respuesta identifica correctamente que deben compararse necesidades de latencia, costo de integración, mantenimiento y prioridad del negocio. También conviene medir costo total de propiedad, volumen, rendimiento, confiabilidad, escalabilidad, riesgo y retorno esperado.

**Pregunta 18.** El modelo debe admitir las modalidades requeridas y una ventana de al menos 80.000 tokens para 70.000 de entrada y 10.000 de salida; en la práctica se deja margen adicional. También deben evaluarse calidad, latencia, precio, rendimiento, integración, seguridad, cumplimiento, disponibilidad regional, mantenimiento y valor para el negocio.

### Punto 10

**Pregunta 19.** Zero-shot no incluye ejemplos; single-shot incluye uno; few-shot incluye varios. Chain-of-thought orienta al modelo a realizar razonamiento intermedio o por pasos para problemas complejos. Una prompt template es una estructura reutilizable con variables. Los ejemplos en el prompt cambian el contexto de la inferencia, no los parámetros del modelo.

**Pregunta 20.** El prompt debe separar instrucciones y correo mediante delimitadores, declarar que el correo es un dato no confiable y ordenar que no se sigan instrucciones incluidas en él. También debe limitar la respuesta a la fuente y usar `No especificado` cuando falte un dato. Los delimitadores aportan estructura, pero no garantizan seguridad. Bedrock Guardrails es una capa configurable de políticas que puede detectar ataques al prompt y bloquear o enmascarar información sensible; no es un documento. IAM aplica permisos de mínimo privilegio y limita los servicios y datos a los que la aplicación puede acceder.

### Punto 11

**Pregunta 21.** Durante la ingesta: conectar y analizar documentos, dividirlos en chunks, convertir los chunks en embeddings y guardar los vectores junto con texto y metadatos en un almacén vectorial. Durante la consulta: convertir la pregunta en embedding, buscar fragmentos similares —posiblemente aplicando filtros, búsqueda híbrida o reranking—, recuperar los relevantes, añadirlos al prompt y pedir al FM que responda con ese contexto. No se divide normalmente la consulta mediante el mismo chunking documental.

**Pregunta 22.** S3 puede guardar los documentos originales. El almacén vectorial guarda e indexa embeddings para la recuperación. Bedrock Knowledge Bases coordina la conexión, ingesta y recuperación para RAG. El FM redacta la respuesta usando el contexto recuperado. `Retrieve` devuelve los fragmentos para que la aplicación los procese; `RetrieveAndGenerate` recupera y genera una respuesta con referencias a las fuentes.

### Punto 12

**Pregunta 23.** Prompting e in-context learning cambian instrucciones o ejemplos de la solicitud y no modifican parámetros. RAG recupera contexto externo y tampoco modifica parámetros. Fine-tuning entrena adicionalmente y sí ajusta parámetros. El preentrenamiento continuo sigue entrenando con un corpus amplio de un dominio y también modifica parámetros; no significa reentrenar constantemente cada vez que cambia un documento. Para políticas semanales corresponde RAG. Para adaptar persistentemente el comportamiento a numerosos ejemplos corresponde fine-tuning, posiblemente instruction tuning.

**Pregunta 24.** Instruction tuning utiliza pares de instrucción y respuesta deseada para mejorar el seguimiento de tareas. RLHF utiliza preferencias o evaluaciones humanas para orientar el comportamiento mediante aprendizaje por refuerzo. La destilación utiliza las salidas o conocimiento de un modelo profesor para entrenar un modelo alumno más pequeño, normalmente buscando reducir costo y latencia conservando calidad suficiente.

## Diagnóstico

### Fortalezas actuales

- Reconoces IA agéntica y distingues entrenamiento de inferencia.
- Seleccionas bien regresión, clustering, pronóstico y anomalías en casos claros.
- Identificas correctamente batch, tiempo real, asíncrona y serverless, aunque debes justificar la elección.
- Mantienes la distinción esencial entre RAG y entrenamiento.
- Calculas correctamente precision y recall.
- Consideras necesidades del negocio, integración y mantenimiento al elegir modelos.
- Distingues zero-shot, single-shot y few-shot.

### Errores prioritarios

1. **Bedrock, SageMaker AI y JumpStart:** la comparación central no está consolidada.
2. **Ciclo de ML y F1:** faltan diagnóstico de deterioro, falsos positivos/negativos y cálculo de F1.
3. **Servicios especializados:** reforzar Amazon Lex y justificar cada selección.
4. **FM, LLM, tokens y embeddings:** corregir definiciones imprecisas y separar embeddings de solapamiento.
5. **Seguridad de prompts:** delimitadores, Guardrails e IAM cumplen papeles diferentes.
6. **Arquitectura de RAG:** separar la ingesta documental de la consulta y precisar las funciones de S3, vector store, Knowledge Bases y FM.
7. **Personalización:** distinguir fine-tuning de preentrenamiento continuo y elegir fine-tuning para comportamiento persistente basado en ejemplos.

## Plan de acción

### Bloque 1 — Correcciones críticas

- Bedrock frente a SageMaker AI frente a JumpStart.
- Precision, recall, F1, falsos positivos y falsos negativos.
- Amazon Lex frente a una aplicación generativa creada con Bedrock.

### Bloque 2 — Fundamentos de modelos y seguridad

- FM frente a LLM; token, embedding y ventana de contexto.
- Prompt template y chain-of-thought.
- Delimitadores, prompt injection, Guardrails e IAM.

### Bloque 3 — RAG y personalización

- Ingesta frente a consulta en RAG.
- S3, almacén vectorial, Knowledge Bases y modelo generador.
- Prompting, RAG, fine-tuning, preentrenamiento continuo, instruction tuning, RLHF y destilación.

### Comprobación posterior

- Realizar preguntas abiertas nuevas y situacionales sobre los errores anteriores.
- Registrar el resultado del refuerzo por separado; no sustituir la nota original de **14/24**.
- Retomar y completar el punto 13 después del refuerzo.
- La próxima evaluación formal acumulativa será al finalizar el punto 15 y tendrá al menos 30 preguntas, dos por cada punto del 1 al 15.

## Referencias oficiales utilizadas para validar la corrección

- [Guía oficial AIF-C01 — dominio 3](https://docs.aws.amazon.com/aws-certification/latest/ai-practitioner-01/ai-practitioner-01-domain3.html)
- [Amazon Bedrock o SageMaker AI](https://docs.aws.amazon.com/decision-guides/latest/decision-guides/bedrock-or-sagemaker.html)
- [Amazon SageMaker JumpStart — modelos fundacionales](https://docs.aws.amazon.com/sagemaker/latest/dg/jumpstart-foundation-models.html)
- [Amazon Lex V2](https://docs.aws.amazon.com/lexv2/latest/dg/what-is.html)
- [Amazon Bedrock Guardrails](https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html)
- [Amazon Bedrock Knowledge Bases — preparación de datos](https://docs.aws.amazon.com/bedrock/latest/userguide/kb-how-data.html)
- [Amazon Bedrock Knowledge Bases — recuperación](https://docs.aws.amazon.com/bedrock/latest/userguide/kb-how-retrieval.html)

