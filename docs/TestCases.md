# Test Cases
Sistema: Evento Internacional Cultural  
Tipo de testing: Funcional / Regresión  
QA Tester: [Tu nombre]

| ID | Módulo | Descripción | Precondiciones | Pasos | Resultado Esperado |
|----|-------|-------------|---------------|------|-------------------|
| TC-01 | Registro | Registrar usuario con datos válidos | Usuario no registrado | 1. Ir a registro <br> 2. Completar datos <br> 3. Enviar formulario | Usuario registrado correctamente |
| TC-02 | Registro | Validar campos obligatorios | Página de registro abierta | 1. Dejar campos vacíos <br> 2. Presionar registrar | El sistema muestra mensajes de error |
| TC-03 | Login | Login con credenciales válidas | Usuario registrado | 1. Ir a login <br> 2. Ingresar email y contraseña | Usuario accede al sistema |
| TC-04 | Login | Login con contraseña incorrecta | Usuario registrado | 1. Ingresar contraseña incorrecta | Sistema muestra error |
| TC-05 | Eventos | Crear evento cultural | Usuario logueado | 1. Ir a crear evento <br> 2. Completar datos | Evento creado correctamente |
| TC-06 | Eventos | Validar campos obligatorios al crear evento | Usuario logueado | 1. Dejar campos vacíos <br> 2. Guardar | Sistema muestra error |
| TC-07 | Eventos | Editar evento existente | Evento creado | 1. Ir a editar evento <br> 2. Modificar datos | Evento actualizado |
| TC-08 | Eventos | Eliminar evento | Evento creado | 1. Seleccionar eliminar | Evento eliminado |
| TC-09 | Inscripciones | Registrarse a un evento | Usuario logueado | 1. Seleccionar evento <br> 2. Inscribirse | Usuario registrado en el evento |
| TC-10 | Inscripciones | Evitar inscripción duplicada | Usuario ya inscrito | 1. Intentar inscribirse nuevamente | Sistema bloquea inscripción |
| TC-11 | Eventos | Visualizar lista de eventos | Sistema con eventos cargados | 1. Ir a página de eventos | Se muestran eventos disponibles |
| TC-12 | Eventos | Buscar evento | Eventos existentes | 1. Usar barra de búsqueda | Evento aparece en resultados |
| TC-13 | UI | Verificar carga de página principal | Sistema activo | 1. Abrir página principal | Página carga correctamente |
| TC-14 | Navegación | Acceso a secciones desde menú | Usuario en home | 1. Usar menú | Navegación correcta |
| TC-15 | Sistema | Validar mensajes de error del sistema | Acción inválida | 1. Provocar error | Sistema muestra mensaje adecuado |