# 📊 Proyecto: Análisis de Clientes - ConnectaTel

## 🎯 Objetivo del Proyecto

El objetivo de este proyecto es analizar el comportamiento de los usuarios de ConnectaTel para identificar patrones de uso, segmentar clientes y generar insights accionables que permitan mejorar la oferta de planes y estrategias de negocio.

---

## 📁 Datasets Utilizados

Se trabajó con los siguientes datasets:

- **users**: información demográfica de los usuarios (edad, ciudad, fechas, plan, etc.).
- **usage**: registros de uso de los usuarios (llamadas y mensajes), incluyendo variables como duración y longitud.

---

## 🔍 Etapas del Análisis

El proyecto se desarrolló siguiendo las siguientes etapas:

1. **Exploración inicial de datos (EDA)**
   - Revisión de estructura, tipos de datos y valores nulos.
   - Identificación de inconsistencias.

2. **Limpieza de datos**
   - Conversión de tipos (fechas, numéricos).
   - Manejo de valores nulos.
   - Validación de datos (fechas futuras, valores inválidos).

3. **Análisis exploratorio**
   - Distribuciones de variables clave (edad, mensajes, llamadas, minutos).
   - Identificación de outliers mediante IQR.
   - Comparación por tipo de plan.

4. **Segmentación de clientes**
   - Creación de grupos por nivel de uso (Bajo, Medio, Alto, Sin datos).
   - Análisis por grupos de edad.

5. **Visualización**
   - Histogramas y gráficos de conteo.
   - Comparación entre segmentos.

6. **Insights y recomendaciones**
   - Identificación de segmentos más valiosos.
   - Detección de oportunidades de negocio.
   - Propuestas de mejora en planes y datos.

---

## ▶️ Cómo ejecutar el proyecto

Puedes ejecutar este proyecto de las siguientes maneras:

###  Google Colab
1. Sube el archivo `.ipynb` a Google Colab.
2. Asegúrate de cargar los datasets necesarios.
3. Ejecuta las celdas en orden.
