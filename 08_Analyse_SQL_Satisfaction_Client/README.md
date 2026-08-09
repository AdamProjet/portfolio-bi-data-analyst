# Analyse SQL de la Satisfaction Client en Magasin

* **Contexte / Besoin métier :** Suivre la satisfaction client et calculer le NPS suite à une série de retours clients, en les croisant avec les spécificités géographiques des magasins.
* **Données :** Tables "retour_client" et "ref_magasin" (codes INSEE, population, coordonnées geo_point_2d).
* **Démarche :** Audit et enrichissement du modèle relationnel pour lier les retours aux données démographiques via SQL.
* **Résultats + Impact :** Transformation d'une simple liste de questions en un dispositif d'analyse structuré. Identification claire des zones géographiques sous-performantes en NPS.
* **Limites + Prochaines pistes :** Requêtes SQL produisant des tableaux statiques. **Piste d'amélioration :** Brancher cette base enrichie sur Power BI pour une restitution dynamique et cartographique des NPS.
