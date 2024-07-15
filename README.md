# Análisis de red social en Twitter: Familiarización con tareas y herramientas
## Introducción
Este proyecto se ha realizado como parte del módulo de Text mining y redes sociales del Máster Data Science, Big Data & Business Analytics de la Universidad Complutense de Madrid. El objetivo principal ha sido familiarizarse con las tareas y herramientas utilizadas en el análisis de redes sociales, aplicándolas a un caso de estudio concreto en Twitter.

El proyecto se basa en una [base de datos](https://github.com/luisgasco/ntic_master_datos/files/10912179/datos_ejercicio_twitter.zip) generada por el profesor [Luis Gascó](https://github.com/luisgasco) a partir de la shared-task [SocialDisNER](https://temu.bsc.es/socialdisner/) (2022). La base de datos incluye información sobre 100 cuentas seed de Twitter y sus seguidores.

### Librerias utilizadas
<table style="border-collapse: collapse; width: 100%;">
        <tr>
            <th style="text-align: center; padding: 10px; "><img src="https://avatars.githubusercontent.com/u/388785?s=200&v=4" alt="NetworkX logo"></a></th>
            <th style="text-align: center; padding: 10px; "><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/84/Matplotlib_icon.svg/240px-Matplotlib_icon.svg.png" alt="Matplotlib logo"></a></th>
            <th style="text-align: center; padding: 10px;"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSz1PzGID0hvBb8sIctrCeNDwx8yKhUgOD3pA&s" alt="Pandas logo"></a></th>
            <th style="text-align: center; padding: 10px;"><img src="https://avatars.githubusercontent.com/u/22799945?s=200&v=4" alt="SeaBorn logo"></a></th>
            <th style="text-align: center; padding: 10px;"><img src="https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcTCGsN1edx5u_YZ6RsLlmWid2xh9hhjK5Pp5Hx346XWiNSjohsG" alt="NumPy logo"></a></th>
        </tr>
        <tr>
            <th style="text-align: center; padding: 10px;"><a href="https://networkx.org/">NetworkX</a></th>
            <th style="text-align: center; padding: 10px;"><a href="https://matplotlib.org/">Matplotlib</a></th>
            <th style="text-align: center; padding: 10px;"><a href="https://pandas.pydata.org">Pandas</a></th>
            <th style="text-align: center; padding: 10px;"><a href="https://seaborn.pydata.org/">SeaBorn</a></th>
            <th style="text-align: center; padding: 10px;"><a href="https://numpy.org">NumPy</a></th>
        </tr>
    </table>


    
## Metodología
El análisis se ha llevado a cabo en las siguientes etapas:

### Descarga de datos 
Se han descargado los datos de la [base de datos](https://github.com/luisgasco/ntic_master_datos/files/10912179/datos_ejercicio_twitter.zip) proporcionada por Luis Gascó.
### Creación de la red
Se ha creado una red social a partir de los datos, utilizando la biblioteca NetworkX.
### Análisis topológico
Se ha analizado la topología de la red mediante el conteo de aristas y grafos y la representación de aquellos nodos con mayor número de aristas de entrada y salida.
### Análisis de conectividad de red
Se ha analizado la conectividad de la red, la longitud de los _short paths_ y el coeficiente de _clustering_.
### Análisis de relevancia de nodos
Se ha analizado la relevancia de los nodos, calculando medidas como la centralidad de cercanía y el PageRank.
### Visualización de la red
Se ha visualizado la red.
#### Representación visual de la red social

![img](https://github.com/Simon-Corpa/SocialDisNER_analysis/blob/main/Representaci%C3%B3n%20generada.png?raw=true)

## Resultados
Dentro del Notebook se pueden observar bloques de Markdown con conclusiones entorno a las distintas medidas y representaciones obtenidas, además de las propias representaciones y tablas.
|
