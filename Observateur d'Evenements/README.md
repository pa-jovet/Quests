# Vue personnalisée - Observateur d'Evenements Windows
## Général
Il s'agit d'une vue personnalisée visant à se concentrer sur les événements liés au DNS

## Paramètres de vue
1. Niveaux à surveiller
   - Critique (1)
   - Erreur (2)
   - Avertissement (3)
   - Information (4) - Pour les démarrages/arrêts

2. Sources d'événements à inclure
   - DNS-Server-Service: Pour les opérations du serveur DNS
   - DNS Client Events: Pour les événements côté client

3. ID d'événements à observer
   - 2: Démarrage du serveur DNS
   - 4: Arrêt du serveur DNS
   - 409: Erreur de résolution de nom
   - 501-502: Échec de chargement de zone
   - 6001-6002: Problèmes de réplication DNS
