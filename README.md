# Club Rotario — Sitio web del Centenario (1926–2026)

Sitio web construido con **React + Vite**, animaciones con **Framer Motion** (estilo react-bits: revelados al hacer scroll, contadores animados, rueda dentada giratoria) y navegación con **React Router**.

## Páginas incluidas

- **Inicio** — hero en video, misión, campañas activas, historia, agenda de eventos, enlaces de interés y llamado a la acción.
- **Quiénes Somos** — línea de tiempo con los hitos del club (1926–2026) y Junta Directiva.
- **Centenario 2026** — cuenta regresiva al aniversario, lema oficial y agenda especial del año.
- **Qué Hacemos** — fichas de proyectos y causas.
- **Juventud** — Rotaract e Interact.
- **Noticias y Eventos** — noticias recientes y seminarios organizados por fecha.
- **Involúcrate** — proceso para ser socio + formulario de interés (nombre, teléfono, correo, motivo).
- **Contacto** — formulario de contacto, dirección, horarios, mapa y redes sociales.

El **pie de página**, presente en todas las páginas, incluye los enlaces a Instagram, Facebook, LinkedIn y Twitter.

## Cómo ejecutarlo

```bash
npm install
npm run dev       # entorno de desarrollo, http://localhost:5173
npm run build     # genera la versión de producción en /dist
npm run preview   # sirve la versión de producción localmente
```

## Personalización rápida

- **Colores y tipografías**: variables CSS en `src/index.css` (`--royal`, `--gold`, `--cream`, fuentes Fraunces/Inter).
- **Logo y video del hero**: `src/assets/rotary-logo.png` y `src/assets/hero-video.mp4` — reemplázalos por los archivos oficiales cuando los tengas en alta resolución.
- **Textos e información**: cada página tiene su contenido en un arreglo de datos al inicio del archivo (`src/pages/*.jsx`), fácil de editar sin tocar el diseño.
- **Formularios**: actualmente simulan el envío en el navegador. Para que lleguen correos reales, conecta el `onSubmit` de `Involucrate.jsx` y `Contacto.jsx` a un servicio como Formspree, EmailJS o un backend propio.
- **Redes sociales**: actualiza las URLs en `src/components/Footer.jsx` y `src/pages/Contacto.jsx`.

## Pendiente de definir con el club

- Paleta e identidad visual definitiva / brandbook oficial (se usó Azul Rotario + Dorado como base).
- Fotografías reales de socios, proyectos y eventos (se usaron marcadores de posición descriptivos).
- Dirección, horario y correos definitivos de la sede.
- Contenido real de noticias, seminarios y miembros de la Junta Directiva.
