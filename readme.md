# LaboReeks Git
## **Labo 5**

In dit vijfde labo gaan we aan de slag met een aantal GitHub features. We zullen ook in dit labo een lokale repository gaan clonen waar we vervolgens alle lokale wijzigingen gaan synchroniseren met deze remote git repository (GitHub). 

Je eindresultaat van het labo zal op deze manier automatisch in deze GitHub repository terecht komen. Met andere woorden, voor dit labo **upload je niks manueel** op GitHub! 
Alles wat gevraagd wordt dien je lokaal toe te voegen en vervolgens via de nodige commandos ook in de online repository te brengen.
Indien er GitHub-specifieke features gevraagd worden dan kan je deze uiteraard uitvoeren op de remote repository zelf. Dit zal aangeduid worden op de taken die van toepassing zijn op GitHub-specifieke features.

#### **Aanvullende toets op Leho**
Na het afwerken van dit labo heb je op Leho een aanvullende toets met betrekking tot het labo en de leerstof gekoppeld aan het labo.
Je kan/mag de aanvullende toets steeds afleggen gebruik makend van alle bronnen (cursusmateriaal, labo, online bronnen, ...)

### **Labo 5:** *Takenlijst*
- [ ] Open de Git Bash Console op de locatie waar je dit labo wil gaan clonen. Dit kan via een rechtermuisklik op de locatie in kwestie en vervolgens de keuze **Git Bash Here** te selecteren.

- [ ] Zorg ervoor dat de startsituatie *(deze repository)* van het labo op jouw pc **gecloned** wordt. Maak hiervoor gebruik van het passende git commando. 

- [ ] Ga **na het clonen** via de Console naar de gecloonde repository. Dit kan/mag je uiteraard ook doen door de nieuwe aangemaakt folder aan te klikken en hier opnieuw een Git Bash console te openen via de **Git Bash Here** optie.
>**Tip!** Controleer voor je verder werkt of je al dan niet in de juiste git repository zit! Je kan dit snel visueel vaststellen in je console.

In de cursus kwam de manier van werken om een GitHub page draaiende te krijgen voor je eigen user aan bod.
In dit labo ga je aan de slag om een GitHub page te voorzien voor deze repository!
Het is de bedoeling dat je hier zelf wat extra opzoek- en/of uitzoekwerk doet om te achterhalen hoe dit precies werkt.

### Het project voorbereiden
Voor we zomaar aan de slag gaan met het publiceren van de GitHub page van deze repository maken we eerst de nodige voorbereiding.

- [ ] Maak een project bord aan **via GitHub** op de repository van dit labo. Geef je project bord de naam *Launch Lab Page*. Kies als template voor je Project de optie **Basic kanban**, dit zal volstaan voor onze noden.

- [ ] Zorg ervoor dat je in de **In progress** kolom van je project bord de keuze maakt om deze te automatiseren zodat pull requests die nieuw toegevoegd worden automatisch in deze kolom terecht komen.

- [ ] Zorg ervoor dat je in de **Done** kolom van je project bord de keuze maakt om deze te automatiseren zodat issues automatisch in deze kolom terecht komen wanneer deze de status **Closed** krijgen. Zorg ook voor deze kolom dat Pull Requests hierin terecht komen als ze de **Merged** status krijgen.

- [ ] Vervolgens ga je **via GitHub** naar de Labels op de repository van dit labo. Verwijder alle bestaande labels. Voeg nadien twee nieuwe labels toe, deze krijgen de naam *Must Have* en *Nice to Have*. Het kleurschema voor deze twee nieuwe labels is vrij te kiezen.

- [ ] **Via GitHub** maak je een nieuwe Milestone aan in de repository van dit labo. Geef deze Milestone de naam *First launch*. Plaats de **Due date** op de deadline van deze labo opdracht.

- **Via GitHub** maak je vervolgens onderstaande issues aan:

    - [ ] **Select page template**, wijs deze toe aan jezelf, wijs de Label *Must Have*, het project *Launch Lab Page* en de Milestone *First Launch* toe aan deze issue.
    - [ ] **Customise page template**, wijs deze toe aan jezelf, wijs de Label *Nice to Have*, het project *Launch Lab Page* en de Milestone *First Launch* toe aan deze issue.
    - [ ] **Configure GitHub Pages**, wijs deze toe aan jezelf, wijs de Label *Must Have*, het project *Launch Lab Page* en de Milestone *First Launch* toe aan deze issue.

- [ ] Ga vervolgens naar het project bord **via GitHub** op de repository van dit labo. Verwijder de 3 standaard cards die aanwezig zijn en zorg ervoor dat je 3 aangemaakte issues (in volgorde, de eerste issue komt bovenaan) in de **To do** kolom geplaatst worden.

- [ ] Maak in je lokale repository een nieuwe branch **dev** die aftakt van **master** en synchroniseer deze met de remote.

- [ ] Maak vanaf **dev** nog een branch in je lokale repository met naam **feature/preparation** en zorg ervoor dat je meteen ook op deze nieuwe branch werkt. Synchroniseer de nieuwe branch naar de remote.

- [ ] Maak vervolgens een screenshot van de **volledige** pagina van je project bord en plaats deze in de **lokale Screenshot folder** die je in je labo5 folder staan hebt. (Op jouw PC/laptop dus!) Geef deze screenshot de naam **deel1** (met extensie naar keuze).

- [ ] Maak gebruik van passende git commando's om de nieuw(e) bestand(en) te commiten naar git. Zorg ervoor dat je lokale wijzigingen vervolgens ook op je remote repository aanwezig zijn.

> **Tip!** Denk aan de conventies rondom naamgeving van de commit messages!

- [ ] Zorg door middel van een Pull Request **via GitHub** dat de wijzigingen die je aanbracht in de **feature/preparation** branch ook op je **dev** branch gemerged worden. Wijs deze Pull Request toe aan jezelf, het Label *Must Have*, het project, en de Milestone die we eerder aanmaakten.

> **Tip!** Vergeet niet om je Pull Request volledig af te werken.

### Ons project stap voor stap afwerken

- [ ] Sleep in je project bord de eerste issue *Select page template* naar de In progress kolom.

- [ ] Voorzie een branch in je lokale repository die je de naam **feature/template-selection** geeft (uiteraard weer afgetakt van **dev**) en zorg ervoor dat je meteen ook op deze nieuwe branch werkt.

- [ ] Maak vervolgens een screenshot van de **volledige** pagina van je project bord en plaats deze in de **lokale Screenshot folder** die je in je labo5 folder staan hebt. (Op jouw PC/laptop dus!) Geef deze screenshot de naam **deel2** (met extensie naar keuze).
 
- [ ] Maak gebruik van passende git commando's om de nieuw(e) bestand(en) te commiten naar git. **Denk eraan om deze commit correct te voorzien van een relatie met de huidige issue die In Progress is.** Zorg ervoor dat je lokale wijzigingen vervolgens ook op je remote repository aanwezig zijn.

> **Tip!** Denk aan de conventies rondom naamgeving van de commit messages!

- [ ] Selecteer een van de drie basis webpagina's die je terug kan vinden in de zip file **op Leho** voor dit labo.

- [ ] Zorg ervoor dat de gekozen webpagina met de bijhorende (nodige) bestanden correct in je lokale repository opgenomen worden. Dit in je **docs** mapje.

> **Tip!** Het is de bedoeling dat de homepage *index.html* van de gekozen template rechtstreeks onder *docs* komt te staan, dus **niet** in een subfolder. We zullen verder in het labo immers de nodige configuratie toevoegen zodat het *docs* mapje de root wordt van de GitHub page van deze repository.

- [ ] Maak gebruik van passende git commando's om de nieuw(e) bestand(en) te commiten naar git. Zorg ervoor dat je lokale wijzigingen vervolgens ook op je remote repository aanwezig zijn. **Zorg ervoor dat je in je commit message een referentie legt naar je issue en gebruik tevens een keyword dat ervoor zal zorgen dat na het mergen met de master branch je issue automatisch af zal sluiten.**

- [ ] Zorg door middel van een Pull Request **via GitHub** dat de wijzigingen die je aanbracht in de **feature/template-selection** branch ook op je **dev** branch gemerged worden. Wijs deze Pull Request toe aan jezelf, het Label *Must Have*, het project, en de Milestone die we eerder aanmaakten.

> **Tip!** Vergeet niet om je Pull Request volledig af te werken.

- [ ] Sleep in je project bord de derde issue *Configure GitHub pages* naar de In progress kolom.

- [ ] Voorzie een branch vanaf **dev** in je lokale repository die je de naam **feature/pages-configuration** geeft en zorg ervoor dat je meteen ook op deze nieuwe branch werkt. Synchroniseer de nieuwe branch met de remote.

- [ ] Maak vervolgens een screenshot van de **volledige** pagina van je project bord en plaats deze in de **lokale Screenshot folder** die je in je labo5 folder staan hebt. (Op jouw PC/laptop dus!) Geef deze screenshot de naam **deel3** (met extensie naar keuze).

- [ ] Maak gebruik van passende git commando's om de nieuw(e) bestand(en) te commiten naar git. **Denk eraan om deze commit correct te voorzien van een relatie met de huidige issue die In Progress is.** Zorg ervoor dat je lokale wijzigingen vervolgens ook op je remote repository aanwezig zijn.

- [ ] Zoek het nodige op om vervolgens je GitHub Pages voor je repository te activeren (als **publiek** beschikbare website). Zorg ervoor dat de **docs** map op de **master** branch gebruikt wordt als root van je site.

> **Tip!** Aangezien we nog niks naar de **master** branch gemerged hebben, is het normaal dat de site daar nog niet op staat en je dus een HTTP 404 (not found) error krijgt wanneer je je site wil bekijken via de publieke url. Op het einde van het labo gaan we alles merge naar **master** en kan je finaal controleren of je site goed getoond wordt.
  
- [ ] Neem op de locatie waar je dit doet een screenshot van de sectie genaamd *GitHub Pages* zodat de screenhot duidelijk de URL in je browser in combinatie met jouw instellingen toont. Plaats deze screenshot in de **lokale Screenshot folder** die je in je labo5 folder staan hebt. (Op jouw PC/laptop dus!) Geef deze screenshot de naam **deel4** (met extensie naar keuze).

- [ ] Maak gebruik van passende git commando's om de nieuw(e) bestand(en) te commiten naar git. Zorg ervoor dat je lokale wijzigingen vervolgens ook op je remote repository aanwezig zijn. **Zorg ervoor dat je in je commit message een referentie legt naar je issue en gebruik tevens een keyword dat ervoor zal zorgen dat na het mergen met de master branch je issue automatisch af zal sluiten.**

- [ ] Zorg door middel van een Pull Request **via GitHub** dat de wijzigingen die je aanbracht in de **feature/pages-configuration** branch ook op je **dev** branch gemerged worden. Wijs deze Pull Request toe aan jezelf, het Label *Must Have*, het project, en de Milestone die we eerder aanmaakten.

> **Tip!** Vergeet niet om je Pull Request volledig af te werken.

- [ ] Controleer of de **dev** branch effectief up to date is met je finale uitwerking.

- [ ] Ga in je lokale repository naar de **dev** branch en controleer of alle stappen in de takenlijst voor dit labo uitgevoerd werden. Pas hiervoor deze readme file aan zodat de checkboxes als afgevinkt weergegeven worden. 

> **Tip!** Vergeet niet om eerst je lokale dev branch eerst up to date te brengen met je remote dev branch. Alle merges gebeurden immers via Pull Requests op GitHub.

- [ ] Maak gebruik van passende git commando's om de nieuwe wijziging(en) te commiten naar git. Zorg ervoor dat je lokale wijzigingen vervolgens ook op je remote repository aanwezig zijn.

- [ ] Merge lokaal (of via een Pull Request op GitHub) je **dev** branch in **master** en synchroniseer een laatste maal je lokale en remote repo.

- [ ] Controleer even of alle aanpassingen finaal op de **master** branch beland zijn op GitHub. De twee afgewerkte must have issues zouden nu ook automatisch in de kolom Done van je project board beland moeten zijn, aangezien de respectievelijke commits nu op de **master** (= default) branch beland zijn.

- [ ] Open je GitHub page in je browser via de url die je terugvindt op de pagina waar je je GitHub page hebt geconfigureerd. **Verifieer dat de site goed getoond wordt op deze url.** Pas indien nodig de instellingen voor de GitHub page verder aan.
