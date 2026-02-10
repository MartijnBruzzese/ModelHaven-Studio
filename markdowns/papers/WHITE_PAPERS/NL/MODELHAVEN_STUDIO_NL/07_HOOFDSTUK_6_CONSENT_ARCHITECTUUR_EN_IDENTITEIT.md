<a id="h6"></a>
## Hoofdstuk 6 — Identiteit en Consent Tokens

Waar eerdere hoofdstukken de normatieve en operationele kaders beschrijven, richt dit hoofdstuk zich op de technische vertaling van toestemming en identiteit binnen ModelHaven Studio.

Centraal hierin staan **consent tokens**: tijdelijke, contextgebonden en herroepbare representaties van toestemming die systeemgedrag expliciet sturen.

Identiteit fungeert hierbij niet als bezit, maar als **voorwaarde voor bescherming**.

---

### 6.1 Van impliciete toestemming naar expliciete tokens

In veel huidige systemen wordt toestemming impliciet afgeleid uit:

- accountstatus;
- eerdere interacties;
- algemene gebruiksvoorwaarden.

ModelHaven Studio verwerpt deze benadering.

Toestemming wordt hier uitsluitend erkend wanneer zij:

- expliciet is vastgelegd;
- contextueel gedefinieerd;
- tijdelijk geldig;
- en actief herroepbaar.

Consent tokens representeren deze toestand op systeemniveau.

Zonder geldig token vindt geen actie plaats.

---

### 6.2 Eigenschappen van consent tokens

Consent tokens binnen ModelHaven Studio zijn:

- **tijdgebonden** (vervallen automatisch);
- **doelgebonden** (niet herbruikbaar buiten oorspronkelijke context);
- **scope-beperkt** (alleen geldig voor specifieke handelingen);
- **herroepbaar** (direct ongeldig te maken);
- **traceerbaar** (auditbaar zonder privacy-inbreuk).

Tokens bevatten geen identiteitsdata zelf, maar verwijzen naar beschermde identiteitslagen.

---

### 6.3 Identiteit als beschermlaag

Identiteit wordt technisch gescheiden van content en output.

Deze scheiding voorkomt:

- ongeautoriseerde koppeling;
- persistente profilering;
- onbedoelde hergebruikscenario’s.

Identiteitslagen zijn:

- rolgebonden;
- tijdelijk toegankelijk;
- en alleen zichtbaar voor subsystemen die ze functioneel nodig hebben.

Dit minimaliseert datalekrisico en machtsconcentratie.

---

### 6.4 Delegatie en meervoudige toestemming

Sommige situaties vereisen gedeelde verantwoordelijkheid, zoals bij:

- minderjarigen;
- zorgrelaties;
- juridische vertegenwoordiging;
- samenwerking tussen makers.

ModelHaven Studio ondersteunt daarom **meervoudige consent tokens**, waarbij meerdere partijen expliciet instemming moeten verlenen voordat acties plaatsvinden.

Geen enkele actor kan eenzijdig beschermingslagen opheffen.

---

### 6.5 Tokens en fail-closed gedrag

Wanneer:

- tokens ontbreken;
- tokens verlopen;
- of tokencontext niet overeenkomt met actuele intent;

dan treedt automatisch fail-closed gedrag in werking.

Het systeem stopt, vraagt herbevestiging of weigert verdere uitvoering.

Tokens zijn geen formaliteit, maar actieve stuurcomponenten.

---

### 6.6 Privacy-by-design en minimale blootstelling

Consent tokens zijn ontworpen volgens privacy-by-design principes:

- minimale datavelden;
- geen permanente identifiers;
- scheiding tussen toestemming en identiteit;
- encryptie in rust en tijdens transport.

Het doel is niet maximale controle, maar **minimale noodzakelijkheid**.

---

### 6.7 Samenvatting

Identiteit en consent tokens vormen samen de technische ruggengraat van ModelHaven Studio.

Zij zorgen ervoor dat:

- toestemming expliciet is;
- identiteit beschermd blijft;
- acties traceerbaar zijn;
- en falen leidt tot begrenzing.

In het volgende hoofdstuk wordt uitgewerkt hoe deze mechanismen worden ingebed in **bestuur, toezicht en menselijke tegenmacht**.

---

[Terug naar inhoudsopgave](#inhoudsopgave)