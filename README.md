# pi2_
# Proyecto data analitic
![](https://principia.es/wp-content/uploads/2020/05/SImulacion-numerica-sector-aeronautico-iStock-497848807-e1557919837219-1536x827.jpg)

CONTEXTO:

Los accidentes aereos pueden ocurrir por por diversos factores como ser, errores humanos, fallos de equipos, problemas meteorológicos, problemas de mantenimiento, fallas en la gestión del tráfico aéreo, problemas de diseño o problemas de fabricación. Esto llevaria tanto a pérdidas económicas como pérdidas de vidas en tierra y que estaban en el vuelo.

Es por eso que la industria de la aviación y las autoridades reguladoras trabajan para mejorar la seguridad y prevenir accidentes. Para ello necesitan investigar, estudiar la causalidad de los accidentes y aprender a cómo prevenirlos en el futuro, ya que esto es la clave para evitar pérdidas tanto económicas como de personas

ROL A DESARROLLAR:

La Organización de Aviación Civil Internacional (OACI), organismo de la Organización de las Naciones Unidas, quiere investigar en profundidad los accidentes producidos desde inicios del siglo XX. Para ello, el objetivo principal es poder obtener un análisis de datos relacionado a esto, junto a un dashboard que complemente los análisis con sus visualizaciones.

ARREGLO DE DATOS:

para arreglar los datos realice estos pasos
- * Reemplace los ? por Na para indentificar los faltantes
  * Al utilizar .info sobre el dataframe me di cuenta que algunas columnasn no tenian en formato adecuado por lo que les cambie el fomrato
  * Renombre algunas columnas para yo tener mayor comprencion de los datos que utilizaba
  * Al darme cuenta que los NA superaban la mitad de los datos decidi trabajar con los NA que no me molestaran mientras los NA que si tenia que eliminar los elimine
  * realice un analisis estadistico basico para indentificar los outliers en las columnas numericas
  * revise si habia duplicados y los elimine utilizando .drop_duplicate
  * realice una matriz de correlacion con las columnas numericas
  * cree la columna año para poder trabajar la formula del kpi
los pueden visualizar en [mi EDA](https://github.com/enzobaz99/pi2_/blob/main/EDA.ipynb)

KPI:



reduccion de la tasa de mortalidad:

  * Calculo la suma total de fallecidos en la tripulacion y la suma total de accidentes aéreos para la decada anterior
  * Calculó la suma total de fallecidos en la tripulación y la suma total de accidentes aéreos para los últimos 10 años.
  * Calculó la tasa de fatalidad de la década anterior y de los últimos 10 años.
  * Calculó el KPI como el porcentaje de cambio en la tasa de fatalidad
  * Cree un gráfico para visualizar el KPI.


DASHBOARD:

Atravez de esto quiero que entiendan a que es lo que apunte con mi trabajo, para ello realice 3 paginas en power bi

 * En la primera pagina es para visualizar la cantidad de accidentes, fallecidos y personas a bordo segun el tipo de vuelo o la aeronave que relizaba el vuelo
 * En la segunda pagina les muestro la cantidad de fallecidos y los muertos en tierra. aparte de esto les muestro un mapa de donde salieron los vuelos
 * En la tercera pagina les muestro la tasa de supervivencia de los pasajeros y de la tripulacion
 * En la cuarta pagina les muestro la tasa de fatalidad de la ultima decada comparada con la de la decada anterior
 * En la quinta pagina hago una prediccion de lo que es posible que pase con la industria aerea

CONCLUSIÓN:

se vio atravez de mis graficos y de los analisis que realice que la tasa de moratalidad fue bajando al pasar los años. gracias a las investigaciones, los avances en temas tecnologicos, avances en temas de aerodinámica, investigacion de riesgos, etc.
Por loq ue el almacenar datos de accidentes y las causas o las circunstancias en las que se dan es escencial para el mejoramineto del servicio 
