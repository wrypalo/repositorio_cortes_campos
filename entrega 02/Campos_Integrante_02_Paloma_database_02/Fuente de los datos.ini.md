# Ficha técnica Campos Paloma

### Fuente de los datos

Los datos que busqué fueron los cuantitativos, para los cuales tuve que buscar en muchos lados. 
Pero las principales páginas que utilicé fueron de TOP de música, específicamente TOP 20 Charts Chile y Charts around the world. 
En estos se indican las canciones y artistas posicionados entre los 20 primeros puestos por semana, y los 100 primeros puestos respectivamente. 
Es importante indicar que para poder concluir si la popularidad subió o bajó se debieron buscar los charts semanales. 
Los que usamos en la base son de fechas entre febrero 20 y marzo 10. 

### Metodología de la construcción de la base

Yo comencé buscando las fechas en las que se realiza el festival de Viña. Una vez teniendo esto,
busqué los charts de las respectivas semanas. En algunas ocasiones no encontraba el de la semana exacta,
por lo cual usaba el de la semana posterior o la anterior a la anterior del festival, siempre con un 
margen máximo de 3 semanas (la pasada al festival, la del festival y la posterior al festival).  
Después buscaba cada artista que había participado y que teníamos en nuestra BBDD, 
buscaba las veces que estaba en el chart y su posición, tanto anterior como posterior a Viña, 
para finalizar con la conclusión: ¿Subió, bajó, ingresó o se mantuvo? 

### Alcance de los datos

Los datos en internet están, pero muchas veces no existe la semana del chart en el top 100, 
o no existe el chart de Chile, por lo cual costaría mucho recopilar desde 1960 a 2025 
todos estos datos. Lo que sí pude localizar es una página que tiene todos los top 20 Chile por semana desde 2002, 
así que nuestro alcance quedará –de momento– hasta aquel año. 

### Característica de los datos

Estos datos son cuantitativos, pero el apartado si subió, bajó, se mantuvo o ingresó, 
son conclusiones cualitativas realizadas en base a los números encontrados. 

### Variables incorporadas: variable | descripción.

¿Aparece en el top 20 nacional antes del festival? → Indica si el artista estuvo presente en el ranking Top 20 Chile en la semana previa al Festival de Viña.
¿Aparece en el top 100 nacional? → Señala si el artista figuraba en el Top 100 Chile en el mismo periodo.
¿Cuántas veces aparece? → Número de canciones en las que aparece el artista en el chart. 
Posición en el chart → Lugar específico que alcanzó en el ranking durante cada semana registrada.
Peak de rating → La mejor posición alcanzada en el rating de TV en su presentación del festival.
Premios → Reconocimientos obtenidos en Viña (antorchas, gaviotas) como indicador de impacto en el público.
¿Aparece en el top 20 nacional después del festival? → Mide si el artista ingresó o se mantuvo en el Top 20 Chile tras su presentación en Viña.
¿Aparece en el top 100 después del festival? → Revisa la presencia en el Top 100 Chile en las semanas posteriores.
¿Cuántas veces aparece? → Número de canciones en las que aparece el artista en el chart. 
Posición en el chart → Posición obtenida después del festival en los rankings.
Conclusión: ¿subió, bajó, se mantuvo o ingresó? → Variable de cierre que resume la variación de la popularidad del artista considerando el antes y el después del evento.

### Otras observaciones que tengan sobre la base.

Todos los datos fueron recopilados a mano, en un proceso en el que recurrimos a bibliotecas, tanto digitales como presenciales, 
internet e IA para la búsqueda profunda en internet sobre datos antiguos. Seguimos en búsqueda de algunos datos
como los rankings 100 Chile y los peak de rating. 


