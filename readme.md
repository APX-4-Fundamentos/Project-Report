
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

## 1.2 Solution Profile
### 1.2.1 Nombre del producto
### 1.2.2 Antecedentes y problemática
### 1.2.3 Lean UX Process
#### 1.2.3.1 Lean UX Problem Statement
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
**Segmento Objetivo 1: Estudiantes de institutos**

El To-Be Scenario Mapping de estudiantes muestra cómo LearnHive centraliza materiales, tareas y métricas en un único espacio. Esto elimina la dispersión de canales y reduce la inseguridad en las entregas, ofreciendo confirmación inmediata y dashboards visuales con retroalimentación en tiempo real. El resultado esperado es mayor tranquilidad, motivación y confianza en la gestión de su desempeño académico.


![to-be_estudiantes.png](assets/to-be_scenariomapping/to-be_estudiantes.png)

**Segmento Objetivo 2: Profesores de Institutos**

El To-Be Scenario Mapping de profesores de instituto plantea un futuro en el que LearnHive simplifica la planificación, automatiza parte de la retroalimentación y centraliza la comunicación con los estudiantes. De esta manera, los docentes reducen su carga administrativa, obtienen métricas claras para intervenir oportunamente y sienten alivio, satisfacción y motivación al enfocarse más en la enseñanza que en las tareas manuales.

![to-be_profesores.png](assets/to-be_scenariomapping/to-be_profesores.png)

## 3.2 User Stories

**Epics:**

<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Título</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>EP-001</td>
      <td>Gestión de Grupos</td>
      <td>Esta épica se enfoca en ofrecer a profesores y estudiantes una forma sencilla y estructurada de crear y administrar grupos académicos. El docente tiene la capacidad de formar equipos, asignar integrantes y mantener un control organizado sobre su composición. Los estudiantes, por su parte, cuentan con un espacio definido para integrarse a sus grupos de trabajo, lo que fomenta la colaboración y la coordinación en sus actividades académicas.</td>
    </tr>
    <tr>
      <td>EP-002</td>
      <td>Gestión de trabajos y entregas</td>
      <td>Esta épica se enfoca en las funcionalidades orientadas a la creación de trabajos académicos para cada grupo, y el recibimiento de entregas, así como la calificación de estas. Por parte de los estudiantes, estos deben poder visualizar sus trabajos pendientes tanto en el menú de un grupo específico como en un menú especializado general que les muestre sus fechas de entrega más cercanas. Por el lado de los profesores, estos deben poder crear trabajos con fechas límite, administrar su visualización y acceder a las entregas de sus alumnos, así como calificarlas y dejar mensajes de retroalimentación.</td>
    </tr>
    <tr>
      <td>EP-003</td>
      <td>Seguimiento de progreso y retroalimentación automatizada</td>
      <td>Esta épica se centra en ofrecer funcionalidades que permitan a estudiantes y profesores acceder a datos en tiempo real sobre el rendimiento académico. Los estudiantes podrán visualizar sus calificaciones, avances y métricas comparativas mediante dashboards gráficos, lo que les permitirá identificar fortalezas, debilidades y áreas de mejora. Además, contarán con retroalimentación automatizada e instantánea, generada a partir de sus entregas y participación, para orientar su aprendizaje de manera continua. Por el lado de los profesores, estos podrán monitorear tanto las métricas individuales de cada estudiante como el desempeño general del grupo, identificando patrones y detectando a tiempo las dificultades más comunes.</td>
    </tr>
    <tr>
      <td>EP-004</td>
      <td>Comunicación, interacción y recursos educativos dinámicos entre usuarios</td>
      <td>Esta épica se orienta al intercambio de información y la creación de espacios de interacción dentro de la plataforma. Los profesores podrán publicar anuncios dirigidos a todo el grupo, en los cuales los alumnos podrán dejar comentarios, consultas o dudas que serán respondidas en el mismo hilo. Tanto docentes como estudiantes recibirán notificaciones automáticas que les mantendrán al tanto de las respuestas e interacciones. Asimismo, los alumnos tendrán la posibilidad de enviarse mensajes privados para coordinar actividades académicas de manera ágil. Como valor agregado, la épica incorpora la posibilidad de compartir recursos educativos interactivos tales como videos cortos, imágenes y materiales en tiempo real, lo que no solo mejora la comunicación, sino que también hace más atractivo y participativo el proceso de aprendizaje.</td>
    </tr>
    <tr>
      <td>EP-005</td>
      <td>Diseño de la landing page</td>
      <td>Como equipo de desarrollo, queremos diseñar y construir una landing page atractiva, informativa y fácil de navegar, que comunique claramente el valor de la plataforma tanto para motociclistas como para mecánicos, con el objetivo de captar nuevos usuarios, generar confianza y facilitar el registro en el sistema.</td>
    </tr>
    <tr>
      <td>EP-006</td>
      <td>Infraestructura técnica, escalabilidad y calidad del sistema</td>
      <td>Esta épica se enfoca en las tareas técnicas necesarias para asegurar el correcto funcionamiento de la plataforma desde el punto de vista tecnológico. Incluye configuraciones de backend, frontend, infraestructura y pruebas automatizadas, que no son visibles directamente para el usuario final pero que resultan fundamentales para garantizar seguridad, rendimiento, estabilidad, escalabilidad y mantenibilidad en el tiempo.</td>
    </tr>
  </tbody>
</table>

**User Stories:**

<table>
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>US-001</td>
      <td>Ingreso a grupos</td>
      <td>Como estudiante, quiero ser capaz de unirme a los grupos formados por mis profesores con facilidad.</td>
      <td>
        Escenario 1: Dado un estudiante en el menú de inicio de la plataforma con un código de grupo válido proporcionado por su profesor, cuando ingresa el código en el campo designado y selecciona la opción "Unirse al grupo", entonces el sistema valida el código, muestra un mensaje de confirmación exitosa y añade automáticamente al estudiante al grupo correspondiente. <br><br>
        Escenario 2: Dado un estudiante en el menú de inicio con una notificación de invitación pendiente para unirse a un grupo de clase, cuando selecciona la notificación y hace clic en el botón "Aceptar invitación", entonces el sistema confirma la aceptación, añade al estudiante al grupo y actualiza la lista de miembros visible para el profesor.</td>
      <td>EP-001</td>
    </tr>
    <tr>
      <td>US-002</td>
      <td>Creación de grupos</td>
      <td>Como profesor, quiero ser capaz de crear grupos para mis cursos en la plataforma.</td>
      <td>
        Escenario 1: Dado un profesor autenticado en la plataforma educativa, cuando selecciona la opción "Crear Nuevo Grupo" desde el menú principal, entonces el sistema despliega un formulario con campos para nombre del grupo, descripción, etc. Permitiendo la creación del grupo tras completar los datos obligatorios.<br><br>
        Escenario 2: Dado un profesor en el proceso de creación de un nuevo grupo, cuando ingresa un nombre idéntico al de un grupo preexistente bajo su misma cuenta y intenta guardar, entonces el sistema detecta la duplicación, muestra un mensaje de error "Nombre de grupo ya existente" y sugiere modificar el nombre o recuperar el grupo existente.
      </td>
      <td>EP-001</td>
    </tr>
    <tr>
      <td>US-003</td>
      <td>Invitación a grupos</td>
      <td>Como profesor, quiero ser capaz de invitar a mis alumnos a los grupos creados por mí.</td>
      <td>
        Escenario 1: Dado un grupo creado por un profesor con un código de invitación generado, cuando un estudiante ingresa correctamente el código en la plataforma, entonces el sistema añade al estudiante al grupo, registra la acción y envía una notificación automática al profesor confirmando la incorporación del nuevo miembro.<br><br>
        Escenario 2: Dado un profesor en la sección de gestión de un grupo específico, cuando ingresa los IDs o correos electrónicos de los estudiantes en el campo de invitaciones y selecciona "Enviar invitaciones", entonces el sistema envía notificaciones individuales a cada estudiante con un enlace directo para unirse al grupo y actualiza el estado de invitaciones pendientes.<br><br>
        Escenario 3: Dado un estudiante que recibe una invitación para unirse a un grupo, cuando hace clic en el enlace de la notificación o ingresa manualmente el código proporcionado, entonces el sistema verifica la validez de la invitación, añade al estudiante al grupo correspondiente y notifica al profesor sobre la aceptación exitosa de la invitación.
      </td>
      <td>EP-001</td>
    </tr>
    <tr>
      <td>US-004</td>
      <td>Eliminación de alumnos</td>
      <td>Como profesor, quiero ser capaz de eliminar integrantes del grupo, para mantener un orden y corregir errores en caso de invitar a alguien por equivocación.</td>
      <td>
        Escenario 1: Dado un profesor en la pantalla de gestión de integrantes de un grupo activo, cuando selecciona la opción "Eliminar" junto al nombre de un estudiante y confirma la acción en el cuadro de diálogo emergente, entonces el sistema remueve al estudiante del grupo, actualiza la lista de miembros y envía una notificación automática al estudiante informando sobre su eliminación del grupo.<br><br>
        Escenario 2: Dado un profesor intentando eliminar a un estudiante que ya ha sido removido previamente del grupo o cuya cuenta ya no existe, cuando confirma la acción de eliminación, entonces el sistema detecta que el estudiante no pertenece al grupo y muestra un mensaje de error: "El estudiante especificado no pertenece a este grupo o ya ha sido eliminado".
      </td>
      <td>EP-001</td>
    </tr>
    <tr>
      <td>US-005</td>
      <td>Creación de trabajos con fechas límite</td>
      <td>Como profesor, quiero crear trabajos dentro de cada curso con sus respectivas fechas de entrega, para organizar las actividades académicas y dar claridad a mis estudiantes.</td>
      <td>
        Escenario 1: Dado un profesor en la página de administración de un curso específico, cuando selecciona la opción "Crear trabajo", completa los campos obligatorios (título, descripción, fecha límite) y confirma la creación, entonces el sistema guarda el trabajo en la base de datos, lo muestra en la lista de actividades del curso y notifica a todos los estudiantes del grupo sobre la nueva tarea asignada.<br><br>
        Escenario 2: Dado un profesor en el proceso de creación de un nuevo trabajo para el curso, cuando ingresa una fecha límite anterior a la fecha actual y intenta guardar, entonces el sistema detecta la incongruencia, muestra un mensaje de error "La fecha de entrega debe ser futura" y resalta el campo de fecha en rojo hasta que se corrija.
      </td>
      <td>EP-002</td>
    </tr>
    <tr>
      <td>US-006</td>
      <td>Recepción de entregas (múltiples oportunidades)</td>
      <td>Como estudiante, quiero poder enviar y reenviar mis entregas en un trabajo académico, para corregir errores y mejorar mi calificación antes de la fecha límite.</td>
      <td>
        Escenario 1: Dado un estudiante con acceso a un trabajo académico dentro del plazo de entrega establecido, cuando selecciona la opción "Subir entrega", adjunta el archivo correspondiente y confirma el envío, entonces el sistema registra la entrega con marca de tiempo, envía una confirmación al estudiante y notifica al profesor sobre la nueva entrega recibida.<br><br>
        Escenario 2: Dado un estudiante que ya ha realizado una entrega previa para un trabajo académico, cuando selecciona "Reemplazar entrega" antes de la fecha límite y sube un nuevo archivo, entonces el sistema guarda la nueva versión, mantiene un historial de todas las entregas realizadas y actualiza la marca de tiempo de la última modificación.<br><br>
        Escenario 3: Dado un estudiante intentando enviar una entrega después de la fecha límite establecida, cuando intenta subir un archivo pasado el plazo, entonces el sistema rechaza la entrega, muestra un mensaje claro indicando "Plazo de entrega vencido" y sugiere contactar al profesor.
      </td>
      <td>EP-002</td>
    </tr>
    <tr>
      <td>US-007</td>
      <td>Visualización de trabajos y fechas</td>
      <td>Como estudiante, quiero visualizar en un dashboard todos mis trabajos y fechas de entrega, para organizar mis actividades y priorizar las más urgentes.</td>
      <td>
        Escenario 1: Dado un estudiante en la página principal de un curso específico, cuando navega a la pestaña "Trabajos", entonces el sistema muestra una lista completa de todas las tareas asignadas, con indicadores visuales de estado (pendiente/entregado/calificado), fechas límite claramente visibles y porcentaje de completitud para cada trabajo.<br><br>
        Escenario 2: Dado un estudiante en su dashboard principal, cuando accede a la sección "Próximas entregas", entonces el sistema muestra una lista consolidada de todos los trabajos pendientes de todos sus cursos, ordenados por fecha límite ascendente (los más urgentes primero), con recordatorios visuales para las tareas con vencimiento en las próximas 48 horas.<br><br>
        Escenario 3: Dado un trabajo académico con fecha límite próxima (menos de 24 horas), cuando el estudiante visualiza su dashboard, entonces el sistema resalta esa tarea con color rojo, muestra una alerta de "Entrega próxima" y ofrece la opción de acceso directo a la página de entrega con un solo clic.
      </td>
      <td>EP-002</td>
    </tr>
    <tr>
      <td>US-008</td>
      <td>Visualización de dashboard de progreso académico</td>
      <td>Como estudiante, quiero visualizar un dashboard con mis calificaciones y progreso en tiempo real, para saber si estoy avanzando de manera adecuada en mis cursos.</td>
      <td>
        Escenario 1: Dado un estudiante con sesión activa en la plataforma educativa, cuando accede a la sección "Mi Progreso" desde el menú principal, entonces el sistema muestra un dashboard interactivo con gráficos de calificaciones por curso, porcentaje de completitud de cada materia, comparativa con el promedio del grupo y proyección de calificación final basada en el rendimiento actual.<br><br>
        Escenario 2: Dado un profesor que ha calificado y publicado nuevos trabajos o exámenes en el sistema, cuando el estudiante recarga su dashboard de progreso, entonces el sistema actualiza automáticamente todas las métricas, muestra las nuevas calificaciones obtenidas con notificaciones de novedades y recalcula el promedio general y por curso en tiempo real.<br><br>
        Escenario 3: Dado un estudiante con calificaciones por debajo del promedio requerido en algún curso, cuando visualiza su dashboard de progreso, entonces el sistema destaca aquellas materias con bajo rendimiento usando indicadores de color.
      </td>
      <td>EP-003</td>
    </tr>
    <tr>
      <td>US-009</td>
      <td>Comparación del rendimiento con el promedio del grupo</td>
      <td>Como estudiante, quiero poder comparar mi rendimiento con el promedio de mis compañeros, para identificar si estoy por encima o debajo del nivel general.</td>
      <td>
        Escenario 1: Dado un estudiante en su dashboard académico principal, cuando selecciona la opción "Comparar con grupo" en cualquier curso, entonces el sistema genera un gráfico de barras comparativas que muestra sus calificaciones individuales junto al promedio del grupo en cada evaluación, con diferencias porcentuales claramente etiquetadas.<br><br>
        Escenario 2: Dado un estudiante en la sección de comparativa de rendimiento, cuando selecciona la opción "Evolución Temporal", entonces el sistema muestra una gráfica de líneas con su progreso histórico y el promedio del grupo a lo largo del semestre, permitiendo identificar tendencias y momentos clave de mejora o retroceso.
      </td>
      <td>EP-003</td>
    </tr>
    <tr>
      <td>US-010</td>
      <td>Visualización de métricas globales de desempeño del grupo</td>
      <td>Como profesor, quiero acceder a métricas globales del grupo, para entender el nivel de desempeño general de la clase.</td>
      <td>
        Escenario 1: Dado un profesor en la página de gestión de un grupo de estudiantes, cuando selecciona la opción "Métricas Globales", entonces el sistema muestra un panel con el promedio general de calificaciones, desviación estándar, tasa de entregas a tiempo, porcentaje de aprobación y comparativa con otros grupos del mismo curso.<br><br>
        Escenario 2: Dado un profesor analizando el rendimiento de su grupo, cuando selecciona un período específico (ej. primer parcial, último mes o trimestre), entonces el sistema genera gráficas de progreso colectivo que incluyen: curva de distribución de calificaciones, tendencia temporal del promedio grupal y heatmap de tasas de entrega por evaluación.
      </td>
      <td>EP-003</td>
    </tr>
    <tr>
      <td>US-011</td>
      <td>Alertas sobre estudiantes con bajo rendimiento</td>
      <td>Como profesor, quiero recibir alertas sobre estudiantes con bajo rendimiento, para poder intervenir de manera temprana.</td>
      <td>
        Escenario 1: Dado un estudiante con calificaciones consistentemente por debajo del 60% en un curso específico durante al menos tres evaluaciones consecutivas, cuando el sistema procesa los resultados académicos, entonces el profesor recibe una notificación con el nombre del estudiante, el curso afectado, las calificaciones específicas y sugerencias de intervención académica.<br><br>
        Escenario 2: Dado un estudiante que no ha entregado al menos dos tareas consecutivas dentro del plazo establecido, cuando el sistema analiza el historial de entregas, entonces genera una alerta automática para el profesor con el nombre del estudiante, las tareas pendientes y la opción de contactar directamente al estudiante desde la plataforma.
      </td>
      <td>EP-003</td>
    </tr>
    <tr>
      <td>US-012</td>
      <td>Recordatorios y notificaciones de entregas</td>
      <td>Como estudiante, quiero recibir notificaciones automáticas y recordatorios de próximas entregas para no olvidar subir mis trabajos a tiempo.</td>
      <td>
        Escenario 1: Dado un trabajo académico con fecha límite definida en el sistema, cuando faltan exactamente 48 y 12 horas para el vencimiento, entonces el sistema envía notificaciones automáticas al estudiante a través de la plataforma web y la aplicación móvil, incluyendo detalles específicos de la tarea y enlace directo para subirla.<br><br>
        Escenario 2: Dado un estudiante que ha completado el proceso de entrega de un trabajo, cuando el sistema verifica y almacena correctamente el archivo subido, entonces muestra una confirmación visual inmediata con número de comprobante, envía un acuse de recibo por correo electrónico y actualiza el estado de la tarea a "Entregado".
      </td>
      <td>EP-004</td>
    </tr>
    <tr>
      <td>US-013</td>
      <td>Reentrega controlada</td>
      <td>Como estudiante, quiero poder reentregar una tarea dentro de un plazo definido para mejorar mi nota según las reglas del curso.</td>
      <td>
        Escenario 1: Dado un trabajo académico configurado con reentregas permitidas por el profesor, cuando el estudiante sube una nueva versión del trabajo antes del plazo máximo de reentrega, entonces el sistema reemplaza automáticamente el archivo anterior, registra el nuevo envío en el historial de versiones y mantiene la marca de tiempo original de la primera entrega para fines de penalización por tardanza.<br><br>
        Escenario 2: Dado un estudiante intentando reentregar un trabajo después del plazo máximo permitido para revisiones, cuando intenta subir un nuevo archivo pasado el límite, entonces el sistema bloquea la acción, muestra un mensaje claro indicando "Plazo de reentrega vencido" y sugiere contactar al profesor para autorización excepcional.
      </td>
      <td>EP-002</td>
    </tr>
    <tr>
      <td>US-014</td>
      <td>Historial de calificaciones</td>
      <td>Como estudiante, quiero poder consultar el historial de calificaciones de mis entregas, para ver mi evolución académica en cada curso.</td>
      <td>
        Escenario 1: Dado un estudiante con múltiples calificaciones registradas en diferentes cursos, cuando accede a la sección "Historial de Calificaciones" desde su dashboard principal, entonces el sistema muestra una tabla completa con todas las notas obtenidas, organizadas por curso, fecha de evaluación, tipo de trabajo y porcentaje de valor en la nota final.<br><br>
        Escenario 2: Dado un estudiante visualizando su historial académico general, cuando selecciona un curso específico y aplica el filtro correspondiente, entonces el sistema muestra una gráfica de evolución temporal con sus calificaciones en ese curso, el promedio del grupo para cada evaluación y una línea de tendencia que visualiza su progreso académico a lo largo del tiempo.
      </td>
      <td>EP-002</td>
    </tr>
    <tr>
      <td>US-015</td>
      <td>Acceso a todas las entregas de un trabajo</td>
      <td>Como profesor, quiero acceder en una sola vista a todas las entregas de un trabajo, para agilizar la revisión y calificación.</td>
      <td>
        Escenario 1: Dado un profesor en la página de administración de un trabajo específico, cuando selecciona la pestaña "Entregas", entonces el sistema muestra una lista completa de todos los estudiantes del curso con sus respectivos estados de entrega (pendiente, enviado, calificado), marcas de tiempo de envío y archivos adjuntos descargables en un solo lugar.<br><br>
        Escenario 2: Dado un profesor revisando múltiples entregas de estudiantes, cuando aplica filtros específicos (solo pendientes, solo calificados, solo enviados sin calificar, por rango de fechas), entonces el sistema actualiza dinámicamente la vista mostrando exclusivamente las entregas que coinciden con los criterios seleccionados, facilitando la revisión por lotes.
      </td>
      <td>EP-002</td>
    </tr>
    <tr>
      <td>US-016</td>
      <td>Publicación de anuncios con comentarios</td>
      <td>Como profesor, quiero publicar anuncios en el curso y que los estudiantes puedan dejar comentarios, para mantener la comunicación centralizada y ordenada.</td>
      <td>
        Escenario 1: Dado un profesor en la página principal del curso, cuando crea un nuevo anuncio completando título, mensaje y configuraciones de visibilidad, y confirma la publicación, entonces el sistema publica el anuncio en el feed del curso, lo marca como prioritario en la parte superior de la lista y envía notificaciones push a todos los estudiantes del grupo.<br><br>
        Escenario 2: Dado un anuncio publicado con la opción de comentarios activada, cuando un estudiante escribe un comentario en el espacio designado y presiona "Enviar", entonces el sistema agrega el comentario al hilo de discusión mostrando nombre del autor, foto de perfil, marca de tiempo exacta y permite respuestas anidadas para mantener conversaciones organizadas.<br><br>
        Escenario 3: Dado un anuncio publicado hace menos de 30 minutos, cuando el profesor edita el contenido del anuncio o desactiva la opción de comentarios desde el menú de configuración, entonces el sistema actualiza el contenido mostrando la leyenda "Editado" con la hora de modificación y, en caso de cierre de comentarios, deshabilita el campo de texto para nuevos comentarios pero mantiene visibles los existentes.
      </td>
      <td>EP-004</td>
    </tr>
    <tr>
      <td>US-017</td>
      <td>Mensajería privada entre miembros</td>
      <td>Como estudiante, quiero enviar mensajes privados a mis compañeros y profesores, para coordinar actividades académicas de manera rápida y directa.</td>
      <td>
        Escenario 1: Dado un estudiante en la sección "Miembros del Curso" con la lista de participantes visibles, cuando selecciona a un compañero o profesor de la lista y envía un mensaje privado a través del botón de mensajería, entonces el sistema crea un hilo de conversación privado, almacena el mensaje en la base de datos y muestra una confirmación de envío exitoso al remitente.<br><br>
        Escenario 2: Dado un hilo de mensajes privados existente entre dos usuarios del mismo curso, cuando el destinatario abre la conversación para leer los mensajes nuevos, entonces el sistema actualiza inmediatamente el estado de los mensajes de "entregado" a "leído", muestra la marca de tiempo de lectura y notifica al remitente sobre el cambio de estado.<br><br>
        Escenario 3: Dado un estudiante intentando iniciar una conversación privada con un usuario que no pertenece a ninguno de sus cursos activos, cuando escribe un mensaje y intenta enviarlo, entonces el sistema bloquea el envío, muestra un mensaje de error claro: "Solo puede enviar mensajes a miembros de sus cursos" y sugiere verificar la lista de contactos disponibles dentro de cada curso.
      </td>
      <td>EP-004</td>
    </tr>
    <tr>
      <td>US-018</td>
      <td>Compartir recursos educativos</td>
      <td>Como profesor, quiero subir materiales de apoyo (documentos, videos, imágenes) al curso, para que los estudiantes los consulten fácilmente en cualquier momento.</td>
      <td>
        Escenario 1: Dado un profesor en la sección "Recursos del Curso" con materiales preparados para compartir, cuando selecciona "Subir nuevo recurso", completa los metadatos obligatorios (título, descripción, tipo de archivo) y confirma la acción, entonces el sistema almacena el archivo en el repositorio, lo categoriza automáticamente y lo publica inmediatamente para todos los estudiantes del curso con permisos de visualización y descarga.<br><br>
        Escenario 2: Dado un recurso educativo publicado en el repositorio del curso con acceso habilitado para estudiantes, cuando un estudiante accede a la sección de recursos y selecciona "Descargar" o "Visualizar" en cualquier material, entonces el sistema permite la acción requerida y registra en el log de actividad el nombre del estudiante, el recurso consultado y la marca de tiempo de acceso.<br><br>
        Escenario 3: Dado un recurso existente en el repositorio que requiere actualización de contenido, cuando el profesor sube una nueva versión del mismo archivo con el mismo identificador único, entonces el sistema preserva la versión anterior en el historial, marca la nueva versión como "actualizada [fecha]" y notifica opcionalmente a los estudiantes sobre la disponibilidad del material revisado.
      </td>
      <td>EP-004</td>
    </tr>
    <tr>
      <td>US-019</td>
      <td>Extensión de plazo de entrega</td>
      <td>Como profesor, quiero poder extender la fecha límite de un trabajo, para dar más tiempo a mis estudiantes en casos especiales.</td>
      <td>
        Escenario 1: Dado un trabajo académico con fecha límite configurada en el sistema, cuando el profesor accede a la configuración del trabajo, modifica la fecha de vencimiento a una nueva fecha futura y guarda los cambios, entonces el sistema actualiza automáticamente la fecha en todos los registros asociados, muestra un mensaje de "Fecha actualizada correctamente" y registra la modificación en el historial de cambios.<br><br>
        Escenario 2: Dado un trabajo con fecha límite recién modificada por el profesor, cuando se confirma la actualización, entonces el sistema envía una notificación automática a todos los estudiantes del curso con el siguiente mensaje: "Plazo extendido: La fecha límite para [nombre del trabajo] ha sido extendida hasta [nueva fecha]. ¡Aprovecha el tiempo adicional!".
      </td>
      <td>EP-002</td>
    </tr>
    <tr>
      <td>US-020</td>
      <td>Estados de entrega</td>
      <td>Como estudiante, quiero ver el estado de cada entrega (pendiente, entregado, en revisión, calificado), para conocer en qué punto del proceso está mi trabajo.</td>
      <td>
        Escenario 1: Dado un estudiante en la sección "Mis Entregas" del curso, cuando selecciona un trabajo específico de la lista, entonces el sistema muestra claramente el estado actual con indicadores visuales (iconos y colores): pendiente, entregado, en revisión o calificado, junto con la fecha de última actualización.<br><br>
        Escenario 2: Dado un profesor realizando la calificación de una entrega estudiantil, cuando asigna una calificación o cambia el estado de revisión en el sistema, entonces el estado del trabajo se actualiza automáticamente en todos los dispositivos, mostrando inmediatamente el nuevo estado (calificado) y los detalles de la evaluación al estudiante.<br><br>
        Escenario 3: Dado un cambio de estado en cualquier entrega de trabajo (de "en revisión" a "calificado", por ejemplo), cuando el sistema registra la modificación, entonces envía una notificación push al estudiante con el mensaje: "Tu trabajo [nombre del trabajo] ha sido [nuevo estado]. Revisa tus resultados en la plataforma."
      </td>
      <td>EP-002</td>
    </tr>
    <tr>
      <td>US-021</td>
      <td>Redirección al aplicativo web</td>
      <td>Como usuario, quiero que exista un botón en la landing page que me redirija al dashboard del aplicativo web del sistema, para acceder a este sin tener que buscar otro enlace.</td>
      <td>
        Escenario 1: Dado un usuario en la landing page de la startup, cuando hace clic en el botón "Acceder al Dashboard" ubicado en el header de la página, entonces el sistema redirige automáticamente a la URL del aplicativo web, abriendo la página de Inicio de Sesión.<br><br>
        Escenario 2: Dado un usuario que ya ha iniciado sesión previamente en el aplicativo web, cuando accede a la landing page y hace clic en el botón "Dashboard", entonces el sistema verifica las credenciales almacenadas y redirige directamente al dashboard principal sin requerir un nuevo inicio de sesión.
      </td>
      <td>EP-005</td>
    </tr>
    <tr>
      <td>US-022</td>
      <td>Sección de Video About the Team</td>
      <td>Como usuario, quiero encontrar en la landing page una sección con un video sobre el equipo detrás de la startup, para conocer quiénes son, su experiencia y la visión que impulsa el producto.</td>
      <td>
        Escenario 1: Dado que un usuario se encuentra en la landing page, cuando se desplaza hasta la sección "Video About the Team", entonces el sistema muestra un reproductor de video central con un título inspirador (ej. "Conoce al equipo que hace esto posible") y una breve descripción del propósito del equipo.<br><br>
        Escenario 2: Dado que un usuario quiere conocer más sobre las personas detrás del producto, cuando hace clic en el video para reproducirlo, entonces el sistema muestra el contenido en alta calidad, con controles de reproducción (pausa, subtítulos, pantalla completa) y, al finalizar, ofrece la opción de ver perfiles breves de los integrantes o enlaces a redes profesionales (ej. LinkedIn).
      </td>
      <td>EP-005</td>
    </tr>
    <tr>
      <td>US-023</td>
      <td>Visualización de Misión y Visión de la startup</td>
      <td>Como usuario, quiero ver una sección en la landing page con la Misión y Visión de la startup para conocer más a detalle los objetivos del proyecto.</td>
      <td>
        Escenario 1: Dado un usuario en la landing page de la startup, cuando hace clic en la sección "Nuestra Propuesta" en el menú principal, entonces el sistema muestra la Misión y Visión de la empresa en un diseño claro y conciso, con iconos representativos y texto destacado que comunica el propósito y los objetivos a largo plazo.<br><br>
        Escenario 2: Dado un visitante interesado en los valores de la startup, cuando se desplaza hasta el pie de página de la landing page, entonces el sistema presenta un resumen de la Misión y Visión junto con los principios fundamentales de la empresa, permitiendo al usuario comprender la esencia del proyecto de forma rápida.
      </td>
      <td>EP-005</td>
    </tr>
    <tr>
      <td>US-024</td>
      <td>Testimonios de usuarios previos</td>
      <td>Como usuario interesado en el producto, quiero ver testimonios reales de clientes en la landing page, para poder confiar en la efectividad de la solución antes de probar el sistema.</td>
      <td>
        Escenario 1: Dado un usuario en la landing page, cuando se desplaza hasta la sección "Experiencias de Usuarios", entonces el sistema muestra al menos tres testimonios verificados con foto, nombre, ubicación y calificación por estrellas, junto con una descripción breve de su experiencia usando el sistema.<br><br>
        Escenario 2: Dado un usuario interesado en conocer opiniones específicas, cuando hace clic en el botón "Ver más testimonios" en la sección designada, entonces el sistema redirige a una página dedicada con filtros por tipo de motocicleta, tiempo de uso del sistema y tipo de servicio evaluado.
      </td>
      <td>EP-005</td>
    </tr>
    <tr>
      <td>US-025</td>
      <td>Sección de Video About the Product</td>
      <td>Como usuario, quiero encontrar en la landing page una sección con un video explicativo del producto, para entender de manera rápida y visual cómo funciona y qué beneficios me ofrece.</td>
      <td>
        Escenario 1: Dado un usuario en la landing page, cuando se desplaza hasta la sección "Video About the Product", entonces el sistema muestra un video central en un reproductor embebido, acompañado de un título atractivo y una breve descripción introductoria.<br><br>
        Escenario 2: Dado un usuario interesado en más detalles, cuando hace clic en el video para reproducirlo, entonces el sistema muestra el contenido en alta calidad, con controles de reproducción (pausa, subtítulos, pantalla completa) y la opción de ver testimonios o casos de uso relacionados al final del video.
      </td>
      <td>EP-005</td>
    </tr>
    <tr>
      <td>TS-001</td>
      <td>Configuración de autenticación y autorización con JWT</td>
      <td>Como desarrollador, quiero implementar un sistema de autenticación y autorización basado en JSON Web Tokens (JWT) en el backend, para asegurar que solo los usuarios autorizados puedan acceder a los endpoints protegidos de la aplicación.</td>
      <td>
        Escenario 1: Dado que un usuario intenta acceder a un endpoint protegido sin un token válido, cuando realiza la petición, entonces el sistema devuelve un error 401 Unauthorized.<br><br>
        Escenario 2: Dado que un usuario inicia sesión correctamente y obtiene un token JWT válido, cuando utiliza ese token en el encabezado de autorización para acceder a un endpoint protegido, entonces el sistema permite el acceso y devuelve la respuesta correspondiente.
      </td>
      <td>EP-006</td>
    </tr>
    <tr>
      <td>TS-002</td>
      <td>Configuración de validación de datos en backend</td>
      <td>Como desarrollador, quiero implementar validaciones con Spring Boot Validation en los endpoints, para asegurar que los datos ingresados por los usuarios cumplan con los formatos y restricciones necesarias.</td>
      <td>
        Escenario 1: Dado que un usuario envía un formulario con un campo obligatorio vacío, cuando la petición llega al backend, entonces el sistema devuelve un error 400 Bad Request con un mensaje indicando que el campo es obligatorio.<br><br>
        Escenario 2: Dado que un usuario envía un email con un formato incorrecto en el registro, cuando el backend procesa la solicitud, entonces el sistema rechaza el request y devuelve un mensaje indicando que el formato del correo no es válido.
      </td>
      <td>EP-006</td>
    </tr>
    <tr>
      <td>TS-003</td>
      <td>Documentación de la API con Swagger</td>
      <td>Como desarrollador, quiero integrar Swagger/OpenAPI en el backend con Spring Boot, para que los endpoints estén documentados automáticamente y puedan ser probados fácilmente desde una interfaz gráfica.</td>
      <td>
        Escenario 1: Dado que un desarrollador accede a la URL /swagger-ui.html, cuando la interfaz de Swagger se carga, entonces el sistema muestra la documentación de todos los endpoints disponibles en el backend.<br><br>
        Escenario 2: Dado que un desarrollador necesita probar un endpoint de la API, cuando utiliza el botón "Try it out" en Swagger UI, entonces el sistema ejecuta la petición y muestra la respuesta en pantalla.
      </td>
      <td>EP-006</td>
    </tr>
    <tr>
      <td>TS-004</td>
      <td>Configuración de CORS en backend</td>
      <td>Como desarrollador, quiero configurar las políticas de CORS en Spring Boot, para permitir que el frontend (Angular) y el backend (Spring) se comuniquen correctamente en entornos de desarrollo y producción.</td>
      <td>
        Escenario 1: Dado que el frontend en Angular se encuentra en un dominio distinto al backend, cuando realiza una petición al servidor, entonces el sistema permite la comunicación siempre que el origen esté autorizado en la configuración de CORS.<br><br>
        Escenario 2: Dado que una aplicación no autorizada intenta consumir un endpoint del backend, cuando realiza la petición desde un dominio no permitido, entonces el sistema bloquea la solicitud y devuelve un error CORS policy: No 'Access-Control-Allow-Origin' header.
      </td>
      <td>EP-006</td>
    </tr>
  </tbody>
</table>

## 3.3 Impact Map

El Impact Mapping de LearnHive permite conectar los objetivos estratégicos de la startup con las acciones concretas de los usuarios. Para ello, se definieron Business Goals bajo criterios SMART, vinculados a los User Personas identificados (profesor y estudiante). A partir de estos actores se establecieron los Impacts, que describen los cambios de comportamiento esperados para alcanzar cada meta. Posteriormente, se definieron los Deliverables, que representan las funcionalidades clave que la plataforma debe ofrecer, y finalmente las User Stories, que detallan en lenguaje de usuario las acciones específicas que habilitan dichos entregables.

Este enfoque asegura que cada funcionalidad desarrollada esté alineada con una meta de negocio clara y con necesidades reales de los usuarios, fortaleciendo la adopción de la plataforma y su impacto en la gestión académica.

![impact_map.png](assets/impact_map.png)


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
