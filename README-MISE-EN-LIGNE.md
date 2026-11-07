# BKTECH Maintenance — Site internet

Site HTML/CSS/JS autonome, sans base de données ni formulaire.

## Aperçu local
Dans ce dossier : `python -m http.server 8000`, puis ouvrir `http://localhost:8000`. Ne pas ouvrir directement les pages en file://, car les liens sont absolus.

## Publication
1. Uploader le contenu de ce dossier (index.html, articles/, services/, assets/, sitemap.xml, robots.txt) dans la racine publique du domaine.
2. Activer HTTPS.
3. Domaine actuel dans les balises canoniques et le sitemap : `https://bktechmaintenance.be`. Si nouveau domaine, remplacer partout `https://bktechmaintenance.be` par le domaine final avant publication.
4. Intégrer **le véritable logo officiel BKTECH** dans l’en-tête en remplacement du monogramme B provisoire. Fichier logo non fourni dans cet environnement.
5. Vérifier le téléphone `0471 31 34 04`, l’adresse, la TVA et la disponibilité affichés.
6. Compléter l’hébergeur dans `mentions-legales.html` et vérifier les informations juridiques/privacy avant la mise en ligne.
7. Ajouter le sitemap dans Google Search Console et mettre le site sur la fiche Google Business Profile.
8. Ajouter de vraies photos d’interventions avec autorisation, et compléter les articles dans le temps.

## Contact prioritaire
- Téléphone : `0471 31 34 04` (tous les boutons click-to-call)
- WhatsApp : `https://wa.me/32471313404`
- E-mail : `info@bktechmaintenance.com`

## Fichiers
- `index.html`: accueil
- `services/`: trois pages prestations
- `articles/`: six articles référencement + index
- `zones-intervention.html`, `contact.html`, `a-propos.html`
- `mentions-legales.html`, `confidentialite.html`
- `robots.txt`, `sitemap.xml`

## SEO
Titres et meta descriptions uniques, balises canonical, liens internes, sitemap, données structurées HVACBusiness. Les classements Google ne sont jamais garantis.

## Numéros affichés
Les deux numéros 0471 31 34 04 et 0499 19 32 54 sont cliquables sur toutes les pages, y compris dans la barre d’appel fixe sur mobile. Le menu de navigation reste visible pendant le défilement (position sticky).


## Articles SEO ajoutés le 7 novembre 2026

- 30 articles originaux supplémentaires, soit 36 guides.
- Sitemap mis à jour automatiquement, liens et descriptions uniques.
- Thèmes inspirés des questions courantes identifiées chez des acteurs du marché, textes entièrement rédigés pour BKTECH.
- Les volumes de recherche et les positions Google ne sont pas garantis.
- Valider le domaine définitif et soumettre le sitemap à Google Search Console avant publication.
- Vérifier périodiquement les notices et réglementations avant de maintenir les articles techniques en ligne.


## Logo officiel
Le logo blanc transparent BKTech Maintenance est inclus dans `assets/logo-bktech-officiel.png` et intégré dans toutes les pages. Garder le bandeau sombre pour garantir sa lisibilité.
