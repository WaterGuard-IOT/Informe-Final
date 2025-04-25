![Logotipo, nombre de la empresa Descripción generada automáticamente](media/image1.png)

# Universidad Peruana de Ciencias Aplicadas

**Ingeniería de Software**

**1ASI0572 - Desarrollo de Soluciones IoT**

**Sección 2939**

**Informe de TB1**

**Profesor:** León Baca, Marco Antonio

**Nombre del StartUp:** WaterGuard

**Integrantes**

Asillo Mendoza, Julio Ernesto u20201b482

Oliva Alva, Kevin Jonathan u201410580

Ramirez Mendoza, Carlos Arian u202020108

Patazca Calderón, Santos Alexis u20201c269

Santivañez Filio, Diego Jesus u202112321

Alfaro Cumba, Leonel u20201a930

**Abril del 2025**

## Registro de Versiones del Informe

| **Versión** | **Fecha** | **Autor** | **Descripción de modificación** |
|-------------|-----------|-----------|--------------------------------|
| TB1 | **08/09/2024** | WaterGuard | Elección del Tema y elaboración de los primeros 4 capítulos, que conlleva: Planteamiento del problema, antecedentes, Investigación con Usuarios, entrevistas, needfinding, Planificación, Historias de Usuario, Arquitectura, Diseño en general del software y planificación de los siguientes pasos a tomar. |

## Contenido

**Student Outcome**

El curso contribuye al cumplimiento del Student Outcome ABET:
**ABET -- EAC - Student Outcome 5: La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.**

| Criterio específico | Acciones realizadas | Conclusiones |
|---------------------|---------------------|--------------|
| Trabajar en equipo para proporcionar liderazgo en forma conjunta. | TB1 **Asillo Mendoza, Julio Ernesto** Realicé los diagramas C4 respecto a los componentes, contenedores y contexto. Ajustar el alcance y definir con el equipo. **Oliva Alva, Kevin Jonathan:** Se realizó la planificación y la recolección de requerimientos necesarios para poder solucionar las necesidades del usuario a través de nuestra solución **Ramirez Mendoza, Carlos Arian** **Patazca Calderón, Santos Alexis** Se llevó a cabo la mejora de los perfiles del proyecto, coordinando ideas con el equipo en reuniones. Contribuí activamente a decisiones clave para alinear el diseño con los objetivos del sistema. **Santivañez Filio, Diego Jesus:** Se realizaron reuniones para poder realizar el desarrollo de la arquitectura y el diseño de software que usaremos en el proyecto **Alfaro Cumba, Leonel** Se realizaron las las preguntas para las entrevistas y de otros puntos relacionados al usuarios para mejorar el enfoque del proyecto | |
| Crear un entorno colaborativo e inclusivo, establecer metas, planificar tareas y cumplir objetivos. | TB1 **Asillo Mendoza, Julio Ernesto** Tomé iniciativa para el futuro del proyecto encargarme del desarrollo mobile. Apoyé activamente en la coordinación. **Oliva Alva, Kevin Jonathan** Se realizaron los user stories, impact mapping y product backlog dentro del rango de fechas prevista para la entrega del trabajo Ramirez Mendoza, Carlos Arian **Patazca Calderón, Santos Alexis** Apoyé con la organización de entregables, promoviendo una comunicación participativa. Desarrolle el avance del frontend y la mejora de apartados de antecedentes y problemática, facilitando el cumplimiento de los objetivos. **Santivañez Filio, Diego Jesus** Se realizaron reuniones para la realización de la estructura del software y para poder definir los bounded context dentro del plazo acordado. **Alfaro Cumba, Leonel** Se establecieron metas claras, y se trabajó en equipo para cumplir los objetivos del proyecto, asegurando un enfoque alineado a las necesidades de los usuarios**.**como el desarrollo del Del Needfinding | |

# Tabla de Contenido

[**Capítulo I: Introducción 7**](#capítulo-i-introducción)

> [1.1. Startup Profile 7](#startup-profile)
>
> [1.1.1. Descripción de la Startup 7](#descripción-de-la-startup)
>
> [1.1.2. Perfiles de integrantes del equipo 8](#perfiles-de-integrantes-del-equipo)
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
> [1.2.2.3. Lean UX Hypothesis Statements 14](#lean-ux-hypothesis-statements)
>
> [1.2.2.4. Lean UX Canvas 16](#lean-ux-canvas)
>
> [1.3. Segmentos objetivo 18](#segmentos-objetivo)

[**Capítulo II: Requirements Elicitation & Analysis 18**](#capítulo-ii-requirements-elicitation-analysis)

> [2.1. Competidores 18](#competidores)
>
> [2.1.1. Análisis competitivo 19](#_heading=h.8uwz5ie3lwpz)
>
> [2.1.2. Estrategias y tácticas frente a competidores 25](#estrategias-y-tácticas-frente-a-competidores)
>
> [2.2. Entrevistas 25](#entrevistas)
>
> [2.2.1. Diseño de entrevistas 25](#diseño-de-entrevistas)
>
> [2.2.2. Registro de entrevistas 27](#registro-de-entrevistas)
>
> [2.2.3. Análisis de entrevistas 29](#análisis-de-entrevistas)
>
> [2.3. Needfinding 29](#_heading=h.lf3ds3bbgvi)
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

[**Capítulo III: Requirements Specification 33**](#capítulo-iii-requirements-specification)

> [3.1. To-Be Scenario Mapping 33](#to-be-scenario-mapping)
>
> [3.2. User Stories 34](#user-stories)
>
> [3.3. Impact Mapping 52](#impact-mapping)
>
> [3.4. Product Backlog 52](#product-backlog)

[**Capítulo IV: Solution Software Design 56**](#capítulo-iv-solution-software-design)

> [4.1 Strategic-Level Domain-Driven Design 56](#strategic-level-domain-driven-design)
>
> [4.1.1. EventStorming 57](#eventstorming)
>
> [4.1.1.1. Candidate Context Discovery 58](#candidate-context-discovery)
>
> [4.1.1.2. Domain Message Flows Modeling 59](#domain-message-flows-modeling)
>
> [4.1.1.3. Bounded Context Canvases 60](#bounded-context-canvases)
>
> [4.1.2. Context Mapping 61](#context-mapping)
>
> [4.1.3. Software Architecture 62](#software-architecture)
>
> [4.1.3.1. Software Architecture Context Level Diagrams 62](#software-architecture-context-level-diagrams)
>
> [4.1.3.2. Software Architecture Container Level Diagrams 63](#software-architecture-container-level-diagrams)
>
> [4.1.3.3. Software Architecture Deployment Diagrams 63](#software-architecture-deployment-diagrams)
>
> [4.2. Tactical-Level Domain-Driven Design 64](#tactical-level-domain-driven-design)
>
> [4.2.1. Bounded Context: Monitoreo de Niveles de Agua 64](#bounded-context-monitoreo-de-niveles-de-agua)
>
> [4.2.1.1. Domain Layer 64](#domain-layer)
>
> [4.2.1.2. Interface Layer 66](#interface-layer)
>
> [4.2.1.3. Application Layer 67](#application-layer)
>
> [4.2.1.4. Infrastructure Layer 68](#infrastructure-layer)
>
> [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams 69](#bounded-context-software-architecture-component-level-diagrams)
>
> [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams 69](#bounded-context-software-architecture-code-level-diagrams)
>
> [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams 70](#bounded-context-domain-layer-class-diagrams)
>
> [4.2.1.6.2. Bounded Context Database Design Diagram 70](#bounded-context-database-design-diagram)
>
> [4.2.2. Bounded Context: Análisis de Calidad de Agua 70](#bounded-context-análisis-de-calidad-de-agua)
>
> [4.2.2.1. Domain Layer 70](#domain-layer-1)
>
> [4.2.2.2. Interface Layer 73](#interface-layer-1)
>
> [4.2.2.3. Application Layer 74](#application-layer-1)
>
> [4.2.2.4. Infrastructure Layer 75](#infrastructure-layer-1)
>
> [4.2.2.5. Bounded Context Software Architecture Component Level Diagrams 76](#bounded-context-software-architecture-component-level-diagrams-1)
>
> [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams 76](#bounded-context-software-architecture-code-level-diagrams-1)
>
> [4.2.2.6.1. Bounded Context Domain Layer Class Diagrams 77](#bounded-context-domain-layer-class-diagrams-1)
>
> [4.2.2.6.2. Bounded Context Database Design Diagram 77](#bounded-context-database-design-diagram-1)
>
> [4.2.3. Bounded Context: Generación de Reportes 77](#bounded-context-generación-de-reportes)
>
> [4.2.3.1. Domain Layer 78](#domain-layer-2)
>
> [4.2.3.2. Interface Layer 80](#interface-layer-2)
>
> [4.2.3.3. Application Layer 80](#application-layer-2)
>
> [4.2.3.4. Infrastructure Layer 81](#infrastructure-layer-2)
>
> [4.2.3.5. Bounded Context Software Architecture Component Level Diagrams 82](#_heading=h.vlpx4cfy2xaf)
>
> [4.2.3.6. Bounded Context Software Architecture Code Level Diagrams 82](#bounded-context-software-architecture-code-level-diagrams-2)
>
> [Conexiones y Relaciones entre Contextos: 83](#conexiones-y-relaciones-entre-contextos)
>
> [4.2.3.6.1. Bounded Context Domain Layer Class Diagrams 84](#bounded-context-domain-layer-class-diagrams-2)
>
> [4.2.3.6.2. Bounded Context Database Design Diagram 84](#bounded-context-database-design-diagram-2)
>
> [4.2.4. Bounded Context: Autenticación de Usuarios 84](#bounded-context-autenticación-de-usuarios)
>
> [4.2.4.1. Domain Layer 85](#domain-layer-3)
>
> [4.2.4.2. Interface Layer 86](#interface-layer-3)
>
> [4.2.4.3. Application Layer 87](#application-layer-3)
>
> [4.2.4.4. Infrastructure Layer 87](#infrastructure-layer-3)
>
> [4.2.4.5. Bounded Context Software Architecture Component Level Diagrams 89](#bounded-context-software-architecture-component-level-diagrams-3)
>
> [4.2.4.6. Bounded Context Software Architecture Code Level Diagrams 89](#section-9)
>
> [4.2.4.6.1. Bounded Context Domain Layer Class Diagrams 90](#bounded-context-domain-layer-class-diagrams-3)
>
> [4.2.4.6.2. Bounded Context Database Design Diagram 91](#bounded-context-database-design-diagram-3)

[**Conclusiones 139**](#_heading=h.5mr1pntf2qf2)

[**Bibliografía 140**](#bibliografía)

[**Anexos 140**](#_heading=h.urqtrfzcypvb)

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

En WaterGuard, nos dedicamos a revolucionar la forma en que se gestiona y monitorea el uso del agua mediante la integración de soluciones basadas en Internet de las Cosas (IoT). Nuestra visión es ser pioneros en la transformación del sector de la gestión del agua, proporcionando soluciones tecnológicas innovadoras que optimicen el monitoreo y la emisión de notificaciones en tiempo real ante niveles críticos, ya sean altos o bajos.

Somos un grupo de estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC), comprometidos con el desarrollo de soluciones tecnológicas que tengan un impacto real en las comunidades. Con WaterGuard, buscamos facilitar el acceso a un sistema de monitoreo hídrico moderno, accesible y adaptable.

**Visión:** Queremos contribuir a que el monitoreo del agua sea más práctico y preciso, permitiendo que el 80% de las comunidades puedan gestionar sus recursos hídricos de manera más eficiente y sostenible.

**Misión:** Nuestro propósito es hacer que el control del agua sea más accesible mediante la creación de herramientas que repliquen en tiempo real el estado de los tanques de agua, permitiendo una supervisión efectiva desde cualquier lugar y en cualquier momento.

### 1.1.2. Perfiles de integrantes del equipo

| ALUMNO 1 | FOTO |
|----------|------|
| Julio Ernesto Asillo Mendoza (u20201b482) - Ingeniería de Software | ![](media/image2.png) |
| Soy una persona activa y comprometida al momento de hacer trabajos grupales. Durante mi carrera como estudiante he adquirido conocimiento sobre programación y trabajo en equipo, por eso siento que daré un buen aporte a mi equipo del curso de Desarrollo de Soluciones IoT. | |

| Soy Diego Santivañez Filio (u202112321) - Ingeniería de Software. | ![](media/image3.png) |
|-------------------------------------------------------------------|------------------------|
| Estudiante de noveno ciclo de la carrera. Elegí esta carrera porque siempre me vi interesado en la tecnología y el funcionamiento de los distintos softwares que las personas usamos día a día las cuales son creadas a través de la programación. Espero poder realizar un aporte significativo a mi grupo. | |

| Mi nombre es Kevin Oliva Alva, actualmente me encuentro avanzando en el 10mo ciclo de la carrera de Ingeniería de Software en la universidad UPC (Universidad Peruana de Ciencias Aplicadas), además soy consultor semi-senior de RPA con Automation Anywhere. Creo firmemente que el éxito en proyectos grupales depende en gran medida de la capacidad de cada miembro para aprovechar sus fortalezas y complementarse para cubrir sus debilidades. | ![](media/image4.png) |

| Santos Alexis Patazca Calderón (u20201c269) - Ingeniería de Software | ![](media/image5.png) |
|-----------------------------------------------------------------------|------------------------|
| Me considero una persona proactiva con pensamiento estratégico, con habilidades en el ámbito de la programación y un gran espíritu investigador. Para este proyecto puedo aportar parte de mi conocimiento adquirido en el curso. Además, de las habilidades blandas tales como el trabajo en equipo, comunicación, entre otras. | |

| Leonel Alfaro Cumba(u20201a930) | ![](media/image6.jpg) |
|----------------------------------|------------------------|
| Ingeniería de Software | |
| Soy un estudiante apasionado por la tecnología y por entender cómo funcionan los software que usamos a diario. Mi interés por la programación me ha permitido profundizar tanto en conocimientos técnicos como en dinámicas de trabajo en equipo. Me considero plenamente comprometido con los proyectos colaborativos, cualidad con la que confío en aportar un valor significativo a cualquier grupo de trabajo. | |

| Carlos Arian Ramirez Mendoza (u202020108) | ![](media/image7.jpg) |
|--------------------------------------------|------------------------|
| Estudiante de Ingeniería de Software. Me gusta el desarrollo de productos de software que generen y aporten valor para quienes lo necesitan. Me interesa también el emprendimiento y el trabajo en equipo. Actualmente realizo mis prácticas en una reconocida entidad bancaria como auditor de TI. Siempre busco la mejora continua de mis habilidades técnicas y blandas, así como salir de mi zona de confort. | |

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

**What? (Qué)**

El problema detectado es la falta de monitoreo preciso y en tiempo real del nivel de agua en los tanques en comunidades rurales, lo que conduce a desperdicios o a la falta de agua en momentos críticos para estas poblaciones vulnerables.

**When? (Cuándo)**

El problema sucede cuando la necesidad de monitoreo continuo y eficiente es constante, especialmente en momentos de escasez de agua, mantenimiento de infraestructura, o cuando se requiere una gestión eficiente de los recursos.

**Where? (Dónde)**

Esta solución se aplica específicamente en comunidades rurales de Perú, donde la gestión del agua es crítica debido a la infraestructura limitada y el acceso reducido a servicios básicos

**Who? (Quién)**

Comunidades rurales, juntas de agua locales, organizaciones no gubernamentales que trabajan en zonas rurales, y entidades gubernamentales responsables de la gestión hídrica en áreas rurales.

**Why? (Por qué)**

Es crucial para optimizar el uso del agua, prevenir desperdicios, y asegurar la disponibilidad de este recurso vital en todo momento. También contribuye a la sostenibilidad y al uso responsable de los recursos naturales.

**How?**

Utilizando sensores IoT de bajo costo y bajo mantenimiento adaptados a las condiciones rurales, que recopilan datos del nivel de agua en tanques y los envían a una plataforma de monitoreo simple y accesible. El sistema incluye alertas tempranas y funciona con conectividad limitada, teniendo en cuenta las restricciones de infraestructura tecnológica en estas zonas.

**How much? (¿Cuánto cuesta o qué recursos se necesitan?)**

La problemática del agua en Perú es alarmante, y las estadísticas revelan la magnitud del desafío. Según la página de Rotoplas (2024), aproximadamente el 10% de la población peruana, equivalente a 3,3 millones de personas, no tiene acceso a una red pública de agua, y el 23% (6,4 millones) carece de conexiones de alcantarillado. Además, solo el 62% de las aguas negras reciben un tratamiento adecuado. Esto implica que una gran parte de la población recurre a la compra de agua a camiones cisterna, pagando hasta el doble del precio del agua de red, lo que genera problemas de acceso y salubridad.

Además, el Instituto Nacional de Estadística e Informática (INEI) informó en 2024 que el 73,7% de los peruanos no tiene acceso a agua de manera segura. Esto significa que más de dos tercios de la población carecen de acceso continuo a agua potable desde fuentes confiables como redes públicas, pilones o pilas, o no tienen suministro disponible las 24 horas del día. En áreas rurales, esta situación es aún más crítica, con un 97,5% de la población sin acceso a agua gestionada de manera segura, en comparación con un 67,8% en áreas urbanas (Infobae, 2024).

Estas estadísticas reflejan la severidad de la escasez de agua y la falta de acceso seguro en el Perú, subrayando la urgencia de soluciones innovadoras como las propuestas por WaterGuard para mejorar la gestión y el monitoreo del agua, y así optimizar su uso y distribución en todo el país.

**Antecedentes:**

En Perú, la gestión del agua es un desafío creciente debido a la distribución desigual de recursos hídricos y la falta de infraestructura adecuada. La mayor parte del agua se encuentra en la cuenca amazónica, una región con baja densidad de población. En contraste, la costa árida, que alberga a la mayoría de la población y la actividad económica del país, enfrenta una severa escasez de agua. Este desequilibrio, combinado con una infraestructura deficiente y una gestión ineficiente, ha resultado en problemas significativos de acceso al agua potable y servicios de alcantarillado.

**Problemática a resolver:**

La problemática central que WaterGuard busca resolver es la falta de un monitoreo eficiente y en tiempo real de los niveles de agua en los tanques específicamente en comunidades rurales de Perú, donde el 97,5% de la población no tiene acceso a agua gestionada de manera segura. Esta carencia de monitoreo conduce a una gestión ineficiente de los recursos hídricos limitados, resultando en desperdicio de agua, riesgos de escasez y falta de respuesta rápida ante emergencias. Además, estas comunidades dependen frecuentemente de soluciones temporales y costosas como camiones cisterna, exacerbando los problemas de salud pública y sostenibilidad.

WaterGuard ofrece una solución innovadora mediante la implementación de tecnología IoT para habilitar un monitoreo remoto y automatizado que optimiza el uso del agua, previene pérdidas y mejora la sostenibilidad del sistema, contribuyendo a una distribución más equitativa de este recurso vital en todo el país.

### 1.2.2 Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**Problem Statement 1**

En Perú, las comunidades rurales enfrentan una gestión ineficiente del agua debido a la falta de tecnologías adecuadas y accesibles para el monitoreo y control de los niveles de agua en tanques y sistemas de distribución. Esta ineficiencia se traduce en un uso deficiente del recurso, provocando desperdicio en algunas épocas mientras sufren de escasez crítica en otras. Además, la limitada infraestructura tecnológica y de comunicaciones en estas zonas impide la implementación de soluciones convencionales y la toma de decisiones rápidas por parte de los administradores locales de recursos hídricos.

Como resultado, estas comunidades rurales enfrentan desafíos significativos: costos elevados por la compra de agua de camiones cisterna, largas distancias para acceder a fuentes de agua, problemas de salud pública debido a la falta de acceso a agua segura y riesgos ambientales por el mal manejo del recurso hídrico. Existe una necesidad clara de una solución tecnológica adaptada a las condiciones rurales que permita un monitoreo y control eficiente del agua con requisitos mínimos de conectividad e infraestructura.

¿Cómo desarrollar una solución tecnológica basada en IoT y gemelos digitales que sea accesible, de bajo costo y fácil mantenimiento, que permita un monitoreo preciso de los niveles de agua, optimizando el uso del recurso y mejorando la gestión hídrica específicamente en comunidades rurales de Perú?

**Problem Statement 2**

En Perú, el 73,7% de la población no tiene acceso a agua gestionada de manera segura, especialmente en áreas rurales donde esta cifra se eleva al 97,5%. Esta situación es resultado de una infraestructura deficiente, la falta de monitoreo en tiempo real y una distribución desigual de los recursos hídricos. Las personas en estas áreas dependen de soluciones alternativas y costosas para acceder al agua, como la compra de agua a proveedores externos, lo cual no garantiza ni la seguridad ni la continuidad del suministro.

La falta de acceso a agua segura genera costos adicionales desproporcionados para las familias rurales, aumenta los riesgos de enfermedades y afecta significativamente su calidad de vida y productividad agrícola. Para abordar esta problemática, es necesario desarrollar una solución tecnológica específicamente adaptada a las condiciones rurales, con bajo costo, fácil instalación y mantenimiento, que facilite el monitoreo y control del agua de manera eficiente y segura en estas áreas vulnerables.

¿Cómo implementar un sistema de monitoreo y control de agua en tiempo real que sea sostenible en entornos rurales con conectividad limitada, que asegure un acceso más seguro y eficiente al agua, reduciendo los costos y riesgos asociados con la gestión inadecuada del recurso en comunidades rurales de Perú?

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions**

**Creo que mis clientes necesitan** una solución eficiente para monitorear y gestionar los recursos hídricos en tiempo real.

**Estas necesidades se pueden resolver con** un sistema basado en IoT y gemelos digitales que proporcione datos en tiempo real y control remoto de recursos hídricos.

**Mis clientes iniciales son** exclusivamente comunidades rurales, juntas de agua locales en zonas rurales, y organizaciones no gubernamentales que trabajan en áreas rurales de Perú**.**

**El valor #1 que un cliente quiere de mi servicio es** la capacidad de optimizar el uso del agua y reducir costos asociados al desperdicio del recurso.

**El cliente también puede obtener estos beneficios adicionales:** reducción de costos operativos, mejoras en la planificación de recursos, mayor sostenibilidad y un mejor manejo de emergencias relacionadas con el agua.

**Voy a adquirir la mayoría de mis clientes a través de** asociaciones con gobiernos locales, ONGs que trabajan en desarrollo rural, programas de capacitación comunitaria, y demostraciones directas en comunidades rurales.

**Haré dinero a través de** tarifas de instalación y mantenimiento de dispositivos IoT, y licencias de uso del software.

**Mi competencia principal en el mercado serán** empresas que ofrecen soluciones tradicionales de monitoreo de agua o tecnologías básicas de control de recursos hídricos.

**Los venceremos debido a** la innovación de nuestra tecnología en tiempo real, la facilidad de uso de nuestra plataforma, y la capacidad de integrar datos de múltiples fuentes en un solo sistema.

**Mi mayor riesgo de producto es** la limitada infraestructura tecnológica y de conectividad en comunidades rurales, así como posibles restricciones presupuestarias para la implementación inicial.

**Resolveremos esto a través de** programas de capacitación, demostraciones gratuitas y pruebas piloto que demuestren el valor y la efectividad de nuestra solución.

**User Assumptions**

¿Quién es el usuario?

Comunidades rurales, específicamente líderes comunitarios, operadores locales de sistemas de agua, y miembros de juntas rurales de agua.

¿Dónde encaja nuestro producto en su trabajo o vida?

El producto encaja en la gestión diaria del suministro de agua en comunidades rurales, permitiendo a los usuarios monitorear y controlar los niveles de agua con tecnología adaptada a sus condiciones, optimizando el uso del recurso escaso, y respondiendo rápidamente a emergencias sin depender de visitas presenciales constantes a los tanques de almacenamiento.

¿Qué problemas tiene nuestro producto? ¿Resolver?

Nuestro producto resuelve problemas de gestión ineficiente del agua, falta de monitoreo en tiempo real, desperdicio del recurso y costos elevados asociados a la compra de agua de fuentes externas.

¿Cuándo y cómo es nuestro producto usado?

El producto es usado diariamente por administradores y usuarios para monitorear y controlar los niveles de agua en tanques y sistemas de distribución a través de una plataforma digital accesible desde cualquier dispositivo con conexión a internet.



