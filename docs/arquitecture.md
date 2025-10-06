# 🏗️ Arquitectura del Sistema

Este documento describe la arquitectura técnica del portal académico para docentes universitarios de ingeniería. El objetivo es ofrecer una visión clara de los componentes principales, sus responsabilidades y cómo interactúan entre sí.

---

## 📐 Visión General

El sistema está dividido en tres capas principales:

1. **Frontend (Angular + TypeScript):**
   - Interfaz web responsiva para docentes.
   - Comunicación con el backend vía HTTP (REST API).
   - Gestión de sesiones, formularios y visualización de datos.

2. **Backend (Spring Boot + Java):**
   - API REST que expone los servicios del sistema.
   - Lógica de negocio, validaciones y seguridad.
   - Acceso a base de datos mediante JPA/Hibernate.

3. **Base de Datos (PostgreSQL):**
   - Almacenamiento relacional de entidades académicas.
   - Integridad referencial y consultas optimizadas.
   - Migraciones gestionadas con Flyway.

---

## 🧱 Componentes Principales

### 🔐 Autenticación y Autorización
- Implementada con **JWT** y **Spring Security**.
- Roles definidos: `DOCENTE`, `ADMIN`, `COORDINADOR`.
- Guardas en Angular para proteger rutas según rol.

### 📚 Gestión Académica
- Entidades: `Docente`, `Asignatura`, `Grupo`, `CargaAcademica`, `Evaluación`.
- Servicios REST para CRUD completo.
- Validaciones de negocio (ej. no duplicar carga en el mismo horario).

### 📅 Calendario y Reportes
- Módulo de calendario académico con eventos y recordatorios.
- Generación de reportes en PDF (evaluaciones, carga, asistencia).

---

## 🔄 Flujo de Datos

```plaintext
[Usuario (Docente)] ⇄ [Angular Frontend] ⇄ [Spring Boot API] ⇄ [PostgreSQL]