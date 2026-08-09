# Modélisation SQL & Analyse d’Assurance Habitation

* **Contexte / Besoin métier :** Comprendre le portefeuille de contrats d'une entreprise d'assurance (surfaces assurées, cotisations moyennes) pour identifier les spécificités territoriales du marché.
* **Données :** Fichiers CSV (30 335 contrats et un référentiel géographique de 38 916 communes).
* **Démarche :** Création d'un dictionnaire de données et d'un schéma relationnel. Chargement en base SQLite. Rédaction de 12 requêtes SQL combinant filtres, tris, agrégations (COUNT, AVG) et jointures géographiques.
* **Résultats + Impact :** Mise en évidence d'incohérences de saisie (limites de qualité des codes géo) et production de KPIs précis sur la sinistralité par région.
* **Limites + Prochaines pistes :** SQLite est mono-utilisateur. **Piste d'amélioration :** Migration vers un SGBD robuste comme PostgreSQL pour un accès concurrentiel multi-équipes.
