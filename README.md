# Fernandez_Didac_examen-animaciones


Exercici 1: Cards amb Transicions (25 punts)
Crea una secció amb 3 cards (targetes) que tinguin les següents característiques:

Requisits:
Estructura bàsica (5 punts):

Cada card ha de tenir un títol, una imatge (o div amb color de fons), i una descripció
Les cards han d’estar disposades en fila amb flexbox o grid
Espaiat adequat entre les cards
Transició de color (5 punts):

Al passar el ratolí (:hover), el fons de la card ha de canviar de color
La transició ha de durar 300ms amb easing ease-in-out
Transformació al hover (10 punts):

Al passar el ratolí, la card ha de:
Escalar-se un 10%
Moure’s cap amunt 10px
La transició ha de durar 400ms amb easing ease-out
Efecte d’ombra (5 punts):

Al passar el ratolí, afegeix una ombra (box-shadow) que doni profunditat
La transició de l’ombra ha de durar 300ms
Exemple de resultat esperat: Les cards han de “elevar-se” visualment quan passes el ratolí per sobre.


Exercici 2: Botons amb Animacions (20 punts)
Crea 4 botons amb diferents tipus d’animacions:

Requisits:
Botó 1 - Transició de fons (5 punts):

Fons inicial: #3498db (blau)
Al hover: #2980b9 (blau fosc)
Transició de 200ms amb ease-in
Botó 2 - Rotació (5 punts):

Al fer clic (:active), el botó ha de rotar 360 graus
Transició de 600ms amb ease-in-out
Botó 3 - Escala (5 punts):

Al hover, escala fins a 1.2
Al fer clic, escala fins a 0.95
Transicions de 200ms
Botó 4 - Combinació (5 punts):

Al hover: escala a 1.1, rotació de 5 graus, i canvi de color de fons
Utilitza múltiples transformacions simultànies
Transició de 300ms


Exercici 3: Animació amb @keyframes (25 punts)
Crea una animació personalitzada utilitzant @keyframes:

Requisits:
Element animat (10 punts):

Crea un div circular (100x100px) amb un color de fons distintiu
Centra’l a la pàgina
Animació de pulsació (15 punts):

L’element ha de fer una animació de “pulsació”
L’element ha de créixer i reduir-se contínuament (scale de 1 a 1.2 i tornar a 1)
Durada: 1.5 segons
Repetició: infinita
Timing function: ease-in-out
Utilitza @keyframes per definir l’animació



Exercici 4: Menú amb Transicions (15 punts)
Crea un menú de navegació horitzontal amb efectes de transició:

Requisits:
Estructura del menú (5 punts):

Almenys 4 elements de menú (Home, Sobre, Serveis, Contacte)
Estil bàsic amb separació adequada
Utilitza una llista (<ul> i <li>) per a la semàntica correcta
Efecte hover (10 punts):

Al passar el ratolí per un element del menú:
El color del text ha de canviar
S’ha d’afegir una línia sota el text que aparegui amb una transició suau
Transició de 250ms amb ease-out



Exercici 5: Loading Spinner (15 punts)
Crea un indicador de càrrega (loading spinner) utilitzant animacions CSS:

Requisits:
Estructura (5 punts):

Crea un cercle amb border (no utilitzar background-color per al cercle)
El cercle ha de tenir una part transparent i una part de color
Animació de rotació (10 punts):

El cercle ha de rotar contínuament
Utilitza @keyframes
Durada: 1 segon
Repetició: infinita
Timing function: linear (velocitat constant)
Exemple visual: Un cercle que gira contínuament, similar als spinners de càrrega que es veuen en les pàgines web.