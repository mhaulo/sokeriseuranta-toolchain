# Sokeriseuranta-toolchain
Muistilista tarvittavista laitteista ja ohjelmistoista. Raakaversio - tarkentuu myöhemmin.

1. Sokeriseuranta-käyttäjätunnus
2. Raspberry Pi
3. Wixel
4. Wixelin softa: xDrip
5. Raspberry Pi:n uploader-softa
6. Valinnainen: nettitikku ja virtapankki


## Sokeriseuranta-käyttäjätunnus

[ks. sokeriseuranta.fi](https://sokeriseuranta.fi)

## Raspberry Pi

Periaatteessa mikä tahansa malli käy. Testattu 3 B:llä. Myös Intel Edison tai muu vasta masiina joka pyörittää uploader-softaa saattaa toimia.

## Wixel

Pololu Wixel (tuotetunnus 1337). Löytyy elektroniikkaliikkeistä.

## Wixelin softa

Wixeliin asennetaan suoraan usb-wixel-xDrip: 

[https://github.com/jamorham/python-usb-wixel-xdrip](https://github.com/jamorham/python-usb-wixel-xdrip). 

Tuossa repossa on valmis asennusskripti.

## Raspberry Pi:n uploader-softa

Tähän käytetään Sokeriseuranta-käyttöä varten modifioitua Parakeet-uploaderia:

[https://github.com/mhaulo/sokeriseuranta-wixel-uploader](https://github.com/mhaulo/sokeriseuranta-wixel-uploader)


## Valinnainen: nettitikku ja virtapankki

Raspberry Pi on parhaimmillaan kotona sisätiloissa, mutta kulkee se laukussakin. Sitä varten tarvitaan virtalähde ja nettiyhteys,

Virtalähteeksi kelpaa ihan tavallinen kännyköiden lataamisen tarkoitettu virtapankki. Kapasiteetista riippuu, kuinka pitkään masiina pysyy käynnissä. Oman pikatestin mukaan n. 10000 mAh:n akku kestää ainakin 12 tuntia. Isompi akku on yleensä myös painavampi, joten varmuuden vuoksi ei kapasiteettia kannata överiksi vetää. Jos ei ole ihan koko päivää reissussa, voi n. 5000 mAh:n akku olla hyvä kompromissi kapasiteetin ja painon suhteen.

Nettiyhteyden voi hoitaa joko jakamalla wlan kännykästä tai käyttämällä nettitikkua. Omien kokemusten mukaan nettitikuista ainakin Soneran verkkoon valmiiksi konffattu Huawei E3372 TeleFinlandin liittymällä toimii lähes laakista. 