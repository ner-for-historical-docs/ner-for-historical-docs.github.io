# NER for OCR'ed historical documents in Paris

Nous sommes un groupe de chercheurs travaillant sur la [reconnaissance d'entités nommées](https://en.wikipedia.org/wiki/Named-entity_recognition) dans des documents historiques.

Nous organisons régulièrement un **séminaire** (diffusé en ligne) suivi d'une session d'échange pour les participants présents sur place (généralement à la Maison de la Recherche, 28 rue Serpente, Paris).

Nous proposons également une **liste de diffusion** pour partager des articles, des codes, des conférences, des données et toute autre information utile sur la reconnaissance d'entités nommées pour les documents historiques transcrits par reconnaissance optique de caractères (OCR) ou de contenus manuscrits (HTR).

Voici une liste non exhaustive des thèmes qui nous intéressent :

- reconnaissance d'entités nommées (REN) en présence de bruit dans les textes
- métriques et méthodes de qualité pour la REN sur des textes bruités
- bonnes pratiques pour l'annotation des entités nommées, l'entraînement et l'évaluation des modèles de REN/Nammed entity linking (NEL)


------ 


## Liste de diffusion

Vous pouvez consulter la page suivante pour vous **inscrire** et vous **désinscrire librement** : <https://groupes.renater.fr/sympa/info/ner-for-historical-docs>

Merci de respecter le thème de la liste lors de l'envoi de messages. Cette liste est modérée.


------ 

## Prochains séminaires

**Lieu et horaire :**  
Les séminaires ont lieu en hybride en visio (lien confirmé quelques jours avant chaque séminaire) et à la Maison de la recherche de Sorbonne Université, au 28 rue Serpente, 75006 Paris (salle S002 — couloir immédiatement à gauche dans la maison de la Recherche) de 13h à 15h. 

**Format des sessions :**

1. Présentation invitée sans interruption pour faciliter le mode hybride pendant 40-50 minutes. 
2. Questions et réponses pendant 10-20 minutes. 
3. Présentations flash de résultats récents en forme d'incitations à collaborer. N'hésitez pas à préparer 1 slide pour servir de support visuel ! Toutes les contributions sont les bienvenues. 
4. Discussions libres jusqu’à la fin du créneau. 



### 19 octobre : Thierry Poibeau — directeur de recherche au CNRS - directeur adjoint du laboratoire [LATTICE](https://www.lattice.cnrs.fr/membres/direction/thierry-poibeau/) (Langues, Textes, Traitements informatiques et Cognition) - titulaire d’une chaire PRAIRIE (Paris Artificial Intelligence Research Institute) en traitement des langues naturelles et humanités numériques - affiliated lecturer au Département de linguistique théorique et appliquée (DTAL) de l’Université de Cambridge
*"Analyser les entités dans les romans pour détecter des tendances historiques (grâce au projet BookNLP)"*

Au cours de cet exposé, je présenterai le projet BookNLP, qui vise à produire des outils pour l’analyse de romans (c’est-à-dire de documents longs, où les mêmes personnages peuvent apparaître sur des centaines de pages). Je montrerai l’importance de l’analyse de la coréférence dans ce contexte. J’illustrerai ce travail par des exemples montrant en quoi ce type d’analyse est important pour une meilleure connaissance de la littérature, de son évolution, mais aussi du contexte culturel et social plus généralement (ce que les anglo-saxons appellent "cultural analytics"). 


### 26 octobre : Marie Puren, Enseignante-Chercheuse à l’EPITA, coordinatrice scientifique du projet AGODA

*Titre et résumé à confirmer*


### 16 novembre : [Thierry PAQUET](https://pagesperso.litislab.fr/tpaquet/), LITIS (Professeur, Université de Rouen, Directeur du LITIS) — [Denis COQUENET](https://factodeeplearning.github.io/), IRISA (MCF, Université de Rennes) — Thomas CONSTUM , LITIS (Doctorant, Université de Rouen)

Cette présentation est dédiée aux approches pour la reconnaissance d’écriture et la reconnaissance d’entités nommées. Nous suivrons l’évolution des techniques utilisées ces dernières années en la matière, et nous nous intéresserons plus particulièrement aux approches récentes basées sur de l’apprentissage profond permettant une reconnaissance de bout-en-bout de documents entiers. Nous verrons comment ces avancées permettent d’envisager le traitement des documents incluant une réelle compréhension de ceux-ci. Des cas d’usage concrets seront étudiés au travers des projets POPP et Exo-POPP portant respectivement sur des tableaux de recensements et des actes de mariages. 


### 14 décembre : Florence Clavaud , Responsable du Lab aux Archives nationales de France, et membre de l'équipe de recherche EA 3624 (Centre Jean-Mabillon) de l'Ecole nationale des chartes
*"NER4Archives : reconnaître, réconcilier et identifier les entités nommées dans les instruments de recherche archivistiques au format EAD"*

Depuis fin 2020, les Archives nationales et l'équipe ALMAnaCH de l'Inria ont joint leurs forces, avec le soutien du ministère de la Culture, pour travailler à la reconnaissance des entités nommées dans les instruments de recherche au format XML/EAD. L'enjeu est important : les Archives nationales gèrent un corpus de plus de 31000 fichiers XML/EAD, qui constituent le coeur de leur système d'information en ligne et qui décrivent les millions de documents et groupes de documents conservés par l'institution ; mais pour diverses raisons ces fichiers sont très peu indexés, ce qui prive les usagers des Archives nationales de points d'entrée appropriés lorsqu'ils font des recherches dans les métadonnées afin d'identifier les documents et données qui les intéressent. II n'est pas possible de procéder à une indexation manuelle de ce corpus. Le problème est globalement le même dans les autres services d'archives français. Les Archives nationales disposent par ailleurs de référentiels servant à l'indexation de ces métadonnées, qu'elles ont sémantisés et souhaitent enrichir par tous les moyens utilisables. Le projet NER4Archives (Named Entity Recognition For Archives), qui entrera dans sa deuxième phase à l'automne 2023, vise donc à doter les Archives nationales (et potentiellement tout autre service intéressé) de corpus d'apprentissage et de modèles d'IA efficaces pour parvenir à annoter les entités nommées mentionnées dans les fichiers EAD, à les classifier, à les réconcilier et à les lier à des référentiels existants (Wikidata) afin d'en extraire des données, pour produire en sortie des fichiers EAD indexés, les éléments d'indexation ainsi posés étant associés à des notices des référentiels des Archives nationales, qu'elles préexistent ou qu'elles aient été créées dans le cadre du projet. La présentation, qui sera faite par plusieurs personnes représentant les deux entités qui portent le projet, évoquera dans un premier temps le contexte, les spécificités et les enjeux du projet, en fera l'historique et en présentera les résultats déjà obtenus, pour évoquer ensuite les scénarios et pistes d'intégration des outils développés dans les outils de travail des archivistes.

Références : 
- <https://github.com/NER4Archives-project> - <https://huggingface.co/ner4archives>
- Florence Clavaud, Laurent Romary, Pauline Charbonnier, Lucas Terriel, Gaetano Piraino, et al. *NER4Archives (named entity recognition for archives) : Conception et réalisation d’un outil de détection, de classification et de résolution des entités nommées dans les instruments de recherche archivistiques encodés en XML/EAD*. Atelier Culture-INRIA, Ministère de la Culture; Inria; Archives nationales, Mar 2022, Pierrefitte sur Seine, France. ⟨[hal-03625734](https://hal.science/hal-03625734)⟩



------ 


## Séminaires passés


### 17 mars 2023 : Carmen Brando Lebas (Dr et ingénieure de recherche en Humanités numériques à l'EHESS) et Frédérique Mélanie-Becquet (Ingénieure d’études CNRS en production, traitement et analyse de données au Lattice).

*Annuaires de propriétaires et des propriétés de Paris (1898, 1903, 1913, 1923) : du papier à la carte*

La présentation reprendra les grandes étapes du traitement entrepris, entre 2019 et 2022, sur l’Annuaire des propriétaires et des propriétés de Paris et du département de la Seine : transcription, structuration et analyse. Le travail que nous présenterons a été effectué dans le contexte du groupe Annuaires et adresses du consortium Paris Time Machine d’Huma-num.
Notre exposé abordera dans un premier temps la transcription des données : quels outils avons-nous utilisés pour passer du format PDF au format texte ? Quels problèmes avons-nous rencontrés et comment les avons-nous solutionnés ? Dans un second temps, nous nous attarderons sur la structuration et l'analyse des données. Nous montrerons les mécanismes mis en place pour passer du texte à l'analyse. Tout d'abord, nous expliquerons comment nous avons structuré nos données : de la création du modèle d'annotation au tableur final. Ensuite, nous exposerons nos premiers résultats, les premières analyses effectuées : de l'observation quantitative des données aux premières projections sur carte.

### 16 septembre 2022 : Présentation de Antoine Doucet (Professeur, Université de La Rochelle, L3I) et Emanuela Boros (Docteure, Ing. Recherche à l'Univ. La Rochelle, L3I) sur l'impact de la reconnaissance optique des caractères sur la reconnaissance des entités nommées.


### 7 juillet 2022 : Session d'introduction


