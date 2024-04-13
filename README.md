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

**Perfil del Startup**
| Startup | MedPro | Calm | Wysa | Simple Habit |
| ------- | ------ | ---- | ---- | -------------|
| Logo    | ![MedPro](/Images/medpro.png) | ![Calm](/Images/calm.png) | ![Wysa](/Images/wysa.png) | ![Simple Habit](/Images/shabit.png) |
| Overview | Nuestra StarpUp ayuda al sector médico a encontrar nuevas soluciones digitales. Dentro de la gestión del rubro como dentro de la propia medicina | Calm es una aplicación móvil y web que se dedica a disminuir los niveles de estrés de sus usuarios mediante la meditación con sonidos especiales. | Wysa es un aplicativo móvil que apoya a sus usuarios a que puedan gestionar sus factores estresantes por medio de una I.A y un chatbot que permite calmar su ansiedad. | Simple Habit es una aplicación de meditación en pequeñas capsulas guiadas y presentan videos que facilitan a los usuarios a conciliar el sueño en un día ajetreado. |
| Ventaja Competitiva <br/> ¿Qué valor ofrece a los clientes? | Nuestra StarpUp ayuda al sector médico a encontrar nuevas soluciones digitales. Dentro de la gestión del rubro como dentro de la propia medicina | Es un aplicativo que aparte de instalarse en dispositivos móviles también es para uso con el computador. Además, ofrece una serie de sonidos para la meditación y relajación auditiva. | Chat-Bot especializado en varias áreas de la salud mental, lo cual permite desestresarse de diferentes maneras. Se caracteriza por ser una app anónima y realiza sus actividades manteniendo privada los datos del usuario. | App móvil que permite aliviar los cuadros de estrés en 5 minutos todos los días |

**Perfil de Marketing**
| Startup | MedPro | Calm | Wysa | Simple Habit |
| ------- | ------ | ---- | ---- | -------------|
| Mercado Objetivo | Mayores de 15 años que presentan problemas de estrés. | Mayores de 10 años que presenten cuadros de estrés. | El uso es para mayores de 18 años, entre usuarios normales y trabajadores. | Para todo público que desee desestresarse. | 
| Estrategias de Marketing | Influencia por redes sociales como Instagram, Facebook, Twitter. | Influencia por redes sociales como Instagram, Facebook, Twitter. | Influencia por redes sociales Instagram, YouTube y Facebook. | Influencia por redes sociales (Facebook y YouTube) ofreciendo la app de manera gratuita totalmente. | 


**Perfil de Producto**
| Startup | MedPro | Calm | Wysa | Simple Habit |
| ------- | ------ | ---- | ---- | -------------|
| Productos & Servicios | Conexión con médicos especialistas en problemas de depresión, ansiedad y estrés. | Espacios virtuales que ayudan a aliviar el estrés a través de la meditación en tan solo 5 minutos | Espacios virtuales que ayudan a aliviar la frustración a través de consejos de profesionales. Asimismo, ofrecen el servicio de supervisión por medio de I.A. |  Espacios virtuales que ayudan a aliviar el estrés y ansiedad con la meditación.|
| Precios y Costos | Suscripción mensual dentro de la aplicación. | Planes anuales y de por vida, con 40% de descuento de 69.99 US$ USD | Planes gratuitos, diarios y anuales. con costos de $29,99 y $68,99 respectivamente. | Planes anuales por $49.99 y sea personales, familiar o para empresas. | 
| Canales de distribución (Web y/o Móvil) |   Web y Móvil | Web y Móvil | Móvil | Móvil | 

**Análisis SWOT**
| Startup | MedPro | Calm | Wysa | Simple Habit |
| ------- | ------ | ---- | ---- | -------------|
| Fortaleza | -Iniciación gratuita <br/> -Múltiples planes asequibles <br/> -Médicos muy profesionales y reconocidos | -Instalación gratuita <br/> -Ofrece múltiples herramientas para tener un mejor tiempo de sueño <br/> -El tiempo de alivio del estrés es de solo 5 minutos. | -Instalación gratuita <br/> -La aplicación puede ser utilizada a cualquier hora del día <br/> -Cuenta con especialistas que brindan conferencias internacionales para conocer más acerca de la salud mental | -Instalación gratuita <br/> -Puede ser descargado en móviles Android o IOS | 
| Debilidades | -Poca popularidad acerca de la aplicación | El tiempo de las sesiones gratuitas son muy limitadas | Los profesionales no están conectados al 100% durante las noches y la respuesta es muy tardía. | La aplicación está todo en inglés y no facilita su uso. | 
| Oportunidades | Importancia en la salud mental en los últimos años por parte de los jóvenes | Aumento del índice de estrés en la sociedad durante los últimos años |  Aumento del índice de estrés en los jóvenes a partir de la pandemia del Coronavirus <br/> Se necesita que las personas conozcan más sobre su salud mental | Aumento del índice de estrés en la población mundial a partir de la pandemia del Coronavirus | 
| Amenazas | La competencia empresarial está constantemente innovando. | Existe diversos competidores con la misma idea de negocio ya que no usan nuevas tecnologías | La competencia empresarial está constantemente innovando | Existe un alto índice de personas hispanohablante que tienen estrés, pero no cuentan con conocimientos del idioma inglés. | 

### 2.1.2. Estrategias y tácticas frente a competidores
- 1.	Identificar el entorno que nos rodea en este caso identificar los competidores que tenemos que brindan el mismo servicio que nosotros en este caso un sistema que une pacientes con medicos de la salud mental, además de preveer un chatbot con un pre diagnostico definido.
- 2. Crear un cuadro para ver que estrategias utilizan cada una de ellas que es lo que ofrecen para diferenciarse cada una de ellas y también nuestro sistema web
- 3. Nosotros ofreceremos una prueba gratis de un mes para que prueben nuestro sistema.
- 4. Como táctica utilizaremos la penetración de mercado, lo cual consiste en promover en todas las redes sociales sobre nuestro sistema de control y atencion al cliente ofreciendo un programa de fidelidad.

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

**Usuario que busca ayuda o pacientes**

El fin que nosotros buscamos no es vender más o solo buscar ganancias económicas, sino crear un impacto significativo en la forma en que los jóvenes experimentan sus vidas y mejoran el estado de su salud mental. La relación entre los artefactos a presentar con el user persona será fundamental para que nuestros usuarios sean los principales beneficiados <br/> ![User Persona paciente](/Images/User%20Persona%20paciente.png)

**Medico Especialista en al salud mental**

En este apartado, buscamos que los médicos tengan una mejor organización en sus agendas asi para poder tener un mejor control de los tratamientos que les puedan prescribir a sus pacientes. Tenemos en cuenta que todo esto es fundamental para que se permita una mejor atención al cliente o paciente. <br/> ![User Persona medico](/Images/User%20Persona%20medico.png)

### 2.3.2. User Task Matrix

**Paciente**

Se ha considerado como primer segmento objetivo los usuarios de Lima entre los 18 y 30 años que puedan sufrir de estrés debido a múltiples problemas surgidos en los tiempos actuales. Para este caso, utilizaremos a nuestro usuario Juan Aaron Rodriguez Chaves.

| User Task | Frecuencia | Importancia |
| --------- | ---------- | ----------- |
| Disponen de un tiempo durante su día para poder usar un chatbot de pre diagnostico | Media | Alta | 
| Separa una cita con nuestros médicos especializados | Media | Baja |
| Realizar actividades de relajamiento por un tiempo que hayan determinado | Media | Media |
|Toman contacto con grupos de apoyo para desestresarse | Media | Media |
| Analizan y ven cómo va la situación de progreso de su salud mental gracias al chatbot | Baja | Alta | 

**Medico**

Se ha considerado como segundo segmento objetivo los medicos especialistas en la salud mental. Para este caso, utilizamos a Javier Mendoza que ya cuenta con una especialidadd de la salud mental.

| User Task | Frecuencia | Importancia |
| --------- | ---------- | ----------- |
| Realizar evaluaciones iniciales de los pacientes para determinar sus necesidades de atención | Alta | Alta | 
|Diseñar planes de tratamiento personalizados para cada paciente, incluyendo terapias y posibles medicaciones | Media | Alta |
| Conducir sesiones de terapia individual o grupal para abordar problemas de salud mental de los pacientes | Alta | Alta |
| Realizar un seguimiento regular del progreso de los pacientes a lo largo del tiempo mediante el chatbot | Alta | Alta |
| Mantenerse actualizado sobre los avances en el campo de la salud mental y la psicología | Alta | Media 
| Colaborar con otros profesionales de la salud en casos de pacientes con necesidades médicas y psicológicas complejas | Media | Alta |
| Proporcionar apoyo y orientación a los pacientes en crisis o situaciones de emergencia | Baja | Alta |
| Documentar de manera precisa el progreso, los diagnósticos y los planes de tratamiento de los pacientes | Alta | Alta   

### 2.3.3. Empathy Mapping 

El Empathy Map fue realizado con la intención que nos ayude a planificar cómo llegar mucho más a nuestro público objetivo, se sientan escuchados y que nosotros como Startup buscamos lo mejor para nuestros usuarios. Para su realización nos basamos en los datos e información brindados por el User Persona durante las entrevistas. Para ello su implementación, se desarrolló el cuadro de manera grupal teniendo como puntos principales “Think and Feel”, “Hear”, “See”, “Say and Do”, “Pain Points y “Gain points”.

**Segmento 1: Pacientes o personas que se atiendan con un profesional de salud mental**
![EM Pacientes](/Images/EM%20Pacientes.jpg)

**Segmento 2: Profesionales de la salud mental**
![EM Medicos](/Images/EM%20Medicos.jpg)

### 2.3.4. AS-IS Scenario Mapping
En el As-Is Scenario Mapping analizamos al usuario antes de conocer nuestra aplicación, es decir cómo esta persona puede llegar a calmar su estrés normalmente con otras aplicaciones. Es por ello que nos basamos de las manifestaciones de nuestros entrevistados para identificar de esta manera las fases en las cuales están conformes o no.

![AS-IS Scenario](/Images/AS-IS.jpg)

## 2.4. Ubiquitous Language

Entendemos que, para este trabajo, todos los participantes tenemos que tener un lenguaje común para poder tener una mejor comunicación durante todo el avance de los proyectos y así también poder brindar una mejor experiencia al usuario, algunos conceptos que tenemos que tener en cuenta en el grupo es:

1.	Pacientes: Usuario que utilizará la aplicación web y quisiera informarse más o ayudarse en el problema que presenta
Síntomas: frustración, estrés, ansiedad, etc
Emociones: felicidad, tristeza, enojo, etc
Historial médico: medicinas, alergias 

2.	Médicos de la salud mental: Usuarios que conectarán con los pacientes, les dará tratamientos y diagnósticos, además de un seguimiento
Transtorno Mentales: TDAH, depresión, ansiedad, etc
Seguimiento: avances del progreso del paciente
Plan de tratamiento: terapias, medicación, ajustes en el estilo de vida del paciente, etc
3.	Chatbot: servicio que ofrece la plataforma para que el paciente tenga un pre diagnostico de lo que esta sintiendo en el día
Evaluación: preguntas de pruebas psicológicas automatizadas
Pre-diagnostico: depresión, ansiedad, etc
Severidad: leve, moderado, grave
Recomendaciones: ayuda psicológica

4.	Aplicación Web: entorno donde el paciente y el médico interactúan y usan los servicios que están a disposición de cada usuario
Interfaz de usuario: intuitiva, llamativa, accesible para el usuario
Seguridad: encriptación de datos sensibles y conexión privada entre paciente y médico. 
