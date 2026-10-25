# Proyecto web: Pensamiento computacional

Sitio académico para presentar el trabajo de grado **“Estrategia didáctica gamificada mediada por herramientas digitales para fortalecer las habilidades de secuenciación lógica del pensamiento computacional en estudiantes de grado cuarto del Instituto Caldas de Bucaramanga”**.

## Cambios de esta versión

- Se reforzó el contraste de la portada con una capa azul oscura para que el texto se lea claramente sobre la fotografía.
- Se retiró por completo la tarjeta de ruta de pensamiento, los pasos y la insignia de XP. La portada muestra ahora la fotografía Imagen1 como imagen visible, no solo como fondo.
- Se agregó un fondo azul sólido a la navegación superior para mantener legibles las letras.
- Las rutas de las imágenes y videos ahora comienzan con `./assets/...`, para que se resuelvan de forma consistente al publicar el repositorio.
- Las imágenes principales de la universidad se cargan de inmediato; las imágenes de docentes y estudiantes muestran una imagen de reserva si aún no se han agregado.
- El sitio mantiene un solo `index.html`, con secciones independientes controladas mediante JavaScript.

## Archivos y carpetas

```text
proyecto-pensamiento-computacional/
├── index.html
├── README.md
└── assets/
    ├── img/
    │   ├── Imagen1.jfif
    │   ├── Imagen2.png
    │   ├── Imagen3.png
    │   ├── Imagen4.jpg             (por agregar)
    │   ├── Docente1.jpg            (por agregar)
    │   ├── Docente2.jpg            (por agregar)
    │   ├── Estudiante1.jpg         (por agregar)
    │   ├── Estudiante2.jpg         (por agregar)
    │   ├── Estudiante3.jpg         (por agregar)
    │   ├── docente-placeholder.svg
    │   └── estudiante-placeholder.svg
    └── video/
        ├── Video1.mp4              (por agregar)
        └── Video2.mp4              (por agregar)
```

## Importante: nombres exactos

GitHub Pages distingue entre mayúsculas y minúsculas. Los nombres y extensiones deben coincidir exactamente con los que aparecen en el código.

- `Imagen1.jpg`: fotografía de portada visible en el bloque principal. Ya incluida.
- `Imagen2.png`: escudo de la Universidad de Cartagena. Ya incluido.
- `Imagen3.png`: fotografía del campus de la Universidad de Cartagena. Ya incluida.
- `Docente1.jpg`: fotografía de Katia Sánchez Palma.
- `Docente2.jpg`: fotografía de Nini Johana Villamizar Parada.
- `Estudiante1.jpg`: fotografía de Heidi Katherine Muñoz Rico.
- `Estudiante2.jpg`: fotografía de Anyie Alexandra Hernández Hernández.
- `Estudiante3.jpg`: fotografía de Luis David Villamizar Portilla.
- `Imagen4.jpg`: imagen o infografía grande que explica el proyecto.
- `Video1.mp4`: video de presentación TI.
- `Video2.mp4`: segundo video.

Si tus imágenes de docentes o estudiantes son PNG, JPG o JPEG con otro nombre, puedes renombrarlas para que coincidan con la tabla o cambiar la ruta en el `index.html`.

## Cómo probar en el computador

1. Descarga y descomprime el archivo ZIP.
2. Conserva `index.html`, `README.md` y la carpeta `assets` en la misma carpeta principal.
3. Abre `index.html` en Chrome, Edge o Firefox.
4. Prueba cada botón del menú: cada botón debe mostrar una sección distinta sin convertir el sitio en una página larga.
5. Agrega tus fotos y videos en las carpetas indicadas.

Tailwind CSS y las fuentes se cargan desde CDN; para ver el diseño completo necesitas conexión a internet.

## Cómo publicar en GitHub Pages

1. Crea un repositorio en GitHub, por ejemplo `proyecto-pensamiento-computacional`.
2. Sube a la raíz del repositorio el archivo `index.html`, el `README.md` y la carpeta `assets` completa. No subas únicamente el HTML.
3. Abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/ (root)`, y pulsa **Save**.
6. Espera a que termine la publicación y abre la URL que aparece en esa misma sección.
7. Si una imagen no aparece en el sitio publicado, revisa que el archivo exista dentro de `assets/img/` y que su nombre coincida exactamente, incluidas mayúsculas, minúsculas y extensión.

## Sobre las imágenes

- Las fotografías de docentes y estudiantes aún no están incluidas porque deben ser suministradas por el equipo. Mientras tanto, se muestran imágenes de reserva.
- `Imagen4.jpg` es un espacio reservado. Cuando agregues el archivo, la imagen aparecerá en la sección de identificación.
- Las imágenes de la universidad están configuradas con dimensiones y recortes definidos para conservar la composición del diseño.

## Actualizar el sitio

Edita el `index.html` o reemplaza los recursos dentro de `assets`, manteniendo los nombres y la estructura de carpetas. Después, sube los cambios al mismo repositorio de GitHub.

## Consideraciones

GitHub Pages sirve sitios estáticos: no incorpora base de datos ni permite que visitantes suban archivos directamente desde la página. Publica únicamente imágenes y videos para los que tengas permiso de uso, especialmente si aparecen menores de edad.
