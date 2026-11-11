<div align="center">

<div align="center">

# `> DarkSoft04`
### **Construyendo soluciones de software eficientes y escalables**

</div>

<img width="380" alt="Trans Fast Banner" src="https://github.com/user-attachments/assets/8aca337a-0dc8-4732-99bc-a4c65489cc72">

# 🚍 Trans Fast.Inc — Sistema ERP de Transporte

**Plataforma empresarial modular para la gestión centralizada de flotas, despacho automatizado y monitoreo de frecuencias en el transporte público urbano.**

[![Estado del Proyecto](https://img.shields.io/badge/Estado-En_Desarrollo-00A86B?style=for-the-badge&logo=github)](https://github.com/)
[![Arquitectura](https://img.shields.io/badge/Arquitectura-ERP_Modular-0052CC?style=for-the-badge&logo=databricks)](https://github.com/)
[![Base de Datos](https://img.shields.io/badge/Base_de_Datos-Relacional_(SQL)-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)](https://github.com/)
[![Institución](https://img.shields.io/badge/PUCE-Sistemas_de_Información-009CDE?style=for-the-badge)](https://www.puce.edu.ec/)
[![Versión](https://img.shields.io/badge/Versión-1.0.0-6C757D?style=for-the-badge)](https://github.com/)
[![Licencia](https://img.shields.io/badge/Licencia-MIT-F5A623?style=for-the-badge)](LICENSE)

<br />

[📖 Descripción](#-descripción-general) •
[✨ Características](#-características-principales) •
[📸 Demo](#-capturas-de-pantalla--demo) •
[🛠️ Stack](#-stack-tecnológico-y-componentes) •
[🏗️ Arquitectura](#️-arquitectura-y-estructura-del-proyecto) •
[🚀 Instalación](#-instalación-y-configuración) •
[💡 Uso](#-ejemplos-de-uso) •
[🗺️ Roadmap](#️-roadmap) •
[🤝 Contribución](#-contribución-y-autores)

</div>

---

## 📖 Descripción General

**Trans Fast.Inc** es un Sistema de Planificación de Recursos Empresariales (**ERP**) diseñado específicamente para cooperativas y operadoras de transporte público urbano. Su objetivo principal es unificar los procesos administrativos y operativos sobre una fuente única de datos compartida, eliminando los silos de información y la gestión manual basada en hojas de cálculo aisladas.

### 🎯 Problemáticas que Resuelve
* **Ausencia de horarios fijos e irregularidad de frecuencias:** Mitiga la circulación aleatoria de unidades, reduciendo los tiempos de espera prolongados para los ciudadanos y evitando la superposición de buses en una misma ruta.
* **Gestión fragmentada del transporte y personal:** Reemplaza los procesos manuales aislados mediante la sincronización en tiempo real entre la disponibilidad de unidades, los turnos de los conductores y el estado mecánico de la flota.
* **Carencia de métricas y trazabilidad:** Proporciona un registro sistematizado de tiempos de recorrido y disponibilidad operativa, permitiendo a los administradores tomar decisiones basadas en datos para ajustar la oferta de buses durante las horas pico.

### 👥 ¿A quién va dirigido?
Está orientado a **cooperativas de transporte urbano, gerentes de operaciones, despachadores, departamentos de recursos humanos y jefes de taller mecánico** que buscan optimizar sus recursos internos y sentar las bases tecnológicas para ofrecer previsibilidad y horarios fijos a los usuarios del transporte público.

---

## ✨ Características Principales

* 🚌 **Módulo de Operaciones y Despacho (Logística de Flota):** Planificación integral de rutas, circuitos y paradas, asignación automatizada de unidades disponibles, monitoreo de frecuencias de salida y control estricto de tiempos de recorrido.
* 👨‍✈️ **Módulo de Recursos Humanos y Gestión de Personal:** Registro centralizado de conductores y personal operativo, validación de vigencia de licencias y documentación habilitante, programación automatizada de turnos rotativos, control de asistencia e historial de desempeño por despacho.
* 🔧 **Módulo de Mantenimiento y Soporte Mecánico (Gestión de Activos):** Control del ciclo de vida técnico de las unidades mediante órdenes de trabajo para mecánicos de planta, programación de mantenimientos preventivos por kilometraje y registro de reparaciones correctivas.
* 🔄 **Bloqueo Operativo Interdepartamental en Tiempo Real:** Integración nativa entre módulos que inhabilita y bloquea automáticamente en el área de Operaciones cualquier unidad que ingrese a taller o cuyo conductor no cuente con documentación vigente.
* 🗄️ **Integridad Referencial Unificada:** Arquitectura respaldada por una base de datos relacional única que garantiza la consistencia de los datos entre unidades, conductores, rutas, paradas y mantenimientos.

---

## 📸 Capturas de Pantalla / Demo

| Panel de Control y Despacho (Operaciones) | Gestión de Turnos y Conductores (RRHH) |
| :---: | :---: |
| ![Dashboard de Operaciones](ruta/a/captura_operaciones.png) | ![Módulo de Recursos Humanos](ruta/a/captura_rrhh.png) |
| *Monitoreo de frecuencias, rutas activas y tiempos por parada.* | *Control de licencias vigentes y asignación de turnos rotativos.* |

| Control de Taller y Activos (Mantenimiento) | Modelo Relacional Unificado |
| :---: | :---: |
| ![Módulo de Mantenimiento](ruta/a/captura_mantenimiento.png) | ![Diagrama de Base de Datos](ruta/a/captura_bd.png) |
| *Órdenes de trabajo y bloqueo automático de unidades en taller.* | *Estructura de entidades con integridad referencial en tiempo real.* |

---

## 🛠️ Stack Tecnológico y Componentes

> [!NOTE]
> El documento de definición establece la arquitectura funcional, el modelado de procesos y el diseño de base de datos relacional del ERP. Completa los placeholders `[COMPLETAR_...]` con las herramientas específicas elegidas para la implementación técnica de tu grupo.

| Capa / Componente | Especificación del Proyecto | Tecnología / Herramienta |
| :--- | :--- | :--- |
| **Arquitectura de Software** | Sistema ERP Modular Integrado | `[COMPLETAR_ARQUITECTURA_EJ_MVC_O_CLIENTE_SERVIDOR]` |
| **Motor de Base de Datos** | Base de Datos Relacional Única (Integridad Referencial) | `[COMPLETAR_SGBD_EJ_POSTGRESQL_ORACLE_MYSQL]` |
| **Backend / Lógica de Negocio** | Sincronización interdepartamental y reglas de despacho | `[COMPLETAR_LENGUAJE_O_FRAMEWORK_BACKEND]` |
| **Frontend / Interfaz de Usuario** | Paneles para Operaciones, RRHH y Taller Mecánico | `[COMPLETAR_TECNOLOGIA_FRONTEND]` |
| **Modelado de Datos y Procesos** | Estructuración de entidades y flujos de trabajo | `[COMPLETAR_HERRAMIENTA_CASE_EJ_POWERDESIGNER]` |

---

## 🏗️ Arquitectura y Estructura del Proyecto

### Flujo de Integración Interdepartamental y Modelo de Dominio (Mermaid.js)

El siguiente diagrama representa cómo interactúan las tres áreas de negocio sobre la base de datos relacional única y las entidades centrales definidas en el sistema:

```mermaid
graph TD
    subgraph "Áreas de Negocio del ERP Trans Fast.Inc"
        OP[🚌 Área de Operaciones y Despacho<br/>Logística de Flota]
        RH[👨‍✈️ Área de Recursos Humanos<br/>Gestión de Personal]
        MT[🔧 Área de Mantenimiento y Soporte<br/>Gestión de Activos]
    end

    subgraph "Fuente Única de Datos Compartida (BD Relacional)"
        DB[(🗄️ Base de Datos Centralizada)]
        E1[Entidad: Unidades de Transporte]
        E2[Entidad: Conductores]
        E3[Entidad: Rutas y Circuitos]
        E4[Entidad: Paradas y Tiempos]
        E5[Entidad: Registros de Mantenimiento]
    end

    OP -->|Planifica y controla| DB
    RH -->|Valida licencias y turnos| DB
    MT -->|Registra órdenes de trabajo| DB

    MT -.->|Bloqueo automático de unidad en taller| OP
    RH -.->|Habilitación legal y operativa del conductor| OP

    DB --- E1
    DB --- E2
    DB --- E3
    DB --- E4
    DB --- E5
