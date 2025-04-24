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
|   -  |    -    |
|  Bernardo Eusebio, Alessandro Joaquin  |    u202113640    |
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
## 3.1. To-Be Scenario Mapping

  A continuación, se presenta el Mapeo de Escenarios Futuros desarrollado específicamente para este proyecto. Este mapa ofrece una visión estructurada sobre la implementación de mejoras y transformaciones en los procesos y sistemas. Seguidamente, se muestra su       representación gráfica.
  
**Segmento: Organizadores de votación comunitaria** 

<p align="center">
  <img src="img/to be scenario map.jpg">
</p>

**Segmento: Ciudadanos votantes** 

<p align="center">
  <img src="img/to be scenario map 2.jpg">
</p>

## 3.2. User Stories
  <table border="1">
  <thead>
    <tr>
      <th>ID</th>
      <th>Épica</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>E1</td>
      <td>Configuración de votaciones descentralizadas</td>
    </tr>
    <tr>
      <td>E2</td>
      <td>Autenticación segura de votantes</td>
    </tr>
    <tr>
      <td>E3</td>
      <td>Emisión de votos anónimos y encriptados</td>
    </tr>
    <tr>
      <td>E4</td>
      <td>Registro inmutable en blockchain</td>
    </tr>
    <tr>
      <td>E5</td>
      <td>Auditoría pública en tiempo real</td>
    </tr>
    <tr>
      <td>E6</td>
      <td>Visualización y publicación de resultados</td>
    </tr>
  </tbody>
</table>

<table border="1">
  <thead>
    <tr>
      <th>Epic / Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="5"><strong>Épica E1: Configuración de votaciones descentralizadas</strong><br>
        Como ciudadano<br>
        Quiero configuración de votaciones descentralizadas<br>
        Para participar de manera confiable y segura en elecciones digitales.
      </td>
    </tr>
    <tr>
      <td>E01_US001</td>
      <td>Definir parámetros de elección</td>
      <td>COMO administrador QUIERO establecer parámetros básicos (nombre, fechas, tipo) PARA iniciar una nueva votación.</td>
      <td>Escenario: En panel de configuración.<br>
        Dado que el administrador accede al panel,<br>
        Cuando completa los campos requeridos,<br>
        Entonces puede guardar los parámetros iniciales.
      </td>
      <td>E1</td>
    </tr>
    <tr>
      <td>E01_US002</td>
      <td>Selección de tipo de elección</td>
      <td>COMO administrador QUIERO elegir entre distintos tipos de votaciones PARA adaptarlas a distintas necesidades.</td>
      <td>Dado que el administrador accede al panel,<br>
        Cuando selecciona el tipo de elección,<br>
        Entonces el sistema adapta los campos requeridos.
      </td>
      <td>E1</td>
    </tr>
    <tr>
      <td>E01_US003</td>
      <td>Crear estructura de votación</td>
      <td>COMO administrador QUIERO definir la estructura de cargos o preguntas PARA estructurar adecuadamente la votación.</td>
      <td>Dado que el administrador está creando una elección,<br>
        Cuando agrega una estructura,<br>
        Entonces se visualiza en la vista previa.
      </td>
      <td>E1</td>
    </tr>
    <tr>
      <td>E01_US004</td>
      <td>Guardar configuraciones iniciales</td>
      <td>COMO administrador QUIERO guardar toda la configuración PARA reutilizarla en el futuro.</td>
      <td>Dado que completó la configuración,<br>
        Cuando selecciona guardar,<br>
        Entonces el sistema confirma que se guardó correctamente.
      </td>
      <td>E1</td>
    </tr>
    <tr>
      <td>E01_US005</td>
      <td>Validación de parámetros</td>
      <td>COMO administrador QUIERO que el sistema valide los parámetros ingresados PARA evitar errores.</td>
      <td>Dado que completó el formulario,<br>
        Cuando hace clic en guardar,<br>
        Entonces el sistema muestra errores si falta algún campo obligatorio.
      </td>
      <td>E1</td>
    </tr>
  </tbody>
</table>
==
<table border="1">
  <thead>
    <tr>
      <th>Epic / Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="5"><strong>Épica E2: Registro y autenticación de votantes</strong><br>
        Como votante<br>
        Quiero registrarme y autenticarme de manera segura<br>
        Para poder participar en las elecciones digitales.
      </td>
    </tr>
    <tr>
      <td>E02_US001</td>
      <td>Registro de votantes</td>
      <td>COMO votante QUIERO registrarme previamente PARA acceder a la votación.</td>
      <td>Dado que estoy en la plataforma,<br>
        Cuando ingreso mis datos,<br>
        Entonces el sistema debe validarlos y confirmar mi registro.
      </td>
      <td>E2</td>
    </tr>
    <tr>
      <td>E02_US002</td>
      <td>Envío de credenciales</td>
      <td>COMO votante QUIERO recibir credenciales únicas PARA acceder a la plataforma.</td>
      <td>Dado que el registro fue exitoso,<br>
        Cuando se generan credenciales,<br>
        Entonces el sistema las envía por un canal seguro.
      </td>
      <td>E2</td>
    </tr>
    <tr>
      <td>E02_US003</td>
      <td>Validación de identidad</td>
      <td>COMO sistema QUIERO validar la identidad del votante PARA garantizar la autenticidad del registro.</td>
      <td>Dado que un votante se registra,<br>
        Cuando el sistema verifica sus datos,<br>
        Entonces debe corroborarlos con bases oficiales.
      </td>
      <td>E2</td>
    </tr>
    <tr>
      <td>E02_US004</td>
      <td>Recuperación de credenciales</td>
      <td>COMO votante QUIERO recuperar mis credenciales PARA acceder si las pierdo.</td>
      <td>Dado que soy un votante registrado,<br>
        Cuando solicito recuperación,<br>
        Entonces el sistema verifica mi identidad y envía nuevas credenciales.
      </td>
      <td>E2</td>
    </tr>
    <tr>
      <td>E02_US005</td>
      <td>Autenticación de dos factores</td>
      <td>COMO votante QUIERO tener autenticación adicional PARA mayor seguridad en mi acceso.</td>
      <td>Dado que ingreso mis credenciales,<br>
        Cuando el sistema solicita un segundo factor,<br>
        Entonces debo completarlo para acceder.
      </td>
      <td>E2</td>
    </tr>
  </tbody>
</table>
==
<table border="1">
  <thead>
    <tr>
      <th>Epic / Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="5"><strong>Épica E3: Votación segura y verificable</strong><br>
        Como votante<br>
        Quiero que mi voto sea secreto, único y verificable<br>
        Para tener confianza en el proceso electoral digital.
      </td>
    </tr>
    <tr>
      <td>E03_US001</td>
      <td>Voto único y anónimo</td>
      <td>COMO votante QUIERO que mi voto sea único y anónimo PARA que no puedan asociarlo conmigo.</td>
      <td>Dado que ingreso al sistema,<br>
        Cuando voto,<br>
        Entonces mi identidad no se asocia con el voto emitido.
      </td>
      <td>E3</td>
    </tr>
    <tr>
      <td>E03_US002</td>
      <td>Encriptación del voto</td>
      <td>COMO votante QUIERO que mi voto esté encriptado PARA protegerlo de manipulaciones.</td>
      <td>Dado que elijo una opción,<br>
        Cuando se emite el voto,<br>
        Entonces se almacena encriptado con clave pública.
      </td>
      <td>E3</td>
    </tr>
    <tr>
      <td>E03_US003</td>
      <td>Confirmación de voto emitido</td>
      <td>COMO votante QUIERO recibir una confirmación de que mi voto fue recibido PARA asegurarme del proceso.</td>
      <td>Dado que termino de votar,<br>
        Cuando se envía el voto,<br>
        Entonces recibo una notificación de éxito.
      </td>
      <td>E3</td>
    </tr>
    <tr>
      <td>E03_US004</td>
      <td>Prevención de doble voto</td>
      <td>COMO votante QUIERO que el sistema impida votar más de una vez PARA garantizar la equidad.</td>
      <td>Dado que ya he votado,<br>
        Cuando intento votar otra vez,<br>
        Entonces el sistema lo impide.
      </td>
      <td>E3</td>
    </tr>
    <tr>
      <td>E03_US005</td>
      <td>Revisión previa al envío</td>
      <td>COMO votante QUIERO revisar mi selección antes de enviarla PARA confirmar mi decisión.</td>
      <td>Dado que seleccioné una opción,<br>
        Cuando hago clic en "Revisar",<br>
        Entonces veo un resumen antes de confirmar el envío.
      </td>
      <td>E3</td>
    </tr>
  </tbody>
</table>
==
<table border="1">
  <thead>
    <tr>
      <th>Epic / Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="5"><strong>Épica E4: Registro inmutable en Blockchain</strong><br>
        Como administrador del sistema<br>
        Quiero que los votos se almacenen en blockchain<br>
        Para garantizar la integridad e inmutabilidad de los resultados electorales
      </td>
    </tr>
    <tr>
      <td>E04_US001</td>
      <td>Guardado en blockchain</td>
      <td>COMO administrador QUIERO registrar los votos emitidos en la blockchain PARA evitar fraudes.</td>
      <td>Dado que un voto es emitido,<br>
        Cuando se procesa,<br>
        Entonces se registra en un bloque inmutable.
      </td>
      <td>E4</td>
    </tr>
    <tr>
      <td>E04_US002</td>
      <td>Verificación de bloques</td>
      <td>COMO administrador QUIERO verificar la integridad de los bloques PARA asegurar consistencia.</td>
      <td>Dado que hay bloques almacenados,<br>
        Cuando se revisa su hash,<br>
        Entonces no debe haber alteraciones.
      </td>
      <td>E4</td>
    </tr>
    <tr>
      <td>E04_US003</td>
      <td>Tiempos de registro optimizados</td>
      <td>COMO desarrollador QUIERO que el registro en blockchain sea eficiente PARA no afectar al rendimiento.</td>
      <td>Dado que se emite un voto,<br>
        Cuando se guarda,<br>
        Entonces debe demorar menos de 2 segundos en escribirse en el bloque.
      </td>
      <td>E4</td>
    </tr>
    <tr>
      <td>E04_US004</td>
      <td>Alerta por inconsistencia</td>
      <td>COMO administrador QUIERO recibir alertas si hay inconsistencias PARA actuar de inmediato.</td>
      <td>Dado que se detecta una alteración,<br>
        Cuando un hash no coincide,<br>
        Entonces se genera una alerta.
      </td>
      <td>E4</td>
    </tr>
    <tr>
      <td>E04_US005</td>
      <td>Registro de auditoría</td>
      <td>COMO desarrollador QUIERO mantener trazabilidad de los bloques PARA fines de auditoría.</td>
      <td>Dado que se registra un bloque,<br>
        Cuando se almacena,<br>
        Entonces queda visible su timestamp, hash y autor.
      </td>
      <td>E4</td>
    </tr>
  </tbody>
</table>
==
<table border="1">
  <thead>
    <tr>
      <th>Epic / Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="5"><strong>Épica E5: Transparencia y Auditoría Pública</strong><br>
        Como ciudadano y auditor<br>
        Quiero acceso transparente a los datos electorales<br>
        Para verificar la integridad del proceso democrático
      </td>
    </tr>
    <tr>
      <td>E05_US001</td>
      <td>Acceso público a resultados</td>
      <td>COMO ciudadano QUIERO acceder a los datos de votos en tiempo real PARA auditar la transparencia.</td>
      <td>Dado que se emiten votos,<br>
        Cuando accedo al panel público,<br>
        Entonces visualizo el recuento actualizado.
      </td>
      <td>E5</td>
    </tr>
    <tr>
      <td>E05_US002</td>
      <td>Trazabilidad de votos</td>
      <td>COMO auditor QUIERO ver la trazabilidad de los bloques PARA verificar la validez de los registros.</td>
      <td>Dado que accedo a un bloque,<br>
        Cuando lo abro,<br>
        Entonces visualizo su historial de cambios (si los hay).
      </td>
      <td>E5</td>
    </tr>
    <tr>
      <td>E05_US003</td>
      <td>Panel público interactivo</td>
      <td>COMO ciudadano QUIERO un panel visual PARA entender los resultados sin ser técnico.</td>
      <td>Dado que accedo a resultados,<br>
        Cuando entro al panel,<br>
        Entonces veo gráficos y datos entendibles.
      </td>
      <td>E5</td>
    </tr>
    <tr>
      <td>E05_US004</td>
      <td>Acceso a logs de actividad</td>
      <td>COMO auditor QUIERO ver los logs de actividad del sistema PARA detectar irregularidades.</td>
      <td>Dado que entro a la sección de auditoría,<br>
        Cuando consulto logs,<br>
        Entonces puedo filtrar por fechas y acciones.
      </td>
      <td>E5</td>
    </tr>
    <tr>
      <td>E05_US005</td>
      <td>Verificación cruzada</td>
      <td>COMO auditor QUIERO comparar datos entre nodos blockchain PARA asegurar integridad del sistema.</td>
      <td>Dado que consulto un bloque,<br>
        Cuando lo comparo con nodos espejos,<br>
        Entonces deben coincidir sus hashes.
      </td>
      <td>E5</td>
    </tr>
  </tbody>
</table>


- 3.3. Impact Mapping

<p align="center">
  <img src="img/impact map.jpg">
</p>

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
## Anexos y Bibliografía 
## Student Outcome
