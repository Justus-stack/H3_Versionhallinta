# Harjoitus 3

## a) Tee tehtävän raportti markdownina.

## d) Näytä omalla git-varastollasi esimerkit komennoista git log, git diff ja git blame.

tein varaston githubiin tätä tehtävää varten. Loin text.md tiedoston, johon laitoin vähän teksiä, jotta voisin testata git log, git diff ja git blame komentoja

git log komennolla näkyy lokit vanhoista 

![kuva1](/images/kuva1.png)

git diff komentoa käytetään, kun halutaan tietää mitä muutoksia kahden eri version välillä on.

![kuva1](/images/kuva2.png)

git blame komennolla näkee että, kuka on muokannut tiettyä riviä viimeksi.

![kuva3](/images/kuva3.png)

## e) Tee tyhmä muutos gittiin

tein tyhmän muutoksen gittiin. Muutin text.md tiedostoa poistamalla rivin tekstiä. tallensin tekstitiedoston ja ajoin komennon:

	sudo git reset --hard

![kuva4](/images/kuva4.png)

git vaihtoi viimeiseen versioon ja teksti oli tullut taikaisin 

## f)Tee uusi salt moduuli

Tein saltilla moduulin, joka asentaa MyPaint ohjelman.

ensiksi tein /srv/salt/paint kansioon init.sls tiedoston. laitoin init.sls tiedostoon seuraavan koodinpätkän:

	mypaint:
	  pkg.installed

Testasin toimiiko

![kuva5](/images/kuva5)

![kuva6](/images/kuva6)

![kuva7](/images/kuva7)
Lähteet:

Tero Karvinen. Publish your project with GitHub. luettavissa: terokarvinen.com/2016/publish-your-project-with-github/index.html Luettu: 21.4.2021

