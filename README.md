#                    UNIVERSIDAD DE LAS FUERZAS ARMADAS ESPE
### Nombre: Camila Antonela Obando Buitron
### Fecha: 03 de agosto de 2023

# PWA Boilerplate con Material Design Lite

Plantilla de inicio para desarrollar Progressive Web Apps (PWAs) modernas usando Material Design Lite (MDL), preparada con un entorno de desarrollo profesional.

---

## Objetivos

- Crear un entorno reutilizable y automatizado para acelerar el desarrollo de PWAs.
- Incluir herramientas de calidad de código para mantener buenas prácticas desde el inicio.
- Simplificar el despliegue y pruebas tanto en desarrollo como en producción.

---

## Estructura del Proyecto

| Carpeta/Archivo     | Descripción |
|---------------------|-------------|
| `index.html`        | Página principal con integración de Material Design Lite. |
| `manifest.json`     | Archivo de manifiesto para la configuración de la PWA. |
| `sw.js`             | Service Worker básico para pruebas de caché offline. |
| `assets/`           | Carpeta para imágenes, íconos, logos, etc. |
| `css/`              | Estilos personalizados. |
| `js/`               | Scripts JavaScript. |
| `package.json`      | Definición del proyecto y scripts automatizados. |

---

## Scripts de NPM

| Comando                | Función |
|------------------------|--------|
| `npm run dev`          | Inicia el servidor de desarrollo con recarga en vivo usando `live-server`. |
| `npm run lint`         | Ejecuta ESLint para detectar errores y advertencias de estilo en el código JS. |
| `npm run format`       | Formatea todos los archivos con Prettier según la configuración. |
| `npm run serve`        | Inicia un servidor de producción local con `http-server`, sin caché para evitar conflictos con el Service Worker. |

---

## Ventajas de Usar esta Plantilla

| Ventaja                         | Descripción |
|----------------------------------|-------------|
| 🔄 **Recarga en vivo**           | Permite ver los cambios en tiempo real, sin recargar manualmente. |
| ✨ **Código limpio y coherente** | ESLint y Prettier aseguran calidad y formato constante. |
| 🛠️ **Ahorro de tiempo**         | Plantilla lista para usar con configuraciones básicas de PWA. |
| 🔁 **Desarrollo y producción diferenciados** | Scripts optimizados para evitar errores comunes de caché. |
| 📦 **Modularidad**              | Estructura organizada que facilita escalar el proyecto. |

---

## Casos de Uso Recomendados

- Aplicaciones de portafolio personales.
- Prototipos rápidos de apps móviles tipo "to-do", notas, agenda.
- Interfaces de kioscos informativos offline.
- PWAs educativas o de acceso público con funcionalidad básica offline.
- Bases para hackatones o MVPs con enfoque en rendimiento y escalabilidad.

---

##  Requisitos Previos

- Node.js y NPM instalados en el sistema.
- Editor de código recomendado: VS Code (con extensiones de ESLint y Prettier).
- Git para control de versiones y despliegue en GitHub.

---

##  Cómo Empezar

1. Clona el repositorio:
```bash
git clone https://github.com/usuario/pwa-boilerplate-mdl.git
```

2. Instala dependencias:
```bash
npm install
```

3. Inicia el servidor de desarrollo:
```bash
npm run dev
```

4. Lint y formato:
```bash
npm run lint
npm run format
```

5. Prueba en producción (con Service Worker):
```bash
npm run serve
```

---

##  Conclusiones

1. Esta plantilla no solo acelera el inicio de nuevos proyectos, sino que impone buenas prácticas desde el primer commit, lo cual es crucial para proyectos colaborativos o de crecimiento a largo plazo.

2. Al integrar herramientas como ESLint, Prettier, y diferenciación de entornos, se logra un flujo de trabajo más fluido, profesional y escalable, ideal para desarrolladores modernos que buscan eficiencia y claridad en sus entregas.

---

