**📋 Cosas raras e inesperadas**
---
Como mencionamos en varias ocasiones a lo largo del proyecto, lo que más nos hizo pensar en diferentes hipótesis y lo que más raro se nos hacía era que el dataset solo hiciese referencia a un préstamo diario. Después de analizar más a fondo también fueron surgiendo las siguientes rarezas y cosas inesperadas:

- Los libros de las categorías poesía, divulgación y ensayo son los que tardan más en devolver. Hemos de pensar que se debe a la densidad de su contenido. Por otro lado que los cómics y los libros infantiles tengan las devoluciones más tempranas confirma la hipótesis ya que sus lecturas son ligeras y poco complicadas aunque llama la atención que la novela gráfica siendo una lectura equiparable al cómic tenga una devolución de casi el triple de tiempo. ¿Se debe a un fallo?

- Más del doble de los usuarios de la biblioteca hacen uso del servicio por las tardes imaginamos que debido a los estudios o el trabajo. Los usuarios por la mañana pueden ser jubilados, parados, trabajadores con turno de tarde etc.. pero, ¿una biblioteca que abre los domingos? Además formando parte de uno de los días con más afluencia y donde más se concentran los préstamos que es en la tarde de este mismo día. 


- Nos llamó la atención el "triunfo" del catalán por encima del inglés.

- Y por último, que por el patrón que vemos temporal reducen a servicios mínimos pero no dejan de abrir en agosto y lo que es más sorprendente, también los domingos, esto se mantiene todo el año. 

**📌Conclusión final**
---


El dataset nos muestra 261 registros de préstamos entre el 3 de enero y el 30 de diciembre de 2025. 

Observamos que los registros son más altos los cinco primeros meses, de enero a mayo, aquí tenemos el 56,7% del total de registros, con una media de 29,6 préstamos mensuales, frente a los 16 préstamos de media del resto del año. Agosto es el mes con menos datos registrados, solo 13.

Ficción es la categoría con más préstamos, 103 préstamos (39.5% del total), seguida de infantil (21,1%), cómic (13,4%) y ensayo (13,0%). Poesía es la categoría menos registrada, con solo 3 préstamos en todo el año.  
La duración de los préstamos varía según la categoría: el cómic es el único con un plazo fijo de devolución de 7 días en el 100% de sus préstamos. La categoría infantil tiene una media de 10,5 días, mientras que poesía y divulgación superan los 25 días de media, siendo las categorías de mayor duración de préstamo.

El ratio de devolución fuera de plazo es del 5,7% (15 préstamos sobre 261). Estos datos de fuera de plazo se concentran en las categorías de plazo más largo: poesía tiene la tasa más alta (66,7%), seguida de divulgación (28,6%) y ensayo (8,8%). Por el contrario, infantil, cómic y novela gráfica registran un 0% de devoluciones en fuera de plazo durante todo el período del dataset. Los libros en inglés presentan la tasa de mora más elevada por idioma (13,0%), frente al 5,3% del español y el 3,4% del catalán. La duración media de los préstamos con mora es de 23,9 días, frente a los 14,3 días de los devueltos a tiempo.
El español es el idioma con más préstamos registrados,  el 80,1% de los préstamos, seguido del catalán con el 11,1% e inglés con el 8,8%. Esta distribución refleja el perfil lingüístico de la comunidad local y la importancia de mantener un fondo diverso en múltiples idiomas.

Respecto al uso horario y temporal, la franja de tarde concentra el 66,3% de los préstamos, aunque la franja de mañana presenta una tasa de devolución tardía ligeramente superior (8,0% frente al 4,6%). Los días de mayor actividad de registros son martes y domingo, con 52 préstamos cada uno, mientras que lunes y sábado son los menos activos, con 21 registros cada uno. En cuanto a la mora mensual, Enero y Marzo presentan las incidencias más altas (10,7% y 9,7% respectivamente), siendo Junio y Octubre los únicos meses sin ningún retraso registrado.

Tras observar todos los datos obtenidos sacamos varias conclusiones, partiendo de que tenemos una ausencia muy grande de documentación para llegar a unas conclusiones definitivas.

Los días que existen registros, solo existe un registro diario, sin saber si son totales de préstamos, el primer registro del día o qué tipo de registro.

- Análisis fuera de plazo


Se puede concluir que hay una tasa muy alta de devolución dentro de plazo (94,3%), se encuentran también ciertos patrones como que los cómics se devuelven siempre a los 7 días. 
Del total de 261 préstamos, 15 fueron devueltos fuera de plazo, es decir el 5,7%.
La categoría con mayor índice de retraso es la poesía, aunque también es la categoría que menos registros de préstamo tiene,  2 de sus 3 préstamos fueron entregados fuera de plazo (66,7%).
Los préstamos en inglés muestran devoluciones más tardías más tarde  (3 de 23 préstamos - 13,0%).
Enero y marzo son los meses con más devoluciones tardías. Junio y octubre son los únicos meses sin ningún registro de préstamo de devoluciones tardías.

Como hemos podido comprobar tiene una buena biblioteca con amplias posibilidades de expansión y productividad, con más datos podríamos colaborar mucho más para lograr un gran centro.


- Las respuestas que obtenemos tras el análisis de los datos nos despiertan importantes dudas sobre la actividad de la biblioteca:

El servicio solo presta un libro al día sin cubrir siquiera los 365 días del año. Esta cuestión nos lleva a preguntarnos si en el registro solo aparece el primer libro prestado en el día o el uso de la biblioteca es marginal. 

No sabemos qué tipo de biblioteca es. La alta actividad de los domingos y el número de préstamos de libros infantiles nos permite presuponer que se trata de una biblioteca ubicada en una zona residencial familiar, pero el caótico sistema horarios con tantas mañanas y tardes sin actividad puede orientar a la posibilidad de un bibliobús que se mueva por diferentes pueblos o aldeas. Faltan datos fiables para determinar si alguna de las opciones barajadas se acerca a la realidad.

La bajada de préstamos tan brusca a partir de mayo hasta el final del año podría entenderse si la biblioteca fuese universitaria o estudiantil, pero esta hipótesis queda rechazada debido a las categorías de libros que están registradas alejándose del rango educativo.

No conocemos el volumen exacto de libros por categoría, por lo cual pensar que los libros de ficción o infantiles son los más pedidos, puede deberse a una moda de interés o simple conformismo por falta de variedad literaria.

Dentro del dataset no hay registro de devoluciones. Se necesita hacer un cálculo entre la fecha de préstamo y la duración del mismo para llegar a esa conclusión sin estar seguro de su fiabilidad. Por otra parte, tenemos diferentes límites de tiempo en el préstamo dependiendo de la categoría del libro sin especificar los motivos.

Faltan muchos datos y todos los huecos que hay alrededor se acaban llenando con imaginación sustituyendo la visión objetiva por la búsqueda subjetiva de sentido y equilibrio.

La ausencia total de registros en 104 días no tiene explicación en los datos: puede ser días cerrados, días sin préstamos, o simplemente días no registrados.
La hipótesis de bibliobús (horarios irregulares, actividad en diferentes días según franjas) es plausible pero no demostrable con estos datos.
La presencia del catalán (11,1%) por encima del inglés (8,8%) sitúa geográficamente la biblioteca con más fiabilidad que cualquier otro dato.
La alta actividad en domingo y el peso del fondo infantil apunta a biblioteca de barrio residencial familiar.
No conocemos el fondo total por categoría, así que no podemos saber si ficción lidera por preferencia o simplemente porque hay más ejemplares.
La caída brusca a partir de mayo podría indicar horario de verano reducido, cierre parcial, o simplemente menos usuarios. Los datos no distinguen entre estas opciones.
La duración de poesía (hasta 35 días) vs cómic (exactamente 7) sugiere que existen políticas de préstamo diferenciadas por categoría, pero no están documentadas en el dataset.
El comportamiento perfectamente uniforme de los cómics (todos a 7 días) contrasta con la variabilidad del resto de categorías, lo que refuerza la sospecha de que el dataset podría ser sintético o generado con reglas.


Cómic e infantil nunca generan retrasos. Son las categorías más "seguras" para la gestión de la colección.
La ficción tiene valores atípicos de duración (hay préstamos de 21 y 28 días cuando la norma es 14). Hay que investigar si son renovaciones o excepciones.
Los retrasos en domingo son los más frecuentes (4 de 15 retrasos totales). Es el día con más préstamos y también el que más retrasos acumula.
La tarde concentra sistemáticamente el doble de préstamos que la mañana en todos los meses. No es un patrón estacional, es estructural.
La divulgación tiene una tasa de retraso del 28,6% siendo la segunda peor tras poesía, pero esto apenas aparece en vuestro análisis.
Los préstamos en inglés fuera de plazo se concentran en ficción y divulgación, que son además las únicas categorías donde aparece el inglés. No se puede aislar si el retraso es por idioma o por categoría.

**👤Bitácora personal**
--- 
📌 Qué he observado


Durante este proyecto he observado las mil vueltas que podemos darle a los datos y los millones de hipótesis que podemos sacar con tan pocos datos (en comparación con una tabla de préstamos reales donde podríamos encontrar más préstamos reales). 

✨ Qué me ha sorprendido


Como cada uno poco a poco hemos ido sacando ideas y de manera natural trabajando en lo que mejor llevábamos pero siempre participando en común y ayudándonos en lo que más sabíamos cada uno.

❓ Qué preguntas me surgen


Me surge la duda de cuántos datos e ideas podemos sacar de tablas más extensas y más estructuradas, además del trabajazo que tiene que suponer (y que nosotros nos hemos evitado) limpiar los datos.

🤷 Qué no entiendo todavía


Todavía me cuesta entender las fórmulas de Google Sheets, pero creo que solo es practicar con ello un poco más. 
