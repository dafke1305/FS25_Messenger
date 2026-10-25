# Messenger — Handleiding

[Nederlands](HANDLEIDING.md) · [English](USER_GUIDE.md) · [Download / README](README.md)

Voor het pakket **1.0.2.3** uit [deze release](https://github.com/dafke1305/FS25_Messenger/releases/tag/v1.0.2.3). Deze instructies horen bij die ZIP, niet bij een andere build met hetzelfde versienummer.

## Installatie

1. Download **FS25_Messenger.zip** onder Assets van de release. Behoud de bestandsnaam en pak de ZIP niet uit. De automatische GitHub Source code-archieven zijn niet de mod.
2. Plaats de ZIP in de ingestelde FS25-modsmap (op Windows gewoonlijk `Documents\My Games\FarmingSimulator2025\mods`) en schakel de mod in vóór het laden van de savegame. Deze scriptmods zijn voor PC/Mac.
3. Server en alle multiplayerclients moeten **dezelfde ZIP** hebben, niet alleen hetzelfde versienummer. Sluit het spel/stop de server en maak vóór bijwerken een saveback-up.

## Openen en versturen

1. Sluit je aan bij een spelersboerderij. Messenger is een **postbus tussen boerderijen**, geen persoonlijke postbus voor één lid van een boerderij.
2. Open Messenger in het spelmenu of druk **Alt+M**. Kies een andere boerderij of gesprek.
3. Vul onderwerp en bericht in en kies **Verzenden / Send**. Maximum: **80 tekens** voor het onderwerp en **600 tekens** voor het bericht. De tellers tonen de gebruikte ruimte.
4. Gebruik **Antwoorden / Reply** of een snelantwoord om verder te praten. **Enter verstuurt direct** in het invoerveld; gebruik de verzendknop wanneer je het verzendmoment bewust wilt kiezen.
5. Bekijk **Verzonden/Gelezen** en gebruik **Newest unread** om naar het nieuwste ongelezen gesprek te springen.

Ook een offline boerderij kan opgeslagen berichten ontvangen zodra leden opnieuw verbinden. De postbus staat in de serversavegame en blijft bij normaal opslaan/herstarten bestaan. Boerderijleden delen de correspondentie van hun boerderij; behandel dit niet als een vertrouwelijke privéchat tussen twee individuele spelers.

## Gesprekken en meldingen beheren

Zoek in gesprekken of filter op ongelezen/vastgezet. **Vastzetten**, **Dempen**, **Archiveren** en **Herstellen** beheren het gekozen boerderijgesprek. Archiveren verbergt het uit de actieve lijst en is iets anders dan wissen. **Gesprek verwijderen** verwijdert het uit jouw boerderijpostbus; dit betekent niet dat de kopie bij iedere andere boerderij ook wordt gewist.

De meldingenknop wisselt tussen **alles**, **stil**, **vastgezet** en **uit**. Stil onderdrukt geluid; vastgezet beperkt meldingen tot vastgezette gesprekken. Deze voorkeur is lokaal per client. Een gedempt gesprek kan daarnaast meldingen onderdrukken; controleer bij ontbrekende meldingen beide instellingen.

## Beheerdersacties

Een in-game aangemelde serverbeheerder kan een aankondiging naar **alle geschikte andere spelersboerderijen** sturen. Lees vóór verzenden de ontvangersbevestiging. Gewone spelers kunnen deze algemene verzendactie niet gebruiken.

**Admin: clear old messages** wist geschikte serverberichten die minstens één volledige **spelmaand** oud zijn en bewaart recente berichten. Dit is serverbrede opschoning, niet het archiveren van je eigen gesprek. Lees de bevestiging en maak vóór opschonen een saveback-up.

## Problemen oplossen

| Probleem | Controle |
| --- | --- |
| Geen ontvangers | Word lid van een boerderij en controleer of een andere geschikte spelersboerderij bestaat. |
| Versturen lukt niet | Vul beide velden, houd 80/600 tekens aan en wacht bij een snelheidslimiet. Verstuur een als opgeslagen bevestigd bericht niet steeds opnieuw. |
| Geen melding | Controleer meldingenstand, dempen en gelezen/ongelezen status. |
| Bericht weg na verbinden | Controleer boerderij/savegame en identieke server-/client-ZIP. Lever logs aan in plaats van postbusgegevens in de save te wijzigen. |

## Hulp vragen

Gebruik [het bug-/supportformulier van deze mod](https://github.com/dafke1305/FS25_Messenger/issues/new/choose). Vermeld release/ZIP, FS25- en mapversie, singleplayer/host/client/dedicated, stappen, tijdstip en het volledige clientbestand `log.txt`; bij een dedicated-serverprobleem ook `server.log` van dezelfde sessie. Voeg relevante screenshots/video toe. De pakketcontrolecode staat in [PUBLICATION.json](PUBLICATION.json). Verwijder wachtwoorden, tokens en privéverbindingsgegevens vóór openbaar plaatsen. Gebruik voor privébewijs alleen een goedgekeurd privékanaal.

Standaardtoetsen zijn aanpasbaar. De actuele F1-hulp en je instellingen onder Besturing zijn leidend.
