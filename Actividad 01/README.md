# imt2200-Actividad 1
 # Introduccion
En esta actividad se aprendio, exploro y uso GitHub en conjunto con Jupyter. Luego se realizo la clonacion del repositorio del curso, donde se creo un repositorio público personal con un archivo README que incluye el nombre del alumno(Liz Ester Gonzalez Guzman), asimismo se trabajo en un notebook de Jupyter para visualizar un mapa de Santiago con la población por comuna usando colores, y finalmente se subieron los archivos actualizados al repositorio para entregar el enlace de la actividad.
# Desarrollo de la Actividad en Notebook Jupyter (archivo formato ipynb)
En la actividad se lograron hacer los siguientes procedimientos:
- Interpretacion de Datos del censo 2017.
- Visualizacion de Datos del censo 2017 con las herramientas para ciencia de datos.                             
- Crear un mapa, donde en el se logro hacer lo siguiente:
  - Cambiar XXX por mi apellido como pide la actividad.
  - Editar el color del mapa en cmap="Reds" a cmap="plasma", en la siguiente linea de codigo "manz.plot(ax=ax, column='TOTAL_PERS', cmap='plasma', legend=True, vmin=0, vmax=1000)". Explicacion: Se escogio porque entre menos poblacion hay en una manzana, serian zonas frias por lo que tendria un color morado oscuro y entre mas junta esta la poblacion esta tendria un color amarillo brillante, pues serian zonas calidas. La razon del cambio es por el paralelismo en como se ve el calor en las camaras termicas(por el calor que emana la poblacion humana).
  - Editar la separacion de la leyenda y el mapa desde pad=0.1 a pad=0.5, por mero interes propio.
 # Herramientas Utilizadas
De forma interactiva con Jupyter Notebook y usando la ide VScode, se utilizaron las siguientes herramientas:
- Pandas
- Matplotlib
- Geopandas
- NumPy
# Referencias
- https://matplotlib.org/stable/users/explain/colors/colormaps.html
- https://docs.github.com/es/get-started/using-github/github-flow

### Nota personal:"Estoy muy feliz de iniciar este nuevo viaje en la ciencia de datos <3."
