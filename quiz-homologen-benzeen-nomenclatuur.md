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
> [Laten we beginnen!](https://liascript.github.io/course/?https://raw.githubusercontent.com/abotzki/presentation/refs/heads/master/quiz-homologen-benzeen-nomenclatuur.md)

## Quiz over Benzeen

        {{0-1}}
*******************
1. Welke elementen bevat benzeen volgens de analyse?
[[ ]] Koolstof en zuurstof
[[x]] Koolstof en waterstof
[[ ]] Koolstof en stikstof

****************

       {{1-2}}
*******************
2. Wat is de molecuulmassa van benzeen?
[[x]] 78,0 u
[[ ]] 92,3 u
[[ ]] 120,0 u

*******************

       {{2-3}}
*******************
3. Wie stelde voor het eerst een aanvaardbare structuur van benzeen voor?
[[ ]] Dalton
[[x]] Kekulé
[[ ]] Avogadro

*******************

       {{3-4}}
*******************
4. Wat is de afstand tussen de koolstofatomen in benzeen?
[[ ]] 154 pm
[[x]] 140 pm
[[ ]] 134 pm

*******************

       {{4-5}}
*******************
5. Wat verklaart de afwijkingen in de chemische eigenschappen van benzeen?
[[ ]] Hybridisatie-model
[[x]] Mesomerie-model
[[ ]] Resonantie-model

*******************

       {{5-6}}
*******************
7. Wat is een aromatisch sextet?
[[ ]] Een zesring van koolstofatomen met afwisselend enkele en dubbele bindingen
[[x]] Een grote ringvormige overlappingsorbitale van zes p-orbitalen met elk één elektron
[[ ]] Een zeshoekige structuur met enkelvoudige bindingen

*******************
