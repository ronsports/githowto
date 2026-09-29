# GitHowTo Õppeprojekt

Tere see on minu esimene Giti  project. See repositoorium nimega work on tehtud hariduste käigus, et õppida tundma gitti(githowto abil) põhitõdesid ja käske.



### Mida ma selle projekti käigus õppisin

* Giti alused: Kuidas luua uut repositooriumi ja jälgida failide olekuid.
* Ajas tagasi liikumine: Kuidas vaadata ajalugu ja vajadusel viimaseid vigu tühistada.
* Harudega töötamine: kuidas luua uusi harusi, et teha uusi asju peamisest koodist eraldi.
* Kuidas pushida: et saaks panna githubi kõikile näha.

---

## Kasutatud git käsud

Siin on nimekiri peamistest käskudest, mida ma kasutasin ajaloo põhjal selles projektis kasutasin:

* `git init` – Algatasin kohaliku tühja repositooriumi.
* `git status` – Kontrollisin failide olekut.
* `git add` – Lisasin failid lavale.
* `git commit` – Salvestasin muudatused püsivalt ajalukku.

Kui tegin kogemata ühe vale commiti, siis kasutasin selle tagasi võtmiseks sellist käsku:

git revert HEAD


Kui oli vaja kood viia tagasi versiooni v1 seisuni kasutasime käsku:

git reset --hard v1


---

## Kuidas Giti põhitöövoog toimib

Giti  töövoog käib järgmiseni:

1. [ ] Muudatuste tegemine: Muudad või lood uusi faile oma kaustas.
2. [ ] Lava ettevalmistus: Lisad failid lavale käsuga `git add .`
3. [ ] Salvestamine: Teed püsiva salvestise käsuga `git commit -m "sõnum"`.

### Failide liigutamine
Kui tahtsin stiili faili viia css kausta, siis kasutasin seda koodi blokki:

mkdir css
git mv style.css css/style.css
