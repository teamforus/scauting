## Leer het systeem kennen!
**Let op!** Voordat je begint met de werkzaamheden willen we je vragen om eerst kennis te maken met ons systeem om algemene informatie te hebben. [Leer het systeem kennen!](https://github.com/teamforus/scauting/blob/master/opdrachten/README.md)

Heb je het systeem al leren kennen? Lees dan verder en succes!

# Testen

Forus levert aan haar opdrachtgevers een SaaS (Software as a Service) oplossing.
Dit betekent dat de verschillende opdrachtgevers gebruik maken van dezelfde applicatie die via een webomgeving te benaderen is. 
Daarnaast doet Forus het beheer, onderhoud en de doorontwikkeling van de applicatie.

Huidige of nieuwe opdrachtgevers hebben verschillende wensen wat betreft de functionaliteiten die de applicatie biedt. Hierdoor hebben wij doorgaans te maken met doorontwikkeling van de applicatie.

Een belangrijk onderdeel van de werkzaamheden bij Forus is het testen van alle functionaliteiten die worden ontwikkeld. Het testen van software komt in verschillende maten en vormen. Wij zullen ons focussen op "Functional Testing" en dan specifiek op de functionaliteiten. Dit betekent dat je gaat controleren of de applicatie werkt zoals bedoeld. Daarnaast willen we je vragen om kritisch te kijken naar de gebruikerservaring.

## Wat ga je testen?

Forus bouwt een generiek platform voor de uitwisseling van waarde. In de praktijk betekent dit dat wij een systeem maken voor gemeenten om geld beschikbaar te stellen aan mensen met een lager inkomen die dit vervolgens weer kunnen uitgeven bij leveranciers die de op voorhand goedgekeurd zijn door de gemeente.

Het systeem bestaat uit:
- Een webshop
- Dashboards
- Mobiele applicatie

**<details><summary>Wil je meer uitleg over het systeem? Klik dan hier! </summary>**

**Webshop**<br>
Elke gemeente heeft een eigen webshop die wordt gebruikt door haar inwoners. De inwoners kunnen via de webshop hun vouchers (budgetten met de daarbijbehorende QR code) en aanbiedingen inzien. Daarnaast kunnen zij hier ook de locaties van de aanbieders vinden waar zij het geld kunnen besteden.

**Sponsor dashboard**<br>
De medewerkers van de gemeente maken gebruikt van het sponsor dashboard om geld beschikbaar te stellen, aanbieders goed te keuren en management informatie bij te houden.

**Provider dashboard**<br>
De aanbieders maken gebruik van het provider dashboard om zich aan te melden voor een regeling, aanbiedingen te plaatsen en transacties bij te houden.

**Me-app**<br>
De Me-app wordt vooral gebruikt door de aanbieders als kassa scanner. Met de Me app scannen zij QR Codes om betalingen te kunnen doen.
Daarnaast wordt de Me-app ook gebruikt door inwoners om vouchers te beheren. 
</details>

**<details><summary>Wil je een opfrisser van hoe het werkt? Klik dan hier!</summary>**
Eerder hebben jullie een demo gekregen van het systeem. Wil je graag een opfrisser bekijk dan de filmpjes over het systeem op onze website!

Bekijk [hier](https://forus.io) de filmpjes. Kies onder het video player een rol om een ander filmpje te zien.
</details>

## Wat heb je nodig?

Om de werkzaamheden met betrekking tot het testen uit te kunnen voeren heb je het volgende nodig:

- Github
- Toegang tot de testpaden
- Toegang tot de testomgeving
- Een testversie van de Me-app

## Waar kan je deze informatie vinden?
Hieronder vindt je een lijst met alles wat je nodig hebt om de werkzaamheden uit te voeren. Klik op een link om een op de pagina of download te openen.

| Wat          | Waar                                                      |
|--------------------|------------------------------------------------------------|
| Testscenarios      | [GitHub](https://github.com/teamforus/scauting/issues)                            |
| Testomgeving   | [Webshop Berkelland](https://staging.berkelland.forus.io)<br>[Webshop Winterswijk](https://staging.winterswijk.forus.io)<br>[Webshop Oostgelre](https://staging.oostgelre.forus.io)<br> |
| Tijdelijke e-mailadres aanmaken | [https://asdasd.nl](https://asdasd.nl) |
| Test versie Me-app | [Android](https://drive.google.com/file/d/1rP6ALApMVI2v52_BhGBXc-oplona4ZAR/view?usp=sharing)<br>Me-iOS: Stuur Gerben een bericht via Rocket.Chat. |

> **_TIP:_**  Maak gebruik van meerdere open tabbladen tijdens het uitvoeren van de werkzaamheden. Maak het jezelf makkelijk en probeer hier een structuur in aan te houden.
 
## Hoe voer je deze taken uit?

### Test scenarios

Om een test uit te kunnen voeren dien je een test scenario te doorlopen. Een test scenario is een voorgeschreven template (sjabloon) om de uitgevoerde test te kunnen documenteren. In een template staan specificaties van de test en een stappenplan om de test uit te kunnen voeren. Bekijk de tabel hieronder om een voorbeeld van de specificaties te zien.

**<details><summary>Wil je een lijst met alle specificaties in een test scenario zien? Klik dan hier!</summary>**

| Omschrijving  | Toelichting                                    |                                                |
|---------------|------------------------------------------------|------------------------------------------------|
| Environment   | - versienummer<br> - database                      | vooraf ingevuld in template                    |
| Preconditions | Voorwaarden om test uit te kunnen voeren       | vooraf ingevuld in template                    |
| Direct URLs   | Welke links dien je te gebruiken voor de test  | vooraf ingevuld in template |
| Input data    | Welke data gebruik je om de test uit te voeren | tester dient gebruike data te registreren      |
| Prerequisites | Wat heb je nodig om de test uit te voeren      | vooraf ingevuld in template                                                |
| Instructions  | Stappenplan om test scenario uit te voeren     | vooraf ingevuld in template                                                |
| Result        | Testresultaat (pass/fail)                      | tester dient testresultaat te registreren      |
| Notes         | Bijzonderheden                                 | tester registreert bijzonderheden indien nodig |

</details>

### Werkinstructies

1. Ga naar [Github](https://github.com/teamforus/scauting/issues)
2. Klik op **New issue**.
3. Kies een test scenario en klik op **Get started**
4. Klik op **Submit new issue** om de test te starten.
5. Volg het stappenplan van het test scenario.
6. Gebruik de comment section om de test data te registreren en klik op **Comment**
7. Gebruik een label om een test resultaat aan te geven, kies voor "fail" of "pass".
8. Is de test gelaagd? Klik dan op **Close issue** om de test te sluiten.
9. Is de test gefaald? Assign Gerben dan aan de issue.

### Waar kan je terecht voor vragen?
- Rocket.Chat:
	- Scauting kanaal
	- Of stel je vraag direct aan Gerben
