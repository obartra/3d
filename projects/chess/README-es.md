# El Juego de Ajedrez de Perros con Capacidades Diferentes

> Traducciones generadas en [<img src="./images/flags/cat.png" height=14 alt="Catalán" />](./README-cat.md) [<img src="./images/flags/fr.png" height=14 alt="Francés" />](./README-fr.md). Original en [<img src="./images/flags/us.png" height=14 alt="Inglés" />](./README.md)

Este proyecto es un tributo a mi entrenadora de perros, Casey Buckley, quien dirige [WP Creative Pets](https://www.wpcreativepets.com/). Si tienes un perro, especialmente uno reactivo, y estás en el área de Filadelfia, no encontrarás mejor entrenadora. Ella se adapta fácilmente a diferentes estilos de enseñanza, está informada sobre traumas, es amigable con la comunidad queer y extremadamente talentosa.

## Historia

Nuestro perro, Iroh, tenía algunos problemas de ansiedad que no pudimos superar hasta que la contactamos. Aquí está ahora, siendo un buen chico:

<p align="center">
    <img alt="Perro mezcla de pitbull y husky en blanco y negro con un collar azul y placas, sentado en un camino cubierto de pétalos de flores rosas, con árboles y vegetación a los lados del camino en un día soleado." src="./images/Iroh.png" width="200" />
</p>

Como agradecimiento por el incansable trabajo de Casey y su impacto en Iroh, quise hacer un proyecto en 3D que sirviera tanto como práctica para mí, ya que estoy aprendiendo a imprimir en 3D, y para honrar su trabajo. Sabiendo que ella colecciona juegos de ajedrez únicos, decidí construirle un juego de ajedrez personalizado con perros con discapacidades. Era importante que estos se mostraran con normalidad y enfocándose en lo positivo en lugar de cualquier aspecto limitante, ya que eso capturaría más precisamente su enfoque y su trabajo.

## Piezas de Ajedrez

Encontré [este juego de ajedrez](https://www.thingiverse.com/thing:5590380) en Thingiverse que era adorable y un excelente punto de partida.

<p align="center">
    <img alt="Seis piezas de ajedrez blancas impresas en 3D que se asemejan a perros, incluyendo dos con coronas, y una pequeña caseta de perro, todas colocadas sobre una superficie verde. Esta imagen muestra el diseño original del juego de ajedrez que inspiró el juego de ajedrez de perros con habilidades diferentes." src="./images/reference-set.png" width="400" />
</p>

### Ideación y Diseño del Modelo 3D

La idea era crear un conjunto que no solo representara diferentes razas de perros, sino que también destacara diversas discapacidades de manera positiva e inclusiva. Quería resaltar una gama diversa de discapacidades para hacer el conjunto lo más inclusivo y representativo posible. Estas discapacidades fueron elegidas para reflejar tanto condiciones visibles como invisibles, temporales y permanentes, con el objetivo de crear conciencia a través del ajedrez.

| Pieza de Ajedrez | Discapacidad | Ayuda Adaptativa |
| - | - | - |
| Rey | Amputación de pata delantera | Pierna protésica |
| Reina | Discapacidad temporal (post-cirugía) | Cono |
| Alfil | Parálisis | Silla de ruedas |
| Caballo | Ceguera | Halo |
| Torre | Artritis | Rampa, alfombra ortopédica |
| Peones 1 y 2 | Trastorno de deglución | Biberón |
| Peones 3 y 4 | Discapacidad invisible | N/A |
| Peones 5 y 6 | Trastorno de ansiedad | Medicación |
| Peones 7 y 8 | Enfermedad degenerativa del disco | Cama ortopédica |

El siguiente paso fue averiguar cómo representar estas discapacidades en los modelos. Incorporé algunos diseños adicionales de Thingiverse en el proyecto y creé el resto.

Por ejemplo, la silla de ruedas del alfil se basó en [este modelo](https://www.thingiverse.com/thing:1397964):

![Chihuahua pequeño en una silla de ruedas impresa en 3D de color verde neón y negro, ladrando o aullando, contra un fondo amarillo brillante.](./images/figowebp.webp)

El renderizado final se veía así:

![Fila de piezas de ajedrez en 3D renderizadas en negro, que se asemejan a perros con habilidades diferentes, sobre bases redondas, colocadas en un fondo verde brillante. De izquierda a derecha: un perro con una pierna protésica y corona, un perro con un cono y corona, un perro en silla de ruedas, un perro con un halo, un perro en una caseta con rampa accesible, y cinco perros pequeños en varias poses, uno con un biberón, otro con pastillas, otro sentado en una cama ortopédica. Estas piezas representan el juego de ajedrez de perros con habilidades diferentes personalizado](./images/render/all.png)

### Proceso de Impresión 3D

Para lograr los mejores resultados, utilicé una altura de capa pequeña de 0.12mm para capturar pequeños detalles. Las piezas se imprimen sólidas, haciéndolas más pesadas y duraderas.

Tomó un par de iteraciones averiguar cómo imprimirlas mejor; algunas, como el rey y el alfil, se imprimieron mejor sin soportes. Otras, como la reina (por el cono) y el caballo (por el halo), los necesitaron.

Dado que muchas tenían detalles delicados (como el halo del caballo), decidí recubrirlas con resina UV transparente para aumentar su resistencia.

### Uso de Resina UV

El uso de resina UV fortalece las piezas pero requiere precauciones de seguridad, como usar equipo de protección. El proceso es sencillo pero requiere cierta preparación. Sigue las instrucciones de la resina para el tiempo de curado para evitar el sobrecurado. Asegúrate de no mirar directamente a la luz UV y evitar el contacto de la piel con la resina.

| Material | Imagen |
| - | - |
| [Resina UV](https://a.co/d/ezitsoy) | <img src="./images/materials/resin.jpg" width="200" /> |
| [Luz UV](https://a.co/d/ezitsoy) | <img src="./images/materials/uvlight.webp" width="200" /> |
| [Gafas de Protección](https://a.co/d/0IKj0s0) | <img src="./images/materials/uvgoggles.jpg" width="200" /> |
| [Guantes de Protección](https://a.co/d/9HWPJkN) | <img src="./images/materials/gloves.webp" width="200" /> |
| [Bata de Protección](https://a.co/d/4McWedg) | <img src="./images/materials/coat.webp" height="200" /> |

Después de aplicar la resina, y para asegurarme de que las piezas se deslizaran bien en el tablero de ajedrez, usé [fieltro verde](https://a.co/d/2bVIOpZ).

### Piezas de Ajedrez Finales

Aquí está el resultado final:

| Pieza de Ajedrez | Discapacidad | Render 3D | Impreso |
| - | - | - | - |
| Rey | Amputación | ![](./images/render/king.png) | ![](./images/print/king.png) |
| Reina | Temporal / Post-cirugía | ![](./images/render/queen.png) | ![](./images/print/queen.png) |
| Alfil | Parálisis | ![](./images/render/bishop.png) | ![](./images/print/bishop.png) |
| Caballo | Ceguera | ![](./images/render/knight.png) | ![](./images/print/knight.png) |
| Torre | Artritis | ![](./images/render/rook.png) | ![](./images/print/rook.png) |
| Peones 1 y 2 | Trastorno de deglución | ![](./images/render/pawn1.png) | ![](./images/print/pawn1.png) |
| Peones 3 y 4 | Discapacidad invisible | ![](./images/render/pawn2.png) | ![](./images/print/pawn2.png) |
| Peones 5 y 6 | Trastorno de ansiedad | ![](./images/render/pawn3.png) | ![](./images/print/pawn3.png) |
| Peones 7 y 8 | Enfermedad degenerativa del disco | ![](./images/render/pawn4.png) | ![](./images/print/pawn4.png) |

## Tarjetas

El objetivo de las tarjetas era hacer más claras las discapacidades mostradas en las piezas de ajedrez mientras se destacaban de manera positiva o neutral, no como una limitación, sino simplemente como parte de la vida del perro.

Después de explorar diferentes estilos, elegí un aspecto ornamentado y antiguo.

| Antiguo | Ecológico | Moderno |
| - | - | - |
| ![Prototipo de tarjeta de estilo ornamentado, antiguo y floral de Kingly el Gran Danés](./images/card/style-antique.jpg) | ![Prototipo de tarjeta de estilo ecológico, moderno de Kingly el Gran Danés](./images/card/style-eco.jpg) | ![Prototipo de tarjeta de estilo minimalista de Kingly el Gran Danés](./images/card/style-minimal.jpg) |

Como el lema de WP Creative Pets es "Cada Momento es un Momento de Entrenamiento", quise incorporarlo como parte del conjunto de tarjetas. Con algo de ayuda de ChatGPT, llegué a la traducción aproximada en latín de "Omne Momentum Disciplina Est."

<p align="center">
    <img src="./images/card/moto.png" width="200" alt="Ilustración de estilo vintage ornamentado con un marco floral decorativo con un centro circular vacío y pancartas que dicen 'Omne Momentum' en la parte superior y 'Disciplina Est' en la parte inferior, en tonos marrones y beige" />
</p>

### Fuentes y Diseño

En cuanto a las fuentes, elegí Trajan Pro tanto para el lema como para el título, ya que parecía combinar bien con el estilo de la tarjeta. OpenDyslexicAlta para el cuerpo fue elegida por su legibilidad y accesibilidad, especialmente porque el objetivo de este ejercicio es no estar limitado por discapacidades.

| Trajan Pro | Open Dyslexic Alta |
| - | - |
| ![Muestra de Trajan Pro](./images/font/trajan-pro.png) | ![Muestra de Open Dyslexic Alta](./images/font/OpenDyslexicAlta.png) |

### Detalles de la Tarjeta

| Pieza de Ajedrez | Tarjeta |
| - | - |
| Rey | <img src="./images/card/king.png" alt="Ilustración de estilo vintage ornamentado con un Gran Danés con tres patas en un marco floral decorativo. El texto dice: 'Kingly el Gran Danés. Kingly, nuestro soberano de tres patas, contempla su reino con una mirada noble. A pesar de perder una extremidad en un rescate valiente, su estatura sigue siendo grandiosa, su comportamiento inquebrantable.' En la parte superior, una pancarta dice 'Omne Momentum Disciplina Est.'" width="200" /> |
| Reina | <img src="./images/card/queen.png" alt="Ilustración de estilo vintage ornamentado con un galgo afgano en un marco floral decorativo. El texto dice: 'Queenie la Afgana. La elegancia de Queenie trasciende el tablero de ajedrez, su cono es un emblema temporal de su reciente cirugía. Con la gracia de una estratega, sus movimientos son un testamento silencioso de su espíritu resiliente.' En la parte superior, una pancarta dice 'Omne Momentum Disciplina Est.'" width="200" /> |
| Alfil | <img src="./images/card/bishop.png" alt="Ilustración de estilo vintage ornamentado con un Akita en una silla de ruedas dentro de un marco floral decorativo. El texto dice: 'Bishop el Akita. Bishop el Akita rueda a través del tablero de ajedrez, un faro de esperanza para todos los que enfrentan desafíos. Su silla de ruedas no lo confina; es su carroza, llevándolo de una victoria a otra.' En la parte superior, una pancarta dice 'Omne Momentum Disciplina Est.'" width="200" /> |
| Caballo | <img src="./images/card/knight.png" width="200" alt="Ilustración de estilo vintage ornamentado con un Bóxer con ojos sin vista en un marco floral decorativo. El texto dice: 'Knightly el Bóxer. Knightly, el centinela sin vista del tablero de ajedrez, posee un coraje que resuena más allá del reino visual. Su halo no es solo una guía sino un símbolo de su conciencia elevada.' En la parte superior, una pancarta dice 'Omne Momentum Disciplina Est.'" /> |
| Torre | <img src="./images/card/rook.png" width="200" alt="Ilustración de estilo vintage ornamentado con un mestizo en un marco floral decorativo. El texto dice: 'Rocky el mestizo. Rocky, con artritis y un defensor firme del reino, guarda las murallas con un espíritu inquebrantable. La rampa junto a su caseta no es un signo de debilidad sino un testimonio de su adaptabilidad.' En la parte superior, una pancarta dice 'Omne Momentum Disciplina Est.'" /> |
| Peones 1 y 2 | <img src="./images/card/pawn1.png" width="200" alt="Ilustración de estilo vintage ornamentado con un Chihuahua en un marco floral decorativo. El texto dice: 'Pebbles el Chihuahua. Pebbles se erige como un faro de perseverancia, navegando la vida con megaesófago. Su nutrición llega en sorbos cuidadosos de un biberón especialmente diseñado, haciendo de cada comida un triunfo sobre la adversidad.' En la parte superior, una pancarta dice 'Omne Momentum Disciplina Est.'" /> |
| Peones 3 y 4 | <img src="./images/card/pawn2.png" width="200" alt="Ilustración de estilo vintage ornamentado con un Chihuahua en un marco floral decorativo. El texto dice: 'Poppy el Chihuahua. Poppy, con Trastorno del Procesamiento Sensorial, pero sin signos externos de sus desafíos, se mueve con una gracia etérea en el tablero de ajedrez, sus sentidos sintonizados a una frecuencia diferente a la de sus compañeros caninos.' En la parte superior, una pancarta dice 'Omne Momentum Disciplina Est.'" /> |
| Peones 5 y 6 | <img src="./images/card/pawn3.png" width="200" alt="Ilustración de estilo vintage ornamentado con un Chihuahua en un marco floral decorativo. El texto dice: 'Patch el Chihuahua. Patch se mueve por el tablero de ajedrez con ansiedad pero también con una resolución inquebrantable. Sus pasos cuidadosos se combinan con respiraciones profundas, ya que ha dominado el arte del enfoque tranquilo.' En la parte superior, una pancarta dice 'Omne Momentum Disciplina Est.'" /> |
| Peones 7 y 8 | <img src="./images/card/pawn4.png" width="200" alt="Ilustración de estilo vintage ornamentado con un Chihuahua en un marco floral decorativo. El texto dice: 'Pillow el Chihuahua. Pillow encuentra consuelo en el apoyo de su trono ortopédico, un bastión en medio de las pruebas de la enfermedad degenerativa del disco. Cada paso a lo largo de los cuadros ajedrezados es prueba de su resistencia.' En la parte superior, una pancarta dice 'Omne Momentum Disciplina Est.'" /> |

La parte posterior era la misma para todas las tarjetas:

| Diseño | Impreso |
| - | - |
| <img src="./images/card/back.png" height="320" alt="Una tarjeta de estilo vintage ornamentado con diseño floral y scrollwork enmarcando el texto: 'WP Creative Pets El Juego de Ajedrez de Perros con Habilidades Diferentes' en una fuente serif decorativa." /> | <img src="./images/card/print-back-and-front.jpeg" height="320" alt="Cuatro tarjetas se muestran sobre una superficie de madera. Una tarjeta es completamente visible, mostrando un diseño ornamentado detallado con una imagen de un perro Akita, etiquetada como 'Bishop el Akita'. El texto describe a Bishop como un perro en silla de ruedas que es un faro de esperanza y un símbolo de superación de desafíos. Las otras tres tarjetas están orientadas hacia atrás, parcialmente visibles, con diseños ornamentados y el texto 'WP Creative Pets - El Juego de Ajedrez de Perros con Habilidades Diferentes.'" /> |

Una vez diseñadas, las tarjetas fueron hechas por [MakePlayingCards.com](https://www.makeplayingcards.com/design/custom-us-game-deck-size-cards.html). El archivo de Photoshop que incluye todas las variaciones de las tarjetas y la plantilla de MakePlayingCards.com está disponible [aquí](./assets/tarot-size.psd). Imprimieron en plástico de alta calidad y cortaron y enviaron las tarjetas.

Una iteración anterior de las tarjetas también está disponible [aquí](./assets/us_game_deck.psd), pero decidí no usarla debido a su tamaño más pequeño, que impactó la legibilidad, y en última instancia, no estaba satisfecho con mi primer diseño. Si tienes curiosidad al respecto, así es como se veían:

| Impreso | Frente | Reverso |
| - | - | - |
| <img src="./images/card/wrapped.jpeg" width="200" alt="Tarjeta impresa con la leyenda 'Kingly el Gran Danés' con una ilustración de un Gran Danés con tres patas, rodeada de elementos decorativos y texto que describe su historia. La tarjeta está envuelta en plástico, colocada sobre una superficie de madera. La pancarta inferior dice 'Omnis Momentum Disciplinae.'" /> | <img src="./images/card/pawn4-old.png" width="200" alt="Ilustración de estilo vintage ornamentado con un Chihuahua en un marco circular coronado con una corona y flanqueado por escudos ajedrezados. El texto dice: 'Pillow el Chihuahua. Pillow encuentra consuelo en el apoyo de su trono ortopédico, un bastión en medio de las pruebas de la enfermedad degenerativa del disco. Cada paso calculado a lo largo de los cuadros ajedrezados es prueba de su resistencia.' En la parte inferior, una pancarta dice 'Omne Momentum Disciplina Est.' El diseño incluye íconos de piezas de ajedrez y elementos decorativos en tonos beige y negro." /> | <img src="./images/card/back2.png" width="200" alt="Ilustración de estilo vintage ornamentado con un perro de pelo largo con una corona, enmarcado por intrincados diseños florales y scrollwork. Tres pancartas rodean al perro, con el texto: 'El Diferente' en la parte superior, 'Juego de Ajedrez de Perros' en el medio, y 'WP Creative Pets' en la parte inferior. El diseño es en tonos de negro, marrón y beige, dándole un aspecto antiguo." /> |

## Tablero

El tablero de ajedrez está diseñado para representar un parque para perros, con la mitad de las baldosas representando "arena" y la otra mitad "césped," rodeado por un camino.

### Diseño y Construcción del Tablero

El tablero de ajedrez representa un parque para perros con baldosas de césped y arena, rodeado por un camino. Las baldosas fueron impresas con texturas detalladas para imitar superficies de la vida real. El tablero de ajedrez está compuesto por cuatro cuadrantes, cada uno repetido dos veces:

![Diagrama de un tablero de ajedrez dividido en cuatro cuadrantes, cada uno con un patrón distinto. El tablero muestra que las diagonales desde la esquina inferior izquierda hasta la superior derecha y desde la esquina inferior derecha hasta la superior izquierda tienen patrones consistentes. Los cuadrantes están marcados con diferentes colores y estilos de sombreado, con una clara delimitación para demostrar la división y la consistencia del patrón a lo largo de las diagonales.](./images/chess-diagonals.png)

Representar el césped requirió varias iteraciones, finalmente llegando a este patrón que se imprimió como una pequeña serie de hilos finos. Los agujeros se llenaron con las baldosas de arena, que se imprimieron verticalmente para una mejor resolución.

![Impresora 3D creando las baldosas verdes que representan el 'césped' para un tablero de ajedrez temático de parque para perros. La boquilla se mueve de un lado a otro, depositando filamento verde capa por capa. La baldosa toma forma gradualmente con una textura detallada, contrastando con los alrededores.](./images/board/grass-printing.gif)

![Primer plano de un cuadrante verde de 'césped' para el tablero de ajedrez temático de parque para perros, con una superficie texturizada. Una baldosa blanca de 'arena' está colocada en uno de los espacios, contrastando con las baldosas verdes de 'césped' que la rodean. La baldosa de 'arena' tiene una textura suave y ondulada, resaltando la diferencia entre los dos tipos de baldosas.](./images/board/first-sand-tile.jpeg)

Una vez que los cuatro cuadrantes de césped fueron impresos y llenados con las baldosas de arena, los pegué en su lugar sobre una hoja de metal para darles una sensación de peso. Utilicé una aleación de aluminio 6061 de <https://www.onlinemetals.com>, que ofrece cortes personalizados, lo que me permitió pedir una hoja precortada.

![Tablero de ajedrez temático de parque para perros preensamblado con baldosas alternas de 'césped' verde y 'arena' blanca. Las baldosas verdes texturizadas contrastan con las baldosas blancas lisas y onduladas, creando un patrón de tablero de ajedrez. Algunas baldosas están apiladas en el fondo, y el tablero está parcialmente ensamblado sobre una superficie de trabajo, mostrando el progreso del proyecto.](./images/board/pre-assembled.jpeg)

Para el borde, utilicé [estas baldosas](https://www.thingiverse.com/thing:2480607) de Thingiverse que ya parecían pavimento y añadí diferentes escenas con perros relajándose, jugando y tratando de agarrar algunos huesos y frutas.

![Renderización 3D de una baldosa rectangular con una textura de adoquines. La baldosa es azul y está colocada plana sobre una cuadrícula gris, mostrando su superficie detallada y desigual, que se asemeja a una sección de un camino de adoquines.](./images/board/pavement.webp)

| Huesera | Ladrón de Zanahorias | Chihuahua Relajado | Reunión de Perros |
| - | - | - | - |
| ![Esquina de un tablero de ajedrez temático de parque para perros con 'caminos' grises con texturas detalladas. Una pequeña figura de perro está posicionada cerca de un pozo circular, añadiendo una escena a la esquina. El patrón de tablero de ajedrez consiste en baldosas alternas de 'césped' verde y 'arena' blanca. Los caminos grises proporcionan un fondo realista, contrastando con los colores vibrantes de las baldosas.](./images/board/side-bones.jpeg) | ![Primer plano de una sección de esquina del tablero de ajedrez temático de parque para perros, mostrando 'caminos' grises detallados con figuras de perros y varios objetos. Dos figuras de perros, una de pie con una zanahoria en la boca y otra sentada, están posicionadas cerca de cajas llenas de comida. Las cajas y los perros añaden una escena realista a la esquina. En el fondo, el patrón de tablero de ajedrez de baldosas alternas de 'césped' verde y 'arena' blanca es visible, proporcionando un contraste vibrante con el camino gris y las figuras.](./images/board/side-boxes.jpeg) | ![Sección de esquina del tablero de ajedrez temático de parque para perros, mostrando un 'camino' gris detallado con una pequeña figura de Chihuahua en el centro. En el fondo, el patrón de tablero de ajedrez de baldosas alternas de 'césped' verde y 'arena' blanca crea un contraste vibrante. El camino gris y la figura del perro pequeño añaden una escena realista al borde del tablero, contrastando con las baldosas coloridas.](./images/board/side-chihuahua.jpeg) | ![Sección de esquina del tablero de ajedrez temático de parque para perros, con un 'camino' gris detallado con pequeñas figuras de perros y una boca de incendio. Un perro está de pie cerca de la boca de incendio, mientras que otro se sienta junto a una pelota. En el fondo, el patrón de tablero de ajedrez de baldosas alternas de 'césped' verde y 'arena' blanca crea un contraste vibrante con el camino gris y las figuras. La escena añade un toque lúdico y realista al borde del tablero.](./images/board/side-hydrant.jpeg) |

Intenté cubrir los huecos entre los cuadrantes usando un bolígrafo 3D y lijando el exceso, pero aún eran bastante visibles.

Finalmente, cubrí la superficie nuevamente con resina UV. Ojalá hubiera tenido en cuenta los huecos, porque causaron algunas burbujas grandes. La resina calentada también disolvió los hilos de césped, lo cual fue desafortunado. Puedes ver cómo se veía con y sin resina a continuación:

| Con Resina | Sin Resina |
| - | - |
| ![Tablero de ajedrez completamente ensamblado con todas las piezas en su lugar, posicionado sobre una mesa de madera. Las piezas están dispuestas para una partida, con piezas blancas en un lado y piezas grises en el otro. El tablero y las piezas tienen una apariencia brillante y húmeda debido a la aplicación de resina UV, que realza su textura y detalle. La resina añade un acabado brillante, haciendo que los colores y los detalles sean más vibrantes.](./images/board/full.jpeg) | ![Tablero de ajedrez temático de parque para perros parcialmente ensamblado sobre una mesa de madera. El tablero tiene baldosas alternas de 'césped' verde y 'arena' blanca, bordeadas por 'caminos' grises detallados con pequeñas figuras de perros y otros elementos. Herramientas y suministros, incluyendo cinta adhesiva y pintura en aerosol, están esparcidos alrededor de la mesa. Dos piezas de ajedrez, un caballo y una torre, están colocadas en el tablero, pero la resina UV no ha sido aplicada.](./images/board/assembled.jpeg) |

## Caja del Tablero

No pude usar la impresora 3D para la caja ya que era mucho más grande que el tablero de ajedrez. Hacerla en una sola pieza sólida asegura que pueda sostener el tablero de ajedrez de manera confiable.

Como el tablero de ajedrez mide 13.75"x13.75", reutilicé una caja de pizza de 14". La pinté de morado y le hice una plantilla de una pieza de ajedrez con una cabeza de perro como logotipo. Para protegerla, añadí una capa de [policrílico](https://a.co/d/cTNn0YK) transparente. Puedes ver el proceso a continuación:

| Paso | Imagen |
| - | - |
| Diseño Inicial | <img alt="diseño SVG en blanco y negro de la plantilla utilizada para el proyecto. El diseño es una pieza de ajedrez estilizada con una cabeza de perro, lista para ser recortada y utilizada como plantilla para pintar." src="./images/box/stencil.svg" width="200" /> |
| Crear plantilla | <img alt="Una estera de corte verde en una mesa desordenada. Sobre la estera hay una impresión en blanco y negro de un diseño de plantilla que se asemeja a una pieza de ajedrez con una cabeza de perro. Hay varias herramientas como un cuchillo de uso, una regla y un bolígrafo esparcidos alrededor. La mesa también tiene otros objetos, incluyendo cinta adhesiva, raíces de jengibre, un jarrón de vidrio con flores y un pequeño contenedor morado." src="./images/box/stencil-design.jpeg" width="200" /> |
| Pintura en aerosol | <img alt="Diseño de plantilla siendo pintado con aerosol sobre una superficie, fijada con cinta adhesiva azul de pintor. El diseño, una pieza de ajedrez con una cabeza de perro, se está pintando de negro. El fondo incluye cartón y algo de vegetación, indicando que la pintura se está realizando al aire libre en un banco de trabajo o lugar similar." src="./images/box/stencil-spray.jpeg" width="200" /> |
| Pintado | <img alt="Una caja de pizza reutilizada pintada de morado con un diseño de plantilla negra rociada sobre ella. El diseño representa una pieza de ajedrez con una cabeza de perro, mostrando un aspecto audaz y limpio. El fondo incluye algunas flores en un jarrón, sugiriendo que la caja está en una cocina o área de estar." src="./images/box/stencil-repainted.jpeg" width="200" /> |

Para el interior, quise añadir una señal en Braille ya que tenemos un perro ciego en el juego de ajedrez. El texto incluye un enlace a esta publicación. Utilicé <https://touchsee.me> para generar los archivos STL para Braille contraído (Grado 2) de modo que el texto dijera:

| Texto Plano | Contraído | Braille | Renderizado | Ensamblado |
| - | - | - | - | - |
| <img src="./images/braille/plain.png" width="200" alt="El texto 'El Juego de Ajedrez de Perros con Habilidades Diferentes. Hecho con amor por Oscar Bartra para Casey Buckley, WP Creative Pets, y todas sus mascotas. Aprende más en: bit.ly/dogchess'" /> | <img src="./images/braille/contracted.png" width="200" alt="Braille contraído con la correspondiente traducción: ',! ,di6}5tly-,a#d ,dog ,*ess , set4 ,made ) love 0,osc> ,b>tra = ,casey ,buckley1 ,,wp ,cr1tive ,pets1 & all h} pets4 ,le>n m at3 bit4ly_/dog*ess'" /> | <img src="./images/braille/braille.png" width="200" alt="Representación en braille del siguiente mensaje: 'El Juego de Ajedrez de Perros con Habilidades Diferentes. Hecho con amor por Oscar Bartra para Casey Buckley, WP Creative Pets, y todas sus mascotas. Aprende más en: bit.ly/dogchess'" /> | <img src="./images/braille/render.png" width="200" alt="Renderizado 3D del texto en braille con una flecha de inicio y un marco alrededor." /> | <img src="./images/braille/assembled.jpeg" width="200" alt="Una caja pintada de morado que contiene un juego de ajedrez impreso en 3D. El tablero de ajedrez es visible en la parte superior, con cuadros verdes y beige con un borde gris. Dentro del pliegue superior de la caja, hay un texto en Braille púrpura y negro." /> |

Tomó varios intentos lograr un texto en Braille claro. También hay un código QR que enlaza a esta página. Lo generé usando <https://printer.tools/qrcode2stl>. Desafortunadamente, no pude imprimirlo de una manera que se viera lo suficientemente bien como para incluirlo en el tablero. Finalmente, hice una tarjeta adicional con el código QR en su lugar.

| Renderizado | Resultado | Tarjeta |
| - | - | - |
| ![Renderizado 3D de un código QR con un icono de información en el centro y un borde cuadrado alrededor de todo el código. El código QR parece elevado desde una superficie plana, y el texto "bit.ly/dogchess" está grabado en relieve a lo largo del borde inferior. El diseño general está configurado contra un fondo de cuadrícula oscuro.](./images/qr/render.png) | ![Fotografía de una impresión 3D fallida de un código QR sobre una superficie de madera. La impresión tiene problemas significativos de cordones, con hilos delgados de filamento conectando varias partes del código QR. El código está impreso en negro sobre un fondo morado, con el texto "bit.ly/dogchess" en la parte inferior. El icono de información es visible en el centro del código, y la impresión está enmarcada por un borde cuadrado. La superficie de la impresión es desigual y desordenada debido a los problemas de cordones.](./images/qr/attempt.png) | ![Una tarjeta con un marco floral ornamentado alrededor de un código QR. La tarjeta contiene el siguiente texto: 'obarta.github.io/3d/projects/chess Hecho con ❤️ por Oscar Bartra para Casey Buckley, WP Creative Pets, y todas sus mascotas'](./images/card/print-qr.png) |

Para tanto el Braille como el código QR, tuve que añadir una pausa para cambiar el filamento ya que mi impresora no soporta impresiones con múltiples materiales. Para hacerlo, añade `M600` al G-code generado donde la pausa debe ocurrir. Si tienes curiosidad sobre lo que sucede cuando añades la pausa en la capa equivocada, puedes verlo aquí:

![Fotografía de una impresión 3D fallida de una placa de braille sobre una superficie de madera. La impresión tiene una capa superior negra con puntos de braille visibles, pero el cambio de color se aplicó incorrectamente, resultando en el uso de filamento negro en la última capa de la parte base en lugar de la capa prevista. La placa está enmarcada por un borde púrpura, y la superficie parece desigual y desordenada debido al problema de color de la capa. El texto en braille es difícil de leer debido al cambio de color incorrecto.](./images/braille/attempt-layer.png)

Por último, usé el mismo fieltro que para las piezas de ajedrez para cubrir la parte inferior del interior de la caja.

## Soporte para Piezas

Para mantener las piezas organizadas y protegidas, diseñé una caja personalizada. Es un poco voluminosa, pero quería que el soporte dentro de la caja también sirviera como un stand para las piezas para que pudieran mostrarse más fácilmente. La caja es un cubo cuadrado con un inserto dentro destinado a ayudar a minimizar el movimiento de las piezas. La parte frontal de la caja tiene una tapa que se desliza y tiene la misma imagen de la pieza de ajedrez de perro que pintamos con plantilla para la caja del tablero.

| Diseño | Abierto | Parcialmente Abierto | Cerrado |
| - | - | - | - |
| ![Renderizado 3D de un diseño de soporte para piezas de ajedrez dentro de una caja rectangular. El renderizado muestra una pieza de ajedrez de caballo estilizada con una cabeza de perro y varios compartimentos para contener piezas de ajedrez.](./images/piece-box/box-set-design.png) | ![Una caja morada con la tapa abierta, mostrando un soporte de piezas de ajedrez translúcido en su interior. El soporte tiene múltiples niveles, con piezas de ajedrez de temática de perro de color beige. Las piezas están ordenadas en sus respectivos compartimentos.](./images/piece-box/open.jpeg) | ![Una caja morada con la tapa parcialmente abierta, revelando el soporte de piezas de ajedrez translúcido en su interior. El soporte contiene múltiples piezas de ajedrez beige, ordenadas en sus respectivos compartimentos.](./images/piece-box//partially-open.jpeg) | ![Una caja morada cerrada con una pieza de ajedrez de caballo estilizada en negro con una cabeza de perro en el lateral. La caja está colocada sobre una superficie de madera clara.](./images/piece-box/closed.jpeg) |

### Resumen

¡Y eso es todo! Gracias por tomarte el tiempo de leer sobre el Juego de Ajedrez de Habilidades Diferentes.

| Tarjetas | Piezas de Ajedrez | Tablero | Caja del Tablero | Caja de Piezas |
| - | - | - | - | - |
| ![Cinco tarjetas que describen las piezas de ajedrez, cada una con un diseño ornamentado y una imagen de un perro diferente. Las tarjetas están etiquetadas como "Rocky el Mongoose," "Knightly el Bóxer," "Bishop el Akita," "Queenie la Afgana," y "Kingly el Gran Danés," cada una describiendo la historia del perro respectivo y su papel en el juego de ajedrez.](./images/card/print-front.jpeg) | ![Un soporte de piezas de ajedrez negro con múltiples niveles, que contiene piezas de ajedrez de perros de color beige y negro. Las piezas están ordenadas en sus respectivos compartimentos.](./images/render/pieces.jpg) | ![Tablero de ajedrez impreso en 3D con cuadros verdes y beige, configurado para una partida con piezas de ajedrez blancas y negras. El tablero está bordeado con gris, y las piezas presentan varios diseños de perros.](./images/board/full.jpeg) | ![Caja morada para el tablero de ajedrez con una pieza de ajedrez de caballo estilizada en negro con una cabeza de perro en el lateral. La caja está colocada en un mostrador de cocina.](./images/box/stencil-repainted.jpeg) | ![Una caja cúbica morada cerrada con una pieza de ajedrez de caballo estilizada en negro con una cabeza de perro en el lateral. La caja está colocada sobre una superficie de madera clara.](./images/piece-box/closed.jpeg) |

Si quieres dejar un comentario o sugerencia, puedes hacerlo [aquí](https://github.com/obartra/3d/issues/new).

![Un banco de trabajo mostrando un juego de ajedrez personalizado completado. A la izquierda hay una caja de pizza pintada de morado con una pieza de ajedrez de caballo estilizada en negro con una cabeza de perro en la tapa, que contiene el tablero de ajedrez en su interior. A la derecha hay una caja cúbica morada con una pieza de ajedrez de caballo estilizada en negro en el lateral, que contiene las piezas de ajedrez y el soporte. Varias herramientas y suministros son visibles en el fondo.](./images/complete.jpeg)
