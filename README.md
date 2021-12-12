

# Pond Platoon
## by BubblyGames Studio



Versión 1.0




## 1. Introducción

### 1.1 Descripción breve del concepto

Tower Defense 3D en un mapa cúbico en perspectiva sobre ranas defendiendo su charco.


### 1.2 Descripción breve de la historia y personajes

En un mundo cúbico hay dos grupos de ranas en caras opuestas de éste, las ranas del estanque sucio y mugriento quieren arrebatarle el estanque a las ranas limpias porque el suyo ya no es habitable. Las ranas del charco limpio las expulsarán con todos los recursos al alcance de sus ancas.


### 1.3 Propósito, público objetivo y plataformas

Se desarrolla para navegadores web y móviles y está dirigido a todos los públicos, aunque su target principal es gente la cual no busca experiencias demasiado complicadas. El objetivo del juego es defender tu estanque de la invasión de ranas sucias.


## 2. Monetización

### 2.1 Tipo de modelo de monetización

El modelo de monetización dependerá del desempeño económico del producto una vez lanzado al mercado. Se han estructurado 3 posibles casos: ruta optimista, ruta normal, ruta pesimista.

![Ruta-Optimista 2](https://user-images.githubusercontent.com/56488179/140507385-0ab6b37b-fa93-49e6-ab92-213dce35a1aa.jpg)

![Ruta-Normal 2](https://user-images.githubusercontent.com/56488179/140507397-54ba72cd-e751-424d-b67c-791d360da57c.jpg)

![Ruta-Pesimista 2](https://user-images.githubusercontent.com/56488179/140507410-1169a49a-f06d-49c8-95d5-5bfa44343184.jpg)

Nuestro cliente objetivo se trata de una persona a la cual le gustan las cosas monas y adorables y que, a la hora de jugar, busca experiencias simples o sencillas de entender.

![nuestroMapa](https://user-images.githubusercontent.com/56488179/143439029-8711e076-5dd3-4320-b65a-d5e297a39fff.png)

### 2.2 Mapa de lienzo

![lienzo_Beta](https://user-images.githubusercontent.com/56488179/140507434-c524ac65-eed2-472b-8f6d-7883491391b7.png)


## 3. Planificación y Costes

### 3.1 El equipo humano

El equipo está formado por 6 integrantes:

Gonzalo Lobo: Scrum Master, Diseñador, Publicidad

Marta Vidal: Artista

Alberto García: Diseñador

Daniel Martí: Programador

José Márquez: Programador

Adrián Ramírez: Programador, Publicidad


### 3.2 Estimación temporal del desarrollo

El tiempo de desarrollo para las distintas etapas del proyecto se estima en:

- Alfa: 4 semanas
- Beta: 3 semanas
- Pruebas Beta: 5 días
- Gold: 2 semanas y 2 días
- Presentación: 1 semana


### 3.3 Costes asociados

Los costes del trabajo consisten en los salarios de programadores, gestores, artistas, publicistas y diseñadores.

### 3.4 Campaña de publicidad

La campaña de publicidad se va a desarrollar en 4 plataformas distintas: Twitter, Reddit, Itch.io y YouTube.
La estrategia general consiste en captar a gente a través de Reddit y Twitter para redirigirles a Itch.io, donde encontrarán más información sobre el juego. Mientras YouTube actúa como plataforma dedicada a mostrar de manera extensa el juego.
- Twitter: subir fotos de elementos de arte, videos gameplay y más elementos del juego, incluyendo en el mensaje un enlace a la página de Itch.io. Se aprovecharán hastags del mundo indie (#ScreenshotSaturday, #indiegame, #indiedev y #indiesp) para conseguir más alcance en el público adecuado. El contenido aquí se sube en castellano.
- Reddit: lo mismo que en Twitter, pero se subirán a subreddits del mundo indie para tener más alcance. En este caso se subirán contenidos a r/IndieGaming, a r/indiegames, a r/frogs y a r/frogsandtoads. El contenido aquí se sube en inglés.
- YouTube: subir versiones extendidas de los vídeos publicados en el resto de redes. Indicar tipo de contenido mostrado en el vídeo.
- Itch.io: subir DevBlogs hablando del desarrollo del juego en cada etapa. Comentar los aspectos más relevantes de cada equipo.

En el caso de las plataformas de Twitter, Reddit y YouTube se subirán elementos los días con más público en cada plataforma (sábados en el caso de Twitter). Para Itch.io se subirán los DevBlogs el último día de cada fase de desarrollo.


## 4. Mecánicas de Juego y Elementos de Juego

### 4.1 Descripción detallada del concepto de juego

Es un Tower Defense 3D en perspectiva en un mapa cúbico. El origen de los enemigos y la meta están en caras opuestas y tienen que recorrer una serie de caminos pasando por el resto de caras para llegar al final. Los caminos serán semi procedimentales, así que el jugador tendrá en primera instancia que familiarizarse con el mapa que le tocó para defenderlo adecuadamente. Los enemigos aparecen por oleadas con una dificultad que aumenta progresivamente, tanto por un aumento de número como por diversidad de tipos de enemigos, además de que su vida se incrementa. Defender satisfactoriamente tiene una recompensa económica para poder seguir expandiendo las defensas y mejorar las ya existentes. Según el nivel aparecerán uno u otros enemigos, al igual que estarán disponibles solo algunos tipos de torres. Estas pueden ser mejoradas para mejorar su desempeño. Si una rana enemiga consigue llegar al final se reduce una cantidad de vida en función del tipo de enemigo hasta que llegue a 0. La partida puede terminar con el jugador derrotado al perder toda la vida o victorioso tras acabar con todos los enemigos.


### 4.2 Descripción detallada de las mecánicas de juego

![](https://lh4.googleusercontent.com/7_tib0ycPSkRPNOmPVR7lpDnccMY1CH9RyNUzCjInd67h-6ZX0qLFfUIJddRScMD8ORfV0BSEqDi8Iqpj8Wfii9Jr68iM_2h8t9bEcG8d3XK19vl0DOSLOA-FJglhf44LmBII0In=s1600)

#### 4.2.1 Victoria y derrota

Para ganar la partida el jugador se ha de defender un número determinado de oleadas y con la vida igual o superior a uno. El número de oleadas defendidas y por defender estarán en pantalla al inicio de cada ronda. Si llegan a tu estanque suficientes enemigos como para bajar la vida a 0, acaba la partida. En función de la cantidad de vida con la que acabe el jugador la partida, conseguirá de 0 a 3 estrellas:
- 0 estrellas si no completa el nivel o muere en el intento.
- 1 estrella si termina el nivel con menos del 50% de vida.
- 2 estrellas si termina con un porcentaje de vida entre 50% y 99%
- 3 estrellas si termina sin recibir daño.


#### 4.2.2 Mapa

El mapa tiene forma de cubo, con sus seis caras siendo terreno jugable. Las caras visibles serán de una a tres, dependiendo de la rotación del cubo que elija el jugador. El cubo se puede rotar en cualquier momento de la partida menos cuando se coloca una torre.

En el mapa hay tres tipos de casillas: Casillas de camino, por las que los enemigos transitan y se pueden poner trampas; Casillas de terreno construible, donde se podrá poner cualquier tipo de torre; y casillas obstáculo, en las que no puede haber camino ni estructuras, salvo Albatro.


#### 4.2.3 Economía

El juego comienza con una cantidad determinada de monedas para poner las torres iniciales. Una vez iniciada la partida, hay 2 fuentes de ingreso: el dinero otorgado por la derrota de enemigos y el dinero generado con la rana de dinero (Especulio). 
El dinero conseguido se usa para mantener en funcionamiento las torres del jugador y para que éste pueda comprar más torres y mejorar las ya existentes. En caso de construir más torres o de mejorar las ya existentes, será necesario construir más Especulios para poder mantenerlas todas en funcionamiento. De no haber ningún Especulio o de no haber suficientes, las torres no funcionarán, dejando de atacar a los enemigos y teniendo que activarlas manualmente una vez se cuente con suficiente dinero.

Las torres se pueden vender, consiguiendo un pequeño porcentaje de dinero a cambio. Si una torre es destruída por la catapulta enemiga, también se recupera un porcentaje de dinero.


#### 4.2.4 Defensas y enemigos

Existen dos tipos de defensas: Las torres y las trampas. Las torres tienen alcance, daño, velocidad de ataque y éstas pueden ser individuales o en área o tener efectos de estado sobre los enemigos. Se puede construir en cualquier lugar menos caminos y rocas, a excepción de Especulio, que solo se puede poner adyacente al camino y de Albatro, que solo puede ser construído sobre las rocas. Además, tienen tres niveles de mejoras para aumentar sus estadísticas, salvo Especulio. Luego están las trampas, las cuales se colocan en el camino del enemigo, tienen daño y pueden tener efecto. Éstas no se pueden mejorar.

Por otro lado están los enemigos, con características de vida y velocidad de movimiento. Aparecen por oleadas y aumentan en número conforme avanzas en la partida, además de que su vida se incrementa. Tienen diferentes roles en función de sus estadísticas, siendo los roles unidad básica, tanque, horda y aéreo, explicadas más adelante en el apartado Enemigos.

![](https://lh6.googleusercontent.com/XyZfstCSw-DLWgamwydXli8vhxtgT-UwKJedln-d8n8b128AX2uwMAu_ZfEi14CkXv6f0j37Y27lFRzzMlJHlza6lMVwx9gM2rYwonhWBWuMDhGatPP_NvB05I83jCBoDTnug5R2=s1600)


### 4.3 Controles

El jugador durante la partida tendrá dos tareas principales: vigilar el mapa para saber el estado de la partida y colocar y mejorar defensas. Para vigilar el mapa podrá rotarlo con click (pulsar en el caso de móvil) y arrastrar. Luego para poner las torres será exactamente el mismo input, click y arrastrar desde la tarjeta de la torre hasta la posición en la que desee ponerla, contando con un offset en la versión de mobiles para poder colocar mejor la torre. Si el jugador lo desea podrá vender una torre clickando primero sobre la torre y después dándole al botón de defender. Para mejorar una torre, primero debe seleccionarla y después darle al botón de mejora.
El jugador puede acceder a las lecciones de las torres durante la partida dándole al botón con una I que aparece sobre cada carta antes de colocarla.

### 4.4 Enemigos

Algunos enemigos cuentan con un nombre alternativo en inglés.

|   **ESPAÑOL**   |   **INGLÉS**  |
| --------------- | ------------- |
| GEPE            | GEPE          |
| GUNTHER         | GUNTHER       |
| HERMANOS ZULETA | THE WILSONS   |
| DOOLITTLE       | DOOLITTLE     |

A medida que van pasando las rondas de un nivel, la vida de los enemigos se incrementa en un 10%.

| **ENEMIGOS**                | VIDA | VELOCIDAD DE MOVIMIENTO | TIPO                 | RECOMPENSA |
| --------------------------- | ---- | ----------------------- | -------------------- | ---------- |
| GEPE (NORMAL)               |  40  | Media (2 ud)            | Terrestre - Normal   |      8     |
| GUNTHER (TANQUE)            | 200  | Lenta (1.5 ud)          | Terrestre - Pesada   |     20     |
| HERMANOS ZULETA (HORDA)     |  25  | Media (3 ud)            | Terrestre - Horda    |      3     |
| DOOLITTLE (AÉREO)           |  30  | Media (3 ud)            | Aérea - Normal       |     15     |

Además, los enemigos lanzarán proyectiles desde su estanque a aquellas zonas en las cuales haya taponamiento de enemigos, destruyendo las defensas del jugador y alterando la figura del cubo, obligando al jugador a adapatarse e improvisar.

### 4.5 Torres y trampas

Algunas torres cuentan con un nombre alternativo en inglés.

|   **ESPAÑOL**         |   **INGLÉS**  |
| --------------------- | ------------- |
| BEERHOUSE             | BEERHOUSE     |
| BATRACIUS             | BATRACIUS     |
| HERMANAS FLOR Y FLETA | ALI AND OLI   |
| ALBATRO               | ALBATRO       |
| ESPECULIO             | BROKER        |
| PETASETA              | MUSHBOMB      |

| **TORRES**                     | ALCANCE      | DAÑO                           | OBJETIVO          | VELOCIDAD DE ATAQUE | MANTENIMIENTO | EFECTO                           | COSTE  |
| ------------------------------ | ---------    | ------------------------------ | ----------------- | ------------------- | ------------- | -------------------------------- |--------|
| BATRACIUS (PESADA)             | Largo (6 ud) | Elevado ( DIR 30 ud  AREA 7 ud)| Proy Área TT\*    | Lento (0.3 ud)      |      8        | \-                               | 300    |
| HERMANAS FLOR Y FLETA (BÁSICA) | Medio (5 ud) | Medio (8 ud)                   | Individual TT\*   | Medio (2 ud)        |      5        | \-                               | 125    |
| BEERHOUSE (PSÍQUICA)           | Corto (4 ud) | Bajo (3 ud)                    | Área TT\*         | Lento (0.3 ud)      |      8        | Ralentiza al enemigo             | 200    |
| ALBATRO (ANTI-AÉREA)           | Largo (7 ud) | Bajo (3 ud)                    | Individual TA\*   | Rápido (5 ud)       |      7        | \-                               | 175    |
| ESPECULIO (ECONÓMICA)          | Nada         | Ninguno                        | Ninguno           | Sin ataque          |               | Genera ingresos de forma pasiva  | 250    |
| **TRAMPAS**                    |              |                                |                   |                     |               |                                  |        |
| PETASETA (PANTANO)             | Corto (3 ud) | Elevado (40 ud)                | Área TT\*         | De un solo uso      |               | Ralentiza al enemigo             | 50     |

Cada defensa del jugador se puede mejorar, por separado, hasta tres veces, aumentando con estas mejoras las estadísticas de dicha defensa y haciéndola más eficaz en combate.

Nivel 1:
| **TORRES**              | ALCANCE      | DAÑO                          | OBJETIVO          | VELOCIDAD DE ATAQUE | MANTENIMIENTO | EFECTO                           | COSTE  |
| ----------------------- | ------------ | ----------------------------- | ----------------- | ------------------- | ------------- | -------------------------------- |--------|
| BATRACIUS (PESADA)      | Largo (6 ud) | Elevado (DIR 40 ud AREA 10 ud)| Proy Área TT\*    | Lento (0.3 ud)      |     12        | \-                               | 150    |
| FLOR Y FLETA (BÁSICA)   | Medio (5 ud) | Medio (12 ud)                 | Individual TT\*   | Medio (2 ud)        |     7         | \-                               | 50     |
| BEERHOUSE (PSÍQUICA)    | Corto (4 ud) | Bajo (5 ud)                   | Área TT\*         | Lento (0.3 ud)      |     12        | Ralentiza al enemigo             | 100    |
| ALBATRO (ANTI-AÉREA)    | Largo (7 ud) | Bajo (4 ud)                   | Individual TA\*   | Rápido (5 ud)       |     10        | \-                               | 75     |

Nivel 2:
| **TORRES**             | ALCANCE      | DAÑO                          | OBJETIVO          | VELOCIDAD DE ATAQUE | MANTENIMIENTO | EFECTO                            | COSTE  |
| ---------------------- | ---------    | ----------------------------- | ----------------- | ------------------- | ------------- | --------------------------------- |--------|
| BATRACIUS (PESADA)     | Largo (8 ud) | Elevado (DIR 40 ud AREA 10 ud)| Proy Área TT\*    | Lento (0.3 ud)      |      13       | \-                                | 200    |
| FLOR Y FLETA (BÁSICA)  | Largo (6 ud) | Medio (14 ud)                 | Individual TT\*   | Medio (2 ud)        |      9        | \-                                | 100    |
| BEERHOUSE (PSÍQUICA)   | Medio (5 ud) | Bajo (6 ud)                   | Área TT\*         | Lento (0.3 ud)      |      14       | Ralentiza al enemigo              | 150    |
| ALBATRO (ANTI-AÉREA)   | Largo (8 ud) | Bajo (4 ud)                   | Individual TA\*   | Rápido (5 ud)       |      12       | \-                                | 125    |

Nivel 3:
| **TORRES**             | ALCANCE      | DAÑO                          | OBJETIVO          | VELOCIDAD DE ATAQUE | MANTENIMIENTO  | EFECTO                            | COSTE  |
| ---------------------- | ---------    | ----------------------------- | ----------------- | ------------------- | -------------- | --------------------------------- |--------|
| BATRACIUS (PESADA)     | Largo (8 ud) | Elevado (DIR 40 ud AREA 10 ud)| Proy Área TT\*    | Lento (0.6 ud)      |      16        | \-                                | 300    |
| FLOR Y FLETA (BÁSICA)  | Largo (6 ud) | Medio (16 ud)                 | Individual TT\*   | Medio (2.2 ud)      |      11        | \-                                | 150    |
| BEERHOUSE (PSÍQUICA)   | Medio (5 ud) | Bajo (6 ud)                   | Área TT\*         | Lento (0.5 ud)      |      16        | Ralentiza al enemigo              | 200    |
| ALBATRO (ANTI-AÉREA)   | Largo (8 ud) | Bajo (5 ud)                   | Individual TA\*   | Rápido (7 ud)       |      15        | \-                                | 200    |

\*TT: Ataques desde Tierra a objetivos Terrestres.
\*TA: Ataques desde Tierra a objetivos Aéreos.

### 4.6 Niveles y misiones

El juego cuenta con cinco mapas, diferenciados a nivel visual y en la generación del terreno. El objetivo en todos ellos es defender tu estanque de las tropas enemigas.

Los niveles son semi procedimentales y se crean mediante una semilla. En función del nivel estarán disponibles unas torres u otras y aparecerán unos u otros enemigos. A medida que se avanza de nivel, empezarán a aparecer todos los tipos de enemigos y de torres, aumentando la dificultad del juego.

**Pantano:**

Cantidad de enemigos por ronda:
| **ENEMIGOS**                | RONDA 1 | RONDA 2 | RONDA 3 |
| --------------------------- | ------- | ------- |---------|
| GEPE (NORMAL)               |  10     |   16    |   13    | 
| GUNTHER (TANQUE)            |   0     |    2    |    5    |

Torres disponibles en el nivel:
- Hermanas Flor Y Fleta
- Especulio

**Tundra:**

Cantidad de enemigos por ronda:
| **ENEMIGOS**                | RONDA 1 | RONDA 2 | RONDA 3 | RONDA 4 | 
| --------------------------- | ------- | ------- |-------- | ------- |
| GEPE (NORMAL)               |  5      |   13    |   20    |   15    |
| GUNTHER (TANQUE)            |  1      |    2    |   10    |   13    |
| HERMANOS ZULETA (HORDA)     |  6      |    5    |   15    |   20    |

Torres disponibles en el nivel:
- Hermanas Flor y Fleta
- Batracius
- Especulio
- Beerhouse

**Otoño:**

Cantidad de enemigos por ronda: 
| **ENEMIGOS**                | RONDA 1 | RONDA 2 | RONDA 3 | RONDA 4 | RONDA 5 |
| --------------------------- | ------- | ------- |-------- | ------- | ------- |
| GEPE (NORMAL)               |  10     |   15    |   8     |   18    |    8    |
| GUNTHER (TANQUE)            |   0     |    2    |   6     |    3    |    4    |
| HERMANOS ZULETA (HORDA)     |   0     |    0    |   6     |    8    |    8    |
| DOLITTLE (AÉREO)            |   3     |    6    |   5     |   10    |    8    |

Torres disponibles en el nivel:
- Todas

**Cerezo:**

Cantidad de enemigos por ronda: 
| **ENEMIGOS**                | RONDA 1 | RONDA 2 | RONDA 3 | RONDA 4 | RONDA 5 |
| --------------------------- | ------- | ------- |-------- | ------- | ------- |
| GEPE (NORMAL)               |   12    |   12    |   10    |   10    |    10   |
| GUNTHER (TANQUE)            |    3    |    5    |    4    |    4    |     6   |
| HERMANOS ZULETA (HORDA)     |    0    |   12    |   10    |   15    |   10    |
| DOLITTLE (AÉREO)            |    4    |    6    |    8    |   10    |   10    |

Torres disponibles en el nivel:
- Todas

**Amatista:**

Cantidad de enemigos por ronda: 
| **ENEMIGOS**                | RONDA 1 | RONDA 2 | RONDA 3 | RONDA 4 | RONDA 5 |
| --------------------------- | ------- | ------- |-------- | ------- | ------- |
| GEPE (NORMAL)               |   15    |   12    |   10    |   12    |   12    |
| GUNTHER (TANQUE)            |    3    |    6    |    6    |    6    |    8    |
| HERMANOS ZULETA (HORDA)     |    0    |   15    |   10    |   20    |   10    |
| DOLITTLE (AÉREO)            |    0    |    6    |    8    |   10    |   10    |

Torres disponibles en el nivel:
- Todas


## 5. Trasfondo

### 5.1 Descripción detallada de la historia y la trama

Dos sociedades de ranitas viven cada una en un estanque de un cubo espacial en paz y armonía. Pero una de las sociedades ha ensuciado su estanque hasta tal punto de volverlo tóxico e inhabitable, lanzando una invasión al estanque de las ranas limpias para poder encontrar un nuevo lugar donde continuar sus actividades.

Las ranas limpias, ante esta situación, deben defender su estanque de la invasión de las ranas sucias.


### 5.2 Personajes

Hay dos personajes característicos en el juego: el líder de las ranas limpias y el líder de las ranas sucias.


### 5.3 Entornos y lugares

Hay cinco niveles jugables, cada uno con su estética única: Pantano, Tundra, Otoño, Cerezo y Nevado.

- Primer mapa: Pantano. El estanque de las ranas limpias es un estanque limpio, vívido y con nenúfares mientras que el estanque de las ranas sucias es oscuro, con lodo.

- Segundo mapa: Tundra. Antes de llegar a las frías tierras del ártico, las ranas se refugian en un charquito de aguas termales, a donde acuden grandes ranas cubiertas de fango. 

- Tercer mapa: Otoño. Con la caída de las hojas y las temperaturas, el suelo se tiñe de marrón y nuestras ranitas buscan el calor grupal en un pequeño estanque. 

- Cuarto mapa: Cerezo. Los cerezos anuncian la llegada de la primavera con su lluvia de pétalos rosas, dando al campo un color jovial y acompañando a una plácida mañana soleada.

- Quinto mapa: Amatista. Las huellas quedan marcadas en la nieve ante el paso de nuestras protagonistas, que se dirigen a una calentita charca. 


## 6. Arte

### 6.1 Estética general del juego

Los gráficos del juego son principalmente 3D, de estética y técnica Voxel Art, tanto para el escenario como para la representación física de defensas y enemigos y sus efectos. Por otro lado, todo lo relacionado con la interfaz, el HUD y otros elementos varios (cartas de personajes, información adicional, etc) son en 2D.

Con todo, la estética general del juego está basada en el minimalismo, con colores planos y suaves, es decir, no muy saturados y con alta luminosidad.


### 6.2 Apartado visual

Siguiendo en todo momento la línea estética general del juego, se diferencian diversos elementos del apartado visual:

#### Escenario

El escenario es un hexaedro regular o cubo, limitado por seis caras del mismo tamaño y generado a partir de unidades definidas en formato Voxel. Por la superficie del poliedro están repartidas zonas elevadas, zonas llanas y caminos, cada uno diferenciado por un color específico. Por último, una de las caras contiene la charca, es decir, el elemento a defender y otra cara, la opuesta, contiene el punto de partida de los enemigos.

![](https://lh5.googleusercontent.com/1pp7M7gs_g1WoIg_xEuAlbCaI-q7GpncsJo5DxNHqUQL1ByV5s9OGFHVqFiTTYkGQAjDMign6c0eZUf87mPH5SDK2_bB-pbNMn-9uj5dNo75ePGSPz11JoL5_9HwieehbhHEpByZ)

Así pues, en una primera instancia, se limitan los colores del escenario jugable a cuatro.

Los biomas presentes son, como se han explicado antes, los siguientes:

**Bioma Pantano:**

![](https://user-images.githubusercontent.com/56488179/142777057-986df292-81c3-43f9-9842-efd53bd7c35f.png)

![](https://user-images.githubusercontent.com/56488179/142777051-af2f45b9-2ccb-4790-a5c1-a07466fc1b29.png)

**Bioma Otoño:**

![](https://lh4.googleusercontent.com/TXgQWhpVlt83etDjwyYZxmVOVPrlITub35fW6DAcFtA7LPzNhg3M7nMgYrNafSEyJ20paOBGp5wyTFgmkCkk-GYfFl1u3ooGeAzqImXpHy3aheO0lrHU4wik3ZZYzqpsGvj-WL_Z)

![](https://lh5.googleusercontent.com/rK1Dd5JWwy1GxaCoPw6uzcGak2qy_9cbq-xHiRPymrxKhMh4TFVeFv0a6Zl4Uu91OFZW7Kf2yeLaik4JcB2CMBWRmC97kNLvhFVIq-XcEEPfvwAeC9l9Nj45nsOXgikCjeNt13u7)


**Bioma Cerezo:**

![](https://lh6.googleusercontent.com/Z41MUXJ7gsGdB0-wqKRionSkHEM7b0xHw2xt5lHWmSbZVd8jw5R1l-QMfFdtzLF-Hmd7l831v-c1z9vijDtHBnatru3Xj26GpkPvsK-eWeHLULY_-Ki46UXsw2BF9tqVgKnxPi4j)

![](https://lh6.googleusercontent.com/ASA0QnjXO-dbM1D6dp4Rvd5GMp41v-_T6zwML90An7MpX2yYpfsXZUPi5RbpV2A0RamsDm2j-jmorlBmVXc9D14YAohFmSMxr7kL_hMfD1FGYAFQm1TlfeZ-4VzBPz0aG9ZEjoZT)


**Bioma Nevado:**

![](https://lh4.googleusercontent.com/BK7V2ioEAjoyQnGm7btwQTIIZejfD8ZpiHLmawmiaaD-DrBs647Yx6qjIlPKCiOrht3NV9W28lh3p_V5Z28jlGwWc9kJnl_4ULSFMy1FiRs9qizqyaVCPhjqrk78uTqrp3hNrKuE)

![](https://lh5.googleusercontent.com/AZ-85cmuXKm2jMr9DdmTxCduSSe7394JMhqrcEQBTV-8728i2_fs2FbrR8CIKmWwq_K4elSYTttiHMw3PbmvKVQ9ZpDRKNnWulx2wJtAUYUVHIer9HSS2pcDGWK6wAiTRKc8pArr)

**Bioma Tundra:**

![](https://lh5.googleusercontent.com/pCXfBnfKCp12tBGAqrz_iixI9uXFEhYbyeM49xcxCWKXDhxbzPcPPdqNF7SUs7KB145WxYBPg7mwlvkVP6AptwDWy7o2m8xY82EaDP3gtb4DAlJru1ZGoRPpUliR0CEQlaWqv1OD)

![](https://lh3.googleusercontent.com/sZM54ldy0WYvTPkmVwHaDWvQA5AxngABtHF8KJui1eTovgTu9EuEFM6PweAag9n3FWCKl7JXVbOHLXRHcAuTjNh3F2RRyddz6-hI7ra0Aa8PuNhc_57iba3Apb0qG1kBLFKADIUJ)

#### Personajes

La representación en el escenario tanto de las defensas como de los enemigos son modelos Voxel de dimensiones 16x16x16 vóxeles.

- Hermanas Flor y Fleta:

![BasicaRender](https://user-images.githubusercontent.com/56488179/142732046-b22a2c75-6138-4ab9-9c17-e657d7c14cc4.png)

- Batracius:

![PesadaRender](https://user-images.githubusercontent.com/56488179/142732038-51339036-f17a-48cb-8eaa-c4de7f963801.png)

- Beerhouse:

![VenenosaRender](https://user-images.githubusercontent.com/56488179/142732066-018798f5-6ca5-4c18-b5a4-cd1715ed443a.png)

- Albatro:

![AereaRender](https://user-images.githubusercontent.com/56488179/142732075-a73a68d8-8cca-4110-a8de-09a1d2f4313d.png)

- Especulio:

![DineroRender](https://user-images.githubusercontent.com/56488179/142732084-a9c8d8bc-cd7e-4724-a1fc-59b2dfb11bc0.png)

- Petaseta:

![MinasRender](https://user-images.githubusercontent.com/56488179/142732128-960ccb57-7cff-42e8-b027-a23c91b36ad3.png)

#### Enemigos

- Gepe:

![NormalRender](https://user-images.githubusercontent.com/56488179/142732143-1a939315-6f58-4d41-86ac-c3a0a8ee60f5.png)

- Gunther:

![TanqueRender](https://user-images.githubusercontent.com/56488179/142732147-72fafd0b-a07a-4a8c-b3b8-e4009980808a.png)

- Hermanos Zuleta:

![HordaRender](https://user-images.githubusercontent.com/56488179/142732505-ff361669-72d7-46aa-8af5-75a9d16d0158.png)

- Doolittle:

![AereoRender](https://user-images.githubusercontent.com/56488179/142773898-0e065091-fb06-48d8-9853-527115f4e0dc.png)

#### Iconos

A su vez, la representación de las estadísticas de las torres se realiza mediante cartas o pantallas de información en gráficos 2D, acorde a las descripciones de la estética general y al resto de elementos 2D.

- Batracius:

![Pesada](https://user-images.githubusercontent.com/56488179/142732267-a5e0ec70-ef13-45e9-aa86-bce248feb8ce.png)

- Hermanas Flor y Fleta:

![Basica](https://user-images.githubusercontent.com/56488179/142732229-6aad8882-4bb4-4b40-bb74-40f4873d6bf8.png)

- Beerhouse:

![Psíquica](https://user-images.githubusercontent.com/56488179/142732258-3350a5d7-4d75-4494-be7d-75a4ecb69431.png)

- Albatro:

![Aerea](https://user-images.githubusercontent.com/56488179/142732217-6d9702b9-d1e2-4d8d-b761-a5b9c89b57d9.png)

- Especulio:

![Dinero](https://user-images.githubusercontent.com/56488179/142732221-19d4812b-b159-4f51-ba5f-78a539826fc0.png)

- Petaseta:

![Mina](https://user-images.githubusercontent.com/56488179/142732239-0a085ffa-8af6-4a25-bbe8-a9993a14e5a2.png)

- Gepe:

![Normal](https://user-images.githubusercontent.com/56488179/142732438-6de3f781-a865-43dc-a8bd-4ea06148a52f.png)

- Gunther:

![Tanque](https://user-images.githubusercontent.com/56488179/142732443-690c01f2-9eda-4bd7-9e16-70a2a53217ba.png)

- Hermanos Zuleta:

![Horda](https://user-images.githubusercontent.com/56488179/142732450-238aba64-f947-4ea5-aa23-d3785851458e.png)

- Doolittle:

![Aereo](https://user-images.githubusercontent.com/56488179/142773870-f647b0ed-0cb2-446b-b71a-fbb24b6bc1cd.png)

### 6.3 Música

El juego cuenta con una sola canción (autor: [Pascual Gázquez Compán](https://open.spotify.com/artist/7y2dfMVexZgClCIeiHd22f?si=Q2ch-_AVR8CC8a927irtxw&utm_source=copy-link)) la cual se reproduce tanto en los menúes como durante la partida.


### 6.4 Ambiente sonoro

Se cuentan con distintos efectos de sonido para la interacción con los elementos de la interfaz.
Estos son usados cuando:
- Se interacciona con un botón de la interfaz para "avanzar"
- Se interacciona con un botón de la interfaz para "dar marcha atrás"
- Se coloca una torre


## 7. Interfaz

### 7.1 Diseños de los menús

La interfaz del juego consta de 7 ventanas:

- Menú principal:

![menuPrinc](https://user-images.githubusercontent.com/56488179/142777098-17abb069-96f6-4e93-a960-d05407b42c2a.png)

- Ajustes:

![menuAjustes](https://user-images.githubusercontent.com/56488179/142775932-6e72387a-2e4e-412e-9064-0d2783f9c809.png)

- Tutoriales y lecciones:

![tutoriales](https://user-images.githubusercontent.com/56488179/145688593-163b0c1d-86a7-4cc3-818e-97a516bbd2e4.png)

- Selector de nivel:

![selector](https://user-images.githubusercontent.com/56488179/145688515-77d838c0-0ae2-4671-88bc-15110b4b011e.png)

- Menú de pausa:

![pausa](https://user-images.githubusercontent.com/56488179/145688558-e7282bfc-1786-483f-b5ea-65eaab04fb1f.png)

- Final de nivel:

![fin](https://user-images.githubusercontent.com/56488179/145688516-f4260b40-7683-4dd8-a802-e34389ce4602.png)

- Interfaz de juego:

![ingame](https://user-images.githubusercontent.com/56488179/145688519-3930746a-2461-476f-8f4f-77863fed6f75.png)


### 7.2 Diagrama de flujo

Flujo de escenas:

![](https://lh6.googleusercontent.com/7k6M4w1ZdGuKuBK72xem0Uu5PHNoBZPJjpaYxPJgbp3hJ1ydfIefFEy0RCkq3md5ElrEPwxL41SNHyZbHJ82DnDf-CXiI_CyJ198rYmyd8uAWpHVXEuaZW8tnHJZfTWVvFW_Q90J=s1600)

Flujo de juego:

![](https://lh3.googleusercontent.com/aF1nWLFmWOgguDnGZoJvcOlg-Rg5idqPTJ36BbybrI7znmQiQz3duVFWYjOZu0G9ywJHTiWaXSx0U-r1mU3JT1imTOPqgxp3-cy9zKN_-aYHIY8eDtvKcv5eABgkfKF-SN-zxnpM=s1600)


## 8. Post-Mortems

### 8.1 Post-Mortem de la etapa Alfa

#### Autocríticas individuales

##### Gonzalo

Debo de ser más duro. La gente ha llegado y en varias ocasiones han saltado a trabajar en tareas que todavía no tenían asignadas y que eran menos prioritarias para el proyecto que las que ya tenían asignadas en ese momento. También he tenido deslices con la programación de reuniones y el tratamiento de redes como olvidarme de fechas, elementos que debían estar presentes en las publicaciones, publicar en unas redes pero olvidarme de publicar en otras…

Lo bueno es que algunas cosas sí que he logrado corregirlas de distintas formas, como ponerme recordatorios de las reuniones los días previos o mirar el GDD para asegurarme de que lo subía a las redes que teníamos pensadas, con la información como hastags debidamente puestos.

Tengo que mejorar mi atención o mis habilidades de gestión, en general. Aunque creo que parto de buen nivel. Ha sido una constante el comprobar los progresos del resto de miembros del equipo y me he adelantado con el planning de tareas para ver a quién podía encajar en qué tarea cuando terminara su actual, además de contar siempre con responsabilidades de los miembros fuera del proyecto para poder planear siguientes asignaciones de tareas o avances.

##### Joy

No considero que sea una persona que destaque en la creatividad así que generalmente suelo estar algo ausente en las tareas iniciales como puede ser el brainstorming para decidir sobre qué irá el juego, aunque luego sí soy bastante crítico si el tema elegido no es de mi agrado, cosa que no me parece justa.

Tras varias vueltas se acabó en una idea que tenía buena pinta. Estuve trabajando en varios prototipos de movimiento que no me llevaron a ningún lado y que debí haber abandonado antes, por suerte otro de mis compañeros del equipo de programación sacó adelante un prototipo sobre el que ya se podía trabajar.

Creo que, en general, he hecho un buen trabajo, pero hay cosas en las que tenía que haberme molestado debido a que somos un estudio pequeño, como conocer el código que hacían mis compañeros en el equipo de programación y comunicar y expresar mejor las ideas diseñadas para que no hubiera desarrollos innecesarios.

##### Adrián

Buena comunicación con el resto de los miembros y flujo constante. Trabajo realizado rápido y muy buena gestión del tiempo.

###### A mejorar:

- Seguir mejorando la comunicación e intentar hacerme oír más.
- Seguir mejorando la gestión del tiempo para poder elaborar código más limpio de una vez en vez de tener que ponerlo bonito después de estar funcional.
- Comentar más el código.
- No retrasar las consultas de dudas.

##### Dani

Desde el primer momento no me entusiasmó excesivamente la idea de hacer un Tower Defense, pero viendo que el resto de mis compañeros estaban decididos, no me pude negar. Mi mayor preocupación era hacer un juego demasiado simple a nivel técnico, ya que consideraba que, teniendo en cuenta el equipo que teníamos, podíamos aspirar a hacer un juego bastante ambicioso. Al final acepté la idea, pero me propuse hacer un juego que, dentro de un género que no suele llamar la atención, destacara por ser innovador. Al final esto último resultó ser más difícil de lo que parecía.

Terminada ya la Alpha me he dado cuenta de que desarrollar un juego completo y pulirlo a un nivel aceptable, por simple que sea el juego, siempre supone un reto. La generación procedimental del mundo y los caminos, de lo que principalmente me he encargado yo, me ha dado infinitos dolores de cabeza, aunque la satisfacción de verlo todo funcionando al final lo compensa.

##### Marta

A nivel personal:

- Ser capaz de expresar abiertamente mi opinión. Una de las cosas que más me ha costado siempre es ser capaz de expresar abiertamente mi opinión. Así que me alegro mucho de haber podido hacerlo en este grupo de trabajo
- Establecer buenos horarios de trabajo. Durante este tiempo de trabajo he sido capaz de establecer unos buenos horarios de trabajo sin llegar a sobreesforzarme. Esto me ha permitido sentirme bien conmigo misma y con el proyecto.
- Problemas con mi pipeline de trabajo. A nivel personal, durante las primeras semanas me demoré más de lo necesario en realizar mis tareas debido a que me intentaba adaptar a lo que el resto del equipo me pedía sin tener en cuenta el flujo de trabajo (a nivel artístico) al que estoy acostumbrada. Esto me llevó a bloquearme en ciertos aspectos, sobre todo referentes al desarrollo conceptual del juego. La solución que propongo es adaptarme a las necesidades de mi equipo, pero sin dejar de tener en cuenta mi propia línea de trabajo de cara a establecer y definir las tareas y/o hitos. Además de esto, me gustaría que las tareas a realizar vinieran de un único canal para evitar problemas de comunicación o errores de prioridad.

##### Alberto

Al inicio estaba bastante motivado con el proyecto porque había salido elegido un juego de estrategia, mi género favorito con diferencia, así que quería aplicar mi experiencia en hacer algo interesante. Después no solo había que compartir el rol de game designer sino que al final prácticamente el juego acabó siendo una decisión de todos. Esto, en realidad, a la larga es favorable para el grupo porque trabajamos todos en algo que más o menos nos gusta a todos, pero, siendo yo game designer principalmente, ¿Solo me encargo de escribir cuántas torres y enemigos hay y cómo funcionan? Cosa que también tenía que ser un consenso entre los dos game designers. Aún así creo que podría haber hecho un mayor ejercicio de creatividad para hacer un juego original, ya que lo del cubo no se nos ocurrió a los diseñadores tampoco.

En conclusión, perdí bastante la motivación que tenía al empezar pero no considero que fuese motivo suficiente para no haber dado más de mí en crear alguna mecánica original.

#### Críticas de equipo

##### Productor

El equipo ha trabajado muy bien. Hemos salido de la Alfa con un juego bastante terminado en lo que a mecánicas se refiere, encima teniendo la procedimentalidad de por medio, algo que complicaba el asunto. A parte de lo mencionado más arriba, un problema que he visto (que va ligado a la cantidad de gente que somos y a circunstancias externas) ha sido el bajo rendimiento del equipo de arte comparado con otros equipos.

Ha habido bastante debate de ideas, algunos que se han alargado hasta otras fases (como es el caso del nombre) o que han ralentizado un poco el desarrollo por alargarse más de lo debido (como fue decidir el tipo de juego y la temática que queríamos abordar). Pero no han sido debates duros, lo cual no ha perjudicado a la sensación de equipo. El equipo, en general, debería de mirar más el GDD, ya que surgen dudas o malentendidos sobre elementos que ya están descritos en el documento.

También destacar que en el equipo de programación han estado brutales: han currado a destajo y han logrado tener muchas mecánicas y funcionalidades listas para la Alfa, algo que baja la intensidad de su trabajo para las siguientes etapas, ya que se centrarán en pulir errores y en expandir o implementar alguna funcionalidad/mecánica extra.

##### Programador 1

El trabajo ha sido fluido y sale bien. Hay un buen ambiente de trabajo y se siente el progreso de cada uno del equipo como propio gracias al Trello y las reuniones. Las reuniones semanales son un acierto, aunque posteriormente se debatirán algunos detalles.

Las reuniones deberían contar con un esquema previo y tratar sobre temas específicos en vez de tantas generales para hacerlas más útiles y concisas. También tener fechas de entrega de tareas, siempre teniendo en cuenta la disponibilidad de cada persona, pero tener plazos fijados.

Respecto a la corrección del trabajo de otros miembros mejor que editarlo directamente se cree más conveniente que se le comuniquen las ideas de mejora al encargado de esa tarea y sea él o ella quien realice las modificaciones. Todo esto para ahorrar tiempo y evitar errores inesperados.

##### Programador 2

Creo que hemos hecho un buen trabajo. Como equipo siento que en ciertos momentos nos ha faltado un poco de comunicación. Hemos tenido momentos de frustración por no entendernos o por querer hacer las cosas de formas distintas, pero al final el proyecto ha salido adelante más o menos como lo habíamos concebido, así que debemos considerarlo un éxito.

##### Programador 3

Considero que todo el equipo ha trabajado correctamente, cada equipo con sus altibajos por diferentes cuestiones:

El equipo de dirección ha trabajado bien encargándose de que todos fuéramos cumpliendo las tareas y organizando una serie de reuniones semanales para ver cómo iban avanzando los equipos.

El equipo de diseño ha hecho un buen trabajo rellenando el GDD con las ideas y mecánicas que decidimos implementar en las reuniones.

El equipo de arte no ha tenido mucho trabajo para la alfa, un par de texturas y modelos han entrado en esta versión. Para compensar el bajo nivel de requerimientos si han trabajado en concepts para avanzar para la siguiente versión.

El equipo de programación ha sido con diferencia el que más trabajo tenía, no ha habido crunch pero sí que ha tenido que dedicarle bastante tiempo tal vez más del debido. Ha sido un buen trabajo en el que cada uno de los integrantes se ha ido dedicando una tarea para avanzar lo más rápido posible, esto, aunque bastante efectivo para implementar la mayoría de las mecánicas si ha provocado de alguno de los integrantes usaran su libre albedrío para implementar las mecánicas como más le apetecía y provocando que otros tuvieran que ir detrás revisando ese trabajo.

##### Arte

A nivel de equipo:

- Correcta asignación de roles. Considero que tenemos un equipo muy compensado y que la asignación de roles ha sido acertada, sobre todo la elección de un productor y Scrum Master, figura que a menudo se ha olvidado o dejado de lado en otros proyectos de ámbito universitario.
- Idea de juego adecuada. La idea de juego quedó muy clara para todos desde un inicio y hemos sabido establecer un buen scope dado el tiempo y los recursos disponibles.
- Buen ambiente y asertividad. El ambiente de trabajo ha sido muy bueno, todo el mundo ha dado su opinión de manera asertiva y eso ha facilitado una correcta comunicación y exposición de las ideas. En este aspecto me he sentido muy cómoda, me alegro de que todos seamos capaces de expresarnos libremente y espero que sigamos haciéndolo.
- Problemas de comunicación y falta de información. Al inicio hubo algunos problemas de comunicación entre las diferentes áreas de trabajo y, si bien pensaba que estaban solucionados, esta última semana de desarrollo se han manifestado nuevas incidencias propiciadas por confusiones evitables o faltas de información. Para solucionar esto, creo que sería necesario comunicar mejor cada una de las tareas realizadas y cada uno de los problemas que nos hemos podido encontrar, así como testear y/o revisar el trabajo de nuestros pares con más frecuencia.
- Presencia en redes sociales. Me he quedado un poco con la sensación de que la presencia en redes sociales la hemos ido improvisando, principalmente por falta de tiempo y material. Creo que sería buena idea elaborar un calendario de contenido para las redes sociales y preparar cada publicación con antelación. Además, de esta forma todos los miembros del equipo estaríamos al tanto de cuáles van a ser las futuras publicaciones y podríamos aportar nuevas ideas, contenido u opiniones.

##### Diseño

En general, en el grupo hay muy buen ambiente de trabajo, consiguen hacer todo estupendamente y a tiempo. En las decisiones grupales nadie discute como si tuviera 12 años y las reuniones son productivas, dentro de lo normal. Considero que soy el menos productivo o el que menos aporta al grupo

### 8.2 Post-Mortem de la etapa Beta

#### Autocríticas individuales

##### Adrian

Buena comunicación con el resto de los miembros y flujo constante. Trabajo realizado rápido y muy buena gestión del tiempo.


##### A mejorar:

- Seguir mejorando la comunicación e intentar hacerme oír más.
- Seguir mejorando la gestión del tiempo para poder elaborar código más limpio de una vez en vez de tener que ponerlo bonito después de estar funcional.
- Comentar más el código.
- No retrasar las consultas de dudas.


##### Alberto

Tras la Alfa, mi papel fue terminar de definir las mecánicas finales y comenzar con el balanceo de las estadísticas para que fuese jugable. Pese a tener el rol de Game Designer nunca había hecho un juego, y menos de estrategia, que llegase a un público mayor que los profesores o un par de compañeros, así que me esperaba que hubiera “exploits” o una dificultad inestable, lo cual ocurrió. 
Lo intenté evitar mirando artículos y vídeos sobre qué elementos componen un tower defense, qué experiencias se pueden intentar crear en el jugador y las distintas mecánicas que existen en el género. Aún así me di cuenta de que, como creador de la jugabilidad, mi perspectiva era muy diferente a la de un jugador externo al proyecto. También fue una mala idea intentar balancear las oleadas, el daño de las torres, su precio y todos los stats de los enemigos en tres días, ya que no daba tiempo a balancear, descansar y desconectar y volver a ello para ver más rápido posibles errores que hubieran. 
Sin pausas uno se enfrasca en el proyecto y adquiere visión de túnel, en el que solo se ve lo que se tiene en la cabeza y no muchas más posibles variantes. Creo que el error en general fue la falta de experiencia, la cual ahora tengo un poco más y no habría hecho las cosas como las hice.


##### Daniel

Por lo general he seguido trabajando al mismo nivel que en la fase anterior, aunque he podido prestar algo más de atención a lo que estaban haciendo mis compañeros y he usado más el tablero de Trello para organizarme, que es algo que me había propuesto.


##### Gonzalo

Diría que he estado mejor. He estado más pendiente y activo en el Trello, igual que en Github. Aunque por toda la cantidad de trabajo que ha habido a parte de este proyecto, no he podido hacer el DevBlog de la Beta a tiempo. Eso sí, fue buena idea hacer que el equipo de arte se pusiera a full desde el minuto uno. De no ser por eso dudo que hubiéramos podido meter todo lo que a nivel de funcionamiento ya estaba preparado.

Aunque noto que el tema publicidad no es lo mío.

En verdad no me acuerdo de muchas más cosas de la etapa Beta. Gran parte de las cosas que dije para la Alfa se podrían aplicar para el post mortem de esta etapa: mantener la atención sobre cuando completan tareas, pre-asignar futuras tareas para que así mis compañeros sepan en qué trabajar después, recordatorios con un margen de tiempo para las reuniones, etc.


##### Joy

Comento lo mismo que en el Post Mortem de la Alfa: conocer mejor el código de mis compañeros y expresar mejor mis ideas.


##### Marta

Cosas que han funcionado bien:

○ He sido capaz de expresar abiertamente mi opinión.

○ He establecido buenos horarios de trabajo. Esto me ha hecho sentirme bien conmigo misma y con el proyecto y, en consecuencia, me ha permitido relacionarme adecuadamente con el resto del equipo y mantener un buen ritmo de trabajo.

Cosas a mejorar:

○ Creo que ampliar mis conocimientos y aprender otros programas como Adobe Illustrator y Adobe XD podría ser útil para futuros desarrollos. Debido a que Adobe Photoshop tiene sus limitaciones en el ámbito del desarrollo UX/UI.

  


#### Críticas de equipo

##### Programador 1

Para esta deadline creo que el equipo al completo nos hemos compenetrado bastante mejor que en la anterior y el juego ha mejorado drásticamente en consecuencia, al menos en lo que a game feel y aspecto visual se refiere.Sin embargo aún tenemos que mejorar la comunicación, puesto que nos ha ocurrido varias veces que varias personas solucionaban el mismo error por lo que se perdía tiempo o un error que ya se había solucionado, reaparecía debido a un puntual mal manejo del sistema de control de versiones.

##### Artista


Buen ambiente y asertividad. El ambiente de trabajo ha sido muy bueno, todo el mundo ha dado su opinión de manera asertiva y eso ha facilitado una correcta comunicación y exposición de las ideas, lo cual beneficia al desarrollo del proyecto.

##### Diseño

No ha variado mi opinión respecto a la Alfa, un grupo estupendo donde la única queja que podría haber son consecuencias de tener una jerarquía horizontal, la toma de decisiones.

##### Programador 2


El trabajo ha sido fluido y sale bien. Hay un buen ambiente de trabajo y se siente el progreso de cada uno del equipo como propio gracias al Trello y las reuniones. Las reuniones semanales son un acierto, aunque posteriormente se debatirán algunos detalles.Las reuniones deberían contar con un esquema previo y tratar sobre temas específicos en vez de tantas generales para hacerlas más útiles y concisas. También tener fechas de entrega de tareas, siempre teniendo en cuenta la disponibilidad de cada persona, pero tener plazos fijados.Respecto a la corrección del trabajo de otros miembros mejor que editarlo directamente se cree más conveniente que se le comuniquen las ideas de mejora al encargado de esa tarea y sea él o ella quien realice las modificaciones. Todo esto para ahorrar tiempo y evitar errores inesperados.

##### Programador 3

Hemos trabajado algo mejor en comparación a la Alfa y hemos tenido menos conflictos pero aún falla la cooperación y cometemos errores como no testear correctamente los cambios antes de hacer un pull request o no mirar el GDD antes de implementar algo.Me alegro de que nos esforzáramos tanto en la fase anterior, porque nos ha permitido relajarnos algo más en ésta.

##### Scrum Master


El juego ha salido bastante bien de la fase Beta. Casi todos los elementos que teníamos planeados para el juego al final acabaron pasando el corte, salvo la destrucción del cubo, que se aprovechó lo ya hecho de otra manera, y los enemigos ligero y especialista.En general el equipo ha prestado más atención al GDD, lo cual nos ha evitado algunos malentendidos y ha permitido ajustar más el comportamiento de algunos elementos del juego (estoy hablando de la torre pesada aka Batracius).Nos deberíamos de sentir bastante orgullosos de que, siendo uno menos, hayamos salido bien adelante con este proyecto.El equipo de arte ha estado fenomenal: no solo ha logrado a tiempo sacar todos los elementos visuales del juego, sino que encima son preciosos; encajando muy bien con el tono del juego, algo que ya nos han dejado claro que gusta.El equipo de diseño ha pasado por bastante peso en esta etapa, sobre todo hacia el final de la etapa, algo que le ha dejado con poco tiempo para ajustar correctamente todo. Por suerte ha salido con unos resultados divertidos, aunque queda trabajo por hacer.El equipo de publicidad ha estado bien, aunque por falta de tiempo en general su trabajo se ha concentrado al final de la etapa, en el anuncio de salida de la Beta del juego.  


### 8.3 Post-Mortem de la etapa Gold


## 9. Hoja de ruta del desarrollo

### 9.1 Hito 1: Alfa

- Motor Voxel que genere de manera procedural el cubo, los caminos y los obstáculos: 26/10/2021
- Funcionalidades básicas de juego (IA, vida y ataque):25/10/2021
- Juego responsive: 18/10/2021.
- Torres y enemigos definidos, con concepts y algún modelo de ellos: 29/10/2021
- Campaña de marketing iniciada (redes sociales preparadas): 11/10/2021


### 9.2 Hito 2: Beta

- Interfaz implementada con estructura final y arte de GUI final: 19/11/2021
- Tutorial introductorio en el que se expliquen las mecánicas básicas: 20/11/2021
- Balanceo de las estadisticas de enemigos y torres para hacer el juego divertido y justo: 15/11/2021
- Crear y meter en el juego los 4 modelos de enemigo y los 6 modelos de torre/defensa: 20/11/2021
- Nueva mecánica característica: No alcanzado
- Añadir offset para la colocación de torres: 19/11/2021
- Arreglar proporciones de las torres en el cubo: 18/11/2021
- Dirigir correctamente la barra de vida de los enemigos hacia la camara del jugador: 16/11/2021
- Portfolio actualizado en su nueva versión: 21/11/2021
- Añadir estanque en el spawn de los enemigos: 19/11/2021

### 9.3 Hito 3: Gold

- Pulir la generación de caminos en el cubo: 9/12/2021
- Dar nombres definitivos a las torres y enemigos: 29/11/2021
- Cambiar modelo de puntuación: 10/12/2021
- Aumentar la Updated to GOoMS versionaccesibilidad de los tutoriales: 12/12/2021
- Ajustar curva de dificultad: 12/12/2021
- Proyectiles enemigos en tapones de enemigos: 7/12/2021
- Añadir elementos restantes a la interfaz: 10/12/2021
- Añadir animaciones a las torres: 11/12/2021
- Añadir efectos de partículas a las torres: 9/12/2021
- Añadir efectos de sonido a la interfaz: 9/12/2021

### 9.4 Fecha de lanzamiento

- Campaña de marketing en redes sociales en el que se hable de los distintos elementos del juego:
  
