# 25-26_DesafioAPS_HTML-CSS_Template

# La Salle Solidaria

Sitio web estático que presenta las acciones solidarias y obras sociales de la red de colegios La Salle en España. El proyecto documenta las distintas iniciativas de transformación social impulsadas por la comunidad educativa lasaliana.

## Descripción

La Salle Solidaria nace del compromiso social histórico de San Juan Bautista de La Salle. El sitio recoge y visibiliza las acciones solidarias que realizan los centros La Salle en diversas comunidades autónomas, organizadas en cinco grandes áreas:

- **Operación Kilo** — Campaña de recogida de alimentos no perecederos para familias vulnerables.
- **Proyectos APS** (Aprendizaje-Servicio) — Proyectos educativos que combinan aprendizaje con servicio a la comunidad.
- **PROYDE** — ONG lasaliana de cooperación al desarrollo centrada en la educación.
- **Comercio Justo** — Programas de apoyo a comunidades productoras del Sur global.
- **Proyectos Propios** — Iniciativas particulares de cada centro (Proyecto Uniraid, Rayo McQueen, mercados solidarios, etc.).

## Estructura del proyecto

```
├── index.html                 # Página de inicio
├── acciones.html              # Índice de acciones solidarias
├── Operacion_kilo.html        # Detalle: Operación Kilo
├── proyecto_APS.html          # Detalle: Proyectos APS
├── PROYDE.html                # Detalle: PROYDE
├── comercio_justo.html        # Detalle: Comercio Justo
├── proyectos_propios.html     # Detalle: Proyectos Propios
├── Proyecto_Uniraid.html      # Subproyecto: Uniraid
├── Rayo_Macqueen.html         # Subproyecto: Rayo McQueen
├── css/
│   ├── reset.css              # Reset CSS base
│   ├── style.css              # Estilos principales y layout
│   ├── style2.css             # Estilos alternativos
│   └── style3.css             # Estilos para secciones con desplegables
└── imagenes/                  # Logos, banderas de CCAA e imágenes de proyectos
```

## Tecnologías

- HTML5 semántico
- CSS3 (variables CSS, Flexbox, media queries)
- Sin dependencias externas ni frameworks

## Cómo usar

El sitio está desplegado y accesible en:

👉 **https://la-salle-solidaria.vercel.app/**

Para desarrollo local, puedes servir los archivos con cualquier servidor estático:

```bash
# Con Python
python3 -m http.server 8000

# Con Node.js
npx serve .
```

## Navegación

1. **Inicio** (`index.html`) — Contexto histórico del compromiso social de La Salle.
2. **Acciones Solidarias** (`acciones.html`) — Índice con tarjetas que enlazan a cada proyecto.
3. **Páginas de detalle** — Cada acción tiene su propia página con descripción y un listado de centros participantes por comunidad autónoma, presentados en desplegables interactivos.

## Licencia

© 2026 Proyecto Acciones Solidarias - La Salle
