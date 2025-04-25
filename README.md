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

El Architectural Drivers Backlog es el resultado de las discusiones y decisiones tomadas en el proceso de Attribute-Driven Design (ADD) para el proyecto VoteChain. En este proceso, se identificaron los drivers arquitectónicos clave que guiarán el diseño del sistema. Estos drivers se seleccionaron considerando tanto los requisitos funcionales como los atributos de calidad y las restricciones técnicas más relevantes para los usuarios (organizadores y votantes) y el contexto del proyecto. A lo largo de varias iteraciones, el equipo acordó priorizar aquellos drivers que son de alta importancia para los stakeholders y que impactan significativamente en la complejidad técnica de la arquitectura.

A continuación, se presenta el Architectural Drivers Backlog que incluye los Functional Drivers, Quality Attribute Drivers y las Constraints seleccionadas:

<table border="1">
  <thead>
    <tr>
      <th>Driver ID</th>
      <th>Título del Driver</th>
      <th>Descripción</th>
      <th>Importancia para Stakeholders</th>
      <th>Impacto en Architectural Technical Complexity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>FD-001</td>
      <td>Seguridad y anonimato de votos</td>
      <td>El sistema debe garantizar que los votos sean anónimos, encriptados y resistentes a manipulaciones, utilizando tecnología blockchain para proteger la integridad del proceso electoral.</td>
      <td>High</td>
      <td>High</td>
    </tr>
    <tr>
      <td>FD-002</td>
      <td>Registro inmutable en blockchain</td>
      <td>El sistema debe registrar cada voto como una transacción inmutable en una red blockchain, permitiendo auditorías públicas y previniendo fraudes.</td>
      <td>High</td>
      <td>High</td>
    </tr>
    <tr>
      <td>FD-003</td>
      <td>Auditabilidad pública en tiempo real</td>
      <td>El sistema debe ofrecer un panel público que permita a ciudadanos y auditores verificar los resultados de las votaciones en tiempo real, asegurando transparencia.</td>
      <td>High</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>FD-004</td>
      <td>Disponibilidad durante votaciones</td>
      <td>El sistema debe estar disponible para los votantes durante los períodos de votación, incluso bajo picos de tráfico, para garantizar la participación.</td>
      <td>High</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>FD-005</td>
      <td>Validación segura de identidad</td>
      <td>El sistema debe validar la identidad de los votantes de manera segura, integrándose con bases de datos locales como RENIEC, para garantizar la autenticidad de los participantes.</td>
      <td>High</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>FD-006</td>
      <td>Usabilidad para usuarios no técnicos</td>
      <td>El sistema debe ofrecer una interfaz intuitiva y accesible, optimizada para dispositivos móviles, que permita a usuarios con conocimientos técnicos limitados votar sin asistencia.</td>
      <td>Medium</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>FD-007</td>
      <td>Escalabilidad para grandes votaciones</td>
      <td>El sistema debe ser capaz de soportar votaciones con hasta 10,000 votantes simultáneos, escalando sin comprometer el rendimiento.</td>
      <td>Medium</td>
      <td>High</td>
    </tr>
    <tr>
      <td>FD-008</td>
      <td>Soporte para conectividad limitada</td>
      <td>El sistema debe permitir a los votantes emitir votos en zonas con conectividad limitada, soportando modos offline y sincronización posterior.</td>
      <td>Medium</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>FD-009</td>
      <td>Costo reducido de operación</td>
      <td>El sistema debe operar con costos mínimos, utilizando tecnologías de bajo costo como Polygon con gas patrocinado, para garantizar viabilidad económica.</td>
      <td>Medium</td>
      <td>Low</td>
    </tr>
    <tr>
      <td>FD-010</td>
      <td>Cumplimiento con regulaciones locales</td>
      <td>El sistema debe cumplir con las normativas electorales peruanas, integrándose con sistemas como ONPE y RENIEC para validación y auditoría.</td>
      <td>Medium</td>
      <td>Medium</td>
    </tr>
  </tbody>
</table>

#### 4.1.4. Architectural Design Decisions.

El proceso de toma de decisiones de diseño arquitectónico se llevó a cabo en varias iteraciones del Attribute-Driven Design (ADD), donde se evaluaron distintos patrones arquitectónicos y tácticas para abordar los Architectural Drivers priorizados. A lo largo de estas iteraciones, el equipo consideró cuidadosamente los pros y contras de cada patrón candidato, tomando decisiones con base en el impacto sobre los atributos de calidad (seguridad, disponibilidad, usabilidad, auditabilidad) y la complejidad técnica de cada controlador.

**Iteración 1: Seguridad y anonimato de votos (FD-001)**
<p>
Para este driver, se evaluaron patrones y tácticas que garanticen la protección de los votos y el anonimato de los votantes mediante el uso de tecnología blockchain.
</p>
<table border="1">
  <thead>
    <tr>
      <th>Driver ID</th>
      <th>Título del Driver</th>
      <th>Pattern 1: Blockchain Pública (Polygon)</th>
      <th>Pattern 2: Blockchain Privada</th>
    </tr>
    <tr>
      <th></th>
      <th></th>
      <th>Pro</th>
      <th>Con</th>
      <th>Pro</th>
      <th>Con</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>FD-001</td>
      <td>Seguridad y anonimato de votos</td>
      <td>Alta seguridad gracias a la inmutabilidad y descentralización.<br>Transacciones verificables públicamente.</td>
      <td>Costos asociados al gas (aunque mínimos en Polygon).<br>Dependencia de la red pública.</td>
      <td>Mayor control sobre los datos.<br>Menor exposición a ataques externos.</td>
      <td>Menor transparencia, ya que no es pública.<br>Alta complejidad para garantizar anonimato sin auditoría pública.</td>
    </tr>
  </tbody>
</table>
<p>
<b>Decisión:</b> Se seleccionó el patrón <b>Blockchain Pública (Polygon)</b> porque ofrece alta seguridad y transparencia, fundamentales para generar confianza en los votantes. Además, Polygon permite minimizar costos mediante el gas patrocinado, alineándose con las restricciones de presupuesto del proyecto.
</p>

**Iteración 2: Registro inmutable en blockchain (FD-002)**
<p>
Para este driver, se evaluaron patrones que permitan un registro eficiente e inmutable de los votos en blockchain, optimizando el rendimiento y la escalabilidad.
</p>
<table border="1">
  <thead>
    <tr>
      <th>Driver ID</th>
      <th>Título del Driver</th>
      <th>Pattern 1: Registro Directo en Blockchain</th>
      <th>Pattern 2: Batching de Transacciones</th>
    </tr>
    <tr>
      <th></th>
      <th></th>
      <th>Pro</th>
      <th>Con</th>
      <th>Pro</th>
      <th>Con</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>FD-002</td>
      <td>Registro inmutable en blockchain</td>
      <td>Alta integridad, ya que cada voto se registra como transacción individual.<br>Simplicidad en la implementación.</td>
      <td>Altos costos y latencia en picos de tráfico.<br>Limitaciones de escalabilidad.</td>
      <td>Reducción de costos y latencia al agrupar transacciones.<br>Mejor escalabilidad para grandes votaciones.</td>
      <td>Mayor complejidad en la implementación.<br>Retraso en la confirmación de votos individuales.</td>
    </tr>
  </tbody>
</table>
<p>
<b>Decisión:</b> Se seleccionó el patrón <b>Batching de Transacciones</b> para optimizar el rendimiento y soportar grandes votaciones (hasta 10,000 votantes simultáneos), alineándose con el driver de escalabilidad (FD-007). Polygon permite implementar batching de manera eficiente, reduciendo costos y latencia.
</p>

**Iteración 3: Auditabilidad pública en tiempo real (FD-003)**
<p>
Para este driver, se evaluaron patrones que permitan a ciudadanos y auditores verificar los resultados de las votaciones de forma transparente y en tiempo real.
</p>
<table border="1">
  <thead>
    <tr>
      <th>Driver ID</th>
      <th>Título del Driver</th>
      <th>Pattern 1: Panel Público con Web3.js</th>
      <th>Pattern 2: API REST con Base de Datos Centralizada</th>
    </tr>
    <tr>
      <th></th>
      <th></th>
      <th>Pro</th>
      <th>Con</th>
      <th>Pro</th>
      <th>Con</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>FD-003</td>
      <td>Auditabilidad pública en tiempo real</td>
      <td>Alta transparencia, ya que los datos se leen directamente de la blockchain.<br>Confianza garantizada para los usuarios.</td>
      <td>Mayor latencia en la consulta de datos.<br>Dependencia de la red blockchain.</td>
      <td>Consulta más rápida y eficiente.<br>Facilidad de implementación con tecnologías conocidas.</td>
      <td>Menor transparencia, ya que los datos no se leen directamente de la blockchain.<br>Riesgo de manipulación en la base de datos.</td>
    </tr>
  </tbody>
</table>
<p>
<b>Decisión:</b> Se seleccionó el patrón <b>Panel Público con Web3.js</b> porque garantiza la máxima transparencia y confianza al leer los datos directamente de la blockchain, lo que es esencial para los stakeholders de VoteChain.
</p>

**Iteración 4: Disponibilidad durante votaciones (FD-004)**
<p>
Para este driver, se evaluaron patrones que aseguren alta disponibilidad del sistema durante los períodos de votación, incluso bajo picos de tráfico.
</p>
<table border="1">
  <thead>
    <tr>
      <th>Driver ID</th>
      <th>Título del Driver</th>
      <th>Pattern 1: Microservicios con Balanceo de Carga</th>
      <th>Pattern 2: Monolito con Caché</th>
    </tr>
    <tr>
      <th></th>
      <th></th>
      <th>Pro</th>
      <th>Con</th>
      <th>Pro</th>
      <th>Con</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>FD-004</td>
      <td>Disponibilidad durante votaciones</td>
      <td>Alta disponibilidad y escalabilidad.<br>Independencia de servicios para evitar fallos en cascada.</td>
      <td>Mayor complejidad en la implementación y despliegue.<br>Curva de aprendizaje para el equipo.</td>
      <td>Simplicidad en la implementación.<br>Rápida configuración inicial.</td>
      <td>Menor escalabilidad.<br>Riesgo de fallo total si el monolito cae.</td>
    </tr>
  </tbody>
</table>
<p>
<b>Decisión:</b> Se seleccionó el patrón <b>Microservicios con Balanceo de Carga</b> para garantizar alta disponibilidad y escalabilidad, esenciales para soportar picos de tráfico durante las votaciones. El despliegue en la nube (AWS o Vercel) facilitará esta arquitectura.
</p>

**Iteración 5: Validación segura de identidad (FD-005)**
<p>
Para este driver, se evaluaron patrones que permitan una validación segura y confiable de la identidad de los votantes, cumpliendo con regulaciones locales.
</p>
<table border="1">
  <thead>
    <tr>
      <th>Driver ID</th>
      <th>Título del Driver</th>
      <th>Pattern 1: Autenticación con 2FA e Integración con RENIEC</th>
      <th>Pattern 2: Autenticación Local con Carga Manual de Padrones</th>
    </tr>
    <tr>
      <th></th>
      <th></th>
      <th>Pro</th>
      <th>Con</th>
      <th>Pro</th>
      <th>Con</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>FD-005</td>
      <td>Validación segura de identidad</td>
      <td>Alta seguridad mediante autenticación de dos factores.<br>Cumplimiento con regulaciones al integrarse con RENIEC.</td>
      <td>Dependencia de APIs externas.<br>Necesidad de permisos para acceder a RENIEC.</td>
      <td>Independencia de sistemas externos.<br>Implementación más rápida.</td>
      <td>Menor confiabilidad en la validación.<br>Riesgo de errores en la carga manual.</td>
    </tr>
  </tbody>
</table>
<p>
<b>Decisión:</b> Se seleccionó el patrón <b>Autenticación con 2FA e Integración con RENIEC</b> para garantizar la autenticidad de los votantes y cumplir con las normativas peruanas, priorizando la seguridad y la confianza.
</p>

#### 4.1.5. Quality Attribute Scenario Refinements.

Se realizó una priorización de los escenarios de atributos de calidad que guían las decisiones arquitectónicas. Estos escenarios se refinaron según su impacto en los Business Goals de VoteChain, con el objetivo de garantizar una solución robusta y eficiente que cumpla con las expectativas de los stakeholders (organizadores y votantes) y las regulaciones locales.

**Scenario Refinement for Scenario 1: Seguridad (FD-001)**
<table border="1">
  <tr>
    <td><b>Scenario(s):</b></td>
    <td>Detección y prevención de intentos de alteración de votos registrados en la blockchain.</td>
  </tr>
  <tr>
    <td><b>Business Goals:</b></td>
    <td>Garantizar la integridad y el anonimato de los votos para generar confianza en los procesos electorales digitales.</td>
  </tr>
  <tr>
    <td><b>Relevant Quality Attributes:</b></td>
    <td>Seguridad</td>
  </tr>
  <tr>
    <td rowspan="6"><b>Scenario Components</b></td>
    <td><b>Stimulus:</b> Intento de alterar un bloque de votos en la blockchain.</td>
  </tr>
  <tr>
    <td><b>Stimulus Source:</b> Atacante externo.</td>
  </tr>
  <tr>
    <td><b>Environment:</b> Plataforma en producción durante o después de una votación.</td>
  </tr>
  <tr>
    <td><b>Artifact [if known]:</b> Smart contracts en Polygon.</td>
  </tr>
  <tr>
    <td><b>Response:</b> El sistema detecta la inconsistencia mediante verificación de hashes y notifica a los administradores.</td>
  </tr>
  <tr>
    <td><b>Response Measure:</b> 100% de los intentos de alteración son detectados en menos de 500 ms, con alertas enviadas en menos de 1 segundo.</td>
  </tr>
  <tr>
    <td><b>Questions:</b></td>
    <td>¿Cómo garantizamos que las alertas lleguen a los administradores en tiempo real? ¿Qué mecanismos de respuesta se implementarán ante un ataque detectado?</td>
  </tr>
  <tr>
    <td><b>Issues:</b></td>
    <td>Dependencia de la red Polygon para la verificación de hashes. Posibles retrasos en la notificación si hay congestión en la red.</td>
  </tr>
</table>

**Scenario Refinement for Scenario 2: Auditabilidad (FD-003)**
<table border="1">
  <tr>
    <td><b>Scenario(s):</b></td>
    <td>Verificación pública de los resultados electorales en tiempo real.</td>
  </tr>
  <tr>
    <td><b>Business Goals:</b></td>
    <td>Proveer transparencia y confianza a los ciudadanos y auditores mediante el acceso a datos verificables de la votación.</td>
  </tr>
  <tr>
    <td><b>Relevant Quality Attributes:</b></td>
    <td>Auditabilidad</td>
  </tr>
  <tr>
    <td rowspan="6"><b>Scenario Components</b></td>
    <td><b>Stimulus:</b> Solicitud de auditoría de bloques de votos.</td>
  </tr>
  <tr>
    <td><b>Stimulus Source:</b> Ciudadano o auditor autorizado.</td>
  </tr>
  <tr>
    <td><b>Environment:</b> Plataforma en producción durante o después de una votación.</td>
  </tr>
  <tr>
    <td><b>Artifact [if known]:</b> Panel público con Web3.js.</td>
  </tr>
  <tr>
    <td><b>Response:</b> El sistema proporciona acceso a los registros inmutables y sus hashes a través del panel público.</td>
  </tr>
  <tr>
    <td><b>Response Measure:</b> 100% de los bloques son verificables en menos de 3 minutos, con datos disponibles para descarga en formato JSON.</td>
  </tr>
  <tr>
    <td><b>Questions:</b></td>
    <td>¿Cómo optimizamos la velocidad de consulta en la blockchain para grandes volúmenes de datos? ¿Qué medidas tomamos si la red Polygon está congestionada?</td>
  </tr>
  <tr>
    <td><b>Issues:</b></td>
    <td>Latencia en la consulta de datos debido a la dependencia de la red Polygon. Necesidad de implementar caché para mejorar el rendimiento.</td>
  </tr>
</table>

**Scenario Refinement for Scenario 3: Disponibilidad (FD-004)**
<table border="1">
  <tr>
    <td><b>Scenario(s):</b></td>
    <td>Procesamiento de votos durante períodos de alta demanda.</td>
  </tr>
  <tr>
    <td><b>Business Goals:</b></td>
    <td>Asegurar que todos los votantes puedan emitir sus votos sin interrupciones, incluso bajo picos de tráfico.</td>
  </tr>
  <tr>
    <td><b>Relevant Quality Attributes:</b></td>
    <td>Disponibilidad</td>
  </tr>
  <tr>
    <td rowspan="6"><b>Scenario Components</b></td>
    <td><b>Stimulus:</b> Solicitud de voto desde un dispositivo móvil.</td>
  </tr>
  <tr>
    <td><b>Stimulus Source:</b> Votante autenticado.</td>
  </tr>
  <tr>
    <td><b>Environment:</b> Plataforma en producción durante el período de votación.</td>
  </tr>
  <tr>
    <td><b>Artifact [if known]:</b> Microservicios con balanceo de carga.</td>
  </tr>
  <tr>
    <td><b>Response:</b> El sistema procesa la solicitud y registra el voto en la blockchain.</td>
  </tr>
  <tr>
    <td><b>Response Measure:</b> 99.9% de disponibilidad, con un tiempo de respuesta promedio de 1.5 segundos bajo carga normal.</td>
  </tr>
  <tr>
    <td><b>Questions:</b></td>
    <td>¿Cómo manejamos picos extremos de tráfico que superen las 10,000 transacciones por minuto? ¿Qué mecanismos de monitoreo implementaremos para garantizar la disponibilidad?</td>
  </tr>
  <tr>
    <td><b>Issues:</b></td>
    <td>Costos asociados al escalado de microservicios en la nube. Posibles fallos en el balanceo de carga si no se configura correctamente.</td>
  </tr>
</table>

**Scenario Refinement for Scenario 4: Usabilidad (FD-006)**
<table border="1">
  <tr>
    <td><b>Scenario(s):</b></td>
    <td>Facilidad de uso para votantes con conocimientos técnicos limitados.</td>
  </tr>
  <tr>
    <td><b>Business Goals:</b></td>
    <td>Garantizar que los votantes puedan emitir sus votos de manera intuitiva y sin asistencia, promoviendo la adopción de la plataforma.</td>
  </tr>
  <tr>
    <td><b>Relevant Quality Attributes:</b></td>
    <td>Usabilidad</td>
  </tr>
  <tr>
    <td rowspan="6"><b>Scenario Components</b></td>
    <td><b>Stimulus:</b> Intento de emitir un voto desde un smartphone.</td>
  </tr>
  <tr>
    <td><b>Stimulus Source:</b> Votante no técnico.</td>
  </tr>
  <tr>
    <td><b>Environment:</b> Plataforma en producción, accesible desde dispositivos móviles.</td>
  </tr>
  <tr>
    <td><b>Artifact [if known]:</b> Interfaz móvil-first desarrollada en React.</td>
  </tr>
  <tr>
    <td><b>Response:</b> La interfaz guía al usuario paso a paso con instrucciones claras y un tutorial interactivo.</td>
  </tr>
  <tr>
    <td><b>Response Measure:</b> 95% de los usuarios completan el proceso de votación sin asistencia en menos de 3 minutos.</td>
  </tr>
  <tr>
    <td><b>Questions:</b></td>
    <td>¿Cómo validamos que la interfaz es intuitiva para usuarios no técnicos? ¿Qué métricas usaremos para medir la usabilidad durante las pruebas?</td>
  </tr>
  <tr>
    <td><b>Issues:</b></td>
    <td>Necesidad de pruebas extensivas con usuarios reales para alcanzar el 95% de éxito. Posibles limitaciones en dispositivos móviles antiguos.</td>
  </tr>
</table>

**Scenario Refinement for Scenario 5: Escalabilidad (FD-007)**
<table border="1">
  <tr>
    <td><b>Scenario(s):</b></td>
    <td>Soporte para grandes votaciones con votantes simultáneos.</td>
  </tr>
  <tr>
    <td><b>Business Goals:</b></td>
    <td>Asegurar que la plataforma pueda escalar para soportar votaciones de gran escala sin comprometer el rendimiento.</td>
  </tr>
  <tr>
    <td><b>Relevant Quality Attributes:</b></td>
    <td>Escalabilidad</td>
  </tr>
  <tr>
    <td rowspan="6"><b>Scenario Components</b></td>
    <td><b>Stimulus:</b> Picos de tráfico con 10,000 votantes simultáneos.</td>
  </tr>
  <tr>
    <td><b>Stimulus Source:</b> Múltiples votantes.</td>
  </tr>
  <tr>
    <td><b>Environment:</b> Plataforma en producción durante una votación masiva.</td>
  </tr>
  <tr>
    <td><b>Artifact [if known]:</b> Batching de transacciones en Polygon.</td>
  </tr>
  <tr>
    <td><b>Response:</b> El sistema procesa todas las transacciones sin caídas, utilizando batching para optimizar el rendimiento.</td>
  </tr>
  <tr>
    <td><b>Response Measure:</b> Soporta hasta 12,000 transacciones por minuto, con un tiempo de procesamiento promedio de 0.8 segundos por voto.</td>
  </tr>
  <tr>
    <td><b>Questions:</b></td>
    <td>¿Qué estrategias implementaremos para manejar picos superiores a 12,000 transacciones por minuto? ¿Cómo optimizamos el batching sin comprometer la integridad?</td>
  </tr>
  <tr>
    <td><b>Issues:</b></td>
    <td>Costos asociados al aumento de transacciones en Polygon. Posible latencia en la confirmación de transacciones durante picos extremos.</td>
  </tr>
</table>

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
#### 4.3.1. Software Architecture System Landscape Diagram.

Esta vista representa el panorama general del sistema VoteChain en relación con su ecosistema. Permite identificar los principales actores externos, ya sean personas o sistemas, y muestra cómo interactúan con la plataforma.

<p align="center">
  <img src="img/SoftwareArchitectureSystemLandscapeDiagram.png" alt="System Landscape Diagram" width="600"/>
</p>

#### 4.3.2. Software Architecture Context Level Diagrams.

En esta sección, se ubica al sistema como el núcleo del diagrama. 

<p align="center">
  <img src="img/SoftwareArchitectureContextLevelDiagrams..png" alt="Context Level Diagram" width="600"/>
</p>

#### 4.3.3. Software Architecture Container Level Diagrams.

El diagrama de contenedores descompone a VoteChain en sus elementos de alto nivel, conocidos como containers.

<p align="center">
  <img src="img/SoftwareArchitectureContainerLevelDiagrams..png" alt="Container Level Diagram" width="600"/>
</p>

#### 4.3.4. Software Architecture Deployment Diagrams.

<p align="center">
  <img src="img/SoftwareArchitectureDeploymentDiagrams.png" alt="Deployment Diagram" width="600"/>
</p>

## Anexos y Bibliografía 
## Student Outcome
