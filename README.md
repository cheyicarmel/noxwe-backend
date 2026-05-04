# NOXWE Backend

API REST de la plateforme immobilière NOXWE — Django 4.2 + PostgreSQL + Redis.

## Structure du projet

\```
config/          → Configuration Django (settings, urls, wsgi)
users/           → Modèle utilisateur custom et authentification
agencies/        → Gestion des agences immobilières
properties/      → Annonces et biens immobiliers
leases/          → Contrats de bail
payments/        → Paiements Mobile Money
notifications/   → Notifications in-app et SMS
\```

## Documentation API

Swagger UI disponible sur http://localhost:8000/api/docs/ après démarrage du serveur.

