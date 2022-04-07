# GitOhje

## Yleistä

Git on versionhallintajärjestelmä jolla voi sillee kivasti tallentaa ja palauttaa tiedostoja ilman että koko projekti syttyy tuleen.

Eli jos vaikka kirjotat 267 riviä jumalan hylkäämää siansaksaa (JavaScript), ja joku ei yhtäkkiä toimi niin voit mennä vanhaan versioon eikä tarvitse aloittaa Stalinistisia puhdistuksia koodille siinä toivossa että se rupeais taas toimimaan.

## Yleisimmät komennot
| Komento | Selitys |
| -- | --:   |
| clone [url]   | hakee url:stä repositoryn omaan koneeseen      |
| branch   | Listaa branchit   |
| add [file]  | Lisää tiedoston commitattavaksi     |
| commit -m "viesti" | committaa eli lisää stagetetut tiedostot uudeksi checkpointiksi |
| log | Listaa kaikkia commitit kyseisestä branchista |
| log --oneline | log mut cooleille tyypeille 😎
| fetch | Hakee uusimman version kaikista brancheista github repositorysta tai vastaavasta |
| pull | Vetää fetchistä haetut tiedot omaan käyttöön |
| merge [branch] | yhdistää nimetyn branchin nykyiseen branchiin |
| checkout | Vaihtaa working directoryn toiseen branchiin |
| push | Työntää commitatut muutokset netissä olevaan repositoryyn mihin nyt ikinä linkititkään |
| status | Näyttää tilanteen, mahdolliset commitit jne. |

Loppu cheatsheet [täältä](https://education.github.com/git-cheat-sheet-education.pdf)
<br/>
<br/>

## GitHubin käyttö  
1. Metsästä repository jota haluat muokata
2. fork
3. clone url
4. teurasta koodia omilla "parannuksilla" kunnes haluat palauttaa. (Normaali git käyttö)
5. push
6. pull request omasta haarukasta siihen alkuperäiseen
7. kirjoita tekosyysi miksi kaikkia ohjelmointikäytänteitä rikkovan purkkakoodisi tulisi mergettää alkuperäiseen repoon
8. tukehdu ilmaan kun näet tämän:
![kuva](merge.png)