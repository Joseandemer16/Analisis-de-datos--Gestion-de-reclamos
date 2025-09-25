# Proyecto Gestión de Reclamos (2023 - 2025)

Este proyecto tiene como objetivo analizar la información de los reclamos registrados en la Sociedad Eléctrica del Sur durante los años 2023, 2024 y 2025.  
La idea principal fue transformar el dataset original en una base de datos estructurada, definir indicadores clave (KPIs) y finalmente crear un dashboard en **Power BI** que permita visualizar los resultados de forma clara y sencilla.

---

## 📂 Contenido del repositorio
- **Diccionario de datos**: archivo con la descripción de todas las variables.  
- **Script SQL**: creación de la base de datos, tablas y carga de información.  
- **Consultas SQL**: sentencias para obtener los KPIs definidos.  
- **Dashboard Power BI**: reporte visual con los indicadores.  
- **Documentación**: informe con el proceso, resultados y conclusiones.  

---

## ⚙️ Proceso realizado
1. **Normalización del dataset**  
   - Identificación de dos entidades principales: **Código** y **Fecha**.  
   - Se mantuvieron todas las variables, ya que cada una complementa al análisis.  

2. **Definición de KPIs**  
   - Total de reclamos registrados en 2023, 2024 y 2025.  
   - Reclamos atendidos y no atendidos por año.  
   - Top 5 de clases de reclamo más frecuentes.  
   - Distribución de reclamos según tipo de resolución.  
   - Formas o canales a través de los cuales se registraron los reclamos.  
   - Provincias distintas a Arequipa que presentaron reclamos.  

3. **Análisis y resultados**  
   - Los KPIs fueron calculados en MySQL mediante consultas SQL.  
   - Posteriormente se diseñó un dashboard en Power BI con tarjetas, gráficos de barras, circulares y mapas.  

---

## 📊 Dashboard en Power BI
El tablero permite responder preguntas clave como:  
- ¿Cuántos reclamos se recibieron cada año?  
- ¿Qué porcentaje fue atendido y cuál quedó pendiente?  
- ¿Cuáles son los reclamos más frecuentes?  
- ¿Qué canales usan más los clientes?  
- ¿En qué distritos y provincias se concentran los reclamos?  

---

## ✅ Conclusiones
El análisis permitió identificar que los reclamos más frecuentes corresponden a **exceso de consumo** y que los principales canales de ingreso son **presencial** y **telefónico**.  
Además, se detectaron provincias fuera de Arequipa con una cantidad significativa de reclamos, lo cual evidencia la necesidad de fortalecer la gestión en esas zonas.  

En general, este proyecto demuestra cómo el uso de **SQL + Power BI** facilita la toma de decisiones y mejora la gestión de reclamos.
