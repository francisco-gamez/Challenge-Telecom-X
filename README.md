# 📈 Análisis de Evasión de Clientes – TelecomX

Este proyecto fue desarrollado como parte del desafío final del bootcamp de Data Science. El objetivo principal es identificar patrones que expliquen la **evasión de clientes (churn)** en una compañía de telecomunicaciones y ofrecer recomendaciones estratégicas basadas en los datos.

---

## 🧠 Objetivo

Analizar los datos de clientes de **TelecomX** para detectar:

- Características comunes de los clientes que abandonan la empresa.
- Variables que más influyen en la retención.
- Patrones de consumo, métodos de pago y servicios contratados que pueden predecir la evasión.
- Recomendaciones basadas en datos para reducir el churn.

---

## 🧰 Herramientas utilizadas

- **Python** (3.10)
- **Pandas** – Manipulación de datos
- **Seaborn & Matplotlib** – Visualización gráfica
- **Google Colab** – Entorno de desarrollo
- **Jupyter Notebook** – Estructura del proyecto
- **GitHub** – Control de versiones y publicación

---

## 📊 Estructura del proyecto

1. **Introducción**  
   Breve explicación del problema de churn en telecomunicaciones.

2. **Importación y limpieza de datos**  
   Se depuraron datos nulos, se ajustaron tipos y se crearon nuevas variables como `Cuentas_Diarias` y `Servicios_Activos`.

3. **Análisis exploratorio (EDA)**  
   - Comparación de abandono por tipo de contrato, servicios y métodos de pago.
   - Histograma y KDE por gasto diario.
   - Multipaneles temáticos con visualizaciones limpias y comparativas.

4. **Conclusiones**  
   Se identificó que el abandono está más presente en:
   - Clientes con contrato mensual.
   - Aquellos que abandonan antes de 10 meses.
   - Quienes usan fibra óptica, múltiples servicios digitales y pagan por *electronic check*.

5. **Recomendaciones**  
   Se proponen estrategias de retención como mejorar la experiencia temprana, personalizar servicios, revisar precios y reforzar el valor percibido.

---

## 🚀 Resultado esperado

Este proyecto permite detectar perfiles de riesgo y **tomar decisiones basadas en datos para reducir la evasión de clientes**, fortalecer la fidelización y mejorar la experiencia del usuario en empresas de telecomunicaciones.

---

## 👤 Autor

**Francisco Gámez**  
Bootcamp de Data Science – 2025  
Proyecto final – Alura Latam & Oracle Next Education  
📍 Querétaro, México

---

## 📎 Dataset

- [`TelecomX_Data.json`](https://raw.githubusercontent.com/francisco-gamez/Challenge-Telecom-X/refs/heads/main/TelecomX_Data.json) – Datos anonimizados de clientes con variables demográficas, financieras y de servicios.

---
