# Digital CV – Albert Einstein

Este es un currículum vitae digital moderno, profesional y responsivo, diseñado específicamente para ser escaneado desde un código QR impreso en una tarjeta de presentación. Al escanear el código, la persona accede instantáneamente a un CV limpio, elegante y optimizado para móviles, que también se imprime perfectamente como PDF o papel.

## ✨ Características

- **Archivo único y autónomo** (separado en HTML, CSS y JS para fácil edición)
- **Diseño mobile-first** y completamente responsivo (grid + flexbox)
- **Botón flotante "Print / PDF"** que activa la impresión del navegador (genera PDF perfecto)
- **Estilos de impresión** (`@media print`) que eliminan elementos no esenciales y ajustan márgenes para A4
- **Navegación sticky** con enlaces de anclaje y desplazamiento suave
- **Paleta de colores profesional**: azul marino (#0A2540), gris suave (#64748B), fondo blanco
- **Tipografía limpia** (sistema sans-serif)
- **Secciones completas**: resumen, experiencia (línea de tiempo), educación, habilidades, idiomas, certificaciones, proyectos, premios, publicaciones, referencias, intereses
- **Microinteracciones** (hover effects) que no afectan la impresión
- **Código semántico y accesible** (etiquetas ARIA, atributos alt, jerarquía de encabezados)

## 📁 Estructura de archivos
 
├── index.html
├── styles.css
├── script.js
└── README.md

## 🚀 Cómo desplegar y generar el código QR

### 1. Personaliza el CV

- Abre `index.html` y reemplaza los datos de Albert Einstein con tu propia información (nombre, título, contacto, experiencia, etc.)
- Si deseas una foto real, reemplaza el `<div class="photo-circle">` por una etiqueta `<img src="tu-foto.jpg">` (recuerda alojar la imagen o usar base64)
- Ajusta colores en las variables CSS de `styles.css` si lo deseas

### 2. Prueba localmente

- Guarda todos los archivos en una misma carpeta
- Abre `index.html` en tu navegador (doble clic)
- Verifica que se vea bien en móvil (puedes usar las herramientas de desarrollador para simular)
- Haz clic en el botón "Print / PDF" y comprueba la vista previa de impresión

### 3. Sube a un hosting gratuito

#### Opción A: Netlify (más sencillo)
- Ve a [app.netlify.com/drop](https://app.netlify.com/drop)
- Arrastra la carpeta con los tres archivos (o un ZIP que los contenga)
- Netlify generará una URL como `nombre-sitio.netlify.app`

#### Opción B: Vercel
- Entra a [vercel.com](https://vercel.com)
- Crea una cuenta y haz clic en "New Project"
- Sube la carpeta o conecta tu repositorio de GitHub

#### Opción C: GitHub Pages
- Crea un repositorio en GitHub
- Sube los tres archivos a la rama principal
- Ve a Settings > Pages, selecciona la rama `main` y carpeta `/root`
- Obtendrás una URL como `usuario.github.io/repositorio`

### 4. Genera el código QR permanente

- Copia la URL de tu sitio (ej. `https://micv.netlify.app`)
- Usa un generador de QR gratuito como:
  - [QR Code Monkey](https://www.qr-code-generator.com/)
  - [QR.io](https://qr.io/)
  - [GoQR.me](https://goqr.me/)
- Pega la URL, descarga el código QR en PNG o SVG
- Imprime el código QR en tu tarjeta de presentación

### 5. Prueba final

- Escanea el código QR con tu teléfono (cámara nativa o app lectora)
- Verifica que la página cargue rápido y se vea correctamente
- Prueba el botón de impresión para obtener el PDF

## 📄 Notas adicionales

- El CV está pensado para que tanto la versión digital como la impresa sean impecables.
- Los enlaces (email, teléfono, LinkedIn, web) son funcionales en el móvil (pueden abrir la app correspondiente).
- Si deseas cambiar el ícono del perfil, puedes usar una imagen real manteniendo la clase `.photo-circle` y ajustando el tamaño.

---

**Digital CV • Scanned from business card QR**