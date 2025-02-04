# GAME OVER - Escape Rooms

## Breedband internet uitzetten

### GTmetrix
Ik heb al enigszins ervaring met het verbeteren van page performance voor de website van mijn werk. Ik gebruik hiervoor altijd GTmetrix. GTmetrix geeft je een uitgebreid overzicht over de laadtijd en structuur van de ingevoerde website. Je kan een locatie kiezen van waaruit de website wordt geladen. Ik kies altijd voor London omdat dit de dichstbijzijnde optie is.

![](img/gtmetrix.png)

### Resultaten

#### Cijfer

**A**

#### Performance
- First Contentful Paint is goed, maar halverwege de hele laadtijd. Aangezien de laadtijd maar 1,5 seconden is (wat erg goed is) is het beter om de First Contentful Paint eerder naar voren te brengen. Dit is echter zeker geen must met zo’n goede laadtijd.

#### Structure
- Hun cache is medium gerankt. Er wordt aangeraden om een betere cache policy te gebruiken. Een aantal grote bestanden worden niet gecached terwijl dit de laadtijd voor terugkomende gebruikers kan verminderen.

#### Waterfall
- Raleway font is een vrij groot bestand (302KB). Dit font staat dan ook op google. Om de performance te verbeteren zou overwogen kunnen worden het font in te laden via bijvoorbeeld de font-host google fonts. Ik weet alleen niet helemaal zeker of dit daadwerkelijk de laadtijd kan versnellen.
- De bestandgroottes van de afbeeldingen zijn vrij klein, maar nog goede kwaliteit. Dit is erg goed voor de laadtijd. Hoe groter het bestand, hoe langer het duurt voordat het op de pagina is geladen.

Een goede manier om je website nog sneller te maken is om bepaalde bestanden te preloaden. Dit zorgt ervoor dat deze bestanden eigenlijk al voordat de pagina geladen wordt, worden opgehaald. Als je dit doet voor grote bestanden (meestal wordt dit gedaan voor bepaalde scripts en css bestanden) hoeven die niet op het moment zelf worden ingeladen en is de laadtijd van de pagina nog korter.

#### Slow network test
Zelfs met trage netwerk laat de pagina in ongeveer 5 seconden.


## Muis/Trackpad werkt niet

Navigatie met tab werkt middelmatig. De navigatie bovenin focust netjes per element, maar het lijkt alsof de blokken halverwege de pagina die worden gefocust of ze hebben geen outline. Hierdoor zie je niet direct op welk blok er gefocust wordt. Misschien heeft het te maken met de outline. Deze kunnen ze met CSS makkelijk toevoegen. Of dit de oplossing is, is niet zeker.
