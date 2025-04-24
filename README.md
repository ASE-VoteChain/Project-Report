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

### 4.1. Strategic-Level Attribute-Driven Design.

Usaremos el Attribute-Driven Design (ADD) para garantizar que la arquitectura de VoteChain cumpla con los requisitos funcionales y no funcionales más críticos, alineándose con las necesitdades de los usuarios (organizaciones y votantes) y las restricciones del proyecto. Esta sección detallará el proceso de diseño, los insumos clave, los controladores arquitectónicos, las decisiones de diseño y los refinamientos de los escenarios de atributos de calidad.

#### 4.1.1. Design Purpose.

El propósito del diseño estratégico de VoteChain es desarrollar una arquitectura robusta, escalable y segura que permita la creación, ejecución y auditoría de votaciones digitales descentralizadas. La arquitectura debe garantizar:

- Transparencia y confianza: A través de registros inmutables en blockchain que permitan auditorías públicas.
- Seguridad y anonimato: Protegiendo la identidad de los votantes y la integridad de los votos.
- Accesibilidad: Facilitando el uso en dispositivos móviles y en zonas con conectividad limitada.
- Escalabilidad: Para soportar desde pequeñas comunidades hasta organizaciones grandes.
- Cumplimiento local: Adaptándose a regulaciones peruanas (e.g., ONPE, RENIEC) y con potencial para expandirse a otros mercados en América Latina.

El diseño se enfoca en priorizar los atributos de calidad **(seguridad, disponibilidad, usabilidad)** y las funcionalidades clave identificadas en las historias de usuario, mientras se respetan las restricciones de presupuesto, tiempo y conocimientos técnicos del equipo.

#### 4.1.2. Attribute-Driven Design Inputs.

Los insumos para el diseño arquitectónico se derivan de los capítulos anteriores, incluyendo las historias de usuario, los atributos de calidad y las restricciones del proyecto.

##### 4.1.2.1. Primary Functionality (Primary User Stories).

Las funcionalidades primarias de VoteChain se extraen de las historias de usuario priorizadas en el Product Backlog. Las siguientes historias de usuario son las más críticas para la arquitectura, ya que definen las capacidades centrales del sistema:

| **HU ID** | **Título** | **Descripción** | **Épica** |
|-----------|------------|-----------------|-----------|
| E01_US001 | Definir parámetros de elección | Como administrador, quiero establecer parámetros básicos (nombre, fechas, tipo) para iniciar una nueva votación. | E1: Configuración de votaciones descentralizadas |
| E02_US003 | Validación de identidad | Como sistema, quiero validar la identidad del votante para garantizar la autenticidad del registro. | E2: Autenticación segura de votantes |
| E03_US001 | Voto único y anónimo | Como votante, quiero que mi voto sea único y anónimo para que no puedan asociarlo conmigo. | E3: Emisión de votos anónimos y encriptados |
| E04_US001 | Guardado en blockchain | Como administrador, quiero registrar los votos emitidos en la blockchain para evitar fraudes. | E4: Registro inmutable en blockchain |
| E05_US001 | Acceso público a resultados | Como ciudadano, quiero acceder a los datos de votos en tiempo real para auditar la transparencia. | E5: Auditoría pública en tiempo real |

Estas historias reflejan las necesidades fundamentales de los segmentos objetivo (organizadores y votantes) y guían las decisiones arquitectónicas para soportar la configuración de votaciones, autenticación segura, votación anónima, registro inmutable y auditoría transparente.

##### 4.1.2.2. Quality attribute Scenarios.

Los atributos de calidad son esenciales para garantizar que VoteChain cumpla con las expectativas de los usuarios y las demandas del entorno. A continuación, se presentan los escenarios de atributos de calidad priorizados, siguiendo el formato estándar (estímulo, fuente, respuesta, medida):

| **Atributo** | **Escenario** | **Prioridad** |
|--------------|---------------|---------------|
| **Seguridad** | **Escenario**: Un atacante intenta modificar un voto registrado en la blockchain.<br>**Estímulo**: Intento de alterar un bloque.<br>**Fuente**: Atacante externo.<br>**Respuesta**: El sistema detecta la inconsistencia mediante verificación de hashes.<br>**Medida**: 100% de los intentos de alteración son detectados y reportados en menos de 1 segundo. | Alta |
| **Disponibilidad** | **Escenario**: Un votante intenta emitir su voto durante el período de votación.<br>**Estímulo**: Solicitud de voto desde un dispositivo móvil.<br>**Fuente**: Votante autenticado.<br>**Respuesta**: El sistema procesa la solicitud y registra el voto.<br>**Medida**: 99.9% de disponibilidad durante el período de votación, con un tiempo de respuesta menor a 2 segundos. | Alta |
| **Usabilidad** | **Escenario**: Un votante con conocimientos técnicos limitados accede a la plataforma para votar.<br>**Estímulo**: Intento de emitir un voto desde un smartphone.<br>**Fuente**: Votante no técnico.<br>**Respuesta**: La interfaz guía al usuario paso a paso, con instrucciones claras.<br>**Medida**: 90% de los usuarios completan el proceso de votación sin asistencia en menos de 3 minutos. | Media |
| **Escalabilidad** | **Escenario**: Una comunidad grande realiza una votación con 10,000 votantes simultáneos.<br>**Estímulo**: Picos de tráfico durante la votación.<br>**Fuente**: Votantes múltiples.<br>**Respuesta**: El sistema procesa todas las transacciones sin caídas.<br>**Medida**: Soporta hasta 10,000 transacciones por minuto con un tiempo de procesamiento promedio de 1 segundo por voto. | Media |
| **Auditabilidad** | **Escenario**: Un auditor externo verifica la validez de los resultados electorales.<br>**Estímulo**: Solicitud de auditoría de bloques.<br>**Fuente**: Auditor autorizado.<br>**Respuesta**: El sistema proporciona acceso a los registros inmutables y sus hashes.<br>**Medida**: 100% de los bloques son verificables en menos de 5 minutos. | Alta |

Estos escenarios aseguran que la arquitectura priorice la seguridad, disponibilidad y auditabilidad, que son críticos para generar confianza en los procesos democráticos digitales.

##### 4.1.2.3. Constraints.

Las restricciones del proyecto influyen en las decisiones arquitectónicas y se derivan del contexto del desarrollo y los recursos disponibles:

<table border="1">
  <thead>
    <tr>
      <th>Technical Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TS-001</td>
      <td>Uso de blockchain de bajo costo</td>
      <td>La plataforma debe utilizar una red blockchain de bajo costo para registrar votos, garantizando accesibilidad económica para comunidades pequeñas.</td>
      <td>- La red blockchain seleccionada tiene costos de transacción menores a 0.01 USD por voto.<br>- Las transacciones de votación son visibles y verificables en la red pública.</td>
      <td>E4</td>
    </tr>
    <tr>
      <td>TS-002</td>
      <td>Soporte para conectividad limitada</td>
      <td>La plataforma debe permitir a los votantes emitir votos en zonas con conectividad limitada, asegurando accesibilidad en áreas rurales.</td>
      <td>- Los votos se almacenan localmente y se sincronizan cuando hay conexión.<br>- El sistema soporta conexiones intermitentes sin pérdida de datos.</td>
      <td>E3</td>
    </tr>
    <tr>
      <td>TS-003</td>
      <td>Cumplimiento con regulaciones locales</td>
      <td>La plataforma debe cumplir con las normativas electorales peruanas, integrándose con sistemas como RENIEC para validar identidades.</td>
      <td>- La validación de identidad es compatible con bases de datos de RENIEC.<br>- Los procesos cumplen con las normativas de ONPE para auditoría electoral.</td>
      <td>E2</td>
    </tr>
    <tr>
      <td>TS-004</td>
      <td>Limitaciones de presupuesto</td>
      <td>La solución debe desarrollarse con tecnologías de bajo costo o gratuitas debido a las restricciones financieras del proyecto.</td>
      <td>- Se utilizan herramientas open-source o servicios gratuitos (e.g., Polygon, Vercel).<br>- Los costos operativos mensuales no exceden los 50 USD durante la fase inicial.</td>
      <td>E1</td>
    </tr>
    <tr>
      <td>TS-005</td>
      <td>Tiempo de desarrollo ajustado</td>
      <td>El sistema debe ser implementado dentro del ciclo académico 2024-02, respetando las fechas límite del proyecto.</td>
      <td>- Las funcionalidades críticas (E1-E5) están implementadas antes del final del ciclo.<br>- El sistema pasa las pruebas de validación con usuarios antes de la entrega final.</td>
      <td>E1</td>
    </tr>
    <tr>
      <td>TS-006</td>
      <td>Capacidades técnicas del equipo</td>
      <td>La arquitectura debe basarse en tecnologías que el equipo domine (React, Node.js, Solidity, MongoDB) para garantizar un desarrollo eficiente.</td>
      <td>- Todos los componentes se desarrollan con tecnologías conocidas por el equipo.<br>- No se requiere aprendizaje de nuevas tecnologías que retrasen el proyecto.</td>
      <td>E1</td>
    </tr>
  </tbody>
</table>

#### 4.1.3. Architectural Drivers Backlog.
template
#### 4.1.4. Architectural Design Decisions.
template
#### 4.1.5. Quality Attribute Scenario Refinements.
template

### 4.2. Strategic-Level Domain-Driven Design.

El equipo VoteChain decidió utilizar una estrategia basada Domain-Driven Design (DDD) para poder comprender y estructurar el dominio del problema.  Esta manera de trabajar nos ayudó a que el diseño del sistema se adaptara mejor a lo que realmente necesitaban los usuarios, lo que a su vez hizo más fácil llevar a cabo votaciones que tuvieran sentido y aportaran valor al negocio.

Para lograr esto, nos concentramos en identificar los momentos importantes dentro del sistema, definir claramente los diferentes entornos o bounded contexts que eran relevantes, diseñar cómo se comunicarían esos entornos entre sí y establecer con exactitud dónde empezaba y terminaba cada parte del sistema. Esta forma de abordar el problema no solo nos permitió entender mejor cómo funcionaba internamente todo el sistema de votación para la comunidad, sino que también nos ayudó a crear una arquitectura que fuera lógica, que pudiera crecer sin problemas y que realmente respondiera a las necesidades de los usuarios.

A continuación, se detallará paso a paso las actividades realizadas en cada etapa de este proceso de Domain-Driven Design a nivel estratégico, desde la primera lluvia de ideas con EventStorming hasta que finalmente mapeamos todos los contextos.

#### 4.2.1. EventStorming.

Para empezar a comprender el funcionamiento de VoteChain, llevamos a cabo una reunión llamada EventStorming, la cual nos sirvió para tener una visión clara de los sucesos más relevantes dentro del sistema. En esta actividad donde todos participamos, pudimos identificar sin confusiones qué pasa desde el momento en que se planea una votación hasta que se dan a conocer los resultados.  Esta dinámica nos permitió encontrar los aspectos cruciales del proceso y establecer el punto de partida para diseñar el sistema de una manera más exacta.

**Unstructured Exploration**
En la fase de Unstructured Exploration, el equipo identificó libremente los eventos y acciones clave relacionados con el proceso de votación, sin seguir aún una estructura definida. Esto permitió una comprensión inicial más abierta del dominio.

<p align="center">
  <img src="img/UnstructuredExplorationVoteChain.jpg" alt="Unstructured Exploration Diagram" width="600"/>
</p>

**Pain Points**
En esta sección identificamos los principales puntos de dolor a partir de la exploración inicial del dominio. Estas preguntas nos permitieron detectar desafíos dentro del proceso de votación, orientándonos hacia áreas que requieren flujos de trabajo más claros, mayor seguridad y una mejor experiencia para el usuario.

<p align="center">
  <img src="img/PainPointsVoteChain.jpg" alt="Pain Points Diagram" width="600"/>
</p>

**Timelines**
Como parte de la fase de Timelines en el EventStorming. Esta línea de tiempo refleja cómo se llevaría a cabo una votación usando VoteChain, desde la creación del evento hasta la publicación de resultados.

<p align="center">
  <img src="img/TimelineVoteChain.jpg" alt="Timeline Diagram" width="600"/>
</p>

**Pivotal Points**
En la fase de Pivotal Points dentro del EventStorming, buscamos destacar los momentos clave de decisión o cambio en el flujo de eventos, aquellos que tienen impacto fuerte en el sistema o representan riesgos, validaciones críticas o transiciones importantes.

<p align="center">
  <img src="img/PivotalPointsVoteChain.jpg" alt="Pivotal Points Diagram" width="600"/>
</p>

**Commands**
En esta etapa del EventStorming, identificamos los comandos clave que representan las acciones iniciadas por los usuarios o el sistema, las cuales dan lugar a eventos importantes dentro del flujo de votación. Estos comandos nos permiten entender cómo se desencadenan los distintos momentos del proceso y facilitan el diseño de una solución coherente y centrada en las interacciones reales.

<p align="center">
  <img src="img/CommandsVoteChain.jpg" alt="Commands Diagram" width="600"/>
</p>

**Policies**
En esta etapa, definimos las políticas que rigen en los eventos mostrados.

<p align="center">
  <img src="img/PoliciesVoteChain.jpg" alt="Policies Diagram" width="600"/>
</p>

**Read Model**
En esta etapa, se refleja lo que el usuario ve en pantalla: los datos que se muestran, cómo se organizan y cómo están disponibles para facilitar su experiencia.

<p align="center">
  <img src="img/ReadModelVoteChain.jpg" alt="Read Models Diagram" width="600"/>
</p>

**External Systems**
En esta etapa, se identifica los sistemas externos con los que nuestra solución interactúa directamente. Estos sistemas cumplen funciones específicas fuera del alcance interno del dominio, como la verificación de identidad, el envío de correos electrónicos, el almacenamiento en blockchain y la generación de reportes.

<p align="center">
  <img src="img/ExternalSystemsVoteChain.jpg" alt="External Systems Diagram" width="600"/>
</p>

**Aggregates**
En este punto, los Aggregates definen unidades clave dentro del dominio de votaciones, agrupando comandos y reglas específicas que aseguran la coherencia de cada proceso, como el registro de votantes o la emisión de votos.

<p align="center">
  <img src="img/AggregatesVoteChain.jpg" alt="Aggregates Diagram" width="600"/>
</p>

**Bounded Contexts**
En esta útima etapa, los Bounded Contexts, nos permitieron dividir el sistema en áreas funcionales, facilitando la organización del modelo de dominio y resaltando los límites entre procesos como la autenticación, la gestión de votaciones o la publicación de resultados

<p align="center">
  <img src="img/BoundedContextsVoteChain.jpg" alt="Bounded Contexts Diagram" width="600"/>
</p>

#### 4.2.2. Candidate Context Discovery.

Ahora, se identifican posibles límites dentro del dominio del problema. A partir de lo aprendido en el Event Storming, el equipo propone agrupaciones lógicas que podrían convertirse en Bounded Contexts, ayudando a organizar mejor las responsabilidades y facilitar futuras decisiones técnicas.

**Voting Management**

<p align="center">
  <img src="img/VotingManagement.jpg" alt="Voting Management Diagram" width="600"/>
</p>

**Voter Access & Authentication**

<p align="center">
  <img src="img/VoterAccess&Authentication.jpg" alt="Voter Access Authentication Diagram" width="600"/>
</p>

**Vote Submission Management**

<p align="center">
  <img src="img/VoteSubmissionManagement.jpg" alt="Vote Submission Management Diagram" width="600"/>
</p>

**Vote Results Management**

<p align="center">
  <img src="img/VoteResultsManagement.jpg" alt="Vote Results Management Diagram" width="600"/>
</p>

**Vote Notification Management**

<p align="center">
  <img src="img/VoteNotificationManagement.jpg" alt="Vote Notification Management Diagram" width="600"/>
</p>

#### 4.2.3. Domain Message Flows Modeling.

En VoteChain, nos permite entender cómo se comunican las diferentes partes del sistema (bounded contexts) para llevar a cabo acciones importantes como registrar a un votante, verificar su identidad y permitir que emita su voto.  Utilizando diagramas de "Narración del Dominio", representamos de forma sencilla cómo viajan los mensajes, las órdenes y los eventos entre los usuarios, los sistemas y los servicios. Esto nos asegura que toda la lógica detrás del proceso funcione de manera coordinada y de acuerdo con las reglas del negocio.

**Voter Register**

<p align="center">
  <img src="img/VoterRegister.jpg" alt="Voter Register Diagram" width="600"/>
</p>

**Submitting a Vote**

<p align="center">
  <img src="img/SubmittingAVote.jpg" alt="Submitting a vote Diagram" width="600"/>
</p>

#### 4.2.4. Bounded Context Canvases.

**Voter Access & Authentication System**

<p align="center">
  <img src="img/BDCanvasVoterAcces&Authentication.jpg" alt="Bounded Context Canvas Voter Access & Authentication Diagram" width="600"/>
</p>

**Voting Management System**

<p align="center">
  <img src="img/BDCanvasVoting.jpg" alt="Bounded Context Canvas Voting Management Diagram" width="600"/>
</p>

**Vote Submission Management System**

<p align="center">
  <img src="img/BDCanvasVoteSubmission.jpg" alt="Bounded Context Canvas Vote Submission Management Diagram" width="600"/>
</p>

**Vote Results Management System**

<p align="center">
  <img src="img/BDCanvasVoteResults.jpg" alt="Bounded Context Canvas Vote Results Management Diagram" width="600"/>
</p>

**Vote Notification Management System**

<p align="center">
  <img src="img/BDCanvasVoteNotification.jpg" alt="Bounded Context Canvas Notification Management Diagram" width="600"/>
</p>

#### 4.2.5. Context Mapping.

En esta sección se representa gráficamente la forma en la que los distintos Bounded Contexts del sistema VoteChain interactúan y se relacionan entre sí. A través del Context Mapping, se analiza cómo fluyen los datos, qué dependencias existen y qué patrones estratégicos del Domain-Driven Design se aplican, como Customer/Supplier, Conformist, o Shared Kernel. Este mapeo permite entender mejor los límites y responsabilidades de cada contexto, así como identificar oportunidades de mejora, desacoplamiento y evolución arquitectónica del sistema.

<p align="center">
  <img src="img/ContextMapping.png" alt="Context Mapping Diagram" width="600"/>
</p>

### 4.3. Software Architecture.
template
#### 4.3.1. Software Architecture System Landscape Diagram.
template
#### 4.3.1. Software Architecture Context Level Diagrams.
template
#### 4.3.2. Software Architecture Container Level Diagrams.
template
#### 4.3.3. Software Architecture Deployment Diagrams.
template

## Anexos y Bibliografía 
## Student Outcome
