# Portfolio électronique · Biologie 12e préuniversitaire

Portfolio de biologie en français : table des matières, lettres d'ouverture et de clôture, cinq unités (scientifique ontarien, article, carrière, carte conceptuelle), carte des thèmes du cours, collage de photos et bibliographie.

## Fichiers

- `index.html` : le site complet (HTML, CSS et JavaScript dans un seul fichier, sans installation)
- `README.md` : ce fichier

## Publier avec GitHub Pages

1. Crée un dépôt sur GitHub (ex. `portfolio-biologie`), en public.
2. Téléverse `index.html` et `README.md` (**Add file** puis **Upload files**), puis **Commit changes**.
3. Va dans **Settings** puis **Pages**.
4. Sous **Build and deployment**, choisis **Deploy from a branch**, la branche `main` et le dossier `/ (root)`, puis **Save**.
5. Attends une ou deux minutes. Le lien apparaît en haut de la page **Pages** : `https://TON-NOM-GITHUB.github.io/portfolio-biologie/`

Ce lien est celui à donner à M. Mark dans le document Google Classroom.

## Modifier le contenu

- Ouvre `index.html` sur GitHub et clique sur le crayon (**Edit**).
- Les textes des unités sont dans le script, dans la liste `UNITS` (champs `f`, `sci`, `career`, `bib`). Les lettres sont dans les fonctions `letterOpen()` et `letterClose()`.
- Les passages en rose (classe `ph`) sont des exemples à remplacer.
- Enregistre avec **Commit changes**. Le site se met à jour en une ou deux minutes.

## À savoir

- Cette version est en lecture seule : les boutons de modification et d'ajout de photos sont cachés, car ce qui est écrit dans la page n'est sauvegardé que dans le navigateur du visiteur.
- Les photos du collage et des portraits ne sont pas incluses. Pour en ajouter, mets les images dans le dépôt et ajoute des balises `<img src="photo.jpg" alt="description">` dans `index.html`.
- Les polices viennent de Google Fonts : il faut une connexion internet.
- Les textes des unités 1 et 2 sont des exemples basés sur de vraies sources; vérifie-les avec M. Mark avant de les remettre.
