# Projet Individuel MGL7460-90 (Hiver 2020)

## Objectifs pédagogiques

Dans ce projet individuel, vous êtes en chargé par votre hiérarchie de l’analyse
d’un logiciel légataire afin d’estimer le risque pour votre compagnie d’accepter
un projet de tierce maintenance applicative sur ce logiciel.

Il est a votre charge d’identifier la méthodologie à mettre en oeuvre pour mener
l’analyse de ce logiciel, de la mettre en oeuvre, et de livrer vos conclusions
vis à vis de la “maintenabilité” du logiciel étudié sous la forme d’un rapport
de synthèse.

## Contraintes

  - Le logiciel étudié doit être disponible sur une plateforme de gestion de
    version (_e.g._, GitHub, Gitlab) de manière publique. Vous êtes entièrement
    libre du choix du projet (_e.g._, langage, taille, ...), mais votre choix
    doit être validé avec l’enseignant.
  - Si votre analyse utilise des scripts ou des outils, vous devez accompagner
    votre rapport de synthèse d’un dépôt de code contenant _(i)_ les scripts /
    chiffriers que vous avez développés et _(ii)_ comment installer et utiliser
    les outils que vous avez réutilisés
  - Le rapport de synthèse doit être livré au format PDF, faire 15 pages maximum
    (page de garde et annexes incluses, police times 11, interligne simple), et
    répondre aux questions d’analyse décrites dans ce sujet. Faites attention à
    la lisibilité des figures (on doit pouvoir lire une version imprimée de
    votre travail).
  - Vos réponses aux questions peuvent être technique, sans tomber dans le
    point de detail. Un développeur lambda doit être capable de comprendre vos
    réponses.
  - Sur la base de vos réponses aux questions d’analyse, vous produirez une note
    de synthèse d’environ une page en conclusion de votre rapport. Cette note
    donnera votre recommandation sur l’état du logiciel analysé, à l’attention
    de votre hiérarchie. Votre recommandation finale doit être de haut niveau,
    et prendre un recul global sur l’application.

## Cadre d'analyse de maintenance

Les thématiques suivantes ne sont pas une liste exhaustive. Vous ne devez pas
tout traiter dans votre projet. Il est de votre responsabilite d'identifier ce
qui a le plus de sens dans le cadre de votre étude.

Pour chaque question, vous êtes libre de choisir la représentation la plus
adaptée a votre projet. Par exemple pour la description de la modularité de
l’application, l’analyse d’un gros projet nécessitera un diagramme de composant
ou de paquetages, mais un projet de taille plus modeste pourrait utiliser un
diagramme de classe. Vous devez justifier vos choix d’outils d’analyse ainsi que
votre méthodologie.


### Dimension "Équipe de développement"

  1. Qui sont les développeurs principaux du projet ?
  2. L'équipe de développement est-elle stable, ou y a t'il beaucoup de rotation ?
  3. Comment est répartie la paternité du code source dans l'équipe ?
  4. Comment les développeurs communiquent entre eux ?

### Dimension "Exigences"

  1. Comment le code source est-il tracé aux exigences ?
  2. Quelle est la vélocité de l'équipe de développement sur la maintenance corrective ?
  3. Quel est le volume d'exigence traité dans le projet ?

### Dimension "Architecture logicielle"

  1. Quels sont les composants principaux de l'application ?
  2. Comment est gérée la modularité de l'application ?
  3. Comment est documentée l'architecture de l'application ?


### Dimension "Code source"

  1. Comment qualifiez vous la _qualité_ du code source ?
  2. Quels outils de construction sont utilisés ?
  3. Quel modèle de branche est utilisé dans le développement du projet ?
  4. Dans quelle mesure la compilation du code est-elle reproductible ?
  5. A quel point le code est-il dépendant de bibliothèques externes ?

### Dimension "Tests"

  1. Quelles sont les méthodes de tests mise en place dans le projet ?
  2. Comment qualifiez vous la _qualité_ des tests mis en oeuvre ?
  3. Dans quelle mesure les tests sont-ils reproductible ?

### Dimension "Déploiement & Livraison"

  1. Quels outils d'intégration / déploiement continus sont mis en place ?
  2. Comment sont gérées les dépendances logicielle dans le projet ?
  3. Quelle méthodologie de publication (_releasing_) est mise en place ?

## Livrables

  - `L0` : Choix du sujet (en message direct sur Slack)
  - `L1` : Rapport intermédiaire.
    * Doit définir les questions qui vont être traitées
    * Doit répondre à un sous-ensemble de ces questions
  - `L2`: Rapport de synthèse final.
    * Contient les corrections demandées suite à la rétroaction sur `L1`;
    * Répond aux questions identifiées;  
    * Contient la note de synthèse sur le logiciel

_Astuce_ : Plus votre rapport intermédiaire contient d'information, plus vous obtiendrez de rétro-action sur votre travail.

## Critères d'évaluation

tba

## Sujets Choisis à cette session :

  1. Marc-André: Logiciel `Krita`
    * Dépôt de code : [https://github.com/KDE/krita](https://github.com/KDE/krita)
