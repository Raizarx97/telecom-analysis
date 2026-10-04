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

## Pasos para ejecutar el notebook

```python
import foobar

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
