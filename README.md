# roll6.net — Pirates de la Méditerranée

**Une mer, mille aventures.** Un site vitrine et un ensemble de prototypes de jeux de plateau
« papier-crayon » inspirés de l'histoire maritime des XVIe, XVIIe et XVIIIe siècles.

Le principe de la collection : **un dé de 6, un crayon, du papier — et c'est parti pour l'aventure.**
Pas de figurines à assembler, pas de matériel à acheter, pas de longues heures de préparation :
on dessine la carte, on note son navire, on lance le D6, et l'histoire commence.

🔗 Site : [roll6.net](https://roll6.net)

---

## Sommaire

- [Le projet](#le-projet)
- [Un travail de recherche au long cours](#un-travail-de-recherche-au-long-cours)
- [Contenu du dépôt](#contenu-du-dépôt)
- [Les jeux](#les-jeux)
- [Contribuer](#contribuer)
- [Licence](#licence)

---

## Le projet

`roll6.net` est une collection de jeux historiques, frugaux et accessibles. Chaque jeu doit tenir
sur une feuille, se comprendre en quelques minutes et se jouer avec un seul dé à six faces.

L'univers commun est la **Méditerranée des corsaires** : des ports, des routes maritimes, du commerce,
des alliances changeantes et des affrontements. Chaque extension peut explorer une région, une
ambition ou un destin différent.

Le projet est aussi un **site web fait main** : des pages HTML statiques, sans framework ni
dépendance externe, conçues pour rester lisibles, rapides et hébergeables n'importe où.

### Principes

| Principe | Ce que ça veut dire |
|---|---|
| **Frugal** | Un D6, un crayon, une feuille. Rien d'autre n'est requis. |
| **Rapide** | Des règles courtes, expliquées en une page. |
| **Historique** | Une inspiration assumée du monde méditerranéen du XVIe au XVIIIe siècle. |
| **Ouvert** | Tout est modifiable, imprimable et partageable. |
| **Accessible** | Un site statique, sans tracker, sans build, sans JavaScript inutile. |

---

## Un travail de recherche au long cours

> **Pirates de la Méditerranée n'est pas un projet improvisé : c'est un travail de recherche
> qui dure depuis longtemps.** vous pouvez voir [La Frise Chronologique](https://www.figma.com/design/u4aIZxcOnKkFYFPz5sH27d/Frise-Chronologique-France-Alg%C3%A9rie?node-id=0-1&t=o22X3ySVviql41H3-1)

Ce projet est le fruit d'une recherche patiente et continue, menée sur plusieurs années.

- **La recherche historique d'abord.** Comprendre les routes maritimes, les ports, les rivalités,
  le commerce, les conditions de navigation, les équipages, les navires et les hommes de la
  Méditerranée des XVIe, XVIIe et XVIIIe siècles. Derrière chaque règle simple se cache une
  question documentée : que transportait un petit marchand ? Qu'est-ce qu'un convoi exceptionnel ?
  Que gagnait réellement un corsaire ? Le butin se comptait-il en richesses ou en prestige ?

- **La recherche mécanique ensuite.** Transformer cette matière en un système jouable, tenant sur
  une feuille et se résumant avec un dé de 6. C'est le travail le plus long : il ne suffit pas
  d'ajouter des règles, il faut les retirer. La règle d'or affichée dans les règles du jeu le dit
  elle-même : *« Le jeu doit rester rapide et amusant. »*

- **La recherche sur le matériel, enfin.** Rendre le plateau imprimable chez soi, en format
  domestique (4 feuilles A4), testable et refaisable. Le plateau évolue : c'est pour cela qu'il
  existe plusieurs versions d'essai dans ce dépôt, chacune étant une étape où l'on apprend,
  où l'on corrige, où l'on recommence.

Ce dépôt n'est donc pas un point d'arrivée, mais un **état de recherche actuel**. Les versions
`test` ne sont pas des erreurs : ce sont les traces visibles du travail d'expérimentation. Les
règles, les zones, les valeurs de butin et le plateau lui-même sont voués à continuer d'évoluer
tant que la recherche n'est pas vraiment terminée — c'est-à-dire, selon toute vraisemblance,
jamais.

Le choix de tout écrire en HTML brut, sans outil ni dépendance, participe de la même démarche :
un travail de recherche doit rester **inspectable, modifiable et durable**. N'importe qui doit
pouvoir ouvrir un fichier, comprendre comment il est fait, et le modifier avec un simple éditeur
de texte.

---

## Contenu du dépôt

```
roll6-net/
├── index.html                          Page d'accueil du site (collection, extension, à venir)
├── corsaires.html                      Règles complètes de Corsaires d'Alger + mini-jeu jouable
├── others/
│   └── robots.html                     Prototype « Robot Monsters » (autre piste de jeu)
├── images/
│   ├── corsaires-d-alger.png           Visuel de l'extension Corsaires d'Alger
│   ├── plateau.png                     Visuel du plateau (panneau « Cap sur l'aventure »)
│   ├── plateau-test1.png               Version d'essai du plateau
│   └── plateau-test2.png               Version d'essai du plateau
├── docs/
│   ├── plateau_4_feuilles_A4.pdf       Plateau imprimable en 4 feuilles A4
│   ├── plateau-test1-a4.pdf            Plateau – version d'essai 1
│   ├── plateau-test2-a4.pdf            Plateau – version d'essai 2
│   └── Une mer, mille aventures.png    Visuel de la collection
├── LICENSE
└── README.md
```

## Les jeux

### Corsaires d'Alger — première extension

Jeu de stratégie et d'aventure pour **2 à 4 joueurs**. Chaque joueur dirige une maison de
corsaires basée à Alger : explorer la Méditerranée, capturer des navires, accumuler des richesses
et rentrer au port avant que la chance ne tourne.

- **Objectif** : atteindre 20 points de prestige et devenir le **Grand Corsaire d'Alger**.
- **Matériel** : 1 dé de 6, 1 feuille (le plateau), 1 stylo, ~30 papiers pour les cartes.
- **Un tour** : 3 actions — se déplacer, chercher, attaquer, réparer, recruter, vendre.
- **Le sel du jeu** : le butin n'est comptabilisé qu'une fois ramené à Alger. En mer, il est
  exposé aux tempêtes et aux autres corsaires.

→ Règles complètes, tableau des rencontres, combats, butin, prestige, événements et **mini-jeu
solo jouable dans le navigateur** : [`corsaires.html`](corsaires.html)

### Pistes à venir

D'autres extensions sont à l'étude, sans page dédiée à ce jour : *Les Corsaires de Tunis*,
*Malte, île des chevaliers*, *Les Routes du Levant*.

## Contribuer

Le dépôt se lit directement dans un navigateur : aucune installation, aucun build.

```bash
git clone https://github.com/nazimboudeffa/roll6-net.git
cd roll6-net
```

Ouvrez ensuite `index.html` dans un navigateur.

Pistes de contribution utiles : relever une incohérence historique dans les règles, proposer une
simplification de mécanique, améliorer le plateau imprimable, ou corriger une faute de français.
Comme il s'agit d'un travail de recherche, les désaccords argumentés sont bienvenus.

## Licence

Voir le fichier [`LICENSE`](LICENSE).
