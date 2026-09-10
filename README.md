# hr-expense-agent 

## Tarkoitus
Tehdä kuvitteelliselle yritykselle agentti, joka auttaa työntekijöitä kirjaamaan ja toimittamaan matka- ja kululaskuja oikein.

## Oppimistavoitteet
Tämä on ensimmäinen toteuttamani agenttiprojekti. Tarkoituksena on tutustua agentin kehittämisen vaiheisiin ja Copilot Studion toiminnallisuuksiin. 

- toteuttaa toimiva agentti
- kehittää taitoja suunnitella ja testata agentin toimivuutta

## Käytetyt teknologiat
- Copilot Studio
- Claude

## Agentin tehtävä
- Auttaa työntekijöitä kirjaamaan ja toimittamaan yrityksen toimintatavan mukaisesti matka- ja kululaskut. 
- Agentin ohjeet luettavissa täältä : [Agentin ohjeet](ohjeistus/agentin-ohjeet.md)



## Projektin vaiheet
1. Matka-ja kululaskusohjeen laatiminen: Pyydetty Claudelta dokumenttia, jossa on usein esitettyjä kysymyksiä ja niiden vastauksia liittyen matka- ja kululaskuihin. Muokkasin saatua dokumenttia osittain vastaamaan haluamaani lopputulosta. Testiympäristössä käytin lähdeaineistona UKK-tiedostoa. Tuotantoympäristössä kuitenkin voisi käyttää esimerkiksi yrityksen SharePoint-kansiota, jossa olisi ohjeet tallennettuna. 
2. Agentin ohjeistuksen laatiminen: Katsoin mallia Copilot Studion esimerkkiohjeistuksesta ja lähdin siitä liikkeelle. Pyysin Claudea täydentämään laatimani ohjeluonnosta, jotta saisin agentin toimimaan mahdollisimman hyvin annetussa roolissa.
3. Testauksen suunnittelu: Pyysin Claudea luomaan testikysymykset lähdedokumenttini perusteella ja niiden oletusvastaukset.
4. Testaus: Esitin testausdokumentin kysymykset agentille ja vertasin saatua vastausta testausdokumenttin. Kirjasin ylös vastasiko agentin antama vastaus oletettua vastausta.
5. Muutokset: 

## Haasteet ja ratkaisut
- Copilot Studion pystyttämäisessä oli ongelmia, koska olin luonut testitilin omaan ympäristööni ja hallinnoin itse ympäristöä/tilausta. Käyttöoikeuksista tuli toistuvasti virheilmoitus, joka esti agentin luomisen. Lopulta ratkaisu löytyi luomalla käyttäjäryhmä, jonka alle lisäsin kehitysympäristöä varten luomani käyttäjätilin Sekä odottamalla tarpeeksi kauan, jotta uudet asetukset "astuivat voimaan".  
- Agentti vastasi ensin englanniksi. Tämä korjaantui, kun lisäsin ohjeisiin halutun kielen. 


## Mitä opin
- Lähdeaineiston tulee olla ajantasaista. Tuotantoympäristössä ennen agentin käyttöä on varmistuttava pohjan (= esim. SharePoint kansion tiedostot) olevan kunnossa. 
- Agentti sopii tilanteisiin joissa ei ole tulkinnanvaraisuutta. Selkeiden ehtojen ja sääntöjen avulla agentti pystyy antamaan luotettavan vastauksen.
- Agentin ohjeistuksessa tulee antaa agentille selvät rajat ja lähteet, jotta se ei anna virheellisiä ohjeita. Epäselvissä tilanteissa agentin on osattava ohjata käyttäjä oikealle henkilölle.
- Testauksen merkitys on suuri. Sillä varmistetaan, että agentin antaman vastaukset ovat luotettavia.
- Ensimmäisen testauksen jälkeen huomasin agentin vastauksien olevan liian tylyjä. 

## Opittavaa
- Miten seurataan/valvotaan agenttien toimintaa
- Hyvät käytänteet testaukseen

## Kuvakaappaukset

### 1. Agentin vastaus esimerkki 1
![OTSIKKO 1](kuvantiedostonimi.jpg)

### 2. Agentin vastaus esimerkki 2
![OTSIKKO 2](kuvantiedostonimi.jpg)


