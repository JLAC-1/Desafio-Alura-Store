README: Análisis de Desempeño de Tiendas Alura Store
📌 Propósito del Proyecto
Este proyecto analiza el desempeño de cuatro tiendas (Tienda 1, Tienda 2, Tienda 3 y Tienda 4) para determinar cuál presenta el menor rendimiento y debería considerarse para su venta. El análisis se basa en:
✅ Facturación total
✅ Ventas por categoría
✅ Calificación de clientes
✅ Productos más/menos vendidos
✅ Costos de envío
✅ Variación de precios en productos clave

Objetivo final: Identificar la tienda menos rentable y justificar su venta con datos cuantitativos.

📂 Estructura del Proyecto
alura-store-analysis/  
├── data/  
│   ├── tienda_1.csv  
│   ├── tienda_2.csv  
│   ├── tienda_3.csv  
│   └── tienda_4.csv  
├── notebooks/  
│   └── analisis_tiendas.ipynb  
├── graficos/  
│   ├── ingresos_tiendas.png  
│   ├── ventas_por_categoria.png  
│   └── costos_envio.png  
└── README.md  
📊 Principales Hallazgos (Insights)

1. Ingresos Totales por Tienda
Tienda 4 tuvo los menores ingresos (1,038,375,700), 10% menos que la Tienda 1.


2. Desempeño por Categoría
Electrodomésticos e instrumentos musicales fueron las categorías más débiles en Tienda 4.


3. Estrategia de Precios Ineficiente
Tienda 4 tiene precios bajos en notebooks (1,499.99) y sofás (799.99), pero no genera más ventas.

En TVs, sus precios son más altos (1,299.99) sin ventajas competitivas.

4. Costos Logísticos
Tienda 4 tiene el menor costo de envío (23,459.46), pero esto no compensa sus bajos ingresos.



🛠️ Instrucciones para Ejecutar el Notebook
Requisitos

.Python 3.8+
.Librerías: pandas, matplotlib, seaborn
.Jupyter Notebook o Google Colab

Pasos
1.Clonar el repositorio:
git clone https://github.com/tu-usuario/alura-store-analysis.git

2.Instalar dependencias:
pip install pandas matplotlib seaborn

3.Abrir el notebook:
jupyter notebook notebooks/analisis_tiendas.ipynb

4.Ejecutar las celdas en orden para reproducir el análisis.

📌 Conclusión
Recomendación: Vender la Tienda 4 debido a:

1.Menores ingresos globales.
2.Bajo desempeño en categorías clave.
3.Estrategia de precios inconsistente.
4.Aunque los costos logísticos son bajos, no compensan el bajo rendimiento.

