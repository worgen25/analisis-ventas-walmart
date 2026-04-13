
# 📊 Análisis de Ventas Walmart

## 📌 Contexto del proyecto
Este proyecto tiene como objetivo analizar el desempeño de ventas de Walmart a partir de múltiples fuentes de datos, incluyendo información de tiendas, departamentos y transacciones de ventas.

Se trabajó con diferentes hojas dentro de un archivo Excel:
- raw_ventas
- raw_departamento
- raw_tiendas
- clean_ventas
- tablas dinámicas (Pivot)
- dashboard final

El propósito principal es transformar datos crudos en información útil para la toma de decisiones, evaluando eficiencia, participación y calidad de datos.

---

## ⚙️ Proceso del proyecto

1. **Extracción de datos**
   - Se utilizaron múltiples tablas con información de ventas, tiendas y departamentos.

2. **Limpieza de datos**
   - Creación de la tabla `clean_ventas`
   - Validación de valores nulos, inconsistentes o erróneos

3. **Transformación**
   - Relación entre tablas
   - Generación de métricas clave

4. **Análisis**
   - Uso de tablas dinámicas
   - Cálculo de KPIs

5. **Visualización**
   - Creación de dashboard para interpretación de resultados

---

## 🔍 Análisis realizado

Se analizaron los datos con enfoque en:

### 📈 Rendimiento de tiendas
- Evaluación de ventas totales
- Comparación entre tiendas

### 🏬 Eficiencia operativa
- KPI: **Ventas por metro cuadrado**
- Permite medir qué tan eficiente es cada tienda

### 📊 Participación
- Porcentaje de contribución de cada tienda o departamento sobre el total

### 🧹 Calidad de datos
Se realizaron validaciones clave:
- Existencia de tiendas sin departamento
- Ventas negativas o nulas
- Tamaños de tienda con valor 0

---

## 📊 KPIs principales

### 1. Ventas por m²
- Mide eficiencia del espacio físico
- A mayor valor, mejor rendimiento de la tienda

### 2. Porcentaje de participación
- Indica el peso de cada segmento dentro del total de ventas

---

## 🖼️ Visualizaciones

### Flujo del proyecto
![Flujo](images/flujo_proyecto.png)

### Proceso de datos
![Pipeline](images/pipeline_datos.png)

---

## ✅ Validaciones (QA)

Se realizaron controles para asegurar la calidad del dataset:

- ✔️ No existen tiendas sin departamento asignado
- ✔️ No hay ventas negativas o inconsistentes
- ✔️ Todos los tamaños de tienda son válidos

---

## 📌 Conclusiones principales

- El análisis permite identificar qué tiendas son más eficientes en términos de espacio (ventas/m²)
- Se puede detectar qué segmentos tienen mayor participación en ingresos
- La limpieza de datos es clave para evitar errores en decisiones estratégicas
- El uso de dashboards facilita la interpretación de grandes volúmenes de información

---

## 🛠️ Herramientas utilizadas

- Excel (limpieza, análisis y dashboard)
- Tablas dinámicas
- Modelado de datos

---

## 🚀 Posibles mejoras

- Automatizar el proceso con Python o SQL
- Conectar a bases de datos en tiempo real
- Crear dashboards en Power BI o Tableau
