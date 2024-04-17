# **PROYECTO INDIVIDUAL Nº2**
# **Siniestros viales en CABA**

## Introducción

El **Observatorio de Movilidad y Seguridad Vial** (OMSV), centro de estudios que se encuentra bajo la órbita de la **Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires**, nos solicita la elaboración de un proyecto de anális de datos, con el fin de generar información que le permita a las autoridades locales tomar medidas para disminuir la cantidad de **víctimas fatales de los siniestros viales**. Para ello, nos disponibilizan un dataset sobre homicidios en siniestros viales acaecidos en la Ciudad de Buenos Aires durante el periodo **2016-2021**. Este dataset se encuentra en formato xlsx y contiene dos hojas llamadas: hechos y víctimas. Asimismo, observarán que incluye otras dos hojas adicionales de diccionarios de datos, que les podrá servir de guía para un mayor entendimiento de la data compartida.

## Tecnologias y herramientas usadas

Se uso **Python** con librerias como **Seaborn** y **Pandas** para la extraccion, analisis y tratamiento de los datos, esto fue puesto en un cuaderno de **jupyter** para una mejor lectura y orden del EDA.
Con el servicio de **[freesqldatabase](https://www.freesqldatabase.com/)** se monta una base de datos **MySQL** y se cargan los CSV exportados en el EDA.
En **Power Bi** realizamos el dashboard con analisis Temporal, Geografico, Demografico y la medicion de los KPI's

## Metodologia

Se realiza el EDA analizando outliers, duplicados, valores faltantes y en general las distintas variables de los datasets luego se exportan los CSV con los datos limpios.
<div style="display: flex;">
    <img src="Imagenes\EDA1.JPG" alt="EDA1" style="width: 50%;">
    <img src="Imagenes\EDA2.JPG" alt="EDA2" style="width: 50%;">
</div>
Se crea una base de datos MySQL y se importan los datasets desde los CSV.
<div style="display: flex;">
    <img src="Imagenes\MySQL.JPG" alt="MySQL1" style="width: 50%;">
    <img src="Imagenes\MySQL2.JPG" alt="MySQL2" style="width: 50%;">
</div>
Luego se crea la conexion de Power BI con la base de datos y se importan las tablas que se requieran.
<div style="display: flex;">
    <img src="Imagenes\conexionSQL.JPG" alt="con1" style="width: 50%;">
    <img src="Imagenes\conexionSQL2.JPG" alt="con2" style="width: 50%;">
</div>
Con los datos listo en Power BI se crean las relaciones entre las tablas y metricas que necesitamos para el analisis de los KPI's.
<div style="display: flex;">
    <img src="Imagenes\Powerbi1.JPG" alt="pbi1" style="width: 50%;">
    <img src="Imagenes\Powerbi2.JPG" alt="pbi2" style="width: 50%;">
</div>
Todo listo solo queda crear el dashboard y presentar los KPI's.
<div style="display: flex;">
    <img src="Imagenes\Powerbi3.JPG" alt="pbi3" style="width: 50%;">
    <img src="Imagenes\Powerbi4.JPG" alt="pbi4" style="width: 50%;">
</div>

## Informe de KPI's
Se plantean 3 KPI's:
- Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior
    - El cumplimiento del KPI se evidencia en una disminución significativa de la tasa de homicidios en comparación con el semestre anterior, donde la tasa era de 1.77 al alcanzar una tasa de 1.35 en el semestre posterior, se supera el objetivo establecido.

- Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.
    - En el incumplimiento del KPI se nota un aumento atipico de la cantidad de accidentes siendo que en lugar de reducir un 7% aumentaron un 70%, esta cifra atípica puede estar influenciada por las restricciones de movilidad impuestas debido a la pandemia.
- Reducir en un 15% la cantidad de accidentes mortales de peatones que son personas mayores respecto al año anterior.
    - El cumplimiento del KPI de reducción del 15% se ha logrado de manera satisfactoria. La disminución de la cifra de 16 accidentes mortales en el año base a 13 en el año actual indica un progreso significativo en la protección de esta población vulnerable.

    

# PI_DA
# PI_DA
