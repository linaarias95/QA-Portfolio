# 🐞 Reporte de Bugs – Proyecto Agendamiento Médico UX/UI

---

## 🐞 Bug #1: Contraste insuficiente en botón de agendar

- **ID:** BUG-001  
- **Severidad:** Media  
- **Prioridad:** Alta  
- **Descripción:** El botón "Agendar Cita" tiene un fondo verde claro con texto blanco, lo que dificulta la lectura para usuarios con baja visión.  
- **Pasos para reproducir:**  
  1. Ingresar a la plataforma  
  2. Seleccionar una especialidad y avanzar hasta el último paso del agendamiento  
  3. Observar el botón "Agendar Cita"  
- **Resultado esperado:** El botón debe tener un contraste mínimo WCAG AA.  
- **Resultado actual:** Contraste deficiente que no cumple estándares de accesibilidad.  
- **Estado:** Abierto

---

## 🐞 Bug #2: El campo "Teléfono" no muestra mensaje de error

- **ID:** BUG-002  
- **Severidad:** Alta  
- **Prioridad:** Alta  
- **Descripción:** El campo de teléfono permite dejarse vacío sin generar mensaje de validación.  
- **Pasos para reproducir:**  
  1. Acceder al formulario de cita  
  2. Dejar vacío el campo de teléfono  
  3. Enviar el formulario  
- **Resultado esperado:** Debe mostrarse un mensaje como “Este campo es obligatorio”.  
- **Resultado actual:** El formulario permite continuar sin alertar al usuario.  
- **Estado:** Abierto

---

## 🐞 Bug #3: Elementos del formulario se sobreponen en móviles

- **ID:** BUG-003  
- **Severidad:** Media  
- **Prioridad:** Media  
- **Descripción:** En dispositivos móviles, los campos de nombre y email se sobreponen entre sí.  
- **Pasos para reproducir:**  
  1. Abrir la aplicación desde un móvil  
  2. Ir al formulario de agendamiento  
  3. Observar el comportamiento al hacer scroll  
- **Resultado esperado:** Todos los campos deben estar alineados y visibles sin solapamiento.  
- **Resultado actual:** Campos visualmente superpuestos.  
- **Estado:** Abierto
