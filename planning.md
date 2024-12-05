# Análisis de Requerimientos de Desarrollo de Proyectos

## Información General del Proyecto

**Nombre del Proyecto:**  
ThePhysio.AI

**Cliente/Empresa:**  
The Physio

**Fecha de Inicio:**  
dd/mm/yyyy

**Responsable del Proyecto:**

Jorge Guerrero

**Equipo de Desarrollo:**

- Jorge Guerrero: Diseño e integración de hardware e infraestructura de red.
- Miguel Hernández: Diseño e integración de interfaces (Frontend).
- Diego Barajas: Diseño e integración de funciones (Backend).

## 1. Descripción del Proyecto

ThePhysio.AI (nombre provisional) es una plataforma web diseñada exclusivamente para los miembros de la franquicia "The Physio". Su propósito es proporcionar herramientas especializadas para la gestión de sucursales, diagnóstico y generación de informes, garantizando una experiencia eficiente y funcional.

## 2. Objetivos del Proyecto

- **Objetivo General:**
  
  Crear una plataforma web para gestionar sucursales, realizar diagnósticos personalizados y generar informes profesionales, optimizando los procesos operativos y administrativos de la franquicia.
  
- **Objetivos Específicos:**
  
  - Implementar un sistema seguro de inicio de sesión y gestión de usuarios.
  - Desarrollar un formulario dinámico para diagnósticos personalizados.
  - Integrar herramientas para la generación automática de informes en formatos PDF y XLSX.
  - Proveer un panel administrativo para gestionar sucursales y accesos.

## 3. Alcance del Proyecto

### 3.1 Funcionalidades Incluidas

- Sistema de inicio de sesión seguro.
- Gestión de sucursales y accesos.
- Formulario dinámico para diagnósticos personalizados.
- Generación automática de informes en PDF y XLSX.
- Roles y permisos para cuentas estándar y administrativas.

### 3.2 Funcionalidades Excluidas

- Gestión de inventarios.
- Integración con dispositivos físicos de diagnóstico.
- Aplicaciones móviles (en esta fase).

## 4. Requerimientos Funcionales

### 4.1 Inicio de Sesión

Sistema de gestión de sesiones que permite a los usuarios acceder a la plataforma de manera segura y personalizada.

### 4.2. Control de Sucursales

Panel de administración que facilita la gestión de las diferentes sucursales de la franquicia.

### 4.3. Control de Accesos

Tipos de Cuenta:

- Estándar: Diseñadas para fisioterapeutas, con acceso a funciones básicas.
  
- Administrativa: Incluye funciones básicas más la capacidad de gestionar accesos (crear, modificar y eliminar). Además, permiten configurar la expiración de accesos de forma automática.
  

### 4.4. Formulario Dinámico para Diagnóstico

Herramienta interactiva para recopilar información progresivamente hasta obtener los datos necesarios para generar un diagnóstico o tratamiento personalizado.

Los fisioterapeutas pueden editar los diagnósticos para corregir errores o realizar mejoras.

### 4.5. Generación de Informes

Creación automática de documentos en formatos:

- XLSX: Para uso interno.
  
- PDF: Para entregar a los pacientes.
  

Ambos formatos respetarán un diseño establecido por el cliente.

## 5. Requerimientos No Funcionales

- **Desempeño:**  
  Respuesta óptima en hardware moderno y conexión estable.
  
- **Seguridad:**  
  Protección contra vulnerabilidades siguiendo OWASP Top 10.
  
- **Usabilidad:**  
  Interfaz intuitiva y accesible para usuarios administrativos y estándar.
  
- **Compatibilidad:**  
  Funcionalidad en navegadores modernos: Chrome, Edge, Safari y Firefox.
  
- **Escalabilidad:**  
  Soporte para futuras expansiones y nuevas funcionalidades.
  
- **Disponibilidad:**  
  Operativa 24/7 con soporte técnico en caso de fallas.
  

## 6. Requerimientos de Infraestructura

- **Servidor:**  
  Cloud server con escalabilidad dinámica.
  
- **Bases de Datos:**  
  MySQL para almacenamiento seguro y eficiente.
  
- **Red y Conectividad:**  
  Conexión confiable y redundante.
  

## 7. Cronograma de Desarrollo y Checkpoints

### 7.1 Fases del Proyecto

| Fase | Descripción | Horas estimadas | Fecha de Inicio | Fecha de Fin |
| --- | --- | --- | --- | --- |
| Diseño | Definición de diseño de UI/UX y patrones de diseño de código. | 15 hrs | dd/mm/yyyy | dd/mm/yyyy |
| Desarrollo | Desarrollo de frontend y backend. |     | dd/mm/yyyy | dd/mm/yyyy |
| Pruebas | Validación funcional y de seguridad. |     | dd/mm/yyyy | dd/mm/yyyy |
| Implementación | Configuración en ambiente de producción. |     | dd/mm/yyyy | dd/mm/yyyy |
| Mantenimiento | Ajustes y soporte post-lanzamiento. |     | dd/mm/yyyy | dd/mm/yyyy |

### 7.2 Sprints

- **Checkpoint 1:** Prototipo del sistema de inicio de sesión y panel administrativo.
- **Checkpoint 2:** Integración del formulario dinámico y generación de informes.
- **Checkpoint 3:** Validación final del sistema y preparación para lanzamiento.

## 8. Reuniones de Seguimiento

- **Reunión Inicial:**
  
  - Fecha: dd/mm/yyyy
  - Objetivos esperados: Definir alcances, responsables y metodología de desarrollo.
- **Reuniones Periódicas:**
  
  - Frecuencia: Semanal (Martes 7:00 PM).
- **Reunión de Cierre:**  
  Fecha: dd/mm/yyyy  
  Objetivos: Validar entregables y formalizar cierre del proyecto.
  

## 9. Riesgos y Contingencias

- **Riesgo 1:** Retrasos en la generación de contenidos de cliente.
  
  - Plan: Establecer fechas límite claras y revisiones periódicas.
- **Riesgo 2:** Incompatibilidades en navegadores menos utilizados.
  
  - Plan: Realizar pruebas exhaustivas en diferentes entornos.

## 10. Documentación Complementaria

- Diagramas de arquitectura del sistema.
- Manuales de usuario para roles estándar y administrativos.

## 11. Firmas y Aprobación

| Rol | Nombre | Firma | Fecha |
| --- | --- | --- | --- |
| Responsable | Jorge Guerrero | Firma | dd/mm/yyyy |
| Cliente/Empresa | Nombre Cliente | Firma | dd/mm/yyyy |
| Líder de Proyecto | Jorge Guerrero | Firma | dd/mm/yyyy |
