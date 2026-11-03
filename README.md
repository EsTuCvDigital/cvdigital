# CVDigital

Sitio de conversion + catalogo de plantillas de **hoja de vida digital**.
Objetivo unico de la landing: llevar visitantes a **WhatsApp**.

## Estructura

```
index.html                     Landing (conversion)
templates/
  primer-empleo.html           Estudiantes / practicantes / recien graduados
  moderna.html                 Jovenes, creativos, marketing
  corporativa.html             Administracion, finanzas, derecho
  minimalista.html             Uso general
  tech.html                    Programadores, DevOps, IT
juan-esteban-rojas/            Hoja de vida publicada (landing moderna)
  index.html                   Pagina web responsive
  cv-print.html                Fuente A4 para generar el PDF
  CV-Juan-Esteban-Rojas.pdf    PDF de una pagina con QR
assets/
  profile.png                  Imagen de perfil de la marca (1080x1080)
  profile-512.png              Version ligera para favicon / icono
```

## Stack

HTML5 + CSS3 + JavaScript vanilla. Sin frameworks, sin build, sin backend.

## Publicacion

- Hojas de vida: entrega manual por WhatsApp (link + codigo QR).
- Hosting: **GitHub Pages** (rama `main`, raiz `/`).
- Sitio: `https://estucvdigital.github.io/cvdigital/`

## Hojas de vida publicadas

| Persona | Página | PDF |
|---|---|---|
| Juan Esteban Rojas Arbeláez | https://estucvdigital.github.io/cvdigital/juan-esteban-rojas/ | `juan-esteban-rojas/CV-Juan-Esteban-Rojas.pdf` |
| Jacob Marin Cataño | https://estucvdigital.github.io/cvdigital/jacob-marin/ | `jacob-marin/CV-Jacob-Marin.pdf` |

El PDF se regenera desde el `cv-print.html` de cada carpeta (A4, una página, QR a la versión web).

## Regla de entrega de cada hoja de vida

Toda hoja de vida digital debe entregarse con:

- `index.html` responsive (página web).
- `cv-print.html` (fuente A4).
- `CV-<Nombre-Apellido>.pdf` (una página A4, mismo contenido, QR a la web).
- `assets/pdf-preview.png` y `.webp` + QR.
- Foto de perfil opcional: `assets/retrato.jpg` (solo si el usuario la entrega).
- La página debe enlazar el PDF en la sección "Hoja de vida en PDF" y en el pie.

## Contacto

- WhatsApp: https://wa.me/573114008507
- Instagram: https://instagram.com/cv_digital0

## Notas

- Precios reales en la landing: Basico $40.000 COP · Personalizado $60.000 COP · Plan Anual $90.000 COP.
- Sin testimonios ficticios. La prueba social se agrega cuando existan casos reales.
