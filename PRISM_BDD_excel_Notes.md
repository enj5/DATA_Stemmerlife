
**TACHE 1**

- **Suite du remplissage du dictionnaire de données des tables du projet**  
> **Modifications à signaler :**  
> TAB_organisation : is_active - Default false to true   **DONE**  
    envoi_erp, envois_cms, envoi_wms à false??? WHY?     **DONE**  
> ajout de TAB_option_libelle / libelle_default default false??  
> TAB_option_groupe_libelle : varchar(255) dans TAB  
> ajout de TAB_option  
> TAB_mesure_unite : is_active default true dans pgAdmin  **DONE**  
    attention des false dans TAB des true dans pagAdmin  
> ajout de TAB_entite_attribut_libelle  
> ajout de TAB_entite_attribut  
> TAB_attribut_groupe : envoi_erp, envois_cms, envoi_wms à false dans TAB et NOT NULL FALSE ??


**TACHE 2**
**Remplissage des vues et des tables dans un fichier excel**
> Faut-il mettre toutes les vues et les tables dans le même fichier excel BDD_PRISM ? **OUI**  
> Est-ce que je dois ajouter, comme dans la vue "explicite_attribut", les colonnes modification_user_id, creation_user_id ??? **NON**  
> Dois-je également ajouter la colonne des couples des clés comme dans la table excel de la vue "explicite_attribut" ?? **NON**  
Question : Dans la vue "explicite_entite_valeur" Je vois une jointure avec "full_entite_valeur" qui est une vue. C'est bizarre?? Bon je pense que c'est comme une fonction qui appelle une autre fonction  

RESTE A FAIRE : Rajouter les BDD des 4 tables parmi les jointure de la vue "explicite_produit_valeur" !!!!!! **DONE**  

**TACHE 3**
> Je me suis arrêté à "explicite_entite_attribut"
(suite)  
> ~~Problème avec la jointure "full_entite_valeur". Est ce que je l'ajoute parmi les vues? **JE ME SUIS SERVI D'ELLE!!~~  
> **Dans la table "option_libelle", o dirait qu'il manque les id de 1 à 25**     **Donc la vue "explicite option NON TERMINEE**  
> ~~**Même pb pour "explicite_produit_valeur". J'ai mis des "NOT_FOUND" pour les données manquantes~~  
> Pour l'instant dans le tableau excel de la vue "explicite_organisation_division", je me suis arrêté à la colonne "categorie_code" et "cl_libelle"  
> **TOUT RECONTROLER, IL Y A BEAUCOUP DE SOUCIS AVEC LES "N/A"  !!!!!**  

(suite 02/04)  
> "explicite_valeur", je me suis arrêté sur les dernières colones à partir de "ea_envoi_erp". Car dans la la vue "explicitite_attribut" il y semble avoir des colones de trop et un renommage  
> ATTENTION - PB avec les vues "explicite_produit_valeur" et "explicite_attribut"
(Ou j'en suis...)
> **"explicite_produit_valeur" table excel  
> Je suis entrain de mettre les formules des envoi_cms, erp, vms... Puis de is_active  
> Egalement, je dois mettre à jour les colonnes en bleues et jaune car la vue correspondante a changée dans postgre!!!**  
> **ATTENTION!!! JE GERE MAL LES "SI", c'est pour ça que ça ne marche pas! C'est parce que je ne sélectionne pas à chaque fois la bonne ligne dans les différents tableaux!!**  
> _Puis je dois faire une revérification générale!!!!_

(suite 03/04)
> Changement dans la vue "explicite_produit_valeur", 3M de ligne. Excel accèpte 1M de ligne par feuille. Je vais à la place prendre 6713 lignes comme pour la vue "explicite_attribut"
> **ATTENTION!! POSER LA QUESTION A BENOIT AVANT DE CONTINUER**
> ~~Avec les 6714 lignes, je suis à "format_id" pour l'instant~~
> **J'ai complété toutes les colonnes sur les 6713 lignes. Mais sur postgre on a 3M de lignes**  NON TERMINE
