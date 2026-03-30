
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
