
<!--
title: "Quiz Polaire en apolaire stoffen"
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

# Welkom bij de quiz over polaire en apolaire stoffen

> We gebruiken de interactieve Open Educational Resource online/offline infrastructuur LiaScript.
> [Laten we beginnen!](https://liascript.github.io/course/?https://raw.githubusercontent.com/abotzki/presentation/refs/heads/master/quiz-polaire-apolaire-stoffen.md)
> Klik vervolgens op de titels 'Vraag 1' tot 'Vraag 6' aan de linkerkant.


# Elektronegativiteit en Moleculaire Polariteit - Quiz

## Vraag 1
**Wat is de elektronegatieve waarde van een element?**

    [[ ]] (1) De massa van een element
    [[ ]] (2) Het aantal protonen in de kern
    [[x]] (3) De neiging van een atoom om elektronen aan te trekken in een chemische binding
    [[ ]] (4) De energie die vrijkomt bij verbranding

## Vraag 2
**Welke waarde heeft fluor?**

    [[ ]] (1) 2,1
    [[ ]] (2) 3,0
    [[x]] (3) 4,0
    [[ ]] (4) 1,5

## Vraag 3
**Wat is een apolaire molecule?**

    [[x]] (1) Een molecule waar de partiele ladingen zich ruimtelijk opheffen
    [[ ]] (2) Een molecule met een positieve en negatieve pool
    [[ ]] (3) Een molecule die altijd metaal bevat
    [[ ]] (4) Een molecule die geen bindingen heeft

## Vraag 4
**Is dizuurstof (O₂) apolair of polair?**

    [[ ]] (1) Polair
    [[x]] (2) Apolair

## Vraag 5
**Hoe symboliseer je een partiële negatieve lading in een molecule?**

    [[ ]] (1) +
    [[ ]] (2) -
    [[x]] (3) δ⁻
    [[ ]] (4) e⁻
