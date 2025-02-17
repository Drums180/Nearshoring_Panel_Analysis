# 📌 Análisis de Nearshoring en México por Entidad Federativa utilizando Datos Panel  

## 📖 Descripción del Proyecto  

Este repositorio contiene un análisis del impacto del **nearshoring** en México a nivel estatal, utilizando técnicas de **análisis de datos panel**. Se exploran factores clave como inversión extranjera directa (IED), infraestructura industrial, costos logísticos y exportaciones manufactureras para evaluar el atractivo de cada entidad federativa para la reubicación de operaciones de empresas internacionales.  

## 📊 Datos Utilizados  

Los datos provienen de diversas fuentes oficiales y privadas, incluyendo:  

- 📌 **Secretaría de Economía** – Estadísticas de Inversión Extranjera Directa (IED).  
- 📌 **INEGI** – Indicadores económicos y logísticos por entidad.  
- 📌 **Banco de México** – Exportaciones manufactureras hacia EE.UU.  
- 📌 **Empresas y Asociaciones Industriales** – Reportes sobre expansión y nuevas plantas.  

Los datos están organizados en un **formato de panel** (entidades federativas observadas en múltiples periodos de tiempo).  

## 🏗️ Metodología  

El análisis se basa en modelos de regresión de datos panel para estimar la influencia de distintas variables en la atracción de inversiones nearshoring en México. Se aplican:  

- **Modelos de efectos fijos** para controlar características inobservables de cada entidad.  
- **Modelos de efectos aleatorios** cuando se asume que las diferencias entre entidades no están correlacionadas con las variables explicativas.  
- **Técnicas de clustering y visualización** para agrupar entidades según su atractivo nearshoring.  

## ⚡ Principales Variables  

Las variables clave utilizadas incluyen:  

### 📈 Variables dependientes:  
- **Flujo de IED en sectores clave** (millones de dólares).  
- **Número de nuevas plantas industriales** en cada entidad.  

### 📊 Variables independientes:  
- **Costo logístico y tiempos de entrega** en comparación con otros países.  
- **Exportaciones manufactureras hacia EE.UU.** (volumen y valor).  
- **Disponibilidad de mano de obra calificada** y nivel salarial.  
- **Infraestructura industrial** (parques industriales, acceso a insumos energéticos).  

## 🚀 Cómo Usar el Código  

1. **Clonar el repositorio:**  
   ```bash
   git clone https://github.com/usuario/repo-nearshoring-mexico.git
   cd repo-nearshoring-mexico
