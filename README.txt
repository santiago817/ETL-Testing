1_ Instalación de Herramientas:
pip install pandas
pip install great_expectations #se instala en la terminal
import pandas as pd
import great_expectations as ge



2_ Extraccion de Datos:
cree un DataFrame con informacion de clientes
idCliente, DNI, Nombre, Apellido y Fecha.
meti datos duplicados en DNI y Nombre tambien agregue valores nulos en la columna Fecha


3_Trasformacion de Datos:
lo q hice fue hacer q se limpiaran los datos duplicados y nulos despues cambie el formato Fecha


4_Carga de datos:
Los datos transformados y reparados se cargaron en una nueva variable para asegurar que no existieran duplicados ni valores nulos

5_Implementación de Pruebas Automatizadas:
use Great Expectations para crear un conjunto de pruebas automatizadas que verifican la calidad de los datos, asegurando que no haya valores nulos en las columnas

6_Reporte de Resultados:
Se generó un reporte que muestra si los datos cumplen con lo esperado y detalla cualquier problema encontrado.

