# TechStore Online 🛒

Tienda online de tecnología moderna con diseño responsive y soporte para modo oscuro automático.

## 📋 Descripción del Proyecto

TechStore Online es una aplicación web de e-commerce especializada en productos tecnológicos. El proyecto incluye:

- **Diseño Responsive**: Adaptado para dispositivos móviles, tablets y desktop
- **Modo Oscuro Automático**: Se adapta automáticamente a las preferencias del sistema
- **Múltiples Categorías**: Smartphones, Laptops, Audio, Tablets, TV & Video, Gaming
- **Sistema de Login**: Autenticación básica para usuarios
- **Navegación Intuitiva**: Fácil navegación entre categorías y productos

## 🚀 Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **SCSS/CSS**: Estilos modulares y organizados
- **JavaScript**: Funcionalidades interactivas
- **Font Awesome**: Iconos vectoriales
- **Git**: Control de versiones

## 📁 Estructura del Proyecto

```
actividad2 - copia/
├── css/
│   └── main.css              # CSS compilado desde SCSS
├── scss/
│   ├── main.scss            # Archivo principal SCSS
│   ├── variables.scss       # Variables de colores y temas
│   ├── mixins.scss          # Mixins reutilizables
│   ├── base.scss            # Estilos base
│   ├── header.scss          # Estilos del header
│   ├── hero.scss            # Sección hero
│   ├── categories.scss      # Categorías
│   ├── products.scss        # Productos
│   └── footer.scss          # Footer
├── script/
│   └── script.js            # JavaScript principal
├── TechStore/
│   ├── login.html           # Página de login
│   ├── login.css            # Estilos del login
│   ├── Smartphones/         # Categoría Smartphones
│   ├── Laptops/             # Categoría Laptops
│   ├── Audio/               # Categoría Audio
│   ├── Tablets/             # Categoría Tablets
│   ├── TV/                  # Categoría TV & Video
│   └── Gaming/              # Categoría Gaming
├── index.html               # Página principal
└── README.md               # Este archivo
```

## 🛠️ Instalación y Uso

### Requisitos Previos

- Node.js (para compilar SCSS)
- Navegador web moderno

### Pasos de Instalación

1. **Clonar el repositorio** (o descargar el proyecto)
   ```bash
   git clone [url-del-repositorio]
   cd actividad2-copia
   ```

2. **Instalar dependencias**
   ```bash
   npm install
   ```

3. **Compilar SCSS a CSS**
   ```bash
   npx sass scss/main.scss css/main.css
   ```
   
   O para compilación en modo watch (automático):
   ```bash
   npx sass --watch scss/main.scss css/main.css
   ```

4. **Abrir en el navegador**
   - Abrir `index.html` directamente en el navegador
   - O usar un servidor local:
     ```bash
     # Con Python
     python -m http.server 8000
     
     # Con Node.js (http-server)
     npx http-server
     ```

## 🎨 Características Principales

### Modo Oscuro Automático
El sitio detecta automáticamente las preferencias del sistema operativo y aplica el tema correspondiente (claro u oscuro) sin necesidad de configuración manual.

### Diseño Responsive
- **Mobile First**: Optimizado para dispositivos móviles
- **Breakpoints**:
  - Phone: max-width 600px
  - Tablet: max-width 900px
  - Desktop: min-width 901px

### Categorías de Productos
Cada categoría tiene su propia página con:
- Información detallada
- Productos destacados
- Navegación entre categorías
- Botón para volver al inicio

### Sistema de Login
- Credenciales por defecto:
  - Email: `admin@techstore.com`
  - Contraseña: `1234`

## 📝 Uso del Sistema

### Navegación Principal
1. Desde la página principal (`index.html`) puedes:
   - Explorar categorías populares
   - Ver productos destacados
   - Acceder al sistema de login

### Categorías
1. Haz clic en cualquier categoría para ver su página dedicada
2. Desde cada categoría puedes:
   - Ver productos relacionados
   - Navegar a otras categorías
   - Volver al inicio

### Login
1. Haz clic en "Ingresar" en el header
2. Ingresa las credenciales
3. Serás redirigido al inicio tras un login exitoso

## 🎨 Personalización

### Colores
Los colores se pueden modificar en `scss/variables.scss`:
- Modo claro: Variables en `:root`
- Modo oscuro: Variables en `@media (prefers-color-scheme: dark)`

### Breakpoints Responsive
Los breakpoints se pueden ajustar en `scss/mixins.scss` en la función `@mixin respond-to`.

## 📦 Scripts Disponibles

```bash
# Compilar SCSS una vez
npm run build

# Compilar SCSS en modo watch
npm run watch
```

## 🤝 Contribución

Este es un proyecto educativo. Para contribuir:

1. Crear una rama para la nueva funcionalidad
2. Hacer commits descriptivos
3. Crear un Pull Request
4. Esperar revisión

## 📄 Licencia

Este proyecto es de uso educativo.

## 👨‍💻 Autor

Desarrollado como parte de una actividad educativa.

## 🔄 Versión

**v1.0.0** - Versión inicial con todas las funcionalidades básicas implementadas.

---

**Nota**: Asegúrate de compilar el SCSS antes de visualizar los cambios en el navegador.
