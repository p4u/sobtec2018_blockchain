<!-- $theme: gaia -->
<!-- footer: Sobtec 2018 -->
<!-- page_number: true -->
<!-- $size: 4:3 -->
<!-- template: invert -->

# ![](img/logo_congres.png)


## Blockchain:
## Un univers contradictori

==Abel - <vdo@greyfaze.net> PGP:0x4EE1184B==
==Pau - <p4u@dabax.net> PGP:0x5CF989CD==

---
# Index

1. Rerefons històric
2. Blockchain
3. Desmitificant Bitcoin
4. Reflexió i debat

---
# 1. Rerefons històric
---

## Història (1)

* **Cypherpunk** (finals dels 80)

>... We the Cypherpunks are dedicated to building anonymous systems. We are defending our privacy with cryptography, with anonymous mail forwarding systems, with digital signatures, and with electronic money. 

Eric Hughes - Cypherpunk manifesto, 1993

---
## Història (2)

 * Criptografia **asimétrica**
(Phil Zimmermann, PGP, 1991)
* **Proof of Work** d'Adam Back (e-mail)
* Xarxes **p2p**
	* Napster 1999
	* e-Donkey, Torrent, etc...
* Nick Szabo, Hal Finney, Dai Wei, etc...

---

## Història (3)

* Satoshi Nakamoto (**Blockchain**)

The Times 03/Jan/2009

<img src="img/times.jpg" width="710">

---

# 2. Blockchain

---

## Blockchain [definició]

* Base de dades distribuïda
* Ordenada i inmutable (hashing)
* Verificada mitjançant criptografia
* Velocitat de creixement control·lada i estipulada

<img src="img/blockchain.png" width="310" align="right">

---


## Blockchain [blocs i miners]

* Informació classificada en _blocs_
* Només els _miners_ poden crear blocs
* Bitcoin: 1 bloc = 1 MByte (max)

<img src="img/mining.png" width="300" align="right">

---

## Blockchain [creixement (PoW)]

* Creixement control·lat amb problema matemàtic.
* Dificultat proporcional al poder de còmput global.
* Cada N blocs es recalcula la dificultat.
* Bitcoin: 
* 		1 bloc cada 10 Minuts
		reajust cada 2048 blocs (~14 dies)


<img src="img/gears.png" width="260" align="right">

---

### Dificultat i hashrate: últims 12 mesos

![](img/dificulty_hashrate.png)

---

## Blockchain [recompensa]
* Per incentivar la mineria hi ha una **recompensa**
* En Bitcoin inicialment 50 BTC. Actualment 12.5
* Cada 4 anys (210k blocs) es redueix a la meitat.

<img src="img/reward.png" width="200" align="right">

---
## Blockchain [diagrama]
<!-- template: -->
<img src="img/blockchain_diagrama.png" width="650" >


---
<!-- template: invert-->
## Blockchain [rel·levància]

* **Base de dades disitribuïda** on els actors no necessiten ser de confiança.
* **Registre inmutable** i ordenat de dades amb marca de temps (timestamp).
* Dissenyada per a evitar centralització i/o censura.

**Exemples:** Sistema monetari, notaria, vot electrònic, Crowdfundings, identitat digital, etc...

_A més  a més plataformes com Ethereum permeten l'execució de 'programes' en el blockchain._

---

# 3. Desmitificant Bitcoin

---

## Bitcoin i Capitalisme

* El sistema es basa en un creixement infinit.

Satoshi és respatlla amb la llei de Moore per justificar la seva escalabilitat.

* Fomenta la competència i economies d'escala.

Els miners han de competir entre ells per generar nous blocs d'informació. Qui més recursos té, més en guanya.

* Fomenta les "grans empreses" de miners per reduïr la variança i assegurar la recompensa 

---
## Ús i abús de la blockchain

* Nova 'criptoeconomia' no regulada i volàtil.
* Manipulació de mercats constant (JP Morgan, etc.)
* Especulació i (re)valorització independent de la seva utilitat real.
* Hiper-tokenització.
* Nous incentius per a infectar màquines i aprofitar-ne els recursos per a minar.
* Spam i Phishing més avançat i rentable.

---

## L'estafa dels darrers anys (1)

### Scam Coins (2013): _monedes 'brossa'_
Crear noves criptomonedes (normalment copiant altres), fer que entrin en algun mercat (normalment partíceps) i esperar el _pump&sell_

>DogeCoin, PotCoin, TrumpCoin, SexCoin, etc.

<img src="img/scam_coins.png" width="640" align="right" >

---
## L'estafa dels darrers anys (2)

### ICO (2016): _initial coin offering_
* Crowdfundings amb recompensa  ¿Model startup?
* Normalment la ICO reparteix un token o moneda entre els seus inversors.
* Casos on l'inversió és multiplica per x1000.
* Un cop tancada la ICO no hi ha control sobre el projecte per part dels inversors.

Arribat un punt dòna igual l'objectiu del projecte a finançar, només si en algun moment es revaloritzarà.

---

## L'estafa dels darrers anys (3)

### Hard Forks (2017)
* Divisions de la cadena en un punt que generen una nova cadena i per tant una nova moneda.
* A tothom se li dupliquen les unitats de moneda. Generem valor sense fonament!

<img src="img/scam_forks.png" width="740" align="right" >

---
## L'estafa dels darrers anys (4)

<img src="img/quartet_crypto.png" width="700" align="right" >

---

## Hiper-tokenització

- El "hype" del terme Blockchain atreu a inversors i especuladors. Qualsevol idea, per absurda que sigui, pot aconseguir fons monetaris.
- Veneçuela (Petro), Iran, Canon, Nostrum, Facebook, Telegram...

<img src="img/icetea.png" width="750" align="right" >

---
## Privacitat

- Bitcoin i la majoria de blockchains no són anònimes, mes aviat totalment _transparents._
* Permeten l'anàlisi i traçabilitat per part d'Estats, empreses privades, agéncies com l'FBI, etc.

<img src="img/bitfury.png" width="750" align="right" >

---

![](img/blockseer.jpg)

---
## Consum d'energia (2017)
- 18.4 TWh / any. (aprox)
- Consum anual comparable a Islàndia.
- A aquest ritme, consum equivalent al 100% el 2020 (?)

<img src="img/world_mining.png" width="600" align="right" >

---
## Alternatives al consum d'energia?

- Proof-of-Stake
	- Seguretat no probada.
	- Incentiva l'acumulació de capital en els validadors.
- Proof of Authority i Proof of Cooperation
	- Recentralitzen la descentralització.
	- Requereixen confiança.
	
No hi ha una sol.lució segura, probada i energéticament sostenible a hores d'ara.

---
# 4. Reflexió

---

- Blockchain és una tecnologia que permet l'autogestió i soberania de les dades digitals.

- Avui dia està sobre explotada i en la majoria dels casos només hi ha un interès econòmic darrera.

- Els objectius de privacitat i anonimat s'estan difuminant, cal que siguin pilars centrals.

- La seguretat i resiliència de la tecnologia ve donada per la decentralització, però la tendencia es centralitzadora.

- Cal fer recerca per trobar solucions sostenibles energèticament.

---
## Satoshi

>Banks must be trusted to hold our money and transfer it electronically, but they lend it out in waves of credit bubbles with barely a fraction in reserve. We have to trust them with our privacy, trust them not to let identity thieves drain our accounts.

>Yes, we will not find a solution to political problems in cryptography, but we can win a major battle in the arms race and gain a new territory of freedom for several years.

--- 
## Debat
El potencial ambivalent d'una tecnologia disruptiva:

+ Autogestió econòmica VS Increment de desigualtats 

* Intel.ligència artificial, Big data...: Al.liat o defensa?

* Privacitat VS transparència

---
## Preguntes i debat
