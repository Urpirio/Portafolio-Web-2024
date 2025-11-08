# 🌟 Portafolio Web 2024 - UrpirioDev

[![React](https://img.shields.io/badge/React-18.3.1-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-6.0.3-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

Portafolio web personal profesional desarrollado con React y Vite, presentando proyectos, habilidades y experiencia en desarrollo web y diseño UX/UI.

## 📋 Descripción

Este es un portafolio web moderno y responsivo que muestra mi trabajo como Desarrollador Web y Diseñador UX. El sitio web incluye secciones para proyectos destacados, educación, habilidades técnicas y un formulario de contacto integrado.

## ✨ Características

- 🎨 **Diseño Moderno**: Interfaz limpia y atractiva con animaciones suaves
- 📱 **Totalmente Responsivo**: Adaptado para dispositivos móviles, tabletas y escritorio
- ⚡ **Alto Rendimiento**: Construido con Vite para carga rápida y optimización
- 🔗 **Navegación Fluida**: Navegación por secciones con scroll suave
- 📧 **Formulario de Contacto**: Integración con EmailJS para mensajes directos
- 🎯 **Secciones Organizadas**: 
  - Presentación personal
  - Estadísticas y métricas
  - Proyectos destacados
  - Educación y certificaciones
  - Habilidades técnicas
  - Información de contacto

## 🛠️ Tecnologías Utilizadas

### Frontend
- **React** (v18.3.1) - Biblioteca de JavaScript para construir interfaces de usuario
- **React Router DOM** (v7.1.1) - Enrutamiento para aplicaciones React
- **Vite** (v6.0.3) - Build tool moderno para desarrollo web

### Estilos y UI
- **CSS3** - Estilos personalizados
- **Bootstrap Icons** (v1.11.3) - Iconos
- **Boxicons** - Iconos adicionales
- **Google Fonts (Poppins)** - Tipografía

### Herramientas de Desarrollo
- **ESLint** (v9.17.0) - Linter para JavaScript
- **@vitejs/plugin-react** (v4.3.4) - Plugin de React para Vite

### Servicios
- **EmailJS** - Servicio de envío de correos electrónicos
- **Resend** (v4.0.1) - API de envío de emails

## 📦 Instalación

### Prerrequisitos

- Node.js (versión 16 o superior)
- npm o yarn

### Pasos de Instalación

1. **Clonar el repositorio**
```bash
git clone https://github.com/Urpirio/Portafolio-Web-2024.git
cd Portafolio-Web-2024
```

2. **Instalar dependencias**
```bash
npm install
```

3. **Configurar variables de entorno** (opcional)
Si necesitas configurar servicios externos, crea un archivo `.env` en la raíz del proyecto.

## 🚀 Uso

### Modo Desarrollo

Para iniciar el servidor de desarrollo con hot-reload:

```bash
npm run dev
```

El sitio estará disponible en `http://localhost:5173`

### Compilar para Producción

Para crear una versión optimizada para producción:

```bash
npm run build
```

Los archivos compilados se generarán en la carpeta `dist/`

### Vista Previa de Producción

Para previsualizar la versión de producción localmente:

```bash
npm run preview
```

### Linting

Para ejecutar el linter y revisar la calidad del código:

```bash
npm run lint
```

## 📂 Estructura del Proyecto

```
Portafolio-Web-2024/
├── public/              # Archivos públicos estáticos
├── src/
│   ├── components/      # Componentes React
│   │   ├── body/        # Componentes del cuerpo principal
│   │   │   ├── Data/    # Datos para las secciones
│   │   │   └── style/   # Estilos CSS
│   │   ├── header/      # Componentes del encabezado
│   │   │   ├── Data/    # Datos del header
│   │   │   ├── img/     # Imágenes del header
│   │   │   └── style/   # Estilos CSS
│   │   └── main/        # Componentes principales
│   │       ├── Data/    # Datos de las secciones
│   │       └── style/   # Estilos CSS
│   └── Web.jsx          # Punto de entrada de la aplicación
├── index.html           # Plantilla HTML
├── package.json         # Dependencias y scripts
├── vite.config.js       # Configuración de Vite
└── README.md            # Documentación del proyecto
```

## 🎨 Secciones del Portafolio

1. **Header/Navegación**: Logo y menú de navegación
2. **Hero/Presentación**: Introducción personal con enlaces a redes sociales
3. **Estadísticas**: Métricas de experiencia y logros
4. **Proyectos**: Showcase de proyectos destacados con imágenes y descripciones
5. **Educación**: Formación académica y certificaciones
6. **Habilidades**: Tecnologías y herramientas dominadas
7. **Contacto**: Formulario de contacto con integración de EmailJS

## 🔧 Configuración de EmailJS

El formulario de contacto utiliza EmailJS. Para configurarlo:

1. Crea una cuenta en [EmailJS](https://www.emailjs.com/)
2. Configura un servicio de email
3. Crea una plantilla de email
4. Reemplaza el ID público en `index.html`:
```javascript
emailjs.init('TU_ID_PUBLICO_AQUI')
```

## 📱 Redes Sociales

- 📸 [Instagram](https://www.instagram.com/urpirio.junior/)
- 💼 [LinkedIn](https://do.linkedin.com/in/urpirio-junior-moreno-vargas-95294b269)
- 💻 [GitHub](https://github.com/Urpirio)

## 🤝 Contribución

Las contribuciones son bienvenidas. Si deseas contribuir:

1. Fork el proyecto
2. Crea una rama para tu característica (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 👨‍💻 Autor

**Urpirio Junior Moreno Vargas**

- Desarrollador Web & Diseñador UX
- Portafolio: [UrpirioDev](https://github.com/Urpirio/Portafolio-Web-2024)

## 🙏 Agradecimientos

- A la comunidad de React por las excelentes herramientas
- A Vite por el increíble rendimiento de desarrollo
- A todos los que han contribuido con feedback

---

⭐ Si te gusta este proyecto, ¡dale una estrella en GitHub!

**Última actualización**: Noviembre 2024
