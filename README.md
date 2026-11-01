# Veille du serveur Kopé

Toutes les 10 minutes, GitHub vérifie que le serveur de Kopé répond (`/api/health`).
S'il ne répond pas après 3 essais, le contrôle échoue et GitHub envoie un e-mail au propriétaire du dépôt.

Historique : onglet **Actions** > **Veille du serveur Kopé** (vert = en ligne, rouge = panne).
Une fois par semaine, un petit fichier est mis à jour pour que GitHub garde ce contrôle actif.
