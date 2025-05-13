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

### **1.1.2. Perfiles de integrantes del equipo**

## **1.2. Solution Profile**

### **1.2.1. Antecedentes y problemática**

### **1.2.2. Lean UX Process**

#### **1.2.2.1. Lean UX Problem Statements**

#### **1.2.2.2. Lean UX Assumptions**

#### **1.2.2.3. Lean UX Hypothesis Statements**

#### **1.2.2.4. Lean UX Canvas**

## **1.3. Segmentos objetivo**

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

En esta sección describiremos las herramienas de software que utilizamos para el ciclo de vida del proyecto.   

**Project Management:**   
- Producto: Trello
- Propósito: Seguimiento del progreso de funcionalidades y gestión de tareas
- Ruta: https://trello.com/es

<div>
    <img src="unknown" alt="project-management.png" width="150px" height="100px">
</div>

**Product UX/UI Design:**
- Producto: Figma
- Propósito: Diseños del Proyecto (Wireframes, Mock-Ups, etc)
- Ruta: https://www.figma.com/es-es/

<div>
    <img src="unknown" alt="product-ux-ui-design.png" width="150px" height="100px">
</div>

**Software Development:**
- Producto: Visual Studio Code
- Propósito: Desarrollo del Landing Page
- Ruta: https://code.visualstudio.com

<div>
    <img src="unknown" alt="software-development.png" width="150px" height="100px">
</div>

**Software Documentation:**
- Producto: Visual Studio Code
- Propósito: Para redactar los capítulos en formato Markdown
- Ruta: https://code.visualstudio.com

<div>
    <img src="unknown" alt="software-documentation.png" width="150px" height="100px">
</div>

**Software Deployment:**
- Producto: GitHub
- Propósito: Repositorio del Proyecto y gestión de versiones
- Ruta: https://github.com

<div>
    <img src="unknown" alt="software-deployment.png" width="150px" height="100px">
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

<div>
    <img src="unknown" alt="sprint-backlog-trello.png" width="150px" height="100px">
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

<div>
    <img src="unknown" alt="home-section.png" width="150px" height="100px">
</div>

- **Sección Servicios:** En esta sección, el usuario puede enterarse del funcionamiento de nuestro producto a través de un video informativo y una pequeña guía de cómo registrarse.

<div>
    <img src="unknown" alt="service-section.png" width="150px" height="100px">
</div>

- **Sección Precios:** En esta sección, ofrecemos al usuario diferentes planes en los que se puede suscribir.

<div>
    <img src="unknown" alt="prices-section.png" width="150px" height="100px">
</div>

- **Sección Testimonios:** En esta sección, el usuario puede ver testimonios de otras personas.

<div>
    <img src="unknown" alt="testimonies-section.png" width="150px" height="100px">
</div>

#### **5.2.1.6. Services Documentation Evidence for Sprint Review**

*Para este primer sprint no fue contemplada la evidencia de documentación de los servicios.*

#### **5.2.1.7. Software Deployment Evidence for Sprint Review**

Para la entrega del primer sprint, desplegamos el landing page en una versión temprana, la cual tiene unas cuantas funcionalidades sin implementar y bugs que, para las siguientes entregas, estarán completamente resueltas. He aquí la evidencia del despliegue:

<div>
    <img src="unknown" alt="deployment-evidence.png" width="150px" height="100px">
</div>

#### **5.2.1.8. Team Collaboration Insights during Sprint**

Aquí se muestra el insight que nos proporciona Github, en su propio apartado:

<div>
    <img src="unknown" alt="team-collaboration-insights.png" width="150px" height="100px">
</div>

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

**TB1:**   
Desarrollar *Autonexo* como parte de nuestro trabajo en equipo nos permitió comprender de forma práctica cómo se aplica la ingeniería de software en contextos reales, especialmente dentro del desarrollo de soluciones para startups tecnológicas. Esta experiencia no solo fortaleció nuestros conocimientos técnicos en modelado, diseño orientado al dominio y arquitectura de sistemas, sino que también nos permitió entender la importancia de una buena comunicación entre miembros del equipo y con los usuarios finales.
Aprendimos a identificar necesidades del negocio, transformarlas en requerimientos funcionales y traducirlas en componentes de software robustos y escalables. Además, reforzamos habilidades clave en metodologías ágiles, análisis de sistemas, pensamiento crítico, y sobre todo, en cómo construir productos que realmente aporten valor. Este proyecto nos acercó a la realidad de nuestra carrera y nos motivó a seguir perfeccionando nuestras competencias como futuros ingenieros de software.

## Bibliografía

## Anexos
