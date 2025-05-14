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
| TB2     | 13/05/2025 | Ronald Joel Peralta Chipa - Victor Andres Cruz Ibarra - Ricardo Fernando Cardenas Minaya - Rafael Andres Vivanco Salazar - Jarod Jack Cespedes Pillco   | Correción del TB1, Sprint 2 en Capitulo 5|
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

**TB2**

Para el desarrollo del informe correspondiente a la entrega TB2, se estableció la implementación de secciones de la siguiente manera para cada integrante del equipo:

|Integrante|Tareas Asignadas|
|-|-|
|Victor Andres Cruz Ibarra|Correción del Capítulo 4 e implementación de pantallas del frontend app|
|Rafael Andres Vivanco Salazar|Correción del Capítulo 1 e implementación de pantallas del frontend app|
|Ricardo Fernando Cardenas Minaya |Correción del Capítulo 3 e implementación de pantalla del frontend app|
|Jarod Jack Cespedes Pillco | Correción del Capítulo 5 e implementación de pantallas del frontend app|
|Ronald Joel Peralta Chipa |Correción del Capítulo 2 e implementación de pantallas del frontend app|
# <font color="red">**Contenido**</font>

### Tabla de contenidos

- [Universidad Peruana De Ciencias Aplicadas](#universidad-peruana-de-ciencias-aplicadas)
  - [Ingeniería de Software](#ingeniería-de-software)
    - [Informe de Trabajo Final](#informe-de-trabajo-final)
    - [Desarrollo de Aplicaciones Open Source](#desarrollo-de-aplicaciones-open-source)
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
    - [**1.2.1. Antecedentes y problemática**](#121-antecedentes-y-problemática)
    - [**1.2.2. Lean UX Process**](#122-lean-ux-process)
      - [**1.2.2.1. Lean UX Problem Statements**](#1221-lean-ux-problem-statements)
      - [**1.2.2.2. Lean UX Assumptions**](#1222-lean-ux-assumptions)
      - [**1.2.2.3. Lean UX Hypothesis Statements**](#1223-lean-ux-hypothesis-statements)
      - [**1.2.2.4. Lean UX Canvas**](#1224-lean-ux-canvas)
  - [**1.3. Segmentos objetivo**](#13-segmentos-objetivo)
- [ **Capítulo II: Requirements Elicitation \& Analysis** ](#-capítulo-ii-requirements-elicitation--analysis-)
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
- [ **Capítulo III: Requirements Specification** ](#-capítulo-iii-requirements-specification-)
  - [**3.1. To-Be Scenario Mapping**](#31-to-be-scenario-mapping)
  - [**3.2. User Stories**](#32-user-stories)
      - [**Epics**](#epics)
      - [**User Stories**](#user-stories)
  - [**3.3. Impact Mapping**](#33-impact-mapping)
  - [**3.4. Product Backlog**](#34-product-backlog)
- [ **Capítulo IV: Product Design** ](#-capítulo-iv-product-design-)
  - [**4.1. Style Guidelines**](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
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
    - [**4.7.2. Diccionario de Clases**](#472-diccionario-de-clases)
  - [**4.8. Database Design**](#48-database-design)
    - [**4.8.1. Database Diagram**](#481-database-diagram)
- [ **Capítulo V: Product Implementation, Validation \& Deployment** ](#-capítulo-v-product-implementation-validation--deployment-)
  - [**5.1. Software Configuration Management**](#51-software-configuration-management)
    - [**5.1.1. Software Development Environment Configuration**](#511-software-development-environment-configuration)
    - [**5.1.2. Source Code Management**](#512-source-code-management)
    - [**5.1.3. Source Code Style Guide \& Conventions**](#513-source-code-style-guide--conventions)
    - [**5.1.4. Software Deployment Configuration**](#514-software-deployment-configuration)
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
  - [Conclusiones](#conclusiones)
  - [Bibliografía](#bibliografía)
  - [Anexos](#anexos)

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
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">Andres Cruz: <br> TB1: Me aseguré de comunicarme de manera clara y respetuosa con mi equipo, transmitiendo mis ideas con asertividad y cumpliendo los compromisos adquiridos. <br> <br>Rafael Vivanco: <br> TB1: Durante las reuniones grupales, me centré en expresar mis ideas y propuestas con claridad, adaptando mi comunicación al contexto para facilitar la comprensión de todos. <br> <br>Fernando Cardenas: <br> TB1: Participé activamente en las tareas asignadas, aplicando mis conocimientos y habilidades para alcanzar los objetivos del equipo en tiempo y forma.<br> <br>Jack Cespedes: <br> TB1: Me mantuve comprometido con el equipo, colaborando en cada etapa del proceso y asegurándome de aportar soluciones para alcanzar los objetivos de manera eficiente. <br> <br>Joel Peralta <br> TB1: Me involucré en un diálogo abierto y constante con el equipo, lo que facilitó la distribución de tareas y la obtención de buenos resultados. Además, procuré mantener siempre una actitud colaborativa y proactiva para fortalecer la dinámica grupal.<br><br> Andres Cruz: <br> TB2: En el TB2, aporté al levantamiento de observaciones y al diseño de pantallas, comunicando mis ideas con claridad para mejorar la interfaz y asegurar una experiencia de usuario efectiva. <br> <br>Rafael Vivanco: <br> TB2: Durante las reuniones grupales, me centré en expresar mis ideas y propuestas con claridad, adaptando mi comunicación al contexto para facilitar la comprensión de todos. <br> <br>Fernando Cardenas: <br> TB2: Contribuí al diseño del frontend y levanté observaciones que mejoraron la calidad visual y funcional del proyecto, reforzando la coordinación mediante una comunicación efectiva. <br> <br>Joel Peralta <br> TB2: Participé activamente en la creación de pantallas y en la revisión crítica del diseño, aportando ideas claras que facilitaron mejoras en el producto final.<br><br>Jack Céspedes <br> TB2: Diseñé pantallas y realicé observaciones clave para optimizar la interfaz, manteniendo siempre una comunicación fluida y proactiva con el equipo.<br><br>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">TB1: A lo largo del proyecto, todos los integrantes del equipo lograron expresar sus ideas de manera oral con claridad y adecuación al contexto. Esto permitió que tanto compañeros como docentes comprendieran nuestras propuestas con facilidad. Gracias a esta capacidad de adaptación en la comunicación, pudimos distribuir tareas de forma eficiente, resolver inquietudes al instante y mantener una dinámica de colaboración efectiva en todo momento.<br>
TB2: A lo largo del desarrollo del TB2, el equipo demostró una comunicación oral efectiva al levantar observaciones y discutir propuestas de mejora para las pantallas del frontend. Cada integrante expresó sus ideas con claridad durante las reuniones, facilitando la toma de decisiones en conjunto y promoviendo la mejora continua del producto. Esta capacidad para dialogar, escuchar activamente y adaptarse al nivel técnico de los interlocutores (docentes, compañeros y usuarios potenciales) fortaleció la cohesión del grupo y permitió avanzar de manera eficiente en los objetivos del proyecto.</td>
</tr>
<tr><td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">Comunica por escrito con efectividad a diferentes rangos de audiencia.</td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">Andres Cruz: <br> TB1: Aporté en diferentes etapas del trabajo, garantizando que la información fuera clara, precisa y organizada, lo que permitió una mejor comprensión y aplicación en el desarrollo del proyecto. <br> <br>Rafael Vivanco: <br> TB1: Contribuí en diversos aspectos del trabajo, garantizando que la información fuera precisa, coherente y comprensible tanto para compañeros como para docentes. <br><br>Fernando Cardenas: <br> TB1: Participé activamente en las tareas asignadas, aplicando mis conocimientos y habilidades para cumplir con los objetivos del equipo de manera efectiva y dentro de los plazos establecidos.<br> <br>Jack Cespedes: <br> TB1:Cumplí con todas las actividades asignadas y considero que tuve un buen desempeño. Sin embargo, reconozco que debo mejorar en la gestión de mi tiempo para optimizar mis resultados en futuros proyectos.<br> <br>Joel Peralta: <br> TB1: Me involucré en la ejecución de las tareas grupales, aportando ideas y soluciones que contribuyeron al desarrollo del proyecto. También procuré mantener una comunicación fluida con mis compañeros para garantizar una coordinación eficiente<br>  Andres Cruz: <br> TB2: En el TB2, aporté al levantamiento de observaciones y al diseño de pantallas, comunicando mis ideas con claridad para mejorar la interfaz y asegurar una experiencia de usuario efectiva. <br> <br>Rafael Vivanco: <br> TB2: Durante las reuniones grupales, me centré en expresar mis ideas y propuestas con claridad, adaptando mi comunicación al contexto para facilitar la comprensión de todos. <br> <br>Fernando Cardenas: <br> TB2: Contribuí al diseño del frontend y levanté observaciones que mejoraron la calidad visual y funcional del proyecto, reforzando la coordinación mediante una comunicación efectiva. <br> <br>Joel Peralta <br> TB2: Participé activamente en la creación de pantallas y en la revisión crítica del diseño, aportando ideas claras que facilitaron mejoras en el producto final.<br><br>Jack Céspedes <br> TB2: Diseñé pantallas y realicé observaciones clave para optimizar la interfaz, manteniendo siempre una comunicación fluida y proactiva con el equipo.<br><br></td>
<td style="border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;text-align:left;vertical-align:top;word-break:normal">TB1: La eficacia del trabajo en equipo también se evidenció en nuestra habilidad para transmitir información de manera escrita. La documentación desarrollada, que abarcó informes, descripciones técnicas y contenido para la landing page, fue precisa, estructurada y accesible. Esto contribuyó a la validación del proyecto y garantizó que el producto final reflejara con claridad su propósito y funcionalidad.<br><br> TB2:Durante el TB2, se evidenció una comunicación escrita clara y efectiva en los documentos entregables, reportes de observaciones y en la elaboración de contenidos para el frontend de la app. Cada miembro del equipo contribuyó en la redacción técnica y descriptiva de las funcionalidades implementadas, así como en la documentación de cambios y mejoras. El nivel de precisión, estructura y coherencia en estos escritos permitió que docentes y usuarios comprendieran fácilmente el progreso del proyecto, lo que aportó a su validación y evolución continua.</td>
</tr>
</tbody></table>
</br></br>


# <font color="red"> **Capítulo I: Introducción** </font>

## **1.1. Startup Profile**

### **1.1.1. Descripción de la Startup**
Autonexo es un software especializado en la gestión integral del mantenimiento vehicular, diseñado para resolver los principales problemas que enfrentan técnicos (mecánicos) o personas al administrar sus flotas. Su objetivo es optimizar la organización, el seguimiento histórico, la gestión de repuestos y el cálculo de presupuesto, todo dentro de un sistema centralizado y fácil de usar.

La plataforma permite registrar vehículos, usuarios y repuestos, así como ejecutar y organizar mantenimientos. Además, ofrece herramientas para el control de inventario, cálculo de presupuesto, acceso al historial de mantenimiento para realizar los cambios necesarios en el vehículo. Según un estudio realizado por Innocar en colaboración con la empresa mexicana Roshfrans, solo el 23.5% de los talleres mecánicos en América Latina utilizan software especializado para gestionar sus operaciones y aspectos administrativos. Este bajo nivel de adopción tecnológica resalta la necesidad de soluciones digitales que optimicen la eficiencia operativa en la gestión de flotas vehiculares.

Autonexo también contempla la integración de tecnologías opcionales como IoT para  un monitoreo en tiempo real, lo que potencia la eficiencia operativa y la estandarización de procesos en el área de mantenimiento vehicular.
<br><br>
A continuación, exponemos un preliminar de, cuadro comparativo de nuestros competidores que será detallado más adelante en el segundo capítulo.
|  **Nombre**    | **Perfil (Overview)** |
|----------------|-----------------------|
| **AutoNexo**   | Autonexo es un software especializado en la gestión del mantenimiento vehicular, diseñado para resolver los principales problemas que enfrentan técnicos (mecánicos) o personas al administrar sus flotas. |
| **Fleetio**    | Fleetio es una de las plataformas más robustas y reconocidas en la gestión de flotas. Su enfoque se centra en brindar a las empresas una solución para controlar todos los aspectos del mantenimiento vehicular. |
| **Drivvo**     | Drivvo es una aplicación orientada tanto a particulares como a pequeñas empresas, enfocada en la administración del mantenimiento, gastos y consumo de vehículos. |
| **Whip Around**| Whip Around es una plataforma para inspecciones y mantenimiento vehicular en flotas comerciales. |

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
Dentro del mercado enfocado en la gestión y mantenimiento de vehículos, existe una amplia gama de plataformas que buscan mejorar la eficiencia, organización y control tanto para usuarios individuales como para empresas. A continuación, se presentan algunos de los principales competidores identificados para Autonexo.

**Fleetio**

Fleetio es una de las plataformas más robustas y reconocidas en la gestión de flotas. Su enfoque se centra en brindar a las empresas una solución integral para controlar todos los aspectos del mantenimiento vehicular, desde el seguimiento de servicios preventivos y correctivos hasta la gestión de combustible, repuestos y órdenes de trabajo. Además, proporciona reportes sobre costos, rendimiento y tiempo de inactividad. Fleetio también destaca por su escalabilidad y capacidad de integración con dispositivos telemáticos.

**Drivvo**

Drivvo es una aplicación orientada tanto a particulares como a pequeñas empresas, enfocada en la administración del mantenimiento, gastos y consumo de vehículos. Su propuesta de valor radica en ofrecer una plataforma sencilla para registrar y monitorear servicios como cambios de aceite, reparaciones, abastecimiento de combustible y más. Drivvo permite establecer recordatorios por tiempo o kilometraje, ayudando a prevenir olvidos en tareas de mantenimiento esenciales. Su interfaz amigable y su enfoque en la eficiencia personal hacen de esta app una opción accesible para los conductores.

**Whip Around**

Whip Around es una solución digital para inspecciones y mantenimiento vehicular en flotas comerciales. Su enfoque está en simplificar el proceso de revisión diaria de vehículos a través de formularios digitales personalizables, lo que ayuda a detectar problemas mecánicos antes de que se conviertan en fallas graves. Además, permite generar órdenes de reparación automáticamente y realizar un seguimiento de cada unidad de la flota. La plataforma también proporciona indicadores clave sobre el estado y rendimiento de los vehículos. Whip Around es especialmente útil para empresas que priorizan la seguridad operativa y el cumplimiento normativo.


### **2.1.1. Análisis competitivo**
| Características | AutoNexo | Fleetio | Drivvo | Whip Around |
|---------------|-----------|---------|---------|-------------|
| **Logo** | ![Descripción de la imagen](img/analisis-logo1.png) | ![Descripción de la imagen](img/analisis-logo2.png) | ![Descripción de la imagen](img/analisis-logo3.png) | ![Descripción de la imagen](img/analisis-logo4.png) |
| **Overview** | Autonexo es un software especializado en la gestión del mantenimiento vehicular, diseñado para resolver los principales problemas que enfrentan técnicos (mecánicos) o personas al administrar sus flotas | Fleetio es una de las plataformas más robustas y reconocidas en la gestión de flotas. Su enfoque se centra en brindar a las una solución para controlar todos los aspectos del mantenimiento vehicular | Drivvo es una aplicación orientada tanto a particulares como a pequeñas empresas, enfocada en la administración del mantenimiento, gastos y consumo de vehículos | Whip Around es una plataforma para inspecciones y mantenimiento vehicular en flotas comerciales |
| **Ventaja Competitiva** | Ofrece una plataforma integral que digitaliza y automatiza el proceso de mantenimiento vehicular, conectando de forma eficiente a conductores/flotas con talleres mecánicos | Optimiza el rendimiento y reduce los costos operativos de la flota mediante una gestión centralizada, automatizada y basada en datos | Facilita el control financiero y el de vehículos personales o comerciales con una app accesible y fácil de usar | Aumenta la seguridad operativa, minimiza riesgos y mejora el cumplimiento legal mediante inspecciones digitales eficientes |
| **Mercado Objetivo** | Dueños de flotas o conductores y mecánicos | Técnicos de mantenimiento y administradores de operaciones | Conductores, dueños de pequeños negocios de transportes | Gerentes de flota, supervisores de operaciones y conductores |
| **Estrategias de Marketing** | Campañas en redes sociales, programas de usuarios recurrentes y eventos | Blog técnico y educativo, guías sobre mantenimiento de flotas, análisis de costos y gestión de activos | Contenido visual y educativo sobre cómo ahorrar dinero en el uso del auto, mantenimiento y consumo | Campañas dirigidas a gerentes de flotas y operaciones |
| **Producto & Servicios** | Registro y gestión de vehículos, registro y control de inventario de repuestos, programación y seguimiento de mantenimientos | Gestión integral de flotas, registro y control con GPS y reportes analíticos avanzados | Registro de gastos, alertas por mantenimiento, control de historial del vehículo | Inspecciones digitales pre y post viaje, generación automática de órdenes de reparación |
| **Precios & Costos** | Servicio de suscripción, costos según plan, accesible | Servicios por suscripción, costos según flota y módulos | Gratuito con funciones básicas, y suscripción "premium" | Planes accesibles, con precios escalables para flotas grandes |
| **Canales de Distribución** | Web y app móvil | Web y app móvil | App móvil | Web y app móvil |
| **Fortalezas** | Solución especializada y completa para el mantenimiento vehicular | Escalable para pequeñas, medianas y grandes empresas | Fuerte presencia en mercados emergentes | Especialización en inspecciones vehiculares con cumplimiento normativo |
| **Oportunidades** | Digitalización creciente del sector automotriz | Posible expansión con IA para predicción de fallas | Expansión con funcionalidades para pequeñas flotas | Integración con más plataformas de gestión de flotas |
| **Debilidades** | Requiere tiempo para educación del usuario en sectores no digitalizados | Costos más elevados en planes avanzados | No ofrece soporte web | Limitación en la gestión completa de flotas |
| **Amenazas** | Fallas en la experiencia de usuario pueden afectar la percepción inicial | Competidores con soluciones más económicas | Usuarios migran a plataformas más completas | Cambios en normativas que reduzcan la necesidad de inspecciones formales |

### **2.1.2. Estrategias y tácticas frente a competidores**
- **Fortaleza utilizada** : Gestión integral y digital del mantenimiento vehicular, incluyendo diagnóstico, historial, repuestos e interacción con talleres.
- **Oportunidad aprovechada**:  Creciente necesidad de transparencia, trazabilidad y control en el mantenimiento de vehículos, especialmente para flotas y talleres que aún trabajan con procesos manuales.
- **Estrategia**: Desarrollar un ecosistema digital que centralice todos los aspectos del mantenimiento, optimizando la comunicación entre conductores y talleres, y facilitando la toma de decisiones mediante datos históricos y notificaciones inteligentes.
- **Táctica**: Implementar APIs RESTful para conectar todos los módulos, desplegar alertas automáticas sobre mantenimientos pendientes o diagnósticos

## **2.2. Entrevistas**
### **2.2.1. Diseño de entrevistas**
En esta sección se plantea una estrategia colaborativa con el equipo para detectar los aspectos comunes a partir de las respuestas proporcionadas por cada entrevistado en cada pregunta. Esto permite realizar un análisis más preciso y confiable, facilitando el desarrollo de nuestra aplicación basándonos en los datos recopilados.

**Segmento 1: Dueños de flotas.**
1. ¿Cómo realiza actualmente el seguimiento del mantenimiento de su flota de vehículos?
2. ¿Con qué frecuencia enfrenta mantenimientos inesperados o fallas imprevistas?
3. ¿Qué información considera imprescindible tener disponible al momento de tomar decisiones sobre reparaciones o servicios?
4. ¿Tiene alguna forma de visualizar el historial de mantenimiento de cada vehículo? ¿Cómo lo gestiona?
5. ¿Ha tenido problemas con talleres o técnicos, como retrasos, falta de transparencia o tareas mal ejecutadas?
6. ¿Qué tan fácil le resulta coordinar el trabajo entre el área técnica y los talleres externos?
7. ¿Suele usar indicadores como MTBF (tiempo medio entre fallas) o el costo por vehículo? ¿Cómo los calcula o supervisa?
8. ¿Le sería útil contar con alertas automáticas para próximos mantenimientos o vencimientos de componentes clave?
9. ¿Qué tan importante considera que sea la estandarización de las tareas de mantenimiento mediante listas o protocolos definidos?
10. Si pudiera implementar una herramienta que le permita controlar su flota desde una app o panel web, ¿qué funcionalidades consideraría indispensables?

**Segmento 2: Mecánicos**
1. ¿Cómo recibe actualmente las solicitudes de reparación o mantenimiento de los clientes?
2. ¿Tiene algún sistema para organizar las reparaciones que tiene pendiente? ¿Cómo lo gestiona?
3. ¿Lleva un control del tiempo que invierte por reparación? ¿Cómo lo hace?
4. ¿Anota o guarda un registro de los repuestos utilizados en cada reparación? ¿Dónde lo hace?
5. ¿Con qué frecuencia se encuentra con la falta de alguna pieza o herramienta al momento de realizar un trabajo?
6. ¿Ha utilizado alguna vez un checklist o guía paso a paso para una reparación? ¿Le resultó útil?
7. ¿Considera útil que un sistema le indique qué pasos debe seguir y qué materiales necesita antes de comenzar una reparación?
8. ¿Cómo guarda evidencia del trabajo que realiza? (Fotos, notas, videos...) ¿Quién se las pide?
9. ¿Tiene acceso al historial de reparaciones de los vehículos que atiende? ¿Le sería útil poder consultarlo?
10. ¿Qué herramienta digital (app o software) usa actualmente para su trabajo, si es que usa alguna? ¿Qué le gusta o no le gusta de ella?

### **2.2.2. Registro de entrevistas**
**Segmento 1: Dueños de flotas**

**Entrevistado 1**

![Descripción de la imagen](img/entrevista1-flota.png)

- **Nombre y Apellido:** Santiago Gómez Iglesias  
- **Edad:** 25  
- **Fecha y lugar:** Lima, Perú  
- **Url:** [Entrevista completa](https://drive.google.com/file/d/13RAjOWoxGp70JdgJCuNyMmnqTYAEUzY/view?usp=sharing)  
- **Duración:** 11:44 minutos
- **Resumen:** El entrevistado habla de como gestiona el mantenimiento y las revisiones técnicas usando su teléfono mobil y un bloc de notas. También nos relata de una mala experiencia con un mecánico que no cumplió con resolver el problema de su vehículo a tiempo. Además, menciona que le gustaría tener una aplicación que le facilite el buscar lugares confiables para obtener repuestos para sus vehículos.

**Entrevistado 2**

![Descripción de la imagen](img/entrevista2-flota.png)

- **Nombre y Apellido:** Jean Chipa  
- **Edad:** 25  
- **Fecha y lugar:** Lima, Perú  
- **Url:** [Entrevista completa](https://drive.google.com/file/d/1W4ka95-DvcHUAsc0Jk4nzsRC8l_r72Qx/view?usp=sharing)  
- **Duración:** 6:28 minutos
- **Resumen:** De acuerdo con la entrevista, el usuario gestiona el mantenimiento y las revisiones técnicas a través de una hoja de Excel y un cuaderno de apuntes. Sin embargo, menciona que, en ocasiones, este método se vuelve engorroso cuando hay variaciones, ya que, a medida que realiza más registros, la información pierde claridad. Además, existe la posibilidad de extraviar el cuaderno de apuntes o olvidar registrar ciertos datos. Le resulta alentador saber que puede implementar un sistema que optimice estos procesos de manera rápida y segura. 

**Entrevistado 3**

![Descripción de la imagen](img/entrevista3-flota.png)

- **Nombre y Apellido:** Bruno Ontón  
- **Edad:** 24  
- **Fecha y lugar:** Lima, Perú  
- **Url:** [Entrevista completa](https://drive.google.com/file/d/14hpxkvlqUsKjHRF6oJVH3KVf7upqzTEZ/view?usp=drive_link )  
- **Duración:** 4:27 minutos
- **Resumen:** El entrevistado comenta que realiza el seguimiento de sus vehículos de forma manual, utilizando hojas de cálculo y recordatorios en el calendario. No cuenta con un sistema automatizado para registrar reparaciones, calcular indicadores como el MTBF o los costos por vehículo. Aunque lleva un control básico, reconoce que este método no es eficiente y que suele enfrentar pequeños imprevistos. Destaca que disponer de una herramienta que emita alertas automáticas, centralice el historial de cada unidad y genere reportes de mantenimiento sería de gran utilidad. 
 

**Segmento 2: Mecánicos**

**Entrevistado 1**

![Descripción de la imagen](img/entrevista1-meca.png)

- **Nombre y Apellido:** Alvaro Espinoza  
- **Edad:** 25  
- **Fecha y lugar:** Lima, Perú  
- **Url:** [Entrevista completa](https://drive.google.com/file/d/1AiEnalDJ3kyt6R3ahbYz2tfpWNI8hX7G/view?usp=drive_linkk )  
- **Duración:** 11:10 minutos
- **Resumen:** El entrevistado menciona que toda la gestión de su mecánica la realiza de manera manual en un bloc de notas. No utiliza ningún software para administrar la cantidad de reparaciones, el stock de productos o los registros de clientes. Sin embargo, reconoce que contar con un sistema que le ayude en estos aspectos sería de gran utilidad, ya que le permitiría optimizar su trabajo de manera más eficiente

**Entrevistado 2**

![Descripción de la imagen](img/entrevista2-meca.png)

- **Nombre y Apellido:** Vicente Vicencio  
- **Edad:** 24  
- **Fecha y lugar:** Lima, Perú  
- **Url:** [Entrevista completa](https://drive.google.com/file/d/1jJUJM2CxZaIUD-mVPSILqKvR_Qjnm9dG/view?usp=sharing)  
- **Duración:** 4:07 minutos
- **Resumen:** Vicente Vicencio, técnico independiente, gestiona sus reparaciones de manera informal, recibiendo solicitudes por llamadas o WhatsApp y organizando su trabajo en una libreta. No lleva un control preciso del tiempo invertido ni de los repuestos utilizados, lo que a veces le causa inconvenientes. También enfrenta problemas por la falta de piezas y herramientas durante las reparaciones. Aunque usa el bloc de notas del celular y Excel de forma básica, considera que un sistema digital optimizado le ayudaría a organizarse mejor, evitar olvidos y acceder a un historial de reparaciones para mejorar su eficiencia.

**Entrevistado 3**

![Descripción de la imagen](img/entrevista3-meca.png)

- **Nombre y Apellido:** Jair Gutierrez  
- **Edad:** 26  
- **Fecha y lugar:** Lima, Perú  
- **Url:** [Entrevista completa](https://drive.google.com/file/d/1s3h2tNtl4xgaC68Lv3HhIh98MvHGtYEA/view?usp=sharing)  
- **Duración:** 3:02 minutos
- **Resumen:** Jair Gutierrez, mecánico de taller, organiza su trabajo en una libreta y recibe solicitudes por el jefe de taller, llamadas o redes sociales. No lleva un registro preciso del tiempo ni de los repuestos, lo que a veces le genera problemas. Frecuentemente enfrenta la falta de piezas o herramientas, lo que retrasa su trabajo. Considera que un sistema digital le ayudaría a mejorar su organización, evitar olvidos y acceder a historiales de reparaciones para mayor eficiencia


### **2.2.3. Análisis de entrevistas**
Se plantea una estrategia colaborativa con el equipo para identificar los aspectos comunes según las respuestas de cada entrevistado. Esto permite realizar un análisis más preciso y confiable, facilitando el desarrollo de la aplicación a partir de la información recopilada.

**Segmento 1 dueños de flotas, puntos en común:**
1. ¿Cómo gestionan actualmente el mantenimiento de sus vehículos?

- Ambos entrevistados utilizan métodos manuales como hojas de Excel, cuadernos o calendarios. Si bien esto les permite llevar un control básico, reconocen que con el tiempo se vuelve desordenado o poco claro.
2. ¿Qué problemas enfrentan con su método actual?

- Tienen dificultades cuando hay variaciones en los registros, olvidos en las anotaciones o pérdida de información. Además, no cuentan con reportes o indicadores técnicos que ayuden en la toma de decisiones.

3. ¿Utilizan indicadores de mantenimiento como MTBF o costos por vehículo?

- No, actualmente no hacen uso de indicadores avanzados. El control que llevan es básico y no permite calcular estos valores importantes para evaluar el rendimiento o eficiencia de cada unidad.

4.  ¿Estarían interesados en usar un sistema automatizado?

- Sí. Ambos ven con buenos ojos la implementación de una herramienta digital que emita alertas, centralice datos y mejore la organización y eficiencia del mantenimiento.

**Segmento 2 mecánicos, puntos en comun:**
1. ¿Cómo gestionan las reparaciones y el trabajo diario?

- Los tres entrevistados organizan su trabajo manualmente, ya sea con una libreta, bloc de notas, o Excel de forma muy básica. Reciben pedidos por WhatsApp, llamadas o redes sociales.

2. ¿Llevan un control preciso del tiempo y de los repuestos utilizados?

- No. Ninguno lleva un registro detallado del tiempo invertido en cada trabajo ni del uso de repuestos, lo cual les genera problemas de organización y control.

3. ¿Qué tipo de inconvenientes enfrentan por la falta de herramientas o piezas?

- La falta de piezas o herramientas durante una reparación es un problema frecuente que retrasa su trabajo y afecta la eficiencia del servicio que ofrecen.

4.  ¿Consideran útil implementar un sistema digital para organizar su trabajo?

- Sí. Todos coinciden en que un sistema digital podría ayudarles a mejorar su organización, evitar olvidos y acceder rápidamente a información histórica sobre sus trabajos.

**Análisis general por segmento**
- **Segmento 1: Dueños de flotas:** Este segmento presenta una necesidad clara de transformación digital. Aunque han intentado organizarse mediante herramientas básicas como Excel, enfrentan dificultades a medida que la flota crece. La falta de automatización, reportes técnicos y control de mantenimiento los expone a errores y pérdidas de información. Están dispuestos a adoptar una solución digital si les brinda facilidad, seguridad y eficiencia.

![User Personas2](img/estdFlota.png)

- **Segmento 2: Mecánicos** Los mecánicos operan con una gestión altamente informal. La mayoría no utiliza herramientas digitales más allá de aplicaciones básicas. Enfrentan problemas de logística, control y planificación debido a la falta de registros precisos. Ven con buenos ojos un sistema que les facilite el día a día, especialmente en el seguimiento de repuestos, tiempos y clientes.

![User Personas2](img/estdMeca.png)

## **2.3. Needfinding**

### **2.3.1. User Personas**
  **Segmento 1: Dueños de flotas:**

![User Personas1](img/user-personas-flota.png)

**Segmento 2: Mecánicos**

![User Personas2](img/user-personas-meca.png)

### **2.3.2. User Task Matrix**
| Task Matrix | Conductor | Conductor | Mecánico | Mecánico |
|------------|-----------|------------|----------|------------|
|  | **Frecuencia** | **Importancia** | **Frecuencia** | **Importancia** |
| Verificar el estado general del vehículo | High | medium | rarely | often |
| Recibir alertas de fallos | medium | High | High | High |
| Registrar fallas o anomalías manualmente | rarely | medium | High | High |
| Ver historial de mantenimiento | often | medium | High | High |
| Solicitar revisión o mantenimiento | often | High | rarely | medium |
| Confirmar ruta y destino desde la app | medium | medium | rarely | rarely |
| Ver notificaciones de revisión próxima | medium | medium | High | High |
| Cargar datos de viaje (distancia, tiempo, etc.) | medium | medium | rarely | rarely |
| Evaluar nivel de combustible | High | High | rarely | medium |
| Revisar detalles de última reparación | rarely | rarely | High | High |
| Diagnóstico de motor en app | rarely | often | High | High |
| Acceder a manual de operación desde el sistema | rarely | rarely | often | often |
| Notificar incidente o avería | medium | High | often | often |
| Descargar reportes de uso o fallos | medium | medium | High | High |

En el caso del conductor, las tareas con mayor frecuencia e importancia incluyen la verificación del estado del vehículo, la recepción de alertas de fallos, y el monitoreo de nivel de combustible. Estas actividades están directamente ligadas con su seguridad y desempeño diario, por lo que requieren una interfaz sencilla, clara y con actualizaciones en tiempo real. Además, tareas como solicitar revisiones o recibir notificaciones de mantenimiento también son frecuentes, aunque pueden variar según el uso del vehículo.
Por otro lado, el mecánico se enfoca en tareas más técnicas y profundas, como el diagnóstico del motor, la revisión del historial de mantenimiento, y la inspección de sensores en tiempo real, las cuales son altamente importantes para la detección precisa de fallas. Aunque estas tareas no se realizan tan frecuentemente como las del conductor, su impacto es crítico, lo que hace indispensable un sistema que facilite el acceso rápido a datos históricos, reportes y alertas.
Una tarea compartida como la recepción de alertas de fallos es esencial para ambos perfiles: el conductor actúa como primer receptor y el mecánico como solucionador. Esto muestra cómo el sistema conecta ambos roles en una misma línea operativa.
En resumen, el sistema debe automatizar la recopilación y análisis de datos en tiempo real para liberar al conductor de tareas manuales repetitivas, mientras proporciona al mecánico herramientas de diagnóstico avanzadas y acceso a información detallada. De esta forma, se garantiza tanto una experiencia de usuario eficiente como una gestión técnica optimizada, cumpliendo el objetivo de mantener los vehículos seguros y operativos.



### **2.3.3. User Journey Mapping**
 **Segmento 1: Dueños de flotas:**

![Journey Mapping1](img/journey-mapping-flota.png)

**Segmento 2: Mecánicos**

![Journey Mapping2](img/journey-mapping-meca.png)

### **2.3.4. Empathy Mapping**
En esta sección, se elaboró un Empathy Map para analizar a nuestros usuarios, comprendiendo completamente el entorno en el que se desenvuelven. Este proceso nos permitirá profundizar en sus necesidades y orientarnos hacia la oferta de servicios que realmente les sean útiles.

**Segmento 1: Dueños de flotas:**

![Journey Mapping1](img/mapa-empatia-flota.png)

El mapa de empatía revela una fuerte necesidad de seguridad y claridad. Se enfrenta a la incertidumbre cuando su auto presenta fallas, teme ser engañado y siente frustración por la falta de información confiable. Busca soluciones rápidas y confía más en recomendaciones informales que en el servicio técnico. Su mayor ganancia sería contar con un proceso transparente y confiable que reduzca su ansiedad.

**Segmento 2: Mecánicos**

![Journey Mapping2](img/mapa-empatia-meca.png)

Podemos analizar que, el problema radica en la falta de herramientas para generar confianza. Aunque tiene experiencia, siente que el cliente no lo comprende ni confía en su diagnóstico. Le gustaría comunicar mejor lo que hace y por qué lo hace, pero muchas veces carece de medios claros para hacerlo. Su motivación principal es ser eficiente y brindar un buen servicio, pero necesita apoyo para transmitir esa calidad al cliente.

### **2.3.5. As-is Scenario Mapping**
En esta sección, exploramos las acciones, pensamientos y emociones que los usuarios experimentan al realizar una tarea. A través de este análisis, buscamos identificar oportunidades de mejora y optimizar su experiencia

  **Segmento 1: Dueños de flotas:**

![User Personas1](img/asis-flota.png)

El escenario actual para el conductor está marcado por el estrés desde el primer síntoma del auto hasta la entrega del vehículo. Sus pensamientos giran en torno al miedo al engaño y a cuánto costará la reparación. Aunque al final suele recibir su auto funcional, la experiencia emocional es negativa, mostrando una gran oportunidad para mejorar la percepción y la confianza durante todo el proceso.

**Segmento 2: Mecánicos**

![User Personas2](img/asis-mecanicos.png)

Para este escenario el flujo actual es rápido y enfocado en la resolución técnica, pero deja de lado la experiencia del usuario. Siente que trabaja bien, pero nota que el cliente no siempre lo valora por la falta de explicaciones o visibilidad del proceso. Esto genera un quiebre en la relación cliente-taller que puede solucionarse con herramientas que acompañen su trabajo con comunicación clara y visual.

## **2.4. Ubiquitous Language**
| Término en Inglés / Español | Definición |
|---------------------------|------------|
| Driver (Conductor) | Persona responsable del uso diario de un vehículo y de solicitar mantenimientos cuando sean necesarios. |
| Mechanic (Mecánico) | Profesional encargado de realizar diagnósticos, reparaciones y mantenimientos a los vehículos. |
| Car (Vehículo) | Medio de transporte registrado en el sistema, con características específicas como marca, modelo, año y kilometraje. |
| Maintenance Record (Registro de mantenimiento) | Documento que describe un mantenimiento específico realizado o planificado, incluyendo el tipo de servicio, fecha, costos y piezas utilizadas. |
| Maintenance Request (Solicitud de mantenimiento) | Propuesta enviada desde el mecánico al conductor con los detalles y costos estimados de un mantenimiento sugerido. |
| Inventory (Inventario) | Conjunto de piezas, repuestos o insumos disponibles por parte del mecánico para ser utilizados durante mantenimientos. |
| Item (Ítem) | Elemento individual dentro del inventario, como una pieza específica o un producto consumible (ej: filtro de aceite, pastilla de freno). |
| Maintenance Service (Servicio de mantenimiento) | Conjunto de operaciones y actividades necesarias para llevar a cabo un mantenimiento, que pueden incluir diagnósticos, reemplazo de piezas, y ajustes. |
| Maintenance Log (Historial de mantenimiento) | Lista histórica de todos los mantenimientos aceptados y ejecutados sobre un vehículo determinado. |
| Stock (Existencias) | Cantidad disponible de un ítem en inventario. |
| Assigned Vehicle (Vehículo asignado) | Vehículo que ha sido aceptado por un mecánico para realizar mantenimientos. |

# <font color="red"> **Capítulo III: Requirements Specification** </font>

## **3.1. To-Be Scenario Mapping**

En esta sección, exploramos las acciones, pensamientos y emociones que los usuarios experimentan al realizar sus tareas utilizando nuestra app. A través de este análisis, buscamos identificar los puntos de mejora y optimización.

**Segmento 1: Dueños de flotas o conductores**

<img src="img/Segmento1-ScenarioMapping.png" alt="Segmento 1 Scenario Mapping" width="800"/>

En esta sección, exploramos las acciones, pensamientos y emociones que los usuarios experimentan al realizar sus tareas utilizando nuestra app. A través de este análisis, buscamos identificar los puntos de mejora y optimización.

**Segmento 2: Mecánicos**

<img src="img/Segmento2-ScenarioMapping.png" alt="Segmento 2 Scenario Mapping" width="800"/>

En el escenario ideal, el conductor experimenta un proceso mucho más fluido y menos estresante. Desde el primer síntoma, puede acceder a una app conectada al vehículo que le ofrece un prediagnóstico basado en datos reales del auto, reduciendo la incertidumbre inicial.

## **3.2. User Stories**

#### **Epics**

**EP01 - Registro y Gestión de Usuario, Vehículo y Repuestos**

**Descripción:**
Como usuario, quiero registrar y gestionar mi perfil, vehículos y repuestos, para tener un control completo de mis activos dentro de AutoNexo.

| User Story ID | Título | Prioridad |
| :---- | :---- | :---- |
| US01 | Registro de usuario | Must |
| US02 | Inicio de sesión seguro | Must |
| US03 | Registro de vehículos | Must |
| US04 | Registro de repuestos | Must |
| US05 | Gestión del perfil del usuario | Should |
| US06 | Edición del perfil desde la app | Should |

**EP02 - Calendario de Mantenimientos Programados**

**Descripción:**
Como usuario, quiero contar con un calendario de mantenimientos para programar servicios futuros y recibir recordatorios automáticos, a fin de evitar fallas o demoras.

| User Story ID | Título | Prioridad |
| :---- | :---- | :---- |
| US07 | Visualización del calendario de mantenimientos | Must |
| US08 | Programación de nuevos mantenimientos | Must |
| US09 | Edición o cancelación de mantenimientos agendados | Should |
| US10 | Recordatorios automáticos para mantenimientos programados | Should |

**EP03 - Gestión de Inventario de Repuestos**

**Descripción:**
Como usuario, quiero gestionar el inventario de repuestos, para asegurarme de contar con los insumos necesarios al momento de realizar mantenimientos.

| User Story ID | Título | Prioridad |
| :---- | :---- | :---- |
| US11 | Consulta de repuestos disponibles | Must |
| US12 | Registro de nuevos ingresos de repuestos | Must |
| US13 | Notificación de repuestos bajos en stock | Should |
| US14 | Actualización del inventario tras mantenimiento | Must |

**EP04 - Cálculo de Presupuesto y Control de Costos**

**Descripción:**
Como usuario, quiero calcular el presupuesto de reparaciones y mantenimiento, para poder anticipar costos y optimizar mis recursos.

| User Story ID | Título | Prioridad |
| :---- | :---- | :---- |
| US15 | Generación de presupuesto de mantenimiento | Should |
| US16 | Edición de costos y repuestos por servicio | Could |
| US17 | Visualización de gastos históricos por vehículo | Could |

**EP05 - Historial de Mantenimientos**

**Descripción:**
Como usuario, quiero ver el historial detallado de mantenimientos por vehículo, para llevar un control técnico del estado de cada uno de ellos.

| User Story ID | Título | Prioridad |
| :---- | :---- | :---- |
| US18 | Consulta del historial por vehículo | Must |
| US19 | Detalle de cada servicio registrado | Should |
| US20 | Exportación o descarga del historial en PDF | Could |

**EP06 - Mensajería entre Usuario y Mecánico**

**Descripción:**
Como usuario, quiero poder comunicarme dentro de la plataforma, para coordinar mantenimientos, resolver dudas y compartir información importante.

| User Story ID | Título | Prioridad |
| :---- | :---- | :---- |
| US21 | Envío de mensajes entre usuario y mecánico | Should |
| US22 | Notificaciones de nuevos mensajes | Could |
| US23 | Historial de conversación por vehículo o servicio | Could |

**EP07 - Gestión de Suscripción y Pagos**

**Descripción:**
Como usuario, quiero gestionar mi suscripción y métodos de pago para asegurar el acceso continuo al servicio según mi plan seleccionado.

| User Story ID | Título | Prioridad |
| :---- | :---- | :---- |
| US24 | Selección del plan de suscripción | Should |
| US25 | Registro de método de pago seguro | Must |
| US26 | Renovación automática de suscripción | Could |
| US27 | Cambio de plan de suscripción | Could |
| US28 | Cancelación o pausa del servicio | Should |

**EP08 - Interacción y Navegación en la Landing Page**

**Descripción:**
Como visitante de la Landing Page, quiero que la navegación sea intuitiva y las acciones claras para poder interactuar fácilmente con la plataforma y descubrir sus funcionalidades.

| User Story ID | Título | Prioridad |
| :---- | :---- | :---- |
| US29 | Navegación Intuitiva | Should |
| US30 | Compatibilidad con lectores de pantalla | Could |
| US31 | Feedback visual en interacciones | Should |

**EP09 - Integración y Exposición de Servicios vía API RESTful**

**Descripción:**
Como developer, quiero construir y exponer los servicios clave del sistema Autonexo mediante una API RESTful, para permitir la interacción entre el frontend y el backend de manera segura, eficiente y escalable.

| Technical Story ID | Título | Prioridad |
| :---- | :---- | :---- |
| TS01 | Registro de usuario a través de un RESTful API | Must |
| TS02 | Registro de repuestos en inventario a través de un RESTful API | Must |
| TS03 | Registro de vehículos a través de un RESTful API | Must |
| TS04 | Creación de diagnósticos a través de un RESTful API | Should |
| TS05 | Creación de mantenimientos programados mediante RESTful API | Must |
| TS06 | Consulta de historial de servicios por vehículo mediante RESTful API | Must |
| TS07 | Actualización del inventario de repuestos mediante RESTful API | Should |

#### **User Stories**

| ID Epic | Epic | ID User Story / ID Technical Story | User Story / Technical Story | Descripción US / TS | Criterios de Aceptación |
|----------|--------------------------------|-------------------------|-----------------------------------------------|--------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| EP01 | Registro y Gestión de Usuario, Vehículo y Repuestos | US01 | Registro de usuario | Como nuevo usuario, quiero registrarme en la plataforma para empezar a utilizar los servicios de AutoNexo. | **Escenario 1:** Registro (conductor): Dado que soy un usuario conductor nuevo, cuando ingreso mis datos requeridos y los envío, entonces se debe crear mi cuenta y mostrarme un mensaje de bienvenida <br> **Escenario 2:** Validación de campos obligatorios: Dado que estoy completando el formulario, cuando omito un campo obligatorio, entonces el sistema debe mostrar un mensaje de error <br> **Escenario 3:** Registro (mecánico): Dado que soy un usuario mecanico nuevo, cuando ingreso mis datos requeridos y los envío, entonces se debe crear mi cuenta y mostrarme un mensaje de bienvenida |
| EP01 | Registro y Gestión de Usuario, Vehículo y Repuestos | US02 | Inicio de sesión seguro | Como usuario registrado, quiero iniciar sesión de forma segura para acceder a todas las funcionalidades de la plataforma. | **Escenario 1:** Inicio de sesión exitoso: Dado que tengo una cuenta activa, cuando ingreso mi correo y contraseña correctamente, entonces debo ser redirigido al panel principal <br> **Escenario 2:** Contraseña incorrecta: Dado que ingreso credenciales, cuando la contraseña no coincide, entonces el sistema debe mostrar un mensaje de error <br> **Escenario 3:** Registro (mecánico): Dado que olvidé mi contraseña, cuando solicito restablecerla, entonces el sistema debe enviarme un enlace de recuperación al correo |
| EP01 | Registro y Gestión de Usuario, Vehículo y Repuestos | US03 | Registro de vehículos | Como usuario, quiero registrar mis vehículos en la plataforma para gestionar su mantenimiento y seguimiento. | **Escenario 1:** Registro exitoso de vehículo: Dado que ingreso los datos del vehículo, Cuando completo todos los campos obligatorios, Entonces el sistema debe guardar la información y mostrar el vehículo en la lista <br> **Escenario 2:** Validación de campos obligatorios: Dado que dejo campos vacíos, Cuando intento guardar el vehículo, Entonces el sistema debe indicar los campos que faltan <br> **Escenario 3:** Visualización del nuevo vehículo: Dado que el vehículo ha sido registrado, Cuando accedo a la lista de vehículos, Entonces debe aparecer correctamente en la interfaz |
| EP01 | Registro y Gestión de Usuario, Vehículo y Repuestos | US04 | Registro de repuestos | Como usuario, quiero registrar repuestos en el sistema para tener un control del inventario. | **Escenario 1:** Registro exitoso de repuesto: Dado que ingreso los datos del repuesto, Cuando completo y envío el formulario, Entonces el sistema debe agregar el repuesto al inventario <br> **Escenario 2:** Campos incompletos: Dado que el formulario no está completo, Cuando intento enviarlo, Entonces el sistema debe advertirme sobre los campos vacíos <br> **Escenario 3:** Duplicado de repuesto: Dado que intento registrar un repuesto existente, Cuando el sistema detecta duplicidad, Entonces debe mostrar un mensaje de advertencia |
| EP01 | Registro y Gestión de Usuario, Vehículo y Repuestos | US06 | Edición del perfil desde la app | Como usuario, quiero editar mi perfil directamente desde la aplicación para mayor comodidad. | **Escenario 1:** Edición desde app: Dado que estoy en la aplicación móvil, Cuando accedo a mi perfil y modifico datos, Entonces el sistema debe reflejar los cambios correctamente <br> **Escenario 2:** Guardado exitoso desde app: Dado que termino de editar los datos, Cuando confirmo los cambios, Entonces se deben guardar sin errores <br> **Escenario 3:** Error al guardar cambios: Error al guardar cambios en la app: Dado que hay un fallo al cambiar los datos, Cuando intento guardar, Entonces se debe mostrar un mensaje de error |
| EP02 | Calendario de Mantenimientos Programados | US07 | Visualización del calendario de mantenimientos | Como usuario, quiero visualizar un calendario con los mantenimientos programados para tener una vista clara de las fechas importantes. | **Escenario 1:** Acceso al calendario: Dado que tengo mantenimientos agendados, Cuando accedo al módulo de calendario, Entonces el sistema debe mostrar las fechas de mantenimiento programadas <br> **Escenario 2:** Detalles del mantenimiento: Dado que selecciono una fecha en el calendario, Cuando hago clic en ella, Entonces el sistema debe mostrar detalles del mantenimiento programado <br> **Escenario 3:** Calendario sin mantenimientos: Dado que no tengo mantenimientos agendados, Cuando accedo al calendario, Entonces debe mostrarse vacío con un mensaje informativo |
| EP02 | Calendario de Mantenimientos Programados | US08 | Programación de nuevos mantenimientos | Como usuario, quiero poder programar nuevos mantenimientos para organizar el cuidado de mi vehículo. | **Escenario 1:** Programación exitosa: Dado que ingreso los datos requeridos, Cuando confirmo la programación, Entonces el sistema debe registrar el mantenimiento en el calendario <br> **Escenario 2:** Validación de fecha y hora, Dado que selecciono una fecha pasada o inválida, Cuando intento agendar el mantenimiento, Entonces el sistema debe mostrar un mensaje de error <br> **Escenario 3:** Confirmación visual: Dado que he programado correctamente un mantenimiento, Cuando regreso al calendario, Entonces el mantenimiento debe aparecer en la fecha seleccionada |
| EP02 | Calendario de Mantenimientos Programados | US09 | Edición o cancelación de mantenimientos agendados | Como usuario, quiero editar o cancelar los mantenimientos programados para mantener mi calendario actualizado según mis necesidades. | **Escenario 1:** Edición exitosa de mantenimiento: Dado que tengo un mantenimiento agendado, Cuando modifico la fecha u hora y guardo los cambios, Entonces el sistema debe actualizar el calendario con la nueva información <br> **Escenario 2:** VCancelación de mantenimiento: Dado que ya no necesito un mantenimiento programado, Cuando selecciono la opción de cancelarlo, Entonces el sistema debe eliminarlo del calendario y mostrar una confirmación <br> **Escenario 3:** Validación de cambios inválidos: Dado que intento cambiar la fecha a una inválida, Cuando intento guardar, Entonces el sistema debe mostrar un mensaje de error indicando el problema |
| EP02 | Calendario de Mantenimientos Programados | US10 | Recordatorios automáticos para mantenimientos programados | Como usuario, quiero recibir recordatorios automáticos para los mantenimientos agendados, para no olvidar ninguna cita importante. | **Escenario 1:** Recepción de recordatorio previo: Dado que tengo un mantenimiento programado, Cuando se acerque la fecha, Entonces el sistema debe enviarme un recordatorio <br> **Escenario 2:** Configuración de recordatorios: Dado que quiero ajustar la anticipación de los avisos, Cuando modifico esta preferencia en la configuración, Entonces el sistema debe aplicar los nuevos intervalos <br> **Escenario 3:** Canales de notificación: Dado que tengo un recordatorio activo, Cuando llega la fecha definida, Entonces el sistema debe enviarlo por la app |
| EP03 | Gestión de Inventario de Repuestos | US11 | Consulta de repuestos disponibles | Como usuario, quiero consultar los repuestos disponibles en el inventario para saber si están en stock antes de agendar un mantenimiento. | **Escenario 1:** Visualización general del inventario: Dado que accedo a la sección de inventario, Cuando ingreso a la plataforma, Entonces el sistema debe mostrar la lista de repuestos con sus cantidades actuales <br> **Escenario 2:** Filtro de repuestos: Dado que necesito un tipo específico de repuesto, Cuando uso los filtros por categoría, nombre o código, Entonces el sistema debe mostrar solo los repuestos que cumplan con los criterios <br> **Escenario 3:** Indicador de stock bajo o agotado: Dado que un repuesto tiene bajo stock, Cuando consulto su disponibilidad, Entonces el sistema debe mostrar una alerta visual con el estado del repuesto |
| EP03 | Gestión de Inventario de Repuestos | US12 | Registro de nuevos ingresos de repuestos | Como administrador, quiero registrar nuevos ingresos de repuestos al sistema para mantener actualizado el inventario. | **Escenario 1:** Registro exitoso de ingreso: Dado que estoy ingresando repuestos al sistema, Cuando completo los datos requeridos y los guardo, Entonces el inventario debe reflejar el nuevo stock actualizado <br> **Escenario 2:** Validación de campos al registrar: Dado que omito información esencial, Cuando intento registrar el ingreso, Entonces el sistema debe mostrar un mensaje indicando los campos faltantes <br> **Escenario 3:** Confirmación del registro: Dado que he ingresado correctamente los datos, Cuando finalizo el registro, Entonces el sistema debe mostrarme una notificación confirmando la operación |
| EP03 | Gestión de Inventario de Repuestos | US13 | Notificación de repuestos bajos en stock | Como usuario, quiero recibir notificaciones cuando los repuestos estén por agotarse, para reabastecer el inventario a tiempo. | **Escenario 1:** Generación automática de alerta: Dado que el stock de un repuesto baja del umbral establecido, Cuando se actualiza el inventario, Entonces el sistema debe generar automáticamente una alerta de stock bajo <br> **Escenario 2:** Visualización en el panel principal: Dado que hay repuestos con bajo stock, Cuando ingreso al panel de control, Entonces el sistema debe mostrar un listado de estos repuestos resaltados <br> **Escenario 3:** Notificación por sistema: Dado que un repuesto se encuentra en nivel crítico, Cuando se registra la disminución de unidades, Entonces el sistema debe enviarme una notificación dentro de la plataforma |
| EP03 | Gestión de Inventario de Repuestos | US14 | Actualización del inventario tras mantenimiento | Como usuario, quiero que el sistema actualice automáticamente el inventario cuando se utilicen repuestos en un mantenimiento, para mantener los datos precisos. | **Escenario 1:** Descuento automático de repuestos utilizados: Dado que se ha completado un mantenimiento, Cuando se registra el uso de ciertos repuestos, Entonces el sistema debe descontar automáticamente la cantidad utilizada del inventario <br> **Escenario 2:** Validación de stock suficiente: Dado que intento registrar un mantenimiento, Cuando el stock de un repuesto es insuficiente, Entonces el sistema debe impedir el registro y mostrar una advertencia |
| EP04 | Cálculo de Presupuesto y Control de Costos | US15 | Generación de presupuesto de mantenimiento | Como usuario, quiero que el sistema genere un presupuesto estimado para el mantenimiento del vehículo, para saber cuánto me costará antes de aprobarlo. | **Escenario 1:** Cálculo automático según repuestos y mano de obra: Dado que selecciono los repuestos y servicios necesarios, Cuando confirmo los detalles del mantenimiento, Entonces el sistema debe calcular el costo total y mostrarme un presupuesto estimado <br> **Escenario 2:** Visualización detallada del presupuesto: Dado que he generado un presupuesto, Cuando reviso la propuesta, Entonces debo ver el desglose de costos por cada ítem |
| EP04 | Cálculo de Presupuesto y Control de Costos | US16 | Edición de costos y repuestos por servicio | Como mecánico, quiero poder modificar los costos y repuestos asignados a un servicio, para reflejar cambios reales antes de facturar. | **Escenario 1:** Modificación de valores antes de confirmar servicio: Dado que he ingresado un mantenimiento, Cuando necesito ajustar los costos o repuestos, Entonces debo poder editar los campos correspondientes antes de la confirmación <br> **Escenario 2:** Validación de datos actualizados: Dado que modifico un presupuesto, Cuando confirmo los cambios, Entonces el sistema debe validar los datos y recalcular el total correctamente |
| EP04 | Cálculo de Presupuesto y Control de Costos | US17 | Visualización de gastos históricos por vehículo |  Como usuario, quiero visualizar los gastos acumulados en mantenimientos por cada vehículo, para tener un control de mi inversión en reparaciones. | **Escenario 1:** Consulta de gastos totales por vehículo: Dado que selecciono un vehículo, Cuando ingreso a su historial, Entonces el sistema debe mostrarme el total acumulado de gastos en mantenimientos <br> **Escenario 2:** Filtros por periodo de tiempo: Dado que deseo ver los gastos, Cuando aplico filtros de fechas, Entonces el sistema debe mostrar los datos correspondientes al rango elegido <br> **Escenario 3:** Visualización en formato gráfico y tabla: Dado que consulto los gastos, Cuando ingreso a la sección de historial, Entonces debo ver los datos en gráficos de barras o líneas y en una tabla detallada |
| EP05 | Historial de Mantenimientos | US18 | Consulta del historial por vehículo |  Como usuario, quiero consultar el historial completo de mantenimientos por cada vehículo, para tener claridad sobre los servicios realizados. | **Escenario 1:** Listado cronológico de mantenimientos: Dado que accedo al historial de un vehículo, Cuando se despliega la información, Entonces debo ver un listado ordenado por fecha de los mantenimientos realizados <br> **Escenario 2:** Visualización de detalles por mantenimiento: Dado que veo el historial, Cuando selecciono un mantenimiento, Entonces debo poder ver sus detalles, como tipo de servicio, repuestos usados y costos <br> **Escenario 3:** Filtros por tipo de servicio: Dado que tengo muchos registros, Cuando aplico un filtro por tipo de servicio, Entonces el sistema debe mostrar solo los resultados que coincidan |
| EP05 | Historial de Mantenimientos | US19 | Detalle de cada servicio registrado |  Como usuario, quiero acceder al detalle de cada servicio registrado para revisar qué repuestos se usaron, el costo y las observaciones del mecánico. | **Escenario 1:** Acceso al detalle desde el historial: Dado que visualizo el historial de mantenimientos, Cuando selecciono un servicio, Entonces se debe mostrar toda la información relacionada a ese mantenimiento <br> **Escenario 2:** Visualización de repuestos utilizados: Dado que estoy en el detalle de un servicio, Cuando accedo a la sección de repuestos, Entonces debo ver los nombres, cantidades y códigos de cada uno <br> **Escenario 3:** Inclusión de observaciones técnicas: Dado que reviso un servicio, Cuando se carga la información, Entonces debo poder leer las observaciones del mecánico o técnico encargado |
| EP05 | Historial de Mantenimientos | US20 | Exportación o descarga del historial en PDF |  Como usuario, quiero poder exportar o descargar en PDF el historial de mantenimientos de un vehículo para conservarlo o compartirlo fácilmente. | **Escenario 1:** Opción de exportar historial completo: Dado que visualizo el historial de un vehículo, Cuando selecciono la opción de exportar, Entonces el sistema debe generar un archivo PDF con toda la información <br> **Escenario 2:** Descarga exitosa del documento: Dado que genero el PDF, Cuando la descarga inicia, Entonces el archivo debe guardarse correctamente en mi dispositivo <br> **Escenario 3:** Inclusión de datos detallados en el PDF: Dado que visualizo el PDF generado, Cuando lo abro, Entonces debe contener fechas, servicios realizados, repuestos utilizados y montos |
| EP06 | Mensajería entre Usuario y Mecánico | US21 | Envío de mensajes entre usuario y mecánico |  Como usuario, quiero poder comunicarme con el mecánico a través de la plataforma para resolver dudas o recibir actualizaciones sobre mis mantenimientos. | **Escenario 1:** Envío de mensaje desde la interfaz del servicio: Dado que tengo un mantenimiento en curso, Cuando ingreso a su detalle y escribo un mensaje, Entonces el sistema debe enviarlo correctamente al mecánico asignado <br> **Escenario 2:** Confirmación de envío: Dado que he enviado un mensaje, Cuando el sistema lo procesa correctamente, Entonces debe aparecer una confirmación visual <br> **Escenario 3:** Comunicación bidireccional: Dado que hay una conversación activa, Cuando el mecánico responde, Entonces el mensaje debe aparecer en la interfaz del chat correspondiente |
| EP06 | Mensajería entre Usuario y Mecánico | US22 | Notificaciones de nuevos mensajes |  Como usuario, quiero recibir notificaciones cuando el mecánico me envíe un mensaje para estar informado sin necesidad de revisar constantemente la app. | **Escenario 1:** Notificación emergente en la app: Dado que recibo un nuevo mensaje, Cuando estoy usando la plataforma, Entonces debe mostrarse una notificación visual <br> **Escenario 2:** Acceso directo desde la notificación: Dado que toco la notificación, Cuando esta se activa, Entonces debo ser dirigido automáticamente a la conversación correspondiente |
| EP06 | Mensajería entre Usuario y Mecánico | US23 | Historial de conversación por vehículo o servicio |  Como usuario, quiero consultar el historial de mensajes asociados a cada vehículo o servicio para revisar fácilmente las conversaciones pasadas con el mecánico. | **Escenario 1:** Acceso al historial desde la ficha del vehículo: Dado que tengo vehículos registrados, Cuando ingreso al detalle de uno de ellos, Entonces debe estar disponible la opción de ver las conversaciones asociadas <br> **Escenario 2:** Visualización ordenada cronológicamente: Dado que ingreso al historial de mensajes, Cuando se cargan las conversaciones, Entonces debe mostrar en orden cronológico los mensajes |
| EP07 | Gestión de Suscripción y Pagos | US24 | Selección del plan de suscripción |  Como usuario, quiero elegir el plan de suscripción que mejor se adapte a mis necesidades para aprovechar los servicios de AutoNexo según mi presupuesto y uso. | **Escenario 1:** Visualización de todos los planes disponibles: Dado que accedo a la sección de suscripciones, Cuando la pantalla carga, Entonces debo ver todos los planes con sus características y precios <br> **Escenario 2:** Selección de un plan: Dado que deseo suscribirme, Cuando selecciono un plan y realizo el pago, Entonces el sistema debe activarlo y mostrarme un mensaje de confirmación <br> **Escenario 3:** Restricciones por plan: Dado que selecciono un plan específico, Cuando utilizo la plataforma, Entonces solo debo tener acceso a las funciones incluidas en dicho plan |
| EP07 | Gestión de Suscripción y Pagos | US25 | Registro de método de pago seguro |  Como usuario, quiero registrar un método de pago seguro para poder realizar mis pagos de suscripción sin preocupaciones y de forma rápida. | **Escenario 1:** Ingreso de datos de tarjeta válidos: Dado que deseo agregar un nuevo método de pago, Cuando ingreso los datos correctamente, Entonces el sistema debe registrarlos y confirmar que se ha guardado con éxito <br> **Escenario 2:** Validación de campos incorrectos: Dado que ingreso datos incompletos o inválidos, Cuando intento guardar el método de pago, Entonces el sistema debe mostrar mensajes de error y no permitir el registro <br> **Escenario 3:** Seguridad del proceso de registro: Dado que estoy ingresando mis datos bancarios, Cuando realizo el proceso, Entonces debe hacerse mediante un canal cifrado y seguro |
| EP07 | Gestión de Suscripción y Pagos | US26 | Renovación automática de suscripción |  Como usuario, quiero que mi suscripción se renueve automáticamente para seguir disfrutando del servicio sin interrupciones. | **Escenario 1:** Activación de la renovación automática: Dado que tengo una suscripción activa, Cuando selecciono la opción de renovación automática, Entonces el sistema debe habilitar esta función y notificarme que está activa <br> **Escenario 2:** Cobro exitoso en la fecha programada: Dado que tengo un método de pago válido y renovación activa, Cuando llega la fecha de renovación, Entonces el sistema debe realizar el cobro y mantener mi suscripción activa <br> **Escenario 3:** Notificación previa a la renovación: Dado que tengo activada la renovación, Cuando se acerque la fecha de cobro, Entonces el sistema debe notificarme con anticipación |
| EP07 | Gestión de Suscripción y Pagos | US27 | Cambio de plan de suscripción |  Como usuario, quiero poder cambiar mi plan de suscripción en cualquier momento para ajustarlo a mis necesidades o presupuesto. | **Escenario 1:** Cambio exitoso de plan: Dado que tengo una suscripción activa, Cuando selecciono un nuevo plan y confirmo el cambio, Entonces el sistema debe aplicar el nuevo plan y mostrar una notificación de éxito <br> **Escenario 2:** Validación de requisitos del nuevo plan: Dado que estoy eligiendo un nuevo plan, Cuando este requiere condiciones específicas (pago anticipado), Entonces el sistema debe indicarlas antes de permitir el cambio <br> **Escenario 3:** Notificación del cambio: Dado que he cambiado mi plan, Cuando se complete el proceso, Entonces debo recibir una notificación de la app confirmando la modificación |
| EP07 | Gestión de Suscripción y Pagos | US28 | Cancelación o pausa del servicio |  Como usuario, quiero tener la opción de cancelar o pausar mi suscripción para detener el servicio temporal o permanentemente según mi situación. | **Escenario 1:** Cancelación voluntaria del servicio: Dado que deseo dejar de utilizar AutoNexo, Cuando solicito la cancelación desde la sección de suscripción, Entonces el sistema debe procesarla y mostrar una confirmación clara <br> **Escenario 2:** Pausar temporalmente el servicio: Dado que no quiero usar el servicio por un tiempo, Cuando selecciono la opción de pausa, Entonces el sistema debe suspender la facturación <br> **Escenario 3:** Confirmación y efectos del estado cancelado o pausado: Dado que he pausado o cancelado mi suscripción, Cuando intento acceder a funcionalidades premium, Entonces el sistema debe informar que están deshabilitadas |
| EP08 | Interacción y Navegación en la Landing Page | US29 | Navegación intuitiva |  Como visitante de la Landing Page, quiero navegar de forma intuitiva entre las secciones del sitio para encontrar rápidamente la información que necesito. | **Escenario 1:** Menú visible y funcional: Dado que el visitante se encuentra en la landing page, Cuando accede desde cualquier dispositivo, Entonces debe visualizar un menú de navegación accesible y funcional <br> **Escenario 2:** Transiciones suaves entre secciones: Dado que el visitante se desplaza por la página, Cuando hace clic en los elementos del menú, Entonces la transición entre secciones debe ser fluida y sin errores |
| EP08 | Interacción y Navegación en la Landing Page | US30 | Compatibilidad con lectores de pantalla |  Como visitante con discapacidad visual, quiero que la Landing Page sea compatible con lectores de pantalla para poder acceder al contenido sin barreras. | **Escenario 1:** Estructura semántica adecuada: Dado que el visitante utiliza un lector de pantalla, Cuando navega por la página, Entonces el lector debe interpretar correctamente los títulos, párrafos, botones y enlaces <br> **Escenario 2:** Etiquetado accesible de imágenes y botones: Dado que el visitante se desplaza por la landing page, Cuando el lector se posiciona sobre imágenes o botones, Entonces debe recibir descripciones adecuadas mediante etiquetas alt o aria-label |
| EP08 | Interacción y Navegación en la Landing Page | US31 | Feedback visual en interacciones |  Como visitante de la Landing Page, quiero recibir retroalimentación visual al interactuar con los elementos para saber que mis acciones han sido reconocidas. | **Escenario 1:** Cambio visual en botones al hacer clic o pasar el mouse: Dado que el visitante interactúa con botones, Cuando pasa el cursor o da clic sobre ellos, Entonces los botones deben responder visualmente <br> **Escenario 2:** Confirmación visual de acciones: Dado que el visitante completa una acción (como enviar un formulario), Cuando se envía correctamente, Entonces debe mostrarse un mensaje o señal de confirmación |
| EP09 | Integración y Exposición de Servicios vía API RESTful | TS01 | Registro de usuario a través de un RESTful API |  Como desarrollador, quiero implementar la opción de registrar nuevos usuarios a través de una API RESTful, para que los conductores y mecánicos puedan crear sus cuentas en la plataforma. | **Escenario 1:** Registro exitoso: Dado que soy un developer, Cuando envío una solicitud con los datos del nuevo usuario, Entonces el API debe registrar al usuario <br> **Escenario 2:** Usuario duplicado: Dado que ya existe un usuario con el mismo correo electrónico, Cuando intento registrar un nuevo usuario con ese mismo correo, Entonces el API debe devolver un mensaje de conflicto |
| EP09 | Integración y Exposición de Servicios vía API RESTful | TS02 | Registro de repuestos en inventario a través de un RESTful API |  Como desarrollador, quiero implementar la opción de registrar repuestos mediante una API RESTful, para que los usuarios puedan llevar un control del inventario de piezas disponibles. | **Escenario 1:** Registro exitoso de repuesto: Dado que tengo datos del repuesto, Cuando envío una solicitud con los datos del nuevo repuesto, Entonces el API debe guardar el repuesto y devolver su ID <br> **Escenario 2:** Repuesto ya existente: Dado que intento registrar un repuesto con un código que ya está en el sistema, Cuando hago la solicitud, Entonces el API debe indicar que el repuesto ya existe |
| EP09 | Integración y Exposición de Servicios vía API RESTful | TS03 | Registro de vehículos a través de un RESTful API |  Como desarrollador, quiero implementar la opción de registrar vehículos mediante una API RESTful, para que los usuarios puedan gestionar sus autos en la plataforma. | **Escenario 1:** Registro exitoso: Dado que tengo todos los datos del vehículo, Cuando los envío mediante una solicitud, Entonces el API debe guardar el vehículo <br> **Escenario 2:** Asociación con usuario: Dado que un usuario está autenticado, Cuando registra un vehículo, Entonces este debe quedar asociado al ID de ese usuario |
| EP09 | Integración y Exposición de Servicios vía API RESTful | TS04 | Creación de diagnósticos a través de un RESTful API |  Como desarrollador, quiero permitir que los mecánicos registren diagnósticos de los vehículos mediante una API RESTful, para que los conductores puedan recibir un reporte claro del estado de su auto. | **Escenario 1:** Diagnostico creado correctamente: Dado que tengo acceso y los datos del diagnóstico, Cuando envío una solicitud POST, Entonces el sistema debe almacenar el diagnóstico <br> **Escenario 2:** Relación con el vehículo: Dado que el diagnóstico pertenece a un vehículo, Cuando lo registro, Entonces debe quedar asociado al vehículo correspondiente en la respuesta |
| EP09 | Integración y Exposición de Servicios vía API RESTful | TS05 | Creación de mantenimientos programados mediante RESTful API |  Como desarrollador, quiero permitir la programación de mantenimientos a través de una API RESTful, para que los usuarios puedan agendar sus servicios con anticipación. | **Escenario 1:** Mantenimiento registrado exitosamente: Dado que envío todos los datos necesarios, Cuando hago una solicitud POST válida, Entonces el API debe guardar el mantenimiento <br> **Escenario 2:** Asociación con vehículo y repuestos: Dado que indico los IDs del vehículo y repuestos, Cuando creo el mantenimiento, Entonces deben quedar relacionados en la base de datos |
| EP09 | Integración y Exposición de Servicios vía API RESTful | TS06 | Consulta de historial de servicios por vehículo mediante RESTful API |  Como desarrollador, quiero permitir la visualización del historial de mantenimiento de un vehículo mediante una API RESTful, para que el usuario tenga acceso completo a los servicios realizados. | **Escenario 1:** Historial disponible: Dado que el vehículo tiene servicios registrados, Cuando realizo una solicitud GET con su ID, Entonces el API debe devolver un listado de los servicios <br> **Escenario 2:** Vehículo no encontrado: Dado que uso un ID de vehículo inexistente, Cuando consulto el historial, Entonces el API debe responder con código erroneo |
| EP09 | Integración y Exposición de Servicios vía API RESTful | TS07 | Actualización del inventario de repuestos mediante RESTful API |  Como desarrollador, quiero actualizar automáticamente el inventario de repuestos usados después de un mantenimiento mediante una API RESTful, para reflejar en tiempo real los niveles de stock. | **Escenario 1:** Actualización exitosa: Dado que tengo permisos y datos válidos, Cuando envío una solicitud PUT con el nuevo stock, Entonces el API debe actualizar el inventario <br> **Escenario 2:** Valor inválido: Dado que ingreso una cantidad negativa, Cuando intento actualizar el stock, Entonces el API debe indicar el error de validación |

## **3.3. Impact Mapping**

<img src="img/ImpactMap.png" alt="Impact Map Autonexo" width="550"/>

## **3.4. Product Backlog**

| \# Orden | User Story ID / Technical Story ID | Título | Descripción | Prioridad | Story Points (1/2/3/5/8) |
| :---: | :---: | :---: | :---: | ----- | :---: |
| **1** | US01 | Registro de usuario	 | Como nuevo usuario, quiero registrarme en la plataforma para empezar a utilizar los servicios de AutoNexo. | Alta | 5 |
| **2** | US02 | Inicio de sesión seguro | Como usuario registrado, quiero iniciar sesión de forma segura para acceder a todas las funcionalidades de la plataforma | Media | 3 |
| **3** | US03 | Registro de vehículos | Como usuario, quiero registrar mis vehículos en la plataforma para gestionar su mantenimiento y seguimiento. | Media | 5 |
| **4** | US04 | Registro de repuestos | Como usuario, quiero registrar repuestos en el sistema para tener un control del inventario. | Media | 3 |
| **5** | US05 | Gestión del perfil del usuario | Como usuario, quiero gestionar mi información personal en mi perfil para mantener mis datos actualizados | Media | 5 |
| **6** | US06 | Edición del perfil desde la app | Como usuario, quiero editar mi perfil directamente desde la aplicación para mayor comodidad. | Baja | 3 |
| **7** | US07 | Visualización del calendario de mantenimientos | Como usuario, quiero visualizar un calendario con los mantenimientos programados para tener una vista clara de las fechas importantes. | Media | 3 |
| **8** | US08 | Programación de nuevos mantenimientos | Como usuario, quiero poder programar nuevos mantenimientos para organizar el cuidado de mi vehículo. | Alta | 5 |
| **9** | US09 | Edición o cancelación de mantenimientos agendados | Como usuario, quiero editar o cancelar los mantenimientos programados para mantener mi calendario actualizado según mis necesidades. | Media | 3 |
| **10** | US10 | Recordatorios automáticos para mantenimientos programados | Como usuario, quiero recibir recordatorios automáticos para los mantenimientos agendados, para no olvidar ninguna cita importante. | Media | 3 |
| **11** | US11 | Consulta de repuestos disponibles | Como usuario, quiero consultar los repuestos disponibles en el inventario para saber si están en stock antes de agendar un mantenimiento. | Alta | 5 |
| **12** | US12 | Registro de nuevos ingresos de repuestos | Como administrador, quiero registrar nuevos ingresos de repuestos al sistema para mantener actualizado el inventario. | Media | 3 |
| **13** | US13 | Notificación de repuestos bajos en stock | Como usuario, quiero recibir notificaciones cuando los repuestos estén por agotarse, para reabastecer el inventario a tiempo. | Baja | 2 |
| **14** | US14 | Actualización del inventario tras mantenimiento | Como usuario, quiero que el sistema actualice automáticamente el inventario cuando se utilicen repuestos en un mantenimiento, para mantener los datos precisos. |    Media | 3 |
| **15** | US15 | Generación de presupuesto de mantenimiento | Como usuario, quiero que el sistema genere un presupuesto estimado para el mantenimiento del vehículo, para saber cuánto me costará antes de aprobarlo. | Alta | 8 |
| **16** | US16 | Edición de costos y repuestos por servicio | Como mecánico, quiero poder modificar los costos y repuestos asignados a un servicio, para reflejar cambios reales antes de facturar. | Media | 5 |
| **17** | US17 | Visualización de gastos históricos por vehículo | Como usuario, quiero visualizar los gastos acumulados en mantenimientos por cada vehículo, para tener un control de mi inversión en reparaciones. | Media | 3 |
| **18** | US18 | Consulta del historial por vehículo | Como usuario, quiero consultar el historial completo de mantenimientos por cada vehículo, para tener claridad sobre los servicios realizados. | Media | 5 |
| **19** | US19 | Detalle de cada servicio registrado | Como usuario, quiero acceder al detalle de cada servicio registrado para revisar qué repuestos se usaron, el costo y las observaciones del mecánico. | Media | 3 |
| **20** | US20 | Exportación o descarga del historial en PDF | Como usuario, quiero poder exportar o descargar en PDF el historial de mantenimientos de un vehículo para conservarlo o compartirlo fácilmente. | Baja | 2 |
| **21** | US21 | Envío de mensajes entre usuario y mecánico | Como usuario, quiero poder comunicarme con el mecánico a través de la plataforma para resolver dudas o recibir actualizaciones sobre mis mantenimientos. | Media | 3 |
| **22** | US22 | Notificaciones de nuevos mensajes | Como usuario, quiero recibir notificaciones cuando el mecánico me envíe un mensaje para estar informado sin necesidad de revisar constantemente la app. | Baja | 2 |
| **23** | US23 | Historial de conversación por vehículo o servicio | Como usuario, quiero consultar el historial de mensajes asociados a cada vehículo o servicio para revisar fácilmente las conversaciones pasadas con el mecánico. | Media | 3 |
| **24** | US24 | Selección del plan de suscripción | Como usuario, quiero elegir el plan de suscripción que mejor se adapte a mis necesidades para aprovechar los servicios de AutoNexo según mi presupuesto y uso. | Alta | 5 |
| **25** | US25 | Registro de método de pago seguro | Como usuario, quiero registrar un método de pago seguro para poder realizar mis pagos de suscripción sin preocupaciones y de forma rápida. | Alta | 8 |
| **26** | US26 | Renovación automática de suscripción | Como usuario, quiero que mi suscripción se renueve automáticamente para seguir disfrutando del servicio sin interrupciones. | Alta | 8 |
| **27** | US27 | Cambio de plan de suscripción | Como usuario, quiero poder cambiar mi plan de suscripción en cualquier momento para ajustarlo a mis necesidades o presupuesto. | Media | 3 |
| **28** | US28 | Cancelación o pausa del servicio | Como usuario, quiero tener la opción de cancelar o pausar mi suscripción para detener el servicio temporal o permanentemente según mi situación. | Media | 3 |
| **29** | US29 | Navegación intuitiva | Como visitante de la Landing Page, quiero navegar de forma intuitiva entre las secciones del sitio para encontrar rápidamente la información que necesito. | Alta | 5 |
| **30** | US30 | Compatibilidad con lectores de pantalla | Como visitante con discapacidad visual, quiero que la Landing Page sea compatible con lectores de pantalla para poder acceder al contenido sin barreras. | Media | 3 |
| **31** | US31 | Feedback visual en interacciones | Como visitante de la Landing Page, quiero recibir retroalimentación visual al interactuar con los elementos para saber que mis acciones han sido reconocidas. | Media | 3 |
| **32** | TS01 | Registro de usuario a través de un RESTful API | Como desarrollador, quiero implementar la opción de registrar nuevos usuarios a través de una API RESTful, para que los conductores y mecánicos puedan crear sus cuentas en la plataforma. | Alta | 5 |
| **33** | TS02 | Registro de repuestos en inventario a través de un RESTful API | Como desarrollador, quiero implementar la opción de registrar repuestos mediante una API RESTful, para que los usuarios puedan llevar un control del inventario de piezas disponibles. | Media | 3 |
| **34** | TS03 | Registro de vehículos a través de un RESTful API | Como desarrollador, quiero implementar la opción de registrar vehículos mediante una API RESTful, para que los usuarios puedan gestionar sus autos en la plataforma. | Media | 2 |
| **35** | TS04 | Creación de diagnósticos a través de un RESTful API | Como desarrollador, quiero permitir que los mecánicos registren diagnósticos de los vehículos mediante una API RESTful, para que los conductores puedan recibir un reporte claro del estado de su auto. | Alta | 2 |
| **36** | TS05 | Creación de mantenimientos programados mediante RESTful API | Como desarrollador, quiero permitir la programación de mantenimientos a través de una API RESTful, para que los usuarios puedan agendar sus servicios con anticipación. | Alta | 5 |
| **37** | TS06 | Consulta de historial de servicios por vehículo mediante RESTful API | Como desarrollador, quiero permitir la visualización del historial de mantenimiento de un vehículo mediante una API RESTful, para que el usuario tenga acceso completo a los servicios realizados. | Media | 3 |
| **38** | TS07 | Actualización del inventario de repuestos mediante RESTful API | Como desarrollador, quiero actualizar automáticamente el inventario de repuestos usados después de un mantenimiento mediante una API RESTful, para reflejar en tiempo real los niveles de stock. | Media | 2 |

Product Backlog en Trello: [https://trello.com/invite/b/6820091b7d003500b1d2cd2a/ATTIfca577753d06f90de7cd5590cef7b936C3B8D00D/product-backlog-autonexo](https://trello.com/invite/b/6820091b7d003500b1d2cd2a/ATTIfca577753d06f90de7cd5590cef7b936C3B8D00D/product-backlog-autonexo) 

<img src="img/ProductBacklog.png" alt="Product Backlog Autonexo" width="750"/>

# <font color="red"> **Capítulo IV: Product Design** </font>

## **4.1. Style Guidelines**

Una **Style Guideline**  es un conjunto de normas y recomendaciones que definen cómo se debe redactar, diseñar o estructurar contenido, ya sea en documentos, sitios web, software u otros productos creativos. A continuación, se detallan los lineamientos específicos aplicados en la organización y diseño del presente proyecto.

**Branding**  
**Brand Overview:**

La startup, presentada con el nombre de “ATG”, se especializa en ofrecer una solución tecnológica integral para optimizar el proceso de mantenimiento vehicular en el Perú. A través de su plataforma digital, permite a los usuarios registrar sus vehículos, seleccionar técnicos de confianza y gestionar todo el flujo de trabajo, desde la solicitud hasta la ejecución del servicio.

La plataforma segmenta el proceso en distintas etapas: registro del vehículo, selección del mecánico, generación de diagnósticos técnicos con costos e inventario, validación del cliente, ejecución de la reparación mediante una checklist guiada y almacenamiento del informe final en el historial del vehículo. Además, el sistema analiza tanto datos históricos como información en tiempo real para brindar trazabilidad, facilitar la toma de decisiones y aumentar la eficiencia operativa de técnicos y dueños de flotas.

Así, se mejora el control del mantenimiento, se reducen costos innecesarios y se optimiza la comunicación entre los actores clave del proceso, digitalizando por completo una tarea que tradicionalmente ha sido manual y desorganizada.

**Misión:** Digitalizar la gestión del mantenimiento vehicular, conectando a técnicos y clientes mediante flujos inteligentes que aseguren organización, eficiencia y trazabilidad en cada servicio realizado.

**Visión:** Ser la plataforma líder en gestión de mantenimientos vehiculares en el Perú, ofreciendo una experiencia integral, intuitiva y confiable para empresas, técnicos y usuarios particulares.

![Descripción de la imagen](img/logoATG.png)

**Brand Name:** 

El nombre de la propuesta de solución es AutoNexo. El concepto nace de la fusión entre los términos “Auto” (vehículo) y “Nexo” (conexión, enlace), reflejando la misión principal de la plataforma: ser el punto de conexión entre clientes y técnicos, y entre cada fase del proceso de mantenimiento vehicular.

Este nombre no solo representa la naturaleza del servicio, sino también el valor que aporta al rubro automotriz: centralizar, automatizar y conectar todos los elementos involucrados en la gestión técnica de una flota o vehículo individual. En ese sentido, AutoNexo se posiciona como una herramienta moderna, confiable y enfocada en transformar digitalmente el sector de mantenimiento vehicular en el país.

![Descripción de la imagen](img/logoComplete.png)

### 4.1.1. General Style Guidelines

Figma:[https://www.figma.com/design/D1mRJqb7kyr4DyR8rcyMXF/AutoNexo-Style-Guidelines?node-id=5118-975\&t=unmpfvn41gldCkVV-1](https://www.figma.com/design/D1mRJqb7kyr4DyR8rcyMXF/AutoNexo-Style-Guidelines?node-id=5118-975&t=unmpfvn41gldCkVV-1)

**Colores:** 

La identidad visual de AutoNexo se apoya en una paleta cromática moderna, contrastante y funcional, pensada para reforzar la experiencia en entornos digitales técnicos. Cada color cumple una función específica dentro de la interfaz, garantizando legibilidad, accesibilidad y consistencia visual.

* **\#**080210 – Violeta o Púrpura Azulado Oscuro  
   Usado como fondo principal, barra de navegación, íconos y textos en fondos fucsia o blancos.

* \#DD22EB – Magenta Brillante / Fucsia  
   Color predominante en títulos sobre fondo blanco, botones activos, elementos principales y enlaces. También aplicado a logotipos e íconos destacados.

* \#F3BAFF – Lila Pastel / Lavanda Claro  
   Utilizado como fondo de inputs, checks activos o botones en estado de hover sobre fondos claros.

* \#540065 – Morado Oscuro Profundo  
   Aplicado en estados hover de enlaces sobre fondo blanco y elementos secundarios destacados.

Esta paleta permite comunicar tecnología, innovación y profesionalismo, facilitando además una interfaz atractiva y funcional en ambientes operativos.

![Descripción de la imagen](img/colors.png)

**Tipografia:** 

La tipografía cumple un papel fundamental en la estructura visual de AutoNexo, ya que permite establecer jerarquías claras entre los distintos niveles de contenido y facilita la navegación del usuario a lo largo de la interfaz. Para este proyecto, se han seleccionado dos tipografías que combinan solidez y legibilidad: Montserrat Bold, utilizada en títulos para transmitir fuerza y profesionalismo, y Roboto, en estilos Bold y Light, empleada en cuerpos de texto y descripciones para asegurar una lectura fluida y moderna.

La jerarquía tipográfica está organizada en cuatro niveles principales dentro del sistema web, definidos por los siguientes tamaños:

* **TITLE 1**  
   *Font:* Montserrat  
   *Tamaño:* 42px / 50px – Bold (700)  
   *Uso:* Títulos principales de formularios y cajas de texto.

* **Button-text**  
   *Font:* Montserrat  
   *Tamaño:* 18px / 21px – Medium (500)  
   *Uso:* Texto de botones interactivos.

* **body-text**  
   *Font:* Roboto  
   *Tamaño:* 16px / 19px – Light (300)  
   *Uso:* Texto de párrafos y entradas (inputs).

* **body-title**  
   *Font:* Roboto  
   *Tamaño:* 32px / 37px – Medium (500)  
   *Uso:* Subtítulos o encabezados antes de bloques de texto.

* **body-title-italic**  
   *Font:* Roboto  
   *Tamaño:* 32px / 37px – Medium (500), *cursiva*  
   *Uso:* Preguntas o instrucciones para el usuario.

* **placeholder**  
   *Font:* Roboto  
   *Tamaño:* 14px / 16.5px – Light (300) o 11px / 13px – Semibold (600)  
   *Uso:* Texto dentro de campos input como guía de usuario.

![Descripción de la imagen](img/typographyMontserrat.png)

![Descripción de la imagen](img/typographyRoboto.png)

**Iconografía:** 

La iconografía en AutoNexo ha sido diseñada para ser intuitiva, reconocible y coherente con el flujo de trabajo de técnicos y administradores. Se emplean íconos funcionales que representan acciones y secciones clave, como perfil, historial, solicitud, inventario, reparación y configuración, así como acciones específicas como agregar, editar, aceptar, denegar, entrar, salir y volver atrás (go back). También se incluyen íconos ilustrativos como carro, imagen y ubicación, que refuerzan visualmente el contexto de cada vista. Esta iconografía contribuye a una navegación más fluida y a una rápida comprensión de las funciones, optimizando la experiencia del usuario en entornos operativos.

![Descripción de la imagen](img/iconography.png)

**Grid System:**

![Descripción de la imagen](img/gridSystems.png)

**Espaciado:**

![Descripción de la imagen](img/spacing.png)

**Campos de Texto:**

![Descripción de la imagen](img/textFields.png)

**Selectores:**

![Descripción de la imagen](img/selectors.png)

**Botones:**

![Descripción de la imagen](img/buttons.png)

**Elementos Grandes:**

![Descripción de la imagen](img/bigElements.png)

**Tarjetas:**

![Descripción de la imagen](img/cards.png)

### 4.1.2. Web Style Guidelines

**Tarjetas**

Se emplean tarjetas visuales para representar elementos clave como solicitudes activas, vehículos asignados, reparaciones enviadas e historial técnico. Estas tarjetas incluyen **títulos, subtítulos, botones funcionales e íconos representativos**, organizados verticalmente para una interacción cómoda con el pulgar. En cada una se destacan datos como el cliente, el vehículo y la acción pendiente, asegurando una vista rápida del estado del proceso.

**Imágenes**

Las imágenes dentro de la aplicación cumplen un rol funcional: se utilizan para mostrar el modelo del vehículo en reparación, representar repuestos o ilustrar íconos de sección. Estas imágenes son simples, claras y colocadas en áreas donde mejoran la comprensión inmediata, sin saturar la interfaz. No se emplean fondos visuales pesados, manteniendo un enfoque sobrio que favorece la legibilidad, especialmente en contextos de trabajo como talleres.

**Botones**

Los botones en la app móvil siguen las normas visuales definidas en la guía general. Se ubican estratégicamente en la parte inferior de cada pantalla para permitir una interacción fluida con una sola mano. Su coloración utiliza el fucsia vibrante \#DD22EB para destacar acciones principales como "Agregar", "Guardar" o "Comenzar reparación". Para acciones de confirmación o eliminación, se aplica un estilo distintivo que utiliza mayor contraste, como tonos oscuros o rojos, reforzando su función crítica.

**Listas y registros**

En lugar de tablas convencionales, se utilizan listas verticales que muestran ítems como repuestos a emplear, reparaciones anteriores o pasos de una checklist. Cada elemento cuenta con un orden visual jerárquico: nombre del proceso, tipo de reparación, detalles y estado. Estas listas pueden contener divisiones por fecha o tipo, y permiten al técnico llevar un seguimiento claro incluso desde un entorno móvil.

**Pantallas Emergentes (Pop-ups)**

Las pantallas emergentes son utilizadas para confirmar acciones sensibles como aceptar o rechazar solicitudes, registrar reparaciones o modificar datos importantes. Se oscurece el fondo para enfocar la atención del usuario y se emplean colores vivos y contrastantes para reforzar la importancia de la decisión antes de continuar el flujo de trabajo. Esto mejora la claridad y reduce el margen de error en tareas críticas.

**Navegación Móvil**

AutoNexo presenta una barra de navegación inferior con íconos circulares altamente visibles, optimizados para el trabajo diario del técnico. Esta barra permite cambiar rápidamente entre módulos: solicitudes, historial, inventario, tareas pendientes, etc. Esta disposición mejora la usabilidad con el pulgar y reduce la necesidad de desplazamientos excesivos, ideal para entornos de campo o talleres.

## **4.2. Information Architecture**

Dado que AutoNexo es una plataforma orientada a optimizar el proceso de gestión y ejecución de mantenimientos vehiculares, resulta fundamental que el usuario se mantenga en todo momento consciente del flujo que está realizando y del punto exacto donde se encuentra dentro de la aplicación. La arquitectura de la información ha sido diseñada para facilitar esa comprensión de forma clara y secuencial.

Cada pantalla responde a una fase específica del proceso, iniciando desde la visualización general de los vehículos asignados, pasando por el registro o revisión de reparaciones, hasta llegar a la ejecución técnica y cierre del mantenimiento. El usuario (técnico o administrador) avanza dentro del sistema siguiendo un flujo progresivo, donde cada unidad representa un vehículo y sus intervenciones a lo largo del tiempo.

Además, a través de la vista de “Panel Técnico” o “Panel de Vehículos”, se proporciona una perspectiva centralizada de las funcionalidades clave como solicitudes activas, historial, inventario disponible y checklist en curso. Esto permite distinguir claramente entre las tareas operativas (registro y ejecución) y las tareas de control y análisis, otorgando un equilibrio entre acción inmediata y seguimiento estratégico del mantenimiento.

Esta estructura garantiza una experiencia de usuario organizada, lógica y enfocada en reducir el esfuerzo cognitivo, lo cual es clave en contextos técnicos donde la eficiencia y la precisión son fundamentales.

### **4.2.1. Organization Systems**

La organización visual del contenido en AutoNexo se ha estructurado en función de las tareas clave que realizan tanto los técnicos como los administradores de flotas. Para lograr una navegación clara y funcional, se implementan distintos tipos de organización: jerárquica, secuencial, matricial y por audiencia, dependiendo del tipo de pantalla y el rol del usuario.

En las pantallas de log-in y de perfil de usuario, se aplica una organización jerárquica. Los títulos como nombres de usuario, cargo y empresa tienen un mayor peso visual que los datos específicos, destacando la identidad del usuario antes de permitir la edición. Las acciones secundarias, como modificar datos o cerrar sesión, están visualmente diferenciadas con botones en colores suaves que no compiten con la información principal.

Las vistas relacionadas con el flujo de trabajo técnico como la gestión de reparaciones, se organizan de forma secuencial, guiando al mecánico a través de un proceso paso a paso: desde la recepción de una solicitud, pasando por la creación de una reparación sugerida, hasta la ejecución y cierre con checklist. Esta secuencia permite mantener un orden lógico de intervención técnica, reduciendo errores y aumentando la trazabilidad.

Para los administradores, el sistema ofrece una vista tipo matricial, especialmente en el panel de control. Esta pantalla agrupa visualmente tarjetas que representan vehículos, estadísticas de mantenimiento, historial técnico y gestión de repuestos. Cada tarjeta está diferenciada por color y función, permitiendo una rápida exploración y acceso a los módulos más utilizados por parte del personal administrativo.

En pantallas como Inventario disponible o Reparaciones enviadas, la organización se basa en listas por categoría y visualización vertical, priorizando claridad y rapidez de lectura. Los elementos se presentan acompañados de imágenes y etiquetas que facilitan la identificación inmediata.

Además, se implementa una categorización por audiencia al momento de ingresar a la aplicación. Por ejemplo, los técnicos inician su jornada en la pantalla de solicitudes activas o vehículos asignados, enfocándose en la acción inmediata. En cambio, los administradores acceden directamente al panel general, donde pueden supervisar el estado global de la flota y coordinar tareas.

### **4.2.2. Labeling Systems**

En AutoNexo, el sistema de etiquetado cumple una función clave para facilitar la comprensión del contenido en cada vista y asegurar una navegación eficiente. Los encabezados están presentes en todas las pantallas, especialmente en aquellas que no forman parte directa del flujo de reparación, como el historial técnico, el inventario disponible o el perfil del usuario. Estos encabezados resumen de forma clara y directa la función principal de la pantalla, permitiendo al usuario identificar de inmediato dónde se encuentra y qué puede hacer.

En el panel principal, las tarjetas informativas como “Vehículos asignados”, “Solicitudes recibidas”, “Reparaciones pendientes” o “Inventario disponible” están acompañadas de etiquetas textuales claras y representativas, que indican con precisión el contenido al que se accederá. Estas etiquetas están reforzadas con íconos visuales consistentes que mejoran la usabilidad, especialmente en contextos de uso rápido como talleres o ambientes móviles.

Dentro de la barra de navegación lateral (desktop) o inferior (mobile), se incluyen labels visibles en todo momento para las vistas más importantes como Inicio, Historial, Reparaciones, Inventario y Perfil, facilitando el desplazamiento entre módulos sin necesidad de exploración innecesaria.

El etiquetado de campos dentro de formularios y procesos técnicos como “Agregar reparación” o “Seleccionar inventario a emplear” también sigue una lógica coherente y específica para el rubro automotriz, con terminología técnica comprensible tanto para mecánicos como para administradores de flotas.

### **4.2.3. SEO Tags and Meta Tags**

Las metaetiquetas son elementos fundamentales para definir metadatos dentro de un sitio web. Aunque no son visibles para los usuarios, sí son interpretadas por navegadores y rastreadores web, permitiendo una mejor organización, interpretación y posicionamiento del contenido en los motores de búsqueda. Su implementación en AutoNexo facilita tanto la correcta visualización del sitio como el mantenimiento de su estructura HTML, aportando además al posicionamiento SEO de la plataforma.

A continuación, se detallan las principales metaetiquetas utilizadas en el proyecto:

**Título**

Esta etiqueta es una de las más relevantes, ya que define el título que se mostrará en los resultados de los buscadores (SERP). Es clave para captar la atención del usuario.

`<title>Gestiona el mantenimiento de tu flota con AutoNexo</title>`

**Codificación de caracteres**

Permite que los caracteres especiales se visualicen correctamente en todos los navegadores.

`<meta charset="utf-8">`

**Descripción**

Brinda un resumen del contenido principal del sitio web, ayudando a los motores de búsqueda a entender su propósito.

`<meta name="description" content="AutoNexo es una plataforma web para la gestión integral del mantenimiento vehicular. Permite registrar vehículos, asignar técnicos, planificar reparaciones y mantener trazabilidad de todo el proceso.">`

**Palabras clave (Keywords)**

Incluye términos relacionados con el contenido del sitio, ayudando al posicionamiento en búsquedas relevantes.

`<meta name="keywords" content="mantenimiento, vehículos, flotas, reparaciones, técnico, gestión, autos, plataforma, AutoNexo">`

**Autor y Derechos de autor**

Define el autor del proyecto y los derechos sobre el contenido publicado.

`<meta name="author" content="AutoNexo Team">`

`<meta name="copyright" content="Copyright AutoNexo 2025">`

### **4.2.4. Searching Systems**

En AutoNexo, los usuarios administradores pueden buscar y filtrar información clave de forma rápida y eficiente. Esto es fundamental para gestionar grandes volúmenes de datos generados por los registros de vehículos, mantenimientos y técnicos.

Se pueden realizar búsquedas por placa, fecha de registro, tipo de mantenimiento o estado del proceso. En el historial, los filtros incluyen tipo de reparación, fecha, técnico responsable y repuestos utilizados.

También es posible buscar técnicos por nombre, especialidad o cantidad de intervenciones, facilitando la organización del equipo. Estas funcionalidades permiten acceder fácilmente a la información necesaria para tomar decisiones rápidas y efectivas.

### **4.2.5. Navigation Systems**

Los sistemas de navegación principales de la Landing Page de Autonexo son los menús de navegación superior e inferior. El sistema de labeling permite a los usuarios desplazarse directamente a las secciones que desean visualizar dentro de la página. En caso de no utilizar estos enlaces, el usuario podrá ver la página de manera descendente. En la aplicación, los usuarios seguirán el proceso de mantenimiento vehicular con secciones enumeradas, visibles arriba de los registros de cada fase del proceso. Los usuarios podrán saltar de una fase a otra o seguir un camino secuencial según el orden de los mantenimientos programados. Los botones en la plataforma representan la apertura, confirmación o finalización de un registro de mantenimiento, permitiendo que los usuarios continúen el proceso en una nueva pantalla de forma intuitiva.

## **4.3. Landing Page UI Design**

Link del Figma: [https://www.figma.com/design/D1mRJqb7kyr4DyR8rcyMXF/AutoNexo-Style-Guidelines?node-id=24-32\&t=CXkvwD2BlgThW7RS-1](https://www.figma.com/design/D1mRJqb7kyr4DyR8rcyMXF/AutoNexo-Style-Guidelines?node-id=24-32&t=CXkvwD2BlgThW7RS-1)

### **4.3.1. Landing Page Wireframe**

**Landing page para Desktop Web Browser**

![Descripción de la imagen](img/wireLandingPageA.png)

![Descripción de la imagen](img/wireLandingPageB.png)

![Descripción de la imagen](img/wireLandingPageC.png)

![Descripción de la imagen](img/wireLandingPageC.png)

![Descripción de la imagen](img/wireLandingPageC.png)

![Descripción de la imagen](img/wireLandingPageD.png)

![Descripción de la imagen](img/wireLandingPageE.png)

![Descripción de la imagen](img/wireLandingPageF.png)

### **4.3.2. Landing Page Mock-up**

**Landing page para Desktop Web Browser**  

![Descripción de la imagen](img/mockupLandingPageA.png)

![Descripción de la imagen](img/mockupLandingPageB.png)

![Descripción de la imagen](img/mockupLandingPageC.png)

![Descripción de la imagen](img/mockupLandingPageD.png)

![Descripción de la imagen](img/mockupLandingPageE.png)

![Descripción de la imagen](img/mockupLandingPageF.png)

![Descripción de la imagen](img/mockupLandingPageG.png)

![Descripción de la imagen](img/mockupLandingPageH.png)

## **4.4. Web Applications UX/UI Design**

### **4.4.1. Web Applications Wireframes**

User:

![Descripción de la imagen](img/wireAppUser.png)

Mechanic:

![Descripción de la imagen](img/wireAppMechanic.png)

Driver:

![Descripción de la imagen](img/wireAppDriver.png)

### **4.4.2. Web Applications Wireflow Diagrams**

![Descripción de la imagen](img/wireFlowA.png)

![Descripción de la imagen](img/wireFlowB.png)

![Descripción de la imagen](img/wireFlowC.png)

### **4.4.3. Web Applications Mock-ups**

User:

![Descripción de la imagen](img/mockupAppUser.png)

Mecánico:

![Descripción de la imagen](img/mockupAppMechanic.png)

![Descripción de la imagen](img/mockupAppMechanicB.png)

Driver:

![Descripción de la imagen](img/mockupAppDriver.png)

### **4.4.4. Web Applications User Flow Diagrams**

Link LucidChart: [https://lucid.app/lucidchart/37e9a14d-a46b-448d-9841-196d02438668/edit?viewport\_loc=-4077%2C-434%2C14613%2C6821%2C0\_0\&invitationId=inv\_547ed1f4-8d1e-41f6-a112-bc3205b6c1c8](https://lucid.app/lucidchart/37e9a14d-a46b-448d-9841-196d02438668/edit?viewport_loc=-4077%2C-434%2C14613%2C6821%2C0_0&invitationId=inv_547ed1f4-8d1e-41f6-a112-bc3205b6c1c8)

**USUARIO:MECANICO**

![Descripción de la imagen](img/mechanicFlowA.png)

![Descripción de la imagen](img/mechanicFlowB.png)

![Descripción de la imagen](img/mechanicFlowC.png)

![Descripción de la imagen](img/mechanicFlowD.png)

![Descripción de la imagen](img/mechanicFlowE.png)

![Descripción de la imagen](img/mechanicFlowF.png)

![Descripción de la imagen](img/mechanicFlowG.png)

![Descripción de la imagen](img/mechanicFlowH.png)

![Descripción de la imagen](img/mechanicFlowI.png)

USUARIO: CONDUCTOR  

![Descripción de la imagen](img/driverFlowA.png)

![Descripción de la imagen](img/driverFlowB.png)

![Descripción de la imagen](img/driverFlowC.png)

![Descripción de la imagen](img/driverFlowD.png)

![Descripción de la imagen](img/driverFlowE.png)

![Descripción de la imagen](img/driverFlowF.png)

![Descripción de la imagen](img/driverFlowG.png)

![Descripción de la imagen](img/driverFlowH.png)

## **4.5. Web Applications Prototyping**

Link Video Prototipo: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311053_upc_edu_pe/Ebh9UlP-IMJIixrQrg9GU2gBmLwOPERJO4AvsirWd7Fstw?e=EO7fVz&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311053_upc_edu_pe/Ebh9UlP-IMJIixrQrg9GU2gBmLwOPERJO4AvsirWd7Fstw?e=EO7fVz&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

## **4.6. Domain-Driven Software Architecture**

Autonexo adopta los principios del Domain Driven Design (DDD) como una estrategia clave para desarrollar un software que realmente entienda y resuelva los problemas del mantenimiento vehicular. El objetivo principal es lograr un entendimiento compartido del dominio entre los desarrolladores y los expertos en mantenimiento (técnicos, mecánicos, administradores de flotas).

Gracias a la perspectiva que brinda DDD, es posible fortalecer la colaboración interdisciplinaria, permitiendo que las decisiones técnicas estén alineadas con las necesidades reales del usuario. En Autonexo, el lenguaje ubicu**o** es parte fundamental del proceso: todos los participantes del proyecto comparten una terminología clara, coherente y contextualizada, lo cual evita ambigüedades y mejora la comunicación.

### **4.6.1. Software Architecture Context Diagram**

![Descripción de la imagen](img/contextDiagram.png)

### **4.6.2. Software Architecture Container Diagrams**

![Descripción de la imagen](img/containerDiagram.png)

### **4.6.3. Software Architecture Components Diagrams**

![Descripción de la imagen](img/componentsDiagramA.png)

![Descripción de la imagen](img/componentsDiagramB.png)

![Descripción de la imagen](img/componentsDiagramC.png)

![Descripción de la imagen](img/componentsDiagramD.png)

## **4.7. Software Object-Oriented Design**

### **4.7.1. Class Diagrams**

Lo hemos realizado en el software de LucidChart: [https://lucid.app/lucidchart/8cc8249e-65e6-47ef-a7ac-43d18a3e7683/edit?viewport\_loc=-542%2C-345%2C3967%2C1443%2C0\_0\&invitationId=inv\_eca9a654-aa1b-4ef6-b9eb-ed29b8f2660e](https://lucid.app/lucidchart/8cc8249e-65e6-47ef-a7ac-43d18a3e7683/edit?viewport_loc=-542%2C-345%2C3967%2C1443%2C0_0&invitationId=inv_eca9a654-aa1b-4ef6-b9eb-ed29b8f2660e)

![Descripción de la imagen](img/classDiagram.png)

### **4.7.2. Diccionario de Clases**

**Class User**

Guarda los atributos y métodos comunes para todo usuario (login, register, name, lastName, phoneNumber) y los métodos login, register para que puedan acceder a la aplicación., también es padre de Driver y Mechanic.

**Class Driver**

Es un tipo de usuario con funcionalidades propias (send request, approve or reject maintenance) y atributos como id driver y lista de carros. Es hija de user y mantiene una relación de asociación con este. 

***Relaciones:*** Driver tiene muchos Car, Driver tiene un solo MaintenanceRequest.

**Class Mechanic**

Es un tipo de usuario con funcionalidades propias (agregar mantenimiento, adjuntar mantenimiento, subir mantenimiento, ver carros para arreglar, agregar inventario, agregar items al inventario y asignar inventario e items para el mantenimiento). Tiene atributos como id mechanic, inventario y lista de carros para arreglar. Es hija de user y mantiene una relación de asociación con este. 

***Relaciones***: Mechanic tiene uno o más inventarios, Mechanic puede tener muchos MaintenanceRecord, Mechanic puede tener muchos MaintenanceRequest.

**Class Car:**

Guarda los datos propios de un auto como la marca, placa, año, modelo y un arreglo de mantenimientos realizados (list\<maintenanceRecord\>). Y los métodos que puede usar son: agregar Mantenimiento y mostrar todos los mantenimientos.

***Relaciones***: Car puede tener muchos MaintenanceRecord.

**Class Car Builder:**

Encapsula la lógica de construcción personalizada de un Car mediante el método Build().

**Service Class Car:**

Encapsula la lógica de negocio específica de Car, proporciona métodos para crear un car con todos sus parámetros,  encontrar un car mediante carId y obtener una lista con todos los car asociados a un driverId.

**Class MaintenanceRequest**

* Es la petición que le hace el Driver a Mechanic, en esta le envía el objeto auto (con todos los datos que la clase auto tiene), deja un comentario e indica a qué Mechanic se lo está enviando mediante mechanicId. La clase tiene los atributos recordId que luego obtendrá un valor una vez el mechanic responda y status que varía entre un enum de (PROGRESO, APROBADO, RECHAZADO)  
* Una vez el Mechanic recibe el request, este responde adjuntando un maintenanceRecord mediante el método attachMaintenanceRecord() y modifica el status mediante updateStatus()

**Class MaintenanceRecord**

Es la clase mantenimiento que crea el Mechanic para adjuntarlo al maintenanceRecord(), guarda toda la información de un mantenimiento de acuerdo a las especificaciones del carro y descripción del problema en el request. La clase MaintenanceRecord tiene los atributos: maitenanceDate, descripcion, totalCost, status, además de una lista con todos los repuestos utilizados para ese mantenimiento 

(list\<item\>). Esta clase puede realizar a través de sus métodos: calculateTotalCost() (calcula precio final del mantenimiento), assignInventory(list\<item\>) (asigna que repuestos se necesitan en ese mantenimiento).

***Relaciones***: MaintenanceRecord puede tener asignado ninguno o muchos Items.

**Service Class Maintenance**

Encapsula la lógica de negocio específica del maintenance o mantenimiento, proporciona métodos para crear un manteinanceRecord con todos sus parámetros, lista de items asignados, idMechanic y idCar. Un método para asignar inventario al mantenimiento con el objeto manteinanceRecord y la lista de items. Y un método para añadirlo al carLog. 

**Class Inventory**

Es el conjunto de Items (repuestos) que posee el Mechanic, tiene como atributo un inventoryId, nombre del inventario, mechanicId y una lista de items. Permite mostrar todos los items mediante getAllItems, agregar, eliminar y obtener un ítem en específico mediante getItem(idItem)

***Relaciones:*** Inventory tiene uno o más items

**Class Inventory Builder:**

Encapsula la lógica de construcción personalizada de un Inventory mediante el método Build(), además de permitir agregar o eliminar un item.

**Class Inventory Service:**

Encapsula la lógica de negocio específica del inventario, proporciona métodos para crear un ítem con todos sus parámetros,  cambiar el stock de cierto ítem y asignar ítems a los mantenimientos.

**Class Item**

Tiene todos los atributos que un repuesto debe tener (name, info, unitPrice, stock), así como el inventario al que pertenece permite mostrar el stock de ese item en el inventario mediante getStock().

## **4.8. Database Design**

### **4.8.1. Database Diagram**

Lo hemos realizado en el software LucidChart:[https://lucid.app/lucidchart/958d1937-30a6-4a7f-a668-5f8f3ce9a7ee/edit?viewport\_loc=-4769%2C-54%2C3624%2C1530%2C0\_0\&invitationId=inv\_eb407874-6533-4622-8f5a-b521552274b2](https://lucid.app/lucidchart/958d1937-30a6-4a7f-a668-5f8f3ce9a7ee/edit?viewport_loc=-4769%2C-54%2C3624%2C1530%2C0_0&invitationId=inv_eb407874-6533-4622-8f5a-b521552274b2)

![Descripción de la imagen](img/dbDiagram.png)

# <font color="red"> **Capítulo V: Product Implementation, Validation & Deployment** </font>

## **5.1. Software Configuration Management**

### **5.1.1. Software Development Environment Configuration**

En esta sección describiremos las herramienas de software que utilizamos para el ciclo de vida del proyecto.   

**Project Management:**   
- Producto: Trello
- Propósito: Seguimiento del progreso de funcionalidades y gestión de tareas
- Ruta: https://trello.com/es

<div align="center">
    <img src="img/project-management.png" alt="project-management.png" width="550px" height="300px">
</div>

**Product UX/UI Design:**
- Producto: Figma
- Propósito: Diseños del Proyecto (Wireframes, Mock-Ups, etc)
- Ruta: https://www.figma.com/es-es/

<div align="center">
    <img src="img/product-ux-ui-design.png" alt="product-ux-ui-design.png" width="550px" height="300px">
</div>

**Software Development:**
- Producto: Visual Studio Code
- Propósito: Desarrollo del Landing Page
- Ruta: https://code.visualstudio.com

<div align="center">
    <img src="img/software-development.png" alt="software-development.png" width="550px" height="300px">
</div>

**Software Documentation:**
- Producto: Visual Studio Code
- Propósito: Para redactar los capítulos en formato Markdown
- Ruta: https://code.visualstudio.com

<div align="center">
    <img src="img/software-documentation.png" alt="software-documentation.png" width="550px" height="300px">
</div>

**Software Deployment:**
- Producto: GitHub
- Propósito: Repositorio del Proyecto y gestión de versiones
- Ruta: https://github.com

<div align="center">
    <img src="img/software-deployment.png" alt="software-deployment.png" width="550px" height="300px">
</div>

### **5.1.2. Source Code Management**

Nuestro proyecto se mantendrá en línea con las convenciones de flujo de trabajo definidas por el modelo GitFlow para el control de versiones de desarrollo. Teniendo a GitHub como plataforma y sistema de control de versiones.
A continuación, detallaremos la implementación del modelo GitFlow y se proporcionará los URL de los repositorios de GitHub de cada producto del trabajo.

**Repositorios de GitHub:**
- Organización en GitHub
- Landing Page
- Frontend Web Application

**Flujo de Trabajo GitFlow:**
GitFlow es un modelo de flujo de trabajo para administrar y gestionar branches en un proyecto Git, propuesto por Vincent Driessen, diseñado para facilitar el desarrollo colaborativo.

**Estructuras de Branches:**
- **Master Branch:** Es la rama principal de la aplicación, contiene las versiones estables y sin errores listas para ser lanzadas públicamente.
- **Develop Branch:** Es la rama base para el desarrollo activo, aquí se integran todas las funcionalidades nuevas antes de que se considere un lanzamiento.
- **Feature Branch:** Es la rama que se usa para desarrollar nuevas funcionalidades o mejoras específicas del proyecto.
- **Release Branch:** Es la rama que se utiliza para preparar una versión estable del proyecto donde se corrigen bug menores, se actualizan versiones y se ajustan las configuraciones necesarias.
- **Hotfix Branch:** Es la rama donde se resuelven errores críticos encontrados en la aplicación lanzada. Esta rama se crea directamente del main, ya que necesitan una solución urgente sin pasar por el ciclo completo de desarrollo.

**Versionamiento Semántico:**
Aplicaremos el sistema de versionamiento semántico (Semantic Versioning) para dar nombre a los releases de nuestra aplicación.

**Convenciones de Commits:**
Para hacer commits claros y estructurados en nuestro proyecto, utilizaremos la especificación Conventional Commits, inspirada en las Angular Commit Guidelines.

### **5.1.3. Source Code Style Guide & Conventions**

**HTML:** Para conseguir un código ordenado y eficiente, deberemos seguir las siguientes indicaciones:
- Aplicar un uso semántico de etiquetas, tales como: ``<header>``, ``<main>``, ``<section>``, ``<article>``, ``<footer>``, entre otros, en lugar de solo usar ``<div>``.
- Asegurarse de cerrar todas las etiquetas y verificar que estén correctamente anidadas.
- Colocar los atributos en orden lógico. Es decir, seguir un patrón coherente y predecible al escribir estos atributos dentro de una etiqueta. Por ejemplo: *id*, *class*, *name*, *src*, *alt*, *dato*, *style* y atributos booleanos.
- Evitar usar abreviaturas al usar los atributos class e id. Por ejemplo, envés de ".pcd", usar ".product-card".
- Usar comentarios para describir pedazos de código o simplemente para separar secciones. Ejemplo: ``<!-- -->``

**CSS:** En este lenguaje es recomendable seguir las siguientes indicaciones:
- Organizar los estilos por componentes o secciones del sitio con ayuda de comentarios. Por ejemplo: ``/* Para el encabezado */``, ``/* Para el pie de página */``.
- Usar nombres descriptivos y consistentes para las clases.
- Separar los nombres de las clases e id usando un guión.
- No especificar la unidad de medida cuando se use 0 como valor.

**Gherkin:** Es un lenguaje de especificación estructurado y legible para humanos. Es usado para escribir pruebas de comportamiento (BDD, Behavior Driven Development). Se recomienda usar las palabras clave como Feature, Scenario, Given, When, Then, entre otras, y usar un lenguaje natural claro para que lo escrito sea entendible tanto por los desarrolladores como los stakeholders.

### **5.1.4. Software Deployment Configuration**

**Landing Page Deployment:**
Para desplegar la landing page debemos cumplir con una serie de requisitos. Algunos de ellos son: Contar con una cuenta personal de GitHub, una organización y un repositorio para subir los archivos. Con lo anterior, será posible desplegar la landing page. A continuación se deben seguir los siguientes pasos:

- Crear una carpeta con el nombre de "docs", en él se aloja el Landing Page.
- Verificar que los archivos tengan las nomenclaturas correctas y adecuadas, ya sea "index.html" para el landing page, "style.css" para los estilos y una carpeta llamada "img" para guardar las imágenes que la página usará.
- Subir los archivos al repositorio mediante commits.
- Ir a "Settings", luego a "Pages" y seleccionar el branch donde se localiza el proyecto.
- Seleccionar la carpeta "docs" como la fuente del landing page.
- Esperar a que GitHub termine de hacer las comprobaciones necesarias. Cuando termine todo este proceso, GitHub nos dará un enlace que nos llevará al Landing Page.

## **5.2. Landing Page, Services & Applications Implementation**

### **5.2.1. Sprint 1**

#### **5.2.1.1. Sprint Planning 1**

<div>
    <table>
        <tr>
            <th>Sprint #</th>
            <td>Sprint 1</td>
        </tr>
        <tr>
            <th>Location</th>
            <td>Reunión virtual a través de Discord</td>
        </tr>
        <tr>
            <th>Prepared by</th>
            <td>Andrés y Victor</td>
        </tr>
        <tr>
            <th>Attendees (to planning meeting)</th>
            <td>Peralta Chiba, Ronald Joel; Cardenas Minaya, Ricardo Fernando; Ibarra Cruz, Victor Andres; Cespedes Pillco, Jarod Jack y Vivanco Salazar, Ricardo Andres</td>
        </tr>
        <tr>
            <th>Sprint (n - 1) Review Summary</th>
            <td>No existe sprint previo</td>
        </tr>
        <tr>
            <th>Sprint 1 Goal</th>
            <td>In this sprint, we focused on deploying a good looking landing page that delivers satisfaction and confidence to us and to our future users. This will be confirmed when all members and users navigate the page without any issues at all.</td>
        </tr>
        <tr>
            <th>Sprint 1 Velocity</th>
            <td>20 story points</td>
        </tr>
        <tr>
            <th>Sum of Story Points</th>
            <td>20 story points</td>
        </tr>
    </table>
</div>

#### **5.2.1.2. Aspect Leaders and Collaborators**

Durante el primer sprint, el equipo **ATG** mostró una impecable unión y organización, lo que permitió cumplir satisfactoriamente el objetivo de desplegar la landing page del proyecto **AutoNexo**. A continuación, se describe el rol desempeñado por cada integrante del equipo.

- Victor Andrés Cruz Ibarra (u202311053)
- Rafael Andrés Vivanco Salazar (u202311064)
- Jarod Jack Céspedes Pillco (u202318588)
- Ricardo Fernando Cárdenas Minaya (u202310004)
- Ronald Joel Peralta Chipa (u202224619)

La ejecución del sprint fue coordinado mediante reuniones virtuales en Discord, con el respaldo de herramientas colaborativas como Google Docs, para redacción conjunta, y GitHub, como repositorio de control de versiones. Esta experiencia colaborativa permitió consolidar un equipo sincronizado, con roles bien definidos y con el establecimiento de una base sólida para los siguientes ciclos de desarrollo.

#### **5.2.1.3. Sprint Backlog 1**

<div align="center">
    <img src="img/sprint-backlog-1.png" alt="sprint-backlog-1.png" width="550px" height="300px">
</div>

Link: https://trello.com/invite/b/680b04bd8f9b8672e4f52732/ATTIcb2cd6271a6b1ae79daa19ca44e24e5657A5F126/product-backlog-autonexo

<div>
    <table>
        <tr>
            <th colspan="2">Sprint #</th>
            <td colspan="6">Sprint 1</td>
        </tr>
        <tr>
            <th colspan="2">User Story</th>
            <th colspan="6">Work-Item/Task</th>
        </tr>
        <tr>
            <th>User Story ID</th>
            <th>User Story Title</th>
            <th>Work Item ID</th>
            <th>Task Title</th>
            <th>Task Description</th>
            <th>Estimation (Hours)</th>
            <th>Assigned To</th>
            <th>Status</th>
        </tr>
        <tr>
            <td rowspan="3">US29</td>
            <td rowspan="3">Navegación Intuitiva</td>
            <td>WU01</td>
            <td>Diseñar interfaz de la Landing Page</td>
            <td>Diseñar la interfaz donde aparecerán los datos del proyecto</td>
            <td>3H</td>
            <td>Victor</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>WU02</td>
            <td>Codificar el Landing Page</td>
            <td>Codificar en HTML</td>
            <td>2H</td>
            <td>Victor</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>WU03</td>
            <td>Aplicar estilos al Landing Page</td>
            <td>Codificar los estilos en CSS</td>
            <td>2H</td>
            <td>Victor</td>
            <td>Done</td>
        </tr>
        <tr>
            <td rowspan="2">US30</td>
            <td rowspan="2">Compatibilidad con Lectores de Pantalla</td>
            <td>WU04</td>
            <td>Diseñar interfaz para que sea compatible con lectores de pantalla</td>
            <td>Diseño de la interfaz en otros dispositivos</td>
            <td>2H</td>
            <td>Ronald</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>WU05</td>
            <td>Codificar los estilos para hacer la landing page responsive</td>
            <td>Codificación de Estilos Responsive</td>
            <td>3H</td>
            <td>Rafael</td>
            <td>To-Do</td>
        </tr>
        <tr>
            <td rowspan="4">US31</td>
            <td rowspan="4">Compatibilidad con Lectores de Pantalla</td>
            <td>WU06</td>
            <td>Codificar la página para registrarse</td>
            <td>Codificación del HTML para registrarse</td>
            <td>1H</td>
            <td>Ricardo</td>
            <td>To-Do</td>
        </tr>
        <tr>
            <td>WU07</td>
            <td>Codificar la página para iniciar sesión</td>
            <td>Codificación del HTML para iniciar sesión</td>
            <td>1H</td>
            <td>Ricardo</td>
            <td>To-Do</td>
        </tr>
        <tr>
            <td>WU08</td>
            <td>Codificar la página para recuperar contraseña</td>
            <td>Codificación del HTML para recuperar contraseña</td>
            <td>1H</td>
            <td>Ricardo</td>
            <td>To-Do</td>
        </tr>
        <tr>
            <td>WU09</td>
            <td>Codificar la página para hacer una barra de navegación funcional</td>
            <td>Codificación para la barra de navegación</td>
            <td>2H</td>
            <td>Jarod</td>
            <td>Done</td>
        </tr>
    </table>
</div>

#### **5.2.1.4. Development Evidence for Sprint Review**

<div>
    <table>
        <tr>
            <th>Repository</th>
            <th>Branch</th>
            <th>Commit ID</th>
            <th>Commit Message</th>
            <th>Commit Message Body</th>
            <th>Commit on (Date)</th>
        </tr>
        <tr>
            <td>project-OpenSource-4310</td>
            <td>Main</td>
            <td>834fb12</td>
            <td>Style</td>
            <td>Landing Page Style</td>
            <td>04/24/2025</td>
        </tr>
        <tr>
            <td>project-OpenSource-4310</td>
            <td>Main</td>
            <td>874fee6</td>
            <td>Feat</td>
            <td>Landing Page</td>
            <td>04/24/2025</td>
        </tr>
    </table>
</div>

#### **5.2.1.5. Execution Evidence for Sprint Review**

En el primer sprint, logramos desarrollar parcialmente la implementación del despliegue del landing page. Donde se muestra las diferentes divisiones que el usuario podrá visualizar como lo sería la información sobre el startup y nuestro producto. A continuación mostramos algunas evidencias:

- **Sección Home (About Us):** En esta sección, damos al usuario una introducción sobre nosotros y nuestro producto.

<div align="center">
    <img src="img/home-section.png" alt="home-section.png" width="550px" height="300px">
</div>

- **Sección Servicios:** En esta sección, el usuario puede enterarse del funcionamiento de nuestro producto a través de un video informativo y una pequeña guía de cómo registrarse.

<div align="center">
    <img src="img/service-section.png" alt="service-section.png" width="550px" height="300px">
</div>

- **Sección Precios:** En esta sección, ofrecemos al usuario diferentes planes en los que se puede suscribir.

<div align="center">
    <img src="img/price-section.png" alt="prices-section.png" width="550px" height="300px">
</div>

- **Sección Testimonios:** En esta sección, el usuario puede ver testimonios de otras personas.

<div align="center">
    <img src="img/testimonies-section.png" alt="testimonies-section.png" width="550px" height="300px">
</div>

#### **5.2.1.6. Services Documentation Evidence for Sprint Review**

*Para este primer sprint no fue contemplada la evidencia de documentación de los servicios.*

#### **5.2.1.7. Software Deployment Evidence for Sprint Review**

Para la entrega del primer sprint, desplegamos el landing page en una versión temprana, la cual tiene unas cuantas funcionalidades sin implementar y bugs que, para las siguientes entregas, estarán completamente resueltas. He aquí la evidencia del despliegue:

<div align="center">
    <img src="img/deployment-evidence.png" alt="deployment-evidence.png" width="550px" height="300px">
</div>

#### **5.2.1.8. Team Collaboration Insights during Sprint**

Aquí se muestra el insight que nos proporciona Github, en su propio apartado:

<div align="center">
    <img src="img/team-collaboration-insights.png" alt="team-collaboration-insights.png" width="550px" height="300px">
</div>

### **5.2.2. Sprint 2**
#### **5.2.2.1. Sprint Planning 2**
| Sprint \# | Sprint 2 |
| :---- | :---- |
| Date | 2025 \- 05 \- 12 |
| Time | 19:00 |
| Location | Reunión virtual a través de Discord |
| Prepared by | Andrés Victor  |
| Attendees (to planning meeting) | Peralta Chiba, Ronald Joel; Cardenas Minaya, Ricardo Fernando; Ibarra Cruz, Victor Andres; Cespedes Pillco, Jarod Jack y Vivanco Salazar, Ricardo Andres |
| Sprint 2  Review Summary | Se presentó el avance del front-end de la aplicación y sus respectivos bounded contexts y diseños. |
| Sprint 2 Retrospective Summary | En esta reunión, todos colaboraron en el diseño y la implementación del frontend, contribuyendo a un desarrollo más ágil y efectivo del proyecto. |
| Sprint 2 Goal | Implementar y diseñar cada uno de los Bounded Context |
| Sprint 2 Velocity | 29 story points |
| Sum of Story Points | 49 story points |}
<br>

#### **5.2.2.2. Aspect Leaders and Collaborators**
Durante el segundo sprint, el equipo ATG mostró una gran organización, lo que permitió cumplir satisfactoriamente el objetivo de diseñar e implementar los bounded context de AutoNexo. A continuación, se describe el rol desempeñado por cada integrante del equipo.
<br>
    * Victor Andres Cruz Ibarra (U202311053): <br>
    * Rafael Andres Vivanco Salazar (U202311064): <br>
    * Jarod Jack Céspedes Pillco (U202318588): <br>
    * Ricardo Fernando Cardenas Minaya (U202310004): <br>
    * Ronald Joel Peralta Chipa (U202224619):<br>
<br>
La ejecución del sprint fue coordinado mediante reuniones virtuales en Discord, con el respaldo de herramientas colaborativas como Google Docs, para redacción conjunta, y GitHub, como repositorio de control de versiones.
<br>

#### **5.2.2.3. Sprint Backlog 2**
<div align="center">
    <img src="img/sprint-backlog-2.png" alt="sprint-backlog-2.png" width="550px" height="300px">
</div>

Link: [https://trello.com/invite/b/680b04bd8f9b8672e4f52732/ATTIcb2cd6271a6b1ae79daa19ca44e24e5657A5F126/product-backlog-autonexo](https://trello.com/invite/b/682413b3332f981bd0a0c9e8/ATTI96c86c3989bcd4016c076c5586951a20E5A6A6A8/sprint-backlog-2-atg)
<br>

| Sprint \# |  | Sprint \#2 |  |  |  |  |  |
| :---- | :---- | ----- | :---- | :---- | :---- | :---- | :---- |
| User Story ID | User Story Title | Work Item ID | Task Title | Task Description | Estimation (Hours) | Assigned To | Status |
| US01 | Registro de usuario	 | 1 | Añadir función de registro de usuario | Como nuevo usuario, quiero registrarme en la plataforma para empezar a utilizar los servicios de AutoNexo. | 2H | Victor | Done |
| US02 | Inicio de sesión seguro | 2 | Función para iniciar sesión en la app | Como usuario registrado, quiero iniciar sesión de forma segura para acceder a todas las funcionalidades de la plataforma | 1H | Ronald | Done |
| US03 | Registro de vehículos | 3 | Añadir función de registro de vehículos | Como usuario, quiero registrar mis vehículos en la plataforma para gestionar su mantenimiento y seguimiento. | 2H | Jarod | Done |
| US05 | Gestión del perfil del usuario | 4 | Pantalla para gestionar el perfil de usuario | Como usuario, quiero gestionar mi información personal en mi perfil para mantener mis datos actualizados. | 2H | Rafael | Done |
| US09 | Edición o cancelación de mantenimientos agendados | 5 | Función para editar o cancelar los mantenimientos | Como usuario, quiero editar o cancelar los mantenimientos programados para mantener mi calendario actualizado según mis necesidades. | 2H | Ricardo | Done |
| US18 | Consulta del historial por vehículo | 6 | Pantalla para ver los datos históricos de cada vehiculo | Como usuario, quiero consultar el historial completo de mantenimientos por cada vehículo, para tener claridad sobre los servicios realizados. | 2H | Jarod | Done |
| US19 | Detalle de cada servicio registrado | 7 | Función para mostrar todos los servicios registrados | Como usuario, quiero acceder al detalle de cada servicio registrado para revisar qué repuestos se usaron, el costo y las observaciones del mecánico. | 3H | Ronald | Done |
<br>

#### **5.2.2.4. Development Evidence for Sprint Review**
<br>

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Commited on (Date) |
| :---- | :---- | :---- | :---- | :---- | :---- |
| project-OpenSource-4310 | develop | 32a8943 | Style | button-classic added in shared/buttons | 05/13/2025 |
| project-OpenSource-4310 | develop | 3e91394 | Feat | ATG AutoNexo Added | 05/12/2025 |
| project-OpenSource-4310 | develop | 43ec90d | Feat | initial commit | 05/07/2025 |
<br>

#### **5.2.2.5. Execution Evidence for Sprint Review**
A continuacion la fake api ejecutada:
<br>
<div align="center">
    <img src="img/json.png" alt="json.png" width="550px" height="300px">
</div>
<br>
<div align="center">
    <img src="img/json2.png" alt="json2.png" width="550px" height="300px">
</div>

#### **5.2.2.6. Services Documentation Evidence for Sprint Review**
En el segundo sprint, logramos desarrollar parcialmente la implementación del despliegue del front end app. Donde se muestra las diferentes pnatallas para el usuario y luego de su registro para el mecánico o conductor.
A continuación evidencias:
<br>

- **Home view:** El entry point del frontendapp.
<div align="center">
    <img src="img/home_view.png" alt="home_view.png" width="550px" height="300px">
</div>
<br>

- **Login:** El login page del frontendapp.
<div align="center">
    <img src="img/login.png" alt="login.png" width="550px" height="300px">
</div>
<br>

- **Register:** El register page del frontendapp.
<div align="center">
    <img src="img/register.png" alt="register.png" width="550px" height="300px">
</div>
<br>

- **Forgot Password:** El forgot password page del frontendapp.
<div align="center">
    <img src="img/forgot_password.png" alt="forgot_password.png" width="550px" height="300px">
</div>
<br>

- **Reparaciones send:** Reparaciones enviadas por parte del mechanic.
<div align="center">
    <img src="img/reparaciones_send.png" alt="reparaciones_send.png" width="550px" height="300px">
</div>
<br>

- **Vehicles:** Los vehiculos que posee el mecánico
<div align="center">
    <img src="img/vehicles.png" alt="vehicles.png" width="550px" height="300px">
</div>
<br>

#### **5.2.2.7. Software Deployment Evidence for Sprint Review**
A continuación, se presentan capturas de los analíticos de colaboración desde el repositorio oficial, donde se evidencia la participación activa de todos los miembros del equipo.

<div align="center">
    <img src="img/network.png" alt="network.png" width="550px" height="300px">
</div>

#### **5.2.2.8. Team Collaboration Insights during Sprint**
Aquí se muestra el insight que nos proporciona Github, en su propio apartado:
<div align="center">
    <img src="img/network.png" alt="network.png" width="550px" height="300px">
</div>
<br>
<div align="center">
    <img src="img/contribuitors.png" alt="contribuitors.png" width="550px" height="300px">
</div>
<br>

## **5.3. Validation Interviews**
### **5.3.1. Diseño de Entrevistas**
### **5.3.2. Registro de Entrevistas**
### **5.3.3. Evaluaciones según heurísticas**


## Conclusiones

**TB1:**   
Desarrollar *Autonexo* como parte de nuestro trabajo en equipo nos permitió comprender de forma práctica cómo se aplica la ingeniería de software en contextos reales, especialmente dentro del desarrollo de soluciones para startups tecnológicas. Esta experiencia no solo fortaleció nuestros conocimientos técnicos en modelado, diseño orientado al dominio y arquitectura de sistemas, sino que también nos permitió entender la importancia de una buena comunicación entre miembros del equipo y con los usuarios finales.
Aprendimos a identificar necesidades del negocio, transformarlas en requerimientos funcionales y traducirlas en componentes de software robustos y escalables. Además, reforzamos habilidades clave en metodologías ágiles, análisis de sistemas, pensamiento crítico, y sobre todo, en cómo construir productos que realmente aporten valor. Este proyecto nos acercó a la realidad de nuestra carrera y nos motivó a seguir perfeccionando nuestras competencias como futuros ingenieros de software.
<br>
**TB2:**
<br>
Durante el TB2, profundizamos en la construcción de Autonexo mediante el diseño e implementación del frontend de la aplicación, lo que nos permitió aplicar conocimientos técnicos en experiencia de usuario, componentes visuales y validación de interfaces. Esta etapa fue clave para fortalecer nuestra capacidad de traducir requerimientos en soluciones tangibles y funcionales. A través del levantamiento de observaciones y la mejora continua del diseño, aprendimos a iterar con base en retroalimentación efectiva, manteniendo siempre una comunicación clara y documentada entre los miembros del equipo. Asimismo, consolidamos nuestras habilidades en trabajo colaborativo, priorización de tareas y control de versiones, pilares esenciales en el desarrollo ágil de software. TB2 nos dio una visión más completa del proceso de desarrollo y reforzó nuestro compromiso con la creación de productos tecnológicos que respondan a necesidades reales del entorno.
## Bibliografía
Innocar & Roshfrans. (2024, junio 8). _Solo el 23.5% de los talleres mecánicos en América Latina utiliza software especializado para gestionar sus operaciones_. La República. https://www.larepublica.co/internet-economy/uso-de-tecnologia-en-talleres-mecanicos-en-colombia-3877209

## Anexos
