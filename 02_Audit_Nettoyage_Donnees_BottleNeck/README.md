# Audit, Nettoyage et Analyse Qualité - "BottleNeck" (Phase Data)

* **Contexte / Besoin métier :** Avant l'analyse stratégique, l'entreprise avait besoin de rapprocher les données de son ERP avec celles de sa boutique web pour calculer son CA en ligne et s'assurer de la viabilité des données.
* **Données :** Fichiers disparates (ERP, Web, table de liaison). Présence d'anomalies (valeurs aberrantes, orphelins).
* **Démarche :** Utilisation de Python (Pandas). Traitement des outliers via des méthodes statistiques. Amélioration des règles de gestion métiers (ex: correction des statuts de stock via fonctions Lambda).
* **Résultats + Impact :** Rapprochement réussi à 100%. Preuve apportée à la direction que les 36 outliers identifiés (4,36% du catalogue) étaient une réalité commerciale (vins de grand prestige) et non des erreurs, sauvant la fiabilité du calcul du CA.
* **Limites + Prochaines pistes :** Fichiers Excel statiques générant un risque d'erreur humaine. **Piste d'amélioration :** Remplacer l'export manuel par une connexion API directe.
