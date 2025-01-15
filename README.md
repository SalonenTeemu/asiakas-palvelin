# asiakas-palvelin

Tämä on C-kielellä Käyttöjärjestelmät-kurssilla Linux-järjestelmälle toteutettu palvelin, joka lähettää vastaanottamiinsa UDP-paketteihin vastauksena arvotut lottonumerot. Lisäksi projekti sisältää asiakasohjelman, jolla palvelinta voi käyttää.

## Käyttöohjeet

### 1. Ohjelmien kääntäminen

Käännä ohjelmat Makefile-tiedostoa käyttäen ajamalla: `make`

### 2. Ohjelmien ajaminen

Aja palvelinohjelma komennolla: `./palvelin`

Lähetä käynnissä olevalle palvelimelle viestejä ajamalla asiakasohjelma komennolla: `./asiakas`

### 3. Siivoaminen

Poista käännetyt ohjelmat tarvittaessa komennolla: `make clean`
