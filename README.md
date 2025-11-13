Este proyecto tiene como objetivo analizar el rendimiento de cuatro tiendas mediante el uso de Python y Google Colab, con el fin de determinar a qué tienda debería vender el Sr. Juan sus productos.
El análisis considera factores clave como ingresos, calificaciones de clientes, categorías más vendidas, costos de envío y distribución geográfica de las ventas.

nálisis Realizado

Ingresos totales por tienda
Se calcularon las ventas acumuladas para cada tienda y se graficaron comparativamente.

Categorías más y menos vendidas
Se identificaron los tipos de productos más populares por tienda, utilizando groupby() y sort_values().

Calificación promedio
Se analizó la satisfacción promedio de los clientes de cada tienda.

Costo de envío promedio
Se calcularon los costos medios de envío, permitiendo evaluar la eficiencia logística.

Ranking de desempeño global
Se generó una puntuación combinada usando:

𝑃 =
(
𝐼
𝑛
𝑔
𝑟
𝑒
𝑠
𝑜
𝑠
×
0.5
)
+
(
𝐶
𝑎
𝑙
𝑖
𝑓
𝑖
𝑐
𝑎
𝑐
𝑖
𝑜
ˊ
𝑛
×
0.4
)
+
(
1
−
𝐸
𝑛
𝑣
ı
ˊ
𝑜
×
0.1
)
P=(Ingresos×0.5)+(Calificaci
o
ˊ
n×0.4)+(1−Env
ı
ˊ
o×0.1)

Esto permitió identificar la tienda con mejor rendimiento general.

Distribución geográfica
Se utilizó Folium para crear:

Un mapa interactivo con íconos con mapa de calor.



