# PR19ASDBJCBZ
Projekt podatkovno rudarjenje

Pri projektu za podatkovno rudarjenje smo se odločili za analizo podatkov o prodaji hiš na območju Ames, Iowa. Naš končni cilj je ugotoviti katere lastnosti manji in bolj vplivajo na končne cene hiš ter kako najbolje napovedati prodajno vrednost. 

Podatki s katerimi delamo so:
- Tip stanovanja(npr. število sob, velikost stavbe, starost,...)
- Tip nepremičnine(Komercialna, stanovanje v gosto poseljenem okolju, komercialna,...)
- Povezava z ulico(Število stopal kolikor je naposredno povezana zgradba z ulico)
- Velikost nepremičnine
- Tip ceste, ki vodi do nepremičnine(makedam, asfaltirana ali pa ni direktno povezana s cesto)
- Oblika nepremičnine
- Ravnina nepremničnine
- Osnovne storitve, ki jih vsebuje nepremičnina(elektrika, voda, ...)
- Soseska
- Bljižina železnice, avtoceste,...
- Tip stanovanja
- Ocena materijala in stanja hiše
- Leto gradnje
- Tip strehe, material,...
- Tip fasade, kvaliteta materiala, sten,...
- Temelji
- Ogrevanje, hlajenje, napeljava,...
- Kvaliteta in kvadratura posameznih prostorov(kuhinja, garaža, klet,...)
- Vrednost pohištva
- Podatki o prodaji(leto, mesec, cena,...)

Prva stvar, ki smo jo naredili je da smo prebrali podatke in na osnovi učnih podatkov izračunali povprečno vrednost nepremičnin glede na njihovo sosesko. Z izrisom grafa so takoj razvidne najcenejše in najdražje lokacije.

**Najcenejše:**

    1. MeadowV
    2. IDOTRR
    3. BrDale
**Najdražje:**

    1. NoRidge
    2. NridgHt
    3. StoneBr

![alt text](https://github.com/amadej10/PR19ASDBJCBZ/blob/master/grafi/povprecna_prodajna_cena_lokacija_izboljsano.png "Graf 1: Povprečna prodajna cena glede na lokacijo")

Nadaljevali smo z iskanjem zelo dobrih kupčij oziroma osamelcev na področju prodajna cena v razmerju z bivalno površino. Iz grafa lahko prepoznamo, da sta se zgodile dve zelo dobri kupčiji.

![alt text](https://github.com/amadej10/PR19ASDBJCBZ/blob/master/grafi/osamelci.png "Graf 2: Iskanje osamelcev")

Ker nas pri nepremičninah najbolj zanima njihova prodajna cena smo iskali povezavo cene še z drugimi atributi. V spodnjih dveh grafih  smo iskali povezavo med letom izgradnje in ceno.
![alt text](https://github.com/amadej10/PR19ASDBJCBZ/blob/master/grafi/cena_leto_gradnje.png "Graf 3: Korelacija cene in leta gradnje")
![alt text](https://github.com/amadej10/PR19ASDBJCBZ/blob/master/grafi/povprecna_cena_leto_gradnje.png "Graf 4: Povprecne cene in leta gradnje")


    
