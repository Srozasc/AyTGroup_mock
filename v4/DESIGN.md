# Design System - WoodPro

## 1. Visual Theme & Atmosphere

El diseño de WoodPro transmite una sensación de calidez, profesionalismo y conexión con la naturaleza. Es un sitio web orientado a la construcción residencial en madera, donde el material noble (la madera) es el protagonista absoluto. La атмосфера combina la calidez orgánica de la madera con la confianza y seriedad de una empresa de construcción establecida.

El color predominante es el blanco y tonos neutros claros que permiten que las imágenes de las casas y proyectos cobren relevancia central. Los acentos de color derivan de la madera misma (tonos café, beige,terracota) junto con un verde propio de la naturaleza y sostenibilidad. La sensación general es acogedora pero profesional, transmitiendo seguridad en la construcción y calidad premium.

**Key Characteristics:**
- Fondo mayoritariamente blanco (`#ffffff`) y tonos crema claros (`#faf9f7`) para destacar imágenes de proyectos
- Tonos tierra y madera como acentos: café cálido, beige Arena, terracota
- Verde naturaleza como color de acento secundario
- Imágenes de alta calidad como protagonistas visuales principales
- Diseño limpio y moderno con secciones bien definidas
- Sensación de calidez, sostenibilidad y construcción de calidad

## 2. Color Palette & Roles

### Background Surfaces
- **White** (`#ffffff`): Fondo principal, secciones de contenido
- **Cream Light** (`#faf9f7`): Fondos alternativos, áreas sutiles
- **Cream Warm** (`#f5f3ef`): Fondo de secciones destacadas
- **Light Beige** (`#ebe8e3`): Áreas de soporte, footers secundarios

### Text & Content
- **Text Primary** (`#1a1a1a`): Títulos principales, texto destacado
- **Text Secondary** (`#3d3d3d`): Párrafos, descripciones
- **Text Muted** (`#6b6b6b`): Textos secundarios, metadata
- **Text Light** (`#9a9a9a`): Placeholders, información menor

### Brand & Accent
- **Madera Principal** (`#8b5a2b`): Tono café madera rico, acentos principales
- **Madera Claro** (`#c4a77d`): Tono madera más claro, detalles
- **Madera Oscuro** (`#5d3a1a`): Tonos oscuros para énfasis
- **Verde Natura** (`#4a7c59`): Verde naturaleza, sostenibilidad
- **Verde Claro** (`#7fb08a`): Verde más claro para hover
- **Terracotta** (`#c4784a`): Tono cálido terracota
- **Arena** (`#d4b896`): Beige arena, transiciones

### Brand Colors
- **Brand Primary** (`#8b5a2b`): Café madera principal
- **Accent Secondary** (`#4a7c59`): Verde naturaleza
- **Accent Warm** (`#c4784a`): Terracota cálida

### Border & Divider
- **Border Light** (`#e5e5e5`): Líneas divisorias sutiles
- **Border Medium** (`#cccccc`): Bordes más visibles
- **Border Dark** (`#a0a0a0`): Bordes de énfasis
- **Shadow Subtle** (`rgba(0,0,0,0.08)`): Sombras ligeras
- **Shadow Medium** (`rgba(0,0,0,0.12)`): Sombras de elevation

## 3. Typography Rules

### Font Family
- **Primary**: `Montserrat`, con fallbacks: `Helvetica Neue, Arial, sans-serif`
- **Secondary**: `Open Sans`, para textos de lectura
- **Accent**: `Playfair Display`, para títulos decorativos cuando se requiera

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|------|------|------|--------|-------------|----------------|-------|
| Display XL | Montserrat | 56px (3.5rem) | 700 | 1.15 | -1px | Títulos de hero principales |
| Display Large | Montserrat | 44px (2.75rem) | 700 | 1.20 | -0.5px | Títulos de sección principales |
| Display | Montserrat | 36px (2.25rem) | 600 | 1.25 | -0.3px | Subtítulos destacados |
| Heading 1 | Montserrat | 32px (2rem) | 600 | 1.30 | normal | Títulos de página |
| Heading 2 | Montserrat | 28px (1.75rem) | 600 | 1.35 | normal | Títulos de sección |
| Heading 3 | Montserrat | 22px (1.375rem) | 600 | 1.40 | normal | Sub-secciones |
| Heading 4 | Montserrat | 18px (1.125rem) | 600 | 1.45 | normal | Títulos de tarjetas |
| Body Large | Open Sans | 18px (1.125rem) | 400 | 1.70 | 0.2px | Introducciones, descripciones |
| Body | Open Sans | 16px (1rem) | 400 | 1.65 | 0.2px | Texto de lectura |
| Body Small | Open Sans | 14px (0.875rem) | 400 | 1.60 | normal | Texto secundario |
| Caption | Open Sans | 13px (0.8125rem) | 400 | 1.50 | normal | Metadatos, etiquetas |
| Button | Montserrat | 14px (0.875rem) | 600 | 1.00 | 1px | Texto de botones |

### Principles
- **Montserrat para jerarquía**: Usar Montserrat para todos los títulos y elementos de navegación, transmitiendo modernidad y profesionalismo
- **Open Sans para lectura**: Usar Open Sans para párrafos y textos largos, optimizando legibilidad
- **Peso 600 para títulos**: Los títulos principales usan peso semibold (600) para impacto sin ser agresivos
- **Peso 700 para display**: Los títulos más grandes usan peso bold (700) para máximo énfasis
- **Letter-spacing negativo en display**: Títulos grandes usan espaciado ligeramente negativo para紧凑感
- **Spacing generoso en lectura**: body text usa line-height 1.65-1.70 para comodidad de lectura

## 4. Component Stylings

### Buttons

**Primary Button (CTA)**
- Background: `#8b5a2b` (madera principal)
- Text: `#ffffff`
- Padding: 14px 28px
- Radius: 4px
- Hover: oscurecer a `#5d3a1a`
- Use: CTAs principales, "Ver proyectos", "Contáctanos"

**Secondary Button**
- Background: `transparent`
- Text: `#8b5a2b`
- Padding: 14px 28px
- Radius: 4px
- Border: `2px solid #8b5a2b`
- Hover: background `rgba(139,90,43,0.1)`
- Use: CTAs secundarios, "Leer más"

**Ghost Button**
- Background: `rgba(139,90,43,0.05)`
- Text: `#8b5a2b`
- Padding: 12px 24px
- Radius: 4px
- Hover: background `rgba(139,90,43,0.1)`
- Use: navegación interna, links adicionales

**Green Accent Button**
- Background: `#4a7c59` (verde naturaleza)
- Text: `#ffffff`
- Padding: 14px 28px
- Radius: 4px
- Hover: oscurecer a `#3a6347`
- Use: CTAs de sostenibilidad, características eco

### Cards & Containers
- Background: `#ffffff`
- Border: `1px solid #e5e5e5`
- Radius: 8px (standard), 12px (featured)
- Shadow: `0 2px 8px rgba(0,0,0,0.08)`
- Hover: shadow aumenta a `0 4px 16px rgba(0,0,0,0.12)`
- Padding: 24px
- Use: tarjetas de servicios, modelos de casas

### Image Treatment
- Imágenes de proyectos con borde sutil o sin borde
- Border-radius: 8px para fotos de casas
- Imágenes de galería: layout masonry o grid
- Imágenes de equipo: circulares o rounded square
- treatment: shadows sutiles para profundidad

### Navigation
- Header blanco con shadow sutil
- Logo a la izquierda
- Links de navegación: Montserrat 14px weight 500
- Links hover: color cambia a `#8b5a2b`
- Mobile: hamburger menu con drawer

### Forms
- Input background: `#ffffff`
- Input border: `1px solid #cccccc`
- Input focus: border `#8b5a2b`
- Input radius: 4px
- Label: Montserrat 14px weight 500

### Badges & Pills
- Background: `#f5f3ef`
- Text: `#6b6b6b`
- Radius: 9999px (pill)
- Padding: 6px 16px
- Font: Montserrat 12px weight 500

## 5. Layout Principles

### Spacing System
- Base unit: 8px
- Scale: 8px, 16px, 24px, 32px, 40px, 48px, 64px, 80px, 96px
- Primary rhythm: 8px, 16px, 24px, 32px, 48px
- Section padding: 64px vertical (desktop), 40px (mobile)
- Container max-width: 1200px

### Grid & Container
- Max content width: 1200px
- Hero: full-width con imagen de fondo o imagen grande
- Feature sections: 2-3 columnas para servicios
- Gallery: grid responsive (2-4 columnas)
- Single column para contenido narrativo

### Whitespace Philosophy
- **Espacios generosos**: Las secciones tienen padding generoso para permitir que el contenido respire
- **Imágenes protagonistas**: Las fotos de proyectos ocupan posiciones destacadas
- **Separación natural**: Las secciones usan whitespace (no líneas divisorias)
- **Equilibrio visual**: Texto e imágenes se distribuyen balanceadamente

### Border Radius Scale
- Micro (2px): Buttons pequeños, inputs
- Standard (4px): Buttons, inputs, tarjetas pequeñas
- Comfortable (8px): Tarjetas, imágenes de proyectos
- Large (12px): Secciones destacadas, modals
- Full (50%): Avatars circulares
- Pill (9999px): Badges, pills

## 6. Depth & Elevation

| Level | Treatment | Use |
|-------|-----------|-----|
| Flat (Level 0) | No shadow, white bg | Page background |
| Subtle (Level 1) | `0 1px 3px rgba(0,0,0,0.08)` | Header, navegación |
| Card (Level 2) | `0 2px 8px rgba(0,0,0,0.08)` | Tarjetas, contenido |
| Elevated (Level 3) | `0 4px 16px rgba(0,0,0,0.12)` | Hover states, elementos flotantes |
| Focus (Level 4) | `0 6px 20px rgba(0,0,0,0.15)` | Modals, elementos destacados |

## 7. Do's and Don'ts

### Do
- Usar Montserrat para títulos y Open Sans para texto de lectura
- Mantener paleta de colores basada en tonos madera y naturaleza
- Usar imágenes de alta calidad de proyectos como protagonistas
- Mantener diseño limpio con mucho whitespace
- Usar botones con color madera (`#8b5a2b`) para CTAs principales
- Incluir verde naturaleza (`#4a7c59`) para mensajes de sostenibilidad
- Aplicar sombras sutiles para profundidad
- Usar border-radius consistente (4px para botones, 8px para tarjetas)

### Don't
- No usar fondos oscuros que Compitan con imágenes de proyectos
- No usar más de 2-3 acentos de color principales
- No saturar el diseño con demasiados elementos
- No usar tipografía decorativa excesiva
- No aplicar sombras intensas que distraigan
- No usar más de 3-4 niveles de tamaño de texto
- No mezclar demasiadas fuentes (máximo 2-3)

## 8. Responsive Behavior

### Breakpoints
| Name | Width | Key Changes |
|------|-------|-------------|
| Mobile Small | <480px | Single column, texto reducido |
| Mobile | 480–640px | Single column, ajustes de padding |
| Tablet | 640–768px | Dos columnas begins |
| Tablet Large | 768–1024px | Grid completo, navegación desktop |
| Desktop | 1024–1200px | Layout completo |
| Large Desktop | >1200px | Máxima anchura de contenido |

### Collapsing Strategy
- Hero: texto 56px → 40px → 32px
- Grid de servicios: 3 columnas → 2 columnas → 1 columna
- Galería de proyectos: 4 → 3 → 2 → 1 columnas
- Navigation: horizontal → hamburger menu
- Imágenes: mantienen aspect ratio
- Section padding: 64px → 40px → 24px

### Touch Targets
- Buttons: mínimo 44px de altura
- Links de navegación: área de click generosa
- Imágenes clickeables: clear indication de interactivity
- Form inputs: tamaño cómodo para mobile

## 9. Agent Prompt Guide

### Quick Color Reference
- Primary CTA: Madera (`#8b5a2b`)
- Secondary CTA: Verde Natura (`#4a7c59`)
- Page Background: White (`#ffffff`)
- Light Background: Cream (`#faf9f7`)
- Heading text: Dark (`#1a1a1a`)
- Body text: Gray (`#3d3d3d`)
- Muted text: (`#6b6b6b`)
- Border: Light (`#e5e5e5`)
- Shadow: Subtle (`rgba(0,0,0,0.08)`)

### Example Component Prompts
- "Create a hero section with white background. Headline at 56px Montserrat weight 700, line-height 1.15, letter-spacing -1px, color `#1a1a1a`. Subtitle at 18px Open Sans weight 400, line-height 1.70, color `#3d3d3d`. Primary button (`#8b5a2b`, white text, 4px radius) and secondary button (transparent, `#8b5a2b` border, 4px radius). Background image of wooden house project."
- "Design a services card: white background, `1px solid #e5e5e5` border, 8px radius, `0 2px 8px rgba(0,0,0,0.08)` shadow. Title at 22px Montserrat weight 600, color `#1a1a1a`. Body at 16px Open Sans, color `#3d3d3d`."
- "Build a navigation bar: white background, `0 1px 3px rgba(0,0,0,0.08)` shadow. Logo left, Montserrat 24px weight 700, color `#1a1a1a`. Links: Montserrat 14px weight 500, color `#3d3d3d`, hover color `#8b5a2b`."
- "Create a gallery grid: 4 columns desktop, 3 tablet, 2 mobile. Images with 8px radius. Hover: shadow increases to `0 4px 16px rgba(0,0,0,0.12)`."
- "Design a footer: `#faf9f7` background. 4-column layout with company info, links, contact, social. Montserrat 16px weight 600 for headings, Open Sans 14px for content."

### Iteration Guide
1. Usar Montserrat para títulos y navegación
2. Usar Open Sans para texto de lectura
3. Dos colores principales: madera (`#8b5a2b`) y verde (`#4a7c59`)
4. Fondo blanco como base, cream para variación sutil
5. Sombras sutiles (no oscuras) para profundidad
6. Imágenes de proyectos como protagonistas
7. Espaciado generoso para diseño limpio