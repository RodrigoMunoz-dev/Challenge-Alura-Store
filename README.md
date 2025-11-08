# 🏬 Alura Store — Data Science Challenge (Latam)

## 📋 Descripción
Este proyecto forma parte del **Challenge de Data Science de Alura Latam**.  
El objetivo es **ayudar al Sr. Juan** a decidir **qué tienda de su cadena Alura Store debería vender**, basándose en un análisis de datos reales de ventas, calificaciones y costos logísticos.

El análisis se realizó con **Python**, utilizando las bibliotecas `pandas`, `matplotlib` y `seaborn` para la manipulación, visualización y exploración de datos.

---

## 🎯 Objetivos del análisis
- Analizar el **rendimiento financiero** de las cuatro tiendas.  
- Evaluar la **satisfacción del cliente** mediante las calificaciones promedio.  
- Comparar la **eficiencia logística** a través del costo promedio de envío.  
- Identificar las **categorías de productos más rentables** en cada tienda.  
- Proporcionar una **recomendación final** sobre cuál tienda vender.

---

## 🧩 Fuentes de datos
Los datos provienen del repositorio oficial de Alura Latam:  
[alura-es-cursos/challenge1-data-science-latam](https://github.com/alura-es-cursos/challenge1-data-science-latam)

Archivos CSV utilizados:
- `tienda_1.csv`
- `tienda_2.csv`
- `tienda_3.csv`
- `tienda_4.csv`

---

## 🧠 Análisis de resultados

### 1️⃣ Ingresos Totales por Tienda
| Tienda | Ingresos Totales ($) |
|:--|--:|
| Tienda 1 | 1,150,880,400 |
| Tienda 2 | 1,116,343,500 |
| Tienda 3 | 1,098,019,600 |
| **Tienda 4** | **1,038,375,700** |

💬 *La Tienda 4 obtiene el menor ingreso total, con una diferencia cercana al 10 % respecto a la Tienda 1.*

---

### 2️⃣ Calificación Promedio por Tienda
| Tienda | Calificación Promedio |
|:--|--:|
| Tienda 3 | 4.05 |
| Tienda 2 | 4.04 |
| Tienda 4 | 4.00 |
| Tienda 1 | 3.98 |

💬 *Las puntuaciones son similares, pero ninguna tienda destaca fuertemente en satisfacción. Tienda 4 mantiene una calificación promedio, sin diferenciarse por servicio.*

---

### 3️⃣ Costo Promedio de Envío por Tienda
| Tienda | Costo Promedio de Envío ($) |
|:--|--:|
| Tienda 1 | 26,019 |
| Tienda 2 | 25,216 |
| Tienda 3 | 24,806 |
| **Tienda 4** | **23,459** |

💬 *Tienda 4 tiene el costo de envío más bajo, lo que indica buena eficiencia logística, pero no logra traducirlo en mayores ingresos.*

---

### 4️⃣ Categorías más fuertes por Tienda
| Tienda | Categoría del Producto | Ingresos |
|:--|:--|--:|
| Tienda 1 | Electrónicos | $429.49M |
| Tienda 2 | Electrónicos | $410.83M |
| Tienda 3 | Electrónicos | $410.78M |
| Tienda 4 | Electrónicos | $409.48M |

💬 *Todas las tiendas concentran su mayor facturación en Electrónicos, pero la Tienda 4 genera menos volumen en la misma categoría, lo que sugiere menor demanda o alcance comercial.*

---

## 📊 Visualizaciones destacadas
- **Ingresos Totales por Tienda** (barras verticales)  
- **Top 5 Categorías mas vendidas por tienda (barras verticales)
- **Calificación Promedio por Tienda** (barras con etiquetas)  
- **Costo Promedio de Envío** (barras horizontales formateadas)  
- **Productos Más y Menos Vendidos** (Top 10 comparativo)

---

## 🧭 Conclusión Final

> Tras analizar ingresos, satisfacción, costos logísticos y categorías de producto, se concluye que la **Tienda 4** es la **menos rentable y la que presenta menor potencial de crecimiento**.  
>  
> Aunque cuenta con bajos costos de envío (indicando buena eficiencia operativa), no logra convertir esa ventaja en ventas significativas ni en calificaciones superiores.  
>  
> ✅ **Recomendación:**  
> El Sr. Juan debería **vender la Tienda 4** y **reinvertir los recursos** en las Tiendas 1–3, enfocando la estrategia comercial en productos de **Electrónicos y Electrodomésticos**, que representan más del **65 % del total de ingresos** de la cadena.

---

## 🧰 Herramientas utilizadas
- **Python 3.10+**
- **Pandas** — manipulación y análisis de datos  
- **Matplotlib** y **Seaborn** — visualización de resultados  
- **Google Colab** — entorno de ejecución  
- **GitHub** — control de versiones y presentación del proyecto  

---

## ✍️ Autor
**Rodrigo Muñoz (@RodrigoMunoz-dev)**  
Estudiante de Data Science & Python  
💡 Proyecto desarrollado como parte del Challenge Data Science Latam — Alura Cursos.

---
