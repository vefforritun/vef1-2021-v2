
# Vefforritun 1, 2021: Verkefni 2, HTML #2

[Kynning í fyrirlestri](https://youtu.be/).

Setja skal upp fjórar síður um nám í tölvunarfræði við HÍ, aðgengilegar af internetinu:

1. Forsíða með upplýsingum um tölvunarfræði nám
2. Síða með skráningarformi í tölvunarfræði
3. Síða með töflu yfir áfanga
4. Síða með spurt og svarað

Fyrir hverja síðu á að einblína á að setja upp merkingarfræðilegt HTML.

Allar síður fyrir utan forsíðu skulu vera innan `pages/` möppu:

* `index.html` skal innihalda upplýsingar um tölvunarfræði nám
* `pages/apply.html` skal innihalda skráningaform
* `pages/courses.html` skal innihalda töflu yfir áfanga
* `pages/faq.html` skal innihalda spurningar og svör

Efnið skal koma frá raunverulegu efni um [nám í tölvunarfræði við HÍ](https://www.hi.is/tolvunarfraedi), athugið að þó að efnið sé sett upp með HTML þýðir það _ekki_ að notað sé merkingarfræðilega rétt element. Þið þurfið að taka afstöðu til þess.

## Efni

Allar síður skulu innihalda valmynd sem vísar á allar aðrar síður og merkja valda síðu á einhvern hátt. Athugið að allar síður fyrir utan forsíðu verða að vera undir `pages/` möppu.

### Forsíða

Inniheldur efni sem fram kemur á síðunni `https://www.hi.is/tolvunarfraedi`, nákvæmt efni er í `data/index.txt`.

Tengill með textanum „Sækja um nám“ skal vísa á umsóknarsíður.

Fella skal inn myndina `data/cs.jpg`
([credit](https://unsplash.com/photos/hbb6GkG6p9M)).

[Fella skal inn efni af YouTube](https://www.youtube.com/watch?v=v2Em6HmlBRU).

### Skráningarform

Form tekur við upplýsingum um umsókn um nám.

Eftirfarandi skal biðja um í formi, hópað saman með `<fieldset>` og með viðeigandi `legend`:

* Persónuupplýsingar
  * Nafn, textareitur, krafist
  * Kennitala, textareitur, krafist, „placeholder“ sem gefur til kynna íslenska kennitölu (t.d. `000000-0000`)
  * Sími, textareitur, krafist
  * Tölvupóstur, textareitur, krafist, innihald ætti að líta út eins og netfang
* Framhaldsskóli
  * Skóli, val á skóla úr listanum í `data/schools.txt`
  * Prófgráða, textareitur
  * Er námi lokið? Val um hvort því sé lokið eða ekki
  * Lokadagsetning, val um dagsetningu þegar námi lauk
* Kjörsvið
  * Val á kjörsviði úr `data/kjorsvid.txt`
* Fylgigögn
  * Þrír reitir sem bjóða upp á að velja skrá með fyrirsögnum: fylgigögn, prófskírteini, annað

Ekki er gefin nákvæm forskrift um það hvernig útfæra skuli reiti, veljið það sem passar best út frá ykkar túlkun á form elementum og forskrift.

Þegar ýtt er á takka gerist ekki neitt, þ.e.a.s. engin kóði keyrir og gögn eru ekki send neitt.

### Áfangar

Birta skal töflu með áföngum í tölvunarfræði, sjá gögn í `data/courses.txt`. Fyrsta lína skilgreinir heiti dálka, milli hvers dálk er tab stafur, `\t`. Bil og fyrirsögn skiptir milli ára.

[Gögnin koma frá kennsluskrá.](https://ugla.hi.is/kennsluskra/index.php?tab=nam&chapter=namsleid&id=080713_20216&kennsluar=2021)

### Spurt og svarað

Inniheldur spurningar frá síðunni `https://www.hi.is/tolvunarfraedi`, nákvæmt efni er í `data/faq.txt`. Athugið að færa skal inn tengla sem eru á síðunni og lesa út úr birtingu hvað þurfi að merkja sérstaklega með merkingarfræðilegu HTML.

## Útlit

Ekki er gefin forskrift að útliti, þar sem verkefnið snýst um að setja upp merkingarfræðilegt HTML.

Ekki þarf að gera neitt með CSS.

## Almennt

* **Nýta skal merkingarfræðilega viðeigandi element**.
* Valmynd má (og á!) að útfæra með því að afrita og breyta milli síðna, ekki er krafa um neina „forritun“ til að útbúa valmynd.
* Allar síður skulu hafa fyrisögn og „beint í efni“ hlekk á eftir fyrirsögn, en á undan valmynd.
* Síður skulu nota `utf-8` stafasett.
* Passa skal upp á að hafa snyrtilega uppsettan kóða þar sem inndráttur er samræmdur.
* Allar síður skulu vera villulausar ef prófaðar með [HTML validator](https://validator.w3.org/).
* Allar síður skulu vera án aðgengisvillna ef prófaðar með [aXe](https://www.deque.com/axe/), setjið upp viðbót í vafra.

## Heimasvæði

Setja skal síður upp á [heimasvæði ykkar hjá HÍ](https://uts.hi.is/node/155) undir möppu `.public_html/vefforritun/verkefni2` svo verkefnið verði aðgengilegt á `https://notendur.hi.is/<notendanafn>/vefforritun/verkefni2` þar sem `<notendnafn>` er notendanafnið þitt (t.d. `osk`).

## Mat

* 20% – Snyrtilega uppsettur kóði með merkingarfræðilegum elementum fyrir hverja síðu
* 20% – Síður án villna frá HTML validator og WAVE validator
* 20% – Form uppsett eftir forskrift
* 20% – Tafla uppsett eftir forskrift
* 20% – Forsíða; spurt og svarað síður uppsettar eftir forskrift

## Sett fyrir

Verkefni sett fyrir í fyrirlestri mánudaginn 30. ágúst 2021.

## Skil

Skila skal í Canvas í seinasta lagi fyrir lok dags þriðjudaginn 7. september 2021.

Skilaboð skulu innihalda:

* slóð á verkefni
* zip skjali með lausn

Hver dagur eftir skil dregur verkefni niður um 10%, allt að 20% ef skilað fimmtudaginn 9. september 2021 en þá lokar fyrir skil.

## Einkunn

Leyfilegt er að ræða, og vinna saman að verkefni en **skrifið ykkar eigin lausn**. Ef tvær eða fleiri lausnir eru mjög líkar þarf að færa rök fyrir því, annars munu allir hlutaðeigandi hugsanlega fá 0 fyrir verkefnið.

Sett verða fyrir tíu minni verkefni þar sem átta bestu gilda 5% hvert, samtals 40% af lokaeinkunn.

Sett verða fyrir tvö hópverkefni þar sem hvort um sig gildir 10%, samtals 20% af lokaeinkunn.

> Útgáfa 0.1
