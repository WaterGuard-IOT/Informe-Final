![Logotipo, nombre de la empresa Descripción generada
automáticamente](media/image1.png){width="2.34375in" height="2.34375in"}

Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

1ASI0572 - Desarrollo de Soluciones IoT

Sección 2939

Informe de TP1

Profesor: León Baca, Marco Antonio

Nombre del StartUp: WaterGuard

Integrantes

Asillo Mendoza, Julio Ernesto u20201b482

Oliva Alva, Kevin Jonathan u201410580

Ramirez Mendoza, Carlos Arian u202020108

Patazca Calderón, Santos Alexis u20201c269

Santivañez Filio, Diego Jesus u202112321

Alfaro Cumba, Leonel u20201a930

Abril del 2025

Registro de Versiones del Informe

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 15%" />
<col style="width: 25%" />
<col style="width: 48%" />
</colgroup>
<thead>
<tr class="header">
<th>Versión</th>
<th>Fecha</th>
<th>Autor</th>
<th>Descripción de modificación</th>
</tr>
<tr class="odd">
<th>TB1</th>
<th>08/09/2024</th>
<th>WaterGuard</th>
<th><blockquote>
<p>Elección del Tema y elaboración de los primeros 4 capítulos, que
conlleva: Planteamiento del problema, antecedentes, Investigación con
Usuarios, entrevistas, needfinding, Planificación, Historias de Usuario,
Arquitectura, Diseño en general del software y planificación de los
siguientes pasos a tomar.</p>
</blockquote></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

Contenido

Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:  
ABET -- EAC - Student Outcome 5: La capacidad de funcionar efectivamente
en un equipo cuyos miembros juntos proporcionan liderazgo, crean un
entorno de colaboración e inclusivo, establecen objetivos, planifican
tareas y cumplen objetivos.

<table>
<colgroup>
<col style="width: 35%" />
<col style="width: 32%" />
<col style="width: 32%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Criterio específico</td>
<td>Acciones realizadas</td>
<td>Conclusiones</td>
</tr>
<tr class="even">
<td>Trabajar en equipo para proporcionar liderazgo en forma
conjunta.</td>
<td><p>TB1</p>
<p>Asillo Mendoza, Julio Ernesto</p>
<p>Realicé los diagramas C4 respecto a los componentes, contenedores y
contexto. Ajustar el alcance y definir con el equipo.</p>
<p>Oliva Alva, Kevin Jonathan:</p>
<p>Se realizó la planificación y la recolección de requerimientos
necesarios para poder solucionar las necesidades del usuario a través de
nuestra solución</p>
<p>Ramirez Mendoza, Carlos Arian</p>
<p>Se realizaron reuniones para entender mejor la problemática y brindar
distintos puntos de vista. En el proceso cada uno de los integrante
promovieron sus ideas.</p>
<p>Patazca Calderón, Santos Alexis</p>
<p>Se llevó a cabo la mejora de los perfiles del proyecto, coordinando
ideas con el equipo en reuniones. Contribuí activamente a decisiones
clave para alinear el diseño con los objetivos del sistema.</p>
<p>Santivañez Filio, Diego Jesus:</p>
<p>Se realizaron reuniones para poder realizar el desarrollo de la
arquitectura y el diseño de software que usaremos en el proyecto</p>
<p>Alfaro Cumba, Leonel</p>
<p>Se realizaron las preguntas para las entrevistas y de otros puntos
relacionados al usuarios para mejorar el enfoque del proyecto</p>
<p>TP</p>
<p>Asillo Mendoza, Julio Ernesto</p>
<p>Colaboramos para repartirnos el trabajo pesado en varias tareas
mínimas, para el desarrollo web, móvil y landing page.</p>
<p>Oliva Alva, Kevin Jonathan</p>
<p>Nos concentramos en definir las historias de usuarios del core del
negocio, lo que nos permitio entender que era lo más relevante que
debíamos implementar para este sprint.</p>
<p>Patazca Calderón, Santos Alexis</p>
<p>Se establecieron objetivos concretos para el desarrollo de las
pantallas principales y se priorizaron las funcionalidades a
implementar.</p>
<p>Santivañez Filio, Diego Jesus</p>
<p>Se establecieron las normativas para poder empezar el desarrollo del
API de la aplicación, además de asignar los user stories a realizar.</p>
<p>Alfaro Cumba, Leonel</p>
<p>Durante el diseño de los wireframes y mock-ups de la aplicación, se
asignaron roles específicos a cada integrante para garantizar
eficiencia. Se trabajó colaborativamente para definir el flujo de
usuario, asegurando que cada pantalla cumpliera con los objetivos
funcionales del sistema.</p>
<p>Ramirez Mendoza Carlos Arian</p>
<p>Se trabajo en equipo para organizar y establecer el desarrollo de la
aplicación, tanto web como móvil, así como el backend de la aplicación y
su despliegue en servicios cloud.</p></td>
<td></td>
</tr>
<tr class="odd">
<td>Crear un entorno colaborativo e inclusivo, establecer metas,
planificar tareas y cumplir objetivos.</td>
<td><p>TB1</p>
<p>Asillo Mendoza, Julio Ernesto</p>
<p>Tomé iniciativa para el futuro del proyecto encargarme del desarrollo
mobile. Apoyé activamente en la coordinación.</p>
<p>Oliva Alva, Kevin Jonathan</p>
<p>Se realizaron los user stories, impact mapping y product backlog
dentro del rango de fechas prevista para la entrega del trabajo</p>
<p>Ramirez Mendoza, Carlos Arian</p>
<p>Patazca Calderón, Santos Alexis</p>
<p>Apoyé con la organización de entregables, promoviendo una
comunicación participativa.</p>
<p>Desarrolle el avance del frontend y la mejora de apartados de
antecedentes y problemática, facilitando el cumplimiento de los
objetivos.</p>
<p>Santivañez Filio, Diego Jesus</p>
<p>Se realizaron reuniones para la realización de la estructura del
software y para poder definir los bounded context dentro del plazo
acordado.</p>
<p>Alfaro Cumba, Leonel</p>
<p>Se establecieron metas claras, y se trabajó en equipo para cumplir
los objetivos del proyecto, asegurando un enfoque alineado a las
necesidades de los usuarios. como el desarrollo del Del Needfinding</p>
<p>Ramirez Mendoza Carlos Arian</p>
<p>Durante el desarrollo del proyecto, se promovió la participación
equitativa dentro del equipo, asignando responsabilidades según las
fortalezas de cada miembro. Se mantuvo una comunicación constante para
asegurar el progreso de las tareas, ajustando estrategias cuando fue
necesario para alcanzar los hitos establecidos.</p>
<p>TP</p>
<p>Asillo Mendoza, Julio Ernesto</p>
<p>Mediante la plataforma de Discord nos coordinamos y bueno, estuve
encargado de repartir los puntos de manera proporcional.</p>
<p>Oliva Alva, Kevin Jonathan</p>
<p>La planificación en equipo fue fundamental para poder avanzar
paralelamente diferentes partes del proyecto, logrando el objetivo
central el cual fue avanzar la primera parte del producto de
software.</p>
<p>Patazca Calderón, Santos Alexis</p>
<p>La planificación inicial fue clave para organizar el tiempo de
desarrollo y priorizar funcionalidades del sistema. El trabajo en equipo
permitió cumplir con los objetivos del Sprint.</p>
<p>Santivañez Filio, Diego Jesus</p>
<p>En el desarrollo del API se establecieron las metas y fechas para
todo el equipo, con el fin de cumplir con el desarrollo y evitar demoras
en la entrega de este Sprint.</p>
<p>Alfaro Cumba, Leonel</p>
<p>En la etapa de diseño de la aplicación, los miembros del equipo
participaron para validar las decisiones visuales y funcionales. Se
estableció una planificación clara que permitió entregar a tiempo los
<em>User Flow Diagrams</em> y mock-ups finales.</p>
<p>Ramirez Mendoza Carlos Arian</p>
<p>Durante el sprint se mantuvo una comunicación constante para asegurar
el progreso de las tareas, ajustando estrategias cuando fue necesario
para alcanzar los hitos establecidos para el desarrollo de los productos
de software.</p></td>
<td></td>
</tr>
</tbody>
</table>

Tabla de Contenido

[Capítulo I: Introducción 7](#capítulo-i-introducción)

> [1.1. Startup Profile 7](#startup-profile)
>
> [1.1.1. Descripción de la Startup 7](#descripción-de-la-startup)
>
> [1.1.2. Perfiles de integrantes del equipo
> 8](#perfiles-de-integrantes-del-equipo)
>
> [1.2. Solution Profile 9](#solution-profile)
>
> [1.2.1 Antecedentes y problemática 9](#antecedentes-y-problemática)
>
> [1.2.2 Lean UX Process 11](#lean-ux-process)
>
> [1.2.2.1. Lean UX Problem Statements 11](#lean-ux-problem-statements)
>
> [1.2.2.2. Lean UX Assumptions 12](#lean-ux-assumptions)
>
> [1.2.2.3. Lean UX Hypothesis Statements
> 14](#lean-ux-hypothesis-statements)
>
> [1.2.2.4. Lean UX Canvas 16](#lean-ux-canvas)
>
> [1.3. Segmentos objetivo 18](#segmentos-objetivo)

[Capítulo II: Requirements Elicitation & Analysis
18](#capítulo-ii-requirements-elicitation-analysis)

> [2.1. Competidores 18](#competidores)
>
> [2.1.1. Análisis competitivo 19](#análisis-competitivo)
>
> [2.1.2. Estrategias y tácticas frente a competidores
> 25](#estrategias-y-tácticas-frente-a-competidores)
>
> [2.2. Entrevistas 25](#entrevistas)
>
> [2.2.1. Diseño de entrevistas 25](#diseño-de-entrevistas)
>
> [2.2.2. Registro de entrevistas 27](#registro-de-entrevistas)
>
> [2.2.3. Análisis de entrevistas 29](#análisis-de-entrevistas)
>
> [2.3. Needfinding 29](#needfinding)
>
> [2.3.1. User Personas 29](#user-personas)
>
> [2.3.2. User Task Matrix 31](#user-task-matrix)
>
> [2.3.3. User Journey Mapping 31](#user-journey-mapping)
>
> [2.3.4. Empathy Mapping 32](#empathy-mapping)
>
> [2.3.5. As-is Scenario Mapping 32](#as-is-scenario-mapping)

[Capítulo III: Requirements Specification
33](#capítulo-iii-requirements-specification)

> [3.1. To-Be Scenario Mapping 33](#to-be-scenario-mapping)
>
> [3.2. User Stories 34](#user-stories)
>
> [3.3. Impact Mapping 52](#impact-mapping)
>
> [3.4. Product Backlog 52](#product-backlog)

[Capítulo IV: Solution Software Design
56](#capítulo-iv-solution-software-design)

> [4.1 Strategic-Level Domain-Driven Design
> 56](#strategic-level-domain-driven-design)
>
> [4.1.1. EventStorming 57](#eventstorming)
>
> [4.1.1.1. Candidate Context Discovery
> 58](#candidate-context-discovery)
>
> [4.1.1.2. Domain Message Flows Modeling
> 59](#domain-message-flows-modeling)
>
> [4.1.1.3. Bounded Context Canvases 60](#bounded-context-canvases)
>
> [4.1.2. Context Mapping 61](#context-mapping)
>
> [4.1.3. Software Architecture 62](#software-architecture)
>
> [4.1.3.1. Software Architecture Context Level Diagrams
> 62](#software-architecture-context-level-diagrams)
>
> [4.1.3.2. Software Architecture Container Level Diagrams
> 63](#software-architecture-container-level-diagrams)
>
> [4.1.3.3. Software Architecture Deployment Diagrams
> 63](#software-architecture-deployment-diagrams)
>
> [4.2. Tactical-Level Domain-Driven Design
> 64](#tactical-level-domain-driven-design)
>
> [4.2.1. Bounded Context: Monitoreo de Niveles de Agua
> 64](#bounded-context-monitoreo-de-niveles-de-agua)
>
> [4.2.1.1. Domain Layer 64](#domain-layer)
>
> [4.2.1.2. Interface Layer 66](#interface-layer)
>
> [4.2.1.3. Application Layer 67](#application-layer)
>
> [4.2.1.4. Infrastructure Layer 68](#infrastructure-layer)
>
> [4.2.1.5. Bounded Context Software Architecture Component Level
> Diagrams
> 69](#bounded-context-software-architecture-component-level-diagrams)
>
> [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams
> 69](#bounded-context-software-architecture-code-level-diagrams)
>
> [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams
> 70](#bounded-context-domain-layer-class-diagrams)
>
> [4.2.1.6.2. Bounded Context Database Design Diagram
> 70](#bounded-context-database-design-diagram)
>
> [4.2.2. Bounded Context: Análisis de Calidad de Agua
> 70](#bounded-context-análisis-de-calidad-de-agua)
>
> [4.2.2.1. Domain Layer 70](#domain-layer-1)
>
> [4.2.2.2. Interface Layer 73](#interface-layer-1)
>
> [4.2.2.3. Application Layer 74](#application-layer-1)
>
> [4.2.2.4. Infrastructure Layer 75](#infrastructure-layer-1)
>
> [4.2.2.5. Bounded Context Software Architecture Component Level
> Diagrams
> 76](#bounded-context-software-architecture-component-level-diagrams-1)
>
> [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams
> 76](#bounded-context-software-architecture-code-level-diagrams-1)
>
> [4.2.2.6.1. Bounded Context Domain Layer Class Diagrams
> 77](#bounded-context-domain-layer-class-diagrams-1)
>
> [4.2.2.6.2. Bounded Context Database Design Diagram
> 77](#bounded-context-database-design-diagram-1)
>
> [4.2.3. Bounded Context: Generación de Reportes
> 77](#bounded-context-generación-de-reportes)
>
> [4.2.3.1. Domain Layer 78](#domain-layer-2)
>
> [4.2.3.2. Interface Layer 80](#interface-layer-2)
>
> [4.2.3.3. Application Layer 80](#application-layer-2)
>
> [4.2.3.4. Infrastructure Layer 81](#infrastructure-layer-2)
>
> [4.2.3.5. Bounded Context Software Architecture Component Level
> Diagrams
> 82](#bounded-context-software-architecture-component-level-diagrams-2)
>
> [4.2.3.6. Bounded Context Software Architecture Code Level Diagrams
> 82](#bounded-context-software-architecture-code-level-diagrams-2)
>
> [Conexiones y Relaciones entre Contextos:
> 83](#conexiones-y-relaciones-entre-contextos)
>
> [4.2.3.6.1. Bounded Context Domain Layer Class Diagrams
> 84](#bounded-context-domain-layer-class-diagrams-2)
>
> [4.2.3.6.2. Bounded Context Database Design Diagram
> 84](#bounded-context-database-design-diagram-2)
>
> [4.2.4. Bounded Context: Autenticación de Usuarios
> 84](#bounded-context-autenticación-de-usuarios)
>
> [4.2.4.1. Domain Layer 85](#domain-layer-3)
>
> [4.2.4.2. Interface Layer 86](#interface-layer-3)
>
> [4.2.4.3. Application Layer 87](#application-layer-3)
>
> [4.2.4.4. Infrastructure Layer 87](#infrastructure-layer-3)
>
> [4.2.4.5. Bounded Context Software Architecture Component Level
> Diagrams
> 89](#bounded-context-software-architecture-component-level-diagrams-3)
>
> [4.2.4.6. Bounded Context Software Architecture Code Level Diagrams
> 89](#bounded-context-software-architecture-code-level-diagrams-3)
>
> [4.2.4.6.1. Bounded Context Domain Layer Class Diagrams
> 90](#bounded-context-domain-layer-class-diagrams-3)
>
> [4.2.4.6.2. Bounded Context Database Design Diagram
> 91](#bounded-context-database-design-diagram-3)

[Capítulo VI: Solution UX Design 91](#capítulo-v-solution-ux-design)

> [6.1. Style Guidelines 91](#style-guidelines)
>
> [6.1.1. General Style Guidelines 91](#general-style-guidelines)
>
> [6.1.2. Web, Mobile & Devices Style Guidelines
> 93](#web-mobile-devices-style-guidelines)
>
> [6.2. Information Architecture 96](#information-architecture)
>
> [6.2.2. Labeling Systems 98](#_heading=h.u74wi9s6m5hw)
>
> [6.2.3. Searching Systems 100](#searching-systems)
>
> [6.2.4. SEO Tags and Meta Tags 100](#_heading=h.g5izufmrs21)
>
> [6.2.5. Navigation Systems 102](#navigation-systems)
>
> [6.3. Landing Page UI Design 105](#landing-page-ui-design)
>
> [6.3.1. Landing Page Wireframe 106](#landing-page-wireframe)
>
> [6.3.2. Landing Page Mock-up 106](#landing-page-mock-up)
>
> [6.4. Applications UX/UI Design 107](#applications-uxui-design)
>
> [6.4.1. Application Wireframes 107](#application-wireframes)
>
> [6.4.1.2 Application Wireframes Diagrams
> 108](#application-wireflow-diagrams)
>
> [6.4.2. Applications Mock-ups 109](#applications-mock-ups)
>
> [6.4.3. Applications User Flow Diagrams
> 111](#applications-user-flow-diagrams)
>
> [6.5. Applications Prototyping 111](#applications-prototyping)

[Capítulo VII: Product Implementation, Validation & Deployment
112](#capítulo-vi-product-implementation-validation-deployment)

> [7.1. Software Configuration Management
> 112](#software-configuration-management)
>
> [7.1.1. Software Development Environment Configuration.
> 112](#software-development-environment-configuration.)
>
> [7.1.2. Source Code Management 114](#source-code-management)
>
> [7.1.3. Source Code Style Guide & Conventions
> 116](#source-code-style-guide-conventions)
>
> [7.1.4. Software Deployment Configuration
> 117](#software-deployment-configuration)
>
> [7.2. Solution Implementation
> 119](#landing-page-services-applications-implementation)
>
> [7.2.1. Sprint 1 119](#sprint-1)
>
> [7.2.1.1. Sprint Planning 1 119](#sprint-planning-1)
>
> [7.2.1.2. Sprint Backlog 1 120](#sprint-backlog-1)
>
> [7.2.1.3. Development Evidence for Sprint Review
> 121](#development-evidence-for-sprint-review)
>
> [7.2.1.4. Testing Suite Evidence for Sprint Review
> 121](#testing-suite-evidence-for-sprint-review)
>
> [7.2.1.5. Execution Evidence for Sprint Review
> 123](#execution-evidence-for-sprint-review)
>
> [7.2.1.6. Services Documentation Evidence for Sprint Review
> 124](#services-documentation-evidence-for-sprint-review)
>
> [7.2.1.7. Software Deployment Evidence for Sprint Review.
> 124](#software-deployment-evidence-for-sprint-review.)
>
> [7.2.1.8. Team Collaboration Insights during Sprint.
> 125](#team-collaboration-insights-during-sprint.)
>
> [7.2.2. Sprint 2 126](#_heading=h.278u5l2hu9tp)
>
> [7.2.2.1. Sprint Planning 2 126](#_heading=h.700plrr5kwru)
>
> [7.2.2.2. Sprint Backlog 2 126](#_heading=h.jeq5dj9zh5kr)
>
> [7.2.2.3. Development Evidence for Sprint Review
> 128](#_heading=h.ufxompwxt7dl)
>
> [7.2.2.4. Testing Suite Evidence for Sprint Review
> 129](#_heading=h.2tc1h1xg09ks)
>
> [7.2.2.5. Execution Evidence for Sprint Review
> 131](#_heading=h.grhfx9k8ykvn)
>
> [7.2.2.6. Services Documentation Evidence for Sprint Review
> 132](#_heading=h.9117u1gi6fcm)
>
> [7.2.2.7. Software Deployment Evidence for Sprint Review
> 132](#_heading=h.vet3aom34m6r)
>
> [7.3. Validation Interviews 133](#_heading=h.z74e69h5bf6r)
>
> [7.3.1. Diseño de Entrevistas 133](#_heading=h.7n1s7xd0gi38)
>
> [7.3.2. Registro de Entrevistas 133](#_heading=h.hk4ckqcuze4q)
>
> [7.3.3. Evaluaciones según Heurísticas 137](#_heading=h.in81lmsmrxec)
>
> [7.4. Video About-the-Product 139](#_heading=h.neu2irf481ne)

[Conclusiones 139](#_heading=h.ekb807e18s5x)

[Bibliografía 140](#_heading=h.27b8znkf2p6m)

[Anexos 140](#_heading=h.urqtrfzcypvb)

# Capítulo I: Introducción

## 1.1. Startup Profile {#startup-profile}

### 1.1.1. Descripción de la Startup {#descripción-de-la-startup}

En WaterGuard, nos dedicamos a revolucionar la forma en que se gestiona
y monitorea el uso del agua mediante la integración de soluciones
basadas en Internet de las Cosas (IoT). Nuestra visión es ser pioneros
en la transformación del sector de la gestión del agua, proporcionando
soluciones tecnológicas innovadoras que optimicen el monitoreo y la
emisión de notificaciones en tiempo real ante niveles críticos, ya sean
altos o bajos.

Somos un grupo de estudiantes de la Universidad Peruana de Ciencias
Aplicadas (UPC), comprometidos con el desarrollo de soluciones
tecnológicas que tengan un impacto real en las comunidades. Con
WaterGuard, buscamos facilitar el acceso a un sistema de monitoreo
hídrico moderno, accesible y adaptable.

Visión: Queremos contribuir a que el monitoreo del agua sea más práctico
y preciso, permitiendo que el 80% de las comunidades puedan gestionar
sus recursos hídricos de manera más eficiente y sostenible.

Misión: Nuestro propósito es hacer que el control del agua sea más
accesible mediante la creación de herramientas que repliquen en tiempo
real el estado de los tanques de agua, permitiendo una supervisión
efectiva desde cualquier lugar y en cualquier momento.

### 1.1.2. Perfiles de integrantes del equipo {#perfiles-de-integrantes-del-equipo}

<table>
<colgroup>
<col style="width: 71%" />
<col style="width: 28%" />
</colgroup>
<tbody>
<tr class="odd">
<td><blockquote>
<p>ALUMNO 1</p>
</blockquote></td>
<td>FOTO</td>
</tr>
<tr class="even">
<td><p>Julio Ernesto Asillo Mendoza (u20201b482) -</p>
<p>Ingeniería de Software</p>
<p>Soy una persona activa y comprometida al momento de hacer trabajos
grupales. Durante mi carrera como estudiante he adquirido conocimiento
sobre programación y trabajo en equipo, por eso siento que daré un buen
aporte a mi equipo del curso de Desarrollo de Soluciones IoT.</p></td>
<td><img src="media/image2.png"
style="width:1.4468in;height:1.85371in" /></td>
</tr>
<tr class="odd">
<td><p>Soy Diego Santivañez Filio (u202112321) - Ingeniería de
Software.</p>
<p>Estudiante de noveno ciclo de la carrera. Elegí esta carrera porque
siempre me vi interesado en la tecnología y el funcionamiento de los
distintos softwares que las personas usamos día a día las cuales son
creadas a través de la programación. Espero poder realizar un aporte
significativo a mi grupo.</p></td>
<td><img src="media/image3.png"
style="width:1.66667in;height:2.16667in" /></td>
</tr>
<tr class="even">
<td><mark>Mi nombre es Kevin Oliva Alva, actualmente me encuentro
avanzando en el 10mo ciclo de la carrera de Ingeniería de Software en la
universidad UPC (Universidad Peruana de Ciencias Aplicadas), además soy
consultor semi-senior de RPA con Automation Anywhere. Creo firmemente
que el éxito en proyectos grupales depende en gran medida de la
capacidad de cada miembro para aprovechar sus fortalezas y
complementarse para cubrir sus debilidades.</mark></td>
<td><img src="media/image4.png"
style="width:1.66667in;height:2.22222in" /></td>
</tr>
<tr class="odd">
<td><p>Santos Alexis Patazca Calderón (u20201c269) -</p>
<p>Ingeniería de Software</p>
<p>Me considero una persona proactiva con pensamiento estratégico, con
habilidades en el ámbito de la programación y un gran espíritu
investigador. Para este proyecto puedo aportar parte de mi conocimiento
adquirido en el curso. Además, de las habilidades blandas tales como el
trabajo en equipo, comunicación, entre otras.</p></td>
<td><img src="media/image5.png"
style="width:1.66667in;height:1.91667in" /></td>
</tr>
<tr class="even">
<td><p>Leonel Alfaro Cumba(u20201a930)</p>
<p>Ingeniería de Software</p>
<p>Soy un estudiante apasionado por la tecnología y por entender cómo
funcionan los software que usamos a diario. Mi interés por la
programación me ha permitido profundizar tanto en conocimientos técnicos
como en dinámicas de trabajo en equipo. Me considero plenamente
comprometido con los proyectos colaborativos, cualidad con la que confío
en aportar un valor significativo a cualquier grupo de trabajo.</p></td>
<td><img src="media/image6.jpg"
style="width:1.66667in;height:1.82292in" /></td>
</tr>
<tr class="odd">
<td><p><mark>Carlos Arian Ramirez Mendoza (u202020108)</mark></p>
<p><mark>Estudiante de Ingeniería de Software. Me gusta el desarrollo de
productos de software que generen y aporten valor para quienes lo
necesitan. Me interesa también el emprendimiento y el trabajo en equipo.
Actualmente realizo mis prácticas en una reconocida entidad bancaria
como auditor de TI. Siempre busco la mejora continua de mis habilidades
técnicas y blandas, así como salir de mi zona de
confort.</mark></p></td>
<td><img src="media/image7.jpg"
style="width:1.66667in;height:1.66667in" /></td>
</tr>
</tbody>
</table>

## 1.2. Solution Profile {#solution-profile}

### 1.2.1 Antecedentes y problemática {#antecedentes-y-problemática}

What? (Qué)

El problema detectado es la falta de monitoreo preciso y en tiempo real
del nivel de agua en los tanques en comunidades rurales, lo que conduce
a desperdicios o a la falta de agua en momentos críticos para estas
poblaciones vulnerables.

When? (Cuándo)

El problema sucede cuando la necesidad de monitoreo continuo y eficiente
es constante, especialmente en momentos de escasez de agua,
mantenimiento de infraestructura, o cuando se requiere una gestión
eficiente de los recursos.

Where? (Dónde)

Esta solución se aplica específicamente en comunidades rurales de Perú,
donde la gestión del agua es crítica debido a la infraestructura
limitada y el acceso reducido a servicios básicos

Who? (Quién)

Comunidades rurales, juntas de agua locales, organizaciones no
gubernamentales que trabajan en zonas rurales, y entidades
gubernamentales responsables de la gestión hídrica en áreas rurales.

Why? (Por qué)

Es crucial para optimizar el uso del agua, prevenir desperdicios, y
asegurar la disponibilidad de este recurso vital en todo momento.
También contribuye a la sostenibilidad y al uso responsable de los
recursos naturales.

How?

Utilizando sensores IoT de bajo costo y bajo mantenimiento adaptados a
las condiciones rurales, que recopilan datos del nivel de agua en
tanques y los envían a una plataforma de monitoreo simple y accesible.
El sistema incluye alertas tempranas y funciona con conectividad
limitada, teniendo en cuenta las restricciones de infraestructura
tecnológica en estas zonas.

How much? (¿Cuánto cuesta o qué recursos se necesitan?)

La problemática del agua en Perú es alarmante, y las estadísticas
revelan la magnitud del desafío. Según la página de Rotoplas (2024),
aproximadamente el 10% de la población peruana, equivalente a 3,3
millones de personas, no tiene acceso a una red pública de agua, y el
23% (6,4 millones) carece de conexiones de alcantarillado. Además, solo
el 62% de las aguas negras reciben un tratamiento adecuado. Esto implica
que una gran parte de la población recurre a la compra de agua a
camiones cisterna, pagando hasta el doble del precio del agua de red, lo
que genera problemas de acceso y salubridad.

Además, el Instituto Nacional de Estadística e Informática (INEI)
informó en 2024 que el 73,7% de los peruanos no tiene acceso a agua de
manera segura. Esto significa que más de dos tercios de la población
carecen de acceso continuo a agua potable desde fuentes confiables como
redes públicas, pilones o pilas, o no tienen suministro disponible las
24 horas del día. En áreas rurales, esta situación es aún más crítica,
con un 97,5% de la población sin acceso a agua gestionada de manera
segura, en comparación con un 67,8% en áreas urbanas (Infobae, 2024).

Estas estadísticas reflejan la severidad de la escasez de agua y la
falta de acceso seguro en el Perú, subrayando la urgencia de soluciones
innovadoras como las propuestas por WaterGuard para mejorar la gestión y
el monitoreo del agua, y así optimizar su uso y distribución en todo el
país.

Antecedentes:

En Perú, la gestión del agua es un desafío creciente debido a la
distribución desigual de recursos hídricos y la falta de infraestructura
adecuada. La mayor parte del agua se encuentra en la cuenca amazónica,
una región con baja densidad de población. En contraste, la costa árida,
que alberga a la mayoría de la población y la actividad económica del
país, enfrenta una severa escasez de agua. Este desequilibrio, combinado
con una infraestructura deficiente y una gestión ineficiente, ha
resultado en problemas significativos de acceso al agua potable y
servicios de alcantarillado.

Problemática a resolver:

La problemática central que WaterGuard busca resolver es la falta de un
monitoreo eficiente y en tiempo real de los niveles de agua en los
tanques específicamente en comunidades rurales de Perú, donde el 97,5%
de la población no tiene acceso a agua gestionada de manera segura. Esta
carencia de monitoreo conduce a una gestión ineficiente de los recursos
hídricos limitados, resultando en desperdicio de agua, riesgos de
escasez y falta de respuesta rápida ante emergencias. Además, estas
comunidades dependen frecuentemente de soluciones temporales y costosas
como camiones cisterna, exacerbando los problemas de salud pública y
sostenibilidad.

WaterGuard ofrece una solución innovadora mediante la implementación de
tecnología IoT para habilitar un monitoreo remoto y automatizado que
optimiza el uso del agua, previene pérdidas y mejora la sostenibilidad
del sistema, contribuyendo a una distribución más equitativa de este
recurso vital en todo el país.

### 1.2.2 Lean UX Process {#lean-ux-process}

#### 1.2.2.1. Lean UX Problem Statements {#lean-ux-problem-statements}

Problem Statement 1  
En Perú, las comunidades rurales enfrentan una gestión ineficiente del
agua debido a la falta de tecnologías adecuadas y accesibles para el
monitoreo y control de los niveles de agua en tanques y sistemas de
distribución. Esta ineficiencia se traduce en un uso deficiente del
recurso, provocando desperdicio en algunas épocas mientras sufren de
escasez crítica en otras. Además, la limitada infraestructura
tecnológica y de comunicaciones en estas zonas impide la implementación
de soluciones convencionales y la toma de decisiones rápidas por parte
de los administradores locales de recursos hídricos.

Como resultado, estas comunidades rurales enfrentan desafíos
significativos: costos elevados por la compra de agua de camiones
cisterna, largas distancias para acceder a fuentes de agua, problemas de
salud pública debido a la falta de acceso a agua segura y riesgos
ambientales por el mal manejo del recurso hídrico. Existe una necesidad
clara de una solución tecnológica adaptada a las condiciones rurales que
permita un monitoreo y control eficiente del agua con requisitos mínimos
de conectividad e infraestructura.

¿Cómo desarrollar una solución tecnológica basada en IoT y gemelos
digitales que sea accesible, de bajo costo y fácil mantenimiento, que
permita un monitoreo preciso de los niveles de agua, optimizando el uso
del recurso y mejorando la gestión hídrica específicamente en
comunidades rurales de Perú?

Problem Statement 2

En Perú, el 73,7% de la población no tiene acceso a agua gestionada de
manera segura, especialmente en áreas rurales donde esta cifra se eleva
al 97,5%. Esta situación es resultado de una infraestructura deficiente,
la falta de monitoreo en tiempo real y una distribución desigual de los
recursos hídricos. Las personas en estas áreas dependen de soluciones
alternativas y costosas para acceder al agua, como la compra de agua a
proveedores externos, lo cual no garantiza ni la seguridad ni la
continuidad del suministro.

La falta de acceso a agua segura genera costos adicionales
desproporcionados para las familias rurales, aumenta los riesgos de
enfermedades y afecta significativamente su calidad de vida y
productividad agrícola. Para abordar esta problemática, es necesario
desarrollar una solución tecnológica específicamente adaptada a las
condiciones rurales, con bajo costo, fácil instalación y mantenimiento,
que facilite el monitoreo y control del agua de manera eficiente y
segura en estas áreas vulnerables.

¿Cómo implementar un sistema de monitoreo y control de agua en tiempo
real que sea sostenible en entornos rurales con conectividad limitada,
que asegure un acceso más seguro y eficiente al agua, reduciendo los
costos y riesgos asociados con la gestión inadecuada del recurso en
comunidades rurales de Perú?

#### 1.2.2.2. Lean UX Assumptions {#lean-ux-assumptions}

Business Assumptions

Creo que mis clientes necesitan una solución eficiente para monitorear y
gestionar los recursos hídricos en tiempo real.

Estas necesidades se pueden resolver con un sistema basado en IoT y
gemelos digitales que proporcione datos en tiempo real y control remoto
de recursos hídricos.

Mis clientes iniciales son exclusivamente comunidades rurales, juntas de
agua locales en zonas rurales, y organizaciones no gubernamentales que
trabajan en áreas rurales de Perú.

El valor \#1 que un cliente quiere de mi servicio es la capacidad de
optimizar el uso del agua y reducir costos asociados al desperdicio del
recurso.

El cliente también puede obtener estos beneficios adicionales: reducción
de costos operativos, mejoras en la planificación de recursos, mayor
sostenibilidad y un mejor manejo de emergencias relacionadas con el
agua.

Voy a adquirir la mayoría de mis clientes a través de asociaciones con
gobiernos locales, ONGs que trabajan en desarrollo rural, programas de
capacitación comunitaria, y demostraciones directas en comunidades
rurales.

Haré dinero a través de tarifas de instalación y mantenimiento de
dispositivos IoT, y licencias de uso del software.

Mi competencia principal en el mercado serán empresas que ofrecen
soluciones tradicionales de monitoreo de agua o tecnologías básicas de
control de recursos hídricos.

Los venceremos debido a la innovación de nuestra tecnología en tiempo
real, la facilidad de uso de nuestra plataforma, y la capacidad de
integrar datos de múltiples fuentes en un solo sistema.

Mi mayor riesgo de producto es la limitada infraestructura tecnológica y
de conectividad en comunidades rurales, así como posibles restricciones
presupuestarias para la implementación inicial.

Resolveremos esto a través de programas de capacitación, demostraciones
gratuitas y pruebas piloto que demuestren el valor y la efectividad de
nuestra solución.

User Assumptions

¿Quién es el usuario?

Comunidades rurales, específicamente líderes comunitarios, operadores
locales de sistemas de agua, y miembros de juntas rurales de agua.

¿Dónde encaja nuestro producto en su trabajo o vida?

El producto encaja en la gestión diaria del suministro de agua en
comunidades rurales, permitiendo a los usuarios monitorear y controlar
los niveles de agua con tecnología adaptada a sus condiciones,
optimizando el uso del recurso escaso, y respondiendo rápidamente a
emergencias sin depender de visitas presenciales constantes a los
tanques de almacenamiento.

¿Qué problemas tiene nuestro producto? ¿Resolver?

Nuestro producto resuelve problemas de gestión ineficiente del agua,
falta de monitoreo en tiempo real, desperdicio del recurso y costos
elevados asociados a la compra de agua de fuentes externas.

¿Cuándo y cómo es nuestro producto usado?

El producto es usado diariamente por administradores y usuarios para
monitorear y controlar los niveles de agua en tanques y sistemas de
distribución a través de una plataforma digital accesible desde
cualquier dispositivo con conexión a internet.

#### 1.2.2.3. Lean UX Hypothesis Statements {#lean-ux-hypothesis-statements}

1.  Creemos que al implementar un sistema de monitoreo en tiempo real
    para los niveles de agua en tanques y sistemas de distribución,
    reduciremos el desperdicio de agua en un 20% en las comunidades que
    utilicen nuestro producto.

> Sabremos que hemos tenido éxito cuando veamos una disminución del
> desperdicio de agua reportado por los administradores de recursos
> hídricos y un aumento en la eficiencia del uso del agua en las
> comunidades.

2.  Creemos que proporcionar alertas automáticas sobre niveles críticos
    de agua y posibles fugas aumentará la capacidad de respuesta de los
    usuarios ante emergencias relacionadas con el agua en un 30%.

> Sabremos que esto es cierto si vemos una mejora en los tiempos de
> respuesta ante emergencias y una reducción de daños relacionados con
> fugas de agua en los primeros tres meses de uso.

3.  Creemos que integrar datos históricos y análisis predictivo en
    nuestra plataforma ayudará a los administradores a planificar mejor
    el suministro de agua y reducirá los costos operativos en un 15%.

> Sabremos que hemos tenido éxito cuando los usuarios reporten una
> planificación más eficiente del suministro de agua y una reducción en
> los costos asociados con la compra y distribución de agua.

4.  Creemos que desarrollar una interfaz de usuario intuitiva y fácil de
    usar mejorará la adopción del producto por parte de los usuarios en
    un 40% en las primeras seis semanas de lanzamiento.

> Sabremos que esto es cierto si las encuestas de satisfacción del
> usuario muestran una alta puntuación en facilidad de uso y si la tasa
> de adopción del producto supera nuestras expectativas iniciales.

5.  Creemos que ofrecer capacitación directa en las comunidades y un
    sistema con mínimos requisitos técnicos aumentará la tasa de
    adopción del producto en un 50% dentro de los primeros seis meses en
    comunidades rurales.

> Sabremos que hemos tenido éxito cuando veamos un aumento significativo
> en el número de comunidades rurales que adoptan nuestra solución y se
> convierten en usuarios de pago después del período de demostración.

6.  Creemos que desarrollar un sistema que funcione con conectividad
    intermitente o limitada permitirá que comunidades rurales con
    infraestructura de comunicaciones deficiente puedan beneficiarse de
    nuestra solución, ampliando nuestro mercado en un 30%.

> Sabremos que esto es cierto cuando veamos una adopción significativa
> de nuestra solución en comunidades rurales que anteriormente no podían
> implementar sistemas de monitoreo debido a problemas de conectividad.

#### 1.2.2.4. Lean UX Canvas {#lean-ux-canvas}

<table>
<colgroup>
<col style="width: 31%" />
<col style="width: 29%" />
<col style="width: 38%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Problema del Negocio</p>
<p>El problema principal del negocio es la ineficiencia en la gestión
del agua y el desperdicio significativo que ocurre específicamente en
comunidades rurales. Estas comunidades carecen de acceso seguro y
continuo al agua, y enfrentan costos elevados por soluciones temporales.
Solucionar estos problemas mediante una tecnología adaptada a entornos
rurales que permita una gestión más eficiente y sostenible del agua es
fundamental para el éxito del negocio.</p></td>
<td rowspan="2"><blockquote>
<p>Soluciones</p>
</blockquote>
<p>Implementar una plataforma digital de bajo costo y mantenimiento
mínimo que use tecnologías IoT adaptadas a entornos rurales para ofrecer
monitoreo en tiempo real, alertas automáticas y análisis predictivo
básico. El sistema funcionará con conectividad intermitente y será fácil
de instalar y mantener por los propios miembros de la comunidad,
permitiéndoles optimizar el uso del agua, detectar fugas y planificar
mejor los recursos hídricos.</p></td>
<td><p>Resultados del negocio</p>
<p>Los resultados esperados para el negocio incluyen el aumento de la
eficiencia en la gestión del agua por parte de los clientes, la
reducción de costos operativos relacionados con el consumo de agua, y la
generación de ingresos sostenibles mediante la venta y suscripción de la
plataforma WaterGuard a empresas y comunidades.</p></td>
</tr>
<tr class="even">
<td><p>Usuarios y Clientes</p>
<p>Comunidades rurales: Habitantes de áreas con acceso limitado a agua
que buscan una solución para monitorear y gestionar mejor el recurso
hídrico disponible. Incluye juntas de agua rurales, líderes comunitarios
y operadores locales de sistemas de agua que necesitan optimizar la
gestión con recursos limitados.</p></td>
<td><p>Resultados del usuario</p>
<p>Los usuarios deberían experimentar un mejor acceso al agua, una
reducción significativa del desperdicio de este recurso y mayor control
sobre su consumo. Esto se traducirá en ahorros de costos, mejoras en la
sostenibilidad ambiental y una mayor satisfacción general con la gestión
de recursos hídricos.</p></td>
</tr>
<tr class="odd">
<td><p>Hypothesis</p>
<p>1. Creemos que al implementar un sistema de monitoreo en tiempo real
para los niveles de agua en tanques y sistemas de distribución,
reduciremos el desperdicio de agua en un 20% en las comunidades que
utilicen nuestro producto.</p>
<p>2. Creemos que proporcionar alertas automáticas sobre niveles
críticos de agua y posibles fugas aumentará la capacidad de respuesta de
los usuarios ante emergencias relacionadas con el agua en un 30%.</p>
<p>3. Creemos que integrar datos históricos y análisis predictivo básico
en nuestra plataforma ayudará a las juntas de agua y líderes
comunitarios rurales a planificar mejor el suministro de agua y reducirá
los costos operativos en un 15%.</p>
<p>4. Creemos que desarrollar una interfaz de usuario intuitiva y fácil
de usar mejorará la adopción del producto por parte de los usuarios en
un 40% en las primeras seis semanas de lanzamiento.</p>
<p>5. Creemos que diseñar un sistema que funcione con mínimos
requerimientos de infraestructura (energía solar, conectividad
intermitente) permitirá la adopción en comunidades rurales remotas,
expandiendo nuestro impacto a zonas tradicionalmente excluidas de
soluciones tecnológicas.</p></td>
<td><p>¿Qué es lo más importante que necesitamos aprender primero?</p>
<ul>
<li><p>Necesitamos aprender si las empresas y comunidades rurales están
dispuestas a adoptar nuestra solución de monitoreo de agua en tiempo
real y si encuentran valor en las alertas automáticas y la optimización
del uso del agua.</p></li>
</ul></td>
<td><p>¿Cuál es la menor cantidad de trabajo que necesitamos hacer para
resolver dudas y para hacer lo más importante?</p>
<p>Lo mínimo que necesitamos hacer es desarrollar una versión mínima
viable del producto (MVP) que incluya las funciones básicas de monitoreo
en tiempo real y alertas automáticas. Luego, realizar pruebas piloto con
empresas y comunidades rurales para recopilar feedback inicial y validar
la propuesta de valor.</p></td>
</tr>
</tbody>
</table>

## 1.3. Segmentos objetivo {#segmentos-objetivo}

Comunidades Rurales

Las comunidades rurales a menudo enfrentan desafíos en el acceso al agua
segura debido a la falta de infraestructura adecuada y recursos
limitados. Estas comunidades necesitan una forma de gestionar mejor el
agua disponible para asegurar un suministro constante y seguro. Nuestra
solución les ofrecerá un sistema fácil de usar para monitorear los
niveles de agua en tiempo real y gestionar el uso de este recurso de
manera eficiente, reduciendo el desperdicio y mejorando la calidad de
vida de los residentes.

![](media/image8.png){width="2.9825820209973752in" height="2.21875in"}

# Capítulo II: Requirements Elicitation & Analysis {#capítulo-ii-requirements-elicitation-analysis}

## 2.1. Competidores {#competidores}

- Suez Smart Solutions: Es una empresa multinacional francesa con una
  larga historia en el sector del agua y la gestión de residuos. Suez
  Smart Solutions es una división de Suez que se especializa en
  soluciones tecnológicas avanzadas para la gestión de recursos
  hídricos. La empresa utiliza tecnologías como IoT (Internet de las
  Cosas), análisis de datos y sistemas de control en tiempo real para
  optimizar el uso del agua y mejorar la eficiencia en la gestión de
  redes de suministro de agua y tratamiento de aguas residuales.

- Xylem Inc: Es una empresa estadounidense que se especializa en la
  tecnología del agua, ofreciendo soluciones innovadoras para el manejo
  y tratamiento de agua y aguas residuales. Xylem se destaca por su
  enfoque en la sostenibilidad y la eficiencia energética, desarrollando
  productos y sistemas que ayudan a mejorar la distribución, el
  tratamiento y el uso eficiente del agua.

- Veolia Water Technologies: Es una subsidiaria de Veolia Environnement,
  una multinacional francesa que es un líder global en la gestión del
  agua, residuos y energía. Veolia Water Technologies se enfoca en el
  diseño y la provisión de soluciones tecnológicas para el tratamiento
  de agua y aguas residuales. La empresa ofrece una amplia gama de
  servicios que incluyen la ingeniería de sistemas de tratamiento de
  agua, soluciones de gestión de recursos hídricos, y productos químicos
  para el tratamiento del agua.

- Siemens Water Solutions: Es una división de Siemens, una de las
  mayores empresas de ingeniería y tecnología del mundo, con sede en
  Alemania. Siemens Water Solutions se enfoca en ofrecer tecnologías
  avanzadas para la automatización y control de sistemas de gestión del
  agua. Siemens integra sus soluciones de automatización con tecnologías
  de tratamiento de agua para optimizar el uso del agua, mejorar la
  eficiencia energética, y asegurar un suministro constante y seguro en
  infraestructuras críticas.

### 2.1.1. Análisis competitivo {#análisis-competitivo}

<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 12%" />
<col style="width: 18%" />
<col style="width: 18%" />
<col style="width: 18%" />
<col style="width: 19%" />
</colgroup>
<tbody>
<tr class="odd">
<td rowspan="2">¿Por qué llevar a cabo este análisis?</td>
<td colspan="5">¿De qué manera nos ayuda a analizar las características
que el usuario busca de una plataforma como la nuestra?</td>
</tr>
<tr class="even">
<td colspan="5">Nos permite adaptarnos y mejorar en aspectos diferentes
a los rivales lo que nos ayudará a destacar y atraer público</td>
</tr>
<tr class="odd">
<td colspan="2">Competidores</td>
<td>Suez Smart Solutions</td>
<td>Xylem Inc</td>
<td>Veolia Water</td>
<td>Siemens Water</td>
</tr>
<tr class="even">
<td rowspan="3">Perfil</td>
<td>Overview</td>
<td rowspan="2"><img src="media/image9.png"
style="width:0.70313in;height:0.70313in" /></td>
<td><img src="media/image10.png"
style="width:0.96875in;height:0.97222in" /></td>
<td><img src="media/image11.png"
style="width:0.95833in;height:0.95833in" /></td>
<td><img src="media/image12.png"
style="width:0.95833in;height:0.31944in" /></td>
</tr>
<tr class="odd">
<td rowspan="2"><p>Ventaja Competitiva</p>
<p>¿Qué valor ofrece a los clientes?</p></td>
<td rowspan="2">Empresa líder en tecnología del agua que combina
hardware robusto con software intuitivo para una gestión eficiente y
automatizada de los recursos hídricos.</td>
<td rowspan="2">Soluciones integrales para el tratamiento y la gestión
del agua, con un enfoque en la calidad y la sostenibilidad mediante la
integración de IoT y tecnologías avanzadas de tratamiento de agua.</td>
<td rowspan="2">Siemens integra tecnología avanzada en sus sistemas de
automatización y control de recursos hídricos, con un enfoque en
eficiencia energética y reducción de costos operativos.</td>
</tr>
<tr class="even">
<td>Ofrece soluciones avanzadas de monitoreo y gestión de recursos
hídricos a través de plataformas IoT, con un enfoque en control en
tiempo real y análisis predictivo.</td>
</tr>
<tr class="odd">
<td rowspan="3">Perfil del Marketing</td>
<td>Mercado objetivo</td>
<td rowspan="2">Suez Smart Solutions se enfoca en grandes empresas,
municipalidades, y organizaciones gubernamentales que gestionan redes de
agua complejas. Su mercado principal incluye ciudades con necesidades de
infraestructura avanzada y empresas que buscan cumplir con regulaciones
ambientales estrictas.</td>
<td>Xylem Inc. apunta a industrias, proveedores de servicios públicos y
gobiernos que necesitan gestionar y optimizar el uso del agua en gran
escala</td>
<td>Veolia se dirige a clientes industriales, urbanos y agrícolas que
requieren soluciones de alta tecnología para la gestión del agua.</td>
<td>Siemens se dirige a industrias pesadas, plantas de energía, y
grandes proveedores de servicios públicos que requieren una gestión
integral del agua y la energía</td>
</tr>
<tr class="even">
<td rowspan="2">Estrategias de Marketing</td>
<td rowspan="2">Xylem utiliza estrategias de marketing basadas en la
educación del cliente, incluyendo webinars, talleres y publicaciones
técnicas.</td>
<td rowspan="2">La estrategia de marketing de Veolia se centra en su
reputación global y su capacidad para ofrecer soluciones personalizadas.
Participan activamente en licitaciones públicas y privadas.</td>
<td rowspan="2">Siemens utiliza una estrategia de marketing basada en la
innovación y la calidad, destacando sus avances tecnológicos y su
capacidad para integrar soluciones complejas.</td>
</tr>
<tr class="odd">
<td>Suez utiliza una combinación de participación en ferias y eventos
del sector, colaboración con gobiernos locales y contenido técnico de
alta calidad</td>
</tr>
<tr class="even">
<td rowspan="5">Perfil del producto</td>
<td rowspan="2">Productos y Servicios</td>
<td rowspan="2"><p>AQUADVANCED®: Plataforma de monitoreo y gestión de
agua en tiempo real.</p>
<p>ON'connect™: Solución IoT para la medición inteligente de agua.</p>
<p>Consultoría y Servicios de Optimización: Asesoría especializada en la
gestión eficiente de redes de agua.</p></td>
<td rowspan="2"><p>Flygt SmartRun®: Sistema de control inteligente para
estaciones de bombeo.</p>
<p>Sensus iPERL®: Contadores de agua con tecnología IoT para medición
avanzada.</p>
<p>Leopold® Filterworx: Soluciones de filtración y tratamiento de
agua.</p></td>
<td rowspan="2"><p>Aquavista™: Plataforma de gestión inteligente de agua
que integra IoT y análisis de datos.</p>
<p>Actiflo®: Sistema avanzado de clarificación de agua para plantas de
tratamiento.</p>
<p>HYDREX™: Gama de productos químicos para el tratamiento de
agua.</p></td>
<td rowspan="2"><p>SIPROCESS GA700: Solución de automatización para
plantas de tratamiento de agua.</p>
<p>SIMATIC PCS 7: Sistema de control de procesos para la gestión
integral del agua.</p>
<p>Soluciones de Energía Híbrida: Sistemas que integran energía
renovable para el suministro de agua.</p></td>
</tr>
<tr class="odd">
</tr>
<tr class="even">
<td>Precios y Costos</td>
<td>Un proyecto típico podría oscilar entre $10,000 y $500,000
dependiendo de la complejidad.</td>
<td>Un proyecto podría variar desde $20,000 hasta varios millones de
dólares, dependiendo del alcance.</td>
<td>Los proyectos pueden costar desde $50,000 hasta millones,
dependiendo de la complejidad.</td>
<td>Un proyecto puede variar desde $100,000 hasta varios millones de
dólares.</td>
</tr>
<tr class="odd">
<td rowspan="2">Canales de distribución (Web y/o Móvil)</td>
<td rowspan="2"><p>Ventas Directas: A través de su equipo de ventas
especializado.</p>
<p>Asociaciones con Gobiernos Locales: Implementación de soluciones en
áreas municipales</p></td>
<td rowspan="2"><p>Distribuidores Globales: Red de distribuidores y
revendedores en más de 150 países.</p>
<p>Consultoría Directa: Implementación y soporte directamente a través
de Xylem.</p></td>
<td rowspan="2"><p>Contratos Públicos: Participación en licitaciones
públicas y privadas.</p>
<p>Consultoría Directa: A través de su red global de consultores e
ingenieros.</p></td>
<td rowspan="2"><p>Ventas Directas: A través de su fuerza de ventas
global y oficinas regionales.</p>
<p>Distribuidores Autorizados: Red de partners y distribuidores
especializados en automatización.</p></td>
</tr>
<tr class="even">
</tr>
<tr class="odd">
<td rowspan="5">Análisis SWOT</td>
<td colspan="5">Desarrollo del startup y competidores, mediante sus
fortalezas que deberían apoyar sus oportunidades y de la misma manera
contribuir a lo que se define como posibles ventajas competitivas.</td>
</tr>
<tr class="even">
<td>Fortalezas</td>
<td><p>Amplia experiencia en la gestión de recursos hídricos y
soluciones de infraestructura.</p>
<p>Tecnología avanzada en monitoreo en tiempo real y análisis
predictivo.</p>
<p>Fuerte presencia global con proyectos en diversas regiones del
mundo.</p>
<p>Capacidad para integrar soluciones personalizadas en infraestructuras
existentes.</p></td>
<td><p>Amplia gama de productos y soluciones que cubren todas las
necesidades de gestión del agua.</p>
<p>Fuerte enfoque en innovación tecnológica y eficiencia energética.</p>
<p>Red global de distribución que asegura un alcance amplio y un
servicio técnico sólido.</p>
<p>Reputación consolidada en el mercado del agua y servicios
públicos.</p></td>
<td><p>Posición de liderazgo en soluciones de tratamiento de agua y
gestión sostenible.</p>
<p>Experiencia en grandes proyectos de infraestructura y capacidad para
personalizar soluciones según las necesidades del cliente.</p>
<p>Fuerte enfoque en la sostenibilidad y cumplimiento de normativas
ambientales.</p>
<p>Amplia gama de productos químicos y tecnologías de tratamiento de
agua.</p></td>
<td><p>Fuerte capacidad de innovación y desarrollo en soluciones de
automatización y control de recursos hídricos.</p>
<p>Integración de soluciones energéticamente eficientes que reducen los
costos operativos de los clientes.</p>
<p>Reputación sólida y confiabilidad en la industria, respaldada por una
marca global fuerte.</p>
<p>Capacidad para ofrecer soluciones llave en mano que cubren desde el
diseño hasta la implementación completa.</p></td>
</tr>
<tr class="odd">
<td>Oportunidades</td>
<td><p>Expansión en mercados emergentes con necesidades críticas de
gestión del agua.</p>
<p>Desarrollo de nuevas soluciones basadas en tecnologías emergentes
como la inteligencia artificial y machine learning.</p>
<p>Creciente demanda de soluciones sostenibles y respetuosas con el
medio ambiente.</p>
<p>Asociaciones con gobiernos y organizaciones internacionales para
grandes proyectos de infraestructura.</p></td>
<td><p>Aumento de la demanda de tecnologías sostenibles y
energéticamente eficientes.</p>
<p>Crecimiento en mercados emergentes con infraestructuras en
desarrollo.</p>
<p>Expansión en el mercado de IoT y soluciones de ciudades
inteligentes.</p>
<p>Oportunidades para establecer asociaciones estratégicas con otros
actores de la industria tecnológica.</p></td>
<td><p>Creciente preocupación por la sostenibilidad y el cumplimiento de
regulaciones ambientales que impulsa la demanda de sus soluciones.</p>
<p>Expansión en mercados en desarrollo con necesidades críticas de
tratamiento de agua.</p>
<p>Oportunidades de innovación en el tratamiento de aguas residuales y
reciclaje de agua.</p>
<p>Creciente demanda de soluciones integradas que combinen tratamiento y
gestión de recursos hídricos.</p></td>
<td><p>Creciente demanda de soluciones de automatización y control en
infraestructuras de agua.</p>
<p>Expansión en mercados de energías renovables y sostenibilidad, donde
la gestión eficiente del agua es crucial.</p>
<p>Desarrollo de soluciones híbridas que integren energías renovables y
gestión del agua.</p>
<p>Potencial para alianzas estratégicas en proyectos de infraestructura
a gran escala.</p></td>
</tr>
<tr class="even">
<td>Debilidades</td>
<td><p>Alto costo de implementación, lo que puede limitar su acceso a
pequeñas empresas o comunidades con recursos limitados.</p>
<p>Dependencia de proyectos a gran escala que requieren largos ciclos de
venta y desarrollo.</p>
<p>Posible rigidez en la adaptación de soluciones para mercados locales
con infraestructuras menos avanzadas.</p></td>
<td><p>Competencia en precios con actores locales o empresas más
pequeñas que ofrecen soluciones más económicas.</p>
<p>Complejidad en la implementación de sus soluciones, lo que puede ser
un obstáculo para clientes con menos recursos técnicos.</p>
<p>Alta dependencia de la venta de hardware, lo que puede limitar la
flexibilidad en modelos de negocio basados en software.</p></td>
<td><p>Altos costos operativos y de implementación que pueden limitar su
acceso a ciertos mercados.</p>
<p>Dependencia de proyectos a gran escala que pueden verse afectados por
cambios en el financiamiento o políticas gubernamentales.</p>
<p>Complejidad en la gestión de soluciones químicas y de tratamiento que
requieren un alto nivel de especialización.</p></td>
<td><p>Alto costo de sus soluciones, lo que puede ser prohibitivo para
pequeños y medianos clientes.</p>
<p>Complejidad en la integración de sistemas, lo que requiere un alto
nivel de personalización y soporte técnico.</p>
<p>Dependencia de la venta de soluciones complejas que pueden tener
largos ciclos de venta e implementación.</p></td>
</tr>
<tr class="odd">
<td>Amenazas</td>
<td><p>ompetencia de empresas más pequeñas y ágiles que ofrecen
soluciones más económicas.</p>
<p>Cambios en las regulaciones gubernamentales que podrían afectar su
capacidad para operar en ciertos mercados.</p>
<p>Dependencia de clientes grandes y proyectos gubernamentales que
pueden verse afectados por cambios políticos.</p></td>
<td><p>Rápido avance tecnológico de nuevos competidores que pueden
ofrecer soluciones más avanzadas o disruptivas.</p>
<p>Riesgos regulatorios y cambios en las políticas ambientales que
pueden afectar el desarrollo de proyectos.</p>
<p>Presión de costos en mercados altamente competitivos, lo que puede
reducir los márgenes de ganancia.</p></td>
<td><p>Competencia de nuevas empresas con soluciones innovadoras y más
económicas.</p>
<p>Cambios en las regulaciones internacionales que podrían impactar su
modelo de negocio.</p>
<p>Fluctuaciones en el costo de los insumos químicos utilizados en sus
procesos de tratamiento.</p></td>
<td><p>Avance de competidores con soluciones más asequibles y fáciles de
implementar.</p>
<p>Riesgos asociados a la dependencia de grandes proyectos
gubernamentales e industriales.</p>
<p>Vulnerabilidad a cambios en las políticas energéticas y ambientales
que podrían impactar su oferta de productos.</p></td>
</tr>
</tbody>
</table>

###   {#section}

### 2.1.2. Estrategias y tácticas frente a competidores {#estrategias-y-tácticas-frente-a-competidores}

Innovación en Usabilidad:

- Estrategia: Desarrollar una plataforma extremadamente intuitiva y
  fácil de usar específicamente diseñada para comunidades rurales con
  diferentes niveles de alfabetización digital.

- Táctica: Invertir en diseño UX/UI centrado en usuarios rurales, con
  interfaces visuales simples, instrucciones claras en lenguaje local y
  mínima necesidad de texto. Ofrecer una aplicación móvil que funcione
  con conexión intermitente y capacitación comunitaria para su uso.

Personalización y Flexibilidad:

- Estrategia: Ofrecer soluciones altamente personalizables que se
  adapten a las necesidades específicas de cada cliente, desde pequeñas
  instalaciones hasta grandes infraestructuras.

- Táctica: Implementar módulos adicionales que los clientes puedan
  agregar según sus necesidades, como análisis predictivo y gestión de
  calidad del agua.

Optimización de Costos de Implementación:

- Estrategia: Reducir los costos iniciales para las comunidades rurales
  a través de soluciones extremadamente económicas, de bajo
  mantenimiento y que puedan funcionar con infraestructura mínima.

- Táctica: Desarrollar kits de instalación IoT de bajo costo que los
  propios miembros de la comunidad puedan configurar, con componentes
  resistentes a condiciones adversas y manuales visuales paso a paso.
  Incluir opciones de alimentación por energía solar para zonas sin
  electricidad estable.

Marketing Educativo:

- Estrategia: Implementar una campaña de marketing que eduque al mercado
  sobre la importancia del monitoreo en tiempo real de recursos hídricos
  y los beneficios de la tecnología IoT.

- Táctica: Crear webinars, whitepapers, y casos de estudio que
  demuestran cómo WaterGuard puede mejorar la eficiencia y reducir
  costos. Establecer un blog corporativo para posicionarse como líder de
  opinión en la gestión de recursos hídricos.

## 2.2. Entrevistas {#entrevistas}

### 2.2.1. Diseño de entrevistas {#diseño-de-entrevistas}

Preguntas Iniciales: Información Básica

1.  ¿Cuál es su nombre?

    - Objetivo: Identificar al entrevistado.

2.  ¿Cuál es su edad?

    - Objetivo: Recopilar datos demográficos que puedan influir en la
      percepción y adopción de la tecnología.

3.  ¿Cuál es su rol o cargo dentro de su organización/comunidad?

    - Objetivo: Entender la responsabilidad específica del entrevistado
      en la gestión del agua o infraestructura.

4.  ¿Cuánto tiempo lleva en su cargo actual?

    - Objetivo: Evaluar la experiencia del entrevistado en la gestión
      del agua y otros recursos.

5.  ¿En qué región o localidad está ubicada su organización/comunidad?

    - Objetivo: Contextualizar la situación geográfica, que puede
      influir en los desafíos y necesidades relacionados con la gestión
      del agua.

Preguntas Generales sobre la Gestión del Agua

1.  ¿Cuáles son los principales desafíos que enfrenta actualmente en la
    gestión del agua?

    - Objetivo: Identificar los problemas y obstáculos que encuentran en
      su día a día.

2.  ¿Qué herramientas o métodos utiliza actualmente para monitorear y
    gestionar el uso del agua?

    - Objetivo: Conocer las soluciones actuales y evaluar su
      efectividad.

3.  ¿Qué tan crítico es para usted el monitoreo en tiempo real del agua
    en su entorno?

    - Objetivo: Medir la importancia del monitoreo en tiempo real en su
      contexto.

Preguntas de Cierre

1.  ¿Qué beneficios espera obtener de una nueva tecnología de gestión
    del agua?

    - Objetivo: Identificar los factores decisivos para la adopción de
      la solución.

2.  ¿Estaría dispuesto a participar en un piloto o prueba de la
    tecnología propuesta por WaterGuard? ¿Por qué?

    - Objetivo: Medir el interés en una prueba inicial de la solución.

3.  ¿Hay algún otro aspecto de la gestión del agua que le gustaría que
    abordamos con esta tecnología?

    - Objetivo: Identificar posibles mejoras o expansiones de la
      solución.

###   {#section-1}

### 2.2.2. Registro de entrevistas {#registro-de-entrevistas}

Comunidades rurales

Primer Entrevista:

Descripción del entrevistado:

![](media/image13.png){width="6.267716535433071in"
height="1.7777777777777777in"}

- Nombre: jhon mamani Quispe

- Edad: 22 años

- Distrito: La Victoria, Lima

- Resumen: Jhon es un chico de una comunidad rural donde ayuda a sus
  padres con los cultivos desde que acabó la secundaria, por otro lado
  nos menciona que a veces no hay suministro de agua por problemas su
  sistema, como atascos, o que simplemente el rio no fluctúa suficiente,
  además de esto también nos menciona que si le gustaria nuestra
  solución y nos recomendó de tener distintos medio para la recolección
  del suministro de agua

- Link de la Entrevista:

> [[https://drive.google.com/file/d/1xZ7Q-G_bLlCjzRgpAR1VzYxvMg31LPRi/view?usp=sharing]{.underline}](https://drive.google.com/file/d/1xZ7Q-G_bLlCjzRgpAR1VzYxvMg31LPRi/view?usp=sharing)

Segunda Entrevista:

![](media/image14.png){width="6.267716535433071in"
height="2.513888888888889in"}

- Nombre: Anderson Macedo

- Edad: 24 años

- Distrito: Puno

- Resumen: Anderson Macedo, un joven de 24 años de Puno, apoya como
  voluntario en su comunidad en temas de agua desde hace dos años.
  Señala que enfrentan problemas como la falta de monitoreo del agua,
  fugas y distribución ineficiente, especialmente en épocas de sequía.
  Actualmente, todo se gestiona de forma manual y considera crítico
  contar con un sistema en tiempo real. Está dispuesto a participar en
  un piloto tecnológico que permita controlar mejor el agua, reducir
  desperdicios y educar a la comunidad sobre su uso.

- Link de la Entrevista:

> [[https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c179_upc_edu_pe/EQVGlvs4oFNCvFjIItE3SpgBUyXDKfwkDASS4hL9BOJqRw?e=7NZLOj&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D]{.underline}](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c179_upc_edu_pe/EQVGlvs4oFNCvFjIItE3SpgBUyXDKfwkDASS4hL9BOJqRw?e=7NZLOj&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

Tercera Entrevista:

Descripción del
Entrevistado:![](media/image15.png){width="6.267716535433071in"
height="3.0416666666666665in"}

- Nombre: Paul Vega

- Edad: 20 años

- Distrito: Lurigancho

- Resumen: El entrevistado nació y vivió gran parte de su vida en el
  departamento de Ayacucho, específicamente en el pueblo-comunidad de
  Spite dentro de la provincia Victor Fajardo. Nos cuenta que al menos 2
  veces a la semana tenían problemas con la conexión hacia su tanque de
  agua que usaban para la cosecha y a la vez para su consumo, nos cuenta
  que tener la gestión al alcance de la mano y ver el estado del agua
  ayudaría bastante como ver el PH y demás, debido a que la gente de
  dónde vive a veces no hierven bien el agua.

- Link de la entrevista:

> [[https://youtu.be/aXAZWVor7tA]{.underline}](https://youtu.be/aXAZWVor7tA)

###  {#section-2}

### 2.2.3. Análisis de entrevistas {#análisis-de-entrevistas}

Comunidades Rurales:

1.  Necesidades: Las comunidades rurales necesitan herramientas
    sencillas que les permitan distribuir el agua de manera equitativa y
    eficiente para sus cultivos y consumo doméstico. Su prioridad es
    asegurar la disponibilidad del agua durante todo el año,
    especialmente en épocas de sequía, y hacerlo de manera sostenible.

2.  Frustraciones: Las principales frustraciones en las comunidades
    rurales están relacionadas con la falta de acceso a tecnologías y la
    limitada capacitación disponible para aprender a utilizar
    herramientas de gestión del agua. Además, enfrentan problemas de
    recursos limitados, lo que dificulta la adopción de nuevas
    tecnologías.

3.  Soluciones Deseadas: Las comunidades rurales buscan soluciones
    accesibles, económicas y fáciles de utilizar que no requieran un
    alto nivel técnico. Quieren herramientas que les permitan mejorar la
    gestión del agua sin complicaciones y que promuevan la
    sostenibilidad en sus prácticas agrícolas y domésticas.

4.  Expectativas: Las comunidades rurales esperan mejorar la
    distribución del agua en un porcentaje considerable, reducir las
    pérdidas de este recurso, y asegurarse de que todos los miembros de
    la comunidad puedan acceder a la misma capacitación y conocimiento
    sobre el uso eficiente del agua. También esperan que las soluciones
    sean sostenibles y asequibles para su entorno.

## 2.3. Needfinding {#needfinding}

### 2.3.1. User Personas {#user-personas}

La siguiente ficha es para el segmento de personas de comunidades
rurales: En este caso, nos enfocamos en la historia de Rosa, una mujer
que vive en una comunidad rural y se encarga de gestionar el uso del
agua para su hogar y sus cultivos. Rosa busca herramientas que le
permitan distribuir el agua de manera eficiente y asegurar su
disponibilidad durante las temporadas secas. Sin embargo, sus
principales frustraciones son la falta de acceso a tecnología asequible,
la escasez de agua en épocas críticas y la dificultad para mantener un
control preciso del recurso.

Usuario 1: Comunidades rurales

![](media/image16.png){width="6.267716535433071in"
height="4.666666666666667in"}

###  {#section-3}

###  {#section-4}

###   {#section-5}

### 2.3.2. User Task Matrix {#user-task-matrix}

La sección de User Task Matrix es una herramienta útil para entender las
tareas y objetivos que cada User Persona desea lograr al utilizar
nuestro producto. En esta sección, se presentarán las matrices de tareas
para cada uno de los User Personas previamente definidos.

Usuario 1: Comunidades Rurales

|                                      |            |             |
|--------------------------------------|------------|-------------|
| Task                                 | Rosa       |             |
|                                      | Frecuencia | Importancia |
| Distribuir el agua para cultivos     | Alta       | Alta        |
| Asegurar el abastecimiento del agua  | Alta       | Alta        |
| Participar en reuniones comunitarias | Media      | Media       |
| Implementar prácticas sostenibles    | Media      | Alta        |

### 2.3.3. User Journey Mapping {#user-journey-mapping}

La sección de User Journey Mapping es una herramienta útil para entender
la experiencia del usuario desde el inicio hasta el final de su
interacción con nuestro producto o servicio. En esta sección, se
presentarán los mapas de experiencia para cada uno de los User Personas
previamente definidos.

Usuario 1: Usuario de comunidades rurales

![](media/image17.png){width="6.267716535433071in"
height="2.8472222222222223in"}

### 2.3.4. Empathy Mapping {#empathy-mapping}

Usuario 1: Usuario de comunidades rurales

![](media/image18.png){width="5.598958880139983in"
height="4.1945680227471565in"}

### 2.3.5. As-is Scenario Mapping {#as-is-scenario-mapping}

Comunidades rurales que gestionan el agua  
![](media/image19.png){width="5.807292213473316in"
height="3.2722823709536306in"}

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping {#to-be-scenario-mapping}

Hogares en comunidades rurales que gestionan el agua:

![](media/image20.png){width="6.267716535433071in"
height="3.5416666666666665in"}

Link miro:
[[https://miro.com/welcomeonboard/WlVRUmt4UWkyNWdLaEVucmx0dnNGMmd4Q0NiVUNWZmxCUHNOaUpKOGF1MGNWTXRpaHlHR1czMjJ5ZFU4SWdLdUJqZjJUc0w1NkdoTjZtNkVPbnZBemRQOGdiNnI4MzFRQTB3eHdmRWRjcmZNRmJUS3JlMXA5VC9hSzRrVHFxbHNQdGo1ZEV3bUdPQWRZUHQzSGl6V2NBPT0hdjE=?share_link_id=948205957300]{.underline}](https://miro.com/welcomeonboard/WlVRUmt4UWkyNWdLaEVucmx0dnNGMmd4Q0NiVUNWZmxCUHNOaUpKOGF1MGNWTXRpaHlHR1czMjJ5ZFU4SWdLdUJqZjJUc0w1NkdoTjZtNkVPbnZBemRQOGdiNnI4MzFRQTB3eHdmRWRjcmZNRmJUS3JlMXA5VC9hSzRrVHFxbHNQdGo1ZEV3bUdPQWRZUHQzSGl6V2NBPT0hdjE=?share_link_id=948205957300)

##   {#section-6}

## 3.2. User Stories {#user-stories}

Epics:

EP-001: Configuración e Integración de Sensores IoT.

EP-002: Monitoreo y Gestión en Tiempo Real.

EP-003: Capacitación y Soporte al Usuario.

EP-004: Personalización y Acceso a Datos.

EP-005: Automatización y Reportes.

EP-006: Gestión y Actualización del Sistema.

EP-007: Soporte Técnico y Monitoreo de Estado.

EP-008: Seguridad y Auditoría de Datos.

EP-009: Automatización y Gestión del Control de Bombas de Agua

<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 14%" />
<col style="width: 21%" />
<col style="width: 34%" />
<col style="width: 15%" />
</colgroup>
<tbody>
<tr class="odd">
<td>US-ID</td>
<td>Título</td>
<td>Descripción</td>
<td>Criterios de Aceptación</td>
<td>ID de Epic Relacionado</td>
</tr>
<tr class="even">
<td>US-001</td>
<td>Configurar sensores IoT</td>
<td>Como técnico, quiero configurar los sensores IoT para monitorear los
tanques de agua.</td>
<td><p>Escenario: Conexión Exitosa de Sensores</p>
<p>Dado que el técnico tiene los sensores IoT listos para instalar.</p>
<p>Cuando conecta los sensores a los tanques de agua y los empareja con
el sistema central.</p>
<p>Entonces el sistema confirma la conexión exitosa mostrando los datos
en tiempo real.</p>
<p>Escenario: Verificación Automática de Sensores</p>
<p>Dado que el técnico ha instalado los sensores IoT en los tanques.</p>
<p>Cuando inicia la configuración en el panel de control del
sistema.</p>
<p>Entonces el sistema realiza una verificación automática y muestra un
mensaje de éxito si todos los sensores están funcionando
correctamente.</p></td>
<td>EP-001</td>
</tr>
<tr class="odd">
<td>US-002</td>
<td>Integrar Sensores con Base de Datos y Backend</td>
<td>Como usuario, quiero que los datos de los sensores se almacenen en
una base de datos en tiempo real y luego se envíen al backend para su
procesamiento y visualización.</td>
<td><p>Escenario: Almacenamiento y Envío de Datos a la Base de Datos</p>
<p>Dado que los sensores IoT están configurados correctamente y
transmiten datos,<br />
Cuando los sensores capturan datos como el nivel de agua, pH,
temperatura, etc.,</p>
<p>Entonces, los datos se envían y se almacenan en la base de datos en
tiempo real.</p>
<p>Escenario: Envío de Datos al Backend</p>
<p>Dado que los datos están almacenados en la base de datos,</p>
<p>Cuando el sistema recibe los datos de la base de datos,</p>
<p>Entonces, el backend procesa la información y la prepara para ser
visualizada por el usuario en la interfaz de la plataforma.</p></td>
<td>EP-001</td>
</tr>
<tr class="even">
<td>US-003</td>
<td>Monitorear datos de agua</td>
<td>Como agricultor, quiero poder monitorear el nivel de agua en los
tanques a través de una app móvil.</td>
<td><p>Escenario: Visualización del Nivel de Agua</p>
<p>Dado que el agricultor ha instalado los sensores IoT en los tanques
de agua y ha descargado la app móvil.</p>
<p>Cuando abre la app y selecciona el tanque que desea monitorear.</p>
<p>Entonces la app muestra el nivel de agua actual en tiempo real, junto
con un gráfico histórico del día.</p>
<p>Escenario: Notificación de Bajo Nivel de Agua</p>
<p>Dado que el agricultor está utilizando la app para monitorear varios
tanques de agua en diferentes ubicaciones.</p>
<p>Cuando el nivel de agua en uno de los tanques cae por debajo del
umbral mínimo establecido.</p>
<p>Entonces la app envía una notificación push alertando al agricultor
de que debe revisar y posiblemente rellenar el tanque.</p></td>
<td>EP-002</td>
</tr>
<tr class="odd">
<td>US-004</td>
<td>Configurar alertas personalizadas</td>
<td>Como usuario, quiero configurar alertas personalizadas para recibir
notificaciones sobre niveles de agua.</td>
<td><p>Escenario: Configuración de Alertas por Nivel Bajo</p>
<p>Dado que el usuario quiere recibir alertas cuando el nivel de agua
esté bajo.</p>
<p>Cuando entra en la configuración de alertas y establece un umbral
mínimo de nivel de agua.</p>
<p>Entonces el sistema envía una notificación por correo electrónico y
SMS cuando el nivel cae por debajo del umbral.</p>
<p>Escenario: Notificaciones Push</p>
<p>Dado que el usuario necesita recibir alertas en su dispositivo
móvil.</p>
<p>Cuando se activa la opción de recibir notificaciones push en la
app.</p>
<p>Entonces el sistema envía alertas push instantáneas cuando se
alcanzan los umbrales establecidos.</p></td>
<td>EP-002</td>
</tr>
<tr class="even">
<td>US-005</td>
<td>Capacitar usuarios en el uso del sistema</td>
<td>Como administrador, quiero realizar capacitaciones para que los
usuarios aprendan a usar el sistema.</td>
<td><p>Escenario: Sesión de Capacitación Inicial</p>
<p>Dado que el administrador necesita que los usuarios aprendan a
utilizar el sistema.</p>
<p>Cuando organiza una sesión de capacitación donde se explica cómo usar
la plataforma.</p>
<p>Entonces los usuarios comprenden los conceptos básicos y pueden
navegar por la plataforma de forma autónoma.</p>
<p>Escenario: Acceso a Recursos de Capacitación</p>
<p>Dado que los usuarios requieren apoyo continuo en el uso del
sistema.</p>
<p>Cuando el administrador proporciona acceso a tutoriales y documentos
de capacitación en línea.</p>
<p>Entonces los usuarios pueden consultar los recursos en cualquier
momento para resolver dudas.</p></td>
<td>EP-003</td>
</tr>
<tr class="odd">
<td>US-006</td>
<td>Acceder al historial de datos</td>
<td>Como usuario, quiero acceder al historial de datos para analizar el
uso del agua a lo largo del tiempo.</td>
<td><p>Escenario: Análisis Semanal de Datos</p>
<p>Dado que el usuario necesita analizar el uso del agua durante la
última semana.</p>
<p>Cuando ingresa a la sección de historial en la plataforma y
selecciona el rango de fechas correspondiente.</p>
<p>Entonces el sistema muestra un gráfico detallado que representa los
niveles de agua durante los días seleccionados, permitiendo al usuario
identificar patrones de consumo.</p>
<p>Escenario: Exportación de Historial de Datos</p>
<p>Dado que el usuario requiere exportar el historial de datos para
compartirlo con su equipo.</p>
<p>Cuando selecciona la opción de exportar desde la interfaz de la
plataforma.</p>
<p>Entonces el sistema genera un archivo CSV con los datos de los
últimos 30 días y lo descarga automáticamente en su
dispositivo.</p></td>
<td>EP-004</td>
</tr>
<tr class="even">
<td>US-007</td>
<td>Optimizar el riego basado en datos</td>
<td>Como agricultor, quiero optimizar el riego en función de los datos
recibidos del sistema.</td>
<td><p>Escenario: Recomendación de Riego</p>
<p>Dado que el agricultor monitorea los niveles de agua
regularmente.</p>
<p>Cuando el sistema detecta que el nivel de agua es óptimo para el
riego.</p>
<p>Entonces el sistema recomienda ajustar el riego en función de los
datos obtenidos.</p>
<p>Escenario: Ajuste Automático de Riego</p>
<p>Dado que el sistema está configurado para automatizar tareas.</p>
<p>Cuando el nivel de agua alcanza el umbral establecido para el
riego.</p>
<p>Entonces el sistema ajusta automáticamente los tiempos de riego sin
intervención manual.</p></td>
<td>EP-002</td>
</tr>
<tr class="odd">
<td>US-008</td>
<td>Automatizar acciones basadas en alertas</td>
<td>Como técnico, quiero que el sistema ejecute acciones automáticamente
cuando se activen alertas.</td>
<td><p>Escenario: Activación de Bomba de Agua</p>
<p>Dado que el sistema está configurado para responder a alertas
críticas.</p>
<p>Cuando el nivel de agua baja drásticamente en uno de los tanques.</p>
<p>Entonces el sistema activa automáticamente la bomba de agua para
rellenar el tanque.</p>
<p>Escenario: Cierre Automático de Válvula</p>
<p>Dado que se detecta una fuga de agua a través de los sensores.</p>
<p>Cuando el sistema recibe la alerta de fuga.</p>
<p>Entonces el sistema cierra automáticamente la válvula principal para
evitar pérdida de agua.</p></td>
<td>EP-005</td>
</tr>
<tr class="even">
<td>US-009</td>
<td>Reportar datos incorrectos</td>
<td>Como usuario, quiero poder reportar datos incorrectos para que sean
corregidos rápidamente.</td>
<td><p>Escenario: Reporte de Anomalías en Datos</p>
<p>Dado que el usuario detecta que los datos mostrados no coinciden con
la realidad.</p>
<p>Cuando selecciona la opción de reportar error en la app.</p>
<p>Entonces el sistema envía un informe detallado al equipo técnico para
su revisión.</p>
<p>Escenario: Confirmación de Reporte</p>
<p>Dado que el usuario ha reportado un error en los datos.</p>
<p>Cuando el sistema recibe el reporte.</p>
<p>Entonces el usuario recibe una notificación confirmando que su
reporte ha sido enviado y está en revisión.</p></td>
<td>EP-004</td>
</tr>
<tr class="odd">
<td>US-010</td>
<td>Actualizar software del sistema</td>
<td>Como administrador, quiero poder actualizar el software del sistema
de manera remota y segura.</td>
<td><p>Escenario: Actualización Automática en Horario Programado</p>
<p>Dado que el administrador programa actualizaciones regulares del
software.</p>
<p>Cuando llega la hora programada para la actualización.</p>
<p>Entonces el sistema se actualiza automáticamente sin interrumpir el
servicio y envía una notificación de finalización exitosa.</p>
<p>Escenario: Respaldo Automático Antes de la Actualización</p>
<p>Dado que el sistema debe mantener la integridad de los datos.</p>
<p>Cuando se inicia una actualización del software.</p>
<p>Entonces el sistema crea automáticamente un respaldo de todos los
datos antes de proceder con la actualización.</p></td>
<td>EP-006</td>
</tr>
<tr class="even">
<td>US-011</td>
<td>Monitorear el estado de los sensores</td>
<td>Como usuario, quiero recibir notificaciones sobre el estado de los
sensores IoT para asegurar su correcto funcionamiento.</td>
<td><p>Escenario: Alerta de Sensor Fuera de Línea</p>
<p>Dado que el sistema monitorea continuamente el estado de los sensores
IoT.</p>
<p>Cuando un sensor se desconecta o deja de enviar datos.</p>
<p>Entonces el sistema envía una alerta inmediata al usuario indicando
que el sensor está fuera de línea.</p>
<p>Escenario: Verificación del Estado de Todos los Sensores</p>
<p>Dado que el usuario quiere asegurarse de que todos los sensores están
funcionando correctamente.</p>
<p>Cuando accede al panel de control del sistema.</p>
<p>Entonces el sistema muestra el estado actual de todos los sensores,
incluyendo cualquier fallo o error detectado.</p></td>
<td>EP-007</td>
</tr>
<tr class="odd">
<td>US-012</td>
<td>Proporcionar acceso multiusuario</td>
<td>Como administrador, quiero que múltiples usuarios puedan acceder al
sistema con diferentes niveles de permiso.</td>
<td><p>Escenario: Creación de Roles y Permisos</p>
<p>Dado que el administrador necesita gestionar el acceso de diferentes
usuarios al sistema.</p>
<p>Cuando crea roles personalizados con permisos específicos en la
plataforma.</p>
<p>Entonces los usuarios asignados a esos roles solo pueden acceder a
las funciones para las que tienen permisos.</p>
<p>Escenario: Asignación de Roles a Nuevos Usuarios</p>
<p>Dado que se han añadido nuevos usuarios al sistema.</p>
<p>Cuando el administrador asigna roles a estos nuevos usuarios.</p>
<p>Entonces los nuevos usuarios reciben un acceso seguro y sus
actividades quedan registradas según sus permisos.</p></td>
<td>EP-006</td>
</tr>
<tr class="even">
<td>US-013</td>
<td>Configurar panel de control personalizado</td>
<td>Como usuario, quiero personalizar mi panel de control para ver solo
la información más relevante para mí.</td>
<td><p>Escenario: Personalización de Widgets en el Panel</p>
<p>Dado que el usuario desea ver solo la información más relevante en su
panel de control.</p>
<p>Cuando personaliza su panel añadiendo y organizando widgets.</p>
<p>Entonces el sistema guarda automáticamente la configuración del panel
y la muestra en su próxima sesión.</p>
<p>Escenario: Restauración de Configuración de Panel por Defecto</p>
<p>Dado que el usuario quiere restablecer su panel de control a la
configuración original.</p>
<p>Cuando selecciona la opción de restaurar configuración por
defecto.</p>
<p>Entonces el sistema elimina las personalizaciones y muestra el panel
en su estado predeterminado.</p></td>
<td>EP-004</td>
</tr>
<tr class="odd">
<td>US-014</td>
<td>Generar informes automáticos</td>
<td>Como administrador, quiero que el sistema genere informes
automáticos sobre el uso del agua.</td>
<td><p>Escenario: Generación Semanal de Informes</p>
<p>Dado que el administrador necesita recibir informes sobre el uso del
agua.</p>
<p>Cuando el sistema genera un informe automático cada semana.</p>
<p>Entonces el informe se envía por correo electrónico al administrador
con gráficos y análisis de tendencias.</p>
<p>Escenario: Configuración de Informes Personalizados</p>
<p>Dado que el administrador desea configurar los informes según las
necesidades específicas.</p>
<p>Cuando ajusta las configuraciones de los informes automáticos en la
plataforma.</p>
<p>Entonces el sistema genera y envía informes personalizados que
cumplen con los criterios establecidos.</p></td>
<td>EP-005</td>
</tr>
<tr class="even">
<td>US-015</td>
<td>Integrar el sistema con otras plataformas</td>
<td>Como administrador, quiero que el sistema se integre con otras
plataformas de gestión de recursos.</td>
<td><p>Escenario: Sincronización de Datos con Otra Plataforma</p>
<p>Dado que el administrador necesita que los datos del sistema se
integren con una plataforma externa.</p>
<p>Cuando configura la API para la sincronización de datos.</p>
<p>Entonces los datos se sincronizan automáticamente entre el sistema y
la plataforma externa, sin necesidad de intervención manual.</p>
<p>Escenario: Importación de Datos desde una Plataforma Externa</p>
<p>Dado que el administrador necesita importar datos desde otra
plataforma al sistema.</p>
<p>Cuando utiliza la integración configurada para importar datos.</p>
<p>Entonces el sistema recibe y almacena los datos importados,
permitiendo su visualización y análisis.</p></td>
<td>EP-006</td>
</tr>
<tr class="odd">
<td>US-016</td>
<td>Ofrecer soporte técnico en línea</td>
<td>Como usuario, quiero poder contactar con soporte técnico en línea si
tengo problemas con el sistema.</td>
<td><p>Escenario: Contacto a Soporte a través de Chat en Vivo</p>
<p>Dado que el usuario tiene un problema técnico con el sistema.</p>
<p>Cuando utiliza la función de chat en vivo disponible en la
plataforma.</p>
<p>Entonces el equipo de soporte técnico responde en tiempo real y
asiste al usuario en la resolución del problema.</p>
<p>Escenario: Envío de Ticket de Soporte</p>
<p>Dado que el usuario necesita asistencia técnica fuera del horario de
soporte en vivo.</p>
<p>Cuando envía un ticket de soporte desde la plataforma.</p>
<p>Entonces el sistema genera un número de ticket y el usuario recibe
una confirmación por correo electrónico con el tiempo estimado de
respuesta.</p></td>
<td>EP-007</td>
</tr>
<tr class="even">
<td>US-017</td>
<td>Configurar usuarios como administradores locales</td>
<td>Como superadministrador, quiero asignar permisos de administrador
local para que otros gestionen su propio sistema.</td>
<td><p>Escenario: Asignación de Permisos de Administrador Local</p>
<p>Dado que el superadministrador necesita que otros usuarios gestionen
sus áreas específicas del sistema.</p>
<p>Cuando asigna permisos de administrador local a estos usuarios.</p>
<p>Entonces los administradores locales pueden gestionar las
configuraciones y datos de su área asignada sin acceso a las demás
áreas.</p>
<p>Escenario: Registro de Actividades de Administradores Locales</p>
<p>Dado que el superadministrador necesita monitorear los cambios
realizados por los administradores locales.</p>
<p>Cuando los administradores locales realizan cambios en el
sistema.</p>
<p>Entonces el sistema registra todas las actividades realizadas y
genera un informe que el superadministrador puede revisar.</p></td>
<td>EP-006</td>
</tr>
<tr class="odd">
<td>US-018</td>
<td>Implementar seguridad de datos</td>
<td>Como usuario, quiero que mis datos estén seguros y cifrados en todo
momento.</td>
<td><p>Escenario: Cifrado de Datos en Tránsito</p>
<p>Dado que el sistema maneja datos sensibles.</p>
<p>Cuando se transmiten datos entre el usuario y el servidor.</p>
<p>Entonces el sistema cifra todos los datos en tránsito usando SSL/TLS,
asegurando que los datos no puedan ser interceptados.</p>
<p>Escenario: Autenticación de Dos Factores (2FA)</p>
<p>Dado que el usuario desea asegurar el acceso a su cuenta.</p>
<p>Cuando activa la autenticación de dos factores en la configuración de
su cuenta.</p>
<p>Entonces el sistema requiere un segundo factor de autenticación, como
un código enviado al teléfono móvil, para permitir el acceso.</p></td>
<td>EP-008</td>
</tr>
<tr class="even">
<td>US-019</td>
<td>Configurar notificaciones push</td>
<td>Como usuario, quiero recibir notificaciones push en mi dispositivo
móvil sobre cambios importantes en el sistema.</td>
<td><p>Escenario: Activación de Notificaciones Push</p>
<p>Dado que el usuario quiere recibir notificaciones instantáneas sobre
eventos importantes.</p>
<p>Cuando activa las notificaciones push desde la configuración de su
dispositivo móvil.</p>
<p>Entonces el sistema envía notificaciones push instantáneas sobre los
eventos configurados.</p>
<p>Escenario: Personalización de Notificaciones Push</p>
<p>Dado que el usuario desea recibir notificaciones solo para ciertos
eventos.</p>
<p>Cuando personaliza las opciones de notificación en la app.</p>
<p>Entonces el sistema solo envía notificaciones push para los eventos
seleccionados por el usuario.</p></td>
<td>EP-002</td>
</tr>
<tr class="odd">
<td>US-020</td>
<td>Auditar las actividades del sistema</td>
<td>Como auditor, quiero revisar todas las actividades realizadas en el
sistema para garantizar la integridad y seguridad.</td>
<td><p>Escenario: Revisión de Logs de Auditoría</p>
<p>Dado que el auditor necesita revisar las actividades realizadas en el
sistema.</p>
<p>Cuando accede a los logs de auditoría desde el panel de
administración.</p>
<p>Entonces el sistema muestra un registro detallado de todas las
acciones realizadas por los usuarios, incluyendo la hora y el usuario
responsable.</p>
<p>Escenario: Exportación de Logs de Auditoría</p>
<p>Dado que el auditor necesita analizar los datos fuera del
sistema.</p>
<p>Cuando selecciona la opción de exportar los logs de auditoría.</p>
<p>Entonces el sistema genera un archivo exportable que contiene todos
los registros de auditoría dentro del rango de fechas
seleccionado.</p></td>
<td>EP-008</td>
</tr>
<tr class="even">
<td>US-021</td>
<td>Activación Automática de las Bombas de Agua</td>
<td>Como técnico, quiero que las bombas de agua se activen
automáticamente cuando el nivel de agua llegue a un umbral crítico, para
evitar que el tanque se quede sin agua.</td>
<td><p>Escenario: Activación Automática por Nivel Bajo</p>
<p>Dado que el sistema monitorea los niveles de agua en los tanques de
forma constante,</p>
<p>Cuando el nivel de agua cae por debajo del umbral mínimo
establecido,</p>
<p>Entonces, el sistema activa automáticamente las bombas de agua para
llenar el tanque hasta el nivel adecuado.</p>
<p>Escenario: Control Manual de las Bombas</p>
<p>Dado que el técnico desea controlar manualmente las bombas,</p>
<p>Cuando accede a la plataforma del sistema y selecciona la opción de
control manual,</p>
<p>Entonces, el sistema permite activar o desactivar las bombas de agua
desde la interfaz.</p></td>
<td>EP-009</td>
</tr>
<tr class="odd">
<td>US-022</td>
<td>Notificación de Baja del Nivel de Agua y Activación de Bombas</td>
<td>Como agricultor, quiero recibir una notificación cuando el nivel de
agua esté bajo y la bomba de agua se haya activado, para saber que el
sistema está funcionando correctamente.</td>
<td><p>Escenario: Notificación de Activación de Bombas</p>
<p>Dado que el nivel de agua en el tanque está bajo,</p>
<p>Cuando el sistema activa la bomba de agua para llenar el tanque,</p>
<p>Entonces el agricultor recibe una notificación push alertando que las
bombas están siendo activadas para restaurar el nivel de agua.</p>
<p>Escenario: Confirmación de Relleno Completo</p>
<p>Dado que el sistema ha activado la bomba de agua,</p>
<p>Cuando el nivel de agua alcanza el umbral predeterminado,</p>
<p>Entonces el agricultor recibe una notificación confirmando que el
tanque está lleno y las bombas se han desactivado
automáticamente.</p></td>
<td>EP-009</td>
</tr>
<tr class="even">
<td>US-023</td>
<td>Desactivación Automática de las Bombas</td>
<td>Como usuario, quiero que el sistema desactive automáticamente las
bombas una vez que el nivel de agua haya alcanzado el umbral máximo para
evitar el sobrellenado de los tanques.</td>
<td><p>Escenario: Desactivación Automática de Bombas</p>
<p>Dado que el nivel de agua en el tanque ha alcanzado el umbral
máximo,</p>
<p>Cuando el sistema detecta que el tanque está lleno,</p>
<p>Entonces, las bombas se desactivan automáticamente para evitar el
desbordamiento.</p>
<p>Escenario: Confirmación de Desactivación</p>
<p>Dado que el sistema ha desactivado las bombas,</p>
<p>Cuando el agricultor consulta la plataforma,</p>
<p>Entonces, el sistema muestra un mensaje indicando que las bombas se
han desactivado porque el nivel de agua es adecuado.</p></td>
<td>EP-009</td>
</tr>
<tr class="odd">
<td>US-024</td>
<td>Supervisión y Monitoreo del Estado de las Bombas</td>
<td>Como administrador, quiero poder supervisar el estado de las bombas
(encendidas/apagadas) desde el sistema, para asegurarme de que todo esté
funcionando correctamente.</td>
<td><p>Escenario: Visualización del Estado de las Bombas</p>
<p>Dado que el administrador accede al panel de control,</p>
<p>Cuando se muestra el estado de las bombas de agua en el sistema,</p>
<p>Entonces, el administrador puede ver si las bombas están encendidas o
apagadas, junto con el nivel de agua actual en los tanques.</p>
<p>Escenario: Alerta de Falla en la Bomba</p>
<p>Dado que el sistema monitorea el funcionamiento de las bombas,</p>
<p>Cuando el sistema detecta una falla en las bombas,</p>
<p>Entonces, se envía una alerta al administrador notificando que las
bombas no están funcionando correctamente.</p></td>
<td>EP-009</td>
</tr>
</tbody>
</table>

##   {#section-7}

## 3.3. Impact Mapping {#impact-mapping}

Hogares en comunidades rurales que gestionan el agua para la agricultura
y consumo propio:

![](media/image21.png){width="6.270833333333333in"
height="2.493225065616798in"}

## 3.4. Product Backlog {#product-backlog}

Los Story Points son una forma de medir el esfuerzo relativo necesario
para completar una tarea o historia de usuario en un proyecto ágil. No
se mide en horas, sino que se basa en la complejidad, la cantidad de
trabajo y la incertidumbre de la tarea. Los números suelen seguir la
secuencia de Fibonacci (1, 2, 3, 5, 8\...), ya que refleja el
crecimiento exponencial de la dificultad a medida que las tareas son más
complejas.

Definición de los valores de Story Points:

1: Tarea muy simple, fácil de hacer, con poca complejidad y sin
incertidumbre.

2: Tarea un poco más compleja, pero sigue siendo manejable y predecible.

3: Tarea de complejidad media, requiere más esfuerzo y puede tener
algunos elementos desconocidos.

5: Tarea compleja, con varias partes a considerar, requiere coordinación
o tiene incertidumbre.

8: Tarea muy compleja y grande, con alta incertidumbre, muchas partes y
un esfuerzo significativo.

|          |               |                                                               |                                                                                                                                                                                   |                          |
|----------|---------------|---------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------|
| \# Orden | User Story ID | Título                                                        | Descripción                                                                                                                                                                       | Story Points (1/2/3/5/8) |
| 1        | US-001        | Configurar sensores IoT                                       | Como técnico, quiero configurar los sensores IoT para monitorear los tanques de agua.                                                                                             | 3                        |
| 2        | US-002        | Integrar Sensores con Base de Datos y Backend                 | Como usuario, quiero que los datos de los sensores se almacenen en una base de datos en tiempo real y luego se envíen al backend para su procesamiento y visualización.           | 8                        |
| 3        | US-003        | Monitorear datos de agua                                      | Como agricultor, quiero poder monitorear el nivel de agua en los tanques a través de una app móvil.                                                                               | 3                        |
| 4        | US-004        | Configurar alertas personalizadas                             | Como usuario, quiero configurar alertas personalizadas para recibir notificaciones sobre niveles de agua.                                                                         | 5                        |
| 5        | US-005        | Capacitar usuarios en el uso del sistema                      | Como administrador, quiero realizar capacitaciones para que los usuarios aprendan a usar el sistema.                                                                              | 8                        |
| 6        | US-006        | Acceder al historial de datos                                 | Como usuario, quiero acceder al historial de datos para analizar el uso del agua a lo largo del tiempo.                                                                           | 3                        |
| 7        | US-007        | Optimizar el riego basado en datos                            | Como agricultor, quiero optimizar el riego en función de los datos recibidos del sistema.                                                                                         | 5                        |
| 8        | US-008        | Automatizar acciones basadas en alertas                       | Como técnico, quiero que el sistema ejecute acciones automáticamente cuando se activen alertas.                                                                                   | 8                        |
| 9        | US-009        | Reportar datos incorrectos                                    | Como usuario, quiero poder reportar datos incorrectos para que sean corregidos rápidamente.                                                                                       | 2                        |
| 10       | US-010        | Actualizar software del sistema                               | Como administrador, quiero poder actualizar el software del sistema de manera remota y segura.                                                                                    | 5                        |
| 11       | US-011        | Monitorear el estado de los sensores                          | Como usuario, quiero recibir notificaciones sobre el estado de los sensores IoT para asegurar su correcto funcionamiento.                                                         | 3                        |
| 12       | US-012        | Proporcionar acceso multiusuario                              | Como administrador, quiero que múltiples usuarios puedan acceder al sistema con diferentes niveles de permiso.                                                                    | 8                        |
| 13       | US-013        | Configurar panel de control personalizado                     | Como usuario, quiero personalizar mi panel de control para ver solo la información más relevante para mí.                                                                         | 5                        |
| 14       | US-014        | Generar informes automáticos                                  | Como administrador, quiero que el sistema genere informes automáticos sobre el uso del agua.                                                                                      | 5                        |
| 15       | US-015        | Integrar el sistema con otras plataformas                     | Como administrador, quiero que el sistema se integre con otras plataformas de gestión de recursos.                                                                                | 8                        |
| 16       | US-016        | Ofrecer soporte técnico en línea                              | Como usuario, quiero poder contactar con soporte técnico en línea si tengo problemas con el sistema.                                                                              | 3                        |
| 17       | US-017        | Configurar usuarios como administradores locales              | Como superadministrador, quiero asignar permisos de administrador local para que otros gestionen su propio sistema.                                                               | 5                        |
| 18       | US-018        | Implementar seguridad de datos                                | Como usuario, quiero que mis datos estén seguros y cifrados en todo momento.                                                                                                      | 8                        |
| 19       | US-019        | Configurar notificaciones push                                | Como usuario, quiero recibir notificaciones push en mi dispositivo móvil sobre cambios importantes en el sistema.                                                                 | 3                        |
| 20       | US-020        | Auditar las actividades del sistema                           | Como auditor, quiero revisar todas las actividades realizadas en el sistema para garantizar la integridad y seguridad.                                                            | 5                        |
| 21       | US-021        | Activación Automática de las Bombas de Agua                   | Como técnico, quiero que las bombas de agua se activan automáticamente cuando el nivel de agua llegue a un umbral crítico, para evitar que el tanque se quede sin agua.           | 2                        |
| 22       | US-022        | Notificación de Baja del Nivel de Agua y Activación de Bombas | Como agricultor, quiero recibir una notificación cuando el nivel de agua esté bajo y la bomba de agua se haya activado, para saber que el sistema está funcionando correctamente. | 2                        |
| 23       | US-023        | Desactivación Automática de las Bombas                        | Como usuario, quiero que el sistema desactive automáticamente las bombas una vez que el nivel de agua haya alcanzado el umbral máximo para evitar el sobrellenado de los tanques. | 2                        |
| 24       | US-024        | Implementación de landing page                                | Como usuario quiero poder ver una página del producto en la cual pueda ver todo lo que me está ofreciendo el producto                                                             | 5                        |

# Capítulo IV: Solution Software Design  {#capítulo-iv-solution-software-design}

## 4.1 Strategic-Level Domain-Driven Design {#strategic-level-domain-driven-design}

En el desarrollo de WaterGuard, decidimos aplicar el enfoque de
Domain-Driven Design (DDD) para asegurarnos de que nuestras decisiones
de diseño estratégico reflejaran fielmente las necesidades del negocio.
Sabíamos que el DDD nos permitiría dividir el dominio complejo de la
gestión y monitoreo del agua en subdominios más manejables, lo que
facilita el desarrollo, mantención y escalabilidad del sistema.

Lo primero que hicimos fue identificar y entender el dominio principal,
que es la gestión de recursos hídricos en tiempo real. Realizamos
entrevistas a usuarios clave, como administradores de edificios,
empresas de servicios públicos y personas rurales o con tanques de agua,
para comprender sus necesidades y definir un lenguaje común que nos
permitiera alinear los términos y conceptos técnicos con los objetivos
comerciales.

Una vez que tuvimos claro el dominio principal, dividimos el sistema en
subdominios con límites claramente definidos. También elaboramos un
context map para visualizar cómo estos subdominios interactúan entre sí.
Todo este trabajo nos permitió mantener el enfoque en lo que es
realmente importante, separando las preocupaciones de manera efectiva y
asegurándonos de que cada parte del sistema pudiera evolucionar de forma
independiente.

Pasos del Proceso Aplicando Domain-Driven Design

1\. Identificación del Dominio Principal

Identificamos que el dominio principal de WaterGuard es la gestión y
monitoreo en tiempo real de recursos hídricos. Esto cubre todos los
aspectos relacionados con la captura de datos de sensores IoT, su
procesamiento, y la presentación de información relevante sobre el
estado del agua (niveles, calidad, alertas) a los usuarios finales.

El dominio abarca tanto las necesidades de usuarios técnicos, como
administradores de infraestructuras y empresas de servicios públicos,
como las de comunidades rurales que requieren una herramienta accesible
para gestionar el agua de forma eficiente.

2\. Identificación de Subdominios y Bounded Contexts

Decidimos que lo mejor era dividir el sistema en varios subdominios para
mantener cada parte del sistema enfocada en un conjunto específico de
responsabilidades. Los subdominios principales que identificamos fueron:

- Monitoreo de Niveles de Agua: Nos encargamos de capturar y procesar
  los datos de los sensores que miden los niveles de agua en tiempo
  real.

  - Bounded Context: Gestión de sensores y datos de monitoreo.

- Calidad del Agua: Aquí procesamos los datos sobre la calidad del agua,
  como pH y turbidez, y emitimos alertas en caso de detectar problemas.

  - Bounded Context: Análisis y reportes de calidad del agua.

- Gestión de Usuarios: Este subdominio se ocupa de la autenticación y
  control de acceso, asegurando que los datos sólo sean accesibles para
  los usuarios autorizados.

  - Bounded Context: Seguridad y gestión de usuarios.

- Alertas y Notificaciones: Nos enfocamos en generar alertas automáticas
  para los usuarios cuando se detectan situaciones críticas, como
  niveles bajos de agua o problemas de calidad.

  - Bounded Context: Gestión de alertas.

- Escalabilidad y Gestión de Infraestructura: Diseñamos este subdominio
  para asegurar que el sistema pueda manejar miles de sensores y
  usuarios, utilizando soluciones basadas en la nube.

  - Bounded Context: Gestión de la infraestructura escalable.

### 4.1.1. EventStorming {#eventstorming}

[[https://miro.com/welcomeonboard/WUI2elkweFZ3bXJQSERpbHUyUVVZUURDM1BKUEFQTDZIMWsyMlN5emJrVG1FTzhwbE9RMFVZQVZlNW02NXNETXwzNDU4NzY0NTUwMDMzMzE1MjA4fDI=?share_link_id=124396993617]{.underline}](https://miro.com/welcomeonboard/WUI2elkweFZ3bXJQSERpbHUyUVVZUURDM1BKUEFQTDZIMWsyMlN5emJrVG1FTzhwbE9RMFVZQVZlNW02NXNETXwzNDU4NzY0NTUwMDMzMzE1MjA4fDI=?share_link_id=124396993617)

![](media/image22.png){width="6.267716535433071in"
height="3.0694444444444446in"}

### 4.1.1.1. Candidate Context Discovery {#candidate-context-discovery}

![](media/image23.png){width="6.267716535433071in"
height="5.222222222222222in"}

### 4.1.1.2. Domain Message Flows Modeling {#domain-message-flows-modeling}

![](media/image24.png){width="6.267716535433071in"
height="5.638888888888889in"}

### 4.1.1.3. Bounded Context Canvases {#bounded-context-canvases}

![](media/image25.png){width="6.267716535433071in"
height="3.486111111111111in"}

![](media/image26.png){width="6.267716535433071in"
height="3.4722222222222223in"}

### 4.1.2. Context Mapping {#context-mapping}

![](media/image27.jpg){width="5.598958880139983in"
height="3.720238407699038in"}

###   {#section-8}

### 4.1.3. Software Architecture {#software-architecture}

### 4.1.3.1. Software Architecture Context Level Diagrams  {#software-architecture-context-level-diagrams}

![](media/image28.png){width="6.267716535433071in"
height="2.888888888888889in"}

Propósito: Muestra una vista de alto nivel de tu sistema WaterGuard y
cómo interactúa con usuarios y sistemas externos.

En este caso:

- Muestra la relación entre las Comunidades Rurales (usuarios) y el
  sistema WaterGuard

- Visualiza cómo los diferentes sensores (nivel de agua, calidad,
  contaminantes) interactúan con tu sistema

- Proporciona una visión general sin detalles técnicos internos

Este diagrama responde a la pregunta: \"¿Cómo encaja WaterGuard en el
ecosistema más amplio?\"

Enlace:
<https://structurizr.com/share/101605/252b795e-2752-4795-ac08-b38ddae71479>

### 4.1.3.2. Software Architecture Container Level Diagrams {#software-architecture-container-level-diagrams}

![](media/image29.png){width="6.267716535433071in"
height="4.458333333333333in"}

Propósito: Desglosa tu sistema WaterGuard en sus principales componentes
técnicos o aplicaciones.

En tu caso:

- Muestra las cuatro partes principales: Web Application, Mobile App,
  API Application y Database

- Visualiza cómo estos contenedores se comunican entre sí

- Incluye detalles sobre tecnologías utilizadas (Angular, Flutter,
  Spring Boot, MySQL)

Este diagrama responde a la pregunta: \"¿Cuál es la arquitectura de alto
nivel del sistema WaterGuard?\"

### 4.1.3.3. Software Architecture Deployment Diagrams {#software-architecture-deployment-diagrams}

![](media/image30.png){width="6.267716535433071in"
height="3.6527777777777777in"}

## 4.2. Tactical-Level Domain-Driven Design {#tactical-level-domain-driven-design}

## 4.2.1. Bounded Context: Monitoreo de Niveles de Agua {#bounded-context-monitoreo-de-niveles-de-agua}

Propósito del Bounded Context:

El Domain Layer en este caso se gestiona principalmente dentro de la
API/Backend, lo que significa que las entidades y comportamientos que
antes serían parte del desarrollo personalizado ahora se presentan y
configuran.

### 4.2.1.1. Domain Layer {#domain-layer}

Este es el núcleo de la lógica de negocio, donde se definen las
entidades y los objetos de valor que representan las reglas del
monitoreo de niveles de agua.

|           |     |                                                         |     |
|-----------|-----|---------------------------------------------------------|-----|
| Nombre    |     | SensorNivelAgua                                         |     |
| Propósito |     | Representar un sensor IoT que mide los niveles de agua. |     |
| Atributos |     |                                                         |     |
|           |     |                                                         |     |
|           |     |                                                         |     |
|           |     |                                                         |     |
|           |     |                                                         |     |
|           |     |                                                         |     |
|           |     |                                                         |     |
|           |     |                                                         |     |
|           |     |                                                         |     |
|           |     |                                                         |     |
|           |     |                                                         |     |
|           |     |                                                         |     |

|                    |                 |                                                                     |                                                              |
|--------------------|-----------------|---------------------------------------------------------------------|--------------------------------------------------------------|
| Nombre             |                 | AlertaNivelAgua                                                     |                                                              |
| Propósito          |                 | Representar una alerta generada cuando el nivel de agua es crítico. |                                                              |
| Atributos          |                 |                                                                     |                                                              |
| Nombre             | Tipo de dato    | Visibilidad                                                         | Descripción                                                  |
| alertaId           | String          | private                                                             | Identificador único de la alerta.                            |
| tipoAlerta         | String          | public                                                              | Tipo de alerta (ej. Crítica, Moderada).                      |
| mensaje            | Float           | public                                                              | Mensaje detallado de la alerta.                              |
| fechaGeneracion    |                 | private                                                             | Fecha y hora en que se generó la alerta.                     |
| nivelCritico       |                 | private                                                             | Valor que disparó la alerta.                                 |
| Metodos            |                 |                                                                     |                                                              |
| Nombre             | Tipo de retorno | Visibilidad                                                         | Descripción                                                  |
| enviarNotificacion | Void            | public                                                              | Envía la alerta a los administradores o usuarios relevantes. |

Reglas y Eventos:

- Umbral de Nivel Crítico: Cuando el nivelActual de un sensor excede el
  umbralCritico, se genera un evento en la app móvil o web, que activa
  la AlertaNivelAgua.

- Eventos de Estado de Sensor: Si un sensor pasa a estado inactivo (por
  desconexión o falla), se genera un evento que también puede activar
  alertas para los administradores.

### 4.2.1.2. Interface Layer {#interface-layer}

El Interface Layer incluye las interfaces de usuario y los mecanismos
mediante los cuales los usuarios interactúan con los datos en tiempo
real de los gemelos digitales y las alertas generadas.

|                                                  |                                           |                                                                             |                                                                                                         |
|--------------------------------------------------|-------------------------------------------|-----------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| Nombre                                           |                                           | MonitoreoNivelAguaController                                                |                                                                                                         |
| tipo                                             |                                           | Controller                                                                  |                                                                                                         |
| Propósito                                        |                                           | Gestionar las solicitudes relacionadas con el monitoreo de niveles de agua. |                                                                                                         |
| Metodos                                          |                                           |                                                                             |                                                                                                         |
| Nombre                                           | Tipo de retorno                           | Visibilidad                                                                 | Descripción                                                                                             |
| obtenerEstadoSensores()                          | ResponseEntity\<List\<SensorNivelAgua\>\> | public                                                                      | Devuelve el estado de todos los sensores conectados, incluyendo su ubicación y el nivel de agua actual. |
| ajustarUmbral(sensorId: int, nuevoUmbral: float) | ResponseEntity\<String\>                  | public                                                                      | Permite que un administrador ajuste el umbral crítico de un sensor específico.                          |

|                                |                                           |                                                           |                                                                               |
|--------------------------------|-------------------------------------------|-----------------------------------------------------------|-------------------------------------------------------------------------------|
| Nombre                         |                                           | AlertaController                                          |                                                                               |
| tipo                           |                                           | Controller                                                |                                                                               |
| Propósito                      |                                           | Gestionar las alertas generadas por los sensores de agua. |                                                                               |
| Metodos                        |                                           |                                                           |                                                                               |
| Nombre                         | Tipo de retorno                           | Visibilidad                                               | Descripción                                                                   |
| obtenerAlertas()               | ResponseEntity\<List\<AlertaNivelAgua\>\> | public                                                    | Devuelve una lista de todas las alertas activas.                              |
| descartarAlerta(alertaId: int) | ResponseEntity\<String\>                  | public                                                    | Permite que un administrador descarte una alerta después de haberla manejado. |

### 4.2.1.3. Application Layer {#application-layer}

En esta capa se define la lógica que coordina los flujos de trabajo y
los procesos relacionados con el monitoreo de niveles de agua.

|                                       |                 |                                                           |                                                                 |
|---------------------------------------|-----------------|-----------------------------------------------------------|-----------------------------------------------------------------|
| Nombre                                |                 | AjustarUmbralCommandHandler                               |                                                                 |
| tipo                                  |                 | Command Handler                                           |                                                                 |
| Propósito                             |                 | Manejar el comando de ajuste de umbrales de los sensores. |                                                                 |
| Metodos                               |                 |                                                           |                                                                 |
| Nombre                                | Tipo de retorno | Visibilidad                                               | Descripción                                                     |
| handle(command: AjustarUmbralCommand) | Void            | public                                                    | Procesa el ajuste del umbral crítico para un sensor específico. |

|                                   |                 |                                                                           |                                                             |
|-----------------------------------|-----------------|---------------------------------------------------------------------------|-------------------------------------------------------------|
| Nombre                            |                 | GenerarAlertaCommandHandler                                               |                                                             |
| tipo                              |                 | Event Handler                                                             |                                                             |
| Propósito                         |                 | Gestionar la creación de una alerta cuando un nivel crítico es alcanzado. |                                                             |
| Metodos                           |                 |                                                                           |                                                             |
| Nombre                            | Tipo de retorno | Visibilidad                                                               | Descripción                                                 |
| handle(event: AlertaCriticaEvent) | Void            | public                                                                    | Genera una nueva alerta basada en el nivel de agua crítico. |

### 4.2.1.4. Infrastructure Layer {#infrastructure-layer}

En este caso, la infraestructura se apoya en las tecnologías IoT, lo que
reduce la cantidad de código personalizado que tu equipo necesita
desarrollar. A continuación, te explico cómo los servicios gestionados
manejan la infraestructura:

Base de Datos (opcional):

- Se puede utilizar una base de datos como MySQL para almacenar datos
  históricos de mediciones y alertas.

### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams ![](media/image31.png){width="5.268999343832021in" height="4.525038276465442in"} {#bounded-context-software-architecture-component-level-diagrams}

### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams {#bounded-context-software-architecture-code-level-diagrams}

En \"WaterGuard\", la arquitectura se divide en contextos bien definidos
que facilitan la gestión y el desarrollo del proyecto:

1.  Contexto de la Interfaz de Usuario (User Interface Context):

    - Este contexto está representado por el UI Web/App, que utiliza
      tecnologías como JavaScript y Angular. Aquí, el código está
      enfocado en proporcionar una experiencia de usuario amigable,
      visualización de datos y la interacción directa con el sistema a
      través de la web.

2.  Contexto de Reportes y Servicios (Reports and Services Context):

    - En este contexto están los componentes Reportes API y
      ReporteService, ambos usando Spring MVC REST Controller. El código
      en este contexto se centra en la lógica de negocio, como la
      generación de reportes, el manejo de peticiones y la comunicación
      con otros sistemas internos.

3.  Contexto de Conectividad de IoT (IoT Connectivity Context):

    - Este contexto involucra la API Network que es la que conectará con
      los dispositivos IoT para que se mantenga una lectura en tiempo
      real y poder realizar acciones automáticas.

4.  Contexto de Almacenamiento de Datos (Data Storage Context):

    - Aquí está el Database Reports con un esquema de base de datos
      MySQL. El código en este contexto se centra en la estructura de la
      base de datos, almacenamiento de reportes generados y consultas de
      datos históricos.

### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams {#bounded-context-domain-layer-class-diagrams}

![](media/image32.png){width="6.267716535433071in"
height="2.3333333333333335in"}

### 4.2.1.6.2. Bounded Context Database Design Diagram {#bounded-context-database-design-diagram}

![](media/image33.png){width="6.267716535433071in"
height="2.138888888888889in"}

## 4.2.2. Bounded Context: Análisis de Calidad de Agua {#bounded-context-análisis-de-calidad-de-agua}

Este bounded context se encarga de analizar la calidad del agua mediante
sensores IoT que miden parámetros como el pH, la turbidez, y otros
indicadores clave. Los datos son procesados y monitoreados en la
Aplicación Móvil o Web, donde se generan alertas y se disparan eventos
en caso de problemas en la calidad del agua.

### 4.2.2.1. Domain Layer {#domain-layer-1}

El Domain Layer de este bounded context también está en gran parte
gestionado por la Aplicación Web y Móvil, que modela los sensores de
calidad del agua y aplica las reglas de negocio para generar alertas.

|                                      |                 |                                                                    |                                                                           |
|--------------------------------------|-----------------|--------------------------------------------------------------------|---------------------------------------------------------------------------|
| Nombre                               |                 | SensorCalidadAgua                                                  |                                                                           |
| Propósito                            |                 | Representar un sensor IoT que mide parámetros de calidad del agua. |                                                                           |
| Atributos                            |                 |                                                                    |                                                                           |
| Nombre                               | Tipo de dato    | Visibilidad                                                        | Descripción                                                               |
| sensorId                             | Int             | private                                                            | Identificador único del sensor.                                           |
| ubicación                            | String          | private                                                            | Ubicación física del sensor.                                              |
| tipo                                 | String          | private                                                            | Tipo de sensor (pH, turbidez, conductividad).                             |
| estado                               | String          | public                                                             | Estado actual del sensor (activo/inactivo).                               |
| Metodos                              |                 |                                                                    |                                                                           |
| Nombre                               | Tipo de retorno | Visibilidad                                                        | Descripción                                                               |
| recibirMedicionCalidad(valor: float) | Void            | public                                                             | Recibe una medición de calidad del agua y actualiza el estado del sensor. |

|                                                       |                 |                                                           |                                                                            |
|-------------------------------------------------------|-----------------|-----------------------------------------------------------|----------------------------------------------------------------------------|
| Nombre                                                |                 | CalidadAgua                                               |                                                                            |
| Propósito                                             |                 | Almacenar y representar el estado de la calidad del agua. |                                                                            |
| Atributos                                             |                 |                                                           |                                                                            |
| Nombre                                                | Tipo de dato    | Visibilidad                                               | Descripción                                                                |
| valor                                                 | Float           | private                                                   | Valor del parámetro medido (por ejemplo, nivel de pH o turbidez).          |
| fechaMedicion                                         | Date            | private                                                   | Fecha y hora en que se realizó la medición.                                |
| sensorId                                              | Int             | private                                                   | Identificador del sensor que tomó la medición.                             |
| Metodos                                               |                 |                                                           |                                                                            |
| Nombre                                                | Tipo de retorno | Visibilidad                                               | Descripción                                                                |
| esCalidadAdecuada(umbralMin: float, umbralMax: float) | Boolean         | public                                                    | Verifica si el valor de la medición está dentro de los límites permitidos. |

|                 |                 |                                                                                    |                                                                          |
|-----------------|-----------------|------------------------------------------------------------------------------------|--------------------------------------------------------------------------|
| Nombre          |                 | AlertaCalidad                                                                      |                                                                          |
| Propósito       |                 | Generar una alerta cuando la calidad del agua cae fuera de los umbrales definidos. |                                                                          |
| Atributos       |                 |                                                                                    |                                                                          |
| Nombre          | Tipo de dato    | Visibilidad                                                                        | Descripción                                                              |
| tipo            | String          | public                                                                             | Tipo de alerta (pH alto, turbidez excesiva).                             |
| mensaje         | String          | public                                                                             | Detalles del problema detectado.                                         |
| fechaGeneracion | Date            | private                                                                            | Fecha en que se generó la alerta.                                        |
| Metodos         |                 |                                                                                    |                                                                          |
| Nombre          | Tipo de retorno | Visibilidad                                                                        | Descripción                                                              |
| generarAlerta() | Void            | public                                                                             | Crea una alerta basada en los valores críticos detectados por el sensor. |
| enviarAlerta()  | Void            | public                                                                             | Envía la alerta a los usuarios designados.                               |

### 4.2.2.2. Interface Layer {#interface-layer-1}

El Interface Layer maneja la interacción del sistema con los usuarios,
permitiendo que se monitoreen los niveles de calidad del agua y se
configuren los umbrales críticos.

|                                                       |                 |                                                                 |                                                                               |
|-------------------------------------------------------|-----------------|-----------------------------------------------------------------|-------------------------------------------------------------------------------|
| Nombre                                                |                 | CalidadAguaController                                           |                                                                               |
| tipo                                                  |                 | Controller                                                      |                                                                               |
| Propósito                                             |                 | Gestionar las solicitudes relacionadas con la calidad del agua. |                                                                               |
| Metodos                                               |                 |                                                                 |                                                                               |
| Nombre                                                | Tipo de retorno | Visibilidad                                                     | Descripción                                                                   |
| registrarMedicionCalidad(sensorId: int, valor: float) | Void            | public                                                          | Recibe y registra una medición de calidad del agua.                           |
| generarAlertaCalidad(sensorId: int, valor: float)     | Void            | public                                                          | Genera una alerta si la calidad del agua está fuera de los límites definidos. |

|                                            |                 |                                                                                                      |                                                                                               |
|--------------------------------------------|-----------------|------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| Nombre                                     |                 | AlertaCalidadService                                                                                 |                                                                                               |
| tipo                                       |                 | Service                                                                                              |                                                                                               |
| Propósito                                  |                 | Manejar la lógica de generación y envío de alertas cuando se detectan problemas de calidad del agua. |                                                                                               |
| Metodos                                    |                 |                                                                                                      |                                                                                               |
| Nombre                                     | Tipo de retorno | Visibilidad                                                                                          | Descripción                                                                                   |
| enviarAlerta(alerta: AlertaCalidad)        | Void            | public                                                                                               | Envía una notificación a los usuarios cuando se detecta una alerta de calidad.                |
| notificarSupervisor(alerta: AlertaCalidad) | Void            | public                                                                                               | Notifica a los supervisores o técnicos responsables cuando la calidad del agua es inadecuada. |

### 4.2.2.3. Application Layer {#application-layer-1}

En este Application Layer, las reglas de negocio que antes procesaban
manualmente los datos de calidad del agua han sido simplificadas
mediante la integración con el sistema de Waterguard que utiliza
sensores IoT para manejar gran parte del procesamiento.

|                                                  |                 |                                                                                                                  |                                                                     |
|--------------------------------------------------|-----------------|------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| Nombre                                           |                 | RegistrarMedicionCalidadCommandHandler                                                                           |                                                                     |
| tipo                                             |                 | Command Handler                                                                                                  |                                                                     |
| Propósito                                        |                 | Procesar el comando para registrar nuevas mediciones de calidad del agua y actualizar el estado de los sensores. |                                                                     |
| Metodos                                          |                 |                                                                                                                  |                                                                     |
| Nombre                                           | Tipo de retorno | Visibilidad                                                                                                      | Descripción                                                         |
| handle(command: RegistrarMedicionCalidadCommand) | Void            | public                                                                                                           | Procesa el comando para registrar una medición de calidad del agua. |

|                                   |                 |                                                                                                        |                                                                                                  |
|-----------------------------------|-----------------|--------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Nombre                            |                 | AlertaCalidadEventHandler                                                                              |                                                                                                  |
| tipo                              |                 | Event Handler                                                                                          |                                                                                                  |
| Propósito                         |                 | Manejar los eventos que son disparados por los sensores IoT, cuando la calidad del agua es inadecuada. |                                                                                                  |
| Metodos                           |                 |                                                                                                        |                                                                                                  |
| Nombre                            | Tipo de retorno | Visibilidad                                                                                            | Descripción                                                                                      |
| handle(event: AlertaCalidadEvent) | Void            | public                                                                                                 | Genera una alerta y envía una notificación cuando se detecta un problema en la calidad del agua. |

### 4.2.2.4. Infrastructure Layer {#infrastructure-layer-1}

En este layer se gestiona el acceso a servicios externos y la
persistencia de datos.

|                                    |                   |                                                                                                                     |                                                             |
|------------------------------------|-------------------|---------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| Nombre                             |                   | SensorCalidadRepository                                                                                             |                                                             |
| tipo                               |                   | Repository                                                                                                          |                                                             |
| Propósito                          |                   | Almacenar y recuperar las mediciones de calidad del agua en una base de datos si se requiere mantener un historial. |                                                             |
| Metodos                            |                   |                                                                                                                     |                                                             |
| Nombre                             | Tipo de retorno   | Visibilidad                                                                                                         | Descripción                                                 |
| guardar(sensor: SensorCalidadAgua) | Void              | protected                                                                                                           | Almacena un nuevo sensor de calidad.                        |
| obtener(sensorId: int)             | SensorCalidadAgua | protected                                                                                                           | Recupera la información de un sensor de calidad específico. |

|                                |                       |                                                                                                              |                                                               |
|--------------------------------|-----------------------|--------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| Nombre                         |                       | AlertaCalidadRepository                                                                                      |                                                               |
| tipo                           |                       | Repository                                                                                                   |                                                               |
| Propósito                      |                       | Almacenar y recuperar las alertas generadas por el sistema cuando se detectan problemas de calidad del agua. |                                                               |
| Metodos                        |                       |                                                                                                              |                                                               |
| Nombre                         | Tipo de retorno       | Visibilidad                                                                                                  | Descripción                                                   |
| guardar(alerta: AlertaCalidad) | Void                  | protected                                                                                                    | Persiste una alerta de calidad del agua en la base de datos.  |
| obtenerPorFecha(fecha: Date)   | List\<AlertaCalidad\> | protected                                                                                                    | Recupera todas las alertas generadas en una fecha específica. |

### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams![](media/image34.png){width="5.836805555555555in" height="4.7605839895013125in"} {#bounded-context-software-architecture-component-level-diagrams-1}

### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams {#bounded-context-software-architecture-code-level-diagrams-1}

En \"WaterGuard\", la arquitectura se divide en contextos bien definidos
que facilitan la gestión y el desarrollo del proyecto:

1.  Contexto de la Interfaz de Usuario (User Interface Context):

    - Este contexto está representado por el UI Web/App, que utiliza
      tecnologías como JavaScript y Angular. Aquí, el código está
      enfocado en proporcionar una experiencia de usuario amigable,
      visualización de datos y la interacción directa con el sistema a
      través de la web.

2.  Contexto de Reportes y Servicios (Reports and Services Context):

    - En este contexto están los componentes Reportes API y
      ReporteService, ambos usando Spring MVC REST Controller. El código
      en este contexto se centra en la lógica de negocio, como la
      generación de reportes, el manejo de peticiones y la comunicación
      con otros sistemas internos.

3.  Contexto de Almacenamiento de Datos (Data Storage Context):

    - Aquí está el Database Reports con un esquema de base de datos
      MySQL. El código en este contexto se centra en la estructura de la
      base de datos, almacenamiento de reportes generados y consultas de
      datos históricos.

### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams {#bounded-context-domain-layer-class-diagrams-1}

![](media/image35.png){width="6.267716535433071in"
height="2.7083333333333335in"}

### 4.2.2.6.2. Bounded Context Database Design Diagram {#bounded-context-database-design-diagram-1}

![](media/image36.png){width="6.267716535433071in"
height="2.4444444444444446in"}

## 4.2.3. Bounded Context: Generación de Reportes {#bounded-context-generación-de-reportes}

Propósito del Bounded Context:

Este bounded context se encarga de la generación automática y manual de
reportes relacionados con los datos de las operaciones del sistema. Los
reportes pueden incluir análisis sobre el rendimiento, consumo de
recursos, métricas del sistema, entre otros.

### 4.2.3.1. Domain Layer {#domain-layer-2}

Este es el núcleo de la lógica de negocio, donde se definen las
entidades y los objetos de valor que representan las reglas del
monitoreo de niveles de agua.

|                     |                         |                                                                    |                                                                                 |
|---------------------|-------------------------|--------------------------------------------------------------------|---------------------------------------------------------------------------------|
| Nombre              |                         | Reporte                                                            |                                                                                 |
| Propósito           |                         | Representar un reporte generado con los datos de los sensores IoT. |                                                                                 |
| Atributos           |                         |                                                                    |                                                                                 |
| Nombre              | Tipo de dato            | Visibilidad                                                        | Descripción                                                                     |
| reportId            | Int                     | private                                                            | Identificador único del reporte.                                                |
| tipoReporte         | String                  | private                                                            | Tipo de reporte generado (consumo, alertas, predicciones)                       |
| fechaGeneración     | Date                    | private                                                            | Fecha y hora en que se generó el reporte                                        |
| estadoReporte       | string                  | private                                                            | Estado actual del reporte (generado, en proceso, fallido)                       |
| datos               | string                  | private                                                            | Datos agregados del reporte provenientes de IoT y gemelos digitales.            |
| dispositivosIoT     | List\<DispositivoIoT\>  | private                                                            | Lista de dispositivos IoT que proporcionan los datos para el reporte.           |
| gemelosDigitales    | List\<Gemelos Digital\> | private                                                            | Lista de gemelos digitales que aportaron datos al reporte.                      |
| Metodos             |                         |                                                                    |                                                                                 |
| Nombre              | Tipo de retorno         | Visibilidad                                                        | Descripción                                                                     |
| generarReporte      | Void                    | public                                                             | Genera un reporte tomando datos de los sensores IoT y gemelos digitales.        |
| obtenerDatosIoT     | List\<String\>          | public                                                             | Obtiene los datos de los sensores IoT conectados a través de Azure IoT Hub      |
| obtenerDatosGemelos | List\<String\>          | public                                                             | Recopila los datos de los gemelos digitales almacenados en Azure Digital Twins. |
| validarReporte      | Boolean                 | public                                                             | Verifica si los datos son suficientes para generar el reporte solicitado.       |

Reglas y Eventos:

- Evento de Creación de Reporte: Se genera un evento cuando los
  dispositivos IoT transmiten datos suficientes a través de los
  dispositivos IoT y se actualiza la base de datos. Este evento dispara
  el proceso de generación del reporte.

- Evento de Alerta Crítica: Si durante la creación de un reporte se
  detecta que los datos exceden un umbral crítico (como una falla en un
  sensor o un valor fuera de rango), se genera un evento de alerta que
  notifica a los administradores.

- Evento de Reporte Fallado: Si ocurre una falla durante el proceso de
  recopilación de datos, como la desconexión de un dispositivo IoT o un
  error en la sincronización con la API que lee los datos en tiempo
  real, se genera un evento que marca el reporte como fallido y notifica
  al equipo de soporte.

### 4.2.3.2. Interface Layer {#interface-layer-2}

El Interface Layer incluye las interfaces de usuario y los mecanismos
mediante los cuales los usuarios interactúan con los datos en tiempo
real de los gemelos digitales y las alertas generadas.

|                  |                                   |                                                                                                |                                                                                                      |
|------------------|-----------------------------------|------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
| Nombre           |                                   | ReporterController                                                                             |                                                                                                      |
| tipo             |                                   | Controller                                                                                     |                                                                                                      |
| Propósito        |                                   | Gestiona las solicitudes relacionadas con la generación, visualización y descarga de reportes. |                                                                                                      |
| Metodos          |                                   |                                                                                                |                                                                                                      |
| Nombre           | Tipo de retorno                   | Visibilidad                                                                                    | Descripción                                                                                          |
| generarReporte() | ResponseEntity\<String\>          | public                                                                                         | Inicia la generación de un nuevo reporte, con los datos de los dispositivos IoT y gemelos digitales. |
| obtenerReporte   | ResponseEntity\<Reporte\>         | public                                                                                         | Permite al usuario obtener el reporte generado según los parámetros solicitados.                     |
| listarReportes   | ResponseEntity\<List\<Reporte\>\> | public                                                                                         | Devuelve una lista con todos los reportes generados y disponibles para consulta.                     |

### 4.2.3.3. Application Layer {#application-layer-2}

En esta capa se define la lógica que coordina los flujos de trabajo y
los procesos relacionados con la generación de reportes.

|                                        |                 |                                                                                                  |                                                                                                                      |
|----------------------------------------|-----------------|--------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| Nombre                                 |                 | GenerarReporteCommandHandler                                                                     |                                                                                                                      |
| tipo                                   |                 | Command Handler                                                                                  |                                                                                                                      |
| Propósito                              |                 | Manejar el comando para la generación de reportes con datos de sensores IoT y gemelos digitales. |                                                                                                                      |
| Metodos                                |                 |                                                                                                  |                                                                                                                      |
| Nombre                                 | Tipo de retorno | Visibilidad                                                                                      | Descripción                                                                                                          |
| handle(command: GenerarReporteCommand) | Void            | public                                                                                           | Procesa la generación de reportes utilizando datos obtenidos de dispositivos IoT y gemelos digitales en tiempo real. |

### 4.2.3.4. Infrastructure Layer {#infrastructure-layer-2}

En este caso, la infraestructura se apoya en Azure IoT Hub y Azure
Digital Twins, lo que reduce la cantidad de código personalizado que tu
equipo necesita desarrollar. A continuación, te explico cómo los
servicios gestionados manejan la infraestructura:

Repositorio de Reportes (Base de Datos)

Método: saveReport(): Persiste el reporte generado en la base de datos.

Método: getReportById(): Recupera un reporte específico utilizando su
reportId.

Método: getAllReports(): Recupera todos los reportes almacenados en la
base de datos.

Persistencia en la Base de Datos:

Los reportes generados, una vez validados, se almacenan en una base de
datos relacional (como MySQL), lo que permite su consulta futura.

### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams  {#bounded-context-software-architecture-component-level-diagrams-2}

### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams![](media/image37.png){width="6.267716535433071in" height="5.375in"} {#bounded-context-software-architecture-code-level-diagrams-2}

En \"WaterGuard\", la arquitectura se divide en contextos bien definidos
que facilitan la gestión y el desarrollo del proyecto:

1.  Contexto de la Interfaz de Usuario (User Interface Context):

    - Este contexto está representado por el UI Web/App, que utiliza
      tecnologías como JavaScript y Angular. Aquí, el código está
      enfocado en proporcionar una experiencia de usuario amigable,
      visualización de datos y la interacción directa con el sistema a
      través de la web.

2.  Contexto de Reportes y Servicios (Reports and Services Context):

    - En este contexto están los componentes Reportes API y
      ReporteService, ambos usando Spring MVC REST Controller. El código
      en este contexto se centra en la lógica de negocio, como la
      generación de reportes, el manejo de peticiones y la comunicación
      con otros sistemas internos.

3.  Contexto de Almacenamiento de Datos (Data Storage Context):

    - Aquí está el Database Reports con un esquema de base de datos
      MySQL. El código en este contexto se centra en la estructura de la
      base de datos, almacenamiento de reportes generados y consultas de
      datos históricos.

###   {#section-9}

### Conexiones y Relaciones entre Contextos:

- El Reports API interactúa con los registros de las base de datos en
  MySQL mediante los ReporteService.

- El UI Web/App es el punto de entrada para los usuarios, y se conecta
  al Reports API para solicitar información y mostrar reportes.

### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams {#bounded-context-domain-layer-class-diagrams-2}

![](media/image38.png){width="6.267716535433071in"
height="3.8194444444444446in"}

### 4.2.3.6.2. Bounded Context Database Design Diagram {#bounded-context-database-design-diagram-2}

![](media/image39.png){width="5.135416666666667in"
height="3.1145833333333335in"}

## 4.2.4. Bounded Context: Autenticación de Usuarios {#bounded-context-autenticación-de-usuarios}

Propósito del Bounded Context:

Gestionar el acceso seguro al sistema mediante la autenticación de
credenciales y la asignación de roles y permisos.

### 4.2.4.1. Domain Layer {#domain-layer-3}

Este es el núcleo de la lógica de negocio, donde se definen las
entidades y los objetos de valor que representan las reglas del
monitoreo de niveles de agua.

|                      |                 |                                                                                                                     |                                                                    |
|----------------------|-----------------|---------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|
| Nombre               |                 | Usuario                                                                                                             |                                                                    |
| Propósito            |                 | Representa a un usuario que interactúa con el sistema y cuyos credenciales son validados para autenticar su acceso. |                                                                    |
| Atributos            |                 |                                                                                                                     |                                                                    |
| Nombre               | Tipo de dato    | Visibilidad                                                                                                         | Descripción                                                        |
| reportId             | Int             | private                                                                                                             | Identificador único del usuario en el sistema.                     |
| nombreUsuario        | String          | private                                                                                                             | Nombre de usuario utilizado para iniciar sesión.                   |
| correoElectrónico    | Date            | private                                                                                                             | Correo electrónico del usuario registrado.                         |
| contraseña           | string          | private                                                                                                             | Contraseña del usuario, almacenada de manera segura.               |
| rol                  | string          | private                                                                                                             | Rol asignado al usuario                                            |
| estado               | String          | private                                                                                                             | Estado actual del usuario                                          |
| tokenSesion          | String          | private                                                                                                             | Token de autenticación generado al iniciar sesión.                 |
| Metodos              |                 |                                                                                                                     |                                                                    |
| Nombre               | Tipo de retorno | Visibilidad                                                                                                         | Descripción                                                        |
| iniciarSesión()      | Boolean         | public                                                                                                              | Autentica el usuario utilizando su nombre de usuario y contraseña, |
| cerrarSesión()       | void            | public                                                                                                              | Finaliza la sesión activa del usuario.                             |
| ActualizarContraseña | void            | public                                                                                                              | Actualiza la contraseña del usuario.                               |
| verificarToken       | Boolean         | public                                                                                                              | Verifica si el token de sesión del usuario es válido.              |

Reglas y Eventos:

- Regla de Autenticación Exitosa: Un usuario solo podrá acceder al
  sistema si su nombre de usuario y contraseña coinciden con los
  registrados, y su cuenta está activa.

- Regla de Bloqueo de Usuario: Si un usuario falla tres veces
  consecutivas al ingresar su contraseña, su cuenta será bloqueada y no
  podrá iniciar sesión hasta que un administrador la desbloquee.

- Regla de Expiración de Sesión: El token de sesión generado al iniciar
  sesión tiene una vigencia de 30 minutos. Si el token expira, el
  usuario será deslogueado automáticamente.

- Regla de Roles y Permisos: Dependiendo del rol asignado
  (administrador, usuario regular, invitado), el acceso a diferentes
  secciones del sistema estará limitado o permitido.

- Evento de Inicio de Sesión Exitoso: Cuando un usuario inicia sesión
  correctamente, se genera un evento que actualiza la última fecha y
  hora de inicio de sesión.

- Evento de Intento Fallido: Si el intento de inicio de sesión falla, se
  genera un evento que incrementa el contador de intentos fallidos para
  el usuario.

- Evento de Bloqueo de Cuenta: Si el usuario falla tres veces
  consecutivas al ingresar sus credenciales, se genera un evento de
  bloqueo, notificando al equipo de soporte o administrador.

- Evento de Cierre de Sesión: Cuando un usuario cierra sesión
  manualmente o su sesión expira, se genera un evento para cerrar la
  sesión y revocar el token de autenticación.

### 4.2.4.2. Interface Layer {#interface-layer-3}

|                         |                           |                                                                                                                   |                                                                         |
|-------------------------|---------------------------|-------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|
| Nombre                  |                           | AutenticacionController                                                                                           |                                                                         |
| tipo                    |                           | Controller                                                                                                        |                                                                         |
| Propósito               |                           | Gestionar las solicitudes relacionadas con el inicio de sesión, cierre de sesión y actualización de credenciales. |                                                                         |
| Metodos                 |                           |                                                                                                                   |                                                                         |
| Nombre                  | Tipo de retorno           | Visibilidad                                                                                                       | Descripción                                                             |
| iniciarSesion()         | ResponseEntity\<String\>  | public                                                                                                            | Inicia sesión validando las credenciales del usuario.                   |
| cerrarSesion()          | ResponseEntity\<String\>  | public                                                                                                            | Cierra la sesión activa del usuario y revoca el token de autenticación. |
| verificarTokenSession() | ResponseEntity\<Boolean\> | public                                                                                                            | Verifica si el token de sesión es válido o si ha expirado.              |

### 4.2.4.3. Application Layer {#application-layer-3}

En esta capa se define la lógica que coordina los flujos de trabajo y
los procesos relacionados con la Autenticación de usuarios..

|                     |                 |                                                                                                           |                                                                                                   |
|---------------------|-----------------|-----------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| Nombre              |                 | AutenticacionService                                                                                      |                                                                                                   |
| tipo                |                 | Command Handler                                                                                           |                                                                                                   |
| Propósito           |                 | Proporciona la lógica de negocio para autenticar usuarios, gestionar tokens de sesión y bloquear cuentas. |                                                                                                   |
| Metodos             |                 |                                                                                                           |                                                                                                   |
| Nombre              | Tipo de retorno | Visibilidad                                                                                               | Descripción                                                                                       |
| autenticarUsuario() | Boolean         | public                                                                                                    | Verifica las credenciales del usuario y genera un token de sesión si la autenticación es exitosa. |

### 4.2.4.4. Infrastructure Layer {#infrastructure-layer-3}

En este caso, la infraestructura se apoya en servicios de seguridad
externa para gestionar la autenticación y los tokens de sesión. A
continuación, te explico cómo los servicios gestionados manejan la
infraestructura:

UsuarioRepository (Base de Datos de Usuarios)

Este componente es responsable de la persistencia de los usuarios y sus
credenciales en la base de datos.

Método: saveUsuario(): Persiste la información del usuario en la base de
datos.

Método: findByUsername(): Busca un usuario en la base de datos por su
nombre de usuario o correo electrónico.

Método: updateUsuario(): Actualiza la información del usuario existente
(ej. cambio de contraseña, estado de cuenta).

Método: deleteUsuario(): Elimina un usuario de la base de datos.

TokenManager (Servicio de Gestión de Tokens)

Este componente gestiona la creación, validación y expiración de tokens
de sesión para los usuarios.

Método: generateToken(): Genera un token de autenticación único y con
tiempo de expiración.

Método: validateToken(): Valida si el token de autenticación es válido o
ha expirado.

Método: revokeToken(): Invalida un token cuando un usuario cierra sesión
o cuando caduca.

PasswordEncryptor (Servicio de Encriptación de Contraseñas)

Este componente maneja la encriptación y verificación de contraseñas de
manera segura.

Método: encryptPassword(): Encripta una contraseña antes de ser
almacenada en la base de datos.

Método: verifyPassword(): Verifica si la contraseña ingresada coincide
con la encriptada almacenada.

Método: updatePassword(): Actualiza y encripta una nueva contraseña
cuando el usuario decide cambiarla.

### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams  {#bounded-context-software-architecture-component-level-diagrams-3}

### ![](media/image40.png){width="6.267716535433071in" height="5.333333333333333in"} {#section-10}

### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams {#bounded-context-software-architecture-code-level-diagrams-3}

En \"WaterGuard\", la arquitectura se divide en contextos bien definidos
que facilitan la gestión y el desarrollo del proyecto:

1.  Contexto de la Interfaz de Usuario (User Interface Context):

    - Este contexto está representado por el UI Web/App, que utiliza
      tecnologías como JavaScript y Angular. Aquí, el código está
      enfocado en proporcionar una experiencia de usuario amigable,
      visualización de datos y la interacción directa con el sistema a
      través de la web.

2.  Contexto de Reportes y Servicios (Reports and Services Context):

    - En este contexto están los componentes Reportes API y
      ReporteService, ambos usando Spring MVC REST Controller. El código
      en este contexto se centra en la lógica de negocio, como la
      generación de reportes, el manejo de peticiones y la comunicación
      con otros sistemas internos.

3.  Contexto de Almacenamiento de Datos (Data Storage Context):

    - Aquí está el Database Reports con un esquema de base de datos
      MySQL. El código en este contexto se centra en la estructura de la
      base de datos, almacenamiento de reportes generados y consultas de
      datos históricos.

### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams {#bounded-context-domain-layer-class-diagrams-3}

![](media/image41.png){width="6.267716535433071in"
height="3.6805555555555554in"}

### 4.2.4.6.2. Bounded Context Database Design Diagram {#bounded-context-database-design-diagram-3}

![](media/image42.png){width="2.5416666666666665in"
height="3.3333333333333335in"}

# Capítulo V: Solution UX Design

## 5.1. Style Guidelines {#style-guidelines}

### 5.1.1. General Style Guidelines {#general-style-guidelines}

El objetivo de esta sección es crear un repositorio central organizado
de recursos visuales que todo el equipo pueda utilizar. Esto garantizará
que la presentación visual sea coherente y consistente en todos los
proyectos, permitiendo que los elementos clave, como activos gráficos,
colores, fuentes y otros detalles, sean aplicados de manera uniforme a
lo largo de todos los productos desarrollados.

#### Branding

El logo de WaterGuard refleja un enfoque técnico y centrado en la
gestión eficiente de los recursos hídricos, utilizando la gota como
símbolo del agua y una herramienta que representa la tecnología y el
mantenimiento. Para mantener la coherencia con el logo, es esencial que
los demás elementos de branding refuercen esta dualidad de tecnología y
sostenibilidad, alineándose con los valores fundamentales del proyecto.

- Tono general: Innovador, tecnológico y accesible.

#### Imágenes

Seleccionamos imágenes que reflejan tecnología, sostenibilidad y
eficiencia en la gestión del agua. Nos enfocamos en evitar gráficos
recargados, optando por imágenes limpias y precisas que transmiten una
sensación de orden y claridad. Este enfoque visual refuerza la
naturaleza técnica del producto y mejora la percepción de la marca.

#### Íconos

Los íconos que usamos son sencillos y estilizados, manteniendo una línea
gráfica alineada con la estética del logo. Utilizamos formas redondeadas
y líneas suaves, lo que asegura que todos los gráficos complementan el
estilo técnico pero amigable de la marca, facilitando su comprensión y
uso.

### Tipografía

La tipografía debe ser clara, legible y profesional, reforzando la
imagen moderna y profesional de nuestro proyecto.

- Tipografía principal: Utilizamos fuentes sans-serif modernas como
  *Roboto* o *Montserrat* para encabezados, subtítulos y botones. Estas
  fuentes se combinan perfectamente con el estilo minimalista y
  tecnológico del logo, proporcionando una experiencia visual limpia y
  profesional.

- Tipografía secundaria: Para el cuerpo del texto, usamos una fuente
  sans-serif más ligera o simple que asegure la legibilidad y mantenga
  un aspecto profesional y accesible.

#### Jerarquía

- Encabezados (H1, H2, H3): Usamos tamaños grandes y llamativos, con
  negrita para los títulos clave, asegurando que los usuarios puedan
  identificar rápidamente la información más importante.

- Cuerpo de texto: Mantenemos un tamaño de fuente entre 14px y 16px, lo
  que facilita la lectura y garantiza una experiencia cómoda en todos
  los dispositivos.

- Botones: Los botones importantes, como los de llamada a la acción
  (CTA), usan letras mayúsculas para destacarse, lo que los hace más
  visibles y fáciles de encontrar en la interfaz.

### Colors (Colores)

La paleta de colores se inspira en el logo de WaterGuard, que
proporciona los colores fundamentales para la interfaz y el diseño
general del producto.

#### Colores principales

- Azul (#0080ff): Este color evoca confianza y tecnología. Lo usamos en
  los elementos clave de la interfaz, como encabezados, botones
  primarios y enlaces, para transmitir un enfoque serio y moderno.

> ![](media/image43.png){width="0.925524934383202in"
> height="0.4659536307961505in"}

- Blanco (#ffffff): El blanco ayuda a crear contraste y mantiene una
  sensación de limpieza y simplicidad. Se utiliza principalmente en
  fondos y secciones de texto para asegurar una visualización clara y
  ordenada.

> ![](media/image44.png){width="0.913086176727909in"
> height="0.913086176727909in"}

- Gris oscuro (#333333): Este color es ideal para textos secundarios o
  fondos contrastantes, dándole un aire más profesional y serio a la
  página.  
  ![](media/image45.png){width="1.078125546806649in"
  height="0.565926290463692in"}

#### Colores secundarios

- Tonos claros de azul (#a3d1ff): Se usan para fondos o áreas que
  necesitan un toque sutil de color sin sobrecargar la página
  visualmente.

#### Colores de acento

- Naranja claro (#ff6600): Se utiliza en los elementos de llamada a la
  acción (CTA), como botones de acción, para destacarlos y captar la
  atención del usuario rápidamente.

#### Accesibilidad

Nos aseguramos de que los colores elegidos cumplan con los requisitos de
contraste para mejorar la legibilidad, especialmente en botones y textos
sobre fondos oscuros, garantizando una experiencia accesible para todos
los usuarios.

### Spacing (Espaciado)

El uso adecuado del espacio es crucial para una buena experiencia visual
y de navegación, asegurando que los elementos no estén sobrecargados.

- Espaciado entre secciones: Mantenemos suficiente espacio entre las
  secciones para evitar que la página se sienta saturada o abrumada.
  Esto mejora la legibilidad y facilita la navegación entre secciones.

- Márgenes y padding: Usamos una escala modular de espaciado (por
  ejemplo, 8px, 16px, 24px) para mantener la coherencia visual en toda
  la interfaz.

- Líneas de texto: En dispositivos móviles, mantenemos las líneas de
  texto dentro de un rango óptimo de 60 a 75 caracteres por línea,
  asegurando que el texto sea fácil de leer y no se sienta apretado.

### Tono de Comunicación

El tono en el que presentamos el contenido debe ser accesible,
profesional y reflejar la tecnología avanzada que respalda el proyecto.

- Divertido/Serio: Aunque el proyecto tiene una base técnica, el tono se
  mantiene accesible y amigable para humanizar la marca, sin perder el
  enfoque profesional.

- Formal/Casual: Usamos un tono casual profesional, lo suficientemente
  amigable para invitar a la interacción, pero con la seriedad que
  inspira confianza y respeto en los usuarios.

- Respetuoso/Irreverente: El tono es respetuoso y educativo, sin espacio
  para la irreverencia. Nos aseguramos de que todos los mensajes sean
  claros y útiles.

- Entusiasta/Sereno: Queremos transmitir entusiasmo por la tecnología,
  pero siempre con una sensación de calma y confianza.

### 5.1.2. Web, Mobile & Devices Style Guidelines {#web-mobile-devices-style-guidelines}

En esta sección, definimos los estándares visuales y de interacción para
interfaces web responsivas y aplicaciones móviles nativas, asegurando
que el producto sea coherente, intuitivo y accesible en todas las
plataformas y dispositivos.

#### Interfaces Web Responsivas

El diseño responsivo asegura que la interfaz web se adapte adecuadamente
a diferentes resoluciones y tamaños de pantalla, desde monitores de
escritorio hasta dispositivos móviles.

##### Layout (Diseño del Layout)

Para garantizar un diseño fluido y adaptable, utilizamos un sistema de
grid fluido. En el caso de escritorio, empleamos un sistema de 12
columnas, y para dispositivos móviles, utilizamos entre 4 y 6 columnas
para optimizar el espacio y la visualización.

Definimos puntos de quiebre clave para ajustar el diseño en diferentes
tamaños de pantalla:

- Desktop: \>= 1200px

- Tablet: entre 768px y 1199px

- Mobile: \<= 767px

Priorizamos el contenido más importante en dispositivos móviles. Esto se
logra utilizando menús desplegables para la navegación y reduciendo el
contenido visual innecesario, lo que garantiza una experiencia de
usuario eficiente en pantallas pequeñas.

##### Tipografía

Nos aseguramos de que la tipografía sea escalable según el tamaño del
dispositivo. Por ejemplo, en pantallas de escritorio usamos una fuente
de 16px, mientras que en móviles reducimos a 14px para mantener la
legibilidad.

Además, mantenemos un interlineado adecuado (1.5x) en dispositivos
móviles para facilitar la lectura.

##### Imágenes y Medios

Utilizamos imágenes responsivas que se ajustan automáticamente al tamaño
del contenedor, sin perder calidad. Para optimizar el rendimiento en
móviles, usamos imágenes en formato WebP y aplicamos técnicas de lazy
loading para cargar las imágenes solo cuando sea necesario.

##### Interacción

Implementamos estados hover y focus visibles en pantallas grandes, y en
móviles, estos estados se traducen en acciones táctiles. También
soportamos gestos móviles, como el deslizamiento (swipe) para facilitar
la navegación y otras interacciones en dispositivos móviles.

#### Interfaces Nativas en Móviles

El diseño de nuestras aplicaciones móviles nativas está pensado para
ofrecer una experiencia consistente y eficiente, tomando en cuenta las
diferencias de interacción y rendimiento entre plataformas (iOS y
Android).

##### Diseño Nativo para iOS y Android

Para iOS, seguimos las Human Interface Guidelines (HIG) de Apple,
priorizando un diseño limpio con amplio espacio blanco, iconografía
simplificada y gestos nativos, como el deslizamiento hacia atrás.

Para Android, aplicamos las pautas de Material Design de Google, que
hacen uso de capas, sombras y colores vibrantes, asegurando que los
elementos interactivos ofrezcan retroalimentación visual clara al
tocarlos (ripple effect).

##### Tipografía Móvil

En dispositivos móviles, utilizamos un tamaño mínimo de fuente de 14px
para garantizar la legibilidad. Utilizamos tipografías nativas del
sistema operativo, como San Francisco para iOS y Roboto para Android,
para mejorar la experiencia del usuario.

##### Botones y Áreas de Toque

Aseguramos que todas las áreas de toque (como botones y enlaces) tengan
un tamaño mínimo de 44px por 44px, lo que facilita el toque en pantallas
pequeñas. Además, los botones primarios se destacan con colores
llamativos, mientras que los secundarios se mantienen discretos con
colores neutros o con borde.

##### Navegación y Gestos

La navegación en nuestras aplicaciones móviles está optimizada para
pantallas más pequeñas. Implementamos un menú tabular en la barra de
navegación inferior, asegurando un acceso rápido a las secciones más
importantes, como Dashboard, Alertas, Historial de datos y
Configuración.

Soportamos gestos nativos para navegación, como deslizar hacia la
derecha para regresar o deslizar hacia arriba para abrir menús
adicionales.

##### Rendimiento

Minimizamos los tiempos de carga mediante la optimización de imágenes y
scripts. Implementamos caché y pre-fetching para mejorar la experiencia
de usuario y garantizar una navegación fluida.

#### Consistencia en la Web y Móvil

Aunque las plataformas puedan diferir en algunas características,
mantenemos una coherencia visual y de interacción entre la versión web y
las aplicaciones móviles, asegurando que la experiencia sea fluida sin
importar el dispositivo utilizado.

##### Colores y Tipografía

La paleta de colores y la tipografía se mantienen consistentes en todas
las plataformas para reforzar la identidad visual del producto. Usamos
los mismos colores y fuentes en web y móvil para asegurar una
experiencia unificada.

##### Iconografía

Utilizamos un conjunto de iconos común en ambas plataformas,
asegurándonos de que los iconos sean sencillos y fácilmente
reconocibles. En la versión móvil, los iconos están diseñados para ser
lo suficientemente grandes como para ser tocados cómodamente.

##### Estilos de Interacción

Los botones de acción principal se mantienen prominentes en ambas
plataformas, manteniendo el mismo color y estilo visual. Además,
implementamos estados de carga claros (como spinners y loaders) cuando
se realizan acciones en ambas plataformas para asegurar una buena
experiencia de usuario.

## 5.2. Information Architecture {#information-architecture}

La arquitectura de la información está pensada para estructurar el
contenido de manera que los usuarios puedan adaptarse rápidamente a la
navegación y funcionalidades tanto en la landing page como en la
aplicación web y móvil. Nuestra prioridad es lograr que esta
organización sea intuitiva, accesible y fluida, permitiendo al usuario
encontrar lo que necesita sin esfuerzo ni confusión. Esta estructura
contempla decisiones relacionadas con la forma en la que se jerarquiza,
etiqueta, navega y busca la información.

#### **Jerarquía Visual**

Estamos aplicando una jerarquía visual clara que dirige la atención del
usuario hacia los elementos más importantes de cada interfaz.

- **Landing Page:** Hemos posicionado el título principal y el botón de
  llamada a la acción (CTA) como los elementos más destacados,
  ubicándolos en la parte superior con suficiente contraste visual para
  generar interés inmediato.

- **Aplicaciones Web y Móvil:** Cada sección está encabezada por títulos
  jerárquicos y legibles, seguidos de bloques de contenido estructurado
  con niveles de prioridad visual definidos por tamaños de fuente,
  colores y espaciado.

#### **Organización Secuencial**

Estamos guiando al usuario mediante una narrativa secuencial que le
permite avanzar paso a paso a través de la experiencia.

- **Landing Page:** El flujo está diseñado para presentar primero el
  problema, luego las funcionalidades clave, los beneficios, testimonios
  y finalmente un llamado a la acción claro. Esta estructura acompaña al
  usuario desde el descubrimiento hasta la conversión.

- **Onboarding en App Móvil:** El recorrido inicial de nuevos usuarios
  presenta funcionalidades clave en pantallas sucesivas, facilitando el
  entendimiento progresivo de la plataforma sin saturación de
  información.

#### **Organización Matricial**

Para secciones que requieren exploración libre o visualización de datos,
estamos aplicando una organización matricial flexible.

- **Dashboard Web:** El usuario puede acceder a diferentes widgets de
  monitoreo y control (como consumo, calidad del agua o estado de las
  bombas) de manera paralela, filtrando por ubicación o periodo de
  tiempo según necesidad.

- **Listados y Tablas:** Los datos se presentan con opciones de
  ordenamiento y filtrado para permitir a cada usuario decidir cómo
  desea ver la información, sin imponer una ruta única de navegación.

#### **Categorización del Contenido**

Estamos organizando el contenido según estructuras lógicas que faciliten
su acceso dependiendo del tipo de información o del perfil del usuario.

- **Por Tópico:** La navegación principal categoriza las secciones como
  \"Inicio\", \"Funcionalidades\", \"Beneficios\", \"Descarga\" y
  \"Contacto\", permitiendo una exploración clara.

- **Por Audiencia:** Las futuras versiones de la aplicación contemplan
  vistas personalizadas para distintos perfiles como administradores,
  técnicos y usuarios residenciales.

## 5.2.2. Labeling Systems {#labeling-systems}

Hemos implementado un sistema de etiquetado simple, coherente y
accesible, que permite a los usuarios identificar rápidamente las
secciones y funcionalidades, sin ambigüedades ni sobrecarga de
información.

#### **Simplicidad en las Etiquetas**

Usamos etiquetas claras y breves que reflejan de forma directa el
contenido que representan.

- En la sección de precios, usamos \"Planes\".

- En configuraciones, usamos \"Ajustes\".

- En el menú principal, cada enlace responde con precisión al contenido
  al que se dirige.

#### **Consistencia en el Etiquetado**

Nos aseguramos de que cada término o etiqueta se mantenga igual en todos
los puntos de contacto con el usuario.

- Si un botón se llama \"Descargar App\" en la landing page, ese mismo
  nombre se mantiene en la app.

- Las secciones \"Funcionalidades\" o \"Beneficios\" aparecen con la
  misma etiqueta en todas las plataformas.

#### **Evitar la Sobrecarga de Información**

Las etiquetas están diseñadas para ser concisas y no abrumar al usuario.

- En formularios, se usan términos como \"Nombre\" y \"Correo
  electrónico\" en lugar de frases extensas o técnicas.

#### **Asociaciones Claras**

Cada etiqueta está claramente vinculada al contenido o acción
correspondiente, eliminando cualquier posibilidad de duda en la
navegación.

- Las categorías como \"Monitoreo\", \"Alertas\", \"Configuración\" o
  \"Reportes\" aparecen como opciones directas y autoexplicativas en la
  navegación.

Este enfoque asegura una experiencia de usuario clara, simple y eficaz
en todos los entornos del producto.

#### 5.2.3. SEO Tags and Meta Tags {#seo-tags-and-meta-tags}

La estructura de etiquetas y metaetiquetas ha sido diseñada para
optimizar la visibilidad de WaterGuard en motores de búsqueda,
asegurando que los usuarios encuentren fácilmente la landing page y
comprendan su propuesta de valor desde los primeros resultados.

**Título (Title Tags)**

- **Landing Page:  
  ** WaterGuard - Optimiza la Gestión de Agua con Tecnología IoT.

> Este título combina claridad y enfoque SEO al incluir términos clave
> como "gestión de agua" e "IoT". También transmite el valor central del
> producto de forma breve y profesional.

- **Web Application:  
  ** WaterGuard Web App - Monitoreo y Control Inteligente de Recursos
  Hídricos.

> Este título está orientado a usuarios que ya utilizan la aplicación y
> refuerza las capacidades principales como el monitoreo en tiempo real
> y la automatización de bombas de agua.

**Meta Descriptions**

- **Landing Page:  
  **WaterGuard optimiza el uso de agua en tu hogar con tecnología IoT.
  Monitorea niveles, controla bombas y recibe alertas en tiempo real
  desde tu móvil.

> Esta descripción está alineada con los textos reales utilizados en la
> sección principal de la landing page, e incorpora palabras clave de
> alto valor.

- **Web Application:  
  **Gestiona y automatiza tu sistema de agua desde una plataforma
  centralizada. Accede a estadísticas, alertas y control de bombas al
  instante.

> Redactada para resaltar los beneficios más relevantes para usuarios
> activos dentro del entorno de la aplicación.

**Keywords**

- **Landing Page:  
  **WaterGuard, gestión de agua, monitoreo en tiempo real, IoT, control
  de bombas, sensores de agua, sostenibilidad.

> Las palabras clave se seleccionaron a partir del contenido real
> utilizado en la interfaz y los beneficios técnicos ofrecidos por el
> sistema.

- **Web Application:  
  **Aplicación de monitoreo de agua, control de bombas de agua, ahorro
  hídrico, automatización IoT, estadísticas de consumo.

> Estas keywords están pensadas para posicionar la aplicación en
> entornos de búsqueda más técnicos y orientados a usuarios con
> intención de compra o implementación.

**Author**

> Author: Equipo de WaterGuard
>
> Se mantiene una identificación clara del equipo desarrollador,
> promoviendo confianza, transparencia y coherencia con la sección de
> contacto y pie de página.

## 5.2.4. Searching Systems {#searching-systems}

El sistema de búsqueda dentro de WaterGuard está diseñado para ayudar a
los usuarios a encontrar información específica de manera rápida y
eficiente, tanto en la landing page como en las futuras versiones de la
aplicación. Se prioriza la facilidad de uso, la claridad en los
resultados y una experiencia de usuario optimizada.

**Búsqueda por palabra clave  
** Se ha incorporado una barra de búsqueda accesible y siempre visible
en los dispositivos de escritorio. Esta barra permite al usuario
ingresar palabras clave para localizar contenido relacionado con
funcionalidades, beneficios o secciones de contacto. Su diseño es
minimalista y se adapta visualmente al entorno general de la interfaz,
utilizando bordes suaves, tipografía clara y contraste adecuado para
garantizar la legibilidad.

**Filtros avanzados  
** En futuras implementaciones dentro del entorno web o móvil, el
sistema de búsqueda integrará filtros avanzados. Estos filtros
permitirán ordenar resultados por categoría, relevancia o fecha,
facilitando una exploración más dirigida y personalizada de la
información.

**Presentación de resultados  
** Los resultados se mostrarán de forma clara y estructurada. Cada
resultado destacará visualmente los términos buscados y permitirá
acceder al contenido con un solo clic o toque. En dispositivos móviles,
los resultados se presentarán en tarjetas verticales de lectura ágil y
amigable para pantallas pequeñas.

### 5.2.5. Navigation Systems {#navigation-systems}

La navegación en WaterGuard ha sido diseñada para guiar a los usuarios a
través de la interfaz de manera intuitiva, clara y sin fricciones, ya
sea desde la landing page informativa o desde la aplicación web y móvil.
Cada decisión en la arquitectura de navegación busca facilitar el acceso
rápido a la información más relevante, promoviendo una experiencia
fluida y centrada en el usuario.

#### **Principios Clave de la Navegación**

**Claridad:  
** Nos aseguramos de que la estructura de navegación sea comprensible
desde el primer momento. Los usuarios deben reconocer fácilmente dónde
están dentro del sitio o la aplicación y cómo desplazarse a otras
secciones importantes sin esfuerzo adicional.

**Accesibilidad:  
** La navegación es accesible en todo momento, tanto en dispositivos de
escritorio como móviles. Esto incluye una estructura coherente en el
menú principal, íconos visibles, y adaptabilidad en pantallas pequeñas
sin sacrificar funcionalidad.

**Consistencia:  
** Mantenemos un sistema de navegación uniforme en todos los entornos
del producto, evitando que el usuario deba reaprender patrones al
cambiar de plataforma.

**Reducción del esfuerzo cognitivo:  
** Minimizamos el número de clics o toques necesarios para llegar a cada
funcionalidad. Las rutas de acceso están optimizadas para reducir el
tiempo de interacción y mejorar la productividad del usuario.

#### **Estructura de la Navegación**

##### **Menú Principal**

En la landing page y la aplicación, el menú principal cumple como punto
de entrada a las secciones más importantes del sistema. Este menú está
disponible de forma persistente y ha sido optimizado para pantallas
grandes y pequeñas.

- **Inicio:** Redirige al usuario a la parte superior de la página o a
  la vista principal de la aplicación.

- **Funcionalidades / Servicios:** Sección que resume los beneficios
  clave del sistema.

- **Descarga o Registro:** Espacio dedicado a llevar al usuario a
  instalar la aplicación o iniciar sesión.

- **Contacto:** Acceso rápido para comunicarse con el equipo de soporte
  o realizar consultas.

En la versión móvil, se implementa un menú tipo hamburguesa que permite
ocultar las opciones bajo un ícono compacto, desplegable al toque. Esta
técnica mejora la experiencia en dispositivos pequeños sin perder acceso
a las funciones esenciales.

##### **Navegación en la Landing Page**

La navegación en la landing page está estructurada para conducir al
usuario desde el primer mensaje hasta la conversión. El diseño
secuencial guía a través de:

- **Botones CTA (Call-To-Action):** Como \"Descargar Ahora\" o
  \"Contáctanos\", ubicados estratégicamente en la Hero Section y
  repetidos a lo largo del scroll para maximizar el acceso.

- **Desplazamiento fluido por secciones:** Permite al usuario navegar
  entre bloques como Beneficios, Cómo Funciona, y Testimonios sin
  interrupciones visuales.

- **Navegación por anclas:** Utilizamos enlaces internos para saltar
  entre secciones clave sin recargar la página, optimizando la
  experiencia del usuario.

##### **Navegación en la Web App**

La aplicación web emplea una estructura que prioriza el acceso inmediato
a funcionalidades críticas:

- **Menú lateral (desktop) o superior desplegable (móvil):** Incluye
  accesos directos a Dashboard, Alertas, Historial, y Configuración.

- **Organización jerárquica:** Permite profundizar en vistas más
  detalladas sin perder el contexto de navegación.

- **Marcadores visuales:** Se usan íconos intuitivos y etiquetas
  legibles para reforzar la comprensión de cada sección.

##### **Breadcrumbs**  {#breadcrumbs}

En vistas internas o con múltiples niveles de navegación, implementamos
breadcrumbs que permiten al usuario ubicarse rápidamente dentro de la
plataforma.

"Inicio \> Monitoreo \> Sensores Activos."

Esto aporta claridad contextual y mejora la eficiencia al retroceder.

#### **Funcionalidades de Navegación en la App Móvil**

Para la aplicación nativa móvil, se adopta una barra de navegación
inferior que ofrece accesos rápidos a:

- **Dashboard:** Visión general del estado de los tanques y sensores.

- **Alertas:** Registro de eventos o notificaciones críticas.

- **Historial:** Visualización de datos pasados con opciones de
  filtrado.

- **Configuración:** Preferencias del usuario, alertas personalizadas, y
  ajustes generales.

Se incorporan también **gestos intuitivos**, como el deslizamiento hacia
la derecha para volver a la pantalla anterior o hacia arriba para
desplegar menús adicionales, mejorando la navegación táctil sin saturar
la interfaz.

#### **Accesibilidad y Usabilidad**

La accesibilidad está integrada desde el diseño, asegurando que personas
con distintas capacidades puedan utilizar la plataforma sin
restricciones.

- **Teclas de acceso rápido (web):** Facilitamos la navegación sin mouse
  mediante combinaciones de teclado.

- **Compatibilidad con lectores de pantalla:** Todos los elementos
  interactivos están etiquetados mediante estándares ARIA para facilitar
  la lectura asistida.

- **Tamaño de botones:** Se garantiza un área mínima de toque de 44px
  por 44px en todos los dispositivos móviles, mejorando la experiencia
  táctil incluso para usuarios con dedos grandes o movilidad reducida.

#### **Retroalimentación Visual y Navegación Activa**

- **Estados Hover y Active:** En la versión web, los elementos de
  navegación responden al cursor con cambios sutiles de color o
  subrayado, indicando interactividad.

- **Indicadores de progreso:** En flujos secuenciales como el registro
  de usuario o configuración inicial, mostramos una barra de avance
  visual que indica en qué etapa se encuentra el usuario.

## 5.3. Landing Page UI Design {#landing-page-ui-design}

En esta sección, presentamos nuestra propuesta de diseño de la interfaz
de usuario (UI) para la **Landing Page de WaterGuard**. El diseño
implementado es resultado directo de las decisiones estratégicas tomadas
en cuanto a arquitectura de la información, jerarquía visual y
lineamientos de estilo definidos previamente en este documento.

El objetivo principal de la interfaz es guiar al usuario desde el primer
contacto hasta una acción clara, como descargar la app, explorar sus
funcionalidades o establecer contacto. La navegación ha sido diseñada
para ser **fluida e intuitiva**, con especial énfasis en los puntos de
conversión.

#### **Estructura General**

La estructura de la Landing Page se divide en bloques verticales
claramente diferenciados, cada uno con un propósito específico dentro
del flujo de atención del usuario:

1.  **Hero Section  
    ** La sección inicial destaca un mensaje central poderoso acompañado
    de un llamado a la acción visible ("Descargar App"). Incluye un
    fondo visual con estilo ondulado, elementos gráficos flotantes que
    refuerzan la temática del agua y una ilustración animada del sensor,
    generando una primera impresión atractiva y profesional.

2.  **Funcionalidades Principales  
    ** Este bloque presenta cinco características clave de WaterGuard,
    organizadas en una grilla visual con íconos, títulos breves y
    descripciones concisas. Las imágenes han sido estandarizadas para
    mantener proporciones uniformes, asegurando coherencia visual en
    todas las tarjetas.

3.  **Beneficios Diferenciadores  
    ** A través de tarjetas destacadas, se comunican los beneficios
    principales de la solución (ahorro de agua, control móvil y
    seguridad en el hogar). Cada tarjeta está visualmente diferenciada
    con colores suaves y animaciones al hacer scroll, alineadas con los
    principios de diseño accesible y moderno.

4.  **Impacto del Sistema (Estadísticas)  
    ** Se incluye un bloque de métricas visuales (número de hogares
    monitoreados, porcentaje de ahorro, volumen de agua ahorrada),
    utilizando íconos y cifras destacadas para reforzar el impacto
    tangible del sistema.

5.  **Cómo Funciona WaterGuard  
    ** Esta sección explica el funcionamiento paso a paso mediante una
    estructura secuencial de tres tarjetas visuales, integrando
    ilustraciones de cada etapa (instalación, sincronización y
    monitoreo), acompañadas de descripciones claras.

6.  **Testimonios  
    ** Presentamos opiniones reales de usuarios que refuerzan la
    confianza en la solución. El diseño incluye tarjetas estilizadas con
    citas destacadas, nombres y ubicación, permitiendo al visitante
    identificarse con los casos de uso presentados.

7.  **Formulario de Contacto  
    ** El formulario está ubicado estratégicamente antes del cierre de
    la página para permitir que el usuario realice consultas o exprese
    interés sin fricción. El diseño es simple, accesible y compatible
    con dispositivos móviles, con campos bien distribuidos y
    validaciones visuales básicas.

8.  **Sección de Descarga  
    ** Incluye botones llamativos para acceder a las tiendas de Google
    Play y App Store. Se mantiene la coherencia cromática con el
    branding, y se ha ampliado el padding para garantizar visibilidad y
    comodidad en pantallas pequeñas.

9.  **Footer  
    ** Cierra la experiencia con enlaces útiles, redes sociales y la
    política de privacidad. Su diseño responde al mismo estilo visual,
    con contraste suficiente para ser legible y elementos bien
    espaciados.

#### **Responsividad y Adaptabilidad**

Todo el diseño ha sido optimizado para adaptarse de forma responsiva a
diferentes dispositivos. El sistema de grillas garantiza un
comportamiento flexible del contenido, mientras que el menú principal se
convierte en un menú tipo hamburguesa en móviles, reduciendo la carga
visual sin perder funcionalidad.

#### **Accesibilidad**

Hemos considerado prácticas de accesibilidad como:

- Contraste adecuado entre texto y fondo.

- Etiquetas semánticas en botones y formularios.

- Tamaño mínimo de interacción en botones para pantallas táctiles.

- Compatibilidad con lectores de pantalla a través de atributos.

El diseño de la Landing Page de WaterGuard busca balancear estética,
funcionalidad y propósito. Cada componente ha sido construido para
aportar valor en el recorrido del usuario, simplificar la comprensión
del producto y facilitar acciones clave. La interfaz no solo es
visualmente atractiva, sino que está pensada para convertir visitantes
en usuarios activos, reflejando fielmente la identidad tecnológica,
sostenible y accesible de WaterGuard.

###   {#section-11}

### 5.3.1. Landing Page Wireframe ![](media/image46.jpg){width="5.5625in" height="9.604884076990377in"} {#landing-page-wireframe}

### 5.3.2. Landing Page Mock-up {#landing-page-mock-up}

![](media/image47.jpg){width="4.739212598425197in"
height="8.177083333333334in"}

|                                                                                                                                                                                                                                                                                                                                |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Link de Miro: [[Landing design link]{.underline}](https://miro.com/welcomeonboard/cWpINVd2TFFhYnVzc2JWQW5SRFpGN2lpb0V6ZUNpdll5eGl1UUNSRDBwaGV4M2hwaVV2NFJXUVkzdUJFRWFVeXFqTXFnOXM4ZThKR0FQZHdpbHNSWDBYeUZIempoa1h0RmlNWmV0aFRpQVFHM2lxSEk0dzMvV3RVSFNHd2UyQXBNakdSWkpBejJWRjJhRnhhb1UwcS9BPT0hdjE=?share_link_id=664931051167) |

## 5.4. Applications UX/UI Design  {#applications-uxui-design}

### 5.4.1. Application Wireframes {#application-wireframes}

Web

Los wireframes para la versión web son los siguientes:

|                                                                                                                                                                                                                            |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Link Figma: [[https://www.figma.com/design/EnYeNyMlQ9hiKHnqz77na2/Untitled?node-id=1-78&t=VrzkssxzEv0QNLZ3-1]{.underline}](https://www.figma.com/design/EnYeNyMlQ9hiKHnqz77na2/Untitled?node-id=1-78&t=VrzkssxzEv0QNLZ3-1) |

![](media/image48.png){width="6.267716535433071in"
height="2.986111111111111in"}

Mobile App

Los wireframes para la versión móvil de la solución son los siguientes:

![](media/image49.png){width="5.776042213473316in"
height="6.591595581802275in"}

|                                                                                                                                                                                                                          |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Link Figma: [[https://www.figma.com/design/3zCiZDaImmyBgWlyToZMxC/Untitled?node-id=0-1&t=JrQ37IWr0qUVIkb3-1]{.underline}](https://www.figma.com/design/3zCiZDaImmyBgWlyToZMxC/Untitled?node-id=0-1&t=JrQ37IWr0qUVIkb3-1) |

### 5.4.2 Application Wireflow Diagrams {#application-wireflow-diagrams}

Los diagramas que hemos detectado son los siguientes:

Demostramos el inicio de sesión, en caso no tenga una cuenta se podrá
registrarse y seleccionar que tipo de usuario (persona o empresa)

Tenemos un método para recuperar tu cuenta en caso se te olvide tu
contraseña, enviaremos un código por tu correo que has
registrado![](media/image50.png){width="6.267716535433071in"
height="1.9583333333333333in"}![](media/image51.png){width="6.267716535433071in"
height="2.0972222222222223in"}

En esta sección podrás visualizar la pantalla del prototipo del sistema,
donde se muestran los datos recopilados por el sensor en tiempo real.
Además, tienes la opción de descargar en un PDF la captura de pantalla
de lo que realices en la página.

![](media/image52.png){width="6.267716535433071in"
height="4.472222222222222in"}

|                                                                                                                                                                                                                                             |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Link del Prototype en Figma: [[https://www.figma.com/design/EnYeNyMlQ9hiKHnqz77na2/Untitled?node-id=1-78&t=VrzkssxzEv0QNLZ3-1]{.underline}](https://www.figma.com/design/EnYeNyMlQ9hiKHnqz77na2/Untitled?node-id=1-78&t=VrzkssxzEv0QNLZ3-1) |

Mobile App:

Para la parte de desarrollo de la app Móvil, presentamos los siguientes
flujos core del negocio.

En primera instancia tenemos el login, donde podrá ingresar al
Home/Dashboard, dónde podrá ver el usuario sus tanques principales y
tenemos un menú de 3 íconos los cuales mostrarán diferentes apartados.
Al hacer clic en un tanque agregado, Mostrará el nivel, Calidad y Nivel
Histórico del tanque de Agua, en un formato amigable.

En segundo flujo presentamos la parte de las Alertas en forma de
Notificaciones, donde se podrá ver el histórico de notificaciones
pendientes y las Resueltas, en caso haya inconvenientes respecto a los
criterios de medición.![](media/image53.png){width="7.486558398950131in"
height="2.20119750656168in"}![](media/image54.png){width="4.925795056867892in"
height="4.637253937007874in"}

### Por último presentamos que mediante el ícono del Dashboard o Home, se puede ir a la parte de Configuraciones y que en este apartado se ingresa los niveles o rangos de medición para generar las alertas y reportes.![](media/image55.png){width="2.4627602799650044in" height="7.036458880139983in"} {#por-último-presentamos-que-mediante-el-ícono-del-dashboard-o-home-se-puede-ir-a-la-parte-de-configuraciones-y-que-en-este-apartado-se-ingresa-los-niveles-o-rangos-de-medición-para-generar-las-alertas-y-reportes.}

|                                                                                                                                                                                                                          |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Link Figma: [[https://www.figma.com/design/3zCiZDaImmyBgWlyToZMxC/Untitled?node-id=0-1&t=JrQ37IWr0qUVIkb3-1]{.underline}](https://www.figma.com/design/3zCiZDaImmyBgWlyToZMxC/Untitled?node-id=0-1&t=JrQ37IWr0qUVIkb3-1) |

### 5.4.3. Applications Mock-ups {#applications-mock-ups}

![](media/image56.png){width="6.267716535433071in"
height="2.736111111111111in"}

![](media/image57.png){width="6.267716535433071in"
height="1.5277777777777777in"}

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Link de Figma:</p>
<p><a
href="https://www.figma.com/design/EnYeNyMlQ9hiKHnqz77na2/Untitled?node-id=0-1&amp;t=VrzkssxzEv0QNLZ3-1"><u>https://www.figma.com/design/EnYeNyMlQ9hiKHnqz77na2/Untitled?node-id=0-1&amp;t=VrzkssxzEv0QNLZ3-1</u></a></p></td>
</tr>
</tbody>
</table>

### Mobile App:![](media/image58.png){width="6.267716535433071in" height="5.402777777777778in"}

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Link de Figma:</p>
<p><a
href="https://www.figma.com/design/3zCiZDaImmyBgWlyToZMxC/Untitled?node-id=2-1270&amp;t=JrQ37IWr0qUVIkb3-1"><u>https://www.figma.com/design/3zCiZDaImmyBgWlyToZMxC/Untitled?node-id=2-1270&amp;t=JrQ37IWr0qUVIkb3-1</u></a></p></td>
</tr>
</tbody>
</table>

### 5.4.3. Applications User Flow Diagrams {#applications-user-flow-diagrams}

![](media/image59.png){width="6.015625546806649in"
height="2.6280883639545056in"}

|                                                                                                                                                                                                                             |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Link de Figma: [[https://www.figma.com/design/EnYeNyMlQ9hiKHnqz77na2/Untitled?node-id=0-1&t=VrzkssxzEv0QNLZ3-1]{.underline}](https://www.figma.com/design/EnYeNyMlQ9hiKHnqz77na2/Untitled?node-id=0-1&t=VrzkssxzEv0QNLZ3-1) |

Mobile App![](media/image60.png){width="4.890625546806649in"
height="4.169057305336833in"}

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Link de Figma:</p>
<p><a
href="https://www.figma.com/design/3zCiZDaImmyBgWlyToZMxC/Untitled?node-id=2-1270&amp;t=JrQ37IWr0qUVIkb3-1"><u>https://www.figma.com/design/3zCiZDaImmyBgWlyToZMxC/Untitled?node-id=2-1270&amp;t=JrQ37IWr0qUVIkb3-1</u></a></p></td>
</tr>
</tbody>
</table>

## 6.5. Applications Prototyping {#applications-prototyping}

![](media/image61.png){width="6.267716535433071in"
height="3.7777777777777777in"}

|                                                                                                                                                                                                                                                                                                                                                                                          |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Link del video: [[Application Prototyping.mp4]{.underline}](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202019038_upc_edu_pe/ETX8nULI__5Lh6x7LIvJucoBaHMRfgPI1iZ4MC7gxG6RXw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=D5PNyD) |

# Capítulo VI: Product Implementation, Validation & Deployment {#capítulo-vi-product-implementation-validation-deployment}

## 6.1. Software Configuration Management {#software-configuration-management}

### 6.1.1. Software Development Environment Configuration. {#software-development-environment-configuration.}

En esta sección se describen cada uno de los productos software que
empleamos en el proyecto. Es importante porque permite que los
integrantes colaboren en el ciclo de vida del proyecto. El formato que
tiene esta sección consiste en lo siguiente: descripción del producto
software y en la parte inferior una url de referencia.

Project Management:

Para la gestión del proyecto se emplearon dos herramientas principales:

- **Trello**: Utilizada para organizar y hacer seguimiento de las
  actividades del equipo, clasificándolas en columnas como "Por hacer",
  "En proceso" y "Finalizadas". Su interfaz basada en tarjetas permite
  una gestión visual, sencilla e intuitiva del trabajo colaborativo.  
  [[https://trello.com/  
  ]{.underline}](https://trello.com/)

- **Google Meet**: Plataforma de videollamadas utilizada para coordinar
  reuniones entre los miembros del equipo. Al ser una aplicación web
  gratuita y de fácil acceso, facilitó la comunicación sin necesidad de
  instalar software adicional.  
  [[https://meet.google.com/]{.underline}](https://meet.google.com/)

Product UX/UI Design:

- **Figma**: Herramienta colaborativa basada en la nube para el diseño
  de interfaces. Se utilizó para crear wireframes y mockups de la
  plataforma. Permite a múltiples usuarios trabajar simultáneamente
  sobre un mismo archivo de diseño. Es gratuita con registro previo.

> [[https://www.figma.com/]{.underline}](https://www.figma.com/)

#### **Test and Api Documentation**

- **Postman**: Aplicación utilizada para realizar pruebas y documentar
  las APIs desarrolladas en el proyecto. Permite enviar solicitudes
  HTTP, visualizar respuestas, automatizar pruebas y organizar
  colecciones de peticiones. Su interfaz amigable facilita la validación
  del comportamiento de los endpoints durante el desarrollo y la
  integración de servicios.  
  [[https://www.postman.com/  
  ]{.underline}](https://www.postman.com/)

### 6.1.2. Source Code Management {#source-code-management}

En esta sección, el equipo establece los medios y el esquema de
organización que se aplicará para el seguimiento de las modificaciones
realizadas en el código fuente. Para ello, utilizaremos GitHub como
plataforma y sistema de control de versiones. A continuación, se detalla
la estructura y las convenciones que seguiremos para gestionar
eficazmente el código de nuestros productos digitales.

Repositorios y URL:

Cada producto digital que forme parte del alcance del proyecto tendrá su
propio repositorio en GitHub. Para el dispositivo tanque de agua
inteligente con IoT, utilizamos el siguiente repositorio:

WaterGaurd-LandingPage:
[[https://github.com/WaterGuard-IOT/LadingPage]{.underline}](https://github.com/WaterGuard-IOT/LadingPage)

WaterGuatd-Frontend:
[[https://github.com/WaterGuard-IOT/WaterGuard-FrontEnd]{.underline}](https://github.com/WaterGuard-IOT/WaterGuard-FrontEnd)

WaterGuard-IOT-Backend:
[[https://github.com/WaterGuard-IOT/Backend]{.underline}](https://github.com/WaterGuard-IOT/Backend)

WaterGuard-MobileApp:
[[https://github.com/WaterGuard-IOT/waterguard-appmobile]{.underline}](https://github.com/WaterGuard-IOT/waterguard-appmobile)

Implementación de GitFlow como Workflow de Control de Versiones:

Adoptaremos el modelo GitFlow, según lo descrito por Vincent Driessen en
su artículo "A successful Git branching model", como nuestro flujo de
trabajo principal para el control de versiones. Este modelo nos
permitirá gestionar de manera eficiente el desarrollo, las versiones y
las correcciones de errores. A continuación, se describen las ramas que
implementaremos y las convenciones asociadas:

#### **Rama Principal (Main)**

- **Nombre:** main

- **Descripción:** Contiene el código completamente estable y listo para
  producción. Todas las versiones oficiales del proyecto serán
  etiquetadas en esta rama.

#### **Rama de Desarrollo (Develop)**

- **Nombre:** develop

- **Descripción:** Es la rama principal para el desarrollo activo. Aquí
  se integran todas las nuevas funcionalidades y mejoras antes de ser
  liberadas a producción.

#### **Ramas de Características (Feature Branches)**

- **Convención de nombres:** feature/nombre-descriptivo

- **Descripción:** Cada funcionalidad o mejora del sistema será
  desarrollada en su propia rama, utilizando una nomenclatura clara y
  descriptiva.  
  **Ejemplo:** feature/integracion-sensor-temperatura

- **Regla:** Las ramas de tipo *feature* deben derivarse de develop y
  fusionarse nuevamente en esta una vez completadas, facilitando un
  desarrollo modular y controlado.

#### **Ramas de Liberación (Release Branches)**

- **Convención de nombres:** release/vX.Y.Z

- **Descripción:** Se utilizan para preparar una nueva versión antes de
  su despliegue. Durante esta etapa se realizan pruebas finales y
  ajustes menores. Al finalizar, se fusionan en main y develop.

#### **Ramas de Corrección Rápida (Hotfix Branches)**

- **Convención de nombres:** hotfix/vX.Y.Z

- **Descripción:** Destinadas a resolver errores críticos detectados en
  producción. Estas correcciones se aplican directamente sobre la rama
  main y, una vez completadas, se fusionan también en develop.

**Versionado Semántico**

Para el control de versiones se empleará la convención **Semantic
Versioning 2.0.0**, utilizando el formato vX.Y.Z, donde:

- **X (Major):** Cambios que introducen incompatibilidades con versiones
  anteriores.

- **Y (Minor):** Nuevas funcionalidades compatibles con versiones
  previas.

- **Z (Patch):** Correcciones de errores que no afectan la
  compatibilidad.

Este sistema permite una gestión predecible y transparente de los
cambios introducidos en cada versión del software.

Convenciones para Mensajes de Commit

Adoptaremos el estándar **Conventional Commits** para estructurar los
mensajes de commit en el proyecto. Este enfoque facilita la lectura del
historial de cambios, mejora la colaboración entre desarrolladores y
permite la automatización de procesos como la integración continua y la
generación de changelogs.

La estructura básica de un mensaje de commit será la siguiente:

\<tipo\>(\<área\>): \<descripción\>

#### **Componentes:**

- **tipo**: Indica la naturaleza del cambio realizado. Ejemplos comunes:

  - feat: Nueva funcionalidad

  - fix: Corrección de errores

  - docs: Cambios en la documentación

  - style: Cambios que no afectan la lógica (formato, estilo, etc.)

  - refactor: Refactorización de código sin cambiar su funcionalidad

  - test: Adición o modificación de pruebas

  - chore: Cambios en tareas de mantenimiento o configuración

- **área** *(opcional)*: Especifica la parte del proyecto afectada, como
  el nombre de un módulo, archivo o componente.

- **descripción**: Breve resumen del cambio realizado, escrito en
  infinitivo y en tiempo presente. Debe ser conciso y claro.

### 6.1.3. Source Code Style Guide & Conventions {#source-code-style-guide-conventions}

1.  Convenciones de Nombramiento

- Las variables deben nombrarse utilizando camelCase. Ejemplo:
  totalCost, numItems.

- Clases y Componentes: Nombrar clases y componentes en PascalCase,
  iniciando cada palabra con mayúscula. Ejemplo: UserProfile,
  DataProcessor.

- Constante: Usar UPPER_CASE y guiones bajos para separar palabras.
  Ejemplo: MAX_CONNECTIONS, DEFAULT_TIMEOUT.

- Funciones y Métodos: Utilizar camelCase y elegir nombres descriptivos
  que reflejen su propósito. Ejemplo: calculateTotal, sendDataToServer.

- Archivos: Usar Kebab-case o snake_case para nombres de archivos.
  Ejemplo: user-profile.js o user_profile.py

2.  Formato de Código

- Indentación: La indentación debe ser de cuatro espacios por nivel para
  mejorar la legibilidad del código.

- Longitud de línea: Mantener el límite de la longitud de línea en
  80-120 caracteres, dependiendo de la claridad y la legibilidad.

- Espacios: Usar un espacio entre operadores (+, -, =) y después de
  comas para mejorar la claridad. Ejemplo: int total = a + b;.

3.  Documentación y Comentarios

- Comentarios de Línea y Bloque: Incluir comentarios para aclarar la
  lógica en secciones complejas o poco evidentes. Evitar comentarios
  redundantes que repitan lo obvio.

- Documentación de Funciones y Métodos: Cada función o método debe tener
  una breve descripción de su propósito, sus parámetros y el valor de
  retorno.

- Estilo de Documentación: Usar un formato uniforme (como Javadoc en
  Java o Doxygen en C++) para que la documentación sea clara y
  estructurada.

4.  Organización de Estructura de Código

- Estructura de Archivos: Organizar el código en módulos o paquetes
  según su funcionalidad (ej., controladores, servicios, modelos).

- Modularización de Funcionalidades: Dividir las funciones en pequeñas
  unidades con una sola responsabilidad para mejorar la reutilización y
  mantenibilidad.

5.  Buenas Prácticas Generales

- Evitar Variables Globales: Reducir el uso de variables globales, ya
  que pueden complicar el mantenimiento y la depuración del código.

- Control de Errores: Implementar manejo de excepciones o errores
  adecuado para capturar y gestionar fallos sin interrumpir el flujo del
  programa.

- Buenas Prácticas de Seguridad: Evitar almacenar información sensible
  directamente en el código. En su lugar, utilizar variables de entorno
  o sistemas de almacenamiento seguro.

- Refactorización Continua: Revisar y mejorar el código regularmente
  para simplificar la lógica, eliminar duplicación y mejorar la
  eficiencia.

### 6.1.4. Software Deployment Configuration {#software-deployment-configuration}

1\. Entornos de Despliegue

- Desarrollo (Development): Se utiliza un entorno de desarrollo para
  pruebas iniciales y verificación de nuevas funcionalidades antes de la
  integración en otros entornos. Este entorno permite realizar pruebas
  de unidad y de integración para validar la calidad del código.

- Pruebas (Testing/Staging): Aquí se despliega el código antes de
  pasarlo a producción, imitando las condiciones de este último. Este
  entorno permite pruebas de carga, regresión y validación final de los
  servicios.

- Producción (Production): El entorno de producción es accesible para
  los usuarios finales y debe ser altamente confiable. En este entorno
  se aplican prácticas de monitoreo constante y políticas de seguridad
  avanzadas para proteger los datos y la operación continua.

2\. Herramientas de Despliegue

- Contenedores Docker: El despliegue se realiza mediante contenedores
  Docker, lo que permite encapsular la aplicación y sus dependencias,
  asegurando que el software se ejecute de manera consistente en
  cualquier entorno.

- CI/CD: Para la integración continua y despliegue continuo (CI/CD), se
  utilizan herramientas como Jenkins o GitLab CI/CD. Estas herramientas
  automatizan la integración de cambios en el código y el despliegue en
  los distintos entornos.

3\. Automatización del Despliegue

- Se utilizan scripts de despliegue automatizados para reducir la
  intervención manual y minimizar errores. La automatización abarca
  desde la construcción del contenedor Docker hasta la configuración de
  la infraestructura en la nube y el despliegue en producción.

- Pruebas Automatizadas: Las pruebas unitarias, de integración y de
  regresión se ejecutan automáticamente como parte de la canalización de
  CI/CD para garantizar que cada cambio en el código no afecte
  funcionalidades existentes.

4\. Monitoreo y Registro (Logging)

- Registro de Errores y Logs: El sistema de registro (logging) almacena
  de manera centralizada los errores y eventos importantes, permitiendo
  un análisis posterior y diagnóstico de problemas.

5\. Seguridad en el Despliegue

- Gestión de Accesos: Se establecen políticas de permisos en los
  entornos de producción para limitar el acceso solo al personal
  autorizado y reducir el riesgo de cambios no controlados.

- Protección de Datos: Toda la información sensible se maneja mediante
  variables de entorno y se utiliza cifrado tanto en tránsito como en
  reposo.

- Copias de Seguridad y Recuperación ante Desastres: Se implementa una
  estrategia de backup en la nube para la recuperación rápida en caso de
  fallos, asegurando la continuidad de las operaciones.

## 6.2. Landing Page, Services & Applications Implementation {#landing-page-services-applications-implementation}

### 6.2.1. Sprint 1 {#sprint-1}

En esta sección se registra y explica el avance en términos de producto
y trabajo colaborativo para el Sprint n.

### 6.2.1.1. Sprint Planning 1 {#sprint-planning-1}

En esta sección se especifican los aspectos principales del Sprint
Planning Meeting o los planeamientos de reuniones para este sprint.

<table>
<colgroup>
<col style="width: 49%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td colspan="2">Spring Planning Background</td>
</tr>
<tr class="even">
<td>Date</td>
<td>12-04-2025</td>
</tr>
<tr class="odd">
<td>Time</td>
<td>9:00</td>
</tr>
<tr class="even">
<td>Location</td>
<td>Lima, Perú de modalidad virtual en discord</td>
</tr>
<tr class="odd">
<td>Prepared By</td>
<td>Julio Asillo Mendoza</td>
</tr>
<tr class="even">
<td>Attendees (to plannig meeting)</td>
<td>Kevin Oliva Alva, Diego Santivañez Filio, Santos Patazca, Leonel
Alfaro, Carlos Ramirez</td>
</tr>
<tr class="odd">
<td><p>Sprint n-1 Review</p>
<p>Summary</p></td>
<td>No aplica por ser el primer sprint.</td>
</tr>
<tr class="even">
<td><p>Sprint n-1 Retrospective</p>
<p>Summary</p></td>
<td>No aplica por ser el primer sprint.</td>
</tr>
<tr class="odd">
<td colspan="2">Spring Goal &amp; User Stories</td>
</tr>
<tr class="even">
<td>Sprint 1 Goal</td>
<td>Implementar la primera versión del Landing Page informativo del
proyecto y desarrollar la interfaz básica de monitoreo de agua en la
aplicación web y móvil para que los usuarios de comunidades rurales
puedan visualizar datos de niveles de agua. Este sprint se considerará
exitoso cuando los usuarios puedan acceder a la Landing Page desplegada
con información del proyecto, y puedan visualizar correctamente los
datos de niveles de agua en las aplicaciones web y móvil.</td>
</tr>
<tr class="odd">
<td>Sprint 1 Velocity</td>
<td>18 story points</td>
</tr>
<tr class="even">
<td>Sum of Story Points</td>
<td>18 story points</td>
</tr>
</tbody>
</table>

### 6.2.1.2. Sprint Backlog 1 {#sprint-backlog-1}

para este apartado empezamos por el objetivo de este sprint el cual es
tener una primera versión del dispositivo iot el cual se pueda conectar
a aws y evidenciarlo con una pantalla oled el cual su data coincida con
los mostrados en aws, así como vincularlo a una base de datos
especializada

|            |                                                |                  |                                                                                          |                                                                                                                                                                                        |                    |                  |                                        |
|------------|------------------------------------------------|------------------|------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|------------------|----------------------------------------|
| Sprint \#  |                                                | Sprint 1         |                                                                                          |                                                                                                                                                                                        |                    |                  |                                        |
| User story |                                                | Work Item / Task |                                                                                          |                                                                                                                                                                                        |                    |                  |                                        |
| Id         | Title                                          | Id               | Title                                                                                    | Description                                                                                                                                                                            | Estimation (Hours) | Assigned To      | Status (To-do InProcess ToReview Done) |
| US-004     | Configurar alertas personalizadas              | W-01             | Visualización de monitoreo e frontend                                                    | Se implementó la interfaz principal del sistema con visualización del estado del agua, historial de sensores y exportación en PDF. Los datos se cargan dinámicamente desde el api fake | 18 horas           | Santos Patazca   | Done                                   |
| US-006     | Acceder al historial de datos                  |                  |                                                                                          |                                                                                                                                                                                        |                    |                  |                                        |
| US-014     | Generar informes automáticos                   |                  |                                                                                          |                                                                                                                                                                                        |                    |                  |                                        |
| US-024     | Implementación de landing page                 | W-02             | Implementación y despliegue de landing page                                              | Se realizo la implementación y despliegue de la landing page explicando el producto y siguiendo los codigos de estilos definidos                                                       | 16 horas           | Kevin Oliva Alva | Done                                   |
| US-013     | Configurar panel de control personaliado       | w-03             | Configurar panel de control de las bombas de agua y visualización de los tanques de agua | Se realizó la visualización de un panel para controlar o ver la cantidad de tanques de agua que se tienen.                                                                             | 3 horas            | Julio Asillo     | Done                                   |
| US021      | Activación automática de las bombas de agua    | W04              | Configurar para que se pueda activar la bomba de manera automática.                      | Configurar en la vista mobile app, para que se active la bomba de manera automática.                                                                                                   | 2 horas            | Julio Asillo     | Done                                   |
| US023      | Desactivación automática de las bombas de agua | W05              | Configurar para que se pueda desactivar la bomba de manera automática.                   | Vista móvil para que se pueda desactivar la bomba de agua, de manera automática cuando este ya alcance el máximo permitido de su umbral.                                               | 2 horas            | Julio Asillo     | Done                                   |

### 6.2.1.3. Development Evidence for Sprint Review {#development-evidence-for-sprint-review}

Para esta presentación solo tendremos disponible el primer commit con la
primera versión funcional disponible en el github del equipo.

Sprint 1:

|                                                                                                                                   |         |           |                                                                    |                     |                    |
|-----------------------------------------------------------------------------------------------------------------------------------|---------|-----------|--------------------------------------------------------------------|---------------------|--------------------|
| Repository                                                                                                                        | Branch  | Commit Id | Commit Message                                                     | Commit Message Body | Commited on (Date) |
| [[Ver commit]{.underline}](https://github.com/WaterGuard-IOT/WaterGuard-FrontEnd/commit/e6f46e67b9361493d1577144b82dfe94691cb298) | develop | e6f46e6   | Se agrega el proyecto                                              |                     | 2025-04-11         |
| [[Ver commit]{.underline}](https://github.com/WaterGuard-IOT/WaterGuard-FrontEnd/commit/a3d63c2e50cff9c013ea7b2bec43028c54bd3ab1) | develop | a3d63c2   | sign-up and login                                                  |                     | 2025-04-12         |
| [[Ver commit]{.underline}](https://github.com/WaterGuard-IOT/WaterGuard-FrontEnd/commit/4fce74ed5a10cbb8f640121f4f829ca5a475da08) | develop | 4fce74e   | feat: registration logic, JSON saving, auth-service and auth-guard |                     | 2025-04-22         |

|                                                                                                |         |           |                                                            |                     |                    |
|------------------------------------------------------------------------------------------------|---------|-----------|------------------------------------------------------------|---------------------|--------------------|
| Repository                                                                                     | Branch  | Commit Id | Commit Message                                             | Commit Message Body | Commited on (Date) |
| [[Ver repositorio landing]{.underline}](https://github.com/WaterGuard-IOT/LadingPage)          | develop | 0b0af5    | Se culmina el desarrollo del landing page                  | \-                  | 2025-04-21         |
| [[Mobile-App Repositorio]{.underline}](https://github.com/WaterGuard-IOT/waterguard-appmobile) | master  | 3292bdb   | Se termina la versión 0.7e, un MVP de la aplicación móvil. | \-                  | 2025-04-11         |

### 6.2.1.4. Testing Suite Evidence for Sprint Review {#testing-suite-evidence-for-sprint-review}

No se realizó ningun testing, debido a que no se desarrolló aún, ningún
servicio del backend.

### 6.2.1.5. Execution Evidence for Sprint Review {#execution-evidence-for-sprint-review}

Aplicación Web: Durante este sprint se desarrollaron las funcionalidades
clave del sistema de monitoreo, enfocadas en la experiencia del usuario
y la visualización de datos ambientales. Se construyó el login, la
pantalla principal (Home), que permite a los usuarios autenticados
visualizar en tiempo real el estado del agua, incluyendo el nivel de pH,
temperatura y volumen, así como revisar tendencias históricas y alertas
recientes. Además, se implementó la navegación entre secciones como
Reports, Device y Settings, cada una con contenido adaptado según el
usuario. Se desarrolló también un sistema de exportación de reportes en
formato PDF, capturando el estado completo del sistema para respaldo o
revisión. Toda la información se carga dinámicamente desde un backend
simulado con db.json.

Login

Permite al usuario ingresar al sistema mediante su correo electrónico y
contraseña. Valida las credenciales con los datos del db.json.

![](media/image62.png){width="6.267716535433071in"
height="2.9722222222222223in"}

Home

Muestra el estado actual del agua para el usuario logueado, incluyendo
los niveles de pH, temperatura y volumen. Además, presenta un historial
de tendencias por fecha y alertas recientes. Incluye un botón para
exportar el contenido en PDF como evidencia del monitoreo.

![](media/image63.png){width="6.067708880139983in"
height="3.1044094488188976in"}

Reports

Muestra una visualización resumida del uso y estado del sistema. Incluye
acceso directo para ver el consumo detallado y la sección del
dispositivo. Sirve como punto intermedio de monitoreo general.

![](media/image64.png){width="6.267716535433071in"
height="3.1805555555555554in"}

Device

Simula la lógica de decisiones del sistema con base en el volumen
registrado en el tanque. Por cada registro de tendencia, se genera una
acción sugerida y su resultado esperado.

![](media/image65.png){width="6.267716535433071in"
height="3.0972222222222223in"}

Settings

Contiene opciones configurables agrupadas por categorías. Cada panel es
un es expandible.

![](media/image66.png){width="6.267716535433071in"
height="2.986111111111111in"}

### 6.2.1.6. Services Documentation Evidence for Sprint Review {#services-documentation-evidence-for-sprint-review}

Para este Sprint solo se hizo prototipado y desarrollo del front para
luego desarrollar los servicios que iran conectados con los dispositivos
IoT.

### 6.2.1.7. Software Deployment Evidence for Sprint Review. {#software-deployment-evidence-for-sprint-review.}

Para la evidencia de deployante, mostramos los servicios creados en

Aplicación Web (Frontend):

La interfaz desarrollada con Angular se encuentra alojada en Netlify.
Esta está configurada para actualizarse automáticamente con cada cambio
que se realiza en la rama principal de desarrollo (develop), asegurando
que siempre se muestre la versión más reciente del sistema.

![](media/image62.png){width="6.267716535433071in"
height="2.9722222222222223in"}

URL de acceso:
[[https://waterguard.netlify.app/]{.underline}](https://waterguard.netlify.app/)

Fake API :

Para simular el comportamiento de la base de datos, se ha desplegado una
API REST utilizando json-server, alojada en Render. Esta API permite
realizar operaciones GET, POST, PUT y DELETE, y contiene endpoints
públicos relacionados con usuarios, estado del agua, alertas y
tendencias.

![](media/image67.png){width="6.267716535433071in"
height="3.5694444444444446in"}

URL de acceso:
[[https://json-api-nj61.onrender.com/]{.underline}](https://json-api-nj61.onrender.com/)

### 6.2.1.8. Team Collaboration Insights during Sprint.  {#team-collaboration-insights-during-sprint.}

Se muestran los avances y la colaboración entre los miembros del equipo
durante el Sprint 1

Aplicación Web

![](media/image68.png){width="6.267716535433071in"
height="4.652777777777778in"}

#  {#section-12}

#   {#section-13}

![](media/image69.png){width="5.21875in"
height="3.7395833333333335in"}Aplicación Móvil

**Backend:**

![](media/image70.png){width="5.208636264216973in"
height="3.989815179352581in"}

**CONCLUSIONES**

**1. Viabilidad de soluciones locales:** La arquitectura basada en
Domain-Driven Design nos ha permitido crear una solución técnicamente
viable que puede funcionar en entornos con conectividad limitada,
eliminando la dependencia de servicios cloud como Azure Digital Twins.

**2. Adaptabilidad a contextos rurales:** El diseño táctico dividido en
cuatro bounded contexts (Monitoreo de Niveles de Agua, Análisis de
Calidad de Agua, Generación de Reportes y Autenticación de Usuarios)
permite una implementación modular que se ajusta a las necesidades
específicas de comunidades rurales.

**3. Reducción de costos operativos:** Al migrar de una arquitectura
basada en servicios cloud a una solución local con servidores en la
comunidad, se logra una significativa reducción en los costos operativos
recurrentes, haciendo la solución más sostenible a largo plazo para
comunidades con recursos limitados.

**4. Empoderamiento comunitario:** La arquitectura propuesta facilita
que las propias comunidades puedan mantener y gestionar sus sistemas de
agua, reduciendo la dependencia de especialistas externos y promoviendo
la autonomía local.

# **Bibliografía**

Camargo, E. T. de, Spanhol, F. A., Slongo, J. S., Silva, M. V. R. da,
Pazinato, J., Lobo, A. V. L., ... Martins, L. D. (2023). Low-Cost Water
Quality Sensors for IoT: A systematic review. *Sensors (Basel,
Switzerland), 23*(9), 4424. https://doi.org/10.3390/s23094424
[[PubMed]{.underline}](https://pubmed.ncbi.nlm.nih.gov/37177633/)

CEPAL. (2002). *Drinking water supply and sanitation services on the
threshold of the XXI century*. Comisión Económica para América Latina y
el Caribe.
[[https://repositorio.cepal.org/bitstream/handle/11362/6454/S047591_en.pdf]{.underline}
[CEPAL
Repository]{.underline}](https://repositorio.cepal.org/bitstream/handle/11362/6454/S047591_en.pdf)

Forhad, H. M., Uddin, M. R., Chakrovorty, R. S., Ruhul, A. M., Faruk, H.
M., Kamruzzaman, S., ... Morshed, A. M. (2024). IoT based real-time
water quality monitoring system in water treatment plants (WTPs).
*Heliyon, 10*(23), e40746. https://doi.org/10.1016/j.heliyon.2024.e40746
[[PubMed]{.underline}](https://pubmed.ncbi.nlm.nih.gov/39698090/)

Jabbar, W. A., Mei Ting, T., Hamidun, M. F. I., Che Kamarudin, A. H.,
Wu, W., Sultan, J., ... Ali, M. A. H. (2024). Development of
LoRaWAN-based IoT system for water quality monitoring in rural areas.
*Expert Systems with Applications, 242*, 122862.
https://doi.org/10.1016/j.eswa.2023.122862
[[ScienceDirect]{.underline}](https://www.sciencedirect.com/science/article/pii/S095741742303364X)

Lal, K., Menon, S., Noble, F., & Arif, K. M. (2024). Low-cost IoT based
system for lake water quality monitoring. *PLoS ONE, 19*(3), e0299089.
https://doi.org/10.1371/journal.pone.0299089
[[PLOS]{.underline}](https://journals.plos.org/plosone/article?id=10.1371%2Fjournal.pone.0299089)

Prabha, C., & Munoth, N. (2024). IoT oriented approach for rural and
urban area based on 'Smart Water Management Systems' through sensors.
*International Journal of Intelligent Systems and Applications in
Engineering, 12*(23s), 301--.
[[https://ijisae.org/index.php/IJISAE/article/view/6740]{.underline}
[ijisae.org]{.underline}](https://ijisae.org/index.php/IJISAE/article/view/6740)

Soto-Córdoba, S. M., Gaviria-Montoya, L., & Pino-Gómez, M. (2016).
Situación de la gestión del agua potable en las zonas rurales de la
provincia de Cartago, Costa Rica. *Tecnología en Marcha, Encuentro de
Investigación y Extensión, 29*, 67--76.
https://www.redalyc.org/articulo.oa?id=699878529008
[[Redalyc.org]{.underline}](https://www.redalyc.org/pdf/6998/699878529008.pdf)

UNESCO. (2024). *United Nations World Water Development Report 2024:
Water for prosperity and peace*. UNESCO.
[[https://unesdoc.unesco.org/ark:/48223/pf0000388948]{.underline}](https://unesdoc.unesco.org/ark:/48223/pf0000388948)
[[UNESCO Digital
Library]{.underline}](https://unesdoc.unesco.org/ark%3A/48223/pf0000388948?utm_source=chatgpt.com)

World Bank. (2017). *Agua para zonas rurales y poblados* \[PDF\]. World
Bank.
[[https://documents1.worldbank.org/curated/en/779331468333062339/pdf/100850PUB0SPANISH0Box74459B01PUBLIC1.pdf]{.underline}
[World
Bank]{.underline}](https://documents1.worldbank.org/curated/en/779331468333062339/pdf/100850PUB0SPANISH0Box74459B01PUBLIC1.pdf)

Banco Interamericano de Desarrollo. (2018). *Proceso Regional de Las
Américas Foro Mundial del Agua 2018: Informe subregional Sudamérica*.
[[https://publications.iadb.org/publications/spanish/document/Proceso_Regional_de_Las_Am%C3%A9ricas_Foro_Mundial_del_Agua_2018_Informe_subregional_Sudam%C3%A9rica.pdf]{.underline}
[Publicaciones
IADB]{.underline}](https://publications.iadb.org/publications/spanish/document/Proceso_Regional_de_Las_Am%C3%A9ricas_Foro_Mundial_del_Agua_2018_Informe_subregional_Sudam%C3%A9rica.pdf)

Bawarshi Abarzúa, G. E., & Glückler, J. (2023). Network governance at
the margin of the state: Rural drinking water communities in Chile.
*Environmental Management, 71*(2), 451--464.
https://doi.org/10.1007/s00267-022-01760-2
[[doi.org]{.underline}](https://doi.org/10.1007%2Fs00267-022-01760-2)

Abrajano, J. V., Botangen, K. A., Nabua, J., Apanay, J., & Peña, C. F.
(2024). IoT-Based Water Quality Monitoring System in Philippine Off-Grid
Communities. *arXiv*.
[[http://arxiv.org/abs/2410.14619]{.underline}](http://arxiv.org/abs/2410.14619)

#   {#section-14}

# **Anexos**

Enlace del Informe en Markdown:
[[https://github.com/WaterGuard-IOT/Informe-Final]{.underline}](https://github.com/WaterGuard-IOT/Informe-Final)

Enlace GitHub:
[[https://github.com/WaterGuard-IOT]{.underline}](https://github.com/WaterGuard-IOT)

Enlace Exposición TB1:
[[https://youtu.be/9dsb8BSQvb0]{.underline}](https://youtu.be/9dsb8BSQvb0)  
Enlace Exposición TP1:
[upc-pre-2025101asi0572-2939-waterguard-expo-tp1.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201b482_upc_edu_pe/EVxBFODrKJ1BhzgONKB3ASkBfvCPQTVKgLslhbsM-HzQxA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=kwOEN2)

Acta de Reunión Nro. 1.

![](media/image71.png){width="6.267716535433071in" height="3.5in"}
