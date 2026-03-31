
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
> Problème avec la jointure "full_entite_valeur". Est ce que je l'ajoute parmi les vues? **JE ME SUIS SERVI D'ELLE!!  
> **Dans la table "option_libelle", o dirait qu'il manque les id de 1 à 25**     **Donc la vue "explicite option NON TERMINEE**
> **Même pb pour "explicite_produit_valeur". J'ai mis des "NOT_FOUND" pour les données manquantes
> Pour l'instant dans le tableau excel de la vue "explicite_organisation_division", je me suis arrêté  la colonne "categorie_code" et "cl_libelle"
> **TOUT RECONTROLER, IL Y A BEAUCOUP DE SOUCIS AVEC LES "N/A"  !!!!!**
