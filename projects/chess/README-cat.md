# El Joc d'Escacs de Gossos Amb Capacitats Diferents

> Traduccions generades en [<img src="./images/flags/es.png" height=14 alt="Castellà" />](./README-es.md) [<img src="./images/flags/fr.png" height=14 alt="Francès" />](./README-fr.md). Original en [<img src="./images/flags/us.png" height=14 alt="Anglès" />](./README.md)

Aquest projecte és un homenatge a la meva entrenadora de gossos, Casey Buckley, que dirigeix [WP Creative Pets](https://www.wpcreativepets.com/). Si teniu un gos, especialment reactiu, i esteu a la zona de Filadèlfia, no trobareu millor entrenadora. S'adapta fàcilment a diferents estils d'ensenyament, té coneixements sobre traumes, és amigable amb la comunitat queer i és extremadament talentosa.

## Història

El nostre gos, Iroh, tenia problemes d'ansietat que no podíem superar fins que la vam contactar. Aquí està ara, sent un bon noi:

<p align="center">
    <img alt="Gos barreja de pitbull i husky en blanc i negre amb un collar blau i xapes assegut en un camí cobert de pètals de flors roses, amb arbres i verdor al fons en un dia assolellat." src="./images/Iroh.png" width="200" />
</p>

Com a agraïment pel treball incansable de Casey i el seu impacte en Iroh, volia fer un projecte en 3D que servís tant per a practicar, ja que estic aprenent la impressió 3D, com per a honrar la seva feina. Sabent que ella col·lecciona jocs d'escacs únics, vaig decidir construir un joc d'escacs personalitzat amb gossos amb discapacitats. Era important que aquests es mostressin amb normalitat i enfocats en el positiu en lloc de qualsevol aspecte limitant, ja que això capturaria més precisament el seu enfocament i la seva feina.

## Peces d'Escacs

Vaig trobar [aquest joc d'escacs](https://www.thingiverse.com/thing:5590380) a Thingiverse que era tan adorable com un bon punt de partida.

<p align="center">
    <img alt="Sis peces d'escacs en 3D impreses en blanc semblants a gossos, incloent-hi dos amb corones, i una petita caseta de gossos, totes col·locades en una superfície verda. Aquesta imatge mostra el disseny original del joc d'escacs que va inspirar el joc d'escacs de gossos amb capacitats diferents." src="./images/reference-set.png" width="400" />
</p>

### Ideació i Disseny del Model 3D

La idea era crear un conjunt que no només representés diferents races de gossos, sinó que també destacés diverses discapacitats d'una manera positiva i inclusiva. Volia destacar una àmplia gamma de discapacitats per fer el conjunt tan inclusiu i representatiu com fos possible. Aquestes discapacitats van ser triades per reflectir tant condicions visibles com invisibles, temporals i permanents, amb l'objectiu de crear consciència a través dels escacs.

| Peça d'Escacs | Discapacitat | Ajuda Adaptativa |
| - | - | - |
| Rei | Amputació de la pota davantera | Pròtesi |
| Reina | Discapacitat temporal (Post-cirurgia) | Coll |
| Alfil | Paràlisi | Cadira de rodes |
| Cavaller | Ceguera | Halo |
| Torre | Artritis | Rampa, matalàs ortopèdic |
| Peons 1 i 2 | Trastorn de deglució | Biberó |
| Peons 3 i 4 | Discapacitat invisible | N/A |
| Peons 5 i 6 | Trastorn d'ansietat | Medicació |
| Peons 7 i 8 | Malaltia degenerativa del disc | Llit ortopèdic |

El següent pas era esbrinar com representar aquestes discapacitats en els models. Vaig incorporar alguns dissenys addicionals de Thingiverse en el projecte i vaig crear la resta.

Per exemple, la cadira de rodes de l'alfil es basava en [aquest model](https://www.thingiverse.com/thing:1397964):

![Petit Chihuahua en una cadira de rodes impresa en 3D de color verd neó i negre, lladrant o udolant, contra un fons groc brillant.](./images/figowebp.webp)

El render final es veia així:

![Fila de peces d'escacs negres renderitzades en 3D semblants a gossos amb capacitats diferents en bases rodones, col·locades sobre un fons verd brillant. D'esquerra a dreta: un gos amb una pròtesi i una corona, un gos amb un coll i una corona, un gos en una cadira de rodes, un gos amb un halo, un gos en una caseta amb una rampa accessible, i cinc gossos petits en diverses posicions, un amb un biberó, un amb pastilles, un assegut en un llit ortopèdic. Aquestes peces representen el joc d'escacs de gossos amb capacitats diferents personalitzat.](./images/render/all.png)

### Procés d'Impressió 3D

Per aconseguir els millors resultats, vaig utilitzar una altura de capa petita de 0,12 mm per capturar petits detalls. Les peces estan impreses sòlides, fent-les més pesades i duradores.

Va caldre un parell d'iteracions per esbrinar com imprimir-les millor; algunes, com el rei i l'alfil, es van imprimir millor sense suports. Altres, com la reina (per al coll) i el cavaller (per al halo), els necessitaven.

Com que moltes tenien detalls delicats (com el halo del cavaller), vaig decidir recobrir-les amb resina UV transparent per augmentar la seva resistència.

### Ús de la Resina UV

L'ús de resina UV enforteix les peces, però requereix precaucions de seguretat com portar equip de protecció. El procés és senzill però requereix una mica de preparació. Seguiu les instruccions de la resina per al temps de curat per evitar un sobrecurat. Assegureu-vos de no mirar directament la llum UV i eviteu el contacte de la resina amb la pell.

| Material | Imatge |
| - | - |
| [Resina UV](https://a.co/d/ezitsoy) | <img src="./images/materials/resin.jpg" width="200" /> |
| [Llum UV](https://a.co/d/ezitsoy) | <img src="./images/materials/uvlight.webp" width="200" /> |
| [Goggles de Protecció](https://a.co/d/0IKj0s0) | <img src="./images/materials/uvgoggles.jpg" width="200" /> |
| [Guants de Protecció](https://a.co/d/9HWPJkN) | <img src="./images/materials/gloves.webp" width="200" /> |
| [Bata de Protecció](https://a.co/d/4McWedg) | <img src="./images/materials/coat.webp" height="200" /> |

Després de l'aplicació de la resina, i per assegurar-me que les peces llisquessin bé pel tauler d'escacs, vaig utilitzar [feltre verd](https://a.co/d/2bVIOpZ).

### Peces Finals d'Escacs

Aquí teniu el resultat final:

| Peça d'Escacs | Discapacitat | Render 3D | Imprès |
| - | - | - | - |
| Rei | Amputació | ![](./images/render/king.png) | ![](./images/print/king.png) |
| Reina | Temporal / Post-cirurgia | ![](./images/render/queen.png) | ![](./images/print/queen.png) |
| Alfil | Paràlisi | ![](./images/render/bishop.png) | ![](./images/print/bishop.png) |
| Cavaller | Ceguera | ![](./images/render/knight.png) | ![](./images/print/knight.png) |
| Torre | Artritis | ![](./images/render/rook.png) | ![](./images/print/rook.png) |
| Peons 1 i 2 | Trastorn de deglució | ![](./images/render/pawn1.png) | ![](./images/print/pawn1.png) |
| Peons 3 i 4 | Discapacitat invisible | ![](./images/render/pawn2.png) | ![](./images/print/pawn2.png) |
| Peons 5 i 6 | Trastorn d'ansietat | ![](./images/render/pawn3.png) | ![](./images/print/pawn3.png) |
| Peons 7 i 8 | Malaltia degenerativa del disc | ![](./images/render/pawn4.png) | ![](./images/print/pawn4.png) |

## Targetes

L'objectiu de les targetes era fer les discapacitats mostrades en les peces d'escacs més clares mentre les destacava d'una manera positiva o neutral, no com una limitació sinó simplement com a part de la vida del gos.

Després d'explorar diferents estils, vaig triar un aspecte adornat i antic.

| Antic | Eco-Friendly | Modern |
| - | - | - |
| ![Prototip d'estil floral, antic i ornamentat de la targeta del Kingly el Gran Danès](./images/card/style-antique.jpg) | ![Prototip d'estil modern i eco-friendly de la targeta del Kingly el Gran Danès](./images/card/style-eco.jpg) | ![Prototip d'estil minimalista de la targeta del Kingly el Gran Danès](./images/card/style-minimal.jpg) |

Com que el lema de WP Creative Pets és "Cada Moment és un Moment d'Entrenament," volia incorporar-lo com a part del conjunt de targetes. Amb una mica d'ajuda de ChatGPT, vaig arribar a la traducció aproximada al llatí de "Omne Momentum Disciplina Est."

<p align="center">
    <img src="./images/card/moto.png" width="200" alt="Il·lustració d'estil vintage adornada amb un marc floral decoratiu amb un centre circular buit i pancartes que diuen 'Omne Momentum' a la part superior i 'Disciplina Est' a la part inferior, en tons marrons i beixos" />
</p>

### Fonts i Disseny

Pel que fa a les fonts, vaig triar Trajan Pro tant per al lema com per al títol, ja que semblava combinar bé amb l'estil de la targeta. OpenDyslexicAlta per al cos va ser triada per la seva llegibilitat i accessibilitat, especialment perquè tot l'exercici és no estar limitat per discapacitats.

| Trajan Pro | Open Dyslexic Alta |
| - | - |
| ![Mostra de Trajan Pro](./images/font/trajan-pro.png) | ![Mostra de Open Dyslexic Alta](./images/font/OpenDyslexicAlta.png) |

### Detalls de les Targetes

| Peça d'Escacs | Targeta |
| - | - |
| Rei | <img src="./images/card/king.png" alt="Il·lustració d'estil vintage adornada amb un Gran Danès amb tres potes en un marc floral decoratiu. El text diu: 'Kingly el Gran Danès. Kingly, el nostre sobirà de tres potes, observa el seu regne amb una mirada noble. Tot i perdre una extremitat en un rescat valent, la seva figura segueix sent majestuosa, el seu comportament inamovible.' A la part superior, una pancarta diu 'Omne Momentum Disciplina Est.'" width="200" /> |
| Reina | <img src="./images/card/queen.png" alt="Il·lustració d'estil vintage adornada amb un Llebrer Afgà en un marc floral decoratiu. El text diu: 'Queenie el Llebrer Afgà. L'elegància de Queenie transcendeix el tauler d'escacs, el seu coll un emblema temporal de la seva recent cirurgia. Amb la gràcia d'una estratega, els seus moviments són un testimoni silenciós del seu esperit resilient.' A la part superior, una pancarta diu 'Omne Momentum Disciplina Est.'" width="200" /> |
| Alfil | <img src="./images/card/bishop.png" alt="Il·lustració d'estil vintage adornada amb un Akita en una cadira de rodes dins d'un marc floral decoratiu. El text diu: 'Bishop l'Akita. Bishop l'Akita roda pel tauler d'escacs, un far d'esperança per a tots els que s'enfronten a desafiaments. La seva cadira de rodes no el confina; és el seu carro, transportant-lo d'una victòria a una altra.' A la part superior, una pancarta diu 'Omne Momentum Disciplina Est.'" width="200" /> |
| Cavaller | <img src="./images/card/knight.png" width="200" alt="Il·lustració d'estil vintage adornada amb un Bòxer amb ulls cecs en un marc floral decoratiu. El text diu: 'Knightly el Bòxer. Knightly, el sentinella cec del tauler d'escacs, posseeix un coratge que ressona més enllà del regne visual. El seu halo no és només una guia sinó un símbol de la seva consciència augmentada.' A la part superior, una pancarta diu 'Omne Momentum Disciplina Est.'" /> |
| Torre | <img src="./images/card/rook.png" width="200" alt="Il·lustració d'estil vintage adornada amb un Gos Comú en un marc floral decoratiu. El text diu: 'Rocky el Gos Comú. Rocky, amb artritis i un defensor ferm del regne, guarda les muralles amb un esperit inamovible. La rampa al costat de la seva caseta no és un signe de debilitat sinó un testimoni de la seva adaptabilitat.' A la part superior, una pancarta diu 'Omne Momentum Disciplina Est.'" /> |
| Peons 1 i 2 | <img src="./images/card/pawn1.png" width="200" alt="Il·lustració d'estil vintage adornada amb un Chihuahua en un marc floral decoratiu. El text diu: 'Pebbles el Chihuahua. Pebbles és un far de perseverança, navegant la vida amb megaesòfag. La seva alimentació es fa en glops suaus i curosos des d'un biberó dissenyat especialment, convertint cada àpat en un triomf sobre l'adversitat.' A la part superior, una pancarta diu 'Omne Momentum Disciplina Est.'" /> |
| Peons 3 i 4 | <img src="./images/card/pawn2.png" width="200" alt="Il·lustració d'estil vintage adornada amb un Chihuahua en un marc floral decoratiu. El text diu: 'Poppy el Chihuahua. Poppy, amb Trastorn de Processament Sensorial, però sense cap signe extern dels seus desafiaments, es mou amb una gràcia etèria pel tauler d'escacs, els seus sentits ajustats a una freqüència diferent de la dels seus companys canins.' A la part superior, una pancarta diu 'Omne Momentum Disciplina Est.'" /> |
| Peons 5 i 6 | <img src="./images/card/pawn3.png" width="200" alt="Il·lustració d'estil vintage adornada amb un Chihuahua en un marc floral decoratiu. El text diu: 'Patch el Chihuahua. Patch es mou pel tauler d'escacs amb ansietat però també amb una resolució inamovible. Els seus passos curosos es combinen amb respiracions profundes, ja que ha dominat l'art del focus tranquil.' A la part superior, una pancarta diu 'Omne Momentum Disciplina Est.'" /> |
| Peons 7 i 8 | <img src="./images/card/pawn4.png" width="200" alt="Il·lustració d'estil vintage adornada amb un Chihuahua en un marc floral decoratiu. El text diu: 'Pillow el Chihuahua. Pillow troba consol en el suport del seu tron ortopèdic, un bastió enmig de les proves de la malaltia degenerativa del disc. Cada pas al llarg de les caselles del tauler és una prova de la seva resistència.' A la part superior, una pancarta diu 'Omne Momentum Disciplina Est.'" /> |

El dors era el mateix per a totes les targetes:

| Disseny | Imprès |
| - | - |
| <img src="./images/card/back.png" height="320" alt="Una targeta d'estil vintage ornamentada amb dissenys florals i de pergamins que emmarquen el text: 'WP Creative Pets The Differently-Abled Dog Chess Set' en una tipografia decorativa amb serif." /> | <img src="./images/card/print-back-and-front.jpeg" height="320" alt="Quatre targetes es mostren sobre una superfície de fusta. Una targeta és totalment visible, mostrant un disseny detallat ornamentat amb una il·lustració d'un gos Akita, etiquetada 'Bishop l'Akita.' El text descriu Bishop com un gos en una cadira de rodes que és un far d'esperança i un símbol de superació de desafiaments. Les altres tres targetes estan girades amb la part posterior visible, mostrant dissenys ornamentats i el text 'WP Creative Pets - The Differently-Abled Dog Chess Set.'" /> |

Un cop dissenyades, les targetes es van fer a [MakePlayingCards.com](https://www.makeplayingcards.com/design/custom-us-game-deck-size-cards.html). El fitxer de Photoshop que inclou totes les variacions de targetes i la plantilla de MakePlayingCards.com està disponible [aquí](./assets/tarot-size.psd). Es van imprimir en plàstic d'alta qualitat i es van tallar i enviar les targetes.

Una iteració més antiga de les targetes també està disponible [aquí](./assets/us_game_deck.psd), però vaig decidir no utilitzar-la degut a la seva mida més petita, que afectava la llegibilitat, i

 en última instància, no estava satisfet amb el meu primer disseny. Si teniu curiositat, així es veien:

| Imprès | Davant | Dors |
| - | - | - |
| <img src="./images/card/wrapped.jpeg" width="200" alt="Targeta impresa amb el text 'Kingly el Gran Danès' amb una il·lustració d'un Gran Danès de tres potes, envoltat d'elements decoratius i text que descriu la seva història. La targeta està embolicada en plàstic, col·locada sobre una superfície de fusta. La pancarta inferior diu 'Omne Momentum Disciplina Est.'" /> | <img src="./images/card/pawn4-old.png" width="200" alt="Il·lustració d'estil vintage adornada amb un Chihuahua en un marc circular coronat amb una corona i flanquejat per escuts amb quadres. El text diu: 'Pillow el Chihuahua. Pillow troba consol en el suport del seu tron ortopèdic, un bastió enmig de les proves de la malaltia degenerativa del disc. Cada moviment calculat al llarg de les caselles és una prova de la seva resistència.' A la part inferior, una pancarta diu 'Omne Momentum Disciplina Est.' El disseny inclou icones de peces d'escacs i elements decoratius en tons beix i negre." /> | <img src="./images/card/back2.png" width="200" alt="Il·lustració d'estil vintage adornada amb un gos de pèl llarg portant una corona, emmarcat per dissenys florals i de pergamins intricats. Tres pancartes envolten el gos, amb el text: 'The Differently-Abled' a la part superior, 'Dog Chess Set' al mig, i 'WP Creative Pets' a la part inferior. El disseny és en tons negres, marrons i beix, donant-li un aspecte antic." /> |

## Tauler

El tauler d'escacs està dissenyat per representar un parc de gossos, amb la meitat de les rajoles representant "sorra" i l'altra meitat "herba," envoltades per una carretera.

### Disseny i Construcció del Tauler

El tauler d'escacs representa un parc de gossos amb rajoles d'herba i sorra, envoltades per una carretera. Les rajoles es van imprimir amb textures detallades per imitar superfícies reals. El tauler d'escacs està compost per quatre quadrants, cadascun repetit dues vegades:

![Diagrama d'un tauler d'escacs dividit en quatre quadrants, cadascun amb un patró distintiu. El tauler mostra que les diagonals des de la cantonada inferior esquerra fins a la superior dreta i des de la cantonada inferior dreta fins a la superior esquerra tenen patrons consistents. Els quadrants estan marcats amb diferents colors i estils de ratllat, amb una clara delimitació per demostrar la divisió i la consistència del patró al llarg de les diagonals.](./images/chess-diagonals.png)

La representació de l'herba va requerir diverses iteracions, finalment arribant a aquest patró que es va imprimir com una petita sèrie de fils prims semblants a cabells. Els forats es van omplir amb les rajoles de sorra, que es van imprimir verticalment per obtenir millor resolució.

![Impressora 3D creant les rajoles verdes que representen 'herba' per a un tauler d'escacs amb temàtica de parc de gossos. La boquilla es mou d'anada i tornada, dipositant filament verd capa a capa. La rajola pren forma gradualment amb una textura detallada, contrastant amb l'entorn.](./images/board/grass-printing.gif)

![Primer pla d'un quadrant d'herba verda per al tauler d'escacs amb temàtica de parc de gossos, amb una superfície texturitzada. Una rajola de sorra blanca es col·loca en un dels espais, contrastant amb les rajoles d'herba verda que l'envolten. La rajola de sorra té una textura suau i ondulada, destacant la diferència entre els dos tipus de rajoles.](./images/board/first-sand-tile.jpeg)

Un cop els quatre quadrants d'herba es van imprimir i omplir amb les rajoles de sorra, els vaig enganxar al seu lloc a sobre d'una làmina de metall per donar-los una sensació de pes. Vaig utilitzar aliatge d'alumini 6061 de <https://www.onlinemetals.com>, que ofereix talls personalitzats, permetent-me demanar una làmina pre-tallada.

![Tauler d'escacs amb temàtica de parc de gossos pre-assemblat amb rajoles d'herba verda i sorra blanca alternades. Les rajoles verdes texturitzades contrasten amb les rajoles de sorra blanca llisa i ondulada, creant un patró de quadres. Algunes rajoles estan apilades al fons, i el tauler està parcialment assemblat sobre una superfície de treball, mostrant el progrés del projecte.](./images/board/pre-assembled.jpeg)

Per a la vora, vaig utilitzar [aquestes rajoles](https://www.thingiverse.com/thing:2480607) de Thingiverse que ja semblaven paviment i vaig afegir diferents escenes amb gossos relaxant-se, jugant i intentant agafar ossos i fruita.

![Renderització 3D d'una rajola rectangular amb textura de llambordes. La rajola és blava i està col·locada plana sobre una graella grisa, mostrant la seva superfície detallada i irregular, semblant a una secció d'un camí de llambordes.](./images/board/pavement.webp)

| Pou d'Os | Lladre de Pastanagues | Chihuahua Relaxat | Reunió de Gossos |
| - | - | - | - |
| ![Cantonada d'un tauler d'escacs amb temàtica de parc de gossos amb camins de llambordes grisos amb textures detallades. Una petita figura de gos està col·locada a prop d'un pou circular, afegint una escena a la cantonada. El patró de quadres està format per rajoles d'herba verda i sorra blanca alternades. Els camins grisos proporcionen un fons realista, contrastant amb els colors vius de les rajoles.](./images/board/side-bones.jpeg) | ![Primer pla d'una secció de cantonada del tauler d'escacs amb temàtica de parc de gossos, mostrant camins de llambordes grisos amb figures de gossos i diversos objectes. Dues figures de gossos, una dempeus amb una pastanaga a la boca i una asseguda, estan col·locades a prop de caixes plenes de menjar. Les caixes i els gossos afegeixen una escena realista a la cantonada. Al fons, el patró de quadres d'herba verda i sorra blanca alternades és visible, proporcionant un contrast vibrant amb el camí gris i les figures.](./images/board/side-boxes.jpeg) | ![Secció de cantonada del tauler d'escacs amb temàtica de parc de gossos, mostrant un camí de llambordes grisos detallat amb una petita figura de Chihuahua al centre. Al fons, les rajoles d'herba verda i sorra blanca del tauler creen un patró de quadres vibrant. El camí gris i la figura del petit gos afegeixen una escena realista a la vora del tauler, contrastant amb les rajoles de colors.](./images/board/side-chihuahua.jpeg) | ![Secció de cantonada del tauler d'escacs amb temàtica de parc de gossos, mostrant un camí de llambordes grisos detallat amb petites figures de gossos i una boca d'incendis. Un gos està dempeus a prop de la boca d'incendis, mentre que un altre està assegut al costat d'una pilota. Al fons, el patró de quadres d'herba verda i sorra blanca alternades és visible, creant un contrast vibrant amb el camí gris i les figures. L'escena afegeix un toc juganer i realista a la vora del tauler.](./images/board/side-hydrant.jpeg) |

Vaig intentar cobrir les esquerdes entre els quadrants utilitzant un bolígraf 3D i llimant l'excés, però encara eren força visibles.

Finalment, vaig cobrir la superfície amb resina UV novament. M'agradaria haver tingut en compte les esquerdes perquè van causar algunes bombolles grans. La resina escalfada també va dissoldre els fils d'herba, cosa que va ser desafortunada. Podeu veure com es veia amb i sense resina a continuació:

| Amb Resina | Sense Resina |
| - | - |
| ![Tauler d'escacs completament assemblat amb totes les peces d'escacs al seu lloc, col·locat sobre una taula de fusta. Les peces estan disposades per a un joc, amb peces blanques d'un costat i peces grises de l'altre. El tauler i les peces tenen un aspecte brillant i humit degut a l'aplicació de resina UV, que millora la seva textura i detall. La resina afegeix un acabat brillant, fent els colors i els detalls més vius.](./images/board/full.jpeg) | ![Tauler d'escacs amb temàtica de parc de gossos parcialment assemblat sobre una taula de fusta. El tauler té rajoles d'herba verda i sorra blanca alternades, envoltades per camins de llambordes grisos detallats amb figures de gossos i altres elements. Eines i subministraments, incloent-hi cinta adhesiva i pintura en aerosol, estan escampats al voltant de la taula. Dues peces d'escacs, un cavaller i una torre, estan col·locades al tauler, però no s'ha aplicat resina UV.](./images/board/assembled.jpeg) |

## Caixa del Tauler

No podia utilitzar la impressora 3D per a la caixa ja que era molt més gran que el tauler d'escacs. Fer-la d'una sola peça sòlida assegura que pot aguantar el tauler d'escacs de manera fiable.

Com que el tauler d'escacs és de 13,75"x13,75", vaig reutilitzar una caixa de pizza de 14". La vaig pintar de porpra i vaig estarcir una peça d'escacs amb cap de gos com a logotip. Per a protecció, vaig afegir una capa de [poliacrílic](https://a.co/d/cTNn0YK) transparent. Podeu veure el procés a continuació:

| Pas | Imatge |
| - | - |
| Disseny Inicial | <img alt="Disseny SVG en blanc i negre de l'estergit utilitzat per al projecte. El disseny és una peça d'escacs de cavall estilitzada amb un cap de gos, preparada per ser tallada i utilitzada com a plantilla per pintar." src="./images/box/stencil.svg" width="200" /> |
| Crear estergit | <img alt="Un mat de tall verd sobre una taula desordenada. Al mat hi ha una impressió en blanc i negre d'un disseny d'estergit semblant a una peça d'escacs de cavall amb un cap de gos. Diverses eines com un ganivet d'utilitat, una regla i un bolígraf estan escampades al voltant. La taula també té altres objectes, incloent-hi cinta adhesiva, arrels de gingebre, un gerro de vidre amb flors i un petit recipient porpra." src="./images/box/stencil-design.jpeg" width="200" /> |
| Pintura amb Spray | <img alt="Disseny d'estergit sent pintat amb spray sobre una superfície, subjectat amb cinta adhesiva blava. El disseny, una peça d'escacs de cavall amb un cap de gos, s'està pintant de negre. El fons inclou cartró i una mica de verd, indicant que la pintura està tenint lloc a l'exterior sobre un banc de treball o una configuració similar." src="./images/box/stencil-spray.jpeg" width="200" /> |
| Pintat | <img alt="Una caixa de pizza reutilitzada pintada de porpra amb un disseny d'estergit negre sobre ella. El disseny representa una peça d'escacs de cavall amb un cap de gos, mostrant un aspecte atrevit i net. El fons inclou algunes flors en un gerro, suggerint que la caixa està en una cuina o sala d'estar." src="./images/box/stencil-repainted.jpeg" width="200" /> |

Per a l'interior, volia afegir un cartell en Braille ja que tenim un gos cec en el joc d'escacs. El text inclou un enllaç a aquesta publicació. Vaig utilitzar <https://touchsee.me> per generar els fitxers STL per a Braille contractat (Grau 2) perquè el text digui:

| Text Pla | Contractat | Braille | Render | Assemblat |
| - | - | - | - | - |
| <img src="./images/braille/plain.png" width="200" alt="El text 'El Joc d'Escacs de Gossos amb Capacitats Diferents. Fet amb amor per Oscar Bartra per a Casey Buckley, WP Creative Pets, i tots els seus mascotes. Aprèn més a: bit.ly/dogchess'" /> | <img src="./images/braille/contracted.png" width="200" alt="Braille contractat amb la corresponent traducció: ',! ,di6}5tly-,a#d ,dog ,*ess , set4 ,made ) love 0,osc> ,b>tra = ,casey ,buckley1 ,,wp ,cr1tive ,pets1 & all h} pets4 ,le>n m at3 bit4ly_/dog*ess'" /> | <img src="./images/braille/braille.png" width="200" alt="Representació en braille del següent missatge: 'El Joc d'Escacs de Gossos amb Capacitats Diferents. Fet amb amor per Oscar Bartra per a Casey Buckley, WP Creative Pets, i tots els seus mascotes. Aprèn més a: bit.ly/dogchess'" /> | <img src="./images/braille/render.png" width="200" alt="Renderització 3D del text en braille amb una fletxa d'inici i un marc al voltant." /> | <img src="./images/braille/assembled.jpeg" width="200" alt="Una caixa pintada de porpra que conté un joc d'escacs imprès en 3D. El tauler d'escacs és visible a la part superior, amb rajoles verdes i beix amb una vora gris. Dins de la tapa superior de la caixa, hi ha un text en braille de color porpra i negre." /> |

Van ser necessaris diversos intents per aconseguir un text en braille clar. També hi ha un codi QR que enllaça a aquesta pàgina. El vaig generar utilitzant <https://printer.tools/qrcode2stl>. Malauradament, no vaig poder imprimir-lo de manera que quedés prou bé per incloure'l al tauler. Finalment, vaig fer una targeta addicional amb el codi QR en lloc.

| Render | Resultat | Targeta |
| - | - | - |
| ![Renderització 3D d'un codi QR amb una icona d'informació al centre i un marc quadrat al voltant de tot el codi. El codi QR sembla elevat d'una superfície plana, i el text 'bit.ly/dogchess' està gravat en relleu al llarg de la vora inferior. El disseny general està situat contra un fons de graella fosca.](./images/qr/render.png) | ![Fotografia d'una impressió 3D fallida d'un codi QR sobre una superfície de fusta. La impressió té problemes de stringing significatius, amb fils fins de filament que connecten diverses parts del codi QR. El codi està imprès en negre sobre un fons porpra, amb el text 'bit.ly/dogchess' a la part inferior. La icona d'informació és visible al centre del codi, i la impressió està emmarcada per un marc quadrat. La superfície de la impressió és irregular i desordenada degut al problema de stringing.](./images/qr/attempt.png) | ![Una targeta amb un marc floral ornamentat al voltant d'un codi QR. La targeta conté el següent text: 'obarta.github.io/3d/projects/chess Fet amb ❤️ per Oscar Bartra per a Casey Buckley, WP Creative Pets, i totes les seves mascotes'](./images/card/print-qr.png) |

Tant per al braille com per al codi QR, vaig haver d'afegir una pausa per canviar el filament ja que la meva impressora no suporta impressions multi-material. Per fer-ho, afegiu `M600` al codi G generat on ha de produir-se la pausa. Si teniu curiositat sobre què passa quan afegiu la pausa a la capa incorrecta, podeu veure-ho aquí:

![Fotografia d'una impressió 3D fallida d'un text en braille sobre una superfície de fusta. La impressió té una capa superior negra amb punts de braille visibles, però el canvi de color del filament s'ha aplicat incorrectament, resultant en el filament negre utilitzat a la última capa de la part base en lloc de la capa prevista. La taula està emmarcada per un marc porpra, i la superfície sembla irregular i desordenada degut al problema de canvi de capa del color del filament. El text en braille és difícil de llegir per culpa de l'error de capa.](./images/braille/attempt-layer.png)

Finalment, vaig utilitzar el mateix feltre que per a les peces d'escacs per cobrir la part inferior de l'interior de la caixa.

## Suport de les Peces

Per mantenir les peces organitzades i protegides, vaig dissenyar una caixa personalitzada. És una mica voluminosa, però volia que el suport interior també servís com a base per a les peces perquè es poguessin mostrar més fàcilment. La caixa és un cub quadrat amb un insert interior destinat a ajudar a minimitzar el moviment de les peces. La part frontal de la caixa té una tapa que es llisca i té la mateixa imatge de la peça d'escacs amb cap de gos que vam estergir per la caixa del tauler.

| Disseny | Obert | Parcialment Obert | Tancat |
| - | - | - | - |
| ![Un render 3D del disseny del suport de peces d'escacs dins d'una caixa rectangular. El render mostra una peça d'escacs de cavall estilitzada amb un cap de gos, i diversos compartiments per mantenir les peces d'escacs.](./images/piece-box/box-set-design.png) | ![Una caixa porpra amb la tapa oberta, mostrant un suport de peces d'escacs translúcid a l'interior. El suport té múltiples nivells, mantenint peces d'escacs temàtiques de gossos beix. Les peces estan ordenades ordenadament als seus respectius compartiments.](./images/piece-box/open.jpeg) | ![Una caixa porpra amb la tapa parcialment oberta, revelant el suport de peces d'escacs translúcid a l'interior. El suport conté múltiples peces d'escacs beix, ordenades ordenadament als seus respectius compartiments.](./images/piece-box/partially-open.jpeg) | ![Una caixa porpra tancada amb una peça d'escacs de cavall estilitzada amb un cap de gos negre a un costat. La caixa està col·locada sobre una superfície de fusta clara.](./images/piece-box/closed.jpeg) |

### Resum

I això és tot! Gràcies per prendre't el temps de llegir sobre el Joc d'Escacs amb Capacitats Diferents.

| Targetes | Peces d'Escacs | Tauler | Caixa del Tauler | Caixa de Peces |
| - | - | - | - | - |
| ![Cinc targetes que descriuen les peces d'escacs, cadascuna amb un disseny ornamentat i una imatge d'un gos diferent. Les targetes estan etiquetades "Rocky el Gos Comú," "Knightly el Bòxer," "Bishop l'Akita," "Queenie el Llebrer Afgà," i "Kingly el Gran Danès," cadascuna descrivint la història del gos respectiu i el seu paper en el joc d'escacs.](./images/card/print-front.jpeg) | ![Un suport de peces d'escacs negre amb múltiples nivells, mantenint peces d'escacs temàtiques de gossos beix i negres. Les peces estan ordenades ordenadament als seus respectius compartiments.](./images/render/pieces.jpg) | ![Tauler d'escacs imprès en 3D amb quadrats verds i beix, preparat per a un joc amb peces d'escacs blanques i negres. El tauler està vorejat amb gris, i les peces mostren diversos dissenys de gossos.](./images/board/full.jpeg) | ![Una caixa porpra per al tauler d'escacs amb una peça d'escacs de cavall estilitzada amb un cap de gos negre a un costat. La caixa està col·locada sobre una superfície de cuina.](./images/box/stencil-repainted.jpeg) | ![Una caixa cúbica porpra tancada amb una peça d'escacs de cavall estilitzada amb un cap de gos negre a un costat. La caixa està col·locada sobre una superfície de fusta clara.](./images/piece-box/closed.jpeg) |

Si vols deixar un comentari o suggeriment, ho pots fer [aquí](https://github.com/obartra/3d/issues/new).

![Un banc de treball que mostra un joc d'escacs personalitzat completat. A l'esquerra hi ha una caixa de pizza pintada de porpra amb una peça d'escacs de cavall estilitzada amb un cap de gos negre a la tapa, que conté el tauler d'escacs a l'interior. A la dreta hi ha una caixa cúbica porpra amb una peça d'escacs similar a un cavall estilitzat amb un cap de gos a un costat, que conté les peces d'escacs i el suport. Diverses eines i subministraments són visibles al fons.](./images/complete.jpeg)
