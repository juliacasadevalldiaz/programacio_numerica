
## Tasca M3 T01
En aquesta tasca treballaràs amb la llibreria numpy i amb les dades de la llibreria sklearn.datasets. D'aquesta llibreria descarrega el conjunt de dades denominat Iris.
Tingues en compte que Iris està conformada per diversos conjunts de dades, dins d'ells, el array denominat: “data” i “target”. També està composta per llistes, per exemple: “feature_*names” i “target_*names”.
Per a obtenir informació del dataset pots consultar el següent enllaç:
-> sklearn.datasets.load_iris

- Exercici 1
Carregar “data” i "target" del conjunt de dades, i visualitza els 10 primers registres de cadascun.

- Exercici 2
Concatena “data” i “target” en un nou array. Mostra els 5 primers registres.

- Exercici 3
Calcula la mitjana i desviació estàndard de la longitud del sèpal ("sepal length (cm)") i la longitud del pètal ("petal length (cm)"). Mostra els resultats amb dos decimals.

- Exercici 4
Selecciona una mostra aleatòria de 20 registres del conjunt que has obtingut en l'exercici anterior.

- Exercici 5
Crea una matriu que mostri: 

• La mitjana de cada característica per espècie. 

• La desviació estàndard de cada característica per espècie.

- Exercici 6
• Calcula la quantitat de mostres per espècie.

• Troba l'espècie amb el valor màxim mitjana de la variable "sepal length (cm)"

- Exercici 7
• Calcula la matriu de correlació entre les variables.

• Filtra els valors majors a la mitjana de la longitud dels pètals i mostra-ho. 

• Troba la mostra amb els pètals més grans.

- Exercici 8
Troba l'espècie amb la diferència més gran entre la longitud mitjana de sèpals i pètals.

## Tasca M3 T02
Exercicis amb Dataframes.

- Exercici 1
Descarrega el data set Airlines Delay: Airline on-time statistics and delay causes i carrega’l a un Pandas Dataframe. Explora les dades que conté, explica breument quines variables hi ha i queda’t únicament amb les columnes que consideris rellevants. Justifica la teva elecció.
->Airlines Delay: Airline on-time statistics and delay causes
 Important
Redueix la dimensió del dataset de manera aleatòria per tal d'obtenir un dataset de només 200.000 registres. Tots els exercicis s'han de fer amb aquest dataset reduït.

- Exercici 2
Fes un informe complet del dataset:

Resumeix estadísticament el dataset i les columnes d’interès. Fes una anàlisi estadístic del que consideris rellevant.
Troba quantes dades faltants hi ha per columna.
Crea columnes noves (velocitat mitjana del vol, si ha arribat tard o no...).
Fes una taula de les aerolínies amb més endarreriments acumulats.
Quins són els vols més llargs? I els més endarrerits? Busca les rutes més llargues i les que acumulen més retards.
Aporta allò que consideris rellevant.

- Exercici 3
Exporta el dataset net i amb les noves columnes a Excel.
