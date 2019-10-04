* 10 pistettä toolchain.md: sisältää kuvauksen yritykselle suunnitellusta työkaluketjusta aina käytetyistä IDE (Integrated development environment) CI ratkaisuun saakka. Perustelkaa valintaa lyhyesti. Pituus n. ainakin 1000 sanaa

Yhteensä 30 pistettä.


### Brackets
Brackets on Adobe Systemsin luoma ilmainen tekstieditori, jota yrityksessämme käytetään muun muassa nettisivujen suunnitteluun, muokkaamiseen ja tekemiseen. Yrityksemme työntekijöillä on aikaisempaa kokemusta Bracketsin käytöstä, ja uusien käyttäjien on helppo oppia Bracketsin käyttö. Brackets käyttää avointa lähdekoodia.  Käyttäjät voivat ilmoittaa lähdekoodissa olevista virhekoodeista, ehdottaa muutoksia ohjelman käytettävyyteen liittyen sekä auttaa koodamaan ohjelmaa. Bracketsin uusin päivitys tukee myös PHP- ohjelmointikieltä, minkä avulla pystytään lisäämään nettisivulle esimerkiksi graafisia ominaisuuksia. Bracketsin Markdown lisäosan ansiosta tekstitiedostossa tehdyt muutokset näkyvät käyttäjälle heti lisäikkunassa. Bracketsin inline- ominaisuus näyttää selaimessa reaaliaikaisesti koodissa tehdyt muutokset nettisivuja tehtäessä.  Brackets on myös yhteensopiva GitHubin kanssa. Brackets on yhteydessä myös selaimeen ja ohjelmassa koodiin tehtyjä muutoksia voi siirtää “push”- komennolla GitHubiin.  Bracketsilla pystyy kätevästi tekemään myös ryhmätöitä, eli monet henkilöt voivat tarvittaessa muokata tiedostoa.


### CI-työkalu
Yrityksemme käyttää projekteissaan version hallinta työkalunaan GitHubia. GitHub mahdollistaa koodiin tehtyjen muokkausten ja edellisten version katselun ja ongelmatilanteissa vanhempi versio voidaan hakea historiasta ja ottaa uudelleen käyttöön. Yritys päätyi käyttämään GitHubia, sillä se oli ennestään tuttu osalle työntekijöistä. GitHub on myös nopea oppia koska internetistä löytyy paljon ohjeita ongelman ratkaisuun.
Yrityksessämme käytössä oleva GitHub Teams maksaa 9 dollaria aina yhtä käyttäjää kohti ja yritys valitsi sen käyttöönsä sen laajan tarjonnan takia. GitHub tarjoaa myös laajan valikoiman ilmaisia sekä maksullisia lisäosia, joita työntekijät voivat halutessaan hyödyntää työnteossaan. Tärkeimpinä lisäosina yritys piti halvempiin ja ilmaiseen versioon verrattaessa työntekijöiden rooleihin sovelletut pääsyoikeudet muokattaviin ja saatavilla oleviin tiedostoihin. Tämä estää työntekijöitä muokkaamasta tiedostoja, joihin heillä ei ole oikeuksia, jolloin jotkin toiminnot saattaisivat lakata toimimasta asiakkaan internet-sivuilla tai jolloin saattaisi syntyä tietosuoja aukkoja. Yritys käyttää verkkosivujen rakentamiseen Brackets ohjelmaa, joka on helppokäyttöinen ja yhteensopiva GitHubin kanssa.


### IDE-työkalu Eclipse
Eclipse (IDE) on ohjelmistoympäristö, joka tukee esimerkiksi Java-ohjelmointikieltä, jota meidän yrityksemme käyttää. Ohjelmointiympäristö on ohjelma tai joukko ohjelmia, joilla ohjelmoija toteuttaa ja suunnittelee ohjelmistoja. Eclipse on ilmainen netistä ladattava ohjelmointiympäristö, jolla voi toteuttaa esimeriksi verkkosivuja. Se tukee myös muita ohjelmointikieliä, kuten PHP, C ja C++. Avoimen lähdekoodin lisenssillä voidaan kehittää ympäristöä. Avoin lähdekoodi tarkoittaa tietokoneohjelmien kehitys- ja tuottamismenetelmiä, jotka tarjoavat mahdollisuuden käyttäjälle tutustua ohjelman lähdekoodiin ja muokata sitä omiin tarpeisiinsa sopivaksi. Sen periaatteisiin kuuluu myös vapaus käyttää ohjelmaa mihin tahansa tarkoitukseen ja kopioida ja levittää sekä alkuperäistä että muokattua versiota. Eclipseä on aloitettu kehittämään vuonna 1993 ja vuonna 2001 Eclipse julkaistiin avoimen lähdekoodin lisenssille. 
Eclipse on toteutettu melkein kokonaan Java-ohjelmointikielellä ja se on melkein kokonaan alustariippumaton, eli se ei ole sidoksissa tiettyyn laitteistoalustaan tai käyttöjärjestelmään. Kuitenkaan Eclipse ei käytä Javan käyttöliittymäkirjastoa, vaan sille on tehty oma kirjasto, joten tämän takia se ei ole täysin alustariippumaton. ffrfrfbfgb


### Apple Xcode
Tarkoitetaan Applen kehittämää ohjelmointiympäristöä, joka on tarkoitettu monille eri alustoille ja ohjelmakielille. 

Xcodea käyttämällä voidaan tehdä komentoriviohjelmia, joita on esimerkiksi Java-applette, macOS- ohjelma ja on mahollista myös tehdä IOS alustalle. 


                                            Xcode IDEN Ominaisuuksia 

  Assistant editorilla voit kirjoittaa koodin käyttämällä ammattimaista editoria, edistyneellä valmiilla koodilla, taitettavalla koodilla, korostamalla syntaksia ja viestikuplaa, joka näyttää varoituksen, virheet ja muut tähän kuuluvat tiedot koodien avulla.                         

Asset catalogi ,Editori Xcodessa, joka hoitaa appsit , kuvat, yhdistää monenlaiset resoluutiot samassa erässä.                         

Assistant editori jakautuu kahteen osaan, tekemällä toisen paneelin ruudun, joka automaattisesti näyttää kyseiset tiedostot, joita tarvitaan apuna editoimisessa. 

 Open quickly, kun painat Cmd-Shift-0 ja avaa minkä tahansa tiedoston ”työtilasta”, ensisijaisella editorilla, myös pitämällä pohjassa valintanäppäintä, kun valitset tiedostoja. 
 
Version editori Näyttää yhtäjaksoisen aikataulun commiteista. 

Apuna selvittäessä syytä koodin perusteella, jota editoidaan, graafisesti laitetaan takaisin, jotta voidaan vertailla lähde tiedostoja. Tuen avulla subversiossa ja git lähdettä kontrolloidaan SCM systems. 

Muita työkaluja on, esimerkiksi  Opengl frame capture, interface builder built in ja quick helper. 



   Instrumentitteja 

  Esimerkkejä Apple Xcoden instrumeteista.                                         

 Data recording, joka kertoo instrumenteille mitä appia analysoida ja minkälaista dataa kerätä. 

 Custom instrumentilla voi tehdä oman instrumentin käyttämällä D-trace ja instrument custom builderia. 


Zombie decetion, hankala löytää erroreita ja katuu, se voidaan laitta “loukkuun” 

Instrumetteihin kun appi yrittää päästä käsiksi mustiin, jota ei enään ole olemassa. 

Visual comparison, kun dataa nauhotetaan ja näytetään siinä tulee helpompaa nähdä yhteydet, molemmissa on  erillaisia tapoja kerätä dataa tai samaa dataa, joka on tallennettu monella kerralla. 


### Ohjelmointikieli Java
Java on ohjelmointikieli, jota käytämme yhtenä ohjelmakielenä yrityksessämme. Java on yksi suurimmista ohjelmointikielistä ohjelmointimaailmassa ja kielenä se on hyvin monipuolinen.  Yrityksellämme on Eclipse (IDE) on ohjelmistoympäristö, joka tukee käyttämäämme Java-kieltä. Javaa hyödynnämme paljon verkkopalveluiden palvelinpään toteuttamiseen ja erilaisiin palvelimella tehtäviin ohjelmiin. Sillä tehdyt ohjelmat toimivat laajalti, esimerkiksi Windows-, Linux- ja Mac-ympäristöissä. Ohjelmistokehitys onnistuu näissä kaikissa ympäristöissä, mistä pidämme paljon. Javalla voimme toteuttaa myös esimerkiksi työpöytäsovelluksia sekä verkkopalveluita. Ohjelmointikielenä Java on avainasemassa Androidissa, koska se kirjoitetaan pääasiassa sillä ja Android käyttöjärjestelmä käyttää paljon Java-teknologiaa. Yksi Javan hyvistä puolista on sen suuri tietorakenteiden- ja kehysten laaja kirjasto, jota hyödyntämällä hankalia kooditekstejä ei tarvitse kirjoittaa käsin manuaalisesti. Java kieli perustuu samaan syntaksiin kuin muummoassa C ja C++ -kielet. Tehokkuutensa ansiosta se sopii esimerkiksi yleiseen kehitykseen tai erilaisiin peli ohjelmiin. Yhteenvetona Java sopii ohjelmointikielenä yritystemme tarpeisiin, koska se on monipuolinen ja sitä pystyy käyttämään moniin eri tarkoituksiin. 


### Android Studio
Yrityksemme on harkinnut alkamaan luomaan mobiilisovelluksia asiakkaille. Tähän tarkoitukseen valitsimme Android Studion, jolla on tehty android-sovelluksien luontiin. Android Studio on android-käyttöjärjestelmän virallinen ohjelmointiympäristö, joka on julkaistiin joulukuussa 2014. Android Studiolla voi koodata Javalla, Kotlinilla, C++:lla. Android Studion hyviä puolia on muun muassa:

- Ohjelmoija voi luoda virtuaalisia laitteita, jotka emuloivat Android Studiota. Tämä ominaisuus antaa sen mahdollisuuden, että tehtyjä sovelluksia voi testata ennen kun ne julkaistaan.
- Android Studion voi yhdistää GitHubiin.
- Jos Android Studion käytössä tarvitsee apua, löytää vastauksen varmasti Androidin foorumeilta, jossa on iso ja aktiivinen yhteisö.
- Ilmainen.
- Helppokäyttöinen.

Android Studiossa ei ole paljoa huonoja puolia, mutta lukemieni arvostelujen mukaan Android Studio tarvitsee paljon tietokoneen prosessointivoimaa ja muistia, joten vakaaseen käyttöön tarvitaan tehokas kannettava tai pöytäkone.


### Adobe Illustrator
Käytämme Adobe Illustratoria työkaluna nettisivujen graafiseen suunnitteluun. Adobe Illustratorin hyviä puolia ovat muun muassa:

- Hyvä käyttöjärjestelmä, jota voi muokata itselleen mukavaksi. Esimerkiksi työkalupalkkeja voi pienentää ja piilottaa tarpeen mukaan.
- Illustratoria voi käyttää melkein millä vain tietokoneella, koska sen järjestelmävaatimuksen ovat pienet. 
- Yhteensopivuus Adobe Photoshopin kanssa
- Vuosittaisia päivityksiä ja uusia ominaisuuksia uuden julkaistavan version yhteydessä.
- Illustrator maksaa 24,97€/kk, joka on mielestämme sopiva hinta.

