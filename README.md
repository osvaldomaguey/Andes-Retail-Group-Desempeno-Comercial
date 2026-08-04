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
