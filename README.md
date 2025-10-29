# Sistema de Gestión de Compras en Excel

Este proyecto —**proyectoPortafolio.xlsm**— es una solución de **automatización en Excel** que permite registrar y analizar compras en tiempo real mediante un **Dashboard dinámico e interactivo**.  
Fue desarrollado con **macros grabadas, validaciones de datos, fórmulas avanzadas y tablas dinámicas**, logrando una experiencia completamente automatizada y sin necesidad de código manual.

---

## Estructura general del proyecto

El archivo cuenta con **4 hojas principales**, cada una con una función específica dentro del flujo del sistema:

| Hoja | Descripción |
|--------|--------------|
| **Compras**   | Hoja principal del sistema. Permite registrar compras, controlar existencias y evitar errores como comprar productos agotados. |
| **Productos**   | Base de datos de productos con cantidades iniciales y restantes. Se actualiza automáticamente al registrar nuevas compras. |
| **Trabajadores**   | Registro de empleados vinculados con las compras, útil para análisis de desempeño y trazabilidad. |
| **Dashboard**   | Panel visual que resume toda la información con tablas dinámicas, métricas y fórmulas avanzadas. |

---

## Funcionalidades principales

- **Registro automático de compras** con validaciones inteligentes (evita comprar productos agotados).  
- **Actualización dinámica** de cantidades de productos.  
- **Dashboard interactivo** que muestra:
  - Producto más comprado  
  - Total de compras realizadas  
  - Cantidades restantes  
  - Gráficos y métricas clave en tiempo real  
- **Botones personalizados** para ejecutar macros grabadas.  
- **Código VBA adicional** para **refrescar automáticamente las tablas dinámicas** al ingresar nuevos datos.  

---

## Aspectos técnicos

- **Macros grabadas (VBA)** para automatizar procesos.  
- **Validaciones de datos** para control de errores.  
- **Tablas dinámicas** con segmentadores para análisis visual.  
- **Fórmulas avanzadas**: `MAX()`, `CONCATENAR()`, `BUSCARX()`, entre otras.  
- **Conexión entre hojas** mediante referencias dinámicas para el control de existencias.  

---

## Objetivo del proyecto

El objetivo principal fue **automatizar el flujo de gestión de compras** en un entorno de Excel, conectando múltiples hojas de datos y mostrando **resúmenes automáticos en tiempo real** a través del Dashboard.  
Esto permite reducir tareas manuales y mejorar la toma de decisiones mediante visualizaciones rápidas y precisas.

---

## Enfoque técnico y aprendizajes

Durante el desarrollo del proyecto se aplicaron principios de **automatización sin código manual**, priorizando el uso de:
- Macros grabadas.  
- Fórmulas conectadas entre hojas.  
- Validaciones lógicas.  
- Un único módulo de VBA para refrescar dinámicamente las tablas.  

Este enfoque demuestra que **Excel puede funcionar como una pequeña aplicación interactiva** cuando se combinan correctamente sus herramientas de automatización.

---

## 📸 Vista previa (opcional)
- Formula para calculo de productos restantes
<img width="822" height="73" alt="image" src="https://github.com/user-attachments/assets/ec31fb2b-f701-4e43-8d25-bfd9ea844a2c" />

- Codigo VBA para refrescar tablas dinamicas automaticamente
<img width="452" height="124" alt="image" src="https://github.com/user-attachments/assets/4c736034-c9da-49e7-90f2-e6f11580d425" />

- Muestra del dashboard (Datos no reales solo ejemplos)
<img width="1857" height="603" alt="image" src="https://github.com/user-attachments/assets/a0900f95-b67f-4c17-9b1f-5025a85fa3cd" />

---

## 🧾 Autor

**Desarrollado por:** *Manuel Ramos*  
**Lenguaje principal:** Excel VBA / Macros  
**Archivo:** `proyectoPortafolio.xlsm`

---

## 💬 Nota final

Este proyecto forma parte de mi portafolio profesional y refleja mi capacidad para **automatizar procesos administrativos y analíticos usando Excel**, combinando lógica, estructura y visualización en una misma herramienta.

> 📘 *Este README fue elaborado con apoyo de ChatGPT para la redacción y presentación profesional del contenido.*

---
