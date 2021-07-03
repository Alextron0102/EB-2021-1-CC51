# EB-2021-1-CC51
Trababajo final del curso de Administración de la información CC50, profesora: Patricia Daniela Reyes Silva

## Objetivo del trabajo
El objetivo del presente proyecto es aplicar los conocimientos adquiridos en el curso de administración de la información para crear conocimiento a partir del conjunto de datos **Trending YouTube Video Statistics** al desarrollar un Análisis Exploratorio de Datos(EDA) y resolver un problema básico de Modelización de Datos, en el marco de la ejecución de un proyecto de analítica.

## Integrantes del grupo
- Ng Cubas, Martín Maeng Men
- Barrios Pérez, Alexis Enrique
- Montes Zarria, Martin Andre

## Descripción del Dataset
[Trending YouTube Video Statistics](https://www.kaggle.com/datasnaek/youtube-new)

## Conclusiones
- ¿Qué categorías de videos son las de mayor tendencia? 
Las categorías de videos con mayor tendencia son Entertainment y People and Blogs, que corresponden a las dos primeras categorías con más videos en tendencia.
- ¿Qué categorías de videos son los que más gustan? ¿Y las que menos gustan?
La categoría de videos que más gustan son: Entertainment con 228M de likes, Music con 109M de likes y Comedy con 70M de likes. Y las categorias de videos que menos gustan son: Movies con 112 mil likes, seguido de Shows con 374 mil likes y Travel & Events 1M de likes.
- ¿Qué categorías de videos tienen la mejor proporción (ratio) de “Me gusta” / “No me gusta”? 
Las categorías de video que tienen la mejor proporción (ratio) de Likes / Dislikes son News & Politics(203.64), seguido de Sports(130.61) y seguido de People & Bolds (121.59).
- ¿Qué categorías de videos tienen la mejor proporción (ratio) de “Vistas” / “Comentarios”? 
Las categorías de video que tienen la mejor proporción (ratio) de Visualizaciones / Cantidad de comentarios son Travel & Events (4036.30), Education (3435.08) y seguido de Sports (2391.79)  
- ¿Cómo ha cambiado el volumen de los videos en tendencia a lo largo del tiempo?
La cantidad total de videos vistos por año tiende a ser constante, con variaciones entre 185~195, excepto cerca a la fecha de mayo 2018, dónde no hubieron muchos videos en tendencia.
- ¿Qué Canales de YouTube son tendencia más frecuentemente? ¿Y cuáles con menos frecuencia? 
Dentro de los 3 primeros canales de YouTube que son tendencia más frecuentemente se encuentran Galleco con 200 videos en tendencia, seguido de Ruhrpottwache con 185 videos y seguido de Анатолий Шарий con 182 videos. Y dentro de los 3 últimos en tendencia se encuentran Massengeschmack-TV, Mr Whaatwaa y Mr. Damon, estos 3 con 1 video en tendencia.
- ¿En qué Estados se presenta el mayor número de “Vistas”, “Me gusta” y “No me gusta”?
Hamburg se encuentra en el primer lugar con 822M de vistas, 25.95M de Me gusta y 1.25M de No me gusta.
- ¿Es factible predecir el número de “Vistas” o “Me gusta” o “No me gusta”?
Si es factible predecirlo mediante el modelo de regresión lineal, puesto que la pendiente de la función es positiva, por lo que si las variables de vistas, me gusta o no me gusta incrementan su valor, entonces se puede predecir cuales vídeos van a estar en tendencia, pero este modelo no es factible para predecir las vistas actuales, puesto que no es del todo exacto.
- ¿Los videos en tendencia son los que mayor cantidad de comentarios positivos reciben? 
No, los videos en tendencia son los que tienen mayor visualizaciones, esto debido a que ningún video del dataset cuenta con 0 reproducciones.

## Licencia
MIT License

<!--
 ▪ - El archivo. Readme, dentro de GitHub, deberá contemplar: 
▪ Objetivo del proyecto. 
▪ Nombre de los alumnos participantes. 
▪ Breve descripción del conjunto de datos (se puede adjuntar el archivo PDF). 
▪ Conclusiones.  -->
