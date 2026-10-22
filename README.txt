TALKUP — VERSION ÉTENDUE

Déjà intégrés : connexion par e-mail/mot de passe, recherche par pseudo, messages privés texte, stories photo (si Storage est activé), choix d'ambiance saisonnière et interface préparatoire pour le profil et les groupes.

À noter : la sauvegarde du profil, la création réelle des groupes, l'envoi de photos/vidéos/audio dans les conversations et les appels audio/vidéo ne sont pas encore entièrement développés. Leurs fonctions demandent du code supplémentaire et des tests. Les tuiles présentes annoncent ces prochaines fonctions, elles ne prétendent pas qu'elles sont déjà actives.

Ambiances : sélection manuelle Coupe du monde, Noël, Nouvel an, été ou classique. En automatique, Noël, Nouvel an et été sont choisis selon la date. La Coupe du monde peut être activée manuellement; pour l'automatiser pendant le prochain tournoi, il faudra ajouter ses dates officielles au code.

Configuration : activer Authentication > E-mail/Mot de passe; publier firestore.rules dans Firestore; activer Storage puis publier storage.rules pour les stories; héberger index.html sur HTTPS. Vérifie que l'appId dans index.html correspond exactement à celui de Firebase.

Les stories sont masquées après 24 h mais leurs fichiers ne sont pas automatiquement supprimés. Ne publie pas d'informations sensibles; les messages et stories ne sont pas chiffrés de bout en bout.
