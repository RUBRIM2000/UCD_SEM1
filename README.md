# SPORTS AND TECH
*Het ontwikkelen van een wearable met behulp van een digitale component voor blessure preventie* 

*Groep 13: Milan Berckmoes; Ruben Rimbaut*

24 - 05 - 2024

## Samenvatting

Afgelopen academiejaar verdiepten we ons in OnTracx, een start-up van UGent die met een innovatief concept op de proppen komt rond het revalideren en voorkomen van loopblessures. In de eerste fase werd voornamelijk naar valkuilen binnen het concept van de start-up gezocht. Uiteindelijk zou de wearable de grootste valkuil zijn, aangezien het hele concept staat of valt bij correcte sensorwaarden. In de definition fase werd gekeken hoe men de band voor iedere gebruiker passend kon maken. In semester 2 werd de volledige develop fase doorlopen, in dit deel wordt de verdere uitwerking van het product in detail omschreven.

<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/f9689242-ddba-413d-b48e-bc5b8381cc98" alt="Hero Image">
  <br>
  <em>Hero image</em>
</p>

## Introductie

Wereldwijd zijn er 110 miljoen lopers, waarvan 50 miljoen last heeft van blessures (De Mey, 2023)[^1]. Ondanks de vele oplossingen die diverse merken bieden dalen deze cijfers niet, de oplossing moet dus elders gezocht worden. OnTracx komt met een vernieuwende aanpak waarbij de kern van het probleem, volgens hen, centraal staat: het verminderen van de impact op de botten. OnTracx heeft al grotendeels de grote lijnen uitgestippeld, maar toch zijn nog enkele valkuilen opgemerkt. 

> "Wereldwijd zijn er 110 miljoen lopers, waarvan 50 miljoen last heeft van blessures."

Het hele project van OnTracx staat of valt met nauwkeurige metingen van de belasting. Daarom ligt de focus tijdens deze ontwerpstudie op het uitwerken van de wearable waarin de sensor verwerkt zit. Er wordt hiervoor op zoek gegaan naar allerhande methoden om deze op een gebruiksvriendelijke manier te kunnen sluiten en aan te spannen. Daarbij is het belangrijk dat de sensor niet kan bewegen en dat we tegelijkertijd de doorbloeding van het been niet afsnijden. Om dit te realiseren zal er worden gebruikgemaakt van een drukmeting, hierdoor zal duidelijk worden wanneer de juiste spanning bereikt is. Voor een nauwkeurige en betrouwbare meting is het essentieel dat de sensor correct gedragen wordt en dat de gebruiker deze dus ook zelf op een correcte manier kan aanbrengen. Vandaar dat er gezocht wordt naar een methode om dit te kunnen garanderen. Om snel en duidelijk aan te geven wanneer de juiste spanning is bereikt, wordt onderzocht hoe de data uit de drukmeting het best gevisualiseerd kan worden. 

In dit project zullen alle aspecten worden gevalideerd door middel van gebruikerstesten, interviews, expert reviews, etc. De feedback van de gebruikers zal leiden tot onderbouwde designbeslissingen en goed gedocumenteerde design requirements.


## Methdologie
Het model dat wordt toegepast tijdens dit project is de ‘triple diamond’ van Zendesk. Dit model bestaat uit vier ontwerpfasen: discover, define, develop en deliver. Alle fasen van dit model worden in dit rapport behandeld.
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/e182623a-a465-46e6-8552-929113b5fef0" alt="Tijdlijn">
  <br>
  <em>Figuur 1: Tijdlijn</em>
</p>

### Discovery
In de discovery fase is er op zoek gegaan naar een antwoord op de vraag: ‘Wat is het probleem?’. Het uiteindelijke doel is het formuleren van een goede “how can we” waarin de doelgroep en het probleem worden vastgelegd. Om dit te bereiken werden er knowledge templates, zoals de innovatrix[^2], toegepast en activiteiten uitgevoerd. Om het probleem te onderzoeken werd er eerst een desktop research en een competitor analysis gedaan om de markt beter te begrijpen. Tot slot werden er user interviews en expert interviews afgenomen om de gebruiker beter te leren kennen. Dit wordt allemaal uitgevoerd door middel van een testing protocol en een rapport achteraf.
Om het probleem te definiëren wordt de informatie die verzameld werd uit de verschillende activiteiten geconvergeerd. De doelgroep wordt bepaald en de belangrijkste inzichten van de gebruikers worden uitgezet in een feasibility/desirability canvas.
Dit komt allemaal samen in een “how can we” die, zoals gezegd, de doelgroep en het probleem vastlegt.

### Definition
Hierna volgt de definition fase waarin een antwoord gezocht wordt op de vraag: Wat is de oplossing?”. Eerst werd er een creativity lab uitgevoerd in de les, waarbij zoveel mogelijk oplossingen en ideeën werden bedacht. Daarna werd er een brainstorm[^3] gedaan om de belangrijkste inzichten van het individuele discovery onderzoek samen te leggen.
Tijdens het convergeren wordt er een gebruiksscenario verteld met behulp van een storyboard. Tot slot worden er concept sketches en low-fi prototypes gemaakt, die vervolgens worden getest bij gebruikers.

### Develop
Uit de feedback van de tussentijdse verdediging bleek dat er te veel aspecten van het OnTracx-project werden behandeld (wearable, real-time feedback in de app, gamification, dashboard voor professionals, etc.), waardoor deze te weinig waren uitgewerkt. Daarom is na de definitionfase besloten om de focus te verleggen naar het ontwikkelen van de wearable en hoe deze zo gebruiksvriendelijk mogelijk kan worden ontworpen.
De developfase bestaat uit drie deelfasen waarbij gefocust wordt op de fysieke ergonomie, de usability en UX en tot slot de sensoriële ergonomie en bijhorende interacties. Er worden prototypes gemaakt en aan de hand van analyses en gebruikerstesten zal de oplossing steeds meer geoptimaliseerd worden. Het resultaat is een finaal ontwerp van de oplossing.

## Discovery
### Doestellingen
Er wordt een antwoord gezocht op de vraag: “Wat is het probleem?”. Het probleem wordt onderzocht met behulp van een desktop research en een competitor analysis. Het doel is om een duidelijk beeld schetsen van welke concurrerende oplossingen/producten er momenteel op de markt zijn. Het onderzoek zal uitwijzen wat de beste features zijn van elk product, de nadelen, prijs etc. Hieruit zal duidelijk worden welke features er absoluut moeten toegevoegd worden aan ons eigen product en welke niet. Het doel van de user en expert interviews is om een inzicht te krijgen in de wensen en noden van de gebruikers, de lopers enerzijds en de kinesitherapeut/arts anderzijds. Op basis van de antwoorden kan er beslist worden wie de doelgroep wordt, welke functies de app/dashboard zeker nodig heeft en aan welke design requirements de wearable moet voldoen. Het uiteindelijke doel is het formuleren van een goede “how can we” waarin de doelgroep en het probleem worden vastgelegd.
### Materiaal & methoden
#### Desktopresearch en competitor analysis
Het onderzoek start bij de desktopresearch en competitor analysis waarbij er gezocht wordt naar welke oplossingen er vandaag al op de markt zijn. Er werd voor de volgende producten gekozen als relevante competitors, dit zijn 7 populaire producten/wearables die je looptechniek kunnen verbeteren:
- **Soul Run Free Bio**
- **Garmin Running Dynamics Pod**
- **ARION Smart Soles**
- **Stryd Pod Shoe Clip**
- **Wahoo Tickr Run HRM**
- **Runscribe Shoe Clip**
- **Sensoria Socks**

De keuze voor de parameters waarop vergeleken wordt is zo veel mogelijk in belang van het project, vandaar dan ook de keuze voor volgende parameters:

- **Mounting**: Hoe de sensor/wearable bevestigd wordt is een van de belangrijkste aspecten van dit project. Dit bepaalt deels de nauwkeurigheid van de verkregen data, anderzijds is het comfort ervan even belangrijk.
- **Best feature**: Het spreekt voor zich dat ieder product uniek is en elk zijn eigen kwaliteiten heeft, vandaar een opsomming van de concurrenten hun beste features.
- **Real-time feedback**: Het doel van dit project is om de loper gezonder te laten lopen aan de hand van real-time feedback, daarom is het interessant om te weten welke concurrenten deze optie voorzien en hoe de feedback aan de gebruiker wordt gegeven.
- **App**: Het al dan niet voorzien van een specifieke app om de verkregen data op te tonen is een pluspunt voor de gebruiker.
- **Cons**: Elk product heeft ook zijn mindere punten, dit zijn opportuniteiten om je eigen product te differentiëren en te benadrukken wat jouw product beter doet.
- **Price**: De prijs van concurrerende producten kan deels bepalen hoe je je eigen product prijst, anderzijds kun je een inzicht krijgen in de kostenstructuur en de winstmarges van de concurrentie.

#### User en expertinterviews
Er werden 3 interviews afgenomen waarvan 2 expertinterviews met een kinesitherapeut en 1 userinterview met een professionele wielrenner die buiten het wielerseizoen regelmatig gaat lopen. De interviews duren tussen de 30 en 45 minuten en werden afgenomen bij de gebruiker thuis en in de praktijken van de kinesitherapeuten. De interviews werden voorbereid door het opstellen van een protocol, een topic guide. Hierin staan de onderwerpen en bijhorende vragen die aan bod gekomen zijn tijdens de interviews. Alle interviews zijn opgenomen (met toestemming) en kunnen voorgelegd worden indien nodig. Met behulp van deze interviews hoopt men een antwoord te krijgen op volgende onderzoeksvragen:

- Welke doelgroepen worden er het vaakst geconfronteerd met blessures?
- Welke behandeling- en opvolgingsmethoden worden er vandaag toegepast?
- Wat zijn de tekortkomingen vandaag qua data en welke functies zouden nodig zijn voor een goede revalidatie-opvolging?
- Welke functies zijn er nodig om de loper gemotiveerd te houden (gamification)?
- Welke feedbacksystemen zijn er mogelijk?

### Resultaten
#### Desktopresearch en competitor analysis
De resultaten van de competitor analysis zijn te zien in tabel 1. We kunnen zien dat de manier van bevestiging vaak verschilt alsook de beste features van de producten. Vier van de zeven producten beschikken over real-time feedback, wat vaak gepaard gaat met het te frequent geven van feedback. Ook moeten deze producten gekoppeld worden aan een sporthorloge of een smartphone om ze te kunnen gebruiken. De prijzen zijn zeer uiteenlopend, gaande van 55 euro voor een product met basisfeatures tot 556 euro voor een product waarbij een analyse in een lab zit inbegrepen. Voor meer uitleg over deze benchmarkanalyse wordt verwezen naar het protocol[^4] en het rapport[^5].

| ***Name***  | ***Product Type*** | ***Mounting*** | ***Best Feature*** | ***Real-time feedback*** | ***App***| ***Cons*** | ***Price (€)*** |
| ------------- | ------------- | ----------- | ---------------- | ------------------------ | ---- | -------- | ------------- |
| **Soul Run Free Bio**  | Lightweight bluetooth headphones  | Ears | Good sound quality | Yes | Yes | Too much interruptions/feedback | 150 |
| **Garmin Running Dynamics Pod**  | Form-tracking pod  | Clipped onto belt of shorts | Long battery life | No | Yes | Needed to pair with Garmin watch | 69 |
| **Arion Smart Soles**  | Smart insole  | In your shoe | Live heatmap visualization of feet striking | Yes | Yes | Too much interruptions/feedback | 261 |
| **Stryd Pod Shoe Clip**  | Shoe clip full of sensors  | Clipped to your shoelaces | Long battery life | No | Yes | Needed to be paired with watch/phone | 269 |
| **Wahoo Tickr Run HRM**  | Heart Rate monitor  | Around your chest | Compatible with running apps | No | No | Very basic running analysis | 55 |
| **Runscribe Shoe Clip** | Shoe clip full of sensors  | Clipped to your shoelaces | A lot of data | Yes | Yes | Expensive | 556 |
| **Sensoria Socks**  | Smart socks  | On your feet | Personalizing your run (feedback,…) | Yes | Yes | Phone needed to view live data | 278 |
<p align="center">
<em>Tabel 1: resultaten competitor analysis</em></p>

#### User en expertinterviews
Uit de interviews blijkt dat de meeste blessures voorkomen bij recreatieve sporters van boven de 50 jaar. Deze sporters willen te snel en te veel lopen, terwijl ze dit niet meer aankunnen. De huidige behandelingsmethoden beginnen bij hands-on therapie, gevolgd door een rustige opbouw waarbij geluisterd wordt naar het lichaam. Indien er geen klachten zijn, kan de intensiteit verhoogd worden. De opvolging gebeurt bij beide kinesitherapeuten a.d.h.v. een app waar ze gepersonaliseerde oefeningen meegeven met de patiënt. Nadeel is dat er niet gecontroleerd kan worden of de oefening juist is uitgevoerd. De combinatie van subjectieve data en objectieve data (stapgrootte, links-rechts verschil, trunk sway en belasting) is het meest interessant voor de opvolging. Dit zou vooral handig zijn als deze gegevens gestructureerd (in de vorm van grafieken of dergelijke) worden weergegeven in het dashboard en gelinkt zijn aan het patiëntendossier. 
Om de loper gemotiveerd te houden is het delen en het kunnen vergelijken van activiteiten met vrienden een grote meerwaarde, al is de motivatie om een gezonde levensstijl na te streven even belangrijk. De gebruiker gaf aan dat hij voorstander is van een ‘voice coach’ om feedback te geven tijdens het lopen, al moet de frequentie ervan instelbaar zijn. 
Zowel de gebruiker als een van de twee kinesisten gaven aan 300 tot 400 euro te willen betalen voor een product die de belasting meet inclusief de app, zolang dit compatibel is met een sporthorloge. Ook bij de interviews wordt verwezen naar de protocols[^6] [^7] en rapporten[^8] [^9].
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/dabddc06-f363-4db2-87e4-13b98e4c8909" alt="Feasibility/Desireability canvas">
  <br>
  <em>Figuur 2: Feasibility/Desireability canvas</em>
</p>


### Conclusies & implicaties
Na het gedane onderzoek kunnen verschillende conclusies getrokken worden die van belang zijn voor het project. Zo zal ons product de beste features van de concurrerende producten moeten integreren en zal de prijs rond de 300 euro moeten bedragen om competitief te zijn. De interviews en de competitor analysis onderstrepen dat het personaliseren van de feedback en de compatibiliteit met een sporthorloge een paar van dé belangrijkste eisen zijn. 

## Definition

### Doestellingen
Vervolgens gaan we opzoek naar een antwoord op de vraag “Wat is de oplossing?”. Hierbij leggen we opnieuw de nadruk op de wearable, die essentieel is voor een optimale werking van de app. Dit onderdeel van het product is bewust gekozen omdat alles valt of staat met het correct dragen van de sensor. Wanneer de sensor niet correct op het scheenbeen is bevestigd, kunnen de gemeten waarden sterk afwijken van de werkelijkheid. Dit is niet alleen van belang voor de gebruiker maar ook voor de kinesitherapeut die het platform zal gebruiken om de patiënt optimaal op te volgen tijdens het revalidatietraject. De kinesisten geven aan het systeem alleen te zullen gebruiken wanneer ze de garantie krijgen dat de meetwaarden betrouwbaar zijn.

### Materiaal & methoden
Wanneer gekeken wordt naar hoe de sensor optimaal op het scheenbeen bevestigd wordt is alles terug te brengen naar wrijvingskracht. De wrijvingskracht zal bepalen vanaf welke impact de sensor zich verplaatst ten opzichte van zijn originele positie, wat resulteert in een grotere foutmarge in de metingen.

Deze wrijvingskracht kunnen we zoals de formule het beschrijft opsplitsen in 2 factoren, de statische wrijvingsconstante en de normaalkracht. 

F_w = μ_s ∙ F_N      (1)

De statische wrijvingsconstante verwijst naar de wrijving tussen de band en de huid. De normaalkracht duidt op de kracht die de band en sensor uitoefenen op het been, met andere woorden, hoe hard de band spant.

#### De statische wrijvingsconstante
Bij een lage wrijvingsconstante tussen de band en de huid zal de sensor zich teveel verplaatsen en zullen de gemeten waarden dus niet betrouwbaar zijn. Daarom is getest met een rubberen inleg die deze wrijving moet verhogen.
De test is geïnspireerd op een bestaand testprotocol[^10].
Test protocol:
15cm band wordt telkens op de rand van een bureau gelegd en belast met een gewicht van 750g, aan het andere uiteinde wordt een emmer bevestigd. 2 types band (figuur 4) worden getest: 

-	Een klassieke rekker 
-	Een rekker met rubberen inleg
De emmer wordt stillaan met water gevuld en wanneer het gewicht begint te schuiven wordt de massa van de gevulde emmer gewogen.
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/dae28c56-c7ed-4500-9323-058267db410d" alt="testopstelling">
  <br>
  <em>Figuur 3: Testopstelling</em>
</p>
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/3f85cad2-4338-4d29-af52-e26577fb25eb" alt="rekkers">
  <br>
  <em>Figuur 4: Rekkers</em>
</p>

#### De normaalkracht/spanning
De spanning van de band bepaalt ook in zeer grote mate of de sensor op zijn plaats blijft zitten. De rekker kan te weinig aangespannen worden, waardoor de sensor afzakt. Maar de rekker kan ook te veel aangespannen worden, waardoor de bloedtoevoer naar de enkel kan worden afgesneden. Dit verhoogt de kans op blessures door een tekort aan bloed in de voetspieren.

De moeilijkheid bij de normaalkracht is dat elke gebruiker de band op juiste spanning moet kunnen brengen. Er dient een systeem te worden ontwikkeld dat voor de gebruiker intuïtief en makkelijk te hanteren is. 
3 systemen werden getest bij gebruikers:

-	**Een systeem zonder feedback (benchmark):**
  Hierbij krijgt de gebruiker geen feedback over hoe strak hij of zij de band aantrekt, maar hij/zij moet zelf bepalen wanneer deze volgens hen voldoende strak is aangespannen. Door middel van een druksensor wordt echter wel gemeten welke druk de sensor op het been uitoefent. Op deze manier kan een beeld worden geschetst van hoe continu de gebruiker deze band aanspant, maar ook hoe dicht de gebruiker op intuïtieve wijze bij de ideale spanning komt.

<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/6b637c24-7385-40c5-9ee5-10cae6c3f5e4" alt="systeem zonder feedback">
  <br>
  <em>Figuur 5: Systeem zonder feedback</em>
</p>

- **Een systeem met analoge feedback:**
    Hiervoor werd een nieuw concept ontwikkeld dat werkt aan de hand van 2 indicatielijnen op de band. Over de band wordt een plaatje geschoven met 2 gleuven in, het is de bedoeling dat men de band verder aanspant tot de 2 indicatielijnen (in het rood weergegeven) overeenkomen met de voorziene gleuven. Wanneer de lijnen niet overeenkomen met de gleuven zal de band ofwel te zacht of te hard aangespannen zijn.

<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/35908880-1f2a-4017-9296-4df3b95212ad" alt="systeem met analoge feedback">
  <br>
  <em>Figuur 6: Systeem met analoge feedback</em>
</p>

 - **Een systeem met digitale feedback:**
    De druksensor die ook gebruikt wordt bij de testen zonder feedback zal hier opnieuw gebruikt worden, maar die zal deze keer ook feedback geven. Aan de hand van een RGB-led kan de gebruiker zien of hij de band te hard, te zacht of precies op de juiste spanning aanspant.
   
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/7204a64d-3d2c-45b2-b6f5-06ffbe03220d" alt="systeem met digitale feedback">
  <br>
  <em>Figuur 7: Systeem met digitale feedback</em>
</p>

De 3 systemen werden getest volgens het testprotocol[^11].
#### Storyboard
Het is essentieel om dieper in te gaan op de vraag “Wat is de oplossing”. Hiervoor zijn we teruggegaan naar de kern van de zaak: wie is de gebruiker en hoe komt deze terecht bij ons product. 
Uit de prijs van het product en de interviews kunnen we concluderen dat sporters de sensor niet meteen zullen dragen, tenzij ze kampen met blessures. Het verhaal begint meestal met een geblesseerd persoon die bij de kinesitherapeut gaat voor revalidatie. Om het product dus bij de gebruiker te introduceren, zal er gefocust worden op professionals zoals kinesisten. Hieronder is een gebruiksscenario geschetst van het finale concept van dit project door middel van een storyboard. De belangrijkste interacties worden hierin duidelijk.

<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/61964aac-cd24-4505-9779-8328a222ccdd" alt="storyboard">
  <br>
  <em>Figuur 8: Storyboard van het finale concept</em>
</p>

### Resultaten
#### De statische wrijvingsconstante
Bij het vullen van de emmer begon het gewicht te schuiven bij zeer uiteenlopende waarden.
De emmer had een leeggewicht van 384g; omdat ook dit al te zwaar bleek te zijn is er gewerkt met een pennenzak waar steeds meer pennen werden in opgeborgen. 
| ***Concept***  | ***Gewicht (gram)*** |
| ------------- | ------------- |
| **Standaard rekker**  | 188  | Ears |
| **Rekker met rubberen inlay**  | 1198 |
<p align="left">
<em>Tabel 2: resultaten wrijvingstesten</em></p>

Aangezien de normaalkracht F_N in deze opstelling constant is, kan aan de hand van formule 1 afgeleid worden dat de statische wrijvingscoëfficiënt van de rekker met rubberen inleg meer dan 6 keer groter is dan de standaard rekker.
#### De normaalkracht/spanning
Uit de interviews komt de band met digitale feedback bij bijna alle gebruikers als favoriet naar boven. Voornamelijk de duidelijke feedback door middel van kleurcodes scoort goed.
 
Een uitgebreidere analyse van de antwoorden op de interviews is terug te vinden in de reports[^12] [^13] [^14].

### Conclusies & implicaties
#### De statische wrijvingsconstante
Uit de resultaten van de statische wrijvingsconstante test kan zeer duidelijk afgeleid worden dat er moet gekozen worden voor een rekker met rubberen inlay. De wrijvingsconstante is meer dan 6 keer groter dan de standaard rekker en de sensor zal dus veel beter op zijn plaats blijven zitten.
#### De normaalkracht/spanning
Naast de conclusie dat de band met digitale feedback als meest gebruiksvriendelijk wordt ervaren, zijn er nog enkele opmerkelijke bevindingen uit de test naar voren gekomen. Zo bleek dat er bij alle gebruikers een gevoel van ongemak ontstond wanneer ze de band zonder feedback moesten aandoen. De analoge feedback werd door quasi iedereen als onvoldoende duidelijk ervaren. Desondanks werd deze oplossing, vanwege de feedback, beter ervaren dan die zonder feedback.
Een van de gebruikers gaf aan dat de oplossing met de led het beste is; lopers zijn voornamelijk mensen die nog voldoende kunnen zien, maar niet per se mensen met een goed gehoor. 
Dit kan een belangrijk inzicht bieden in andere aspecten van het systeem.
Tenslotte viel ook op dat het steeds opnieuw instellen of aanspannen van de band voor enkele gebruikers te veel moeite was. Zo kwam er een gebruiker op het idee om de band op maat te laten maken. De belangrijkste inzichten werden gedocumenteerd in de design requirements[^15].

## Develop 1
### Doelstellingen
Tijdens de develop fase wordt er een antwoord gezocht op de vraag: 'Hoe moet de oplossing eruit zien?'. Dit gebeurt aan de hand van 3 develop fasen waarbij gefocust wordt op: 'Human Body', 'Human Mind' en 'Human Senses'. Bij developfase 1 wordt er gekeken naar de 'Human Body' en zal er met behulp van gebruikerstesten en een antropometrische analyse gezocht worden naar optimalisaties op vlak van fysieke ergonomie. Tijdens deze fase zullen we testen op de grootte van de wearable en de manier waarop deze gesloten en aangespannen wordt. Op basis van de antwoorden van de gebruikers wordt het ontwerp aangepast en verbeterd.

### Materiaal en methoden
#### Antropometrische analyse
Bij de antropometrische analyse werd er gekeken naar de belangrijkste maten voor het ontwerpen van de wearable. Blijkt dat voor deze challenge enkel de omtrek van het scheenbeen van belang is. Aangezien deze maat niet in de antropometrische databases te vinden was, werd er beslist om de analyse toe te passen op basis van een steekproef in de klas waarbij de omtrek van het scheenbeen werd gemeten. De steekproef bestond uit een groep van 24 mensen tussen 19 en 22 jaar, waarvan de mannen in de overgrote meerderheid waren. De meest geschikte ontwerpstrategie (design for x) wordt bepaald en op basis van de data-analyse worden er ontwerpbeslissingen gemaakt.

#### Gebruikerstesten
Verder zijn er bij 4 personen gebruikerstesten (n=4) uitgevoerd met als doel het optimaliseren van de fysieke ergonomie. De focus bij deze testen lag op de manier van aanspannen van de wearable en het sluiten ervan. Er zijn hiervoor 3 prototypes gemaakt elk met verschillende sluit- en spansystemen. Link naar protocol[^16].

Er is een prototype gemaakt met een gesloten band en een gesp om deze aan te spannen, deze is van een skihandschoen afgeknipt.
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/30604347-47d8-46aa-bc02-0bfd5bae2f61" alt="prototype gesp">
  <br>
  <em>Figuur 9: Prototype gesp</em>
</p>
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/aab1e746-de94-40ee-a95f-d65402061866" alt="skihandschoen">
  <br>
  <em>Figuur 10: Skihandschoen waarvan de gesp afkomstig is</em>
</p>

Er is een prototype waarvan er een stuk van een hartslagmeter is afgeknipt, deze kan aangespannen worden met een dubbele riem. De band wordt geopend en gesloten met een haakje dat er aangenaaid is, hierdoor moet de maat slechts 1 keer ingesteld worden en kan deze daarna telkens geopend en gesloten worden met het haakje. 
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/30868aa8-1f01-4312-bf85-ee25e97a2246" alt="prototype haakje en dubbele riem">
  <br>
  <em>Figuur 11: Prototype met haakje en dubbeke riem</em>
</p>
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/b1c8dca9-73f6-4e5c-9dce-15a1f04862fa" alt="hartslagmeter">
  <br>
  <em>Figuur 12: Hartslagmeter waarvan het prototype afkomstig is</em>
</p>

Tot slot is er een prototype waarbij gebruikgemaakt wordt van een BOA-sluiting. De BOA-sluiting is afgeknipt van een oud paar fietsschoenen en deze werden vastgenaaid op een lintje stof zodat er een gesloten band gevormd wordt.
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/1632cb5e-898a-4c37-8f76-6f68a4099b88" alt="prototype met boa sluiting">
  <br>
  <em>Figuur 13: Prototype met BOA-sluiting</em>
</p>
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/92a3b5d5-4f61-482c-8ca9-6c7bdbef7f4d" alt="fietsschoen">
  <br>
  <em>Figuur 14: Fietsschoen waarvan de BOA-sluiting afkomstig is</em>
</p>


### Resultaten
#### Antropometrische analyse
Op basis van de resultaten van de steekproef is er gekozen voor volgende designstrategie: design for the tall. Uit de steekproef is gebleken dat de gemiddelde omtrek van het scheenbeen 22,86cm is met een standaardafwijking van 2,17cm. De lengte van de band zal reiken tot P95, en dan aanpasbaar zijn voor elke gebruiker. Hierdoor is ons product voor een groot deel van de bevolking toegankelijk maar worden de extreme hoge waarden uitgesloten om kosten en verliezen te besparen. De lengte van de band zal dus maximaal 26,43cm zijn, deze zal aanpasbaar zijn en kan dus voor alle gebruikers met een scheenbeenomtrek kleiner of gelijk aan 26,43cm gebruikt worden. Link naar analyse van de steekproef[^17].

#### Gebruikerstesten
Uit de gebruikerstesten zijn verschillende dingen duidelijk geworden op basis van de feedback van de gebruikers. Eerst en vooral ging de voorkeur qua vormgeving naar de wearable met haakje en dubbele riem, maar de andere twee wearables waren meer quick & dirty waardoor we kritisch moeten staan tegenover deze feedback.
Hoe ze de wearables moesten sluiten kon op twee manieren, er is enerzijds het prototype met het haakje en anderzijds de twee prototypes waarbij je de wearable rond je voet moet doen om deze te kunnen bevestigen aan je scheenbeen. De gebruikers waren het unaniem eens over de manier van aandoen en kozen resoluut voor de optie met het haakje. Deze feature zal dus absoluut geïntegreerd worden in ons product. Tot slot werd de manier van aanspannen getest, hier waren er 3 verschillende opties. Bij de wearable met gesp bleek de manier van aanspannen redelijk goed maar een groot nadeel is de overblijvende stof die bengelt aan het been van de gebruiker. Bij de wearable met de dubbele riem verliep het aanspannen stroef en onhandig, ook is het niet zo duidelijk hoe er moet aangespannen worden en hoe deze losser kan. Tot slot werden de meeste problemen ondervonden bij de wearable met de BOA-sluiting. Ten eerste was het niet duidelijk dat er op het knopje moest geduwd worden om de sluiting toe te draaien, eens dat duidelijk was ging het aanspannen met het wieltje wel vrij vlot. Hierbij bleek het moeilijk om de wearable goed vast te houden terwijl er gedraaid wordt aan het wieltje. Tenslotte sneden de draadjes van de BOA-sluiting in het been van de gebruikers wat absoluut niet gewenst is. Link naar reports van gebruikerstesten[^18] [^19] [^20] [^21].

### Conclusies en implicaties
Uit deze antropometrische analyse en gebruikerstesten kunnen meerdere conclusies getrokken worden om het product te optimaliseren. Enerzijds is er beslist om de 'design for the tall' designstrategie toe te passen en een band van 26,43cm te voorzien die vervolgens aanpasbaar is. Hierdoor is het product voor 95% van de bevolking toegankelijk.
Anderzijds kan er uit de gebruikerstesten geconcludeerd worden dat er geen ideale manier van aanspannen is, de BOA-sluiting en de gesp kwamen wel naar voren als favoriet. Door de toevoeging van het haakje kan de gebruiker zijn op maat gemaakte band openen en sluiten zonder dat hij/zij daarbij zijn schoenen moet uitdoen. De design requirements worden gedocumenteerd en zijn te vinden via volgende link[^15].

## Develop 2
### Doelstellingen
Uit eerdere gebruikerstesten bleek dat veel gebruikers twijfelen of ze wel de tijd zullen nemen om de band correct aan te spannen. Bovendien geeft de gebruiker aan zijn eigen gevoel meer te vertrouwen dan de digitale feedback met betrekking tot de spanning. Na een gesprek met medewerkers van Comate en Niko is uiteindelijk besloten dat het aanbrengen van de juiste spanning in de band niet langer door de gebruiker zelf kan worden gedaan, maar door een professional, zoals een kinesitherapeut of podoloog. De focus ligt vanaf nu op het vinden van een systeem dat eenvoudig te gebruiken is door professionals. De design requirements zullen dus deels aangepast moeten worden naar de eisen en wensen van deze professionelen.

### Materiaal en methoden
Voordat een dergelijk systeem kan worden ontworpen, moeten de eisen en wensen van de professionals duidelijk worden vastgesteld. De Orde der artsen schrijft in hoofdstuk 4, artikel 34 dat artsen geen medicatie mogen produceren noch medicatie mogen verkoop aan patiënten(Orde der artsen, 2018)[^22]. Deze regel geldt ook voor kinesitherapeuten, wat ervoor zorgt dat iedere band volledig herbruikbaar moet zijn. De band zal dus wasbaar en aanpasbaar moeten zijn. Vooraf gedefinieerde design requirements[^15] blijven uiteraard gelden.

Met het gerealiseerde prototype zal een expertinterview worden gehouden waarbij professionals enkele vragen zullen worden gesteld De experten zullen punten moeten toekennen aan vooraf gedefinieerde heuristieken. Tenslotte zullen usability testen plaatsvinden om de bevindingen van de expertinterviews te bevestigen en verder inzicht te verschaffen in het systeem en wat de gebruiker ervan vindt. Link naar protocol expert review[^23]. Link naar protocol usability testen[^24].  

#### Prototype
Zoals in figuur 15 weergegeven, bestaat het nieuwe prototype uit verschillende onderdelen met verschillende fuctionaliteiten.
1.	De rekker met lus: in de rekker met rubberen inleg (hier niet zichtbaar) is een lus gemaakt zodat deze eenvoudig rondom het haakje kan glijden.
2.	De clip: Rondom de rekker is een clip geplaatst om het overtollige deel rekker aan vast te maken. Zo hangt dit niet te bengelen tijdens het lopen.
3.	De sensor houder: In de sensorhouder kan zoals het woord het zegt de sensor geplaatst worden, daarnaast is deze ook voorzien van een haakje (5) en een systeem die de band vast knelt.
4.	De spanner: de spanner is een plaatje dat de band tegen de sensorhouder aandrukt waardoor deze niet meer kan verplaatsen, door het plaatje opnieuw te verwijderen is de band opnieuw instelbaar.
5.	Het haakje
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/9869f205-32c7-4d59-8dcf-4fee78757a41" alt="Prototype develop 2">
  <br>
  <em>Figuur 15: Prototype develop 2</em>
</p>

#### Gebruiksprotocol
Dit is het protocol dat de professional moet volgen om de band correct op maat van de gebruiker in te stellen. Naast de band is hiervoor een dummy van de sensor nodig, waarin de druksensor past. Zoals eerder beschreven, geeft deze sensor feedback met behulp van een RGB-led en dit keer ook met een grafiek.

<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/bb74dd45-0d3a-4151-8bc1-4f0552214197" alt="Sensordummy">
  <br>
  <em>Figuur 16: Sensordummy met boven- en bodemplaatje waar de druksensor in bevestigd wordt</em>
</p>

**Stap 1: Aanspannen**
Plaats de band rond het been van de patiënt op ongeveer 10cm boven de enkel. Span de rekker aan tot de RGB-led groen gaat branden, doe dit met de dummy en de sensor in de sensor houder maar zonder de spanner zodat de band instelbaar is.

**Stap 2: Voorlopig bevestigen**
Maak de band los door middel van het haakje terwijl je de rekker op de juiste lengte houdt. Verwijder de dummy en schuif de spanner op zijn plaats, vervolgens plaats je de dummy terug in de houder.

**Stap 3: Looptest**
Laat de patiënt 2 tot 5 min lopen en controleer of de waarden op de grafiek niet te danig veel afwijken. Dit kan van patiënt tot patiënt verschillen. Indien de waarden te veel uitwijken kan de band bijgeregeld worden of dichter naar de enkel toe verplaatst worden.

**Stap 4: Definitief bevestigen** 
Wanneer de sensor correct is aangespannen verwijderen we de dummy en plaatsen we de echte sensor in de plaats, de spanner mag indien deze reeds op zijn plaats zit blijven zitten.

De begeleide filmpjes voor al deze stappen zijn terug te vinden via volgende link: https://youtu.be/KHiOjnsXP4o.
Het STL-files van de volledige wearable en dummy zijn terug te vinden via deze link[^25].


#### Expert review
Om de gebruiksprocedure te controleren werden twee kinesisten geïnterviewd. Link naar protocol[^23].
Deze experts moesten bij afloop punten geven op volgende heuristieken:
-	**Visibility and System Status:** Hoe duidelijk is de feedback van het systeem uit?
-	**Error Prevention:** Hoe makkelijk kan je fouten maken bij het gebruiken van dit systeem?
-	**Recognition Rather then Recal:** Hoe goed wijst het system zichzelf uit?
-	**System reliability:** Hoe betrouwbaar is dit systeem
-	**Reusability:** Hoe herbruikbaar is dit systeem?
-	**Help and Documentation:** Wat vindt u van de documentatie die erbij is?

#### Usability tests
Ook werden 4 testpersonen aan een usability test onderworpen. Deze 4 personen hebben niet de vooropleiding zoals dit bij de experten wel het geval was. Op die manier kunnen zij extra inzicht geven in het ontwerp en mogelijks bevindingen bevestigen die reeds naar boven kwamen in de expertinterviews. Link naar protocol[^24].

### Resultaten
#### Expert review
Het antwoorden van de expertinterviews zijn terug te vinden via volgende links[^26] [^27].
De 2 experten quoteerden de heuristieken als volgt:
| ***Heuristics***  | ***Expert 1*** | ***Expert 2*** |
| ------------- | ------------- | ----------- | 
| **Visibility & system status**  | 8  | 9 |
| **Error Prevention**  | 7  | 8 |
| **Recognition Rather Than Recall**  | 7  | 5 |
| **System Reliability**  | 7 | / Testen nodig |
| **Reusability**  | 10 | 8 |
| **Help & Documentation** | 6 | 3 | 
<p align="left">
<em>Tabel 3: resultaten scores op heuristieken door experten</em></p>

#### Usability tests
De resultaten van de usabilty tests zijn terug te vinden via deze links[^28] [^29] [^30] [^31].

### Conclusies en implicaties
#### Expert review
Uit de expertinterviews vallen enkele sterke en zwakke punten af te leiden. Globaal gezien zijn de experten zeer enthousiast over het systeem en dan vooral over de feedback en de werking. De vooraf gemaakte assumpties dat een looptest nodig zou zijn om de correcte spanning op de band te verifiëren bevestigden ze met klem. 
Echter was de werking van hoe de band in elkaar zat niet erg duidelijk en al zeker niet vanop het eerste zicht. Specifiek de sensorhouder en de spanner bleken zichzelf niet uit te wijzen. Deze bevinding kan positief en negatief geïnterpreteerd worden, enerzijds moet de kinesitherapeut wel de werking inzien om het systeem te kunnen gebruiken, anderzijds is het niet de bedoeling dat de gebruiker het systeem nog aanpast nadat de kinesist deze op maat maakte. 
Daarnaast gaven ze ook nog enkele tips om het systeem gebruiksvriendelijker te maken, bijvoorbeeld een grip punt op de spanner en een lipje aan de band om het eenvoudiger door de gleuf van de sensorhouder te trekken.

#### Usability tests
Uit de usability tests kwamen min of meer dezelfde conclusies, ook hier werd gewezen op het gebruiksvriendelijker maken van de spanner en de band. Ook voor hen wees het systeem zichzelf niet uit, wat we zoals eerder vermeld op 2 manieren kunnen interpreteren. Net als bij de experten waren ook deze gebruikers wel aangenaam verrast over de functionaliteit van het systeem.

## Develop 3
### Doelstellingen
De laatste developfase, developfase 3, draait rond 'Human Senses'. Er wordt naar manieren gezocht om de interacties van de gebruiker met het product te optimaliseren. Dit wordt gedaan aan de hand van een hiërarchische taakanalyse en gebruikerstesten. Uit deze analyses zullen opnieuw design requirements worden Het resultaat is een geoptimaliseerd ontwerp op vlak van de sensoriële ergonomie. Aangezien dit de laatste fase van het proces is, zal dit ook het finale ontwerp zijn.
### Materiaal en methoden
#### Hiërarchische taakanalyse
Vooraleer er getest wordt met gebruikers wordt er een hiërarchische taakanalyse van het product opgesteld. Een gebruikersdoel wordt onderverdeeld in subdoelen en deze subdoelen worden verder onderverdeeld in subtaken. Binnen dit project zijn er meerdere gebruikersdoelen, zo is er het uitvoeren van de drukmeting door een professional, het gebruik van de app om feedback te krijgen tijdens de drukmeting, het assembleren van de wearable indien deze moet gewassen worden en het aandoen van de wearable door de loper. Het valt op dat vooral bij het uitvoeren van de drukmeting heel wat stappen nodig zijn om het doel te bereiken. Om problemen te voorkomen is er een instructievideo voorzien in de app, deze kan gevonden worden door rechtsboven op het hulpicoontje te klikken. In de app zelf zijn er ook een aantal stappen te voltooien voordat de drukmeting kan worden uitgevoerd. Deze stappen kunnen worden aangepast, afhankelijk van de feedback uit de gebruikerstesten. De interacties in de app zijn voornamelijk tactiel, waarbij de gebruiker op het scherm klikt, en visueel, waarbij feedback en knoppen worden geïdentificeerd. Omdat de loper alleen de wearable met het haakje hoeft vast te maken, zijn de stappen die nodig zijn om het gebruikersdoel te bereiken, namelijk het aandoen van de wearable, zeer beperkt. Tijdens de gebruikerstesten zullen gebruikers proberen om deze doelen te bereiken en zal er gekeken worden welke interacties verbeterd moeten worden. Na de optimalisaties worden opnieuw hiërarchische taakanalyses opgesteld.
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/f4c53788-db25-408c-b722-3f71346d1d64" alt="HTA drukmeting">
  <br>
  <em>Figuur 17: Hiërarchische taakanalyse voor uitvoeren van de drukmeting</em>
</p>
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/f0531c73-ba43-4b68-8069-c12b32b2f757" alt="HTA app">
  <br>
  <em>Figuur 18: Hiërarchische taakanalyse voor het gebruik van de app</em>
</p>
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/9a260716-1da1-42e7-8954-5718ee1138b4" alt="HTA assembleren van de wearable">
  <br>
  <em>Figuur 19: Hiërarchische taakanalyse voor het assembleren van de wearable</em>
</p>
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/327d803e-951f-4094-b401-37d327577068" alt="HTA voor loper">
  <br>
  <em>Figuur 20: Hiërarchische taakanalyse voor de loper</em>
</p>

#### Gebruikerstesten
De gebruikerstesten (n=4) worden uitgevoerd aan de hand van volgend protocol [^32]. Zoals gezegd zullen de gebruikers worden gevraagd om verschillende gebruikersdoelen te bereiken. Op deze manier doorlopen ze een user-journey en kan worden gezien welke interacties ze uitvoeren. Er wordt gevraagd hoe ze de wearable moeten assembleren, hoe ze de drukmeting uitvoeren en hoe ze de wearable moeten aandoen. Het prototype waarmee getest wordt, is een medium fidelity prototype. Dit is hetzelfde prototype als bij developfase 2. Een toevoeging aan dit prototype is het gebruik van de app om de feedback van de drukmeting weer te geven. Op het scherm zijn bolletjes te zien; centraal staat een grote groene bol, met links en rechts steeds kleiner wordende bolletjes. Hoe verder de bolletjes van de groene centrale bol afstaan, hoe verder de gebruiker is van het bereiken van de juiste spanning. Lichten de bolletjes links van de groene bol op, dan zit de wearable te los. Lichten ze rechts op, dan zit de wearable te strak. Zodra het groene bolletje oplicht, is de perfecte spanning bereikt. Momenteel wordt het veranderen van de bolletjes fictief gedaan door de interviewer, door de slider te verslepen. In de toekomst is het uiteraard de bedoeling dat de bolletjes effectief overeenkomen met de metingen van de drukmeter. In deze eerste versie van de app wordt ook de grafiek van de drukmeting weergegeven. Deze kan door de professional worden gebruikt om tijdens de looptest te zien hoeveel de spanning afwijkt van de perfecte spanning. Op die manier kan de spanning van de band eventueel nog worden aangepast. In een volgende versie zal de grafiek alleen op het computerscherm van de professional te zien zijn.

### Resultaten
#### Hiërarchische taakanalyse
Er zijn verschillende aanpassingen gedaan aan de HTA's om de interacties te optimaliseren en de user-journey te vereenvoudigen. Bij het uitvoeren van de drukmeting is ervoor gekozen om de drukmeter te bevestigen in het bovenplaatje.
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/4e9e9a46-44ec-46ad-a613-067be31e4635" alt="bovenplaatje met drukmeter">
  <br>
  <em>Figuur 21: Bovenplaatje met drukmeter erin bevestigd</em>
</p>
Hierdoor is er een subdoel minder voor de gebruiker en dus ook minder stappen waarop de gebruiker fouten kan maken. Doordat de pinnen op de achterkant van het bodemplaatje te lang zijn, moet de gebruiker tijdens het fixeren van de band deze eerst losmaken van het been, het bodemplaatje verwijderen en dan pas de band fixeren. Dit werd geoptimaliseerd door de pinnen korter te maken, zodat de band gefixeerd kan worden terwijl deze nog rond het scheenbeen zit. 
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/d26503ff-b6f6-4dbf-9638-872c7b857ac6" alt="bodemplaatje">
  <br>
  <em>Figuur 22: Bodemplaatje met kortere pinnen</em>
</p>
Deze aanpassing heeft ook een impact op de HTA van het gebruik van de app. Verder werden er nog aanpassingen doorgevoerd in de app, waardoor de gebruiker sneller naar de gewenste scene kan navigeren om de drukmeting uit te voeren. De knoppen 'connect sensor' en 'wearable calibration' zijn vervangen door een 'start drukmeting' knop op het hoofdscherm, wat het eveneens duidelijker maakt voor de gebruiker. Tot slot is ook de aanduiding voor de instructievideo aangepast. Tijdens de gebruikerstesten bleek het niet meteen duidelijk waar deze video te vinden was. Nu wordt deze nadrukkelijk weergegeven op het scherm van de scene voor de drukmeting (link naar eerste versie van de app: https://youtube.com/shorts/jntpQ0VLZdQ?feature=share) (link naar verbeterde versie van de app: https://youtube.com/shorts/CEbw54Z8cdw).
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/c232053c-5818-4144-ad95-a4ef5824c2ff" alt="verbeterde HTA voor drukmeting">
  <br>
  <em>Figuur 23: Verbeterde HTA voor het uitvoeren van de drukmeting</em>
</p>
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/b49f5376-1454-4dae-a2ca-617d0e7504b9" alt="verbeterde HTA voor app">
  <br>
  <em>Figuur 24: Verbeterde HTA voor het gebruik van de app</em>
</p>

#### Gebruikerstesten
Uit de gebruikerstesten bleek opnieuw dat het voor de gebruikers niet duidelijk is hoe de wearable in elkaar zit. Vooral het inbrengen van de band in de sensorhouder blijkt een knelpunt te zijn. Daarom werden er bij de tweede iteratie pijltjes toegevoegd die de montage verduidelijken.
<p align="center">
  <img src="https://github.com/RUBRIM2000/UCD_SEM1/assets/125655509/c84f7ee7-7a3a-4d1f-a216-645478c32bfd" alt="prototype met pijltjes">
  <br>
  <em>Figuur 25: Prototype met pijltjes</em>
</p>

Dit prototype is getest bij de laatste gebruiker, die bevestigde dat het de montage duidelijker maakte [^36]. Bij de eerste drie gebruikers werd de eerste versie van de app getest, terwijl de nieuwste versie werd getest bij de laatste gebruiker. Deze laatste kon bevestigen dat dankzij de duidelijkere instructievideo het uitvoeren van de drukmeting geen probleem vormde. Tenslotte bleek dat de feedback van de drukmeting zeer duidelijk was en geen aanpassingen meer nodig had. Reports van deze gebruikerstesten[^33] [^34] [^35] [^36].

### Conclusies en implicaties
Uit de taakanalyses en gebruikerstesten kwamen meerdere verbeterpunten naar voren, zoals duidelijkere instructies en het vereenvoudigen van sommige interacties. De toevoeging van de pijltjes aan de sensorhouder en het verkorten van de pinnen van het bodemplaatje zijn implicaties op de wearable, hierdoor werd het gebruik duidelijker en eenvoudiger. In de app werden vooral de interacties vereenvoudigd en de instructievideo duidelijker weergegeven. Tot slot werden de design requirements gedocumenteerd [^15].

## Algemene conclusie
Door vele testen en interviews met zowel professionelen als gebruikers kan een werkend eindproduct afgeleverd worden. De band die ontwikkeld werd voor de sensor van Ontracx kan gezien worden als een sterke aanvulling op het bestaand concept. De sensorband creëert de mogelijkheid om de sensor correct en met de juiste spanning te dragen, hierdoor zullen steeds de correcte sensorwaarden uitgelezen worden. Desondanks hier een sterk product beschreven wordt, zijn er wel nog heel wat mogelijkheden om het product te optimaliseren. Zo zou het een grote meerwaarde zijn om de druksensor in de toekomst in de sensor te integreren, op die manier kan de gebruiker zelf de sensor aanspannen en worden de waarden ook steeds gecheckt. Nu werd een band gebruikt om aan de design requirements te voldoen, maar in de toekomst kan mogelijks ook met kinesiotape gewerkt worden om de sensor te bevestigen. 
Kortom kan besloten worden dat deze wearable een sterke aanvulling is voor het product, maar dat de mogelijkheden niet eindigen bij hetgeen in dit rapport beschreven staat. 

## Bill of materials
Het fysiek uitwerken van prototypes zal vooral gebeuren bij de uitwerking van de wearable. Hiervoor werden volgende materialen gebruikt:

- **PLA**: kunststof gebruikt voor het 3D printen van prototypes

- **TPU**: elastogeen gebruikt voor het 3D pinten van prototypes

- **Polyester**: een textielsoort die werd gebruikt bij het prototypen van een band.

- **Nylon**: textiel dat verwerkt zit in een band voor rond het been. 


## Kritische reflectie
We kijken voornamelijk met een positief gevoel terug op dit project. We hebben een aantal keer ons concept volledig omgegooid en zo goed als helemaal opnieuw begonnen. Hierdoor hebben we ons snel moeten aanpassen aan de nieuwe eisen en wensen. Dit zorgde voor de nodige uitdagingen. Na de concept pitch werden we als groep samengesteld. Hierbij bleek meteen dat we dezelfde visie hadden op waar de problemen lagen en hoe deze op te lossen. Aan de hand van een constructieve brainstorm die vooraf reeds beschreven werd konden we aan de slag met het prototypen. Na de tussentijdse verdediging kregen we te horen dat we met teveel zaken tegelijk bezig waren waardoor deze te weinig uitgewerkt en onderbouwd waren. We besloten om ons daarna te focussen op de wearable en proberen om deze zo gebruiksvriendelijk mogelijk te maken voor de loper.

Bij developfase 1 zijn 3 verschillende manieren van aandoen en aanspannen getest met prototypes. Sommige hiervan waren beter uitgewerkt dan andere, waardoor we kritisch moesten zijn ten opzichte van de resultaten. Het had misschien beter geweest om prototypes van dezelfde kwaliteit te testen om zo invloed van kwaliteit te verminderen. Bij het zoeken naar oplossingen voor de wearable werd duidelijk dat sommige gebruikers niet goed weten wanneer ze de juiste spanning bereikten. Daardoor werd gezocht naar manieren om die spanning een indicatie te geven zodat de gebruiker feedback krijgt. Ook waren sommige lopers niet zeker of ze wel de tijd willen nemen om voor elke activiteit de band correct aan te spannen. Hierdoor twijfelden we of we ons zouden focussen op de loper of een professional die de band op maat maakt. Na een gesprek met de bedrijfsmensen (Comate & Niko) werd duidelijk dat we ons best op focussen op de professionals omdat een gebruiker ook heel veel waarde hecht aan de expertise van zo'n professional. Dit zorgde voor een tweede pivot point in ons proces, vanaf dan moesten we ons focussen op het ontwikkelen van een systeem dat eenvoudig te gebruiken is voor professionals. Hier hebben we onmiddellijk op proberen inspelen door de expert reviews af te nemen bij kinesisten in plaats van medestudenten.

Uiteindelijk zijn we wel tevreden over het finale resultaat, de wearable met drukmeting en bijhorende app voor feedback zijn een mooi resultaat van een iteratief traject. Omdat we zo laat tot de conclusie kwamen dat we ons gingen focussen op de professionals is het finale prototype misschien niet zo ver uitgewerkt als bij andere groepen. Maar het toont wel dat we gebruiksgericht en iteratief gewerkt hebben en op basis van de feedback van gebruikers gezocht hebben naar oplossingen voor een specifiek probleem binnen het OnTracx project. In de toekomst zou de drukmeting kunnen verwerkt worden in de sensor die de belasting meet en zou de gebruiker een kalibratie kunnen doen alvorens die gaat lopen om te checken of de juiste spanning nog geldig is. Dit zijn uiteraard zaken waarover OnTracx zelf moet beslissen maar voor dit project zijn we tevreden met wat we bereikt hebben.


## Bronnen
- De Mey, K. (2023). Wat is OnTracx. [PowerPoint slides]. Gepresenteerd tijdens de meeting in de les, Kortijk, België.
- Etienne, S. (2018, 22 september). Soul Run Free Pro Bio Review: A running coach in your headphones. The Verge. Geraadpleegd op 6 november 2023, van https://www.theverge.com/2018/9/22/17886692/soul-run-free-pro-bio-earbuds-review 
- Molina, A. (2019, 15 april). Soul Electronics Run Free Pro Bio review - SoundGuys. SoundGuys. Geraadpleegd op 6 november 2023, van https://www.soundguys.com/soul-run-free-pro-bio-review-21587/ 
- Garmin. (z.d.). Hardloopdynamieksensor | Garmin. Garmin. Geraadpleegd op 6 november 2023, van https://www.garmin.com/nl-BE/p/561205 
- Home | ARION. (z.d.). Geraadpleegd op 6 november 2023, van https://www.arion.run/- Stryd | Run with Power | Stryd (Europe). (z.d.). Stryd (Europe). Geraadpleegd op 6 november 2023, van https://www.stryd.com/eu/en 
- von Waldthausen, D. (2020, 22 januari). RUNVI - YOUR ADVANCED DIGITAL RUNNING COACH. Kickstarter. Geraadpleegd op 6 november 2023, van https://www.kickstarter.com/projects/runvi/runvi-the-worlds-most-advanced-digital-running-coa
- TICKR X Chest Heart Rate Monitor. (z.d.). Wahoo Fitness. Geraadpleegd op 6 november 2023, van https://eu.wahoofitness.com/devices/heart-rate-monitors/tickr-x-buy 
- RunScribe. (2023, 31 oktober). RunScribe - Wearable IMU - GAIT analysis. Geraadpleegd op 6 november 2023, van https://runscribe.com/ 
- Sensoria home page. (z.d.). Geraadpleegd op 6 november 2023, van https://www.sensoriafitness.com/
- Alger, K. (2018, 21 september). 5 of the best form-fixing gadgets to improve your running efficiency and technique. Runner’s World. Geraadpleegd op 6 november 2023, van https://www.runnersworld.com/uk/a776422/best-form-fixing-gadgets-to-improve-your-running-efficiency-and-technique/ 
- George, L. (2019, 17 oktober). 7 running wearables that will transform the way you move. 20 Fit. Geraadpleegd op 6 november 2023, van https://shapescale.com/blog/fitness-gear/7-running-wearables-transform/
- Orde der artsen. (2018). Artikel 34: Integriteit [Webpagina]. Geraadpleegd op 1 april 2024, van https://ordomedic.be/nl/code2018/integriteit/34#:~:text=Artikel%2034&text=De%20arts%20stelt%20de%20belangen,promoot%20medische%20hulpmiddelen%20of%20gezondheidsproducten.


## Bijlagen
[^1]: De Mey, K. (2023). Wat is OnTracx. [PowerPoint slides]. Gepresenteerd tijdens de meeting in de les, Kortijk, België.
[^2]: Innovatrix: https://drive.google.com/file/d/1MV3y32ipnZEfoEKJDSRju2GLiE1Tqw7x/view?usp=drive_link
[^3]: Brainstorm: https://drive.google.com/file/d/1b5-SRC9vry1JRoN5dqAmx1vkEeve9sD-/view?usp=drive_link
[^4]: protocol competitor analysis: https://drive.google.com/file/d/1wHGh7CsQYgv2biXCs35QFxxe1GM6f_Dv/view?usp=drive_link
[^5]: report competitor analysis: https://drive.google.com/file/d/1jjlTNJBltOpXLYm31RzHXCOjIFAlKGUQ/view?usp=drive_link
[^6]: protocol interview Milan Discovery: https://drive.google.com/file/d/1m1I5E_-V09NOw_wSy9RsEpCx_DURTtM5/view?usp=drive_link
[^7]: protocol interview Ruben Discovery: https://drive.google.com/file/d/1PUERY7WOe_0lMdr5ibPD2JiIq6wNtUD2/view?usp=drive_link
[^8]: report interview Milan Discovery: https://drive.google.com/file/d/1AH3_2Y1O2Cm2qCNJkhiGDWLtq_c95EFd/view?usp=drive_link
[^9]: report interview Ruben Discovery: https://drive.google.com/file/d/17NUr8E6auOlrrevVlJ7KdzkwKCOv1vjS/view?usp=drive_link
[^10]: protocol wrijvingstest Definition: https://drive.google.com/file/d/19jeL0ZEN-83-99ft4u5FwCuxMYfwXHej/view?usp=sharing
[^11]: protocol concepttests Definition: https://drive.google.com/file/d/1IaHkj3sAe9eTu9GQcuiDed8aoEXkItHe/view?usp=sharing
[^12]: report 1 concepttests Definition: https://drive.google.com/file/d/1fSNksWGU855KfythgU_HQNRO4YRoYiyi/view?usp=sharing
[^13]: report 2 concepttests Definition: https://drive.google.com/file/d/1MPmSvX-WhsuCDyhlgZ8NYXPyFp9DhcGU/view?usp=sharing
[^14]: report 3 concepttests Definition: https://drive.google.com/file/d/1IreY5sqx2D4tiUg1gdh6wfR_-qc7Gkrf/view?usp=sharing
[^15]: Design requiremetns: https://docs.google.com/spreadsheets/d/1iGADVxJSK1JoBgBKZvWEBh5SpYmDUdK2/edit?usp=sharing&ouid=104531495302844941125&rtpof=true&sd=true
[^16]: protocol fysieke ergonomie test Develop 1: https://drive.google.com/file/d/17XYh_JO_GjCk8g6aMVpJncWcSUWI1Rpc/view?usp=sharing
[^17]: analyse steekproef Develop 1: https://docs.google.com/spreadsheets/d/1dfp82gCfqAKlyUgWzPSJSQePwe9WFY8h/edit?usp=sharing&ouid=104531495302844941125&rtpof=true&sd=true
[^18]: report 1 fysieke ergonomie test Develop 1: https://drive.google.com/file/d/1YoYJV58Poh1C11cC7PnlUD2nj2j3-C0m/view?usp=sharing
[^19]: report 2 fysieke ergonomie test Develop 1: https://drive.google.com/file/d/1ybBpL4jTeQeP3s6BjhY_ei0IeatBJZhL/view?usp=sharing
[^20]: report 3 fysieke ergonomie test Develop 1: https://drive.google.com/file/d/192tbNJnfO9MCWqrIpPvJbfqYHZ_nhoOO/view?usp=sharing
[^21]: report 4 fysieke ergonomie test Develop 1: https://drive.google.com/file/d/1vhZPG9o-GIXEPIoKeTjllEztJ10_HLHy/view?usp=sharing
[^22]: Orde der artsen. (2018). Artikel 34: Integriteit [Webpagina]. Geraadpleegd op 1 april 2024, van https://ordomedic.be/nl/code2018/integriteit/34#:~:text=Artikel%2034&text=De%20arts%20stelt%20de%20belangen,promoot%20medische%20hulpmiddelen%20of%20gezondheidsproducten.
[^23]: protocol expertreview Develop 2: https://drive.google.com/file/d/1YuBjbtdYMK4UHUx1W5S2uZ0zwaUDNFOf/view?usp=sharing
[^24]: protcol usability testes Develop 2: https://drive.google.com/file/d/1-ePkM79NEO9WDhytGWuOTmqYT1eqnrvM/view?usp=sharing
[^25]: Link naar alle STL-files: https://drive.google.com/drive/folders/1hmEfo-gLLVtM0-jGU2Ee1byHQV_EXLIO?usp=sharing
[^26]: expert review report 1 Develop 2: https://drive.google.com/file/d/13BtOuCHYZ8xK3q9j22VW_-xFYxYlAu64/view?usp=sharing
[^27]: expert review report 2 Develop 2: https://drive.google.com/file/d/1gw7CmEqENKas49DA3ixNHUUo8uNIPy7o/view?usp=sharing
[^28]: usability test report 1 Develop 2: https://drive.google.com/file/d/1QLfKxiJAfwgvhHkpXarFcKco6sy9kOkO/view?usp=sharing
[^29]: usability test report 2 Develop 2: https://drive.google.com/file/d/10T33OEa6xQjv_pdswnFzApR6N_yoeUeW/view?usp=sharing
[^30]: usability test report 3 Develop 2: https://drive.google.com/file/d/1CtInHBVPipVYBwzL3Hb9u6E6JVq6UJcJ/view?usp=sharing
[^31]: usability test report 4 Develop 2: https://drive.google.com/file/d/11mNRkz4ua7i0YyWWFQwfG1j5ncA9AbbR/view?usp=sharing
[^32]: protocol interaction tests Develop 3: https://drive.google.com/file/d/19jSclKmYd-9Yy8LSLiXTgeETT-s-0s7x/view?usp=sharing
[^33]: report 1 interaction test Develop 3: https://drive.google.com/file/d/1OutHTIUTfgsq1Vp5TwZ22oTeyu6AAS0Y/view?usp=sharing
[^34]: report 1 interaction test Develop 3: https://drive.google.com/file/d/1M63ijIzqqOtPc_CfRCGLS9Zi7Ydn_HLx/view?usp=sharing
[^35]: report 1 interaction test Develop 3: https://drive.google.com/file/d/1f8Hrp1Ix5XuOoazNwSqcXMq9xCe8D36O/view?usp=sharing
[^36]: report 1 interaction test Develop 3:

