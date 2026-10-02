# cognitivo
asistente estudiantil
## 1. Perfil del agente
<img width="1145" height="872" alt="Procesos cognitivos" src="https://github.com/user-attachments/assets/915abd2c-5e8b-4bc7-a22f-a31e0eb58c0f" />
<img width="1414" height="2000" alt="Índice Tabla Creativo Multicolor" src="https://github.com/user-attachments/assets/d02aa4f5-5d5d-4cef-b37e-038c85c081eb" />
inputs 
<img width="1920" height="1080" alt="cognitivo 2" src="https://github.com/user-attachments/assets/44b5cfd7-941f-4e02-8dc0-a4df8d35b506" />
diagrama de flujo 
<img width="1920" height="1080" alt="1" src="https://github.com/user-attachments/assets/0a1e90f0-0be7-4ec9-b96b-0fb8ee5b3736" />
filtros de atención 
filtro de longitud de texto 
1. Filtro de longitud: controlar mensajes demasiado extensos.
Menos de 100 palabras → atención completa.
Entre 100 y 500 palabras → identificar información principal.
Más de 500 palabras → priorizar palabras clave, ideas principales y última instrucción.
2 filtro de palabras importantes: El asistente busca palabras importantes relacionadas con el contexto académico.
Ejemplos:
examen,parcial,tarea,urgente,entregar,cálculo,química,programación,fecha
Si detecta estas palabras, aumenta su prioridad.
3 filtro emocional:
3 filtro emocional:
3 filtro emocional:Detecta el tono general del estudiante para adaptar la respuesta.
Por ejemplo:
Confusión → explicación más sencilla.
Estrés → dividir el problema en pasos.
Prisa → respuesta directa.
Curiosidad → explicación más amplia.
Frustración → lenguaje tranquilo y ejercicios progresivos.

Tipo de Memoria	Categoría de Datos	Descripción	Ejemplo de Entrada
Semántica (LTM)	Conceptos académicos	Conocimientos generales utilizados para resolver consultas académicas.	"Una derivada representa la tasa de cambio de una función."
Semántica (LTM)	Fórmulas y procedimientos	Fórmulas, reglas y procedimientos necesarios para las diferentes asignaturas.	"Fórmula de pendiente: m = (y₂-y₁)/(x₂-x₁)."
Semántica (LTM)	Asignaturas	Información organizada por áreas académicas.	"Cálculo, Química, Programación e Inteligencia Artificial."
Semántica (LTM)	Fechas y conceptos académicos generales	Información permanente relacionada con actividades académicas cuando sea necesario conservarla como referencia.	"Un parcial corresponde a una evaluación académica."
Episódica (LTM)	Historial de interacción	Información relevante de conversaciones anteriores que ayude a mantener el contexto.	"El estudiante estaba trabajando ejercicios de derivadas."
Episódica (LTM)	Perfil académico	Datos útiles del estudiante para personalizar la asistencia.	"El estudiante cursa Ingeniería en Inteligencia Artificial."
Episódica (LTM)	Preferencias de aprendizaje	Forma en la que el estudiante prefiere recibir explicaciones.	"Prefiere explicaciones paso a paso y de dificultad progresiva."
Episódica (LTM)	Horario y actividades	Información personal de organización académica proporcionada por el estudiante.	"Tiene clase de Cálculo los lunes."
Memoria de trabajo	Mensaje actual	Información temporal que el agente necesita mantener mientras procesa la solicitud.	"Resolver el ejercicio 3 de la guía."
Memoria de trabajo	Resultados de los filtros	Información obtenida durante el análisis del mensaje actual.	"Palabra clave detectada: parcial."
Memoria de trabajo	Contexto inmediato	Datos necesarios para construir la respuesta actual.	"El estudiante necesita una explicación sencilla."
3.1 Memoria semántica

La memoria semántica funciona como la enciclopedia interna del asistente. Contiene conocimientos académicos relativamente permanentes, como conceptos, fórmulas, definiciones, procedimientos y contenidos organizados por asignatura.

Esta memoria permite que el agente responda preguntas sin depender únicamente de la información presente en el mensaje actual.

3.2 Memoria episódica

La memoria episódica almacena información relacionada con las interacciones y experiencias académicas del estudiante. Su función es conservar el contexto necesario para personalizar futuras respuestas.

Por ejemplo, puede almacenar que el estudiante está trabajando en un tema determinado, qué tipo de explicación prefiere o qué actividad académica estaba realizando.
