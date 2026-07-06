# Nexo Coworking & Innovación

## Descripción del proyecto

Este proyecto corresponde al desarrollo de una landing page profesional para **Nexo Coworking & Innovación**, una empresa ficticia orientada a ofrecer espacios de coworking, oficinas privadas, salas de reuniones, membresías flexibles y actividades de innovación empresarial.

La página fue diseñada como una propuesta digital para presentar la marca, comunicar sus servicios principales, atraer posibles clientes y facilitar una solicitud visual de reserva o información.

## Datos de la actividad

**Estudiante:** Lady Arleth Vasquez Muñoz  
**Asignatura:** Fundamentos de Sistemas Web  
**Tema asignado:** Centro de coworking e innovación empresarial  
**Proyecto:** Landing page responsive  
**Institución:** Universidad de las Fuerzas Armadas ESPE - Sede Santo Domingo  

## Objetivo del proyecto

Diseñar y desarrollar una landing page semántica, responsive y visualmente coherente para una empresa ficticia de coworking, aplicando HTML5, CSS externo modular, Bootstrap 5, Bootstrap Icons y enfoque mobile first.

## Características principales

La landing page incluye:

- Encabezado con logotipo y menú de navegación.
- Sección hero con mensaje principal, descripción, botones de llamada a la acción e imagen destacada.
- Presentación de la empresa ficticia.
- Tarjetas de servicios con imágenes, iconos, títulos y descripciones.
- Carrusel de espacios destacados.
- Indicadores o datos relevantes del negocio.
- Planes o membresías.
- Testimonios ficticios de clientes.
- Formulario visual de reserva o solicitud de información.
- Pie de página con datos de contacto, horario, dirección ficticia e iconos de redes sociales.

## Tecnologías utilizadas

- HTML5
- CSS3
- Bootstrap 5
- Bootstrap Icons
- Google Fonts
- Git
- GitHub
- GitHub Pages

## Organización del proyecto

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
│   ├── vasquez-lady-landing.pdf
└── README.md
```

## Descripción de archivos principales

**index.html**  
Contiene la estructura semántica de la landing page. Incluye las secciones principales: encabezado, hero, empresa, servicios, espacios, indicadores, membresías, testimonios, formulario y footer.

**css/base.css**  
Contiene las variables CSS, estilos generales, tipografía, colores base, botones y reglas iniciales del diseño mobile first.

**css/componentes.css**  
Define los estilos visuales de las secciones y componentes principales, como tarjetas, hero, carrusel, testimonios, formulario y pie de página.

**css/responsive.css**  
Incluye las media queries utilizadas para adaptar el diseño a tabletas, computadoras y pantallas amplias.

**img/**  
Carpeta donde se almacenan las imágenes utilizadas en la landing page.

**docs/**  
Contiene el informe técnico del proyecto y las capturas utilizadas como evidencia.

## Uso de Bootstrap

Bootstrap 5 se utilizó para organizar el diseño responsive mediante contenedores, filas, columnas, tarjetas, botones, formularios, espaciados, alineación, imágenes fluidas y carrusel.

Algunas clases utilizadas fueron:

```html
container
row
col-12
col-md-6
col-lg-4
card
btn
img-fluid
form-control
form-select
text-center
d-flex
```

## Uso de variables CSS

El proyecto utiliza variables CSS para mantener una identidad visual ordenada y facilitar cambios globales en colores, sombras, bordes y tipografía.

Ejemplo:

```css
:root {
    --color-principal: #506779;
    --color-secundario: #C8E1EC;
    --color-menta: #C8F4D8;
    --color-lavanda: #DDD7ED;
    --color-fondo: #F8FBFC;
    --color-texto: #25333B;
}
```

Estas variables se aplican en botones, fondos, encabezados, tarjetas, iconos y textos.

## Enfoque mobile first

El diseño fue desarrollado primero para pantallas pequeñas. Luego se agregaron media queries para mejorar la distribución en tabletas y computadoras.

El proyecto fue probado en los siguientes tamaños:

- 375 px: vista móvil.
- 768 px: vista tableta.
- 1366 px: vista escritorio.

En las pruebas realizadas no se observó desplazamiento horizontal provocado por desbordamiento de elementos.

## Instrucciones para abrir el proyecto

1. Descargar o clonar el repositorio.
2. Abrir la carpeta del proyecto.
3. Abrir el archivo `index.html` en un navegador web.
4. Verificar que las imágenes se carguen correctamente desde la carpeta `img`.

## Repositorio en GitHub

Repositorio del proyecto:

```text
https://github.com/LadyVasquez22/U3_FWEB_T1_LandingPage 
```

## Fuentes de recursos

- **Bootstrap 5:** utilizado para la estructura responsive y componentes visuales.
- **Bootstrap Icons:** utilizado para los iconos de servicios, beneficios, contacto y redes sociales.
- **Google Fonts:** fuente Inter utilizada para mejorar la legibilidad.
- **Imágenes:** recursos visuales relacionados con coworking e innovación empresarial, almacenados localmente en la carpeta `img`.
- **Capturas:** evidencias generadas desde la visualización del proyecto en diferentes tamaños de pantalla.

## Observación sobre el formulario

El formulario incluido en la landing page es visual. No almacena ni envía información, debido a que el proyecto no utiliza JavaScript personalizado, backend ni base de datos.

## Estado del proyecto

Proyecto finalizado para entrega académica. Incluye landing page responsive, archivos CSS separados, imágenes organizadas, informe técnico y README documentado.