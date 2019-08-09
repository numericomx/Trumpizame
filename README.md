## Adventurous Social Science |
![Dos EE. UU.](/images/note_image.jpeg "Dos EE. UU.")

# El odio a los mexicanos es reforzado por el discurso antinmigrante de Trump

El pasado sábado un crimen de odio en contra de mexicanos sucedió en El Paso, Texas. En su manifiesto, el atacante retomó puntos de la retórica antinmigrante de Trump y sus seguidores. En Ñumérico creemos que las palabras importan. Consideramos que este ataque es una consecuencia de la narrativa nativista formada en los últimos años alrededor de los migrantes mexicanos en EE. UU. y que ha sido aprovechada por Donald Trump para formar su base social. Entender esa narrativa es clave para entender el contexto ideológico en que esta tragedia tuvo lugar. Para entender a profundidad, hemos creado un modelo de lenguaje que busca explicar cómo los seguidores de Trump interpretan a los mexicanos y a los migrantes.

## _Modelando el lenguaje de los seguidores de Trump_
Estamos convencidos de que podemos comprender mejor la visión de una comunidad al entender su dialecto. Las lenguas son el marco de referencia de nuestro pensamiento --- si logramos entender cómo las palabras están asociadas en la mente de una persona, podemos entender cómo sus ideas se forman. Por esta razón, comenzamos por recolectar cuatro millones de tuits pertenecientes a más de dos mil fervientes seguidores de Trump[1].

Para analizar esa enorme cantidad de tuits entrenamos un modelo de su lenguaje. Este **modelo** busca aprender el **significado** de las **palabras** estudiando el texto que usamos para entrenarlo. (Puedes leer más sobre él [aquí](https://en.wikipedia.org/wiki/Word2vec).) Al ser este un modelo **matemático**, este significado es codificado en un **vector** --un conjunto de números-- que representan toda la información representada por cada palabra.

La **distancia geométrica** entre dichos vectores cuantifica la **distancia semántica** con otras palabras. Por ejemplo, el vector de la palabra blanco estará cerca de claro pero lejos de negro. Dado que la transformación de palabras a vectores fue estimada con el texto recolectado de sus seguidores, **podemos analizar qué conceptos fueron asociados a qué ideas dentro de dicha comunidad**. 

Aquí un ejemplo del **espacio semántico** cercano a la palabra __estúpido__:
![El vocabulario de los seguidores de Trump](/charts/esp/png/01_stupid.png "Vocabulario de los seguidores de Trump")

## _¿Qué ideas son cercanas a los mexicanos en la mente de un seguidor de Trump?_
![Los 4 grandes temas](/charts/esp/png/02_illegals.png "Los 4 grandes temas")

La figura anterior muestra diferentes términos en el vecindario semántico de la palabra **mexicanos**. Podemos distinguir cuatro temas: **Inmigración**, **Crimen**, **Gobierno intervencionista** y **Empleos**. El grupo temático con mayor palabras es Crimen.

El discurso de Trump alimenta el **odio** y **miedo** de sus seguidores. Infunde el miedo hacia los extranjeros, en especial a los **latinos**. Esta transferencia de miedo es únicamente posible porque los seguidores de Trump ya están atemorizados de los migrantes: ven a los extranjeros como una masa borrosa de invasores que realizan crímenes y les roban el trabajo. Esta idea está profundamente arraigada en su visión, como veremos posteriormente. Además, dicho miedo es peligroso ya que consideramos fue el detonante de la masacre en Texas. Es un nicho perfecto para la violencia.

## _¿Por qué los seguidores de Trump tienen tanto miedo a los inmigrantes?_
Para entender como un extranjero se convierte en un enemigo, nos concentramos en dibujar un camino mental de **extranjero** a **invasor**. Hemos creado mapas mentales que crean los siguientes términos como raíces y hemos incluido de forma paulatina otras palabras que están relacionadas semánticamente en la mente de los seguidores de Trump. A esto le llamamos árboles semánticos. Pueden ser interpretados como trenes de pensamiento dentro del imaginario de los seguidores fervientes de Trump.

![Mapa mental de aliens](/charts/esp/png/03_aliens_mindmap.png "Mapa mental de aliens")

Los mapas mentales muestran que la visión del mundo en los seguidores de Trump es un caldo de cultivo ideal para los discursos xenófobos. Muestran que la palabra **__mexicano__** es exclusivamente **asociada** a conceptos concernientes a la **inmigración ilegal**. Términos como ilegales o indocumentados, y otros términos peyorativos tales como criminales son evocados. La palabra **__invasores__** salta a la vista dentro de este tren de pensamiento. Una palabra tristemente utilizada por el perpetrador del ataque del pasado sábado en su manifiesto.

![Mapa mental de invaders](/charts/esp/png/04_invaders_mindmap.png "Mapa mental de invaders")

Los mexicanos no son los únicos considerados como enemigos. Otros grupos (e.g. alemanes, refugiados sirios, musulmanes y refugiados) son retratados con conceptos que denotan amenazas reales tales como terroristas, **invasores**, yihadistas, violadores y bárbaros.

Analizando estos árboles semánticos podemos inferir los sustantivos de los seguidores de Trump. El **enemigo** es un ente externo, poderoso, difuso y multifacético (**ilegales**, mexicanos, refugiados, musulmanes, europeos). El enemigo es responsable por el estado de desastre y es una amenaza peligrosa (violadores, terroristas, crimen) que se debería combatir. Los extranjeros se han convertido en la principal causa de ansiedad.

## _¿Cómo altera la propaganda de Trump el comportamiento y las creencias de sus seguidores?_

Hemos analizado la evolución temporal de cuatro temáticas que caracterizan la vecindad de la palabra mexicanos. **Estos temas juntos representan más del 20% de los tuits diarios de los seguidores de Trump**.

![Cambio del tema en el discurso](/charts/esp/png/05_cluster_counts.png "Cambio del tema en el discurso")

Desde el principio de la campaña de Trump, hemos visto un ascenso en los tuits relacionados con inmigrantes. A finales del 2015, el tema del crimen fue una parte importante de la conversación dentro de los seguidores de Trump. No duró mucho. A principios del 2016, la tuitósfera de Trump cambio a como los trabajadores mexicanos y chinos estaban robando los trabajos manuales a los americanos.

No hay duda que la propaganda de Trump ha cambiado el enfoque de la discusión pública de dilemas tradicionales, tales como derecha versus izquierda, hacia una agenda en donde el fenómeno migratorio está al centro y es asociado a ansiedades profundas como la **inseguridad personal** y **laboral**.

Analizando los tuits de los seguidores de Trump hemos identificado similaridades entre dos conceptos: **mexicanos** y **enemigo**. Los **mexicanos** son desprovistos de todo cualidad humana, para ser vistos como meros invasores de los cuales deben defenderse. Son ideas que han sido reforzadas con el **discurso** xenófobo de **Trump**, y que lamentablemente el sábado pasado resonaron en el atacante. Dicho discurso debe parar.

---
[1]: Somos conscientes de que esto podría sesgar los resultados. Sin embargo, creemos que asumir que la gente que expresa su apoyo a Trump en Twitter son una población representativa, es menos dañino que confiar en diagnósticos meramente cualitativos.  En el peor escenario, este estudio es un análisis válido de una parte importante de los seguidores de Trump, en especial entre jóvenes internautas.  
