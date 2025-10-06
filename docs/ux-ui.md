# 🎨 UX/UI del Portal Académico

Este documento describe los principios de diseño y experiencia de usuario aplicados al desarrollo del portal académico para docentes universitarios de ingeniería. El objetivo es garantizar una interfaz intuitiva, accesible y coherente con las necesidades del usuario.

---

## 🧭 Principios de UX

- **Claridad:** La información debe ser fácil de encontrar, leer y entender.
- **Consistencia:** Uso uniforme de colores, tipografías, iconografía y componentes.
- **Feedback inmediato:** El sistema debe responder claramente a las acciones del usuario (ej. confirmaciones, errores).
- **Accesibilidad:** Compatible con lectores de pantalla, navegación por teclado y contraste adecuado.
- **Minimización de esfuerzo:** Reducción de clics y pasos innecesarios para completar tareas frecuentes.

---

## 🖼️ Lineamientos de UI

### 🎨 Paleta de colores

- **Primario:** Amarillo institucional (#fab514)
- **Secundario:** Amarillo claro (#fdfdfc)
- **Énfasis:** Verde éxito (#4CAF50), Rojo error (#F44336)
- **Texto:** Negro (#212121) y gris medio (#757575)

### 🅰️ Tipografía

- **Fuente principal:** Roboto
- **Jerarquía:**  
  - Títulos: `h1`, `h2` con peso 500–700  
  - Texto base: `p` con peso 300 - 400  
  - Notas y etiquetas: `small` con peso 100 - 200

### 🧩 Componentes clave

- **Navbar fija:** Acceso rápido a módulos principales (Horario, Calificaciones, Mensajes, Perfil).
- **Sidebar contextual:** Opciones específicas según el módulo activo.
- **Cards informativas:** Para asignaturas, grupos y eventos.
- **Modales:** Para formularios de edición y confirmaciones.
- **Toasts:** Para notificaciones breves (éxito, error, advertencia).

---

## 📱 Diseño Responsivo

- **Mobile-first:** Optimización para pantallas pequeñas desde el inicio.
- **Breakpoints:**  
  - `sm`: ≥576px  
  - `md`: ≥768px  
  - `lg`: ≥992px  
  - `xl`: ≥1200px

- **Comportamientos adaptativos:**  
  - Menú hamburguesa en móviles  
  - Reordenamiento de columnas en tablas  
  - Ocultamiento de elementos secundarios en pantallas pequeñas

---

## 🧪 Prototipos y Wireframes

- Los prototipos fueron diseñados en Figma y validados con docentes reales.
- Se realizaron pruebas de usabilidad para ajustar navegación, legibilidad y carga cognitiva.
- Acceso a prototipos: *(enlace interno o referencia a carpeta de diseño)*

---

## 🧠 Consideraciones UX específicas

- **Gestión de calificaciones:** Formularios simplificados, validación en tiempo real, exportación directa.
- **Mensajería:** Historial accesible, filtros por grupo, confirmación de lectura.
- **Perfil docente:** Edición rápida, campos obligatorios destacados, foto de perfil visible en navbar.

---

## 📌 Referencias Relacionadas

- [`user-stories.md`](user-stories.md): necesidades funcionales por rol.
- [`architecture.md`](architecture.md): estructura técnica del sistema.
- [`roadmap.md`](../roadmap.md): fases de desarrollo y entregables.
