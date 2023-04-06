# Incendio forestal en Valle Nuevo, febrero-marzo de 2023

## Cómputo definitivo (actualización a 9 de marzo)

La imagen posincendio de mejor calidad y más cercana a la fecha de extinción/control fue tomada por el satélite Landsat 9 el 7 de marzo. Con ésta, combinando con la óptima preincendio, estimé con mayor precisión la superficie quemada por el incendio en Valle Nuevo de febrero-marzo 2023, usando el método de severidad de quema (ver detalle al final de este cuaderno). En total, unos 41.78 km<sup>2</sup> (4178 ha, ~66452 tareas). Como aclaré, mi anterior cómputo subestimaba debido al humo (ver abajo).

![](animacion-con-landsat-9.gif)

La severidad de quema es muy variable en este incendio, y habrá que cruzar este cálculo con otro generado con Sentinel 2, pero el cómputo total no variará mucho. Cuando tenga tiempo, subiré los resultados a GitHub, así como el método (esto último, muy importante).

Hay dos temas relevantes a abordar en una fase posincendio que se han estudiado muy poco en RD: 1) Aumento de la actividad de flujos de escombros/barro (debris flow, movimientos de masa), lo cual induce riesgos de desastres; 2) Colonización por especies pioneras.

Estudios de esta naturaleza aportarían muchos elementos nuevos para la comprensión del posincendio. Viviremos con el fuego por siempre, por lo que nos convendría aprender de estos temas (y de muchos otros), para orientar mejor las acciones del posincendio.

## Actualizaciones hasta el 5 de marzo. Reemplazadas por cómputo definitivo

El 25 de febrero de 2023, dentro del parque nacional Valle Nuevo, hacia su límite centro-occidental, inició un incendio forestal. Realicé un seguimiento desde dicha fecha, el cual publiqué regularmente [aquí](https://twitter.com/geografiard).

![](repo-captura-1.jpg)

Usando imágenes satelitales ópticas (Sentinel 2), y aplicando una versión modificada del [*script* Google Earth Engine de UN-Spider “BURN SEVERITY MAPPING USING THE NORMALIZED BURN RATIO (NBR)”](https://un-spider.org/advisory-support/recommended-practices/recommended-practice-burn-severity/burn-severity-earth-engine) (mi versión [aquí](https://code.earthengine.google.com/2aa9e527b5a9c1b5d50d9ffd4bc92747)), realicé un análisis de la severidad de quemado en dicho incendio usando el diferencial del índice normalizado de quema (dNBR) para estimar la superficie quemada. Bajo distintas severidades de quemado, **estimé que unos 25.32 km<sup>2</sup> (2,532 hectáreas, ~40,000 tareas) se habrían quemado (a distintas severidades y sobre todo pinar) hasta el 4 de marzo**, fecha de la imagen más reciente al momento de escribir este resumen. Vale notar que la imagen más reciente presentaba áreas bajo la pluma de humo, la superficie calculada es subestima la real.

![](repo-captura-2-y-3.gif)
