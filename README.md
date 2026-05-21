# 🎂 Feliz Cumpleaños Daniel

Página de cumpleaños con animaciones, galería de fotos y música de fondo.

---

## 📁 Estructura de archivos

```
cumpleanos-daniel/
├── index.html                  ← Página principal
├── README.md                   ← Este archivo
└── assets/
    ├── fotos/
    │   ├── fotos.js            ← Lista de fotos (editar aquí)
    │   ├── foto1.jpg           ← Tus fotos van aquí
    │   └── foto2.jpg
    └── musica/
        └── cancion.mp3         ← Tu canción va aquí
```

---

## 🎵 Cómo agregar la música

1. Copia tu archivo de música dentro de `assets/musica/`
2. **Renómbralo** a `cancion.mp3` (o edita la línea en `index.html`)
3. Formatos soportados: `.mp3` `.ogg` `.wav` `.m4a`

> Si tu archivo tiene otro nombre, abre `index.html` y busca:
> ```html
> <source src="assets/musica/cancion.mp3" ...>
> ```
> Cambia `cancion.mp3` por el nombre real de tu archivo.

---

## 📸 Cómo agregar las fotos

1. Copia tus imágenes dentro de `assets/fotos/`
2. Abre el archivo `assets/fotos/fotos.js`
3. Agrega el nombre de cada foto en la lista:

```js
const FOTOS_LIST = [
  "foto1.jpg",
  "daniel_y_yo.png",
  "recuerdo.webp"
];
```

---

## 🚀 Subir a GitHub Pages (obtener enlace gratis)

1. Crea una cuenta en [github.com](https://github.com) si no tienes
2. Crea un repositorio nuevo (ej: `cumpleanos-daniel`)
3. Sube todos los archivos manteniendo la misma estructura de carpetas
4. Ve a **Settings → Pages**
5. En **Branch** selecciona `main` y carpeta `/ (root)`
6. Haz clic en **Save**
7. En unos minutos tendrás tu enlace:
   ```
   https://TU-USUARIO.github.io/cumpleanos-daniel/
   ```

¡Comparte ese enlace con Daniel! 🎉
