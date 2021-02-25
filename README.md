# Madame Juliette et les Ptimo

Bienvenue dans l'Univers de **Madame Juliette et les Ptimo**. MJP est un jeu de rôle dans lequel vous incarnez Madame Juliette, une scientifique de renom qui étudie des créatures magiques et mystérieuses, les Ptimo...

### But du jeu

Madame Juliette est reconnue comme étant la plus grande spécialiste en Ptimo, cependant trois Ptimos rares lui échappe. Le but du jeu est de capturer ces trois Ptimo !

### Système de jeu

Le jeu en tour par tour simule une suite de tentatives de capture de Ptimo. En lançant le jeu, on vous propose de tenter de capturer un Ptimo.

**Exemple d'interface**

![Image](./readme/1.png)


Si vous décidez de relever le défi vous vous retrouvez face à un des Ptimo suivants :

- Sacbleu (rare)
- Pyralia (très rare)
- Pokrand (existe t'il vraiment ?)

Pour capturer un Ptimo il faut être à moins d'un mètre de lui, mais chaque rapprochement à tendance à le rendre plus stressé.

Par ailleurs, plus le Ptimo est dominant, plus il risque de vous attaquer !

Afin de faire le bon choix vous devez prendre en compte l'état de stresse, le caractère dominant et la distance qui vous sépare du Ptimo.

À la fin d'une rencontre, vous avez le choix d'arrêter le jeu ou de tenter de capturer un autre Ptimo.

**Exemple d'actions**

![Image](./readme/2.png)


## Spécifications

### Ptimo

Les Ptimos sont des êtres sensibles et vos actions influent leurs sentiments ! Lors de son instanciation, un Ptimo se voit attribué des points de dominance et de stress compris entre (50 et 80). Ces deux attributs peuvent atteindre un maximum de 100 points.


Tous les Ptimos ont quatre actions possibles :

**Rugir :**
Permet au Ptimo de prendre confiance en lui (augmente les points de dominance et réduit son stress).

Un Ptimo va avoir tendance à plus souvent rugir lorsque qu'il sent que sa dominance est basse mais que son stress est haut. La distance influe aussi, à mois de 3m le Ptimo aura tendance à plus souvent attaqué et à plus de 10m à essayer de s'éloigner.

**Attaquer :**
Plus un Ptimo est dominant et plus il risque de vous attaquer.

Un Ptimo va avoir tendance à plus souvent attaquer lorsque sa dominace est haute. Par ailleurs, plus la distance est réduite ou le stress élevé et plus le risque d'attaque magique est grand.

Fréquence de l'attaque en fonction de la dominance : 0-30 (peu fréquent) 31-55 (assez fréquent) 56+ (très fréquent)

**S'éloigner :**
En début de rencontre un Ptimo se situe entre 8m et 15m de distance. Si il vient à s'éloigner à plus de 15m alors le Ptimo s'enfuit sans que vous puissiez le rattraper.

Plus le Ptimo est stressé et éloigné et plus il aura tendance à s'éloigner d'avantage.

Fréquence de l'éloignement en fonction du stress : 0-30 (peu fréquent) 31-55 (assez fréquent) 56+ (très fréquent)

**Attaque magique :**
Cette attaque est différente pour chaque Ptimo, plus vous êtes proche de lui et plus le risque d'attaque magique est grand. Si un Ptimo atteint un score de dominance de 100, cela déclenche automatiquement une attaque magique.

Vous êtes libre d'ajuster les fréquences pour rendre le jeu le plus fun possible !


#### Sacbleu

Le Sacbleu est un Ptimo au tempérament plutôt stressé et pas très dominant. Cependant il exite des Sacbleu 

#### Pyralia

Le Sacbleu est un Ptimo au tempérament plutôt stressé et pas très dominant. Cependant il exite des Sacbleu 

#### Pokrand

Une légende dit que le Pokrand est un Ptimo protecteur. Celui-ci viendrait dans le but de libérer les Ptimos que vous avez capturé...

Pour son attaque magique, Pokrand sort un jeu de cartes et s'en distribue 5 :

Si le combo de cartes est supérieur ou égale à un full, le Pokrand vous assome, libère les Ptimos et fuit.

Si le combo de cartes est supérieur ou égale à un brelan, le Pokrand fuit.

Si le combo est 

Pour rencontrer un Pokrand il faut que vous ayez capturé au moins 5 Ptimos 


### Juliette

Juliette a six actions possibles :

**Observer :**
Permet d'en savoir plus sur le Ptimo. Attention vous n'avez que des informations visuelles, mais à aucun moment un accès directe aux nombres de points de stress ou de dominance du Ptimo.

Score de stress : 0-25 (détendu) 26-50 (méfiant) 51-75 (nerveux) 75+ (paniqué)
Score de dominance : 0-25 (inoffensif) 26-50 () 51-75 (féroce) 75+ (dangereux)