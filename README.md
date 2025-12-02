# snowflake-end2end-bi-project
Un proyecto end-to-end que integra Snowflake y Looker Studio para analizar la performance de agencias de cobranza. Incluye ingesta desde CSV, modelo estrella, vistas analíticas y dashboards ejecutivos con métricas de recupero, eficiencia, contactabilidad y calidad operativa.

# ❄️ Snowflake End-to-End BI Project  
### Recupero & Eficiencia Operativa – Snowflake + Looker Studio

![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![BI](https://img.shields.io/badge/Tech-Snowflake-blue)
![Looker Studio](https://img.shields.io/badge/Visualization-Looker%20Studio-blueviolet)
![SQL](https://img.shields.io/badge/Language-SQL-lightgrey)

---

## 📌 Descripción

Este proyecto implementa un pipeline **end-to-end** utilizando **Snowflake** como Data Warehouse y **Looker Studio** como herramienta de visualización.

A partir de datos sintéticos de gestión y pagos, se construye:

- Un **modelo estrella** (dimensiones + hechos)
- Proceso de **ingesta desde CSV** mediante un Stage interno
- **Vistas analíticas** optimizadas para BI
- Dashboards ejecutivos con métricas clave:
  - Recupero por agencia  
  - Eficiencia sobre stock  
  - Contactabilidad  
  - Promesas  
  - Volumen total de gestiones  
  - Calidad operativa mensual  

Este proyecto replica el tipo de ejercicio que suelen solicitar consultoras de Data & Analytics (PowerData, Globant, Accenture, etc.) para roles de **Data Engineer, Analytics Engineer o BI Developer**.

---

## 📚 Tabla de Contenidos

1. [Arquitectura General](#arquitectura-general)  
2. [Modelo Estrella](#modelo-estrella)  
3. [Ingesta de Datos](#ingesta-de-datos)  
4. [SQL del Modelo](#sql-del-modelo)  
5. [Vista Analítica Principal](#vista-analítica-principal)  
6. [Dashboards](#dashboards)  
7. [Capturas](#capturas)  
8. [Cómo reproducir el proyecto](#cómo-reproducir-el-proyecto)  
9. [Próximos pasos](#próximos-pasos)  

---

## 🏗️ Arquitectura General

Diagrama conceptual del flujo:

