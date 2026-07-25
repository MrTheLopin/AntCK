# Game Design Document (synthétique) – Jeu tycoon médiéval

## Pitch
Un jeune roi défend son royaume naissant contre une armée de morts-vivants, en combattant directement sur le terrain (arc à distance, épée au corps à corps) tout en développant son château et son économie grâce à des ouvriers.

## Piliers de gameplay
1. **Combat direct et engageant** — le joueur contrôle le roi lui-même, pas une vue de dessus abstraite.
2. **Gestion simple et lisible** — un château, quelques bâtiments, peu de ressources : la gestion ne doit jamais éclipser le combat.
3. **Tension progressive** — les vagues de morts-vivants montent en difficulté et poussent à renforcer défense et production en parallèle.

## Boucle de jeu (gameplay loop)
```
Explorer / combattre → gagner des ressources / repousser une vague
        ↓
Construire / améliorer des bâtiments
        ↓
Produire plus de ressources → plus de défense / plus d'ouvriers
        ↓
Affronter une vague plus difficile
```

## Personnage principal
- Le roi : monté à cheval pour le déplacement
- Arme à distance : arc
- Arme de mêlée : épée
- Le château : posé par le joueur, génère 3 ouvriers à la construction

## Ennemis
- Armée de morts-vivants : vagues d'ennemis de difficulté croissante
- Boss final : le roi des morts-vivants

## Bâtiments (v1 — à affiner)
- Production de ressource primaire (ex : ferme ou scierie)
- Bâtiment de transformation (ex : forge)
- Logement pour ouvriers supplémentaires
- Défense (mur, tour)

## Hors scope pour la v1
- Carte ouverte explorable
- Seigneurs rivaux gérés par IA
- Diplomatie

## Références de style
- Ambiance visuelle envisagée : ton plus sombre/grimdark, cohérent avec l'identité déjà développée pour RamForge (portfolio du studio).
