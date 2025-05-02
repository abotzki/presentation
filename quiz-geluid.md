<!--
title: "Quiz Benzeen"
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
> [Laten we beginnen!](https://liascript.github.io/course/?https://raw.githubusercontent.com/abotzki/presentation/refs/heads/master/quiz-geluid.md)
> Klik vervlgens op de titels 'Vraag 1' tot 'Vraag 5' aan de linkerkant.


# Quiz over Geluid

Dit is een quiz over de kenmerken van geluid.

## Vraag 1
**Wat veroorzaakt geluid?**

    [[X]] Een trilling die wordt doorgegeven door een middenstof.
    [[ ]] Een lichtstraal die door een vacuüm reist.
    [[ ]] Een trilling die zich in vacuüm voortplant.


## Vraag 2
**Wat is resonantie?**

    [[ ]] Het absorberen van geluid door een materiaal.
    [[X]] Het meetrillen van een voorwerp onder invloed van een ander voorwerp dat met dezelfde trilling doorgroeft.
    [[ ]] Het weerkaatsen van geluidsgolven tegen een oppervlak.


## Vraag 3
**Wat bepaalt de toonhoogte van een geluid?**

    [[X]] De frequentie van de trilling.
    [[ ]] De amplitude van de trilling.
    [[ ]] De snelheid van de trilling.

## Vraag 4
**Wat is de eenheid van geluidssterkte?**

    [[X]] Decibel (dB)
    [[ ]] Hertz (Hz)
    [[ ]] Meter per seconde (m/s)

## Vraag 5
Wat is het hoorbereik van het menselijk oor?

        [[ ]] 20 – 20.000 Hz
        [[X]] 20 – 20.000 Hz
        [[ ]] 10 – 10.000 Hz
        [[ ]] 30 – 30.000 Hz

## Vraag 6
Wat is het verschil in hoorbereik tussen mensen en verschillende dieren?

        [[ ]] Mensen horen tussen 20 – 20.000 Hz, honden horen tussen 40 – 60.000 Hz, dolfijnen horen tot 150 kHz, en olifanten horen tussen 16 Hz – 12 kHz.
        [[X]] Mensen horen tussen 20 – 20.000 Hz, honden horen tussen 40 – 60.000 Hz, dolfijnen horen tot 150 kHz, en olifanten horen tussen 16 Hz – 12 kHz.
        [[ ]] Mensen horen tussen 20 – 20.000 Hz, honden horen tussen 20 – 40.000 Hz, dolfijnen horen tot 100 kHz, en olifanten horen tussen 10 Hz – 10 kHz.
        [[ ]] Mensen horen tussen 10 – 10.000 Hz, honden horen tussen 30 – 50.000 Hz, dolfijnen horen tot 120 kHz, en olifanten horen tussen 20 Hz – 15 kHz.
