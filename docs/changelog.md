# 📦 Changelog

Todas las modificaciones importantes de este proyecto se documentan en este archivo.

Este proyecto sigue [Semantic Versioning](https://semver.org/lang/es/) y esta plantilla se basa en [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

Este archivo documenta los cambios significativos en el proyecto desde su concepción.

## [Pre-desarrollo] - 05-10-2025
### 🧠 Planeación inicial
- Se definió el alcance del proyecto: portal académico para docentes universitarios de la facultad de ingeniería.
- Objetivos principales: gestión de cursos, carga académica, evaluaciones, y comunicación con estudiantes.
- Se identificaron los módulos clave: autenticación, gestión de asignaturas, calendario académico, reportes.

### 🛠️ Tecnologías seleccionadas
- **Backend:** Spring Boot (Java 21).
- **Frontend:** Angular (TypeScript).
- **Base de datos:** PostgreSQL.
- **ORM:** Spring Data JPA.
- **Autenticación:** JWT + Spring Security.
- **Control de versiones:** Git + GitHub.
- **Documentación:** Markdown en carpeta `docs/`.

### 📁 Estructura inicial del repositorio
- `frontend/` para la interfaz de usuario.
- `backend/` para la API REST.
- `docs/` para documentación técnica y funcional.

### 📄 Documentación creada
- [`diagrams/`](diagrams/): digramas propuestos y creados para el desarrollo del proyecto.
- [`arquitecture.md`](arquitecture.md): descripción de la arquitectura propuesta.
- [`user-stories.md`](user-stories.md): recopilación de historias de usuario para docentes, con criterios de aceptación y prioridades.
- [`ux-ui.md`](ux-ui.md): lineamientos de diseño visual, wireframes iniciales y componentes clave de la interfaz.
- [`roadmap.md`](roadmap.md): fases del desarrollo y entregables.

### 🎯 Objetivos del MVP
- Inicio de sesión y registro de docentes.
- Visualización y edición de carga académica.
- Gestión de asignaturas y grupos.
- Generación de reportes básicos en PDF.