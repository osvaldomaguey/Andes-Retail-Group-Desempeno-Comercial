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
Creación de medidas DAX.
Comunicar los hallazgos en un dashboard en Power BI

## 🗂️ Dataset
Fuente: Andes_Retail_Group_2024_2025.csv
Tamaño: 8,500 registros de ventas

Fuente: dim_clientes.csv
Tamaño: 3,500 registros de clientes

Fuente: dim_propiedades.csv
Tamaño: 8,000 registros de propiedades

## **Variables Analizadas**
| Variable | Tipo | Descripción |
|---------|-------------|-------------------|
| precio_venta	| Numérica | Precio final de venta de la propiedad |
| monto_comision | Numérica |	Monto de comisión generado por la venta |
| ciudad | Categórica	| Ciudad donde se realizó la venta |
| tipo_propiedad	| Categórica	| Tipo de propiedad vendida |
| segmento_comprador | Categórica | Tipo o perfil del comprador |
| canal_venta	| Categórica	| Canal utilizado para la venta |
| tipo_propiedad | Categórica	| Tipo de propiedad |
| fecha_venta	| Fecha	| Fecha en que se realizó la venta |

## 🛠️ Metodología
Limpieza de datos.
Modelado de datos.
Herramientas Utilizadas: *Power BI Desktop o Tableau, Visualizaciones nativas (barras, líneas, mapas, tarjetas KPI), Modelo de narrativa SQCA.*

## 🔄 Etapas del Análisis
Este proyecto sigue un flujo estructurado de análisis dividido en 5 etapas principales:

| Etapa	 | Descripción | Resultado Esperado |
|---------|-------------|-------------------|
| 1. Exploración y limpieza | Cargar y explorar el dataset | Entender estructura, columnas, tipos, métricas clave, corregir formatos, valores nulos y eliminar duplicados |
| 2. Creación de tabla de calendario | Se creó el la tabla dim_fecha | Calcular KPIs y cohortes de retención | 
| 3. Modelado de datos | Crear el modelo estrella, y definir las relaciones adecuadas entre tablas | Tener un modelo que pueda calcular medidas DAX y KPIs sin presentar errores de ejecución o de cálculo |
| 4. Creacion de medidas y cohortes | Calcular medidas qué contesten las preguntas de negocio | Entender el desempeño del negocio y el comportamiento del cliente a lo largo del tiempo |
| 5. Visualización | Crear visualizaciones |	Dashboard interactivo en Power BI |
 
### 🎯 Enfoque del Análisis
Naturaleza: Descriptivo (KPIs de negocio) y Exploratorio (cohortes)
Variable objetivo: Revenue y profit, y Tasa de retención mensual
Tipos de relaciones analizadas: Comportamiento del usuario por tipo de cliente, ingresos por tipo de propiedad, Actividad anual y mensual por cohorte de registro.

### 🗂 Producto Final
Un reporte de rentabilidad y retención que combina:

✅ Evidencia visual (Dashboard interactivo en PowerBI)
✅ Evidencia numérica (KPIs de performance)
✅ Retención por cohortes
✅ Implicaciones de negocio accionables

### **📊 Resultado del Análisis**
- El tipo de propiedad que genera mayor revenue son las casas con $2.24 mil millones (37.3% del total).
- La ciudad con mayor volumen de ventas es Ciudad de México con 53.92% de participación.
- El canal de venta más eficiente en términos de ingresos son los corredores con 72.85% de participación.
- El negocio registró un crecimiento del 14.28% en 2024 vs 2023.
- Las ventas muestran patrones estacionales con picos en marzo-abril y septiembre-noviembre.
- Las ventas muestran un crecimiento sostenido del 14.28% YoY.
- Los corredores generan 2.7 veces más ingresos que las ventas directas.

## **🖋 Conclusiones y recomendaciones**
- Priorizar la comercialización de propiedades tipo comercial por su alto ticket promedio ($1.79M).
- Fortalecer el canal de corredores que presenta mayor participación en el revenue (72.85%).
- Implementar estrategias de upselling para clientes primerizos hacia propiedades de mayor valor.
- Desarrollar campañas estacionales aprovechando los picos de marzo-abril y septiembre-noviembre.
- Crear programas de fidelización para el segmento de inversionistas (24.47%) con potencial de recompra.
- Optimizar la eficiencia de costos en el canal de corredores manteniendo su efectividad comercial.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:
[Google Colab](https://colab.research.google.com/drive/1AeliHUxdl8CC2TGrKDZelCq_pRMMwOKm?usp=sharing)

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/S11 Proyecto_InmobiliarioGrupoAndes.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/`
