Use-Cases
### UC01: Nieuwe Items Monitoren op Vinted

| _Naam_           | UC01: Nieuwe Items Monitoren op Vinted                                                                                                                                                                                                                                                                   |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| _Samenvatting_   | Het systeem controleert Vinted op nieuw geplaatste items en stuurt notificaties naar gebruikers.                                                                                                                                                                                                         |
| _Actors_         | Systeem                                                                                                                                                                                                                                                                                                  |
| _Aannamen_       | Het systeem is actief en gebruikers hebben hun voorkeuren al ingesteld.                                                                                                                                                                                                                                  |
| _Scenario_       | <ol><li>Het systeem vraagt Vinted om nieuw geplaatste items.</li><li>Het systeem vergelijkt deze items met de voorkeuren van de gebruiker.</li><li>Items die voldoen aan de voorkeuren worden opgeslagen in de database.</li><li>Een notificatie wordt verstuurd naar de relevante gebruikers.</li></ol> |
| _Uitzonderingen_ | <ol><li>Als er geen nieuwe items worden gevonden, blijft het systeem monitoren zonder actie.</li><li>Als Vinted onbereikbaar is, probeert het systeem het later opnieuw.</li></ol>                                                                                                                       |
| _Resultaat_      | Nieuwe relevante items worden opgeslagen in de database en notificaties worden verzonden naar gebruikers.                                                                                                                                                                                                |

---

### UC02: Gebruikersvoorkeuren Instellen

|_Naam_|UC02: Gebruikersvoorkeuren Instellen|
|---|---|
|_Samenvatting_|De gebruiker stelt zijn voorkeuren in om notificaties te ontvangen voor relevante nieuwe items.|
|_Actors_|Gebruiker|
|_Aannamen_|De gebruiker is ingelogd en heeft toegang tot de voorkeurenpagina.|
|_Scenario_|<ol><li>De gebruiker navigeert naar de voorkeurenpagina.</li><li>De gebruiker selecteert criteria zoals categorie, prijs, merk en maat.</li><li>De gebruiker verstuurt de voorkeuren.</li><li>Het systeem slaat de voorkeuren op in de database.</li></ol>|
|_Uitzonderingen_|<ol><li>Als ongeldige voorkeuren worden ingevoerd, vraagt het systeem om correctie.</li><li>Als het opslaan van voorkeuren mislukt, ontvangt de gebruiker een foutmelding.</li></ol>|
|_Resultaat_|De voorkeuren van de gebruiker worden succesvol opgeslagen en gebruikt om nieuwe items te filteren.|

---

### UC03: Bekijken van Items op het Webdashboard

| _Naam_           | UC03: Bekijken van Items op het Webdashboard                                                                                                                                                                                                                                                                                            |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| _Samenvatting_   | De gebruiker bekijkt nieuwe items die door het systeem zijn gedetecteerd via het webdashboard.                                                                                                                                                                                                                                          |
| _Actors_         | Gebruiker                                                                                                                                                                                                                                                                                                                               |
| _Aannamen_       | De gebruiker is ingelogd en heeft notificaties ontvangen voor nieuwe items.                                                                                                                                                                                                                                                             |
| _Scenario_       | <ol><li>Het dashboard toont een overzicht van nieuwe items.</li><li>De gebruiker klikt op een item voor meer details.</li><li>De gebruiker kan de items favoriten</li><li>De gebruiker kan op een item clicken om het item op vinted te bekijken.</li><li>De gebruiker de images swipen om zo all fotos van een item te zien.</li></ol> |
| _Uitzonderingen_ | <ol><li>Als een item buiten de fitlers valt word het item niet getoond</li></ol>                                                                                                                                                                                                                                                        |
| _Resultaat_      | De gebruiker kan relevante items bekijken en actie ondernemen (bijv. kopen of opslaan).                                                                                                                                                                                                                                                 |

---

### UC04: Lijst met gevonden items weergeven

| _Naam_           | UC04: Lijst met gevonden items weergeven                                                                                                                                                                 |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| _Samenvatting_   | De gebuiker kan een lijst met alle gevonden items bekijken met filters.                                                                                                                                  |
| _Actors_         | Gebruiker                                                                                                                                                                                                |
| _Aannamen_       | Het systeem heeft een of meerder items gevonden.                                                                                                                                                         |
| _Scenario_       | <ol><li>De gebruiker stelt filters in.</li><li>De gebruiker krijgt een lijst met de gefilterde items te zien</li><li>De Gebruiker kan op items klicken om het in vitned te openen of favoriten</li></ol> |
| _Uitzonderingen_ | <ol><li>Als er geen items binnen de filters vallen word er niks getoond.</li></ol>                                                                                                                       |
| _Resultaat_      | De gebruiker krijgt een lijst met gevonden items te zien.                                                                                                                                                |

---



