# Digital Horizons 2025 - Landing Page

## 📋 Descripción del Proyecto

Digital Horizons 2025 es una landing page creada para practicar diseño responsive, CSS moderno y estructura semántica, simulando un evento tecnológico real.

## ✨ Características

- **Diseño Responsivo**: Optimizado para dispositivos móviles, tablets y desktop
- **Interfaz Moderna**: Utiliza gradientes, animaciones CSS y efectos visuales
- **Formulario de Registro**: Formulario funcional para captura de leads
- **Perfiles de Ponentes**: Cards interactivas con información de los speakers
- **Agenda del Evento**: Lista visual de los temas a tratar
- **Optimización SEO**: Meta tags completos y Open Graph para redes sociales, etiquetas semánticas y aria-labels apropiados

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica y moderna
- **CSS3**:
  - Grid Layout y Flexbox
  - Gradientes y animaciones
  - Media queries para responsividad
  - Custom properties (variables CSS)
- **Google Fonts**: Tipografía Inter
- **SVG**: Iconos vectoriales optimizados

## 📁 Estructura del Proyecto

```
landing page/
├── index.html              # Página principal
├── style.css               # Estilos CSS principales
├── README.md              # Documentación del proyecto
└── imagenes/              # Directorio de imágenes
    ├── agenda.svg         # Icono de agenda
    ├── favicon.png        # Icono de la página
    ├── hombre.jpg         # Foto ponente masculino 1
    ├── hombre2.jpg        # Foto ponente masculino 2
    ├── logo nav.svg       # Logo principal del evento
    └── mujer.jpg          # Foto ponente femenina
```

## 🚀 Cómo Usar

### Prerrequisitos

- Un navegador web moderno (Chrome, Firefox, Safari, Edge)
- No requiere servidor web para visualización local

### Instalación y Ejecución

1. **Clonar o descargar el proyecto**

   ```bash
   # Si tienes git instalado:
   git clone [url-del-repositorio]

   # O simplemente descarga los archivos
   ```

2. **Abrir en navegador**
   - Haz doble clic en `index.html`
   - O arrastra el archivo a tu navegador
   - O usa un servidor local:

     ```bash
     # Con Python 3
     python -m http.server 8000

     # Con Node.js (si tienes http-server instalado)
     npx http-server
     ```

## 📱 Responsive Design

Optimizado para desktop, tablet y mobile mediante media queries.

## 🎨 Paleta de Colores

- **Primario**: `#3b82f6` (Azul)
- **Secundario**: `#60a5fa` (Azul claro)
- **Acento**: `#f59e0b` (Naranja)
- **Texto**: `#1e293b` (Gris oscuro)
- **Fondo**: `#f8fafc` (Gris muy claro)

## 👥 Ponentes Confirmados

1. **Laura Gomez** - CED en Codeivave

   - Especialista en desarrollo web y arquitecturas escalables

2. **Andres Martinez** - AI Researcher

   - Explora cómo la inteligencia artificial transforma nuestra forma de trabajar

3. **Juan Ramirez** - UI Designer en Inmobiliaria
   - Diseñando experiencias inclusivas y accesibles que conectan personas

## 📅 Agenda del Evento

- **Inteligencia Artificial**
- **UX y Diseño**
- **Ciberseguridad**
- **Blockchain**

## 📝 Formulario de Registro

El formulario incluye campos para:

- Nombre
- Apellido
- Email
- Comentarios/Observaciones

_Nota: El formulario está preparado para integración con servicios de backend o APIs de email marketing._

## 🔧 Personalización

### Cambiar Colores

Edita las variables CSS en `style.css`:

```css
:root {
  --primary-color: #3b82f6;
  --secondary-color: #60a5fa;
  --accent-color: #f59e0b;
}
```

### Modificar Contenido

- Edita `index.html` para cambiar textos, imágenes o estructura
- Reemplaza las imágenes en la carpeta `imagenes/` manteniendo los mismos nombres
- Actualiza la información de los ponentes en las cards correspondientes

### Agregar Nuevas Secciones

1. Añade el HTML en `index.html`
2. Define los estilos CSS correspondientes
3. Asegúrate de mantener la coherencia con el diseño existente

## 📈 Optimizaciones Implementadas

- **Performance**: Imágenes optimizadas, CSS minificado
- **SEO**: Meta tags completos, estructura semántica
- **Accesibilidad**: Alt texts, labels, contraste adecuado

## 🧠 Qué aprendí con este proyecto

- A estructurar una landing page usando HTML semántico para mejorar accesibilidad y SEO.
- A combinar CSS Grid y Flexbox según el tipo de layout.
- A diseñar componentes reutilizables como cards y formularios.
- A aplicar diseño responsive desde desktop hacia mobile.
- A mantener consistencia visual usando variables CSS.

## 👨‍💻 Créditos

**Desarrollado por**: Daphne De Jesus  
**Año**: 2026

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo LICENSE para más detalles.

---

⭐ **¡Gracias por usar Digital Horizons 2025 Landing Page!** ⭐
