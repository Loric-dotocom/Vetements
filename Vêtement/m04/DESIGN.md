# DESIGN.md — RELIEF

## 1. Concept & positionnement

RELIEF est une marque de vêtements qui vend des ensembles pensés, pas des pièces isolées. La promesse : des vêtements originaux mais discrets, portables normalement dans la rue. Le nom RELIEF (du verbe *relever*) porte l'idée centrale : rien n'est plat. La sobriété de la palette ne doit jamais se lire comme de la simplicité — le design doit sentir qu'il domine, par la matière, la texture et la forme, jamais par la couleur ou le motif.

## 2. Palette de couleurs

- Noir, blanc, nuances de gris — palette strictement neutre.
- Aucune couleur vive ou flashy, même en accent.
- Le contraste et la hiérarchie visuelle se font par la valeur (clair/foncé), pas par la teinte.
- *À préciser en codant : les gris exacts (2-3 nuances suffisent — un gris clair de fond, un gris moyen pour le texte secondaire, un gris foncé proche du noir pour le texte principal).*

## 3. Typographie

- **Titres / nom RELIEF :** Ogg — serif contrasté, éditorial, donne le caractère et la "vie" à l'identité.
- **Texte courant / navigation :** une sans-serif neutre (Inter ou Söhne) — pour ne pas concurrencer Ogg et garder le texte lisible.
- Contraste volontaire entre les deux : le titre respire et affirme, le texte reste discret.

## 4. Texture & matière

- Pas de grain photographique : la texture est **vectorielle**, dessinée, jamais une photo floutée en fond.
- Motif de vagues vectorielles (SVG), discret, en arrière-plan de certaines zones — jamais au premier plan, jamais sur le texte lisible.
- Objectif : que la page ne paraisse jamais plate, même en restant strictement noir/blanc/gris.

## 5. Grille & mise en page

- Mise en page aérée, beaucoup d'espace blanc.
- L'espace fait partie du "relief" : il donne de l'air aux vêtements et aux vagues vectorielles pour respirer, sans surcharge.
- Grille simple, colonnes larges plutôt que denses.

## 6. Imagerie / photographie

- Photos des mannequins en noir et blanc / désaturé.
- Cohérent avec la palette : aucune couleur, y compris dans les photos, ne doit venir concurrencer le texte ou les vêtements.
- Le contraste des photos peut servir de deuxième niveau de "relief" (jeu d'ombre et de lumière sur les vêtements eux-mêmes).

## 7. Composants UI *(proposition à valider/ajuster)*

- Boutons discrets : contour fin, pas de fond plein sauf au survol/état actif.
- Cartes produit (ensembles) : bordures fines, pas d'ombre portée lourde — la séparation se fait par l'espace, pas par un encadré marqué.
- Navigation minimale, texte seul, pas d'icônes superflues.

## 8. Ton & voix

- Minimal, presque silencieux : peu de texte, chaque mot compte.
- Pas de discours de vente classique ("découvrez notre nouvelle collection exceptionnelle...") — le vêtement et l'image parlent, le texte accompagne sans en rajouter.

## 9. Do's & Don'ts

**On fait :**
- Palette noir / blanc / gris
- Texture vectorielle (vagues), légère et discrète
- Serif éditorial (Ogg) pour les titres, sans-serif neutre pour le texte
- Espace généreux, silence dans le texte

**On ne fait pas :**
- Motifs chargés ou imprimés complexes
- Couleurs vives ou flashy
- Vrai système d'avis clients (hors cadre HTML/CSS) — remplacé par une sélection curée par la marque
- Vente de pièces isolées — toujours des ensembles
- Discours marketing verbeux
