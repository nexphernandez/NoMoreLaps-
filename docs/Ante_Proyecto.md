# Anteproyecto – NoMoreLaps

![NoMoreLaps Logo](../images/Logo.png)

**Autores:** Nicolás Expósito Hernández y Alejandro Díaz Luis  

**Tutor**: Eleazar Morales Díaz

**Ciclo**: Desarrollo de Aplicaciones Multiplataforma

**Periodo de ejecución**: Febrero 2026 – Mayo 2026

---

## Índice de Contenidos

1. [Introducción](#1.-Introducción)
2. [Origen, contextualización y justificación del proyecto](##2.-Origen,-contextualización-y-justificación-del-proyecto)
3. [Objetivo general del proyecto](#objetivo-general-del-proyecto)
4. Descripción del proyecto (alcance)
  4.1 Aplicación móvil Usuario
  4.2 Aplicación móvil Empresa
  4.3 Backend
  4.4 API pública para integración empresarial
5. Tareas
6. Cronograma
7. Recursos humanos y materiales
8. Política de seguimiento y control de calidad
9. Cláusulas
10. Plan de marketing
11. Plan de sostenibilidad
12. Estudio de riesgos
13. Arquitectura del sistema
14. Simulación de costes

---

## 1. Introducción

El presente documento describe el anteproyecto del sistema NoMoreLaps, desarrollado dentro del módulo de Proyecto del Ciclo Formativo de Grado Superior en Desarrollo de Aplicaciones Multiplataforma.

En él se detallan la planificación, alcance, organización del trabajo, recursos, control de calidad y viabilidad del sistema conforme a las directrices del instituto.

## 2. Origen, contextualización y justificación del proyecto

La búsqueda de aparcamiento en entornos urbanos genera:

* Congestión de tráfico

* Pérdida de tiempo

* Incremento de emisiones contaminantes

* Gestión ineficiente de parkings privados

NoMoreLaps surge como una solución tecnológica multiplataforma que digitaliza la gestión de aparcamientos mediante:

* Aplicación móvil para usuarios

* Aplicación móvil para empresas

* API REST segura con integración externa

El proyecto se contextualiza dentro del ámbito de Smart Cities y digitalización de servicios urbanos.

## 3. Objetivo general del proyecto

Desarrollar una plataforma compuesta por:

* Aplicación móvil para usuarios

* Aplicación móvil para empresas

* Backend centralizado con API REST segura

El sistema permitirá gestionar reservas de aparcamiento con:

* Precios dinámicos

* Integración con calendario

* Aplicación automática de sanciones

* API pública para integración empresarial

## 4. Descripción del proyecto (alcance)

### 4.1 Aplicación móvil Usuario

* Registro e inicio de sesión

* Geolocalización de parkings

* Reserva de plaza

* Historial de reservas

* Visualización de sanciones

* Integración con calendario

### 4.2 Aplicación móvil Empresa

* Gestión de parkings

* Gestión de plazas

* Configuración de precios dinámicos

* Consulta de reservas

* Visualización de sanciones

### 4.3 Backend

Desarrollado con:

* Java + Spring Boot

* Autenticación JWT

* Validación mediante Swagger

* Control de roles

* Motor automático de sanciones (+10 minutos)

* Cálculo de precios dinámicos

* Base de datos SQLite

* Servidor externo con certificado digital SSL

### 4.4 API pública para integración empresarial

La plataforma dispondrá de endpoints públicos protegidos mediante API Key para que empresas puedan integrar el sistema en su propio software.

Funcionalidades expuestas:

* Consulta de disponibilidad

* Creación de reservas

* Consulta de reservas activas

* Consulta de sanciones

* Sincronización de ocupación

## 5. TAREAS DEL PROYECTO

| Nº	| Tarea	| Descripción	| Duración (horas)	| Mes | 
|------------|-----------|-----------|-----------|-----------|
| 1	| Análisis y Diseño | Recogida de requisitos, casos de uso, diagramas UML y modelo entidad-relación	| 60	| Febrero | 
| 2 |	Diseño Base de Datos	| Modelo relacional, script SQL e índices	| 40	| Febrero | 
| 3 |	Desarrollo Backend	| Implementación API REST, JWT, CRUD, sanciones, precios dinámicos, Swagger, SSL	| 140	| Marzo – Abril | 
| 4	| Desarrollo Apps Móviles	| Desarrollo app usuario y empresa, integración API, mapas y calendario	| 130	| Marzo – Abril |
| 5	| Pruebas y Validación	| Pruebas funcionales y validación de endpoints con Swagger	| 30	| Mayo| 
| 6	| Documentación y Defensa	| Redacción memoria y preparación presentación	| 20	| Mayo | 
| | | TOTAL	| | 420 horas | Febrero – Mayo | 

## 6. CRONOGRAMA DEL PROYECTO

| Tarea	| Febrero	| Marzo	| Abril	| Mayo | 
|------------|-----------|-----------|-----------|-----------|
| Análisis y Diseño	| ✔	 |  |  |  | 	
| Diseño Base de Datos	| ✔	 |  |  |  | 	
| Desarrollo Backend	|  | ✔ | ✔ |  | 	
| Desarrollo Apps		|  | ✔ | ✔ |  | 	
| Pruebas		|  |  |  | ✔ | 	
| Documentación		|  |  |  | ✔ | 	

## 7. RESUMEN DE RECURSOS HUMANOS

### 7.1 Recursos Humanos
| Rol	| Nº Personas |	Funciones	| Dedicación |
|------------|-----------|-----------|-----------|
| Desarrollador Backend |	1	| API REST, seguridad, base de datos, lógica de negocio |	210 h |
| Desarrollador Frontend Mobile	| 1	| Aplicaciones móviles, integración API, UI	| 210 h |
| Total equipo	| 2 personas	| Desarrollo completo del sistema	| 420 h |

### 7.2 Recursos Materiales

* 2 ordenadores

* 2 dispositivos móviles

* Visual Studio Code

* GitHub + Kanban

* Servidor externo

* Certificado digital SSL

* Swagger


## 8. Política de seguimiento y control de calidad

* Control de versiones con GitHub

* Gestión mediante Kanban

* Revisión semanal

* Validación endpoints con Swagger

* Pruebas funcionales en ambas apps

* Validación de roles y seguridad


### 9. Cláusulas

* Prioridad a funcionalidades críticas en caso de retraso

* Entrega completa y funcional antes de defensa

* Entrega de código, documentación y presentación

## 10. Plan de Marketing

### 10.1 Público objetivo

* Conductores urbanos

* Empresas con parkings

### 10.2 Propuesta de valor

* Integración calendario

* Sanciones automáticas

* Precios dinámicos

* API pública profesional

### 10.3 Modelo de ingresos

* Comisión por reserva (5–10%)

* Suscripción mensual empresas

### 10.4 Objetivos primer año

* 500 usuarios

* 20 empresas

* 1.000 reservas mensuales

---

## 11. Plan de Sostenibilidad

### 11.1 Económica

Modelo mixto de ingresos.

### 11.2 Social

Optimización del tiempo urbano.

### 11.3 Ambiental

Reducción indirecta de emisiones.

## 12. Estudio de Riesgos
### 12.1 Técnicos

* Caída servidor

* Problemas SSL

* Fallos integración calendario

* Errores en precios dinámicos

* Vulnerabilidades seguridad

Medidas:

* HTTPS obligatorio

* JWT + API Key

* Copias de seguridad

* Validaciones backend

### 12.2 Organizativos

* Retrasos → priorización

* Sobrecarga → división tareas

### 12.3 Económicos

* Control de costes infraestructura

## 13. Arquitectura del Sistema

Arquitectura cliente-servidor basada en API REST:

App Usuario (React Native)
App Empresa (React Native)
→ HTTPS (JWT / API Key)
→ API REST Spring Boot
→ Base de Datos SQLite

Sistema externo empresa
→ HTTPS + API Key
→ API REST NoMoreLaps

Seguridad:

* HTTPS

* JWT

* API Key

* Spring Security

## 14. Simulación de Costes
*Desarrollo*

420 h × 20 €/h = 8.400 €

*Servidor anual*

300 €

*Certificado SSL*

80 €

*Dominio*

15 €

Coste total estimado inicial: 8.795 €

