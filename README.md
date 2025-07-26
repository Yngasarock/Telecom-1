# Telecom-1

# 📉 TelecomX LATAM – Análisis de Evasión de Clientes (Churn)

Este repositorio contiene un análisis exploratorio de datos (EDA) del comportamiento de **churn** (cancelación de clientes) para la empresa **Telecom X**, una compañía de telecomunicaciones en LATAM. El objetivo es identificar los factores que influyen en la pérdida de clientes y proponer recomendaciones estratégicas para reducir la evasión.

---

## 📁 Contenido

- `TelecomX_LATAM.ipynb`: Notebook con el análisis completo (carga de datos, limpieza, EDA, conclusiones y recomendaciones).
- `data/`: Carpeta con los datos utilizados en formato JSON (si deseas descargar una copia local).
- `images/`: Carpeta opcional para incluir gráficas del análisis.

---

## 🔍 Objetivo del Proyecto

TelecomX enfrenta una alta tasa de cancelación de clientes. El reto consiste en:

- Analizar el dataset de clientes y sus características contractuales.
- Identificar patrones de comportamiento asociados a la evasión.
- Proponer recomendaciones estratégicas basadas en los hallazgos.

---

## 📊 Análisis Exploratorio (EDA)

El EDA realizado incluye:

- Limpieza de datos y tratamiento de estructuras anidadas.
- Análisis demográfico (género, edad, dependientes).
- Tiempo de permanencia (`tenure`) y su relación con el churn.
- Tipos de servicios contratados y cancelación.
- Facturación (mensual, por día y total) y métodos de pago.
- Visualizaciones clave para interpretar patrones de abandono.

---

## 📌 Conclusiones Principales

- El churn está asociado a factores como **bajo tiempo de permanencia**, **contratos mensuales** y **pocos servicios contratados**.
- El método de **pago automático** se relaciona con mayor evasión, contrario a lo esperado.
- **Clientes sin soporte técnico o servicios adicionales** presentan mayor riesgo de cancelación.

---

## 🎯 Recomendaciones Estratégicas

- 📦 Promover paquetes combinados con beneficios exclusivos.
- 🕒 Enfocar esfuerzos en clientes con menos de 12 meses de permanencia.
- 🛠️ Mejorar atención al cliente y resolver puntos de fricción en pagos automáticos.
- 🔍 Desarrollar modelos predictivos para segmentar y anticiparse al churn.
- 💬 Implementar encuestas de satisfacción proactivas.

---

## 🧠 Tecnologías Utilizadas

- `Python`
- `Pandas`
- `Matplotlib` & `Seaborn`
- `Jupyter Notebook`
- API para descarga de datos (`requests`)

---

## 🔧 Instalación y dependencias

### 🔹 Requisitos previos

- Python 3.8 o superior
- Git (opcional)

### 🔹 Clonar el repositorio

```bash
git clone https://github.com/Yngasarock/Telecom-1.git
