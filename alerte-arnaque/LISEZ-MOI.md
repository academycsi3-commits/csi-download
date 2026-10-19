# Alerte Arnaque — données publiques

Fichiers lus par l'application Android **Alerte Arnaque** de CSI Academy.

- `alertes.json` : alertes sur les arnaques en cours, vérifiées par CSI Academy. Chaque alerte cite sa source.
- `liste-noire.json` : numéros d'escrocs confirmés par CSI Academy.

Ne publiez ici que des informations vérifiées.

**Ajouter une alerte** : copiez un bloc existant en tête de la liste `alertes`, donnez-lui un `id` unique
(date + mots-clés), puis mettez à jour `maj`. Les téléphones la recevront en notification.

**Ajouter un numéro** : ajoutez `{"num": "70123456", "type": "Faux dépôt", "op": "Orange"}` dans `numeros`.
