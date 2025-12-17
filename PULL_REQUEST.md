# Pull Request: Feature - Categorías y Mejoras de Estilos

## 📋 Descripción

Este PR incluye la reorganización completa del proyecto, migración a SCSS, implementación de modo oscuro automático y creación de páginas individuales para cada categoría.

## 🎯 Cambios Principales

### 1. Reorganización de Estructura
- ✅ Renombrado `TechStoreLogin` → `TechStore`
- ✅ Movidas todas las carpetas de categorías dentro de `TechStore`
- ✅ Actualizadas todas las rutas y enlaces

### 2. Migración a SCSS
- ✅ Eliminados estilos inline del HTML
- ✅ Creada estructura modular de SCSS:
  - `variables.scss` - Variables de colores y temas
  - `mixins.scss` - Mixins reutilizables
  - `base.scss` - Estilos base
  - `header.scss` - Estilos del header
  - `hero.scss` - Sección hero
  - `categories.scss` - Categorías
  - `products.scss` - Productos
  - `footer.scss` - Footer

### 3. Modo Oscuro Automático
- ✅ Implementado detección automática con `prefers-color-scheme`
- ✅ Eliminado botón de toggle manual
- ✅ Colores modernos con tonos pastel para ambos modos

### 4. Páginas de Categorías
- ✅ Creadas páginas individuales para:
  - Smartphones
  - Laptops
  - Audio
  - Tablets
  - TV & Video
  - Gaming
- ✅ Navegación entre categorías
- ✅ Botón para volver al inicio

### 5. Mejoras de Diseño
- ✅ Diseño totalmente responsive
- ✅ Colores actualizados y modernos
- ✅ Mejores efectos hover y transiciones
- ✅ Mejor contraste y legibilidad

### 6. Documentación
- ✅ README.md completo con:
  - Descripción del proyecto
  - Instrucciones de instalación
  - Estructura del proyecto
  - Guía de uso
  - Scripts disponibles

## 📁 Archivos Modificados

- `index.html` - Actualizado con nuevas rutas
- `script/script.js` - Simplificado para modo oscuro automático
- `scss/*.scss` - Todos los archivos SCSS actualizados
- `package.json` - Agregados scripts npm
- `README.md` - Documentación completa (nuevo)

## 📁 Archivos Nuevos

- `TechStore/Smartphones/smartphones.html` y `.css`
- `TechStore/Laptops/laptops.html` y `.css`
- `TechStore/Audio/audio.html` y `.css`
- `TechStore/Tablets/tablets.html` y `.css`
- `TechStore/TV/tv.html` y `.css`
- `TechStore/Gaming/gaming.html` y `.css`
- `README.md`

## 🧪 Testing

- ✅ Verificado en navegadores modernos
- ✅ Probado modo claro y oscuro
- ✅ Verificado responsive en diferentes tamaños
- ✅ Navegación entre páginas funcional

## 📝 Commits Incluidos

1. `docs: agregar README.md con documentación completa del proyecto`
2. `feat: reorganizar estructura y migrar a SCSS con modo oscuro automático`

## ✅ Checklist

- [x] Código compilado sin errores
- [x] Estilos aplicados correctamente
- [x] Navegación funcional
- [x] Responsive design verificado
- [x] Modo oscuro funcionando
- [x] Documentación actualizada
- [x] Commits descriptivos

## 🚀 Cómo Probar

1. Compilar SCSS: `npm run build`
2. Abrir `index.html` en el navegador
3. Probar navegación entre categorías
4. Verificar modo oscuro cambiando preferencias del sistema
5. Probar responsive en diferentes tamaños de pantalla

## 📸 Screenshots

(Agregar screenshots si es necesario)

---

**Rama origen**: `feature/categorias-y-estilos`  
**Rama destino**: `main`  
**Tipo**: Feature

