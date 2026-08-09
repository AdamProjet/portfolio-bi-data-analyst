# Préparation RGPD d’un jeu de données CRM - "Dev’Immediat"

* **Contexte / Besoin métier :** Un courtier en assurance automobile a besoin de préparer un jeu de données CRM pour l’analyse commerciale tout en garantissant la confidentialité des informations personnelles et la conformité RGPD.
* **Données :** Base de données SQLite de 2022 (identité, revenus, situation familiale, tarifs).
* **Démarche :** Extraction SQL et Power Query (langage M). Suppression des identifiants directs et agrégation (généralisation) des dates et revenus. Documentation stricte du processus de désidentification.
* **Résultats + Impact :** Production d'un fichier CSV désidentifié et reproductible, rendant la donnée exploitable par les commerciaux sans risque légal. Remise d'un rapport avec 5 recommandations de gouvernance.
* **Limites + Prochaines pistes :** L'anonymisation parfaite (risque zéro) est illusoire. **Piste d'amélioration :** Implémenter des techniques de K-anonymat ou de Differential Privacy.
