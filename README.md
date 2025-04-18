# COURSE PROJECT

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Diseño de Experimentos de Ingeniería de Software - 4453</strong><br>
    <strong>Profesor: Julio Manuel Noriega Melendez</strong><br>
    <br>INFORME
</p>
<p align="center">
    <strong>Startup:  </strong><br>
    <strong>Producto:  </strong>
</p>

<div>
    <h3 align="center">Team Members:</h3>
    </div>
<div>
     <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Alvarez Araguache, Samira Jetzabel</td>
            <td>U20211A046</td>
        </tr>
        <tr>
            <td> Apellidos, nombres</td>
            <td> Código </td>
        </tr>
        <tr>
            <td>Ramirez Contreras, Zaid Valentino</td>
            <td>U202218472</td>
        </tr>
        <tr>
            <td>Apellidos, nombres</td>
            <td>Código</td>
        </tr>
         <tr>
            <td>Velasquez Pizarro, Jair</td>
            <td>U202218114</td>
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
            <td> Alvarez Araguache, Samira Jetzabel<br><br>Apellidos y nombres<br><br>Apellidos y nombres<br><br>Apellidos y nombres<br><br>Apellidos y nombres<br>
            <td>Se agregó el contenido del capítulo 1, apartados 1.1, 1.2 y 1.3; el contenido del capítulo 2, apartados 2.1, 2.2, 2.3, 2.4; el contenido del capítulo 3, apartados 3.1, 3.2, 3.3 y 3.4; el contenido del capítulo 4, apartados 4.1, 4.2, 4.3, 4.4, 4.5, 4.6, 4.7 y 4.8; y el contenido del capítulo 5, apartados 5.1, 5.2, 5.3 y 5.4</td>
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
<table >
        <tr>
            <th style="text-align:center;">Criterio específico</th>
            <th style="text-align:center;">Acciones realizadas</th>
            <th style="text-align:center;">Conclusiones</th>
        </tr>
        <tr>
            <td align = "center">4.c.2 Emite juicios informados
considerando el impacto de las
soluciones de ingeniería de
software en contextos globales,
económicos, ambientales y
sociales</td>
            <td> 

Apellidos y nombres <br>
TB1 <br>

Apellidos y nombres <br>
TB1 <br>

Apellidos y nombres <br>
TB1 <br>

Apellidos y nombres <br>
TB1 <br>

Apellidos y nombres <br>
TB1 <br>

</td>
         <td> TB1: Conclusiones <br>
</td>         

  <tr>
            <td align = "center">4.c.1 Reconoce responsabilidad
ética y profesional en
situaciones de ingeniería de
software</td>
            <td>


Apellidos y nombres <br>
TB1 <br>

Apellidos y nombres <br>
TB1 <br>

Apellidos y nombres <br>
TB1 <br>

Apellidos y nombres <br>
TB1 <br>

Apellidos y nombres <br>
TB1 <br>

</td>
            <td>TB1: Conclusiones<br>
            

</td>
       <tr>
</table>

<br>

---

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de integrantes del equipo

<table border="1" width="70%" style="text-align:center;">
    <tr align="center">
        <td rowspan="3">
        <img src="https://raw.githubusercontent.com/Open-Source-SW54-Group-3-ArtCollab/Report/develop/assets/images/Samira-Alvarez-photo.jpg" alt="Samira Alvarez Araguache"  style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Samira Jetzabel Alvarez Araguache
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy una estudiante de ingeniería de software con experiencia en los lenguajes de programación C++, C# y JavaScript. Soy una persona comunicativa, capaz de trabajar eficazmente con mi equipo y con habilidades para liderar y gestionar proyectos.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="" alt="" style="margin-bottom: 5px;" width="150"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Nombre apellido
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        </td>
    </tr>
     <tr align="center">
        <td rowspan="3">
            <img src="" alt="" style="margin-bottom: 5px;" width="150"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Nombre apellido
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="" alt=""  style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>
            Zaid Valentino Ramirez Contreras 
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        </td>
    </tr>
     <tr align="center">
        <td rowspan="3">
            <img src="" alt="" style="margin-bottom: 5px;" width="150"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>
            Jair Velasquez Pizarro
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ingeniería de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        </td>
    </tr>
    
</table>

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
**Segmento emprendedores y PYMES**
<br/>**Escenario principal:** Adquirir freelancers para el desarrollo de proyecto de software
<br/>**Fases**: Búsqueda y selección de candidatos. Negociación y acuerdo. Colaboración y seguimiento. Evaluación y cierre.

<img src="./assets/chapter-III/As-is Emprendedores y PYMES.jpg" alt="Segmento emprendedores y PYMES ">

Enlace a Miro: https://miro.com/app/board/uXjVIA0Hwb4=/?moveToWidget=3458764625322270209&cot=14 

**Segmento Desarrolladores Freelance**
<br/>**Escenario Principal:** Adquirir un proyecto cuyo desarrollo sea remunerado
<br/>**Fases:** Búsqueda de proyectos de software. Elección y contacto con el jefe del proyecto. Desarrollo del proyecto. Entrega y pago final.

<img src="./assets/chapter-III/As-is Desarrollador Freelance.jpg" alt="Segmento Desarrolladores Freelance ">


Enlace a Miro: https://miro.com/app/board/uXjVIA0Hwb4=/?moveToWidget=3458764625320099091&cot=14 


## 2.4. Ubiquitous Language

---

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping
**Segmento emprendedores y PYMES**
<br/>**Escenario principal:** Adquirir freelancers para el desarrollo de proyecto de software
<br/>**Fases**: Búsqueda y selección de candidatos. Negociación y acuerdo. Colaboración y seguimiento. Evaluación y cierre.

<img src="./assets/chapter-III/To-be Emprendedores y PYMES.jpg" alt="Segmento emprendedores y PYMES ">

Enlace a Miro: https://miro.com/app/board/uXjVIA0Hwb4=/?moveToWidget=3458764625325230193&cot=14 

**Segmento Desarrolladores Freelance**
<br/>**Escenario Principal:** Adquirir un proyecto cuyo desarrollo sea remunerado
<br/>**Fases:** Búsqueda de proyectos de software. Elección y contacto con el jefe del proyecto. Desarrollo del proyecto. Entrega y pago final.

<img src="./assets/chapter-III/" alt="Segmento Desarrolladores Freelance ">


Enlace a Miro: https://miro.com/app/board/uXjVIA0Hwb4=/?moveToWidget=3458764625325170755&cot=14 

## 3.2. User Stories

<table>
<colgroup>
<col style="width: 11%" />
<col style="width: 15%" />
<col style="width: 21%" />
<col style="width: 39%" />
<col style="width: 11%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Epic / Story ID</td>
<td>Título</td>
<td>Descripción</td>
<td>Criterios de Aceptación</td>
<td>Relación Epic ID</td>
</tr>

<tr class="header">
<td colspan="5" style="text-align: center"><strong>Epic 1: Autenticación de usuario</strong><br>
<strong>Como</strong> empresario o freelancer<br>
<strong>Quiero</strong> autenticarme y configurar mi perfil del usuario<br>
<strong>Para</strong> ingresar a la aplicación de forma segura y personalizar mi experiencia</td>
</tr>

<tr class="even">
<td>E1-US101</td>
<td>Registrar usuario</td>
<td><p><strong>Como</strong> empresario o freelancer</p>
<p><strong>quiero</strong> tener un apartado de registro en la aplicación</p>
<p><strong>para</strong> que mi información se guarde y pueda acceder a mi cuenta</p></td>
<td><p><strong>Escenario 1: Acceder a la pantalla de registro</strong></p>
<p><strong>Dado que</strong> el empresario o freelancer está en la pantalla de inicio de sesión</p>
<p><strong>Cuando</strong> seleccione la opción "Crear Cuenta"</p>
<p><strong>Entonces</strong> se le mostrará un formulario de registro donde podrá ingresar su nombre de usuario, correo electrónico, contraseña y tipo de cuenta.</p>
<p><strong>Escenario 2: Registrarse exitosamente</strong></p>
<p><strong>Dado que</strong> el empresario o desarrollador ha completado todos los campos requeridos en el formulario de registro</p>
<p><strong>Y</strong> se han validado los datos</p>
<p><strong>Cuando</strong> presione la opción "Crear cuenta"</p>
<p><strong>Entonces</strong> el sistema guardará la información del usuario de manera segura, creará una cuenta nueva y redirigirá al usuario a la pantalla de inicio de sesión.</p></td>
<td>1</td>
</tr>

<tr class="odd">
<td>E1-US102</td>
<td>Iniciar sesión</td>
<td><p><strong>Como</strong> empresario o desarrollador usuario de la aplicación</p>
<p><strong>quiero</strong> ingresar con mi cuenta con la cual me registre</p>
<p><strong>para</strong> usar las herramientas a mi disposición.</p></td>
<td><p><strong>Escenario 1: Iniciar sesión exitosamente</strong></p>
<p><strong>Dado que</strong> el empresario o desarrollador se encuentra en la pantalla de "Inicio de sesión"</p>
<p><strong>Cuando</strong> ingrese el correo electrónico y contraseña correctos</p>
<p><strong>Y</strong> presione el botón de "Iniciar sesión"</p>
<p><strong>Y</strong> los datos sean validados correctamente</p>
<p><strong>Entonces</strong> se le redirigirá a la página principal de la aplicación</p>
<p><strong>Escenario 2: Iniciar sesión erróneamente</strong></p>
<p><strong>Dado que</strong> el empresario o desarrollador se encuentra en la pantalla de "Inicio de sesión"</p>
<p><strong>Cuando</strong> ingrese un correo electrónico o una contraseña incorrectos</p>
<p><strong>Y</strong> presione el botón "Iniciar sesión"</p>
<p><strong>Y</strong> los datos no sean validados correctamente</p>
<p><strong>Entonces</strong> el sistema mostrará un mensaje de error en rojo bajo el campo de la contraseña con el texto "Las credenciales son incorrectas"</p></td>
<td>1</td>
</tr>

<tr class="even">
<td>E1-US103</td>
<td>Recuperar contraseña</td>
<td><p><strong>Como</strong> usuario quiero que la aplicación ofrezca una opción para recuperar mi contraseña</p>
<p><strong>para</strong> poder acceder a mi cuenta si olvido la contraseña</p></td>
<td><p><strong>Escenario 1: Solicitar de recuperación de contraseña</strong></p>
<p><strong>Dado que</strong> el empresario o freelancer ha olvidado su contraseña y no puede iniciar sesión</p>
<p><strong>Cuando</strong> seleccione la opción "Olvidé mi contraseña" en la pantalla de inicio de sesión</p>
<p><strong>Y</strong> presione el botón "Enviar enlace de recuperación"</p>
<p><strong>Entonces</strong> la aplicación enviará un correo electrónico con un enlace para restablecer la contraseña al correo registrado</p>
<p><strong>Escenario 2: Recuperar contraseña tras múltiples intentos fallidos</strong></p>
<p><strong>Dado que</strong> el empresario o desarrollador está en la pantalla de inicio de sesión</p>
<p><strong>Cuando</strong> intente iniciar sesión con una contraseña incorrecta más de 4 veces</p>
<p><strong>Entonces</strong> la aplicación mostrará un aviso de recuperación de contraseña</p>
<p><strong>Y</strong> el aviso incluirá un enlace para que el usuario pueda recibir instrucciones para restablecer su contraseña al correo electrónico registrado</p>
<p><strong>Y</strong> el aviso tendrá un botón "Enviar enlace de recuperación" para proceder con la solicitud.</p></td>
<td>1</td>
</tr>

<tr class="header">
<td colspan="5" style="text-align: center"><strong>Epic 2: Funcionalidades como empresario</strong><br>
<strong>Como</strong> empresario<br>
<strong>Quiero</strong> poder gestionar proyectos de desarrollo de software de forma eficiente<br>
<strong>Para</strong> encontrar freelancers adecuados, hacer seguimiento al trabajo realizado y calificar el trabajo</td>
</tr>

<tr class="odd">
<td>E2-US101</td>
<td>Visualizar proyectos en la pantalla de inicio</td>
<td><p><strong>Como</strong> empresario</p>
<p><strong>quiero</strong> visualizar todos los proyectos publicados</p>
<p><strong>para</strong> poder ver fácilmente el progreso de los mismos</p></td>
<td><p><strong>Escenario 1: Visualizar proyectos en la pantalla de inicio</strong></p>
<p><strong>Dado que</strong> el empresario se encuentre en la pantalla principal de la aplicación</p>
<p><strong>Cuando</strong> presione el logo de la aplicación que dice "Inicio"</p>
<p><strong>Entonces</strong> podrá ver todos los proyectos que he publicado</p>
<p><strong>Y</strong> cada proyecto estará representado por una tarjeta con el nombre del proyecto, número de postulantes o el indicador de progreso.</p>
<p><strong>Escenario 2: Visualizar detalles de un proyecto</strong></p>
<p><strong>Dado que</strong> el empresario está en la pantalla de inicio</p>
<p><strong>Cuando</strong> seleccione un proyecto específico de la lista</p>
<p><strong>Entonces</strong> se abrirá una vista detallada del proyecto</p>
<p><strong>Y</strong> el empresario podrá ver información adicional como la descripción, los entregables y las fechas de entrega.</p></td>
<td>2</td>
</tr>

<tr class="even">
<td>E2-US102</td>
<td>Gestionar una propuesta de proyecto de software</td>
<td><p><strong>Como</strong> empresario que necesita una solución de software</p>
<p><strong>quiero</strong> utilizar la aplicación para publicar propuesta de proyecto de desarrollo de software</p>
<p><strong>para</strong> que los freelancers interesados puedan contactarme</p></td>
<td><p><strong>Escenario 1: Publicar solicitud de proyecto de software</strong></p>
<p><strong>Dado que</strong> el empresario se encuentre en cualquier página de la aplicación</p>
<p><strong>Cuando</strong> seleccione la opción "Publicar Proyecto"</p>
<p><strong>Y</strong> complete el formulario con los detalles del proyecto</p>
<p><strong>Y</strong> presione el botón "Publicar proyecto"</p>
<p><strong>Y</strong> luego presione el botón "Aceptar"</p>
<p><strong>Entonces</strong> el proyecto debe aparecer en la lista de proyectos disponibles.</p>
<p><strong>Escenario 2: Cancelar la publicación del proyecto</strong></p>
<p><strong>Dado que</strong> el empresario ha iniciado el proceso de publicación del proyecto</p>
<p><strong>Cuando</strong> decida no continuar con la publicación</p>
<p><strong>Y</strong> seleccione algún botón de la barra de navegación</p>
<p><strong>Entonces</strong> se le redirigirá a la página de la opción seleccionada sin guardar la propuesta</p>
<p><strong>Y</strong> la solicitud de publicación del proyecto no se guardará ni se mostrará en la lista de proyectos.</p></td>
<td>2</td>
</tr>

<tr class="odd">
<td>E2-US103</td>
<td>Gestionar lista de postulantes</td>
<td><p><strong>Como</strong> empresario</p>
<p><strong>quiero</strong> un sistema de gestión de mi lista de postulantes</p>
<p><strong>para</strong> gestionar las postulaciones de los freelancers a mis proyectos activos</p></td>
<td><p><strong>Escenario 1: Aceptar postulación</strong></p>
<p><strong>Dado que</strong> el empresario ha recibido solicitudes de postulación</p>
<p><strong>Cuando</strong> se encuentre en la página de aplicantes de un proyecto</p>
<p><strong>Y</strong> presione el botón con el "tick" verde en la carta de un postulante</p>
<p><strong>Entonces</strong> se asignará ese proyecto al desarrollador aceptado</p>
<p><strong>Y</strong> se le notificará al desarrollador que ha sido aceptado</p>
<p><strong>Escenario 2: Rechazar postulación</strong></p>
<p><strong>Dado que</strong> el empresario ha recibido solicitudes de postulación</p>
<p><strong>Cuando</strong> se encuentre en la página de aplicantes de un proyecto</p>
<p><strong>Y</strong> presione el botón con la "equis" roja en la carta de un postulante</p>
<p><strong>Entonces</strong> se eliminará ese postulante de la lista</p>
<p><strong>Y</strong> se le notificará al desarrollador que ha sido rechazado</p></td>
<td>2</td>
</tr>

<tr class="even">
<td>E2-US104</td>
<td>Visualizar y dar calificación a desarrolladores</td>
<td><p><strong>Como</strong> empresario</p>
<p><strong>quiero</strong> un sistema de calificación</p>
<p><strong>para</strong> conocer la fiabilidad de los desarrolladores web</p></td>
<td><p><strong>Escenario 1: Visualizar calificaciones</strong></p>
<p><strong>Dado que</strong> el empresario se encuentre en la página de aplicantes de un proyecto</p>
<p><strong>Cuando</strong> presione la foto de perfil de un desarrollador</p>
<p><strong>Entonces</strong> entrará al perfil del freelancer y visualizará su calificación representada con estrellas</p>
<p><strong>Escenario 2: Dar una calificación</strong></p>
<p><strong>Dado que</strong> el empresario ha trabajado en un proyecto con un desarrollador</p>
<p><strong>Cuando</strong> el proyecto finalice y acceda a la pantalla de detalles</p>
<p><strong>Entonces</strong> verá una opción para calificar al freelancer con estrellas (1-5) y podrá enviar la evaluación</p></td>
<td>2</td>
</tr>

<tr class="odd">
<td>E2-US105</td>
<td>Visualizar el repositorio de un desarrollador</td>
<td><p><strong>Como</strong> empresario</p>
<p><strong>quiero</strong> visualizar una lista con los trabajos realizados por un desarrollador</p>
<p><strong>para</strong> tener mayor confianza al contactarlo</p></td>
<td><p><strong>Escenario 1: Ver lista de trabajos realizados</strong></p>
<p><strong>Dado que</strong> el empresario está en la pantalla de lista de aplicantes</p>
<p><strong>Cuando</strong> presione la foto de perfil de un freelancer</p>
<p><strong>Entonces</strong> verá en su perfil la sección "Repositorio" con los trabajos previos</p>
<p><strong>Escenario 2: Ver trabajo específico</strong></p>
<p><strong>Dado que</strong> el empresario está en el perfil de un desarrollador</p>
<p><strong>Cuando</strong> seleccione un trabajo del repositorio</p>
<p><strong>Entonces</strong> se abrirá en nueva pestaña el trabajo deployado o su repositorio original</p></td>
<td>2</td>
</tr>

<tr class="even">
<td>E2-US106</td>
<td>Crear y gestionar entregables</td>
<td><p><strong>Como</strong> empresario</p>
<p><strong>quiero</strong> un sistema de entregables</p>
<p><strong>para</strong> establecer los aspectos que debe enviar el desarrollador</p></td>
<td><p><strong>Escenario 1: Crear entregables</strong></p>
<p><strong>Dado que</strong> el empresario está en la pantalla de "Cronograma de entregables"</p>
<p><strong>Cuando</strong> presione el botón "+"</p>
<p><strong>Entonces</strong> podrá crear un nuevo entregable con título, descripción y fecha límite</p>
<p><strong>Escenario 2: Editar entregable</strong></p>
<p><strong>Dado que</strong> el empresario selecciona un entregable existente</p>
<p><strong>Cuando</strong> elija "Editar"</p>
<p><strong>Entonces</strong> podrá modificar sus detalles y guardar cambios</p>
<p><strong>Escenario 3: Eliminar entregable</strong></p>
<p><strong>Dado que</strong> el empresario selecciona "Eliminar" en un entregable</p>
<p><strong>Cuando</strong> confirme la acción</p>
<p><strong>Entonces</strong> el entregable será removido del cronograma</p></td>
<td>2</td>
</tr>

<tr class="odd">
<td>E2-US107</td>
<td>Gestionar fechas de entregables en el calendario</td>
<td><p><strong>Como</strong> empresario</p>
<p><strong>quiero</strong> un sistema de calendario</p>
<p><strong>para</strong> ver, asignar, actualizar y eliminar fechas de entregables</p></td>
<td><p><strong>Escenario 1: Asignar fecha</strong></p>
<p><strong>Dado que</strong> el empresario está creando/editando un entregable</p>
<p><strong>Cuando</strong> seleccione una fecha en el calendario emergente</p>
<p><strong>Entonces</strong> la fecha se asignará al entregable</p>
<p><strong>Escenario 2: Actualizar fecha</strong></p>
<p><strong>Dado que</strong> el empresario edita un entregable existente</p>
<p><strong>Cuando</strong> cambie la fecha y guarde</p>
<p><strong>Entonces</strong> se actualizará en el calendario</p>
<p><strong>Escenario 3: Eliminar fecha</strong></p>
<p><strong>Dado que</strong> el empresario selecciona "Eliminar" en la fecha de un entregable</p>
<p><strong>Cuando</strong> confirme la acción</p>
<p><strong>Entonces</strong> la fecha será removida</p></td>
<td>2</td>
</tr>

<tr class="even">
<td>E2-US108</td>
<td>Obtener status de verificado como empresario</td>
<td><p><strong>Como</strong> empresario premium</p>
<p><strong>quiero</strong> el sistema de verificado</p>
<p><strong>para</strong> dar mayor fiabilidad a los desarrolladores freelancer</p></td>
<td><p><strong>Escenario 1: Obtener el estatus de verificado</strong></p>
<p><strong>Dado que</strong> el empresario ha pagado la suscripción premium</p>
<p><strong>Cuando</strong> acceda a su perfil</p>
<p><strong>Entonces</strong> se mostrará un indicador de verificación</p>
<p><strong>Escenario 2: Mayor visibilidad</strong></p>
<p><strong>Dado que</strong> el empresario es verificado</p>
<p><strong>Cuando</strong> publique un proyecto</p>
<p><strong>Entonces</strong> aparecerá el icono de verificado junto a su nombre</p></td>
<td>2</td>
</tr>

<tr class="odd">
<td>E2-US109</td>
<td>Navegar por la aplicación como empresario</td>
<td><p><strong>Como</strong> empresario</p>
<p><strong>quiero</strong> un sistema de navegación eficiente</p>
<p><strong>para</strong> acceder fácilmente a las secciones</p></td>
<td><p><strong>Escenario 1: Acceder a Buscar Desarrolladores</strong></p>
<p><strong>Dado que</strong> el empresario ha iniciado sesión</p>
<p><strong>Cuando</strong> presione "Explorar Desarrolladores"</p>
<p><strong>Entonces</strong> será dirigido a esa sección</p>
<p><strong>Escenario 2: Acceder a Mensajes</strong></p>
<p><strong>Dado que</strong> el empresario ha iniciado sesión</p>
<p><strong>Cuando</strong> seleccione "Mensajes"</p>
<p><strong>Entonces</strong> verá el formulario de mensajería</p>
<p><strong>Escenario 3: Cerrar sesión</strong></p>
<p><strong>Dado que</strong> el empresario ha iniciado sesión</p>
<p><strong>Cuando</strong> presione "Salir"</p>
<p><strong>Entonces</strong> regresará a la pantalla de inicio de sesión</p></td>
<td>2</td>
</tr>

<tr class="even">
<td>E2-US110</td>
<td>Estadísticas del proyecto</td>
<td><p><strong>Como</strong> empresa</p>
<p><strong>quiero</strong> acceder a un panel de estadísticas</p>
<p><strong>para</strong> visualizar el estado, rendimiento y puntualidad del freelancer</p></td>
<td><p><strong>Escenario 1: Visualizar progreso</strong></p>
<p><strong>Dado que</strong> hay un proyecto en curso</p>
<p><strong>Cuando</strong> acceda a estadísticas</p>
<p><strong>Entonces</strong> verá un gráfico de progreso por entregables</p>
<p><strong>Escenario 2: Entregables a tiempo vs retrasados</strong></p>
<p><strong>Dado que</strong> hay entregables completados</p>
<p><strong>Cuando</strong> revise estadísticas</p>
<p><strong>Entonces</strong> verá un gráfico comparando entregas puntuales y retrasadas</p>
<p><strong>Escenario 3: Evaluar riesgo de retraso</strong></p>
<p><strong>Dado que</strong> el proyecto está en progreso</p>
<p><strong>Cuando</strong> analice fechas límite vs avance</p>
<p><strong>Entonces</strong> verá indicadores de riesgo</p></td>
<td>2</td>
</tr>

<tr class="header">
<td colspan="5" style="text-align: center"><strong>Epic 3: Funcionalidades como desarrollador freelancer</strong><br>
<strong>Como</strong> desarrollador freelancer<br>
<strong>Quiero</strong> encontrar proyectos adecuados, postularme fácilmente y gestionar mis entregas<br>
<strong>Para</strong> trabajar de forma organizada y recibir una remuneración por mi trabajo</td>
</tr>

<tr class="even">
<td>E3-US101</td>
<td>Visualizar y gestionar proyectos asignados</td>
<td><p><strong>Como</strong> freelancer</p>
<p><strong>quiero</strong> visualizar todos los proyectos en los que soy desarrollador en la pantalla de inicio</p>
<p><strong>para</strong> facilitar el seguimiento y el envío de los avances</p></td>
<td><p><strong>Escenario 1: Visualizar proyectos en la pantalla de inicio</strong></p>
<p><strong>Dado que</strong> el desarrollador freelancer ha iniciado sesión en la aplicación</p>
<p><strong>Cuando</strong> presione el logo de la aplicación en la barra de navegación superior</p>
<p><strong>Entonces</strong> deberá ver su perfil, así como una lista de todos los proyectos en los que está asignado como desarrollador</p>
<p><strong>Escenario 2: Acceder a detalles de un proyecto</strong></p>
<p><strong>Dado que</strong> el desarrollador freelancer esté en la pantalla de inicio</p>
<p><strong>Cuando</strong> toque el nombre de un proyecto en la lista de proyectos asignados</p>
<p><strong>Entonces</strong> será dirigido a la pantalla de Detalles del Proyecto</p>
<p><strong>Y</strong> podrá ver información detallada del proyecto como su descripción y los entregables</p></td>
<td>3</td>
</tr>

<tr class="odd">
<td>E3-US102</td>
<td>Buscar proyectos</td>
<td><p><strong>Como</strong> freelancer</p>
<p><strong>quiero</strong> buscar proyectos</p>
<p><strong>para</strong> encontrar proyectos que se alineen con mis habilidades e intereses</p></td>
<td><p><strong>Escenario 1: Buscar Proyecto</strong></p>
<p><strong>Dado que</strong> el desarrollador se encuentra en la pantalla principal de la aplicación</p>
<p><strong>Cuando</strong> seleccione la opción de "Explorar Proyectos" la barra de navegación</p>
<p><strong>Entonces</strong> es dirigido a la sección de buscar proyectos</p></td>
<td>3</td>
</tr>

<tr class="odd">
<td>E3-US103</td>
<td>Postular a proyectos de desarrollo de software</td>
<td><p><strong>Como</strong> freelancer</p>
<p><strong>quiero</strong> postularme a desarrollar un proyecto</p>
<p><strong>para</strong> ser aceptado como desarrollador</p></td>
<td><p><strong>Escenario 1: Postular a un proyecto</strong></p>
<p><strong>Dado que</strong> el freelancer encuentra un proyecto de interés</p>
<p><strong>Cuando</strong> toque "Postular a Proyecto"</p>
<p><strong>Entonces</strong> aparecerá una ventana de confirmación</p>
<p><strong>Y</strong> al aceptar, se enviará la postulación</p>
<p><strong>Escenario 2: Postulaciones ilimitadas (premium)</strong></p>
<p><strong>Dado que</strong> el freelancer tiene suscripción premium</p>
<p><strong>Cuando</strong> postule a proyectos</p>
<p><strong>Entonces</strong> no tendrá límites en postulaciones</p>
<p><strong>Escenario 3: Prioridad en listas (premium)</strong></p>
<p><strong>Dado que</strong> el freelancer es premium</p>
<p><strong>Cuando</strong> postule</p>
<p><strong>Entonces</strong> su postulación aparecerá en posición más alta</p></td>
<td>3</td>
</tr>

<tr class="even">
<td>E3-US104</td>
<td>Obtener status de verificado como freelancer</td>
<td><p><strong>Como</strong> freelancer premium</p>
<p><strong>quiero</strong> obtener una verificación en mi cuenta</p>
<p><strong>para</strong> generar mayor confianza</p></td>
<td><p><strong>Escenario 1: Obtener verificado</strong></p>
<p><strong>Dado que</strong> el freelancer paga suscripción premium</p>
<p><strong>Cuando</strong> complete el proceso</p>
<p><strong>Entonces</strong> aparecerá icono de verificado en su perfil</p>
<p><strong>Escenario 2: Confirmación de verificación</strong></p>
<p><strong>Dado que</strong> el freelancer es premium</p>
<p><strong>Cuando</strong> acceda a su perfil</p>
<p><strong>Entonces</strong> recibirá notificación de verificación</p></td>
<td>3</td>
</tr>

<tr class="odd">
<td>E3-US105</td>
<td>Navegar por la aplicación como freelancer</td>
<td><p><strong>Como</strong> freelancer</p>
<p><strong>quiero</strong> un menú con accesos directos</p>
<p><strong>para</strong> navegar fluidamente</p></td>
<td><p><strong>Escenario 1: Acceder a Inicio</strong></p>
<p><strong>Dado que</strong> el freelancer ha iniciado sesión</p>
<p><strong>Cuando</strong> presione el logo de la app</p>
<p><strong>Entonces</strong> verá su perfil y proyectos asignados</p>
<p><strong>Escenario 2: Acceder a Mensajes</strong></p>
<p><strong>Dado que</strong> el freelancer ha iniciado sesión</p>
<p><strong>Cuando</strong> seleccione "Mensajes"</p>
<p><strong>Entonces</strong> podrá enviar/recepcionar mensajes</p>
<p><strong>Escenario 3: Cerrar sesión</strong></p>
<p><strong>Dado que</strong> el freelancer ha iniciado sesión</p>
<p><strong>Cuando</strong> presione "Salir"</p>
<p><strong>Entonces</strong> regresará al inicio de sesión</p></td>
<td>3</td>
</tr>

<tr class="even">
<td>E3-US106</td>
<td>Gestionar entregables de un proyecto</td>
<td><p><strong>Como</strong> freelancer</p>
<p><strong>quiero</strong> explorar y revisar los entregables</p>
<p><strong>para</strong> verificar los tiempos de entrega</p></td>
<td><p><strong>Escenario 1: Revisar entregables</strong></p>
<p><strong>Dado que</strong> el freelancer está asignado a un proyecto</p>
<p><strong>Cuando</strong> acceda a "Entregables"</p>
<p><strong>Entonces</strong> verá la lista con descripciones y fechas</p>
<p><strong>Escenario 2: Notificaciones anticipadas</strong></p>
<p><strong>Dado que</strong> un entregable tiene fecha próxima</p>
<p><strong>Cuando</strong> falten 3 días</p>
<p><strong>Entonces</strong> recibirá una notificación recordatoria</p></td>
<td>3</td>
</tr>

<tr class="header">
<td colspan="5" style="text-align: center"3.2><strong>Epic 4: Preferencias en la aplicación</strong><br>
<strong>Como</strong> empresa o desarrollador freelancer<br>
<strong>Quiero</strong> configurar preferencias en la aplicación<br>
<strong>Para</strong> tener una mejor experiencia en la aplicación según mis preferencias</td>
</tr>

<tr class="even">
<td>E4-US101</td>
<td>Seleccionar idioma</td>
<td><p><strong>Como</strong> empresario o freelance</p>
<p><strong>quiero</strong> configurar preferencias de idioma</p>
<p><strong>para</strong> utilizar la aplicación según mi preferencia de idioma.</p></td>
<td><p><strong>Escenario 1: Modo predeterminado de preferencia de idioma</strong></p>
<p><strong>Dado que</strong> el empresario o desarrollador freelancer no haya realizado cambios de preferencias de idioma a la aplicación</p>
<p><strong>Cuando</strong> ingrese a la aplicación</p>
<p><strong>Entonces</strong> el idioma predeterminado es inglés</p>
<p><strong>Escenario 2: Cambio de preferencias de idioma en la aplicación</strong></p>
<p><strong>Dado que</strong> el empresario o postulante se encuentra en la sección de configuraciones de idioma</p>
<p><strong>Cuando</strong> selecciona un idioma</p>
<p><strong>Entonces</strong> el idioma de la aplicación se cambia al idioma seleccionado.</p></td>
<td>4</td>
</tr>

<tr class="even">
<td>E4-US102</td>
<td>Manejar y reportar errores</td>
<td><p><strong>Como</strong> empresario o freelancer</p>
<p><strong>quiero</strong> ser informado de errores</p>
<p><strong>para</strong> que se puedan resolver y mejorar la experiencia</p></td>
<td><p><strong>Escenario 1: Error 404</strong></p>
<p><strong>Dado que</strong> el usuario accede a una ruta inexistente</p>
<p><strong>Cuando</strong> la aplicación detecte el error</p>
<p><strong>Entonces</strong> mostrará pantalla de error con opción a redirigir</p>
<p><strong>Escenario 2: Reportar bug</strong></p>
<p><strong>Dado que</strong> el usuario encuentra un problema</p>
<p><strong>Cuando</strong> acceda a "Soporte" en el menú</p>
<p><strong>Entonces</strong> podrá enviar un reporte detallado</p></td>
<td>4</td>
</tr>

<tr class="odd">
<td>E4-US103</td>
<td>Gestionar perfil de usuario</td>
<td><p><strong>Como</strong> usuario</p>
<p><strong>quiero</strong> gestionar mi información de perfil</p>
<p><strong>para</strong> configurarlo a mi gusto</p></td>
<td><p><strong>Escenario 1: Visualizar perfil</strong></p>
<p><strong>Dado que</strong> el usuario inicia sesión</p>
<p><strong>Cuando</strong> acceda a su perfil</p>
<p><strong>Entonces</strong> verá su información actual</p>
<p><strong>Escenario 2: Editar perfil</strong></p>
<p><strong>Dado que</strong> el usuario selecciona "Editar perfil"</p>
<p><strong>Cuando</strong> modifique datos y guarde</p>
<p><strong>Entonces</strong> los cambios se reflejarán inmediatamente</p></td>
<td>4</td>
</tr>

<tr class="header">
<td colspan="5"  style="text-align: center"> <strong>Epic 5: Backend API</strong><br>
<strong>Como</strong> desarrollador<br>
<strong>Quiero</strong> utilizar un backend API<br>
<strong>Para</strong> que los usuarios puedan interactuar con la aplicación</td>
</tr>

<tr class="odd">
<td>E5-US101</td>
<td>Seleccionar fechas de entregables en el calendario</td>
<td><p><strong>Como</strong> desarrollador</p>
<p><strong>quiero</strong> funciones de información</p>
<p><strong>para</strong> que los usuarios puedan manipular y observar la fecha de los entregables de los proyectos</p></td>
<td><p><strong>Escenario 1: Solicitud GET</strong></p>
<p><strong>Dado que</strong> desarrollador utilice el endpoint</p>
<p><strong>Cuando</strong> utilice el método GET a los usuarios</p>
<p><strong>Entonces</strong> consigue las fechas de los entregables</p>
<p><strong>Escenario 2: Solicitud POST</strong></p>
<p><strong>Dado que</strong> desarrollador utilice el endpoint</p>
<p><strong>Cuando</strong> utilice el método POST a los entregables</p>
<p><strong>Y</strong> los datos son validados</p>
<p><strong>Entonces</strong> se crea una nueva fecha en el calendario</p>
<p><strong>Escenario 3: Solicitud PUT</strong></p>
<p><strong>Dado que</strong> desarrollador utilice el endpoint</p>
<p><strong>Cuando</strong> utilice el método PUT con el ID del entregable con la fecha a editar</p>
<p><strong>Y</strong> los datos son validados</p>
<p><strong>Entonces</strong> se cambia la fecha seleccionada en el calendario</p>
<p><strong>Escenario 4: Solicitud DELETE</strong></p>
<p><strong>Dado que</strong> desarrollador utilice el endpoint</p>
<p><strong>Cuando</strong> utilice el método DELETE con el ID del entregable con la fecha a eliminar</p>
<p><strong>Y</strong> los datos son validados</p>
<p><strong>Entonces</strong> se eliminará la fecha del entregable seleccionado del calendario</p></td>
<td>5</td>
</tr>

</tbody>
</table>

## 3.3. Impact Mapping
**Segmento emprendedores y PYMES**

<img src="./assets/chapter-III/Impact-map emprendedores y PYMES.PNG" alt="Impact map del segmento emprendedores y PYMES">

**Segmento desarrolladores freelance**

<img src="./assets/chapter-III/Impact-map Desarrollador Freelance.png" alt="Impact map del segmento desarrolladores freelance">

## 3.4. Product Backlog

<img src="./assets/chapter-III/Product-backlog.PNG" alt="Product backlog de la aplicación FromZero">

Enlace al tablero de Trello: https://trello.com/b/gNzXJS37/from-zero 

<table border="1">
  <thead>
    <tr>
      <th>User story ID</th>
      <th>Título</th>
      <th>Story Points (1 / 2 / 3 / 5 / 8)</th>
      <th>Sprint</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>E2-US109</td>
      <td>Navegar por la aplicación como empresario</td>
      <td>3</td>
      <td>1</td>
    </tr>
    <tr>
      <td>E2-US102</td>
      <td>Gestionar una propuesta de proyecto de software</td>
      <td>3</td>
      <td>1</td>
    </tr>
    <tr>
      <td>E2-US106</td>
      <td>Crear y gestionar entregables</td>
      <td>5</td>
      <td>1</td>
    </tr>
    <tr>
      <td>E2-US107</td>
      <td>Gestionar fechas de entregables en el calendario</td>
      <td>5</td>
      <td>1</td>
    </tr>
    <tr>
      <td>E2-US110</td>
      <td>Estadísticas del proyecto</td>
      <td>2</td>
      <td>1</td>
    </tr>
    <tr>
      <td>E2-US101</td>
      <td>Visualizar proyectos en la pantalla de inicio</td>
      <td>3</td>
      <td>1</td>
    </tr>
    <tr>
      <td>E2-US104</td>
      <td>Visualizar y dar calificación a desarrolladores</td>
      <td>3</td>
      <td>1</td>
    </tr>
    <tr>
      <td>E1-US101</td>
      <td>Registrar usuario</td>
      <td>3</td>
      <td>1</td>
    </tr>
    <tr>
      <td>E1-US102</td>
      <td>Iniciar sesión</td>
      <td>3</td>
      <td>1</td>
    </tr>
    <tr>
      <td>E2-US103</td>
      <td>Gestionar lista de postulantes</td>
      <td>5</td>
      <td>2</td>
    </tr>
    <tr>
      <td>E5-US101</td>
      <td>Seleccionar fechas de entregables en el calendario</td>
      <td>5</td>
      <td>2</td>
    </tr>
    <tr>
      <td>E2-US105</td>
      <td>Visualizar el repositorio de un desarrollador</td>
      <td>3</td>
      <td>2</td>
    </tr>
    <tr>
      <td>E2-US108</td>
      <td>Obtener status de verificado como empresario</td>
      <td>3</td>
      <td>2</td>
    </tr>
    <tr>
      <td>E3-US104</td>
      <td>Navegar por la aplicación como freelancer</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <td>E3-US102</td>
      <td>Postular a proyectos de desarrollo de software</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <td>E3-US101</td>
      <td>Visualizar y gestionar proyectos asignados</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <td>E3-US103</td>
      <td>Obtener status de verificado como freelancer</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <td>E4-US101</td>
      <td>Seleccionar idioma</td>
      <td>2</td>
      <td>4</td>
    </tr>
    <tr>
      <td>E4-US102</td>
      <td>Manejar y reportar errores</td>
      <td>1</td>
      <td>4</td>
    </tr>
    <tr>
      <td>E1-US103</td>
      <td>Recuperar contraseña</td>
      <td>3</td>
      <td>4</td>
    </tr>
  </tbody>
</table>

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
