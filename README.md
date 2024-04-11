# MediConnect-Report
 ![Universidad Aplicada de Ciencias Aplicadas](https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png) 

 Universidad: Universidad Peruana de Ciencias Aplicadas

 Carrera: Ingeniería de Software

 Nombre del Curso: Arquitectura de Software Emergentes

 Sección: WX82

 Nombre del Profesor: Christian Luis de los Rios Fernandez

 "Informe del Trabajo Final"

 Nombre de la startup: "MediConnect"

 Nombre del Producto: "MedPro"

 Relacion de Integrantes:
  - Gabriela Soledad Nomberto Ramos (U202113876)
  - Dennis Piero Quevedo Yucra (U201619823)
  - Diego Enrique Osorio Horna (U201913822)
  - Andrea Sofia Alfaro Salinas (U202115862)

Mes y Año: Abril 2024

Ciclo: 2024-1   

# Registro de Versiones del Informe

| Version | Fecha | Autor | Descripcion de la Modificación  | 
|---------- | ----- |------ | ----------------| 


## Project Report Collaboration Insights 
**Enlace del Project Report:** [https://github.com/MediConnect-Arq/MediConnect-Report/tree/main] 

## Contenido 

### [Tabla de Contenidos](#tabla-de-contenidos)

### Student Outcome

### Capítulo I: Introducción
  - #### 1.1. Startup Profile
    - 1.1.1. Descripción de la Startup
    - 1.1.2. Perfiles de Integrantes del equipo
  - #### 1.2. Solution Profile
    - 1.2.1. Antecedentes y problemática
    - 1.2.2. Lean UX Process
      - 1.2.2.1 Lean UX Problem Statements
      - 1.2.2.2 Lean UX Assumptions
      - 1.2.2.3 Lean UX Hypothesis Statements
      - 1.2.2.4 Lean UX Canvas
  - #### 1.3. Segmentos Objetivos

### Capítulo II: Requirements Elicitation & Analysis
  - #### 2.1. Competidores
    - 2.1.1. Análisis competitivo
    - 2.1.2. Estrategias y tácticas frente a competidores
  - #### 2.2. Entrevistas
    - 2.2.1. Diseño de entrevistas
    - 2.2.2. Registro de entrevistas
    - 2.2.3. Análisis de entrevistas
  - #### 2.3. Needfinding
    - 2.3.1. User Personas
    - 2.3.2. User Task Matrix
    - 2.3.3. Empathy Mapping
    - 2.3.4. As-is Scenario Mapping
  - #### 2.4. Ubiquitous Language

### Capítulo III: Requirements Specification
  - #### 3.1. To-Be Scenario Mapping
  - #### 3.2. User Stories
  - #### 3.3. Impact Mapping
  - #### 3.4. Product Backlog

### Capítulo IV: Strategic-Level Software Design
  - #### 4.1. Strategic-Level Attribute-Driven Design
    - 4.1.1. Design Purpose
    - 4.1.2. Attribute-Driven Design Inputs
      - 4.1.2.1. Primary Functionality (Primary User Stories)
      - 4.1.2.2. Quality attribute Scenarios
      - 4.1.2.3. Constraints
    - 4.1.3. Architectural Drivers Backlog
    - 4.1.4. Architectural Design Decisions
    - 4.1.5. Quality Attribute Scenario Refinements
  - #### 4.2. Strategic-Level Domain-Driven Design
    - 4.2.1. EventStorming
    - 4.2.2. Candidate Context Discovery
    - 4.2.3. Domain Message Flows Modeling
    - 4.2.4. Bounded Context Canvases
    - 4.2.5. Context Mapping
  - #### 4.3. Software Architecture
    - 4.3.1. Software Architecture System Landscape Diagram
    - 4.3.2. Software Architecture Context Level Diagrams
    - 4.3.3. Software Architecture Container Level Diagrams
    - 4.3.4. Software Architecture Deployment Diagrams
### Conclusiones 
  - #### Conclusiones y Recomendaciones
  - #### Video About-the-Team
  
### Bibliografía

### Anexos

  
# Student Outcome

| Criterio Especíico | Acciones Realizadas | Conclusiones|
| ------------------ | ------------------- | ----------- |


# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

<div style="text-align: justify">
Como grupo hemos reconocido que existe un aumento desmedido en la mala salud mental que padecen los jóvenes durante los últimos años en el país.

Observamos que en la actualidad es común encontrar jóvenes entre 18 y 30 años que padecen de sentimientos frustrantes relacionados a temas laborales, académicos, familiares, económicos, etc. En la mayoría de estas situaciones hemos evidenciado que no se toma en cuenta la importancia que tiene la salud mental en la vida de las personas. Por esta razón, nuestro equipo de trabajo, al ver el grave estado de la salud mental de los jóvenes en la ciudad de Lima, nos juntamos para crear una solución de software eficaz que pueda aliviar y reducir los mencionados cuadros emocionales.

Decidimos crear nuestra Startup MediConnect, de esta forma conectaremos profesionales de la salud mental con personas que requieran, busquen o necesiten una ayuda para poder avanzar en aspectos de su vida diaria y no lleguen a encontrar una salida o solución, además contaremos con una línea de emergencia para el momento en que las personas lo requieran y a cualquier momento del día. 
Finalmente, le agregaremos un chatbot predictivo ....
</div>

### 1.1.2. Perfiles de integrantes del equipo

| Nombre | Descripción | Foto
| ----- | ------- |  ----  |    
| Gabriela Nomberto Ramos |  |  |
| Dennis Quevedo Yucra    |  |  |
| Diego Osorio Horna      |  |  | 
| Andrea Alfaro Salinas   |  |  | 


## 1.2. Solution Profile
### 1.2.1. Antecedentes y Problemática
<div style="text-align: justify">
Para esta parte haremos uso de la técnica de 5W’s y 2H’s para resaltar la problemática y poder solucionarlo.

  - Who?
  
    En principio, están involucrados en esta problemática un buen porcentaje de los jóvenes de 18 a 30 años pertenecientes a la cuidad de Lima, Perú. Quienes pasan por diversos problemas de tensión laboral, educativa, familiar, económica, etc.
  - What?

    La problemática que nosotros estamos enfrentando con nuestra solución es el alto índice del mal estado de la salud mental que se encuentra presente en gran cantidad de la población joven de 18 a 30 años de la ciudad de Lima, Perú. Este problema evidencia que la salud mental en nuestro país no es tomada en cuenta por el valor que tiene. Asimismo, la dificultad que existe para aliviar estos comportamientos son en su mayoría muy difíciles ya que los jóvenes le dedican un tiempo mínimo a su estabilidad emocional, evidenciando un aumento desmedido de cuadros de estrés, que en muchos casos suelen llegar a situaciones de ansiedad, depresión y problemas de aprendizaje en la población limeña.
  - When?
  
    Este problema es de hace bastante tiempo atrás, pero se ha hecho notar más a partir de los años 2000 en adelante. En la actualidad, los casos suelen suscitarse mucho más y evidencia que la mayoría de los jóvenes pueden pasar por cuadros de estrés, frustración o ataques en cualquier hora del día, dependerá mucho de la persona, de su entorno y de los problemas que este pasando.
  - Why?
  
    Sabemos que a raíz de la pandemia se vio una deficiencia notoria en los sistemas de los centros de salud y se debe mejorar para no presentar errores que puedan afectar a los pacientes, médicos y el mismo centro de salud.
  - Where? 

    Los problemas de salud mental suelen presentarse en cualquier lugar. En la etapa de la juventud, los problemas se pueden presentar en lugares concurridos donde uno puede socializar, como en la universidad, trabajo, hasta en el mismo hogar. Este problema no depende tanto del lugar donde se encuentre sino de las circunstancias en cómo suceden
  - How?
  
    Lo que llevó a estos jóvenes a llegar a esta situación son los diversos factores familiares, sociales, académicos que están pasando. Muchos de ellos, lo toman como problemas sin solución lo que causa frustración en ellos. Además, al no tomar en cuenta el valor que tiene su salud mental suelen dejar pasar esta sensación de estrés y evitan programar una cita con un psicólogo por falta de disponibilidad. Ante ello, los cuadros de frustración y problemas sin precedentes van en aumento llegando así a un punto grave.
  - How Much?
  
    Según fuentes confiables, a lo largo de este tiempo se ha evidenciado en los jóvenes que el problema de la falta de salud mental es un problema grave, confirmando según lo siguiente:
    - Según la Asociación Americana de Psicología, el 39% de las personas entre 18 y 33 años se declaran estresados. El estrés que sufren los jóvenes los hace más propensos a cuadros de irritabilidad y a sufrir de ansiedad o depresión.
    - Según el Consejo General de la Psicología, el 80% de jóvenes con trastornos de estrés y ansiedad no reciben ningún tratamiento o no buscan ayuda a profesionales expertos en la salud mental.
    - Según la Unicef, más del 20% de los jóvenes de todo el mundo sufren trastornos mentales.
    - Para entender la importancia de poner atención en estos tipos de problemas, según la OMS, el hecho de no ocuparse de los trastornos de salud mental de los jóvenes tiene consecuencias que se extienden a la edad adulta, perjudican la salud física y mental de la persona y restringen sus posibilidades de llevar una vida plena en el futuro.
    - De acuerdo con el Instituto Nacional de la Salud, cerca de 1 de cada 3 jóvenes entre las edades de 18 años puede tener un trastorno de ansiedad y estrés. El número va en aumento; entre el 2007 y el 2012, los trastornos de ansiedad en los jóvenes aumentaron un 20 %.
    - Hoy en día, se sabe que el Colegio de Psicólogos y las facultades luchan para mantener a flote la importancia de la salud mental, así como erradicar a los llamados “falsos psicólogos” que existen en Lima Perú. Asimismo, buscan que haya una mejor expansión y concientización sobre la salud mental hacia las personas. 

</div>

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions 
#### 1.2.2.3. Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos Objetivos
Identificamos dos segmentos objetivos claves para este startup que son los médicos que necesitan registrar de forma segura los tratamientos y/o citas; y los pacientes que necesitan saber que sus reservas, datos personales, historial médico, etc. se encuentren seguros y lo puedan visualizar de una forma sencilla. 


**Profesionales de la salud mental:**

Nos dirigimos a este segmento dado que requieren una solución segura y de confianza que les ayude a gestionar y registrar de manera segura los tratamientos, citas y algún aspecto clínico extra de los pacientes que atiendan y quieran sus servicios. 

**Usuarios que necesiten un apoyo:**

Para nosotros este es otro segmento fundamental dado que representan a las personas que buscan una atención médica de salud mental de calidad asi como de administrar y acceder a su información medica como lo es su historial de manera segura y sencilla.

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores
### 2.1.1. Análisis Competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas 
### 2.2.1. Diseño de Entrevistas

- Al comienzo de la entrevista
    - Al empezar la entrevista, nos presentaremos de manera correcta utilizando un lenguaje amical y breve para no perjudicar la comunicación con el usuario.
    - Deberemos solicitar la aprobación del usuario con la entrevista, mencionándole que lo sucedido en la entrevista será para recopilación de datos para uso académico y confidencial.
  
- Durante la entrevista
    - Se respetará la decisión del entrevistado si no quiere responder alguna pregunta para mantener el clima agradable y pueda expresarse de mejor forma sus opiniones.
    - Como entrevistador, debemos recaudar toda la información necesaria para poder lograr el objetivo del trabajo presente, debemos dirigir la entrevista por si llega haber una leve desviación del tema.
  
- Después de la entrevista
    - Siendo el entrevistador, debemos agradecer la participación y el tiempo brindado por el entrevistado, asimismo pediremos una conclusión del entrevistado y procederemos a cerrar la entrevista.

- Relación de preguntas (Médicos de la salud mental)
  1. ¿Cuál es su nombre, edad y ocupación?
  2. Usted que trabaja en un centro de salud o de manera independiente, ¿Qué deficiencias ha podido evidenciar al momento de registrar o revisar historiales clínicos?
  3. En algún momento y durante su horario de trabajo, ¿el sistema de registro con el cual trabaja no respondía o presentaba errores?
  4. Con lo dicho, ¿llego a tener problemas con los pacientes debido a los errores del sistema?
  5. Comentándole sobre nuestra aplicación web ¿Le sería de mayor utilidad y tendría la seguridad de usarlo? ¿Le podría ayudar a no cometer errores que en su campo laboral pueda ser básico?
  6. ¿Cuánto estaría dispuesto a pagar por la aplicación dándole mejoras a su atención al cliente? ¿Por qué?
  7. ¿Consideras que nuestro aplicativo podría satisfacer tus necesidades de mejorar tu salud mental? Caso contrario, ¿Qué mejoras le darías a nuestro producto para cumplir con este objetivo? 

- Relación de preguntas (Pacientes y/o personas necesiten ayuda para mejorar su salud mental)
  1. ¿Cuál es su nombre y edad?
  2. ¿Cuánto tiempo dedica en sacar una cita? ¿En algún momento tuvo errores o demoras en el sistema?
  3. ¿Cree que las deficiencias del sistema puedan mejorar y tener un mejor control propio de su avance médico?
  4. ¿De qué forma consideras que tu salud mental ha impactado en tu vida diaria durante los últimos años?
  5. ¿Qué aspectos crees que no se están tomando en cuenta al momento de hablar sobre la salud mental?
  6. ¿Qué esperarías encontrar en una aplicación que se dedique a mejorar la salud mental?
  7. Con lo comentado de nuestra aplicación web, ¿Estaría dispuesto a utilizar la aplicación que le dé una mejor atención y no encuentre errores al momento de registrarse o visualizar sus datos?
  8. ¿Cuánto estaría dispuesto a pagar por la aplicación por una mejor atención, asi como poder visualizar su historial médico?
  9. ¿Consideras que nuestro aplicativo podría satisfacer tus necesidades de mejorar tu salud mental? Caso contrario, ¿Qué mejoras le darías a nuestro producto para cumplir con este objetivo?
 
### 2.2.2. Registro de Entrevistas

**Especialistas de la Salud Mental**

| Foto de la Entrevista    | Descripción |
| -----------------------  | ----------- |
| ![Entrevista 1](/Images/entrevista%201.png) | N°: 1 <br/> Enlace: https://www.youtube.com/watch?v=w8fwZyjWcBc&ab_channel=D%C3%A9nnisPieroQuevedo <br/> Entrevistado: Alvaro Garcia Pinto <br/> Entrevistador: Dennis Piero Quevedo |
| ![Entrevista 2](/Images/entrevista%202.jpg) | N°: 2 <br/> Enlace:  <br/> Entrevistado: Antonella Del Carmen <br/> Entrevistador: Diego Osorio |

**Paciente o Usuario**

| Foto de la Entrevista    | Descripción |
| ------------------------ | ----------- |
| ![Entrevista 3](/Images/entrevista%203.jpg) | N°: 3 <br/> Enlace: https://www.youtube.com/watch?v=XSzqqVFpn9U&ab_channel=GabrielaNombertoRamos <br/> Entrevistado: Gabriel Aragón <br/> Entrevistador: Gabriela Nomberto |
| ![Entrevista 4](/Images/entrevista%204.png) | N°: 4 <br/> Enlace: https://www.youtube.com/watch?v=Y-awOdihQfY&ab_channel=D%C3%A9nnisPieroQuevedo <br/> Entrevistado: Fiorella Quevedo Mestanza <br/> Entrevistador: Dennis Piero Quevedo |

### 2.2.3. Análisis de Entrevistas

**Entrevista 1: Dennis Piero Quevedo (Especialista)**
En la entrevista, un profesional de la salud que trabaja en un centro médico expone deficiencias en la gestión de historiales clínicos, resaltando la falta de consistencia y detalles completos. Problemas con sistemas de registro lentos y errores al guardar datos han afectado la eficiencia y la calidad de la atención, generando frustración en los pacientes. El entrevistado ve una oportunidad en una aplicación web que evite errores y aumente la precisión en el registro. Estaría dispuesto a pagar por mejoras que beneficien a los pacientes y reduzcan errores. Además, considera que la aplicación podría contribuir a la salud mental de los pacientes, pero sugiere colaboración con profesionales especializados para lograr un enfoque integral y personalizado.

**Entrevista 2: Diego Osorio (Especialista)**
En esta entrevista, Antonella nos comenta que la aplicación les ayuda como profesionales de la salud a buscar personas que necesiten ayuda o aumentar su campo laboral. Nos comenta que para ella a sido muy difícil la inserción al campo laboral dado que no tiene recomendaciones por el momento pero que poco a poco lo ha ido teniendo.

**Entrevista 3: Gabriela Nomberto (Paciente)**
Durante la entrevista, Gabriel nos comenta que la aplicación utilizada tiene y cumple su propósito dado que a medida que busca un profesional para ayudarse puede ver las valoraciones que le dan al médico en cuestión y esto le da cierta confianza para que confíe en nosotros asi como también para que sus datos sean seguros. Nos comenta que las secciones adicionales le ayudarían demasiado, además que al ver su avance personal publicado le dará una cierta motivación para mejorar sesión tras sesión. 

**Entrevista 4: Dennis Piero Quevedo (Paciente)**
La entrevistada de 23 años nos comenta que ha llevado sesiones con un coach para poder mejorar en su vida diaria en el entorno laboral y social. Ella cree que la salud mental es importante y que influye bastante en cada acción que realiza e incentiva a los demás a tomar sesiones con un couch o psicólogo para aliviar algún problema que tengan. También, menciona que las gestiones de reservas en las entidades de salud mental tienen problemas al asignar algún especialista y demora mucho el proceso para obtener una cita. Además, considera que la aplicación podría contribuir a la salud mental de los pacientes, pero sugiere colaboración con profesionales especializados para lograr un enfoque integral y personalizado.

En general, esta solución parece estar bien alineada con las necesidades y preocupaciones expresadas por la entrevistada.


## 2.3. Needfinding
### 2.3.1. User Persona
### 2.3.2. User Task Matrix
### 2.3.3. Empathy Mapping 
### 2.3.4. AS-IS Scenario Mapping

## 2.4. Ubiquitous Language
