# SPORTS AND TECH
*Het ontwikkelen van een wearable met behulp van een digitale component voor blessure preventie* 

*Groep 13: Milan Berckmoes; Ruben Rimbaut*

19 - 02 - 2024

## Samenvatting

Afgelopen semester verdiepten we ons in OnTracx, een start-up van UGent die met een innovatief concept op de proppen komt rond het revalideren en voorkomen van loopblessures. We definieerden de probleemstelling en zochten constructief naar oplossingen. In dit tussentijds verslag wordt inzicht gegeven in hoe de tot nu toe gevormde concepten en prototypes tot stand kwamen. Het vooraf gedane onderzoek wordt toegelicht en de gemaakte prototypes verduidelijkt.

## Introductie

Wereldwijd zijn er 110 miljoen lopers, waarvan 50 miljoen last heeft van blessures[^1]. Ondanks de vele oplossingen die diverse merken bieden dalen deze cijfers niet, de oplossing moet dus elders gezocht worden. OnTracx komt met een vernieuwende aanpak waarbij de kern van het probleem, volgens hen, centraal staat: het verminderen van de impact op de botten. OnTracx zette ons al voor een groot deel op weg, maar hier en daar zagen wij toch nog enkele valkuilen. 

Wij zullen ons binnen deze designstudie focussen op het uitwerken van de wearable waarin de sensor verwerkt zit en een app voor het visualiseren van de data. Voor de wearable gaan we opzoek naar allerhande methoden waarmee de sensor aan het scheenbeen bevestigd kan worden. Daarbij is het belangrijk dat de sensor niet kan bewegen en dat we tegelijkertijd de doorbloeding van het been niet afsnijden. Voor een nauwkeurige en betrouwbare meting is het cruciaal dat de sensor correct gedragen wordt en dat de gebruiker deze dus ook zelf op een correcte manier kan aanbrengen.

Voor het visualiseren van de data gaan we opzoek naar een gebruiksvriendelijke applicatie waarbij de focus ligt op het revalidatieproces enerzijds en het gemotiveerd houden van de gebruiker anderzijds. Dit laatste zullen we proberen met behulp van gamificatie zodat de gebruiker steeds een doel heeft om naar toe te werken en zichzelf kan vergelijken met andere gebruikers. Op deze manier proberen we het revalidatieproces dragelijker te maken. 


## Methdologie
Het model dat wordt toegepast tijdens dit project is de ‘triple diamond’ van Zendesk. Dit model bestaat uit vier ontwerpfasen: discover, define, develop en deliver. In dit tussentijds rapport wordt er dieper ingegaan op de eerste twee fasen van het model, namelijk de dicovery en de definition fasen.

### Discovery
In de discovery fase zijn we op zoek naar een antwoord op de vraag: ‘Wat is het probleem?’. Er wordt gedivergeerd bij het onderzoeken van het probleem en geconvergeerd bij het definiëren van het probleem. Het uiteindelijke doel is het formuleren van een goede “how can we” waarin de doelgroep en het probleem worden vastgelegd. Om dit te bereiken werden er knowledge templates toegepast en activiteiten uitgevoerd. Een van de templates die uitgevoerd werd, is de innovatrix. Om het probleem te onderzoeken werd er eerst een desktop research en een competitor analysis gedaan om de markt beter te begrijpen. Tot slot werden er user interviews en expert interviews afgenomen om de gebruiker beter te leren kennen. Dit wordt allemaal uitgevoerd door middel van een testing protocol en een rapport achteraf. Een voorbeeld van zo’n testing protocol is een topic guide, die dient om het interview in goede banen te leiden.
Om het probleem te definiëren wordt de informatie die verzameld werd uit de verschillende activiteiten geconvergeerd. De doelgroep wordt bepaald en de belangrijkste inzichten van de gebruikers worden uitgezet in een feasibility/desirability canvas. Uit het marktonderzoek worden de huidige oplossingen en de belangrijkste trends bepaald.
Dit komt allemaal samen in een “how can we” die, zoals gezegd, de doelgroep en het probleem vastlegt.

### Definition
Hierna volgt de definition fase waarin een antwoord gezocht wordt op de vraag: Wat is de oplossing?”. Ook hier wordt er gedivergeerd tijdens de ideation fase en geconvergeerd bij het vormgeven van de oplossing. 
Tijdens de ideation fase worden zo veel mogelijk oplossingen en ideeën bedacht. Dit begint bij een in-class ideation waar a.d.h.v. de lotus blossum ideation verschillende deeloplossingen worden bedacht. Daarna werd er een brainstorm gedaan om de belangrijkste inzichten van het individuele discovery onderzoek samen te leggen.
Tijdens het convergeren wordt er een gebruiksscenario verteld met behulp van een storyboard. Er worden low-fidelity prototypes, concept sketches en wireframes gemaakt om de concepten te testen bij de gebruikers. 


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
De resultaten van de competitor analysis zijn te zien in tabel 1. We kunnen zien dat de manier van bevestiging vaak verschilt alsook de beste features van de producten. Vier van de zeven producten beschikken over real-time feedback, wat vaak gepaard gaat met het te frequent geven van feedback. Ook moeten deze producten gekoppeld worden aan een sporthorloge of een smartphone om ze te kunnen gebruiken. De prijzen zijn zeer uiteenlopend, gaande van 55 euro voor een product met basisfeatures tot 556 euro voor een product waarbij een analyse in een lab zit inbegrepen. Voor een meer uitgebreide benchmarkanalyse wordt verwezen naar het protocol[^2] en het rapport[^3].

| ***Name***  | ***Product Type*** | ***Mounting*** | ***Best Feature*** | ***Real-time feedback*** | ***App***| ***Cons*** | ***Price (€)*** |
| ------------- | ------------- | ----------- | ---------------- | ------------------------ | ---- | -------- | ------------- |
| **Soul Run Free Bio**  | Lightweight bluetooth headphones  | Ears | Good sound quality | Yes | Yes | Too much interruptions/feedback | 150 |
| **Garmin Running Dynamics Pod**  | Form-tracking pod  | Clipped onto belt of shorts | Long battery life | No | Yes | Needed to pair with Garmin watch | 69 |
| **Arion Smart Soles**  | Smart insole  | In your shoe | Live heatmap visualization of feet striking | Yes | Yes | Too much interruptions/feedback | 261 |
| **Stryd Pod Shoe Clip**  | Shoe clip full of sensors  | Clipped to your shoelaces | Long battery life | No | Yes | Needed to be paired with watch/phone | 269 |
| **Wahoo Tickr Run HRM**  | Heart Rate monitor  | Around your chest | Compatible with running apps | No | No | Very basic running analysis | 55 |
| **Runscribe Shoe Clip** | Shoe clip full of sensors  | Clipped to your shoelaces | A lot of data | Yes | Yes | Expensive | 556 |
| **Sensoria Socks**  | Smart socks  | On your feet | Personalizing your run (feedback,…) | Yes | Yes | Phone needed to view live data | 278 |

#### 4.3.2	User en expertinterviews
Uit de interviews blijkt dat de meeste blessures voorkomen bij recreatieve sporters van boven de 50 jaar. Deze sporters willen te snel en te veel lopen, terwijl ze dit niet meer aankunnen. De huidige behandelingsmethoden beginnen bij hands-on therapie, gevolgd door een rustige opbouw waarbij geluisterd wordt naar het lichaam. Indien er geen klachten zijn, kan de intensiteit verhoogd worden. De opvolging gebeurt bij beide kinesitherapeuten a.d.h.v. een app waar ze gepersonaliseerde oefeningen meegeven met de patiënt. Nadeel is dat er niet gecontroleerd kan worden of de oefening juist is uitgevoerd. De combinatie van subjectieve data en objectieve data (stapgrootte, links-rechts verschil, trunk sway en belasting) is het meest interessant voor de opvolging. Dit zou vooral handig zijn als deze gegevens gestructureerd (in de vorm van grafieken of dergelijke) worden weergegeven in het dashboard en gelinkt zijn aan het patiëntendossier. 
Om de loper gemotiveerd te houden is het delen en het kunnen vergelijken van activiteiten met vrienden een grote meerwaarde, al is de motivatie om een gezonde levensstijl na te streven even belangrijk. De gebruiker gaf aan dat hij voorstander is van een ‘voice coach’ om feedback te geven tijdens het lopen, al moet de frequentie ervan instelbaar zijn. 
Zowel de gebruiker als een van de twee kinesisten gaven aan 300 tot 400 euro te willen betalen voor een product die de belasting meet inclusief de app, zolang dit compatibel is met een sporthorloge.

### Conclusies & implicaties
Na het gedane onderzoek kunnen verschillende conclusies getrokken worden die van belang zijn voor het project. Zo zal ons product de beste features van de concurrerende producten moeten integreren en zal de prijs rond de 300 euro moeten bedragen om competitief te zijn. De interviews en de competitor analysis onderstrepen dat het personaliseren van de feedback en de compatibiliteit met een sporthorloge een paar van dé belangrijkste eisen zijn. 

## Definition
Max. 1000 woorden
### Doestellingen
Wat wilde je bereiken?
### Materiaal & methoden
Hoe onderzocht je dit? Wees volledig.
### Resultaten
Rapporteer over de resultaten (incl. foto's, quotes, analyseframeworks, ...)
### Conclusies & implicaties
Definieer de belangrijkste designbeslissingen

## Bill of materials
- Welk
- Materiaal
- Heb
- Je
- Nu
- Nodig
- Voor
- Je
- Prototype

## Kritische reflectie
Max. 500 woordenn

## Bronnen
Voeg je volledige bibliografie toe van bronnen naarwaar je verwees.

## Bijlagen
[^1]: Uit presentatie Kristof de Mey
[^2]: https://drive.google.com/file/d/1wHGh7CsQYgv2biXCs35QFxxe1GM6f_Dv/view?usp=drive_link
[^3]: https://drive.google.com/file/d/1jjlTNJBltOpXLYm31RzHXCOjIFAlKGUQ/view?usp=drive_link
