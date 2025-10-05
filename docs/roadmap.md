# 🛣️ Roadmap de Desarrollo

Este documento describe las fases de desarrollo del portal académico para docentes universitarios de ingeniería. El roadmap está organizado por sprints funcionales, con objetivos específicos y entregables por etapa.

---

## 🧭 Visión General

El proyecto se desarrollará en **6 fases principales**, siguiendo una metodología ágil basada en sprints quincenales. Cada fase incluye funcionalidades clave, pruebas y documentación.

---

## 🚀 Fase 0: Pre-desarrollo

**Objetivo:** Definir el alcance, arquitectura y herramientas base.

- Selección de tecnologías (Spring Boot, Angular, PostgreSQL).
- Diseño de arquitectura técnica y modelo de datos.
- Creación de repositorio y estructura inicial (`frontend/`, `backend/`, `docs/`).
- Documentación base: [`architecture.md`](architecture.md), [`user-stories.md`](user-stories.md), [`modelado.md`](modelado.md).

---

## 🧪 Fase 1: Autenticación y Seguridad

**Objetivo:** Implementar acceso seguro al sistema.

- Registro e inicio de sesión con JWT.
- Roles: `DOCENTE`, `ADMIN`, `COORDINADOR`.
- Guardas de ruta en Angular.
- Recuperación y cambio de contraseña.
- Pruebas unitarias de autenticación.
- Documentación: [`endpoints.md`](endpoints.md), [`docs/acceso.md`](docs/acceso.md).

---

## 📚 Fase 2: Gestión Académica

**Objetivo:** Visualización y administración de asignaturas y horarios.

- Consulta de asignaturas asignadas por semestre.
- Visualización de horario semanal.
- Notificaciones por cambios de horario.
- Gestión de carga académica.
- Diagrama ER actualizado en [`modelado.md`](modelado.md).

---

## 📝 Fase 3: Registro de Calificaciones

**Objetivo:** Registrar, modificar y exportar notas.

- Registro de calificaciones por grupo.
- Observaciones por estudiante.
- Edición de notas y validación.
- Exportación en Excel.
- Pruebas de integración con base de datos.

---

## 📊 Fase 4: Reportes y Estadísticas

**Objetivo:** Generar reportes académicos y métricas institucionales.

- Reportes de asistencia por grupo.
- Rendimiento académico por asignatura.
- Estadísticas por programa académico.
- Exportación en PDF.
- Dashboard para administrativos.

---

## 💬 Fase 5: Comunicación y Perfil

**Objetivo:** Mejorar la interacción y personalización del portal.

- Mensajes individuales y grupales.
- Historial de mensajes enviados.
- Actualización de perfil docente.
- Personalización de idioma y tema visual.
- Integración con redes académicas (ORCID, Google Scholar).

---

## 🧹 Fase 6: Optimización y Despliegue

**Objetivo:** Preparar el sistema para producción.

- Refactorización y limpieza de código.
- Pruebas de carga y rendimiento.
- Contenedores Docker para backend y base de datos.
- Despliegue en entorno productivo.
- Documentación final y manual de usuario.

---

## 📌 Próximos pasos

- Revisión de historias de usuario y priorización.
- Asignación de tareas por sprint.
- Integración continua con GitHub Actions.
- Feedback de usuarios piloto (docentes reales).

---

## 📎 Referencias Relacionadas

- [`user-stories.md`](user-stories.md): recopilación de funcionalidades por rol.
- [`architecture.md`](architecture.md): estructura técnica del sistema.
- [`model.md`](model.md): entidades y relaciones de base de datos.
