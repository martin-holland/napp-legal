---
title: Napps integritetspolicy
lang: sv
permalink: /sv/
---

# Napps integritetspolicy

Senast uppdaterad: 29.10.2026

Napp är en fiskeapp för Finlands vatten. Den här policyn förklarar vad som händer med dina uppgifter när du använder appen. Kort sagt:

- Napp har inga konton, inga annonser, inga analysverktyg och ingen spårning.
- Din fångstdagbok och dina exakta fiskeplatser stannar i telefonen.
- För att hämta väder-, vatten- och regeldata frågar appen öppna datatjänster om sjöar med hjälp av sjöarnas offentliga registerpunkter.

## Personuppgiftsansvarig

Personuppgiftsansvarig för uppgifter som behandlas via Napp är Beacon International Oy, Finland.

Kontakt: dev@beacon-international.org

## Det som stannar i telefonen

Napp sparar följande endast i appens lagring i telefonen:

- din fångstdagbok och dina fiskepass;
- GPS-positionerna för dina fångster och fiskepass, och de exakta platser till havs som du väljer på kartan;
- dina favoritvatten, ditt språkval och dina inställningar;
- uppgiften om du har Napp Full som prenumeration eller engångsköp, och när en prenumeration tar slut eller senast bekräftades av butiken;
- kopior av de data som appen har hämtat, så att den fungerar utan uppkoppling.

Napp laddar aldrig upp något av detta.

Om säkerhetskopiering är påslagen i telefonen (Google eller iCloud) tar telefonen med appens data i din egen säkerhetskopia, under ditt konto och enligt den tjänstens villkor. När du avinstallerar appen raderas uppgifterna från telefonen men inte från säkerhetskopior som redan har gjorts. Dem hanterar du i ditt Google- eller iCloud-konto.

## Platsbehörighet

Napp ber om platsen bara medan du använder appen, och bara för att spara var du fick en fisk. Det finns ingen spårning i bakgrunden. Platsen är frivillig: du kan neka eller återkalla behörigheten i telefonens inställningar. Appen fungerar ändå, men fångster sparas då utan plats.

Förhållandena för ett fiskepass eller en fångst hämtas för den sjö du har valt, inte för din position. Till havs hämtas de för den plats du valde på kartan, avrundad till 0,1 grader (cirka 5-10 km). Om en fångst någon gång sparades utan sjö eller plats till havs skulle appen i stället använda din position avrundad till 0,1 grader. Din exakta position skickas aldrig.

## Vad appen skickar och varför

För att visa väder, vattentemperatur, vattenstånd, is och fiskeregler hämtar appen öppna data. Varje förfrågan innehåller något av följande:

- **En sjös registerpunkt eller nummer:** från det offentliga finländska sjöregistret. Den skickas när du öppnar en sjö, ser den på kartan eller loggar ett fiskepass eller en fångst där. Den är inte din GPS-position. Eftersom en sjö som hämtas medan du loggar en fångst ändå sannolikt är den där du är, behandlar vi dessa förfrågningar som ungefärlig plats.
- **En plats till havs, avrundad:** när du väljer en plats på havet på kartan, öppnar den eller loggar ett fiskepass eller en fångst där, skickar appen platsen avrundad till 0,1 grader (cirka 5-10 km), aldrig den exakta punkten. Eftersom den ungefär är där du fiskar, behandlar vi dessa förfrågningar som ungefärlig plats.
- **Kartområdet på skärmen:** kartrutor hämtas för det område du tittar på. Kartan följer aldrig din GPS-position.
- **Ett sjönamn:** texten du skriver när du söker efter en sjö.

Som vid alla förfrågningar på internet ser tjänsterna också din enhets IP-adress.

Förfrågningarna går till:

| Tjänst | Till vad | Vem som driver den |
| --- | --- | --- |
| Napps server (Supabase, EU-region) | Hämtar och cachar väder-, vatten- och begränsningsdata, och delar ut uppdateringar av artprofiler och regler | Supabase för vår räkning (biträde) |
| Finlands miljöcentral Syke (rajapinnat.ymparisto.fi) | Sjösökning och sjöuppgifter, alltid direkt; vattentemperatur, vattenstånd och is när vår server inte svarar | Syke |
| Meteorologiska institutet (opendata.fmi.fi) | Väder och prognoser när vår server inte svarar | Meteorologiska institutet |
| Tjänsten Kalastusrajoitus (avoinkara-mmm.ruokavirasto-awsa.com, JSM, drivs av Livsmedelsverket) | Lokala fiskebegränsningar när vår server inte svarar | JSM / Livsmedelsverket |
| OpenFreeMap (tiles.openfreemap.org) | Kartrutor | OpenFreeMap |

**På Napps server:**

- **Cachen:** hämtade öppna data cachas med sjöns punkt eller en kartruta som nyckel och kopplas inte till dig eller din enhet. Posterna raderas när deras giltighetstid har gått ut: väder inom cirka 5 timmar, fiskebegränsningar inom cirka 28 timmar och listor över mätstationer i en sjö (efter sjönummer) inom cirka 8 dagar.
- **Loggarna:** leverantörens förfrågningsloggar innehåller varje förfrågans adress (även den sjöpunkt eller det sjönummer som efterfrågades), din IP-adress och tidpunkten. Med vår nuvarande plan sparas de i en dag, och i alla fall högst 7 dagar, för att driva och skydda tjänsten. Supabase och dess nätverksleverantörer (Cloudflare, AWS) sparar sina egna infrastrukturloggar enligt vårt personuppgiftsbiträdesavtal.
- **Användning:** vi använder varken cachen eller loggarna för att identifiera eller följa någon, och vi kan inte koppla dem till en person om du inte ger oss din IP-adress och tidpunkten (artikel 11 i dataskyddsförordningen).
- **Rättslig grund:** vårt berättigade intresse av att driva den app du har valt att använda på ett tillförlitligt och säkert sätt (artikel 6.1 f i dataskyddsförordningen). Napp fattar inga automatiserade beslut om dig.

Meteorologiska institutet, Syke, tjänsten Kalastusrajoitus och OpenFreeMap hanterar sina egna serverloggar enligt sina egna integritetsvillkor.

## Köp

Napp Full säljs via App Store eller Google Play, som prenumeration eller engångsköp. Apple eller Google hanterar betalningen och en eventuell gratis provperiod enligt sina egna villkor. Napp får bara butikens bekräftelse på vad du har (för en prenumeration även när den aktuella perioden tar slut, om butiken anger det) och sparar den bara i telefonen, så att appen öppnas upplåst utan nät och slutar låsa upp när prenumerationen tar slut. Vi ser aldrig dina betalningsuppgifter.

## Länkar

Vissa vyer länkar till andra webbplatser, till exempel Omakala för den lagstadgade fångstrapporten eller dataleverantörernas egna sidor. De webbplatserna har sina egna integritetspolicyer.

## Överföringar utanför EU

Napps server körs i en EU-region. Supabase är ett amerikanskt företag. Eventuell åtkomst utanför EU omfattas av EU:s standardavtalsklausuler i vårt personuppgiftsbiträdesavtal med Supabase. Kontakta oss för en kopia. Apple och Google behandlar köp enligt sina egna villkor.

## Dina rättigheter

Enligt dataskyddsförordningen har du rätt att:

- få tillgång till dina personuppgifter;
- få dem rättade eller raderade;
- begränsa behandlingen av dem;
- invända mot behandling som grundar sig på berättigat intresse (artikel 21).

Napp sparar inga personuppgifter om dig på sina servrar utöver de kortlivade loggar och den cache som beskrivs ovan. De flesta av dina uppgifter finns därför under din egen kontroll i telefonen. Kontakta oss på adressen ovan i övriga frågor.

Du kan också lämna in ett klagomål till dataombudsmannens byrå i Finland (tietosuoja.fi).

## Ändringar

Om policyn ändras publiceras den nya versionen på den här adressen med ett nytt datum. Väsentliga ändringar nämns också i appens versionsinformation.
