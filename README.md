# ClickMalla - Prototipo de Gestión Curricular

> Una aplicación web interactiva para la visualización y gestión malla curricular, diseñada para ayudar a estudiantes de Ingeniería Civil Informática a llevar el control de sus ramos, progreso y planificación de horarios.

![Estado del Proyecto](https://img.shields.io/badge/estado-finalizado-green)
![Licencia](https://img.shields.io/badge/licencia-MIT-blue)
![HTML5](https://img.shields.io/badge/html-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📋 Descripción

**ClickMalla** es una aplicación web completa que permite a los estudiantes:
- Visualizar su malla curricular por semestres
- Registrar el estado de cada ramo (pendiente, cursando, aprobado, reprobado)
- Ingresar y consultar notas finales
- Simular qué nota se necesita para alcanzar un promedio objetivo
- Planificar horarios semestrales
- Llevir un dashboard con estadísticas generales
- Gestionar ramos personalizados

La aplicación persiste los datos en `localStorage`, por lo que los datos permanecen guardados entre sesiones.

## 🛠️ Tecnologías Utilizadas

| Tecnología | Descripción |
|------------|-------------|
| **HTML5** | Estructura semántica de la aplicación |
| **CSS3** (TailwindCSS via CDN) | Estilizado responsivo y diseños modernos |
| **JavaScript Vanilla** | Lógica completa sin dependencias externas |
| **Lucide Icons** | Iconos vectoricos ligeros |
| **LocalStorage API** | Persistencia de datos en el navegador |

## ✨ Características Principales

- **Interfaz responsiva**: Funciona desde móviles hasta desktop (breakpoints md)
- **Gestión completa de ramos**: Agregar, editar estado y notas
- **Dashboard estadístico**: Promedio general, avance de créditos, distribución de estados
- **Planificador de horarios**: Visualización semanal de clases
- **Persistencia de datos**: Datos guardados automáticamente en el navegador
- **Modales interactivos**: Flows completos de usuario (login, agregar ramos, etc.)
- **Animaciones sutiles**: Efectos fade-in y transiciones suaves

## 📁 Estructura del Proyecto

Dado que es un prototipo compacto, la estructura se concentra en un solo archivo principal:

```
clickmalla/
├── index.html          # HTML estructural, CSS estilizado y JavaScript completo
└── .git/               # Repositorio Git
```

**Nota**: Todo el código (HTML, CSS y JS) está integrado en `index.html` utilizando:
- TailwindCSS v3 vía CDN para estilos responsivos
- Scripts inline para la lógica de aplicación
- Enlaces a fuentes Google Fonts (Inter) e iconos Lucide

## 🎯 Casos de Uso para CV

Este proyecto demuestra competencias en:

### Desarrollo Frontend
- Construcción de interfaces interactivas con HTML5/CSS3/JavaScript puro
- Diseño responsive sin frameworks complejos
- Gestión de estado local con LocalStorage
- Animaciones y transiciones CSS

### Experiencia de Usuario (UX)
- Flujos de usuario completos (onboarding → uso → persistencia)
- Diseño accesible y responsive
- Feedback visual claro mediante toasts y estados

### Buenas Prácticas
- Código modular organizado en funciones bien definidas
- Persistencia de datos del lado del cliente
- Manejo de errores básico y validaciones
- Comentarios y documentación del código

*Proyecto creado como parte del desarrollo de habilidades en tecnologías web para la universidad. Licencia MIT - libre para usar y modificar con atribución.*