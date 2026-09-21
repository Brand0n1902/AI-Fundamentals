# Evaluación acumulativa — AWS Certified AI Practitioner

**Cobertura:** puntos 1 al 12 de la ruta de estudio  
**Cantidad:** 24 preguntas abiertas, dos por cada punto  
**Puntuación:** 1 punto por respuesta completa, 0,5 por respuesta parcialmente correcta y 0 por respuesta incorrecta o ausente  
**Estado:** pendiente de responder

## Instrucciones

- Responde únicamente debajo de cada encabezado **Tu respuesta**.
- Conserva los enunciados y la numeración sin cambios.
- Explica brevemente el razonamiento; no basta con escribir solo el nombre de un servicio cuando la pregunta pide justificar.
- Para que el resultado mida tu retención, responde sin consultar materiales externos.
- No hay claves de respuesta ni pistas escondidas en el archivo.
- Cuando termines las 24 preguntas, guarda el archivo y avisa que está listo para corregir.
- La corrección se realizará después de completar todo el examen. Tus respuestas originales no se reemplazarán con las correcciones.

---

## Punto 1 — Fundamentos de IA

### Pregunta 1

Explica la relación entre inteligencia artificial, machine learning y deep learning. Después, indica qué característica distingue a la IA generativa de un modelo tradicional que solo clasifica datos.

#### Tu respuesta

En la relación la inteligencia artificial se puede solapar o dividir en machine learning el cual es el aprendizaje del modelo y dentro de este esta el deeo learning, el cual es un aprendizaje mas profundo. 
Una IA generativa genera un contenido, y un modelo tradicional que clasifica datos, justamente esta enfocado en la clasificacion de datos.

### Pregunta 2

Un asistente recibe un objetivo, decide varios pasos, consulta una herramienta autorizada y ejecuta una acción. ¿Qué concepto de IA representa? Explica por qué no basta con llamarlo simplemente chatbot o modelo generativo.

#### Tu respuesta
Agentic AI, por que realiza una serie de acciones con diferentes objetivos para lograr un objetivo. En comparación con chatbot que podría ser un LLM o un modelo de generativo, el cual genera contenido. El agentic AI para poder lograr su objetivo asignado hace uso de pequeñas tareas, decisiones, pasos y objetivos por cada uno.


---

## Punto 2 — Aprendizaje y datos

### Pregunta 3

Una empresa posee correos marcados previamente como `fraude` o `legítimo` y quiere entrenar un modelo para clasificar correos nuevos. Identifica el tipo de aprendizaje, explica qué papel cumplen las etiquetas y menciona qué serían las características de los datos en este caso.

#### Tu respuesta
Aprendisaje supervisado por que se tiene marcados los tipos de correos. Las etiquetas sirven para que el modelo no tenga que gastar recursos en saber que dato es el que va a aprender, con ello puede aprender el tipo de etiquetas son y como son sus caracteristcas, para poder identificar a otros correos que puedan tener las mismas caractericas. 

### Pregunta 4

Clasifica cada fuente como dato estructurado, semiestructurado o no estructurado y justifica brevemente: una tabla de ventas con columnas fijas, un archivo JSON de eventos y una grabación de una llamada. Luego explica cuándo tendría sentido usar aprendizaje no supervisado con alguno de esos datos.

#### Tu respuesta

Clasificacion: 
Dato estructurado -> tablas con columnas fijas
Semiestructurado -> archivo JSON
no estructurado -> grabación.

Tendría sentido usar el no estructurado con la grabacion, ya nos sirve para identificar patrones o caracteristicas dentro de la llamada, 

---

## Punto 3 — Problemas de machine learning

### Pregunta 5

Una tienda quiere realizar estas dos tareas: estimar el importe exacto que gastará un cliente y asignar clientes a grupos naturales sin categorías previas. ¿Qué tipo de problema de ML corresponde a cada tarea y por qué?

#### Tu respuesta

Regresión; no necesita de una serie de datos, simplemente estima por las caracteristicas de los datos una cantidad y clustering; agrupa por caracteristicas parecidas.

### Pregunta 6

Una fábrica quiere predecir la demanda semanal a partir de su historial y, además, detectar lecturas inusuales en sus sensores. Identifica el enfoque adecuado para cada necesidad y explica cuál es la pista decisiva en cada caso.

#### Tu respuesta
Pronostico; por que se basa en una serie de datos y/o historial previo para poder estimar una cantidad; deteccion de anomalias; busca algo raro que este fuera de las caracteristicas usuales del dato. 


---

## Punto 4 — Entrenamiento e inferencia

### Pregunta 7

Explica la diferencia entre entrenamiento e inferencia. Usa como ejemplo un modelo que detecta daños en fotografías de productos.

#### Tu respuesta

El aprendizaje es la etapa donde entreanan al modelo a poder detectar daños de productos por fotografias; y inferencias, es la tapa donde el modelo ya esta entrenado y ya puedo detectar si un productos esta dañado por fotografias. 

### Pregunta 8

Elige y justifica el modo de inferencia más apropiado para cada caso: a) procesar un archivo nocturno con un millón de registros; b) responder inmediatamente a una solicitud web; c) procesar una solicitud individual grande cuyo resultado puede llegar más tarde; d) atender tráfico ocasional e impredecible sin mantener capacidad permanente.

#### Tu respuesta
a) batch
b) tiempo real
c)  asincrona
d) serverless

---

## Punto 5 — Ciclo de ML y métricas

### Pregunta 9

Después de desplegar un modelo, su desempeño empeora. Explica por qué detectar el deterioro no revela automáticamente su causa y describe qué comprobaciones harías antes de decidir si debe reentrenarse o reemplazarse.

#### Tu respuesta

Si sigue siendo util para la empresa, o para el usuario que lo usa. Y comprobar que el problema no haya sido en el proceso de entrenamiento del modelo. 

### Pregunta 10

Existen 200 transacciones fraudulentas reales. El modelo genera 160 alertas y 120 de ellas corresponden realmente a fraude. Calcula **precision**, **recall** y **F1**. Explica también qué representan los falsos positivos y los falsos negativos en este caso.

#### Tu respuesta
Total: 200
Accuracy: 160
precision: 75%
recall: 60%

---

## Punto 6 — Servicios especializados de AWS

### Pregunta 11

Identifica el servicio de AWS más adecuado para cada tarea y justifica: convertir llamadas en texto, generar audio hablado desde texto, traducir mensajes y extraer entidades o sentimiento de documentos.

#### Tu respuesta
Transcribe, polly, translate, comprehend


### Pregunta 12

Identifica el servicio de AWS más adecuado para cada tarea y justifica: reconocer objetos o rostros en imágenes, extraer texto y estructura de formularios, crear recomendaciones personalizadas y construir un chatbot conversacional.

#### Tu respuesta
rekognition, textrac, personalize, bedrock


---

## Punto 7 — Modelos fundacionales y representaciones

### Pregunta 13

Explica la diferencia entre modelo fundacional y LLM. Aclara si todos los modelos fundacionales trabajan exclusivamente con texto y qué significa que un modelo sea multimodal.

#### Tu respuesta
- Un modelo fundacional no simpre es un modelo entrenado en texto, en cambio el LLM si. Ambos igual son modelos entrenados para ser utilices en personalizar mas el modelo si el usuario y el negocio lo requiere. Y multimodal significa que el modelo esta entrenado para aceptar y responder datos que no solamente sean textos, como fotos, videos, etc 


### Pregunta 14

Define **token**, **embedding** y **ventana de contexto**. Después explica por qué un embedding puede representar una frase completa y no necesariamente una sola palabra.

#### Tu respuesta

Token: es la unidad que se usa para el procesamiento de datos de un modelo. 
embaddings: es la representación numerica de una elemeto, procesado. 
Ventana de contexto:  es la cantidad de tokens que el modelo puede procesos, en todo el ciclo de la conversacion, desde la entrada hasta la respuesta. 
Por el solpamiento que hay para poder entender el input, y tokenizar según una representación importante para el modelo. Por lo que puede ser una palabra como una serie de palabras un embeddings. 


---

## Punto 8 — Amazon Bedrock, SageMaker AI y JumpStart

### Pregunta 15

Una empresa quiere consumir rápidamente modelos fundacionales administrados mediante API y añadir capacidades generativas sin construir todo el entorno de ML. Otra necesita control detallado para crear, entrenar y desplegar modelos dentro de un flujo completo de ML. ¿Qué plataforma de AWS encaja mejor en cada caso y por qué? Evita afirmar que sus capacidades son absolutamente excluyentes.

#### Tu respuesta

amazon sagemaker jumpsrtart, sirve por que tiene una coleccion de modelos, los cuales puedes escoger para realizar un entrenamiento o usarlo, manejando el control del cilo del ML.

### Pregunta 16

Explica qué es SageMaker JumpStart. Si un modelo preentrenado de su catálogo ya cumple los requisitos del negocio, ¿es obligatorio volver a entrenarlo? Justifica y aclara dentro de qué plataforma se utiliza JumpStart.

#### Tu respuesta

No, no es necesario volver a entrenar al modelo o hacer un fine-tuning, por que ya cumple con los requisitos del negocio. Eso esta dentro de la plataforma de sagemaker. 

---

## Punto 9 — Selección de modelos y valor de negocio

### Pregunta 17

Dos modelos producen resultados de calidad similar. El modelo A responde más rápido, pero cuesta más por solicitud. El modelo B es más barato por solicitud, pero exige más integración y mantenimiento. ¿Qué información adicional evaluarías antes de elegir y por qué el precio por solicitud no basta?

#### Tu respuesta
Debo de saber que modelo se adapta mas al negocio, si al negocio no le importa una respuesta rapida y estan dispuestos realizaer la integracion y mantenimineto o gastar en eso podria ser la B. O si lo que necesitan son las respuestas mas rapidas sin importar el costo, sería el modelo A. El precio en si no juega un rol tan importante en primera instancia, se necesita conocer al cliente, saber que es lo que necesita en su caso. 


### Pregunta 18

Una aplicación debe analizar imágenes y texto, aceptar una entrada de 70.000 tokens y generar hasta 10.000 tokens. Explica qué requisitos mínimos debe cumplir el modelo y qué otros criterios técnicos y de negocio considerarías antes de seleccionarlo.

#### Tu respuesta
Primero que el modelo sea multimodal, segundo que el modelo tenga mas de 80 mil token como ventana de contexo, y saber el caso de uso que va a tener el negocio con el modelo.


---

## Punto 10 — Ingeniería de prompts

### Pregunta 19

Define zero-shot, single-shot, few-shot, chain-of-thought y prompt template. Explica también por qué incluir ejemplos dentro del prompt no equivale a fine-tuning.

#### Tu respuesta

zero-shot: sin ejemplos
single-shot: un ejemplo
few-shot: mas de un ejemplo
chain-of-thought: dividir una tarea o problema en partes mas pequeñas.
propmt template: es un template, quese usa para que el modelo sepa como debe de responder.
El incluir ejemplos en el prompt no cambia los parametros del modelo, solo le cambia el contexo y el fine-tuning si modifica los parametros de este. 

### Pregunta 20

Un sistema resume correos que pueden contener instrucciones maliciosas y datos personales. Diseña, en palabras, un enfoque de prompt y controles complementarios que reduzcan invenciones, prompt injection y exposición de información. Distingue qué pueden aportar los delimitadores, Bedrock Guardrails e IAM.

#### Tu respuesta
Los delimitadores, le indica al modelo que temas no tocar en el procesamiento o que no prestar atencion en ese proceso. Bedrock guardrails son un documento donde asegura que el modelo evita algunos temas que pueden ser ofensivos, racistas, etc. IAM es el gestor de AWS permisos a los servicios de amazon


---

## Punto 11 — RAG y Amazon Bedrock Knowledge Bases

### Pregunta 21

Describe en orden el flujo de un sistema RAG basado en documentos: desde la preparación de las fuentes hasta la generación de la respuesta. Incluye chunking, embeddings, almacén vectorial, consulta, recuperación y contexto para el modelo.

#### Tu respuesta
consulta del usuario -> chucking de la consulta -> embedding de la consulta -> se busca su relacion cercana en el alamcen vectoria -> se recupera  -> contexto al modelo -> se redacta la respuesta


### Pregunta 22

Explica la función diferenciada de una fuente como Amazon S3, un almacén vectorial, Amazon Bedrock Knowledge Bases y el modelo fundacional. Después distingue `Retrieve` de `RetrieveAndGenerate` y da un caso en el que elegirías cada operación.

#### Tu respuesta
s3 storage serverless, alamcen vectorial almacenamiento de una serie numerica en una bd, bedrock knowledge bases provee de informacion al RAG, modelo fundacional es el modelo inicial. Un retrieve produce informacion de aucerdo al contexto brindado (RAG) mientras un retrieveGenerate, toma el contexo (RAG) como un contexto para respuesta pero genera contenido en base a al (RAG)


---

## Punto 12 — Personalización de modelos

### Pregunta 23

Compara prompting, RAG, fine-tuning y preentrenamiento continuo. Indica cuáles modifican los parámetros del modelo y elige la estrategia más apropiada para: a) políticas que cambian semanalmente; b) adaptar de forma persistente el comportamiento del modelo a muchos ejemplos especializados.

#### Tu respuesta
RAG: da contexto a un modelo sobre una base de información.
Fine-tuning: es un entrenamiento pequeño
preentranamiento continuo: es el entreamiento al modelo constantemente.

El fine-tuning y el preentramiento continuo modifican los parametros del modelo.

 a) políticas que cambian semanalmente; RAG
 b) adaptar de forma persistente el comportamiento del modelo a muchos ejemplos especializados.: Preentramiento constante

### Pregunta 24

Explica las diferencias entre instruction tuning, RLHF y destilación. Para cada una, indica qué tipo de señal o datos utiliza y cuál es el objetivo principal.

#### Tu respuesta
instruction tuning, es el entrenamiento mediante instrucciones al modelo, es un tipo de fine-tuning.
RLHF: reforzamiento de un humano en el entrenamiento.
destilacion: Crear un modelo mas pequeño de otro, y tratar de tener sus caracteristicas mas  importantes. 


---

## Declaración de finalización

Cuando hayas respondido todas las preguntas, cambia el estado inicial de **pendiente de responder** a **completada** y escribe aquí:

**Evaluación completada:** Completada

