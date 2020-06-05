# Activité "A1" : Définir le périmètre de l’application

## But
Il s'agit de définir le périmètre que va "embrasser" l'application et par conséquent la "surface" qu'elle va couvrir,  ...   
... autrement dit sont "Quoi ?" métier, ce qu'elle va faire (indépendement de la manière de le faire).

### Pourquoi le faire ?
Si l'on ne défini pas clairement ce qu'il doit être fait, alors lorsqu'on va essayer de dévelloper l'application on va être confronté à la problématique de "trouver une solution" (le Comment ?) à "une situation" (le Quoi ?) qui n'a jamais - vraiement - été définie !

### Comment le faire ?
2 manières différentes mais complémentaires permettent de contribuer à la définition du __périmètre__ d'une application.
* La 1ere, basée sur la description de __cas d'usage__ concret est très pragmatique et permet dès le départ de commencer à se consituer une base de test (= pour la "recette").
* La 2nd, basée sur la définition d'__activités métier__ (connectée entre-elles pour constituer un __processus métier__ global) est plus théorique (car au lieu de baser sur des éléments contrets, elle met en oeuvre des types d'éléments plus abstrait). 

## Mantra
Le meileur conseil pour cette activité est sans doute le suivant : 
> Définir - autant que possible - les activités en terme de __finalité__ (et NON en terme de __moyen__)

![BizSpecFctSpec](https://github.com/iPlumb3r/BizApp-Spec-Methodo/blob/master/_Images/BusinessSpecifciation_VS_FunctionalSpecification.png)

La difficulté éprouvée par les clients à "remonter vers le métier" lors de la phase d'expression du besoin est bien illustré par la célèbre phrase d'Henry Ford : 
> Si j'avais demandé à mes clients de quoi il avait besoin, il m'aurait dit "d'un cheval qui avance plus vite" ;-)

## Livrable(s)
### Cas d'usage :
Il s'agit d'une description textuelle et/ou graphique représentant une situation emblématique de la problématique devant être supportée par l'application informatique. Chaque situation particulière devant faire l'objet d'une description à part de manière à "paver" l'ensemble du territoire "à couvrir".

### Fiche d'activité métier / processus métier
Il s'agit d'un ensemble de fiche d'__Activité Métier__ qui prisent globalement permettent de constituer une cartographie de "Qui réalise quelle activité dans quel but" (Autrement nommé __Processus Métier__)
 
## Notions Clefs
La notion centrale pour cette activité est la notion d'__Activité Métier__ (Cf <a href="https://github.com/iPlumb3r/pEAr4pEEr/blob/master/1_Semantic/Conceptionary/%23BusinessActivity.md">#BusinessActivity</a>) qui  : 
* est réalisé par 1 (ou plusieurs) __Rôle(s) Métier(s)__ (Cf <a href="https://github.com/iPlumb3r/pEAr4pEEr/blob/master/1_Semantic/Conceptionary/%23BusinessRole.md">#BusinessRole</a>)
* consommes 1 (ou plusieurs) __Objet(s) Métier(s)__ (Cf <a href="https://github.com/iPlumb3r/pEAr4pEEr/blob/master/1_Semantic/Conceptionary/%23BusinessObject.md">#BusinessObject</a>)
* et produit  1 (ou plusieurs) __Objet(s) Métier(s)__

Les autres notions connexes : <a href="https://github.com/iPlumb3r/pEAr4pEEr/blob/master/1_Semantic/Conceptionary/%23BusinessProcess.md">#BusinessProcess</a>, <a href="https://github.com/iPlumb3r/pEAr4pEEr/blob/master/1_Semantic/Conceptionary/%23BusinessConcept.md">#BusinessConcept</a>, <a href="https://github.com/iPlumb3r/pEAr4pEEr/blob/master/1_Semantic/Conceptionary/%23BusinessSubject.md">#BusinessSubject</a> sont défini dans le Conceptionary de l'initiative pEAr4pEEr : https://github.com/iPlumb3r/pEAr4pEEr/tree/master/1_Semantic/Conceptionary

## Modèle Sémantique
Les __Activités Métiers__ s'inscrivent dans le contexte du modèle sémantique suivant :    
![SemanticModel](https://github.com/iPlumb3r/pEAr4pEEr/blob/master/images/BusinessProcess_2020-05-05.png)



