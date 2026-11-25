# Evaluation mi-parcours - HTML & CSS de base

**Chapitres couverts : 1 a 12**
(Structure HTML, texte, liens, images, listes, tableaux, formulaires, introduction CSS, typographie, DevTools, selecteurs, box model)

> **Remarque importante** : Flexbox, le responsive, le positionnement avance et l'accessibilite avancee n'ont **pas encore ete vus** au moment de cette evaluation. Vous n'en avez pas besoin pour reussir le projet. Concentrez-vous sur ce que vous savez faire proprement.

---

## Consigne generale

Vous allez realiser **un mini-site d'une seule page** (single page) avec HTML et CSS.

**Vous avez le choix entre 3 sujets**. Choisissez **UN SEUL sujet** parmi les trois proposes ci-dessous. Tous les sujets sont equivalents en difficulte et notes sur le meme bareme.

---

## Sujet 1 - Fiche d'un restaurant

Vous presentez un restaurant (reel ou imaginaire) sur une page web.

**Sections obligatoires :**
1. **En-tete** : nom du restaurant (h1), slogan, navigation interne (liens d'ancre vers les sections)
2. **Presentation** : un paragraphe d'introduction, une image de la salle ou de la facade
3. **Le menu** : un **tableau** avec au moins 6 plats (colonnes : plat, description, prix). Au moins une categorie en `<thead>`.
4. **Galerie photos** : 3 a 6 images des plats (chacune avec un `alt` descriptif)
5. **Horaires** : presentes sous forme de **liste** (jour - horaires)
6. **Formulaire de reservation** : nom, email, telephone, date, nombre de personnes, message, bouton "Reserver". Tous les champs avec `<label>`.
7. **Pied de page** : adresse, telephone, mention legale

---

## Sujet 2 - Page d'un evenement

Vous presentez un evenement de votre choix (concert, conference, festival, salon, soiree associative...).

**Sections obligatoires :**
1. **En-tete** : titre de l'evenement (h1), date et lieu, navigation interne
2. **Presentation** : description de l'evenement, image d'illustration
3. **Programme** : un **tableau** des creneaux (colonnes : heure, activite, intervenant). Minimum 6 creneaux.
4. **Intervenants** : 3 a 6 cartes (article ou div) avec photo, nom (h3), role, courte bio
5. **Infos pratiques** : presentees sous forme de **liste** (acces, tarif, public, contact...)
6. **Formulaire d'inscription** : nom, email, telephone, type de billet (radio ou select), nombre de places, message, bouton "S'inscrire". Tous les champs avec `<label>`.
7. **Pied de page** : organisateur, contact, reseaux sociaux

---

## Sujet 3 - Fiche d'une recette de cuisine

Vous presentez une recette (reelle ou imaginaire) de maniere claire et appetissante.

**Sections obligatoires :**
1. **En-tete** : nom de la recette (h1), une accroche, navigation interne
2. **Presentation** : photo principale du plat, paragraphe descriptif, mention du temps de preparation, du temps de cuisson et du nombre de personnes
3. **Ingredients** : sous forme de **liste non ordonnee** (au moins 8 ingredients avec quantites)
4. **Etapes** : sous forme de **liste ordonnee** (au moins 6 etapes detaillees)
5. **Valeurs nutritionnelles** : un **tableau** (colonnes : nutriment, quantite par portion, % AJR). Minimum 5 lignes.
6. **Galerie** : 3 a 4 images (etapes ou variantes du plat)
7. **Formulaire de commentaire** : nom, email, note (radio ou select de 1 a 5), commentaire, bouton "Publier". Tous les champs avec `<label>`.
8. **Pied de page** : auteur, date, mention legale

---

## Exigences communes a tous les sujets

### HTML (chapitres 1 a 7)

- [ ] DOCTYPE, langue (`lang="fr"`), encodage UTF-8, balise `<title>` adaptee
- [ ] Structure semantique : `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- [ ] Hierarchie correcte des titres (un seul `h1`, puis `h2`, `h3`...)
- [ ] Au moins une **liste** (ordonnee ou non) selon le sujet
- [ ] Au moins un **tableau** avec `<thead>`, `<tbody>`, `<th>`, `<td>`
- [ ] Au moins **3 images** avec un attribut `alt` pertinent
- [ ] **Liens d'ancre** internes fonctionnels dans la navigation (`href="#section"`)
- [ ] Au moins un **lien externe** (`target="_blank"` recommande pour les liens externes)
- [ ] Un **formulaire** complet avec `<label for="...">` lie a chaque `<input>` via `id`
- [ ] Utilisation de plusieurs **types d'input** differents (text, email, tel, date, number, radio, select, textarea...)
- [ ] Bouton de soumission

### CSS (chapitres 8 a 12)

- [ ] **Fichier CSS externe** (`style.css`) lie au HTML via `<link>`
- [ ] Reset minimal en haut du fichier (`* { box-sizing: border-box; margin: 0; padding: 0; }`)
- [ ] Au moins une **police personnalisee** (Google Fonts ou pile de polices safe)
- [ ] Utilisation de **plusieurs types de selecteurs** : par balise, par classe, par id, descendant, pseudo-classe (`:hover` au minimum)
- [ ] Couleurs coherentes (palette de 2 a 4 couleurs)
- [ ] Tailles de police lisibles, hierarchie visuelle claire
- [ ] **Box model** maitrise : usage de `padding`, `margin`, `border`, `border-radius`
- [ ] Au moins une **bordure stylisee** (couleur, epaisseur, style)
- [ ] Au moins un **effet au survol** (`:hover`) sur les liens ou les boutons
- [ ] Au moins une **boite centree** horizontalement avec `margin: 0 auto`
- [ ] Une **carte** ou un **bloc encadre** avec ombre (`box-shadow`)
- [ ] Le **tableau** doit etre stylise (bordures, padding dans les cellules, fond alterne sur les lignes par exemple)
- [ ] Le **formulaire** doit etre stylise (champs avec padding, bordures, focus visible)

### Qualite generale

- [ ] Code **indente proprement**
- [ ] **Commentaires** dans le HTML pour separer les sections
- [ ] **Commentaires** dans le CSS pour separer les blocs de regles
- [ ] Aucune erreur dans la console des DevTools
- [ ] Le site est testable dans le navigateur (s'ouvre, s'affiche, les liens fonctionnent)

---

## Bareme - 20 points

| Critere | Points |
|---------|-------:|
| **Structure HTML** (DOCTYPE, semantique, hierarchie titres) | 3 |
| **Contenu obligatoire du sujet** (toutes les sections demandees presentes) | 3 |
| **Tableau** (structure correcte avec thead/tbody, contenu pertinent) | 1.5 |
| **Liste(s)** (utilisation correcte de ul/ol/li) | 1 |
| **Images** (presence, alt descriptif, chemin correct) | 1 |
| **Liens** (internes d'ancre fonctionnels + au moins un externe) | 1 |
| **Formulaire** (labels lies, types varies, bouton soumission) | 2 |
| **CSS - selecteurs varies et organisation** | 2 |
| **CSS - typographie et couleurs** (police importee, palette coherente) | 1.5 |
| **CSS - box model** (padding, margin, border, border-radius bien utilises) | 2 |
| **CSS - effets** (hover, box-shadow, borders stylises) | 1 |
| **Soin general** (indentation, commentaires, pas d'erreur console) | 1 |

**Total : /20**

---

## Consignes de rendu

**Tout rendu après la date limite du 26 mai sera pénalisé (-2 points par jour de retard).**

1. Travaillez dans le dossier `evaluation-mi-parcours/` qui vous a ete fourni.
2. Modifiez les fichiers `index.html` et `style.css`.
3. Vous pouvez creer un dossier `images/` pour vos images. Si vous ne trouvez pas d'images libres de droit, utilisez des placeholders comme `https://picsum.photos/600/400` ou `https://placehold.co/600x400`.
4. **Au debut de votre `index.html`, indiquez en commentaire le sujet choisi** (1, 2 ou 3) et votre nom.
5. Rendu : un fichier zip contenant `index.html`, `style.css` et le dossier `images/` si necessaire.

---

## Conseils

- **Commencez par le HTML en entier** avant de toucher au CSS. Un site mal structure ne sera jamais bien stylise.
- Utilisez les **DevTools (F12)** pour inspecter votre box model et corriger les espaces.
- N'essayez pas de faire un design tres complexe. **Simplicite et coherence** valent mieux que surcharge.
- Pas de Flexbox : pour aligner des elements cote a cote, utilisez `display: inline-block` (vu au chapitre 12).
- Testez votre formulaire : tous les labels doivent etre cliquables et focaliser le bon champ.
- Sauvegardez regulierement et rechargez la page pour voir vos modifications.

Bon courage !