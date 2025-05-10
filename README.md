<div align="center">

<img src="img/logo_upc.png" alt="Logo UPC" width="100"/>

# Universidad Peruana De Ciencias Aplicadas

## Ingeniería de Software

### Informe de Trabajo Final

### Desarrollo de Aplicaciones Open Source 

**Sección:** 
4310

**Profesor:**  
Ivan Robles Fernández

**Integrantes:**
<div style="text-align: left; display: inline-block;">
    <ul>
        <li>Victor Andres Cruz Ibarra - U202311053</li>
        <li>Rafael Andres Vivanco Salazar - U202311064</li>
        <li>Ricardo Fernando Cardenas Minaya - U202310004</li>
        <li>Jarod Jack Cespedes Pillco - U202318588</li>
        <li>Ronald Joel Peralta Chipa -U202224619</li>
    </ul>
</div>

**2025 - 1**

</div>

---

# <font color="red">**Registro de Versiones del Informe**</font>

| Versión | Fecha      | Autor                          | Descripción de modificación      |
|---------|------------|--------------------------------|----------------------------------|
| TB1     | 26/01/2025 | Ronald Joel Peralta Chipa - Victor Andres Cruz Ibarra - Ricardo Fernando Cardenas Minaya - Rafael Andres Vivanco Salazar - Jarod Jack Cespedes Pillco   | Capitulo 1, Capitulo 2, Capitulo 3, Capitulo 4, Capitulo 5 |
| TB2     |            |                                |                                  |
| TB3     |            |                                |                                  |

# <font color="red">**Project Report Collaboration Insights**</font>

Enlace de la organización para el reporte del proyecto: https://github.com/orgs/project-OpenSource-4310/repositories

**TB1**

Para el desarrollo del informe correspondiente a la entrega TB1, se estableció la implementación de secciones de la siguiente manera para cada integrante del equipo:

|Integrante|Tareas Asignadas|
|-|-|
|Victor Andres Cruz Ibarra|Style Guidelines, Information Architecture, Landing Page UI Design, Web Applications UI/UI Design, Web Applications Prototyping|
|Rafael Andres Vivanco Salazar| Startup Profile, Solution Profile, Domain-Driven Software Architecture, Software Object-Oriented Design y Database Design|
|Ricardo Fernando Cardenas Minaya |Competidores, Análisis competitivo, To-Be Scneario Mapping, User Stories, Impact Mapping y Product Backlog|
|Jarod Jack Cespedes Pillco | Source Code Management, Source Style Guide, Software Deployment Configuration|
|Ronald Joel Peralta Chipa|Análisis de entrevistas, NeedFinding, User personas, User Task Matrix, User Journey Mapping, Empathy Mapping, As-is Scenario Mapping.|

# <font color="red">**Contenido**</font>

### Tabla de contenidos

- [**Registro de Versiones del Informe**](#registro-de-versiones-del-informe)
- [**Project Report Collaboration Insights**](#project-report-collaboration-insights)
- [**Contenido**](#contenido)
  - [Tabla de contenidos](#tabla-de-contenidos)
- [**Student Outcome**](#student-outcome)
- [ **Capítulo I: Introducción** ](#-capítulo-i-introducción-)
  - [**1.1. Startup Profile**](#11-startup-profile)
    - [**1.1.1. Descripción de la Startup**](#111-descripción-de-la-startup)
    - [**1.1.2. Perfiles de integrantes del equipo**](#112-perfiles-de-integrantes-del-equipo)
  - [**1.2. Solution Profile**](#12-solution-profile)
    - [**1.2.1 Antecedentes y problemática**](#121-antecedentes-y-problemática)
     - [**1.2.2 Lean UX Process**](#122-lean-ux-process)
    - [**1.2.2.1. Lean UX Problem Statements**](#1221-lean-ux-problem-statements)
    - [**1.2.2.2. Lean UX Assumptions**](#1222-lean-ux-assumptions)
    - [**1.2.2.3. Lean UX Hypothesis Statements**](#1223-lean-ux-hypothesis-statements)
    - [**1.2.2.4. Lean UX Canvas**](#1224-lean-ux-canvas)
  - [**1.3. Segmentos objetivo**](#13-segmentos-objetivo)
- [ **Capítulo II: Requirements Elicitation \& Analysis**](#-capítulo-ii-requirements-elicitation--analysis)
  - [**2.1. Competidores**](#21-competidores)
    - [**2.1.1. Análisis competitivo**](#211-análisis-competitivo)
    - [**2.1.2. Estrategias y tácticas frente a competidores**](#212-estrategias-y-tácticas-frente-a-competidores)
  - [**2.2. Entrevistas**](#22-entrevistas)
    - [**2.2.1. Diseño de entrevistas**](#221-diseño-de-entrevistas)
    - [**2.2.2. Registro de entrevistas**](#222-registro-de-entrevistas)
    - [**2.2.3. Análisis de entrevistas**](#223-análisis-de-entrevistas)
  - [**2.3. Needfinding**](#23-needfinding)
    - [**2.3.1. User Personas**](#231-user-personas)
    - [**2.3.2. User Task Matrix**](#232-user-task-matrix)
    - [**2.3.3. User Journey Mapping**](#233-user-journey-mapping)
    - [**2.3.4. Empathy Mapping**](#234-empathy-mapping)
    - [**2.3.5. As-is Scenario Mapping**](#235-as-is-scenario-mapping)
  - [**2.4. Ubiquitous Language**](#24-ubiquitous-language)
- [ **Capítulo III: Requirements Specification**](#-capítulo-iii-requirements-specification)
  - [**3.1. To-Be Scenario Mapping**](#31-to-be-scenario-mapping)
  - [**3.2. User Stories**](#32-user-stories)
  - [**3.3. Impact Mapping**](#33-impact-mapping)
  - [**3.4. Product Backlog**](#34-product-backlog)
- [**Capítulo IV: Product Design**](#capítulo-iv-product-design)
  - [**4.1. Style Guidelines**](#41-style-guidelines)
    - [**4.1.1. General Style Guidelines**](#411-general-style-guidelines)
    - [**4.1.2. Web Style Guidelines**](#412-web-style-guidelines)
  - [**4.2. Information Architecture**](#42-information-architecture)
    - [**4.2.1. Organization Systems**](#421-organization-systems)
    - [**4.2.2. Labeling Systems**](#422-labeling-systems)
    - [**4.2.3. SEO Tags and Meta Tags**](#423-seo-tags-and-meta-tags)
    - [**4.2.4. Searching Systems**](#424-searching-systems)
    - [**4.2.5. Navigation Systems**](#425-navigation-systems)
  - [**4.3. Landing Page UI Design**](#43-landing-page-ui-design)
    - [**4.3.1. Landing Page Wireframe**](#431-landing-page-wireframe)
    - [**4.3.2. Landing Page Mock-up**](#432-landing-page-mock-up)
  - [**4.4. Web Applications UX/UI Design**](#44-web-applications-uxui-design)
    - [**4.4.1. Web Applications Wireframes**](#441-web-applications-wireframes)
    - [**4.4.2. Web Applications Wireflow Diagrams**](#442-web-applications-wireflow-diagrams)
    - [**4.4.3. Web Applications Mock-ups**](#443-web-applications-mock-ups)
    - [**4.4.4. Web Applications User Flow Diagrams**](#444-web-applications-user-flow-diagrams)
  - [**4.5. Web Applications Prototyping**](#45-web-applications-prototyping)
  - [**4.6. Domain-Driven Software Architecture**](#46-domain-driven-software-architecture)
    - [**4.6.1. Software Architecture Context Diagram**](#461-software-architecture-context-diagram)
    - [**4.6.2. Software Architecture Container Diagrams**](#462-software-architecture-container-diagrams)
    - [**4.6.3. Software Architecture Components Diagrams**](#463-software-architecture-components-diagrams)
  - [**4.7. Software Object-Oriented Design**](#47-software-object-oriented-design)
    - [**4.7.1. Class Diagrams**](#471-class-diagrams)
    - [**4.7.2. Class Dictionary**](#472-class-dictionary)
  - [**4.8. Database Design**](#48-database-design)
    - [**4.8.1. Database Diagram**](#481-database-diagram)
- [**Capítulo V: Product Implementation, Validation & Deployment**](#capítulo-v-product-implementation-validation--deployment)
  - [**5.1. Software Configuration Management**](#51-software-configuration-management)
    - [**5.1.1. Software Development Environment Configuration**](#511-software-development-environment-configuration)
    - [**5.1.2. Source Code Management**](#512-source-code-management)
    - [**5.1.3. Source Code Style Guide & Conventions**](#513-source-code-style-guide--conventions)
    - [**5.1.4. Software Deployment Configuration**](#514-software-deployment-configuration)
  - [**5.2. Landing Page, Services & Applications Implementation**](#52-landing-page-services--applications-implementation)
    - [**5.2.1. Sprint 1**](#521-sprint-1)
      - [**5.2.1.1. Sprint Planning 1**](#5211-sprint-planning-1)
      - [**5.2.1.2. Aspect Leaders and Collaborators**](#5212-aspect-leaders-and-collaborators)
      - [**5.2.1.3. Sprint Backlog 1**](#5213-sprint-backlog-1)
      - [**5.2.1.4. Development Evidence for Sprint Review**](#5214-development-evidence-for-sprint-review)
      - [**5.2.1.5. Execution Evidence for Sprint Review**](#5215-execution-evidence-for-sprint-review)
      - [**5.2.1.6. Services Documentation Evidence for Sprint Review**](#5216-services-documentation-evidence-for-sprint-review)
      - [**5.2.1.7. Software Deployment Evidence for Sprint Review**](#5217-software-deployment-evidence-for-sprint-review)
      - [**5.2.1.8. Team Collaboration Insights during Sprint**](#5218-team-collaboration-insights-during-sprint)
    - [**5.2.2. Sprint 2**](#522-sprint-2)
      - [**5.2.2.1. Sprint Planning 2**](#5221-sprint-planning-2)
      - [**5.2.2.2. Aspect Leaders and Collaborators**](#5222-aspect-leaders-and-collaborators)
      - [**5.2.2.3. Sprint Backlog 2**](#5223-sprint-backlog-2)
      - [**5.2.2.4. Development Evidence for Sprint Review**](#5224-development-evidence-for-sprint-review)
      - [**5.2.2.5. Execution Evidence for Sprint Review**](#5225-execution-evidence-for-sprint-review)
      - [**5.2.2.6. Services Documentation Evidence for Sprint Review**](#5226-services-documentation-evidence-for-sprint-review)
      - [**5.2.2.7. Software Deployment Evidence for Sprint Review**](#5227-software-deployment-evidence-for-sprint-review)
      - [**5.2.2.8. Team Collaboration Insights during Sprint**](#5228-team-collaboration-insights-during-sprint)
  - [**5.3. Validation Interviews**](#53-validation-interviews)
    - [**5.3.1. Diseño de Entrevistas**](#531-diseño-de-entrevistas)
    - [**5.3.2. Registro de Entrevistas**](#532-registro-de-entrevistas)
    - [**5.3.3. Evaluaciones según heurísticas**](#533-evaluaciones-según-heurísticas)

[Conclusiones](#conclusiones)

[Bibliografía](#bibliografía)

[Anexos](#anexos)

# <font color="red">**Student Outcome**</font>

El curso contribuye al cumplimiento del Student Outcome ABET: </br> 
**ABET – EAC - Student Outcome 3** 
**Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias. 
En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.

</br>

<table style="border-collapse:collapse;border-spacing:0" class="tg"><thead><tr><th style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal"><span style="font-weight:normal">Criterio específico</span></th><th style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal"><span style="font-weight:normal">Acciones realizadas</span></th><th style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal"><span style="font-weight:normal">Conclusiones</span></th></tr></thead>
<tbody>
<tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">Comunica oralmente con efectividad a diferentes rangos de audiencia </td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">Andres Cruz: <br> TB1: Me aseguré de comunicarme de manera clara y respetuosa con mi equipo, transmitiendo mis ideas con asertividad y cumpliendo los compromisos adquiridos. <br> <br>Rafael Vivanco: <br> TB1: Durante las reuniones grupales, me centré en expresar mis ideas y propuestas con claridad, adaptando mi comunicación al contexto para facilitar la comprensión de todos. <br> <br>Fernando Cardenas: <br> TB1: Participé activamente en las tareas asignadas, aplicando mis conocimientos y habilidades para alcanzar los objetivos del equipo en tiempo y forma.<br> <br>Jack Cespedes: <br> TB1: Me mantuve comprometido con el equipo, colaborando en cada etapa del proceso y asegurándome de aportar soluciones para alcanzar los objetivos de manera eficiente. <br> <br>Joel Peralta <br> TB1: Me involucré en un diálogo abierto y constante con el equipo, lo que facilitó la distribución de tareas y la obtención de buenos resultados. Además, procuré mantener siempre una actitud colaborativa y proactiva para fortalecer la dinámica grupal.<br><br>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">TB1: A lo largo del proyecto, todos los integrantes del equipo lograron expresar sus ideas de manera oral con claridad y adecuación al contexto. Esto permitió que tanto compañeros como docentes comprendieran nuestras propuestas con facilidad. Gracias a esta capacidad de adaptación en la comunicación, pudimos distribuir tareas de forma eficiente, resolver inquietudes al instante y mantener una dinámica de colaboración efectiva en todo momento.<br> </td>
</tr>
<tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">Comunica por escrito con efectividad a diferentes rangos de audiencia.</td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">Andres Cruz: <br> TB1: Aporté en diferentes etapas del trabajo, garantizando que la información fuera clara, precisa y organizada, lo que permitió una mejor comprensión y aplicación en el desarrollo del proyecto. <br> <br>Rafael Vivanco: <br> TB1: Contribuí en diversos aspectos del trabajo, garantizando que la información fuera precisa, coherente y comprensible tanto para compañeros como para docentes. <br><br>Fernando Cardenas: <br> TB1: Participé activamente en las tareas asignadas, aplicando mis conocimientos y habilidades para cumplir con los objetivos del equipo de manera efectiva y dentro de los plazos establecidos.<br> <br>Jack Cespedes: <br> TB1:Cumplí con todas las actividades asignadas y considero que tuve un buen desempeño. Sin embargo, reconozco que debo mejorar en la gestión de mi tiempo para optimizar mis resultados en futuros proyectos.<br> <br>Joel Peralta: <br> TB1: Me involucré en la ejecución de las tareas grupales, aportando ideas y soluciones que contribuyeron al desarrollo del proyecto. También procuré mantener una comunicación fluida con mis compañeros para garantizar una coordinación eficiente<br> </td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">TB1: La eficacia del trabajo en equipo también se evidenció en nuestra habilidad para transmitir información de manera escrita. La documentación desarrollada, que abarcó informes, descripciones técnicas y contenido para la landing page, fue precisa, estructurada y accesible. Esto contribuyó a la validación del proyecto y garantizó que el producto final reflejara con claridad su propósito y funcionalidad.<br><br></td>
</tr>
</tbody></table>
</br></br>


# <font color="red"> **Capítulo I: Introducción** </font>

## **1.1. Startup Profile**

### **1.1.1. Descripción de la Startup**
Autonexo es un software especializado en la gestión integral del mantenimiento vehicular, diseñado para resolver los principales problemas que enfrentan técnicos (mecánicos) o personas al administrar sus flotas. Su objetivo es optimizar la organización, el seguimiento histórico, la gestión de repuestos y el cálculo de presupuesto, todo dentro de un sistema centralizado y fácil de usar.

La plataforma permite registrar vehículos, usuarios y repuestos, así como ejecutar y organizar mantenimientos. Además, ofrece herramientas para el control de inventario, cálculo de presupuesto, acceso al historial de mantenimiento para realizar los cambios necesarios en el vehículo.

Autonexo también contempla la integración de tecnologías opcionales como IoT para  un monitoreo en tiempo real, lo que potencia la eficiencia operativa y la estandarización de procesos en el área de mantenimiento vehicular.
<br>
### **1.1.2. Perfiles de integrantes del equipo**

| <img src="./img/group-members/RonaldPeralta.png" alt="Ronald Peralta" width="300"/> | **Ronald Peralta \- u202224619** <br> Mi nombre es Ronald Joel Peralta Chipa. Soy una persona comprometida con el orden, con un estilo de liderazgo democrático y una gran capacidad para escuchar y comprender. Disfruto crecer en equipo y siempre estoy dispuesto a aprender de los demás. En mi faceta como desarrollador, tengo un especial interés en los lenguajes C# y JavaScript. |
| :---: | ----- |
| <img src="./img/group-members/JarodCespedes.png" alt="Jarod Céspedes" width="300"/> | **Jarod Céspedes \- u202318588** <br> Mi nombre es Jarod Jack Céspedes Pillco, actualmente estoy cursando el quinto ciclo de la carrera Ingeniería de Software. Considero que soy atento, creativo y colaborador, siempre intentando apoyar a mi equipo en lo más que puedo. Además, tengo conocimientos en varios lenguajes de programación como C++, C#, Python y Java. |
| <img src="./img/group-members/RicardoCardenas.png" alt="Ricardo Cardenas" width="300"/> | **Ricardo Cardenas \- u202310004** <br> Mi nombre es Ricardo Cardenas, tengo 19 años y estoy en el 5to ciclo de Ingeniería de Software en la UPC. Soy apasionado, creativo y dedicado en lo que hago. Estoy comprometido a dar lo mejor de mí para lograr resultados sobresalientes y contribuir de manera significativa al equipo. |
| <img src="./img/group-members/VictorCruz.png" alt="Victor Cruz" width="300"/> | **Victor Cruz \- u202311053** <br> Mi nombre es Victor Cruz, tengo 19 años y estoy cursando mi 5to ciclo de la carrera de Ingeniería de Software en la UPC. Soy una persona entusiasta, creativa y comprometida con cada actividad que realizo. Estoy decidido a dar lo mejor de mi en este proyecto para lograr resultados de calidad. |
| <img src="./img/group-members/RafaelVivanco.png" alt="Rafael Vivanco" width="300"/>| **Rafael Vivanco \- u202311064** <br> Mi nombre es Rafael Vivanco, tengo 19 años y actualmente curso el 5to ciclo de la carrera de Ingeniería de Software en la UPC. Me considero una persona responsable con facilidad para adaptarme a distintos entornos y manejar varias tareas a la vez. Siempre doy lo mejor de mí en cada proyecto, aportando dedicación, esfuerzo y actitud positiva. |

## **1.2. Solution Profile**
### **1.2.1. Antecedentes y problemática**
### Who (¿Quién?)
Afecta principalmente a mecánicos encargados del mantenimiento y dueños de flotas (empresas o particulares).
### What (¿Qué?)
Los responsables del mantenimiento vehicular y dueños de vehículos enfrentan dificultades para organizar, planificar y dar seguimiento a los mantenimientos. También hay fallas en el control de inventario de repuestos, registros históricos desorganizados, y una falta de estandarización en los procesos. Esto genera pérdidas económicas, mantenimientos tardíos y decisiones poco informadas.
### Where (¿Dónde?)
Esta problemática se presenta en talleres mecánicos, empresas con flotas de vehículos (logística, transporte, servicios), y en general en cualquier entorno como el hogar donde se requiera un control sistemático del mantenimiento vehicular.
### When (¿Cuándo?)
Es un problema constante, pero se intensifica a medida que aumenta el número de vehículos  cuando se acercan fechas críticas de mantenimiento y no se tiene un control claro.
### Why (¿Por qué?)
Esto se debe a la falta de un sistema centralizado y especializado. Muchos utilizan métodos manuales (hojas de Excel, cuadernos) o herramientas genéricas  no adaptadas a las necesidades específicas del mantenimiento vehicular. Además, hay una escasa integración tecnológica (como IoT) que permita un monitoreo en tiempo real del estado de los vehículos.
### How (¿Cómo?)
A través del desarrollo de un software llamado Autonexo que permitirá reducir costos operativos, ahorrar tiempo y dinero perdido por vehículos fuera de servicio, mejorar el servicio al cliente y la eficiencia operativa a través de datos históricos confiables en una plataforma centralizada.
### How Much (¿Cuánto?)
Se estima que hasta el 65% de las empresas con flotas pequeñas o medianas no tienen un sistema especializado para el mantenimiento vehicular.  Las empresas pueden perder hasta un 20% más en costos de mantenimiento por no contar con una gestión eficiente. Es por esto que con Autonexo se espera una mejora de entre 30% a 50% en la eficiencia operativa, reducción de hasta un 25% en gastos por mantenimientos correctivos y una mejora del 40% en la trazabilidad y control del historial vehicular.
<br>
### **1.2.2. Lean UX Process**

#### **1.2.2.1. Lean UX Problem Statements**
Nuestra startup proporciona una plataforma especializada en la gestión integral del mantenimiento vehicular. Está dirigida específicamente a propietarios de vehículos y técnicos mecánicos que requieren una herramienta digital eficiente para organizar mantenimientos, controlar repuestos, calcular presupuestos y llevar un historial técnico actualizado. Nuestra solución centraliza todas estas funciones dentro de una plataforma intuitiva y accesible desde la web, optimizando el proceso de control vehicular.
Hemos identificado un factor crítico que afecta tanto a personas como a empresas: la desorganización en el mantenimiento de vehículos, lo que genera sobrecostos, fallas mecánicas evitables y pérdida de tiempo en tareas repetitivas o improvisadas.
Ante este problema, surge la pregunta: ¿Cómo podemos ayudar a los usuarios a gestionar de forma eficiente sus vehículos para reducir imprevistos, optimizar costos y asegurar un mantenimiento constante sin complicaciones?
<br>
#### **1.2.2.2. Lean UX Assumptions**
### Users:
Propietarios de vehículos particulares preocupados por el buen estado de sus autos.
Mecánicos que desean llevar un control digital de sus mantenimientos y repuestos.
### User Outcomes:
**1. ¿Quién es el usuario?** Nuestros usuarios serán dueños de vehículos y mecánicos. Los propietarios de vehículos buscan una solución para organizar y hacer un seguimiento eficiente de los mantenimientos de sus vehículos mientras que los mecánicos necesitan gestionar múltiples vehículos, repuestos, presupuestos y registros de mantenimientos para optimizar su operación.
<br>
**2. ¿Dónde encaja nuestro producto en su trabajo o vida?** AutoNexo se convierte en una herramienta diaria de consulta y planificación, tanto para usuarios que desean mantener su vehículo en buen estado como para técnicos que necesitan gestionar varios vehículos con eficiencia.
<br>
**3. ¿Qué problemas tiene nuestro producto y cómo se puede resolver?** Uno de los problemas principales es la adopción de la tecnología, ya que algunos usuarios pueden no estar familiarizados con el uso de plataformas digitales. Para resolver esto, debemos ofrecer una interfaz intuitiva y fácil de navegar, con un proceso de integración simple y tutoriales para que los nuevos usuarios puedan configurar rápidamente sus vehículos y 
mantenimientos. 
<br>
**4. ¿Cuándo y cómo es usado nuestro producto?** Será usado cada vez que los usuarios necesiten gestionar el mantenimiento de sus vehículos. El uso se realiza a través de una plataforma web accesible desde cualquier dispositivo, brindando flexibilidad en el momento de acceder a la información.
<br>
**5. ¿Qué características son importantes?** Algunas características importantes son:
Registro integral de vehículos, usuarios y repuestos
* Calendario de mantenimientos programados
* Control de inventario de repuestos
* Cálculo de presupuesto de reparaciones y mantenimientos
* Historial detallado de mantenimientos por vehículo
* Plataforma intuitiva y accesible desde web
* Servicio de mensajería entre usuario y mecánico<br>
**6. ¿Cómo debe verse nuestro producto y cómo debe comportarse?** Nuestro producto debe tener un diseño limpio y moderno. La interfaz debe ser clara y accesible, con menús fáciles de navegar y funciones bien definidas, sin sobrecargar al usuario con información innecesaria. En cuanto al comportamiento, la plataforma debe contar con tiempos de carga cortos y sin interrupciones. Las notificaciones y recordatorios deben ser automáticos, proporcionando una experiencia fluida y de confianza al usuario.
  
### Business Outcomes:
**1. Creo que mis clientes necesitan** una plataforma que les permita gestionar de forma eficiente el mantenimiento de sus vehículos, llevar control de repuestos, calcular presupuestos y acceder a un historial detallado de intervenciones.
<br>
**2. Estas necesidades se pueden resolver** mediante una solución digital centralizada, accesible desde la web, que automatice procesos, reduzca la improvisación y brinde herramientas de seguimiento y planificación de mantenimiento vehicular
<br>
**3. Mis clientes iniciales serán** propietarios de vehículos particulares y mecánicos que buscan mayor organización y eficiencia en el manejo de mantenimientos.
<br>
**4. El valor #1 que un cliente quiere de mi servicio** es poder llevar un control integral y ordenado del mantenimiento de sus vehículos en un solo lugar, sin depender de registros manuales o desorganizados.
<br>
**5. El cliente también puede obtener estos beneficios adicionales:** 
* Ahorro de tiempo y costos por mantenimientos tardíos o improvisados.
* Recordatorios automáticos y seguimiento personalizado.
* Control eficiente del inventario de repuestos.
* Generación de presupuestos claros y detallados.

**6. Voy a adquirir la mayoría de mis clientes a través de** marketing digital dirigido, contenido educativo sobre mantenimiento vehicular, y programas de referidos. 
<br>
**7. Haré dinero a través de** planes de suscripción mensual o anual para acceso premium, cobros por funcionalidades avanzadas, y alianzas comerciales con proveedores del sector automotriz.
<br>
**8. Mi competencia principal en el mercado serán** aplicaciones como Drivvo o Fleetio y softwares de gestión vehicular generalistas.
<br>
**9. Los venceremos debido a nuestro apoyo** enfocado especialmente en el contexto local, con una interfaz amigable, enfoque específico en propietarios individuales y técnicos, y funcionalidades relevantes como historial 
  detallado y gestión de repuestos.
<br>
**10. Mi mayor riesgo de producto es** que los usuarios no adopten la plataforma por considerar que sus métodos actuales (manuales o informales) ya les funcionan o por falta de conocimiento digital.
Resolveremos esto a través de capacitación básica, demostraciones gratuitas, versión gratuita con funcionalidades clave y testimonios de clientes satisfechos.
<br>
**11. ¿Qué otras suposiciones tenemos?** 
<br>
**Suposición 1:** Los mecánicos y dueños de vehículos están dispuestos a cambiar sus métodos actuales por una solución digital.
<br>
**Suposición 2:** Los usuarios consideran útil llevar un historial detallado y control digital del mantenimiento.
<br>
**Suposición 3:** El modelo de suscripción es viable para este segmento de usuarios.
<br>
**Suposición 4:** Los usuarios valorarán funciones adicionales como notificaciones, presupuestos y control de inventario.
<br>
**¿Eso, si se prueba que es falso, causará que nuestro negocio / proyecto no funcione?** 
Si los usuarios no consideran que el cambio a una solución digital aporta suficiente valor o si no están dispuestos a pagar por ello, el modelo de negocio no será sostenible ni escalable.

#### **1.2.2.3. Lean UX Hypothesis Statements**
**1. Creemos que** al ofrecer una plataforma centralizada para registrar vehículos, repuestos y mantenimientos, ayudaremos a los usuarios a organizar mejor sus procesos y reducir errores o pérdidas de información.
<br>
**Sabremos que** hemos tenido éxito cuando al menos el 70% de los usuarios registre y mantenga actualizado su historial de vehículos y mantenimientos en el primer mes.
<br>
**2. Creemos que** al integrar herramientas de control de inventario y cálculo automático de presupuestos, facilitaremos la gestión operativa y financiera tanto a mecánicos como a dueños de vehículos.
<br>
**Sabremos que** hemos tenido éxito cuando el 60% de los usuarios utilicen estas funciones para planificar o ejecutar mantenimientos dentro de la plataforma.
<br>
**3. Creemos que** al diseñar una interfaz web intuitiva y accesible, incentivaremos el uso constante de Autonexo incluso por usuarios sin experiencia técnica.
<br>
**Sabremos que** hemos tenido éxito cuando al menos el 75% de los usuarios activos utilicen la plataforma semanalmente para gestionar sus vehículos.
<br>
**4. Creemos que** al permitir el acceso al historial completo de mantenimiento, aumentaremos la confianza de los usuarios en sus decisiones de reparación o venta de vehículos.
<br>
**Sabremos que** hemos tenido éxito cuando el 50% de los usuarios consulten el historial como parte del proceso de evaluación del estado del vehículo.
<br>
#### **1.2.2.4. Lean UX Canvas**
|  | | |
|-------------|--------------|--------------|
| **Business Problem**<br>Autonexo es una plataforma que combina la eficiencia de un sistema digital con la gestión integral del mantenimiento vehicular. Su objetivo es ayudar a mecánicos y dueños de flotas a organizar, controlar y optimizar todas las actividades relacionadas con el mantenimiento de vehículos desde una sola herramienta. Ante la falta de seguimiento histórico, la desorganización en el manejo de repuestos, y la dificultad para presupuestar y programar mantenimientos, muchos usuarios recurren a métodos manuales o herramientas poco integradas que generan errores, pérdidas económicas y tiempos de inactividad. Además, enfrentan una experiencia fragmentada al usar múltiples sistemas para registrar vehículos, calcular costos o acceder a información técnica. | **Features**<br>- Registro integral de vehículos, usuarios y repuestos <br>- Calendario de mantenimientos programados <br>- Control de inventario de repuestos <br>- Cálculo de presupuesto de reparaciones y mantenimientos <br>- Historial detallado de mantenimientos por vehículo <br>- Plataforma intuitiva y accesible desde web <br>- Servicio de mensajería entre usuario y mecánico | **Business Outcomes**<br>- Reducir mantenimientos olvidados o tardíos mediante recordatorios y seguimiento digital <br>- Fidelizar a los usuarios con historial completo y recomendaciones personalizadas <br>- Posicionar a Autonexo como líder en Perú <br>- Mejorar la productividad de mecánicos y talleres reduciendo errores y tiempos de espera |
| **Customers**<br>Autonexo está dirigido a dueños de vehículos que buscan controlar sus mantenimientos de forma práctica y a técnicos o talleres que desean optimizar su gestión operativa. Ambos valoran soluciones digitales que les permitan organizar historiales, prevenir fallas, reducir costos y tomar decisiones informadas. | **Customer Benefits**<br>- Confianza y transparencia en reparaciones <br>- Mejora en la toma de decisiones <br>- Disminución de costos operativos <br>- Mejora de la reputación profesional (mecánicos) <br>- Acceso a estadísticas y reportes | **Hypothesis**<br>- Plataforma centralizada reducirá errores y mejorará la organización. Éxito: 70% mantiene historial en el primer mes. <br>- Inventario y presupuestos facilitarán la gestión. Éxito: 60% los usa para planificar o ejecutar mantenimientos. <br>- Interfaz intuitiva incentivará el uso. Éxito: 75% usa la plataforma semanalmente. |
| **¿Qué debemos aprender primero?**<br>Debemos entender cómo los técnicos y conductores actualmente organizan sus mantenimientos, qué herramientas usan, qué problemas enfrentan al llevar control manual, y si realmente valoran una solución integral que incluya presupuestos, inventario, entre otras cosas. | **¿Cuál es el menor esfuerzo para validar?**<br>- Desarrollar versión básica para registrar vehículos, usuarios, repuestos y mantenimientos <br>- Implementar funciones esenciales: historial y presupuesto simple <br>- Diseñar una interfaz web sencilla e intuitiva <br>- Aplicar encuestas a un grupo reducido de mecánicos y dueños de vehículos para validar si la solución resuelve sus principales problemas operativos |  |
<br>

## **1.3. Segmentos objetivo**
Con el propósito de llegar de manera efectiva a posibles clientes, Autonexo ha definido dos segmentos principales como público objetivo.
<br>
   **Segmento objetivo \#1: Dueños de flota o conductores**
    Personas que poseen uno o más vehículos personales y desean gestionar de forma eficiente el mantenimiento, control de gastos y estado general de su unidad, evitando olvidos o problemas mecánicos por falta de     seguimiento.
<br>
   Aspectos demográficos:
* Sexo: Masculino y femenino  
* Rango de edad: 25–50 años  
* Nivel socioeconómico: Clases B y C (media-alta y media)  
  Aspectos geográficos:  
* Nacionalidad: Perú  
* Zona geográfica: Urbana (principalmente Lima Metropolitana y otras ciudades con alta concentración vehicular)  
  Aspectos psicográficos:  
* Intereses: Cuidado del vehículo, control financiero, tecnología práctica, seguridad vial, soluciones digitales simples.  
* Estilo de vida: Conducen regularmente, valoran la comodidad y buscan evitar gastos imprevistos o pérdidas de tiempo por fallas mecánicas.  
* Actitudes: Son conscientes de la importancia del mantenimiento preventivo y están abiertos a herramientas digitales que les faciliten llevar un control ordenado, práctico y accesible desde su celular o computadora.<br>
    **Segmento objetivo \#2: Mecánicos**  
    Profesionales que trabajan de manera independiente o en talleres y desean gestionar mejor sus servicios, controlar inventarios, ofrecer presupuestos precisos y acceder a historiales de mantenimiento para brindar un     mejor servicio a sus clientes.
  <br>  
  Aspectos demográficos:  
* Sexo: Masculino (en su mayoría)  
* Rango de edad: 25–50 años  
* Nivel socioeconómico: Clases C y D (media y media-baja)  
  Aspectos geográficos:  
* Nacionalidad: Perú  
* Zona geográfica: Urbana (distritos con concentración de talleres y servicios automotrices)  
  Aspectos psicográficos:  
* Intereses: Reparación automotriz, optimización de tiempo, herramientas digitales accesibles, atención al cliente.  
* Estilo de vida: Profesionales prácticos, con un enfoque técnico, acostumbrados al trabajo manual, pero abiertos a soluciones tecnológicas si son simples y funcionales.  
* Actitudes: Desean mejorar la calidad de su servicio y organización interna. Valoran las plataformas que les permitan brindar un servicio más profesional sin complicaciones adicionales.
# <font color="red"> **Capítulo II: Requirements Elicitation & Analysis** </font>

## **2.1. Competidores**

### **2.1.1. Análisis competitivo**

### **2.1.2. Estrategias y tácticas frente a competidores**

## **2.2. Entrevistas**

### **2.2.1. Diseño de entrevistas**

### **2.2.2. Registro de entrevistas**

### **2.2.3. Análisis de entrevistas**

## **2.3. Needfinding**

### **2.3.1. User Personas**
  
### **2.3.2. User Task Matrix**

### **2.3.3. User Journey Mapping**

### **2.3.4. Empathy Mapping**

### **2.3.5. As-is Scenario Mapping**

## **2.4. Ubiquitous Language**

# <font color="red"> **Capítulo III: Requirements Specification** </font>

## **3.1. To-Be Scenario Mapping**

## **3.2. User Stories**

## **3.3. Impact Mapping**

## **3.4. Product Backlog**

# <font color="red"> **Capítulo IV: Product Design** </font>

## **4.1. Style Guidelines**

### 4.1.1. General Style Guidelines

### 4.1.2. Web Style Guidelines

## **4.2. Information Architecture**

### **4.2.1. Organization Systems**

### **4.2.2. Labeling Systems**

### **4.2.3. SEO Tags and Meta Tags**

### **4.2.4. Searching Systems**

### **4.2.5. Navigation Systems**

## **4.3. Landing Page UI Design**

### **4.3.1. Landing Page Wireframe**

### **4.3.2. Landing Page Mock-up**

## **4.4. Web Applications UX/UI Design**

### **4.4.1. Web Applications Wireframes**

### **4.4.2. Web Applications Wireflow Diagrams**

### **4.4.3. Web Applications Mock-ups**

### **4.4.4. Web Applications User Flow Diagrams**

## **4.5. Web Applications Prototyping**

## **4.6. Domain-Driven Software Architecture**

### **4.6.1. Software Architecture Context Diagram**

### **4.6.2. Software Architecture Container Diagrams**

### **4.6.3. Software Architecture Components Diagrams**

## **4.7. Software Object-Oriented Design**

### **4.7.1. Class Diagrams**

### **4.7.2. Diccionario de Clases**

## **4.8. Database Design**

### **4.8.1. Database Diagram**

# <font color="red"> **Capítulo V: Product Implementation, Validation & Deployment** </font>

## **5.1. Software Configuration Management**


### **5.1.1. Software Development Environment Configuration**


### **5.1.2. Source Code Management**

### **5.1.3. Source Code Style Guide & Conventions**

### **5.1.4. Software Deployment Configuration**

#### **5.2.1.2. Aspect Leaders and Collaborators**

#### **5.2.1.3. Sprint Backlog 1**

#### **5.2.1.4. Development Evidence for Sprint Review**

#### **5.2.1.5. Execution Evidence for Sprint Review**

#### **5.2.1.6. Services Documentation Evidence for Sprint Review**

#### **5.2.1.7. Software Deployment Evidence for Sprint Review**

#### **5.2.1.8. Team Collaboration Insights during Sprint**
### **5.2.2. Sprint 2**
#### **5.2.2.1. Sprint Planning 2**
#### **5.2.2.2. Aspect Leaders and Collaborators**
#### **5.2.2.3. Sprint Backlog 2**
#### **5.2.2.4. Development Evidence for Sprint Review**
#### **5.2.2.5. Execution Evidence for Sprint Review**
#### **5.2.2.6. Services Documentation Evidence for Sprint Review**
#### **5.2.2.7. Software Deployment Evidence for Sprint Review**
#### **5.2.2.8. Team Collaboration Insights during Sprint**

## **5.3. Validation Interviews**
### **5.3.1. Diseño de Entrevistas**
### **5.3.2. Registro de Entrevistas**
### **5.3.3. Evaluaciones según heurísticas**


## Conclusiones

## Bibliografía

## Anexos
