# Surveillance

Vérifie toutes les 10 minutes que mes sites répondent et que leurs certificats sont valables encore 14 jours
(`.github/workflows/sonde.yml`). En cas d'échec, GitHub envoie un e-mail. Ajouter un site : une ligne dans `matrix.site`.
