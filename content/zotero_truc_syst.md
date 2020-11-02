# Trucs et astuces pour optimiser l'utilisation de Zotero dans le contexte d'une revue de littérature ou d'une revue systématique

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

![zotero_organisation_overview](zotero_intro_FR/content/img/zotero_organisation_overview_en.png)

Pourquoi privilégier les marqueurs plutôt que les collections?

2 raisons principales :

* **Lisibilité** : grâce à l'onglet "Marqueurs" du volet de droite vous visualisez immédiatement tous les marqueurs associés à un document ; grâce aux **marqueurs colorés** vous visualisez rapidement tous les documents associés à un marqueur.
* **Portabilité** : les marqueurs font partie des informations bibliographiques du document et sont ainsi, par exemple, exportés au même titre que toutes les autres informations bibliographiques lorsque vous exportez des documents dans un fichier au format .ris, . csv, etc. Les collections et les recherches enregistrées relèvent en revanche de **l'interface** de votre bibliothèque, l'information du classement dans une collection n'est pas enregistrée en tant qu'information bibliographique du document.

Plus d'infos : [Cours "Introduction à Zotero, votre assistant de recherche personnel" > section "Constituer sa bibliothèque Zotero étape 2, organiser le contenu"](https://github.com/fflamerie/zotero_intro_FR/blob/master/content/zotero_intro_FR_COURS.md#4-constituer-sa-biblioth%C3%A8que-zotero-%C3%A9tape-2-organiser-le-contenu)


## Automatiser et optimiser la recherche du texte intégral

Zotero dispose de fonctionnalités par défaut pour rechercher et enregistrer automatiquement le texte intégral, telles que les suivantes.

* **L'enregistrement automatique du PDF présent sur une page web** lorsque vous utilisez le connecteur Zotero (bouton Zotero dans votre navigateur).
* La détection et l'enregistrement automatiques du **proxy de l'université** pour vous rediriger vers les accès souscrits par l'université lorsque vous naviguez sur les sites des éditeurs - voir [Documentation Zotero : Les préférences du connecteur Zotero > Préférences pour les serveurs mandataires](https://www.zotero.org/support/fr/connector_preferences?do=#preferences_pour_les_serveurs_mandataires).
* La recherche automatique de **PDF disponibles en libre accès** grâce à Unpaywall - [description de la fonctionnalité sur le blog Zotero francophone](https://zotero.hypotheses.org/2130).

Deux fonctionnalités complémentaires vous permettent d'augmenter ces fonctions de recherche. Elles sont toutes les 2 accessibles depuis **le menu _Localiser_**, c'est-à-dire la flèche verte en haut du volet de droite dans votre bibliothèque Zotero. Il s'agit de :

* la **configuration OpenURL** pour l'Université de Bordeaux,
* et la personnalisation des **moteurs de recherche intégrés à Zotero**.


Pour la configuration OpenURL, il suffit :
* d'aller à l'onglet _Avancées_ > _Générales_ des _Préférences_,
* dans le champ _OpenURL_ > _Résolveur des liens_, coller l'URL suivante :

```
https://babordplus.hosted.exlibrisgroup.com/primo-explore/openurl?&Force_direct=false&vid=33PUDB_UB_VU1&institution=33PUDB_UB&
```

* En cliquant sur le menu _Localiser_ > _Rechercher dans la bibliothèque_, vous afficherez le document dans Babord+ avec toutes les options d'accès de l'université de Bordeaux.

La personnalisation des moteurs de recherche, incluant un fichier de moteurs préconfiguré, est décrite en détails dans le billet du blog Zotero francophone [Les moteurs de recherche intégrés à Zotero](https://zotero.hypotheses.org/3388).
