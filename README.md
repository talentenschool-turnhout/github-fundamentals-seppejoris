# :wave: De basis van GitHub

## 🤓 Cursusoverzicht en leerresultaten

Het doel van deze cursus is om je een korte introductie tot GitHub te geven. We geven je ook materiaal voor verdere verdieping en een paar ideeën om je op weg te helpen op ons platform. 🚀

## :octocat: Git en GitHub

Git is een **gedistribueerd versiebeheersysteem (VCS)**, wat betekent dat het een handige tool is om eenvoudig wijzigingen in je code bij te houden, samen te werken en te delen. Met Git kun je de wijzigingen die je in je project aanbrengt bijhouden, zodat je altijd een overzicht hebt van waar je aan hebt gewerkt en indien nodig gemakkelijk kunt teruggaan naar een oudere versie. Het maakt het ook gemakkelijker om met anderen samen te werken: groepen mensen kunnen samenwerken aan hetzelfde project en hun wijzigingen samenvoegen tot één bron!

GitHub is een manier om dezelfde kracht van Git online te gebruiken met een gebruiksvriendelijke interface. Het wordt in de softwarewereld en daarbuiten gebruikt om samen te werken en de projectgeschiedenis bij te houden.

GitHub is de thuisbasis van enkele van de meest geavanceerde technologieën ter wereld. Of je nu data visualiseert of een nieuwe game bouwt, er is een complete community en een set tools op GitHub die je naar de volgende stap kunnen brengen. Deze cursus begint met de basisprincipes van GitHub, maar we zullen later dieper ingaan op de rest.

## :octocat: De GitHub-flow begrijpen

De GitHub-flow is een lichtgewicht workflow waarmee je gemakkelijk kunt experimenteren en samenwerken aan je projecten, zonder het risico te lopen je eerdere werk te verliezen.

### Repositories

Een repository is waar je projectwerk plaatsvindt - zie het als je projectmap. Het bevat alle bestanden en revisiegeschiedenis van je project. Je kunt alleen binnen een repository werken of anderen uitnodigen om met je samen te werken aan die bestanden.

### Klonen

Wanneer een repository met GitHub wordt aangemaakt, wordt deze extern opgeslagen in de ☁️. Je kunt een repository klonen om een ​​lokale kopie op je computer te maken en vervolgens Git gebruiken om de twee te synchroniseren. Dit maakt het gemakkelijker om problemen op te lossen, bestanden toe te voegen of te verwijderen en grotere commits te pushen. Je kunt ook de bewerkingstool van je keuze gebruiken in plaats van de GitHub-gebruikersinterface. Het klonen van een repository haalt ook alle repositorygegevens op die GitHub op dat moment heeft, inclusief alle versies van elk bestand en elke map voor het project! Dit kan handig zijn als je met je project experimenteert en je je realiseert dat je een eerdere versie beter vond.
Lees ["Een repository klonen"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) voor meer informatie over klonen.

### Committen en pushen
**Committen** en **pushen** zijn de manieren waarop je de wijzigingen die je op je lokale machine hebt aangebracht, kunt toevoegen aan de externe repository in GitHub. Zo kunnen je instructeur en/of teamgenoten je laatste werk zien wanneer je klaar bent om het te delen. Je kunt een commit maken wanneer je wijzigingen in je project hebt aangebracht die je wilt "checkpointen". Je kunt ook een handige **commitmelding** toevoegen om jezelf of je teamgenoten eraan te herinneren wat je hebt gedaan (bijv. "Een README toegevoegd met informatie over ons project").

Zodra je een of meerdere commits hebt die je klaar bent om aan je repository toe te voegen, kun je de push-opdracht gebruiken om die wijzigingen aan je externe repository toe te voegen. Committen en pushen voelt misschien in het begin nieuw aan, maar we beloven dat je eraan went 🙂

## 💻 GitHub-termen om te kennen

### Repositories
We hebben het al over repositories gehad; daar gebeurt je projectwerk, maar laten we het nog even hebben over de details ervan! Naarmate je meer met GitHub werkt, zul je veel repositories tegenkomen, wat in het begin verwarrend kan zijn. Gelukkig helpt je ["GitHub-dashboard"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) je om eenvoudig naar je repositories te navigeren en nuttige informatie erover te bekijken. Zorg ervoor dat je ingelogd bent om het te zien!

Repositories bevatten ook **README**'s. Je kunt een README-bestand aan je repository toevoegen om anderen te vertellen waarom je project nuttig is, wat ze ermee kunnen doen en hoe ze het kunnen gebruiken. Met behulp van deze README willen we u laten weten hoe u Git en GitHub kunt leren. 😄
Lees ["Creating, Cloning, and Archiving Repositories](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) en ["About README's"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes) voor meer informatie over repositories.

### Branches
Je kunt branches op GitHub gebruiken om werk te isoleren dat je nog niet in je uiteindelijke project wilt mergen. Branches stellen je in staat om functies te ontwikkelen, bugs op te lossen of veilig te experimenteren met nieuwe ideeën in een afgebakend gebied van je repository. Normaal gesproken maak je een nieuwe branch aan vanuit de standaardbranch van je repository: main. Dit maakt een nieuwe werkkopie van je repository waarmee je kunt experimenteren. Zodra je nieuwe wijzigingen door een teamgenoot zijn beoordeeld, of je er tevreden mee bent, kun je je wijzigingen mergen in de standaardbranch van je repository.
Lees ["Over branches"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches) voor meer informatie over branching.

### Forks
Een fork is een andere manier om een ​​repository te kopiëren, maar wordt meestal gebruikt wanneer je wilt bijdragen aan het project van iemand anders. Het forken van een repository stelt je in staat om vrijelijk te experimenteren met wijzigingen zonder het oorspronkelijke project te beïnvloeden en is erg populair bij het bijdragen aan open source softwareprojecten!
Lees ["Fork a repo"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo) voor meer informatie over forken.

### Pull requests
Wanneer je met branches werkt, kun je een pull request gebruiken om anderen te informeren over de wijzigingen die je wilt aanbrengen en om hun feedback te vragen. Zodra een pull request is geopend, kun je de potentiële wijzigingen met medewerkers bespreken en beoordelen en indien nodig meer wijzigingen toevoegen. Je kunt specifieke personen toevoegen als reviewers van je pull request, wat laat zien dat je hun feedback op je wijzigingen wilt! Zodra een pull request klaar is, kan deze worden samengevoegd met je hoofdbranch. Lees ["Over Pull Requests"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) voor meer informatie over pull requests.

### Issues
Issues zijn een manier om verbeteringen, taken of bugs voor je werk op GitHub bij te houden. Issues zijn een geweldige manier om alle taken waaraan je voor je project wilt werken bij te houden en anderen te laten weten waar je aan wilt werken. Je kunt issues ook gebruiken om een ​​favoriet open-sourceproject te informeren over een bug die je hebt gevonden of een functie die je graag zou willen toevoegen!

Voor grotere projecten kun je meerdere issues bijhouden op een projectbord. GitHub-projecten helpen je bij het organiseren en prioriteren van je werk. Je kunt er meer over lezen [in dit document "Over projectborden"](https://docs.github.com/en/github/managing-your-work-on-github/about-project-boards). Je hebt waarschijnlijk geen projectbord nodig voor je opdrachten, maar zodra je aan grotere projecten begint, zijn ze een geweldige manier om het werk van je team te organiseren!
Je kunt ook pull-requests en issues aan elkaar koppelen om aan te geven dat er een oplossing wordt uitgevoerd en om het issue automatisch te sluiten wanneer iemand de pull-request samenvoegt.
Lees ["Over issues"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues) voor meer informatie over issues en hoe je ze aan je pull-requests kunt koppelen.

### Je gebruikersprofiel

Je profielpagina vertelt mensen het verhaal van je werk via de repositories waarin je geïnteresseerd bent, de bijdragen die je hebt geleverd en de gesprekken die je hebt gevoerd. Je Je kunt de wereld ook een uniek inzicht geven in wie je bent met je profiel README. Je kunt je profiel gebruiken om toekomstige werkgevers alles over je te laten weten!

Lees ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme) voor meer informatie over je gebruikersprofiel en het toevoegen en bijwerken van je profiel.

### Markdown gebruiken op GitHub

Je hebt het misschien al gemerkt, maar je kunt je issues, pull requests en bestanden een leuke styling geven. ["Markdown"](https://guides.github.com/features/mastering-markdown/) is een eenvoudige manier om je issues, pull requests en bestanden te stylen met een eenvoudige syntaxis. Dit kan handig zijn om je informatie te ordenen en het voor anderen gemakkelijker te maken om te lezen. Je kunt ook gifs en afbeeldingen toevoegen om je punt over te brengen!
Lees ["Managing Your Profile README"](https://guides.github.com/features/mastering-markdown/) voor meer informatie over het gebruik van GitHub's versie van markdown. ["Basissyntaxis voor schrijven en opmaken"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).

### Interactie met de GitHub-community

De GitHub-community is enorm. Er zijn veel verschillende mensen die GitHub dagelijks gebruiken: studenten zoals jij, professionele ontwikkelaars, hobbyisten die aan open-sourceprojecten werken en ontdekkingsreizigers die net de wereld van softwareontwikkeling induiken. Er zijn veel manieren om te communiceren met de bredere GitHub-community, maar hier zijn drie plekken waar je kunt beginnen.

#### Repositories een ster geven

Als je een repository interessant vindt of wilt bijhouden, geef hem dan een ster! Wanneer je een repository een ster geeft, wordt dit ook gebruikt als signaal om betere aanbevelingen op github.com/explore te tonen. Wil je je gemarkeerde repositories weer zien, dan kun je dat doen via je gebruikersprofiel.

Lees ["Repositories opslaan met sterren"](https://docs.github.com/en/github/getting-started-with-github/saving-repositories-with-stars) voor meer informatie over het markeren van repositories met sterren.

#### Gebruikers volgen

Je kunt mensen op GitHub volgen om meldingen over hun activiteit te ontvangen en projecten in hun community's te ontdekken. Wanneer je een gebruiker volgt, wordt zijn of haar openbare GitHub-activiteit weergegeven op je dashboard, zodat je kunt zien waar hij of zij aan werkt.

Lees ["Volgende mensen"](https://docs.github.com/en/github/getting-started-with-github/following-people) voor meer informatie over het volgen van gebruikers.

#### Bladeren door GitHub Explore

GitHub Explore is een geweldige plek om precies dat te doen … exploreren :smile: Je vindt er nieuwe projecten, evenementen en ontwikkelaars om mee te communiceren.

Je kunt de GitHub Explore-website bekijken [op github.com/explore](https://github.com/explore). Hoe meer je met GitHub werkt, hoe meer je Explore-weergave zal worden afgestemd.

## 📝 Optionele volgende stappen

* Open een pull request en laat je docent weten dat je deze cursus hebt afgerond.
* Maak een nieuw markdown-bestand aan in deze repository. Laat ze weten wat je hebt geleerd en waar je nog vragen over hebt! Experimenteer met verschillende stijlen!
* Maak je profiel aan in de README-sectie. Laat de wereld iets meer over jezelf weten! Wat wil je leren? Waar ben je mee bezig? Wat is je favoriete hobby? Lees meer over het aanmaken van je profiel in de README-documentatie ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).
* Ga naar je gebruikersdashboard en maak een nieuwe repository aan. Experimenteer met de functies in die repository om er vertrouwd mee te raken.
* [Laat ons weten wat je wel of niet leuk vond aan de inhoud van deze cursus](https://support.github.com/contact/education). Wat zou je graag meer willen zien? Wat zou interessant of nuttig zijn voor je leertraject?

## 📚 Bronnen
* [Een korte video die uitlegt wat GitHub is](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be)
* [Leermiddelen voor Git en GitHub](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources)
* [De GitHub-flow begrijpen](https://guides.github.com/introduction/flow/)
* [Hoe GitHub-branches te gebruiken](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Interactief Git-trainingsmateriaal](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://lab.github.com/)
* [Onderwijscommunityforum](https://education.github.community/)
* [GitHub communityforum](https://github.community/)
