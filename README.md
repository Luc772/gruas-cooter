# Grúas Cooter — Landing Page

Sitio web de una sola página para **Grúas Cooter**, servicio de grúa hidráulica 24/7 en Concepción y alrededores.

## 🌐 Ver el sitio en vivo

Una vez publicado con GitHub Pages, el sitio quedará disponible en:

```
https://TU-USUARIO.github.io/gruas-cooter/
```

(Reemplaza `TU-USUARIO` por tu nombre de usuario de GitHub una vez subido).

## 📁 Estructura del proyecto

```
gruas-cooter/
├── index.html          # Página principal (todo el sitio en un solo archivo)
├── README.md            # Este archivo
└── images/               # Fotos de trabajos realizados
    ├── trabajo-01.jpg
    ├── trabajo-02.jpg
    ├── trabajo-03.jpg
    ├── trabajo-04.jpg
    ├── trabajo-05.jpg
    └── trabajo-06.jpg
```

⚠️ **Importante:** no muevas ni renombres las imágenes sin actualizar también las referencias dentro de `index.html` (etiquetas `<img src="images/...">`).

## 🚀 Cómo publicar en GitHub Pages

1. Sube todo el contenido de esta carpeta al repositorio (manteniendo la carpeta `images/`).
2. Ve a **Settings → Pages** en el repositorio.
3. En "Branch", selecciona `main` y carpeta `/root` (o `/(root)`).
4. Guarda. En 1-2 minutos el sitio estará disponible en la URL de arriba.

## ✏️ Cómo actualizar contenido

- **Teléfono/WhatsApp:** busca `56978622109` en `index.html` y reemplázalo en todas las apariciones (aparece en botones y links `wa.me`).
- **Agregar más fotos de trabajos:** sube la imagen a `images/`, y copia un bloque `<div class="gallery-item">...</div>` dentro de la sección `id="trabajos"`, cambiando el `src` y el texto de la etiqueta.
- **Textos generales:** todo el contenido está directamente en `index.html`, en español, fácil de ubicar con Ctrl+F.

## 🎨 Identidad visual

- **Colores:** negro (`#0a0a0a`) y rojo (`#e01023`), acorde a la pintura real de la grúa.
- **Tipografías:** Anton (títulos), Inter (texto), JetBrains Mono (detalles técnicos/teléfono).
- Sin frameworks ni dependencias de build — es HTML + CSS puro, funciona con solo abrir el archivo o subirlo a cualquier hosting estático.

## 📞 Contacto del negocio

- **WhatsApp:** +56 9 7862 2109
- **Cobertura:** Concepción y alrededores
- **Disponibilidad:** 24/7
