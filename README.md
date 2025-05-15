<p align="center">
  <img src="img/image1.png" alt="Logo de UPC" width="100%">
</p>

<div align="center">

# <span style="color:red">**Universidad Peruana de Ciencias Aplicadas**</span>
## Carrera de Ingeniería de Software

Ciclo: 2025 - 10

Curso: 1ASI0728 Arquitecturas De Software Emergentes

NRC: 2510

Profesor: Rojas Malasquez, Royer Edelwer

“Informe de Trabajo Final"

Startup: -

Producto: VoteChain

Grupo: 5

|          Integrantes          |      Código      |
|:-----------------------------:|:-------------------:|
|   -  |    -    |
|   -  |    -    |
|  Ramos Ramirez, Renzo Manuel           |    u202113745    |
|  Bernardo Eusebio Alessandro Joaquin   |    u202113640    |
|  Ramirez Mendez, Sebastian Andre       |    u20191e575    |

Abril 2025 

</div>

---

## Registro de Versiones Del Informe

## Project Report Collaboration Insights

### **Reporte de colaboración de la entrega del TB1:**

------
## Tabla de contenidos
## Capítulo I: Introducción
- 1.1. Startup Profile
  - 1.1.1. Descripción de la Startup
  - 1.1.2. Perfiles de integrantes del equipo
- 1.2. Solution Profile
  - 1.2.1. Antecedentes y problemática
  - 1.2.2. Lean UX Process
    - 1.2.2.1. Lean UX Problem Statements
    - 1.2.2.2. Lean UX Assumptions
    - 1.2.2.3. Lean UX Hypothesis Statements
    - 1.2.2.4. Lean UX Canvas
- 1.3. Segmentos objetivo

## Capítulo II: Requirements Elicitation & Analysis
- 2.1. Competidores
  - 2.1.1. Análisis competitivo
  - 2.1.2. Estrategias y tácticas frente a competidores
- 2.2. Entrevistas
  - 2.2.1. Diseño de entrevistas
  - 2.2.2. Registro de entrevistas
  - 2.2.3. Análisis de entrevistas
- 2.3. Needfinding
  - 2.3.1. User Personas
  - 2.3.2. User Task Matrix
  - 2.3.3. Empathy Mapping
  - 2.3.4. As-is Scenario Mapping
- 2.4. Ubiquitous Language

## Capítulo III: Requirements Specification
- 3.1. To-Be Scenario Mapping
- 3.2. User Stories
- 3.3. Impact Mapping
- 3.4. Product Backlog

## Capítulo IV: Strategic-Level Software Design
- 4.1. Strategic-Level Attribute-Driven Design
  - 4.1.1. Design Purpose
  - 4.1.2. Attribute-Driven Design Inputs
    - 4.1.2.1. Primary Functionality (Primary User Stories)
    - 4.1.2.2. Quality Attribute Scenarios
    - 4.1.2.3. Constraints
  - 4.1.3. Architectural Drivers Backlog
  - 4.1.4. Architectural Design Decisions
  - 4.1.5. Quality Attribute Scenario Refinements
- 4.2. Strategic-Level Domain-Driven Design
  - 4.2.1. EventStorming
  - 4.2.2. Candidate Context Discovery
  - 4.2.3. Domain Message Flows Modeling
  - 4.2.4. Bounded Context Canvases
  - 4.2.5. Context Mapping
- 4.3. Software Architecture
  - 4.3.1. Software Architecture System Landscape Diagram
  - 4.3.2. Software Architecture Context Level Diagrams
  - 4.3.3. Software Architecture Container Level Diagrams
  - 4.3.4. Software Architecture Deployment Diagrams

## Capítulo V: Tactical-Level Software Design
- 5.1. Bounded Context: Voting Management
  - 5.1.1. Domain Layer
    
  <ul>
    <li>
      <strong>VotingProcess:</strong> Define el proceso completo de votación, incluyendo su configuración, estado actual y reglas de operación. 
      Encapsula toda la información necesaria para gestionar un proceso electoral desde su creación hasta su finalización.
    </li>
    <li>
      <strong>VotingSession:</strong> Representa una sesión de votación activa dentro de un proceso electoral. 
      Contiene información sobre el período de tiempo en que las votaciones están habilitadas, controla el inicio y cierre de la sesión.
    </li>
    <li>
      <strong>Ballot:</strong> Define la papeleta o boleta electoral que contiene las opciones disponibles para votar. 
      Incluye la estructura de la papeleta y las opciones que pueden ser seleccionadas por los votantes.
    </li>
    <li>
      <strong>Vote:</strong> Encapsula el voto emitido por un votante. 
      Contiene la selección realizada y mantiene la integridad del voto sin comprometer el anonimato del votante.
    </li>
  </ul>
  
  - 5.1.2. Interface Layer
 
    <ul>
    <li>
      <strong>VotingProcessController:</strong> Se encarga de gestionar las solicitudes HTTP relacionadas con la creación, configuración y administración de procesos de votación.
      Proporciona endpoints para definir nuevos procesos electorales y consultar su estado.
    </li>
    <li>
      <strong>VotingSessionController:</strong> Maneja las operaciones de apertura, monitoreo y cierre de sesiones de votación. 
      Expone endpoints para controlar el ciclo de vida de una sesión electoral.
    </li>
    <li>
      <strong>BallotController:</strong> Gestiona las solicitudes relacionadas con la definición y consulta de papeletas electorales. 
      Proporciona interfaces para configurar las opciones de voto disponibles para los electores.
    </li>
    <li>
      <strong>VoteController:</strong> Procesa las solicitudes de emisión de votos y consulta de resultados agregados. 
      Asegura que los votos se registren correctamente mientras mantiene el anonimato del votante.
    </li>
  </ul>
    
  - 5.1.3. Application Layer

<ul>
    <li>
      <strong>VotingProcessService:</strong> Implementa la lógica de negocio para la creación y gestión de procesos de votación. 
      Coordina las operaciones necesarias para definir, configurar y monitorear procesos electorales completos.
    </li>
    <li>
      <strong>VotingSessionService:</strong> Maneja la lógica relacionada con la apertura, operación y cierre de sesiones de votación. 
      Garantiza que las sesiones se ejecuten según las reglas definidas para el proceso electoral.
    </li>
    <li>
      <strong>BallotManagementService:</strong> Implementa la lógica para la creación y administración de papeletas electorales. 
      Asegura que las papeletas cumplan con los requisitos establecidos para cada tipo de elección.
    </li>
    <li>
      <strong>VoteProcessingService:</strong> Gestiona el registro seguro de los votos emitidos y el cálculo de resultados. 
      Implementa los algoritmos necesarios para procesar los votos manteniendo la integridad del proceso electoral.
    </li>
  </ul>

  - 5.1.4. Infrastructure Layer
    
  <ul>
    <li>
      <strong>VotingProcessRepository:</strong> Se encarga de la persistencia y recuperación de datos relacionados con los procesos de votación. 
      Implementa operaciones CRUD para los procesos electorales en la base de datos.
    </li>
    <li>
      <strong>VotingSessionRepository:</strong> Gestiona el almacenamiento y acceso a datos de las sesiones de votación. 
      Proporciona métodos para persistir el estado de las sesiones electorales activas.
    </li>
    <li>
      <strong>BallotRepository:</strong>Maneja la persistencia de las definiciones de papeletas electorales. 
      Implementa operaciones para almacenar y recuperar la estructura y opciones de las papeletas.
    </li>
    <li>
      <strong>VoteRepository:</strong> Se encarga del almacenamiento seguro y anónimo de los votos emitidos. 
      Implementa mecanismos para registrar votos manteniendo su integridad y confidencialidad.
    </li>
  </ul>


  - 5.1.6. Bounded Context Software Architecture Component Level Diagrams
  - 5.1.7. Bounded Context Software Architecture Code Level Diagrams
    - 5.1.7.1. Bounded Context Domain Layer Class Diagrams
    - 5.1.7.2. Bounded Context Database Design Diagram

- 5.X. Bounded Context: <Bounded Context Name>
  - 5.X.1. Domain Layer
  - 5.X.2. Interface Layer
  - 5.X.3. Application Layer
  - 5.X.4. Infrastructure Layer
  - 5.X.6. Bounded Context Software Architecture Component Level Diagrams
  - 5.X.7. Bounded Context Software Architecture Code Level Diagrams
    - 5.X.7.1. Bounded Context Domain Layer Class Diagrams
    - 5.X.7.2. Bounded Context Database Design Diagram

## Capítulo VI: Solution UX Design
- 6.1. Style Guidelines
  - 6.1.1. General Style Guidelines
  - 6.1.2. Web, Mobile & Devices Style Guidelines
- 6.2. Information Architecture
  - 6.2.2. Labeling Systems
  - 6.2.3. Searching Systems
  - 6.2.4. SEO Tags and Meta Tags
  - 6.2.5. Navigation Systems
- 6.3. Landing Page UI Design
  - 6.3.1. Landing Page Wireframe
  - 6.3.2. Landing Page Mock-up
- 6.4. Applications UX/UI Design
  - 6.4.1. Applications Wireframes
  - 6.4.2. Applications Wireflow Diagrams
  - 6.4.3. Applications Mock-ups
  - 6.4.4. Applications User Flow Diagrams
- 6.5. Applications Prototyping

## Capítulo VII: Product Implementation, Validation & Deployment
- 7.1. Software Configuration Management
  - 7.1.1. Software Development Environment Configuration
  - 7.1.2. Source Code Management
  - 7.1.3. Source Code Style Guide & Conventions
  - 7.1.4. Software Deployment Configuration
- 7.2. Solution Implementation
  - 7.2.X. Sprint n
    - 7.2.X.1. Sprint Planning n
    - 7.2.X.2. Sprint Backlog n
    - 7.2.X.3. Development Evidence for Sprint Review
    - 7.2.X.4. Testing Suite Evidence for Sprint Review
    - 7.2.X.5. Execution Evidence for Sprint Review
    - 7.2.X.6. Services Documentation Evidence for Sprint Review
    - 7.2.X.7. Software Deployment Evidence for Sprint Review
    - 7.2.X.8. Team Collaboration Insights during Sprint
- 7.3. Validation Interviews
  - 7.3.1. Diseño de entrevistas
  - 7.3.2. Registro de entrevistas
  - 7.3.3. Evaluaciones según heurísticas
- 7.4. Video About-the-Product

## Conclusiones
- Conclusiones y recomendaciones
- Video About-the-Team

## Bibliografía

## Anexos

# Contenido
## Capítulo I: Introducción 
## Capítulo II: Requirements Elicitation & Analysis
## Capítulo III: Requirements Specification
## Capítulo IV: Solution Software Design
## Anexos y Bibliografía 
## Student Outcome
