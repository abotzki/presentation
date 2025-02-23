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

## Wat zijn de namen van deze homologe verbindingen van benzeen?

## Oefening 1

Geef de systematische naam van dit molecuul ![dit molecuul](https://github.com/abotzki/presentation/blob/quiz-nomenclatuur/img/oefening01.png?raw=true)

[[cumeen]]
<script>
let input = "@input".trim().toLowerCase()

input == "cumeen" || input == "isoproylbenzeen" || input == "(1-methylethyl)benzene"
</script>
***********************************************************************

De correcte antwoorden zijn: cumeen of isoproylbenzeen of (1-methylethyl)benzene

***********************************************************************

## Oefening 2

Geef de systematische naam van dit molecuul ![dit molecuul](https://github.com/abotzki/presentation/blob/quiz-nomenclatuur/img/oefening02.png?raw=true)

[[  1-butyl-4-ethyl-2-propylbenzene
    | ( 4-butyl-1-ethyl-2-propylbenzene )
    |   4-butyl-2-ethyl-1-propylbenzene
    |   1-butyl-4-ethyl-3-propylbenzene 
    ]]
***********************************************************************

Het correcte antwoord is: 4-butyl-1-ethyl-2-propylbenzene omdat we de kleinst mogelijke cijfers voor de substituenten willen gebruiken.

***********************************************************************

## Oefening 3

Geef de systematische naam van dit molecuul. ![dit molecuul](https://github.com/abotzki/presentation/blob/quiz-nomenclatuur/img/oefening03.png?raw=true)

[[  (4-methylhex-4-en-3-yl)benzene
    | ( [(4E)-4-methylhex-4-en-3-yl]benzeen )
    | ( (2E)-4-fenyl-3-methylhex-2-een ) 
    |  4-fenyl-3-methylhex-2-een
    ]]
***********************************************************************

Het correcte antwoord is: [(4E)-4-methylhex-4-en-3-yl]benzeen - de IUPAC nomenclatuur geeft de voorkeur aan ringsystemen over ketens indien beide uit dezelfde elementen bestaan.
***********************************************************************
