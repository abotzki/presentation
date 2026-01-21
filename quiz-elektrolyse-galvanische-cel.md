<!--
title: "Quiz Nomenclatuur Homologe verbindingen van benzeen"
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
> [Laten we beginnen!](https://liascript.github.io/course/?https://raw.githubusercontent.com/abotzki/presentation/refs/heads/master/quiz-elektrolyse-galvanische-cel.md)


# Quiz: Galvanische cellen vs. elektrolysecellen

## Vraag 1
Wat is het fundamentele verschil in energieomzetting tussen een galvanische cel en een elektrolysecel?

<!-- data-randomize -->
- [[ ]] A. Beide celtypes zetten chemische enerige in warmteenergie om.
- [[X]] B. Een galvanische cel zet chemische energie in elektrische energie om.
- [[X]] C. Een electrolysecel zet elektrische energie in chemische energie om.
******
 - ✅ Juist. Bij elektrolyse wordt een niet-spontane reactie afgedwongen door een externe spanningsbron.
- ✅ Juist. Een galvanische (voltaïsche) cel levert een spanning uit een spontane redoxreactie.
- ❌ Onjuist. Warmte kan vrijkomen, maar dat is niet de fundamentele functie van deze cellen.

*****

## Vraag 2
Welk proces vindt plaats aan de anode, ongeacht of het een galvanische of een elektrolysecel is?

<!-- data-randomize -->
- [[ ]] A. Neutralisatie
- [[ ]] B. Reductie
- [[X]] C. Oxidatie
***********
✅ Juist. **O**xidatie aan de **A**node (ezelsbrug: **A**node - **O**xidatie**).

Reductie vindt plaats aan de **kathode**.

Neutralisatie is een zuur–baseproces en hoort niet specifiek bij elektrochemische elektroden.

***********

## Vraag 3
Welke uitspraak over de spontaniteit van de reacties in de cellen is correct?

<!-- data-randomize -->
- [[X]] A. De reacties in een elektrolysecel zijn niet-spontaan en worden door een externe stroombron aangedreven. 

