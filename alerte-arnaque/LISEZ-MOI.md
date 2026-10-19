# Alerte Arnaque — page de téléchargement et données publiques

Page publique : https://academycsi3-commits.github.io/csi-download/alerte-arnaque/

- `index.html` : la page de présentation et de téléchargement.
- `AlerteArnaque.apk` : la dernière version de l'appli. Pour publier une nouvelle version, remplacez ce fichier et mettez à jour le numéro de version dans `index.html`.
- Ne créez PAS de « Release » GitHub pour Alerte Arnaque dans ce dépôt : les Releases servent aux mises à jour de CSI Download.

Fichiers lus par l'application Android **Alerte Arnaque** de CSI Academy.

- `alertes.json` : alertes sur les arnaques en cours, vérifiées par CSI Academy. Chaque alerte cite sa source.
- `liste-noire.json` : numéros d'escrocs confirmés par CSI Academy.

Ne publiez ici que des informations vérifiées.

**Ajouter une alerte** : copiez un bloc existant en tête de la liste `alertes`, donnez-lui un `id` unique
(date + mots-clés), puis mettez à jour `maj`. Les téléphones la recevront en notification.

**Ajouter un numéro** : ajoutez `{"num": "70123456", "type": "Faux dépôt", "op": "Orange"}` dans `numeros`.
