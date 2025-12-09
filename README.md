<<<<<<< HEAD
# Almers
# Nombre del equipo.
Eldarûn


# Nombre del mundo. 
World of Fantasy


# Descripción del mundo.
El mundo de los elfos está dividido entre luz, penumbra y gloria eterna.
En la superficie, Alfheim florece como un reino de bosques encantados, ciudades llenas de música y mercados perfumados donde la magia convive en paz con la naturaleza. Muy por debajo, oculto entre cavernas infinitas, Menzoberranzan retuerce esa gracia élfica en intriga y veneno: una ciudad de belleza oscura, bioluminiscencia púrpura y sonrisas afiladas como dagas. Por encima de ambos, más allá del alcance de los mortales, se alza Valinor, el cielo de los elfos: un reino dorado y sagrado donde la luz nunca muere y sus habitantes guardan, en silencio, secretos tan antiguos como el comienzo del mundo.


# integrantes
Miguel David Calle restrepo
Camilo Florez Moreno
Hector Hernan Rios Ramirez
Ximena Jaramillo Cardenas

Sección “Semántica usada” (mínimo 5 etiquetas).
# Semántica usada
<header> - Encabezado con navegación y título
<nav> - Navegación entre reinos
<main> - Contenido principal de la página
<article> - Cada reino es un artículo independiente con id único
<h1>, <h2> - Jerarquía de títulos
<footer> - Pie de página con información de autores
<audio> - Elemento multimedia para música de fondo
<p> - Párrafos 

Breve explicación (2–4 líneas) de cómo organizaron el trabajo con ramas.
URL pública del sitio en GitHub Pages.


# Contribución de cada miembro

# Miguel David Calle restrepo

# Camilo Florez Moreno

Este mini–proyecto es básicamente una página web donde presentas **tres razas de elfos**, cada una con su propia imagen, descripción y efectos visuales. Todo está dividido en dos archivos: uno HTML y uno CSS. A continuación te explico qué hace cada parte.


# Hector Hernan Rios Ramirez
En el proyecto, mi trabajo principal fue crear toda la historia, identidad y fondo narrativo del mundo de los elfos. No solo escribí descripciones, sino que construí todo el concepto que une a las razas como si existieran dentro de un mismo universo real.

Yo desarrollé la idea de que todas las razas pertenecen a un solo pueblo llamado Eldarûn, que significa “Los Hijos del Alba Eterna”. A partir de ese nombre, creé los nombres de cada rama élfica para que todo tuviera coherencia y no pareciera aleatorio:

Eldarûn Aethr para los Elfos Primordiales.

Eldarûn Sylr para los Elfos del Bosque.

Eldarûn Vayr para los Elfos del Vacío.

Mi idea fue que no fueran razas sueltas, sino una familia dividida por su historia.

También escribí todas las descripciones: su origen, cómo viven, cómo se visten, qué creen y cómo se relacionan con la magia. Traté de que cada raza tuviera personalidad propia:
que los Primordiales se sintieran divinos, los del Bosque vivos y los del Vacío inquietantes.

Además, ayudé a definir el mundo en el que existen, inventando lugares como Menzoberranzan y la estructura de las ciudades élficas, para que el proyecto no fuera solo una página bonita, sino un universo con lógica.

En resumen, yo me encargué de que esto no fuera solo “una web de elfos”, sino una historia con alma.
Le di nombre, identidad y corazón al proyecto.

# Ximena Jaramillo Cardenas

Kingdoms es la página principal del proyecto. En ella se presenta una pequeña introducción de los tres reinos de fantasía: Menzoberranza, Valinor y Alfheim. Desde esta página se puede acceder a cada reino a través de dos tipos de enlaces: los subtítulos de cada reino y los logos ubicados en la parte superior derecha.

Los logos tienen dos funciones en todas las páginas. La primera es la navegación: al hacer clic en el logo de un reino, se abre la página correspondiente a ese reino. La segunda es el control de la música: si ya estás en la página de un reino y vuelves a hacer clic sobre el logo de ese mismo reino, comienza a sonar la música de fondo asociada a ese mundo. En la página principal, al hacer clic en el logo de Kingdoms también se inicia la música. Cada página tiene una canción diferente, pensada para ambientar el universo de cada reino.

Los fondos de todas las páginas son imágenes relacionadas con los mundos que representan, lo que refuerza la temática y la inmersión del usuario. Los logos se reutilizan en todas las páginas (se copiaron y pegaron), de modo que la identidad visual se mantiene consistente a lo largo de todo el sitio.

Cada uno de los reinos, Menzoberranza, Valinor y Alfheim, cuenta con su propia página individual. Estas páginas están organizadas en tres secciones principales: Población, Mapas e Infraestructuras. Además, cada reino tiene su propio logo y su propia pista musical, que se activa mediante el logo tal como se describió antes. De esta manera, cada reino ofrece una experiencia única, tanto en su contenido como en su ambientación visual y sonora.
Importante, las imagenes que utilice algunas son sacadas de pinteres pero la mayoria socreadas con chatgpt.
=======
# Almers# Archivos Élficos — Almers

## Descripción General

**Archivos Élficos** es un proyecto web interactivo que presenta el lore, razas, habilidades y reinos de un universo élfico mediante una interfaz narrativa basada en portales. El proyecto combina diseño artístico, estructura narrativa inmersiva e interactividad visual para crear una experiencia cohesiva.

---

## Visión del Proyecto

El sitio se organiza en **cuatro secciones principales** accesibles desde un index narrativo:

1. **Chronicles of the First Dawn** — Historia y origen de los elfos
2. **Songs of the Endless Blood and the Whispering Void** — Razas y linajes élficos
3. **Codex et Grimoria Magna Arcana Aethrûn** — Habilidades y magia
4. **Chronicles of the Explorers, Cities and the Realm** — Reinos y ciudades

Cada sección funciona como portal independiente pero cohesivo, conectado visualmente por una paleta de colores élfica (plateados, verdes, morados, dorados) y efectos visuales consistentes.

---

## Estructura del Proyecto

```
Almers/
├── index.html                 # Página principal con portales narrativos
├── history.html              # Sección: Historia y origen élfico
├── races_and_class.html      # Sección: Razas y linajes
├── elves_habilities.html     # Sección: Habilidades y magia
├── kingdoms.html             # Sección: Reinos principales
├── Menzoberranzan.html       # Página interna: Ciudad subterránea
├── Alfheim.html              # Página interna: Reino aéreo
├── Valinor.html              # Página interna: Reino divino
├── styles.css                # Hoja de estilos unificada
├── imagenes/                 # Logo, botones e imágenes de razas
├── fondo/                    # Fondos y texturas
└── fonts/                    # Fuentes personalizadas (Tengwar Annatar, Ringbearer)
```

---

## Tecnologías Utilizadas

- **HTML5**: Estructura semántica y portales interactivos
- **CSS3**: Gradientes temáticos, sombras metálicas, efectos de texto arcano, responsive design
- **Imágenes generadas por IA**: Personajes, fondos y elementos visuales

---

## Contribuciones por Rol

### Miguel David Calle Restrepo (Migue) — Dirección Creativa & Integración

**Responsabilidades:**
- Dirección creativa general y visión narrativa del universo élfico
- Arquitectura y diseño del index como "puerta narrativa" del mundo
- Definición de paleta de colores y estilo visual (plateados, verdes, morados, efectos metálicos)
- Generación de prompts profesionales para imágenes por IA
- Creación de titulares narrativos épicos para secciones principales
- Integración técnica de estructura HTML y unificación de clases CSS
- Curación del lore y coherencia narrativa entre páginas
- Refinamiento de contenido en páginas principales (index.html, elves_habilities.html)
- Resolución de problemas técnicos y control de calidad integral

**Páginas bajo su responsabilidad directa:**
- index.html (arquitectura de portales)
- elves_habilities.html (integración de contenido)

### Camilo Florez Moreno — [Describir rol]

**Responsabilidades:**
- [Detallar contribuciones específicas]

### Hector Hernan Ríos Rodriguez — [Describir rol]

**Responsabilidades:**
- [Detallar contribuciones específicas]

### Ximena Jaramillo Cardenas — [Describir rol]

**Responsabilidades:**
- [Detallar contribuciones específicas]

---

## Estado Actual

### ✅ Completado
- Index finalizado con portales narrativos funcionales
- Sección Historia (history.html) implementada
- Sección Razas y Linajes (races_and_class.html) implementada
- Sección Habilidades (elves_habilities.html) integrada
- Página Reinos Principales (kingdoms.html) funcional
- Estilos unificados en styles.css
- Footer reorganizado con gradiente arena-mostaza

### 🔄 En Progreso
- Páginas internas de ciudades (Menzoberranzan, Alfheim, Valinor)
- Contenido completo de ciudades y sus historias

### ⏳ Próximos Pasos
- Pulir contenido de páginas internas
- Optimizar responsividad en dispositivos móviles
- Refinamiento de efectos visuales en portales

---

## Guía de Instalación & Uso

### Requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexión a internet (para fuentes personalizadas, si aplica)

### Pasos
1. Clonar o descargar el repositorio:
   ```bash
   git clone https://github.com/ElvesLatte/Almers.git
   cd Almers
   ```

2. Abrir `index.html` en el navegador:
   ```bash
   # Opción 1: Abrir directamente
   open index.html

   # Opción 2: Usar un servidor local (recomendado)
   python -m http.server 8000
   # Luego acceder a http://localhost:8000
   ```

---

## Notas de Desarrollo

- **Ramas**: 
  - `main`: Rama principal con cambios integrados y probados
  - `Dev/miguel`: Rama de desarrollo con características en progreso

- **CSS**: Los estilos están centralizados en `styles.css` para mantener consistencia. Las páginas específicas pueden tener hojas adicionales (ej: `style_cfm.css` para races_and_class.html)

- **Imágenes**: Todas las imágenes están en carpeta `imagenes/` con nombres descriptivos. Las rutas en CSS y HTML deben ser relativas a la raíz del proyecto.

---

## Contacto & Créditos

**Equipo de Desarrollo:**
- Miguel David Calle Restrepo
- Camilo Florez Moreno
- Hector Hernan Ríos Rodriguez
- Ximena Jaramillo Cardenas

**Repositorio:** [GitHub - ElvesLatte/Almers](https://github.com/ElvesLatte/Almers)

---

*Último actualizado: Diciembre 2025*
>>>>>>> e46b863384bcb7d60136846c8a7c5c076496999b
