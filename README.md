# Kalenteriprojekti

## Projektin kuvaus
Tässä projektissa luodaan interaktiivinen kalenteri, jossa on mahdollisuus avata kalenteriluukkuja tiettyinä päivinä ja katsella niihin liittyvää sisältöä. Projekti käyttää JavaScriptiä dynaamisen sisällön luomiseen ja muokkaamiseen. Käyttäjä voi klikata luukkuja ja saada niihin liittyviä kuvia ja tekstejä, jotka muuttuvat tietyn aikarajan mukaan. 

### Ominaisuudet:
- **Kalenteriluukut**: Kalenteri sisältää päivämäärät, jotka on määritelty dynaamisesti JavaScriptin avulla. Kun käyttäjä valitsee tietyn päivän luukun, siihen liittyvä sisältö avautuu.
- **Interaktiivisuus**: Jokaiselle luukulle on määritelty toiminnallisuus, joka muuttaa sisältöä napin painalluksella. Sisältö voi olla tekstiä, kuvia, karttoja tai muuta interaktiivista dataa.
- **Dynaaminen sisältö**: JavaScriptin avulla käyttäjä voi muuttaa sisältöä (esim. kuvia ja tekstejä) reaaliaikaisesti päivämäärän ja napin valinnan perusteella.
- **CSS-tyylit**: Käytetään perusstyylejä, kuten varjoja ja hover-efektejä, nappeihin ja muihin elementteihin. Kaikki tehty manuaalisesti :)

## Käytetyt teknologiat
- **HTML**: Perusrakenteen luominen, kuten elementit (nappi, kuva-alue, otsikko jne.).
- **CSS**: Tyylit, kuten napin ulkoasu, tekstin ja kuvien koon ja sijainnin määrittäminen, sekä hover- ja varjo-efektit.
- **JavaScript**: 
  - Dynaaminen sisällön muuttaminen päivämäärien ja napin valinnan mukaan.
  - `createElement()` ja `appendChild()` -metodit kuvien ja muiden elementtien luomiseen ja lisäämiseen.
  - `setInterval()` tai `setTimeout()` ajastimien käyttö ajankohtaisen luukun näyttämiseksi.
  - `Date`-objekti päivämäärän tarkistamiseen ja dynaamisten ehtojen luomiseen.

## Oppimisaiheita
Tässä projektissa käsitellään useita tärkeitä aiheita, kuten:
- **DOM-manipulointi**: Opitaan, miten HTML-elementtejä luodaan ja muokataan JavaScriptin avulla. Esimerkiksi `createElement()` ja `appendChild()` ovat keskeisiä elementtien luomisessa ja lisäämisessä.
- **Ehtojen tarkistus**: Käytetään JavaScriptin ehtolauseita (if-else), kuten päivämäärän vertailu, jolla voidaan dynaamisesti muuttaa sisältöä ja navigointia.
- **CSS-tyylit ja responsiivisuus**: Opitaan luomaan visuaalisesti houkuttelevia ja responsiivisia käyttöliittymiä, joissa elementit mukautuvat näytön kokoon.
- **Upotukset ja ulkoiset API:t**: Google Mapsin ja muiden ulkoisten resurssien (kuten kuvat ja kartat) upottaminen on olennainen osa projektin interaktiivisuutta.

## Tulevaisuuden parannukset
- **Käyttäjän datan tallentaminen**: Lisäämällä tallennusmekanismin (esimerkiksi LocalStorage tai Backend-tietokanta) käyttäjän vuorovaikutuksen ja valintojen tallentamiseen.
- **Käyttöliittymän parantaminen**: Lisää visuaalisia efektejä ja animoituja siirtymiä parantaaksesi käyttäjäkokemusta.
- **Työn viimeistely**: loput luukut valmiiksi, jos haluaa valmiin kalenterin. Työssä tehtiin vain muutama "testiluukku", joten kaikkia luukkuja ei voida avata.
