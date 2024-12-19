<!--
title: "Sleutel-Slot-principe"
language: nl
narrator: Dutch Female
mode: Presentation

import: https://raw.githubusercontent.com/LiaScript/CodeRunner/master/README.md
        https://raw.githubusercontent.com/LiaTemplates/BeforeAndAfter/0.0.1/README.md

link:   https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css
        https://fonts.googleapis.com/css?family=Lato:400,400italic,700
        style.css

@runR: @LIA.eval(`["main.R"]`, `none`, `Rscript main.R`)

@JSONLD
<script run-once>
  let json = @0 

  const script = document.createElement('script');
  script.type = 'application/ld+json';
  script.text = JSON.stringify(json);

  document.head.appendChild(script);

  // this is only needed to prevent and output,
  // as long as the result of a script is undefined,
  // it is not shown or rendered within LiaScript
  console.debug("added json to head")
</script>
@end


link:   https://unpkg.com/leaflet@1.9.4/dist/leaflet.css
script: https://unpkg.com/leaflet@1.9.4/dist/leaflet.js

-->

# Welkom

> We gebruiken de interactieve Open Educational Resource online/offline infrastructuur LiaScript.
> [Laten we beginnen!](https://liascript.github.io/course/?https://raw.githubusercontent.com/abotzki/presentation/refs/heads/master/sleutel-slot-principe.md)

De presentatie wordt volledig op je computer geladen. Vervolgens kan je met de pijltoetsen van je toetsenbord door de presentatie gaan. Klik uiteraard ook op het Luidspreker icoontje onderaan de pagina om de uitleg bij elke slide te kunnen beluisteren.

# Welke doelen heeft deze korte presentatie?

* je kunt het sleutel-slot principe in een biologische context herkennen

* je kunt beschrijven wat het sleutel-slot-principe in de biochemie betekent

# Het sleutel-slot-principe

![sleutel-slot](./img/rb_111368.png "[^🦶]")

[^🦶]: https://www.freepik.com/free-vector/lock-key-sticker_16263312.htm 

    --{{0}}--
Hallo iedereen, vandaag wil ik jullie het sleutel-slot principe uitleggen aan de hand van een voorbeeld uit de geneeskunde. Stel je voor dat je een sleutel hebt die perfect past in een slot. Alleen met deze specifieke sleutel kun je het slot openen. Dit idee, dat een sleutel precies past in een slot, is een belangrijk concept in de biologie en wordt het sleutel-slot principe genoemd. Het sleutel-slot principe helpt ons te begrijpen hoe moleculen in ons lichaam samenwerken. Een goed voorbeeld hiervan is hoe een klein molecuul zich bindt aan een receptor. Receptoren zijn eiwitten op het oppervlak van cellen die specifieke moleculen, de substraten, herkennen en binden. Net zoals een sleutel alleen in een bepaald slot past, past een substraat alleen bij een specifieke receptor. Vandaag gaan we dieper ingaan op hoe dit principe werkt, waarom het zo belangrijk is voor ons lichaam, en we zullen een voorbeeld uit de geneeskunde bekijken om het beter te begrijpen.

# Hoe krijgen we de liefdesslotjes open?

   --{{0}}--
Maar laat ons eerst naar een andere situatie uit het dagelijkse leven kijken: Je vindt ze vaak op bruggen in populaire touristische bestemmingen: de liefdesslotjes. Stel we zouden enkele sloten willen open krijgen. Wat hebben we nodig en hoe gaan we te werk?

![liefdesslotjes](./img/00-sleutels-sloten.svg "[^🦶]")

[^🦶]: https://nl.freepik.com/vrije-photo/beveiligingsconcept-met-slot_22632767.htm#fromView=search&page=1&position=49&uuid=abfcf2c4-41ae-4315-beea-83b36deca858; https://nl.freepik.com/vrije-photo/hou-van-hangsloten-op-metalen-reling_9898302.htm#fromView=search&page=1&position=47&uuid=03fe7b58-ae23-4945-81f7-4d3d14f83ffc

# De basisprincipes

<!-- style="font-size: 2em" -->
> We hebben een sleutel die specifiek in een slot past.

<!-- style="font-size: 2em" -->
> Door de passende ruimtelijke structuur van de sleutel gaat het slotje open.  

# Binnenkort weer hooikoorts? Eerst geen vuiltje aan de lucht

   --{{0}}--
Genieten van de lente is lastig als je hooikoorts hebt: snotteren, niezen en tranende ogen. Je bent of kent vast wel iemand met een allergie. Gelukkig is er iets aan te doen. Neem een antihistaminepilletje, dat is een medicijn tegen allergieverschijnselen, en je hebt veel minder last. Er bestaan al veel verschillende antihistaminemedicijnen. We weten dat alle antihistamines werken op een speciaal molecuul in je lichaam: de histaminereceptor. Een receptor is een groot molecuul (een eiwit) dat als antenne voor je cellen fungeert. Het steekt door de buitenkant van de cel heen en vangt signalen op uit de rest van je lichaam, of soms zelfs van buiten, en geeft dit binnen in de cel door.

![histaminereceptor met cel](./img/01cel-receptor.svg "[^🦶]")


[^🦶]: https://www.c3.nl/wp-content/uploads/woocommerce_uploads/2018/02/Voor-de-leerling-Knutselen-met-moleculen.pdf

# Je lichaam ruikt gevaar, histamine is vrijgekomen

   --{{0}}--
Als er iets gevaarlijks in de lucht hangt, gaan er allerlei alarmbellen af in je lichaam. Eén zo’n noodsignaal is een klein molecuul, histamine, dat in het slijmvliesweefsel van je ogen en neus vrijkomt.

![histamine](./img/02histamine-cel-niet-gebonden.svg "[^🦶]")


[^🦶]: https://www.c3.nl/wp-content/uploads/woocommerce_uploads/2018/02/Voor-de-leerling-Knutselen-met-moleculen.pdf

# Groot alarm -- je ogen tranen, je hebt een snotneus...

   --{{0}}--
Histamine wordt vastgegrepen door de histaminereceptor. Zodra die twee elkaar hebben gevonden, weten je slijmvliescellen: ‘Er is groot alarm! We moeten extra slijm maken.’ Je ogen gaan tranen, je krijgt een snotneus en kriebel in je keel: zo probeert het lichaam de gevaarlijke deeltjes zo snel mogelijk weer kwijt te raken.

![histamine bindt aan ](./img/03histamine-cel-gebonden.svg "[^🦶]")

[^🦶]: https://www.c3.nl/wp-content/uploads/woocommerce_uploads/2018/02/Voor-de-leerling-Knutselen-met-moleculen.pdf


# Ook in ons lichaam hebben we 'sleutels' en 'sloten' 

   --{{0}}--
De kleine moleculen zoals histamine in ons voorbeeld zijn de sleutels. Deze moleculen worden ook substraten genoemd. En de eiwitten zijn de sloten -- in ons voorbeeld een histaminereceptor. Op een cel vinden we meer dan een type eitwitreceptor terug. 

![biologische sleutels en sloten](./img/05molecuul-receptor-cel.svg "[^🦶]")

[^🦶]: https://www.c3.nl/wp-content/uploads/woocommerce_uploads/2018/02/Voor-de-leerling-Knutselen-met-moleculen.pdf

# Niet elke sleutel past op elk slot

   --{{0}}--
Zoals in ons voorbeeld van de liefdesslotjes bestaan er ook in ons lichaam meer dan een sleutels. En sommige sleutels passen wel, het histamine in ons voorbeeld, en andere niet, zoals de blauwe, spitse sleutel, op de histaminereceptor. 

![sleutel past of niet](./img/06sleutel-slot-yes-no.svg "[^🦶]")

[^🦶]: https://www.c3.nl/wp-content/uploads/woocommerce_uploads/2018/02/Voor-de-leerling-Knutselen-met-moleculen.pdf

# Biologische sloten hebben vaak meer dan een sleutel 

   --{{0}}--
Maar als je allergisch bent, gaat het alarm te vroeg af. Dan denkt je lichaam dat ongevaarlijke dingen, zoals stuifmeel, wél gevaarlijk zijn. Heel irritant! Sommige mensen lopen de hele lente te snotteren. Om hen te helpen, zijn er onder andere antihistaminemedicijnen uitgevonden. Die medicijnen plakken nog beter dan histamine zelf aan de antenne (de histaminereceptor) waardoor er geen plek meer is voor het alarmmolecuul histamine. Het alarm kan dan niet meer afgaan. De slijmcellen merken niks en je neus blijft droog.

![een antihistamine onderdrukt de biologische reactie](./img/07sleutel-slot-yes-no-inhibitor.svg "[^🦶]")

[^🦶]: https://www.c3.nl/wp-content/uploads/woocommerce_uploads/2018/02/Voor-de-leerling-Knutselen-met-moleculen.pdf

# In ons lichaam hebben we veel sleutels en heel veel sloten  

   --{{0}}--
Laat ons even terugkijken naar het verhaal van de liefdesslotjes en de sleutels. Zoals in het echte leven hebben we in ons lichaam heel veel sleutels voor heel veel sloten. Enkel als ze een sleutel (histamine of anti-histamine) op de juiste slot (histaminereceptor) past, kan een biologische signaal worden doorgegeven of worden tegengehouden.

![de sleutel moet op het slot passen](./img/04sleutel-slot-cel.svg "[^🦶]")

[^🦶]: https://www.c3.nl/wp-content/uploads/woocommerce_uploads/2018/02/Voor-de-leerling-Knutselen-met-moleculen.pdf

# Het sleutel-slot principe is al 130 jaar oud
   
      --{{0}}--
Laat ons even samenvatten: Het sleutel-slot principe is essentieel voor het begrijpen van moleculaire interacties in de biologie en heeft brede toepassingen in de wetenschap en geneeskunde. Sleutels zijn moleculen of substraten en de sloten zijn eiwitten. Niet elke sleutel past op elk slot en biologische sloten hebben vaak meer dan een sleutel. Dit prinzipe werd 1894 door Emil Fischer hypothetisch beschreven aan de hand van de spezifieke interactie tussen een enzym, een eiwit, en substraat. Het sleutel-slot principe wordt toegepast bij hormoon-receptor binding, enzym-substraat interacties, en bij medicijnontwerp.

![](https://upload.wikimedia.org/wikipedia/commons/e/e0/Hermann_Emil_Fischer_c1895.jpg "[^🦶]")
Het sleutel-slot principe wordt toegepast in enzym-substraat interacties, hormoon-receptor binding, en medicijnontwerp.

[^🦶]: Emil Fischer https://en.wikipedia.org/wiki/File:Hermann_Emil_Fischer_c1895.jpg; 


# Referenties

- Knutselen met moleculen. (2018, februari). Centrum Jongeren­Communicatie Chemie. https://www.c3.nl/wp-content/uploads/woocommerce_uploads/2018/02/Voor-de-leerling-Knutselen-met-moleculen.pdf
- Emil Fischer. (2024 december 1) https://en.wikipedia.org/wiki/Emil_Fischer
