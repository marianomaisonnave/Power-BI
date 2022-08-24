Este proyecto gira en torno al Subte de Buenos Aires. El principal objetivo es describir la red actual, cuantificar la demanda de viajes, identificar picos de demanda. Valorar el sistema actual, diagnosticar las disfunciones del Subte de Buenos Aires, para poder proponer correcciones/intervenciones concretas, respondiendo las siguientes preguntas: 
¿Cuántos pasajeros transporta la red de subte?
¿Cuáles son las estaciones que tienen el mayor tránsito de pasajeros?
¿Cómo es la evolución del tráfico?
¿Cuáles son las franjas horarias con mayor densidad de pasajeros?
¿Y los días de la semana?
¿Hay relación con la variación en las tarifas?
¿Qué recomendaciones podríamos realizar?
¿Qué otros datos podríamos incorporar a nuestro análisis para poder ofrecer otras propuestas?

Para dicho proyecto nos brindaron los dataset de molinetes de Buenos Aires Data. 
El proceso de ETL tuvo sus complicaciones debido al tamaño de los datasets. Cada cambio que aplicábamos en Power Query demandaba mucho timpo de carga, lo cual atrasaba mucho el proyecto. A medida que íbamos generando las primeras visualizaciones, descubrimos errores en los datos y faltantes en los mismos. Por ej, el dataset correspondiente al año 2013, sólo contenía información entre los meses de Julio y Diciembre, por lo cual tuvimos que optar por excluirlo del análisis. De la misma manera, el dataset correspondiente al año 2022 sólo contenía información para el mes de Abril. Con respecto al dataset correspondiente al año 2021, nos encontramos con una disminución muy abrupta en la canidad de viajes, lo cual indica que ésta merma debía corresponder al período más estricto del confinamiento por la pandemia de COVID-19 y debía corresponder al año 2020. En otros datasets, nos encontramos con un error en el cálculo del total de pasajeros, lo cual debimos subsanar. Debido a todos estos detalles, hubo datasets que no pudimos tener en cuenta para el proyecto. En conclusión, uno de los principales hallazgos fue identificar los errores que contenían los datasets y los faltantes de datos en los mismos. Como agregados, decidimos incluir información referida a estaciones accesibles, con indicadores de la cantidad de escaleras mecánicas y ascensores en las estaciones. Decidimos adoptar como principio de accesibilidad la presencia de ascensores, para concluir que aquellas que no cuentan con los mismos, deberían ser las estaciones en las que habría que poner el foco de atención para realizar modificaciones y adaptarlas. Por último, adoptamos una mirada desde el punto de vista del marketing, al considerar que las estaciones con mayor tránsito de pasajeros pueden ser de interés para el establecimiento de espacios publicitarios y comercios.
