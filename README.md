<div align="center">

# 📦 Mercado Libre - Módulo de Gestión de Pedidos y Envíos (OMS)

**Trabajo Práctico Integrador y Progresivo (TPI) - Entrega N.º 4**

</div>

---

## 📌 1. Descripción del Sistema y Contexto Organizacional

El presente proyecto modela e implementa de forma sistémica el **Módulo de Gestión de Pedidos y Envíos (Order Management System - OMS)** dentro del ecosistema de comercio electrónico y servicios logísticos de **Mercado Libre**. 

Bajo el marco de la **Teoría General de Sistemas (TGS)** y la **Gestión basada en Procesos (GbP)**, el OMS opera como un subsistema abierto, crítico y adaptativo que articula:

* 💳 **Pasarela de Pagos (Mercado Pago):** Verificación de solvencia financiera y scoring antifraude.
* ⚙️ **Backend Transaccional (OMS Core):** Sincronización en tiempo real de inventarios en almacén, facturación digital y enrutamiento inteligente.
* 🚚 **Fulfillment y Distribución (Mercado Envíos Full):** Coordinación operativa de *picking*, *packing*, etiquetado y despacho físico de paquetes.

---

## 🛠️ 2. Arquitectura Tecnológica y Entorno

| Componente | Tecnología / Herramienta | Descripción |
| :--- | :--- | :--- |
| **Frontend** | ![React] ![Tailwind] | Interfaz de usuario para gestión y visualización de pedidos. |
| **Backend** | ![Python] | Lógica de negocio y APIs de pedidos e inventario. |
| **Base de Datos** | ![PostgreSQL] | Modelo relacional estructurado mediante Diccionario de Datos. |
| **Integración Logística** | **APIs RESTful** | Conexión con Mercado Envíos y trazabilidad de *tracking*. |
| **Modelado de Procesos** | ![Bizagi] | Modelado BPMN 2.0 del flujo transaccional. |
| **Control de Versiones** | ![Git] ![GitHub]| Trabajo colaborativo y control de cambios. |
| **Gestión Ágil** | ![Projects] | Seguimiento del Backlog del TPI. |

---

## 🌿 3. Estrategia de Ramas (Gitflow Simplificado)

Para mantener la estabilidad de la rama principal de producción y asegurar la trazabilidad del desarrollo, se implementa una política estructurada de ramas:

* `main`: Rama protegida y estable que contiene la versión consolidada y funcional del proyecto.
* `feature/bpmn-order-process`: Rama secundaria destinada al modelado y documentación del flujo BPMN de despacho.
* `docs/tpi-entrega4`: Rama de trabajo colaborativo donde se redactaron las especificaciones técnicas, historias de usuario y estándares de control.

---

## 👥 4. Integrantes 

| **Luciana Calisaya** |

---

## 🔗 5. Enlaces Rápidos y Documentación

* 📋 **Tablero de Gestión Ágil:** [Ver Tablero en GitHub Projects](https://github.com/lucianacalisaya/organizacion_empresarial_UTN/projects)
* 📄 **Informe Consolidado (PDF):** Disponible en la carpeta [`/docs`](./docs) de este repositorio.

---

<div align="center">
  <b>Tecnicatura Universitaria en Programación a Distancia (TUP AD)</b><br>
  Universidad Tecnológica Nacional (UTN) - Facultad Regional<br>
  <i>Ciclo Lectivo 2026</i>
</div>
