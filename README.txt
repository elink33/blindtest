BLINDLY — VERSION MULTI-APPAREILS POUR GITHUB PAGES

1. Mets index.html dans ton dépôt GitHub Pages.
2. Ouvre ton site sur l'iPad du maître du jeu.
3. Clique « Créer une partie ».
4. Les joueurs scannent le QR affiché.
5. Chaque appareil se connecte directement au navigateur du maître via WebRTC/PeerJS.
6. Les réponses et scores sont synchronisés.

Aucun serveur applicatif n'est à installer ou à gérer.
Le projet utilise PeerJS comme service de signalisation public pour établir la connexion WebRTC. Le contenu de la partie passe ensuite entre les navigateurs.

NOTE : un code court tapé manuellement n'est pas suffisant pour retrouver le maître sans annuaire. La version est donc conçue autour du QR/lien, ce qui est beaucoup plus simple et fiable.
