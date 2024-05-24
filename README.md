# API-specificatie-template-repository
Deze repository is een template repository die als basis voor het genereren van nieuwe API-specificatie of Groep van API-specificaties repository gebruikt kan worden.
Een VNG-R GitHub administrator kan de link [_Use this template_](https://github.com/VNG-Realisatie/API-specificatie-template-repository/generate) gebruiken om een kopie van de onderliggende template aan te maken die vervolgens aangepast en uitgebreid kan worden.

De op die wijze gecreëerde kopie bevat een standaard content en structuur die door de eigenaar van de repository kan worden aangepast afhankelijk van de wensen en functie van de repository.
* Indien de repository niet bedoeld is om een OAS in te beheren kan de folder 'specificaties' worden verwijderd;
* Ongewenste issue-report types kunnen uit de folder '.github/ISSUE_TEMPLATE' worden verwijderd;
* Indien geen feature bestanden (rules) gewenst zijn dan kan de folder 'features' worden verwijderd;
* De folder 'test' kan worden verwijderd als er in de repository nooit test bestanden zullen worden opgenomen;
* De 'docs' folder kan in zijn geheel worden verwijderd als er vanuit de repository geen GitHub Pages site gegenereerd hoeft te worden;
* Als een GitHub Pages site wel gewenst is kan de structuur in de 'docs' folder naar wens worden aangepast:
  * verwijderen van ongewenste folders;
  * creëren van folders;
  * vullen van de diverse Markdown bestanden;
  * crëeren van Markdown bestanden;
  * plaatsen van illustratieve bestanden;
  * configureren van het '_config.yml' bestand.
  * Tevens kan de repository dan direct of op een later tijdstip worden geconfigureerd voor het genereren van een GitHub Pages site.
  * **LET OP!** Vergeet niet de repository toe te voegen aan het 'gh-pages-rebuild.yml' script in de repo van het gerelateerde Jekyll theme.
