# Project-report
<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Arquitecturas De Software Emergentes - 4283</strong><br>
    <strong>Profesor: Royer Edelwer Rojas Malasquez</strong><br>
    <br>INFORME
</p>
<p align="center">
    <strong>Startup:  TechSign</strong><br>
    <strong>Producto:  GloveTalk</strong>
</p>
    <h3 align="center">Team Members:</h3>
    </div>
<div>
     <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td></td>
            <td></td>
        </tr>
	<tr>
            <td>Llacchua Peralta, Joseph Ulysses</td>
            <td>u202317002</td>
        </tr>
        <tr>
            <td></td>
            <td> </td>
        </tr>
        <tr>
            <td></td>
            <td></td>
        </tr>
         <tr>
            <td></td>
            <td></td>
        </tr>
    </table>
</div>

<p align="center">
    <strong>2025</strong>
</p>

<br>

# Registro de Versiones del Informe
<table>
        <tr>
            <th style="text-align:center;">Versión</th>
            <th style="text-align:center;">Fecha</th>
            <th style="text-align:center;">Autor</th>
            <th style="text-align:center;">Descripción de la modificación</th>
        </tr>
        <tr>
            <td align = "center">TB1</td>
            <td>18/04/2025</td>
            <td> Grupo 1
            <td>Se agregó el contenido del capítulo 1, apartados 1.1, 1.2 y 1.3; el contenido del capítulo 2, apartados 2.1, 2.2, 2.3, 2.4; el contenido del capítulo 3, apartados 3.1, 3.2, 3.3 y 3.4; el contenido del capítulo 4, apartados 4.1 y 4.2</td>
        </tr>
</table>
<br>

# Tabla de Contenidos
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1. EventStorming](#411-eventstorming)
      - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
      - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Architecture](#413-software-architecture)
      - [4.1.3.1. System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
      - [4.1.3.2. Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
      - [4.1.3.3. Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
      - [4.1.3.4. Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
  - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.X. Bounded Context](#42x-bounded-context-bounded-context-name)
      - [4.2.X.1. Domain Layer](#42x1-domain-layer)
      - [4.2.X.2. Interface Layer](#42x2-interface-layer)
      - [4.2.X.3. Application Layer](#42x3-application-layer)
      - [4.2.X.4. Infrastructure Layer](#42x4-infrastructure-layer)
      - [4.2.X.5. Component Level Diagrams](#42x5-component-level-diagrams)
      - [4.2.X.6. Code Level Diagrams](#42x6-code-level-diagrams)
        - [4.2.X.6.1. Domain Layer Class Diagrams](#42x61-domain-layer-class-diagrams)
        - [4.2.X.6.2. Database Design Diagram](#42x62-database-design-diagram)
- [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
  - [5.1. Style Guidelines](#51-style-guidelines)
    - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
    - [5.1.2. Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)
  - [5.2. Information Architecture](#52-information-architecture)
    - [5.2.1. Organization Systems](#521-organization-systems)
    - [5.2.2. Labeling Systems](#522-labeling-systems)
    - [5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
    - [5.2.4. Searching Systems](#524-searching-systems)
    - [5.2.5. Navigation Systems](#525-navigation-systems)
  - [5.3. Landing Page UI Design](#53-landing-page-ui-design)
    - [5.3.1. Wireframe](#531-wireframe)
    - [5.3.2. Mock-up](#532-mock-up)
  - [5.4. Applications UX/UI Design](#54-applications-uxui-design)
    - [5.4.1. Wireframes](#541-wireframes)
    - [5.4.2. Wireflow Diagrams](#542-wireflow-diagrams)
    - [5.4.3. Mock-ups](#543-mock-ups)
    - [5.4.4. User Flow Diagrams](#544-user-flow-diagrams)
  - [5.5. Applications Prototyping](#55-applications-prototyping)
- [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
  - [6.1. Software Configuration Management](#61-software-configuration-management)
    - [6.1.1. Development Environment Configuration](#611-development-environment-configuration)
    - [6.1.2. Source Code Management](#612-source-code-management)
    - [6.1.3. Style Guide & Conventions](#613-style-guide--conventions)
    - [6.1.4. Deployment Configuration](#614-deployment-configuration)
  - [6.2. Implementation](#62-implementation)
    - [6.2.X. Sprint n](#62x-sprint-n)
      - [6.2.X.1. Sprint Planning](#62x1-sprint-planning)
      - [6.2.X.2. Aspect Leaders and Collaborators](#62x2-aspect-leaders-and-collaborators)
      - [6.2.X.3. Sprint Backlog](#62x3-sprint-backlog)
      - [6.2.X.4-8. Sprint Review Evidences](#62x4-8-sprint-review-evidences)
      - [6.2.X.9. Team Collaboration Insights](#62x9-team-collaboration-insights)
  - [6.3. Validation Interviews](#63-validation-interviews)
    - [6.3.1. Diseño](#631-diseño)
    - [6.3.2. Registro](#632-registro)
    - [6.3.3. Evaluaciones](#633-evaluaciones)
  - [6.4. Video About-the-Product](#64-video-about-the-product)
- [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

---

# Student Outcome

| Student Name | Contribution Summary |
|--------------|----------------------|
|              |                      |

---

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de integrantes del equipo

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

#### 2.1.1 Análisis competitivo

|                                                         | **GloveTalk**                                                                                                                               | **SignAloud**                                                                                                                           | **SignAll**                                                                                                                      | **MotionSavvy**                                                                                                                                                 |
| ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **PERFIL**                                              |                                                                                                                                             |                                                                                                                                           |                                                                                                                                  |                                                                                                                                                                  |
| **Overview**                                            | Guante IoT con sensores que traducen la lengua de señas peruana en audio en tiempo real, respaldado por Deep Learning.                       | Guantes que traducen American Sign Language en texto y voz, desarrollados por estudiantes de la University of Washington.                    | Sistema de traducción automática de ASL basado en visión por computadora y NLP, utilizando cámaras y guantes marcados.            | UNI es un dispositivo portátil que utiliza tecnología Leap Motion en una funda para tablet que traduce lenguaje de señas a voz y texto. |
| **Ventaja competitiva** ¿Qué valor ofrece a los clientes? | Adaptación al contexto peruano y validación en instituciones locales; combinación de hardware y software.                                     | Ligero, ergonómico y premiado con el Lemelson-MIT Student Prize por su innovación.                                                       | Primera solución comercial que cubre todo el flujo de traducción sin necesidad de hardware especializado adicional.               | Permite comunicación bidireccional (señas↔texto/voz) sin Internet, actualizable vía crowdsourcing de nuevos gestos. |
| **PERFIL DE MARKETING**                                 |                                                                                                                                             |                                                                                                                                           |                                                                                                                                  |                                                                                                                                                                  |
| **Mercado Objetivo**                                    | Personas con discapacidad auditiva o del habla en Perú, sus familias, instituciones educativas y centros de rehabilitación.                  | Comunidades ASL en EE. UU. y entornos académicos (universidades, laboratorios).                                                         | Instituciones educativas y empresas en EE. UU. que requieren traducción en tiempo real.                                         | Personas sordas y oyentes en entornos cotidianos que necesitan comunicación fluida; sectores educativos y profesionales. |
| **Estrategias de Marketing**                            | Alianzas con instituciones educativas y de salud; pilotos gratuitos y campañas de concientización en redes locales.                        | Demostraciones en ferias tecnológicas y hackatones; cobertura en medios especializados (UW Today).                                       | Pilotos en bibliotecas y universidades (Gallaudet, PVAMU); partnership con Microsoft BizSpark.                                  | Crowdfunding en Indiegogo con early-birds, prensa en Forbes/CBS, y demostraciones en eventos de tecnología asistiva. |
| **PERFIL DE PRODUCTO**                                  |                                                                                                                                             |                                                                                                                                           |                                                                                                                                  |                                                                                                                                                                  |
| **Productos & Servicios**                               | Guante inteligente IoT + algoritmo de Deep Learning + dashboards web para seguimiento y análisis de uso en tiempo real.                    | Par de guantes con sensores de movimiento que envían datos vía Bluetooth a un computador para traducir gestos.                           | Workstation con cámaras y guantes marcados + SDK y chat app para traducción instantánea.                                       | Funda para tablet con Leap Motion + app móvil que reconoce gestos y traduce a texto/voz al instante. |
| **Precios & Costos**                                    | Modelo freemium con licencias institucionales y subsidios para el mercado peruano.                                                           | Prototipo en fase de investigación; no comercializado.                                                                                     | Disponible bajo lista de espera; precios no divulgados públicamente.                                                           | Early-bird en Indiegogo a USD 198; precio de lista USD 499, suscripción mensual USD 19.99 (futuro retail USD 499). |
| **Canales de distribución (Web y/o Móvil)**             | Web (landing page), distribuidores locales, API pública.                                                                                     | UW CoMotion MakerSpace y eventos académicos; no venta abierta.                                                                            | Descarga de demos vía web; demos presenciales en eventos.                                                                       | Indiegogo, sitio web oficial y distribución de apps en tablet preconfiguradas. |
| **ANÁLISIS SWOT**                                        |                                                                                                                                             |                                                                                                                                           |                                                                                                                                  |                                                                                                                                                                  |
| **Fortalezas**                                          | Enfoque local, adaptado a LSP; integración hardware-software; validación en campo.                                                           | Premiado con Lemelson-MIT; diseño ergonómico; uso de sensores precisos.                                                                  | Precisión (>99%) gracias a IA y visión por computadora; cobertura de oraciones completas.                                       | Comunicación bidireccional sin Internet; hardware accesible (tablet + funda); reconocimiento colaborativo de gestos. |
| **Debilidades**                                         | Requiere inversión inicial alta; pruebas de campo y escalabilidad pendientes.                                                               | No incluye expresiones faciales ni marcadores no manuales.                                                                               | Necesita múltiples cámaras y setup complejo; alto costo de infraestructura.                                                     | Dependencia de hardware específico (Leap Motion + tablet); exige entrenamiento inicial. |
| **Oportunidades**                                       | Subvenciones gubernamentales y ONGs; alianzas educativas; escalabilidad en LATAM.                                                            | Potencial comercialización y mejoras con Deep Learning.                                                                                   | Adaptación a otros idiomas de señas y mercados internacionales.                                                                  | Expansión a otras plataformas móviles; incorporación de nuevos idiomas de señas; mercado corporativo. |
| **Amenazas**                                            | Competencia global con más recursos; avances en software puro de visión por computadora.                                                     | Soluciones de software puro sin hardware que abaratan costos.                                                                            | Nuevas tecnologías emergentes de visión por computadora sin necesidad de guantes.                                                | Aparición de apps móviles basadas en IA sin depender de hardware adicional. |


### 2.1.2. Estrategias y tácticas frente a competidores

**AFRONTAR LAS FORTALEZAS (de la competencia):**

* Respaldar la innovación académica de SignAloud con alianzas locales: colaboraciones con universidades peruanas para co-desarrollar y validar nuevas versiones del guante.
* Igualar la precisión de SignAll mediante un ciclo ágil de mejora continua: implementar feedback de campo y tests en escuelas de LSP para refinar los modelos de Deep Learning.

**APROVECHAR LAS DEBILIDADES (de la competencia):**

* Prototipo listo para producción vs. investigación en prototipo: fabricar lotes iniciales del guante y comercializarlos localmente, aprovechando que SignAloud aún no está en mercado.
* Simplicidad de implementación: usar un solo dispositivo IoT (el guante) sin necesidad de cámaras adicionales ni setups complejos como SignAll o MotionSavvy.

**OPORTUNIDADES Y AMENAZAS DE LA COMPETENCIA:**

**Oportunidades:**
* Acceder a subvenciones y programas de inclusión social del gobierno peruano y ONGs, que buscan financiar tecnología para discapacidad.
* Escalar a otros idiomas de señas de Latinoamérica, aprovechando la experiencia piloto en Perú como caso de éxito.

**Amenazas:**
* Soluciones de software puro basadas en visión por computadora que prescinden de hardware y pueden ser más económicas.
* Grandes empresas tecnológicas con presupuestos mayores podrían lanzar apps integradas (voz + señas) apoyadas en sus plataformas globales.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

1. **Datos generales**
   1. ¿Cuál es su nombre?
   2. ¿Cuántos años tiene?
   3. ¿En qué ciudad y distrito reside?
   4. ¿A qué se dedica actualmente?

2. **Segmento 1: Personas con discapacidad auditiva y del habla (Cuidadores)**
   1. ¿Cuál es su relación con la persona con discapacidad auditiva o del habla que cuida?
   2. ¿Qué estrategias o métodos utiliza actualmente para comunicarse con ella?
   3. ¿En qué tipo de situaciones suele haber más dificultades de comunicación (visitas médicas, trámites, tiendas, transporte, etc.)?
   4. ¿Con qué tipo de personas se presentan mayores barreras (familiares, profesores, personal de atención al cliente, desconocidos)?
   5. ¿Utilizan actualmente algún tipo de tecnología o aplicación para facilitar la comunicación? ¿Cuál ha sido su experiencia?
   6. ¿Qué limitaciones ha encontrado en las herramientas existentes para ayudar en la comunicación?
   7. ¿Ha presenciado o vivido junto con la persona bajo su cuidado situaciones de exclusión o malentendidos debido a la barrera del lenguaje?
   8. ¿Cómo se sienten usted y la persona que cuida cuando no pueden hacerse entender en ciertos contextos?
   9. ¿Considera que la sociedad en general está preparada para interactuar adecuadamente con personas con discapacidad auditiva o del habla?
   10. ¿Cree que esta situación afecta las oportunidades educativas, sociales o laborales de la persona que cuida?
   11. ¿Qué tipo de funcionalidades esperaría de un dispositivo o aplicación para facilitar la comunicación?
   12. ¿Qué tipo de mensajes o expresiones serían más útiles que se pudieran traducir automáticamente con la ayuda de un dispositivo?
   13. ¿En qué espacios le gustaría que esta herramienta sea especialmente útil (hospitales, bancos, centros educativos, etc.)?

3. **Segmento 2: Instituciones educativas especializadas**
   1. ¿Cuál es su rol dentro de la institución?
   2. ¿Cuántos estudiantes con discapacidad auditiva o del habla atienden en promedio?
   3. ¿Qué métodos utilizan actualmente para facilitar la enseñanza del lenguaje de señas?
   4. ¿Han utilizado tecnología para mejorar la comunicación o el aprendizaje de sus estudiantes? ¿Cuál fue su experiencia?
   5. ¿Qué dificultades enfrentan sus estudiantes al interactuar con personas fuera del entorno institucional?
   6. ¿Considera que el lenguaje de señas se enseña de forma adecuada en los niveles educativos actuales?
   7. ¿Qué limitaciones tienen actualmente en cuanto a recursos tecnológicos para mejorar sus procesos de enseñanza?
   8. ¿Qué tipo de dispositivo o aplicación cree que sería útil para reforzar la enseñanza del lenguaje de señas?
   9. ¿Le gustaría contar con una herramienta que permita evaluar en tiempo real la expresión en señas de los estudiantes?

4. **Validación de la propuesta**
   1. Se presenta al entrevistado la idea del proyecto GloveTalk y sus principales funcionalidades (traducción en tiempo real de señas a texto o voz y viceversa, uso de IA para mejorar la precisión, compatibilidad con dispositivos móviles y wearables).
   2. ¿Qué le parece la propuesta de GloveTalk?
   3. ¿Cree que podría ser útil en su vida diaria o en su entorno educativo/laboral?
   4. ¿Alguna vez ha usado una tecnología similar?
   5. ¿Cuál es el aspecto que más le llama la atención de esta propuesta?
   6. ¿Qué sugerencias o mejoras le gustaría que tenga el dispositivo o la aplicación?
   7. ¿En qué escenarios le gustaría poder utilizar esta solución?

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

| **Tareas Identificadas**                    | **Cuidadores Importancia** | **Cuidadores Frecuencia** | **Educadores Importancia** | **Educadores Frecuencia** |
|---------------------------------------------|-----------------------------|----------------------------|-----------------------------|----------------------------|
| Motivar la comunicación                     | Alta                        | Alta                       | Alta                        | Alta                       |
| Practicar lenguaje de señas                 | Alta                        | Media                      | Alta                        | Alta                       |
| Promover la autonomía comunicativa          | Alta                        | Alta                       | Alta                        | Alta                       |
| Adaptar el entorno para comunicarse         | Alta                        | Media                      | Alta                        | Alta                       |
| Hacer seguimiento al progreso comunicativo  | Alta                        | Media                      | Alta                        | Alta                       |
| Buscar herramientas de apoyo                | Alta                        | Media                      | Alta                        | Media                      |
| Coordinar con instituciones                 | Media                       | Media                      | Alta                        | Alta                       |
| Recibir capacitación                        | Alta                        | Baja                       | Alta                        | Media                      |

### 2.3.3. Empathy Mapping

### 2.3.4. As-is Scenario Mapping

## 2.4. Ubiquitous Language

---

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

## 3.3. Impact Mapping

## 3.4. Product Backlog

---

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. EventStorming

#### 4.1.1.1. Candidate Context Discovery

#### 4.1.1.2. Domain Message Flows Modeling

#### 4.1.1.3. Bounded Context Canvases

### 4.1.2. Context Mapping

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

#### 4.1.3.2. Software Architecture Context Level Diagrams

#### 4.1.3.3. Software Architecture Container Level Diagrams

#### 4.1.3.4. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.X. Bounded Context: <Bounded Context Name>

#### 4.2.X.1. Domain Layer

#### 4.2.X.2. Interface Layer

#### 4.2.X.3. Application Layer

#### 4.2.X.4. Infrastructure Layer

#### 4.2.X.5. Component Level Diagrams

#### 4.2.X.6. Code Level Diagrams

##### 4.2.X.6.1. Domain Layer Class Diagrams

##### 4.2.X.6.2. Database Design Diagram

---

# Capítulo V: Solution UI/UX Design

## 5.1. Style Guidelines

### 5.1.1. General Style Guidelines

### 5.1.2. Web, Mobile and IoT Style Guidelines

## 5.2. Information Architecture

### 5.2.1. Organization Systems

### 5.2.2. Labeling Systems

### 5.2.3. SEO Tags and Meta Tags

### 5.2.4. Searching Systems

### 5.2.5. Navigation Systems

## 5.3. Landing Page UI Design

### 5.3.1. Wireframe

### 5.3.2. Mock-up

## 5.4. Applications UX/UI Design

### 5.4.1. Wireframes

### 5.4.2. Wireflow Diagrams

### 5.4.3. Mock-ups

### 5.4.4. User Flow Diagrams

## 5.5. Applications Prototyping

---

# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management

### 6.1.1. Development Environment Configuration

### 6.1.2. Source Code Management

### 6.1.3. Style Guide & Conventions

### 6.1.4. Deployment Configuration

## 6.2. Implementation

### 6.2.X. Sprint n

#### 6.2.X.1. Sprint Planning

#### 6.2.X.2. Aspect Leaders and Collaborators

#### 6.2.X.3. Sprint Backlog

#### 6.2.X.4-8. Sprint Review Evidences

#### 6.2.X.9. Team Collaboration Insights

## 6.3. Validation Interviews

### 6.3.1. Diseño

### 6.3.2. Registro

### 6.3.3. Evaluaciones

## 6.4. Video About-the-Product

---

# Conclusiones y Recomendaciones

# Video About-the-Team

# Bibliografía

# Anexos

---

# Student Outcome

| Student Name | Contribution Summary |
|--------------|----------------------|
|              |                      |

---

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de integrantes del equipo

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

### 2.3.5. As-is Scenario Mapping

## 2.4. Ubiquitous Language

---

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## 3.2. User Stories

## 3.3. Impact Mapping

## 3.4. Product Backlog

---

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. EventStorming

#### 4.1.1.1. Candidate Context Discovery

#### 4.1.1.2. Domain Message Flows Modeling

#### 4.1.1.3. Bounded Context Canvases

### 4.1.2. Context Mapping

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

#### 4.1.3.2. Software Architecture Context Level Diagrams

#### 4.1.3.3. Software Architecture Container Level Diagrams

#### 4.1.3.4. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.X. Bounded Context: <Bounded Context Name>

#### 4.2.X.1. Domain Layer

#### 4.2.X.2. Interface Layer

#### 4.2.X.3. Application Layer

#### 4.2.X.4. Infrastructure Layer

#### 4.2.X.5. Component Level Diagrams

#### 4.2.X.6. Code Level Diagrams

##### 4.2.X.6.1. Domain Layer Class Diagrams

##### 4.2.X.6.2. Database Design Diagram

---

# Capítulo V: Solution UI/UX Design

## 5.1. Style Guidelines

### 5.1.1. General Style Guidelines

### 5.1.2. Web, Mobile and IoT Style Guidelines

## 5.2. Information Architecture

### 5.2.1. Organization Systems

### 5.2.2. Labeling Systems

### 5.2.3. SEO Tags and Meta Tags

### 5.2.4. Searching Systems

### 5.2.5. Navigation Systems

## 5.3. Landing Page UI Design

### 5.3.1. Wireframe

### 5.3.2. Mock-up

## 5.4. Applications UX/UI Design

### 5.4.1. Wireframes

### 5.4.2. Wireflow Diagrams

### 5.4.3. Mock-ups

### 5.4.4. User Flow Diagrams

## 5.5. Applications Prototyping

---

# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management

### 6.1.1. Development Environment Configuration

### 6.1.2. Source Code Management

### 6.1.3. Style Guide & Conventions

### 6.1.4. Deployment Configuration

## 6.2. Implementation

### 6.2.X. Sprint n

#### 6.2.X.1. Sprint Planning

#### 6.2.X.2. Aspect Leaders and Collaborators

#### 6.2.X.3. Sprint Backlog

#### 6.2.X.4-8. Sprint Review Evidences

#### 6.2.X.9. Team Collaboration Insights

## 6.3. Validation Interviews

### 6.3.1. Diseño

### 6.3.2. Registro

### 6.3.3. Evaluaciones

## 6.4. Video About-the-Product

---

# Conclusiones y Recomendaciones

# Video About-the-Team

# Bibliografía

# Anexos
