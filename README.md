# Panamá Smart Trails

Proyecto académico desarrollado para **Ingeniería en Sistemas II** e **Inteligencia Artificial** en la **Universidad Interamericana de Panamá**.

## Descripción

**Panamá Smart Trails** es una aplicación orientada a visitantes de parques y senderos. Su objetivo es facilitar la orientación, consulta de información y planificación de recorridos mediante mapas, rutas, puntos de interés, reportes de incidencias y consultas por texto o voz.

El prototipo integra navegación sobre senderos, información de fauna y servicios, reportes comunitarios y apoyo de Inteligencia Artificial para interpretar consultas del usuario.

## Funciones principales

- Visualización de parques, senderos y puntos de interés.
- Búsqueda de lugares, servicios y fauna.
- Cálculo de rutas sobre la red de senderos.
- Rutas con paradas intermedias.
- Navegación y simulación de recorridos.
- Reportes de incidencias en senderos.
- Confirmación y actualización de reportes comunitarios.
- Consultas por texto y voz.
- Uso de GPS para geolocalización.
- Modo de demostración para pruebas fuera del parque.

## Tecnologías

- React
- TypeScript
- Vite
- Capacitor
- FastAPI
- Supabase PostgreSQL
- MapLibre GL
- OpenStreetMap
- Google Gemini API
- GPS del dispositivo
- Git y Git LFS

## Estructura de la entrega

```text
ProyectoFinal_PANAMÁ_SMART_TRAILS_Alonso_Euris_Juan_Aaron_Carlos_Abel/
├── 01_Documentacion/
│   └── Documento_Tecnico_Panama_Smart_Trails.pdf
├── 02_Prototipo/
│   └── Senderos-Panama.apk
├── 03_Banner/
│   └── Banner / flyer presentado en la feria
├── 04_Video/
│   └── Video promocional
├── 05_Bitacora/
│   └── Bitácora del proceso
├── 06_Presentacion/
│   └── Presentaciones utilizadas durante el proyecto
└── 07_Equipo/
    └── Foto del equipo durante la exposición
```

## Inteligencia Artificial

La IA se utilizó en dos áreas:

1. **Dentro del prototipo:** Google Gemini se utiliza para interpretar consultas realizadas por texto o voz y extraer la intención y las entidades relevantes.
2. **Durante el desarrollo:** se utilizaron herramientas como ChatGPT y Codex como apoyo para análisis, documentación, revisión de código, pruebas y correcciones.

La IA no calcula directamente las rutas. Los destinos se validan contra los datos disponibles y el recorrido se calcula mediante lógica determinista sobre la red de senderos.

## Equipo

- Alonso
- Euris
- Juan
- Aaron
- Carlos
- Abel

## Entrega académica

Este repositorio contiene la versión utilizada para la entrega final del proyecto.

Algunos archivos binarios, especialmente el video promocional, se almacenan mediante **Git LFS** debido a su tamaño.

Para clonar correctamente el repositorio con los archivos administrados por LFS:

```bash
git lfs install
git clone https://github.com/3UR12/Ingenieria-de-sistemas-2.git
```

## Uso y derechos

Este proyecto fue desarrollado con fines académicos.

**Copyright © 2026 Equipo Panamá Smart Trails. Todos los derechos reservados.**

El contenido de este repositorio no se publica bajo una licencia de software de código abierto. La publicación del repositorio permite su consulta y evaluación académica, pero no concede autorización para copiar, redistribuir, modificar o reutilizar el proyecto con fines comerciales o como entrega académica propia sin autorización de sus autores.
