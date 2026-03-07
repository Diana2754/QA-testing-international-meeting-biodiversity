# Regression Execution – v1.0

## Información General

- **Versión:** 1.0
- **Tipo de ejecución:** Primera ejecución del checklist de regresión
- **Tester:** Diana Alali
- **Fecha:** 02/02/2025
- **Ambiente:** Dev
- **Resultado general:** Fallido

---

## Resumen de resultados

| Área | Resultado |
|-----|-----|
| Navegación | ✅ Aprobado |
| Carrusel | ❌ Fallido |
| Información del evento | ❌ Fallido |
| Cronograma | ⚠️ Parcial |
| Donaciones (PayPal) | ❌ Fallido |
| Formularios | ⚠️ Parcial |
| UI / Integridad visual | ⚠️ Parcial |
| Responsive | ❌ Fallido |
| Cross-browser | ✅ Aprobado |

---

## Bugs detectados

### BUG-001 – Carrusel no funciona en mobile

**Severidad:** Alta  
**Dispositivo:** Mobile (375px)

**Descripción:**  
El carrusel no permite cambiar de slide en mobile.  
Los botones de navegación no responden.

**Resultado esperado:**  
El usuario debe poder navegar entre las imágenes del carrusel.

---

### BUG-002 – Botón de donación PayPal no redirige

**Severidad:** Crítica

**Descripción:**  
Al hacer clic en el botón de donación, no ocurre ninguna acción.

**Resultado esperado:**  
Debe redirigir a la página de pago de PayPal.

---

### BUG-003 – Cronograma desalineado en tablet

**Severidad:** Media

**Descripción:**  
En resolución tablet (768px) algunos horarios del cronograma aparecen desalineados.

---

### BUG-004 – El logo no reedirige al menú principal

**Severidad:** Media

**Descripción:**  
El formulario permite enviar correos sin formato válido.

---

### BUG-005 – El color del background no coincide

**Severidad:** Media

**Descripción:**  
El color debe coincidir con la visualización del figma.

---

### BUG-006 – Faltan patrocinadores

**Severidad:** Media

**Descripción:**  
Deben estar todos los patrocinadores del evento con logo actualizado.

---

## Conclusión

La versión **no aprueba regresión** debido a defectos críticos en el carrusel y la funcionalidad de donaciones.