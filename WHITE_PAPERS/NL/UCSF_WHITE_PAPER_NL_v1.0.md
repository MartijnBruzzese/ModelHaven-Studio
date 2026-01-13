<a id="inhoudsopgave"></a>
# UCSF — Universal Consent & Safety Framework  
## Academische Nederlandstalige Versie
**Versie:** v1.0  
**Datum:** 12 januari 2026 
**Status:** Publieke white paper – open voor peer review
---

## Inhoudsopgave

0. [Voorwoord](#0-voorwoord)

1. [Waarom UCSF Bestaat](#ch-1)  
   1.1 Structurele schade in digitale systemen  
   1.2 Van incident naar ontwerppatroon  

2. [Consent in Digitale Systemen](#ch-2)  
   2.1 Consent als toestand, niet als handeling  
   2.2 Vrije instemming, herroepbaarheid en afhankelijkheid  
   2.3 Juridische versus ethische legitimiteit  

3. [Veiligheid als Ontwerpverantwoordelijkheid](#ch-3)  
   3.1 Reactieve versus preventieve veiligheid  
   3.2 Voorspelbare schade en ontwerpaansprakelijkheid  

4. [Falen, Herstel en Reparatie](#ch-4)  
   4.1 Onvermijdelijkheid van falen op schaal  
   4.2 Herstel als plicht, niet als gunst  

5. [Macht, Governance en Verantwoordelijkheid](#ch-5)  
   5.1 Platformmacht en besluitvorming  
   5.2 Transparantie, tegenmacht en legitimiteit  

6. [Implementatie zonder Ethische Ontwijking](#ch-6)  
   6.1 Ethiek als randvoorwaarde  
   6.2 Schaalbaarheid versus toelaatbaarheid  

7. [Grenzen en Ethische Weigering](#ch-7)  
   7.1 Normalisering van structurele schade  
   7.2 Niet-bouwen als ethische uitkomst  

8. [Infrastructuur, Materiële Schade en Gedeelde Verantwoordelijkheid](#ch-8)  
   8.1 Digitale systemen als fysieke infrastructuur  
   8.2 Externalisering van ecologische en sociale kosten  

9. [Reikwijdte en Gebruik](#ch-9)  
   9.1 Normatief kader, geen certificaat  
   9.2 Beperkingen en expliciete afbakening  

10. [Auteurschap en Menselijke Verantwoordelijkheid](#ch-10)

- [Dankwoord](#dankwoord)  
- [Licentie en Gebruik](#licentie-en-gebruik)  
- [Uitnodiging tot Peer Review](#uitnodiging-tot-peer-review)  
- [Slotbeschouwing](#slotbeschouwing)  
- [Toegankelijkheid van Bronnen](#toegankelijkheid-van-bronnen)  
- [Referenties / Literatuurlijst](#referenties--literatuurlijst)

---
---

<a id="0-voorwoord"></a>
## 0. Voorwoord

Digitale systemen zijn uitgegroeid tot structuren die diep ingrijpen in het menselijk leven. Zij beïnvloeden identiteit, bestaanszekerheid, zichtbaarheid, veiligheid en maatschappelijke participatie, vaak zonder directe menselijke tussenkomst. Waar deze systemen ooit ondersteunend waren, functioneren zij steeds vaker als beslissende infrastructuur.

De ethische aannames waarop deze systemen zijn ontworpen, hebben deze ontwikkeling niet in gelijke mate bijgehouden. Door de snelheid en schaal waarmee digitale technologieën worden ontwikkeld en uitgerold — waaronder ten tijde van schrijven de introductie van de AI-bril als alledaags interactiemiddel — ontstaat een structurele kloof tussen technische implementatie en normatieve verantwoording. Ethiek wordt hierdoor niet slechts vertraagd, maar systematisch ingehaald.

Dit document vertrekt vanuit de vaststelling dat veel van de schade die in digitale omgevingen zichtbaar wordt, niet het gevolg is van uitzonderlijke fouten of misbruik, maar van voorspelbare ontwerppatronen. Consent wordt gereduceerd tot formaliteit, veiligheid wordt reactief georganiseerd, herstelmechanismen ontbreken of zijn onvoldoende, en macht concentreert zich zonder effectieve tegenmacht of transparante verantwoording.

Het Universal Consent & Safety Framework (UCSF) is ontwikkeld als antwoord op deze structurele discrepantie. Het is geen technologie-specifiek model en geen reactie op een enkel incident. UCSF biedt een normatief kader voor de beoordeling en begrenzing van systemen die invloed uitoefenen op menselijke autonomie, veiligheid en bestaanszekerheid.

UCSF vertrekt vanuit een ontwerpgerichte ethiek: wanneer schade voorspelbaar is, is zij niet toevallig; wanneer herstel ontbreekt, is dat geen tekortkoming maar een keuze; en wanneer consent niet vrij kan worden ingetrokken, is er geen sprake van instemming. In die zin adresseert dit kader niet alleen wat systemen doen, maar wat zij mogen doen.

Dit document beoogt geen morele volledigheid en geen definitieve oplossingen. Het stelt minimale voorwaarden vast waaronder digitale systemen ethisch verdedigbaar kunnen functioneren, en erkent expliciet dat het niet bouwen, niet opschalen of niet implementeren van een systeem een legitieme ethische uitkomst kan zijn.

UCSF biedt geen comfort.  
Het stelt grenzen.

[⬆ Terug naar inhoudsopgave](#inhoudsopgave)

---

<a id="ch-1"></a>
## 1. Waarom UCSF Bestaat

Digitale systemen nemen in toenemende mate beslissingen die directe gevolgen hebben voor mensen. Zij bepalen wie zichtbaar is, wie toegang heeft tot diensten of inkomsten, wie wordt uitgesloten en wie zonder duidelijke uitleg zijn positie verliest. Deze beslissingen vinden steeds vaker plaats zonder directe menselijke tussenkomst, op basis van geautomatiseerde processen, beleidslogica en schaalmechanismen die voor gebruikers grotendeels ondoorzichtig zijn.

Wat deze ontwikkeling problematisch maakt, is niet enkel de technische complexiteit, maar de asymmetrie die zij creëert. Individuen worden geconfronteerd met systemen die wél handelingsmacht hebben, maar nauwelijks aanspreekbaar zijn. Beslissingen zijn vaak definitief, moeilijk te betwisten en slecht uitlegbaar, terwijl de gevolgen ervan diep kunnen ingrijpen in bestaanszekerheid, reputatie en autonomie.

In uiteenlopende digitale contexten — van sociale platforms tot arbeidsmarktplaatsen en AI-gedreven diensten — herhalen zich daarbij dezelfde structurele patronen:
- consent wordt gereduceerd tot een formaliteit of een eenmalige handeling;
- veiligheid wordt pas geadresseerd nadat aantoonbare schade is ontstaan;
- herstelmechanismen zijn traag, ontoereikend of afwezig;
- macht concentreert zich bij systeemontwerpers en platformexploitanten, zonder effectieve tegenmacht of transparante verantwoording.

Deze patronen zijn geen incidenten en geen uitzonderingen. Zij vormen terugkerende kenmerken van hedendaagse digitale infrastructuren. Dat zij in verschillende sectoren en technologieën telkens opnieuw zichtbaar worden, wijst niet op individueel falen, maar op gedeelde ontwerpkeuzes en onderliggende aannames.

UCSF vertrekt vanuit de vaststelling dat veel van de schade die in digitale systemen ontstaat, voorspelbaar is. Wanneer schade structureel optreedt, kan zij niet langer worden afgedaan als neveneffect of onbedoelde consequentie. In dergelijke gevallen is sprake van ontwerpverantwoordelijkheid. Dat geldt temeer wanneer systemen bewust op schaal worden uitgerold, terwijl de risico’s bekend zijn of redelijkerwijs voorzienbaar waren.

Een terugkerend probleem in bestaande ethische kaders is dat zij vaak normatief sterk zijn, maar operationeel zwak. Ethiek wordt geformuleerd als intentie, richtlijn of aspiratie, terwijl daadwerkelijke systeemarchitectuur, governance en implementatie buiten beschouwing blijven. Hierdoor ontstaat een discrepantie tussen wat systemen beloven en wat zij feitelijk doen.

Het Universal Consent & Safety Framework (UCSF) bestaat om deze discrepantie expliciet te adresseren. Het is ontwikkeld als antwoord op structurele tekortkomingen in hoe digitale systemen omgaan met consent, veiligheid, herstel en macht. UCSF is geen technologie-specifiek model en geen reactie op een enkel incident. Het biedt een normatief kader voor de beoordeling en begrenzing van systemen die invloed uitoefenen op menselijke autonomie, veiligheid en bestaanszekerheid.

Centraal binnen UCSF staat de overtuiging dat ethiek niet los kan worden gezien van ontwerp. Wanneer systemen zodanig zijn ingericht dat consent niet vrij kan worden ingetrokken, dat schade niet kan worden hersteld, of dat macht niet kan worden betwist, dan is dat geen tekortkoming in gebruik, maar een eigenschap van het systeem zelf.

UCSF positioneert zich daarom expliciet ontwerpgericht. Het stelt niet alleen vragen over gedrag en beleid, maar over architectuur, besluitvorming en verantwoordelijkheidsstructuren. Daarmee verschuift de focus van individuele gebruikers of incidenten naar de systemen die deze uitkomsten mogelijk maken.

Dit hoofdstuk vormt het normatieve vertrekpunt van het framework. De volgende hoofdstukken werken deze uitgangspunten verder uit langs de assen consent, veiligheid, herstel, governance en implementatie, en formuleren minimale voorwaarden waaronder digitale systemen ethisch verdedigbaar kunnen functioneren.

### Structureel falen als ontwerppatroon

Wat in publieke en beleidsmatige discussies vaak wordt gepresenteerd als incidenten — foutieve beslissingen, misbruik, uitsluiting of onbedoelde schade — blijkt bij nadere analyse structureel van aard. Deze schade ontstaat niet ondanks het ontwerp van digitale systemen, maar juist *door* terugkerende ontwerppatronen waarin snelheid, schaal en efficiëntie prioriteit krijgen boven menselijke begrenzing.

Wanneer vergelijkbare vormen van schade zich herhalen in uiteenlopende contexten en platforms, kan niet langer worden gesproken van toeval. Het betreft dan geen uitzonderingen, maar systemische uitkomsten. In die gevallen is schade voorspelbaar, en daarmee ethisch relevant op ontwerpniveau.

### Van verantwoordelijkheid achteraf naar verantwoordelijkheid vooraf

Veel digitale systemen hanteren een impliciet moreel model waarin verantwoordelijkheid pas ontstaat nádat schade zich heeft voorgedaan. Moderatie, klachtenprocedures en bezwaarmechanismen fungeren als correctielaag, niet als ontwerpprincipe. Deze benadering verschuift de last van risico en herstel structureel naar individuen die het minst in staat zijn deze te dragen.

UCSF verwerpt dit model. Wanneer de maatschappelijke, psychologische of economische gevolgen van een systeem vooraf te voorzien zijn, ontstaat een verantwoordelijkheid vóór implementatie. Ontwerpkeuzes die bekende risico’s externaliseren, zijn geen neutrale beslissingen maar ethische posities.

### Macht zonder expliciete verantwoording

Een kernprobleem binnen hedendaagse digitale infrastructuur is de asymmetrie tussen macht en verantwoordelijkheid. Systemen die beslissen over zichtbaarheid, toegang, inkomsten of uitsluiting, oefenen feitelijke macht uit over mensenlevens, terwijl zij zichzelf juridisch en discursief blijven positioneren als neutrale technologieën.

Deze ontkoppeling van macht en expliciete ethische verantwoording vormt de aanleiding voor UCSF. Het framework vertrekt vanuit de stelling dat waar feitelijke macht wordt uitgeoefend, ook normatieve verantwoordelijkheid moet worden gedragen — ongeacht intenties, automatisering of schaal.

### De noodzaak van begrenzing

UCSF bestaat niet om systemen te optimaliseren, maar om grenzen te definiëren. Het erkent dat niet elk technisch haalbaar systeem ethisch verdedigbaar is, en dat het ontbreken van expliciete grenzen leidt tot normalisering van schade.

Daarmee adresseert dit hoofdstuk niet alleen waarom UCSF nodig is, maar waarom bestaande ethische benaderingen tekortschieten zolang zij falen te erkennen dat sommige systemen fundamenteel onverenigbaar zijn met menselijke autonomie, veiligheid en bestaanszekerheid.

*(Zie [1](#ref-1), [2](#ref-2), [5](#ref-5), [6](#ref-6), [7](#ref-7))*

[⬆ Terug naar inhoudsopgave](#inhoudsopgave)

---

<a id="ch-2"></a>
## 2. Consent in Digitale Systemen

In veel digitale systemen wordt consent behandeld als een eenmalige handeling: een klik, een akkoordverklaring, een stilzwijgende instemming bij voortgezet gebruik. Deze benadering reduceert consent tot een juridisch afvinkmoment en miskent de dynamiek van machtsverhoudingen, afhankelijkheid en context waarin digitale interacties plaatsvinden.

UCSF verwerpt deze benadering.

Consent is geen gebeurtenis, maar een toestand. Zij moet expliciet, herroepbaar, contextueel en temporeel begrensd zijn. Een systeem dat consent beschouwt als permanent of impliciet, verplaatst de verantwoordelijkheid eenzijdig naar de gebruiker en onttrekt zichzelf aan ethische toetsing.

Onder UCSF geldt daarom dat:
- consent actief en ondubbelzinnig moet worden gegeven;
- consent zonder directe of indirecte sancties moet kunnen worden ingetrokken;
- consent altijd gekoppeld is aan een specifiek doel en een specifieke context;
- stilte, voortgezet gebruik of economische noodzaak nooit als instemming mag worden geïnterpreteerd;
- afhankelijkheidsrelaties (financieel, sociaal of infrastructureel) consent niet mogen afdwingen.

### Consent als machtsrelatie

Binnen digitale systemen kan consent niet los worden gezien van machtsverhoudingen. Wanneer toegang tot werk, zichtbaarheid, sociale participatie of inkomen afhankelijk wordt gemaakt van instemming, verschuift consent van een vrije keuze naar een voorwaarde voor overleving. In dergelijke contexten functioneert consent niet langer als ethisch legitimatiemechanisme, maar als instrument van disciplinering.

UCSF stelt daarom dat consent alleen betekenisvol kan zijn wanneer reële weigering mogelijk blijft zonder disproportionele gevolgen. Systemen die formeel instemming vragen, maar structureel afhankelijkheid creëren, ondermijnen de normatieve waarde van consent, ongeacht juridische correctheid.

Wanneer het intrekken van consent leidt tot verlies van zichtbaarheid, toegang, inkomen of bestaanszekerheid, is er geen sprake van vrije instemming maar van structurele dwang. In dergelijke situaties functioneert consent als legitimatie-instrument voor macht, niet als uitdrukking van autonomie.  
*(Zie [3](#ref-3))*

### 2.1 Consent, Macht en Asymmetrie

Digitale systemen opereren zelden in machtsneutrale contexten. Platforms bepalen toegang, zichtbaarheid, handhaving en economische voorwaarden. Gebruikers bevinden zich daardoor structureel in een afhankelijke positie, zelfs wanneer formeel sprake lijkt van vrijwillige deelname.

UCSF stelt dat consent ongeldig wordt wanneer:
- de gebruiker geen reëel alternatief heeft;
- de gevolgen van weigering of intrekking disproportioneel zijn;
- de voorwaarden eenzijdig en niet-onderhandelbaar worden opgelegd;
- de werking van het systeem onvoldoende begrijpelijk is om een geïnformeerde keuze te maken.

In dergelijke gevallen functioneert consent als compliance: niet als keuze, maar als noodzakelijke aanpassing om toegang te behouden. Dit onderscheid is essentieel. Een systeem kan juridisch compliant zijn en tegelijkertijd ethisch onhoudbaar.

### 2.2 Consent als Ontwerpverantwoordelijkheid

UCSF verplaatst consent expliciet van de gebruikersinterface naar het systeemontwerp. Het is onvoldoende om consent “aan te bieden” via voorwaarden of instellingen; systemen moeten zodanig zijn ontworpen dat:
- intrekking van consent technisch mogelijk én praktisch haalbaar is;
- gevolgen van intrekking proportioneel en transparant zijn;
- eerdere instemming geen blijvend eigendoms- of machtsrecht creëert;
- consent niet wordt gekoppeld aan irrelevante of cumulatieve voorwaarden.

Wanneer een systeem alleen kan functioneren door consent structureel te ondermijnen of te fixeren, is dat geen implementatieprobleem maar een fundamenteel ontwerpfout.

### 2.3 Grenzen van Toelaatbaarheid

UCSF erkent dat niet elk systeem ethisch kan worden herontworpen. In sommige gevallen is het onmogelijk om vrije, herroepbare en betekenisvolle instemming te garanderen zonder het systeem zelf fundamenteel te wijzigen.

In die gevallen is ethische weigering — het niet bouwen, niet uitrollen of niet opschalen van een systeem — geen falen, maar een noodzakelijke uitkomst.

Consent is binnen UCSF geen formaliteit en geen juridisch schild. Het is een toetssteen voor legitimiteit. Waar consent niet vrij kan bestaan, verliest een systeem zijn ethische rechtvaardiging.

[⬆ Terug naar inhoudsopgave](#inhoudsopgave)

---

<a id="ch-3"></a>
## 3. Veiligheid als Ontwerpverantwoordelijkheid

Veel digitale systemen benaderen veiligheid reactief. Schade wordt pas aangepakt nadat deze zich heeft voorgedaan, via moderatie, meldsystemen of bezwaarprocedures. In deze benadering wordt veiligheid behandeld als een operationele correctielaag, losgekoppeld van het ontwerp zelf.

UCSF stelt dat deze benadering fundamenteel tekortschiet.

Wanneer schade voorspelbaar is, dient zij vooraf te worden ondervangen. Systemen die herhaaldelijk dezelfde vormen van schade veroorzaken, kunnen zich niet beroepen op toeval, uitzonderingen of onvoorzien gebruik. Structurele schade wijst op structurele ontwerpkeuzes.

Binnen UCSF wordt veiligheid niet opgevat als afwezigheid van incidenten, maar als een eigenschap van het systeemontwerp. Veiligheid is daarmee geen aanvullende functie, maar een kernverantwoordelijkheid die voorafgaand aan implementatie moet worden geborgd.

### 3.1 Toetsbare veiligheid

UCSF beschouwt veiligheid niet alleen als normatief principe, maar ook als toetsbaar criterium.  
Een systeem voldoet slechts aan de veiligheidsvoorwaarde wanneer aan de volgende minimale eisen wordt voldaan:

- schade is niet structureel reproduceerbaar  
- escalatiepaden zijn begrensd en controleerbaar  
- kwetsbare gebruikers dragen geen disproportioneel risico  
- correctie is niet afhankelijk van publieke blootstelling of reputatieschade  
- preventie is aantoonbaar effectiever dan achteraf herstel  

Ontwerp dat deze criteria niet kan waarmaken, faalt niet technisch maar ethisch.

### 3.2 Risico versus schade

UCSF maakt expliciet onderscheid tussen risico en schade.  
Risico kan onder voorwaarden ethisch aanvaardbaar zijn; schade niet.

Digitale systemen mogen onzekerheid bevatten, maar mogen geen voorspelbare, structurele schade incorporeren als functioneel bijproduct. Wanneer schade noodzakelijk blijkt voor schaalbaarheid, winstgevendheid of kernfunctionaliteit, is niet de uitvoering problematisch, maar het systeem zelf.

Het normaliseren van schade onder het mom van “complexiteit” of “onvermijdelijke bijwerkingen” is binnen UCSF niet aanvaardbaar.

### 3.3 Automatisering en verantwoordelijkheid

Automatisering verschuift uitvoering, maar niet verantwoordelijkheid.

Wanneer beslissingen worden gedelegeerd aan algoritmische processen of geautomatiseerde infrastructuren, blijft de morele aansprakelijkheid bij de menselijke ontwerp-, bestuurs- en eigendomsstructuren. De afwezigheid van directe menselijke tussenkomst reduceert het risico niet, maar vergroot de plicht tot voorafgaande veiligheidsborging.

Systemen die hun impact legitimeren door te verwijzen naar automatisering, abstraheren verantwoordelijkheid op een ethisch onhoudbare wijze.

### 3.4 Veiligheid als relationeel ontwerpprincipe

Veiligheid binnen UCSF is relationeel: zij bestaat niet los van machtsverhoudingen, afhankelijkheid en context. Een systeem dat veilig is voor de ene groep maar structureel schadelijk voor een andere, voldoet niet aan de veiligheidsvoorwaarde.

Een systeem dat slechts veilig functioneert wanneer gebruikers zich perfect gedragen, volledige kennis bezitten of voortdurend waakzaam zijn, is per definitie onveilig.

Veiligheid moet worden gedragen door het ontwerp zelf, niet afgewenteld op individuele gebruikers.

*(Zie [4](#ref-4), [9](#ref-9))*

[⬆ Terug naar inhoudsopgave](#inhoudsopgave)

---

<a id="ch-4"></a>
## 4. Falen, Herstel en Reparatie

Geen enkel systeem functioneert foutloos op schaal. Naarmate digitale systemen meer autonomie krijgen en diepere invloed uitoefenen op menselijke levens, neemt de waarschijnlijkheid van falen toe. De ethische vraag is daarom niet *of* falen zal optreden, maar *hoe* systemen zijn ontworpen om met falen om te gaan.

In veel digitale omgevingen wordt falen behandeld als een uitzonderlijke gebeurtenis: een bug, een incident, een individuele fout. Herstel wordt gepresenteerd als service, coulance of goedwillendheid. Deze benadering miskent de structurele aard van schade in grootschalige systemen.

UCSF verwerpt het idee dat herstel een gunst is. Wanneer een systeem schade kan veroorzaken, is herstel geen optionele toevoeging maar een **ethische kernverantwoordelijkheid van het ontwerp**.

### 4.1 Falen als voorspelbaar ontwerpprobleem

Falen in digitale systemen is zelden volledig onvoorzien. Veel schadepatronen zijn herhaalbaar, systematisch en statistisch voorspelbaar: onterechte uitsluiting, foutieve classificatie, inkomensverlies, reputatieschade of psychologische belasting.

Wanneer dergelijke schade zich herhaaldelijk voordoet, kan zij niet langer worden aangemerkt als incident. Zij wordt dan een **structureel effect van het systeemontwerp**.

Onder UCSF geldt:
- als schade voorspelbaar is, moet zij worden meegenomen in het ontwerp  
- systemen die structureel schade veroorzaken, falen ethisch, ook als zij technisch functioneren  
- het ontbreken van herstelmechanismen is geen neutraliteit, maar een keuze  

Een systeem dat correct werkt maar onherstelbare schade veroorzaakt, is niet ethisch neutraal maar normatief gebrekkig.

### 4.2 Herstel als ontwerpvereiste

Herstelmechanismen worden in veel systemen pas achteraf toegevoegd, vaak onder druk van publieke kritiek, regelgeving of juridische procedures. UCSF stelt dat deze benadering onvoldoende is.

Herstel moet **vooraf** worden ontworpen en integraal onderdeel zijn van de systeemarchitectuur.

Dit omvat onder meer:
- **omkeerbaarheid** van beslissingen waar mogelijk  
- **proportionaliteit** van maatregelen en sancties  
- **tijdigheid** van herstel (schade die te laat wordt hersteld, blijft schade)  
- **continuïteitsbescherming** bij bestaanszekerheid, zoals toegang tot werk, inkomen of zichtbaarheid  

Wanneer beslissingen onomkeerbaar zijn, dient de ethische drempel voor implementatie aanzienlijk hoger te liggen.

### 4.3 Reparatie versus correctie

Veel systemen beperken herstel tot correctie: het aanpassen van een fout, het herstellen van een status, het heractiveren van een account. UCSF maakt expliciet onderscheid tussen correctie en reparatie.

Correctie herstelt de technische toestand.  
Reparatie erkent en adresseert de **gevolgen van schade**.

Reparatie kan onder meer betekenen:
- compensatie voor geleden verlies  
- herstel van reputatie of zichtbaarheid  
- transparante erkenning van fout en impact  
- structurele aanpassing om herhaling te voorkomen  

Zonder reparatie blijft schade extern en wordt zij gedragen door individuen, terwijl het systeem intact blijft.

### 4.4 Asymmetrie van macht en bewijslast

In veel digitale omgevingen ligt de bewijslast bij de gebruiker: men moet aantonen dat schade is ontstaan, dat het systeem fout zat en dat herstel gerechtvaardigd is. Tegelijkertijd beschikt het systeem over data, logs, algoritmen en besluitvormingsmacht.

UCSF beschouwt deze asymmetrie als ethisch problematisch.

Wanneer een systeem macht uitoefent over mensen, dient het:
- **verantwoordelijkheid te dragen voor bewijsvoering**  
- **transparantie te bieden over besluitvorming**  
- **toegankelijke herstelpaden** te garanderen zonder excessieve drempels  

Een herstelprocedure die theoretisch bestaat maar praktisch onbereikbaar is, voldoet niet aan ethische eisen.

### 4.5 Onherstelbare schade en ethische grenzen

Niet alle schade kan worden hersteld. In gevallen waarin schade structureel, grootschalig of onomkeerbaar is, stelt UCSF dat het ontwerp zelf ter discussie moet worden gesteld.

Wanneer:
- herstel onmogelijk is  
- schade disproportioneel is  
- of de lasten systematisch bij kwetsbare groepen liggen  

dan is het ethisch verdedigbaar — en soms noodzakelijk — om implementatie, opschaling of voortzetting te weigeren.

Herstel is geen alibi om schadelijke systemen te rechtvaardigen. Het ontbreken van herstel is echter een directe aanwijzing dat een systeem zijn ethische grenzen overschrijdt.

*(Zie [9](#ref-9), [10](#ref-10))*

[⬆ Terug naar inhoudsopgave](#inhoudsopgave)

---

<a id="ch-5"></a>
## 5. Macht, Governance en Verantwoordelijkheid

Digitale systemen zijn geen neutrale infrastructuren. Zij structureren macht door controle over toegang, zichtbaarheid, handhaving, data en inkomstenstromen. Deze machtsuitoefening is vaak impliciet, technisch bemiddeld en onttrokken aan directe democratische of juridische controle.

UCSF vertrekt vanuit de stelling dat ethische verantwoordelijkheid daar ligt waar **feitelijke macht** wordt uitgeoefend, niet waar intenties worden uitgesproken.

Wanneer een systeem beslissingen kan nemen die gevolgen hebben voor bestaanszekerheid, reputatie, veiligheid of autonomie, oefent het macht uit — ongeacht of die macht formeel, informeel, geautomatiseerd of “slechts ondersteunend” wordt genoemd.

### 5.1 Macht als systeemkenmerk

In veel digitale omgevingen wordt macht verhuld door taal van efficiëntie, gebruiksgemak of neutraliteit. Beslissingen worden gepresenteerd als technische noodzaak of algoritmisch gevolg, terwijl zij in werkelijkheid normatieve keuzes bevatten.

Macht manifesteert zich onder meer door:
- controle over wie zichtbaar is en wie niet  
- toegang tot markten, platforms of infrastructuur  
- handhaving van regels zonder gelijkwaardige inspraak  
- asymmetrische informatiepositie  
- het vermogen om voorwaarden eenzijdig te wijzigen  

UCSF stelt dat deze vormen van macht niet verdwijnen door ze te automatiseren. Automatisering verschuift verantwoordelijkheid niet, maar **verankert haar in ontwerp**.

### 5.2 Governance versus intentie

Veel organisaties beroepen zich op goede intenties, ethische richtlijnen of waardenstatements. UCSF erkent intenties als moreel relevant, maar beschouwt ze als **ethisch onvoldoende**.

Wat telt is governance: de concrete structuren waarmee macht wordt uitgeoefend, begrensd en getoetst.

Onder UCSF geldt:
- intenties zonder afdwingbare structuren bieden geen bescherming  
- waarden zonder governance zijn symbolisch  
- ethiek zonder tegenmacht is fragiel  

Ethische verantwoordelijkheid vereist:
- expliciete besluitvormingsprocessen  
- toetsbare regels en criteria  
- mogelijkheid tot bezwaar en correctie  
- transparantie over wie beslist en waarom  

### 5.3 Concentratie van macht en gebrek aan tegenmacht

Digitale systemen op schaal vertonen vaak een sterke concentratie van macht. Gebruikers, makers en afhankelijke partijen hebben doorgaans beperkte onderhandelingsruimte en weinig effectieve middelen om beslissingen aan te vechten.

Deze asymmetrie wordt versterkt door:
- afhankelijkheid van platforminkomsten  
- lock-in effecten  
- gebrek aan alternatieven  
- juridische complexiteit  
- ondoorzichtige besluitvorming  

UCSF beschouwt het ontbreken van effectieve tegenmacht niet als een marktfalen, maar als een **ethisch ontwerpprobleem**.

Systemen die macht concentreren zonder structurele tegenmacht, ondermijnen hun eigen ethische legitimiteit.

### 5.4 Verantwoordelijkheid en uitbesteding

Een veelvoorkomend patroon in digitale systemen is het uitbesteden of fragmenteren van verantwoordelijkheid: beslissingen worden toegeschreven aan algoritmen, externe leveranciers, moderatieteams of “het systeem”.

UCSF verwerpt deze vorm van verantwoordelijkheidsspreiding wanneer zij leidt tot onduidelijkheid of ongrijpbaarheid.

Onder UCSF geldt:
- verantwoordelijkheid is niet overdraagbaar aan systemen  
- outsourcing ontslaat niet van ethische plicht  
- automatisering vermindert aansprakelijkheid niet  

Waar macht ligt, ligt verantwoordelijkheid — ongeacht technische architectuur of organisatorische afstand.

### 5.5 Transparantie als noodzakelijke maar onvoldoende voorwaarde

Transparantie wordt vaak gepresenteerd als oplossing voor machtsasymmetrie. Hoewel transparantie noodzakelijk is, beschouwt UCSF haar als **onvoldoende** wanneer zij niet gepaard gaat met handelingsmogelijkheden.

Inzicht zonder invloed corrigeert geen macht.

Ethische governance vereist daarom:
- begrijpelijke transparantie (niet slechts formele openheid)  
- daadwerkelijke mogelijkheden tot bezwaar  
- herstel bij onrechtmatige beslissingen  
- structurele aanpassing bij herhaalde schade  

Transparantie zonder correctiemechanismen legitimeert macht in plaats van haar te begrenzen.

### 5.6 Macht en ethische begrenzing

UCSF stelt dat niet alle vormen van machtsuitoefening ethisch aanvaardbaar zijn, zelfs wanneer zij legaal, winstgevend of efficiënt zijn.

Wanneer:
- macht structureel onevenwichtig is  
- afhankelijkheid niet vrijwillig is  
- schade voorspelbaar en herhaaldelijk optreedt  
- en tegenmacht ontbreekt  

dan dient niet optimalisatie maar **begrenzing** het uitgangspunt te zijn.

In sommige gevallen betekent dit dat systemen niet ethisch verantwoord kunnen worden voortgezet zonder fundamentele herstructurering.

*(Zie [5](#ref-5), [6](#ref-6))*

[⬆ Terug naar inhoudsopgave](#inhoudsopgave)

---

<a id="ch-6"></a>
## 6. Implementatie zonder Ethische Ontwijking

Ethische principes verliezen hun betekenis op het moment dat zij worden geconfronteerd met implementatiekeuzes. Juist in deze fase ontstaat de grootste kloof tussen normatieve intentie en feitelijke praktijk.

UCSF stelt dat ethiek geen abstracte laag is die boven systemen zweeft, maar een ontwerpeis die **concreet afdwingbaar** moet zijn in technische, organisatorische en economische beslissingen.

### 6.1 De mythe van het implementatiedilemma

Veel digitale systemen presenteren ethische tekortkomingen als onvermijdelijke bijproducten van schaal, snelheid of complexiteit. Deze framing suggereert dat ethiek een luxe is die pas mogelijk wordt na optimalisatie.

UCSF verwerpt deze benadering.

Wanneer ethische principes alleen gelden zolang zij geen frictie veroorzaken, functioneren zij niet als principes maar als voorkeuren.

Ontwerpkeuzes die schade veroorzaken omdat zij “praktisch noodzakelijk” zouden zijn, zijn geen dilemma’s maar **ethische ontwijking**.

### 6.2 Ethische schuld en technische schuld

In softwareontwikkeling is technische schuld een erkend concept: tijdelijke keuzes die later herstel vereisen. UCSF introduceert het concept van **ethische schuld**.

Ethische schuld ontstaat wanneer:
- bekende risico’s worden genegeerd  
- herstelmechanismen bewust worden uitgesteld  
- schade wordt geaccepteerd als operationele kosten  
- afhankelijkheid wordt uitgebuit  

In tegenstelling tot technische schuld treft ethische schuld niet systemen, maar mensen. Zij stapelt zich op in de vorm van bestaansonzekerheid, uitsluiting en structurele schade.

### 6.3 Ethiek als randvoorwaarde, niet als optimalisatiedoel

UCSF positioneert ethiek niet als variabele in een optimalisatiemodel, maar als **grensvoorwaarde**.

Onder UCSF geldt:
- systemen moeten ethisch verdedigbaar zijn vóór opschaling  
- onethische efficiëntie is geen vooruitgang  
- winstgevendheid rechtvaardigt geen schade  

Wanneer een systeem alleen functioneert door ethische grenzen te overschrijden, is het systeem zelf onhoudbaar.

### 6.4 Implementatie en institutionele verantwoordelijkheid

Ethische implementatie vereist institutionele verantwoordelijkheid. Individuele engineers, moderators of eindgebruikers kunnen geen structurele ethische tekortkomingen compenseren.

UCSF vereist:
- expliciete toewijzing van ethische verantwoordelijkheid  
- structurele besluitvorming op organisatieniveau  
- vastgelegde herstelprocedures  
- onafhankelijke toetsing waar macht geconcentreerd is  

Ethiek die afhankelijk is van individuele goede wil is fragiel en niet schaalbaar.

*(Zie [7](#ref-7), [11](#ref-11), [12](#ref-12))*

[⬆ Terug naar inhoudsopgave](#inhoudsopgave)

---

<a id="ch-7"></a>
## 7. Grenzen en Ethische Weigering

Niet alle schade is acceptabel. Niet alle systemen verdienen opschaling. Niet elke innovatie is moreel verdedigbaar.

UCSF introduceert **ethische weigering** als volwaardige en noodzakelijke uitkomst van ethische analyse.

### 7.1 De normalisering van schade

In digitale ecosystemen worden bepaalde vormen van schade genormaliseerd: uitsluiting, psychologische druk, economische afhankelijkheid en structurele ongelijkheid worden gepresenteerd als onvermijdelijke bijwerkingen.

UCSF verwerpt deze normalisering.

Wanneer schade:
- structureel is  
- voorspelbaar is  
- herhaaldelijk optreedt  
- en vooral wordt gedragen door partijen zonder reële keuzevrijheid  

dan is zij geen bijwerking maar een kernkenmerk van het systeem.

### 7.2 De ethische grens van optimalisatie

Veel systemen blijven schade optimaliseren in plaats van elimineren. Drempels worden verhoogd, frictie verminderd, maar het onderliggende probleem blijft bestaan.

UCSF stelt dat sommige problemen **niet oplosbaar zijn binnen het bestaande systeemontwerp**.

In dergelijke gevallen is weigering geen falen, maar verantwoordelijkheid.

### 7.3 Niet-bouwen, niet-opschalen, niet-implementeren

Onder UCSF zijn de volgende uitkomsten legitiem:
- het niet bouwen van een systeem  
- het stoppen van verdere opschaling  
- het intrekken van bestaande implementaties  

Deze uitkomsten zijn ethisch gerechtvaardigd wanneer:
- consent structureel niet vrij kan worden gegeven  
- herstel onmogelijk of disproportioneel is  
- macht niet begrensd kan worden  
- schade niet kan worden voorkomen  

Groei is geen morele waarde op zichzelf.

### 7.4 Weigering als ontwerpprincipe

UCSF positioneert weigering niet als laatste redmiddel, maar als **ontwerpoptie**.

Ethisch ontwerp omvat ook:
- het definiëren van harde grenzen  
- het inbouwen van stopmechanismen  
- het accepteren van niet-marktbare uitkomsten  

Systemen die geen mogelijkheid tot ethische weigering bevatten, zijn per definitie onethisch rigide.

*(Zie [1](#ref-1), [2](#ref-2), [4](#ref-4))*

[⬆ Terug naar inhoudsopgave](#inhoudsopgave)
---

<a id="ch-8"></a>
## 8. Infrastructuur, Materiële Schade en Gedeelde Verantwoordelijkheid

Digitale systemen worden vaak gepresenteerd als immaterieel. In werkelijkheid rusten zij op omvangrijke fysieke infrastructuren: datacenters, energievoorziening, watergebruik, grondstoffenwinning en menselijke arbeid.

UCSF stelt dat ethische verantwoordelijkheid niet eindigt bij de gebruikersinterface.

### 8.1 De materialiteit van digitale systemen

Elke digitale interactie heeft materiële gevolgen. De schaal waarop systemen opereren vertaalt zich direct naar ecologische belasting en sociale impact.

Deze gevolgen worden vaak:
- geografisch verplaatst  
- uitbesteed aan kwetsbare gemeenschappen  
- juridisch gefragmenteerd  
- buiten zicht gehouden van eindgebruikers  

UCSF beschouwt deze externalisering als een ethisch vraagstuk, niet slechts als logistiek of economisch probleem.

### 8.2 Gedeelde maar niet verdunde verantwoordelijkheid

Hoewel infrastructuur vaak bestaat uit complexe ketens, verwerpt UCSF het idee dat verantwoordelijkheid daardoor verdwijnt.

Gedeelde verantwoordelijkheid is geen vrijbrief voor verdunning.

Onder UCSF geldt:
- elke actor is verantwoordelijk voor zijn bijdrage  
- kennis van schade impliceert verantwoordelijkheid  
- schaal vergroot verplichting, niet afstand  

### 8.3 Onzichtbare arbeid en menselijke kosten

Naast ecologische impact rusten digitale systemen op grootschalige menselijke arbeid: moderatie, labeling, onderhoud en correctie.

Wanneer deze arbeid:
- structureel onderbetaald is  
- psychologisch schadelijk is  
- sociaal onzichtbaar blijft  

dan is sprake van ethische exploitatie, ongeacht contractuele legitimiteit.

### 8.4 Infrastructuur en ethische legitimiteit

Systemen die hun materiële schade structureel externaliseren, verliezen hun ethische legitimiteit, zelfs wanneer hun digitale functionaliteit ogenschijnlijk “veilig” is.

UCSF vereist dat infrastructuurdeelname wordt meegenomen in ethische beoordeling.

*(Zie [5](#ref-5), [6](#ref-6), [9](#ref-9), [13](#ref-13))*

[⬆ Terug naar inhoudsopgave](#inhoudsopgave)

---

<a id="ch-9"></a>
## 9. Reikwijdte en Gebruik

UCSF pretendeert geen morele volledigheid te bieden. Het is geen ethisch totaalmodel en geen universele oplossing.

Het kader definieert **minimale voorwaarden** waaronder systemen die invloed uitoefenen op menselijke autonomie, veiligheid of bestaanszekerheid ethisch verdedigbaar kunnen functioneren.

### 9.1 Normatief, geen instrumenteel kader

UCSF is geen product, keurmerk of compliance-tool. Het biedt geen certificering en geen ethisch schild.

Het functioneert als:
- beoordelingskader  
- begrenzingsinstrument  
- normatieve toets  

Gebruik van UCSF zonder bereidheid tot daadwerkelijke consequenties ondermijnt zijn betekenis.

### 9.2 Toepassingsgebied

UCSF is van toepassing op systemen die:
- beslissingen nemen of afdwingen  
- afhankelijkheid creëren  
- toegang reguleren  
- schade kunnen veroorzaken  

Het kader is technologie-agnostisch en richt zich op **effecten**, niet op labels.

### 9.3 Grenzen van toepassing

UCSF erkent expliciet dat sommige contexten:
- politieke afweging vereisen  
- juridische kaders overstijgen  
- maatschappelijke consensus vragen  

In dergelijke gevallen fungeert UCSF niet als oplossing, maar als **waarschuwingskader**.

### 9.4 Ethische weigering als valide uitkomst

Een kernstelling van UCSF is dat het weigeren van implementatie een geldige uitkomst is van ethische analyse.

Wanneer minimale voorwaarden niet kunnen worden gewaarborgd, is doorgaan geen neutraliteit maar actieve keuze.

*(Zie [8](#ref-8), [10](#ref-10), [14](#ref-14), [15](#ref-15))*

[⬆ Terug naar inhoudsopgave](#inhoudsopgave)

---

<a id="ch-10"></a>
## 10. Auteurschap en Menselijke Verantwoordelijkheid

Dit document is opgesteld door een mens, met gebruik van AI-systemen ter ondersteuning van structurering, taal en iteratie. Deze ondersteuning doet geen afbreuk aan het auteurschap, noch aan de verantwoordelijkheid voor de inhoud.

UCSF vertrekt vanuit de fundamentele stelling dat ethiek niet kan worden gedelegeerd. Systemen kunnen ondersteunen, versnellen of structureren, maar zij kunnen geen morele verantwoordelijkheid dragen.

### 10.1 AI als hulpmiddel, niet als auteur

AI-systemen functioneren binnen door mensen vastgestelde kaders, datasets en optimalisatiedoelen. Zij bezitten geen intentie, geen begrip van schade en geen vermogen tot morele afweging.

Het gebruik van AI in de totstandkoming van dit document verandert niets aan:
- de normatieve keuzes  
- de ethische positie  
- de verantwoordelijkheid voor consequenties  

Alle standpunten in UCSF zijn menselijke keuzes.

### 10.2 Verantwoordelijkheid blijft menselijk

UCSF verwerpt expliciet elke verschuiving van verantwoordelijkheid naar:
- “het systeem”  
- “het algoritme”  
- “onvoorziene emergente effecten”  

Wanneer systemen schade veroorzaken, ligt verantwoordelijkheid bij degenen die:
- het systeem hebben ontworpen  
- het systeem hebben ingezet  
- het systeem hebben opgeschaald  
- het systeem hebben laten voortbestaan ondanks bekende risico’s  

Technische complexiteit ontslaat niet van morele plicht.

### 10.3 Transparantie over totstandkoming

Het expliciet benoemen van AI-ondersteuning is geen zwakte, maar een vereiste van ethische transparantie. Juist in een tijd waarin menselijke en geautomatiseerde besluitvorming steeds meer vervlochten raken, is duidelijkheid over auteurschap essentieel.

UCSF beschouwt deze transparantie als voorbeeld, niet als uitzondering.

### 10.4 Slotstelling

Ethiek kan niet worden geautomatiseerd.

Zij vereist menselijke afweging, verantwoordelijkheid en bereidheid tot consequenties. Zonder deze elementen verwordt ethiek tot retoriek.

[⬆ Terug naar inhoudsopgave](#inhoudsopgave)

---

<a id="dankwoord"></a>
## Dankwoord

UCSF is ontstaan uit observatie, ervaring en langdurige ethische reflectie op digitale systemen en hun impact op mensenlevens. Het kader is niet voortgekomen uit één discipline, één incident of één theoretisch model, maar uit het samenkomen van technische, maatschappelijke en morele vragen die te vaak afzonderlijk worden behandeld.

Dit document is mede gevormd door bestaande academische literatuur, publieke debatten en maatschappelijke ontwikkelingen. Tegelijkertijd is het expliciet geen samenvatting van bestaand werk, maar een zelfstandig normatief standpunt.

Dank gaat uit naar:
- onderzoekers en denkers die ethiek niet reduceren tot abstractie  
- kritische stemmen die structurele schade zichtbaar maken  
- en allen die bereid zijn ethische grenzen te benoemen, ook wanneer dit ongemakkelijk is  

UCSF is geen afgesloten project. Het wordt aangeboden voor toetsing, kritiek en verdere verdieping, met behoud van zijn kernprincipes.

De verantwoordelijkheid voor de inhoud, keuzes en formuleringen berust volledig bij de auteur.

[⬆ Terug naar inhoudsopgave](#inhoudsopgave)
---

<a id="slotbeschouwing"></a>
## Slotbeschouwing

Dit document is geschreven vanuit de overtuiging dat de ethische vraagstukken rond digitale systemen niet langer kunnen worden behandeld als randvoorwaarden, optimalisatieproblemen of toekomstige aandachtspunten. Zij vormen het hart van de systemen zelf.

UCSF maakt zichtbaar dat veel van de schade die vandaag wordt toegeschreven aan “misbruik”, “complexiteit” of “onvoorziene effecten”, in werkelijkheid voortkomt uit herhaalbare ontwerppatronen en structurele keuzes. Wanneer consent niet herroepbaar is, wanneer veiligheid pas volgt na schade, en wanneer herstel geen integraal onderdeel vormt van systeemarchitectuur, is de uitkomst niet toevallig maar voorspelbaar.

Het kader stelt daarom geen nieuwe morele idealen voor, maar benoemt minimale ethische voorwaarden. Het maakt expliciet waar grenzen liggen, en erkent dat niet iedere technologische mogelijkheid ook een ethisch verdedigbare implementatie kent. In die zin is UCSF evenzeer een kader voor beoordeling als voor weigering.

Belangrijk is dat UCSF geen claim legt op volledigheid of finaliteit. Het is geen sluitend moreel systeem en geen universeel antwoord. Het biedt een structuur waarbinnen verantwoordelijkheid kan worden genomen, keuzes expliciet worden gemaakt en schade niet langer kan worden wegverklaard.

Wat UCSF uiteindelijk onderscheidt, is niet de complexiteit van zijn principes, maar de eenvoud van zijn kernstelling:  
wanneer systemen macht uitoefenen over menselijke autonomie, veiligheid of bestaanszekerheid, dan is ethische verantwoordelijkheid geen optionele laag maar een fundamentele ontwerpeis.

Die verantwoordelijkheid kan niet worden gedelegeerd.  
Zij blijft menselijk.

Tijdens het werken aan dit project werd voor de auteur steeds duidelijker dat de technologische ontwikkeling en implementatie van AI-systemen zich in een uitzonderlijk hoog tempo voltrekt. Zelfs binnen de looptijd van dit onderzoek vonden significante verschuivingen plaats, waardoor het onmogelijk bleek om alle concrete ontwikkelingen afzonderlijk en uitputtend te verwerken.

Deze snelheid vormt echter geen randverschijnsel, maar een wezenlijk onderdeel van het probleem dat dit document adresseert. Juist het tempo waarmee AI-technologieën worden ontwikkeld en uitgerold — vaak sneller dan normatieve, juridische en maatschappelijke reflectie kan bijbenen — vergroot de urgentie van een kader dat niet afhankelijk is van specifieke toepassingen of momentopnames.

Daarbij speelt ook de maatschappelijke impact van deze ontwikkelingen een doorslaggevende rol. De effecten van grootschalige digitale systemen manifesteren zich niet uitsluitend technisch, maar raken fundamentele aspecten van autonomie, veiligheid, zichtbaarheid en bestaanszekerheid. Deze cumulatieve impact verleent dit werk niet alleen relevantie, maar ook urgentie.

In die zin is UCSF niet louter een theoretische exercitie, maar een noodzakelijke bijdrage aan een debat dat zich sneller ontwikkelt dan de structuren die het zouden moeten begrenzen.

[⬆ Terug naar inhoudsopgave](#inhoudsopgave)

---

<a id="licentie-en-gebruik"></a>
## Licentie en Gebruik

Dit document wordt beschikbaar gesteld ten behoeve van academische, maatschappelijke en beleidsmatige reflectie op ethiek, consent en veiligheid in digitale systemen.

### Toegestaan gebruik

Dit document mag vrij worden:
- gelezen, gedeeld en geciteerd;
- gebruikt voor niet-commerciële educatieve, academische en onderzoeksdoeleinden;
- besproken in publieke debatten, peer reviews en beleidscontexten;

mits correcte bronvermelding plaatsvindt en de inhoud niet selectief of misleidend wordt gerepresenteerd.

### Beperkingen

Het Universal Consent & Safety Framework (UCSF):
- is geen certificering, keurmerk of compliance-label;
- mag niet worden gebruikt om producten, platforms of diensten impliciet of expliciet als “ethisch goedgekeurd” te positioneren;
- mag niet commercieel worden geëxploiteerd zonder expliciete toestemming van de auteur;
- mag niet worden aangepast of herverpakt op een wijze die de normatieve strekking, grenzen of ethische weigeringen ondermijnt.

Gebruik van UCSF-termen, -structuur of -taal in marketing, branding of productclaims zonder inhoudelijke implementatie wordt expliciet afgewezen.

### Auteurschap en verantwoordelijkheid

De intellectuele eigendom van dit document berust bij de auteur.  
Het kader weerspiegelt diens normatieve positie en ontwerpethische visie ten tijde van publicatie.

Interpretatie, toepassing of implementatie van UCSF in concrete systemen blijft de verantwoordelijkheid van de implementerende partij. Verwijzing naar dit document ontslaat geen enkele actor van eigen ethische, juridische of maatschappelijke verantwoordelijkheid.

### Doorontwikkeling en versies

UCSF is een levend kader. Toekomstige versies kunnen worden gepubliceerd op basis van maatschappelijke ontwikkelingen, peer review en voortschrijdend inzicht. Eerdere versies blijven traceerbaar en geldig binnen hun context.

---

<a id="uitnodiging-tot-peer-review"></a>
## Uitnodiging tot Peer Review

Het Universal Consent & Safety Framework (UCSF) wordt expliciet aangeboden voor open academische, maatschappelijke en interdisciplinaire toetsing.

Kritische analyse, inhoudelijke tegenargumenten, aanvullende literatuur en reflecties op toepasbaarheid zijn welkom. Peer review wordt niet benaderd als bevestiging, maar als noodzakelijke stap in het aanscherpen van normatieve grenzen en ontwerpethische uitgangspunten.

### Wie worden uitgenodigd

Bijzonder wordt een reactie verwelkomd van:
- AI-ethici en filosofen;
- juristen en beleidsdeskundigen op het gebied van technologie en mensenrechten;
- ontwerpers en engineers van digitale systemen met maatschappelijke impact;
- onderzoekers in platformstudies, governance en digitale arbeid;
- maatschappelijke organisaties die werken op het snijvlak van technologie en kwetsbare groepen.

### Hoe feedback kan worden aangeleverd

Inhoudelijke feedback, opmerkingen en peer-reviewbijdragen kunnen worden aangeleverd via:

- **GitHub (voorkeur):**  
  via issues of pull requests in de openbare repository waar dit document wordt beheerd.  
  Dit waarborgt transparantie, versiebeheer en publieke discussie.

- **E-mail:**  
  voor langere bijdragen, formele peer reviews of wanneer publieke bespreking niet wenselijk is.

### Contact

- **Naam:** Martijn Bruzzese  
- **Project / kader:** Universal Consent & Safety Framework (UCSF)  
- **GitHub:** https://github.com/MartijnBruzzese  
- **E-mail: martijnbruzzese@gmail.com**

Bijdragen worden gelezen, gedocumenteerd en waar relevant verwerkt in toekomstige versies. Reacties worden niet gefilterd op instemming, maar op inhoudelijke kwaliteit.

---

<a id="toegankelijkheid-van-bronnen"></a>
## Toegankelijkheid van bronnen

De in dit document gebruikte bronnen bestaan uit een combinatie van
peer-reviewed artikelen, academische boeken en publieke beleidsdocumenten.
Niet alle bronnen zijn vrij toegankelijk; dit is gebruikelijk binnen
academisch onderzoek.

Waar mogelijk zijn open-access versies geraadpleegd. In andere gevallen
zijn gezaghebbende edities gebruikt zoals uitgegeven door universitaire
uitgeverijen. Alle bronnen zijn volledig traceerbaar via academische
zoekmachines zoals Google Scholar en universitaire bibliotheken.

--- 

<a id="referenties--literatuurlijst"></a>
<a id="referenties"></a>
## Referenties / Literatuurlijst

De onderstaande bronnen onderbouwen de normatieve, ethische en structurele uitgangspunten van het Universal Consent & Safety Framework (UCSF).

<span id="ref-1"></span>

[1] Benjamin, R. (2019).  
*Race After Technology: Abolitionist Tools for the New Jim Code*.  
Polity Press.  
— Kritische analyse van algoritmische bias, structurele ongelijkheid en technologische macht.

**Bron:** [Hier te vinden](https://www.ruhabenjamin.com/)

↩ [Terug naar hoofdstuk 1](#ch-1)  
↩ [Terug naar hoofdstuk 7](#ch-7)

<hr>

<span id="ref-2"></span>

**[2] Floridi, L., Cowls, J., et al. (2018).**  
AI4People—An Ethical Framework for a Good AI Society. *Minds and Machines*, 28(4), 689–707.  
— Europese principes voor verantwoorde AI-ontwikkeling.

**Bron:** [Hier te vinden](https://link.springer.com/article/10.1007/s11023-018-9482-5)

↩ [Terug naar hoofdstuk 1](#ch-1)  
↩ [Terug naar hoofdstuk 7](#ch-7)

<hr>

<span id="ref-3"></span>

**[3] Binns, R. (2018).**  
Fairness in Machine Learning: Lessons from Political Philosophy. *(veel geciteerd position paper / survey-achtig werk in fairness-discussie)*  
— Fairness als normatief vraagstuk; waarom “technische fairness” zonder waardenkader vaak faalt.

**Bron:** [Hier te vinden](https://arxiv.org/abs/1712.03586)

↩ [Terug naar hoofdstuk 2](#ch-2)

<hr>

<span id="ref-4"></span>

**[4] Nissenbaum, H. (2010).**  
*Privacy in Context: Technology, Policy, and the Integrity of Social Life*. Stanford University Press.  
— Contextuele benadering van privacy en consent (contextual integrity).

**Bron:** [Hier te vinden](https://www.sup.org/books/law/privacy-context)

↩ [Terug naar hoofdstuk 3](#ch-3)  
↩ [Terug naar hoofdstuk 7](#ch-7)

<hr>

<span id="ref-5"></span>

**[5] Gillespie, T. (2018).**  
*Custodians of the Internet: Platforms, Content Moderation, and the Hidden Decisions That Shape Social Media*. Yale University Press.  
— Analyse van platformmacht, moderatie en private governance-structuren.

**Bron:** [Hier te vinden](https://yalebooks.yale.edu/book/9780300261431/custodians-of-the-internet/)

↩ [Terug naar hoofdstuk 1](#ch-1)  
↩ [Terug naar hoofdstuk 5](#ch-5)  
↩ [Terug naar hoofdstuk 8](#ch-8)

<hr>

<span id="ref-6"></span>

**[6] van Dijck, J., Poell, T., & de Waal, M. (2018).**  
*The Platform Society: Public Values in a Connective World*. Oxford University Press.  
— Platformisering en structurele impact op publieke waarden.

**Bron:** [Hier te vinden](https://global.oup.com/academic/product/the-platform-society-9780190889777)

↩ [Terug naar hoofdstuk 1](#ch-1)  
↩ [Terug naar hoofdstuk 5](#ch-5)  
↩ [Terug naar hoofdstuk 8](#ch-8)

<hr>

<span id="ref-7"></span>

**[7] Gray, M. L., & Suri, S. (2019).**  
*Ghost Work: How to Stop Silicon Valley from Building a New Global Underclass*. Houghton Mifflin Harcourt.  
— Digitale arbeid en onzichtbare menselijke kosten.

**Bron:** [Hier te vinden](https://books.google.com/books/about/Ghost_Work.html?id=u10-uQEACAAJ)

↩ [Terug naar hoofdstuk 1](#ch-1)  
↩ [Terug naar hoofdstuk 6](#ch-6)

<hr>

<span id="ref-8"></span>

**[8] Europese Unie (2022).**  
*Digital Services Act (DSA)* — Regulation (EU) 2022/2065.  
— Platformverantwoordelijkheid en systeemtoezicht binnen de EU.

**Bron:** [Hier te vinden](https://eur-lex.europa.eu/eli/reg/2022/2065/oj)

↩ [Terug naar hoofdstuk 9](#ch-9)

<hr>

<span id="ref-9"></span>

**[9] IEEE (2019).**  
*Ethically Aligned Design (EAD), v2*.  
— Mensgerichte waarden, accountability en ontwerpprincipes voor autonome/intelligente systemen.

**Bron:** [Hier te vinden](https://standards.ieee.org/wp-content/uploads/import/documents/other/ead_v2.pdf)

↩ [Terug naar hoofdstuk 3](#ch-3)  
↩ [Terug naar hoofdstuk 4](#ch-4)  
↩ [Terug naar hoofdstuk 8](#ch-8)

<hr>

<span id="ref-10"></span>

**[10] Pasquale, F. (2015).**  
*The Black Box Society: The Secret Algorithms That Control Money and Information*. Harvard University Press.  
— Transparantie, accountability en machtsasymmetrie door “black box” systemen.

**Bron:** [Hier te vinden](https://www.hup.harvard.edu/books/9780674970847)

↩ [Terug naar hoofdstuk 4](#ch-4)  
↩ [Terug naar hoofdstuk 9](#ch-9)

<hr>

<span id="ref-11"></span>

**[11] Jones, N. (2018).**  
How to stop data centres from gobbling up the world’s electricity. *Nature*, 561, 163–166.  
— Energie- en schaalproblematiek van datacenters.

**Bron:** [Hier te vinden](https://www.nature.com/articles/d41586-018-06610-y)

↩ [Terug naar hoofdstuk 6](#ch-6)

<hr>

<span id="ref-12"></span>

**[12] OECD (2021).**  
*The Environmental Impacts of Artificial Intelligence*. OECD Publishing.  
— Milieu-impact van AI- en datasystemen.

**Bron:** [Hier te vinden](https://www.oecd.org/digital/the-environmental-impacts-of-artificial-intelligence-7babf571-en.htm)

↩ [Terug naar hoofdstuk 6](#ch-6)

<hr>

<span id="ref-13"></span>

**[13] Crawford, K. (2021).**  
*Atlas of AI: Power, Politics, and the Planetary Costs of Artificial Intelligence*. Yale University Press.  
— Materiële kosten: grondstoffen, arbeid, infrastructuur en geopolitiek van AI.

**Bron:** [Hier te vinden](https://yalebooks.yale.edu/book/9780300209570/atlas-of-ai/)

↩ [Terug naar hoofdstuk 8](#ch-8)

<hr>

<span id="ref-14"></span>

**[14] UNESCO (2021).**  
*Recommendation on the Ethics of Artificial Intelligence*.  
— Internationale normering: mensenrechten, governance, proportionaliteit.

**Bron:** [Hier te vinden](https://unesdoc.unesco.org/ark:/48223/pf0000380455)

↩ [Terug naar hoofdstuk 9](#ch-9)

<hr>

<span id="ref-15"></span>

**[15] Foucault, M. (1977).**  
*Discipline and Punish: The Birth of the Prison*. Vintage Books.  
— Macht, disciplinering en systemische controle (analytisch kader).

**Bron:** [Hier te vinden](https://books.google.com/books/about/Discipline_and_Punish.html?id=pWv1R2o_PWsC)

↩ [Terug naar hoofdstuk 9](#ch-9)


**Opmerking:**  
UCSF is normatief en ontwerpgericht. Deze referenties dienen ter academische verankering, niet als uitputtend literatuuroverzicht.

<small><a href="#inhoudsopgave">↑ inhoud</a></small>
