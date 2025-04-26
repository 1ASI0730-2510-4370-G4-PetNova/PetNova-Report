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

<img src="./assets/Chapter05/deploy1.jpg">

2. Accdemos a Github Pages:<br><br>
   <img src="./assets/Chapter05/deploy2.jpg">

3. Una vez completada la configuración, GitHub Pages generó la URL pública de la Landing Page de Pet Nova, permitiendo su acceso y distribución. <br><br>
   <img src="./assets/Chapter05/rep3.png">

Enlace a la Landing Page de Pet Nova:<br>
https://1asi0730-2510-4370-g4-petnova.github.io/Landing-Page-NovaPet/

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
    <td> Diseñar y desarrollar las secciones principales de la Landing Page de Pet Nova para permitir a los usuarios explorar sus funcionalidades y comprender los beneficios que ofrece el servicio. </td>
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


#### **5.2.1.3. Sprint Backlog 1**



#### **5.2.1.4. Development Evidence for Sprint Review**



#### **5.2.1.5. Execution Evidence for Sprint Review**


#### **5.2.1.6. Services Documentation Evidence for Sprint Review**


#### **5.2.1.8. Team Collaboration Insights during Sprint**

#### **Avance de Conclusiones**


#### **Bibliografia**


#### **Anexo**
1. Despliegue del Landing Page: 
2. Figma con los User Flow Diagrams, wireframes y mockups de la landing page.: 

