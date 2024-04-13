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

| Nombre | Descripción | Foto |
| ----- | ------- |  ----  |    
| Gabriela Nomberto Ramos | Soy Gabriela Nomberto, pertenezco a la carrera de Ingeniería de Software en el 8vo ciclo de esta.<br/> Tengo experiencia amplia en diversos lenguajes de programación, así como el uso de servidores cloud, soy muy organizada, responsable y sobre todo puntual. Soy bailarina de caporales en una agrupación externa a la universidad. Todo ello me enseñó a como trabajar en equipo, apoyar e investigar temas que me emocionan como lo es ciberseguridad y bases de datos, mis mejores habilidades es la comunicación en grupo y solucionar problemas bajo presión | ![Gaby](/Images/Gaby.jpg) |
| Dennis Quevedo Yucra    | Soy Dennis Piero Quevedo, estudiante de la carrera de Ingeniería de Software y estoy cursando el 8vo ciclo. Tengo conocimientos de múltiples lenguajes de programación. Así mismo, me encuentro realizando mis prácticas pre-profesionales aplicando todos los conocimientos adquiridos a lo largo de la carrera. Me considero una persona responsable y sobre todo puntual. Por otro lado, soy ciclista aficionado, me gusta mucho aprender por cuenta propia y una de mis mejores habilidades es solucionar los problemas a la brevedad posible | ![Dennis](/Images/Dennis.jpg) |
| Diego Osorio Horna      | Soy un estudiante de la carrera de Software de la UPC en Monterrico, actualmente estoy cursando el 8vo ciclo. Mi afición es la programación de aplicaciones web front-end y lenguaje favorito es JavaScript | ![Diego](/Images/Diego.jpg) | 
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

    Los problemas de salud mental suelen presentarse en cualquier lugar. En la etapa de la juventud, los problemas se pueden presentar en lugares concurridos donde uno puede socializar, como en la universidad, trabajo, hasta en el mismo hogar. Este problema no depende tanto del lugar donde se encuentre sino de las circunstancias en cómo suceden.

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

Para nosotros este es otro segmento fundamental dado que representan a las personas que buscan una atención médica de salud mental de calidad asi como de administrar y acceder a su información medica como lo es su historial de manera segura y sencilla