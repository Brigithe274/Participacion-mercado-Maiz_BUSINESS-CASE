# BUSINESS CASE en Power BI: Participacion de mercado maiz importado
Este dashboard muestra el Indicador Trimestral de Porcentaje de Participación de Mercado en Lima del Volumen de Importación en toneladas de Commodities de Agricultura (Maíz) de la empresa ABC. Permite visualizar y analizar la participación de ABC frente a sus competidores e identificar tendencias.

# Creación de la base de datos
Se creó una base de datos en SQL para almacenar los datos de importación de maíz. Este proceso incluyó:
Diseño del Esquema de la Base de Datos: Definición de tablas, relaciones y restricciones. Se cuenta con 10 tablas maestras y 2 tablas transaccionales.
Inserción de Datos: Importación de datos históricos y actuales sobre la importación de maíz.

# Modelado de la Base de Datos
Se elaboró un diagrama de la base de datos para visualizar la estructura y las relaciones entre las diferentes tablas. Esto incluyó:

_Diagrama ER (Entidad-Relación): Representación gráfica de las entidades y sus relaciones._
![1](https://github.com/user-attachments/assets/b6bb509a-4222-4f5a-9255-bf080c3ec46a)

# Conexión a Power BI
Se conectó la base de datos SQL a Power BI para la visualización y análisis de datos. Esto permitió:
 * Extraer Datos: Importación de datos relevantes desde la base de datos.
 * Transformar Datos: Limpieza y transformación de datos para adecuarlos al análisis.
 * Crear Visualizaciones: Desarrollo de gráficos y dashboards interactivos en Power BI.

# Business Case
Para crear el Indicador Trimestral de Participación de Mercado, se utilizó un business case que incluyó:
 * Objetivo: Al 31 de marzo de 2024, el INDICADOR TRIMESTRAL DE PORCENTAJE DE PARTICIPACIÓN DEL MERCADO EN EL DEPARTAMENTO DE LIMA DE VOLUMEN DE IMPORTACION EN TN DE COMMODITIES DE AGRICULTURA (MAIZ) DE LA EMPRESA ABC tiene un valor de 17% (semáforo amarillo). Para el 31 de marzo de 2025, se desea incrementar el valor de este indicador hasta llegar a un valor de 20.0% (semáforo verde).
 * Estrategia: Para lograr este objetivo se plantea implementar una estrategia de upselling brindando una diferenciación del producto ofreciendo a los clientes un maíz orgánico (grado 1), el cual presenta ciertas ventajas frente al maíz convencional, y de esta forma se podría crecer en el mercado. Para ello se necesitaría la obtención de una certificación orgánica desde el país de origen y destino, lo cual implicaría costos de inspección y auditoría.
 * Costo Beneficio: El precio total de implementación de esta estrategia es de 15 millones de dólares como costo total. Se estima que al cumplir este objetivo en la fecha propuesta, la facturación adicional trimestral será de 6.525 millones, lo cual sumaria 26.1 millones de dólares de facturación adicional solamente durante el primer año, posterior a la fecha de cumplimiento del objetivo.

_Caso de negocio_
![image](https://github.com/user-attachments/assets/1888ae12-6f22-4c42-9d55-bd24b2835f48)

# Indicador
Este indicador mide el volumen de importación en TN de commodities de agricultura (maíz) de la empresa ABC sobre el volumen de importación en TN de commodities de agricultura (maiz) de todas las empresas del departamento de Lima, durante un periodo trimestral especifico. Este indicador nos muestra la posición de la empresa ABC en relación con sus competidores.

_Indicador principal_
![image](https://github.com/user-attachments/assets/86f1300a-0419-4a89-8354-d125a02c9a80)

# Dashboard
Este indicador muestra la participación de mercado de la empresa ABC en el sector de importación de maíz en el departamento de Lima, expresado en un porcentaje del volumen total importado. Al observar el semáforo de rangos, el indicador se encuentra en la zona amarilla, con un 17.0%, lo que significa que la participación de mercado de la empresa está en un rango intermedio, entre el 17% y el 20%.

_Dashborad comercial de la empresa ABC_
![image](https://github.com/user-attachments/assets/334b3b59-765f-47db-b99d-1e9ef267c669)

# Reporte
El reporte muestra una tabla y un gráfico de líneas para visualizar el porcentaje de participación de mercado con y sin inversión, en el contexto del volumen de importación de maíz en toneladas en Lima para la empresa ABC.

 * Participación con Inversión:
Inició en 17% en el primer trimestre de 2024 y alcanzó el 20% al final del primer trimestre de 2025. Se proyecta un crecimiento constante, llegando a 21.9% al final del cuarto trimestre de 2026.
 * Participación sin Inversión: Se mantiene constante en 0.17% durante todo el período.

Análisis ("What?", "So what?", "Now what?"):
 * What?: Al 31 de marzo de 2024, la participación de mercado era del 17%.
 * So what?: Estar 3% por debajo del nivel óptimo (20%) implica una pérdida de facturación de 2.18 millones de dólares trimestrales por cada punto porcentual.
 * Now what?: Se plantea una estrategia de upselling para alcanzar el 20% diferenciando el producto como maíz orgánico, lo que podría requerir certificaciones orgánicas y costos adicionales de inspección y auditoría.

_Reporte del indicador principal_
![image](https://github.com/user-attachments/assets/8f9decb6-1d2b-4029-a0b5-cbe2e45932da)

# Questions:
Para este caso de negocio, se plantearon preguntas clave que permitirán evaluar los avances del business case a través de la herramienta Power BI.

## P1. ¿CUALES SON LOS CINCO PRINCIPALES CLIENTES EN TERMINOS DE VOLUMEN POR PEDIDOS DE MAIZ (GRADO 1 y 2) POR AÑO?
Se utilizaron dos gráficos de barras: agrupadas y apiladas y una tabla.
Se presenta un listado que separa el volumen de los últimos cuatro semestres de cada cliente. De ello, se desprende un gráfico de barras apiladas que compila el volumen de pedidos del último año de cada cliente. El top 5 está conformado por Gustavo Salazar, Ricardo Jiménez, Jorge Vargas, Renato López y José Landa. Adicionalmente, se presenta una recopilación histórica de los clientes ordenados por mayor volumen de pedidos en un gráfico de barras agrupadas donde lidera Gustavo Salazar con casi 39 mil toneladas de maíz de Grado 1 y cerca de 72 mil toneladas de Grado 2.

![image](https://github.com/user-attachments/assets/ba3f4421-5b08-47b8-9bef-43e66220a18f)

## P2. ¿CUÁL ES EL VOLUMEN TOTAL DE IMPORTACIÓN DE MAÍZ (TANTO DE GRADO UNO COMO DE GRADO DOS) DE CADA TRIMESTRE POR AÑO?
Se utilizo el gráfico de líneas para visualizar el volumen de maiz importado por trimestre, tanto para maíz grado 1 y 2.

 - Maíz Grado 1🥇: Se incorporo a partir del semestre 2024-1, con un volumen trimestral de 102 mil toneladas y terminando el último trimestre del 2024 con 146 mil toneladas.

 - Maíz Grado 2🥈: Para el primer trimestre del 2024 inicio com 149 mil toneladas y termino el año con 295 mil toneladas.
Esta visualización facilita la comparación directa entre el maiz de grado 1 y 2 y destaca al maíz de Grado 2 como principal producto importador.

![image](https://github.com/user-attachments/assets/da7ffb71-7c90-4707-a70c-26e1d9c5e77f)

## P3. ¿CUÁL ES TOP 3 DE PUERTOS CON MAYOR VOLUMEN DE IMPORTACIÓN DE MAIZ Y SU PORCENTAJE DE PARTICIPACIÓN RESPECTIVAMENTE POR AÑO?
El gráfico de barras nos permite comparar e identificar rápidamente cuál es el top 3 se puertos con mayor volumen de importación de maíz. Los principales puertos desde los cuales la empresa ABC realiza importaciones son: P Thunder Bay, P. Houston y P. Vancouver. De los cuales P Thunder Bay, P. Vancouver y P. Prince son los principales puertos donde se importa el Maíz de Grado 2. Mientras que el maíz de grado 1 es proveniente de los puertos P. Houston, P. Thunder Bay y P. Buenos aires

![image](https://github.com/user-attachments/assets/926ebf55-0bcd-4ad8-aae4-11a063177a19)

## P4. ¿CUÁL ES EL PORCENTAJE DE PEDIDOS DE MAÍZ (TANTO DE GRADO UNO Y DOS) DE CADA TRIMESTRE POR AÑO?
El gráfico de líneas nos permite visualizar la tendencia en el volumen de pedidos por trimestre y por tipo de producto. Se observa que, en general, el maíz de Grado 2 presenta una tendencia positiva. Sin embargo, existe un punto de quiebre en el primer trimestre de 2024, a partir del cual se implementa la estrategia de diferenciación y upselling para incrementar la participación en el mercado. Después de eso, se refleja la continuidad de la tendencia positiva en ambos productos hasta el último trimestre de 2024.

![image](https://github.com/user-attachments/assets/00d5e170-ab13-435c-b566-f413f02618d9)

## P5. ¿CÓMO VARIÓ EL PORCENTAJE DE PARTICIPACIÓN TRIMESTRAL EN EL MERCADO DE LA EMPRESA ABC EN COMPARACIÓN DEL AÑO 2023 Y 2024?
Se han utilizado tablas, gráficos de línea y circular y tarjetas que explican la variación del porcentaje de participación. Tanto el gráfico de línea, gráfico circular y tabla reúnen información dinámica del porcentaje de participación de mercado de la empresa ABC. En el tercer trimestre del 2023 se tuvo el menor porcentaje de participación de mercado con un 16.84% y se proyecta una participación de mercado del 19.50% para el último trimestre del 2024. No obstante, se resalta una variación porcentual nula entre un año y otro a nivel trimestral.

![image](https://github.com/user-attachments/assets/390d13a8-49e3-4365-8b31-c0c7f706cd4a)

## P6. ¿CUÁLES SON LOS 2 PROVEEDORES MÁS IMPORTANTES EN TÉRMINOS DE VOLUMEN DE MAÍZ IMPORTADO PARA MAÍZ GRADO 1 Y MAÍZ GRADO 2 DURANTE EL 2024?
El gráfico utiliza barras para visualizar el volumen de maíz importado por los dos principales proveedores en 2024, tanto para maíz grado 1 como para maíz grado 2.

 - Maíz Grado 1🥇: Dreyfus Commodities lidera con 348 mil toneladas, mientras Grain Norte SAC sigue con 146 mil toneladas.

 - Maíz Grado 2🥈: Grain Norte SAC es el principal proveedor con 405 mil toneladas, mientras Richardson International ocupa el segundo lugar con 308 mil toneladas.

Esta visualización facilita la comparación directa entre proveedores y destaca a Dreyfus Commodities y Grain Norte SAC como los principales importadores en sus respectivas categorías.

![image](https://github.com/user-attachments/assets/827a6c46-8ea4-483c-9b75-66d6fad67896)

## P7. ¿CUÁL ES EL PORCENTAJE DE PARTICIPACIÓN TRIMESTRAL DE CADA PRODUCTO POR EL PAÍS DE ORIGEN?
Se utilizo el gráfico de barras para visualizar el porcentaje de participación trimestral por cada producto, según el país de origen.

- Producto 1: Durante el año 2024 (incorporación del producto organico), se observa el crecimiento porcentual por cada trimestre. Llegando al siguiente trimestre con 7.61% y finalizando con 11.66% proveniente de Argentina.

- Producto 2: También tuvo un incremento porcentual, pasando de 7.12% hasta 10.20%, proveniente de EE.UU.

- Producto 3: Del mismo modo, se incremento hasta finalizar el año con un 8.94%, habiendo iniciado con un 5.8%, proveniente de Estados Unidos.

Esta visualización facilita la comparación directa entre productos según su país de origen.

![image](https://github.com/user-attachments/assets/6c604cae-4cec-47a3-810c-a7eb9f32a537)

## P8. ¿CÓMO HA SIDO LA EVOLUCIÓN DE LOS PEDIDOS TIPO CONTADO Y PEDIDOS TIPO CRÉDITO EN RELACIÓN AL TOTAL DE PEDIDOS POR TRIMESTRES A PARTIR DEL 2024?
El gráfico utiliza líneas para visualizar la evolución de los pedidos tipo contado, pedidos tipo crédito y el total de pedidos por trimestre desde 2024.

- Pedidos Contado: Presentan una tendencia fluctuante con varios trimestres sin pedidos, alcanzando un pico de 3 pedidos en el 2025-4.
- Pedidos Crédito: Varían principalmente debido a los cambios en los pedidos contado cerrando el 2026-4 en alza.
- Total de Pedidos: Se mantienen constantes en 9 pedidos por trimestre, mostrando estabilidad.

![image](https://github.com/user-attachments/assets/fdc1da64-bae7-4158-b71d-ee72ed442152)

## P9. ¿CUÁL ES LA CORRELACIÓN ENTRE EL VOLUMEN DE IMPORTACIÓN Y EL VOLUMEN DE PEDIDOS DURANTE LOS TRIMESTRES DEL 2023 Y 2024?
El gráfico de dispersión nos permite visualizar la relación entre dos variables y detectar patrones. En este caso, se presenta una correlación positiva, es decir, a medida que el volumen de pedidos por producto aumenta, el volumen de importación también se incrementa.

![image](https://github.com/user-attachments/assets/53ac3179-9600-4c8f-b733-6d31faa1e9d5)

## P10. ¿CUÁL ES LA VARIACIÓN DE LOS INGRESOS Y LOS COSTOS QUE INCURREN EN LA IMPORTACIÓN DEL MAIZ DURANTE LOS TRIMESTRES DEL 2023 Y 2024?
El gráfico más apropiado para visualizar de manera correcta una fluctuación es el de cascadas y, para obtener la información, hemos utilizado una columna calculada para poder parametrizar las diferencias respecto a los ingresos y costos de trimestre de los años 2023 y 2024.
Para lo cual obtenemos que en el periodo 2023:
 - El primer trimestre tuvo un aumento de 48,000 respecto al trimestre anterior.
 - El segundo trimestre tuvo un aumento de 94,000 respecto al trimestre anterior.
 - El tercer trimestre tuvo un aumento de 26,000 respecto al trimestre anterior.
 - El cuarto trimestre tuvo una disminución de 12,000 respecto al trimestre anterior.

![image](https://github.com/user-attachments/assets/bdd1277e-1c46-48cf-8cbd-9bd9d88227da)

Respecto al periodo 2024:
 - El primer trimestre tuvo un aumento de 251,000 respecto al trimestre anterior.
 - El segundo trimestre tuvo un aumento de 87,000 respecto al trimestre anterior.
 - El tercer trimestre tuvo un aumento de 64,000 respecto al trimestre anterior.
 - El cuarto trimestre tuvo un aumento de 39,000 respecto al trimestre anterior.

Gracias al gráfico que estamos presentando, podemos observar fácilmente el aumento acumulado de cada uno de los periodos, teniendo como sobresaliente al primer trimestre del 2024.

![image](https://github.com/user-attachments/assets/634afc15-ed7f-4b77-8333-0fb511932053)

¡GRACIAS!
