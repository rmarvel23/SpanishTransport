# PRUEBA TÉCNICA: ANÁLISIS DE DATOS DE TRANSPORTE PÚBLICO EN ESPAÑA

## Partes:

### Código en Jupyter
En este documento encontramos código comentado que nos guía paso a paso para subir el archivo CSV, examinar su contenido, limpiarlo, transformar datos y mostrar gráficos que nos ayuden a encontrar patrones en él. He utilizado `seaborn` y `matplotlib`. Con esta última librería se pueden hacer gráficos mucho más elaborados, pero al menos aquí podemos hacernos una idea del uso que se le puede dar. También hemos creado una tabla de manera manual y la hemos unido a la nuestra a través de un JOIN. Posteriormente, hemos volcado nuestros datos en una base de datos creada en SQL Server y hemos realizado consultas en ella. Finalmente, hemos terminado de preprocesar los datos para su posterior entrenamiento con Machine Learning.

### Dashboard en PowerBI
En este dashboard interactivo podemos filtrar los datos por tipo de transporte, día de la semana y mes. Los datos que obtenemos son:
- El número de pasajeros total por ruta (siglas) en un gráfico de barras.
- La media de viajes por ruta en otro gráfico de barras.
- La media de duración de los viajes y el número de pasajeros en un gráfico de dispersión donde el color muestra el tipo de transporte y el tamaño de las burbujas el número de pasajeros.
- Un gráfico de líneas con los viajes en total según la hora del día.
- Otro gráfico de líneas con la media de los minutos de retraso por hora del día.

### Dashboard en Tableau
Este dashboard se puede consultar pulsando en este [enlace](https://public.tableau.com/app/profile/roc.o.mart.nez.veloso/viz/Anlisis_Transporte/Dashboard1). Aunque hiciera el dashboard en PowerBI, también quería hacer una pequeña muestra de lo que es capaz de hacer esta otra herramienta con mucho potencial. Aquí vemos varios gráficos de barras con los que se puede interactuar con los filtros personalizados de: día de la semana, mes y tipo de transporte.

## Comentarios adicionales:
- Es importante comprobar que el archivo CSV está subido en Jupyter para su lectura.
- El código para insertar los datos en la base de datos SQL puede dar error, porque la base de datos ya está creada y porque la he creado desde mi servidor. Habría que subir el archivo SQL a SQL Server y cambiar el nombre de “server” en el código.
- La parte final de preprocesamiento de datos para Machine Learning podría extenderse. No sé si esta materia se imparte en el máster, pero si estuvierais interesadas, a mí me encantaría hacer un apartado breve pero conciso para que las alumnas sepan enfrentarse a técnicas básicas de aprendizaje automático supervisado. Es un ámbito que se va aplicando cada vez más en muchas empresas y les abriría muchas puertas.
- También podríamos adentrarnos un poco en el ámbito de la Programación Orientada a Objetos o el NLP, en los cuales tengo bastante experiencia. Una propuesta sería, si no da tiempo impartir ciertas materias como estas en clase, subir vídeos en diferido a la plataforma para que puedan estudiarlas ellas mismas y preguntar las dudas directamente en las tutorías.
- Si tenéis cualquier problema o duda con el código, podéis escribrirme a: rmartinezveloso@gmail.com
