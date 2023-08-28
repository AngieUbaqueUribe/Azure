# Azure
Creado: Angie Hasbleidy Ubaque Uribe
Fecha:24/08/2023

Proyecto realizado en Azure
Se creo un grupo de recursos con un datalake y azure data factory

En el Datalake se maneja la arquitectura de medallones (Bronze, Silver, Gold)

En Azure data factory se creo un proceso completo de extraccion transformacion y carga

En la capa bronze se almacenan los datos crudos de la nomina, la utilizacion y la proyeccion por proyecto por medio de un pipeline
En la capa silver se cargo con el pipeline que ejecuta un dataflow que hace join calculos y generacion de data transformada
En la capa Gold de realiza por medio de otro pipeline el join de la nomina y la proyeccion para saber la rentabilidad de los proyectos

Todo se orquesta por medio de un pipeline maestro.
