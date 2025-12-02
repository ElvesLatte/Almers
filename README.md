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