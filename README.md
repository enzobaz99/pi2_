# pi2_
# Proyecto data analitic
![](https://images.yourstory.com/cs/2/96eabe90392211eb93f18319e8c07a74/DATAANALYTICS-1686234812978.png)

ARREGLO DE DATOS:

para arreglar los datos realice estos pasos
- * Reemplace los ? por Na para indentificar los faltantes
  * Al utilizar .info sobre el dataframe me di cuenta que algunas columnasn no tenian en formato adecuado por lo que les cambie el fomrato
  * Renombre algunas columnas para yo tener mayo comprencion de los datos que utilizaba
  * Al darme cuenta que los NA superaban la mitad de los datos decidi trabajar con los NA que no me molestaran mientras los NA que si tenia que eliminar los elimine

![Captura de pantalla 2023-10-10 213239](https://github.com/enzobaz99/pi2_/assets/111725717/db755e39-1307-444e-86f9-1261df2e7048)

  * realice un analisis estadistico basico para indentificar los outliers en las columnas numericas
  * revise si habia duplicados y los elimine utilizando .drop_duplicate
  * realice una matriz de correlacion con las columnas numericas
 
![Captura de pantalla 2023-10-10 213433](https://github.com/enzobaz99/pi2_/assets/111725717/6223c86e-3649-4d79-9886-08fc2159787e)

  * cree la columna año para poder trabajar la formula del kpi


KPI:

  * Calculo la suma total de fallecidos en la tripulacion y la suma total de accidentes aéreos para la decada anterior
  * Calculó la suma total de fallecidos en la tripulación y la suma total de accidentes aéreos para los últimos 10 años.
  * Calculó la tasa de fatalidad de la década anterior y de los últimos 10 años.
  * Calculó el KPI como el porcentaje de cambio en la tasa de fatalidad
  * Cree un gráfico para visualizar el KPI.

![pi2](https://github.com/enzobaz99/pi2_/assets/111725717/d8ae9b63-087d-4929-bc80-7014b4056c64)

DASHBOARD:

![Captura de pantalla 2023-10-10 213722](https://github.com/enzobaz99/pi2_/assets/111725717/d2289088-932b-4f75-99b4-01bcbaec9e9b)
![Captura de pantalla 2023-10-10 213739](https://github.com/enzobaz99/pi2_/assets/111725717/7d8c4ea4-3e3d-49d8-95e2-7b3024b323cd)
![Captura de pantalla 2023-10-10 213751](https://github.com/enzobaz99/pi2_/assets/111725717/43ccde57-5aa7-4928-93b6-e0826c088ea7)

CONCLUSIÓN:

se vio atravez de mis graficos y de los analisis que realice que la tasa de moratalidad fue bajando al pasar los años. gracias a las investigaciones, los avances en temas tecnologicos, avances en temas de aerodinámica, investigacion de riesgos, etc.
Por loq ue el almacenar datos de accidentes y las causas o las circunstancias en las que se dan es escencial para el mejoramineto del servicio 
