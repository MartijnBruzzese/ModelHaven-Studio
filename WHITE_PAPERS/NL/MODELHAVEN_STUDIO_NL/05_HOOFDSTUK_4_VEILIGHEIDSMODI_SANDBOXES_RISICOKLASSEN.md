<a id="h4"></a>
## Hoofdstuk 4 — Veiligheidsmodi, Sandboxes en Risicoklassen

Waar Hoofdstuk 3 de ethische fundamenten beschrijft, richt dit hoofdstuk zich op de operationele vertaling daarvan: hoe consent, identiteit en intent worden omgezet in concrete systeemgedragingen.

ModelHaven Studio hanteert hiervoor een gelaagde veiligheidsarchitectuur, bestaande uit **modi**, **sandboxes** en **risicoklassen**. Deze componenten functioneren niet los van elkaar, maar vormen samen een adaptief beschermingssysteem.

---

### 4.1 Veiligheidsmodi als interpretatiekader

Veiligheidsmodi bepalen de context waarin interacties worden geïnterpreteerd. Voorbeelden zijn:

- standaardmodus  
- creatieve modus  
- educatieve modus  
- adult-modus  
- journalistieke modus  

Elke modus activeert specifieke grenzen, toleranties en interpretatiekaders.

Belangrijk is dat modi **geen uitzonderingszones** zijn. Zij verruimen of verfijnen expressie, maar heffen nooit fundamentele beschermingsregels op. Consentvereisten, identiteitsbescherming en intentiesensoren blijven altijd actief.

---

### 4.2 Sandboxes als gecontroleerde experimenteerruimte

Sandboxes zijn afgebakende omgevingen waarin gebruikers kunnen experimenteren binnen strikt gedefinieerde grenzen.

Binnen ModelHaven Studio worden sandboxes ingezet om:

- creatieve vrijheid mogelijk te maken;
- risicovolle concepten te testen zonder externe impact;
- nieuwe interactievormen te verkennen.

Sandboxes zijn expliciet:

- tijdelijk;
- lokaal;
- niet-exporteerbaar zonder herbeoordeling;
- onderhevig aan automatische logging en patroonherkenning.

Zij bieden ruimte, maar geen vrijbrief.

---

### 4.3 Risicoklassen en dynamische escalatie

Elke interactie wordt door het systeem continu beoordeeld en toegewezen aan een risicoklasse.

Indicatieve categorieën zijn:

- laag risico (normale creatieve of informatieve interacties);
- verhoogd risico (ambigue intent, gevoelige context);
- hoog risico (seksualiteit, identiteit, kwetsbare groepen);
- kritisch risico (patronen van misbruik of grensoverschrijding).

Bij oplopend risico past het systeem automatisch beschermingsniveaus aan:

- extra verificatie;
- beperking van functionaliteit;
- overgang naar sandbox;
- tijdelijke weigering.

Deze escalatie verloopt gradueel en contextueel, niet binair.

---

### 4.4 Fail-closed gedrag als ontwerpprincipe

Wanneer het systeem onvoldoende zekerheid heeft over:

- geldige toestemming;
- identiteit;
- of intent,

treedt fail-closed gedrag in werking.

Dit betekent:

- geen output boven onzekere drempels;
- geen optimalisatie onder twijfel;
- expliciete weigering met transparante motivatie.

Fail-closed is geen strafmechanisme, maar een beschermingslogica.

---

### 4.5 Menselijke interventie en governance

Hoewel veel processen automatisch verlopen, blijft menselijke tussenkomst essentieel.

ModelHaven Studio voorziet in:

- escalatiepaden naar menselijke reviewers;
- transparante logging;
- audit trails;
- mogelijkheid tot handmatige override binnen strikt afgebakende kaders.

Automatisering ondersteunt ethiek, maar vervangt haar niet.

---

### 4.6 Adaptiviteit zonder normalisatie van risico

Een belangrijk onderscheid met bestaande systemen is dat ModelHaven Studio niet optimaliseert voor “gewenning”.

Herhaald grensoverschrijdend gedrag leidt niet tot versoepeling, maar tot verscherping. Patronen van misbruik worden niet gemodelleerd als voorkeuren, maar als signalen voor verhoogde bescherming.

Het systeem leert niet om risico te tolereren.

---

### 4.7 Samenvatting

Veiligheidsmodi, sandboxes en risicoklassen vormen samen een adaptieve beschermingsarchitectuur.

Zij zorgen ervoor dat:

- context wordt herkend;
- risico wordt geschaald;
- twijfel leidt tot begrenzing;
- en menselijke verantwoordelijkheid ingebed blijft.

In het volgende hoofdstuk wordt uitgewerkt hoe deze structuur wordt aangevuld met **niet-onderhandelbare bescherming en expliciete faalmodi**.