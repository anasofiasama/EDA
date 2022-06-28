# Template for Machine Learning projects

La base de datos se obtiene del URL : https://raw.githubusercontent.com/4GeeksAcademy/data-preprocessing-project-tutorial/main/AB_NYC_2019.csv

La transformación de los datos implica cambiar el tipo de dato de la siguiente manera:
- 'name','host_name': string
- 'neighbourhood_group','neighbourhood','room_type':'category
- 'last_review':datetime with format='%Y/%m/%d'

La limpieza de los datos implica:
1. Se imputan los precios de los alojamientos cuyo precio por noche es igual a 0
2. Se elimina aquellos alojamientos cuyo minimo de noches es mayor a 750

> *Nota*: No se incluye el tratamiento del precio por noche del alojamiento en Manhattan en el 2013 que parecería ser anormal, ya que se necesitaría consultar a un especialista.




