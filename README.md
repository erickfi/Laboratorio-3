# Laboratorio-3
# Análisis de Nodos
**Autores:** Figueroa Erick, León Steven, Viracucha William
# 1. Planteamiento del Problema

Al analizar un circuito, encontramos que este se conecta a una fuente de voltaje, o fuente de corriente, por dos lineas, cables, que permiten el flujo de corriente, sin embargo, el proceso involucrado no solo permite que la corriente ingrese al circuito, sino que regrese a la fuente, es por ello que encontramos una fase, positivo, y un neutro, negativo, sin embargo, el valor que regresa a la fuente no es el mismo que salió, esto se debe a la *Ley de la Conservación de la Energía.*

Al analizar las *Leyes de Kirchhoff* podemos deducir 2 cosas fundamentales:
- La corriente de bifurca en un nodo.
- La corriente recorre por un camino cerrado.

Por otro lado, el voltaje realiza el mismo recorrido que la corriente, de aqui se deduce que cada linea tiene su voltaje, simplificandolo, se puede encontrar voltaje en los nodos del circuito.

# 2. Objetivos
- Comprobar experimentalmente el análisis de nodos.
- Analizar e identificar los nodos en los que el voltaje será diferente al de la fuente.
- Comprender y explicar la forma de medir la corriente en un nodo.

# 3. Marco Teórico 

Un nodo es un punto de un circuito donde están conectados dos o más elementos, por el que circula corriente y por ende voltajes, la *Ley de Corriente de Kirchhoff* permite expresar corrientes en forma de voltaje, empleando la *Ley de Ohm* ya que si tenemos un elemento como un resistor, la tensión del elemento será igual a la diferencia de las tensiones de sus nodos.

Para determinar las tensiones en los nodos, primeramente se debe seleccionar un nodo de referencia, al cual se le asigna una tensión V=0, por lo general este nodo de referencia será el nuetro, negativo, del circuito, después se analiza los nodos restantes y se debe aplicar la *Ley de Corrientes de Kirchhoff* para cada uno de los n - 1 nodos, despúes se usa la *Ley de Ohm* para relacionar las corrientes en forma de voltaje.

La diferencia de potencial a la que está sometida una resistencia es igual al voltaje antes de la resistencia menos el voltaje después de la resistencia. Con esto construiremos nuestras ecuaciones para cada nodo. Necesitamos primero escoger el sentido de las corrientes tomando en cuenta que cuando hay una fuente de voltaje la corriente sale del positivo de la fuente. Si no hay una fuente se asume que todas las corrientes fluyen de izquierda a derecha y de arriba hacia abajo.

# 4. Diagramas

- Circuito para el análisis de nodos

![](https://github.com/erickfi/Laboratorio-3/blob/master/img/Diagrama-3.PNG)

# 5. Lista de componentes

![](https://github.com/erickfi/Laboratorio-3/blob/master/img/materiales-3.PNG)

# 6. Tabla de resultados

| Nodo | Resultados Analíticos | Resultados Simulados | Error |
| ------------- | ------------- |------------- |------------- |
|1 | 2.82 V | 2.82 V| 0% |
| 2 | 4.8 V | 4.8 V | 0% |
| 2-1 | 1.98 V | 1.98 V | 0% |

# 7. Conclusiones

- Usando la *Ley de Corrientes de Kirchhoff* y la *Ley de Ohm* se realiza el análisis de las corrientes en un nodo y se la puede expresar como tensión.
- El voltaje de un elemento en un circuito será la diferencia de tensión entre los nodos a los que se conecta el elemento.
- Al observar la tabla se puede evidenciar que el error es de 0%, por lo tanto, no hay pérdida de energía en los nodos.

# 8. Recomendaciones

- Elegir a la linea de neutro como el nodo de referencia.

# 9. Cronograma

![](https://github.com/erickfi/Laboratorio-3/blob/master/img/cronograma-3.PNG)

# 10. Bibliografía

- https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-node-voltage-method
- http://panamahitek.com/ley-de-las-corrientes-de-kirchhoff-metodo-de-nodos/
- https://mielectronicafacil.com/analisis-de-circuitos/teorema-de-nodos/#Dibujar-trayectoria-de-las-corrientes

# 11. Anexos

- https://github.com/erickfi/Laboratorio-3/blob/master/C%C3%A1lculos/C%C3%A1lculos.pdf







