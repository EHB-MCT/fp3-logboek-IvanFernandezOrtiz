# Logboek

**Datum:** `[28/01/2025]`  
**Studentnaam:** `[Ivan Fernandez]`  
**Groepsnaam:** `[A2]`

---

## 1) Wat heb ik vandaag gedaan voor mijn project?

*Instructie (schrijf in bullets waar je aan gewerkt hebt):*  
- connectie gemaakt met mongoDb zodat de sorrydoos kan worden opgeslagen met een TTL
- sorrykaart.js, liedPreview.js en teken.js aangepast zodat je na het maken van het item ze kunt opslaan in de database. Dit zul je dan later kunnen zien met de link dat je deelt. 
- Na beantwoorden van de vragen en de resultaat lezen wordt een doos gemaakt in de database dat in het begin leeg is. Deze wordt dan gevuld na bijvoorbeeld het maken van een tekening en klikken op 'voeg toe'. Je kunt de tekening veranderen door het opnieuw te doen.
- LocalStorage gebruikt om de id van de lege doos te bewaren om zo de items hieraan toe te voegen.
- Get path gemaakt zodat je de inhoud van de doos kunt zien (momenteel lukt dat enkel via postman, dit is nog niet in de site verwerkt)
- Localstorage gebruikt om de prompt van het genereren van het liedje bij te sturen m.b.v. de antwoorden op de vragen bij de reflectie.

> **Activiteiten:**  
> - .env file aangepast zodat het de login gegevens heeft en ik zo aan de database kan
> - Paths gemaakt om eerst alle items afzonderlijk op te slaan. Eerst ben ik begonnen met de kaart op te slaan daarna de tekening en ten laatste het liedje. 
> - Nadat de paths gemaakt werden heb ik ervoor gezorgd dat er een lege doos object gemaakt wordt dat een Time To Live (TTL) heeft zodat de doos na een bepaalde tijd wordt verwijderd. Het object heeft een Id, song, tekening, sorryKaart, aanmaakdatum en delete tijd. 
> - Localstorage gebruikt om de boxId te bewaren bij het maken van de doos en boxId mee te geven bij het toevoegen van items zoals de tekening.
> - Eenmaal de lege doos object klaar was heb ik de POST paths veranderd naar PATCH. Dit is zodat ik in plaats van een nieuwe item te maken de gemaakte items in de doos kon zetten. 
> - Localstorage gebruikt om na het antwoorden van alle vragen de vragen en antwoorden op te slaan om later te kunnen gebruiken bij het genereren van het liedje

---
## 2) Wat heb ik nieuw geleerd of voor het eerst zelf gedaan?

*Instructie (1 item per dag volstaat):*  
- Hoe ik met localstorage moet werken
- Hoe ik collections kan maken dat maar gedurende een bepaalde tijd blijven.


> **Nieuwe skills:**  
> - LocalStorage gebruiken in javascript
> - TTL bij collections in MongoDb plaatsen
---

## 3) Wat is mijn gevoel over vandaag?

*Instructie:*  
- Noteer in 1 zin hoe je je voelt.  
- Voeg een kleur of symbool toe dat je stemming weergeeft (bijv. een donderwolk bij boosheid of een happy smiley als je tevreden bent).


> **Algemeen gevoel:**  
> - **"Tevreden"** :smiley:  
>

---

