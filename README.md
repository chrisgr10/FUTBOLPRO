# FaceID App 🤖
Aplicación web de reconocimiento facial en tiempo real, desarrollada como proyecto final de la materia de Implementación de Aplicaciones Móviles Multiplataforma.

🔗 **App en vivo:** https://bucolic-hummingbird-b6f978.netlify.app

---

## Descripción
FaceID App permite registrar personas mediante fotografías y reconocerlas automáticamente a través de la cámara del dispositivo, usando inteligencia artificial con la librería face-api.js.

---

## Funciones principales
1. **Agregar personas** — Registra personas con nombre y una o varias fotos
2. **Reconocimiento facial en tiempo real** — Detecta y reconoce rostros usando la cámara
3. **Eliminar personas** — Borra personas registradas del sistema
4. **Cambiar cámara** — Alterna entre cámara frontal y trasera
5. **Historial de detecciones** — Guarda un registro con nombre, fecha, hora y confianza de cada detección
6. **Exportar reporte** — Descarga el historial completo en formato .txt
7. **Estadísticas** — Muestra gráficas de detecciones por persona y actividad por hora del día

---

## Tecnologías usadas
- HTML5, CSS3, JavaScript
- [face-api.js](https://github.com/justadudewhohacks/face-api.js) — reconocimiento facial con IA
- LocalStorage — almacenamiento de datos en el navegador
- PWA (Progressive Web App) — instalable en dispositivos móviles
- Netlify — despliegue y hosting

---

## Instalación y uso
1. Clona el repositorio:
```
git clone https://github.com/a23328061310382-LLUVIA/faceid-app.git
```
2. Abre el archivo `index.html` en tu navegador
3. O visita directamente: https://bucolic-hummingbird-b6f978.netlify.app

---

## Estructura del proyecto
```
faceid-app/
├── index.html        # Estructura principal de la app
├── app.js            # Lógica y funciones de la aplicación
├── style.css         # Estilos y diseño visual
├── manifest.json     # Configuración PWA
├── sw.js             # Service Worker para modo offline
├── icon-192.png      # Ícono de la app (192x192)
└── icon-512.png      # Ícono de la app (512x512)
```

---

## Requisitos del sistema
- Navegador moderno (Chrome, Edge, Firefox, Safari)
- Cámara web o cámara del dispositivo móvil
- Conexión a internet (para cargar los modelos de IA la primera vez)

---

## Autor
Desarrollado por **a23328061310382-LLUVIA**  
Materia: Implementación de Aplicaciones Móviles Multiplataforma  
Semestre 6 — 2026
