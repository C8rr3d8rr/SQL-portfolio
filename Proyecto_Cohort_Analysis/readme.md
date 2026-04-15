# 📊 Cohort Analysis en SQL

---

## 🌟 Introducción

✨ Este proyecto muestra cómo realizar un **Cohort Analysis** utilizando **SQL**, con el objetivo de analizar la **retención de clientes a lo largo del tiempo**.

Un análisis de cohortes permite agrupar usuarios según su **primera interacción (primera compra)** y medir cómo se comportan en periodos posteriores.

---

## 🎯 Objetivo del Proyecto

🚀 Transformar datos transaccionales en **insights de negocio**, permitiendo entender:

* 📉 Cuándo se pierden los clientes
* 📈 Qué tan fuerte es la retención
* 🧠 Cómo mejorar la fidelización

---

## 🧠 ¿Qué es un Cohort Analysis?

📊 Es una técnica que agrupa usuarios en **cohortes** (grupos) según un evento inicial.

En este caso:

* Cohorte = Mes de primera compra
* Métrica = Retención de clientes por mes

---

## 🗄️ Estructura de los Datos

El dataset incluye:

* 📅 Fecha
* 🧑‍💼 Cliente
* 💳 Producto
* 📊 Métricas de negocio (TPV, transacciones, utilidad)

---

## ⚙️ Metodología

El análisis se construye en 4 pasos clave:

1. 🥇 Identificar la primera compra de cada cliente
2. 📅 Asignar cada cliente a su cohorte (mes)
3. 🔢 Calcular la diferencia de meses desde su primera compra
4. 📊 Medir cuántos clientes regresan en cada periodo

---

## 📈 Resultado Esperado

Obtendrás una tabla como esta:

| Cohorte | Mes 0 | Mes 1 | Mes 2 | Mes 3 |
| ------- | ----- | ----- | ----- | ----- |
| 2025-01 | 100%  | 60%   | 45%   | 30%   |
| 2025-02 | 100%  | 55%   | 40%   | 25%   |

👉 Esto permite visualizar la **retención de clientes** en el tiempo.

---

## 🔥 Valor de Negocio

Este análisis permite:

* 📉 Detectar pérdida de clientes (churn)
* 📊 Evaluar la calidad de adquisición
* 🎯 Mejorar estrategias de retención

---

## 🚀 Uso del Proyecto

1. Ejecutar la creación de la tabla
2. Generar los datos simulados
3. Ejecutar las consultas SQL
4. Analizar la retención por cohorte

---

## 🧠 Enfoque

💡 Este proyecto demuestra cómo **SQL puede ser utilizado más allá de consultas básicas**, convirtiéndose en una herramienta clave para análisis estratégico.

---

🔥 *"Retener clientes es más rentable que adquirir nuevos"* 🔥
