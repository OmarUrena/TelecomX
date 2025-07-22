

# **Telecom X - Análisis de Evasión de Clientes**
Proyecto Telecom X- ONE Alura

He sido contratado como asistente de análisis de datos en Telecom X para colaborar en el proyecto **"Churn de Clientes"**. La empresa está enfrentando una alta tasa de cancelaciones de servicios y mi objetivo es contribuir a identificar los factores que influyen en la pérdida de clientes.

Mi responsabilidad será recopilar, procesar y analizar los datos disponibles, utilizando **Python** y sus principales bibliotecas. A partir del análisis, el equipo de Data Science podrá desarrollar modelos predictivos más precisos y diseñar estrategias efectivas para reducir la evasión.

Durante este proyecto voy a:

* ✅ Importar y manipular datos desde una API de forma eficiente.
* ✅ Aplicar el proceso **ETL (Extracción, Transformación y Carga)** para * preparar los datos.
* ✅ Crear visualizaciones estratégicas que permitan detectar patrones y tendencias relevantes.
* ✅ Realizar un **Análisis Exploratorio de Datos (EDA)** y generar un informe con los principales hallazgos e insights.
### Introducción
Este informe tiene como objetivo revelar información importante a la compañía TelecomX acerca de la emergente tendencia de cancelación de servicios de sus clientes. Basándome en un conjunto de datos de los clientes de la compañía, se ha hecho un proceso de ETL (Extracción, Transformación y Carga) para obtener insights que puedan ayudar a la toma de decisiones para mejorar esta problemática.

### Limpieza y tratamiento de datos
Los datos proporcionados vienen de una API en formato JSON. Por ende, requerían una serie de transformaciones para poder trabajar con el conjunto de datos.

1. Se normalizaron las columnas cuyos valores eran objetos JSON.
2. Se eliminaron valores nulos y vacíos del dataset.
3. Se corrigieron valores inesperados en las columnas.
4. Agregamos la columna Cuentas_Diarias para tener una mejor idea del gasto diario de cada cliente.

### Análisis exploratorio de los datos
Luego de tratar los datos correctamente, seguía la parte del análisis de los datos.

1. Graficamos la proporción de cancelación de subscripción entre los usuarios en el dataset.

<img width="513" height="466" alt="image" src="https://github.com/user-attachments/assets/2f46bdd0-d3e4-4684-b7d8-a8dc089a2642" />


2. Visualizamos la relación entre las variables categóricas como *Género, Servico de Internet, Método de pago y Tipo de contrato*, con el abandono de los clientes.

<img width="1000" height="1000" alt="newplot (1)" src="https://github.com/user-attachments/assets/3fb89395-e999-4ade-a20a-73d8a1f184d5" />


3. Graficamos también la comparación entre los **gastos mensuales** de los clientes que abandonaron y los que no.

<img width="538" height="539" alt="image" src="https://github.com/user-attachments/assets/e95449cb-a512-4233-bfc6-ed210e5196a3" />


4. Por último, revisamos la correlación entre las variables numéricias del dataset y la cancelación.

<img width="601" height="181" alt="image" src="https://github.com/user-attachments/assets/05a64f76-5feb-41b4-8071-161aae0fe68c" />


### Conclusiones
Luego de un arduo análisis de los datos, podemos obtener las siguientes conclusiones:

1. El género no parece guardar ninguna relación con la cancelación de los clientes, pues la distribución entre hombres y mujeres es muy pareja.

2. Los clientes que más cancelaron tenían un contrato renovado **mensualmente**, al contrario, los clientes con planes de 1 o 2 años no mostraron altas cancelaciones.

3. El método de pago con mayores cancelaciones fue el de **electronic check (revisión electrónica)**, mientras que los otros métodos de pago mostraron muy bajas cancelaciones.

4. El servicio de internet con el que los usuarios tienen a cancelar más es con **fibra óptica**, mostrando una cantidad de cancelaciones evidentemente mayor al **DSL**.

5. La media de **pagos mensuales** de los clientes que cancelaron es significativamente más alta que los que no lo hicieron, eso puede atribuirse a que los clientes que abandonaron tenían contratados una mayor cantidad de servicios.


### Recomendaciones:
Basado en los insights detallados anteriormente, he podido formular las siguientes recomendaciones para TelecomX:

1. **Promover** los planes de contrato a largo plazo (1 o 2 años) para reducir significativamente la tasa de cancelación. Usar herramientas como descuentos y promociones para los planes de 1 o 2 años para mantener a los clientes suscritos a la compañía.

2. **Agregar** descuentos a pagos con tarjeta de crédito, ya que es el método de pago con menor tasa de cancelación. Además, fomentar el pago automático ayuda a reducir costos operativos y a asegurar la permanencia del cliente.

3. **Revisar** la disponibilidad, efectividad y calidad del servicio de **Fibra óptica**, pues es el servicio que presenta mayores cancelaciones. Se recomienda a la empresa investigar si esta alta tasa de cancelación está relacionada con la calidad del servicio.
