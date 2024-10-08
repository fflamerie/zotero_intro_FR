# Trucs et astuces pour optimiser l'utilisation de Zotero dans le contexte d'une revue de littérature ou d'une revue systématique

<!-- MDTOC maxdepth:2 firsth1:0 numbering:0 flatten:0 bullets:1 updateOnSave:1 -->

- [Créer une bibliothèque de groupe pour votre revue](#créer-une-bibliothèque-de-groupe-pour-votre-revue)   
- [Enregistrer les références par import de fichier plutôt que par le connecteur Zotero (bouton "Save to Zotero" dans votre navigateur)](#enregistrer-les-références-par-import-de-fichier-plutôt-que-par-le-connecteur-zotero-bouton-save-to-zotero-dans-votre-navigateur)   
   - [PubMed](#pubmed)   
   - [Scopus](#scopus)   
   - [Web of Science Core Collection](#web-of-science-core-collection)   
   - [PsycINFO, CINAHL et autres bases disponibles via EBSCO](#psycinfo-cinahl-et-autres-bases-disponibles-via-ebsco)   
   - [LiSSa](#lissa)   
- [Snowballing, ou enregistrer toutes les références citées par un article](#snowballing-ou-enregistrer-toutes-les-références-citées-par-un-article)   
   - [Avec Web of Science ou Scopus](#avec-web-of-science-ou-scopus)   
   - [Avec Citation Chaser](#avec-citation-chaser)   
- [Organiser sa bibliothèque avec des marqueurs](#organiser-sa-bibliothèque-avec-des-marqueurs)   
   - [Créer un marqueur dans un document et lui attribuer une couleur](#créer-un-marqueur-dans-un-document-et-lui-attribuer-une-couleur)   
- [Fusionner les doublons par lot avec Zotero Duplicates Merger](#fusionner-les-doublons-par-lot-avec-zotero-duplicates-merger)   
- [Automatiser et optimiser la recherche du texte intégral](#automatiser-et-optimiser-la-recherche-du-texte-intégral)   
   - [Configuration OpenURL](#configuration-openurl)   
   - [Moteurs de recherche intégrés à Zotero](#moteurs-de-recherche-intégrés-à-zotero)   

<!-- /MDTOC -->

## Créer une bibliothèque de groupe pour votre revue

Même si vous travaillez seul, il est préférable de créer une bibliothèque de groupe pour votre revue de littérature, cela facilitera notamment **la gestion des doublons**. La recherche de doublons s'exécute toujours sur tout le contenu d'une bibliothèque, il n'est pas possible de la lancer seulement sur une partie de votre bibliothèque (une collection par exemple).

## Enregistrer les références par import de fichier plutôt que par le connecteur Zotero (bouton "Save to Zotero" dans votre navigateur)

Cliquer sur le bouton "Save to Zotero" est la meilleure méthode pour enregistrer des documents dans votre bibliothèque au fil de votre navigation dans les bases de données, lorsqu'il s'agit d'enregistrer un document après l'autre.

Dans le cadre d'une revue de littérature où vous devez enregistrer d'un seul coup depuis une base de données tous les résultats d'une équation de recherche, l'import de fichier est plus adapté, car beaucoup plus rapide.

Voici comment procéder dans différents outils de recherche bibliographique, à partir d'une liste de résultats.

### PubMed

1. Cliquez sur _Send to_ > _Citation manager_.
2. Dans le menu _Selection_ choisissez _All results_.
3. Enregistrez le fichier **.nbib** ainsi généré sur votre ordinateur.
4. Allez ensuite dans Zotero, dans le menu _Fichier_ >_Importer..._ et sélectionnez ce fichier **.nbib**.
5. Suivez les étapes, les références sont automatiquement importées dans votre bibliothèque.

### Scopus

1. Dans le menu _All_  cochez le bouton _Select All_,
2. Puis dans le menu _Export_  sélectionnez le format _BibTex_ et choisissez les informations à exporter.

💡 N'oubliez pas le **résumé**, il n'est pas inclus par défaut.

💡 Il est recommandé d'utiliser préférentiellement le format BibTeX au format RIS, car il conserve les **prénoms des auteurs**  sous leur forme complète. Dans le format RIS, les prénoms sont abrégés à leur initiale.

3. Cliquez sur _Export_.
4. Une boîte de dialogue s'affiche, choisissez _Ouvir avec_ > _Zotero_.
5. Les références sont automatiquement importées dans votre bibliothèque.

Lorsque vous incluez le résumé, une limitation à **20'000 références** s'applique pour l'export. Si vous souhaitez exporter plus de 20'000 références, utilisez les filtres par date pour créer des lots par année de publication. Vous serez ainsi sûr d'inclure tous les résultats dans vos exports.

### Web of Science Core Collection

A partir d'une liste de résultats, cliquez directement sur _Export_ pour afficher toutes les options vous permettant de choisir :

* le format d'export,
* puis les références à exporter,
* et les champs à exporter.

Le **format RIS** permet une détection et un import automatiques du fichier dans Zotero.

⚠️ Il présente toutefois les limitations suivantes :

* les titres de revue sont entièrement en majuscules, ce qui contraint à de fastidieuses corrections du champ "Publication" pour conserver seulement les majuscules initiales,
* il ne permet pas d'exporter des champs complémentaires, sélectionnés avec l'option _Custom selection_.

💡 **Il convient par conséquent de privilégier le format _Plain Text File_** et d'importer le fichier ainsi généré de la même façon que pour PubMed.

Une limitation à **1'000 références** s'applique pour l'export. Comme pour Scopus, il faut procéder par petits lots successifs si vous souhaitez exporter plus de 1'000 références.

### PsycINFO, CINAHL et autres bases disponibles via EBSCO

Sur la plateforme EBSCOhost , le fichier d'export est mis à disposition à un lien dédié, dont l'URL vous est envoyée par messagerie électronique. Cette procédure présente l'inconvénient d'être moins directe et immédiate que les exports directs disponible sur les outils précédemment cités, toutefois elle autorise des exports plus massifs, jusqu'à **25'000** références. Le lien pour télécharger le fichier peut être envoyé à plusieurs adresses de messagerie.

1. Depuis la liste de résultats que vous souhaitez exporter, cliquez sur _Partager_ > _Résultats de l'exportation : Envoyer un e-mail avec un lien permettant de télécharger les résultats exportés (jusqu'à XXX)_ (XXX remplace le nombre de résultats de votre requête).

![img_EBSCO_1](img/EBSCO_export_lot_01.PNG)

2. Sur la page suivante, saisissez les adresses de messagerie auxquelles le lien doit être envoyé, choisissez le format _Format RIS (par ex. CITAVI, EasyBib, EndNote, ProCite, Reference Manager, Zotero)_ si ce dernier n'est pas sélectionné par défaut, et enfin cliquez sur _Envoyer_.

![img_EBSCO_2](img/EBSCO_export_lot_02.PNG)

3. Vous recevrez dans un délai de quelques minutes le lien vous permettant de télécharger le fichier .RIS comportant toutes les références.
4. Une fois extrait de l'archive .zip le fichier .RIS, il suffit de l'importer dans Zotero depuis le menu _Fichier_>_Importer..._

### LiSSa

1. Modifiez le nombre le nombre de résultats par page en le passant à la valeur maximale proposée, c'est-à-dire 100 : cela vous permettra de sélectionner d'un seul clic toutes les références affichées sur la page.
2. Une fois les références sélectionnées, cliquez sur _Envoyer_ > _Citations (ris)_.
3. Une boîte de dialogue vous permettra d'importer le fichier dans Zotero.

💡 **Vous pouvez sélectionner consécutivement plusieurs pages de résultats avant de lancer l'export, afin d'enregistrer d'un seul coup plus de 100 références.**

![zotero_lissa](img/zotero_lissa.png)

## Snowballing, ou enregistrer toutes les références citées par un article

Le _snowballing_ fait partie des méthodes de recherche bibliographique utilisables pour une revue de littérature ; elle peut être requise.

Nous vous présentons ici des outils permettant d'enregistrer automatiquement toutes les références citées par un article. Combiné à la fonctionnalité de **Connexe** de Zotero, cela permet de retrouver rapidement dans une bibliothèque Zotero tous les articles cités par un article donné, et de restituer le lien de citation.

Notez que vous pouvez avec ces mêmes outils retrouver et enregistrer non seulement les **références citées**, mais également les **références citantes**, c'est-à-dire les références des articles ultérieurs qui citent l'article considéré.

### Avec Web of Science ou Scopus

**Les références citées non indexées** dans la base de données sont traitées différemment dans Scopus et Web of Science.

* Dans Scopus elles sont exportées mais incomplètes.
* Dans Web of Science Core Collection elles ne sont pas exportées du tout.

💡 **Il est donc préférable d'utiliser préférentiellement Scopus pour cet usage.**

Voici comment procéder à partir de Scopus, la procédure est similaire pour le Web of Science.

1. Sur la page d'un article, allez à la rubrique _References_ et cliquez sur le lien permettant d'afficher la liste des références sous la forme d'une liste de résultats. Dans Scopus il s'agit de _View in search results format_. Vous pouvez ensuite effectuer l'export de toutes les références comme décrit précédemment.

![snowballing_1](img/SCOPUS_ref_citees_01.png)

2. Dans votre bibliothèque Zotero, sélectionnez l'article dont vous venez d'importer la bibliographie, puis cliquez sur _Ajouter_ dans l'onglet _Connexe_ et sélectionnez toutes les références que vous venez d'importer.

![snowballing_2](img/SCOPUS_ref_citees_02.png)

3. Un lien réciproque est créé entre l'article et chacune des références qu'il cite. Ces liens sont affichés dans l'onglet _Connexe_ ; ils vous permettent de naviguer de l'article aux références qu'il cite et inversement.

 ![snowballing_3](img/SCOPUS_ref_citees_03.png)

### Avec Citation Chaser

[Citation Chaser](https://estech.shinyapps.io/citationchaser/), développé et mis à disposition par des chercheurs en écologie, présentent de nombreux avantages.

* Son utilisation est **libre et gratuite**.
* La base de données d'indexation des citations utilisée est la base de données non commerciale **Lens.org**, offrant une couverture plus large que celle de Scopus ou du Web of Science puisqu'elle combine Microsoft Academic, PubMed, CORE et Crossref.
* La recherche et l'export des références citées et citantes est très simple et rapide à effectuer, comme le montre les captures d'écran ci-dessous.

1.  L'onglet  _Article input_ permet de charger les articles à considérer, à partir de la saisie d'un de leurs identifiants (PMID, DOI, etc. ), d'un fichier .csv ou d'un fichier .ris.

![Interface de chargement des articles source dans Citation Chaser](img/CChaser_01_ArticleInput.png)

2.  Les onglets _References_ et _Citations_ permettent ensuite de rechercher et exporter au format .ris respectivement les références citées et les références citantes.

![Interface de recherche et d'export des références citantes dans Citation Chaser](img/CChaser_02_citations.png)

3. Les onglets _Analysis_ et _Network_ fournissent des fonctionnalités complémentaires d'analyse et de visualisation.

Haddaway, N. R., Grainger, M. J., Gray, C. T. 2021. citationchaser: An R package and Shiny app for forward and backward citations chasing in academic searching. doi: [10.5281/zenodo.4543513](https://doi.org/10.5281/zenodo.4543513)

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

### Créer un marqueur dans un document et lui attribuer une couleur

![gif_ajout_tag](img/ZoteroTags.gif)

_Source : [Mini-site Zotero Lausanne > Tutoriel Zotero](https://lausannecitationstyle.github.io/support/3.html)_

## Fusionner les doublons par lot avec Zotero Duplicates Merger

Lorsque vous affichez les doublons potentiels repérés par Zotero en cliquant sur la collection _Doublons_, vous devez ensuite valider individuellement chaque doublon pour fusionner les enregistrements concurrents. Ce fonctionnement est optimal pour **éviter les faux positifs**, c'est-à-dire fusionner automatiquement des documents qui ne sont pas des doublons. Il peut toutefois être pénalisant dans le cadre d'une revue de littérature, lorsque vous effectuez des imports par lot depuis différentes bases de données comme décrit précédemment. Vous enregistrez alors des volumes importants de références, avec potentiellement un nombre important de doublons, du fait des recouvrements entre les bases de données interrogées. Le risque de faux positif est par ailleurs quasiment nul.

Vous pouvez alors recourir avec profit à la fonctionnalité de dédoublonnage par lot du module complémentaire [Zotero Duplicates Merger](https://github.com/frangoud/ZoteroDuplicatesMerger). Zotero Duplicates Merger ajoute en effet une option de fusion des doublons par lot ou _Bulk merge_ .

Voici comment l'activer.

1. Dans la collection _Doublons_ de votre bibliothèque Zotero, sélectionnez tous les documents affichés dans le panneau central de Zotero.
2. Affichez le menu contextuel par un clic-droit sur cette sélection.
3. Choisissez l'option _Duplicates Merger_ > _Bulk merge duplicates_.

![copie_ecran_zotero_duplicate_merger](img/zotero_duplicate_merger.png)

⚠️L'option _Smart merge items_ a un comportement bien différent. Avec cette option, vous fusionnez **TOUS** les documents sélectionnés au profit d'un seul. Il faut donc veiller à sélectionner la bonne option dans le menu contextuel.

Notez que Zotero Duplicates Merger offre d'autres fonctionnalités tels qu'un bouton de raccourci pour fusionner les documents ou la définition du critère de choix de la version du document à conserver comme document maître lors de la fusion (la plus ancienne, la plus récente ou celle avec le nom de premier auteur le plus long).

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
* dans la rubrique _OpenURL_, ouvrir le menu déroulant et naviguer dans la liste géographique jusqu'à l'entrée "Université de bordeaux".

![zotero_openurl](img/zotero_openurl.png)

* En cliquant sur le menu _Localiser_ > _Rechercher dans la bibliothèque_, vous afficherez le document dans Babord+ avec toutes les options d'accès de l'université de Bordeaux.

### Moteurs de recherche intégrés à Zotero

Ces moteurs de recherche vous permettent de lancer une recherche dans diverses sources pour trouver un fichier de texte intégral disponible sur un site web personnel  (moteurs Google, Google Scholar), ou pour compléter les informations bibliographiques de vos documents (moteur Sudoc pour les livres et les thèses, moteur PubMed pour les articles).

Pour en savoir plus concernant la personnalisation des moteurs de recherche et découvrir d'autres moteurs que ceux installés dans le fichier de moteurs préconfiguré ci-dessous, consultez le billet du blog Zotero francophone [Les moteurs de recherche intégrés à Zotero](https://zotero.hypotheses.org/3388).

#### Fichier de moteurs de recherche préconfiguré

Vous trouverez dans le fichier [engines_BX-svs.json](https://raw.githubusercontent.com/fflamerie/zotero_intro_FR/master/content/engines_BX-svs.json) les moteurs de recherche ci-dessous.

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

1. 📥 Téléchargez le fichier en faisant un clic droit sur ce lien : [engines_BX-svs.json](https://raw.githubusercontent.com/fflamerie/zotero_intro_FR/master/content/engines_BX-svs.json) et en choisissant "Enregistrer le lien sous…" ou "Enregistrer la cible du lien sous...".

2. Renommez-le ensuite en `engines.json`.

3. 🖱️ Copiez-le dans le répertoire `locate` de votre répertoire de données Zotero, en remplacement du fichier existant.

ℹ️ Pour accéder à votre répertoire de données Zotero depuis les _Préférences_ de Zotero, cliquez sur :

_Avancées_ > _Fichiers et dossiers_ > _Ouvrir le répertoire de données_

4. Redémarrez Zotero : lorsque vous sélectionnez un document de votre bibliothèque, vous devez voir s'afficher vos nouveaux moteurs de recherche sous le menu _Localiser_.
