
<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" width="150" alt="UPC Logo">

# Universidad Peruana de Ciencias Aplicadas

### **CURSO:** Fundamentos de Arquitectura de Software

### **NRC**: 6342

### **Profesor:** Abel Nehemias Rosales Caururu

### **Ingeniería de software**

## Informe de Trabajo Final

### **Nombre del startup:** APX-4

### **Nombre del producto:** LearnHive

## **Integrantes**


| **Nombre**                                | **Código** |
|-------------------------------------------|------------|
| **Alejo Cardenas, Jose Antonio**             | U202122484 |
| **Real Calderon, Sebastian Omar**       | U20221D964 |
| **Luquillas Asto, Omar** | U20211G641 |
| **Olivera Barzola, Eric Marlon**          | U202315032  |
| **Aliaga Urbina, Wilder Gonzalo**            | U202222001 |


**Septiembre 2025**

## Registro de Versiones del Informe

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
      <td>0.1</td>
      <td>03/09/25</td>
      <td>Jose Alejo</td>
      <td>Elaboración de plantilla del reporte</td>
    </tr>
  </tbody>
</table>

# Contenido  

- [Student Outcome](#student-outcome) → Ver anexo A al final de este documento  

- [Capítulo I: Introducción](#capítulo-i-introducción)  
  - [1.1 Startup Profile](#11-startup-profile)  
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)  
    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  
  - [1.2 Solution Profile](#12-solution-profile)  
    - [1.2.1 Nombre del producto](#121-nombre-del-producto)  
    - [1.2.2 Antecedentes y problemática](#122-antecedentes-y-problemática)  
    - [1.2.3 Lean UX Process](#123-lean-ux-process)  
      - [1.2.3.1 Lean UX Problem Statement](#1231-lean-ux-problem-statement)  
      - [1.2.3.2 Lean UX Assumptions](#1232-lean-ux-assumptions)  
      - [1.2.3.3 Lean UX Hypothesis](#1233-lean-ux-hypothesis)  
      - [1.2.3.4 Lean UX Canvas](#1234-lean-ux-canvas)  
  - [1.3 Segmentos objetivo](#13-segmentos-objetivo)  

- [Capítulo II: Requirements & Analysis](#capítulo-ii-requirements--analysis)  
  - [2.1 Competidores](#21-competidores)  
  - [2.2 Entrevistas](#22-entrevistas)  
  - [2.3 Needfinding](#23-needfinding)  
    - [2.3.1 User Personas](#231-user-personas)  
    - [2.3.2 User Task Matrix](#232-user-task-matrix)  
    - [2.3.3 Empathy Maps](#233-empathy-maps)  
    - [2.3.4 As-is Scenario Mapping](#234-as-is-scenario-mapping)  

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)  
  - [3.1 To-Be Scenario Mapping](#31-to-be-scenario-mapping)  
  - [3.2 User Stories](#32-user-stories)  
  - [3.3 Impact Map](#33-impact-map)  
  - [3.4 Product Backlog (Avance1)](#34-product-backlog-avance1)  

- [Capítulo IV: Product Architecture Design](#capítulo-iv-product-architecture-design)  
  - [4.1 Design Concepts, ViewPoints & ER Diagrams](#41-design-concepts-viewpoints--er-diagrams)  
    - [4.1.1 Principles Statements](#411-principles-statements)  
    - [4.1.2 Approaches Statements Architectural Styles & Patterns](#412-approaches-statements-architectural-styles--patterns)  
    - [4.1.3 Context Diagram](#413-context-diagram)  
    - [4.1.4 Approach driven ViewPoints Diagrams](#414-approach-driven-viewpoints-diagrams)  
    - [4.1.5 Relational/Non Relational Database Diagram](#415-relationalnon-relational-database-diagram)  
    - [4.1.6 Design Patterns](#416-design-patterns)  
    - [4.1.7 Tactics](#417-tactics)  
  - [4.2 Architectural Drivers](#42-architectural-drivers)  
    - [4.2.1 Design Purpose](#421-design-purpose)  
    - [4.2.2 Primary Functionality (Primary User Stories)](#422-primary-functionality-primary-user-stories)  
    - [4.2.3 Quality Attribute Scenarios](#423-quality-attribute-scenarios)  
    - [4.2.4 Constraints](#424-constraints)  
    - [4.2.5 Architectural Concerns](#425-architectural-concerns)  
  - [4.3 ADD Iterations](#43-add-iterations)  
    - [4.3.X Iteration N: <Iteration Name>](#43x-iteration-n-iteration-name)  
      - [4.3.X.1 Architectural Design Backlog N](#43x1-architectural-design-backlog-n)  
      - [4.3.X.2 Establish Iteration Goal by Selecting Drivers](#43x2-establish-iteration-goal-by-selecting-drivers)  
      - [4.3.X.3 Choose Elements to Refine](#43x3-choose-elements-to-refine)  
      - [4.3.X.4 Choose Design Concepts That Satisfy Drivers](#43x4-choose-design-concepts-that-satisfy-drivers)  
      - [4.3.X.5 Instantiate Elements, Allocate Responsibilities & Define Interfaces](#43x5-instantiate-elements-allocate-responsibilities--define-interfaces)  
      - [4.3.X.6 Sketch Views (C4 & UML) and Record Design Decisions](#43x6-sketch-views-c4--uml-and-record-design-decisions)  
      - [4.3.X.7 Analysis & Review (Kanban Board) (Avance 2)](#43x7-analysis--review-kanban-board-avance-2)  

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)  
  - [5.1 Testing Suites & General Patterns](#51-testing-suites--general-patterns)  
    - [5.1.1 Backend Application Core Testing Suite](#511-backend-application-core-testing-suite)  
    - [5.1.2 Pattern Based Backend Application(s)](#512-pattern-based-backend-applications)  
    - [5.1.3 Pattern Based Custom Software Library](#513-pattern-based-custom-software-library)  
    - [5.1.4 Framework Pattern Driven Refactoring Report](#514-framework-pattern-driven-refactoring-report)  
  - [5.2 Software Configuration Management](#52-software-configuration-management)  
    - [5.2.1 Software Development Environment Configuration](#521-software-development-environment-configuration)  
    - [5.2.2 Source Code Management](#522-source-code-management)  
    - [5.2.3 Source Code Style Guide & Conventions](#523-source-code-style-guide--conventions)  
    - [5.2.4 Software Deployment Configuration](#524-software-deployment-configuration)  
  - [5.3 Microservices Implementation](#53-microservices-implementation)  
    - [Sprint 1 (TP1)](#sprint-1-tp1)  
    - [Sprint 2 (Avance 3)](#sprint-2-avance-3)  
    - [Sprint 3 (Avance 4)](#sprint-3-avance-4)  
    - [Sprint 4](#sprint-4)  
  - [5.4 Microservices Deployment](#54-microservices-deployment)  
    - [5.4.1 Cloud Architecture Diagram](#541-cloud-architecture-diagram)  
    - [5.4.2 Cloud Architecture Deployment (AWS, Azure o GCP)](#542-cloud-architecture-deployment-aws-azure-o-gcp)  

- [Conclusiones](#conclusiones)  
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)  
  - [Video About-The-Team](#video-about-the-team)  

- [Referencias Bibliográficas](#referencias-bibliográficas)  

- [Anexos](#anexos)  
  
- [Links](#links)  

# Student Outcome

| Criterio específico | Acciones realizadas | Conclusiones |
|----------------------|---------------------|--------------|
| **Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.** | **Alejo Cardenas, Jose Antonio**<br>TB1: AAA…<br>TB2: BBB…<br>**Real Calderon, Sebastian Omar**<br>TB1: AAA…<br>**Luquillas Asto, Omar**<br>TB1: AAA…<br><br>**Olivera Barzola, Eric Marlon**<br>TB1: AAA…<br><br>**Aliaga Urbina, Wilder Gonzalo**<br>TB1: AAA…<br> | AAA… |
| **Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.** | **Alejo Cardenas, Jose Antonio**<br>TB1: BBB…<br>TB2: BBB…<br>**Real Calderon, Sebastian Omar**<br>TB1: BBB…<br>**Luquillas Asto, Omar**<br>TB1: BBB…<br><br>**Olivera Barzola, Eric Marlon**<br>TB1: BBB…<br><br>**Aliaga Urbina, Wilder Gonzalo**<br>TB1: BBB…<br> | BBB... |


# Capítulo I: Introducción

## 1.1 Startup Profile

### 1.1.1 Descripción de la Startup

APX-4 es una startup iniciada por estudiantes de la Universidad Peruana de Ciencias Aplicadas con el objetivo de desarrollar soluciones tecnológicas para el ámbito educativo del Perú. Con nuestro producto principal, LearnHive, queremos ofrecer una alternativa de entorno digital para institutos académicos que no cuentan con una plataforma propia, ofreciéndoles las herramientas para el desarrollo de sus actividades de forma rápida, fácil y segura.

### 1.1.2 Perfiles de integrantes del equipo

<table>
  <tr>
    <th colspan="2"> Jose Antonio Alejo Cardenas </th>
  </tr>
  <tr>
    <td> <img src="images/chapter-1/jose-pfp.jpg" alt="Jose Alejo" style="width: 500px; height: auto;"> </td>
    <td> Soy José Alejo Cárdenas, estudiante de la carrera de Ingeniería de Software del séptimo ciclo. Desde pequeño he sentido facinacion por la tecnologia en general sobretodo por el funcionamiento, desarrollo y proteccion del software en el ambito de ciberseguridad. He estudiado lenguajes de programacion (javascript, python y C++), bases de datos (Microsoft SQL Server y Mongo DB) y Sistemas Operativos (Kali Linux y Windows). Asi mismo, tengo experiencia con hardware a nivel de esamblamiento de equipos y funcionamiento del mismo con sus especificaciones tecnicas. Además, mi constante comunicacion y organizacion durante cualquier trabajo grupal aportara mucho dinamismo al proyecto. Mis principales hobbies son entrenar en el gimnasio, jugar videojuegos con mis amigos y salir a conversar con estos ultimos durante algun almuerzo o cena. Para el proyecto aportare organizacion, comunicacion e inspiracion durante todo el transcurso del mismo. </td>
  </tr>
  <tr>
    <th colspan="2"> Sebastián Omar Real Calderón </th>
  </tr>
  <tr>
    <td> <img src="images/chapter-1/sebastian-pfp.jpeg" alt="Sebastian Real" style="width: 500px; height: auto;"> </td>
    <td> Soy Sebastián Real Calderón, estudiante de Ingeniería de Software. Tengo conocimiento de diferentes lenguajes de programación, como C#, C++ y Java. Mi mayor objetivo al desarrollar software es crear una experiencia de usuario con la que los consumidores puedan sentirse satisfechos al trabajar con nuestras aplicaciones. Asimismo, aspiro a ser un buen participante al mantener una comunicación constante con mis compañeros, resolviendo problemas y apoyándo a quién lo necesite para crear un ambiente cómodo para todos. </td>
  </tr>
  <tr>
    <th colspan="2"> Omar Luquillas Asto </th>
  </tr>
  <tr>
    <td> <img src="images/chapter-1/omar-pfp.jpg" alt="Omar Luquillas" style="width: 500px; height: auto;"> </td>
    <td> Soy Omar Luquillas Asto, estudiante de la carrera de Ingeniería de Software. Elegí esta carrera porque me apasiona la tecnología, el desarrollo de software y la programación. Tengo conocimientos en lenguajes de programación como C++, Python y Java. Me considero una persona investigadora, ya que me gusta aprender cosas nuevas y siempre estoy en busca de soluciones creativas e innovadoras que generen un impacto positivo en la vida de las personas. Además, valoro el trabajo en equipo, soy responsable y me comprometo a cumplir con mis tareas de manera eficiente. </td>
  </tr>
  <tr>
    <th colspan="2">-</th>
  </tr>
  <tr>
    <td> <img src="images/chapter-1/" alt="" style="width: 500px; height: auto;"> </td>
    <td>  </td>
  </tr>
  <tr>
    <th colspan="2">-</th>
  </tr>
  <tr>
    <td> <img src="images/chapter-1/" alt="" style="width: 500px; height: auto;"> </td>
    <td>  </td>
  </tr>
</table>

## 1.2 Solution Profile
### 1.2.1 Nombre del producto

El producto desarrollado se denomina LearnHive. LearnHive busca ofrecer una herramienta digital integral que facilite la gestión de grupos, actividades y métricas de desempeño estudiantil, adaptándose a las necesidades de docentes y estudiantes en entornos que carecen de plataformas propias de gestión académica.

### 1.2.2 Antecedentes y problemática

**1. What / ¿QUÉ?**
- ¿Cuál es el problema que se está presentando?

El problema es que los institutos académicos de Lima carecen de plataformas educativas propias que resuelvan eficientemente la gestión de grupos de estudio, la organización de tareas y el seguimiento del rendimiento estudiantil.

**2. When / ¿CUÁNDO?**
- ¿Cuándo estamos viendo el problema?

El problema se presenta durante los periodos académicos regulares, especialmente en las etapas de proyectos grupales, asignación de tareas y evaluaciones parciales.

- ¿En qué momento del día o del proceso en cuestión?

Sucede principalmente en las semanas previas a entregas y evaluaciones, cuando la necesidad de organización y coordinación entre docentes y estudiantes es más alta.

**3. Where / ¿DÓNDE?**

- ¿Dónde estamos viendo los problemas?

Estamos viendo los problemas en institutos académicos de Lima que no cuentan con plataformas propias de gestión educativa.

- ¿En qué parte del proceso estamos viendo el problema?

El problema aparece en la organización, asignación de tareas y seguimiento académico, donde las herramientas informales (como correo electrónico o grupos de mensajería) no permiten una coordinación efectiva.

**4. Who / ¿QUIÉN?**

- ¿A quién le sucede?

Este problema afecta principalmente a los estudiantes de institutos, quienes enfrentan dificultades para coordinarse y entregar tareas de manera ordenada; a los docentes, que deben asumir una carga adicional al organizar actividades y revisar entregas sin contar con un sistema centralizado; y a los institutos académicos, que carecen de métricas claras sobre la participación y el desempeño de sus estudiantes.

- ¿El problema está relacionado con las habilidades de las personas?

No está directamente relacionado con las habilidades, sino con la falta de herramientas digitales adecuadas para su contexto.

**5. Why / ¿POR QUÉ?**

- ¿Por qué sucede el problema?

Porque las plataformas actuales (ej. Google Classroom, Blackboard) están enfocadas en universidades o colegios con mayores recursos tecnológicos y no contemplan las necesidades específicas de los institutos académicos, como la simplicidad, la creación ágil de grupos con códigos de ingreso o la disponibilidad de métricas personalizadas.

**6. How / ¿CÓMO?**

- ¿Cómo se diferencia el problema del estado normal (óptimo)?

En un estado óptimo, los estudiantes y docentes deberían gestionar grupos, tareas y métricas desde una única plataforma sencilla y adaptada a sus necesidades. Actualmente, deben recurrir a múltiples aplicaciones externas, lo que genera desorganización, duplicidad de esfuerzos y pérdida de información.

- ¿La tendencia en la que aparece el problema es aleatoria o sigue un patrón?

Sigue un patrón claro: aparece en cada ciclo académico, especialmente cuando se requiere colaboración grupal o evaluaciones conjuntas.

**7. How Much / ¿CUÁNTO?**

- ¿Cuántos problemas se dan en un día, una semana o un mes?

Cada grupo de estudiantes puede enfrentar problemas de coordinación varias veces por semana, en especial en las semanas de entregas o evaluaciones.

- ¿Cuánto dinero están implicando?

Aunque no existe un gasto monetario directo, los institutos podrían optimizar hasta un 30% del tiempo de gestión docente y reducir significativamente los problemas de coordinación si contaran con una plataforma como LearnHive.

### 1.2.3 Lean UX Process

El Lean UX Process es una metodología de diseño centrada en el usuario que busca trabajar de forma práctica y ágil. Su enfoque se basa en realizar ciclos cortos de creación, prueba y mejora, lo que permite validar rápidamente si una idea realmente responde a las necesidades de los usuarios. A diferencia de los métodos tradicionales que requieren mucha documentación, Lean UX da más importancia a la retroalimentación constante y al trabajo en equipo, asegurando que el producto evolucione de acuerdo con la experiencia real de los estudiantes y docentes. De esta forma, se pueden identificar y corregir fallas a tiempo, evitando desperdicio de recursos y garantizando una solución más cercana a lo que el usuario necesita.

#### 1.2.3.1 Lean UX Problem Statement

Nuestra plataforma tiene como propósito optimizar la gestión académica y la interacción entre estudiantes y docentes de institutos en un único espacio digital. Hemos detectado que gran parte de los usuarios continúa utilizando herramientas aisladas y poco integradas, como WhatsApp, correo electrónico o carpetas en la nube, lo que complica la organización de grupos, asignaciones y entregas. Este escenario provoca desorden, desperdicio de tiempo y una comunicación menos efectiva, afectando en el desempeño de los estudiantes y aumentando la carga administrativa de los docentes. ¿Cómo podemos mejorar nuestra solución para que los estudiantes y docentes de institutos coordinen sus actividades académicas de forma más ágil, evaluando el éxito mediante una mayor participación en los grupos, un mejor cumplimiento de las tareas y una reducción del tiempo dedicado a la organización?

#### 1.2.3.2 Lean UX Assumptions
#### 1.2.3.3 Lean UX Hypothesis
#### 1.2.3.4 Lean UX Canvas

## 1.3 Segmentos objetivo



# Capítulo II: Requirements & Analysis

## 2.1 Competidores
## 2.2 Entrevistas
## 2.3 Needfinding
### 2.3.1 User Personas
### 2.3.2 User Task Matrix
### 2.3.3 Empathy Maps
### 2.3.4 As-is Scenario Mapping



# Capítulo III: Requirements Specification

## 3.1 To-Be Scenario Mapping
## 3.2 User Stories
## 3.3 Impact Map
## 3.4 Product Backlog (Avance1)



# Capítulo IV: Product Architecture Design

## 4.1 Design Concepts, ViewPoints & ER Diagrams
### 4.1.1 Principles Statements
### 4.1.2 Approaches Statements Architectural Styles & Patterns
### 4.1.3 Context Diagram
### 4.1.4 Approach driven ViewPoints Diagrams
### 4.1.5 Relational/Non Relational Database Diagram
### 4.1.6 Design Patterns
### 4.1.7 Tactics

## 4.2 Architectural Drivers
### 4.2.1 Design Purpose
### 4.2.2 Primary Functionality (Primary User Stories)
### 4.2.3 Quality Attribute Scenarios
### 4.2.4 Constraints
### 4.2.5 Architectural Concerns

## 4.3 ADD Iterations
### 4.3.X Iteration N: <Iteration Name>
#### 4.3.X.1 Architectural Design Backlog N
#### 4.3.X.2 Establish Iteration Goal by Selecting Drivers
#### 4.3.X.3 Choose Elements to Refine
#### 4.3.X.4 Choose Design Concepts That Satisfy Drivers
#### 4.3.X.5 Instantiate Elements, Allocate Responsibilities & Define Interfaces
#### 4.3.X.6 Sketch Views (C4 & UML) and Record Design Decisions
#### 4.3.X.7 Analysis & Review (Kanban Board) (Avance 2)


# Capítulo V: Product Implementation, Validation & Deployment

## 5.1 Testing Suites & General Patterns
### 5.1.1 Backend Application Core Testing Suite
### 5.1.2 Pattern Based Backend Application(s)
### 5.1.3 Pattern Based Custom Software Library
### 5.1.4 Framework Pattern Driven Refactoring Report

## 5.2 Software Configuration Management
### 5.2.1 Software Development Environment Configuration
### 5.2.2 Source Code Management
### 5.2.3 Source Code Style Guide & Conventions
### 5.2.4 Software Deployment Configuration

## 5.3 Microservices Implementation

### Sprint 1 (TP1)
#### 5.3.1.1 Sprint Backlog 1
#### 5.3.1.2 Development Evidence for Sprint Review
#### 5.3.1.3 Testing Suite Evidence for Sprint Review
#### 5.3.1.4 Execution Evidence for Sprint Review
#### 5.3.1.5 Microservices Documentation Evidence for Sprint Review
#### 5.3.1.6 Software Deployment Evidence for Sprint Review
#### 5.3.1.7 Team Collaboration Insights during Sprint
#### 5.3.1.8 Kanban Board

### Sprint 2 (Avance 3)
#### 5.3.2.1 Sprint Backlog 2
#### 5.3.2.2 Development Evidence for Sprint Review
#### 5.3.2.3 Testing Suite Evidence for Sprint Review
#### 5.3.2.4 Execution Evidence for Sprint Review
#### 5.3.2.5 Microservices Documentation Evidence for Sprint Review
#### 5.3.2.6 Software Deployment Evidence for Sprint Review
#### 5.3.2.7 Team Collaboration Insights during Sprint
#### 5.3.2.8 Kanban Board

### Sprint 3 (Avance 4)
#### 5.3.3.1 Sprint Backlog 3
#### 5.3.3.2 Development Evidence for Sprint Review
#### 5.3.3.3 Testing Suite Evidence for Sprint Review
#### 5.3.3.4 Execution Evidence for Sprint Review
#### 5.3.3.5 Microservices Documentation Evidence for Sprint Review
#### 5.3.3.6 Software Deployment Evidence for Sprint Review
#### 5.3.3.7 Team Collaboration Insights during Sprint
#### 5.3.3.8 Kanban Board

### Sprint 4
#### 5.3.4.1 Sprint Backlog 4
#### 5.3.4.2 Development Evidence for Sprint Review
#### 5.3.4.3 Testing Suite Evidence for Sprint Review
#### 5.3.4.4 Execution Evidence for Sprint Review
#### 5.3.4.5 Microservices Documentation Evidence for Sprint Review
#### 5.3.4.6 Software Deployment Evidence for Sprint Review
#### 5.3.4.7 Team Collaboration Insights during Sprint
#### 5.3.4.8 Kanban Board

## 5.4 Microservices Deployment
### 5.4.1 Cloud Architecture Diagram
### 5.4.2 Cloud Architecture Deployment (AWS, Microsoft Azure o Google Cloud) → TF1



# Conclusiones
## Conclusiones y recomendaciones
## Video About-The-Team



# Referencias Bibliográficas



# Anexos
# Links
