# Norme bibliographique HAISSa (note, français/french)
La norme bibliographique HAISSa est une norme bibliographique en français, prenant en charge les bibliographies et les références en notes de bas de page, installable sur [Zotero](https://www.zotero.org/).
Cette norme a été développée dans le but de pouvoir référencer et citer les catalogues d'exposition, mais prend aussi en charge les autres types de documents imprimés.

## Installation
- Télécharger le fichier ['norme-haissa.csl'](/norme-haissa.csl). 
- Dans votre application Zotero installée en local, aller dans le menu 'Édition > Préférences > Citer'. 
- Ajouter cette norme à l'aide du bouton '+'.

## Usage
Cette norme prend en compte les types de documents suivants :
- livre ;
- chapitre de livre ;
- article de revue ;
- article de journal ;
- article de colloque ;
- thèse et mémoire ;
- catalogue d'exposition

Pour une équivalence entre les champs Zotero et les champs CSL, voir le fichier ['Mapping'](/Mapping.md).

### Livre, chapitre, article et thèse

Pour ces types de documents, les références se composent selon les normes bibliographiques françaises. 

Les références s'affichent pareillement selon qu'elles apparaissent dans la bibliographie ou en note de bas de pages, sauf pour les références déjà citées qui se limitent aux indications de ou des auteurs, du titre principal et des informations de localisation.

En voici des exemples :

![Exemples pour les documents "de base"](/Exemples/NormeHAISSa_Exemples-Autres.jpg)

En bibliographie, les références apparaissent dans l'ordre alphabétique du nom des auteurs puis dans l'ordre chronologique de leur date de publication.

### Catalogues d'exposition
Pour les catalogues d'exposition, les références se composent ainsi :

>*Titre de l'exposition*, NOM et Prénom du ou des commissaires (éd.), cat. exp. (ville de l'exposition, institution, dates), ville d'édition, maison d'édition, date de publication.

Les informations relatives aux expositions doivent être renseignées dans le champ 'Édition' dans la bibliothèque Zotero. **Il est impératif que ce soit l'unique type de document où ce champ est rempli, puisque cela détermine la manière dont la référence est construite et comment elle apparaît dans la bibliographie et les notes de bas de page !**

En voici un exemple :

![Exemples pour les catalogues d'exposition](/Exemples/NormeHAISSa_Exemples-CatExp.jpg)

En note de bas de page, la référence se limitera au titre et à la date de l'exposition.

En bibliographie, ces références apparaîtront dans l'ordre chronologique de leur date.

## Aide et contribution
Pour signaler des problèmes, demander des développements ou suggérer des améliorations, je vous serai reconnaissante de me contacter *via* mail : [claire.dupindb@gmail.com](mailto:claire.dupindb@gmail.com).

## Auteurs et remerciements
Cette norme a été developpée par [Claire Dupin de Beyssat](https://github.com/ClaireDDB) à l'aide du [Visual CSL Editor](https://editor.citationstyles.org/visualEditor/). Merci à [Federico Nurra](https://github.com/FedericoNurra) et Johanna Daniel pour leur aide et leur initiation.

## Licence

[CC BY-NC](https://creativecommons.org/licenses/by-nc/4.0/)
