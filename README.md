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

|             Integrantes             |   Código   |
| :---------------------------------: | :--------: |
|                  -                  |     -      |
|                  -                  |     -      |
|     Ramos Ramirez, Renzo Manuel     | u202113745 |
| Bernardo Eusebio Alessandro Joaquin | u202113640 |
|   Ramirez Mendez, Sebastian Andre   | u20191e575 |

Abril 2025

</div>

---

## Registro de Versiones Del Informe

## Project Report Collaboration Insights

### **Reporte de colaboración de la entrega del TB1:**

---

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

## 5.1. Bounded Context: Voting Management

### 5.1.1. Domain Layer

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
  
  ### 5.1.2. Interface Layer
 
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
    
  ### 5.1.3. Application Layer

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

### 5.1.4. Infrastructure Layer

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

### 5.1.5. Bounded Context Software Architecture Component Level Diagrams

  <p>El diagrama ilustra la estructura en capas del bounded context de Voting Management, mostrando cómo se organizan los componentes desde la interfaz hasta la infraestructura. 
    Presenta claramente la separación entre controladores, servicios, entidades de dominio y repositorios, con flechas que indican el flujo de dependencias entre cada capa.</p>
  <img src="img/boundedDiagram1.png">
  
  ### 5.1.6. Bounded Context Software Architecture Code Level Diagrams
  #### 5.1.6.1. Bounded Context Domain Layer Class Diagrams
  
  <p>Muestra las principales clases del dominio de gestión de votaciones (VotingProcess, VotingSession, Ballot y Vote) con sus propiedades y métodos más relevantes. 
    Incluye las relaciones entre estas clases, donde un VotingProcess puede tener múltiples VotingSessions, cada sesión puede tener múltiples Votes, y cada Ballot está asociado con varios Votes.</p>
  <img src="img/boundedDiagram2.png">
  
  #### 5.1.6.2. Bounded Context Database Design Diagram
  
  <p>Representa el esquema de base de datos para el bounded context de Voting Management, mostrando las tablas principales (voting_processes, voting_sessions, ballots, votes y ballot_options) con sus columnas clave. 
    Las relaciones entre tablas están indicadas con líneas y flechas, ilustrando las conexiones lógicas como claves foráneas.</p>
  <img src="img/boundedDiagram3.png">

## 5.2. Bounded Context: Voter Access & Authentication Bounded Context

### 5.2.1. Domain Layer

<ul>
    <li>
      <strong>Voter:</strong> Representa a una persona registrada que tiene derecho a votar. 
      Contiene la información necesaria para identificar al votante sin comprometer datos personales sensibles.
    </li>
    <li>
      <strong>IdentityCredential:</strong> Define las credenciales utilizadas para verificar la identidad de un votante. 
      Encapsula los mecanismos de autenticación manteniendo la seguridad de la información personal.
    </li>
    <li>
      <strong>AuthenticationSession:</strong> Representa una sesión de autenticación activa para un votante. 
      Gestiona el estado de la sesión, desde su inicio hasta su finalización.
    </li>
    <li>
      <strong>ElectoralRegistry:</strong> Mantiene el registro centralizado de todos los votantes elegibles. 
      Proporciona mecanismos para validar la elegibilidad de los votantes durante el proceso electoral.
    </li>
  </ul>
  
  ### 5.2.2. Interface Layer

<ul>
    <li>
      <strong>VoterRegistrationController:</strong> Gestiona las solicitudes relacionadas con el registro de nuevos votantes en el sistema. 
      Proporciona endpoints para la creación y actualización de registros de votantes.
    </li>
    <li>
      <strong>AuthenticationController:</strong> Maneja el proceso de autenticación de votantes. 
      Expone endpoints para la verificación de identidad y emisión de tokens de autenticación.
    </li>
    <li>
      <strong>IdentityVerificationController:</strong> Procesa las solicitudes de verificación de identidad de los votantes. 
      Proporciona interfaces para validar credenciales y documentos de identificación.
    </li>
    <li>
      <strong>SessionManagementController:</strong> Gestiona las sesiones de autenticación de los votantes. 
      Expone endpoints para iniciar, renovar y cerrar sesiones seguras.
    </li>
  </ul>
  
  ### 5.2.3. Application Layer

  <ul>
    <li>
      <strong>VoterRegistrationService:</strong> Implementa la lógica de negocio para el registro y validación de votantes. 
      Coordina el proceso de verificación de elegibilidad y creación de nuevos registros de votantes.
    </li>
    <li>
      <strong>AuthenticationService:</strong> Maneja la autenticación segura de los votantes. 
      Implementa los mecanismos necesarios para verificar la identidad de los votantes antes de permitir el acceso al sistema.
    </li>
    <li>
      <strong>IdentityVerificationService:</strong>  Implementa la lógica para validar la identidad de los votantes utilizando múltiples factores. 
      Coordina la verificación de credenciales y documentos de identificación.
    </li>
    <li>
      <strong>SessionManagementService:</strong> Gestiona el ciclo de vida de las sesiones de autenticación. 
      Implementa los mecanismos para crear, mantener y cerrar sesiones seguras para los votantes autenticados.
    </li>
  </ul>
  
  ### 5.2.4. Infrastructure Layer

  <ul>
    <li>
      <strong>VoterRepository:</strong> Gestiona la persistencia y recuperación de datos de los votantes registrados. 
      Implementa operaciones CRUD para los registros de votantes en la base de datos.
    </li>
    <li>
      <strong>CredentialRepository:</strong> Maneja el almacenamiento seguro de las credenciales de autenticación. 
      Proporciona métodos para persistir y verificar las credenciales de identidad de forma segura.
    </li>
    <li>
      <strong>AuthenticationSessionRepository:</strong> Se encarga del almacenamiento y gestión de datos relacionados con las sesiones de autenticación. 
      Implementa operaciones para mantener el estado de las sesiones activas.
    </li>
    <li>
      <strong>ElectoralRegistryRepository:</strong> Gestiona el acceso a los datos del registro electoral centralizado. 
      Proporciona métodos para consultar y validar la elegibilidad de los votantes durante el proceso electoral.
    </li>
  </ul>

### 5.2.5. Bounded Context Software Architecture Component Level Diagrams

  <p>Muestra la arquitectura en capas del bounded context de autenticación y acceso de votantes, donde se pueden ver los controladores en la capa de interfaz, los servicios en la capa de aplicación, las entidades centrales en la capa de dominio, y los repositorios en la capa de infraestructura, con flechas que indican la dirección de dependencia.</p>
  <img src="img/boundedDiagram4.png">
  
  ### 5.2.6. Bounded Context Software Architecture Code Level Diagrams
  #### 5.2.6.1. Bounded Context Domain Layer Class Diagrams
  
  <p>Ilustra las principales clases del dominio de autenticación de votantes (Voter, IdentityCredential, AuthenticationSession y ElectoralRegistry) con sus atributos y métodos esenciales. 
    El diagrama muestra las relaciones clave, como un Voter que puede tener múltiples IdentityCredentials y AuthenticationSessions, y cómo el ElectoralRegistry mantiene referencias a los votantes registrados.</p>
  <img src="img/boundedDiagram5.png">
  
  #### 5.2.6.2. Bounded Context Database Design Diagram
  <p>Representa la estructura de almacenamiento de datos para el bounded context de autenticación, mostrando las tablas principales (voters, identity_credentials, authentication_sessions) con sus columnas clave y relaciones. Las conexiones entre tablas representan las relaciones de clave foránea que mantienen la integridad referencial del sistema..</p>
  <img src="img/boundedDiagram6.png">

## 5.3. Bounded Context: Vote Submission Management

### 5.3.1. Domain Layer

  <ul>
    <li>
      <strong>VoteSubmission:</strong> Representa el proceso completo de envío de un voto, desde la visualización de opciones hasta la confirmación final. 
      Asegura que el flujo de votación sea seguro y trazable.
    </li>
    <li>
      <strong>VoteSubmissionScreen:</strong> Define la interfaz de usuario que muestra las opciones de votación y captura la selección del votante. 
      Gestiona la renderización de las opciones de manera clara y accesible.
    </li>
    <li>
      <strong>EncryptedVote:</strong> Encapsula el voto encriptado generado a partir de la selección del votante. 
      Garantiza la seguridad y anonimato del voto antes de su envío.
    </li>
    <li>
      <strong>BlockchainVote:</strong> Representa el voto almacenado de forma inmutable en la blockchain. 
      Gestiona la transmisión y verificación del voto en la cadena de bloques.
    </li>
  </ul>

### 5.3.2. Interface Layer

  <ul>
    <li>
      <strong>VoteSubmissionController:</strong> Maneja las solicitudes HTTP relacionadas con el proceso de envío de votos. 
      Proporciona endpoints para mostrar opciones, emitir y confirmar votos.
    </li>
    <li>
      <strong>EncryptedVoteController:</strong> Gestiona las solicitudes para encriptar y enviar votos a la blockchain. 
      Expone endpoints para asegurar la integridad y confidencialidad del proceso.
    </li>
  </ul>

### 5.3.3. Application

  <ul>
    <li>
      <strong>VoteSubmissionService:</strong> Implementa la lógica de negocio para renderizar opciones de votación y gestionar el envío. 
      Coordina las etapas de visualización, emisión y confirmación del voto.
    </li>
    <li>
      <strong>EncryptedVoteService:</strong> Maneja la encriptación de los votos y su preparación para el envío. 
      Asegura que el proceso de encriptación cumpla con los estándares de seguridad.
    </li>
    <li>
      <strong>BlockchainVoteService:</strong> Gestiona la lógica para enviar votos encriptados a la blockchain. 
      Garantiza que la transmisión sea exitosa y verificable.
    </li>

### 5.3.4. Infrastructure Layer

  <ul>
    <li>
      <strong>VoteSubmissionRepository:</strong> Responsable de la persistencia y recuperación de datos del proceso de envío de votos. 
      Implementa operaciones CRUD para rastrear el estado de las submissions.
    </li>
    <li>
      <strong>EncryptedVoteRepository:</strong> Gestiona el almacenamiento seguro de los votos encriptados. 
      Proporciona métodos para persistir y consultar datos encriptados.
    </li>
    <li>
      <strong>BlockchainVoteRepository:</strong> Maneja la interacción con la blockchain para el almacenamiento de votos. 
      Implementa métodos para enviar y verificar votos en la cadena.
    </li>
  </ul>

### 5.3.5. Bounded Context Software Architecture Component Level Diagrams

  <p>
    El diagrama muestra la arquitectura en capas del bounded context de Vote Submission Management, ilustrando la organización e interacción de sus componentes desde la interfaz hasta la infraestructura. Se destaca la separación de responsabilidades entre las capas Interface Layer, Application Layer, Domain Layer e Infrastructure Layer, con flechas que indican el flujo de dependencias y el proceso de envío de votos.
  </p>
  
- La Interface Layer incluye los componentes VoteSubmissionController y EncryptedVoteController, que gestionan las solicitudes HTTP provenientes del usuario (un ciudadano votante que interactúa a través de una interfaz web o móvil). Estos controladores invocan los servicios correspondientes en la capa de aplicación para procesar las solicitudes.
- La Application Layer está formada por VoteSubmissionService, EncryptedVoteService y BlockchainVoteService, que coordinan la lógica de negocio. El VoteSubmissionService se encarga de renderizar y confirmar las opciones de votación, el EncryptedVoteService gestiona la encriptación de los votos, y el BlockchainVoteService asegura el almacenamiento seguro en la blockchain, con interacciones coordinadas entre ellos.
- La Domain Layer contiene las entidades VoteSubmissionScreen, VoteSubmission, EncryptedVote y BlockchainVote. El diagrama representa el flujo del proceso de votación: VoteSubmissionScreen renderiza las opciones de votación, VoteSubmission las muestra y emite el voto encriptado, EncryptedVote confirma el envío, y BlockchainVote almacena el voto en la blockchain.
- La Infrastructure Layer incluye VoteSubmissionRepository, EncryptedVoteRepository y BlockchainVoteRepository, que persisten los datos en una Database e interactúan con la Blockchain. Los repositorios gestionan las operaciones de almacenamiento y recuperación, garantizando la integridad y la inmutabilidad de los datos.

<img src="img/Architecture-Component_Vote-Submission-Management.png">
  
  ### 5.3.6. Bounded Context Software Architecture Code Level Diagrams
  #### 5.3.6.1. Bounded Context Domain Layer Class Diagrams
  El diagrama muestra las clases principales de la capa de dominio del bounded context de Vote Submission Management, representando las entidades clave que encapsulan la lógica central del proceso de envío de votos. Este diagrama de clases detalla las propiedades, métodos y relaciones con cardinalidad entre las entidades VoteSubmission, VoteSubmissionScreen, EncryptedVote, y BlockchainVote, que son esenciales para gestionar el flujo de votación desde la visualización hasta el almacenamiento en la blockchain.

- La clase VoteSubmission representa el proceso completo de envío de un voto, con propiedades como submissionId (identificador único), status (estado de la submission), y selectedOption (opción seleccionada). Incluye métodos como displayVotingOptions() (mostrar opciones de votación) y castEncryptedVote() (emitir voto encriptado). Esta clase tiene una relación de composición de uno a uno (1:1) con VoteSubmissionScreen y genera un EncryptedVote mediante composición.
- La clase VoteSubmissionScreen modela la interfaz de usuario que muestra las opciones de votación, con propiedades como screenId (identificador único) y renderStatus (estado de renderización). Su método principal es renderOptions() (renderizar opciones). Está asociada a VoteSubmission mediante una relación de composición.
- La clase EncryptedVote encapsula el voto encriptado, con propiedades como voteId (identificador único), encryptedData (datos encriptados), y submissionStatus (estado de la submission). Incluye métodos como encryptVote() (encriptar voto) y submitEncryptedVote() (enviar voto encriptado). Tiene una relación de composición de uno a uno (1:1) con VoteSubmission y genera un BlockchainVote mediante agregación.
- La clase BlockchainVote representa el voto almacenado en la blockchain, con propiedades como blockchainId (identificador único), transactionHash (hash de la transacción), y confirmationStatus (estado de confirmación). Sus métodos incluyen storeOnBlockchain() (almacenar en blockchain) y sendVoteToBlockchain() (enviar voto a blockchain). Está asociada a EncryptedVote mediante una relación de agregación de uno a uno (1:1).

<img src="img/Context-Domain_Vote-Submission-Management.png">

#### Bounded Context Database Design Diagram

El diagrama entidad-relación (ER) representa el diseño de la base de datos para el Vote Submission Management, mostrando las entidades, atributos y relaciones que soportan el flujo de votación desde la renderización de opciones hasta el almacenamiento en blockchain.

Las entidades son VoteSubmission (submission_id PK, status, selected_option nullable), VoteSubmissionScreen (screen_id PK, render_status nullable, submission_id FK), EncryptedVote (vote_id PK, encrypted_data, submission_status nullable, submission_id FK), y BlockchainVote (blockchain_id PK, transaction_hash, confirmation_status nullable, vote_id FK).

Las relaciones, todas 1:1, son:

- VoteSubmission compone VoteSubmissionScreen (1:1), asociando una pantalla por submission.
- VoteSubmission compone EncryptedVote (1:1), generando un voto encriptado por submission.
- EncryptedVote agrega BlockchainVote (1:1), almacenando un registro en blockchain por voto encriptado.
- Este diseño asegura unicidad y trazabilidad en el proceso de votación, alineándose con los requisitos del sistema.

    <img src="img/Context-database_Vote-Submission-Management.png">

## 5.4. Bounded Context: Vote Results Management

### 5.4.1. Domain Layer

- VoteResult: Representa el resultado agregado de la votación, encapsulando el total de votos y su estado. Asegura la integridad y trazabilidad de los resultados finales.
- VotingReport: Define el informe generado sobre la votación, incluyendo datos analíticos y estadísticas. Facilita la generación y visualización de reportes.
- TallyResult: Encapsula el proceso de conteo de votos encriptados, garantizando precisión y seguridad en el cálculo de resultados.
- PublishedResult: Representa el resultado final publicado, incluyendo la fecha de publicación y datos verificables. Gestiona la difusión de resultados.

### 5.4.2. Interface Layer

- VotingReportController: Maneja las solicitudes HTTP para generar y consultar informes de votación. Proporciona endpoints para crear y recuperar reportes.
- PublishedResultController: Gestiona las solicitudes HTTP para publicar y visualizar resultados finales. Expone endpoints para acceso público a los resultados.

### 5.4.3. Application

- VotingReportService: Implementa la lógica de negocio para generar informes de votación. Coordina la creación y almacenamiento de reportes.
- TallyResultService: Maneja el conteo de votos encriptados y la validación de resultados. Asegura la precisión del proceso de tallado.
- PublishedResultService: Gestiona la publicación de resultados finales y su distribución. Verifica la integridad antes de publicar.

### 5.4.4. Infrastructure Layer

- VotingReportRepository: Responsable de la persistencia y recuperación de informes de votación. Implementa operaciones CRUD para reportes.
- TallyResultRepository: Gestiona el almacenamiento de los resultados contados. Proporciona métodos para consultar y actualizar datos.
- PublishedResultRepository: Maneja la interacción con el almacenamiento de resultados publicados. Asegura la accesibilidad y verificación.

### 5.4.5. Bounded Context Software Architecture Component Level Diagrams

El diagrama muestra la arquitectura en capas del bounded context de Vote Results Management, ilustrando la interacción entre sus componentes desde la interfaz hasta la infraestructura. Se destaca la separación de responsabilidades entre las capas Interface Layer, Application Layer, Domain Layer e Infrastructure Layer, con flechas que indican el flujo de dependencias y el proceso de gestión de resultados.

- La Interface Layer incluye los componentes VotingReportController y PublishedResultController, que gestionan solicitudes HTTP de usuarios (e.g., administradores o ciudadanos) para generar reportes y acceder a resultados, invocando servicios de la capa de aplicación.
- La Application Layer consta de VotingReportService, TallyResultService, y PublishedResultService, que coordinan la lógica de negocio. VotingReportService genera informes, TallyResultService procesa el conteo de votos, y PublishedResultService publica los resultados, con interacciones secuenciales.
- La Domain Layer contiene las entidades VoteResult, VotingReport, TallyResult, y PublishedResult. El flujo es: VoteResult inicia el proceso, VotingReport genera informes, TallyResult calcula resultados, y PublishedResult los publica.
- La Infrastructure Layer incluye VotingReportRepository, TallyResultRepository, y PublishedResultRepository, que persisten datos en una base de datos y aseguran la distribución de resultados.

<img src="img/Architecture-Component_Vote_Results_Management.png">

### 5.4.6. Bounded Context Software Architecture Code Level Diagrams

#### 5.4.6.1. Bounded Context Domain Layer Class Diagrams

El diagrama muestra las clases principales de la capa de dominio del bounded context de Vote Results Management, representando las entidades clave que gestionan el procesamiento y publicación de resultados. Detalla propiedades, métodos y relaciones con cardinalidad 1:1.

- La clase VoteResult representa el resultado general, con propiedades como result_id (UUID), total_votes (Integer), y status (String). Incluye métodos generateReport() y initiateTally(). Tiene relaciones de composición 1:1 con VotingReport y TallyResult.
- La clase VotingReport gestiona informes, con propiedades como report_id (UUID), report_data (String), y generated_date (DateTime). Su método es createReport(). Está compuesta por VoteResult.
- La clase TallyResult procesa el conteo, con propiedades como tally_id (UUID) y encrypted_votes (String). Incluye métodos processVotes() y finalizeTally(). Tiene una relación de composición 1:1 con VoteResult y agregación 1:1 con PublishedResult.
- La clase PublishedResult maneja la publicación, con propiedades como publish_id (UUID), final_result (String), y publish_date (DateTime). Su método es publishResults(). Está agregada por TallyResult.

<img src="img/Context-Domain_Vote_Results_Management.png">

#### 5.4.6.2. Bounded Context Database Design Diagram

El diagrama ER presenta el diseño de la base de datos para Vote Results Management, mostrando entidades, atributos y relaciones 1:1 que soportan el flujo de resultados.

- **VoteResult**: result_id (PK), total_votes, status.
- **VotingReport**: report_id (PK), report_data, generated_date, result_id (FK).
- **TallyResult**: tally_id (PK), encrypted_votes, result_id (FK).
- **PublishedResult**: publish_id (PK), final_result, publish_date, tally_id (FK).

Las relaciones son:

- **VoteResult** compone **VotingReport** (1:1), generando un informe por resultado.
- **VoteResult** compone **TallyResult** (1:1), procesando un conteo por resultado.
- **TallyResult** agrega **PublishedResult** (1:1), publicando un resultado por conteo.

<img src="img/Context-database_Vote_Results_Management.png">

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
