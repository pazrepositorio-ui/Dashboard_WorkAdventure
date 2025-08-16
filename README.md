# 🚴 Visualizando el Rendimiento de Adventure Works Cycles (AWC) con Power BI

Este proyecto integrador tiene como objetivo diseñar y desarrollar un reporte interactivo en Power BI para analizar en profundidad las ventas, costos y rentabilidad de **Adventure Works Cycles (AWC)**. Surge ante la necesidad de la empresa de contar con indicadores confiables y visuales que faciliten la toma de decisiones estratégicas basadas en datos.

👩‍💻 Autora: María Paz Camino  
📅 Año: 2024  
🎓 Proyecto Final – Analista de Datos  

---

## 📌 Objetivos del Proyecto

- Mejorar la calidad y estructura de los datos utilizados por AWC.
- Construir un modelo de datos relacional optimizado.
- Implementar métricas clave en DAX para analizar rendimiento comercial.
- Diseñar un tablero visual e interactivo que sintetice insights estratégicos.

---

## 🔄 Etapas de Desarrollo

### 1. **Calidad y Limpieza de Datos**
- Restauración de base `AdventureWorksDW2019` en SQL Server.
- Conexión e integración de tablas desde SQL y Excel.
- Limpieza en Power Query: columnas innecesarias eliminadas, encabezados corregidos, valores nulos tratados, uniones para enriquecer tablas como `DimCustomer`, `DimProduct`, `DimGeography`, etc.

### 2. **Modelo Relacional y Mockup**
- Modelo estrella estructurado: tabla de hechos `FactInternetSales` y dimensiones como `DimProduct`, `DimCustomer`, `DimDate`, etc.
- Combinación de tablas geográficas para simplificar relaciones.
- Desarrollo del Mockup con visualizaciones estratégicas (formato Z, KPIs, mapas, segmentadores).

### 3. **Métricas y DAX**
- Creación de medidas organizadas por carpetas:
  - Medidas Financieras (ingresos, utilidad bruta/neta, COGS, márgenes, ratios)
  - Medidas Temporales (actual vs LY, acumulados, promedios móviles)
  - Medidas Geográficas (por país/ciudad)
- Implementación de parámetros y grupos de cálculo como `Par_MedidasUSA`, `Par_Medidas`, `Variación_Tiempo`.

### 4. **Diseño del Dashboard Final**
- Página 1: **Análisis Financiero** (tarjetas, medidores, gráficos de columnas, mapas).
- Página 2: **Análisis USA** (tabla detallada por ciudad y provincia, segmentadores).
- Página 3: **Análisis Serie Temporal** (ventas mensuales, fines de semana, promedios móviles).
- Navegación interactiva mediante bookmarks y segmentadores.

---

## 📊 Resultados Clave

- **Ingresos totales:** $29 millones  
- **Utilidad neta:** $9 millones  
- **Producto estrella:** Bicicletas (95% de las unidades)  
- **Mercado líder:** EE.UU. (31% de facturación)  
- **Meses con estacionalidad alta:** Noviembre y diciembre  
- **43% de ventas se dan en fines de semana**

---

## 📚 Recomendaciones

- **Campañas enfocadas en fines de semana y fin de año**
- **Ampliar la oferta de productos más allá de bicicletas**
- **Profundizar análisis por estado en EE.UU.**
- **Explorar modelos predictivos y terminar el análisis de 2014**

---

## 🤔 Reflexión Final

Este proyecto me permitió aplicar integralmente todo lo aprendido en la carrera: desde SQL y Power Query hasta DAX y diseño visual en Power BI. A lo largo del proceso enfrenté desafíos técnicos que resolví con criterio analítico y herramientas apropiadas. Sin dudas, consolidé habilidades clave para desempeñarme como Analista de Datos en entornos reales.

---

## 🗂 Archivos Incluidos

- 📄 `Informe_AWC_PowerBI.pdf`: Informe con desarrollo completo del proyecto.
- 📊 `dashboard_AWC.pbix`: Archivo Power BI (si lo subís al repositorio).

---

## 🌐 Contacto

- 📧 pazrepositorio@gmail.com  
- 🔗 [LinkedIn](https://www.linkedin.com/in/pazcamino)  
- 💼 [GitHub](https://github.com/pazcaminoDA)

---

_Gracias por visitar este proyecto. Tu feedback es bienvenido._
