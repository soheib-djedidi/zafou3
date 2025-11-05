# Rapport de réalisation des attendus

## 1. Corrections et améliorations réalisées
- Uniformisation de la navigation et du menu responsive sur l'ensemble du site.
- Ajout d'un pied de page commun contenant un formulaire de contact accessible.
- Correction des structures HTML (déclaration `<!DOCTYPE html>`, balises manquantes, script JS correctement référencé).
- Mise à jour de la page d'accueil avec des sections clarifiées et des liens fonctionnels vers toutes les pages.

**Capture à intégrer :** `![Navigation unifiée](A_REMPLACER_par_votre_capture.png)`
> *Légende suggérée : « Navigation homogène avec menu responsive actif. »*

## 2. Formulaire d'entraînement sur la page HTML
- Création d'un formulaire documenté en commentaires pour rappeler le rôle de chaque balise et attribut.
- Ajout d'une section pédagogique décrivant les attributs `method`, `action`, `required` et `name`.

**Capture à intégrer :** `![Formulaire d'entraînement documenté](A_REMPLACER_par_votre_capture.png)`
> *Légende suggérée : « Formulaire HTML annoté pour les apprenants. »*

## 3. Mémento des commandes Linux
- Nouvelle page `linux_command_line.html` présentant un tableau synthétique avec légende, en-têtes et portée (`scope`).
- Feuille de style dédiée (`css/linux_command_line.css`) pour mettre en valeur les données.
- Section explicative rappelant la fonction de chaque balise de tableau (`<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`).

**Capture à intégrer :** `![Tableau des commandes Linux](A_REMPLACER_par_votre_capture.png)`
> *Légende suggérée : « Tableau synthétique des commandes Linux étudiées. »*

## 4. Formulaire de contact commun (footer)
- Intégration du formulaire de contact dans le footer de toutes les pages (`index.html`, `pages/*.html`).
- Styles harmonisés via `css/Global.css` pour garantir lisibilité et accessibilité.
- Le formulaire reprend les champs Nom, E-mail et Message avec validation HTML.

**Capture à intégrer :** `![Formulaire de contact global](A_REMPLACER_par_votre_capture.png)`
> *Légende suggérée : « Formulaire de contact présent dans chaque footer. »*

## 5. Explication des attributs du formulaire
- `method` : choisie sur `post` pour envoyer les données de manière sécurisée.
- `action` : pointe vers une ancre locale (`#contact`) afin de centraliser la collecte ou le traitement ultérieur.
- `required` : empêche l'envoi du formulaire sans information essentielle.
- `name` : identifie chaque champ côté serveur afin de récupérer les valeurs soumises.

## 6. Lier CSS et HTML
- Les pages relient leurs styles avec `<link rel="stylesheet" href="chemin-vers-la-feuille.css" />` placé dans l'en-tête.
- Cette méthode permet de séparer le fond (HTML) de la forme (CSS), de réutiliser les mêmes styles sur plusieurs pages et de profiter du cache navigateur.

## 7. Pages en construction
- Création des pages d'attente pour JavaScript, PHP, Kotlin, Python, SQL, Angular, Git, GitHub et Linux.
- Chaque page signale l'état « en construction » tout en conservant la navigation et le formulaire de contact.

**Capture à intégrer :** `![Exemple de page en construction](A_REMPLACER_par_votre_capture.png)`
> *Légende suggérée : « Modèle de page en construction avec message informatif. »*

## 8. Synthèse des fichiers créés ou mis à jour
- `index.html`, `pages/html.html`, `pages/css.html` : restructuration, formulaires et navigation.
- `pages/linux_command_line.html` & `css/linux_command_line.css` : mémento des commandes Linux.
- `pages/javascript.html`, `pages/php.html`, `pages/kotlin.html`, `pages/python.html`, `pages/sql.html`, `pages/angular.html`, `pages/git.html`, `pages/github.html`, `pages/linux.html` : pages d'attente cohérentes.
- `css/Global.css` : palettes, typographies et styles des formulaires.
- `js/main.js` : sécurisation du script de navigation.

**Capture finale à intégrer :** `![Aperçu global du site](A_REMPLACER_par_votre_capture.png)`
> *Légende suggérée : « Aperçu des principales pages livrées. »*

---

*Remplacez chaque chemin `A_REMPLACER_par_votre_capture.png` par le fichier image correspondant une fois vos captures réalisées.*
