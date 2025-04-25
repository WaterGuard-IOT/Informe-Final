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

#### 1.2.2.3. Lean UX Hypothesis Statements

1. Creemos que al implementar un sistema de monitoreo en tiempo real para los niveles de agua en tanques y sistemas de distribución, reduciremos el desperdicio de agua en un 20% en las comunidades que utilicen nuestro producto.

  > Sabremos que hemos tenido éxito cuando veamos una disminución del desperdicio de agua reportado por los administradores de recursos hídricos y un aumento en la eficiencia del uso del agua en las comunidades.

2. Creemos que proporcionar alertas automáticas sobre niveles críticos de agua y posibles fugas aumentará la capacidad de respuesta de los usuarios ante emergencias relacionadas con el agua en un 30%.

  > Sabremos que esto es cierto si vemos una mejora en los tiempos de respuesta ante emergencias y una reducción de daños relacionados con fugas de agua en los primeros tres meses de uso.

3. Creemos que integrar datos históricos y análisis predictivo en nuestra plataforma ayudará a los administradores a planificar mejor el suministro de agua y reducirá los costos operativos en un 15%.

  > Sabremos que hemos tenido éxito cuando los usuarios reporten una planificación más eficiente del suministro de agua y una reducción en los costos asociados con la compra y distribución de agua.

4. Creemos que desarrollar una interfaz de usuario intuitiva y fácil de usar mejorará la adopción del producto por parte de los usuarios en un 40% en las primeras seis semanas de lanzamiento.

  > Sabremos que esto es cierto si las encuestas de satisfacción del usuario muestran una alta puntuación en facilidad de uso y si la tasa de adopción del producto supera nuestras expectativas iniciales.

5. Creemos que ofrecer capacitación directa en las comunidades y un sistema con mínimos requisitos técnicos aumentará la tasa de adopción del producto en un 50% dentro de los primeros seis meses en comunidades rurales.

  > Sabremos que hemos tenido éxito cuando veamos un aumento significativo en el número de comunidades rurales que adoptan nuestra solución y se convierten en usuarios de pago después del período de demostración.

6. Creemos que desarrollar un sistema que funcione con conectividad intermitente o limitada permitirá que comunidades rurales con infraestructura de comunicaciones deficiente puedan beneficiarse de nuestra solución, ampliando nuestro mercado en un 30%.

  > Sabremos que esto es cierto cuando veamos una adopción significativa de nuestra solución en comunidades rurales que anteriormente no podían implementar sistemas de monitoreo debido a problemas de conectividad.

#### 1.2.2.4. Lean UX Canvas

| **Problema del Negocio** | **Soluciones** | **Resultados del negocio** |
|---------------------------|----------------|----------------------------|
| El problema principal del negocio es la ineficiencia en la gestión del agua y el desperdicio significativo que ocurre específicamente en comunidades rurales. Estas comunidades carecen de acceso seguro y continuo al agua, y enfrentan costos elevados por soluciones temporales. Solucionar estos problemas mediante una tecnología adaptada a entornos rurales que permita una gestión más eficiente y sostenible del agua es fundamental para el éxito del negocio. | Implementar una plataforma digital de bajo costo y mantenimiento mínimo que use tecnologías IoT adaptadas a entornos rurales para ofrecer monitoreo en tiempo real, alertas automáticas y análisis predictivo básico. El sistema funcionará con conectividad intermitente y será fácil de instalar y mantener por los propios miembros de la comunidad, permitiéndoles optimizar el uso del agua, detectar fugas y planificar mejor los recursos hídricos. | Los resultados esperados para el negocio incluyen el aumento de la eficiencia en la gestión del agua por parte de los clientes, la reducción de costos operativos relacionados con el consumo de agua, y la generación de ingresos sostenibles mediante la venta y suscripción de la plataforma WaterGuard a empresas y comunidades. |
| **Usuarios y Clientes** | | **Resultados del usuario** |
| Comunidades rurales: Habitantes de áreas con acceso limitado a agua que buscan una solución para monitorear y gestionar mejor el recurso hídrico disponible. Incluye juntas de agua rurales, líderes comunitarios y operadores locales de sistemas de agua que necesitan optimizar la gestión con recursos limitados. | | Los usuarios deberían experimentar un mejor acceso al agua, una reducción significativa del desperdicio de este recurso y mayor control sobre su consumo. Esto se traducirá en ahorros de costos, mejoras en la sostenibilidad ambiental y una mayor satisfacción general con la gestión de recursos hídricos. |
| **Hypothesis** | **¿Qué es lo más importante que necesitamos aprender primero?** | **¿Cuál es la menor cantidad de trabajo que necesitamos hacer para resolver dudas y para hacer lo más importante?** |
| 1. Creemos que al implementar un sistema de monitoreo en tiempo real para los niveles de agua en tanques y sistemas de distribución, reduciremos el desperdicio de agua en un 20% en las comunidades que utilicen nuestro producto. | - Necesitamos aprender si las empresas y comunidades rurales están dispuestas a adoptar nuestra solución de monitoreo de agua en tiempo real y si encuentran valor en las alertas automáticas y la optimización del uso del agua. | Lo mínimo que necesitamos hacer es desarrollar una versión mínima viable del producto (MVP) que incluya las funciones básicas de monitoreo en tiempo real y alertas automáticas. Luego, realizar pruebas piloto con empresas y comunidades rurales para recopilar feedback inicial y validar la propuesta de valor. |
| 2. Creemos que proporcionar alertas automáticas sobre niveles críticos de agua y posibles fugas aumentará la capacidad de respuesta de los usuarios ante emergencias relacionadas con el agua en un 30%. | | |
| 3. Creemos que integrar datos históricos y análisis predictivo básico en nuestra plataforma ayudará a las juntas de agua y líderes comunitarios rurales a planificar mejor el suministro de agua y reducirá los costos operativos en un 15%. | | |
| 4. Creemos que desarrollar una interfaz de usuario intuitiva y fácil de usar mejorará la adopción del producto por parte de los usuarios en un 40% en las primeras seis semanas de lanzamiento. | | |
| 5. Creemos que diseñar un sistema que funcione con mínimos requerimientos de infraestructura (energía solar, conectividad intermitente) permitirá la adopción en comunidades rurales remotas, expandiendo nuestro impacto a zonas tradicionalmente excluidas de soluciones tecnológicas. | | |

## 1.3. Segmentos objetivo

**Comunidades Rurales**

Las comunidades rurales a menudo enfrentan desafíos en el acceso al agua segura debido a la falta de infraestructura adecuada y recursos limitados. Estas comunidades necesitan una forma de gestionar mejor el agua disponible para asegurar un suministro constante y seguro. Nuestra solución les ofrecerá un sistema fácil de usar para monitorear los niveles de agua en tiempo real y gestionar el uso de este recurso de manera eficiente, reduciendo el desperdicio y mejorando la calidad de vida de los residentes.

![](media/image8.png)

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

- **Suez Smart Solutions**: Es una empresa multinacional francesa con una larga historia en el sector del agua y la gestión de residuos. Suez Smart Solutions es una división de Suez que se especializa en soluciones tecnológicas avanzadas para la gestión de recursos hídricos. La empresa utiliza tecnologías como IoT (Internet de las Cosas), análisis de datos y sistemas de control en tiempo real para optimizar el uso del agua y mejorar la eficiencia en la gestión de redes de suministro de agua y tratamiento de aguas residuales.

- **Xylem Inc**: Es una empresa estadounidense que se especializa en la tecnología del agua, ofreciendo soluciones innovadoras para el manejo y tratamiento de agua y aguas residuales. Xylem se destaca por su enfoque en la sostenibilidad y la eficiencia energética, desarrollando productos y sistemas que ayudan a mejorar la distribución, el tratamiento y el uso eficiente del agua.

- **Veolia Water Technologies**: Es una subsidiaria de Veolia Environnement, una multinacional francesa que es un líder global en la gestión del agua, residuos y energía. Veolia Water Technologies se enfoca en el diseño y la provisión de soluciones tecnológicas para el tratamiento de agua y aguas residuales. La empresa ofrece una amplia gama de servicios que incluyen la ingeniería de sistemas de tratamiento de agua, soluciones de gestión de recursos hídricos, y productos químicos para el tratamiento del agua.

- **Siemens Water Solutions**: Es una división de Siemens, una de las mayores empresas de ingeniería y tecnología del mundo, con sede en Alemania. Siemens Water Solutions se enfoca en ofrecer tecnologías avanzadas para la automatización y control de sistemas de gestión del agua. Siemens integra sus soluciones de automatización con tecnologías de tratamiento de agua para optimizar el uso del agua, mejorar la eficiencia energética, y asegurar un suministro constante y seguro en infraestructuras críticas.

### 2.1.1. Análisis competitivo

| ¿Por qué llevar a cabo este análisis? | ¿De qué manera nos ayuda a analizar las características que el usuario busca de una plataforma como la nuestra? | | | | |
|--------------------------------------|--------------------------------------------------|----------|----------|----------|----------|
| | Nos permite adaptarnos y mejorar en aspectos diferentes a los rivales lo que nos ayudará a destacar y atraer público | | | | |
| Competidores | | Suez Smart Solutions | Xylem Inc | Veolia Water | Siemens Water |
| Perfil | Overview | ![](media/image9.png) | ![](media/image10.png) | ![](media/image11.png) | ![](media/image12.png) |
| | Ventaja Competitiva | Ofrece soluciones avanzadas de monitoreo y gestión de recursos hídricos a través de plataformas IoT, con un enfoque en control en tiempo real y análisis predictivo. | Empresa líder en tecnología del agua que combina hardware robusto con software intuitivo para una gestión eficiente y automatizada de los recursos hídricos. | Soluciones integrales para el tratamiento y la gestión del agua, con un enfoque en la calidad y la sostenibilidad mediante la integración de IoT y tecnologías avanzadas de tratamiento de agua. | Siemens integra tecnología avanzada en sus sistemas de automatización y control de recursos hídricos, con un enfoque en eficiencia energética y reducción de costos operativos. |
| Perfil del Marketing | Mercado objetivo | Suez Smart Solutions se enfoca en grandes empresas, municipalidades, y organizaciones gubernamentales que gestionan redes de agua complejas. Su mercado principal incluye ciudades con necesidades de infraestructura avanzada y empresas que buscan cumplir con regulaciones ambientales estrictas. | Xylem Inc. apunta a industrias, proveedores de servicios públicos y gobiernos que necesitan gestionar y optimizar el uso del agua en gran escala | Veolia se dirige a clientes industriales, urbanos y agrícolas que requieren soluciones de alta tecnología para la gestión del agua. | Siemens se dirige a industrias pesadas, plantas de energía, y grandes proveedores de servicios públicos que requieren una gestión integral del agua y la energía |
| | Estrategias de Marketing | Suez utiliza una combinación de participación en ferias y eventos del sector, colaboración con gobiernos locales y contenido técnico de alta calidad | Xylem utiliza estrategias de marketing basadas en la educación del cliente, incluyendo webinars, talleres y publicaciones técnicas. | La estrategia de marketing de Veolia se centra en su reputación global y su capacidad para ofrecer soluciones personalizadas. Participan activamente en licitaciones públicas y privadas. | Siemens utiliza una estrategia de marketing basada en la innovación y la calidad, destacando sus avances tecnológicos y su capacidad para integrar soluciones complejas. |
| Perfil del producto | Productos y Servicios | **AQUADVANCED®:** Plataforma de monitoreo y gestión de agua en tiempo real. **ON'connect™:** Solución IoT para la medición inteligente de agua. **Consultoría y Servicios de Optimización:** Asesoría especializada en la gestión eficiente de redes de agua. | **Flygt SmartRun®:** Sistema de control inteligente para estaciones de bombeo. **Sensus iPERL®:** Contadores de agua con tecnología IoT para medición avanzada. **Leopold® Filterworx:** Soluciones de filtración y tratamiento de agua. | **Aquavista™:** Plataforma de gestión inteligente de agua que integra IoT y análisis de datos. **Actiflo®:** Sistema avanzado de clarificación de agua para plantas de tratamiento. **HYDREX™:** Gama de productos químicos para el tratamiento de agua. | **SIPROCESS GA700:** Solución de automatización para plantas de tratamiento de agua. **SIMATIC PCS 7:** Sistema de control de procesos para la gestión integral del agua. **Soluciones de Energía Híbrida:** Sistemas que integran energía renovable para el suministro de agua. |
| | | | | | |
| | Precios y Costos | Un proyecto típico podría oscilar entre $10,000 y $500,000 dependiendo de la complejidad. | Un proyecto podría variar desde $20,000 hasta varios millones de dólares, dependiendo del alcance. | Los proyectos pueden costar desde $50,000 hasta millones, dependiendo de la complejidad. | Un proyecto puede variar desde $100,000 hasta varios millones de dólares. |
| | Canales de distribución (Web y/o Móvil) | **Ventas Directas:** A través de su equipo de ventas especializado. **Asociaciones con Gobiernos Locales:** Implementación de soluciones en áreas municipales | **Distribuidores Globales:** Red de distribuidores y revendedores en más de 150 países. **Consultoría Directa:** Implementación y soporte directamente a través de Xylem. | **Contratos Públicos:** Participación en licitaciones públicas y privadas. **Consultoría Directa:** A través de su red global de consultores e ingenieros. | **Ventas Directas:** A través de su fuerza de ventas global y oficinas regionales. **Distribuidores Autorizados:** Red de partners y distribuidores especializados en automatización. |
| | | | | | |
| Análisis SWOT | Desarrollo del startup y competidores, mediante sus fortalezas que deberían apoyar sus oportunidades y de la misma manera contribuir a lo que se define como posibles ventajas competitivas. | | | | |
| | Fortalezas | Amplia experiencia en la gestión de recursos hídricos y soluciones de infraestructura. Tecnología avanzada en monitoreo en tiempo real y análisis predictivo. Fuerte presencia global con proyectos en diversas regiones del mundo. Capacidad para integrar soluciones personalizadas en infraestructuras existentes. | Amplia gama de productos y soluciones que cubren todas las necesidades de gestión del agua. Fuerte enfoque en innovación tecnológica y eficiencia energética. Red global de distribución que asegura un alcance amplio y un servicio técnico sólido. Reputación consolidada en el mercado del agua y servicios públicos. | Posición de liderazgo en soluciones de tratamiento de agua y gestión sostenible. Experiencia en grandes proyectos de infraestructura y capacidad para personalizar soluciones según las necesidades del cliente. Fuerte enfoque en la sostenibilidad y cumplimiento de normativas ambientales. Amplia gama de productos químicos y tecnologías de tratamiento de agua. | Fuerte capacidad de innovación y desarrollo en soluciones de automatización y control de recursos hídricos. Integración de soluciones energéticamente eficientes que reducen los costos operativos de los clientes. Reputación sólida y confiabilidad en la industria, respaldada por una marca global fuerte. Capacidad para ofrecer soluciones llave en mano que cubren desde el diseño hasta la implementación completa. |
| | Oportunidades | Expansión en mercados emergentes con necesidades críticas de gestión del agua. Desarrollo de nuevas soluciones basadas en tecnologías emergentes como la inteligencia artificial y machine learning. Creciente demanda de soluciones sostenibles y respetuosas con el medio ambiente. Asociaciones con gobiernos y organizaciones internacionales para grandes proyectos de infraestructura. | Aumento de la demanda de tecnologías sostenibles y energéticamente eficientes. Crecimiento en mercados emergentes con infraestructuras en desarrollo. Expansión en el mercado de IoT y soluciones de ciudades inteligentes. Oportunidades para establecer asociaciones estratégicas con otros actores de la industria tecnológica. | Creciente preocupación por la sostenibilidad y el cumplimiento de regulaciones ambientales que impulsa la demanda de sus soluciones. Expansión en mercados en desarrollo con necesidades críticas de tratamiento de agua. Oportunidades de innovación en el tratamiento de aguas residuales y reciclaje de agua. Creciente demanda de soluciones integradas que combinen tratamiento y gestión de recursos hídricos. | Creciente demanda de soluciones de automatización y control en infraestructuras de agua. Expansión en mercados de energías renovables y sostenibilidad, donde la gestión eficiente del agua es crucial. Desarrollo de soluciones híbridas que integren energías renovables y gestión del agua. Potencial para alianzas estratégicas en proyectos de infraestructura a gran escala. |
| | Debilidades | Alto costo de implementación, lo que puede limitar su acceso a pequeñas empresas o comunidades con recursos limitados. Dependencia de proyectos a gran escala que requieren largos ciclos de venta y desarrollo. Posible rigidez en la adaptación de soluciones para mercados locales con infraestructuras menos avanzadas. | Competencia en precios con actores locales o empresas más pequeñas que ofrecen soluciones más económicas. Complejidad en la implementación de sus soluciones, lo que puede ser un obstáculo para clientes con menos recursos técnicos. Alta dependencia de la venta de hardware, lo que puede limitar la flexibilidad en modelos de negocio basados en software. | Altos costos operativos y de implementación que pueden limitar su acceso a ciertos mercados. Dependencia de proyectos a gran escala que pueden verse afectados por cambios en el financiamiento o políticas gubernamentales. Complejidad en la gestión de soluciones químicas y de tratamiento que requieren un alto nivel de especialización. | Alto costo de sus soluciones, lo que puede ser prohibitivo para pequeños y medianos clientes. Complejidad en la integración de sistemas, lo que requiere un alto nivel de personalización y soporte técnico. Dependencia de la venta de soluciones complejas que pueden tener largos ciclos de venta e implementación. |
| | Amenazas | Competencia de empresas más pequeñas y ágiles que ofrecen soluciones más económicas. Cambios en las regulaciones gubernamentales que podrían afectar su capacidad para operar en ciertos mercados. Dependencia de clientes grandes y proyectos gubernamentales que pueden verse afectados por cambios políticos. | Rápido avance tecnológico de nuevos competidores que pueden ofrecer soluciones más avanzadas o disruptivas. Riesgos regulatorios y cambios en las políticas ambientales que pueden afectar el desarrollo de proyectos. Presión de costos en mercados altamente competitivos, lo que puede reducir los márgenes de ganancia. | Competencia de nuevas empresas con soluciones innovadoras y más económicas. Cambios en las regulaciones internacionales que podrían impactar su modelo de negocio. Fluctuaciones en el costo de los insumos químicos utilizados en sus procesos de tratamiento. | Avance de competidores con soluciones más asequibles y fáciles de implementar. Riesgos asociados a la dependencia de grandes proyectos gubernamentales e industriales. Vulnerabilidad a cambios en las políticas energéticas y ambientales que podrían impactar su oferta de productos. |



