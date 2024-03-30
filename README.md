# ¿Cómo escribir prompts en ChatGPT?
## ¿Para qué usar ChatGPT y prompt engineering?
Revolucionó el uso de la IA

**Diferentes usos:**
- Resumen de información
- Redacción de textos
- Asistencia personal virtual
- Redactar código de programación
- Toma de decisiones
- Chatbot de atención al cliente

> [!NOTE]
> Todo lo que requiera texto o comprensión de lenguaje se puede optimizar con los distintos modelos de PLN

Aprenderemos a diseñar preguntas o instrucciones para comunicarnos de manera efectiva con estas IA
**Prompt:** Instrucción a la IA.

Tienen cabida en todos los sectores de la industria
- Marketing
- Negocios
- Software
 - Y más

> [!WARNING]
> ADVERTENCIA: Nunca pongas información sensible o confidencial en ChatGPT

## Estructura de un Prompt
Los prompts se componen de instrucción, contexto, inputs y outputs, ejemplo:
```bash
Actúa como un experto en historia del arte,
compara y contrasta las pinturas "La última cena"
de Leonarda Da Vinci y "El Guernica" de Pablo Picasso,
entrégame las comparaciones en numerales.
```
- **Instrucción:** Compara y contrasta las pinturas.
- **Contexto:** Actúa como un experto en historia del arte.
- **Inputs:** "La última cena" de Leonarda Da Vinci y "El Guernica" de Pablo Picasso.
- **Outputs:** Entrégame las comparaciones en numerales.

> [!TIP]
> No siempre es nesesario tener los cuatro aspectos en un prompt.
> 
> ![image](https://github.com/dan33pro/PromptEngineeringChatGPT/assets/52634579/2b9da69c-8401-4ad9-9a57-a2c894b1ed8c)
>
> ![image](https://github.com/dan33pro/PromptEngineeringChatGPT/assets/52634579/27fffff4-6e31-4099-a6af-d63726370de0)
>
> ![image](https://github.com/dan33pro/PromptEngineeringChatGPT/assets/52634579/af18dbfe-07d2-4314-b1fe-43f342c69395)

## Limitaciones y uso ético de ChatGPT
**Falta de comprensión profunda:**
- Por ejemplo, en la instrucción del nutricionista él no entiende de problemas físicos ni mentales, solo satisface la estructura de texto que yo le dé
- No sabe interpretar sentimientos
- Respuestas plausibles pero incorrectas. Existen alucinaciones ya que siempre hay cierto grado de incertidumbre.
- Si no tienes un criterio para cierto tema, no es recomendable usar el chat.
- Sensibilidad al sesgo. Porque estos algoritmos se entrenan con datos de internet. El algoritmo puede tener sesgos raciales, económicos, étnicos.
- Vulnerabilidad a manipulación. Están entrenados para no apoyar acciones relacionadas con el mal. Sin embargo, hay técnicas para saltarse esos filtros.
- Respuestas largas y repetitivas. Sobre entrenados.
- Dificultad en mantener contexto. En conversaciones largas.
- Actualización en tiempo real. Bases de datos desactualizadas.
- Máximo de tokens. Límite de palabras al recibir y al generar.

## Precauciones al usar ChatGPT con información sensible o confidencial
Como usuario o usuaria de ChatGPT, es importante que tengas precaución al compartir información sensible o confidencial a través del chatbot. Aunque ChatGPT es una herramienta útil y segura para la mayoría de las interacciones, no es infalible y siempre existe la posibilidad de que tus datos puedan ser comprometidos.

Aquí hay algunas precauciones que debes tomar al usar ChatGPT para proteger tu información sensible:
1. No compartas información personal identificable con el chatbot. Evita compartir información como tu nombre completo, dirección, número de seguro social, número de tarjeta de crédito o cualquier otra información que pueda identificarte personalmente.
2. No compartas información que esté protegida bajo un acuerdo de confidencialidad (ADC), acuerdo de no divulgación (en inglés Non-Disclosure Agreement o NDA). Esto podría meterte en problemas y afectar a la empresa u organizaciones con las que colabores.
3. Ten cuidado con la información médica. Esta información es especialmente sensible y debe manejarse con precaución. Consulta con tu profesional de la salud para compartir información sobre tus condiciones médicas, medicamentos o tratamientos con ChatGPT.
4. Evita compartir contraseñas. Los chatbots no necesitan esa información para proporcionarte ayuda.
5. No compartas información financiera como números de cuenta o información de tarjetas de crédito o débito.
6. Asegúrate de estar en un entorno seguro. Evita utilizar ChatGPT en redes públicas o abiertas de Wi-Fi. Utiliza una conexión segura y privada, como una red Wi-Fi doméstica, una conexión celular o una VPN.
7. Revisa los términos y condiciones de uso de ChatGPT. Asegúrate de leer los términos y condiciones de uso de ChatGPT y comprende cómo se maneja y protege tu información. Si tienes preguntas o inquietudes, ponte en contacto con el equipo de soporte de ChatGPT.

Adicional a estas recomendaciones, te sugiero leer la visión y propuesta de OpenAI para desarrollar y usar sistemas de IA seguros y responsables.

---

En conclusión, aunque ChatGPT es una herramienta útil para trabajar con inteligencia artificial, siempre es importante tener precaución al compartir información sensible o confidencial. Sigue estas precauciones para proteger tus datos y mantenerlos seguros.

## Tips básicos para mejorar un Prompt: ㅤ

1. **Comienza simple:** Es recomendable comenzar con indicaciones simples para validar que el modelo sea capaz de generar lo que necesito, y poco a poco ir agregando elementos y contexto para ir obteniendo un resultado cada vez más preciso. Esto es útil cuando se tiene una tarea grande que se puede dividir en subtareas más simples.

![image](https://github.com/dan33pro/PromptEngineeringChatGPT/assets/52634579/bf4e1660-ce4f-469e-bd5a-3c6473612d31)

2. **Especificidad:** Ser muy específico en la instrucción que se le pide al modelo: cuanto más detalle se otorgue, se generarán mejores resultados. Los detalles deben ser relevantes y contribuir a la tarea en cuestión, siempre teniendo en cuenta la limitación de la cantidad de texto de entrada.
3. **Evitar imprecisiones:** Es importante no caer en ambigüedades al redactar los prompts. Hay elementos que pueden ser subjetivos entre lo que considero que significan y lo que el modelo puede considerar que significa (por ejemplo, utilizar “breve/extenso”, “poco/mucho”). Es mejor especificar al máximo (por ejemplo con valores numéricos) a qué nos referimos con estos elementos.
4. **Reafirma:** Resulta útil, al final de los prompts, preguntarle al modelo si entendió lo que debe realizar para obligarle a comenzar su respuesta con la confirmación textual de lo que debe realizar. Así nos aseguramos que esté haciendo lo que le pedimos y podremos detectar si necesitamos añadir mayor precisión.
5. **Audiencia objetivo:** En los casos en los que sea posible, podemos indicar una audiencia objetivo para garantizar mayor precisión en la manera en que el resultado debe ser generado (por ejemplo: para explicarle a un niño, a un estudiante universitario, a un experto en el tema).
6. **Proporcionar ejemplos:** Proporcionar ejemplos en el prompt sobre cómo queremos que sea el resultado, es muy efectivo para obtener respuestas muy ajustadas a formatos específicos.

## Errores comunes al escribir un prompt

1. **Demasiado extenso o complicado:** Se debe evitar extenderse innecesariamente, cambiar el sentido de la petición y caer en redundancias que no aporten a la especificidad del prompt y que haga difícil la tarea de identificar cuál es la instrucción específica que estamos dando.
2. **Jergas o ambiguedad:** De no ser estrictamente necesario, no utilizar palabras o expresiones que sean solamente utilizadas en algún país, región o por un nicho muy específico de la población. Entre más natural sea el lenguaje de entrada, mejor podrá ser el resultado.
3. **Limitaciones del modelo:** No tener en cuenta las limitaciones de los modelos nos puede llevar a caer en errores, ya sea en el contenido de la respuesta o de problemas como sesgos o información no actualizada.
4. **Supuestos:** Se relaciona con la especificidad. El prompt debe contener toda la información necesaria que evite al modelo tener que suponer datos de entrada que no le estamos otorgando.

# Técnicas básicas de prompt engineering
## Zero-shot y One-shot Prompting
Las técnicas Zero-shot, One-shot y Few-shot son utilizadas en todos los modelos de Inteligencia Artificial: no están limitadas a los modelos de generación de texto. ㅤ

- **Zero-shot:** Se refiere a la capacidad de un modelo para realizar una tarea por sí solo, sin necesidad de entrenamiento previo, utilizando solo una breve descripción de la tarea y sin necesidad de ejemplos o contextos. Ejemplo: “Diseña 10 preguntas de deletro para un niño de 7 años.” ㅤ
- **One-shot:** Se refiere a la capacidad de un modelo para realizar una tarea después de haberle proporcionado solamente un ejemplo que le ayude a ejecutar la instrucción. Ejemplo: “Diseña 10 preguntas de deletro para un niño de 7 años. Sigue el siguiente ejemplo: ¿Cómo se escribe la palabra del animal que ladra?” ㅤ
- **Few-shot:** Se refiere a la capacidad de un modelo para realizar una tarea después de haber entrenada con algunos pocos ejemplos. Ejemplo: “Diseña 10 preguntas de deletro para un niño de 7 años. Sigue los siguientes ejemplos: ¿Cómo se escribe la palabra del animal que ladra? ¿Cómo se escribe la fruta dulce y roja que crece en los árboles?” ㅤ

> [!IMPORTANT]
> Por defecto, ChatGPT está diseñado para no requerir el uso de One-shot o Few-shot prompting, puesto que está entrenado para generar los resultados adecuados con su propia base de conocimientos. Sin embargo, son técnicas que pueden ser útiles para contribuir a la especificidad de los prompts.

## Chain-of-Thought Prompting
Es un método que permite mejorar las habilidades de razonamiento de los modelos de lenguaje. 
El concepto de esta técnica, se basa en permitirle a los modelos descomponer un problema de varios pasos en pasos intermedios y así resolver problemas que no se podrían resolver con métodos de prompts estándar. ㅤ 
> [!TIP]
> 🧮 Esta es la manera de mejorar la precisión en tareas de razonamiento aritmético, en las que los modelos de lenguaje suelen tener bastantes dificultades para resolver correctamente. ㅤ

Este es un ejemplo de un prompt estándar que NO involucra el Chain-of-Thought:

![image](https://github.com/dan33pro/PromptEngineeringChatGPT/assets/52634579/9208e787-21fd-409e-817a-86bc2951c5a6)

Y en esta versión se incluye el Chain-of-Thought:

![image](https://github.com/dan33pro/PromptEngineeringChatGPT/assets/52634579/23555dd4-f339-4977-b1a8-52868fcd501f)

En este caso, el prompt estándar le pide al modelo una respuesta directa de un problema de razonamiento de varios pasos, conduciendo a una respuesta incorrecta. Mientras que el prompt utilizando Chain-of-Thought, descompone el problema en pasos intermedios que conducen a una respuesta correcta.

1. Otro ejemplo sencillo es si le preguntas lo siguiente con prompt estandar:
```bash
Toma las últimas letras de las palabras "Nunca pares de aprender" y concaténalas
```
Ahora con **Chain-of-Thought:**
```bash
Q: Toma las últimas letras de las palabras "Un corto ejemplo" y concaténalas
A: La última letra de la palabra "Un " es N, la última letra de la palabra "corto " es O, la última letra de la palabra "ejemplo " es O, al concatenarlas el resultado es "NOO"
Q: Toma las últimas letras de las palabras "Nunca pares de aprender" y concaténalas
```
> [!IMPORTANT]
> Q: (Pregunta) A: (Respuesta)

2. Un ejemplo más robusto del uso de cadena de pensamiento es este:
```bash
Eres un bot de decisiones. Tu trabajo es ayudar a tomar una decisión
haciendo una serie de preguntas una a la vez y llegando a una decisión
razonable basada en la información proporcionada.

Utilizará el siguiente formato para ayudar a crear la serie de preguntas.

formato: [Problema/Escenario/Pregunta]: [Proporcione una breve descripción del problema, escenario o pregunta].

Cadena de pensamiento:

[Paso 1]: Identifique el [elemento/variable clave] en [problema/escenario/pregunta].
[Paso 2]: Comprender la [relación/conexión] entre [elemento A] y [elemento B].
[Paso 3]: [Analizar/Evaluar/Considerar] el [contexto/implicación] de la [relación/conexión] entre [elemento A] y [elemento B].
[Paso 4]: [Concluir/Decidir/Determinar] el [resultado/solución] basado en el [análisis/evaluación/consideración] de [elemento A], [elemento B] y su [relación/conexión].
[Respuesta/Conclusión/Recomendación]: [Proporcione una respuesta coherente y lógica basada en la cadena de pensamiento.]

Guiarás al usuario a través de una serie de preguntas de una en una.
La primera pregunta es amplia, y las siguientes se vuelven más específicas.

Empieza presentandote y haciendo solamente y nada más que la primera
pregunta (paso 1), de manera sencilla y fácil.
```

3. Otro ejemplo de una **cadena de pensamiento** podría ser:
```bash
Toma las últimas letras de las palabras "Nunca pares de aprender" y concaténalas

Piensalo, paso por paso(palabra por palabra)
```

> [!WARNING]
> Este es un ejemplo de **Chain-of-Thought** que es **Zero-shot** pero no siempre da buenos resultados.
