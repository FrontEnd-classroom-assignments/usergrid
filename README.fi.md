# Käyttäjäruudukko

Luo responsiivinen React-sovellus, joka hakee käyttäjälistan julkisesta API-rajapinnasta ja esittää käyttäjät Material UI -komponenttien avulla.

## Vaihe 1: Datan haku
Käytä päätepistettä https://reqres.in/api/users hakeaksesi käyttäjätiedot. Sinun tulee hankkia ilmainen API-avain [Reqres.in](https://reqres.in/) -sivustolta käyttääksesi REST API:a.

Käsittele lataus- ja virhetilat asianmukaisesti.

## Vaihe 2: Käyttäjien näyttäminen
Käytä Material UI:n Card-komponenttia jokaisen käyttäjän esittämiseen. Lue Card-komponentin dokumentaatio osoitteesta https://mui.com/material-ui/react-card/.

Jokaisessa kortissa tulee näkyä:
- Käyttäjän avatar
- Koko nimi
- Sähköpostiosoite

Asettele kortit responsiiviseen ruudukkoon Material UI:n Grid-järjestelmällä. Lue Grid-komponentin dokumentaatio osoitteesta https://mui.com/material-ui/react-grid/.

### Esimerkkitulos:

<img src="./src/assets/usergrid.png" alt="Käyttäjäruudukko" style="width: 50%;" />

### Vaihe 3: Käyttäjäsuodatin
Paranna käyttöliittymää toteuttamalla reaaliaikainen hakusuodatin. Lisää tekstikenttä, jonka avulla käyttäjiä voidaan suodattaa nimen perusteella. Kun käyttäjä kirjoittaa tekstikenttään, näytettävä käyttäjälista päivittyy dynaamisesti näyttämään vain ne käyttäjät, joiden nimessä (etunimi + sukunimi) on syötetty merkkijono (kirjainkoolla ei ole väliä).

- Lisää tekstikenttä käyttäjälistan yläpuolelle.
- Kuuntele muutoksia tekstikentässä ja päivitä näytettävä lista.
- Toteuta kirjainkoolla riippumaton suodatus käyttäjän koko nimeen (esim. etunimi + sukunimi).

### Esimerkkitulos:

<img src="./src/assets/usergrid2.png" alt="Käyttäjäruudukko" style="width: 50%;" />
