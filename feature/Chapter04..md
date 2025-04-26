
# **CAPÍTULO IV: PRODUCT DESIGN**
El objetivo principal de esta sección es definir el diseño funcional y visual de la plataforma, transformando los requerimientos en interfaces intuitivas y accesibles para veterinarios y dueños de mascotas. A través de flujos de usuario, wireframes y lineamientos visuales, se asegura una experiencia coherente y fluida, facilitando la gestión de historiales, productos y servicios. Este diseño mejora la eficiencia operativa, apoya la misión de mejorar la calidad de vida de las mascotas y sus dueños, y contribuye a la visión de convertir a la plataforma en la herramienta líder en gestión veterinaria, optimizando el cuidado de las mascotas y fortaleciendo la relación entre veterinarios y propietarios.

## 4.1. Style Guidelines.
Es una serie de normas que definen la identidad visual y la interacción estética de un producto.Funciona como una guía de estilo que asegura la coherencia visual en todos los componentes del diseño, incluyendo colores, tipografías, íconos e imágenes, manteniéndolos en sintonía con la identidad visual y la esencia de la marca. A continuación, se presentan las pautas de estilo definidas para nuestro proyecto.

## 4.1.1 General Style Guidelines

### Branding

La identidad visual de la marca **PETNOVA** representa el compromiso con el cuidado animal moderno e integral. El logotipo presenta la figura de un conejo dentro de un círculo, proyectando cercanía, agilidad y confianza. El nombre **PETNOVA** se muestra en una tipografía clara y moderna, lo que refuerza la imagen tecnológica y accesible de la plataforma.

![PETNOVA_LOGO.png](PETNOVA_LOGO.png)

### Typography

Se utilizará la tipografía **Poppins**, ideal por su estilo limpio, amigable y altamente legible en distintos dispositivos. Se empleará en todos los niveles de texto: títulos, subtítulos, etiquetas e información dentro de formularios, garantizando una jerarquía visual clara y coherente.

### Colors

La paleta de colores está basada en tonos azules claros, los cuales transmiten confianza, tranquilidad y tecnología amigable. Estos colores permiten una navegación intuitiva, sin causar fatiga visual, y mantienen un entorno accesible tanto para veterinarios como para usuarios frecuentes.

![Paleta_colores.png](Paleta_colores.png)

**Principal:**  
`#6ABFE3` – Celeste claro: Botones principales, títulos destacados y acciones clave.

**Secundario:**  
`#1E3A5F` – Azul profundo: Encabezados, fondo de navbar, pie de página o énfasis visual.

**Fondo:**  
- `#EAF7FC` – Celeste muy claro: Fondo de secciones, formularios, y contenedores suaves.  
- `#FFFFFF` – Blanco puro: Fondo base de pantallas, tarjetas, inputs y elementos limpios.

**Neutro:**  
`#A0AAB2` – Gris suave: Texto secundario, íconos, bordes, descripciones.

### Tone of Communication

- **Amigable:** Para mensajes generales y explicaciones dentro de la plataforma, buscando cercanía con los usuarios.
- **Profesional:** Aplicado en las descripciones de servicios, reportes médicos y perfiles de mascotas, manteniendo claridad y precisión.
- **Empático:** Para comunicar situaciones sensibles como alertas de salud o historial médico.
- **Informativo:** En mensajes de ayuda, tutoriales o recomendaciones veterinarias.
- **Motivador:** Para celebrar logros como revisiones completas o mejoras en la salud de las mascotas.
- **Formal:** En secciones legales como términos, condiciones y políticas de privacidad.
  
### 4.1.2. Web Style Guidelines

**Elementos Visuales:**
Se emplearán imágenes y videos con distintas finalidades. Las imágenes incluirán desde íconos hasta fotos de perfil, mientras que los videos formarán parte de la explicación del contenido, especialmente en la sección de características, facilitando el aprendizaje visual.
**Botones:**
Los botones permitirán al usuario ejecutar acciones como enviar formularios o navegar por la plataforma. Su diseño seguirá las pautas de estilo establecidas, destacándose claramente entre los demás elementos visuales para garantizar una interacción fluida.
**Formularios:**
Se implementarán formularios para usuarios que deseen registrarse ingresando sus datos personales. Su estructura estará pensada para facilitar la experiencia del usuario durante estos procesos clave.
**Interfaz Web Responsiva:**
La aplicación presentará un diseño adaptable a distintos dispositivos, gracias al uso de Flexbox y CSS Grid. Se prioriza la usabilidad mediante una interfaz clara e intuitiva, compatible con navegadores como Chrome, Firefox y Safari. Además, las imágenes estarán optimizadas para asegurar una carga rápida incluso con conexiones lentas.

## 4.2. Information Architecture

La arquitectura de la información es fundamental para organizar y estructurar el contenido de forma que sea fácil de entender y navegar. En este apartado, abordaremos cómo se han definido las categorías, las etiquetas, la optimización SEO, las metaetiquetas, y los sistemas de búsqueda y navegación que construyen la base de nuestro producto.


## 4.2.1. Organization Systems

### 4.2.2. Labeling Systems

**Sistemas de Etiquetado**
Los sistemas de etiquetado cumplen un rol clave en la organización del contenido, ya que permiten mejorar la navegación y facilitar la búsqueda de información dentro del producto. Según el contexto y el tipo de usuario, se han definido diferentes enfoques de etiquetado:


- **Etiquetado Descriptivo:** Se utilizan términos claros y precisos que describen directamente el contenido, permitiendo que el usuario entienda rápidamente su propósito y lo localice fácilmente mediante el buscador.


    - Ejemplos antes de iniciar sesión: Inicio, Why choose us?, Contact, Service feature.


- **Etiquetado por Perfil de Usuario:** Las etiquetas se adaptan a las características o necesidades del usuario según su rol o nivel de acceso, mejorando así la relevancia de la información mostrada.


    - Ejemplos después de iniciar sesión: Mis mascotas, Citas, Historial de mascotas, Notificaciones de citas, Perfil, Cerrar sesión.


- **Etiquetado Basado en Relevancia:** Aquí, las etiquetas se asignan considerando la popularidad o utilidad del contenido. Esto puede basarse en estadísticas de uso o en la interacción de los usuarios, como clics, valoraciones o frecuencia de acceso.



### 4.2.3. SEO Tags and Meta Tags

### 4.2.4. Searching Systems

 **Sistemas de Búsqueda**


Contar con un sistema de búsqueda eficiente es clave para que los usuarios puedan acceder rápidamente a la información que necesitan. A continuación, se presentan los distintos métodos de búsqueda implementados:

- **Búsqueda por Términos Clave:** El usuario puede ingresar palabras específicas para localizar contenido relacionado. El sistema muestra los resultados más cercanos a esos términos.


- **Búsqueda con Filtros:** Permite acotar los resultados aplicando criterios como categoría, fecha o tipo de contenido, lo que mejora la exactitud de lo que se busca.


- **Búsqueda Facetada:** Esta opción ayuda a refinar los resultados utilizando distintas propiedades del contenido, como ubicación, temática o tipo, ideal para manejar grandes volúmenes de datos.


- **Búsqueda por Relevancia:** Ordena los resultados según qué tan útiles o relacionados son con lo buscado, gracias a algoritmos que priorizan la información más pertinente.


### 4.2.5. Navigation Systems
## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up
## 4.4. Web Applications UX/UI Design

Crear una experiencia de usuario efectiva en aplicaciones web requiere planificar cuidadosamente cada interacción del usuario. En esta sección se muestran los wireframes, flujos de navegación y mockups que aseguran una interfaz clara y fácil de usar.


### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups
### 4.4.4. Web Applications User Flow Diagrams
## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture

Este enfoque resalta la importancia de comprender profundamente el dominio del negocio para el cual se desarrolla el software. Su objetivo es diseñar soluciones alineadas de manera precisa con las necesidades y particularidades del negocio, garantizando que el sistema aporte verdadero valor y responda eficazmente a sus requerimientos.

### 4.6.1. Software Architecture Context Diagram 
### 4.6.2. Software Architecture Container Diagrams
### 4.6.3. Software Architecture Components Diagrams
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
### 4.7.2. Class Dictionary
## 4.8. Database Design
### 4.8.1. Database Diagram 

###

###

###

###

###
