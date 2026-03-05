# Regression Execution – v1.1

## Información General

- **Versión:** 1.1
- **Cambio aplicado:** Corrección de bugs detectados en v1.0
- **Tester:** Diana Alali
- **Fecha:** 18/02/2025
- **Ambiente:** Staging
- **Resultado general:** Aprobado con observaciones

---

## Retest de bugs

| Bug ID | Estado | Observaciones |
|------|------|------|
| BUG-001 | ✅ Corregido | Carrusel funcional en mobile |
| BUG-002 | ✅ Corregido | Botón redirige a PayPal correctamente |
| BUG-003 | ❌ Persistente | Desalineación parcial en tablet |
| BUG-004 | ✅ Corregido | Validación de email agregada |
| BUG-005 | ✅ Corregido | Background actualizado |
| BUG-006 | ✅ Corregido | Patrocinadores agregados |
---

## Nuevos hallazgos

### BUG-007 – Imagen del carrusel tarda en cargar

**Severidad:** Baja

**Descripción:**  
La primera imagen del carrusel tarda varios segundos en mostrarse en conexiones lentas.

---

### BUG-008 – Botón de donación demasiado pequeño en mobile

**Severidad:** Baja

**Descripción:**  
En mobile el botón de PayPal es difícil de presionar.

---

## Resumen de resultados

| Área | Resultado |
|-----|-----|
| Navegación | ✅ Aprobado |
| Carrusel | ⚠️ Parcial |
| Información del evento | ✅ Aprobado |
| Cronograma | ⚠️ Parcial |
| Donaciones | ⚠️ Parcial |
| UI | ⚠️ Parcial |
| Responsive | ⚠️ Parcial |

---

## Conclusión

Los bugs críticos fueron corregidos.  
Persisten algunos problemas menores de UI y responsive.