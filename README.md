# 📊 Azure Telemetry & Security Analysis (ADX / KQL)

Este repositorio contiene un conjunto de consultas analíticas desarrolladas en **Kusto Query Language (KQL)** para su uso en **Azure Data Explorer (ADX)** y Azure Log Analytics. 

El objetivo de estas consultas es proporcionar observabilidad avanzada, detectar anomalías de seguridad (Zero Trust) y monitorizar el rendimiento de la infraestructura en la nube.

## 🚀 Consultas Destacadas

* **`Security-Detect-BruteForce.kql`**: Identifica múltiples intentos fallidos de inicio de sesión seguidos de un acceso exitoso (posible ataque de fuerza bruta o credenciales comprometidas).
* **`Perf-VM-HighCPU-Alert.kql`**: Detecta máquinas virtuales en Azure que han mantenido un uso de CPU superior al 90% durante los últimos 30 minutos, ideal para la gestión proactiva de incidentes (ITSM).

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** KQL (Kusto Query Language)
* **Plataformas:** Microsoft Azure, Azure Data Explorer, Log Analytics Workspace
* **Casos de uso:** SecOps, FinOps, Monitorización de Rendimiento.

---
*Nota: Los datos y nombres de recursos en estas consultas son ejemplos genéricos para ilustrar la lógica de las consultas de telemetría corporativa.*
