# Ohjelmistotekniikka, syksy 2019

_Kurssin nimi on muuttunut, aiemmin kurssi tunnettiin nimellä Ohjelmistotekniikan menetelmät_

## Yleistä

Kurssilla tutustutaan ohjelmistokehityksen periaatteisiin sekä menetelmiin ja sovelletaan niitä toteuttamalla pienehkö harjoitustyö.

Kurssin kolmella ensimmäisellä viikolla on muutama ohjauksessa tai omatoimisesti tehtävä harjoitustehtävä. Kurssin pääpainon muodostaa viikolla 2 aloitettava, itsenäisesti tehtävä harjoitustyö. Työtä on tarkoitus edistää pala palalta [viikoittaisten](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019#aikataulu) tavoitteiden ohjaamana. 

Kurssin arvostelu perustuu pääasiassa harjoitustyöstä saataviin pisteisiin. Osa pisteistä kertyy [aikatauluun](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019#aikataulu) määriteltyjen viikoittaisten välitavoitteiden kautta, osa taas perustuu työn lopulliseen palautukseen.

Kurssilla ei ole koetta. Harjoitustyö tulee tehdä kurssin aikataulujen puitteissa. Kesken jäänyttä harjoitustyötä ei voi jatkaa seuraavalla kurssilla (keväällä 2020), joten **muista varata riittävästi aikaa (10-15h viikossa) koko periodin ajaksi!**

Tarkemmat arvosteluperusteet [täällä](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/web/arvosteluperusteet.md).


## HUOM!  Kurssilla tarvitset java 8 versiota

Tarkasta koneesi java-versio kirjoittamalla terminaaliin käsky:

`mvn -v`

Jos koneellasi on jokin muu versio vaihda se alla olevan ohjeen mukaisesti:

Jotta kurssin [esimerkkisovelluksen](https://github.com/mluukkai/OtmTodoApp) saa toimimaan laitoksen koneilla vaihda se alla olevalla terminaalikäskyllä

`export JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-amd64/`

Komennon onnistumisen varmistamiseksi mvn -v rupeaa näyttämään oikeaa versiota. 
Eli java 11 sijaan mvn -v sanoo java8.
Tuon aiemmassa komennossa olevan polun löytää helposti ainakin cubblilla komennolla:

`update-alternatives --list java`


## Kirjoitusvirheitä 

Jos huomaat tehtävissä tai muussa materiaalissa kirjoitusvirheitä, kirjaudu GitHubiin ja toimi [täällä](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/web/typokorjaukset.md) olevan ohjeen mukaan.

## Ajankohtaista

- [Telegram](https://t.me/tktlotm) on whatsappin/messengerin tyylinen keskustelufoorumisovellus jota on mahdollista käyttää selaimella, mobiililaitteilla ja Windows/Linux/OSX-clienteillä
  - Telegram-kanava on sillattu IRC-kanavaan #otm
  - **Huom:** kaikki epäasialliset, halventavat ja jotain ihmisryhmää syrjivät kommentit kanavalla ovat kiellettyjä ja tälläisten kommenttien esittäjät poistetaan kanavalta


## Linkkejä

- [Kurssimateriaali](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/web/materiaali.md)
- Viikoittaiset palautukset
  - viikko 1 [laskarit](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/viikko1.md) 
  - viikko 2 [laskarit](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/viikko2.md) ja [harjoitustyö](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/harjoitustyo_viikko2.md)
  - viikko 3 [laskarit](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/viikko3.md) ja [harjoitustyö](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/harjoitustyo_viikko3.md)
  - viikko 4 [harjoitustyö](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/harjoitustyo_viikko4.md)
  - viikko 5 [harjoitustyö](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/harjoitustyo_viikko5.md)
  - viikko 6 [harjoitustyö](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/harjoitustyo_viikko6.md)
  - viikko 7 [harjoitustyö](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/harjoitustyo_viikko7.md)
  
**HUOM! Saadaksesi harjoitustyöstä viikkokohtaiset pisteet, sovelluksen tulee toimia laitoksen koneella ja ohjaajien pitää pystyä se niiltä aukaisemaan!!** Esim. [Virtuaalisessatyöasemassa](https://vdi.helsinki.fi) voit testata tätä.

- Kurssin referenssisovellus [OtmTodoApp](https://github.com/mluukkai/OtmTodoApp)
  - Sovelluksen tarkoituksena on demonstroida erästä tapaa tehdä suurin piirtein täysiin pisteisiin riittävä dokumentaatio ja testaus projektillesi. Itse ohjelma on sen verran suppea, että saadaksesi kurssilta arvosanan 5 joudut tekemään hieman laajemman sovelluksen. 
- [Labtool](https://study.cs.helsinki.fi/labtool/courses/TKT20002.2019.K.K.1)
- Ohjeita 
  - Kaikki ohjeista eivät ole kurssin alussa vielä ajankohtaisia. Kaikkeen tärkeään tulee aikanaan linkki laskareihin tai harjoitustöiden viikkotavoitteisiin
  - [Aiheideoita ja ohjeita työn harjoitustyön aloittamiseen](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/web/tyon_aloitus.md)
  - [JUnit-ohje](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/web/junit.md) 
  - [Käyttöliittymän ja tietojen tallettamisen toteuttamiseen sekä sovelluksen konfigurointiin liittyviä vihjeitä](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/web/java.md)
  - [Maven](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/web/maven.md)
  - [Checkstyle](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/web/checkstyle.md)  
  - [JavaDoc](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/web/javadoc.md)
  - [koodin laatu](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/web/koodin_laatuvaatimukset.md)
- Työkaluja kaavioiden piirtoon
  - <http://yuml.me/> luokkakaaviot
  - <https://www.websequencediagrams.com/> sekvenssikaavioihin
  - <https://draw.io/> kaikki kaaviot

## Pajaohjauksen aikatauluja

Pajaohjaus alkaa aina akateemisella vartilla ja kestää tasaan asti, ohjaajien välillä on siis 15 minuutin tauko.

Luokka BK107

| Kellonaika | Maanantai | Tiistai | Keskiviikko | Torstai | Perjantai |
|:-:|:-:|:-:|:-:|:-:|:-:|
| 10 - 12 |      |       |      |          | |
| 12 - 14 | Harri | Virva | Riku | Valtteri | |
| 14 - 16 | Jere | Roope |      |          | Joakim | 

Paja alkaa vasta tiistaina 29.10.

## Aikataulu 

### viikko 1

Palautuksen deadline ti 5.11. klo 23:59

- Maanantaina 28.10. klo 14-16 kurssin aloitustilaisuus salissa A111
- Komentorivi- ja Git-harjoittelu (2p)
  - Pajassa tehtävät tai omatoimiset [tehtävät](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/viikko1.md)
- Tehtävien palautus tapahtuu tekemällä repositorio githubiin ja rekisteröitymällä labtooliin

### viikko 2

Palautuksen deadline ti 12.11. klo 23:59

- Harjoitustyön aiheen alustava määrittelydokumentti (1p)
  - katso tarkemmin [täältä](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/harjoitustyo_viikko2.md) 
- JUnit-harjoittelu (2p)
  - Pajassa tehtävät tai omatoimiset [tehtävät](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/viikko2.md)
- Oman projektin koodaus alkaa

### viikko 3

Palautuksen deadline ti 19.11. klo 23:59

- Harjoitustyön koodin runko valmiina (2p)
  - katso tarkemmin [täältä](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/harjoitustyo_viikko3.md) 
- Pajassa tehtävät tai omatoimiset [tehtävät](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/viikko3.md) Luokka- ja sekvenssikaaviosta (1p)

### viikko 4

Palautuksen deadline ti 26.11. klo 23:59

- Harjoitustyö (3p)
  - Ohjelman perustoiminnallisuus 
  - Testien aloitus 
  - Alustava rakenne luokkakaaviona 
  - Checkstyle otettu käyttöön
- Tarkemmat ohjeet [täältä](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/harjoitustyo_viikko4.md) 

### viikko 5

Palautuksen deadline ti 3.12. klo 23:59

- Harjoitustyö (3p)
  - Release 1 
  - Testikattavuus nousee 
  - Jotain päätoiminnallisuutta kuvaava sekvenssikaavio 
- Tarkemmat ohjeet [täältä](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/harjoitustyo_viikko5.md) 
- Koodikatselmointi (2p)
  - [Koodikatselmointi](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/web/koodikatselmointi.md)

### viikko 6

Palautuksen deadline ti 10.12. klo 23:59

- Harjoitustyö (3p)
  - Release 2
  - Testikattavuus nousee 
  - JavaDoc aloitettu 
  - Alustava versio arkkitehtuuridokumentista 
- Tarkemmat ohjeet [täältä](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/harjoitustyo_viikko6.md) 

### viikko 7

Lopullisen palautuksen deadline su 22.12. klo 23:59

- [loppupalautuksen ohjeet](https://github.com/mluukkai/ohjelmistotekniikka-syksy-2019/blob/master/tehtavat/harjoitustyo_viikko7.md) 
