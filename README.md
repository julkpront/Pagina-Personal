# Página Personal — Julián Muñoz

Sitio web personal estático. Presenta el perfil profesional, los proyectos y los datos de contacto de Julián Muñoz, desarrollador especializado en automatización e IA local.

## Estructura

```
Pagina-Personal/
├── index.html        # Página de inicio
├── biografia.html    # Perfil y trayectoria
├── portfolio.html    # Proyectos: IAuditoring y Lilu
├── contacto.html     # Formulario y datos de contacto
├── css/
│   └── style.css     # Estilos del sitio
└── img/              # Capturas de pantalla de los proyectos
```

## Tecnologías

- HTML5 semántico
- CSS3 (sin frameworks, variables CSS, diseño responsive)
- Tipografía: IBM Plex Sans + IBM Plex Mono (Google Fonts)

## Proyectos que se muestran

**IAuditoring** — Sistema de auditoría automática de llamadas con IA, en producción diaria. Detecta intentos de evasión de plataforma usando transcripción y modelos de lenguaje ejecutados 100% en local (Python, faster-whisper, Ollama, FastAPI, SQLite).

**Lilu** — Asistente conversacional personal, completamente local y privado. Entiende voz e imágenes, mantiene memoria persistente y genera imágenes sin depender de servicios en la nube (Python, FastAPI, Ollama, Kokoro TTS).

## Uso

Es un sitio estático: basta con abrir `index.html` en el navegador o servirlo con cualquier servidor HTTP sencillo.

```bash
# Ejemplo con Python
python -m http.server 8000
```
