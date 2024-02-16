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
[^1]: Uit presentatie Kristof de Mey

## Methdologie
Het model dat wordt toegepast tijdens dit project is de ‘triple diamond’ van Zendesk. Dit model bestaat uit vier ontwerpfasen: discover, define, develop en deliver. In dit tussentijds rapport wordt er dieper ingegaan op de eerste twee fasen van het model, namelijk de dicovery en de definition fasen.

### 3.1	Discovery
In de discovery fase zijn we op zoek naar een antwoord op de vraag: ‘Wat is het probleem?’. Er wordt gedivergeerd bij het onderzoeken van het probleem en geconvergeerd bij het definiëren van het probleem. Het uiteindelijke doel is het formuleren van een goede “how can we” waarin de doelgroep en het probleem worden vastgelegd. Om dit te bereiken werden er knowledge templates toegepast en activiteiten uitgevoerd. Een van de templates die uitgevoerd werd, is de innovatrix. Om het probleem te onderzoeken werd er eerst een desktop research en een competitor analysis gedaan om de markt beter te begrijpen. Tot slot werden er user interviews en expert interviews afgenomen om de gebruiker beter te leren kennen. Dit wordt allemaal uitgevoerd door middel van een testing protocol en een rapport achteraf. Een voorbeeld van zo’n testing protocol is een topic guide, die dient om het interview in goede banen te leiden.
Om het probleem te definiëren wordt de informatie die verzameld werd uit de verschillende activiteiten geconvergeerd. De doelgroep wordt bepaald en de belangrijkste inzichten van de gebruikers worden uitgezet in een feasibility/desirability canvas. Uit het marktonderzoek worden de huidige oplossingen en de belangrijkste trends bepaald.
Dit komt allemaal samen in een “how can we” die, zoals gezegd, de doelgroep en het probleem vastlegt.

### 3.2	Definition
Hierna volgt de definition fase waarin een antwoord gezocht wordt op de vraag: Wat is de oplossing?”. Ook hier wordt er gedivergeerd tijdens de ideation fase en geconvergeerd bij het vormgeven van de oplossing. 
Tijdens de ideation fase worden zo veel mogelijk oplossingen en ideeën bedacht. Dit begint bij een in-class ideation waar a.d.h.v. de lotus blossum ideation verschillende deeloplossingen worden bedacht. Daarna werd er een brainstorm gedaan om de belangrijkste inzichten van het individuele discovery onderzoek samen te leggen.
Tijdens het convergeren wordt er een gebruiksscenario verteld met behulp van een storyboard. Er worden low-fidelity prototypes, concept sketches en wireframes gemaakt om de concepten te testen bij de gebruikers. 


## Discovery
### Doestellingen
Er wordt een antwoord gezocht op de vraag: “Wat is het probleem?”. Het probleem wordt onderzocht met behulp van een desktop research en een competitor analysis. Het doel is om een duidelijk beeld schetsen van welke concurrerende oplossingen/producten er momenteel op de markt zijn. Het onderzoek zal uitwijzen wat de beste features zijn van elk product, de nadelen, prijs etc. Hieruit zal duidelijk worden welke features er absoluut moeten toegevoegd worden aan ons eigen product en welke niet. Het doel van de user en expert interviews is om een inzicht te krijgen in de wensen en noden van de gebruikers, de lopers enerzijds en de kinesitherapeut/arts anderzijds. Op basis van de antwoorden kan er beslist worden wie de doelgroep wordt, welke functies de app/dashboard zeker nodig heeft en aan welke design requirements de wearable moet voldoen. Het uiteindelijke doel is het formuleren van een goede “how can we” waarin de doelgroep en het probleem worden vastgelegd.
### Materiaal & methoden
#### 4.2.1	Desktopresearch en competitor analysis
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
- Cons: Elk product heeft ook zijn mindere punten, dit zijn opportuniteiten om je eigen product te differentiëren en te benadrukken wat jouw product beter doet.
- Price: De prijs van concurrerende producten kan deels bepalen hoe je je eigen product prijst, anderzijds kun je een inzicht krijgen in de kostenstructuur en de winstmarges van de concurrentie.

### Resultaten
Rapporteer over de resultaten (incl. foto's, quotes, analyseframeworks, ...)
### Conclusies & implicaties
Definieer de belangrijkste designbeslissingen

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
Max. 500 woorden

## Bronnen
Voeg je volledige bibliografie toe van bronnen naarwaar je verwees.

## Bijlagen
