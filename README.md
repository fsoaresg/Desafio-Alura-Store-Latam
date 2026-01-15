---

# Desafio Alura Store Latam

---

## Descripción del proyecto

El objetivo es identificar la tienda menos eficiente y presentar una recomendación final basada en los datos que ayude al Sr. Juan a decidir qué tienda de su cadena Alura Store debe vender para iniciar un nuevo emprendimiento. Para ello, se analizan datos de ventas, rendimiento y reseñas de las 4 tiendas de Alura Store.

---

## Tecnologías utilizadas

- **Python 3**
- **Pandas**: manipulación y análisis de datos.
- **NumPy**: operaciones numéricas.
- **Matplotlib**: visualización de datos estática.
- **Folium**: mapas interactivos para análisis geográfico.
- **Google Colab**: entorno de ejecución y colaboración.

---

## Datos

Se analizaron las ventas de las 4 tiendas:  

| Tienda | Dataset |
|--------|---------|
| Tienda 1 | [CSV](https://raw.githubusercontent.com/fsoaresg/Desafio-Alura-Store-Latam/main/base-de-datos-alura-store-latam/tienda_1%20.csv) |
| Tienda 2 | [CSV](https://raw.githubusercontent.com/fsoaresg/Desafio-Alura-Store-Latam/main/base-de-datos-alura-store-latam/tienda_2.csv) |
| Tienda 3 | [CSV](https://raw.githubusercontent.com/fsoaresg/Desafio-Alura-Store-Latam/main/base-de-datos-alura-store-latam/tienda_3.csv) |
| Tienda 4 | [CSV](https://raw.githubusercontent.com/fsoaresg/Desafio-Alura-Store-Latam/main/base-de-datos-alura-store-latam/tienda_4.csv) |

--- 
**Columnas principales:**  
- Producto  
- Categoría del producto  
- Precio  
- Costo de envío  
- Calificación promedio  
- Vendedor  
- Ubicación (latitud y longitud)

---

## Contenido del proyecto

1. **Importación de datos**
   - Se importaron los datasets de las 4 tiendas desde GitHub.
   - Cada dataset contiene: `Producto`, `Categoría del Producto`, `Precio`, `Calificación`, `Costo de envío`, `Vendedor`, `lat`, `lon`.

2. **Análisis de datos**
   - **Ingresos totales por tienda**: cálculo de ingresos y porcentaje sobre el total.
   - **Ventas por categoría**: identificación de categorías con mayor y menor volumen de ventas.
   - **Calificación promedio de clientes**: satisfacción promedio por tienda.
   - **Productos más y menos vendidos**: análisis del desempeño de productos individuales.
   - **Costo de envío promedio por tienda**: evaluación del impacto en eficiencia.
   - **Matriz de Eficiencia**: relación entre satisfacción y costo de envío.
   - **Matriz de Valor Estratégico**: relación entre satisfacción y ingresos.
   - **Eficiencia Global**: combinación ponderada de ingresos, satisfacción y costos de envío.
   - **Causa raíz de baja eficiencia (Tienda 4)**: categorías, productos y vendedores con bajo desempeño.
   - **Análisis geográfico**: concentración de ventas por ubicación y mapa interactivo.

3. **Visualizaciones**
   - Gráficos de barras horizontales para ingresos, satisfacción, costo de envío y productos.
   - Comparativas de ventas por categoría entre tiendas.
   - Matrices de eficiencia y valor estratégico.
   - Mapas de calor y mapas interactivos de ventas.
  
4. **Informe Final**
   - Introducción
   - Desarrollo del análisis
   - Conclusión y recomendación final
   - Recomendación adicional
  
  ---

  ## Resultados clave

- **Tienda con mayor eficiencia global**: Tienda 1
- **Tienda con menor eficiencia global**: Tienda 4

**Observaciones de la Tienda 4:**

- Presenta el menor ingreso total de las cuatro tiendas.
- No destaca en la venta de categorías clave ni en la rotación de productos.
- Tiene una calificación promedio inferior, reflejando una menor satisfacción del cliente.
- Sus productos más vendidos no alcanzan el nivel de desempeño observado en otras tiendas.
- Productos con baja rotación, principalmente en **Instrumentos musicales** y **Electrodomésticos**.
- Aunque posee el costo de envío más bajo, este factor no compensa sus debilidades en ingresos y experiencia del cliente.
- Incluso vendedores con buen historial en otras sucursales, como Pedro Gomez, muestran bajo desempeño, lo que sugiere problemas operativos o logísticos.
- Muestra la menor eficiencia global dentro del portafolio.

---

## Conclusión y recomendación

- **Tienda recomendada para vender**: Tienda 4

Basado en los indicadores de ingresos, satisfacción y eficiencia global, la Tienda 4 es la unidad menos estratégica del portafolio de Alura Store. Su venta permitiría al Sr. Juan optimizar recursos y reinvertir en un nuevo emprendimiento con mayor potencial.

---

## Cómo usar este proyecto

1. Abrir el cuaderno en **[Google Colab](https://colab.research.google.com/github/fsoaresg/Desafio-Alura-Store-Latam/blob/main/AluraStoreLatam.ipynb)**.
2. Ejecutar las celdas paso a paso para:
   - Importar los datos desde GitHub.
   - Generar métricas de ingresos, ventas, satisfacción y eficiencia.
   - Visualizar los gráficos y mapas interactivos.
3. Analizar los resultados y tomar decisiones estratégicas basadas en los insights.

---

## Estructura del repositorio

├── Challenge-Alura-Store.ipynb # Cuaderno de Colab con análisis completo

├── README.md # Este archivo

├── base-de-datos-alura-store-latam/

│ ├── tienda_1.csv

│ ├── tienda_2.csv

│ ├── tienda_3.csv

│ └── tienda_4.csv

---

## Autor

**Fátima Soares**  
Analista de datos, apasionada por la visualización y análisis de métricas, transformando datos en información útil para la toma de decisiones.  
[GitHub](https://github.com/fsoaresg)

---

## Licencia

Este proyecto es de **uso educativo y demostrativo**, con base en un desafío de Alura Latam.
