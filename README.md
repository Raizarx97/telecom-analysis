# telecom-analysis

## Objetivo del Proyecto
Análisis de patrones de uso, comportamientos atípicos y segmentos de clientes de la empresa ConnectaTel.

## Datasets Utilizados

Se utilizaron los siguientes datasets:

- **plans.csv:** los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
- **users_latam.csv:** información de clientes: edad, ciudad, fecha de registro, plan contratado.
- **usage.csv:** el detalle de uso real: llamadas (duración) y mensajes (longitud).

## Etapas de análisis realizadas

- Se hizo limpieza y estandarización de datos.
- Se reemplazaron sentinels por valores nulos o la mediana dependiendo de la columna.
- Se combinaron los datasets de usuarios y uso.
- Se calculo el total de mensajes, total de llamadas y el total de minutos de llamada utilizados.
- Se obtuvieron gráficos del comportamiento de las columnas del punto anterior, en base a los planes.
- Se segmento a los clientes por edad y por uso.
- Se grafico en base a grupos de edad y grupos de uso.

## Ejecutar el notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Raizarx97/telecom-analysis/blob/main/S7-Analisis-ConnectaTel.ipynb)

## Guía de Reproduccion.

- Abre el notebook en Colab.
- Da clic en "Run All".
