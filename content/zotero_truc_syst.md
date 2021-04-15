# Trucs et astuces pour optimiser l'utilisation de Zotero dans le contexte d'une revue de littérature ou d'une revue systématique

<!-- MDTOC maxdepth:1 firsth1:0 numbering:0 flatten:0 bullets:1 updateOnSave:1 -->

- [Enregistrer les références par import de fichier plutôt que par le connecteur Zotero (bouton "Save to Zotero" dans votre navigateur)](#enregistrer-les-références-par-import-de-fichier-plutôt-que-par-le-connecteur-zotero-bouton-save-to-zotero-dans-votre-navigateur)   
- [Organiser sa bibliothèque avec des marqueurs](#organiser-sa-bibliothèque-avec-des-marqueurs)   
- [Automatiser et optimiser la recherche du texte intégral](#automatiser-et-optimiser-la-recherche-du-texte-intégral)   

<!-- /MDTOC -->

## Enregistrer les références par import de fichier plutôt que par le connecteur Zotero (bouton "Save to Zotero" dans votre navigateur)

Cliquer sur le bouton "Save to Zotero" est la meilleure méthode pour enregistrer des documents dans votre bibliothèque au fil de votre navigation dans les bases de données, lorsqu'il s'agit d'enregistrer un document après l'autre.

Dans le cadre d'une revue de littérature où vous devez enregistrer d'un seul coup depuis une base de données tous les résultats d'une équation de recherche, l'import de fichier est plus adapté, car beaucoup plus rapide.

Voici comment procéder dans Scopus et PubMed, à partir d'une liste de résultats.

### Scopus : importer les références dans un fichier

Dans la barre de menu grisée juste au-dessus de la liste de résultats :

1. Cochez la case _All_ >_Select All_.
2. Puis cliquez sur _RIS export_ et choisissez les informations à exporter.

**/!\\ N'oubliez pas le résumé, il n'est pas inclus par défaut.**

3. Cliquez sur _Export_.
4. Une boîte de dialogue s'affiche, choisissez "Ouvir avec" > "Zotero".
5. Les références sont automatiquement importées dans votre bibliothèque.

### PubMed : importer les références dans un fichier

1. Cliquez sur _Send to_ > _Citation manager_.
2. Dans le menu _Selection_ choisissez _All results_.
3. Enregistrez le fichier **.nbib** ainsi généré sur votre ordinateur.
4. Allez ensuite dans Zotero, dans le menu _Fichier_ >_Importer..._ et sélectionnez ce fichier **.nbib**.
5. Suivez les étapes, les références sont automatiquement importées dans votre bibliothèque.

Plus d'infos : [Cours "Introduction à Zotero, votre assistant de recherche personnel" > section " Constituer sa bibliothèque Zotero étape 1, ajouter des documents et des fichiers"](https://github.com/fflamerie/zotero_intro_FR/blob/master/content/zotero_intro_FR_COURS.md#3-constituer-sa-biblioth%C3%A8que-zotero-%C3%A9tape-1-ajouter-des-documents-et-des-fichiers)

## Organiser sa bibliothèque avec des marqueurs

Zotero dispose de plusieurs outils pour organiser une bibliothèque :

* les collections -> plus ou moins des dossiers, plutôt des listes de lecture,
* les marqueurs -> des mots-clés,
* les recherches enregistrées -> des collections dynamiques,
* les documents connexes -> pour établir des liens entre les documents,
* les notes -> indexées par le moteur de recherche de Zotero, saisies dans un éditeur html permettant une mise en forme.

![zotero_organisation_overview](img/zotero_organisation_overview_en.png)

Pourquoi privilégier les marqueurs plutôt que les collections?

2 raisons principales :

* **Lisibilité** : grâce à l'onglet "Marqueurs" du volet de droite vous visualisez immédiatement tous les marqueurs associés à un document ; grâce aux **marqueurs colorés** vous visualisez rapidement tous les documents associés à un marqueur.
* **Portabilité** : les marqueurs font partie des informations bibliographiques du document et sont ainsi, par exemple, exportés au même titre que toutes les autres informations bibliographiques lorsque vous exportez des documents dans un fichier au format .ris, . csv, etc. Les collections et les recherches enregistrées relèvent en revanche de **l'interface** de votre bibliothèque, l'information du classement dans une collection n'est pas enregistrée en tant qu'information bibliographique du document.

Plus d'infos : [Cours "Introduction à Zotero, votre assistant de recherche personnel" > section "Constituer sa bibliothèque Zotero étape 2, organiser le contenu"](https://github.com/fflamerie/zotero_intro_FR/blob/master/content/zotero_intro_FR_COURS.md#4-constituer-sa-biblioth%C3%A8que-zotero-%C3%A9tape-2-organiser-le-contenu)

### Rappel en images : créer un marqueur dans un document et lui attribuer une couleur

![gif_ajout_tag](img/ZoteroTags.gif)

_Source : [Mini-site Zotero Lausanne > Tutoriel Zotero](https://lausannecitationstyle.github.io/support/3.html)_

## Automatiser et optimiser la recherche du texte intégral

Zotero dispose de fonctionnalités par défaut pour rechercher et enregistrer automatiquement le texte intégral, telles que les suivantes.

* **L'enregistrement automatique du PDF présent sur une page web** lorsque vous utilisez le connecteur Zotero (bouton Zotero dans votre navigateur).
* La détection et l'enregistrement automatiques du **proxy de l'université** pour vous rediriger vers les accès souscrits par l'université lorsque vous naviguez sur les sites des éditeurs - voir [Documentation Zotero : Les préférences du connecteur Zotero > Préférences pour les serveurs mandataires](https://www.zotero.org/support/fr/connector_preferences?do=#preferences_pour_les_serveurs_mandataires).
* La recherche automatique de **PDF disponibles en libre accès** grâce à Unpaywall - [description de la fonctionnalité sur le blog Zotero francophone](https://zotero.hypotheses.org/2130).

Deux fonctionnalités complémentaires vous permettent d'augmenter ces fonctions de recherche. Elles sont toutes les 2 accessibles depuis **le menu _Localiser_**, c'est-à-dire la flèche verte en haut du volet de droite dans votre bibliothèque Zotero. Il s'agit de :

* la **configuration OpenURL** pour l'Université de Bordeaux,
* la personnalisation des **moteurs de recherche intégrés à Zotero**.


### Configuration OpenURL

Pour la configuration OpenURL, il suffit :

* d'aller à l'onglet _Avancées_ > _Générales_ des _Préférences_,
* dans le champ _OpenURL_ > _Résolveur des liens_, coller l'URL suivante :

```
https://babordplus.hosted.exlibrisgroup.com/primo-explore/openurl?&Force_direct=false&vid=33PUDB_UB_VU1&institution=33PUDB_UB&
```

* En cliquant sur le menu _Localiser_ > _Rechercher dans la bibliothèque_, vous afficherez le document dans Babord+ avec toutes les options d'accès de l'université de Bordeaux.

### Moteurs de recherche intégrés à Zotero

Ces moteurs de recherche vous permettent de lancer une recherche dans diverses sources pour trouver un fichier de texte intégral disponible sur un site web personnel  (moteurs Google, Google Scholar), ou pour compléter les informations bibliographiques de vos documents (moteur Sudoc pour les livres et les thèses, moteur PubMed pour les articles).

Pour en savoir plus concernant la personnalisation des moteurs de recherche et découvrir d'autres moteurs que ceux installés dans le fichier de moteurs préconfiguré ci-dessous, consultez le billet du blog Zotero francophone [Les moteurs de recherche intégrés à Zotero](https://zotero.hypotheses.org/3388).

#### Fichier de moteurs de recherche préconfiguré

Vous trouverez dans le fichier [engines_BX-svs.json](https://github.com/fflamerie/zotero_intro_FR/blob/master/content/engines_BX-svs.json) les moteurs de recherche ci-dessous.

* Bordeaux + - Université de Bordeaux
* Crossref
* Google Scholar
* Google Scholar - Title Only
* Google
* SUDOC
* SUDOC - auteur(s)/titre
* SUDOC - auteur(s)/titre/ISBN
* SUDOC - ISBN
* PubMed DOI
* PubMed (title + author)

Voici comment procéder pour installer ce fichier dans Zotero.

_Les raccourcis clavier indiqués sont ceux utilisables sous Windows._

1. Dans les _Préférences_ de Zotero, cliquez sur _Avancées_ > _Fichiers et dossiers_ > _Ouvrir le répertoire de données_
2. Dans la fenêtre de votre explorateur de fichiers qui s'affiche, ouvrez le dossier `locate`.
3. Fermez complètement Zotero, c'est-à-dire y compris la fenêtre des préférences.
4. Ouvrez avec le Bloc-notes le fichier `engines.json` qui se trouve à l'intérieur du dossier `locate`.
5. Allez à l'adresse suivante pour afficher et récupérer facilement le contenu du fichier de moteurs préconfiguré `engines_BX-svs.json` : <https://raw.githubusercontent.com/fflamerie/zotero_intro_FR/master/content/engines_BX-svs.json>
6. Sur cette page, activez les raccourcis clavier `Ctrl+A` puis `Ctrl+C` pour sélectionner et copier tout le contenu du fichier : il ne doit manquer aucun signe, aucune virgule ni crochet, sinon le fichier ne fonctionnera pas.
7. Revenez dans le Bloc-notes et remplacez le contenu du fichier `engines.json` par le contenu du fichier `engines_BX-svs.json` , que vous venez de copier : activez les raccourcis clavier `Ctrl+A` puis `Ctrl+V` pour ce faire.
8. Enregistrez et fermez le fichier `engines.json`.
9. Redémarrez Zotero : lorsque vous sélectionnez un document de votre bibliothèque, vous devez voir s'afficher vos nouveaux moteurs de recherche sous le menu _Localiser_.
