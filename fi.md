---
title: Nappin tietosuojaseloste
lang: fi
permalink: /fi/
---

# Nappin tietosuojaseloste

Päivitetty: 1.11.2026

Napp on kalastussovellus Suomen vesille. Tässä selosteessa kerrotaan, mitä tiedoillesi tapahtuu, kun käytät sovellusta. Lyhyesti:

- Nappissa ei ole käyttäjätilejä, mainoksia, analytiikkatyökaluja eikä seurantaa.
- Kalapäiväkirjasi, saaliskuvasi ja tarkat kalapaikkasi pysyvät puhelimessasi, ellet itse vie kalapäiväkirjaa.
- Sää-, vesi- ja sääntötietojen hakemiseksi sovellus kysyy avoimen datan palveluilta järvistä niiden julkisen rekisteripisteen avulla sekä paikoista merellä ja katselemastasi kartta-alueesta 0,1 asteen ruutuihin pyöristettyinä.

## Rekisterinpitäjä

Nappin kautta käsiteltävien henkilötietojen rekisterinpitäjä on Beacon International Oy, Suomi.

Yhteystieto: dev@beacon-international.org

## Mikä pysyy puhelimessasi

Napp säilyttää seuraavat tiedot vain sovelluksen tallennustilassa puhelimessasi:

- kalapäiväkirjasi ja kalastuskertasi;
- saaliisiin lisäämäsi kuvat (Napp Full). Napp tallentaa niistä oman kopion, joka on koodattu uudelleen ja josta on poistettu kuvan metatiedot, kuten kameran tallentama GPS-sijainti, aika ja kameran malli. Valitsemasi kuva säilyy puhelimesi galleriassa ennallaan. Napp ei tallenna Nappissa ottamaasi kuvaa galleriaasi, mutta kamerasovelluksesi voi säilyttää siitä oman kopion;
- saaliiden ja kalastuskertojen GPS-sijainnit sekä kartalta merellä valitsemiesi paikkojen tarkat sijainnit;
- suosikkivetesi, kielivalintasi ja asetuksesi;
- tiedon siitä, onko sinulla Napp Full tilauksena tai kertaostona, sekä milloin tilaus päättyy tai kauppa viimeksi vahvisti sen;
- kopiot sovelluksen hakemista tiedoista, jotta sovellus toimii myös ilman verkkoyhteyttä.

Napp ei lähetä näitä tietoja minnekään.

**Kalapäiväkirjan vienti (Napp Full):** kun napautat Kalapäiväkirja-näkymässä "Vie CSV-tiedostoksi", sovellus tekee kalapäiväkirjastasi CSV-tiedoston puhelimeen ja avaa puhelimen jakovalikon. Tiedostossa ovat kalastuskertasi ja saaliisi aikoineen, lajeineen, mittoineen ja tallennettuine olosuhteineen; muistiinpanosi ja vieheesi; kalastamiesi vesien nimet; sekä paikkojesi tarkat koordinaatit (missä kalastit kalastuskerralla, mistä sait kunkin kalan ja merellä valitsemasi paikat). Tiedosto menee vain sinne, minne itse sen lähetät (sähköpostiin, pilvipalveluun, toiseen sovellukseen), ja siellä sovelletaan kyseisen palvelun ehtoja. Napp ei saa tiedostosta kopiota eikä kerää siitä mitään. Kopio voi jäädä sovelluksen omaan välimuistiin puhelimessa seuraavaan vientiin asti tai kunnes puhelin tyhjentää välimuistin.

Jos puhelimesi varmuuskopiointi on päällä (Google tai iCloud), puhelin sisällyttää sovelluksen tiedot omaan varmuuskopioosi. Saaliskuvat jätetään pois Androidin varmuuskopioista; iPhonessa ne kuuluvat laitteen varmuuskopioon (iCloud tai tietokone). Ne säilyvät sinun tililläsi kyseisen palvelun ehtojen mukaisesti. Kun poistat sovelluksen, tiedot poistuvat puhelimesta mutta eivät jo tehdyistä varmuuskopioista. Niitä hallitset Google- tai iCloud-tililläsi.

## Sijaintilupa

Napp pyytää sijaintia vain silloin, kun käytät sovellusta, ja vain tallentaakseen saaliin paikan. Taustaseurantaa ei ole. Sijainti on vapaaehtoinen: voit evätä luvan tai perua sen puhelimen asetuksista. Sovellus toimii silloinkin, mutta saaliit tallentuvat ilman paikkaa.

Kalastuskerran tai saaliin olosuhteet haetaan valitsemallesi järvelle, ei sinun sijainnillesi. Merellä ne haetaan kartalta valitsemallesi paikalle pyöristettynä 0,1 asteeseen (noin 5-11 km). Jos saalis joskus tallentuisi ilman järveä tai paikkaa merellä, sovellus käyttäisi sen sijaan sijaintiasi pyöristettynä 0,1 asteeseen. Tarkkaa sijaintiasi ei koskaan lähetetä.

## Kamera ja kuvat

Napp pyytää kameraa vain, kun napautat "Ota kuva", ja käyttää sitä vain sen kuvan ottamiseen. Kuvien valinnassa käytetään puhelimesi omaa kuvavalitsinta: Napp saa vain valitsemasi kuvat eikä pyydä lupaa kuvakirjastoosi. Voit evätä kameraluvan tai perua sen puhelimen asetuksista; kuvia voit silti valita. Kuvia ei koskaan ladata palvelimelle eikä lähetetä minnekään.

## Mitä sovellus lähettää ja miksi

Näyttääkseen sään, veden lämpötilan, vedenkorkeuden, jäätiedot ja kalastussäännöt sovellus hakee avointa dataa. Kussakin pyynnössä on jokin seuraavista:

- **Järven rekisteripiste tai -numero:** julkisesta Suomen järvirekisteristä (satelliitin jäähavainnossa pieni alue pisteen ympärillä). Se lähetetään, kun avaat järven, näet sen kartalla tai kirjaat sille kalastuskerran tai saaliin. Se ei ole GPS-sijaintisi. Koska saalista kirjatessa haettu järvi on kuitenkin todennäköisesti se, jolla olet, käsittelemme näitä pyyntöjä likimääräisenä sijaintina.
- **Paikka merellä pyöristettynä:** kun valitset kartalta paikan merellä, avaat sen tai kirjaat sille kalastuskerran tai saaliin, sovellus lähettää paikan pyöristettynä 0,1 asteeseen (noin 5-11 km), ei koskaan tarkkaa pistettä. Koska se on suunnilleen siellä, missä kalastat, käsittelemme näitä pyyntöjä likimääräisenä sijaintina.
- **Näytölläsi oleva kartta-alue:** karttatiilet haetaan sille alueelle, jota katselet. Kun lähennät karttaa riittävästi, sovellus hakee myös alueen kalastusrajoitusalueet: näkyvän alueen pyöristettyinä 0,1 asteen ruutuina (noin 5-11 km). Ne lähetetään Nappin palvelimelle tai, jos se ei voi toimittaa tietoja, Kalastusrajoitus-palveluun. Kartta ei koskaan seuraa GPS-sijaintiasi.
- **Järven nimi:** teksti, jonka kirjoitat järvihakuun.

Kuten kaikissa internetpyynnöissä, palvelut näkevät myös laitteesi IP-osoitteen.

Pyynnöt menevät näille palveluille:

| Palvelu | Mihin | Ylläpitäjä |
| --- | --- | --- |
| Nappin palvelin (Supabase, EU-alue) | Hakee sää-, vesi- ja rajoitustiedot ja tallentaa ne välimuistiin sekä jakaa päivitykset lajiprofiileihin ja sääntöihin | Supabase meidän lukuunamme (käsittelijä) |
| Suomen ympäristökeskus Syke (rajapinnat.ymparisto.fi, geoserver2.ymparisto.fi) | Järvihaku ja järven tiedot aina suoraan; veden lämpötila, vedenkorkeus, jää ja järvien jäätilanne satelliittikuvista silloin, kun palvelimemme ei voi toimittaa tietoja | Syke |
| Ilmatieteen laitos (opendata.fmi.fi) | Sää ja ennusteet sekä merellä meriveden lämpötila, merivedenkorkeus ja aallokko silloin, kun palvelimemme ei voi toimittaa tietoja | Ilmatieteen laitos |
| Copernicus Marine Service (wmts.marine.copernicus.eu) | Meriveden lämpötila satelliitista pyöristetylle paikalle merellä silloin, kun palvelimemme ei voi toimittaa tietoja | Mercator Ocean International EU:n lukuun |
| Kalastusrajoitus-palvelu (avoinkara-mmm.ruokavirasto-awsa.com, MMM, ylläpitäjänä Ruokavirasto) | Paikalliset kalastusrajoitukset silloin, kun palvelimemme ei voi toimittaa tietoja | MMM / Ruokavirasto |
| OpenFreeMap (tiles.openfreemap.org) | Karttatiilet | OpenFreeMap |

**Nappin palvelimella:**

- **Välimuisti:** haettu avoin data tallennetaan välimuistiin, ja tunnisteena on järven piste tai karttaruutu. Sitä ei yhdistetä sinuun eikä laitteeseesi. Tiedot poistetaan niiden voimassaolon päätyttyä: sää- ja meriennusteet noin 5 tunnin, satelliittihavainnot noin 10 tunnin, kalastusrajoitukset noin 28 tunnin ja järven mittausasemien luettelot (järvinumeron mukaan) noin 8 päivän kuluessa.
- **Lokit:** palveluntarjoajan pyyntölokeissa on kunkin pyynnön osoite (myös haettu järven piste tai numero tai karttaruutu), IP-osoitteesi ja aika. Nykyisellä palvelutasollamme ne säilyvät yhden päivän ja joka tapauksessa enintään 7 päivää palvelun ylläpitoa ja tietoturvaa varten. Supabase ja sen verkkopalveluntarjoajat (Cloudflare, AWS) säilyttävät omia infrastruktuurilokejaan tietojenkäsittelysopimuksemme mukaisesti.
- **Käyttö:** emme käytä välimuistia emmekä lokeja kenenkään tunnistamiseen tai seuraamiseen. Emme voi yhdistää niitä henkilöön, ellet anna meille IP-osoitettasi ja ajankohtaa (tietosuoja-asetuksen 11 artikla).
- **Käsittelyperuste:** oikeutettu etumme pitää käyttöön ottamasi sovellus toimivana ja turvallisena (tietosuoja-asetuksen 6 artiklan 1 kohdan f alakohta). Napp ei tee sinusta automaattisia päätöksiä.

Ilmatieteen laitos, Syke, Copernicus Marine, Kalastusrajoitus-palvelu ja OpenFreeMap käsittelevät omia palvelinlokejaan omien tietosuojaehtojensa mukaisesti.

## Ostot

Napp Fullia myydään App Storessa ja Google Playssa tilauksena tai kertaostona. Maksun ja mahdollisen ilmaisen kokeilun käsittelee Apple tai Google omien ehtojensa mukaisesti. Napp saa vain kaupan vahvistuksen siitä, mitä sinulla on (tilauksesta myös kuluvan jakson päättymisajan, jos kauppa sen kertoo), ja säilyttää sen vain puhelimessasi, jotta sovellus aukeaa ilman verkkoyhteyttä ja lakkaa avaamasta Napp Fullia, kun tilaus päättyy. Emme koskaan näe maksutietojasi.

## Linkit

Joissakin näkymissä on linkkejä muille sivustoille, esimerkiksi Omakalaan lakisääteistä saalisilmoitusta varten tai datantuottajien omille sivuille. Niillä sivustoilla on omat tietosuojakäytäntönsä.

## Siirrot EU:n ulkopuolelle

Nappin palvelin toimii EU-alueella. Supabase on yhdysvaltalainen yritys. Mahdollinen EU:n ulkopuolelta tapahtuva käyttö on katettu EU:n vakiosopimuslausekkeilla, jotka sisältyvät Supabasen kanssa tekemäämme tietojenkäsittelysopimukseen. Saat niistä kopion pyytämällä. Apple ja Google käsittelevät ostot omien ehtojensa mukaisesti.

## Oikeutesi

Tietosuoja-asetuksen mukaan sinulla on oikeus:

- saada pääsy henkilötietoihisi;
- saada ne oikaistuksi tai poistetuksi;
- rajoittaa niiden käsittelyä;
- vastustaa oikeutettuun etuun perustuvaa käsittelyä (21 artikla).

Napp ei säilytä sinusta palvelimillaan henkilötietoja edellä kuvattuja lyhytaikaisia lokeja ja välimuistia lukuun ottamatta, joten suurin osa tiedoistasi on omassa hallinnassasi puhelimessasi. Muissa asioissa ota yhteyttä yllä olevaan osoitteeseen.

Voit myös tehdä valituksen tietosuojavaltuutetun toimistolle (tietosuoja.fi).

## Muutokset

Jos tämä seloste muuttuu, uusi versio julkaistaan tässä osoitteessa uudella päivämäärällä. Olennaisista muutoksista kerrotaan myös sovelluksen julkaisutiedoissa.
