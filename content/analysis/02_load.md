
Utvärdera webbplatsers laddningstider
=======================

<!-- Skriv en eller två rader om vad uppgiften handlar om. -->
Den här rapporten undersöker tre specifika webbplatser och dess undersidors laddningstider och användbarhet. Rapporten tittar även på sidors totala storlek och hur mycket som behöver överföras för att webbplatsen ska fungera. 


Urval
-----------------------

<!-- Berätta vilka webbplatser du valt att undersöka och varför eller hur du gick tillväga när du gjorde ditt urval. -->
Mina webbplatser befinner sig alla inom bilindustrin och mitt urval är baserat på vilken målgrupp/priskategori respektive märke har. De märken jag kommer att undersöka är:

- KIA (mellanprissegment)
- Volvo (övre mellanprissegment/ högprissegment)
- Koenigsegg (lyxprissegment)

Jag har gjort mitt urval för att ta reda på om det skiljer sig något mellan de olika webbplatserna, behöver egentligen Koenigsegg en "snabb" sida - de säljer väl bilar ändå? Eller matchar prestandan i deras bilar prestandan på deras webbplats? Hur väl fungerar mobilvarianterna för respektive märke, inte köper man en bil via mobilen - eller?

Metod
-----------------------

<!-- Berätta kort om din "metod", hur du gör för att utföra undersökningen. Berätta om du använder något speciellt verktyg. -->
I den här rapporten har jag använt Googles verktyg PageSpeedInsights (PSI) tillsammans med Utvecklarverktyget i webbläsaren Firefox Developer Edition. Varje sida har körts en gång i PSI för att mäta hastighet och prestanda för både mobil- och desktop-varianten. Dess resultat har antecknats i ett Google Kalkylark som finns inbäddat i denna rapport. Vidare mättes varje sidas laddningshastighet via Utvecklarverktyget i Firefox tre gånger, dessa resultat har också antecknats i kalkylarket tillsammans med snittet på de tre mätningarna. 

Resultat
-----------------------

<!-- Dokumentera dina resultat från din studie. Berätta vad du kom fram till, vilka resultat du hittade och observerade. -->
## Koenigsegg

![Koenigsegg](%assets_url%/img/Koenigsegg_home.png){.home-page}

### Resultat - mobilt
<iframe title="Koenigsegg mobilt" class="spreadsheet" width="650px" height="770px" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTl587CS0krchXy5d9vlLD_LV-r3OZzAwlRcMG9JNqdqztY5k7LsS-sG7i0IOJSwKddmDP86sp6PyBC/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

#### Förbättringar - mobilt
De förbättringar som PSI anger är:
- skicka bilder i modernare format (WebP, AVIF)
- ta bort resurser som blockerar renderingen
- reducera JavaScript/CSS som inte används

### Resultat - desktop
<iframe title="Koenigsegg desktop" class="spreadsheet" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTl587CS0krchXy5d9vlLD_LV-r3OZzAwlRcMG9JNqdqztY5k7LsS-sG7i0IOJSwKddmDP86sp6PyBC/pubhtml?gid=706159693&amp;single=true&amp;widget=true&amp;headers=false" ></iframe>

#### Förbättringar - desktop
De förbättringar som PSI anger är:
- ta bort resurser som blockerar renderingen
- skicka bilder i modernare format (WebP, AVIF)

## KIA

![KIA](%assets_url%/img/KIA_home.png){.home-page}

### Resultat - mobilt
<iframe title="KIA mobilt" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTl587CS0krchXy5d9vlLD_LV-r3OZzAwlRcMG9JNqdqztY5k7LsS-sG7i0IOJSwKddmDP86sp6PyBC/pubhtml?gid=2106853689&amp;single=true&amp;widget=true&amp;headers=false" class="spreadsheet"></iframe>

#### Förbättringar - mobilt
De förbättringar som PSI anger är:
- skicka bilder i modernare format (WebP, AVIF)
- skjut upp inläsningen av bilder som inte visas på skärmen
- ta bort resurser som blockerar renderingen
- reducera JavaScript/CSS som inte används
- minska serverns första svarstid

### Resultat - desktop
<iframe title="KIA desktop" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTl587CS0krchXy5d9vlLD_LV-r3OZzAwlRcMG9JNqdqztY5k7LsS-sG7i0IOJSwKddmDP86sp6PyBC/pubhtml?gid=1036166023&amp;single=true&amp;widget=true&amp;headers=false" class="spreadsheet"></iframe>

#### Förbättringar - desktop
De förbättringar som PSI anger är:
- skicka bilder i modernare format (WebP, AVIF)
- skjut upp inläsningen av bilder som inte visas på skärmen
- ta bort resurser som blockerar renderingen

## Volvo

![Volvo](%assets_url%/img/Volvo_home.png){.home-page}

### Resultat - mobilt
<iframe title="Volvo mobilt" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTl587CS0krchXy5d9vlLD_LV-r3OZzAwlRcMG9JNqdqztY5k7LsS-sG7i0IOJSwKddmDP86sp6PyBC/pubhtml?gid=1230954065&amp;single=true&amp;widget=true&amp;headers=false" class="spreadsheet"></iframe>

#### Förbättringar - mobilt
De förbättringar som PSI anger är:
- använd bilder med rätt storlek
- reducera JavaScript som inte används

### Resultat - desktop
<iframe title="Volvo desktop" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTl587CS0krchXy5d9vlLD_LV-r3OZzAwlRcMG9JNqdqztY5k7LsS-sG7i0IOJSwKddmDP86sp6PyBC/pubhtml?gid=1996291819&amp;single=true&amp;widget=true&amp;headers=false" class="spreadsheet"></iframe>

#### Förbättringar - desktop
De förbättringar som PSI anger är:
- använd bilder med rätt storlek
- reducera JavaScript som inte används


Analys
-----------------------

<!-- Diskutera och analysera de resultaten du fann. -->
Av de resultat som har framkommit i den här rapporten är jag väldigt förvånad över att alla mobila webbplatser presterar så dåligt hos de undersökta bilmärkena. Inte nog med det så presterar Koenigsegg (lyxmärket) sämst av allihop, borde det inte vara tvärtom? Här anser jag inte att webbplatsen motsvarar produkten de säljer och det känns inte som att mobil-varianten är deras fokus. Trots att både KIA och Volvos hemsida får en cookie-popup, som är det första man möts av, så presterar de bättre än en sida som inte ens ställer en fråga om cookies.

Det borde finnas en anledning till att inte en enda mobil-sida får godkänt av PSI och en hypotes är att det antagligen finns statistik hos respektive bilmärke som visar att majoriteten av sidvisningar sker via desktop och att de helt enkelt inte väljer att optimera sina mobila webbplatser. Om det skulle vara fallet så känns det ändå lite orimligt då bilindustrin i sig är en bransch som stolt berättar om sina innovationer, borde det inte också synas på det mediet som antagligen flest människor möter deras varumärke via?
Bland de förbättringsåtgärder som framkommer av de mobila-webbplatserna så är det mest förekommande förslaget "reducera JavaScript/CSS som inte används" och det antar jag beror på att ingen skapar separata mobilsidor. Utan de ändras t.ex. via media queries och då ligger så klart kod som t.ex. endast används på desktop kvar i filerna som ändå måste laddas ner till mobilen. 

Nästa förbättringsåtgärd som gäller de mobila webbplatserna är att "använda bilder med rätt storlek/skicka bilder i modernare format" vilket visar på att bilder just kan vara en flaskhals på ens webbplats om de inte optimeras eller används på rätt sätt. Det ser man framförallt på laddningstiden av respektive startsida där Volvo har den snabbaste tiden på 1,58 sekunder medan Koenigsegg hamnar på rejäla 4,10 sekunder, trots att Volvo har hela 15 bilder på startsidan jämfört med Koenigseggs 4 bilder... 

Nummer tre på förbättringslistan, som gäller KIA och Koenigseggs mobila webbplatser, är att de inte "tar bort resurser som blockerar renderingen" vilket ger längre laddningstider. De har alltså inte optimerat när och hur innehållet ska renderas för att få en snabbare webbplats.

Vidare känns det också märkligt att det är så många desktop-sidor som inte får godkänt av PSI, Volvo är undantaget vars alla desktop-sidor blir godkända av PSI tillsammans med låga överföringshastigheter. Men om nu Volvo har en så bra desktop-sida, varför fixar man inte till mobil-sidan? Koenigsegg hämtar sig lite i testerna men hamnar återigen sist utan några PSI-godkända sidor medan KIA får en sida godkänd (Om/historia). Återigen nämner förbättringsåtgärderna det som redan fångats in på mobil-sidorna, bilder och rendering. 

Min egna rangordning, utefter eget tycke, som jag också trodde att rapporten skulle understryka:
1. Koenigsegg
2. Volvo
3. KIA

När jag däremot rangordnar webbplatserna utefter resultaten från PSI och Utvecklarverktyget så ser det ut så här, både för mobil- och desktopsidorna:
1. Volvo
2. KIA
3. Koenigsegg

Då jag vet att Volvo är innovativa och duktiga när det kommer till olika typer av medier (titta bara på deras reklamfilmer) så antog jag att de skulle placera sig högt i denna rapporten, men jag trodde faktiskt att Koenigsegg skulle ta första platsen. Detta då de har en så specifik målgrupp som de måste utmärka sig för samtidigt som det finns rätt många sport/lyxbilsmärken att konkurrera med. Men, det verkar som att de säljer bilar oavsett hur dess webbplats presterar och helt ärligt - är de ens medvetna om att webbplatsen presterar så dåligt som den gör?

Min egna smärtgräns för hur länge en webbplats får ladda ligger på cirka 5 sekunder och där klarar sig alla webbplatser. Efter det så börjar i alla fall jag få tankar som t.ex. "fungerar verkligen webbplatsen" eller "är det fel på min uppkoppling". Rent generellt och bortsett från ovan resultat så upplevs majoriteten av webbplatserna som hyfsat snabba, men det är väl klart att man som blivande webbprogrammerare alltid vill ha den snabbaste sidan - både i verkligheten och teoretiskt? 

Referenser
-----------------------

<!-- Ange de eventuella referenser du använder dig av, om några. -->
- PageSpeed Insights, https://pagespeed.web.dev/
- Utvecklarverktyget i Firefox Developer Edition

Övrigt
-----------------------
Alexis Norberg och jag har skrivit den här rapporten enskilt. 
<!-- Skriv ditt eget namn samt vilka gruppmedlemmar som deltog i att författa rapporten. -->
