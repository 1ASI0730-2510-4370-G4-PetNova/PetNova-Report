# Capítulo V: Product Implementation, Validation & Deployment

### 5.1. Software Configuration Management.

#### 5.1.1. Software Development Environment Configuration.

En esta sección, se describen las herramientas y plataformas empleadas por el equipo para llevar a cabo el desarrollo de nuestro startup. Estas soluciones han sido fundamentales para facilitar el trabajo colaborativo, la programación y la gestión eficiente del proyecto. A continuación, se ofrece un resumen detallado de cada herramienta utilizada:

- **GitHub**

  **Descripción:** GitHub es una plataforma que permite el alojamiento y la gestión de código fuente mediante Git, fomentando la colaboración entre equipos. <br>
  **Uso:** Lo empleamos para controlar el versionado del código, manejar ramas y pull requests, así como para centralizar la documentación del proyecto.

- **Git**

  **Descripción:** Git es una herramienta de control de versiones distribuida que optimiza el seguimiento de modificaciones en el código fuente. <br>
  **Uso:** Se utilizó para gestionar commits, sincronizar cambios mediante push y pull, y organizar ramas, asegurando un flujo de trabajo continuo y efectivo.

- **Canva**

  **Descripción:** Canva es una plataforma de diseño gráfico en línea que simplifica la creación de elementos visuales de manera intuitiva. <br>
  **Uso:** La usamos para desarrollar gráficos y elementos visuales para la Landing Page, como banners, íconos y otros recursos que enriquecen la estética de la aplicación.

- **Visual Studio Code**

  **Descripción:** Visual Studio Code (VS Code) es un editor de código fuente versátil y ligero, compatible con múltiples lenguajes de programación.
  **Uso:** Fue nuestro editor principal para escribir y modificar el código, aprovechando sus extensiones para optimizar el flujo de trabajo y agilizar el desarrollo.

- **WhatsApp**

  **Descripción:** WhatsApp es una aplicación de mensajería instantánea que facilita la comunicación rápida y efectiva.<br>
  **Uso:** La utilizamos para coordinar actividades diarias, resolver dudas rápidamente y organizar reuniones informales entre los miembros del equipo.

- **Google Meet**

  **Descripción:** Google Meet es una solución de videoconferencia que facilita la realización de reuniones virtuales de forma eficiente. <br>
  **Uso:** Se empleó para realizar sesiones virtuales de equipo, permitiendo discusiones en tiempo real y presentaciones de avances a los stakeholders.

- **Figma**

  **Descripción:** Figma es una herramienta de diseño colaborativo en línea, ideal para crear y prototipar interfaces de usuario. <br>
  **Uso:** La usamos para diseñar y prototipar las interfaces de la aplicación, fomentando la colaboración en tiempo real entre diseñadores y desarrolladores para perfeccionar los diseños.

<br></br>

#### 5.1.2. Source Code Management.

**Gestión del Código Fuente:**

En este apartado, se explica el enfoque adoptado para organizar y supervisar el desarrollo del código en el proyecto Pet Nova. GitHub fue seleccionado como la plataforma principal para la gestión del código fuente, acompañado de Git como sistema de control de versiones. Además, implementamos el flujo de trabajo GitFlow para garantizar un desarrollo ordenado y eficiente.

- Repositorio GitHub para nuestra Landing Page:
  <b>https://1asi0730-2510-4370-g4-petnova.github.io/Landing-Page-NovaPet/</b>

**Ramas Principales:**

- **main:** Conocida también como "master", esta rama alberga la versión más estable y definitiva del proyecto, lista para su despliegue en producción. Todos los cambios incorporados aquí han superado pruebas y revisiones rigurosas, garantizando su preparación para el lanzamiento.

- **develop:** La rama develop sirve como núcleo de integración para las nuevas funcionalidades y mejoras en curso. Las características y correcciones se fusionan aquí para pruebas adicionales antes de su integración final en la rama main.

**Uso de GitFlow:**

- **Feature Branches:** Las ramas de características se emplean para desarrollar nuevas funcionalidades, derivándose de la rama develop. Una vez completadas y aprobadas mediante revisiones, se integran nuevamente en develop.

- **Bugfix Branches:** Para abordar errores que deben corregirse antes de la próxima versión, se crean ramas de corrección de errores, generalmente a partir de develop o, en casos urgentes, de main.

- **Hotfix Branches:** Estas ramas se utilizan para resolver problemas críticos en producción de manera inmediata. Se derivan de la rama main y, tras solucionar el problema, los cambios se fusionan tanto en main como en develop.

Este flujo de trabajo basado en GitFlow nos ha permitido organizar el desarrollo del código de manera efectiva, facilitando la incorporación de nuevas funcionalidades, la resolución de errores y la preparación de versiones estables para producción.

**Commits Conventions:**

En Pet Nova, los commits se nombran de forma que reflejen claramente el progreso y los cambios realizados. Optamos por no seguir una convención estricta, permitiendo a los desarrolladores usar descripciones detalladas y específicas que representen el trabajo realizado, lo que aporta flexibilidad y claridad al historial de cambios.

#### 5.1.3. Source Code Style Guide & Conventions.

En Pet Nova, hemos establecido un conjunto de estándares de estilo para garantizar que el código sea claro, uniforme y fácil de mantener en las diferentes tecnologías utilizadas:

<b>HTML y CSS:</b> <br>

1. El tipo de documento se declara al inicio del archivo con `<!DOCTYPE html>`.

2. Se añaden los meta tags necesarios.

3. La etiqueta `<title>` se incluye dentro del bloque `<head>`.

4. Usamos una indentación de dos espacios.

5. Se escriben en minúsculas los nombres de los elementos HTML, atributos, propiedades, valores y selectores CSS.

6. Los atributos de los elementos HTML siempre están entre comillas.

<b>JavaScript</b>

1. Cada línea de código termina con un punto y coma.

2. Las variables y funciones siguen la convención de CamelCase.

3. Las cadenas de texto (strings) se colocan entre comillas simples.

4. La indentación es de 2 espacios.

5. Se utiliza preferentemente let y const en lugar de var para declarar variables.

6. Gherkin (Convenciones de Gherkin para Especificaciones Legibles)

7. Se utilizan los términos "Given", "When", "Then" y "And" para definir los pasos del escenario.

Estas prácticas aseguran que el código sea legible, consistente y fácil de mantener a lo largo del desarrollo del proyecto.

- US01:

![Gherkin1](./assets/Chapter05/US01.png)

- US02:

![Gherkin2](./assets/Chapter05/US02.png)

- US03:

![Gherkin3](./assets/Chapter05/US03.png)

- US04:

![Gherkin4](./assets/Chapter05/US04.png)

- US05:

![Gherkin5](./assets/Chapter05/US05.png)

- US06:

![Gherkin6](./assets/Chapter05/US06.png)

- US07:

![Gherkin7](./assets/Chapter05/US07.png)

- US08:

![Gherkin8](./assets/Chapter05/US08.png)

- US09:

![Gherkin9](./assets/Chapter05/US09.png)

- US010:

![Gherkin10](./assets/Chapter05/US10.png)

- US11:

![Gherkin11](./assets/Chapter05/US11.png)

- US12:

![Gherkin12](./assets/Chapter05/US12.png)

- US13:

![Gherkin13](./assets/Chapter05/US13.png)

- US14:

![Gherkin14](./assets/Chapter05/US14.png)

- US15:

![Gherkin15](./assets/Chapter05/US15.png)

- US16:

![Gherkin16](./assets/Chapter05/US16.png)

- US17:

![Gherkin17](./assets/Chapter05/US17.png)

- US18:

![Gherkin18](./assets/Chapter05/US18.png)

- US19:

![Gherkin19](./assets/Chapter05/US19.png)

- US20:

![Gherkin20](./assets/Chapter05/US20.png)

- US21:

![Gherkin21](./assets/Chapter05/US21.png)

- US22:

![Gherkin22](./assets/Chapter05/US22.png)

- US23:

![Gherkin23](./assets/Chapter05/US23.png)

- US24:

![Gherkin24](./assets/Chapter05/US24.png)

- US25:

![Gherkin25](./assets/Chapter05/US25.png)

- US26:

![Gherkin26](./assets/Chapter05/US26.png)

- US27:

![Gherkin27](./assets/Chapter05/US27.png)

- US28:

![Gherkin28](./assets/Chapter05/US28.png)

- US29:

![Gherkin29](./assets/Chapter05/US29.png)

- US30:

![Gherkin30](./assets/Chapter05/US30.png)

- US31:

![Gherkin31](./assets/Chapter05/US31.png)

- US32:

![Gherkin32](./assets/Chapter05/US32.png)

- US33:

![Gherkin33](./assets/Chapter05/US33.png)

- US34:

![Gherkin34](./assets/Chapter05/US34.png)

- US35:

![Gherkin35](./assets/Chapter05/US35.png)

### 5.1.4. Configuración de la implementación del software

En este apartado, se detalla el proceso de despliegue de la Landing Page de Pet Nova a través de GitHub Pages. A continuación, se presentan los pasos realizados para garantizar el acceso público a la página de destino de Pet Nova, acompañados de capturas de pantalla que ilustran cada etapa.

1. Verificamos que la configuración de GitHub Pages estuviera activa para el repositorio de la Landing Page de Pet Nova, accediendo a las opciones de configuración del repositorio en GitHub. <br><br>

<img src="./assets/Chapter05/Github Pages 1.PNG">

2. Accedemos a Github Pages y procedemos con la configuración. Una vez completada la configuración, GitHub Pages generó la URL pública de la Landing Page de Pet Nova, permitiendo su acceso y distribución. <br><br>
   <img src="./assets/Chapter05/Github Pages 2.PNG">

Enlace a la Landing Page de Pet Nova:<br>
https://1asi0730-2510-4370-g4-petnova.github.io/PetNova-Landing-Page/

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

<table>
  <tr>
    <th> Sprint # </th>
    <th> Sprint 1 </th>
  </tr>
  <tr>
    <td style="font-weight: bold;" colspan="2"> Sprint Planning Background </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Date </td>
    <td> 20/04/2025 </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Time </td>
    <td> 19:00 horas (GMT-5) </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Location </td>
    <td> Virtual (Google Meet) </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Prepared By </td>
    <td> Prado Vargas, Mario Benjamin </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Attendees (to planning meeting) </td>
    <td>
      Bastidas Bastidas, Diego Martin<br>
      Belahonia Miranda, Fabrisio<br>
      Choquehuanca Núñez, Luciana Carolina<br>
      Escobar Palomino, Sebastian Matias<br>
      Prado Vargas, Mario Benjamín
    </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 1 Review Summary </td>
    <td> Dado que este es el primer sprint de desarrollo, no contamos con un review summary previo. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 1 Retrospective Summary </td>
    <td> Al ser el primer sprint, aún no hemos identificado áreas específicas de mejora para el proceso. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;" colspan="2"> Sprint Goal & User Stories </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 1 Goal </td>
    <td> Diseñar y desarrollar las secciones principales de la Landing Page de Pet Nova, incluyendo la barra de navegación, la sección 'Why Choose Us?', las opciones de suscripción, las reseñas de clientes, el formulario de contacto y la sección de videos informativos, para permitir a los usuarios explorar sus funcionalidades de manera intuitiva, comprender los beneficios que ofrece el servicio (como la gestión de citas y el monitoreo de mascotas), integrar elementos visuales atractivos creados con Canva, realizar pruebas iniciales de usabilidad y optimizar la experiencia para dispositivos móviles y desktops, asegurando un diseño responsive y accesible. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 1 Velocity </td>
    <td> <strong>8 </strong><br> El equipo determinó una capacidad de 8 Story Points para este Sprint, considerando la experiencia previa y la carga de trabajo estimada. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sum of Story Points </td>
    <td> 8 </td>
  </tr>
</table>

#### **5.2.1.2. Aspect Leaders and Collaborators.**

| **Team Member (Last Name, First Name)**  | **GitHub Username** | **Capítulo I: Introducción (L/C)** | **Capítulo II: Requirements Elicitation & Analysis (L/C)** | **Capítulo III: Requirements Specification (L/C)** | **Capítulo IV: Product Design (L/C)** | **Capítulo V: Product Implementation, Validation & Deployment (L/C)** |
| ---------------------------------------- | ------------------- | ---------------------------------- | ---------------------------------------------------------- | -------------------------------------------------- | ------------------------------------- | --------------------------------------------------------------------- |
| **Belahonia Miranda, fabrisio**          | devfab17            | L                                  | C                                                          | C                                                  | C                                     | C                                                                     |
| **Bastidas Bastidas, Diego Martin**      | ghostnotfound404    | C                                  | L                                                          | C                                                  | C                                     | C                                                                     |
| **Choquehuanca Núñez, Luciana Carolina** | lucianxaaa          | C                                  | C                                                          | L                                                  | C                                     | C                                                                     |
| **Prado Vargas, Mario Benjamín**         | mariopvdev          | C                                  | C                                                          | C                                                  | L                                     | C                                                                     |
| **Escobar Palomino, Sebastian Matias**   | sebasepe            | C                                  | C                                                          | C                                                  | C                                     | L                                                                     |

#### **5.2.1.3. Sprint Backlog 1**

En el primer sprint, el equipo enfocó su trabajo en crear una landing page que fuera tanto funcional como atractiva, asignando las tareas en el tablero de Sprint según las habilidades de cada miembro.

| ID   | Title                                   | Tarea | Description                                                                              | Estimations(Hours) | Assigned To                          | Status | Total US Hours |
| ---- | --------------------------------------- | ----- | ---------------------------------------------------------------------------------------- | ------------------ | ------------------------------------ | ------ | -------------- |
| US17 | Barra de Navegación en la Landing Page  | TS01  | Diseño visual de la barra de navegación.                                                 | 2                  | Bastidas Bastidas, Diego Martin      | DONE   |                |
|      |                                         | TS02  | Implementación de enlaces a "¿Cómo funciona?", "Casos de éxito", "Planes" y "Contactos". | 2                  | Bastidas Bastidas, Diego Martin      | DONE   | **4**          |
| US18 | Sección "Why Choose Us?"                | TS01  | Redacción de testimonios y selección de influencers.                                     | 1.5                | Belahonia Miranda, Fabrisio          | DONE   |                |
|      |                                         | TS02  | Maquetación e inserción de imágenes y citas en la sección.                               | 1.5                | Belahonia Miranda, Fabrisio          | DONE   | **3**          |
| US19 | Gestión de Suscripciones                | TS01  | Diseño de tarjetas de planes de suscripción.                                             | 2                  | Choquehuanca Núñez, Luciana Carolina | DONE   |                |
|      |                                         | TS02  | Implementación de precios y características en cada tarjeta.                             | 3                  | Choquehuanca Núñez, Luciana Carolina | DONE   | **5**          |
| US20 | Reseñas de Clientes                     | TS01  | Recolección de citas y reseñas reales de usuarios.                                       | 2                  | Escobar Palomino, Sebastian Matias   | DONE   |                |
|      |                                         | TS02  | Implementación de carrusel o layout de reseñas.                                          | 2                  | Escobar Palomino, Sebastian Matias   | DONE   | **4**          |
| US21 | Formulario de Contacto                  | TS01  | Maquetación del formulario de contacto (nombre, correo, mensaje).                        | 1.5                | Escobar Palomino, Sebastian Matias   | DONE   |                |
|      |                                         | TS02  | Implementación de validación básica y botón de envío.                                    | 1.5                | Escobar Palomino, Sebastian Matias   | DONE   | **3**          |
| US22 | Videos en la Sección de Características | TS01  | Recolección y organización de videos explicativos.                                       | 1.5                | Prado Vargas, Mario Benjamín         | DONE   |                |
|      |                                         | TS02  | Integración de reproductor de video en la sección de características.                    | 1.5                | Prado Vargas, Mario Benjamín         | DONE   | **3**          |
| US23 | Cambio de Idioma en la App Web          | TS01  | Implementación del botón para cambio de idioma.                                          | 2                  | Prado Vargas, Mario Benjamín         | DONE   |                |
|      |                                         | TS02  | Configuración de contenido multilenguaje (español e inglés).                             | 2                  | Prado Vargas, Mario Benjamín         | DONE   | **4**          |

#### **5.2.1.4. Development Evidence for Sprint Review**

| **Repository**                                                  | **Branch** | **Commit Id** | **Commit Message**                                                                                                | **Committed By** | **Committed On** |
| --------------------------------------------------------------- | ---------- | ------------- | ----------------------------------------------------------------------------------------------------------------- | ---------------- | ---------------- |
| 1ASI0729-2510-4307-G2-InfluMatch/Landing-Page-InfluMatch-Public | develop    | 671b8dc       | feat(images): add new images for project assets                                                                   | ghostnotfound404 | Apr 26, 2025     |
| 1ASI0729-2510-4307-G2-InfluMatch/Landing-Page-InfluMatch-Public | develop    | bfb2010       | Merge branch 'develop' of github.com:1ASI0729-2510-4307-G2-InfluMatch/Landing-Page-InfluMatch-Public into develop | ghostnotfound404 | Apr 26, 2025     |
| 1ASI0729-2510-4307-G2-InfluMatch/Landing-Page-InfluMatch-Public | develop    | fa2c951       | feat(index): add plans                                                                                            | Lucianxaaa       | Apr 26, 2025     |
| 1ASI0729-2510-4307-G2-InfluMatch/Landing-Page-InfluMatch-Public | develop    | 00b1ce6       | feat(index): update styles and content for 'Casos de éxito' and 'Planes' sections                                 | Lucianxaaa       | Apr 26, 2025     |
| 1ASI0729-2510-4307-G2-InfluMatch/Landing-Page-InfluMatch-Public | develop    | 2d1a453       | fix(landing page styles_css): feat update hero section                                                            | Lucianxaaa       | Apr 26, 2025     |
| 1ASI0729-2510-4307-G2-InfluMatch/Landing-Page-InfluMatch-Public | develop    | 3fdb9a1       | fix(landing page): feat update hero section                                                                       | Lucianxaaa       | Apr 26, 2025     |
| 1ASI0729-2510-4307-G2-InfluMatch/Landing-Page-InfluMatch-Public | develop    | f3e4b79       | fix(header): style header and navigation for responsiveness                                                       | devfab17         | Apr 26, 2025     |
| 1ASI0729-2510-4307-G2-InfluMatch/Landing-Page-InfluMatch-Public | develop    | 5b29013       | fix(header): update structure and navigation links                                                                | devfab17         | Apr 26, 2025     |
| 1ASI0729-2510-4307-G2-InfluMatch/Landing-Page-InfluMatch-Public | develop    | 0ac9c10       | fix: upload images and change code of footer section                                                              | mariopvdev       | Apr 26, 2025     |
| 1ASI0729-2510-4307-G2-InfluMatch/Landing-Page-InfluMatch-Public | develop    | a0fe5c2       | feat: update 'Why Choose Us' section layout and replace image                                                     | sebasepe         | Apr 26, 2025     |
| 1ASI0729-2510-4307-G2-InfluMatch/Landing-Page-InfluMatch-Public | develop    | 46b5dbb       | feat: design veterinarian section with features and call-to-action                                                | sebasepe         | Apr 26, 2025     |
| 1ASI0729-2510-4307-G2-InfluMatch/Landing-Page-InfluMatch-Public | develop    | 77bdaaf       | feat: update partners and customers sections with new layout                                                      | sebasepe         | Apr 26, 2025     |
| 1ASI0729-2510-4307-G2-InfluMatch/Landing-Page-InfluMatch-Public | develop    | 9285a1a       | feat: redesign subscriptions section with plan cards and images                                                   | sebasepe         | Apr 26, 2025     |
| 1ASI0729-2510-4307-G2-InfluMatch/Landing-Page-InfluMatch-Public | develop    | 285c2d9       | feat: update 'Why Choose Us' section layout with three images and video icons                                     | sebasepe         | Apr 26, 2025     |

---

#### **5.2.1.5. Execution Evidence for Sprint Review**

En el Sprint 1 se realizó el desarrollo, diseño e implementación de la landing page. Esta página incluye secciones que permiten a los usuarios obtener más información sobre la startup y el producto que se ofrecerá. A continuación, se muestran las evidencias.

**Hero Section (Sección Principal)**

Es la primera sección visible de la página, que presenta un mensaje atractivo para el usuario. En ella se destaca el propósito de la startup, junto con una llamada a la acción como “Get Started” (Comienza ahora). También incluye una imagen relevante que acompaña el mensaje.

<div style="text-align: center;">
  <img src="https://i.imgur.com/IRYz79z.png[/img]"  width="100%" />
</div>

**Why Choose Us?**

En esta sección, se explica por qué la plataforma es valiosa para los usuarios, destacando beneficios como la facilidad de acceso a los registros médicos de las mascotas, un diseño intuitivo y la optimización de tareas diarias. Se acompañan con videos e íconos ilustrativos.

<div style="text-align: center;">
  <img src="https://i.imgur.com/zwxLecZ.png[/img]"  width="100%" />
</div>

**Subscriptions**

Presenta los diferentes planes de suscripción que ofrece la plataforma, como el plan Starter, Growth y Premium, con sus respectivos precios y características. Cada plan está acompañado de una imagen que refleja el nivel del plan.

<div style="text-align: center;">
  <img src="https://i.imgur.com/ZV9nhgF.png[/img]"  width="100%" />
</div>

**Partners (Socios)**

Aquí se muestran los logos de las marcas asociadas o colaboradoras, como proveedores de alimentos y productos para mascotas. Esta sección genera confianza y validación de la plataforma.

<div style="text-align: center;">
  <img src="https://i.imgur.com/uo0xEiV.png[/img]"  width="100%" />
</div>

**Customers (Clientes)**

Esta sección resalta testimonios de usuarios satisfechos, mostrando cómo la plataforma facilita su trabajo diario, con frases como "Flujo de trabajo optimizado" y "Gestión sin esfuerzo". Está acompañada de imágenes de personas con sus mascotas.

<div style="text-align: center;">
  <img src="https://i.imgur.com/rDngf4T.png[/img]"  width="100%" />
</div>

**Sección "¿Eres Veterinario?"**

En esta sección, la plataforma se enfoca en los veterinarios, invitándolos a conocer más sobre las herramientas digitales que PetNova ofrece para gestionar su clínica. El encabezado "¿Eres veterinario?" capta su atención y les dirige a un botón de llamada a la acción con el texto "Gestiona tu clínica", lo que los lleva a registrarse en la plataforma y comenzar a gestionar su clínica de manera digital. La sección incluye íconos relevantes que representan funcionalidades claves, como "Cuidado de la clínica", "Registros de pacientes" y "Citas", brindando un acceso visual y directo a las principales características de la plataforma.

<div style="text-align: center;">
  <img src="https://i.imgur.com/RxzVkV7.png[/img]"  width="100%" />
</div>

**Preguntas Frecuentes (FAQ)**

Esta sección responde a las dudas comunes que los posibles usuarios pueden tener sobre PetNova. Con el encabezado "Preguntas frecuentes", se presentan interrogantes clave como si la plataforma está diseñada solo para clínicas grandes, los beneficios para los veterinarios, cómo PetNova ayuda a simplificar las operaciones diarias y si se necesita conocimientos técnicos para usarla. Los usuarios pueden interactuar con las preguntas, ya que cada una se puede expandir para ver la respuesta detallada, lo que hace que la sección sea amigable y fácil de navegar.

<div style="text-align: center;">
  <img src="https://i.imgur.com/Ybk9Cdu.png[/img]"  width="100%" />
</div>

**Sección de Contacto**

La sección de contacto permite a los usuarios ponerse en contacto directamente con el equipo de PetNova para resolver dudas o inquietudes. El encabezado es claro: "Ponte en contacto con PetNova", y debajo se encuentran campos para ingresar el nombre, número de teléfono y mensaje. Al completar el formulario, los usuarios pueden presionar el botón "Enviar mensaje" para contactar al soporte o al equipo de PetNova de manera directa. Esta sección está diseñada para facilitar la comunicación entre los usuarios y el equipo.

<div style="text-align: center;">
  <img src="https://i.imgur.com/AFZbka2.png[/img]"  width="100%" />
</div>

**Footer**

El footer ofrece enlaces útiles e información adicional. Incluye el enlace "¿Necesitas más información?" que redirige a la sección de contacto, así como las funciones clave de la plataforma, como gestionar, programar citas, registrar mascotas y registrar clientes. También presenta enlaces para descargar la aplicación en diferentes plataformas: iOS, Android, Windows y Mac. Además, se ofrece la posibilidad de conectarse con PetNova a través de redes sociales, proporcionando una manera fácil de mantenerse en contacto y actualizado sobre las novedades de la plataforma.

<div style="text-align: center;">
  <img src="https://i.imgur.com/FjZQiU9.png[/img]"  width="100%" />
</div>

#### **5.2.1.6. Services Documentation Evidence for Sprint Review**

En esta entrega del proyecto, el enfoque principal fue el desarrollo de la landing page, por lo que no se requirió la implementación de servicios adicionales.

#### **5.2.1.7. Software Deployment Evidence for Sprint Review**

Se utilizó GitHub Pages para publicar la landing page, permitiendo su despliegue directamente desde el repositorio de código. A continuación, se comparte el enlace al sitio: https://1asi0730-2510-4370-g4-petnova.github.io/PetNova-Landing-Page/

<div style="text-align: center;">
  <img src="https://i.imgur.com/Qj2QWWe.png[/img]"  width="100%" />
</div>

#### **5.2.1.8. Team Collaboration Insights during Sprint**

Para la realización de este proyecto se utilizaron diversas herramientas, destacando entre ellas Visual Studio Code y el sistema de control de versiones Git. La landing page se dividió en varias secciones, que fueron asignadas a los miembros del equipo de forma individual. Finalmente, uno de los miembros se encargó de integrar las aportaciones de cada participante, consolidando el producto final.

<div style="text-align: center;">
  <img src="https://i.imgur.com/pyad7mE.png[/img]"  width="100%" />
</div>

### 5.2.2. Sprint 2

#### 5.2.2.1. Sprint Planning 2

<table>
  <tr>
    <th> Sprint # </th>
    <th> Sprint 2 </th>
  </tr>
  <tr>
    <td style="font-weight: bold;" colspan="2"> Sprint Planning Background </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Date </td>
    <td> 27/04/2025 </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Time </td>
    <td> 19:00 horas (GMT-5) </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Location </td>
    <td> Virtual (Google Meet) </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Prepared By </td>
    <td> Escobar Palomino, Sebastian Matias </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Attendees (to planning meeting) </td>
    <td>
      Bastidas Bastidas, Diego Martin<br>
      Belahonia Miranda, Fabrisio<br>
      Choquehuanca Núñez, Luciana Carolina<br>
      Escobar Palomino, Sebastian Matias<br>
      Prado Vargas, Mario Benjamín
    </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 1 Review Summary </td>
    <td> En Sprint 1, se completó con éxito la Landing Page de Pet Nova, incluyendo secciones como la barra de navegación, "Why Choose Us?", suscripciones, reseñas, formulario de contacto, videos y cambio de idioma. Todas las User Stories (US17 a US23) fueron implementadas y desplegadas en GitHub Pages. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 1 Retrospective Summary </td>
    <td> El equipo identificó que la comunicación en Google Meet fue efectiva, pero los mensajes de commit podrían ser más descriptivos. Se acordó mejorar la documentación de commits y realizar pruebas de usabilidad más exhaustivas en futuros sprints. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;" colspan="2"> Sprint Goal & User Stories </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 2 Goal </td>
    <td> Iniciar el desarrollo de la Web Application de Pet Nova, implementando funcionalidades clave como el registro e inicio de sesión de usuarios, la gestión de perfiles, el registro de mascotas y las notificaciones de citas, con un enfoque en una interfaz intuitiva, integración inicial con la base de datos MySQL, y pruebas de funcionalidad básica para garantizar una experiencia fluida para veterinarios y dueños de mascotas. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 2 Velocity </td>
    <td> <strong>8</strong><br> El equipo mantiene una capacidad de 8 Story Points para este Sprint, consistente con Sprint 1, considerando la experiencia adquirida y la carga de trabajo estimada. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sum of Story Points </td>
    <td> 8 </td>
  </tr>
</table>

#### 5.2.2.2. Aspect Leaders and Collaborators

| **Team Member (Last Name, First Name)**  | **GitHub Username** | **Capítulo I: Introducción (L/C)** | **Capítulo II: Requirements Elicitation & Analysis (L/C)** | **Capítulo III: Requirements Specification (L/C)** | **Capítulo IV: Product Design (L/C)** | **Capítulo V: Product Implementation, Validation & Deployment (L/C)** |
| ---------------------------------------- | ------------------- | ---------------------------------- | ---------------------------------------------------------- | -------------------------------------------------- | ------------------------------------- | --------------------------------------------------------------------- |
| **Belahonia Miranda, Fabrisio**          | devfab17            | L                                  | C                                                          | C                                                  | C                                     | C                                                                     |
| **Bastidas Bastidas, Diego Martin**      | ghostnotfound404    | C                                  | L                                                          | C                                                  | C                                     | C                                                                     |
| **Choquehuanca Núñez, Luciana Carolina** | lucianxaaa          | C                                  | C                                                          | L                                                  | C                                     | C                                                                     |
| **Prado Vargas, Mario Benjamín**         | mariopvdev          | C                                  | C                                                          | C                                                  | L                                     | C                                                                     |
| **Escobar Palomino, Sebastian Matias**   | sebasepe            | C                                  | C                                                          | C                                                  | C                                     | L                                                                     |

#### 5.2.2.3. Sprint Backlog 2

En el segundo sprint, el equipo se enfocó en iniciar el desarrollo de la Web Application de Pet Nova, implementando funcionalidades esenciales para la autenticación de usuarios, gestión de perfiles, registro de mascotas y notificaciones. Las tareas se asignaron según las habilidades de cada miembro.

#### **5.2.1.4. Sprint Backlog 2**

En el segundo sprint, el equipo centró su desarrollo en funcionalidades esenciales como el registro e inicio de sesión, gestión de perfil y mascotas, así como el sistema de notificaciones. Cada historia de usuario fue dividida en tareas específicas para mejorar la organización y seguimiento del trabajo.

| ID   | Title                   | Tarea | Title de la Tarea              | Description                                                              | Estimations(Hours) | Assigned To                          | Status | Total US Hours |
| ---- | ----------------------- | ----- | ------------------------------ | ------------------------------------------------------------------------ | ------------------ | ------------------------------------ | ------ | -------------- |
| US01 | Registro de usuario     | TS08  | Formulario de registro         | Crear formulario HTML/CSS con validación para nombre, email, contraseña. | 2                  | Bastidas Bastidas, Diego Martin      | To-do  |                |
|      |                         | TS09  | Backend de registro            | Implementar endpoint en backend para guardar usuarios en MySQL.          | 2                  | Bastidas Bastidas, Diego Martin      | To-do  |                |
|      |                         | TS16  | Validación y feedback UI       | Agregar mensajes de error y confirmación en tiempo real.                 | 2                  | Bastidas Bastidas, Diego Martin      | To-do  | **6**          |
| US02 | Inicio de sesión        | TS10  | Formulario de login            | Crear formulario de inicio de sesión con email y contraseña.             | 2                  | Belahonia Miranda, Fabrisio          | To-do  |                |
|      |                         | TS11  | Autenticación backend          | Implementar endpoint para autenticar usuarios con JWT.                   | 2                  | Belahonia Miranda, Fabrisio          | To-do  |                |
|      |                         | TS17  | Control de sesión              | Implementar manejo de sesiones activas con cookies o tokens.             | 2                  | Belahonia Miranda, Fabrisio          | To-do  | **6**          |
| US03 | Gestión de perfil       | TS12  | Pantalla de perfil             | Desarrollar pantalla para mostrar/editar datos del usuario.              | 3                  | Choquehuanca Núñez, Luciana Carolina | To-do  |                |
|      |                         | TS18  | Edición y guardado de datos    | Habilitar edición y validación de campos en el perfil.                   | 2                  | Choquehuanca Núñez, Luciana Carolina | To-do  | **5**          |
| US09 | Registro de mascotas    | TS13  | Formulario de mascota          | Crear formulario para registrar nombre, edad, raza de la mascota.        | 3                  | Escobar Palomino, Sebastian Matias   | To-do  |                |
|      |                         | TS14  | Backend de mascotas            | Implementar endpoint para guardar datos de mascotas en MySQL.            | 2                  | Escobar Palomino, Sebastian Matias   | To-do  |                |
|      |                         | TS19  | Validación de campos mascota   | Validar campos obligatorios y formato adecuado.                          | 1                  | Escobar Palomino, Sebastian Matias   | To-do  | **6**          |
| US15 | Notificaciones de citas | TS15  | Sistema de notificaciones      | Implementar envío de notificaciones por email o en la app para citas.    | 3                  | Prado Vargas, Mario Benjamín         | To-do  |                |
|      |                         | TS20  | Configuración de recordatorios | Permitir al usuario elegir cuándo recibir notificaciones.                | 2                  | Prado Vargas, Mario Benjamín         | To-do  |                |
|      |                         | TS21  | Diseño de UI para alertas      | Crear interfaz para visualizar y gestionar notificaciones.               | 2                  | Prado Vargas, Mario Benjamín         | To-do  | **7**          |

#### 5.2.2.4. Development Evidence for Sprint Review

#### 5.2.2.5. Execution Evidence for Sprint Review

En el Sprint 2 se inició el desarrollo de la Web Application de Pet Nova, implementando funcionalidades esenciales como el registro e inicio de sesión de usuarios, la gestión de perfiles, el registro de mascotas y las notificaciones de citas. Estas funcionalidades permiten a los usuarios (veterinarios y dueños de mascotas) interactuar con la plataforma de manera inicial, facilitando la autenticación y la gestión de datos básicos. A continuación, se muestran las evidencias.

#### 5.2.2.6. Services Documentation Evidence for Sprint Review

#### 5.2.2.7. Software Deployment Evidence for Sprint Review

#### 5.2.2.8. Team Collaboration Insights during Sprint

Para el desarrollo de la Web Application en este sprint, se utilizaron herramientas clave como Visual Studio Code para la escritura de código, Git para el control de versiones, y GitHub para la gestión de ramas y pull requests. Las funcionalidades de la Web App, como el registro e inicio de sesión, gestión de perfiles, registro de mascotas y notificaciones, se dividieron en tareas específicas asignadas a cada miembro del equipo según sus habilidades. Un integrante se encargó de integrar las contribuciones individuales, asegurando la cohesión del producto final.

### 5.2.3. Sprint 3

#### 5.2.3.1. Sprint Planning 3

<table>
  <tr>
    <th> Sprint # </th>
    <th> Sprint 3 </th>
  </tr>
  <tr>
    <td style="font-weight: bold;" colspan="2"> Sprint Planning Background </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Date </td>
    <td> 5/06/2025 </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Time </td>
    <td> 21:00 horas (GMT-5) </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Location </td>
    <td> Virtual (Discord) </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Prepared By </td>
    <td> Escobar Palomino, Sebastian Matias </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Attendees (to planning meeting) </td>
    <td>
      Bastidas Bastidas, Diego Martin<br>
      Belahonia Miranda, Fabrisio<br>
      Choquehuanca Núñez, Luciana Carolina<br>
      Escobar Palomino, Sebastian Matias<br>
      Prado Vargas, Mario Benjamín
    </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 2 Review Summary </td>
    <td> En el Sprint 2, se completó con éxito la Web App de Pet Nova, incorporando funcionalidades como la gestión de usuarios, perfiles de mascotas, citas veterinarias, notificaciones y visualización del historial médico. También se implementaron herramientas administrativas para el manejo de clientes, medicamentos y reportes. Todas las User Stories (US01 a US06, US09, US10, US14, US15, US23 y US31) fueron implementadas y desplegadas en GitHub Pages. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 2 Retrospective Summary </td>
    <td> Durante la retrospectiva, el equipo valoró positivamente la organización del trabajo y el avance sostenido. Se identificó como área de mejora la gestión del tiempo en tareas técnicas específicas. Para próximos sprints, se acordó fomentar revisiones tempranas en equipo para reducir retrabajos. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;" colspan="2"> Sprint Goal & User Stories </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 3 Goal </td>
    <td> Finalizar la implementación completa del backend de Pet Nova, abarcando todos los contextos funcionales definidos, para permitir su integración total con la interfaz frontend. El objetivo incluye asegurar una experiencia coherente y fluida para todos los roles del sistema, consolidar la lógica de negocio, y reforzar aspectos clave como validaciones y consistencia de datos. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 3 Velocity </td>
    <td> <strong>8</strong><br> El equipo mantiene una capacidad de 8 Story Points para este Sprint, consistente con Sprint 2, considerando la experiencia adquirida y la carga de trabajo estimada. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sum of Story Points </td>
    <td> 8 </td>
  </tr>
</table>

#### 5.2.3.2. Aspect Leaders and Collaborators

| **Team Member (Last Name, First Name)**  | **GitHub Username** | **Capítulo I: Introducción (L/C)** | **Capítulo II: Requirements Elicitation & Analysis (L/C)** | **Capítulo III: Requirements Specification (L/C)** | **Capítulo IV: Product Design (L/C)** | **Capítulo V: Product Implementation, Validation & Deployment (L/C)** |
| ---------------------------------------- | ------------------- | ---------------------------------- | ---------------------------------------------------------- | -------------------------------------------------- | ------------------------------------- | --------------------------------------------------------------------- |
| **Belahonia Miranda, Fabrisio**          | devfab17            | L                                  | C                                                          | C                                                  | C                                     | C                                                                     |
| **Bastidas Bastidas, Diego Martin**      | ghostnotfound404    | C                                  | L                                                          | C                                                  | C                                     | C                                                                     |
| **Choquehuanca Núñez, Luciana Carolina** | lucianxaaa          | C                                  | C                                                          | L                                                  | C                                     | C                                                                     |
| **Prado Vargas, Mario Benjamín**         | mariopvdev          | C                                  | C                                                          | C                                                  | L                                     | C                                                                     |
| **Escobar Palomino, Sebastian Matias**   | sebasepe            | C                                  | C                                                          | C                                                  | C                                     | L                                                                     |

#### 5.2.3.3. Sprint Backlog 3

| ID   | Title                           | Tarea | Description                                    | Estimations(Hours) | Assigned To                          | Status     | Total US Hours |
| ---- | ------------------------------- | ----- | ---------------------------------------------- | ------------------ | ------------------------------------ | ---------- | -------------- |
| US01 | Registro de Usuario             | Tk01  | Agregar lógica de validación                   | 3                  | Bastidas Bastidas, Diego Martin      | DONE       |                |
|      |                                 | Tk02  | Definir estructura del modelo                  | 2                  | Belahonia Miranda, Fabrisio          | DONE       |                |
|      |                                 | Tk03  | Desarrollar API REST                           | 3                  | Prado Vargas, Mario Benjamín         | DONE       | **8**          |
| US03 | Gestión de Perfiles de Usuarios | Tk01  | Listar y filtrar usuarios                      | 3                  | Bastidas Bastidas, Diego Martin      | DONE       |                |
|      |                                 | Tk02  | Editar datos de perfil                         | 3                  | Escobar Palomino, Sebastian Matias   | DONE       |                |
|      |                                 | Tk03  | Inhabilitar o eliminar cuentas                 | 2                  | Bastidas Bastidas, Diego Martin      | DONE       | **8**          |
| US04 | Creación de Perfil de Mascota   | Tk01  | Validar y guardar datos de mascota             | 2                  | Choquehuanca Núñez, Luciana Carolina | DONE       |                |
|      |                                 | Tk02  | Controlar duplicidad de nombres                | 3                  | Belahonia Miranda, Fabrisio          | DONE       |                |
|      |                                 | Tk03  | Generar código único por mascota               | 1                  | Choquehuanca Núñez, Luciana Carolina | DONE       | **6**          |
| US05 | Edición de Perfil de Mascota    | Tk01  | Editar datos del perfil de mascota             | 3                  | Escobar Palomino, Sebastian Matias   | DONE       |                |
|      |                                 | Tk02  | Validar campos obligatorios                    | 3                  | Belahonia Miranda, Fabrisio          | DONE       |                |
|      |                                 | Tk03  | Confirmar cambios con retroalimentación visual | 1                  | Escobar Palomino, Sebastian Matias   | IN PROCESS | **7**          |
| US07 | Búsqueda de Mascotas por ID     | Tk01  | Desarrollar búsqueda por ID                    | 2                  | Choquehuanca Núñez, Luciana Carolina | DONE       |                |
|      |                                 | Tk02  | Manejar ID inexistente                         | 2                  | Prado Vargas, Mario Benjamín         | DONE       | **4**          |
| US08 | Gestión de Perfiles de Mascotas | Tk01  | Eliminar perfiles de mascotas                  | 4                  | Belahonia Miranda, Fabrisio          | DONE       |                |
|      |                                 | Tk02  | Actualizar información de mascotas             | 3                  | Prado Vargas, Mario Benjamín         | DONE       | **7**          |
| US09 | Agendamiento de Citas           | Tk01  | Crear lógica de agendamiento                   | 3                  | Escobar Palomino, Sebastian Matias   | TO REVIEW  |                |
|      |                                 | Tk02  | Sugerir citas alternativas                     | 4                  | Escobar Palomino, Sebastian Matias   | DONE       | **7**          |
| US10 | Cancelación de Citas            | Tk01  | Cancelar cita                                  | 4                  | Belahonia Miranda, Fabrisio          | DONE       |                |
|      |                                 | Tk02  | Advertencia por cancelación tardía             | 3                  | Escobar Palomino, Sebastian Matias   | TO REVIEW  | **7**          |
| US11 | Gestión de Citas Veterinarias   | Tk01  | Filtrar por fecha y estado                     | 2                  | Bastidas Bastidas, Diego Martin      | TO-DO      |                |
|      |                                 | Tk02  | Listar todas las citas                         | 4                  | Choquehuanca Núñez, Luciana Carolina | DONE       |                |
|      |                                 | Tk03  | Exportar listado como PDF o Excel              | 2                  | Bastidas Bastidas, Diego Martin      | DONE       | **8**          |
| US12 | Búsqueda de Citas por ID        | Tk01  | Buscar cita por ID                             | 3                  | Escobar Palomino, Sebastian Matias   | DONE       |                |
|      |                                 | Tk02  | Controlar error por ID inválido                | 2                  | Belahonia Miranda, Fabrisio          | DONE       |                |
|      |                                 | Tk03  | Mostrar mensaje sugerido para redirección      | 1                  | Escobar Palomino, Sebastian Matias   | DONE       | **6**          |
| US13 | Edición de Citas Veterinarias   | Tk01  | Actualizar fecha y hora                        | 3                  | Choquehuanca Núñez, Luciana Carolina | DONE       |                |
|      |                                 | Tk02  | Modificar estado y notificar                   | 4                  | Bastidas Bastidas, Diego Martin      | TO REVIEW  | **7**          |
| US24 | Edición de Perfiles de Clientes | Tk01  | Registrar cliente con datos obligatorios       | 4                  | Prado Vargas, Mario Benjamín         | DONE       |                |
|      |                                 | Tk02  | Generar ID único de cliente                    | 3                  | Choquehuanca Núñez, Luciana Carolina | DONE       | **7**          |
| US25 | Edición de Perfiles de Clientes | Tk01  | Editar datos del cliente                       | 3                  | Escobar Palomino, Sebastian Matias   | DONE       |                |
|      |                                 | Tk02  | Agregar nuevas mascotas                        | 3                  | Bastidas Bastidas, Diego Martin      | DONE       |                |
|      |                                 | Tk03  | Validar relaciones mascota-cliente             | 1                  | Escobar Palomino, Sebastian Matias   | IN PROCESS | **7**          |
| US26 | Búsqueda de Clientes por ID     | Tk01  | Buscar cliente por ID exacto                   | 4                  | Prado Vargas, Mario Benjamín         | DONE       |                |
|      |                                 | Tk02  | Mostrar sugerencias por coincidencia parcial   | 3                  | Choquehuanca Núñez, Luciana Carolina | IN PROCESS | **7**          |

#### 5.2.3.4. Development Evidence for Sprint Review

|                                 Repository                                  |     Branch     | Commit Id |                     Commit <br>Message                     | Commit <br>Message Body | Commited <br>on (Date) |
| :-------------------------------------------------------------------------: | :------------: | :-------: | :--------------------------------------------------------: | :---------------------: | :--------------------: |
| [Backend](https://github.com/1ASI0730-2510-4370-G4-PetNova/PetNova-BackEnd) |   feat/diego   |  25de917  |                feat: code backend pet nova                 |                         |       21/06/2025       |
|                               PetNova-Backend                               |   feat/diego   |  3f8f027  |           feat: add codebase backend of Pet Nova           |                         |       21/06/2025       |
|                               PetNova-Backend                               |  feat/luciana  |  6f5a58c  |          feat(shared): implement JwtTokenService           |                         |       21/06/2025       |
|                               PetNova-Backend                               | feat/fabrisio  |  de2e786  |              feat(shared): implement SeedDara              |                         |       21/06/2025       |
|                               PetNova-Backend                               | feat/sebastian |  e795eb8  |         feat(shared): implement generic UnitofWork         |                         |       21/06/2025       |
|                               PetNova-Backend                               | feat/fabrisio  |  7086d6c  |        feat(shared): implement generic EfRepository        |                         |       21/06/2025       |
|                               PetNova-Backend                               |   feat/mario   |  10d0d85  |            feat(shared): add Swagger Extension             |                         |       21/06/2025       |
|                               PetNova-Backend                               | feat/sebastian |  920f290  |               feat(shared): add AppDbContext               |                         |       21/06/2025       |
|                               PetNova-Backend                               | feat/fabrisio  |  5592eff  |               feat(shared): add ToKebabCase                |                         |       21/06/2025       |
|                               PetNova-Backend                               |  feat/luciana  |  fbd932d  |                feat(shared): add kebab-case                |                         |       21/06/2025       |
|                               PetNova-Backend                               |   feat/mario   |  973f244  |          feat(shared): add IUnitOfWork interface           |                         |       21/06/2025       |
|                               PetNova-Backend                               | feat/sebastian |  1c8d128  |      feat(shared): add generic IRepository interface       |                         |       21/06/2025       |
|                               PetNova-Backend                               |  feat/luciana  |  270155c  |         feat(shared): add ITokenService interface          |                         |       21/06/2025       |
|                               PetNova-Backend                               |   feat/mario   |  25de917  |                feat: code backend pet nova                 |                         |       21/06/2025       |
|                              PetNova-Frontend                               |   feat/mario   |  efb8856  |                feature: Add search function                |                         |       21/06/2025       |
|                              PetNova-Frontend                               |   feat/diego   |  f18f89b  |                 Update: form to create pet                 |                         |       21/06/2025       |
|                              PetNova-Frontend                               | feat/sebastian |  85501a6  | feat(home): add initial implementation of home and profile |                         |       21/06/2025       |

#### 5.2.3.5. Execution Evidence for Sprint Review

Para esta entrega nuestro equipo logró completar con éxito la creación y el deployment del FrontEnd de la Aplicación Web.

También se lanzó una nueva versión de la página de inicio y del frontend de la aplicación, optimizando la experiencia del usuario y habilitando acceso a funciones esenciales desarrolladas en este sprint, como la creación y administración de perfiles de usuario y mascota. Esta actualización incorpora videos informativos sobre el producto y el equipo, ofreciendo un resumen de los servicios de Pet Nova.

La API del backend se documenta mediante Swagger, facilitando el acceso a todos los endpoints para el equipo de desarrollo y futuros colaboradores.

Enlace del deployment del Backend: FALTA

Enlace del deployment del FrontEnd: [https://petnovaapp.netlify.app/](https://petnovaapp.netlify.app/)

Enlace del deployment de la Landing Page: [https://1asi0730-2510-4370-g4-petnova.github.io/PetNova-Landing-Page/](https://1asi0730-2510-4370-g4-petnova.github.io/PetNova-Landing-Page/)

**Swagger UI**

<img src="./assets/Chapter05/Swagger UI.jpg">

**Seccion video about the team en landing page**

[![About the product video](IMAGEN FALTA)](FALTA LINK DEL VIDEO)

**Seccion video about the product en landing page**

[![About the product video](./assets/Chapter05/about_the_product.JPG)](https://www.youtube.com/watch?v=21mBKrna1iw)

#### 5.2.3.6. Services Documentation Evidence for Sprint Review

El alcance del Sprint 3, el equipo se centro principalmente en la integración, implementación y despliegue de los bounded contexts de clientes y mascotas en el backend, también se realizaron las correciones del fronted y añadimos algunas otras vistas y funcionalidad, como el filtro de mascotas por nombre. Durante este sprint, se actualizó y extendió la documentación de servicios web mediante Swagger, proporcionando una guía clara y completa para el uso de la API por parte del frontend y futuros desarrolladores.

La documentación incluye:
Descripción detallada de los endpoints relacionados con clientes y mascotas. Operaciones permitidas como la creación, edición y eliminación de datos en estos módulos. Ejemplos actualizados de solicitudes y respuestas para garantizar una integración efectiva con el frontend. Información sobre las capas de seguridad y autenticación implementadas en el backend. Este nivel de documentación asegura que todos los miembros del equipo tengan una comprensión compartida y uniforme sobre el comportamiento y las capacidades de la API, lo que facilita el desarrollo continuo y la integración de nuevas funcionalidades.

#### 5.2.3.7. Software Deployment Evidence for Sprint Review

En este trabajo se hizo uso de las siguientes herramientas para el desarrollo del backend de la aplicación web, como también para la actualización del frontend.

- Git: Sistema de control de versiones.

- GitFlow: Flujo de trabajo colaborativo.

- GitHub Desktop: Herramienta de interfaz gráfica que utilizamos para interactuar con nuestro repositorio de GitHub.

- GitHub: Plataforma de desarrollo colaborativo que nos proporcionó el repositorio donde almacenamos y gestionamos el código fuente de nuestro proyecto.

- Azure Web Services: Servicio en la nube utilizado para desplegar el backend de nuestra aplicación.

- MySQL for Azure: Servicio de base de datos en la nube que utilizamos para almacenar y gestionar los datos de la aplicación.

Enlace del deployment de la Landing Page: [https://1asi0730-2510-4370-g4-petnova.github.io/PetNova-Landing-Page/](https://1asi0730-2510-4370-g4-petnova.github.io/PetNova-Landing-Page/)

Enlace del deployment del FrontEnd: [https://petnovaapp.netlify.app/](https://petnovaapp.netlify.app/)

Enlace del deployment del Backend: FALTA

#### 5.2.3.8. Team Collaboration Insights during Sprint

En el Sprint 3, el equipo organizó el desarrollo del backend y correción del frontend de la aplicación web utilizando ramas específicas para cada funcionalidad, siguiendo las convenciones de GitFlow. Este enfoque permitió a los desarrolladores trabajar de manera independiente en diferentes aspectos del proyecto, facilitando la colaboración y el mantenimiento del código.

A continuación, se detallan las tareas asignadas a cada miembro del equipo, junto con las contribuciones realizadas a través de la plataforma GitHub:

| Alumno                                   | Actividad                                                                                                                                                      |
| ---------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Choquehuanca Núñez, Luciana Carolina** | Desarrollo y despliegue del backend como también en el frontend en la nube, garantizando la operatividad de la API y su integración con el frontend.           |
| **Bastidas Bastidas, Diego Martin**      | Desarrollo del backend y soporte en la integración de datos, contribuyendo al diseño y funcionalidad de los módulos clave, también desarrolló el frontend.     |
| **Prado Vargas, Mario Benjamín**         | Implementación de características tanto en el backend como en el frontend, mejorando la experiencia de usuario y asegurando la funcionalidad de la plataforma. |
| **Escobar Palomino, Sebastian Matias**   | Desarrollo del frontend junto con el backend y diseño de la landing page, enfocándose en la usabilidad y estética para ofrecer una experiencia intuitiva.      |
| **Belahonia Miranda, Fabrisio**          | Desarrollo del frontend junto con el backend y diseño de la landing page, enfocándose en la usabilidad y estética para ofrecer una experiencia intuitiva.      |

A continuación, se mostrará la tabla de colaboradores en el repositorio de GitHub, con el objetivo de identificar a cada miembro del equipo.

Tabla de integrantes:

| Username (GitHub) | Nombre                               |
| ----------------- | ------------------------------------ |
| ghostnotfound404  | Bastidas Bastidas, Diego Martin      |
| lucianxaaa        | Choquehuanca Núñez, Luciana Carolina |
| mariopvdev        | Prado Vargas, Mario Benjamín         |
| sebasepe          | Escobar Palomino, Sebastian Matias   |
| devfab17          | Belahonia Miranda, Fabrisio          |

A continuación se mostrarán los gráficos de insights durante el sprint:

Anexo: Flujo de trabajo entre las ramas.

<img src="./assets/Chapter05/graph.JPG">

Anexo: Tablas de commits en el periodo de 1 mes.

<img src="./assets/Chapter05/Commits over time.png">
<img src="./assets/Chapter05/commits insights.JPG">

#### 5.3. Validation Interviews

#### 5.3.1. Diseño de Entrevistas

#### 5.3.2. Registro de Entrevistas

#### 5.3.3. Evaluación Basada en Heurísticas

| **Sitio o App Evaluada**         | Pet Nova                                                                                                                                                                                                                                                                                           |
| :------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Tareas evaluadas**             | Esta evaluación abarca la revisión de usabilidad de las siguientes tareas:                                                                                                                                                                                                                         |
| **Landing Page (Desktop)**       | - Información y descripción de la app y sus funciones <br> - Breve descripción del equipo de trabajo <br> - Visualización de testimonios <br> - Header y footer funcionales                                                                                                                        |
| **Aplicación Web (Desktop)**     | - Visualización de datos registrados en el sistema <br> - Header y footer funcionales <br> - Pestañas de navegación internas <br> - Botones intuitivos e interactivos <br> - Visualización de elementos relacionados                                                                               |
| **Excluidas en esta evaluación** | - Landing Page (Desktop) <br> - Formularios de registro o cambio de contraseña <br> - Políticas de privacidad y términos de uso <br> - Aplicación Web (Desktop) <br> - Perfil de usuario <br> - Detalles ampliados de productos al seleccionarlos <br> - Políticas de privacidad y términos de uso |

**ESCALA DE GRAVEDAD:**

Los errores se clasificarán según la siguiente escala:

| Nivel | Descripción                                                                                                                                                  |
| :---- | :----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1     | Error menor: el usuario puede solucionarlo fácilmente o ocurre raramente. No es urgente corregirlo, salvo que haya tiempo disponible.                        |
| 2     | Error moderado: aparece con más frecuencia o representa una dificultad media para el usuario. Debe resolverse en futuras actualizaciones con prioridad baja. |
| 3     | Error grave: frecuente o difícil de resolver para los usuarios. Requiere corrección prioritaria.                                                             |
| 4     | Error crítico: impide el uso normal de la herramienta. Debe solucionarse antes del lanzamiento.                                                              |

**TABLA RESUMEN (AMBOS SEGMENTOS):**

**Aplicación Web**

| #   | Problema | Gravedad | Heurística/Principio afectado          |
| :-- | :------- | :------- | :------------------------------------- |
| 1   |          | 1        | IA - ¿Es claro?                        |
| 2   |          | 2        | IA - ¿Es fácil de encontrar?           |
| 3   |          | 1        | Usabilidad - Consistencia y estándares |

**Landing Page**

| #   | Problema | Gravedad | Heurística/Principio afectado |
| :-- | :------- | :------- | :---------------------------- |
| 1   |          | 1        | IA - ¿Es claro?               |
| 2   |          | 1        | IA - ¿Es usable?              |
| 3   |          | 1        | IA - ¿Es usable?              |

**DETALLE DE PROBLEMAS:**

**1. Aplicación Web**

**PROBLEMA #1:**

| Gravedad: 1             | Heurística: IA - ¿Es claro?                                                                           |
| :---------------------- | :---------------------------------------------------------------------------------------------------- |
| **Inconveniente:**      | La navegación dentro de la app podría no ser intuitiva, dificultando la ubicación de secciones clave. |
| **Solución propuesta:** | Mejorar la estructura de navegación y usar etiquetas más descriptivas en las pestañas.                |

**PROBLEMA #2:**

| Gravedad: 2             | Heurística: IA - ¿Es fácil de encontrar?                                                             |
| :---------------------- | :--------------------------------------------------------------------------------------------------- |
| **Inconveniente:**      | La información importante no es visible o requiere demasiados pasos para acceder a ella.             |
| **Solución propuesta:** | Reestructurar la disposición de la información para facilitar su acceso desde la pantalla principal. |

---

**2. Landing Page**

**PROBLEMA #1:**

| Gravedad: 1             | Heurística: Usabilidad - Consistencia y estándares                  |
| :---------------------- | :------------------------------------------------------------------ |
| **Inconveniente:**      | Falta uniformidad en el diseño entre distintas secciones.           |
| **Solución propuesta:** | Definir y aplicar guías de diseño coherentes en toda la plataforma. |

**PROBLEMA #2:**

| Gravedad: 1             | Heurística: IA - ¿Es claro?                                                        |
| :---------------------- | :--------------------------------------------------------------------------------- |
| **Inconveniente:**      | La descripción de la app y sus funciones no es suficientemente clara.              |
| **Solución propuesta:** | Redactar textos más simples y directos que expliquen mejor el propósito de la app. |

**PROBLEMA #3:**

| Gravedad: 1             | Heurística: IA - ¿Es usable?                                                     |
| :---------------------- | :------------------------------------------------------------------------------- |
| **Inconveniente:**      | Los testimonios no destacan y podrían no ser notados por los usuarios.           |
| **Solución propuesta:** | Rediseñar la sección de testimonios para mejorar su visibilidad y funcionalidad. |

---

### 5.4. Video About the Product

En este video presentamos **Pet Nova**, una innovadora aplicación diseñada para mejorar la gestión de la salud y bienestar de las mascotas.

**Características principales:**

- **Interfaz intuitiva** que facilita el acceso a información relevante
- **Gestión integral** de la salud de las mascotas
- **Historial médico** siempre actualizado

**Funcionalidades destacadas:**

| Función              | Beneficio                                                   |
| -------------------- | ----------------------------------------------------------- |
| Perfiles de mascotas | Creación y edición de perfiles detallados para cada mascota |
| Historial médico     | Acceso rápido al registro completo de salud de la mascota   |

**Ventajas clave:**

1. **Organización centralizada** de toda la información médica
2. **Recordatorios automáticos** para no olvidar citas importantes
3. **Acceso inmediato** al historial clínico cuando se necesita

La aplicación está diseñada para brindar **paz mental** a los dueños de mascotas, asegurando que sus compañeros animales reciban siempre los mejores cuidados.

#### **Avance de Conclusiones**

- La colaboración efectiva entre los miembros del equipo fue clave para avanzar de manera organizada y cubrir todas las etapas del proyecto. Cada integrante asumió con claridad su rol y responsabilidades, facilitando una ejecución ordenada.

- La definición de User Stories y del Product Backlog permitió priorizar las funcionalidades esenciales, asegurando que el producto respondiera a las necesidades del mercado.

- Un diseño de arquitectura sólido y orientado a objetos favoreció la escalabilidad y el mantenimiento, minimizando riesgos en el despliegue.

- El uso de metodologías ágiles, como reuniones de sprint y retrospectivas, ayudó a ajustar prioridades y mejorar continuamente el flujo de trabajo.

- Finalmente, el enfoque en UI/UX permitió construir una plataforma intuitiva y atractiva para los usuarios finales.

#### **Bibliografia**

- Sedano, L. (2024). _Manual para la gestión eficaz de clínicas veterinarias: Estrategias administrativas y organizativas_. Recuperado de [https://punto-medic.cl/blogs/manuales-y-guias/manual-para-la-gestion-eficaz-de-clinicas-veterinarias-estrategias-administrativas-y-organizativas](https://punto-medic.cl/blogs/manuales-y-guias/manual-para-la-gestion-eficaz-de-clinicas-veterinarias-estrategias-administrativas-y-organizativas)

- BioSystems S.A. (s.f.). _Guía de buenas prácticas en veterinaria_. Barcelona, España: ioSystems S.A. Recuperado de [https://covetrija.org/wp-content/uploads/2021/10/VET_GuiaBuenasPracticas_ESP.pdf](https://covetrija.org/wp-content/uploads/2021/10/VET_GuiaBuenasPracticas_ESP.pdf)

#### **Anexo**

1. Despliegue del Landing Page: https://1asi0730-2510-4370-g4-petnova.github.io/PetNova-Landing-Page/
2. Figma con los User Flow Diagrams, wireframes y mockups de la landing page.: https://www.figma.com/design/XjI2alaHmyFV0MPlaPpxzO/Web-design?node-id=401-8424&t=kuv2vsPlXaFzVYvk-0
3. Video De Exposición TB1: https://upcedupe-my.sharepoint.com/:f:/g/personal/u20221a301_upc_edu_pe/Eqi44YEDeiVKgGPNfaTVK6MBWYenSQeOT--MkZtImi2TbQ?e=86Pe27
