# Final Test Report – Evento Cultural Internacional

## Información General

- **Proyecto:** Web del Evento Cultural Internacional
- **Tipo de proyecto:** Sitio web informativo con donaciones
- **Tester:** Diana Alali
- **Fecha del reporte:** 02/02/2025
- **Ambiente testeado:** Development

### Navegadores utilizados

- Google Chrome
- Mozilla Firefox

### Dispositivos evaluados

- Desktop (1920px)
- Tablet (768px)
- Mobile (375px)

---

# Objetivo del Testing

El objetivo del proceso de testing fue validar el correcto funcionamiento del sitio web del evento cultural internacional, verificando la navegación, integridad visual, adaptabilidad responsive y la funcionalidad del sistema de donaciones.

Se buscó asegurar que todos los componentes del sitio funcionen correctamente antes de su publicación.

---

# Alcance del Testing

Las pruebas incluyeron los siguientes componentes del sitio:

- Header y menú de navegación
- Logo del evento
- Carrusel de imágenes
- Información del evento
- Cronograma de actividades
- Botón de donación (PayPal)
- Footer y enlaces externos
- Adaptabilidad responsive
- Integridad visual de la interfaz

---

# Tipos de Testing Realizados

Durante el proceso de QA se realizaron los siguientes tipos de pruebas:

- Testing funcional
- Testing de interfaz de usuario (UI)
- Testing de experiencia de usuario (UX)
- Testing responsive
- Testing cross-browser
- Testing de regresión

---

# Historial de Ejecución de Pruebas

Durante el proceso de testing se realizaron tres ciclos de ejecución:

| Ejecución | Resultado | Observaciones |
|----------|-----------|---------------|
| Regression v1 | ❌ Fallido | Se detectaron múltiples bugs |
| Regression v2 | ⚠️ Parcial | Se corrigieron defectos críticos |
| Regression v3 | ✅ Aprobado | No se detectaron defectos |

---

# Bugs Detectados y Corrección

Durante la primera ejecución se detectaron los siguientes defectos:

| ID | Descripción | Severidad | Estado |
|----|-------------|-----------|--------|
| BUG-001 | Carrusel no funciona en mobile | Alta | ✅ Resuelto |
| BUG-002 | Botón de donación PayPal no redirige | Crítica | ✅ Resuelto |
| BUG-003 | Cronograma desalineado en tablet | Media | ✅ Resuelto |
| BUG-004 | Logo no redirige al home | Media | ✅ Resuelto |
| BUG-005 | Color de background no coincide con diseño | Media | ✅ Resuelto |
| BUG-006 | Faltan patrocinadores en la sección correspondiente | Media | ✅ Resuelto |

---

# Resultados Finales

Luego de aplicar las correcciones y ejecutar la **tercera instancia de pruebas de regresión**, se verificó que:

- Todos los defectos reportados fueron corregidos.
- No se detectaron nuevos bugs.
- La navegación funciona correctamente.
- La funcionalidad de donaciones redirige correctamente a PayPal.
- El sitio mantiene consistencia visual en todos los dispositivos evaluados.

---

# Conclusión

La versión actual del sitio **aprueba satisfactoriamente el proceso de testing** luego de la tercera ejecución de pruebas de regresión.

El sitio cumple con los criterios de calidad definidos y se considera **apto para su publicación**.

---

# Recomendaciones

Para futuras versiones del sitio se recomienda:

- Ejecutar pruebas de regresión ante cualquier modificación del diseño o contenido.
- Mantener actualizado el cronograma y los patrocinadores del evento.
- Continuar monitoreando la experiencia de usuario en dispositivos móviles.

---