# Soluciones-tecnol-gicas-del-Norte-S.A.
Soluciones tecnológicas del Norte S.A. es una empresa ficticia que se dedica a desarrollar software que solucionen problemas y necesidades reales en distintos ámbitos.

## Producto: Gamboard — Plataforma de Gestión y Presentación para Estudios Indie

> **Trabajo Práctico Integrador (TPI) — Organización Empresarial**  
> **Institución:** Universidad Tecnológica Nacional (UTN) — Tecnicatura Universitaria en Programación a Distancia (TUP AD)  
> **Alumno:** Facundo Ariel Molinas (DNI: 50.458.058)  
> **Comisión / Ciclo:** Ciclo Lectivo 2026  

---

### 1. Sobre la Empresa y el Producto

**Soluciones Tecnológicas del Norte S.A.** es una empresa tecnológica orientada al desarrollo de software SaaS (Software as a Service) de alto impacto.

Nuestro producto insignia es **Gamboard**, una solución web concebida para estudios de videojuegos independientes (indie). Gamboard centraliza el Game Design Document (GDD), tableros visuales de moodboards, gestión de tareas en sprints y compilación automatizada de Pitch Decks para inversores y publishers.

* **Modalidad Freemium:** Plan Free con funciones manuales esenciales y Plan Pro con **Smart Ingestion** (migración automática de proyectos vía `.ZIP`/`.7Z` mediante IA multimodal) y agentes silenciosos de auditoría lógica y benchmarking de mercado contra Steam y ArtStation.

---

### 2. Estructura y Trazabilidad del Proyecto (Entregas 1 a 4)

El desarrollo del proyecto integra formalmente las cuatro etapas curriculares:

* **[Entrega N.º 1: Enfoque Sistémico y Módulo de Negocio](docs/entregas/Entrega_1.pdf)**  
  * Modelado bajo la Teoría General de Sistemas (TGS): entradas, procesos, salidas, retroalimentación y límites.  
  * Planteamiento del Módulo de Facturación Electrónica y Cobros.
* **[Entrega N.º 2: Planeamiento Estratégico y Cronograma](docs/entregas/Entrega_2.pdf)**  
  * Matriz FODA cruzada de Gamboard.  
  * Cinco metas cuantitativas SMART y diagrama de Gantt operativo a 12 semanas.
* **[Entrega N.º 3: Diseño Organizacional y Datos](docs/entregas/Entrega_3.pdf)**  
  * Estructura orgánica piramidal lineal-staff (12 colaboradores).  
  * Diccionario de datos formal con 5 entidades (`ESTUDIO_USUARIO`, `PROYECTO_JUEGO`, `ELEMENTO_TABLERO`, `TAREA_SPRINT`, `FACTURA_SUSCRIPCION`).
* **[Entrega N.º 4: Procesos, Trabajo Colaborativo y Control](docs/entregas/Entrega_4.pdf)**  
  * Modelado formal de procesos en notación BPMN 2.0 (Pools, Lanes, Compuertas y Flujos de Mensaje).  
  * Configuración de control de versiones bajo GitHub Flow, Pull Requests y Code Review.  
  * Backlog Ágil con Historias de Usuario e indicadores de control/KPIs y gobernanza de IA.

---

### 3. Convenciones de Ingeniería y Gestión de Configuración

* **Estrategia de Ramificación :** Se utiliza **GitHub Flow**. La rama `main` representa la versión productiva y validada. Toda nueva funcionalidad se desarrolla en ramas descriptivas de tipo `feat/<nombre-funcionalidad>` y se integra exclusivamente mediante **Pull Requests** con revisión de pares obligatoria.
* **Convención de Commits:** Se aplica el estándar *Conventional Commits*:
  * `feat:` Nuevas funcionalidades del producto o modelo.
  * `docs:` Cambios o incorporaciones en la documentación.
  * `fix:` Correcciones o ajustes de procesos y schemas.
* **Estructura del Repositorio:**
  * `/diagramas`: Diagramas formales en formato estándar (`.bpmn` y `.png`).
  * `/docs`: Entregables académicos y documentación técnica de arquitectura.

---

### 4. Equipo de Desarrollo y Gobierno del Proyecto

* **Lead Product Owner & Dirección General:** Facundo Ariel Molinas
* **Organización:** Soluciones Tecnológicas del Norte S.A.
* **Contacto Institucional:** `tup.sied.utn.edu.ar`
