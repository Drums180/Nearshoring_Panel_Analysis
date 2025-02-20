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

## ⚡ Dataset  

Este análisis utiliza un conjunto de datos estructurado en **panel data** con información relevante sobre el impacto del nearshoring en México a nivel estatal.  

### 📖 Glosario de Variables  

#### 📈 Variables dependientes:  
- **new_fdi:** Ingresos de Nueva Inversión Extranjera Directa (IED). Millones de dólares.  
- **reinv_profits:** Reinversión de utilidades – Flujos de IED. Millones de dólares.  
- **intercom_acc:** Cuentas intercompañía – Flujos de IED. Millones de dólares.  
- **total_fdi:** Total de flujos de Inversión Extranjera Directa. Millones de dólares.  

#### 📊 Variables independientes:  
- **crime_rate:** Tasa de criminalidad por cada 100,000 habitantes del estado.  
- **unemployment:** Porcentaje de población desempleada.  
- **employment:** Porcentaje de población empleada.  
- **business_activity:** Índice de actividad económica ponderado por la distancia del estado al puerto de entrada más cercano en EE.UU.  
- **real_wage:** Salario real ajustado usando el INPC 2018 = 100. Pesos mexicanos.  
- **pop_density:** Densidad de población por km² del estado.  
- **good_governance:** Relación entre la inversión pública del estado y su deuda pública.  
- **ratio_public_investment:** Relación entre la inversión pública del estado y su Producto Interno Bruto (PIB).  
- **lq_primary:** Cociente de localización de personas empleadas en la industria primaria.  
- **lq_secondary:** Cociente de localización de personas empleadas en el sector secundario.  
- **lq_tertiary:** Cociente de localización de personas empleadas en el sector terciario.  
- **exchange_rate:** Tipo de cambio – Pesos MXN por 1 USD.  
- **patents_rate:** Número de patentes de I+D por cada 100,000 habitantes del estado.  
- **inpc:** Índice Nacional de Precios al Consumidor (INPC). Base 2018 = 100.
  
## 🚀 Cómo Usar el Código  

1. **Clonar el repositorio:**  
   ```bash
   git clone https://github.com/usuario/repo-nearshoring-mexico.git
   cd repo-nearshoring-mexico
