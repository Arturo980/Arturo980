<div align="center">

# Arturo Figueroa

### Ingeniero Informático

**Desarrollo de Software · Backend · Bases de Datos · Ciberseguridad**

Desarrollador orientado a la creación de soluciones mantenibles, seguras y escalables,  
con interés en arquitectura de software, desarrollo backend y ciberseguridad.

[LinkedIn](https://www.linkedin.com/in/arfigueroa980/) · [GitHub](https://github.com/Arturo980)

</div>

---

## Sobre mí

Soy Ingeniero Informático con experiencia en desarrollo de aplicaciones, integración de servicios, bases de datos y mejora de arquitecturas de software.

Durante mi formación y experiencia profesional he trabajado con tecnologías frontend y backend, bases de datos relacionales y NoSQL, autenticación, control de acceso, integración de APIs y organización de proyectos mediante arquitecturas modernas.

Actualmente estoy enfocado en continuar fortaleciendo mis conocimientos en:

- Desarrollo Backend
- Arquitectura de Software
- Ciberseguridad
- Cloud
- Bases de Datos
- Buenas prácticas de desarrollo

---

## Tecnologías

<div align="center">

### Lenguajes

![JavaScript](https://img.shields.io/badge/JavaScript-111827?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-111827?style=for-the-badge&logo=typescript&logoColor=3178C6)
![Python](https://img.shields.io/badge/Python-111827?style=for-the-badge&logo=python&logoColor=3776AB)
![SQL](https://img.shields.io/badge/SQL-111827?style=for-the-badge&logo=postgresql&logoColor=336791)

<br><br>

### Frontend

![React](https://img.shields.io/badge/React-111827?style=for-the-badge&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-111827?style=for-the-badge&logo=html5&logoColor=E34F26)
![CSS3](https://img.shields.io/badge/CSS3-111827?style=for-the-badge&logo=css3&logoColor=1572B6)

<br><br>

### Backend

![Node.js](https://img.shields.io/badge/Node.js-111827?style=for-the-badge&logo=node.js&logoColor=339933)
![REST APIs](https://img.shields.io/badge/REST_APIs-111827?style=for-the-badge&logo=swagger&logoColor=85EA2D)

<br><br>

### Bases de Datos

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-111827?style=for-the-badge&logo=postgresql&logoColor=336791)
![Supabase](https://img.shields.io/badge/Supabase-111827?style=for-the-badge&logo=supabase&logoColor=3ECF8E)
![MongoDB](https://img.shields.io/badge/MongoDB-111827?style=for-the-badge&logo=mongodb&logoColor=47A248)

<br><br>

### Arquitectura y Herramientas

![Git](https://img.shields.io/badge/Git-111827?style=for-the-badge&logo=git&logoColor=F05032)
![GitHub](https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=FFFFFF)
![Turborepo](https://img.shields.io/badge/Turborepo-111827?style=for-the-badge&logo=turborepo&logoColor=FFFFFF)
![npm Workspaces](https://img.shields.io/badge/npm_Workspaces-111827?style=for-the-badge&logo=npm&logoColor=CB3837)
![Clerk](https://img.shields.io/badge/Clerk-111827?style=for-the-badge&logo=clerk&logoColor=6C47FF)
![Row Level Security](https://img.shields.io/badge/Row_Level_Security-111827?style=for-the-badge&logo=supabase&logoColor=3ECF8E)

</div>

---

## Experiencia Técnica

He trabajado en proyectos relacionados con plataformas web y sistemas que requieren integración entre diferentes aplicaciones, servicios y bases de datos.

Algunas de las áreas en las que he trabajado incluyen:

- Desarrollo de aplicaciones con React y TypeScript.
- Desarrollo e integración de servicios con Node.js.
- Diseño e integración de APIs REST.
- Gestión de información con PostgreSQL y Supabase.
- Trabajo con bases de datos NoSQL mediante MongoDB.
- Implementación de autenticación y autorización.
- Gestión de permisos y políticas mediante Row Level Security.
- Organización de aplicaciones mediante arquitectura monorepo.
- Gestión de dependencias con npm Workspaces.
- Uso de Turborepo para organización y construcción de proyectos.
- Control de versiones y trabajo colaborativo mediante Git y GitHub.
- Implementación de trazabilidad y registro estructurado de procesos.

---

## Proyecto Destacado

### Trazabilidad y Arquitectura para Plataforma Digital de Seguros

**Proyecto de Titulación · Ingeniería Informática**

Durante mi proyecto de titulación trabajé en una plataforma tecnológica orientada a digitalizar el proceso de contratación de seguros.

La plataforma estaba compuesta por distintas aplicaciones y servicios que participaban en etapas como la simulación de un seguro, la generación de una cotización, la contratación, el pago y finalmente la emisión de documentación asociada.

Uno de los principales desafíos era que esta información se encontraba distribuida entre distintos procesos y sistemas, lo que dificultaba reconstruir de forma clara qué había ocurrido durante una operación específica.

Mi trabajo se concentró principalmente en dos áreas: **trazabilidad de procesos** y **mejora de la arquitectura del ecosistema de aplicaciones**.

---

### Trazabilidad de procesos

El primer desafío consistía en poder reconstruir de forma ordenada el recorrido realizado por un usuario durante el proceso de contratación.

Antes de la implementación, la información necesaria para analizar una operación podía encontrarse distribuida entre diferentes aplicaciones, registros y servicios. Esto hacía más complejo investigar incidencias, comprobar qué acciones se habían ejecutado o reunir evidencia de una operación.

Para resolver este problema trabajé en la implementación de un sistema de trazabilidad que permitiera registrar los principales eventos generados durante cada etapa del proceso.

El flujo podía seguir una estructura similar a:

```text
Sesión
   ↓
Simulación
   ↓
Cotización
   ↓
Contratación
   ↓
Orden de pago
   ↓
Pago
   ↓
Emisión de certificado
