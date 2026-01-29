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
> [Laten we beginnen!](https://liascript.github.io/course/?https://raw.githubusercontent.com/abotzki/presentation/refs/heads/quiz-elektrolyse/quiz-elektrolyse-galvanische-cel.md)

# Quiz: Galvanische cellen vs. elektrolysecellen

## Vraag 1
Welk proces vindt plaats aan de anode, ongeacht of het een galvanische of een elektrolysecel is?

<!-- data-randomize -->
- [[ ]] **ORANGE**<!-- style="color: #ffc14a" --> Neutralisatie
- [[ ]] **LICHTBLAUW**<!-- style="color: #76c0d6" --> Reductie
- [[X]] **ROZE**<!-- style="color: #ff71ce" --> Oxidatie
***********
✅ Juist. **O**xidatie aan de **A**node (ezelsbrug: **A**node - **O**xidatie).

Reductie vindt plaats aan de **kathode**.

Neutralisatie is een zuur–baseproces en hoort niet specifiek bij elektrochemische elektroden.

***********

## Vraag 2
Welke uitspraak over de **spontaniteit** van de reacties in de cellen is correct?

<!-- data-randomize -->
- [[X]] **ORANGE**<!-- style="color: #ffc14a" --> In een galvanische cel verloopt de netto reactie spontaan, in een elektrolysecel niet-spontaan.
- [[ ]] **LICHTBLAUW**<!-- style="color: #76c0d6" --> Beide celtypes vereisen externe energie om te reageren.
- [[ ]] **ROZE**<!-- style="color: #ff71ce" --> Bij beide celtypes staan de reacties in evenwicht.
*******
✅ Juist. Galvanisch: **spontaan** (ΔG < 0, E°cel > 0). Elektrolyse: **niet-spontaan** (ΔG > 0, externe spanning vereist).
❌ Onjuist. Alleen elektrolyse vereist externe energie om de reactie te laten verlopen.
❌ Onjuist. ΔG = 0 hoort bij evenwicht, niet bij werkende cellen.

*******

## Vraag 3
Wat is de rol van een **inerte elektrode** in een elektrochemische cel?

<!-- data-randomize -->
- [[X]] **ROZE**<!-- style="color: #ff71ce" --> Ze geleidt elektronen maar neemt zelf niet deel aan de redoxreactie.
- [[ ]] **LICHTBLAUW**<!-- style="color: #76c0d6" --> Ze reageert actief mee om de netto celreactie mogelijk te maken.
- [[ ]] **ORANGE**<!-- style="color: #ffc14a" --> Ze verandert spontaan in een ion om de halfreacties te ondersteunen.
***********
✅ Correct. **Inerte elektroden** (zoals Pt of grafiet) dienen enkel als geleidend oppervlak wanneer de reactanten in vloeibare of oplossing zitten en de elektrode zelf niet kan of mag reageren.

❌ Onjuist. Als de elektrode mee zou reageren, is ze per definitie **niet inert**.

❌ Onjuist. Inerte elektroden lossen niet op en vormen geen ionen; ze blijven chemisch stabiel tijdens de reactie.
***********

## Vraag 4
Wat is het fundamentele verschil in energieomzetting tussen een galvanische cel en een elektrolysecel?

<!-- data-randomize -->
- [[ ]] **ROZE**<!-- style="color: #ff71ce" --> Beide celtypes zetten chemische energie in warmteenergie om.
- [[X]] **LICHTBLAUW**<!-- style="color: #76c0d6" --> Een galvanische cel zet chemische energie in elektrische energie om.
- [[X]] **ORANGE**<!-- style="color: #ffc14a" --> Een elektrolysecel zet elektrische energie in chemische energie om.
******
- ✅ Juist. Een galvanische (voltaïsche) cel levert een spanning uit een **spontane** redoxreactie.
- ✅ Juist. Bij elektrolyse wordt een **niet-spontane** reactie afgedwongen door een externe spanningsbron.
- ❌ Onjuist. Warmte kan vrijkomen, maar dat is niet de fundamentele functie van deze cellen.

*****

## Vraag 5
Wat gebeurt er met de **elektronenstroom** en het **ionentransport** in een werkende elektrolyseopstelling met twee vaten?

<!-- data-randomize -->
- [[X]] **ROZE**<!-- style="color: #ff71ce" --> Elektronen worden door de externe spanningsbron naar de kathode gestuurd; via de zoutbrug bewegen kationen naar de kathode en anionen naar de anode.
- [[ ]] **LICHTBLAUW**<!-- style="color: #76c0d6" --> Elektronen bewegen door de oplossing alsook door de externe stroomkring. De ionen bewegen via de zoutbrug tussen de twee vaten.
- [[ ]] **ORANGE**<!-- style="color: #ffc14a" --> Zowel elektronen als ionen bewegen uitsluitend door de externe stroomkring, de elektrolyt speelt geen rol.
***********
✅ Juist. De externe spanningsbron forceert elektronen naar de **kathode** (negatieve pool). Via de zoutbrug migreren **kationen** naar het vat met de kathode en **anionen** naar het vat met de anode.

❌ Onjuist. Elektronen bewegen **nooit** door de oplossing; daar vindt enkel **ionentransport** plaats.

❌ Onjuist. De elektrolyt én ionenmigratie zijn essentieel om lading in de cel te compenseren en de kring te sluiten.
***********



