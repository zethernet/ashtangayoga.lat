# Biblioteca de Mantras y Yoga

Página estática en español para buscar y compartir mantras, himnos y sūtras usando un archivo JSON.

## Estructura
- `index.html`: interfaz y lógica de búsqueda.
- `data/library.json`: catálogo en JSON (puede ampliarse con más entradas).

## Cómo subirlo a tu perfil de GitHub
1. Crea un repositorio público nuevo en GitHub y súbelo con estos archivos.
2. Activa **GitHub Pages** en la pestaña *Settings → Pages* seleccionando la rama principal y la carpeta raíz (`/`).
3. Espera a que GitHub genere el sitio. La URL tendrá el formato `https://<tu-usuario>.github.io/<nombre-del-repo>/`.
4. Cada vez que actualices `data/library.json`, solo haz un commit y push para que se publique automáticamente.

## Añadir contenido
1. Abre `data/library.json`.
2. Agrega un objeto con campos como `id`, `tipo`, `titulo`, `texto`, `idioma`, `devanagari`, `significado`, `etiquetas` y `fuente`.
3. Guarda y publica; la página leerá el nuevo contenido sin más cambios.

## Uso
- Escribe el nombre o una etiqueta (ej. "sabiduria" o "Gayatri") en el buscador.
- Haz clic en "Copiar" para llevarte el texto completo o en "Compartir" para obtener un enlace y usar el sistema de compartir del navegador.
