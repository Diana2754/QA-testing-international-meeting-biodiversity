# Test Execution Report

## Información General

- **Proyecto:** Evento Cultural Internacional
- **Tester:** Diana Alali
- **Fecha de ejecución:** 10/02/2025
- **Ambiente:** Development
- **Tipo de testing:** Funcional / UI / Responsive

---

# Resultados de Ejecución

| Test Case ID | Área | Descripción | Resultado | Observaciones |
|---------------|------|-------------|-----------|---------------|
| TC-01 | Navegación | Verificar funcionamiento del menú principal |  Aprobado | Todas las opciones redirigen correctamente |
| TC-02 | Navegación | Verificar redirección del logo |  Fallido | El logo no redirige al inicio |
| TC-03 | Carrusel | Verificar navegación del carrusel |  Aprobado | El carrusel cambia correctamente entre imágenes |
| TC-04 | Carrusel | Verificar funcionamiento del carrusel en mobile |  Fallido | El carrusel no responde en mobile |
| TC-05 | Información del evento | Verificar visualización de información |  Aprobado | Información visible y legible |
| TC-06 | Cronograma | Verificar alineación del cronograma |  Fallido | Horarios desalineados |
| TC-07 | Cronograma | Verificar visualización del cronograma en tablet |  Fallido | Elementos desalineados en tablet |
| TC-08 | Donaciones | Verificar botón de donación |  Fallido | Botón no redirige a PayPal |
| TC-09 | Donaciones | Verificar visibilidad del botón de donación |  Aprobado | Botón visible |
| TC-10 | Links externos | Verificar enlaces a redes sociales |  Aprobado | Enlaces funcionan correctamente |
| TC-11 | Patrocinadores | Verificar presencia de patrocinadores |  Fallido | Faltan patrocinadores en la sección |
| TC-12 | Patrocinadores | Verificar logos de patrocinadores |  Fallido | Logos incompletos |
| TC-13 | UI | Verificar colores del sitio |  Fallido | Color de fondo no coincide con diseño |
| TC-14 | Responsive | Verificar diseño responsive mobile |  Fallido | Layout presenta problemas |
| TC-15 | Responsive | Verificar responsive tablet |  Parcial | Algunos elementos desalineados |

---

# Resumen de Resultados

| Resultado | Cantidad |
|----------|----------|
| Aprobados | 5 |
| Fallidos | 9 |
| Parciales | 1 |

---

# Bugs Detectados

Durante la ejecución se detectaron los siguientes defectos:

| Bug ID | Descripción | Severidad |
|------|-------------|-----------|
| BUG-001 | Carrusel no funciona en mobile | Alta |
| BUG-002 | Botón de donación no redirige a PayPal | Crítica |
| BUG-003 | Cronograma desalineado | Media |
| BUG-004 | Logo no redirige al inicio | Media |
| BUG-005 | Colores del sitio no coinciden con el diseño | Media |
| BUG-006 | Faltan patrocinadores en la sección sponsors | Media |

---

# Conclusión

Durante la primera ejecución de pruebas se detectaron múltiples defectos funcionales y visuales que afectan la experiencia del usuario.

Se recomienda corregir los bugs reportados y ejecutar pruebas de regresión para validar las correcciones implementadas.