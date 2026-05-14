# Portafolio Web – Andres Felipe Mora

Sitio web de portafolio personal desarrollado íntegramente con HTML5 y CSS3, sin frameworks ni dependencias externas. Presenta mis proyectos, certificaciones y habilidades técnicas.

**Demo en vivo:** https://morafelipe.github.io/portafolio-web/

---

## Stack técnico

| Tecnología | Uso |
|------------|-----|
| HTML5 semántico | Estructura del sitio |
| CSS3 puro | Estilos, layout y animaciones |
| `@media (prefers-color-scheme)` | Modo oscuro automático |
| `@keyframes fadeInUp` | Animaciones de entrada |
| Video HTML5 (`<video>`) | Fondo animado en loop |
| CSS Grid / Flexbox | Layout responsive |

Sin npm, sin bundlers, sin frameworks — el sitio abre directamente desde el navegador.

---

## Secciones

- **Header** – Nombre y rol profesional con animación de entrada
- **Sobre mí** – Descripción personal y motivaciones
- **Herramientas** – Stack técnico actual (HTML, CSS, JS, Java, Python, MySQL, Git, Next.js)
- **Certificaciones** – Cursos completados en Platzi y MongoDB University con capturas
- **Proyectos** – AppFitt, Servidor Nginx virtualizado y Apple-Hub con imágenes y descripción
- **Footer** – Contacto directo por email

---

## Correrlo localmente

No necesita instalación. Solo clona el repo y abre el archivo en el navegador:

```bash
git clone https://github.com/morafelipe/portafolio-web.git
cd portafolio-web
# Abre index.html en tu navegador
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

> **Nota sobre el video de fondo:** el archivo `./videos/fondo.mp4` debe estar presente. Si no se reproduce, el sitio funciona igualmente — el `<video>` tiene texto de fallback.

---

## Características técnicas destacadas

- **Modo oscuro automático** — detecta la preferencia del sistema operativo con `prefers-color-scheme: dark`, sin necesidad de botón manual.
- **Video de fondo a pantalla completa** — fijado con `position: fixed`, `object-fit: cover` y reducción de brillo al 40% para mantener legibilidad.
- **Animaciones `fadeInUp`** — aplicadas al header y secciones para una entrada suave sin JavaScript.
- **Responsive** — breakpoint principal en 768px ajusta tamaños de fuente y padding.

---

## Autor

**Andres Felipe Mora**  
Estudiante de Tecnología en Desarrollo de Software  
[andresfelipemoramancipe@gmail.com](mailto:andresfelipemoramancipe@gmail.com)  
[GitHub @morafelipe](https://github.com/morafelipe)
