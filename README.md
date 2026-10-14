# 📊 ConnectaTel — Análisis estadístico de usuarios

## 🎯 Objetivo

Analizar los datos de clientes y uso de servicios de **ConnectaTel** para identificar patrones de comportamiento, segmentar usuarios y generar recomendaciones de negocio basadas en los datos.

El análisis se enfoca principalmente en el **nivel de uso, edad, tipo de plan y preferencias de interacción** entre llamadas y mensajes.

---

## 📂 Datasets

El proyecto utiliza tres datasets:

- **`users_latam.csv`**: información demográfica y de suscripción de los usuarios.
- **`usage.csv`**: registros de llamadas y mensajes realizados por los usuarios.
- **`plans.csv`**: características y precios de los planes de telefonía.

La base final contiene información de **4.000 usuarios**.

---

## 🔎 Etapas del análisis

El proyecto se desarrolló en las siguientes etapas:

1. **Exploración de los datos**
   - Estructura, dimensiones y tipos de datos.
   - Estadísticas descriptivas.

2. **Calidad de los datos**
   - Identificación de valores nulos, inválidos y sentinels.
   - Revisión de fechas y variables numéricas.

3. **Limpieza**
   - Tratamiento de valores faltantes e inválidos.
   - Corrección de inconsistencias según el tipo de interacción.

4. **Análisis estadístico**
   - Distribución de variables demográficas y de uso.
   - Identificación y evaluación de outliers.

5. **Construcción del perfil de usuario**
   - Cantidad de mensajes.
   - Cantidad de llamadas.
   - Minutos totales de llamadas.

6. **Segmentación**
   - Por grupo de edad: Joven, Adulto y Adulto Mayor.
   - Por nivel de uso: Bajo, Medio y Alto.

7. **Conclusiones y recomendaciones**
   - Análisis de patrones de comportamiento.
   - Identificación de segmentos de mayor valor.
   - Propuestas de acciones comerciales.

---

## 🛠️ Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## ▶️ Cómo ejecutar el proyecto

### Google Colab

1. Abrir [Google Colab](https://colab.research.google.com/).
2. Seleccionar **File → Upload notebook**.
3. Cargar el archivo `ConnectaTel_Analysis.ipynb`.
4. Cargar los datasets en la carpeta correspondiente.
5. Ejecutar las celdas del notebook en orden.
