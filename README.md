# 📞 Análisis de Tarifas - Megaline
Análisis de ingresos por planes prepago con Python y pruebas estadísticas

## 📌 Introducción
Megaline, un operador de telecomunicaciones, ofrece dos planes de prepago: **Surf** y **Ultimate**. El objetivo es determinar cuál de los dos planes genera más ingresos promedio, ayudando así al departamento comercial a enfocar sus campañas publicitarias.

Este análisis se basa en los datos de 500 clientes e incluye su uso mensual de minutos, mensajes SMS y datos móviles.

## 🎯 Problema de negocio
Las tarifas móviles generan ingresos distintos dependiendo del comportamiento del usuario. Megaline necesita saber:

- Qué plan aporta más ingresos en promedio
- Cómo varía el uso de servicios por tarifa
- Si hay diferencias regionales en ingresos

## 🔍 Objetivos del proyecto
✔ Calcular uso mensual (minutos, SMS, datos) por usuario  
✔ Estimar ingresos mensuales con base en excedentes  
✔ Comparar Surf vs. Ultimate mediante visualizaciones  
✔ Probar hipótesis estadísticas sobre ingresos  

## ❓ Preguntas clave
- ¿Qué tarifa es más rentable en promedio?
- ¿Cuánto consumen los usuarios por mes según su tarifa?
- ¿Existen diferencias de ingreso por región?
- ¿Cuál es la variabilidad de consumo entre usuarios?

## 📊 Métricas clave
📌 Por usuario:
- Minutos por mes
- SMS por mes
- MB de datos por mes
- Ingreso mensual estimado

📌 Por tarifa:
- Promedio y desviación estándar de ingresos
- Distribución del consumo por tipo de servicio

📌 Estadísticas:
- Prueba t entre tarifas
- Prueba t entre regiones (NY-NJ vs. otros)

## 🗂 Descripción del conjunto de datos
5 archivos CSV con información de usuarios y consumo durante 2018.

- `megaline_users.csv` — Datos de los clientes
- `megaline_calls.csv` — Llamadas por usuario
- `megaline_messages.csv` — SMS enviados
- `megaline_internet.csv` — Uso de internet (MB)
- `megaline_plans.csv` — Detalles de cada tarifa

## ⚙️ Proceso de análisis
📌 Realizado en Python con Pandas, Matplotlib, NumPy y SciPy

### Paso 1: Revisión y carga de datos
✔ Carga de 5 archivos  
✔ Conversión de tipos de datos y fechas  
✔ Limpieza y tratamiento de valores faltantes

### Paso 2: Ingeniería de características
✔ Agregación mensual por usuario  
✔ Cálculo de ingresos según condiciones de cada plan  
✔ Redondeo conforme a reglas de facturación

### Paso 3: Análisis exploratorio
✔ Histogramas de consumo  
✔ Estadísticas por plan  
✔ Visualización de distribuciones

### Paso 4: Pruebas estadísticas
✔ Comparación de ingresos entre tarifas  
✔ Comparación de regiones (NY-NJ vs. otras)  
✔ Justificación de hipótesis y valor alfa

## 📁 Estructura del repositorio
📂 data  
 └── megaline_users.csv  
 └── megaline_calls.csv  
 └── megaline_messages.csv  
 └── megaline_internet.csv  
 └── megaline_plans.csv  

📂 notebooks  
 └── Proyecto_Sprint5_FINAL.ipynb  

📂 insights  
 └── summary.md  

## 📬 Contacto
📧 Correo: jessica.elizondo.t@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/jessica-elizondo-t
