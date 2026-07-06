# Nexo Coworking & Innovación

## Nombre del estudiante
Lady Arleth Vasquez Muñoz

## Tema asignado
Centro de coworking e innovación empresarial.

## Descripción
Landing page profesional para una empresa ficticia llamada **Nexo Coworking & Innovación**. La página presenta espacios de trabajo, oficinas privadas, salas de reuniones, membresías, comunidad, eventos y un formulario visual para solicitar reservaciones.

## Tecnologías utilizadas
- HTML5 semántico
- CSS3 externo y modular
- Bootstrap 5
- Bootstrap Icons
- Google Fonts
- Git y GitHub Pages

## Estructura del proyecto
```text
vasquez-lady-landing/
├── index.html
├── css/
│   ├── base.css
│   ├── componentes.css
│   └── responsive.css
├── img/
│   ├── logo.png
│   ├── hero.jpg
│   ├── servicio-01.jpg
│   ├── servicio-02.jpg
│   ├── servicio-03.jpg
│   ├── carrusel-01.jpg
│   ├── carrusel-02.jpg
│   └── carrusel-03.jpg
├── docs/
│   └── vasquez-lady-landing.pdf
└── README.md
```

La carpeta `docs/` queda reservada para incorporar el informe técnico en una etapa posterior.

## Instrucciones para abrir la página
1. Descargar o clonar el repositorio.
2. Abrir la carpeta `vasquez-lady-landing`.
3. Abrir el archivo `index.html` en un navegador web.

## Enlace de GitHub Pages
La publicación se realiza desde la rama principal del repositorio mediante GitHub Pages. Una vez publicado, el enlace seguirá el formato:

`https://github.com/LadyVasquez22/U3_FWEB_T1_LandingPage`

## Captura principal
![Vista principal de Nexo Coworking e Innovación](img/hero.jpg)

## Uso de variables CSS
Una variable CSS es un valor reutilizable que se declara normalmente dentro de `:root` y se emplea mediante la función `var()`. Sirve para mantener consistencia visual y facilitar cambios globales sin repetir códigos de color, tipografías o medidas.

En este proyecto, `css/base.css` define variables como `--color-principal`, `--color-secundario`, `--color-menta`, `--color-lavanda`, `--color-fondo` y `--fuente-principal`. Los demás estilos consumen esas variables, por ejemplo: `background-color: var(--color-principal);`.

## Fuentes de imágenes e iconos
- Imágenes: recursos visuales generados con OpenAI para este proyecto y optimizados localmente en formato JPG.
- Iconos: Bootstrap Icons.
- Tipografía: Google Fonts, familia Inter.
- Framework: Bootstrap 5.
