# Invitación de Boda - Georgia & José Miguel

Invitación digital de matrimonio con diseño elegante y animaciones.

## 🌐 Ver en línea

Una vez publicado en GitHub Pages, la invitación estará disponible en:
```
https://[tu-usuario].github.io/[nombre-repo]/
```

## 📁 Archivos del proyecto

```
├── index.html          # Invitación principal
├── editor.html         # Editor visual (opcional)
├── bodafoto.jpeg       # Foto principal (Save the Date)
├── bodafoto2.jpeg      # Galería
├── bodafoto3.jpeg      # Galería
├── bodafoto4.jpeg      # Galería
├── bodafoto5.jpeg      # Galería
├── bodafoto6.jpeg      # Galería
├── bodafoto7.jpeg      # Galería
└── die-with-a-smile.mp3  # Música de fondo (agregar)
```

## 🎵 Música

Para agregar la música "Die With A Smile" de Bruno Mars & Lady Gaga:

1. Descarga el archivo MP3 de la canción
2. Renómbralo a `die-with-a-smile.mp3`
3. Colócalo en la misma carpeta que `index.html`

**Nota:** Por derechos de autor, el archivo MP3 no está incluido en el repositorio.

## 🚀 Publicar en GitHub Pages

### Paso 1: Crear repositorio en GitHub
1. Ve a [github.com](https://github.com) e inicia sesión
2. Haz clic en **"New repository"** (nuevo repositorio)
3. Nombre: `boda-georgia-josemiguel` (o el que prefieras)
4. Selecciona **Public**
5. Haz clic en **"Create repository"**

### Paso 2: Subir archivos
Opción A - Desde la web:
1. En tu nuevo repositorio, haz clic en **"uploading an existing file"**
2. Arrastra todos los archivos de esta carpeta
3. Haz clic en **"Commit changes"**

Opción B - Desde terminal:
```bash
cd "c:\Users\HP\Desktop\invitacion de matrimonio"
git init
git add .
git commit -m "Invitación de boda"
git branch -M main
git remote add origin https://github.com/[tu-usuario]/[nombre-repo].git
git push -u origin main
```

### Paso 3: Activar GitHub Pages
1. Ve a **Settings** (configuración) del repositorio
2. En el menú lateral, haz clic en **Pages**
3. En "Source", selecciona **Deploy from a branch**
4. En "Branch", selecciona **main** y carpeta **/ (root)**
5. Haz clic en **Save**

### Paso 4: Esperar y acceder
- GitHub tarda 1-2 minutos en publicar
- Tu invitación estará en: `https://[tu-usuario].github.io/[nombre-repo]/`

## ✏️ Personalizar

Abre `index.html` y busca el bloque `const CONFIG = {` para editar:
- Nombres de los novios
- Fecha y hora
- Lugares de ceremonia y recepción
- Fotos
- Música
- Código de vestimenta
- Y más...

## 💒 Características

- Diseño elegante y responsive (móvil y escritorio)
- 9 temas visuales diferentes
- Cuenta regresiva animada
- Galería de fotos con lightbox
- Confirmación de asistencia por WhatsApp
- Música de fondo
- Animaciones suaves
- Compatible con GitHub Pages (100% estático)

---

Con amor, para Georgia & José Miguel 💕
