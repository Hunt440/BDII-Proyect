Descripción breve del proyecto

El proyecto actual consistió en modelar y diseñar una red logística urbana con Neo4j, donde los almacenes, las intersecciones y los puntos de entrega se representaron como nodos y las conexiones viales como relaciones ponderadas que contenían atributos tales como el tiempo estimado, la distancia y la situación del tráfico.
Se elaboró una proyección en memoria con la librería Neo4j Graph Data Science, lo cual posibilitó llevar a cabo algoritmos de caminos mínimos, como A* y Dijkstra, para establecer rutas ideales bajo diversos parámetros de optimización.
El proyecto evidenció que el análisis de la conectividad y la optimización de rutas en tiempo real son simplificados mediante una perspectiva fundamentada en grafos, lo cual brinda una solución más apropiada que los modelos relacionales tradicionales para las dificultades logísticas que giran en torno a relaciones complejas.

--Tecnologías empleadas
Neo4j
Neo4j Graph Data Science
APOC

--Requisitos previos
Neo4j Desktop
GDS instalado
APOC instalado

--Estructura del Proyecto
Script_carga_bd
consultas_datos_bd.cypher
README.md
Informe tecnico - Grupo Angel G Glihanny S Cesar R.pdf

Como replicar la ejecución del proyecto

Paso a paso:
1. Crear una instancia que aloje a la base de datos. Crear y nombre la base de datos en el programa Neo4j, bajo el nombre que guste.
2. Ejecutar Script_carga_bd.cypher
3. Ejecutar consultas_datos_bd.cypher

--Funcionalidades implementadas

 Optimización por distancia (Dijkstra)
 Optimización por tiempo (A*)
 Restricción por peso
 
--Autores
Angel Gonzalez - C.I: 30.366.096
Cesar Reyes - C.I 29.906.628
Glihanny Sotillo - C.I 27.766.805
