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

### 2.1.2. Estrategias y tácticas frente a competidores

**Innovación en Usabilidad:**

- **Estrategia:** Desarrollar una plataforma extremadamente intuitiva y fácil de usar específicamente diseñada para comunidades rurales con diferentes niveles de alfabetización digital.

- **Táctica:** Invertir en diseño UX/UI centrado en usuarios rurales, con interfaces visuales simples, instrucciones claras en lenguaje local y mínima necesidad de texto. Ofrecer una aplicación móvil que funcione con conexión intermitente y capacitación comunitaria para su uso.

**Personalización y Flexibilidad:**

- **Estrategia:** Ofrecer soluciones altamente personalizables que se adapten a las necesidades específicas de cada cliente, desde pequeñas instalaciones hasta grandes infraestructuras.

- **Táctica:** Implementar módulos adicionales que los clientes puedan agregar según sus necesidades, como análisis predictivo y gestión de calidad del agua.

**Optimización de Costos de Implementación:**

- **Estrategia:** Reducir los costos iniciales para las comunidades rurales a través de soluciones extremadamente económicas, de bajo mantenimiento y que puedan funcionar con infraestructura mínima.

- **Táctica:** Desarrollar kits de instalación IoT de bajo costo que los propios miembros de la comunidad puedan configurar, con componentes resistentes a condiciones adversas y manuales visuales paso a paso. Incluir opciones de alimentación por energía solar para zonas sin electricidad estable.

**Marketing Educativo:**

- **Estrategia:** Implementar una campaña de marketing que eduque al mercado sobre la importancia del monitoreo en tiempo real de recursos hídricos y los beneficios de la tecnología IoT.

- **Táctica:** Crear webinars, whitepapers, y casos de estudio que demuestran cómo WaterGuard puede mejorar la eficiencia y reducir costos. Establecer un blog corporativo para posicionarse como líder de opinión en la gestión de recursos hídricos.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

Preguntas Iniciales: Información Básica

1. **¿Cuál es su nombre?**

- **Objetivo:** Identificar al entrevistado.

2. **¿Cuál es su edad?**

- **Objetivo:** Recopilar datos demográficos que puedan influir en la percepción y adopción de la tecnología.

3. **¿Cuál es su rol o cargo dentro de su organización/comunidad?**

- **Objetivo:** Entender la responsabilidad específica del entrevistado en la gestión del agua o infraestructura.

4. **¿Cuánto tiempo lleva en su cargo actual?**

- **Objetivo:** Evaluar la experiencia del entrevistado en la gestión del agua y otros recursos.

5. **¿En qué región o localidad está ubicada su organización/comunidad?**

- **Objetivo:** Contextualizar la situación geográfica, que puede influir en los desafíos y necesidades relacionados con la gestión del agua.

Preguntas Generales sobre la Gestión del Agua

1. **¿Cuáles son los principales desafíos que enfrenta actualmente en la gestión del agua?**

- **Objetivo:** Identificar los problemas y obstáculos que encuentran en su día a día.

2. **¿Qué herramientas o métodos utiliza actualmente para monitorear y gestionar el uso del agua?**

- **Objetivo:** Conocer las soluciones actuales y evaluar su efectividad.

3. **¿Qué tan crítico es para usted el monitoreo en tiempo real del agua en su entorno?**

- **Objetivo:** Medir la importancia del monitoreo en tiempo real en su contexto.

Preguntas de Cierre

1. **¿Qué beneficios espera obtener de una nueva tecnología de gestión del agua?**

- **Objetivo:** Identificar los factores decisivos para la adopción de la solución.

2. **¿Estaría dispuesto a participar en un piloto o prueba de la tecnología propuesta por WaterGuard? ¿Por qué?**

- **Objetivo:** Medir el interés en una prueba inicial de la solución.

3. **¿Hay algún otro aspecto de la gestión del agua que le gustaría que abordamos con esta tecnología?**

- **Objetivo:** Identificar posibles mejoras o expansiones de la solución.

### 2.2.2. Registro de entrevistas

**Comunidades rurales**

Primer Entrevista:

Descripción del entrevistado:

![](media/image13.png)

- **Nombre**: jhon mamani Quispe

- **Edad**: 22 años

- **Distrito**: La Victoria, Lima

- **Resumen**: Jhon es un chico de una comunidad rural donde ayuda a sus padres con los cultivos desde que acabó la secundaria, por otro lado nos menciona que a veces no hay suministro de agua por problemas su sistema, como atascos, o que simplemente el rio no fluctúa suficiente, además de esto también nos menciona que si le gustaria nuestra solución y nos recomendó de tener distintos medio para la recolección del suministro de agua

- **Link de la Entrevista:**

> [https://drive.google.com/file/d/1xZ7Q-G_bLlCjzRgpAR1VzYxvMg31LPRi/view?usp=sharing](https://drive.google.com/file/d/1xZ7Q-G_bLlCjzRgpAR1VzYxvMg31LPRi/view?usp=sharing)

Segunda Entrevista:

![](media/image14.png)

- **Nombre**: Anderson Macedo

- **Edad**: 24 años

- **Distrito**: Puno

- **Resumen**: Anderson Macedo, un joven de 24 años de Puno, apoya como voluntario en su comunidad en temas de agua desde hace dos años. Señala que enfrentan problemas como la falta de monitoreo del agua, fugas y distribución ineficiente, especialmente en épocas de sequía. Actualmente, todo se gestiona de forma manual y considera crítico contar con un sistema en tiempo real. Está dispuesto a participar en un piloto tecnológico que permita controlar mejor el agua, reducir desperdicios y educar a la comunidad sobre su uso.

- **Link de la Entrevista:**

> [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c179_upc_edu_pe/EQVGlvs4oFNCvFjIItE3SpgBUyXDKfwkDASS4hL9BOJqRw?e=7NZLOj&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c179_upc_edu_pe/EQVGlvs4oFNCvFjIItE3SpgBUyXDKfwkDASS4hL9BOJqRw?e=7NZLOj&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

Tercera Entrevista:

Descripción del Entrevistado:
![](media/image15.png)

- **Nombre**: Paul Vega

- **Edad**: 20 años

- **Distrito**: Lurigancho

- **Resumen**: El entrevistado nació y vivió gran parte de su vida en el departamento de Ayacucho, específicamente en el pueblo-comunidad de Spite dentro de la provincia Victor Fajardo. Nos cuenta que al menos 2 veces a la semana tenían problemas con la conexión hacia su tanque de agua que usaban para la cosecha y a la vez para su consumo, nos cuenta que tener la gestión al alcance de la mano y ver el estado del agua ayudaría bastante como ver el PH y demás, debido a que la gente de dónde vive a veces no hierven bien el agua.

- **Link de la entrevista:**

> [https://youtu.be/aXAZWVor7tA](https://youtu.be/aXAZWVor7tA)

### 2.2.3. Análisis de entrevistas

**Comunidades Rurales:**

1. Necesidades: Las comunidades rurales necesitan herramientas sencillas que les permitan distribuir el agua de manera equitativa y eficiente para sus cultivos y consumo doméstico. Su prioridad es asegurar la disponibilidad del agua durante todo el año, especialmente en épocas de sequía, y hacerlo de manera sostenible.

2. Frustraciones: Las principales frustraciones en las comunidades rurales están relacionadas con la falta de acceso a tecnologías y la limitada capacitación disponible para aprender a utilizar herramientas de gestión del agua. Además, enfrentan problemas de recursos limitados, lo que dificulta la adopción de nuevas tecnologías.

3. Soluciones Deseadas: Las comunidades rurales buscan soluciones accesibles, económicas y fáciles de utilizar que no requieran un alto nivel técnico. Quieren herramientas que les permitan mejorar la gestión del agua sin complicaciones y que promuevan la sostenibilidad en sus prácticas agrícolas y domésticas.

4. Expectativas: Las comunidades rurales esperan mejorar la distribución del agua en un porcentaje considerable, reducir las pérdidas de este recurso, y asegurarse de que todos los miembros de la comunidad puedan acceder a la misma capacitación y conocimiento sobre el uso eficiente del agua. También esperan que las soluciones sean sostenibles y asequibles para su entorno.

## 2.3. Needfinding

### 2.3.1. User Personas

**La siguiente ficha es para el segmento de personas de comunidades rurales:** En este caso, nos enfocamos en la historia de Rosa, una mujer que vive en una comunidad rural y se encarga de gestionar el uso del agua para su hogar y sus cultivos. Rosa busca herramientas que le permitan distribuir el agua de manera eficiente y asegurar su disponibilidad durante las temporadas secas. Sin embargo, sus principales frustraciones son la falta de acceso a tecnología asequible, la escasez de agua en épocas críticas y la dificultad para mantener un control preciso del recurso.

**Usuario 1:** Comunidades rurales

![](media/image16.png)

### 2.3.2. User Task Matrix

La sección de User Task Matrix es una herramienta útil para entender las tareas y objetivos que cada User Persona desea lograr al utilizar nuestro producto. En esta sección, se presentarán las matrices de tareas para cada uno de los User Personas previamente definidos.

**Usuario 1: Comunidades Rurales**

| **Task** | **Rosa** |  |
|----------|----------|--|
| | **Frecuencia** | **Importancia** |
| Distribuir el agua para cultivos | Alta | Alta |
| Asegurar el abastecimiento del agua | Alta | Alta |
| Participar en reuniones comunitarias | Media | Media |
| Implementar prácticas sostenibles | Media | Alta |

### 2.3.3. User Journey Mapping

La sección de User Journey Mapping es una herramienta útil para entender la experiencia del usuario desde el inicio hasta el final de su interacción con nuestro producto o servicio. En esta sección, se presentarán los mapas de experiencia para cada uno de los User Personas previamente definidos.

**Usuario 1:** Usuario de comunidades rurales

![](media/image17.png)

### 2.3.4. Empathy Mapping

**Usuario 1:** Usuario de comunidades rurales

![](media/image18.png)

### 2.3.5. As-is Scenario Mapping

Comunidades rurales que gestionan el agua

![](media/image19.png)

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

Hogares en comunidades rurales que gestionan el agua:

![](media/image20.png)

Link miro:
[https://miro.com/welcomeonboard/WlVRUmt4UWkyNWdLaEVucmx0dnNGMmd4Q0NiVUNWZmxCUHNOaUpKOGF1MGNWTXRpaHlHR1czMjJ5ZFU4SWdLdUJqZjJUc0w1NkdoTjZtNkVPbnZBemRQOGdiNnI4MzFRQTB3eHdmRWRjcmZNRmJUS3JlMXA5VC9hSzRrVHFxbHNQdGo1ZEV3bUdPQWRZUHQzSGl6V2NBPT0hdjE=?share_link_id=948205957300](https://miro.com/welcomeonboard/WlVRUmt4UWkyNWdLaEVucmx0dnNGMmd4Q0NiVUNWZmxCUHNOaUpKOGF1MGNWTXRpaHlHR1czMjJ5ZFU4SWdLdUJqZjJUc0w1NkdoTjZtNkVPbnZBemRQOGdiNnI4MzFRQTB3eHdmRWRjcmZNRmJUS3JlMXA5VC9hSzRrVHFxbHNQdGo1ZEV3bUdPQWRZUHQzSGl6V2NBPT0hdjE=?share_link_id=948205957300)

## 3.2. User Stories

Epics:

**EP-001**: Configuración e Integración de Sensores IoT.

**EP-002**: Monitoreo y Gestión en Tiempo Real.

**EP-003**: Capacitación y Soporte al Usuario.

**EP-004**: Personalización y Acceso a Datos.

**EP-005**: Automatización y Reportes.

**EP-006**: Gestión y Actualización del Sistema.

**EP-007**: Soporte Técnico y Monitoreo de Estado.

**EP-008**: Seguridad y Auditoría de Datos.

**EP-009**: Automatización y Gestión del Control de Bombas de Agua

| **US-ID** | **Título** | **Descripción** | **Criterios de Aceptación** | **ID de Epic Relacionado** |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-001 | Configurar sensores IoT | Como técnico, quiero configurar los sensores IoT para monitorear los tanques de agua. | **Escenario: Conexión Exitosa de Sensores** **Dado que** el técnico tiene los sensores IoT listos para instalar. **Cuando** conecta los sensores a los tanques de agua y los empareja con el sistema central. **Entonces** el sistema confirma la conexión exitosa mostrando los datos en tiempo real. **Escenario: Verificación Automática de Sensores** **Dado que** el técnico ha instalado los sensores IoT en los tanques. **Cuando** inicia la configuración en el panel de control del sistema. **Entonces** el sistema realiza una verificación automática y muestra un mensaje de éxito si todos los sensores están funcionando correctamente. | EP-001 |
| US-002 | Integrar Sensores con Base de Datos y Backend | Como usuario, quiero que los datos de los sensores se almacenen en una base de datos en tiempo real y luego se envíen al backend para su procesamiento y visualización. | **Escenario: Almacenamiento y Envío de Datos a la Base de Datos** **Dado que** los sensores IoT están configurados correctamente y transmiten datos,  **Cuando** los sensores capturan datos como el nivel de agua, pH, temperatura, etc., **Entonces,** los datos se envían y se almacenan en la base de datos en tiempo real. **Escenario: Envío de Datos al Backend** **Dado que** los datos están almacenados en la base de datos, **Cuando** el sistema recibe los datos de la base de datos, **Entonces**, el backend procesa la información y la prepara para ser visualizada por el usuario en la interfaz de la plataforma. | EP-001 |
| US-003 | Monitorear datos de agua | Como agricultor, quiero poder monitorear el nivel de agua en los tanques a través de una app móvil. | **Escenario: Visualización del Nivel de Agua** **Dado que** el agricultor ha instalado los sensores IoT en los tanques de agua y ha descargado la app móvil. **Cuando** abre la app y selecciona el tanque que desea monitorear. **Entonces** la app muestra el nivel de agua actual en tiempo real, junto con un gráfico histórico del día. **Escenario: Notificación de Bajo Nivel de Agua** **Dado que** el agricultor está utilizando la app para monitorear varios tanques de agua en diferentes ubicaciones. **Cuando** el nivel de agua en uno de los tanques cae por debajo del umbral mínimo establecido. **Entonces** la app envía una notificación push alertando al agricultor de que debe revisar y posiblemente rellenar el tanque. | EP-002 |
| US-004 | Configurar alertas personalizadas | Como usuario, quiero configurar alertas personalizadas para recibir notificaciones sobre niveles de agua. | **Escenario: Configuración de Alertas por Nivel Bajo** **Dado que** el usuario quiere recibir alertas cuando el nivel de agua esté bajo. **Cuando** entra en la configuración de alertas y establece un umbral mínimo de nivel de agua. **Entonces** el sistema envía una notificación por correo electrónico y SMS cuando el nivel cae por debajo del umbral. **Escenario: Notificaciones Push** **Dado que** el usuario necesita recibir alertas en su dispositivo móvil. **Cuando** se activa la opción de recibir notificaciones push en la app. **Entonces** el sistema envía alertas push instantáneas cuando se alcanzan los umbrales establecidos. | EP-002 |
| US-005 | Capacitar usuarios en el uso del sistema | Como administrador, quiero realizar capacitaciones para que los usuarios aprendan a usar el sistema. | **Escenario: Sesión de Capacitación Inicial** **Dado que** el administrador necesita que los usuarios aprendan a utilizar el sistema. **Cuando** organiza una sesión de capacitación donde se explica cómo usar la plataforma. **Entonces** los usuarios comprenden los conceptos básicos y pueden navegar por la plataforma de forma autónoma. **Escenario: Acceso a Recursos de Capacitación** **Dado que** los usuarios requieren apoyo continuo en el uso del sistema. **Cuando** el administrador proporciona acceso a tutoriales y documentos de capacitación en línea. **Entonces** los usuarios pueden consultar los recursos en cualquier momento para resolver dudas. | EP-003 |
| US-006 | Acceder al historial de datos | Como usuario, quiero acceder al historial de datos para analizar el uso del agua a lo largo del tiempo. | **Escenario: Análisis Semanal de Datos** **Dado que** el usuario necesita analizar el uso del agua durante la última semana.

**Cuando** ingresa a la sección de historial en la plataforma y selecciona el rango de fechas correspondiente.

**Entonces** el sistema muestra un gráfico detallado que representa los niveles de agua durante los días seleccionados, permitiendo al usuario identificar patrones de consumo.

**Escenario: Exportación de Historial de Datos**

**Dado que** el usuario requiere exportar el historial de datos para compartirlo con su equipo.

**Cuando** selecciona la opción de exportar desde la interfaz de la plataforma.

**Entonces** el sistema genera un archivo CSV con los datos de los últimos 30 días y lo descarga automáticamente en su dispositivo. | EP-004 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-007 | Optimizar el riego basado en datos | Como agricultor, quiero optimizar el riego en función de los datos recibidos del sistema. | **Escenario: Recomendación de Riego**

**Dado que** el agricultor monitorea los niveles de agua regularmente.

**Cuando** el sistema detecta que el nivel de agua es óptimo para el riego.

**Entonces** el sistema recomienda ajustar el riego en función de los datos obtenidos.

**Escenario: Ajuste Automático de Riego**

**Dado que** el sistema está configurado para automatizar tareas.

**Cuando** el nivel de agua alcanza el umbral establecido para el riego.

**Entonces** el sistema ajusta automáticamente los tiempos de riego sin intervención manual. | EP-002 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-008 | Automatizar acciones basadas en alertas | Como técnico, quiero que el sistema ejecute acciones automáticamente cuando se activen alertas. | **Escenario: Activación de Bomba de Agua**

**Dado que** el sistema está configurado para responder a alertas críticas.

**Cuando** el nivel de agua baja drásticamente en uno de los tanques.

**Entonces** el sistema activa automáticamente la bomba de agua para rellenar el tanque.

**Escenario: Cierre Automático de Válvula**

**Dado que** se detecta una fuga de agua a través de los sensores.

**Cuando** el sistema recibe la alerta de fuga.

**Entonces** el sistema cierra automáticamente la válvula principal para evitar pérdida de agua. | EP-005 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-009 | Reportar datos incorrectos | Como usuario, quiero poder reportar datos incorrectos para que sean corregidos rápidamente. | **Escenario: Reporte de Anomalías en Datos**

**Dado que** el usuario detecta que los datos mostrados no coinciden con la realidad.

**Cuando** selecciona la opción de reportar error en la app.

**Entonces** el sistema envía un informe detallado al equipo técnico para su revisión.

**Escenario: Confirmación de Reporte**

**Dado que** el usuario ha reportado un error en los datos.

**Cuando** el sistema recibe el reporte.

**Entonces** el usuario recibe una notificación confirmando que su reporte ha sido enviado y está en revisión. | EP-004 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-010 | Actualizar software del sistema | Como administrador, quiero poder actualizar el software del sistema de manera remota y segura. | **Escenario: Actualización Automática en Horario Programado**

**Dado que** el administrador programa actualizaciones regulares del software.

**Cuando** llega la hora programada para la actualización.

**Entonces** el sistema se actualiza automáticamente sin interrumpir el servicio y envía una notificación de finalización exitosa.

**Escenario: Respaldo Automático Antes de la Actualización**

**Dado que** el sistema debe mantener la integridad de los datos.

**Cuando** se inicia una actualización del software.

**Entonces** el sistema crea automáticamente un respaldo de todos los datos antes de proceder con la actualización. | EP-006 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-011 | Monitorear el estado de los sensores | Como usuario, quiero recibir notificaciones sobre el estado de los sensores IoT para asegurar su correcto funcionamiento. | **Escenario: Alerta de Sensor Fuera de Línea**

**Dado que** el sistema monitorea continuamente el estado de los sensores IoT.

**Cuando** un sensor se desconecta o deja de enviar datos.

**Entonces** el sistema envía una alerta inmediata al usuario indicando que el sensor está fuera de línea.

**Escenario: Verificación del Estado de Todos los Sensores**

**Dado que** el usuario quiere asegurarse de que todos los sensores están funcionando correctamente.

**Cuando** accede al panel de control del sistema.

**Entonces** el sistema muestra el estado actual de todos los sensores, incluyendo cualquier fallo o error detectado. | EP-007 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-012 | Proporcionar acceso multiusuario | Como administrador, quiero que múltiples usuarios puedan acceder al sistema con diferentes niveles de permiso. | **Escenario: Creación de Roles y Permisos**

**Dado que** el administrador necesita gestionar el acceso de diferentes usuarios al sistema.

**Cuando** crea roles personalizados con permisos específicos en la plataforma.

**Entonces** los usuarios asignados a esos roles solo pueden acceder a las funciones para las que tienen permisos.

**Escenario: Asignación de Roles a Nuevos Usuarios**

**Dado que** se han añadido nuevos usuarios al sistema.

**Cuando** el administrador asigna roles a estos nuevos usuarios.

**Entonces** los nuevos usuarios reciben un acceso seguro y sus actividades quedan registradas según sus permisos. | EP-006 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-013 | Configurar panel de control personalizado | Como usuario, quiero personalizar mi panel de control para ver solo la información más relevante para mí. | **Escenario: Personalización de Widgets en el Panel**

**Dado que** el usuario desea ver solo la información más relevante en su panel de control.

**Cuando** personaliza su panel añadiendo y organizando widgets.

**Entonces** el sistema guarda automáticamente la configuración del panel y la muestra en su próxima sesión.

**Escenario: Restauración de Configuración de Panel por Defecto**

**Dado que** el usuario quiere restablecer su panel de control a la configuración original.

**Cuando** selecciona la opción de restaurar configuración por defecto.

**Entonces** el sistema elimina las personalizaciones y muestra el panel en su estado predeterminado. | EP-004 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-014 | Generar informes automáticos | Como administrador, quiero que el sistema genere informes automáticos sobre el uso del agua. | **Escenario: Generación Semanal de Informes**

**Dado que** el administrador necesita recibir informes sobre el uso del agua.

**Cuando** el sistema genera un informe automático cada semana.

**Entonces** el informe se envía por correo electrónico al administrador con gráficos y análisis de tendencias.

**Escenario: Configuración de Informes Personalizados**

**Dado que** el administrador desea configurar los informes según las necesidades específicas.

**Cuando** ajusta las configuraciones de los informes automáticos en la plataforma.

**Entonces** el sistema genera y envía informes personalizados que cumplen con los criterios establecidos. | EP-005 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-015 | Integrar el sistema con otras plataformas | Como administrador, quiero que el sistema se integre con otras plataformas de gestión de recursos. | **Escenario: Sincronización de Datos con Otra Plataforma**

**Dado que** el administrador necesita que los datos del sistema se integren con una plataforma externa.

**Cuando** configura la API para la sincronización de datos.

**Entonces** los datos se sincronizan automáticamente entre el sistema y la plataforma externa, sin necesidad de intervención manual.

**Escenario: Importación de Datos desde una Plataforma Externa**

**Dado que** el administrador necesita importar datos desde otra plataforma al sistema.

**Cuando** utiliza la integración configurada para importar datos.

**Entonces** el sistema recibe y almacena los datos importados, permitiendo su visualización y análisis. | EP-006 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-016 | Ofrecer soporte técnico en línea | Como usuario, quiero poder contactar con soporte técnico en línea si tengo problemas con el sistema. | **Escenario: Contacto a Soporte a través de Chat en Vivo**

**Dado que** el usuario tiene un problema técnico con el sistema.

**Cuando** utiliza la función de chat en vivo disponible en la plataforma.

**Entonces** el equipo de soporte técnico responde en tiempo real y asiste al usuario en la resolución del problema.

**Escenario: Envío de Ticket de Soporte**

**Dado que** el usuario necesita asistencia técnica fuera del horario de soporte en vivo.

**Cuando** envía un ticket de soporte desde la plataforma.

**Entonces** el sistema genera un número de ticket y el usuario recibe una confirmación por correo electrónico con el tiempo estimado de respuesta. | EP-007 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-017 | Configurar usuarios como administradores locales | Como superadministrador, quiero asignar permisos de administrador local para que otros gestionen su propio sistema. | **Escenario: Asignación de Permisos de Administrador Local**

**Dado que** el superadministrador necesita que otros usuarios gestionen sus áreas específicas del sistema.

**Cuando** asigna permisos de administrador local a estos usuarios.

**Entonces** los administradores locales pueden gestionar las configuraciones y datos de su área asignada sin acceso a las demás áreas.

**Escenario: Registro de Actividades de Administradores Locales**

**Dado que** el superadministrador necesita monitorear los cambios realizados por los administradores locales.

**Cuando** los administradores locales realizan cambios en el sistema.

**Entonces** el sistema registra todas las actividades realizadas y genera un informe que el superadministrador puede revisar. | EP-006 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-018 | Implementar seguridad de datos | Como usuario, quiero que mis datos estén seguros y cifrados en todo momento. | **Escenario: Cifrado de Datos en Tránsito**

**Dado que** el sistema maneja datos sensibles.

**Cuando** se transmiten datos entre el usuario y el servidor.

**Entonces** el sistema cifra todos los datos en tránsito usando SSL/TLS, asegurando que los datos no puedan ser interceptados.

**Escenario: Autenticación de Dos Factores (2FA)**

**Dado que** el usuario desea asegurar el acceso a su cuenta.

**Cuando** activa la autenticación de dos factores en la configuración de su cuenta.

**Entonces** el sistema requiere un segundo factor de autenticación, como un código enviado al teléfono móvil, para permitir el acceso. | EP-008 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-019 | Configurar notificaciones push | Como usuario, quiero recibir notificaciones push en mi dispositivo móvil sobre cambios importantes en el sistema. | **Escenario: Activación de Notificaciones Push**

**Dado que** el usuario quiere recibir notificaciones instantáneas sobre eventos importantes.

**Cuando** activa las notificaciones push desde la configuración de su dispositivo móvil.

**Entonces** el sistema envía notificaciones push instantáneas sobre los eventos configurados.

**Escenario: Personalización de Notificaciones Push**

**Dado que** el usuario desea recibir notificaciones solo para ciertos eventos.

**Cuando** personaliza las opciones de notificación en la app.

**Entonces** el sistema solo envía notificaciones push para los eventos seleccionados por el usuario. | EP-002 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-020 | Auditar las actividades del sistema | Como auditor, quiero revisar todas las actividades realizadas en el sistema para garantizar la integridad y seguridad. | **Escenario: Revisión de Logs de Auditoría**

**Dado que** el auditor necesita revisar las actividades realizadas en el sistema.

**Cuando** accede a los logs de auditoría desde el panel de administración.

**Entonces** el sistema muestra un registro detallado de todas las acciones realizadas por los usuarios, incluyendo la hora y el usuario responsable.

**Escenario: Exportación de Logs de Auditoría**

**Dado que** el auditor necesita analizar los datos fuera del sistema.

**Cuando** selecciona la opción de exportar los logs de auditoría.

**Entonces** el sistema genera un archivo exportable que contiene todos los registros de auditoría dentro del rango de fechas seleccionado. | EP-008 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-021 | Activación Automática de las Bombas de Agua | Como técnico, quiero que las bombas de agua se activen automáticamente cuando el nivel de agua llegue a un umbral crítico, para evitar que el tanque se quede sin agua. | **Escenario: Activación Automática por Nivel Bajo**

**Dado que** el sistema monitorea los niveles de agua en los tanques de forma constante,

**Cuando** el nivel de agua cae por debajo del umbral mínimo establecido,

**Entonces**, el sistema activa automáticamente las bombas de agua para llenar el tanque hasta el nivel adecuado.

**Escenario: Control Manual de las Bombas**

**Dado que** el técnico desea controlar manualmente las bombas,

**Cuando** accede a la plataforma del sistema y selecciona la opción de control manual,

**Entonces**, el sistema permite activar o desactivar las bombas de agua desde la interfaz. | EP-009 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-022 | Notificación de Baja del Nivel de Agua y Activación de Bombas | Como agricultor, quiero recibir una notificación cuando el nivel de agua esté bajo y la bomba de agua se haya activado, para saber que el sistema está funcionando correctamente. | **Escenario: Notificación de Activación de Bombas**

**Dado que** el nivel de agua en el tanque está bajo,

**Cuando** el sistema activa la bomba de agua para llenar el tanque,

**Entonces** el agricultor recibe una notificación push alertando que las bombas están siendo activadas para restaurar el nivel de agua.

**Escenario: Confirmación de Relleno Completo**

**Dado que** el sistema ha activado la bomba de agua,

**Cuando** el nivel de agua alcanza el umbral predeterminado,

**Entonces** el agricultor recibe una notificación confirmando que el tanque está lleno y las bombas se han desactivado automáticamente. | EP-009 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-023 | Desactivación Automática de las Bombas | Como usuario, quiero que el sistema desactive automáticamente las bombas una vez que el nivel de agua haya alcanzado el umbral máximo para evitar el sobrellenado de los tanques. | **Escenario: Desactivación Automática de Bombas**

**Dado que** el nivel de agua en el tanque ha alcanzado el umbral máximo,

**Cuando** el sistema detecta que el tanque está lleno,

**Entonces**, las bombas se desactivan automáticamente para evitar el desbordamiento.

**Escenario: Confirmación de Desactivación**

**Dado que** el sistema ha desactivado las bombas,

**Cuando** el agricultor consulta la plataforma,

**Entonces**, el sistema muestra un mensaje indicando que las bombas se han desactivado porque el nivel de agua es adecuado. | EP-009 |
|-----------|------------|-----------------|----------------------------|---------------------------|
| US-024 | Supervisión y Monitoreo del Estado de las Bombas | Como administrador, quiero poder supervisar el estado de las bombas (encendidas/apagadas) desde el sistema, para asegurarme de que todo esté funcionando correctamente. | **Escenario: Visualización del Estado de las Bombas**

**Dado que** el administrador accede al panel de control,

**Cuando** se muestra el estado de las bombas de agua en el sistema,

**Entonces**, el administrador puede ver si las bombas están encendidas o apagadas, junto con el nivel de agua actual en los tanques.

**Escenario: Alerta de Falla en la Bomba**

**Dado que** el sistema monitorea el funcionamiento de las bombas,

**Cuando** el sistema detecta una falla en las bombas,

**Entonces**, se envía una alerta al administrador notificando que las bombas no están funcionando correctamente. | EP-009 |
