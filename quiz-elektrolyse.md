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
> [Laten we beginnen!](https://liascript.github.io/course/?https://raw.githubusercontent.com/abotzki/presentation/refs/heads/master/quiz-elektrolyse.md)

# Quiz: Elektrolyse

Vul de tabel hieronder in op basis van je kennis.

## 📝 Vragen

1. **Is een elektrolyse een spontaan of niet‑spontaan proces?**  
2. **Welke type van chemische reactie vindt aan de anode plaats?**  
3. **Wat doet elektrolyse met elektrische stroom: leveren of verbruiken?**  
4. **Wat is de richting van de elektronstroom in een galvanische cel?**  

Vul ter vergelijking ook aan voor de galvanische cel.

| Kenmerk | Galvanische cel | Elektrolyse |
|--------|------------------|-------------|
| Spontaniteit | [[spontaan ]] | [[niet-spontaan ]] |
| Stroom | [[Levert elektrische stroom ]] | [[Verbruikt elektrische stroom ]] |
| Anode | [[negatief geladen ]] | [[positief geladen ]] |
| Cathode | [[positief geladen ]] | [[negatief geladen ]] |
| Elektronen stromen | [[van min naar plus ]] | [[van plus naar min ]] |
| Analogie | [[Batterij gebruiken ]] | [[Batterij opladen ]] |

5. **Welk voorteken heeft het verschil van het standaard redoxpotentiaal bij elektrolyse?**
6. **Hoe beinvloedt het verschil van het standaard redoxpotentiaal welke twee halfreacties bij elektrolyse met niet-inerte elektroden doorgaan?**
