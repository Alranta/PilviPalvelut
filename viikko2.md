# This is the second week
Github actionsilla voidaan automatisoida sivustojen ylläpitoa, muokkaamista ja testaamista. Github pages automaattisesti päivittyy ja hakee uusimman version mikä on repositoryyn tallennettu. Tärkeää myös on muistaa se että sivusto on online kokoajan, eikä vaadi sivuston alasajoa välissä versionvaihdossa ja versionhallinnassa.

CI/CD Putkisto websovellukselle tärkein osa mielestäni on git eli versionhallinta. Se mahdollistaa devaajien yhteisen työskentelyn jakamisen ja työskentelyn pitämisen ajanhallinnassa, ja varmistetaan että kaikilla on oikea ja toimiva versio websovelluksesta. Lisäksi jos jossakin epäonnistutaan, voidaan siirtyä takaisin vanhassa versiossa.
Continigous integrationissa voidaan myös käyttää esimerkiksi Jenkinsiä tai Travis CI, tai github pagesia. Github pages ja actions on myös CI työkalu.
Nykyään suosittuja teknologioita ovat myös konttiteknologiat, jotka verrattuna entiseen vanhaan pull menetelmään käytetään websovelluksesta containeria, joka on käytännössä
virtual machine, jossa ohjelmisto käyttäytyy kuten sen tekijän tietokoneella. Näin varmistetaan että websovellus toimii kaikilla laitteilla.
Testausta voidaan suorittaa esimerkiksi robotframeworkilla, ja testausta voidaan suorittaa ohjelmistokoodissa yksikkötesteillä.