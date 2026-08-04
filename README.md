# 📊 Análisis Comercial Andes Capital Real State

## 🇪🇦 Español

## 🎯 Descripción del Proyecto
Andes Retail Group es una empresa de retail con operaciones en Perú, Chile y Colombia, que comercializa productos en cuatro categorías:
🖥️ Electrónica
👕 Ropa
⚽ Deportes
🏠 Hogar
La dirección ejecutiva necesita un dashboard interactivo que permita entender el desempeño comercial de los años 2024–2025.

El análisis realizado se llevo a cabo en Power BI en 5 etapas: Calidad de datos, Tranformación con Power Query, Diseño y planificación del Dashboard, Crear visualizaciones, Narrativa con Modelo SCQA.

## 🔍 Pregunta de Investigación
¿Cómo ha evolucionado el ingreso total entre 2024 y 2025?
¿Qué segmentos de clientes aportan mayor ingreso y rentabilidad?
¿Qué categorías de producto tienen mayor impacto en el negocio?
¿Existen diferencias relevantes entre países o regiones?
¿Qué patrones temporales se observan a lo largo del año?
¿Dónde podrían existir oportunidades de mejora comercial?

## 📋 Objetivos
Realizar una limpieza adecuada de los datos para garantizar la validez de los mismos en los análisis posteriores.
Identificar KPIs relevantes para las preguntas de negocio.
Creación de medidas con DAX.
Comunicar los hallazgos en un dashboard en Power BI

## 🗂️ Dataset
Fuente: Andes_Retail_Group_2024_2025.csv
Tamaño: 8,500 registros de ventas

## **Variables Analizadas**
| Variable | Tipo | Descripción |
|---------|-------------|-------------------|
| unidades_vendidas	| Numérica | Cantidad de unidades vendidas |
| ingresos | Numérica |	Total vendido (precio × unidades) |
| pais | Categórica	| País donde se realizó la venta |
| estacion	| Categórica	| Temporada del año según el hemisferio sur|
| segmento_cliente | Categórica | Tipo de cliente según valor comercial |
| canal_venta	| Categórica	| Canal utilizado para la venta |
| categoria_producto | Categórica	| Tipo de producto vendido |
| fecha_pedido	| Fecha	| Fecha en que se realizó la venta |

## 🛠️ Metodología
Limpieza de datos.

Transformación en Power Query.

Herramientas Utilizadas: *Power BI Desktop o Tableau, Visualizaciones nativas (barras, líneas, mapas, tarjetas KPI), Modelo de narrativa SQCA.*

## 🔄 Etapas del Análisis
Este proyecto sigue un flujo estructurado de análisis dividido en 5 etapas principales:

| Etapa	 | Descripción | Resultado Esperado |
|---------|-------------|-------------------|
| 1. Calidad de datos | Cargar y explorar el dataset | Entender estructura, columnas, tipos, métricas clave |
| 2. Tranformación con Power Query | Preparar los datos para el análisis | Estándarizar formatos, corregirr tipo de datos y crear columnas descriptivas | 
| 3. Diseño y planificación del Dashboard | Escoger KPIs y gráficos que resuelvan preguntas de negocio | Tener filtrada la información relevante para stakeholders|
| 4. Crear visualizaciones | Diseñar el dashboard | Tener un dashboard interactivo  con jerarquía visual y fácil de leer |
| 5. Narrativa con Modelo SCQA | Realizar una narrativa ejecutiva clara y breve |	Un mensaje que refuerza lo mostrado en el dashboard |
 
### 🎯 Enfoque del Análisis
Naturaleza: Descriptivo (KPIs de negocio)
Variable objetivo: Revenue y profit, tipo de cliente y categoría de producto
Tipos de relaciones analizadas: Comportamiento del usuario por tipo de cliente, ingresos por categoría de producto y país, y comparativo de ingresos YoY.

### 🗂 Producto Final
Un reporte de rentabilidad y retención que combina:

✅ Evidencia visual (Dashboard interactivo en PowerBI)

✅ Evidencia numérica (KPIs de performance)

✅ Implicaciones de negocio accionables

### **📊 Resultado del Análisis**
- Se identifica un patrón de ventas claramente estacional, con picos en verano (diciembre-enero) y caídas pronunciadas en invierno (junio-agosto).
- Se observa una disminución general de ingresos de 2024 a 2025.
- Existe una revés en el comportamiento de compra: en verano dominan las ventas altas (≥1,000), y durante otoño, primavera e invierno aumentan las ventas bajas (<$1,000).

## **🖋 Conclusiones y recomendaciones**
Se identificó una doble problemática:
- Estacionalidad esperada: Picos en verano (dic-ene) y caídas en invierno (jun-ago)
- Tendencia decreciente: Disminución general de ingresos de 2024 a 2025.

Analizando los datos se descubrieron los siguientes hallazgos por segmento de cliente:
- Clientes Premium y Estándar: Aportan mayor valor, y comportamiento similar en las diferentes épocas del año.
- Clientes Económico: Segmento con mayor potencial sin explotar.

Se recomienda
• Activar segmento Económico durante todo el año
• Estrategias específicas para mantener ventas altas en temporadas frías
• Enfoque en Electrónica y Deportes (categorías líderes)

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:
[Google Colab](https://colab.research.google.com/drive/1oIXoxRuottmAUMYMLIrVUlYH0fOTfCCE?usp=sharing)

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/S11 Proyecto_InmobiliarioGrupoAndes.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/`

# 📊 Commercial Performance Analysis - Andes Retail Group

## 🇬🇧 English

## 🎯 Project Description
Andes Retail Group is a retail enterprise with operations in Peru, Chile, and Colombia, commercializing products across four core categories:
🖥️ Electronics
👕 Apparel
⚽ Sports
🏠 Home
Executive leadership required an interactive dashboard to evaluate commercial performance across the 2024–2025 period.
The analysis was executed in Power BI across 5 main stages: Data Quality Check, Power Query Transformation, Dashboard Planning & Layout, Data Visualization, and Executive Storytelling using the SCQA Framework.

## 🔍 Research Questions
- How has total revenue evolved between 2024 and 2025?
- Which customer segments contribute most to overall revenue and profitability?
- Which product categories exert the strongest business impact?
- Are there significant variations across countries or geographic regions?
- What seasonal patterns emerge throughout the year?
- Where do key commercial optimization opportunities exist?

## 📋 Objectives
- Perform thorough data cleaning to guarantee data integrity for downstream analysis.
- Identify core business KPIs aligned with executive research questions.
- Engineer analytical metrics using DAX.
- Communicate findings via an interactive Power BI dashboard.

## 🗂️ Dataset
Source: `Andes_Retail_Group_2024_2025.csv`  
Size: 8,500 sales transactions  

## **Analyzed Variables**

| Variable | Type | Description |
| :--- | :--- | :--- |
| unidades_vendidas | Numerical | Number of units sold |
| ingresos | Numerical | Total revenue generated (price × units) |
| pais | Categorical | Country where the transaction occurred |
| estacion | Categorical | Season of the year based on the Southern Hemisphere |
| segmento_cliente | Categorical | Customer category based on commercial value |
| canal_venta | Categorical | Acquisition channel used for the sale |
| categoria_producto | Categorical | Product category sold |
| fecha_pedido | Date | Date when the order was placed |

## 🛠️ Methodology
Data Cleaning, ETL Transformations in Power Query.  
Tools Used: *Power BI Desktop / Tableau, Native Visualizations (bar charts, line charts, maps, KPI cards), SCQA Storytelling Framework.*

## 🔄 Analysis Stages
This project follows a structured analytical workflow divided into 5 main stages:

| Stage | Description | Expected Outcome |
| :--- | :--- | :--- |
| 1. Data Quality Check | Load and inspect the dataset | Understand data structure, column types, and key metrics |
| 2. Power Query ETL Transformation | Prepare data for analysis | Standardize formats, fix data types, and engineer custom descriptive columns |
| 3. Dashboard Layout & Planning | Select KPIs and charts addressing business questions | Filter relevant insights tailored for executive stakeholders |
| 4. Data Visualization | Build dashboard interface | Deliver an interactive dashboard with clear visual hierarchy and readability |
| 5. SCQA Executive Storytelling | Craft a concise executive narrative | Deliver a clear message that reinforces dashboard insights |

### 🎯 Analytical Focus
Nature: Descriptive Analysis (Business KPIs).  
Target Variables: Revenue, Profitability, Customer Segment, and Product Category.  
Relationship Types Analyzed: Customer behavior across segments, revenue distribution by product category and country, and Year-over-Year (YoY) revenue comparisons.

### 🗂 Final Product
A comprehensive commercial performance and retention report combining:
✅ Visual evidence (Interactive Power BI Dashboard)  
✅ Numerical evidence (Performance KPIs)  
✅ Actionable business implications  

### 📊 **Key Findings**
- Clear seasonal patterns emerged, featuring sales peaks during Summer (December–January) and steep declines during Winter (June–August).
- An overall decline in revenue was observed from 2024 to 2025.
- A shift in purchasing behavior was detected: High-value orders (≥ $1,000) dominate during Summer, whereas low-value transactions (< $1,000) surge during Autumn, Spring, and Winter.

## 🖋 **Conclusions & Recommendations**
A dual commercial challenge was identified:
- **Expected Seasonality:** Demand surges during Summer (Dec–Jan) and contracts during Winter (Jun–Aug).
- **Declining Trajectory:** Overall YoY revenue contraction from 2024 to 2025.

**Segment-level insights:**
- **Premium & Standard Customers:** Drive the highest value, displaying similar purchasing behaviors across all seasons.
- **Budget Customer Segment:** Represents the largest untapped growth opportunity.

**Strategic Recommendations:**
- Activate and engage the Budget customer segment throughout the entire calendar year.
- Implement targeted promotional strategies to maintain high-ticket sales during colder seasons.
- Focus commercial efforts on Electronics and Sports (the leading product categories).

## ▶ How to open the notebook in Google Colab
Click on the following button:  
[Google Colab](https://colab.research.google.com/drive/1oIXoxRuottmAUMYMLIrVUlYH0fOTfCCE?usp=sharing)

## 📘 How to reproduce the analysis
1. Open `notebooks/S11 Proyecto_InmobiliarioGrupoAndes.ipynb`
2. Execute the cells in sequential order
3. The notebook automatically loads datasets from `/data/`
