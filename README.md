# Grecia Eterna · atlas-chronous

Atlas 3D del origen de la filosofía griega: un hilo cronológico de descubrimiento, creatividad y asombro, de Troya a Plotino, con capas de lectura de Luciano De Crescenzo y de Plotino y, desde la v0.6, **El Umbral**: la Caverna, el mito de Er y la Atlántida de Platón en Three.js.

**Sitio:** https://atlas-chronous.web.app

## Estructura

```
public/
  index.html                 la web completa (HTML + CSS + JS en un archivo)
  assets/img/                imágenes de concepto de El Umbral
  fonts/                     tipografías autoalojadas (Commissioner, Courier Prime, GFS Didot · OFL)
  vendor/three/r128/         Three.js r128 y los pases de postprocesado (bloom)
firebase.json                configuración de Hosting y cabeceras
.github/workflows/           despliegue automático
CHANGELOG.md                 historial de versiones
```

## Flujo de trabajo

| Acción | Resultado |
|---|---|
| `push` a `main` | se publica en el sitio principal |
| abrir un *pull request* | Firebase crea un enlace de vista previa (7 días) y lo deja como comentario en el PR |

Para pedir feedback sobre una versión nueva sin tocar la publicada: rama nueva → PR → compartir el enlace de vista previa.

## Privacidad (RGPD)

- Sin cookies, sin analítica, sin formularios.
- Tipografías y librerías servidas desde el propio dominio: el navegador no contacta con Google Fonts ni con CDN de terceros.
- Firebase Hosting (Google) registra datos técnicos de acceso como cualquier servidor web.
- Durante la fase de revisión la web lleva `noindex`: no aparece en buscadores.

## Transparencia (Reglamento UE de IA, art. 50)

Textos, traducciones orientativas y código elaborados con asistencia de IA (Claude, Anthropic) a partir del corpus del proyecto, con dirección, selección y revisión humanas.

## Derechos

Contenido y código: © Dear / ArtsLab Berlin. Todos los derechos reservados salvo que se indique otra licencia.
Three.js: MIT (ver `public/vendor/three/r128/LICENSE`). Tipografías: SIL Open Font License.
Los libros y PDFs de investigación del proyecto no forman parte del repositorio.
