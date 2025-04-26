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
      <table>
    <!-- Título -->
      <tr>
        <th colspan="6" valign="top"><b>Análisis Competitivo</b></th>
      </tr>

      <!-- Motivación del análisis -->
      <tr>
        <td rowspan="2" colspan="1" valign="top">¿Por qué llevar a cabo este Análisis?</td>
        <td colspan="5" valign="top">
          Este análisis permite identificar fortalezas, debilidades y “espacios
          libres” en el mercado de plataformas de votación blockchain, de modo que
          VoteChain priorice características, precios y mensajes de marketing que
          maximicen su adopción en comunidades peruanas y LATAM.
        </td>
      </tr>
      <tr></tr>

      <!-- Cabeceras de competidores (logo + nombre) -->
      <tr>
        <td colspan="2" valign="top"></td>
        <td valign="top">
          <p><b>VoteChain</b></p>
          <img width="130" src="img/logo.png"/>
        </td>
        <td valign="top">
          <p><b>Voatz</b></p>
          <img src="img/Voatz.png"/>
        </td>
        <td valign="top">
          <p><b>Polys</b></p>
          <img src="img/Polys.png"/>
        </td>
        <td valign="top">
          <p><b>Follow My Vote</b></p>
          <img src="img/followmyvote.png"/>
        </td>
      </tr>

      <!-- PERFIL -->
      <tr>
        <td rowspan="2" valign="top"><p>Perfil</p></td>
        <td valign="top">Overview</td>
        <td valign="top">Plataforma web peruana de votación descentralizada para barrios, universidades, municipios y ONGs.</td>
        <td valign="top">App móvil de voto remoto (iOS / Android) con biometría y cadena privada; pilotos en 8 estados EE. UU. y ligas deportivas.</td>
        <td valign="top">SaaS de Kaspersky con backend blockchain y urna física sincronizada; orientado a gobiernos, universidades y empresas.</td>
        <td valign="top">Solución OSS “end‑to‑end verifiable” sobre blockchain pública; instala‑se on‑premise o en la nube comunitaria.</td>
      </tr>
      <tr>
        <td valign="top">¿Qué valor ofrece a los clientes?</td>
        <td valign="top">Transparencia auditable, gas patrocinado y precios freemium.</td>
        <td valign="top">Permite sufragio seguro de electores remotos con biometría y auditoría postelectoral centralizada.</td>
        <td valign="top">Permite elecciones mixtas (online + presencial) con seguridad Kaspersky y despliegue rápido.</td>
        <td valign="top">Transparencia absoluta (código abierto), auditoría ciudadana y verificación individual del voto.</td>
      </tr>

      <!-- MARKETING -->
      <tr>
        <td rowspan="2" valign="top"><p>Perfil de Marketing</p></td>
        <td valign="top">Mercado objetivo</td>
        <td valign="top">Comunidades de Perú (barrios, universidades, municipios) con proyección Latinoamérica.</td>
        <td valign="top">Electores militares/discapacitados, convenciones partidarias, ligas deportivas US.</td>
        <td valign="top">Ayuntamientos, universidades europeas y cámaras empresariales.</td>
        <td valign="top">ONGs, comunidades pro-democracia y DAOs tecnológicas.</td>
      </tr>
      <tr>
        <td valign="top">Estrategias de marketing</td>
        <td valign="top">Alianzas ONPE / RENIEC; webinars en español; caso de éxito piloto barrial; plan freemium.</td>
        <td valign="top">Relaciones públicas con secretarías estatales; premios de accesibilidad; foco en voto móvil.</td>
        <td valign="top">Contenido de ciber‑seguridad Kaspersky; demos de urna; blog técnico.</td>
        <td valign="top">Campañas open‑source, hackathons y patrocinios de transparencia electoral.</td>
      </tr>

      <!-- PRODUCTO -->
      <tr>
        <td rowspan="3" valign="top"><p>Perfil de Producto</p></td>
        <td valign="top">Productos & Servicios</td>
        <td valign="top">Portal de creación de elecciones, smart‑contracts upgradable, informes en tiempo real.</td>
        <td valign="top">App voto, backend permissioned‑chain, kiosco tablet, portal autoridades y kit auditoría.</td>
        <td valign="top">Plataforma cloud, hardware de urna, votación por correo seguro, API REST.</td>
        <td valign="top">SDK OSS (app voto + app auditor), wallets multisig identidad, servidor verificable.</td>
      </tr>
      <tr>
        <td valign="top">Precios y costos</td>
        <td valign="top">Plan Comunidad (≤500 votos): gratis; Pro US$ 49/mes; Enterprise a medida.</td>
        <td valign="top">Modelo de licencia por jurisdicción + tarifa de soporte (no público).</td>
        <td valign="top">Pago por elección o licencia anual; hardware con coste adicional.</td>
        <td valign="top">Software libre; integración y soporte bajo contrato.</td>
      </tr>
      <tr>
        <td valign="top">Canales de distribución</td>
        <td valign="top">Web app y pasarelas locales (Yape/Plin).</td>
        <td valign="top">App stores y portal web de administración.</td>
        <td valign="top">Web app (cloud) más hardware dedicado.</td>
        <td valign="top">GitHub (auto‑hosting) y nube comunitaria.</td>
      </tr>

      <!-- SWOT -->
      <tr>
        <td rowspan="4" valign="top"><p>Análisis SWOT</p></td>
        <td valign="top">Fortalezas</td>
        <td valign="top">• Cumplimiento legal local<br/>• Gas patrocinado → coste ínfimo</td>
        <td valign="top">• Pilotos gubernamentales reales<br/>• Biometría integrada</td>
        <td valign="top">• Respaldo Kaspersky<br/>• Opción híbrida online/urna</td>
        <td valign="top">• Código 100 % abierto<br/>• Verificación individual E2E</td>
      </tr>
      <tr>
        <td valign="top">Debilidades</td>
        <td valign="top">• Capital limitado<br/></td>
        <td valign="top">• Código cerrado; cuestionamientos de transparencia</td>
        <td valign="top">• Percepción geopolítica (origen ruso)<br/>• Sin KYC integrado</td>
        <td valign="top">• Escasa tracción institucional<br/>• Financiamiento irregular</td>
      </tr>
      <tr>
        <td valign="top">Oportunidades</td>
        <td valign="top">• Ley de gobierno digital Perú<br/>• Mercado LATAM poco competido</td>
        <td valign="top">• Voto corporativo y sindical</td>
        <td valign="top">• Demanda post‑COVID de urnas híbridas</td>
        <td valign="top">• Alianzas DAO y ONG de transparencia</td>
      </tr>
      <tr>
        <td valign="top">Amenazas</td>
        <td valign="top">• Desconfianza pública en blockchain<br/>• Cambios regulatorios electorales</td>
        <td valign="top">• Auditorías negativas pueden frenar adopción</td>
        <td valign="top">• Posibles sanciones a empresas rusas</td>
        <td valign="top">• Competidores con mayor presupuesto</td>
      </tr>
      </table>
  - 2.1.2. Estrategias y tácticas frente a competidores

      - **Transparencia radical y código abierto**  
      Publicar el repositorio de VoteChain y las auditorías de smart‑contracts para contrastar con soluciones cerradas (Voatz, Polys).

    - **Precios freemium y gas patrocinado**  
      Plan Comunidad gratuito (≤ 500 votantes) y subsidio del gas en Polygon para romper barreras de entrada frente a licencias cerradas.

    - **Alianzas institucionales locales**  
      Convenios con ONPE, RENIEC y municipios piloto; certificación académica con universidades públicas para legitimidad regulatoria.

    - **Educación sobre la blockchain**  
      Webinars, bootcamps y kits de voto blockchain en español para líderes vecinales.

    - **Modo offline y diseño móvil‑first**  
      Acceso estable en zonas con conectividad limitada, ventaja frente a plataformas solo web o apps cerradas.

- 2.2. Entrevistas
  - 2.2.1. Diseño de entrevistas

    ### 1. Preguntas generales  
    - ¿Cuál es tu nombre?   
    - ¿Cuántos años tienes?   
    - ¿Cuál es tu ocupación o rol dentro de la comunidad o institución?   

    - ¿Con qué frecuencia participas en procesos de votación (organizando o votando)?  

    ---

    ### 2. Preguntas — **Segmento: Organizadores de votación comunitaria** 

    1. **Proceso actual** 

      - ¿Cómo gestionas hoy un proceso de votación?  

    2. **Herramientas y tecnología**  

      - ¿Qué herramientas estás utilizando y por qué?  

      - ¿Cuáles de esas herramientas te generan mayor confianza y cuáles menos?  

    3. **Desafíos principales**  

      - ¿Qué problemas enfrentas en términos de transparencia, seguridad o logística? 

      - ¿Cómo impactan el tiempo y el costo en tu capacidad de organizar elecciones?  

    4. **Transparencia y auditoría**  

      - ¿Qué tan fácil es para los votantes y observadores auditar los resultados que publicas?  

      - ¿Has recibido cuestionamientos sobre la legitimidad de una elección?  

    5. **Participación ciudadana**  

      - ¿Cómo motivas a que la gente participe?  

      - ¿Qué obstáculos ves para alcanzar una alta participación?  

    6. **Anonimato y privacidad**  

      - ¿En qué medida te preocupa que los votantes mantengan su anonimato?  

      - ¿Qué prácticas sigues para proteger sus datos personales?  

    7. **Características ideales**  

      - Si pudieras diseñar la plataforma perfecta, ¿qué funciones imprescindibles tendría?  

      - ¿Qué tipo de panel o métricas te ayudarían a supervisar mejor el proceso?  

    8. **Integración y soporte**  

      - ¿Necesitas que se integre con sistemas externos (RENIEC o padrones internos)? 

      - ¿Qué nivel de soporte técnico o capacitación esperarías del proveedor de la plataforma?  

    ---

    ### 3. Preguntas — **Segmento: Ciudadanos votantes** 

    1. **Experiencia de voto actual** 

      - ¿Cómo fue la última vez que votaste en tu comunidad?

      - ¿Qué tan satisfecho/a quedaste con ese proceso?  

    2. **Confianza y transparencia**  

      - ¿Confías en que tu voto se contó correctamente? 

      - ¿Qué evidencias o garantías necesitas para creer en el resultado final?  

    3. **Dificultades y barreras**  

      - ¿Has dejado de votar alguna vez por falta de tiempo, distancia, desconfianza o complejidad tecnológica?  

      - ¿Cuál es tu dispositivo de preferencia (móvil, computadora o ambos)?  

    4. **Anonimato y privacidad**  

      - ¿Qué tan importante es para ti que nadie pueda vincular tu identidad con tu voto?  

      - ¿Qué preocupaciones tienes sobre la seguridad de tus datos personales?  

    5. **Accesibilidad y facilidad de uso**  

      - ¿Prefieres instrucciones paso a paso, vídeos tutoriales u otro formato?  

    6. **Características deseadas** 
     
      - ¿Te gustaría recibir confirmación inmediata de que tu voto fue registrado?  

      - ¿Valoras poder consultar resultados en tiempo real o prefieres un anuncio oficial posterior?   

    7. **Percepción de tecnología blockchain**  
      - ¿Has oído hablar de la votación en blockchain? Y si es así ¿Qué opinas?

      - ¿Qué información o demostraciones te ayudarían a sentirte cómodo usando VoteChain?  

  - 2.2.2. Registro de entrevistas
    
    ### Segmento 1: Organizadores de votación comunitaria
    
     - Nombre: Luis Torres
       
     - Edad: 66 años
       
     - Ocupación: Lider de junta vecinal
       
     - Enlace: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202113640_upc_edu_pe/EULULKQDzrRDjYoEw8v_2ScBYDiAuc8vPjDNKV7qRYOusw?e=Len3sk&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
    
    <img src="img/entrevista1.PNG">

    <br/>

    - Nombre: Gustavo Zapata

    - Edad: 24 años

    - Ocupación: Presidente de una junta vecinal

    - Enlace: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202113745_upc_edu_pe/EWsgd1gutK5Os40hXVOUm0cB5ufQNNUl_ISlGoAFJVlyZA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=NrclhL

    <img src="img/entrevista2.png">

    <br/>
    
    ### Segmento 2: Ciudadanos votantes
    
  - 2.2.3. Análisis de entrevistas

    ### Segmento 1: Organizadores de votación comunitaria
 
     - Nombre: Luis Torres
   
     - Entrevistador: Alessandro Bernardo
       
        Luis Torres, coordinador electoral de una junta vecinal, gestiona las votaciones de forma semi-digital usando herramientas como Google Forms, Excel y WhatsApp. Los principales problemas incluyen la dificultad para garantizar la seguridad, la transparencia y la auditoría de los resultados. La falta de anonimato, la baja confianza en el proceso y el alto costo en horas voluntarias limitan la participación. Se busca un sistema ideal con autenticación segura, votación anónima pero verificable, conteo transparente y herramientas de supervisión en tiempo real. Estos desafíos generan desconfianza y cuestionamientos sobre la legitimidad de las elecciones.

    <br/>

     - Nombre: Gustavo Zapata

     - Entrevistador: Renzo Ramos

        Gustavo Zapata, es el presidente de una junta vecinal de su localidad, quien emplea herramientas tradicionales como la impresión de carteles y cédulas de votación. La única herramientas digital que domina es Word. Realizar estos procesos de votación le cuestan demasiado dinero. Le gustaría que existiera una herramienta donde pueda hacer seguimiento de la cantidad votos en tiempo real y segura.


    ### Segmento 2: Ciudadanos votantes

- 2.3. Needfinding
  - 2.3.1. User Personas
      - **Segmento: Organizadores de votación comunitaria**

        <img src="img/Persona 1.png">

      <br/>

      - **Segmento: Ciudadanos votantes**

        <img src="img/Persona 2.png">

      <br/>

  - 2.3.2. User Task Matrix
      - **Segmento: Organizadores de votación comunitaria**

        | Tarea | Frecuencia | Importancia |
        |-------|------------|-------------|
        | Crear un nuevo proceso de votación | Alta | Alta |
        | Configurar opciones, fechas y reglas de la elección | Alta | Alta |
        | Registrar o cargar el padrón electoral | Media | Alta |
        | Difundir la convocatoria a votación | Alta | Alta |
        | Supervisar la emisión de votos | Alta | Alta |
        | Verificar participación | Media | Alta |
        | Publicar resultados de forma transparente | Alta | Alta |
        | Generar reportes o actas para auditoría | Media | Alta |
        | Atender reclamos o disputas del proceso | Baja | Media |
        | Coordinar con instituciones (municipios, universidades) | Media | Media |

      - **Segmento: Ciudadanos votantes**

        | Tarea | Frecuencia | Importancia |
        |-------|------------|-------------|
        | Recibir convocatoria o notificación de elección | Alta | Alta |
        | Validar identidad y autenticarse para votar | Media | Alta |
        | Emitir voto de manera anónima desde un dispositivo | Alta | Alta |
        | Confirmar que el voto fue registrado correctamente | Alta | Alta |
        | Consultar resultados de la votación | Media | Alta |
        | Acceder a ayuda o tutoriales sobre cómo votar | Media | Media |
        | Confiar en que su voto será contado sin manipulaciones | Alta | Alta |
        | Reportar errores o problemas técnicos | Baja | Media |

  - 2.3.3. Empathy Mapping
       
       - **Segmento: Organizadores de votación comunitaria**
  
       </br>
       <img src="img/empathy-1.png">

       </br>

       - **Segmento: Ciudadanos votantes**
       
       </br> 
       <img src="img/empathy-2.png">

       </br>
  - 2.3.4. As-is Scenario Mapping

      Este apartado describe el escenario actual de los usuarios antes de utilizar VoteChain, identificando sus acciones, pensamientos y emociones durante los procesos de votación tradicionales.

      **Segmento objetivo: Organizadores de votación comunitaria**

      <img src="img/as-is-1.png"/>

      </br>

      **Segmento objetivo: Ciudadanos votantes**

      <img src="img/as-is-2.png"/>
- 2.4. Ubiquitous Language
    
    Para el desarrollo de nuestro proyecto, es esencial establecer un lenguaje claro y conciso que refleje las necesidades y expectativas de todos los usuarios. Por esta razón, hemos identificado los siguientes términos clave que serán utilizados de forma consistente por el equipo de negocio y de desarrollo.

    - **Comunidad:** Cualquier barrio, universidad u organización que crea y participa en una elección.  
    - **Organizador:** Usuario que configura reglas, padrón y calendario de votación.  
    - **Votante:** Miembro autorizado a emitir un voto único y anónimo.  
    - **Padrón electoral:** Listado cifrado de votantes, registrado en blockchain como hash verificable.  
    - **Boleta digital:** Voto firmado criptográficamente que se convierte en transacción.  
    - **Smart-contract:** Programa autoejecutable desplegado en una red blockchain que contiene reglas definidas por las partes.  
    - **Transacción:** Registro inmutable de un voto o acción administrativa.  
    - **Tablero de resultados:** Panel en tiempo real que lee eventos del smart-contract.  
    - **Auditoría pública:** Verificación independiente descargando la cadena y recomputando votos.  
    - **Gas patrocinado:** Modelo en el que la plataforma paga las comisiones para que el votante no necesite criptomonedas.
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
## Anexos y Bibliografía 
## Student Outcome
