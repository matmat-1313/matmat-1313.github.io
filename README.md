# D’hier à aujourd’hui — site associatif

Site statique multipage en HTML, CSS et JavaScript, conçu pour GitHub Pages.

## Avant publication : liste obligatoire

1. Remplacer `VOTRE-PSEUDO.github.io` dans les balises `canonical`, les métadonnées `og:url`, `robots.txt` et `sitemap.xml` par la véritable URL du site.
   - Site de compte GitHub : `https://PSEUDO.github.io/`
   - Site d’un dépôt de projet : `https://PSEUDO.github.io/NOM-DU-DEPOT/` (adapter aussi les chemins canoniques du sitemap).
2. Remplacer l’adresse de démonstration `CONTACT-A-REMPLACER@example.org` dans `adhesion.html` par l’adresse officielle.
3. Compléter `mentions-legales.html` et `politique-confidentialite.html` avec les informations exactes de l’association et des traitements réels.
4. Remplacer les actualités de démonstration par des événements confirmés.
5. Remplacer les illustrations SVG de démonstration par des photographies dont l’association détient les droits ou pour lesquelles elle a les autorisations nécessaires.
6. Vérifier tous les liens, le nom officiel, les modalités d’adhésion et les coordonnées avant lancement.

## Arborescence

- `index.html` : accueil
- `association.html` : présentation
- `photographie.html` : pratique et galerie
- `genealogie.html` : archives et transmission
- `actualites.html` : annonces
- `adhesion.html` : contact / adhésion
- `mentions-legales.html`, `politique-confidentialite.html`
- `assets/css/style.css` : styles responsives
- `assets/js/main.js` : menu mobile et année du pied de page
- `robots.txt`, `sitemap.xml`, `assets/images/`

## Publication GitHub Pages

1. Créez un dépôt GitHub public, par exemple `dhier-a-aujourdhui`.
2. Téléversez le contenu du dossier, en conservant la structure.
3. Dans **Settings → Pages**, choisissez **Deploy from a branch**, la branche `main` et le dossier `/ (root)`, puis enregistrez.
4. Attendez le déploiement et ouvrez l’URL indiquée par GitHub Pages.
5. Testez les pages sur mobile et ordinateur, ainsi que `robots.txt` et `sitemap.xml`.
6. Dans Google Search Console, ajoutez la propriété URL exacte, vérifiez-la, puis soumettez le sitemap. L’indexation n’est pas instantanée ni garantie.

## Limites importantes

GitHub Pages héberge des fichiers statiques : il n’exécute pas PHP et ne fournit pas de base de données. Cette version n’a donc pas d’espace membre, de base d’adhérents ni de formulaire serveur. Le bouton de contact utilise `mailto:`. Pour collecter des demandes en ligne, choisissez ultérieurement un prestataire de formulaire adapté, informez les visiteurs et vérifiez ses conditions de confidentialité.

## Sécurité généalogique et droit à l’image

- Ne publiez pas d’arbres détaillés ou de données identifiantes sur des personnes vivantes sans base légale et autorisation appropriées.
- Ne mettez jamais en ligne des actes, coordonnées privées ou documents confidentiels.
- Vérifiez les droits d’auteur et les autorisations de diffusion des photos ; prudence renforcée pour les mineurs.
- N’ajoutez jamais de mots de passe, clés API ou fichiers de membres au dépôt public.
- Le site est public : un dépôt GitHub Pages public ne convient pas à un espace généalogique privé.

## Accessibilité

Le modèle inclut un lien d’évitement, des libellés de navigation, un menu mobile accessible, des états de focus visibles et une prise en compte de `prefers-reduced-motion`. Avant publication, testez au clavier, sur mobile, avec zoom à 200 %, et ajoutez des textes alternatifs pertinents aux vraies photos.


## Page Contact

La page `contact.html` utilise la feuille de style partagée `assets/css/style.css` et le menu mobile `assets/js/main.js`.

Avant publication :
- Remplacer `CONTACT-A-REMPLACER@example.org` dans `contact.html` par l’adresse e-mail officielle de l’association (à la fois dans `CONTACT_EMAIL` et dans le lien visible).
- Remplacer les URL `https://VOTRE-PSEUDO.github.io/` dans les balises canoniques et dans `sitemap.xml` par l’URL réelle du site.
- Vérifier et compléter les mentions légales et la politique de confidentialité.
- Le formulaire ouvre le logiciel de messagerie du visiteur : il ne transmet pas les messages directement depuis GitHub Pages.


## Thème clair

Le thème global a été harmonisé en clair (ivoire, blanc cassé et bronze), y compris l’en-tête, les bandeaux de page, les menus mobiles et le pied de page. Le logo définitif reste à fournir pour remplacer le monogramme provisoire.


## Positionnement de l’association

Le site présente l’association comme proposant des ateliers de retouche photo sur ordinateur, organisés dans une salle équipée, pour les personnes de tous niveaux (débutants à avancés), ainsi que des activités de généalogie. L’association n’est pas présentée comme un studio de photographie ou comme un groupe de photographes professionnels.


## Logo officiel
Le logo fourni par l’association est placé dans `assets/images/logo-association.png`. Il est utilisé dans l’en-tête et le pied de page et reste cliquable vers `index.html`. Le fichier image du logo est conservé sans modification. Le nom de l’association est affiché en texte à côté du logo afin de rester lisible sur ordinateur et mobile.


## Visuels des deux cartes de la page d’accueil

Les visuels personnalisés sont `assets/images/accueil-retouche-photo.png` et `assets/images/accueil-genealogie.png`. Ils sont affichés dans les deux cartes cliquables de la page d’accueil ; les liens vers `photographie.html` et `genealogie.html` sont conservés.


## Formulaire de contact

La page `contact.html` reprend le fonctionnement du formulaire de référence : le visiteur remplit les champs sur le site, puis le bouton ouvre sa messagerie avec le destinataire, le sujet et le message préremplis. Le site ne transmet pas directement les messages. Avant publication, remplacez `CONTACT-A-REMPLACER@example.org` dans `contact.html` (lien visible et constante `CONTACT_EMAIL`) par l’adresse officielle.
