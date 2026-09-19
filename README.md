<div align="center">
<p align="center">
  <img src="assets/img/upc_logo.png" alt="logo" width="200"/>
</p>

<h4>UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS</h4>
<h4>INGENIERIA DE SOFTWARE</h4>
<h4>CICLO 8</h4>
<h4>CURSO:</h4>
<h4>1ASI0728 – ARQUITECTURAS DE SOFTWARE EN TECNOLOGIAS EMERGENTES</h4>
<h4>NRC: 9077</h4>
<h4>PROFESOR(A): Marino Humberto Jara Palacios</h4>
<h4>INFORME DE TB1</h4>
<h4>CICLO: 2026-20</h4>

<br>

<h4>STARTUP: ReWear</h4>
<h4>PRODUCTO: Mirage</h4>
<h4>INTEGRANTES:</h4>
<p>
- Cabanillas Meza, Jose Mateo (u202311458)<br>
- Ortiz Cardenas, Johanna Antuanete (u202310358)<br>
- Sánchez Manrique, Italo Ludwing (u202316967)<br>
- Sarmiento Medina, Loreley (u202310005)<br>
- Zegarra López, Renato Sebastián Rubber (u202311558)
</p>

<br>

<h4>SETIEMBRE - 2026</h4>

</div>

<div style="page-break-after: always;"></div>



<br>
<br>
<br>


## Registro de Versiones del Informe

<div align="center">
<table>
  <thead>
    <tr>
      <th>Versión</th>
      <th>Fecha</th>
      <th>Autor</th>
      <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TB1</td>
      <td>17/04/2026</td>
      <td>
        - Cabanillas Meza, Jose Mateo <br>
        - Ortiz Cardenas, Johanna Antuanete <br>
        - Sánchez Manrique, Italo Ludwing <br>
        - Sarmiento Medina, Loreley <br>
        - Zegarra López, Renato Sebastián Rubber
      </td>
      <td>
        - Capítulo I: Introducción (1.1 – 1.3)<br>
        - Capítulo II: Requirements & Analysis (2.1 – 2.4)<br>
        - Capítulo III: Requirements Specification (3.1 – 3.4)<br>
        - Capítulo IV: Strategic-Level Software Design (4.1 – 4.3)
      </td>
    </tr>
  
  </tbody>
</table>
</div>

## **Project Report Collaboration Insights**

TB1 (19/09/2026):

 ![insights](assets/img/insights1.png)

## **STUDENT OUTCOME**

**ABET – EAC – Student Outcome 3 – Trabajo Multidisciplinario:** Capacidad de comunicarse efectivamente con un rango de audiencias.

<table border="1">
<thead>
<tr>
<th>Criterio específico</th>
<th>Acciones realizadas</th>
<th>Conclusiones</th>
</tr>
</thead>
<tbody>
<tr>
<td>3.c1. Comunica oralmente con efectividad a diferentes rangos de audiencia.</td>
<td>
<b>Cabanillas Meza, Jose Mateo</b><br>
TB1: Participé exponiendo los diagramas de arquitectura de software (system landscape, contexto, contenedores y despliegue) ante el equipo y el docente.<br><br>
<b>Ortiz Cardenas, Johanna Antuanete</b><br>
TB1: Participé explicando el Attribute-Driven Design (drivers, decisiones de diseño y escenarios de calidad) al equipo y en la sustentación.<br><br>
<b>Sánchez Manrique, Italo Ludwing</b><br>
TB1: Participé comunicando los hallazgos de entrevistas, needfinding y ubiquitous language en las revisiones del equipo.<br><br>
<b>Sarmiento Medina, Loreley</b><br>
TB1: Participé presentando el perfil de la startup, el proceso Lean UX y los segmentos objetivo ante el equipo y el docente.<br><br>
<b>Zegarra López, Renato Sebastián Rubber</b><br>
TB1: Participé exponiendo el Event Storming y el modelado estratégico de DDD al equipo.
</td>
<td>TB1: El equipo comunicó oralmente sus avances de forma clara y ordenada, adaptando el nivel técnico según la audiencia (compañeros, docente).</td>
</tr>
<tr>
<td>3.c2. Comunica por escrito con efectividad a diferentes rangos de audiencia.</td>
<td>
<b>Cabanillas Meza, Jose Mateo</b><br>
TB1: Me encargué de redactar la sección de arquitectura de software del informe (4.3).<br><br>
<b>Ortiz Cardenas, Johanna Antuanete</b><br>
TB1: Me encargué de redactar la sección de Attribute-Driven Design del informe (4.1).<br><br>
<b>Sánchez Manrique, Italo Ludwing</b><br>
TB1: Me encargué de redactar las secciones de entrevistas, needfinding y ubiquitous language del informe (2.2 a 2.4).<br><br>
<b>Sarmiento Medina, Loreley</b><br>
TB1: Me encargué de redactar el perfil de la startup, el Lean UX y el análisis de competidores del informe (1.1 a 2.1).<br><br>
<b>Zegarra López, Renato Sebastián Rubber</b><br>
TB1: Me encargué de redactar la sección de Domain-Driven Design con Event Storming del informe (4.2.2 a 4.2.5).
</td>
<td>TB1: El equipo elaboró un informe escrito estructurado y coherente, integrando cada sección de forma clara para distintos lectores (docente, equipo).</td>
</tr>
</tbody>
</table>

## **Contenido**

- [STUDENT OUTCOME](#student-outcome)
- [CAPÍTULO I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
      - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
      - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
      - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
      - [1.2.2. Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3. Lean UX Hypothesis](#1223-lean-ux-hypothesis)
        - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
 
- [CAPÍTULO II: Requirements & Analysis](#capítulo-ii-requirements--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1 Análisis de Competidores](#211-análisis-de-competidores)
    - [2.1.2. Estrategias frente a competidores](#212-estrategias-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3 Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. Empathy Mapping](#233-empathy-mapping)
    - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)
    - [2.4.	Ubiquitous Language.](#24-ubiquitous-language)
      
 - [CAPÍTULO III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
    - [3.2. User Stories](#32-user-stories)
    - [3.3. Impact Mapping](#33-impact-mapping)
    - [3.4. Product Backlog](#34-product-backlog)
      
 - [CAPÍTULO IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)
  - [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    - [4.1.1. Design Purpose](#411-design-purpose)
    - [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
      - [4.1.2.1. Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)
      - [4.1.2.2. Quality Attribute Scenarios](#4122-quality-attribute-scenarios)
      - [4.1.2.3. Constraints](#4123-constraints)
    - [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)
    - [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)
    - [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)
  - [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
    - [4.2.1. EventStorming](#421-eventstorming)
    - [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)
    - [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)
    - [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)
    - [4.2.5. Context Mapping](#425-context-mapping)
  - [4.3. Software Architecture](#43-software-architecture)
    - [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
    - [4.3.2. Software Architecture Context Level Diagrams](#432-software-architecture-context-level-diagrams)
    - [4.3.3. Software Architecture Container Level Diagrams](#433-software-architecture-container-level-diagrams)
    - [4.3.4. Software Architecture Deployment Diagrams](#434-software-architecture-deployment-diagrams)

- [Conclusiones](#conclusiones)
- [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
  
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

# CAPÍTULO I: Introducción

# 1.1. Startup Profile

## 1.1.1. Descripción de la Startup

ReWear es una startup tecnológica enfocada en mejorar la forma en que las personas organizan, aprovechan y se relacionan con las prendas que forman parte de su día a día. La propuesta combina moda y tecnología para ofrecer experiencias más personalizadas, ayudando a las personas a conocer mejor lo que tienen, descubrir nuevas posibilidades dentro de su propio armario y expresar su estilo de una manera más práctica. Buscamos aprovechar tecnologías como la inteligencia artificial y las experiencias digitales interactivas para desarrollar nuevas formas de relacionarse con la moda. ReWear parte de la idea de que la tecnología no solo puede ayudar a descubrir nuevas tendencias, sino también a comprender mejor el estilo personal y aprovechar de una manera más consciente las prendas que ya forman parte del guardarropa.

### Misión

Desarrollar soluciones tecnológicas que ayuden a las personas a organizar, conocer y aprovechar mejor su armario, brindándoles herramientas que faciliten la exploración de su estilo y la creación de nuevas combinaciones de manera sencilla y personalizada.

### Visión

Convertirnos en una startup referente en la aplicación de tecnología e inteligencia artificial a la moda, creando experiencias digitales que permitan a las personas relacionarse con su ropa de una manera más personalizada, práctica y consciente.

### 1.1.2. Perfiles de integrantes del equipo

| Estudiante | Descripción |
|------------|-------------|
| ![team member profile photo](assets/img/profiles/mateo_cabanillas.png) **Cabanillas Meza, José Mateo (u202311458)** | Mi nombre es Mateo Cabanillas y en la actualidad estoy cursando el octavo ciclo de la carrera de ingeniería de software en la universidad peruana de ciencias aplicadas, con una mente creativa y una actitud colaborativa. Mi amor por la programación y la resolución de problemas me impulsa a explorar nuevas soluciones y aportar ideas frescas a los proyectos. Como compañero de equipo, soy amable, atento y siempre estoy dispuesto a ayudar. Creo firmemente en la importancia de la comunicación efectiva y la colaboración para lograr resultados excepcionales. |
| ![team member profile photo](assets/img/profiles/loreley_sarmiento.jpg) **Sarmiento Medina, Loreley (u202310005)** | Mi nombre es Loreley Sarmiento, tengo 20 años y actualmente curso la carrera de Ingeniería de Software. Me considero una persona responsable, organizada y con buena disposición para el trabajo en equipo, ya que valoro la comunicación y la colaboración como elementos clave para lograr buenos resultados. Me interesa seguir aprendiendo constantemente y asumir nuevos retos que me permitan fortalecer mis habilidades.En este proyecto, busco participar de manera activa, apoyar a mis compañeros, aportar ideas que contribuyan al desarrollo del equipo y cumplir con las tareas asignadas dentro de los plazos establecidos, con el objetivo de alcanzar un resultado de calidad. |
| ![team member profile photo](assets/img/profiles/italo_sanchez.jpeg) **Italo Ludwing Sanchez Manrique (u202316967)** | Mi nombre es Italo Ludwing Sanchez Manrique, soy estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC) y actualmente curso el octavo ciclo académico. Me considero una persona perseverante, tolerante, responsable y comprometida con el cumplimiento de mis objetivos. Estas cualidades me permiten afrontar los diferentes retos que surgen durante el desarrollo de proyectos, manteniendo una actitud orientada a la búsqueda de soluciones, el aprendizaje continuo y la mejora constante. Tengo conocimientos en desarrollo de software, programación, bases de datos y diseño de soluciones tecnológicas, destacando principalmente en lenguajes como Java y C++. Asimismo, cuento con experiencia trabajando con diferentes tecnologías de gestión de datos, como SQL Server, PostgreSQL y MongoDB, desarrollando consultas, realizando operaciones de manipulación y gestión de información, y aplicando diferentes enfoques de almacenamiento de datos de acuerdo con las necesidades de cada proyecto. |
| ![team member profile photo](assets/img/profiles/antuanete_ortiz.png) **Ortiz Cardenas, Johanna Antuanete (u202310358)** | Mi nombre es Johanna Antuanete Ortiz Cárdenas, tengo 20 años y me encuentro en el sexto ciclo de la carrera de Ingeniería de Software. Me considero una persona proactiva y responsable, siempre buscando que mis trabajos sean de la mejor calidad posible. Me apasiona investigar sobre tecnología, lo que me permite estar al tanto de las últimas novedades y tendencias. En mi tiempo libre, disfruto jugar videojuegos, escuchar música y leer cómics. En el presente proyecto grupal, me comprometo a colaborar de manera activa, aportando ideas y siendo puntual con los entregables para garantizar resultados sobresalientes. |
| ![team member profile photo](assets/img/profiles/renato_zegarra.png) **Zegarra Lopez, Renato Sebastian Rubber (u202311558)** | Mi nombre es Renato Zegarra, tengo 20 años y actualmente estoy cursando la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Fuera de mis estudios, disfruto explorar mis intereses en música, videojuegos y tecnología, siempre buscando nuevas formas de integrar estas pasiones en mi vida cotidiana. Me comprometo a colaborar de manera activa y responsable en la elaboración de este documento y en la concreción de la idea propuesta, aportando mis habilidades en análisis, creatividad y adaptabilidad. Estoy convencido de que con esfuerzo y trabajo en equipo, podemos alcanzar resultados innovadores y de alta calidad. |

## 1.2. Solution Profile
Mirage consiste en una aplicación mobile enfocada en la gestión del armario personal y la exploración del estilo. La plataforma permitirá que los usuarios mantengan una representación digital de sus prendas y utilicen esa información para descubrir nuevas combinaciones, organizar outfits y recibir recomendaciones personalizadas de acuerdo con sus preferencias. Además, se plantea incorporar inteligencia artificial y tecnologías de visualización digital para enriquecer la experiencia del usuario. Entre las posibilidades que se explorarán se encuentra la generación de recomendaciones de outfits y la visualización de determinados artículos mediante representaciones tridimensionales y realidad aumentada.

### 1.2.1. Antecedentes y problemática
Para realizar una primera aproximación al problema se aplicó la técnica The 5 W's and 2 H's, considerando las preguntas Who, What, Where, When, Why, How y How Much.

### What

**¿Cuál es el problema que se está presentando?**

Las personas pueden tener una cantidad considerable de prendas y, aun así, utilizar solamente una parte de ellas con frecuencia. Tener más ropa no necesariamente significa conocer todas las posibilidades que existen dentro del propio armario o recordar todas las prendas que se encuentran disponibles.

*De Wagenaar et al. (2022)* analizaron el contenido de los guardarropas de participantes de diferentes países. Los participantes registraron en promedio 132.33 prendas, de las cuales 32.91 se encontraban sin uso, lo que representó aproximadamente el 24.87 % de las prendas registradas.Estos resultados corresponden a la muestra estudiada y no pueden generalizarse a toda la población. Sin embargo, permiten observar que existe una oportunidad para investigar cómo las personas pueden conocer y aprovechar mejor las prendas que ya poseen.

El problema que aborda el proyecto se relaciona principalmente con la dificultad para mantener una visión organizada del armario, recordar todas las prendas disponibles y encontrar nuevas maneras de combinarlas.

### When

**¿Cuándo se presenta el problema?**

El problema puede aparecer cuando una persona debe decidir qué ponerse y siente que no encuentra una combinación adecuada, incluso cuando dispone de diferentes prendas. También puede presentarse cuando organiza su armario, prepara un outfit para alguna ocasión o busca nuevas ideas para combinar su ropa. En estos momentos, la persona suele depender de revisar físicamente su armario, recordar combinaciones anteriores o buscar inspiración en diferentes medios digitales.

### Where

**¿Dónde se presenta el problema?**

El problema comienza principalmente en el armario personal, pero también se extiende al entorno digital.Actualmente, una persona puede guardar fotografías de prendas en su teléfono, encontrar outfits en redes sociales, descubrir referencias de estilo en diferentes plataformas o encontrar artículos que le resultan interesantes en tiendas digitales.

Sin embargo, esta información normalmente se encuentra distribuida entre diferentes medios y no necesariamente está relacionada con las prendas que la persona ya posee.

### Who

**¿A quién le sucede?**

Inicialmente se considera que este problema puede ser relevante para jóvenes y adultos jóvenes interesados en moda y acostumbrados al uso de herramientas digitales. Como referencia dentro del contexto peruano, *Leclercq-Machado et al. (2022)* realizaron una investigación con 396 consumidores de artículos relacionados con moda en Perú. Dentro de su muestra, el 88.3 % tenía entre 18 y 29 años y el 69.97 % eran estudiantes universitarios.

Estos porcentajes corresponden únicamente a la muestra de dicha investigación y no representan a toda la población joven del Perú. Sin embargo, sirven como antecedente para considerar inicialmente a un público joven vinculado con la moda y el uso de medios digitales.La delimitación final del público objetivo deberá validarse mediante encuestas, entrevistas y pruebas realizadas durante el desarrollo del proyecto.

### Why

**¿Por qué sucede el problema?**

Una de las razones es que el armario físico no siempre facilita recordar todas las prendas disponibles ni visualizar fácilmente las diferentes combinaciones que podrían realizarse con ellas.

*Jiang y Macintyre (2025)* analizaron 27 aplicaciones de gestión de armarios y 5,953 reseñas publicadas por usuarios. Entre las reseñas estudiadas, identificaron 70 usuarios que mencionaron cambios relacionados con un menor sobreconsumo o un mayor aprovechamiento de sus prendas. Asimismo, 210 usuarios mencionaron beneficios relacionados con mayor claridad mental o menor ansiedad.

Estos resultados provienen de opiniones publicadas por los propios usuarios y no de un experimento controlado. Sin embargo, muestran que algunas personas encuentran valor en utilizar herramientas digitales que les permiten conocer y organizar mejor las prendas que poseen.

### How

**¿Cómo se enfrenta actualmente el problema?**

Actualmente, las personas pueden revisar manualmente su armario, tomar fotografías de algunas prendas, guardar referencias en redes sociales o buscar ideas de outfits en Internet. El inconveniente es que estas acciones suelen realizarse por separado. Una combinación encontrada en Internet puede resultar atractiva, pero no necesariamente considera las prendas que el usuario realmente posee.

*Bang y Su (2022)* estudiaron la adopción de armarios virtuales mediante una investigación realizada con 265 estudiantes universitarios. Los autores describen este tipo de tecnología como una herramienta que permite crear y administrar digitalmente un guardarropa y utilizar esa información para apoyar decisiones relacionadas con el estilo. En su investigación encontraron que una actitud favorable hacia los armarios virtuales estaba relacionada con una mayor intención de utilizarlos.

Por otro lado, *Ding et al. (2023)* desarrollaron un modelo para generar outfits personalizados considerando tanto las preferencias del usuario como la compatibilidad entre las prendas. En sus pruebas, el modelo consiguió mejoras de 7.8 % y 10.3 % en precisión de personalización sobre los conjuntos de datos iFashion y Polyvore, respectivamente.Estos antecedentes muestran que existe una base tecnológica que permite explorar soluciones orientadas a organizar el armario y generar recomendaciones personalizadas.

### How Much

**¿Qué tan relevante es el problema?**

Actualmente no se cuenta con una medición propia que permita determinar qué porcentaje del público objetivo presenta este problema en el contexto local o con qué frecuencia ocurre. Esta información deberá obtenerse posteriormente mediante investigación directa con usuarios. Sin embargo, los antecedentes permiten identificar indicadores que justifican estudiar el problema. *De Wagenaar et al. (2022)* encontraron que el 24.87 % de las prendas registradas por los participantes de su estudio se encontraba sin uso.

Por su parte, *Jiang y Macintyre (2025)* analizaron 5,953 reseñas reales de usuarios de aplicaciones de gestión de armarios, encontrando experiencias relacionadas con organización, aprovechamiento de prendas y cambios en determinados hábitos.Estos resultados no permiten afirmar que todas las personas presenten el mismo problema, pero sí muestran que existe una situación que merece ser investigada dentro del segmento seleccionado.

Para el desarrollo de la solución se aplicará el proceso Lean UX con el objetivo de convertir las ideas iniciales del proyecto en supuestos que puedan ser evaluados y validados progresivamente con usuarios.

En esta etapa todavía no se asume que todas las funcionalidades propuestas resolverán el problema. Aspectos como la disposición del usuario a mantener un armario digital, el valor de las recomendaciones personalizadas o el interés por nuevas formas de visualización deberán ser comprobados mediante investigación, prototipos y pruebas.

### 1.2.2.1. Lean UX Problem Statements

#### Domain

El proyecto se encuentra dentro del dominio de la moda digital y la gestión personalizada del armario, incorporando tecnologías relacionadas con inteligencia artificial, sistemas de recomendación y nuevas formas de visualización digital.

#### Customer Segments

Inicialmente se considera como segmento a jóvenes y adultos jóvenes interesados en moda y familiarizados con el uso frecuente de plataformas digitales.

Este segmento representa un punto de partida para la investigación y podrá modificarse de acuerdo con los resultados obtenidos durante las entrevistas, encuestas y pruebas con usuarios.

#### Pain Points

A partir de los antecedentes revisados se identifican inicialmente los siguientes problemas:

- Dificultad para recordar todas las prendas disponibles en el armario.
- Uso frecuente de las mismas prendas o combinaciones.
- Existencia de prendas que permanecen sin utilizar.
- Dificultad para encontrar nuevas combinaciones utilizando la ropa existente.
- Información e inspiración distribuida entre diferentes aplicaciones y plataformas.
- Dificultad para visualizar cómo una nueva prenda o accesorio puede relacionarse con las prendas existentes.
- Recomendaciones de moda que no necesariamente consideran el armario real de cada persona.

Estos puntos representan una primera aproximación y deberán ser confirmados mediante investigación directa con usuarios.

#### Gap

Actualmente existen aplicaciones destinadas a organizar armarios y plataformas que ofrecen inspiración relacionada con moda. Sin embargo, existe una oportunidad para explorar una experiencia que tome como punto de partida el armario personal y utilice esa información para organizar prendas, generar combinaciones y ofrecer recomendaciones más relacionadas con el estilo de cada usuario.

Jiang y Macintyre (2025) muestran que algunos usuarios encuentran valor en las herramientas digitales de gestión del armario. Por otro lado, Ding et al. (2023) muestran que los sistemas de recomendación pueden considerar simultáneamente las preferencias personales y la compatibilidad entre diferentes prendas.

La oportunidad del proyecto consiste en investigar cómo estas capacidades pueden integrarse dentro de una experiencia centrada en el armario de cada persona.

#### Vision / Strategy

La estrategia consiste en colocar el armario personal del usuario como punto central de la experiencia.

En lugar de ofrecer únicamente recomendaciones generales de moda, la solución busca utilizar la información de las propias prendas y las preferencias del usuario para ofrecer una experiencia más personalizada.

A partir de esta información, el usuario podrá organizar su armario, descubrir nuevas combinaciones, planificar outfits y explorar diferentes posibilidades relacionadas con su estilo.

#### Initial Segment

Como segmento inicial se plantea trabajar con jóvenes de 18 a 29 años interesados en moda y familiarizados con herramientas digitales.

Este rango de edad constituye una hipótesis inicial de segmentación y deberá validarse posteriormente mediante investigación directa con el público objetivo.

#### Problem Statement

La solución está orientada a personas que poseen diferentes prendas, pero que no siempre tienen una visión clara de todo lo que existe dentro de su armario ni de las combinaciones que podrían realizar con ellas. Los antecedentes revisados muestran que una parte de las prendas registradas en guardarropas puede permanecer sin utilizar y que algunos usuarios encuentran valor en herramientas digitales que les permiten organizar y conocer mejor su ropa.

Actualmente, una persona puede recurrir a su armario físico, fotografías, redes sociales u otras plataformas cuando necesita inspiración. Sin embargo, estas alternativas no necesariamente consideran las prendas que realmente forman parte de su guardarropa.Por ello, se busca explorar una solución que permita reunir la información del armario personal y utilizarla para generar nuevas posibilidades de combinación y una experiencia más personalizada.

**¿Cómo podríamos ayudar a las personas a conocer y aprovechar mejor las prendas que poseen, facilitando la creación y organización de outfits de acuerdo con su propio estilo?**


### 1.2.2.2. Lean UX Assumptions

#### Business Assumptions

- Creemos que existe un grupo de personas que no tiene una visión completa de todas las prendas que posee.
- Creemos que organizar las prendas dentro de un armario digital puede aportar valor al usuario.
- Creemos que el armario digital tendrá mayor utilidad si la información registrada puede utilizarse posteriormente para generar nuevas combinaciones.
- Creemos que los outfits generados utilizando prendas del propio usuario pueden resultar más relevantes que recomendaciones generales.
- Creemos que permitir guardar y organizar outfits puede incentivar el uso recurrente de la solución.
- Creemos que incorporar prendas encontradas en otras fuentes como referencia puede ayudar a explorar nuevas posibilidades de estilo.
- Creemos que las recomendaciones pueden mejorar a medida que se conocen las preferencias del usuario.
- Consideramos que uno de los principales riesgos es que registrar las prendas requiera demasiado tiempo o esfuerzo.
- Otro riesgo consiste en que las recomendaciones generadas no representen adecuadamente el estilo de cada persona.
- La utilización de representaciones tridimensionales y realidad aumentada representa un reto tecnológico que deberá ser evaluado antes de considerarse parte definitiva de la solución.
- El modelo de monetización todavía no ha sido validado y deberá analizarse en etapas posteriores del proyecto.

#### User Assumptions

**¿Quién es el usuario?**

Una persona interesada en moda que utiliza herramientas digitales para encontrar inspiración y que posee prendas que podrían organizarse dentro de un armario digital.

**¿Dónde encaja la solución en su vida?**

Principalmente en aquellos momentos en los que necesita decidir qué vestir, organizar su ropa, preparar un outfit o buscar nuevas ideas utilizando las prendas que ya posee.

**¿Qué problema busca resolver?**

La dificultad para visualizar de manera organizada las prendas de su armario y encontrar nuevas formas de combinarlas.

**¿Cuándo podría utilizar la solución?**

Antes de decidir qué ponerse, al organizar el armario, cuando prepara un outfit para alguna ocasión o cuando busca inspiración para crear nuevas combinaciones.

**¿Qué características podrían ser importantes para el usuario?**

- Registro sencillo de prendas.
- Organización visual del armario.
- Recomendaciones personalizadas de outfits.
- Posibilidad de guardar combinaciones.
- Personalización según preferencias.
- Incorporación de prendas externas como referencia.
- Nuevas formas de visualización digital.

**¿Cómo debería comportarse la solución?**

La experiencia debe ser principalmente visual, sencilla y rápida de comprender. El usuario debería poder identificar fácilmente sus prendas, explorar combinaciones y entender por qué determinadas recomendaciones pueden relacionarse con su estilo.

### 1.2.2.3. Lean UX Hypothesis

Las siguientes hipótesis representan supuestos que deberán ser validados mediante investigación y pruebas con usuarios. Los valores o comportamientos esperados todavía no representan resultados obtenidos.

#### Hypothesis Statement 01: Armario digital

Creemos que permitir que los usuarios registren y visualicen sus prendas dentro de un armario digital facilitará que conozcan mejor lo que poseen.

Sabremos que esta hipótesis tiene sustento si los usuarios pueden consultar sus prendas con facilidad y consideran que la representación digital les ayuda a recordar lo que forma parte de su armario.

#### Hypothesis Statement 02: Registro de prendas

Creemos que los usuarios estarán dispuestos a invertir tiempo en registrar sus prendas si posteriormente reciben un beneficio claro.

Sabremos que esta hipótesis tiene sustento si los usuarios continúan incorporando prendas después de utilizar las primeras funciones relacionadas con organización o recomendaciones.

#### Hypothesis Statement 03: Generación de outfits

Creemos que las recomendaciones realizadas utilizando las prendas del propio usuario serán más útiles que recomendaciones generales de moda.

Sabremos que esta hipótesis tiene sustento si los usuarios muestran una mayor preferencia por las combinaciones generadas utilizando prendas de su propio armario.

Ding et al. (2023) sirven como antecedente para esta hipótesis, ya que sus resultados muestran que es posible combinar preferencias individuales y compatibilidad entre prendas para mejorar la personalización de los outfits.

#### Hypothesis Statement 04: Organización de outfits

Creemos que permitir guardar y organizar outfits facilitará que los usuarios planifiquen sus combinaciones.

Sabremos que esta hipótesis tiene sustento si los usuarios regresan posteriormente a consultar outfits que previamente guardaron.

#### Hypothesis Statement 05: Personalización

Creemos que conocer progresivamente las preferencias del usuario permitirá ofrecer recomendaciones más relacionadas con su estilo.

Sabremos que esta hipótesis tiene sustento si las recomendaciones posteriores reciben mejores valoraciones después de que el sistema cuente con mayor información sobre las preferencias del usuario.

#### Hypothesis Statement 06: Prendas de referencia

Creemos que permitir agregar prendas encontradas en otras fuentes ayudará al usuario a explorar cómo podrían relacionarse con las prendas de su propio armario.

Sabremos que esta hipótesis tiene sustento si los usuarios utilizan estas prendas para generar o evaluar nuevas combinaciones.

#### Hypothesis Statement 07: Recuperación de prendas poco utilizadas

Creemos que mostrar nuevas combinaciones utilizando prendas existentes puede ayudar a que los usuarios vuelvan a considerar ropa que utilizan con poca frecuencia.

Sabremos que esta hipótesis tiene sustento si los usuarios identifican prendas poco utilizadas dentro de las recomendaciones y muestran interés en volver a utilizarlas.

#### Hypothesis Statement 08: Visualización tridimensional

Creemos que representar determinados artículos en un entorno tridimensional puede aportar una nueva forma de explorar el estilo personal.

Sabremos que esta hipótesis merece continuar desarrollándose si las pruebas técnicas permiten generar representaciones suficientemente reconocibles y los usuarios consideran útil interactuar con ellas.

Chen et al. (2024) presentaron un método que permite reconstruir prendas tridimensionales utilizando una sola imagen como entrada. Este estudio sirve como antecedente técnico para explorar esta posibilidad, aunque no garantiza el funcionamiento completo de la funcionalidad propuesta dentro del proyecto.

#### 1.2.2.4. Lean UX Canvas
![LeanUx_canva photo](assets/img/LeanUX.png)
# 1.3. Segmentos objetivo

La solución está dirigida inicialmente a dos segmentos principales: por un lado, jóvenes interesados en organizar mejor su ropa y descubrir nuevas formas de combinarla; y, por otro, tiendas de moda que buscan aumentar la visibilidad de sus prendas dentro de un entorno digital más personalizado.

Ambos segmentos se relacionan dentro de la plataforma, ya que los usuarios podrán descubrir prendas de las tiendas, guardarlas como referencia dentro de su armario digital y acceder posteriormente al canal de la tienda si desean conocer más información sobre el producto.

### Consumidor de moda 
Personas que poseen distintas prendas, pero que no siempre recuerdan todo lo que tienen o encuentran nuevas formas de combinarlas. Buscan una manera más práctica de organizar su ropa, descubrir nuevas combinaciones y aprovechar mejor las prendas disponibles.

- **Edad estimada:** 15 a 30 años.
- **Ubicación inicial:** zonas urbanas.
- **Características demográficas y de comportamiento:**
  - Utilizan smartphones y plataformas digitales de manera frecuente.
  - Tienen interés por la moda y su imagen personal.
  - Buscan nuevas formas de combinar las prendas que ya poseen.
  - Pueden repetir outfits por no recordar todas las opciones disponibles en su armario.
  - Consumen contenido relacionado con moda, estilos y tendencias.
  - Están familiarizados con aplicaciones visuales y experiencias personalizadas.

- **Necesidades principales:**
  - Mantener sus prendas organizadas en un solo lugar.
  - Recordar con facilidad qué ropa poseen.
  - Encontrar nuevas combinaciones utilizando sus propias prendas.
  - Guardar y organizar outfits para diferentes ocasiones.
  - Aprovechar prendas que utilizan con poca frecuencia.
  - Descubrir nuevas prendas que puedan complementar su estilo.

### Tiendas de ropa

Tiendas de ropa, accesorios y productos relacionados con moda que buscan ampliar la exposición de su catálogo y llegar a usuarios interesados en prendas que puedan complementar su estilo personal.

Dentro de la plataforma, las tiendas podrán registrar prendas de su catálogo para que puedan ser descubiertas por los usuarios. Estas prendas podrán ser guardadas como referencia dentro del armario digital del usuario y estarán vinculadas al canal de la tienda correspondiente, permitiendo que la plataforma funcione como un medio de descubrimiento y visibilidad, sin realizar directamente la venta.

- **Tipo de organización:** tiendas de ropa, accesorios y negocios relacionados con moda.
- **Ubicación inicial:** negocios con presencia física o digital en zonas urbanas.
- **Características y comportamiento:**
  - Cuentan con un catálogo de productos que desean promocionar.
  - Utilizan redes sociales, páginas web u otros canales digitales para mostrar sus prendas.
  - Buscan nuevas formas de llegar a usuarios interesados en moda.
  - Necesitan generar mayor visibilidad para sus productos.
  - Valoran herramientas que permitan mostrar sus prendas dentro de contextos más personalizados.
  - Buscan atraer tráfico hacia sus propios canales digitales o comerciales.

- **Necesidades principales:**
  - Incrementar la visibilidad de sus prendas.
  - Mostrar su catálogo a usuarios con interés en moda.
  - Conseguir que sus productos sean descubiertos dentro de una experiencia personalizada.
  - Permitir que los usuarios guarden prendas de la tienda dentro de su armario digital.
  - Generar tráfico hacia sus propios canales de información o venta.
  - Tener presencia dentro de un entorno donde las prendas puedan relacionarse con el estilo y el armario de cada usuario.

# CAPÍTULO II: Requirements & Analysis

# 2.1. Competidores

## 2.1.1. Análisis de Competidores

### Competitive Analysis Landscape

**¿Por qué llevar a cabo este análisis?**

El análisis de competidores permite conocer cómo las soluciones actuales abordan la organización del armario digital, la recomendación de outfits y la personalización de la experiencia de moda. A partir de esta comparación se pueden identificar funcionalidades ya presentes en el mercado y oportunidades de diferenciación para la solución propuesta.

Para el análisis se seleccionaron Whering, Acloset y XZ(Closet) debido a que comparten características relacionadas con armarios digitales, organización de prendas y generación de combinaciones de ropa.

| Perfil | Aspecto | Solución propuesta | Whering | Acloset | XZ(Closet) |
|---|---|---|---|---|---|
| **Perfil** | **Overview** | Plataforma orientada a la gestión del armario personal mediante herramientas digitales e inteligencia artificial. Busca permitir al usuario organizar sus prendas, generar outfits personalizados y explorar prendas de tiendas que puedan complementar su estilo. También se plantea incorporar experiencias de prueba virtual y realidad aumentada. | Aplicación de armario digital y estilismo social que permite registrar prendas, crear outfits, planificar combinaciones, analizar el uso del armario e interactuar con los armarios de otros usuarios. | Aplicación de armario inteligente que utiliza IA para organizar prendas, recomendar outfits, registrar información automáticamente y apoyar al usuario en decisiones relacionadas con su estilo. | Aplicación de armario digital enfocada en ayudar al usuario a organizar sus prendas y recibir nuevas ideas de combinaciones de manera periódica. |
| **Perfil** | **Ventaja competitiva / ¿Qué valor ofrece?** | Busca integrar en una misma experiencia el armario personal, recomendaciones mediante IA, visualización de prendas y conexión con catálogos de tiendas. La propuesta para las tiendas se centra en aumentar la visibilidad de sus productos y dirigir a los usuarios hacia sus propios canales comerciales. | Cuenta con una fuerte orientación social y comunitaria. Permite explorar otros armarios, compartir outfits y analizar estadísticas como frecuencia de uso y costo por uso de las prendas. | Su principal fortaleza está en la automatización mediante IA. Puede reconocer información de las prendas, recomendar outfits e importar productos desde historiales de compra y páginas de tiendas. | Se caracteriza por una experiencia sencilla enfocada en generar ideas de outfits utilizando las prendas disponibles en el armario del usuario. |
| **Perfil de Marketing** | **Mercado objetivo** | Jóvenes interesados en moda y herramientas digitales, inicialmente entre 18 y 29 años. Como segundo segmento, tiendas de ropa y accesorios interesadas en obtener mayor visibilidad para sus productos. | Personas interesadas en organizar su guardarropa, crear outfits, compartir estilos y aprovechar mejor las prendas que poseen. | Usuarios interesados en utilizar inteligencia artificial para administrar su guardarropa, recibir recomendaciones de estilo y planificar outfits. | Hombres y mujeres que buscan organizar digitalmente sus prendas y recibir ideas para combinarlas. |
| **Perfil de Marketing** | **Estrategias de marketing / posicionamiento** | Posicionamiento centrado en personalización, uso del armario propio e integración entre usuarios y tiendas. Se plantea complementar la captación digital con alianzas con tiendas y experiencias mediante QR. | Su comunicación se enfoca en aprovechar mejor el armario, la comunidad, el intercambio de inspiración y una relación más consciente con la moda. | Su posicionamiento se centra principalmente en la inteligencia artificial, automatización del armario y reducción del esfuerzo necesario para organizar prendas y decidir qué vestir. | Su propuesta se comunica alrededor de una necesidad cotidiana: tener prendas disponibles pero no saber cómo combinarlas. Destaca la generación automática de ideas de outfits. |
| **Perfil de Producto** | **Productos y servicios** | - Armario digital<br>- Registro y clasificación de prendas<br>- Recomendaciones personalizadas de outfits<br>- Organización y guardado de combinaciones<br>- Catálogo de tiendas aliadas<br>- Incorporación de prendas comerciales al armario<br>- Avatar y probador virtual propuestos<br>- Experiencias de realidad aumentada propuestas<br>- Funciones sociales | - Armario digital<br>- Carga de prendas mediante fotografías, base de datos y navegador<br>- Creación y planificación de outfits<br>- Estadísticas del armario<br>- Listas de deseos y moodboards<br>- Funciones sociales<br>- Armarios compartidos<br>- Herramientas para viajes y planificación | - Armario digital con IA<br>- Clasificación automática de prendas<br>- Recomendación de outfits mediante IA<br>- Estadísticas de estilo<br>- Importación desde tiendas online<br>- Extensión para navegador<br>- Lista de deseos<br>- Funciones de estilista mediante IA<br>- Funciones de prueba virtual disponibles dentro de determinados planes | - Armario digital<br>- Registro de prendas<br>- Eliminación de fondo y recorte de imágenes<br>- Ideas automáticas de outfits<br>- Administración de prendas<br>- Recomendaciones periódicas de combinaciones |
| **Perfil de Producto** | **Precios y costos** | El modelo de monetización todavía se encuentra en etapa de definición y validación. No se ha establecido un precio definitivo para usuarios o tiendas. | Aplicación gratuita con compras dentro de la aplicación y servicios adicionales de pago. | Permite utilizar gratuitamente determinadas funciones hasta un límite de 100 prendas. Posteriormente requiere suscripción. En Perú, App Store muestra planes Básico, Premium y Experto con diferentes precios. | Aplicación gratuita con publicidad y compras dentro de la aplicación. En la App Store peruana aparecen opciones de pago desde aproximadamente S/ 2.90. |
| **Perfil de Producto** | **Canales de distribución** | - Aplicación móvil<br>- Landing page informativa<br>- Integración con tiendas aliadas<br>- Códigos QR en establecimientos físicos como canal complementario | - Aplicación móvil<br>- Sitio web<br>- Extensión de navegador | - Aplicación móvil<br>- Plataforma y extensión para navegador<br>- Integraciones con tiendas online | - Aplicación móvil para iOS/iPadOS<br>- Aplicación Android |
| **Análisis SWOT** | **Fortalezas** | Propuesta que busca conectar el armario personal con recomendaciones inteligentes y productos provenientes de tiendas. La integración B2C y B2B permite generar valor tanto para usuarios como para comercios. Las funcionalidades planteadas de avatar, QR y AR pueden aportar una experiencia diferenciada si se validan correctamente. | Comunidad amplia y consolidada, con más de 10 millones de usuarios declarados en su sitio oficial. Cuenta con funciones sociales, estadísticas de uso del guardarropa y diferentes herramientas de planificación. | Cuenta con más de 8 millones de usuarios declarados y presenta un fuerte uso de IA para automatizar el registro de prendas, generar recomendaciones y facilitar la incorporación de productos desde tiendas online. | Propuesta sencilla y directa para personas que buscan ideas de outfits. Permite añadir prendas rápidamente y recibir recomendaciones automáticas sin requerir una configuración demasiado compleja. |
| **Análisis SWOT** | **Debilidades** | La solución se encuentra en una etapa temprana y todavía no cuenta con una comunidad consolidada. Además, funcionalidades como IA, avatar, estimación corporal y AR incrementan considerablemente la complejidad técnica. El valor para las tiendas dependerá también de alcanzar una cantidad suficiente de usuarios. | La propuesta pública está fuertemente orientada al usuario final y a la comunidad. En las fuentes revisadas no se observa una propuesta B2B equivalente en la que las tiendas administren directamente un catálogo para obtener visibilidad dentro de la plataforma. | El acceso gratuito tiene límites y algunas funciones dependen de planes de suscripción. Su amplia cantidad de herramientas puede aumentar la cantidad de opciones que un usuario debe conocer y configurar. | Frente a Whering y Acloset, la propuesta pública presenta una menor amplitud de funciones relacionadas con IA avanzada, comunidad o integración comercial. En App Store se encuentra disponible principalmente en inglés y japonés. |
| **Análisis SWOT** | **Oportunidades** | Diferenciarse mediante la integración con tiendas locales, visibilidad de catálogos, códigos QR, personalización y experiencias de prueba virtual. También existe la oportunidad de adaptar la plataforma al contexto peruano y posteriormente latinoamericano. | Puede profundizar la integración con comercios y experiencias de prueba virtual para conectar su comunidad con productos externos. | Puede ampliar su modelo hacia una relación más directa con tiendas y marcas que quieran promocionar sus catálogos dentro de la experiencia del usuario. | Puede incorporar mayor personalización mediante IA, nuevas funciones sociales, idiomas adicionales y una mayor integración con tiendas. |
| **Análisis SWOT** | **Amenazas** | Whering y Acloset ya cuentan con millones de usuarios y funcionalidades de armario digital consolidadas. La rápida evolución de soluciones basadas en IA puede reducir la diferenciación si las funcionalidades propuestas no generan un valor claramente perceptible. | Competidores como Acloset están ampliando rápidamente sus capacidades de IA e integración con tiendas online. | Existe una alta competencia entre aplicaciones de armario digital e IA, y otras soluciones pueden incorporar rápidamente funciones similares de automatización. | Competidores con ecosistemas más completos, mayor personalización y capacidades de IA pueden atraer a los usuarios que buscan una experiencia más avanzada. |


## 2.1.2. Estrategias frente a competidores

### Personalización basada en el armario real del usuario

**Estrategia:** Diferenciar la experiencia utilizando las prendas que el usuario realmente posee como base para las recomendaciones.

**Táctica:** Utilizar la información registrada en el armario, las preferencias de estilo y las interacciones anteriores para generar outfits personalizados y permitir que el usuario refine las recomendaciones mediante comentarios o selecciones.


### Integración directa con tiendas de moda

**Estrategia:** Diferenciarse de aplicaciones centradas únicamente en el usuario mediante la incorporación de tiendas como segundo segmento dentro de la plataforma.

**Táctica:** Permitir que las tiendas aliadas creen un perfil profesional, publiquen prendas y accesorios de su catálogo e incluyan enlaces hacia sus propios canales oficiales. Las prendas podrán aparecer dentro de espacios de descubrimiento y ser utilizadas por los usuarios como referencia junto con su armario personal.


### Visibilidad de productos sin convertirse en marketplace

**Estrategia:** Ofrecer a las tiendas un nuevo canal de exposición sin asumir directamente el proceso de compra y venta.

**Táctica:** Cada prenda comercial podrá incluir información de la tienda y un acceso hacia su sitio web, red social o canal de venta. De esta manera, la plataforma genera descubrimiento y tráfico mientras la transacción continúa realizándose en el canal oficial de la tienda.


### Conexión entre tienda física y experiencia digital mediante QR

**Estrategia:** Integrar la experiencia presencial de las tiendas con las herramientas digitales de la plataforma.

**Táctica:** Permitir que las tiendas generen códigos QR asociados a determinadas prendas. El usuario podrá escanearlos para consultar el producto, incorporarlo a su armario virtual como referencia o utilizarlo dentro de las herramientas de combinación y prueba disponibles.


### Experiencia de prueba virtual

**Estrategia:** Complementar la organización del armario y las recomendaciones con una experiencia visual que permita experimentar con diferentes prendas y accesorios.

**Táctica:** Desarrollar progresivamente funcionalidades de avatar, probador virtual y realidad aumentada que permitan visualizar determinados artículos antes de utilizarlos o acceder al canal de la tienda.

Estas funcionalidades deberán validarse técnicamente y con usuarios antes de considerarse un diferenciador definitivo.


### Reducción del esfuerzo necesario para crear el armario digital

**Estrategia:** Reducir una de las principales barreras de las aplicaciones de armario: el tiempo necesario para registrar todas las prendas.

**Táctica:** Utilizar procesamiento de imágenes e inteligencia artificial para reconocer automáticamente información como tipo de prenda, categoría y color, permitiendo que el usuario revise y corrija los datos antes de guardarlos.

También se plantea permitir la incorporación rápida de prendas comerciales mediante códigos QR.


### Recomendaciones que evolucionen con el usuario

**Estrategia:** Evitar que el sistema funcione únicamente como un generador estático de outfits.

**Táctica:** Permitir que el usuario guarde, descarte y modifique recomendaciones. Estas interacciones podrán utilizarse para conocer mejor sus preferencias y mejorar progresivamente las sugerencias posteriores.


### Construcción de una comunidad alrededor del estilo

**Estrategia:** Complementar el armario individual con una experiencia social que permita obtener inspiración de otras personas.

**Táctica:** Permitir que los usuarios hagan públicas determinadas prendas u outfits, sigan a otros perfiles, reaccionen a combinaciones y exploren prendas disponibles públicamente en otros armarios.


### Adaptación inicial al mercado local

**Estrategia:** Desarrollar inicialmente una propuesta cercana al contexto del usuario peruano y a tiendas que necesiten nuevos canales digitales de visibilidad.

**Táctica:** Buscar alianzas con tiendas locales, trabajar con usuarios del segmento definido durante las primeras pruebas y adaptar progresivamente la experiencia según los resultados obtenidos.

La expansión hacia otros mercados deberá realizarse después de validar la propuesta de valor en el mercado inicial.

## 2.2. Entrevistas

De acuerdo con Easwaramoorthy y Zarinpoush (2006), las entrevistas son un método de investigación en el que se lleva a cabo una conversación orientada a recolectar información. A través de este método, se plantean una serie de preguntas que permiten conocer con mayor profundidad las experiencias, necesidades, comportamientos y puntos de vista de los participantes respecto a una problemática determinada.

Para Mirage, la información recogida mediante las entrevistas es fundamental para comprender las dificultades que presentan los consumidores de moda al momento de organizar sus prendas, recordar qué tienen disponible, encontrar nuevas formas de combinar su ropa y descubrir prendas que se adapten a su estilo. Asimismo, permitirá conocer las necesidades de las tiendas de ropa relacionadas con la visibilidad de sus productos, la promoción de sus catálogos y el uso de canales digitales para llegar a potenciales clientes.

Por ello, se plantea realizar un total de **3 entrevistas por cada segmento objetivo**, considerando tanto consumidores de moda como representantes de tiendas de ropa. Las entrevistas podrán realizarse de manera presencial o a distancia mediante herramientas digitales como Google Meet, Zoom o Discord, procurando en ambos casos generar un ambiente cómodo y adecuado que permita a los participantes expresar libremente sus experiencias y opiniones.

## 2.2. Entrevistas

De acuerdo con Easwaramoorthy y Zarinpoush (2006), las entrevistas son un método de investigación en el que se lleva a cabo una conversación orientada a recolectar información. A través de este método, se plantean una serie de preguntas que permiten conocer con mayor profundidad las experiencias, necesidades, comportamientos y puntos de vista de los participantes respecto a una problemática determinada.

Para Mirage, la información recogida mediante las entrevistas es fundamental para comprender las dificultades que presentan los consumidores de moda al momento de organizar sus prendas, recordar qué tienen disponible, encontrar nuevas formas de combinar su ropa y descubrir prendas que se adapten a su estilo. Asimismo, permitirá conocer las necesidades de las tiendas de ropa relacionadas con la visibilidad de sus productos, la promoción de sus catálogos y el uso de canales digitales para llegar a potenciales clientes.

Por ello, se plantea realizar un total de **3 entrevistas por cada segmento objetivo**, considerando tanto consumidores de moda como representantes de tiendas de ropa. Las entrevistas podrán realizarse de manera presencial o a distancia mediante herramientas digitales como Google Meet, Zoom o Discord, procurando en ambos casos generar un ambiente cómodo y adecuado que permita a los participantes expresar libremente sus experiencias y opiniones.

### 2.2.1 Diseño de entrevistas

## **Segmento objetivo #1: Consumidores de moda**

### **Preguntas principales:**

- ¿Cómo organizas actualmente las prendas que tienes en tu armario?
- ¿Con qué frecuencia recuerdas qué prendas tienes disponibles al momento de elegir qué vestir?
- ¿Qué dificultades encuentras al momento de elegir un outfit para una ocasión determinada?
- ¿Qué haces actualmente cuando quieres encontrar nuevas formas de combinar las prendas que ya tienes?
- ¿Con qué frecuencia utilizas prendas que tienes guardadas pero que usas poco?
- ¿Has tenido situaciones en las que compraste una prenda y luego descubriste que ya tenías otras prendas similares?
- ¿Qué medios utilizas actualmente para buscar inspiración sobre outfits, estilos o combinaciones de ropa?
- ¿Qué información consideras importante para decidir si una prenda combina con tu estilo o con otras prendas que ya tienes?
- ¿Has utilizado alguna aplicación o herramienta digital para organizar tu ropa, crear outfits o buscar inspiración? ¿Cómo fue tu experiencia?
- ¿Qué características esperarías de una aplicación que te permita registrar y organizar digitalmente las prendas de tu armario?
- ¿Qué tan útil sería para ti recibir sugerencias de outfits basadas en las prendas que ya tienes? ¿Por qué?
- ¿Qué factores considerarías importantes para confiar en las recomendaciones realizadas por una aplicación?
- ¿Qué opinas de poder visualizar digitalmente cómo podría verse una prenda o combinación antes de decidir utilizarla?
- ¿En qué situaciones considerarías útil utilizar realidad aumentada o una representación digital de una prenda?
- ¿Qué información te gustaría encontrar cuando descubres una prenda de una tienda dentro de una aplicación de moda?

### **Preguntas complementarias:**

- ¿Qué tipo de prendas te resulta más difícil combinar?
- ¿Qué haces cuando tienes una prenda que te gusta pero no sabes con qué combinarla?
- ¿Sueles planificar tus outfits con anticipación o decides qué vestir en el momento?
- ¿Qué aplicaciones relacionadas con moda utilizas actualmente y qué es lo que más valoras de ellas?
- ¿Qué haría que dejaras de utilizar una aplicación para organizar tu armario?
- Si pudieras mejorar una sola cosa de la forma en que actualmente eliges tus outfits, ¿qué cambiarías?

## **Segmento objetivo #2: Tiendas de ropa**

### **Preguntas principales:**

- ¿Cómo muestran actualmente sus prendas y productos a sus clientes?
- ¿Qué canales digitales utilizan actualmente para promocionar su catálogo?
- ¿Qué dificultades encuentran al momento de conseguir que sus productos tengan mayor visibilidad?
- ¿Cómo identifican actualmente qué productos generan mayor interés entre sus clientes?
- ¿Qué estrategias utilizan para llegar a nuevos clientes interesados en sus productos?
- ¿Qué importancia tiene para su negocio que una prenda sea mostrada dentro de un contexto relacionado con el estilo del cliente?
- ¿Han utilizado alguna plataforma digital adicional a sus redes sociales o página web para promocionar sus productos? ¿Cómo fue la experiencia?
- ¿Qué información consideran importante mostrar de una prenda para que un usuario pueda conocerla mejor?
- ¿Qué beneficios y dificultades encontrarían al registrar parte de su catálogo en una plataforma digital externa?
- ¿Qué características tendría que ofrecer una plataforma para que consideraran útil mostrar sus productos en ella?
- ¿Qué opinan de una plataforma que permita a los usuarios descubrir prendas de diferentes tiendas según sus preferencias y estilo?
- ¿Qué valor tendría para su negocio que un usuario pueda guardar una de sus prendas como referencia dentro de su armario digital?
- ¿Qué información o métricas les gustaría conocer sobre las personas que interactúan con sus productos dentro de una plataforma?
- ¿Qué opinan de utilizar representaciones digitales o tridimensionales para mostrar determinadas prendas?
- ¿Considerarían útil que los usuarios puedan visualizar digitalmente una prenda antes de visitar el canal de la tienda? ¿Por qué?

### **Preguntas complementarias:**

- ¿Qué tipo de prendas consideran que necesitan mayor promoción o visibilidad?
- ¿Qué redes sociales o plataformas les generan actualmente mayor interacción con sus clientes?
- ¿Qué dificultades encuentran al mantener actualizado su catálogo digital?
- ¿Qué información necesitarían de una plataforma para evaluar si realmente les genera valor?
- ¿Qué condiciones tendrían que cumplirse para que confiaran en una plataforma que muestre sus productos?
- ¿Qué funcionalidades adicionales les gustaría encontrar en una plataforma digital orientada a la promoción de moda?

### 2.2.2 Registro de entrevistas

En esta sección, el equipo realiza el registro de las entrevistas realizadas

### Segmento #1: Consumidores de moda

**Entrevista: Nicole González**  
- **Sexo:** Femenino  
- **Edad:** 18  
- **Link:** [Ver entrevista](https://www.youtube.com/watch?v=4Ar3FaM9zWA)  
- **Inicia en:** 0:04
- **Duración:** 8:00

![Registro_photo](assets/Entrevista/Entrevista-1.PNG)
  
### Resumen de entrevista: 

**Datos objetivos y perfil general:**  
Nicole González es una joven de 18 años que reside en el distrito de Ate, Lima. Se encuentra dentro del segmento objetivo de consumidores de moda jóvenes que utilizan tecnologías digitales diariamente. Organiza su armario físico agrupando las prendas por tipo de ropa y por color. No siempre recuerda con exactitud todo el catálogo de prendas que posee, por lo que debe revisar su clóset físicamente cada vez que arma un outfit.

**Características subjetivas – Personalidad y comportamiento:**  
Nicole muestra una personalidad práctica, juvenil y orientada a la estética personal. Tiende a decidir qué vestir en el momento de salir, salvo en ocasiones especiales donde planifica sus outfits con días de anticipación. Experimenta momentos de fricción y estres al no saber cómo combinar ciertas prendas o cuando no encuentra en su clóset lo que ve en plataformas de inspiración digital.

**Relación con la organización del armario y vestuario:**  
Al enfrentar fallas eléctricas como cortes de luz o tomacorrientes que no funcionan, su primera reacción es buscar ayuda externa. No intenta resolverlo por sí misma, y suele sentir frustración e incertidumbre. No realiza mantenimientos preventivos eléctricos debido a la falta de conocimientos técnicos y a la ausencia de recordatorios o planificación específica en su rutina.

**Canales de búsqueda y decisión:**  
Su canal principal para buscar inspiración de estilo es Pinterest, la cual valora por su versatilidad y variedad. Sin embargo, manifiesta que la experiencia resulta estresante y poco eficiente debido a que los outfits sugeridos en dicha red no corresponden con las prendas reales que ella tiene disponibles en su clóset.

**Dispositivos y tecnología utilizada:**  
Es usuaria habitual de smartphones y aplicaciones móviles con alto contenido visual. Demuestra una actitud sumamente receptiva hacia la incorporación de representaciones digitales y realidad aumentada (AR) para probarse ropa de manera virtual, destacando que esta tecnología le ahorraría tiempo valioso en días donde necesita vestirse con prisa.

**Criterios de elección de técnicos/proveedores:**  
Al momento de armar un outfit o evaluar prendas de tiendas externas dentro de una app, los factores que más valora son:

- **Coherencia estética y armonía de colores.**  
- **Compatibilidad con sus accesorios habituales.**  
- **Tallas y medidas exactas al explorar ropa de tiendas.**  
- **Previsualización digital de cómo le quedaría la prenda antes de usarla o comprarla.**  

**Influencias y factores de rechazo / abandono:**

Su decisión de adoptar y mantener el uso de una aplicación depende de la fluidez y libertad que esta le ofrezca. Mencionó explícitamente que dejaría de usar la plataforma si esta impone límites a la cantidad de ropa que puede subir o si requiere un costo/suscripción obligatoria. Valora la gratuidad en funciones esenciales de organización y la precisión de la IA para adaptarse a sus gustos.



**Entrevista 2: Matías Medina**  
- **Sexo:** Masculino  
- **Edad:** 21  
- **Link:** [Ver entrevista](https://www.youtube.com/watch?v=4H6sIBXIa74)  
- **Inicia en:** 0:04
- **Duración:** 5:24

![Registro_Matias_photo](assets/Entrevista/Entrevista-2.PNG)
  
### Resumen de entrevista: 

**Datos objetivos y perfil general:**  
Matías Medina es un joven de 21 años residente en el distrito de La Molina, Lima. Forma parte del segmento objetivo de consumidores de moda urbanos. Organiza su armario de manera básica dividiendo sus prendas únicamente por tipo (polos colgados en ganchos, pantalones guardados en cajones), sin categorizar por colores u ocasiones. Admite que solo recuerda y utiliza con frecuencia una pequeña fracción de su vestuario, manteniendo guardadas prendas que olvida que posee.

**Características subjetivas – Personalidad y comportamiento:**  
Matías muestra una personalidad práctica, reservada y con un alto enfoque en la comodidad funcional. Es un usuario que prioriza mantener su propio estilo personal por encima de las tendencias del momento. Su principal punto de fricción al vestirse radica en la dificultad de visualizar cómo lucirá una combinación sin probársela físicamente, lo cual le genera pérdida de tiempo e incertidumbre sobre si el outfit se ajusta al nivel de formalidad requerido por la ocasión.

**Relación con la organización del armario y vestuario:**  
Al no contar con una categorización estructurada, no le resulta fácil recordar todo su guardarropa. Ha comprado prendas duplicadas o casi idénticas en múltiples ocasiones (posee polos del mismo diseño y cuatro buzos prácticamente iguales) debido a no recordar lo que ya tiene. Ante la dificultad de combinar, suele repetir las mismas combinaciones seguras de siempre o recurre a comprar ropa nueva en lugar de explorar combinaciones con su vestuario actual

**Canales de búsqueda y decisión:**  
Consume esporádicamente contenidos en redes sociales, pero no las utiliza como su canal principal de inspiración. Considera que lo que se vuelve "trending" en internet no siempre refleja sus gustos reales, por lo que prefiere guiarse por su propio criterio estético y nivel de confort.

**Dispositivos y tecnología utilizada:**  
Es usuario habitual de smartphones. Mencionó haber intentado utilizar previamente aplicaciones extranjeras de organización de ropa (como la versión beta de la app "Alta"), aunque sintió limitaciones por la falta de disponibilidad completa en el país. Se muestra abierto a la tecnología siempre que le aporte soluciones prácticas y no sea restrictiva.

**Criterios de elección de técnicos/proveedores:**  
Al momento de elegir una prenda o evaluar una combinación, Matías establece la siguiente jerarquía de criterios:

- **Comodidad (factor primordial e indispensable).**  
- **Material y textura de la prenda.**  
- **Color y preferencia de tono personal.**  
- **Adecuación al contexto (evaluación de si el look es suficientemente formal o casual para el evento)**  

**Influencias y factores de rechazo / abandono:**

Su adopción de la plataforma está condicionada a la capacidad del sistema de mostrar visualizaciones integrales realistas. Dejaría de utilizar la aplicación si esta impone restricciones en sus funciones de personalización o si solo muestra listas/fotografías estáticas que no le permitan evaluar el outfit completo.



### Segmento #2: Tiendas de ropa

**Entrevista: Rodrigo Mendez**  
- **Sexo:** Masculino   
- **Edad:** 20  
- **Link:** [Ver entrevista](https://www.youtube.com/watch?v=QUZJWbwIgeY)  
- **Inicia en:** 0:05
- **Duración:** 4:59

![Registro_Tienda_photo](assets/Entrevista/Entrevista-3.PNG)
  
### Resumen de entrevista: 

**Datos objetivos y perfil general:**  
Rodrigo es un joven emprendedor de 20 años que administra la tienda de ropa "Clouds Plus Ultra", ubicada en el distrito de San Martín de Porres, Lima. Su modelo de negocio combina la atención directa en su local físico con la comercialización y exhibición digital a través de redes sociales. Mantiene un catálogo activo dirigido a un público joven interesado en moda urbana.

**Características subjetivas – Personalidad y comportamiento:**  
Rodrigo demuestra una actitud pragmática, innovadora y orientada al crecimiento comercial. Es consciente de la alta saturación de marcas en el mercado textil y busca constantemente alternativas para destacar. Valora la experiencia visual del cliente, comprendiendo que el usuario no solo compra una prenda por separado, sino por cómo esta se integra con su estilo de vestir personal.

**Relación con la organización del armario y vestuario:**  
Su mayor reto actual es la alta competencia en redes sociales y la dificultad para alcanzar orgánicamente a nuevos clientes. Mide el interés de sus productos evaluando las ventas finales, las consultas directas de precio/talla y las interacciones en publicaciones (likes y comentarios). Reconoce que cuando una prenda se muestra contextualizada (sugerida en un outfit real), el cliente logra imaginar la combinación con mayor facilidad, aumentando la probabilidad de compra.

**Canales de búsqueda, promoción y decisión:**  
Promociona su catálogo utilizando principalmente Instagram, Facebook, TikTok y WhatsApp Business. Hasta la fecha no ha utilizado plataformas comerciales o apps especializadas en fashion discovery, concentrando todos sus esfuerzos en redes sociales tradicionales y la recomendación boca a boca de sus propios clientes.

**Dispositivos y tecnología utilizada:**  
Utiliza smartphones y herramientas de gestión digital para administrar sus redes y canalizar ventas. Se mostró receptivo y entusiasmado ante la incorporación de tecnologías tridimensionales (3D) y Realidad Aumentada (AR), destacando que estas representaciones permiten apreciar mejor la calidad del diseño, los acabados y los detalles de cada prenda.

**Criterios de elección de técnicos/proveedores:**  
Para considerar útil una plataforma de exhibición de productos, Rodrigo exige que esta permita detallar los siguientes datos clave:

- **Fotografías de alta calidad de la prenda.**  
- **Precio, disponibilidad de colores y tallas.**  
- **Tipo de material y guía de medidas exactas.**  
- **Facilidad técnica para registrar y actualizar ítems en tiempo real.**  

**Influencias y factores de rechazo / abandono:**

Su principal preocupación y factor de fricción es la complejidad en el mantenimiento del inventario. Señaló que dejaría de usar la plataforma si la actualización del catálogo y precios resulta tediosa, si el sistema es difícil de usar o si no le proporciona estadísticas e indicadores útiles sobre el comportamiento del usuario con sus productos.

### 2.2.3 Análisis de entrevistas

En esta sección, el equipo realiza el análisis respectivo de las entrevistas cualitativas realizadas, consolidándolo en un resumen estructurado por cada uno de los segmentos objetivo de **ReWear**.

---

### Segmento 1: Consumidores de moda

**Total entrevistados:** 3  
**Edad promedio:** 22.5 años  
**Sexo:** 67% femenino, 33% masculino  

#### Características objetivas:
- **100%** utiliza sus smartphones y plataformas digitales (TikTok, Instagram, Pinterest) de manera frecuente para consumir contenido de moda.
- **100%** admite repetir outfits con frecuencia por no recordar todas las prendas disponibles en su guardarropa o por falta de tiempo en las mañanas.
- **100%** posee prendas en el clóset que utiliza con poca o nula frecuencia debido a la dificultad para combinarlas.
- **67%** tarda más de 15 minutos diarios probándose ropa frente al espejo antes de decidir qué vestir.
- **100%** muestra interés en probar herramientas tecnológicas que sugieran combinaciones automáticas según el clima, evento o estilo.

#### Características subjetivas:
- Sensación constante de "no tener nada qué ponerse" a pesar de tener el armario saturado de ropa.
- Frustración por no aprovechar la inversión económica realizada en prendas que quedan en el olvido.
- Ansiedad matutina provocada por la falta de organización y el desorden generado al probarse diferentes prendas.
- Actitud muy positiva hacia la digitalización de su ropa si el proceso de registro es rápido e intuitivo.

> **Insight clave:** El consumidor urbano no busca comprar más ropa constantemente, sino gestionar mejor lo que ya tiene. ReWear debe posicionarse como un organizador inteligente que libera tiempo, reduce el estrés matutino y redescubre el valor del guardarropa propio.

---

### Segmento 2: Tiendas de ropa y marcas independientes

**Total entrevistados:** 3 
**Edad promedio:** 23 años
**Ubicación / Cobertura:** Negocios urbanos con presencia física y digital (ej. San Martín de Porres)

#### Características objetivas:
- **100%** utiliza exclusivamente redes sociales tradicionales (Instagram, TikTok, Facebook, WhatsApp Business) como canales principales de promoción
- **0%** ha utilizado previamente aplicaciones o plataformas especializadas en *fashion discovery* o prueba digital
- **100%** enfrenta problemas para mantener visibilidad orgánica alta debido a la fuerte competencia y cambios de algoritmo en redes
- **100%** mide el éxito de sus productos mediante revisiones manuales de ventas, mensajes directos e interacciones sociales (likes y comentarios)
- **100%** está dispuesto a publicar su catálogo en una app externa si esta redirige tráfico a sus canales de venta sin cobrar comisión directa de venta

#### Características subjetivas:
- Preocupación constante por la baja efectividad y el alto costo de la publicidad pagada en redes sociales.
- Comprensión clara de que mostrar prendas aisladas no vende igual que mostrarlas integradas dentro de un outfit o estilo completo
- Entusiasmo por la incorporación de tecnologías 3D o Realidad Aumentada para resaltar la calidad de sus diseños
- Temor a que la gestión o actualización del inventario en la plataforma consuma demasiado tiempo operativo

> **Insight clave:** Las tiendas independientes necesitan un canal alternativo a las redes sociales que reduzca la fricción publicitaria. ReWear debe ofrecer un medio de descubrimiento donde sus prendas aparezcan en el contexto real de combinación de los usuarios, brindando métricas de interés real a cambio de un mantenimiento ágil del catálogo

---

**Entrevista: César Vázquez**  
- **Sexo:** Masculino  
- **Edad:** 22 años  
- **Ocupación:** Gerente de una tienda de ropa  
- **Link:** [Ver entrevista](https://youtu.be/GomduemGw4E?si=7g3iN5LehWtjluyt)  
- **Inicia en:** 0:02  
- **Duración:** 7:36  

![Entrevista_Cesar_Vazquez](assets/Entrevista/Entrevista_cesar.png)

### Resumen de entrevista

**Datos objetivos y perfil general:**  
César Vázquez tiene 22 años y trabaja como gerente de una tienda de ropa. Actualmente, la tienda utiliza principalmente canales digitales como Instagram y TikTok para mostrar sus productos, debido al carácter visual de estas plataformas. También cuentan con un catálogo para clientes que prefieren revisar las prendas de manera física y utilizan Gmail para comunicar novedades, nuevos productos y ofertas.

**Características subjetivas – Personalidad y comportamiento:**  
Durante la entrevista, César mostró una actitud abierta hacia el uso de nuevas herramientas digitales para promocionar las prendas de la tienda. Considera importante mantener una comunicación cercana con los clientes y conocer sus opiniones y gustos para poder ofrecerles recomendaciones más relacionadas con su estilo. También valora especialmente que las herramientas utilizadas por la tienda sean prácticas y fáciles de aprender, debido a que la incorporación de nuevo personal puede generar retrasos cuando las aplicaciones utilizadas son complejas.

**Promoción y visibilidad de las prendas:**  
La tienda concentra actualmente su promoción en Instagram y TikTok. César señaló que identifican qué productos generan mayor interés observando las preguntas realizadas por los clientes y las métricas disponibles en sus publicaciones, principalmente la cantidad de visualizaciones y "me gusta".

Uno de los objetivos de la tienda es llegar a más clientes y mantener una interacción constante con ellos. Para César, conocer las preferencias de cada persona también permite recomendar prendas que puedan ajustarse mejor a su estilo.

**Canales digitales utilizados:**  
Los principales medios utilizados actualmente por la tienda son:

- Instagram.
- TikTok.
- Gmail para informar sobre nuevos productos u ofertas.
- Catálogo físico.

César indicó que actualmente no utilizan una aplicación externa especializada ni cuentan con una plataforma propia adicional para promocionar su catálogo.

**Información importante al mostrar una prenda:**  
Para César, una publicación debería mostrar suficiente información para que el usuario pueda comprender correctamente las características del producto antes de interesarse por él.

Entre la información que considera más importante se encuentran:

- Medidas de la prenda.
- Tipo de material.
- Color real del producto.
- Tallas disponibles.
- Información visual clara y detallada.

Mencionó especialmente la importancia de representar correctamente el color, ya que una fotografía puede hacer que una prenda se vea más clara, opaca o desgastada de lo que realmente es.

**Dificultades en la gestión del catálogo:**  
Uno de los principales problemas identificados está relacionado con la actualización de productos entre el canal digital y la tienda física. César explicó que, cuando las ventas se realizan en ambos espacios, puede resultar difícil mantener correctamente actualizada la cantidad disponible de cada producto.

Esto puede ocasionar que una prenda permanezca publicada aunque ya no exista stock, que un producto haya salido de temporada o que resulte difícil identificar cuánto se ha vendido de manera virtual y cuánto de manera presencial.

Por esta razón, considera importante que una plataforma permita realizar cambios de manera rápida y sencilla, incluyendo:

- Agregar productos.
- Modificar información.
- Actualizar productos.
- Eliminar productos del catálogo.

**Valor de una plataforma de armario digital:**  
César considera positiva la posibilidad de que las prendas de una tienda puedan formar parte de una aplicación de armario virtual. Durante la entrevista indicó que este tipo de plataformas le parecen interactivas y que actualmente tienen potencial comercial.

También considera beneficioso que un usuario pueda guardar una prenda de la tienda dentro de su armario digital y utilizarla como referencia al momento de crear outfits. Desde su perspectiva, esto podría ayudar al cliente a reducir el tiempo necesario para decidir si una prenda combina con su ropa.

Además, señaló que una decisión más rápida antes de visitar la tienda podría contribuir a reducir el tiempo de compra, las colas y la aglomeración dentro del establecimiento.

**Información que sería útil conocer sobre los usuarios:**  
César manifestó interés en conocer determinada información del público que interactúa con las prendas de la tienda.

Entre los datos mencionados durante la entrevista se encuentran:

- Edad del usuario.
- Tipo de ropa de preferencia.
- Rango de precios de interés.
- Tallas.

Destacó particularmente el rango de precios y las tallas, debido a que esta información podría facilitar la presentación de productos más relacionados con las posibilidades y características del cliente.

**Percepción sobre Realidad Aumentada y prueba virtual:**  
César mostró una opinión favorable frente a la posibilidad de utilizar Realidad Aumentada para visualizar prendas o accesorios antes de visitar el canal de venta.

Considera que sería una propuesta creativa y que permitiría observar con mayor detalle los productos y apreciarlos desde diferentes ángulos. También señaló que visualizar previamente cómo podría verse una prenda sobre el usuario podría generar mayor seguridad respecto al producto que está considerando.

Según su percepción, este tipo de experiencia haría más eficiente el proceso de decisión del cliente, ya que tendría una referencia visual antes de acudir a la tienda o realizar la compra.

**Principales necesidades identificadas:**

- Conseguir mayor visibilidad para las prendas de la tienda.
- Llegar a nuevos clientes interesados en sus productos.
- Mostrar información detallada y visualmente clara de cada prenda.
- Mantener actualizado el catálogo de forma sencilla.
- Reducir problemas de sincronización entre productos disponibles en canales físicos y digitales.
- Conocer qué prendas generan mayor interés entre los usuarios.
- Conocer información como preferencias, rango de precios y tallas de potenciales clientes.
- Permitir que los usuarios puedan guardar productos y utilizarlos como referencia para crear outfits.
- Facilitar una experiencia que permita al cliente visualizar mejor una prenda antes de dirigirse al canal de venta.

**Influencias y factores de rechazo / abandono:**  
El principal factor de rechazo identificado es la complejidad de uso. César explicó que cuando una herramienta requiere demasiado tiempo para aprenderse, la capacitación de nuevo personal se vuelve más lenta y puede generar retrasos en las operaciones.

También podría existir una dificultad si la plataforma no permite mantener fácilmente actualizado el catálogo, especialmente cuando la tienda maneja simultáneamente productos y ventas en canales digitales y físicos.

Por ello, para que una plataforma resulte útil para la tienda, César considera importante que sea:

- Práctica.
- Fácil de aprender y utilizar.
- Rápida al momento de modificar información.
- Sencilla para agregar o eliminar productos.
- Capaz de mantener actualizado el catálogo.
---

## Síntesis de Hallazgos y Validación Cuantitativa

A partir de los datos consolidados del formulario y las entrevistas estructuradas, se identificaron los siguientes criterios para la elaboración de los gráficos de validación:

### Gráfico 1: Tiempo diario dedicado a elegir qué vestir (Consumidor)

![Grafico1](assets/Entrevista/Grafico1.PNG)
**Interpretación para el informe:** El 80% de los usuarios admite repetir combinaciones por falta de visibilidad de su ropa, respaldando la propuesta del Armario Digital

---

### Gráfico 2: Frecuencia con la que repiten outfits por falta de organización (Tienda)

![Grafico2](assets/Entrevista/grafico2.PNG)  
**Interpretación para el informe:** Muestra la alta dependencia de las tiendas hacia las redes sociales convencionales, lo que valida la necesidad de ReWear como un canal de descubrimiento especializado

---

### Conclusión general

El análisis cualitativo y cuantitativo demuestra una perfecta simetría entre ambos segmentos: los **consumidores** sufren por la falta de organización y creatividad al vestirse, mientras que las **tiendas de ropa** sufren por la falta de espacios contextualizados para exhibir sus catálogos. ReWear actúa como el punto de encuentro ideal al transformar la gestión del armario en un canal interactivo y de descubrimiento personalizado.

## 2.3. Needfinding

### 2.3.1. User Personas

En esta sección, el equipo presenta los User Personas realizados

### Olivia Rodriguez

/
![User_photo](assets/empathy/Olivia-Perez.png)

--- 

### Alejandro Lopez

/
![User_Alejandro_photo](assets/empathy/Alejandro-Lopez.png)

---


### 2.3.2. User Task Matrix

En esta sección se detallan las tareas clave que realizan los diferentes segmentos de usuarios representados por los **User Personas** de **ReWear**, con el objetivo de cumplir sus metas relacionadas con la organización del armario digital, el descubrimiento de outfits mediante Inteligencia Artificial, la prueba virtual en avatar 3D y la visibilidad de catálogos comerciales para tiendas aliadas.

| Persona | Actividad | Frecuencia | Importancia |
|---|---|---|---|
| **Olivia Rodríguez - Consumidor de moda** | Digitalizar prendas en el armario virtual mediante captura de foto o carga | Frecuentemente | Alta |
| | Solicitar recomendaciones automáticas de outfits a la IA según el contexto (clima, evento) | Diariamente | Alta |
| | Probar combinaciones de ropa y accesorios sobre su avatar 3D personalizado | Frecuentemente | Alta |
| | Guardar y organizar outfits favoritos en colecciones personalizadas | Frecuentemente | Media |
| | Escanear códigos QR en tiendas para vincular prendas de catálogo a su armario | Ocasionalmente | Media |
| | Explorar el armario virtual de amigos e interactuar con prendas compartidas | Ocasionalmente | Media |
| **Alejandro López - Owner de boutique / Tienda de ropa** | Registrar y cargar prendas del catálogo comercial en la plataforma | Ocasionalmente | Alta |
| | Generar códigos QR comerciales para etiquetado en tiendas físicas o e-commerce | Ocasionalmente | Alta |
| | Monitorear métricas de rendimiento (veces guardada la prenda, pruebas en avatar) | Frecuentemente | Alta |
| | Actualizar información, fotos o etiquetas de prendas registradas | Ocasionalmente | Media |
| | Evaluar el tráfico derivado desde la plataforma hacia sus propios canales de venta | Frecuentemente | Alta |

### 2.3.3. Empathy Mapping

En esta sección , el equipo presenta los mapas de empatia o Empathy Maps realizados por User Persona

### Olivia Rodriguez

/
![Empathy_Mapping_ photo](assets/empathy/Olvia-Empathy-map.png)

---

### Alejandro Lopez

/
![Empathy_Mapping_ photo](assets/empathy/Alejandro-Lopez-empathy.png)

---


### 2.3.4. As-is Scenario Mapping

En esta sección, el equipo presenta los escnerarios as is para sus respectivos users personas


### Olivia Rodriguez

![ As-is_photo_Olvia](assets/As-is/As-is-olivia.PNG)

---

### Alejandro Lopez

![ As-is_photo_Alejandro](assets/As-is/As-is-Alejandro.PNG)

---

## 2.4. Ubiquitous Language

De acuerdo con Evans (2003), el Lenguaje Ubicuo (*Ubiquitous Language*) es un pilar fundamental del Diseño Guiado por el Dominio (*Domain-Driven Design*), consistente en un lenguaje común y estructurado compartido entre los desarrolladores del software y los expertos del dominio de negocio. A través de este glosario, se busca eliminar las ambigüedades en la comunicación, garantizando que los términos utilizados en la documentación, los requerimientos y el código fuente reflejen fielmente la lógica del negocio de **ReWear**.

### 2.3.1. Stakeholders & Roles (Partes interesadas y roles)

* **Fashion Consumer (Consumidor de moda):** Usuario final de la plataforma que digitaliza su armario, explora su estilo personal, recibe combinaciones recomendadas por IA y prueba prendas mediante tecnologías visuales.
* **Partner Store (Tienda aliada):** Comercio o marca de moda registrada en la aplicación que publica su catálogo comercial para incrementar la visibilidad de sus productos y derivar tráfico a sus canales oficiales de venta.
* **AI Stylist / Recommendation Agent (Estilista IA / Agente de recomendación):** Motor inteligente encargado de analizar las prendas del armario personal para calcular compatibilidades y generar propuestas de outfits contextualizadas.

### 2.3.2. Digital Wardrobe & Garment Management (Armario digital y gestión de prendas)

* **Digital Wardrobe (Armario digital):** Representación e inventario virtual donde el usuario organiza, clasifica y gestiona las prendas que forman parte de su guardarropa real.
* **Garment (Prenda):** Artículo individual de vestir o accesorio registrado en la plataforma, asociado a atributos físicos y estéticos específicos.
* **Garment Attribute (Atributo de prenda):** Propiedad descriptiva de un artículo de vestir, tal como categoría, color primario, tela, temporada, marca y grado de formalidad.
* **Automatic Tagging (Etiquetado automático):** Proceso ejecutado mediante visión por computadora e inteligencia artificial para identificar y asignar atributos a una prenda a partir de una fotografía.
* **QR Code Tagging (Etiquetado por código QR):** Funcionalidad de escaneo que permite vincular de forma instantánea una prenda de tienda o de un tercero al armario digital del usuario.

### 2.3.3. AI Recommendation & Personalization (Recomendación con IA y personalización)

* **Outfit Recommendation (Sugerencia de outfit):** Combinación armónica de prendas y accesorios generada de forma automática para responder a un estilo y necesidad de vestuario.
* **Context Parameter (Parámetro contextual):** Variable ingresada por el usuario (como clima, tipo de evento o grado de formalidad) para condicionar la sugerencia generada por la IA.
* **Style Preference (Preferencia de estilo):** Configuración de etiquetas estéticas, paleta de colores y estilos de vestir que definen el gusto personal de cada usuario.
* **Style Feedback (Retroalimentación de estilo):** Acción de guardar, ajustar o descartar una propuesta de outfit, utilizada por el algoritmo para aprender y ajustar futuras recomendaciones.

### 2.3.4. Virtual Try-On & Visualizations (Probador virtual y visualización)

* **Digital Avatar (Avatar digital):** Representación tridimensional parametrizada según la contextura y medidas físicas del usuario para simular el uso de prendas.
* **Virtual Fitting Room (Probador virtual):** Entorno interactivo donde se superponen las prendas digitales sobre el avatar para evaluar el ajuste y la combinación de un look.
* **Augmented Reality Preview (Visualización en realidad aumentada):** Proyección tridimensional de prendas o accesorios sobre el entorno o el cuerpo del usuario capturado en tiempo real por la cámara.

### 2.3.5. Store Integration & Commercial Discovery (Integración con tiendas y descubrimiento comercial)

* **Commercial Catalog (Catálogo comercial):** Colección de productos registrados por tiendas aliadas dentro de la plataforma para ser descubiertos dentro de combinaciones de outfits.
* **Product Discovery (Descubrimiento de producto):** Experiencia mediante la cual un usuario encuentra prendas comerciales afines a sus gustos mientras organiza su armario o recibe recomendaciones.
* **External Channel Redirection (Redirección a canal externo):** Vinculación directa desde la ficha del producto hacia la tienda online, red social o canal oficial de venta de la marca aliada.
* **Store Profile (Perfil de tienda):** Espacio digital de la marca dentro de la plataforma donde muestra su identidad comercial, catálogo disponible e información de contacto.

### 2.3.6. Community & Social Fashion (Comunidad y moda compartida)

* **Shared Wardrobe (Armario compartido):** Configuración de privacidad que permite a un usuario mostrar parte de su catálogo digital a su red de amigos agregados.
* **Garment Loan Request (Solicitud de préstamo de prenda):** Interacción social en la cual un usuario solicita prestada una prenda del armario digital de un amigo para una ocasión especial.

---

# CAPÍTULO III: Requirements Specification

## 3.1. To-Be Scenario Mapping

En esta sección , el equipo muestra los artecfactos To-Be Scenario Maps 


### Olivia Rodriguez

![ To-Be_photo_Olvia](assets/As-is/To-be-olivia.PNG)

---

### Alejandro Lopez

![ To-Be_photo_Alejandro](assets/As-is/To-be-Alejandro.PNG)

---
## 3.2. User Stories

### Epics:

| Epic ID | Título | Descripción |
| :--- | :--- | :--- |
| **EP01** | **Gestión de Identidad, Perfil y Preferencias de Estilo** | Enfocada en el inicio de sesión, registro de usuarios y configuración inicial del perfil personal de moda. Incluye autenticación segura mediante correo o redes sociales, gestión de credenciales y el registro/actualización de preferencias de estilo, gustos y parámetros estéticos. Su objetivo es garantizar la seguridad del usuario mientras se construye la base de información necesaria para personalizar toda la experiencia. |
| **EP02** | **Gestión del Armario Virtual** | Esta épica se centra en permitir a los usuarios digitalizar, organizar y administrar sus prendas dentro de un inventario virtual. Contempla la carga de fotografías, el reconocimiento e identificación automática mediante IA (categoría, color, tipo), la edición de información y el añadido rápido mediante códigos QR. El objetivo es ofrecer un control centralizado e intuitivo del guardarropa personal. |
| **EP03** | **Agente de Recomendación (Estilista IA)** | Comprende el desarrollo del motor inteligente que analiza el catálogo del armario para generar sugerencias automáticas de outfits. Considera factores contextuales como el clima, la ocasión o gustos personales, calculando la compatibilidad entre prendas y guardando favoritos. El objetivo es ayudar al usuario a descubrir nuevas combinaciones y optimizar el uso de su ropa. |
| **EP04** | **Integración con Tiendas Aliadas y Catálogo Comercial** | Esta épica abarca las herramientas para que marcas asociadas registren sus perfiles, publiquen prendas y generen códigos QR comerciales. Permite a los usuarios escanear dichos códigos, vincular artículos de tienda con su propio armario y probar combinaciones previas a la compra. Su objetivo es conectar el comercio físico y digital con la experiencia del usuario. |
| **EP05** | **Avatar Digital y Probador Virtual** | Se centra en la creación y personalización de una representación digital (avatar) basada en las medidas del usuario. Incluye la superposición de prendas e inteligencias de ajuste sobre el avatar para simular combinaciones de vestir. El objetivo es brindar una experiencia interactiva de probador virtual para evaluar los looks antes de vestirlos o comprarlos. |
| **EP06** | **Experiencia en Realidad Aumentada (AR)** | Incluye la implementación de tecnologías de Realidad Aumentada para proyectar prendas y accesorios mediante la cámara en tiempo real. Considera el procesamiento del entorno, detección del usuario y superposición tridimensional de accesorios en el espacio real. El objetivo es proporcionar una visualización inmersiva e innovadora de los artículos. |
| **EP07** | **Comunidad y Moda Compartida** | Esta épica permitirá a los usuarios conectar con amigos, explorar armarios de su entorno social e interactuar a través de la moda. Contempla la gestión de amistad, solicitud de préstamos, permisos para probar ropa ajena y creación de espacios compartidos. Se busca construir un entorno colaborativo que fortalezca la interacción y la inspiración colectiva. |
| **EP08** | **Desarrollo Técnico del Backend e Infraestructura (RESTful API)** | Esta épica comprende la implementación de la infraestructura técnica que soportará la aplicación, incluyendo la base de datos, API RESTful, servicios en la nube y procesamiento para algoritmos de IA y AR. El foco está en garantizar rendimiento, seguridad y escalabilidad para manejar de manera eficiente las operaciones de usuarios y tiendas. |
| **EP09** | **Plataforma Web Informativa (Landing Page)** | Se centra en el desarrollo de una landing page que funcione como punto de entrada informativo y vitrina principal de Mirage, presentando la propuesta de valor, características clave y beneficios de la plataforma. El objetivo es atraer tanto a usuarios finales como a tiendas aliadas interesadas en unirse al ecosistema. |

### User Stories:

### Historias de Usuario - EP01

| User Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| :--- | :--- | :--- | :--- | :--- |
| **US01** | Registro de nueva cuenta de usuario | Como nuevo usuario, quiero registrarme en la aplicación mediante correo electrónico o cuenta de Google (Gmail) para crear mi cuenta y acceder a Mirage. | **ESCENARIO 01:** Registro exitoso con correo<br>**DADO** que el nuevo usuario accede a la pantalla de registro,<br>**CUANDO** completa sus datos válidos (nombre, correo y contraseña),<br>**Y** confirma la acción,<br>**ENTONCES** el sistema crea la cuenta, envía un correo de verificación y redirige al flujo de bienvenida.<br><br>**ESCENARIO 02:** Registro directo con Google (Gmail)<br>**DADO** que el usuario presiona el botón "Continuar con Google",<br>**CUANDO** autentica exitosamente su cuenta de Gmail,<br>**ENTONCES** el sistema crea su perfil automáticamente usando sus datos de Google.<br><br>**ESCENARIO 03:** Intentar registro con correo existente<br>**DADO** que el usuario ingresa un correo ya registrado,<br>**CUANDO** presiona el botón de registro,<br>**ENTONCES** el sistema muestra un mensaje de alerta indicando que la cuenta ya existe y sugiere iniciar sesión. | EP01 |
| **US02** | Inicio de sesión de usuario | Como usuario registrado, quiero iniciar sesión con mis credenciales o mi cuenta de Google para acceder a mi armario personal y funcionalidades de la app. | **ESCENARIO 01:** Autenticación correcta con credenciales<br>**DADO** que el usuario registrado ingresa sus credenciales válidas,<br>**CUANDO** presiona el botón "Iniciar Sesión",<br>**ENTONCES** el sistema autentica la cuenta y redirige a la pantalla principal del armario.<br><br>**ESCENARIO 02:** Autenticación directa con Google<br>**DADO** que el usuario registrado presiona "Iniciar sesión con Google",<br>**CUANDO** valida sus credenciales de Gmail,<br>**ENTONCES** el sistema concede acceso directo a su cuenta.<br><br>**ESCENARIO 03:** Ingreso de credenciales erróneas<br>**DADO** que el usuario ingresa una contraseña o correo incorrecto,<br>**CUANDO** intenta autenticarse,<br>**ENTONCES** el sistema muestra un mensaje de error indicando datos inválidos. | EP01 |
| **US03** | Recuperación de contraseña | Como usuario registrado, quiero restablecer mi contraseña en caso de olvido para poder acceder nuevamente a la plataforma. | **ESCENARIO 01:** Restablecimiento con correo válido<br>**DADO** que un usuario solicita restablecer su contraseña con un correo válido,<br>**CUANDO** ingresa su correo electrónico en la sección de recuperación,<br>**Y** el sistema valida que esté registrado,<br>**Y** genera un enlace o código de recuperación,<br>**ENTONCES** el sistema envía el método de restablecimiento,<br>**Y** el usuario puede actualizar su contraseña.<br><br>**ESCENARIO 02:** Restablecimiento con correo no registrado<br>**DADO** que un usuario solicita restablecer su contraseña con un correo no registrado,<br>**CUANDO** el sistema valida la información ingresada,<br>**Y** no encuentra coincidencias,<br>**Y** verifica la inexistencia de la cuenta,<br>**ENTONCES** el sistema rechaza la acción,<br>**Y** muestra un mensaje informando que no existe cuenta asociada. | EP01 |
| **US04** | Cierre de sesión | Como usuario registrado, quiero finalizar mi sesión para garantizar la seguridad de mi cuenta en cualquier dispositivo. | **ESCENARIO 01:** Cierre de sesión exitoso<br>**DADO** que un usuario tiene una sesión activa,<br>**CUANDO** solicita cerrar sesión,<br>**Y** el sistema recibe la solicitud,<br>**Y** verifica las credenciales activas,<br>**ENTONCES** invalida el token de autenticación,<br>**Y** finaliza la sesión correctamente.<br><br>**ESCENARIO 02:** Intento de cierre sin sesión activa<br>**DADO** que un usuario no tiene una sesión activa,<br>**CUANDO** solicita cerrar sesión,<br>**Y** el sistema valida el estado de autenticación,<br>**Y** detecta la ausencia de sesión,<br>**ENTONCES** el sistema rechaza la acción,<br>**Y** muestra un mensaje indicando que no hay sesión activa. | EP01 |
| **US05** | Configuración y edición del perfil personal | Como usuario, quiero personalizar mi información de perfil (foto de avatar, nombre e información básica) para mantener mi cuenta actualizada. | **ESCENARIO 01:** Actualización exitosa de perfil<br>**DADO** que el usuario se encuentra en la sección "Editar Perfil",<br>**CUANDO** modifica su foto de perfil o nombre y selecciona "Guardar cambios",<br>**ENTONCES** el sistema actualiza la información en la base de datos y la refleja inmediatamente en la interfaz. | EP01 |
| **US06** | Registro y actualización de preferencias de estilo | Como usuario, quiero definir mis gustos, paleta de colores y estilos de moda preferidos para recibir recomendaciones personalizadas. | **ESCENARIO 01:** Definición de preferencias en el onboarding<br>**DADO** que el usuario se encuentra en el flujo inicial de configuración de estilo,<br>**CUANDO** selecciona sus estilos de vestir (ej. casual, formal, streetwear) y paletas de colores,<br>**ENTONCES** el sistema guarda estas etiquetas en su perfil para alimentar al agente de recomendación.<br><br>**ESCENARIO 02:** Edición posterior de preferencias<br>**DADO** que el usuario accede a sus ajustes de estilo desde el perfil,<br>**CUANDO** añade o elimina etiquetas de preferencia y confirma,<br>**ENTONCES** el sistema recalibra sus preferencias para futuras sugerencias de outfits. | EP01 |
| **US07** | Carga y captura de imágenes de prendas | Como usuario, quiero capturar una foto con la cámara o subir una imagen de mi galería para iniciar la digitalización de mi prenda. | **ESCENARIO 01:** Carga exitosa de fotografía<br>**DADO** que el usuario accede a la opción de agregar prenda,<br>**CUANDO** captura una foto clara o selecciona una imagen válida de su galería,<br>**ENTONCES** el sistema procesa la imagen, elimina el fondo de la prenda y muestra una vista previa.<br><br>**ESCENARIO 02:** Imagen de baja calidad o no detectada<br>**DADO** que la fotografía cargada no tiene suficiente nitidez o iluminación,<br>**CUANDO** el sistema intenta procesarla,<br>**ENTONCES** muestra un mensaje recomendando capturar la prenda sobre un fondo neutro o con mejor luz. | EP02 |
| **US08** | Detección y etiquetado automático con IA | Como usuario, quiero que la IA identifique automáticamente el tipo, categoría, color y características de mi prenda para agilizar su registro. | **ESCENARIO 01:** Identificación exitosa por IA<br>**DADO** que la imagen de la prenda ha sido cargada,<br>**CUANDO** la IA analiza la prenda,<br>**ENTONCES** asigna automáticamente etiquetas sugeridas de categoría (ej. camiseta, pantalón), color primario y estilo.<br><br>**ESCENARIO 02:** Ajuste manual de etiquetas identificadas<br>**DADO** que el usuario revisa los atributos generados por la IA,<br>**CUANDO** detecta una imprecisión en el color o categoría,<br>**ENTONCES** puede modificar manualmente el campo antes de confirmar el registro. | EP02 |
| **US09** | Edición y registro de atributos de prenda | Como usuario, quiero guardar y editar los detalles específicos de mis prendas (marca, temporada, tela, notas) para mantener mi armario bien documentado. | **ESCENARIO 01:** Guardado completo de prenda<br>**DADO** que el usuario verifica la foto y atributos de la prenda,<br>**CUANDO** completa la información opcional (marca, temporada) y presiona "Guardar en Armario",<br>**ENTONCES** la prenda se registra con éxito en su inventario virtual.<br><br>**ESCENARIO 02:** Edición posterior de prenda existente<br>**DADO** que el usuario selecciona una prenda guardada previamente en su armario,<br>**CUANDO** edita cualquier campo informativo y selecciona "Guardar cambios",<br>**ENTONCES** el sistema actualiza la ficha de la prenda. | EP02 |
| **US10** | Añadido rápido de prendas mediante código QR | Como usuario, quiero escanear un código QR de una prenda para incorporarla directamente a mi armario virtual sin necesidad de cargar fotos manualmente. | **ESCENARIO 01:** Escaneo de QR válido<br>**DADO** que el usuario abre el escáner de la app,<br>**CUANDO** apunta a un código QR válido de una prenda de tienda o compartida,<br>**ENTONCES** el sistema obtiene la información completa de la prenda y la agrega inmediatamente a su catálogo personal.<br><br>**ESCENARIO 02:** QR no reconocido o caducado<br>**DADO** que el usuario escanea un código QR no perteneciente a la plataforma o corrupto,<br>**CUANDO** el sistema intenta validar el código,<br>**ENTONCES** muestra una alerta informando que el código no es válido. | EP02 |
| **US11** | Búsqueda y filtrado del armario personal | Como usuario, quiero filtrar y buscar mis prendas por categoría, color, uso o etiquetas personalizadas para encontrar la ropa que necesito rápidamente. | **ESCENARIO 01:** Aplicación de filtros combinados<br>**DADO** que el usuario se encuentra en la pantalla de su armario,<br>**CUANDO** selecciona filtros como "Categoría: Calzado" y "Color: Negro",<br>**ENTONCES** el sistema actualiza el catálogo mostrando solo las prendas que coinciden exactamente con la combinación.<br><br>**ESCENARIO 02:** Búsqueda sin resultados<br>**DADO** que el usuario ingresa un término de búsqueda que no coincide con ninguna prenda,<br>**CUANDO** se realiza la consulta,<br>**ENTONCES** el sistema muestra un mensaje indicando que no se encontraron coincidencias. | EP02 |
| **US12** | Creación y gestión de categorías personalizadas | Como usuario, quiero crear mis propias etiquetas o categorías (ej. "Trabajo", "Gym", "Fiesta") y asignarlas a mis prendas para organizar mi armario a mi gusto. | **ESCENARIO 01:** Creación de nueva categoría<br>**DADO** que el usuario ingresa a la sección de ajustes de categorías del armario,<br>**CUANDO** escribe el nombre de una nueva categoría y la guarda,<br>**ENTONCES** la categoría queda disponible para ser asignada a cualquier prenda de su armario.<br><br>**ESCENARIO 02:** Asignación de categoría a una prenda<br>**DADO** que el usuario edita una prenda de su armario,<br>**CUANDO** selecciona una o varias etiquetas personalizadas y guarda,<br>**ENTONCES** la prenda queda vinculada a dichas categorías personalizadas. | EP02 |
| **US13** | Eliminación de prendas del armario | Como usuario, quiero eliminar prendas de mi armario virtual cuando ya no las posea o no las utilice para mantener mi inventario actualizado. | **ESCENARIO 01:** Eliminación con confirmación<br>**DADO** que el usuario selecciona la opción de borrar una prenda,<br>**CUANDO** confirma el mensaje de alerta "¿Deseas eliminar esta prenda?",<br>**ENTONCES** el sistema remueve la prenda definitivamente de su armario virtual.<br><br>**ESCENARIO 02:** Cancelación de eliminación<br>**DADO** que el usuario presiona borrar prenda,<br>**CUANDO** en la ventana de confirmación elige "Cancelar",<br>**ENTONCES** la prenda se mantiene en el armario sin sufrir ningún cambio. | 
| **US14** | Generación de sugerencias integrales por contexto | Como usuario, quiero recibir recomendaciones automáticas de outfits (prendas y accesorios) basadas en el clima, la ocasión o el evento ingresado. | **ESCENARIO 01:** Recomendación exitosa de outfit y accesorios<br>**DADO** que el usuario ingresa parámetros de contexto (ej. "Boda de día", "Clima cálido"),<br>**CUANDO** solicita la recomendación a la IA,<br>**ENTONCES** el agente analiza el armario y sugiere una combinación armónica de ropa, calzado y accesorios.<br><br>**ESCENARIO 02:** Inventario insuficiente para el contexto<br>**DADO** que el usuario solicita una recomendación,<br>**CUANDO** el agente detecta que faltan elementos clave en el armario para esa ocasión,<br>**ENTONCES** la app muestra una sugerencia parcial y notifica qué tipo de prenda o accesorio completaría el look. | EP03 |
| **US15** | Recomendación a partir de un artículo clave | Como usuario, quiero seleccionar un elemento específico de mi armario (prenda o accesorio) para que la IA me sugiera cómo combinarlo. | **ESCENARIO 01:** Recomendación basada en un accesorio o prenda<br>**DADO** que el usuario selecciona un artículo (ej. un reloj, un bolso o una chaqueta),<br>**CUANDO** presiona "Sugerir combinación con este elemento",<br>**ENTONCES** la IA genera propuestas de estilo que resaltan y combinan con el artículo seleccionado.<br><br>**ESCENARIO 02:** Sin artículos compatibles disponibles<br>**DADO** que el usuario selecciona un artículo específico,<br>**CUANDO** la IA no encuentra coincidencias de estilo en el catálogo actual,<br>**ENTONCES** sugiere ajustar las preferencias de estilo o explorar tiendas aliadas. | EP03 |
| **US16** | Refinamiento interactivo de sugerencias mediante comentarios | Como usuario, quiero ingresar comentarios o instrucciones de ajuste (ej. "cambia las zapatillas", "hazlo más abrigo") a la sugerencia mostrada para que la IA la reformule. | **ESCENARIO 01:** Reformulación exitosa con comentario del usuario<br>**DADO** que el agente presenta una propuesta de outfit,<br>**CUANDO** el usuario escribe o selecciona una instrucción de reajuste (ej. "hazlo más casual" o "cambia el pantalón"),<br>**ENTONCES** el agente recalcula la combinación manteniendo la esencia del look pero reemplazando los elementos indicados.<br><br>**ESCENARIO 02:** Ajuste no realizable por falta de prendas<br>**DADO** que el usuario ingresa una instrucción de ajuste (ej. "agrega una casaca de cuero"),<br>**CUANDO** el agente verifica que no existe dicho artículo en el armario personal,<br>**ENTONCES** la app notifica la falta del ítem en su armario y le ofrece sugerir opciones de tiendas aliadas. | EP03 |
| **US17** | Valoración, guardado y aprendizaje del agente | Como usuario, quiero guardar mis combinaciones favoritas o descartar propuestas para que el agente aprenda progresivamente sobre mis gustos reales. | **ESCENARIO 01:** Guardado de propuesta en colección personal<br>**DADO** que el usuario recibe una sugerencia final satisfactoria,<br>**CUANDO** presiona "Guardar outfit",<br>**ENTONCES** la combinación se almacena en su colección y el agente registra el feedback positivo para futuros patrones.<br><br>**ESCENARIO 02:** Descarte de propuesta<br>**DADO** que al usuario no le agrada una recomendación,<br>**CUANDO** presiona "Descartar",<br>**ENTONCES** la IA desecha la combinación actual y actualiza sus ponderaciones internas para evitar combinaciones similares. | EP03 |
| **US18** | Registro de cuenta profesional de tienda | Como representante de una marca, quiero crear una cuenta profesional en la plataforma para habilitar mi presencia comercial y gestionar mi catálogo. | **ESCENARIO 01:** Registro exitoso de cuenta comercial<br>**DADO** que el representante de la tienda completa el formulario comercial con sus datos válidos,<br>**CUANDO** confirma el registro,<br>**ENTONCES** el sistema crea la cuenta profesional y habilita el panel de administración.<br><br>**ESCENARIO 02:** Registro con datos duplicados<br>**DADO** que se ingresa una identificación fiscal o correo previamente registrado,<br>**CUANDO** intenta presionar registrar,<br>**ENTONCES** el sistema muestra una alerta de cuenta existente. | EP04 |
| **US19** | Vinculación de enlaces y canales externos | Como representante de una tienda aliada, quiero vincular mi sitio web, redes sociales y canales de contacto a mi perfil comercial para redirigir a los usuarios a mis plataformas oficiales. | **ESCENARIO 01:** Agregar enlaces externos con éxito<br>**DADO** que la tienda ingresa las URLs de su e-commerce y redes sociales en la configuración del perfil,<br>**CUANDO** guarda los cambios,<br>**ENTONCES** el sistema muestra los accesos directos en el perfil público de la marca.<br><br>**ESCENARIO 02:** Formato de URL inválido<br>**DADO** que la tienda ingresa un enlace con estructura incorrecta,<br>**CUANDO** intenta guardar,<br>**ENTONCES** la plataforma señala el campo erróneo y solicita corregir el enlace. | EP04 |
| **US20** | Publicación de catálogo comercial y accesorios | Como tienda aliada, quiero subir prendas y accesorios a mi catálogo para que los usuarios puedan explorarlos y probárselos virtualmente. | **ESCENARIO 01:** Publicación de producto con enlace externo<br>**DADO** que la tienda ingresa las fotos, categoría y enlace a su web oficial,<br>**CUANDO** presiona "Publicar en catálogo",<br>**ENTONCES** el artículo queda visible en Mirage para pruebas virtuales.<br><br>**ESCENARIO 02:** Redirección a la web oficial<br>**DADO** que un usuario explora un artículo comercial,<br>**CUANDO** presiona el botón "Ver en tienda oficial",<br>**ENTONCES** la app lo redirige al enlace configurado por la marca. | EP04 |
| **US21** | Generación de códigos QR comerciales de exhibición y adquisición | Como tienda aliada, quiero generar códigos QR de exhibición para locales y códigos QR de adquisición para etiquetas físicas de mis productos. | **ESCENARIO 01:** Generación de QR de probador para exhibición<br>**DADO** que el producto está publicado en el catálogo,<br>**CUANDO** la tienda selecciona "Generar QR de Probador",<br>**ENTONCES** el sistema genera un QR listo para colocar en vitrinas o mostradores.<br><br>**ESCENARIO 02:** Generación de QR de adquisición para etiquetas<br>**DADO** que el producto se vende físicamente,<br>**CUANDO** la tienda selecciona "Generar QR de Adquisición",<br>**ENTONCES** el sistema crea un código único para la etiqueta que permitirá al cliente añadirlo a su armario tras la compra. | EP04 |
| **US22** | Escaneo de QR de exhibición y prueba previa a la compra | Como posible comprador, quiero escanear el QR de exhibición en una tienda física para probarme el artículo en mi avatar y combinarlo con la ropa de mi armario. | **ESCENARIO 01:** Escaneo de QR de exhibición en tienda física<br>**DADO** que el posible comprador escanea un QR de exhibición dentro del local,<br>**CUANDO** la app reconoce el artículo,<br>**ENTONCES** abre la interfaz del probador virtual y permite combinar la prenda comercial con su armario personal.<br><br>**ESCENARIO 02:** QR de exhibición no válido<br>**DADO** que el usuario escanea un código QR ajeno o dañado,<br>**CUANDO** el sistema intenta procesarlo,<br>**ENTONCES** muestra un mensaje indicando que el código no corresponde a un producto de la plataforma. | EP04 |
| **US23** | Añadir prenda comercial al armario desde el probador virtual | Como posible comprador, quiero agregar a mi armario virtual una prenda comercial que estoy visualizando en el probador virtual, para conservarla y combinarla posteriormente con mis prendas. | ESCENARIO 01: Añadir prenda desde el probador virtual<br>DADO que el usuario ha escaneado un QR de exhibición y está visualizando la prenda en el probador virtual,<br>CUANDO selecciona la opción "Agregar a mi armario",<br>ENTONCES el sistema incorpora la prenda a su armario virtual con su imagen y atributos registrados en la plataforma.<br><br>ESCENARIO 02: Prenda ya registrada en el armario<br>DADO que el usuario intenta agregar una prenda que ya se encuentra en su armario virtual,<br>CUANDO selecciona la opción "Agregar a mi armario",<br>ENTONCES el sistema informa que la prenda ya está registrada y evita duplicarla. | EP04 |
| **US24** | Generación de rostro mediante selfie | Como usuario, quiero tomarme una foto del rostro para que la app genere un avatar con mis facciones reales. | **ESCENARIO 01:** Mapeo exitoso de rostro<br>**DADO** que el usuario captura una selfie clara desde la app,<br>**CUANDO** la plataforma la procesa mediante reconocimiento facial,<br>**ENTONCES** genera el rostro del avatar recreando sus facciones y tono de piel.<br><br>**ESCENARIO 02:** Rostro no detectado<br>**DADO** que la foto capturada está borrosa u oscura,<br>**CUANDO** el sistema intenta procesarla,<br>**ENTONCES** muestra una alerta pidiendo repetir la captura con mejores condiciones de luz. | EP05 |
| **US25** | Estimación automática de dimensiones corporales por foto de cuerpo entero | Como usuario, quiero subir o capturar una fotografía de cuerpo completo para que la IA extraiga automáticamente mis proporciones corporales sin tener que medirme manualmente. | **ESCENARIO 01:** Escaneo corporal automático exitoso<br>**DADO** que el usuario se ubica frente a la cámara y captura una foto de cuerpo completo siguiendo las guías visuales de la pantalla,<br>**CUANDO** la IA analiza la silueta y la profundidad,<br>**ENTONCES** calcula automáticamente la estatura estimada, contorno de pecho, cintura y cadera, modelando la silueta del avatar al instante.<br><br>**ESCENARIO 02:** Detección incompleta de la silueta<br>**DADO** que el usuario lleva ropa demasiado holgada o la foto no encuadra el cuerpo entero,<br>**CUANDO** la IA intenta estimar las proporciones,<br>**ENTONCES** notifica que no pudo detectar el contorno con precisión y ofrece reintentar o ajustar manualmente. | EP05 |
| **US26** | **Ajuste y refinamiento manual de proporciones corporales** | Como usuario, quiero ajustar manualmente mis proporciones corporales representadas en mi avatar visual, para corregir o personalizar la estimación obtenida a partir de mis fotografías. | **ESCENARIO 01:** Ajuste manual de proporciones<br>**DADO** que el sistema ha generado una representación visual del usuario a partir de sus fotografías,<br>**CUANDO** el usuario modifica los valores de sus proporciones corporales mediante campos numéricos o deslizadores,<br>**ENTONCES** el sistema actualiza la representación visual del usuario de acuerdo con los valores seleccionados.<br><br>**ESCENARIO 02:** Validación de medidas<br>**DADO** que el usuario ingresa un valor fuera del rango permitido,<br>**CUANDO** intenta aplicar los cambios,<br>**ENTONCES** el sistema muestra un mensaje indicando que el valor ingresado no es válido. | EP05 |
| **US27** | Prueba virtual de prendas sobre el avatar personalizado | Como usuario, quiero probarme prendas de mi armario o de tiendas aliadas sobre mi avatar para visualizar cómo me lucen puestas. | **ESCENARIO 01:** Superposición exitosa de prendas<br>**DADO** que el usuario selecciona una prenda superior e inferior en el probador,<br>**CUANDO** confirma la selección,<br>**ENTONCES** el sistema renderiza la ropa adaptándola automáticamente a la silueta y proporciones de su avatar.<br><br>**ESCENARIO 02:** Reemplazo inmediato de prendas<br>**DADO** que el avatar ya viste un outfit,<br>**CUANDO** el usuario selecciona una nueva prenda del catálogo,<br>**ENTONCES** la app sustituye la pieza anterior de forma fluida. | EP05 |
| **US28** | Prueba virtual de accesorios sobre el avatar | Como usuario, quiero colocar accesorios (gafas, bolsos, sombreros, joyas) en mi avatar para evaluar el impacto visual del look completo. | **ESCENARIO 01:** Posicionamiento automático de accesorios<br>**DADO** que el avatar viste ropa en la escena,<br>**CUANDO** el usuario selecciona un accesorio,<br>**ENTONCES** el probador posiciona el objeto en el punto anatómico correspondiente del avatar.<br><br>**ESCENARIO 02:** Desactivación de accesorios<br>**DADO** que el avatar lleva puestos varios accesorios,<br>**CUANDO** el usuario desmarca uno de ellos,<br>**ENTONCES** el probador retira dicho objeto sin alterar el resto de las prendas. | EP05 |
| **US29** | **Estimación del calce de la prenda** | Como usuario, quiero consultar una estimación del calce de una prenda comercial según mis proporciones corporales, para conocer si una talla podría quedarme ajustada, justa u holgada. | **ESCENARIO 01:** Visualización del calce por talla<br>**DADO** que el usuario selecciona una prenda comercial con una talla determinada,<br>**CUANDO** consulta la opción "Calce de la prenda",<br>**ENTONCES** el sistema compara las medidas registradas de la prenda con las proporciones corporales del usuario y muestra una representación visual diferenciada según el nivel de ajuste estimado.<br><br>**ESCENARIO 02:** Sugerencia de cambio de talla<br>**DADO** que las medidas de la prenda seleccionada presentan una diferencia desfavorable respecto a las proporciones del usuario,<br>**CUANDO** el sistema realiza la comparación,<br>**ENTONCES** muestra un aviso sugiriendo considerar una talla diferente. | EP05 |
| **US30** | Comparación de looks | Como usuario, quiero comparar dos combinaciones diferentes probadas sobre mi avatar para decidir cuál se me ve mejor. | **ESCENARIO 01:** Comparación de combinaciones<br>**DADO** que el usuario arma dos combinaciones distintas,<br>**CUANDO** presiona "Comparar Looks",<br>**ENTONCES** la pantalla muestra a su avatar personalizado portando ambos conjuntos para su evaluación visual.<br><br>**ESCENARIO 02:** Selección de combinación ganadora<br>**DADO** que el usuario observa la comparación,<br>**CUANDO** presiona "Elegir este look",<br>**ENTONCES** el sistema selecciona dicha combinación en la pantalla principal del probador. | EP05 |
| **US31** | Guardado de outfits generados | Como usuario, quiero guardar en mi colección los outfits generados (manualmente en el probador o sugeridos por la IA) para consultarlos o usarlos posteriormente. | **ESCENARIO 01:** Guardado exitoso de outfit<br>**DADO** que el usuario visualiza un outfit armado en su avatar,<br>**CUANDO** presiona "Guardar Outfit",<br>**ENTONCES** el sistema almacena la combinación completa en su sección "Mis Outfits" y la vincula con su historial.<br><br>**ESCENARIO 02:** Personalización de datos del outfit<br>**DADO** que el usuario presiona guardar,<br>**CUANDO** ingresa un nombre y selecciona una ocasión,<br>**ENTONCES** la app registra la combinación clasificada bajo esos parámetros. | EP05 |
| **US32** | Probador virtual de prendas en tiempo real con cámara | Como usuario, quiero usar la cámara de mi dispositivo en tiempo real para probarme prendas de vestir sobre mi cuerpo mediante Realidad Aumentada. | **ESCENARIO 01:** Superposición de ropa en vivo<br>**DADO** que el usuario activa la cámara en modo AR probador,<br>**CUANDO** selecciona una prenda de vestir,<br>**ENTONCES** el sistema superpone dinámicamente la prenda sobre la silueta del usuario en tiempo real adaptando la escala a sus movimientos.<br><br>**ESCENARIO 02:** Pérdida de seguimiento corporal<br>**DADO** que la cámara pierde la detección de la silueta por mala iluminación o movimiento brusco,<br>**CUANDO** el sistema no reconoce los puntos del cuerpo,<br>**ENTONCES** muestra una guía para volver a encuadrar el cuerpo. | EP06 |
| **US33** | Prueba de accesorios en tiempo real | Como usuario, quiero probarme accesorios (gafas, sombreros, joyas, bolsos) mediante filtros AR sobre mi rostro o cuerpo en tiempo real para evaluar cómo lucen. | **ESCENARIO 01:** Detección y superposición de accesorios<br>**DADO** que el usuario selecciona un accesorio y activa la cámara,<br>**CUANDO** la cámara reconoce el rostro o zona del cuerpo,<br>**ENTONCES** proyecta el accesorio en 3D ajustando la escala, perspectiva y sombreado a los movimientos en vivo.<br><br>**ESCENARIO 02:** Pérdida de seguimiento facial/corporal<br>**DADO** que la cámara pierde el encuadre del rostro o cuerpo,<br>**CUANDO** el seguimiento se interrumpe,<br>**ENTONCES** la app muestra una guía visual para volver a centrar la toma. | EP06 |
| **US34** | Captura de fotos en Realidad Aumentada | Como usuario, quiero tomar fotografías de mi prueba en AR con prendas o accesorios para guardarlas en mi galería o compartirlas. | **ESCENARIO 01:** Captura exitosa de foto en modo AR<br>**DADO** que el usuario tiene aplicadas prendas o accesorios en tiempo real,<br>**CUANDO** presiona el botón de obturador,<br>**ENTONCES** la app genera una fotografía renderizada en alta resolución y la guarda en su galería.<br><br>**ESCENARIO 02:** Previsualización y exportado<br>**DADO** que la foto ha sido capturada en modo AR,<br>**CUANDO** el usuario ingresa a la vista previa,<br>**ENTONCES** el sistema permite descartarla, guardarla o compartirla directamente a otras plataformas. | EP06 |
| **US35** | Perfil público de armario y outfits | Como usuario, quiero mostrar mis outfits creados y prendas públicas en mi perfil para que mis amigos puedan explorar mi estilo. | **ESCENARIO 01:** Visualización de armario de perfil<br>**DADO** que un usuario ingresa al perfil de un amigo,<br>**CUANDO** navega por sus pestañas de prendas u outfits,<br>**ENTONCES** el sistema muestra la galería de ítems y combinaciones configuradas como públicas.<br><br>**ESCENARIO 02:** Ocultar ítems privados<br>**DADO** que el usuario marca una prenda o combinación como "Privada",<br>**CUANDO** otros usuarios visitan su perfil,<br>**ENTONCES** la app omite la visualización de esos elementos. | EP07 |
| **US36** | Seguimiento e interacción con amigos | Como usuario, quiero buscar y seguir a otros usuarios para estar conectado con sus perfiles de estilo. | **ESCENARIO 01:** Seguir a un usuario<br>**DADO** que el usuario visita el perfil de otra persona,<br>**CUANDO** presiona el botón "Seguir",<br>**ENTONCES** el sistema actualiza el estado a "Siguiendo" y añade el perfil a su lista de amigos/seguidos.<br><br>**ESCENARIO 02:** Dejar de seguir<br>**DADO** que el usuario ya sigue a una persona,<br>**CUANDO** presiona nuevamente para dejar de seguir,<br>**ENTONCES** el sistema remueve la vinculación de la lista. | EP07 |
| **US37** | Prueba virtual de prendas del armario de un amigo | Como usuario, quiero seleccionar prendas del armario de un amigo para probármelas en mi propio avatar dentro del probador virtual. | **ESCENARIO 01:** Cargar prenda de amigo al probador<br>**DADO** que el usuario revisa el armario público de un amigo,<br>**CUANDO** selecciona una prenda y presiona "Probar en mi avatar",<br>**ENTONCES** el sistema abre el probador virtual y renderiza la prenda del amigo sobre el avatar del usuario.<br><br>**ESCENARIO 02:** Intentar probar prenda privada o eliminada<br>**DADO** que el amigo cambió la visibilidad de la prenda a privada,<br>**CUANDO** el usuario intenta cargarla en su avatar,<br>**ENTONCES** la app notifica que la prenda ya no está disponible para prueba. | EP07 |
| **US38** | Reacciones a outfits de perfil | Como usuario, quiero dar "me gusta" a las combinaciones guardadas en el perfil de mis amigos para interactuar con sus outfits. | **ESCENARIO 01:** Dar "me gusta" a un outfit<br>**DADO** que el usuario explora los outfits en el perfil de un amigo,<br>**CUANDO** presiona el icono de reacción en una combinación,<br>**ENTONCES** la app incrementa el contador de likes y envía una notificación al autor.<br><br>**ESCENARIO 02:** Retirar la reacción<br>**DADO** que el usuario ya reaccionó previamente a un outfit,<br>**CUANDO** presiona nuevamente el icono,<br>**ENTONCES** el sistema retira el like y decrementa el contador. | EP07 |
| **US39** | Información general y propuesta de valor | Como visitante, quiero entender rápidamente los beneficios de Mirage y tener un botón accesible para descargar la aplicación. | **ESCENARIO 01:** Presentación y llamado a la acción<br>**DADO** que el visitante accede a la landing page,<br>**CUANDO** visualiza la pantalla principal (Hero),<br>**ENTONCES** el sistema muestra las funciones clave (probador virtual, armario digital) y resalta el botón de descarga directa hacia las tiendas de aplicaciones. | EP09 |
| **US40** | Navegación responsive y encabezado | Como usuario móvil o de escritorio, quiero un menú de navegación claro que se adapte a cualquier tamaño de pantalla. | **ESCENARIO 01:** Adaptabilidad y menú navegable<br>**DADO** que el usuario accede desde cualquier dispositivo,<br>**CUANDO** interactúa con el encabezado o activa el menú lateral en pantallas reducidas,<br>**ENTONCES** la web se desplaza fluidamente hacia la sección seleccionada manteniendo la navegación visible. | EP09 |
| **US41** | Sección de equipo, misión y visión | Como visitante interesado, quiero conocer al equipo creador y los objetivos de Mirage a largo plazo. | **ESCENARIO 01:** Despliegue de "About the Team"<br>**DADO** que el visitante navega a la sección del equipo,<br>**CUANDO** se carga la información,<br>**ENTONCES** la web presenta los nombres, fotos y roles de los integrantes, junto con la declaración de Misión y Visión de la empresa. | EP09 |
| **US42** | Registro de alianzas para tiendas (B2B) | Como representante de una tienda física, quiero un formulario de contacto para solicitar unirme a la red de comercios aliados. | **ESCENARIO 01:** Envío de solicitud B2B<br>**DADO** que el representante de tienda ingresa sus datos comerciales en el formulario,<br>**CUANDO** presiona "Solicitar información",<br>**ENTONCES** el sistema almacena la solicitud y muestra una confirmación de recepción. | EP09 |
| **US43** | Pie de página con enlaces institucionales | Como visitante, quiero un pie de página organizado para acceder fácilmente a redes sociales, políticas de privacidad y contacto. | **ESCENARIO 01:** Interacción con el pie de página<br>**DADO** que el visitante llega al final de la landing page,<br>**CUANDO** selecciona uno de los enlaces del pie de página,<br>**ENTONCES** el sistema lo redirige a la red social, sección o documento legal correspondiente. | EP09 |

| Technical Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|---|---|---|---|---|
| TS01 | Procesamiento centralizado de modelos de IA | Los modelos de IA usados para reconocimiento de prendas, estimación corporal y recomendaciones deben ejecutarse en un módulo separado, independiente del backend principal. | El sistema resuelve las solicitudes de IA sin que una falla en ese módulo afecte el resto de funcionalidades. | EP03, EP08 |
| TS02 | Renderizado 3D y AR compatible con hardware estándar | El avatar y el probador con Realidad Aumentada deben funcionar en dispositivos móviles de gama media, sin exigir hardware especializado. | El probador virtual y el módulo AR se ejecutan de forma fluida en los dispositivos objetivo definidos por el equipo. | EP05, EP06 |
| TS03 | Procesamiento asíncrono de imágenes | La carga y el análisis de fotografías de prendas o de cuerpo completo deben resolverse en segundo plano, sin bloquear la interacción del usuario con la aplicación. | El usuario puede seguir navegando en la aplicación mientras la imagen se procesa. | EP08 |
| TS04 | Escalamiento independiente por tipo de usuario | La infraestructura debe permitir escalar por separado la carga generada por usuarios finales y por tiendas aliadas. | El aumento de tráfico de un segmento no degrada el rendimiento del otro. | EP08 |
| TS05 | Integración con servicios externos | El sistema debe conectarse con proveedores externos de autenticación, generación de QR y servicios de IA en la nube. | El login con proveedores externos y la generación de QR funcionan de forma independiente al núcleo del sistema. | EP08 |
| TS06 | Despliegue en infraestructura cloud | La solución debe alojarse en un proveedor cloud que soporte el procesamiento de IA y de renderizado sin depender de servidores propios. | La plataforma permanece disponible en línea y soporta acceso remoto continuo. | EP08 |

## 3.3. Impact Mapping
El Impact Mapping nos ayuda a ordenar la idea del proyecto y entender cómo cada parte de la solución aporta valor. A partir del objetivo principal, se identifican los usuarios involucrados, los resultados que se busca generar en cada uno y las funcionalidades necesarias para alcanzarlos. En este caso, el mapa permite relacionar las necesidades de los usuarios finales y de las tiendas aliadas con los entregables e historias de usuario del proyecto.

 ![ImpactMap_ photo](assets/img/ImpactMapMirage.png)
## 3.4. Product Backlog

El Product Backlog organiza todas las funcionalidades e historias técnicas identificadas.

| Orden | User Story ID | Título | Descripción | Story Points |
| :---: | :---: | :--- | :--- | :---: |
| **1** | US01 | Registro de nueva cuenta de usuario | Como nuevo usuario, quiero registrarme en la aplicación mediante correo electrónico o cuenta de Google (Gmail) para crear mi cuenta y acceder a Mirage.| 3 |
| **2** | US02 | Inicio de sesión de usuario | Como usuario registrado, quiero iniciar sesión con mis credenciales o mi cuenta de Google para acceder a mi armario personal y funcionalidades de la app. | 2 |
| **3** | US03 | Recuperación de contraseña | Como usuario registrado, quiero restablecer mi contraseña en caso de olvido para poder acceder nuevamente a la plataforma. | 3 |
| **4** | US04 | Cierre de sesión | Como usuario registrado, quiero finalizar mi sesión para garantizar la seguridad de mi cuenta en cualquier dispositivo. | 1 |
| **5** | US05 | Configuración y edición del perfil personal | Como usuario, quiero personalizar mi información de perfil (foto de avatar, nombre e información básica) para mantener mi cuenta actualizada. | 2 |
| **6** | US06 | Registro y actualización de preferencias de estilo | Como usuario, quiero definir mis gustos, paleta de colores y estilos de moda preferidos para recibir recomendaciones personalizadas. | 3 |
| **7** | US07 | Carga y captura de imágenes de prendas | Como usuario, quiero capturar una foto con la cámara o subir una imagen de mi galería para iniciar la digitalización de mi prenda. | 5 |
| **8** | US08 | Detección y etiquetado automático con IA | Como usuario, quiero que la IA identifique automáticamente el tipo, categoría, color y características de mi prenda para agilizar su registro. | 8 |
| **9** | US09 | Edición y registro de atributos de prenda | Como usuario, quiero guardar y editar los detalles específicos de mis prendas (marca, temporada, tela, notas) para mantener mi armario bien documentado. | 3 |
| **10** | US10 | Añadido rápido de prendas mediante código QR | Como usuario, quiero escanear un código QR de una prenda para incorporarla directamente a mi armario virtual sin necesidad de cargar fotos manualmente. | 3 |
| **11** | US11 | Búsqueda y filtrado del armario personal | Como usuario, quiero filtrar y buscar mis prendas por categoría, color, uso o etiquetas personalizadas para encontrar la ropa que necesito rápidamente. | 3 |
| **12** | US12 | Creación y gestión de categorías personalizadas | Como usuario, quiero crear mis propias etiquetas o categorías (ej. "Trabajo", "Gym", "Fiesta") y asignarlas a mis prendas para organizar mi armario a mi gusto.| 2 |
| **13** | US13 | Eliminación de prendas del armario | Como usuario, quiero eliminar prendas de mi armario virtual cuando ya no las posea o no las utilice para mantener mi inventario actualizado. | 1 |
| **14** | US14 | Generación de sugerencias integrales por contexto | Como usuario, quiero recibir recomendaciones automáticas de outfits (prendas y accesorios) basadas en el clima, la ocasión o el evento ingresado. | 8 |
| **15** | US15 | Recomendación a partir de un artículo clave | Como usuario, quiero seleccionar un elemento específico de mi armario (prenda o accesorio) para que la IA me sugiera cómo combinarlo. | 5 |
| **16** | US16 | Refinamiento interactivo de sugerencias mediante comentarios | Como usuario, quiero ingresar comentarios o instrucciones de ajuste (ej. "cambia las zapatillas", "hazlo más abrigo") a la sugerencia mostrada para que la IA la reformule. | 8 |
| **17** | US17 | Valoración, guardado y aprendizaje del agente | Como usuario, quiero guardar mis combinaciones favoritas o descartar propuestas para que el agente aprenda progresivamente sobre mis gustos reales. | 5 |
| **18** | US18 | Registro de cuenta profesional de tienda | Como representante de una marca, quiero crear una cuenta profesional en la plataforma para habilitar mi presencia comercial y gestionar mi catálogo. | 3 |
| **19** | US19 | Vinculación de enlaces y canales externos | Como representante de una tienda aliada, quiero vincular mi sitio web, redes sociales y canales de contacto a mi perfil comercial para redirigir a los usuarios a mis plataformas oficiales.| 2 |
| **20** | US20 | Publicación de catálogo comercial y accesorios | Como tienda aliada, quiero subir prendas y accesorios a mi catálogo para que los usuarios puedan explorarlos y probárselos virtualmente. | 5 |
| **21** | US21 | Generación de códigos QR comerciales de exhibición y adquisición | Como tienda aliada, quiero generar códigos QR de exhibición para locales y códigos QR de adquisición para etiquetas físicas de mis productos. | 5 |
| **22** | US22 | Escaneo de QR de exhibición y prueba previa a la compra | Como posible comprador, quiero escanear el QR de exhibición en una tienda física para probarme el artículo en mi avatar y combinarlo con la ropa de mi armario.| 5 |
| **23** | US23 | Añadir prenda comercial al armario desde el probador virtual | Como posible comprador, quiero agregar a mi armario virtual una prenda comercial que estoy visualizando en el probador virtual, para conservarla y combinarla posteriormente con mis prendas. | 3 |
| **24** | US24 | Generación de rostro mediante selfie | Como usuario, quiero tomarme una foto del rostro para que la app genere un avatar con mis facciones reales. | 8 |
| **25** | US25 | Estimación automática de dimensiones corporales por foto de cuerpo entero | Como usuario, quiero subir o capturar una fotografía de cuerpo completo para que la IA extraiga automáticamente mis proporciones corporales sin tener que medirme manualmente.| 13 |
| **26** | US26 | Ajuste y refinamiento manual de proporciones corporales | Como usuario, quiero ajustar manualmente mis proporciones corporales representadas en mi avatar visual, para corregir o personalizar la estimación obtenida a partir de mis fotografías. | 3 |
| **27** | US27 | Prueba virtual de prendas sobre el avatar personalizado | Como usuario, quiero probarme prendas de mi armario o de tiendas aliadas sobre mi avatar para visualizar cómo me lucen puestas. | 13 |
| **28** | US28 | Prueba virtual de accesorios sobre el avatar | Como usuario, quiero colocar accesorios (gafas, bolsos, sombreros, joyas) en mi avatar para evaluar el impacto visual del look completo. | 8 |
| **29** | US29 | Estimación del calce de la prenda | Como usuario, quiero consultar una estimación del calce de una prenda comercial según mis proporciones corporales, para conocer si una talla podría quedarme ajustada, justa u holgada. | 8 |
| **30** | US30 | Comparación de looks | Como usuario, quiero comparar dos combinaciones diferentes probadas sobre mi avatar para decidir cuál se me ve mejor. | 5 |
| **31** | US31 | Guardado de outfits generados | Como usuario, quiero guardar en mi colección los outfits generados (manualmente en el probador o sugeridos por la IA) para consultarlos o usarlos posteriormente.| 3 |
| **32** | US32 | Probador virtual de prendas en tiempo real con cámara | Como usuario, quiero usar la cámara de mi dispositivo en tiempo real para probarme prendas de vestir sobre mi cuerpo mediante Realidad Aumentada. | 21 |
| **33** | US33 | Prueba de accesorios en tiempo real | Como usuario, quiero probarme accesorios (gafas, sombreros, joyas, bolsos) mediante filtros AR sobre mi rostro o cuerpo en tiempo real para evaluar cómo lucen. | 13 |
| **34** | US34 | Captura de fotos en Realidad Aumentada | Como usuario, quiero tomar fotografías de mi prueba en AR con prendas o accesorios para guardarlas en mi galería o compartirlas. | 5 |
| **35** | US35 | Perfil público de armario y outfits | Como usuario, quiero mostrar mis outfits creados y prendas públicas en mi perfil para que mis amigos puedan explorar mi estilo. | 5 |
| **36** | US36 | Seguimiento e interacción con amigos | Como usuario, quiero buscar y seguir a otros usuarios para estar conectado con sus perfiles de estilo. | 3 |
| **37** | US37 | Prueba virtual de prendas del armario de un amigo | Como usuario, quiero seleccionar prendas del armario de un amigo para probármelas en mi propio avatar dentro del probador virtual. | 8 |
| **38** | US38 | Reacciones a outfits de perfil | Como usuario, quiero dar "me gusta" a las combinaciones guardadas en el perfil de mis amigos para interactuar con sus outfits.| 2 |
| **39** | US39 | Información general y propuesta de valor | Como visitante, quiero entender rápidamente los beneficios de Mirage y tener un botón accesible para descargar la aplicación. | 2 |
| **40** | US40 | Navegación responsive y encabezado | Como usuario móvil o de escritorio, quiero un menú de navegación claro que se adapte a cualquier tamaño de pantalla. | 3 |
| **41** | US41 | Sección de equipo, misión y visión | Como visitante interesado, quiero conocer al equipo creador y los objetivos de Mirage a largo plazo. | 1 |
| **42** | US42 | Registro de alianzas para tiendas (B2B) | Como representante de una tienda física, quiero un formulario de contacto para solicitar unirme a la red de comercios aliados.| 3 |
| **43** | US43 | Pie de página con enlaces institucionales | Como visitante, quiero un pie de página organizado para acceder fácilmente a redes sociales, políticas de privacidad y contacto. | 1 |
| **44** | TS01 | Procesamiento centralizado de modelos de IA | Los modelos de IA usados para reconocimiento de prendas, estimación corporal y recomendaciones deben ejecutarse en un módulo separado, independiente del backend principal. | 13 |
| **45** | TS02 | Renderizado 3D y AR compatible con hardware estándar | El avatar y el probador con Realidad Aumentada deben funcionar en dispositivos móviles de gama media, sin exigir hardware especializado.| 13 |
| **46** | TS03 | Procesamiento asíncrono de imágenes | La carga y el análisis de fotografías de prendas o de cuerpo completo deben resolverse en segundo plano, sin bloquear la interacción del usuario con la aplicación. | 8 |
| **47** | TS04 | Escalamiento independiente por tipo de usuario | La infraestructura debe permitir escalar por separado la carga generada por usuarios finales y por tiendas aliadas. | 8 |
| **48** | TS05 | Integración con servicios externos | El sistema debe conectarse con proveedores externos de autenticación, generación de QR y servicios de IA en la nube. | 5 |
| **49** | TS06 | Despliegue en infraestructura cloud | La solución debe alojarse en un proveedor cloud que soporte el procesamiento de IA y de renderizado sin depender de servidores propios. | 5 |

# CAPÍTULO IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design

En esta sección se presenta el proceso de diseño arquitectónico basado en Attribute-Driven Design (ADD), aplicado a la solución propuesta por el equipo con su producto Mirage. Se describen los principales insumos del diseño, los drivers arquitectónicos, las decisiones tomadas y la forma en que se abordan los atributos de calidad, con el objetivo de definir una arquitectura alineada a las necesidades del negocio y de los usuarios.

### 4.1.1. Design Purpose

El propósito del proceso de diseño arquitectónico es definir una solución de software escalable, segura y alineada a los objetivos estratégicos de Mirage, mediante la aplicación del enfoque Attribute-Driven Design (ADD). Este proceso responde a la problemática identificada en el proyecto, relacionada con la dificultad de las personas para conocer y aprovechar las prendas que ya poseen, así como para encontrar nuevas combinaciones dentro de su propio armario. La dispersión de la información entre fotos, redes sociales y otras plataformas genera una experiencia fragmentada que no considera realmente el guardarropa del usuario.

A través del diseño estratégico, se busca construir una arquitectura para Mirage que:

Soporte las funcionalidades principales identificadas en las historias de usuario, como el registro de prendas mediante IA, la generación de recomendaciones de outfits, el avatar digital y las experiencias de Realidad Aumentada.

Garantice atributos de calidad esenciales como rendimiento, escalabilidad y seguridad, considerando el uso simultáneo de módulos de procesamiento de imágenes, IA y renderizado 3D.

Permita una integración confiable con actores externos como tiendas aliadas y proveedores de autenticación, sin comprometer la disponibilidad del resto de la plataforma.

Asimismo, este proceso de diseño está orientado a satisfacer las necesidades de los dos segmentos objetivo del producto: los usuarios finales interesados en moda y las tiendas aliadas que buscan mayor visibilidad para sus catálogos, brindándoles una plataforma que centralice el armario digital, mejore la exploración de estilo y conecte de forma práctica el comercio físico con la experiencia del usuario.

### 4.1.2. Attribute-Driven Design Inputs

En esta sección se presentan los principales insumos utilizados para el proceso de diseño arquitectónico basado en Attribute-Driven Design (ADD) para el producto Mirage. Estos insumos incluyen la funcionalidad principal del sistema, los escenarios de atributos de calidad y las restricciones del entorno, los cuales permiten identificar los drivers arquitectónicos que guían las decisiones de diseño.

#### 4.1.2.1. Primary Functionality (Primary User Stories)

En esta sección se presentan las User Stories más relevantes que tienen un impacto directo en la arquitectura del sistema. Fueron seleccionadas porque definen funcionalidades críticas como el reconocimiento de prendas con IA, la generación de recomendaciones, la creación del avatar y la Realidad Aumentada, las cuales requieren decisiones importantes de diseño, rendimiento y estructura del sistema.

A continuación, se detallan las historias de usuario seleccionadas:

| EPIC/USER STORY ID | TÍTULO | DESCRIPCIÓN | CRITERIO DE ACEPTACIÓN | RELACIONADO CON (EPIC ID) |
|---|---|---|---|---|
| US07 | Carga y captura de imágenes de prendas | Como usuario, quiero capturar o subir una foto de una prenda, para iniciar su digitalización dentro del armario virtual. | El sistema procesa la imagen, elimina el fondo y muestra una vista previa lista para confirmar. | EP02 |
| US08 | Detección y etiquetado automático con IA | Como usuario, quiero que la IA identifique automáticamente el tipo, color y categoría de mi prenda, para agilizar su registro. | El sistema asigna etiquetas sugeridas que el usuario puede corregir manualmente. | EP02 |
| US14 | Generación de sugerencias integrales por contexto | Como usuario, quiero recibir recomendaciones de outfits según el clima o la ocasión, para descubrir nuevas combinaciones. | El agente analiza el armario y sugiere una combinación coherente con el contexto ingresado. | EP03 |
| US25 | Estimación automática de dimensiones corporales por foto | Como usuario, quiero que la IA calcule mis proporciones a partir de una foto de cuerpo completo, para generar mi avatar sin medirme manualmente. | El sistema modela la silueta del avatar a partir del análisis de la imagen. | EP05 |
| US32 | Probador virtual de prendas en tiempo real con cámara | Como usuario, quiero probarme prendas usando la cámara de mi dispositivo mediante Realidad Aumentada, para ver cómo me quedan sin vestirlas físicamente. | El sistema superpone la prenda sobre la imagen en vivo, ajustándose a los movimientos del usuario. | EP06 |

#### 4.1.2.2. Quality Attribute Scenarios

En esta sección se presentan los escenarios iniciales de atributos de calidad que tienen mayor impacto en la arquitectura de Mirage.

Estos escenarios se enfocan en atributos clave como comportamiento temporal, rendimiento, escalabilidad, seguridad, interoperabilidad y precisión, considerando el uso de tecnologías como Inteligencia Artificial y Realidad Aumentada, las cuales requieren procesamiento de imágenes, renderizado en tiempo real y análisis de datos del usuario.

A continuación, se detallan los escenarios identificados:

| ATRIBUTO | FUENTE | ESTÍMULO | ARTEFACTO | ENTORNO | RESPUESTA | MEDIDA |
|---|---|---|---|---|---|---|
| Comportamiento Temporal | Usuario | Sube una foto para registrar una prenda | Módulo de detección con IA | Operación normal | El sistema procesa la imagen y devuelve las etiquetas sugeridas | Tiempo de respuesta ≤ 4 segundos en el 90% de los casos |
| Rendimiento | Usuario | Activa el probador con AR usando la cámara | Módulo de Realidad Aumentada | Operación normal, dispositivo móvil | El sistema superpone la prenda ajustándose a los movimientos del usuario | Latencia ≤ 200 ms por frame |
| Escalabilidad | Sistema | Incremento simultáneo de usuarios activos | Backend / API RESTful | Alta carga (campaña o lanzamiento) | El sistema mantiene tiempos de respuesta estables sin caídas | Soporta ≥ 500 usuarios concurrentes sin degradación significativa |
| Seguridad | Usuario | Intenta iniciar sesión con credenciales inválidas repetidas veces | Módulo de autenticación | Operación normal | El sistema bloquea temporalmente los intentos y notifica al usuario | Bloqueo tras 5 intentos fallidos en menos de 2 minutos |
| Interoperabilidad | Tienda aliada | Genera un código QR de adquisición para una prenda física | Módulo de integración comercial | Operación normal | El sistema crea el código y lo vincula al catálogo sin duplicados | Generación correcta en el 100% de los casos válidos |
| Precisión (IA) | Sistema | Se analiza el armario del usuario para generar un outfit | Agente de Recomendación (IA) | Procesamiento con datos del usuario | El sistema entrega una combinación relevante según el contexto ingresado | Aceptación del outfit sugerido en al menos el 70% de las pruebas de usuario |

#### 4.1.2.3. Constraints

En esta sección se presentan las principales restricciones del sistema Mirage, las cuales no son negociables y condicionan el diseño de la arquitectura. Todas las Technical Stories de esta sección se agrupan bajo la Epic EP08 (Desarrollo Técnico del Backend e Infraestructura), por tratarse de restricciones que afectan la base técnica transversal del sistema; cuando una restricción también condiciona directamente a otro módulo (IA, avatar o AR), se referencia igualmente ese Epic.

A continuación, se detallan los constraints definidos como Technical Stories:

| TECHNICAL STORY ID | TÍTULO | DESCRIPCIÓN | CRITERIOS DE ACEPTACIÓN | RELACIONADO CON (EPIC ID) |
|---|---|---|---|---|
| TS01 | Procesamiento centralizado de modelos de IA | Los modelos de IA usados para reconocimiento de prendas, estimación corporal y recomendaciones deben ejecutarse en un módulo separado, independiente del backend principal. | El sistema resuelve las solicitudes de IA sin que una falla en ese módulo afecte el resto de funcionalidades. | EP03, EP08 |
| TS02 | Renderizado 3D y AR compatible con hardware estándar | El avatar y el probador con Realidad Aumentada deben funcionar en dispositivos móviles de gama media, sin exigir hardware especializado. | El probador virtual y el módulo AR se ejecutan de forma fluida en los dispositivos objetivo definidos por el equipo. | EP05, EP06 |
| TS03 | Procesamiento asíncrono de imágenes | La carga y el análisis de fotografías de prendas o de cuerpo completo deben resolverse en segundo plano, sin bloquear la interacción del usuario con la aplicación. | El usuario puede seguir navegando en la aplicación mientras la imagen se procesa. | EP08 |
| TS04 | Escalamiento independiente por tipo de usuario | La infraestructura debe permitir escalar por separado la carga generada por usuarios finales y por tiendas aliadas. | El aumento de tráfico de un segmento no degrada el rendimiento del otro. | EP08 |
| TS05 | Integración con servicios externos | El sistema debe conectarse con proveedores externos de autenticación, generación de QR y servicios de IA en la nube. | El login con proveedores externos y la generación de QR funcionan de forma independiente al núcleo del sistema. | EP08 |
| TS06 | Despliegue en infraestructura cloud | La solución debe alojarse en un proveedor cloud que soporte el procesamiento de IA y de renderizado sin depender de servidores propios. | La plataforma permanece disponible en línea y soporta acceso remoto continuo. | EP08 |

### 4.1.3. Architectural Drivers Backlog

En esta sección se presenta el conjunto de Architectural Drivers definidos a partir del análisis de las Primary User Stories, los Quality Attribute Scenarios y los Constraints del sistema Mirage.

Estos drivers fueron identificados mediante un proceso iterativo inspirado en el enfoque de Quality Attribute Workshop (QAW), permitiendo priorizar aquellos elementos con mayor impacto tanto en los stakeholders como en la complejidad técnica de la arquitectura.

A continuación, se presenta el backlog de drivers arquitectónicos, ordenados según su nivel de importancia e impacto:

| DRIVER ID | TÍTULO DE DRIVER | DESCRIPCIÓN | IMPORTANCIA PARA STAKEHOLDERS | IMPACTO EN ARCHITECTURE TECHNICAL COMPLEXITY |
|---|---|---|---|---|
| AD01 | Reconocimiento automático de prendas con IA | El sistema debe identificar categoría, color y estilo de una prenda a partir de una foto, sin depender de un registro manual extenso. | HIGH | HIGH |
| AD02 | Agente de recomendación de outfits | El sistema debe generar combinaciones relevantes considerando el clima, la ocasión y las preferencias del usuario. | HIGH | HIGH |
| AD03 | Avatar digital y probador virtual | El sistema debe representar al usuario mediante un avatar 3D generado a partir de sus proporciones reales. | HIGH | HIGH |
| AD04 | Experiencia de Realidad Aumentada en tiempo real | El sistema debe proyectar prendas y accesorios sobre la cámara en vivo del usuario. | MEDIUM | HIGH |
| AD05 | Escalamiento independiente por segmento | La infraestructura debe soportar el crecimiento de usuarios finales y de tiendas aliadas sin afectarse entre sí. | MEDIUM | HIGH |
| AD06 | Procesamiento asíncrono de imágenes | El sistema debe procesar fotos de prendas y de cuerpo completo sin bloquear la interacción del usuario. | HIGH | MEDIUM |
| AD07 | Integración comercial mediante códigos QR | El sistema debe conectar el catálogo físico de las tiendas aliadas con el armario digital del usuario. | MEDIUM | MEDIUM |
| AD08 | Seguridad en autenticación | El sistema debe proteger las cuentas de usuarios y tiendas frente a accesos indebidos. | HIGH | MEDIUM |
| AD09 | Despliegue en entorno cloud | El sistema debe operar en infraestructura cloud para soportar el procesamiento de IA y AR. | MEDIUM | MEDIUM |

### 4.1.4. Architectural Design Decisions

En esta sección se presentan las decisiones de diseño arquitectónico para el sistema Mirage, basadas en el análisis de los Architectural Drivers identificados previamente.

Siguiendo un enfoque inspirado en el Quality Attribute Workshop (QAW), el equipo evaluó diferentes patrones arquitectónicos considerando su impacto en atributos de calidad como rendimiento, escalabilidad y capacidad de integración con tecnologías emergentes como IA y Realidad Aumentada. Se priorizaron primero los drivers con mayor impacto en la complejidad técnica (AD01, AD03 y AD05), por ser los que más condicionan la estructura general del sistema.

A continuación, se presenta la matriz de evaluación de patrones candidatos:

| DRIVER ID | TÍTULO DE DRIVER | PATTERN 1: Microservicio de IA externo | | PATTERN 2: IA embebida en el backend | | PATTERN 3: Arquitectura monolítica modular | |
|---|---|---|---|---|---|---|---|
| | | Pro | Contra | Pro | Contra | Pro | Contra |
| AD01 | Reconocimiento de prendas con IA | Permite actualizar o escalar el modelo sin afectar el resto del sistema | Introduce latencia de red adicional entre servicios | Menor latencia al no depender de llamadas externas | Acopla el ciclo de vida del modelo al del resto del backend | No aplica directamente | No aplica directamente |
| AD03 | Avatar y probador virtual | Permite usar servicios especializados de renderizado en la nube | Depende de una conexión estable y de mayor costo | No aplica directamente | No aplica directamente | Simplifica el desarrollo inicial al mantener el renderizado dentro de la aplicación | Limita el uso de modelos 3D más pesados |
| AD05 | Escalamiento independiente por segmento | Permite escalar el módulo de tiendas y el de usuarios de forma independiente | Mayor complejidad operativa desde el inicio | No aplica directamente | No aplica directamente | Más simple de desarrollar y desplegar en las primeras etapas | Un pico de carga en un módulo puede afectar a los demás |

A partir de esta evaluación, el equipo decidió mantener el módulo de IA como un servicio desacoplado del backend principal, priorizar el renderizado del avatar y del módulo AR en el dispositivo del usuario para reducir la latencia percibida, y sostener por ahora una arquitectura modular que permita separar en el futuro los servicios de tiendas y de usuarios finales, sin asumir todavía la complejidad completa de microservicios desde el arranque del proyecto.

### 4.1.5. Quality Attribute Scenario Refinements

En esta sección se presentan los escenarios de atributos de calidad refinados y priorizados para el sistema Mirage.

Como resultado del proceso de Quality Attribute Workshop (QAW), se priorizaron escenarios relacionados con el reconocimiento de prendas mediante IA, la experiencia de Realidad Aumentada, la generación de recomendaciones y la seguridad de acceso, debido a su alto impacto en la arquitectura y en los objetivos del negocio.

<table>
<tr><td colspan="3"><b>Scenario Refinement for Scenario 1 - Reconocimiento con IA</b></td></tr>
<tr><td><b>Scenario(s):</b></td><td colspan="2">Registro de una prenda mediante foto y etiquetado automático</td></tr>
<tr><td><b>Business Goals:</b></td><td colspan="2">Reducir la fricción en el registro de prendas para incentivar el uso continuo del armario digital</td></tr>
<tr><td><b>Relevant Quality Attributes:</b></td><td colspan="2">Comportamiento Temporal, Corrección Funcional</td></tr>
<tr><td rowspan="6"><b>Scenario Components</b></td><td>Stimulus:</td><td>El usuario captura o carga una fotografía de una prenda</td></tr>
<tr><td>Stimulus Source:</td><td>Usuario final desde la aplicación móvil</td></tr>
<tr><td>Environment:</td><td>Operación normal, conexión estable a internet</td></tr>
<tr><td>Artifact (if Known):</td><td>Módulo de detección de prendas con IA</td></tr>
<tr><td>Response:</td><td>El sistema elimina el fondo de la imagen y devuelve categoría, color y estilo sugeridos</td></tr>
<tr><td>Response Measure:</td><td>Tiempo de respuesta ≤ 4 segundos en el 90% de las solicitudes</td></tr>
<tr><td><b>Questions:</b></td><td colspan="2">¿Qué ocurre si el servicio de IA externo no responde a tiempo?</td></tr>
<tr><td><b>Issues:</b></td><td colspan="2">Definir un tiempo máximo de espera y un mensaje de reintento para el usuario</td></tr>
</table>

<table>
<tr><td colspan="3"><b>Scenario Refinement for Scenario 2 - Realidad Aumentada</b></td></tr>
<tr><td><b>Scenario(s):</b></td><td colspan="2">Prueba de una prenda en tiempo real mediante el probador con AR</td></tr>
<tr><td><b>Business Goals:</b></td><td colspan="2">Ofrecer una experiencia inmersiva que diferencie a Mirage de otras aplicaciones de armario</td></tr>
<tr><td><b>Relevant Quality Attributes:</b></td><td colspan="2">Rendimiento, Usabilidad</td></tr>
<tr><td rowspan="6"><b>Scenario Components</b></td><td>Stimulus:</td><td>El usuario selecciona una prenda y activa la cámara en modo AR</td></tr>
<tr><td>Stimulus Source:</td><td>Usuario final desde la aplicación móvil</td></tr>
<tr><td>Environment:</td><td>Operación normal, dispositivo móvil de gama media</td></tr>
<tr><td>Artifact (if Known):</td><td>Módulo de Realidad Aumentada</td></tr>
<tr><td>Response:</td><td>El sistema superpone la prenda sobre la imagen en vivo, ajustándose a los movimientos del usuario</td></tr>
<tr><td>Response Measure:</td><td>Latencia ≤ 200 ms por frame, sin pérdida de seguimiento corporal en condiciones normales de luz</td></tr>
<tr><td><b>Questions:</b></td><td colspan="2">¿Qué tan tolerante debe ser el sistema ante variaciones de iluminación?</td></tr>
<tr><td><b>Issues:</b></td><td colspan="2">Evaluar si se necesita un modelo de detección más ligero para dispositivos de gama baja</td></tr>
</table>

<table>
<tr><td colspan="3"><b>Scenario Refinement for Scenario 3 - Recomendación de Outfits con IA</b></td></tr>
<tr><td><b>Scenario(s):</b></td><td colspan="2">Generación de una recomendación de outfit según contexto (clima, ocasión)</td></tr>
<tr><td><b>Business Goals:</b></td><td colspan="2">Aumentar el uso recurrente de la aplicación ofreciendo combinaciones relevantes del propio armario del usuario</td></tr>
<tr><td><b>Relevant Quality Attributes:</b></td><td colspan="2">Precisión, Usabilidad</td></tr>
<tr><td rowspan="6"><b>Scenario Components</b></td><td>Stimulus:</td><td>El usuario ingresa un contexto (ej. "boda de día", "clima cálido") y solicita una recomendación</td></tr>
<tr><td>Stimulus Source:</td><td>Usuario final desde la aplicación móvil</td></tr>
<tr><td>Environment:</td><td>Operación normal, con el armario del usuario ya registrado</td></tr>
<tr><td>Artifact (if Known):</td><td>Agente de Recomendación (IA)</td></tr>
<tr><td>Response:</td><td>El sistema analiza el armario y sugiere una combinación coherente con el contexto ingresado</td></tr>
<tr><td>Response Measure:</td><td>Aceptación del outfit sugerido en al menos el 70% de las pruebas de usuario, respuesta entregada en menos de 3 segundos</td></tr>
<tr><td><b>Questions:</b></td><td colspan="2">¿Qué ocurre si el armario no tiene suficientes prendas para el contexto solicitado?</td></tr>
<tr><td><b>Issues:</b></td><td colspan="2">Definir cómo se comunica al usuario una recomendación parcial cuando falta alguna prenda clave</td></tr>
</table>

<table>
<tr><td colspan="3"><b>Scenario Refinement for Scenario 4 - Seguridad en Autenticación</b></td></tr>
<tr><td><b>Scenario(s):</b></td><td colspan="2">Intentos repetidos de inicio de sesión con credenciales inválidas</td></tr>
<tr><td><b>Business Goals:</b></td><td colspan="2">Proteger las cuentas de usuarios y tiendas aliadas frente a accesos no autorizados</td></tr>
<tr><td><b>Relevant Quality Attributes:</b></td><td colspan="2">Seguridad</td></tr>
<tr><td rowspan="6"><b>Scenario Components</b></td><td>Stimulus:</td><td>El usuario ingresa credenciales incorrectas de forma repetida</td></tr>
<tr><td>Stimulus Source:</td><td>Usuario (o actor malicioso) desde la aplicación móvil</td></tr>
<tr><td>Environment:</td><td>Operación normal</td></tr>
<tr><td>Artifact (if Known):</td><td>Módulo de autenticación</td></tr>
<tr><td>Response:</td><td>El sistema bloquea temporalmente los intentos y notifica al usuario</td></tr>
<tr><td>Response Measure:</td><td>Bloqueo tras 5 intentos fallidos en menos de 2 minutos</td></tr>
<tr><td><b>Questions:</b></td><td colspan="2">¿Cuánto debe durar el bloqueo temporal antes de permitir un nuevo intento?</td></tr>
<tr><td><b>Issues:</b></td><td colspan="2">Definir si el bloqueo es por cuenta, por IP, o por ambos, para evitar falsos bloqueos a usuarios legítimos</td></tr>
</table>

## 4.2. Strategic-Level Domain-Driven Design


En esta sección se describe el enfoque aplicado para orientar las decisiones estratégicas relacionadas con el diseño del dominio de Mirage, tomando como referencia los principios de Domain-Driven Design (DDD). El propósito principal fue comprender y estructurar el dominio del sistema a partir de sus procesos, actores, reglas de negocio y responsabilidades, permitiendo identificar límites funcionales coherentes dentro de la solución.

Para este proceso, el equipo empleó herramientas de modelado colaborativo como Event Storming y Bounded Context Canvas. Event Storming permitió explorar el comportamiento del dominio mediante la identificación de eventos, comandos, actores y procesos relevantes, facilitando una visión compartida de cómo se desarrollan las principales operaciones de Mirage. Posteriormente, el Bounded Context Canvas permitió analizar y delimitar los contextos identificados, especificando su propósito, responsabilidades, modelos y relaciones con otras partes del dominio.

Este enfoque permitió construir una representación estructurada del dominio de Mirage y establecer límites funcionales basados en las responsabilidades y reglas del negocio, evitando una separación arbitraria de los componentes del sistema. De esta manera, las decisiones arquitectónicas posteriores se fundamentan en una comprensión previa del dominio y de las relaciones existentes entre sus diferentes procesos.

### 4.2.1. EventStorming

En esta sección se presenta el proceso de Event Storming realizado por el equipo para obtener una primera representación del dominio de Mirage. Esta técnica permitió identificar los principales eventos que ocurren dentro del sistema, así como los comandos, actores y procesos que intervienen en su generación, proporcionando una visión general del comportamiento esperado de la solución.

Durante la sesión, el equipo analizó los diferentes escenarios funcionales de Mirage y organizó los elementos del dominio de acuerdo con la secuencia en la que ocurren las acciones y sus respectivos resultados. La representación visual permitió identificar dependencias, relaciones entre procesos y posibles límites funcionales, además de facilitar la discusión entre los integrantes del equipo sobre las reglas y comportamientos que debería contemplar el sistema.

El desarrollo de Event Storming permitió establecer una base común de conocimiento sobre el dominio antes de definir su estructura interna. A partir de los eventos y procesos identificados, posteriormente se analizaron posibles agrupaciones de responsabilidades que sirvieron como referencia para la definición de los Bounded Contexts de Mirage y para las decisiones de diseño de su arquitectura.

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/paso1.png" alt="EventStorming" style="width: 700">
</p>

### 4.2.2. Candidate Context Discovery
Durante la sesión de Event Storming se realizó el levantamiento y organización de los principales eventos asociados al funcionamiento de Mirage. A partir de esta actividad, se examinaron las acciones que intervienen en los diferentes procesos de la aplicación, buscando reconocer cómo se relacionan entre sí y qué funcionalidades del sistema representan. Esta revisión permitió agrupar los eventos de acuerdo con los flujos funcionales identificados y obtener una primera representación del comportamiento del dominio de Mirage.

A partir de la organización obtenida, se establecieron las siguientes líneas de acción:

**Personalización del avatar**

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/paso2_personalizacion.png" alt="EventStorming" style="width: 700">
</p>

**Recomendación y gestión de outfits**

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/paso2_recomendacion.png" alt="EventStorming" style="width: 700">
</p>


**Configuración del perfil y preferencias de estilo**

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/paso2_configuracion.png" alt="EventStorming" style="width: 700">
</p>


**Prueba de outfits mediante realidad aumentada**

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/paso2_prueba.png" alt="EventStorming" style="width: 700">
</p>


**Administración del armario virtual**

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/paso2_administracion.png" alt="EventStorming" style="width: 700">
</p>


**Reconocimiento y registro de prendas**

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/paso2_reconocimiento.png" alt="EventStorming" style="width: 700">
</p>


**Gestión del catálogo de prendas de tiendas**

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/paso2_gestion.png" alt="EventStorming" style="width: 700">
</p>


**Integración de prendas y proceso de compra**

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/paso2_integracion.png" alt="EventStorming" style="width: 700">
</p>


**Intercambio de prendas entre usuarios**

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/paso2_intercambio.png" alt="EventStorming" style="width: 700">
</p>


**Conexión entre usuarios mediante amistades**

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/paso2_conexion.png" alt="EventStorming" style="width: 700">
</p>


**Prueba virtual de prendas compartidas**

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/paso2_prueba_virtual.png" alt="EventStorming" style="width: 700">
</p>

Una vez agrupados los eventos del dominio, se realizó una revisión de los diferentes flujos con el propósito de identificar los pain points, entendidos como situaciones que pueden generar dificultades, fricciones o inconsistencias durante la interacción con las funcionalidades de Mirage. Entre los principales puntos identificados se encuentran:

- Dificultad para obtener las medidas corporales necesarias para generar un avatar personalizado.
- Posibles inconsistencias en el reconocimiento automático de las características de una prenda a partir de una imagen.
- Necesidad de contar con información suficiente del armario para generar recomendaciones de outfits pertinentes.
- Dependencia de las preferencias de estilo del usuario para personalizar las propuestas de outfits.
- Posibles dificultades en la actualización y mantenimiento de las prendas disponibles en el catálogo de las tiendas.
- Necesidad de mantener sincronizada la información de las prendas entre el catálogo de las tiendas y el armario digital del usuario.
- Dependencia de la detección correcta del usuario y del entorno para realizar la proyección de prendas mediante realidad aumentada.
- Necesidad de controlar la visibilidad de las prendas y armarios cuando son compartidos entre usuarios.
- Posibles fricciones en la gestión de solicitudes de amistad y permisos para compartir o probar prendas.

Posteriormente, se identificaron los pivotal points, considerados como aquellos eventos o decisiones dentro de los flujos que pueden generar una transición significativa en el comportamiento del sistema. Los principales identificados fueron:

- La creación y configuración de la cuenta del usuario.
- El registro de las medidas necesarias para generar el avatar personalizado.
- La generación de un outfit personalizado.
- La incorporación de una prenda al armario digital.
- El reconocimiento y registro de una prenda mediante una fotografía.
- El registro de una tienda y la incorporación de sus prendas al catálogo.
- La identificación de una prenda mediante el escaneo de un código QR.
- La activación del modo de realidad aumentada.
- El establecimiento de una amistad entre usuarios.
- La aceptación o rechazo de una solicitud para compartir una prenda.
- La generación de un outfit a partir de prendas de una tienda.

A partir de este análisis, fue posible determinar cómo los diferentes eventos, puntos críticos y responsabilidades identificados durante el Event Storming podían organizarse en límites funcionales del dominio. Como resultado, se establecieron los siguientes Bounded Contexts para Mirage: Profile, Recommendation, Store Catalog, Social Interactions, Augmented Reality y Digital Closet.

**Profile**

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/profile_bc.png" alt="EventStorming" style="width: 700">
</p>

**Recommendation**
<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/recommendation_bc.png" alt="EventStorming" style="width: 700">
</p>

**Store Catalog**

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/store_bc.png" alt="EventStorming" style="width: 700">
</p>


**Social Interactions**

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/social_bc.png" alt="EventStorming" style="width: 700">
</p>

**Augmented Reality**

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/reality_bc.png" alt="EventStorming" style="width: 700">
</p>

**Digital Closet**

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/closet_bc.png" alt="EventStorming" style="width: 700">
</p>

### 4.2.3. Domain Message Flows Modeling

El siguiente modelo representa la interacción entre los diferentes Bounded Contexts identificados para Mirage, mostrando cómo determinadas acciones realizadas por los usuarios generan eventos que permiten establecer relaciones entre los contextos del sistema. Cada Bounded Context mantiene responsabilidades específicas dentro del dominio, pero puede intercambiar información con otros contextos cuando un proceso requiere complementar sus funcionalidades.

Las principales relaciones identificadas son las siguientes:

**Profile y Store Catalog:**

Una vez que el usuario crea satisfactoriamente su cuenta y configura su perfil, puede registrar dicha cuenta como una tienda dentro de Mirage. De esta manera, la información gestionada desde Profile permite habilitar las funcionalidades correspondientes a la administración de una tienda y su catálogo de prendas.

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/profile_store.png" alt="EventStorming" style="width: 700">
</p>

**Profile y Social Interactions:**

Después de crear y personalizar su perfil y avatar, el usuario puede establecer conexiones con otros usuarios mediante el envío de solicitudes de amistad. Una vez aceptada la solicitud, se establece la relación entre ambos perfiles, habilitando las funcionalidades de interacción social disponibles en Mirage.

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/profile_social.png" alt="EventStorming" style="width: 700">
</p>


**Profile y Digital Closet:**

Luego de personalizar su perfil y avatar, el usuario puede incorporar prendas a su armario digital mediante el escaneo de las prendas. La información obtenida durante este proceso permite registrar las prendas y asociarlas con el usuario dentro de Digital Closet.

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/profile_digital_closet.png" alt="EventStorming" style="width: 700">
</p>


**Digital Closet y Recommendation:**

Una vez que el usuario cuenta con prendas registradas en su armario digital, esta información puede ser utilizada por Recommendation para generar outfits personalizados. Las prendas disponibles y las preferencias de estilo del usuario sirven como elementos para elaborar propuestas acordes con sus características y preferencias.

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/digital_recommendation.png" alt="EventStorming" style="width: 700">
</p>


**Recommendation y Augmented Reality:**

Después de obtener una recomendación de outfit, el usuario puede visualizarla mediante la funcionalidad de realidad aumentada. El outfit generado por Recommendation es utilizado como información de entrada para que Augmented Reality pueda proyectarlo sobre el usuario y permitir su visualización en el entorno aumentado.

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/recommendation_reality.png" alt="EventStorming" style="width: 700">
</p>


**Vista completa:**

Este modelo representa las principales relaciones identificadas entre los Bounded Contexts de Mirage, permitiendo visualizar cómo las diferentes capacidades del sistema se complementan entre sí. Profile concentra la información relacionada con la cuenta, configuración del usuario, preferencias, medidas y avatar; Store Catalog gestiona las tiendas y las prendas disponibles en sus catálogos; Digital Closet administra las prendas incorporadas al armario personal; Recommendation utiliza la información disponible para generar outfits personalizados; Augmented Reality permite visualizar y probar virtualmente las prendas y outfits; y Social Interactions gestiona las relaciones entre usuarios y el intercambio de prendas.

<p align="center">
  <img src="assets/img/Capitulo-4/EventStorming/vista_completa.png" alt="EventStorming" style="width: 700">
</p>

### 4.2.4. Bounded Context Canvases

En esta sección se presentan los Bounded Contexts que delimitan y organizan el dominio principal de Mirage. Su definición se realizó a partir del análisis de los eventos, comandos, políticas y relaciones identificados durante el Event Storming, buscando establecer límites claros entre las distintas responsabilidades del sistema y evitar la superposición de conceptos. Para documentar cada contexto se empleó el Bounded Context Canvas, herramienta que permite describir de manera estructurada su propósito, reglas de negocio, capacidades, lenguaje ubicuo, dependencias y consideraciones de diseño.

El proceso de definición de los contextos contempló los siguientes aspectos:

Context Overview Definition: Se establece el propósito y alcance de cada contexto, especificando la responsabilidad que asume dentro del dominio de Mirage.
Business Rules Distillation & Ubiquitous Language Capture: Se determinan las reglas de negocio propias de cada contexto y los conceptos principales que conforman su lenguaje ubicuo.
Capability Analysis: Se identifican las capacidades necesarias para cumplir con las responsabilidades asignadas al contexto.
Capability Layering: Se organizan las capacidades según su importancia, diferenciando aquellas que constituyen el núcleo del contexto de las que funcionan como soporte.
Dependencies Capture: Se reconocen las relaciones que mantiene cada contexto con los demás, considerando la información que requiere o proporciona para completar determinados procesos.
Design Critique: Se analiza la delimitación propuesta, considerando fortalezas, posibles debilidades y riesgos asociados al diseño del contexto.

A continuación, se presentan los Bounded Context Canvas correspondientes a cada uno de los contextos identificados para Mirage.

Profile: Este contexto concentra la gestión de la información principal del usuario dentro de Mirage. Comprende la creación y configuración de la cuenta, las preferencias de estilo, el registro de medidas corporales y la generación del avatar personalizado, proporcionando la información necesaria para personalizar la experiencia del usuario.

<p align="center">
  <img src="assets/img/Capitulo-4/BC_Canvas/bc_canvas_profile.png" alt="EventStorming" style="width: 700">
</p>

Digital Closet: Este contexto se encarga de administrar las prendas pertenecientes al armario digital del usuario. Incluye el registro, incorporación, actualización, eliminación y organización de prendas, así como el procesamiento de información obtenida mediante el reconocimiento de imágenes.

<p align="center">
  <img src="assets/img/Capitulo-4/BC_Canvas/bc_canvas_closet.png" alt="EventStorming" style="width: 700">
</p>

Recommendation: Este contexto gestiona la generación de outfits personalizados a partir de las prendas disponibles y las preferencias de estilo del usuario. Comprende el cálculo de compatibilidad, la generación de propuestas y las acciones posteriores sobre los outfits, como guardarlos, marcarlos como favoritos o rechazarlos.

<p align="center">
  <img src="assets/img/Capitulo-4/BC_Canvas/bc_canvas_recommendation.png" alt="EventStorming" style="width: 700">
</p>

Store Catalog: Este contexto administra la información relacionada con las tiendas y sus prendas disponibles. Incluye el registro de tiendas, la configuración de sus perfiles, la gestión del catálogo de productos, la generación de códigos QR y la actualización o retiro de prendas.

<p align="center">
  <img src="assets/img/Capitulo-4/BC_Canvas/bc_canvas_store.png" alt="EventStorming" style="width: 700">
</p>

Social Interactions: Este contexto gestiona las relaciones e interacciones entre los usuarios de Mirage. Comprende el envío y gestión de solicitudes de amistad, el establecimiento de relaciones, la visualización de perfiles y armarios de amistades y el intercambio de prendas entre usuarios.

<p align="center">
  <img src="assets/img/Capitulo-4/BC_Canvas/bc_canvas_social.png" alt="EventStorming" style="width: 700">
</p>

Augmented Reality: Este contexto se encarga de las funcionalidades relacionadas con la visualización y prueba virtual de prendas y outfits mediante realidad aumentada. Incluye la detección del usuario y del entorno, la generación de superposiciones y la proyección de prendas u outfits sobre el usuario.

<p align="center">
  <img src="assets/img/Capitulo-4/BC_Canvas/bc_canvas_reality.png" alt="EventStorming" style="width: 700">
</p>

### 4.2.5. Context Mapping
El Context Mapping es una técnica estratégica de Domain-Driven Design (DDD) que permite representar las relaciones existentes entre los diferentes Bounded Contexts de un sistema. A través de este mapeo se pueden identificar las dependencias entre contextos y determinar qué contexto proporciona información o capacidades y cuál las consume. De esta manera, se establecen límites claros entre las distintas partes del dominio y se facilita una evolución independiente de cada contexto, evitando dependencias innecesarias.

En Mirage se identificaron seis Bounded Contexts principales: Profile, Store Catalog, Social Interactions, Digital Closet, Recommendation y Augmented Reality. El contexto Profile actúa como Upstream (U) frente a Store Catalog, Social Interactions y Digital Closet, ya que proporciona información relacionada con el usuario que es utilizada por estos contextos, que cumplen el rol de Downstream (D). A su vez, Digital Closet funciona como Upstream para Recommendation, proporcionando la información de las prendas registradas que permite generar recomendaciones personalizadas. Finalmente, Recommendation actúa como Upstream para Augmented Reality, que consume las recomendaciones generadas para permitir su visualización mediante realidad aumentada.

<p align="center">
  <img src="assets/img/Capitulo-4/BC_Canvas/Context_Mapping.png" alt="EventStorming" style="width: 700">
</p>

## 4.3. Software Architecture

En la arquitectura de software primero nos enfocamos en aterrizar la estructura técnica de Mirage. Para lograrlo, decidimos utilizar el Modelo C4, ya que nos permite explicar la arquitectura de forma progresiva, desde lo más general hasta los detalles técnicos. A través de estos diagramas mostramos cómo se ve la plataforma por fuera y cómo hemos dividido las responsabilidades internamente para soportar las funcionalidades de probador virtual (VTO), gestión de armarios digitales e interacción omnicanal en tiendas físicas de forma escalable y eficiente.

### 4.3.1. Software Architecture System Landscape Diagram

En esta sección se presenta el System Landscape Diagram, el cual permite visualizar a Mirage dentro de un entorno más amplio, considerando no solo a los usuarios finales y tiendas aliadas que interactúan con la solución, sino también a los servicios externos clave (como motores de visión por computadora para IA/AR y servicios en la nube). Este diagrama ofrece una perspectiva general del ecosistema en el que se encuentra la aplicación, mostrando cómo se relaciona con sus actores principales y servicios externos. De esta manera, se facilita la comprensión del alcance del sistema, sus dependencias y las integraciones que hacen posible la experiencia interactiva de la plataforma.
<p align="center">
  <img src="assets/img/Capitulo-4/c4/LandscapeDiagram.png" alt="LandscapeDiagram" style="width: 600">
</p>

### 4.3.2. Software Architecture Context Level Diagrams

El diagrama ubica a Mirage en el centro de la arquitectura como el motor de la experiencia, conectando las interacciones del Usuario quien gestiona su armario digital, combina outfits y usa el probador virtual con las de la Tienda, que administra su catálogo y códigos QR. Para soportar estos flujos, la plataforma delega tareas operativas en integraciones clave: Cloudinary almacena los recursos multimedia, Gmail gestiona el correo transaccional, Google Gemini API extrae atributos e interpreta las imágenes de las prendas, y TripoSR las convierte en modelos 3D para la experiencia en realidad aumentada.

<p align="center">
  <img src="assets/img/Capitulo-4/c4/ContextDiagram.png" alt="ContextDiagram" style="width: 600">
</p>

### 4.3.3. Software Architecture Container Level Diagrams

En este nivel, las solicitudes de los usuarios ingresan desde la aplicación móvil (Flutter) o la Landing Page (Angular) e impactan en un API Gateway centralizado (C++ / Drogon) que gestiona la autenticación y el enrutamiento. Desde allí, el tráfico se distribuye hacia microservicios especializados (Auth, Wardrobe y QR Service) respaldados por bases de datos PostgreSQL independientes. Por su parte, las operaciones complejas de visión, recomendación y 3D son canalizadas mediante una fachada de integración en Python (FastAPI), la cual coordina un grupo de agentes de IA apoyados en caché Redis, base de datos vectoriales, embeddings en Pinecone y la asistencia de API externas como Gemini y TripoSR.

<p align="center">
  <img src="assets/img/Capitulo-4/c4/ContainerDiagram.png" alt="ContainerDiagram" style="width: 700">
</p>

### 4.3.4. Software Architecture Deployment Diagrams

El Diagrama de Despliegue ilustra la distribución física de Mirage en una infraestructura de nube optimizada para alta disponibilidad e inferencia de IA. Mientras la Landing Page se aloja en GitHub Pages y la Mobile App corre nativamente en los dispositivos de los usuarios, todo el backend se orquesta en AWS Cloud Infrastructure. Allí, el tráfico ingresa mediante un servidor de API Gateway y se distribuye hacia tres clústeres especializados: un clúster Kubernetes para los microservicios de negocio, un clúster con nodos GPU dedicado exclusivamente al procesamiento de los agentes de IA, y un clúster de bases de datos gestionadas que asegura la persistencia relacional, vectorial y de caché.

<p align="center">
  <img src="assets/img/Capitulo-4/c4/DeploymentDiagram.png" alt="DeploymentDiagram" style="width: 700">
</p>

# Conclusiones

El enfoque Attribute-Driven Design permitió priorizar drivers arquitectónicos (comportamiento temporal, rendimiento, escalabilidad, seguridad, interoperabilidad y precisión de IA) a partir de las user stories principales, asegurando que la arquitectura responda a necesidades reales del negocio y no solo a funcionalidad.

Los escenarios de atributos de calidad definidos con medidas concretas (ej. ≤4 segundos de respuesta, ≤200 ms de latencia, >500 usuarios concurrentes) hacen verificable el cumplimiento de los requisitos no funcionales, facilitando pruebas y validación posterior.

El refinamiento del escenario de reconocimiento con IA evidenció la dependencia crítica de servicios externos, lo cual obliga a considerar mecanismos de resiliencia (timeouts, reintentos) desde etapas tempranas del diseño.

# Recomendaciones

Definir un plan de contingencia formal para fallos o demoras del servicio de IA externo, especificando tiempos máximos de espera y estrategias de reintento o degradación controlada del servicio.

Ampliar los escenarios de calidad con pruebas de carga reales antes del lanzamiento, para validar que el umbral de 500 usuarios concurrentes se cumple bajo condiciones de infraestructura de producción.

Documentar y monitorear métricas de precisión de IA en producción (no solo en pruebas), ya que el 70% de aceptación de recomendaciones es un valor inicial que debe ajustarse con datos reales de uso.

# Bibliografía

- Chrimes, C., & Boardman, R. (2023). Las oportunidades y desafíos del metaverso para las marcas de moda. La economía de la confección: Comprender la historia, desarrollar modelos de negocio y aprovechar tecnologías digitales, 389-410. [https://link.springer.com/chapter/10.1007/978-3-031-33302-6_20](https://link.springer.com/chapter/10.1007/978-3-031-33302-6_20)

Brandolini, A. (2021). Introducing EventStorming: An acts-on-software visual guide to domain discovery. Leanpub. [ https://www.leanpub.com/introducing_eventstorming]( https://www.leanpub.com/introducing_eventstorming)


Evans, E. (2003). Domain-driven design: Tackling complexity in the heart of software. Addison-Wesley Professional.[ https://www.oreilly.com/library/view/domain-driven-design-tackling/0321125215/]( https://www.oreilly.com/library/view/domain-driven-design-tackling/0321125215/) 

Mu, X., Zhang, H., Shi, J., Hou, J., Ma, J., & Yang, Y. (2024). Fashion intelligence in the Metaverse: promise and future prospects. Artificial Intelligence Review, 57(3), 67.  [ https://link.springer.com/article/10.1007/s10462-024-10703-8]( https://link.springer.com/article/10.1007/s10462-024-10703-8)



# Anexos

- Enlace de Miro: As-is y To-be : 
[https://miro.com/welcomeonboard/SkNzcnk2TS9LOXVNUFNIZTZZWjJabDZSNGd3OGtJNjBScGtSL2JvMXF0b0NUS1pEY3ZseWJtaGc2QlQyTXBSOTFWcmVEa0Urd2UrY1BEUlltVm5EbTRacmZsZ0NhbjhxTXdGY2xMc0dFN0xlMkMzd2xWVklVNVJKcGkwVWFzYnd3VHhHVHd5UWtSM1BidUtUYmxycDRnPT0hdjE=?share_link_id=442470584812](https://miro.com/welcomeonboard/SkNzcnk2TS9LOXVNUFNIZTZZWjJabDZSNGd3OGtJNjBScGtSL2JvMXF0b0NUS1pEY3ZseWJtaGc2QlQyTXBSOTFWcmVEa0Urd2UrY1BEUlltVm5EbTRacmZsZ0NhbjhxTXdGY2xMc0dFN0xlMkMzd2xWVklVNVJKcGkwVWFzYnd3VHhHVHd5UWtSM1BidUtUYmxycDRnPT0hdjE=?share_link_id=442470584812)
