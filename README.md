# VoxPop Audio Interview Form

Ce projet est une mini-application web permettant à un utilisateur d’enregistrer sa voix depuis le navigateur et d’envoyer l’audio vers un scénario Make pour transcription automatique.

## Fonctionnalités

- Enregistrement audio via MediaRecorder API
- Envoi via `fetch()` vers un Webhook Make
- Intégration simple avec OpenAI Whisper ou Gladia pour la transcription
- Déploiement ultra-rapide avec Vercel

## Déploiement

1. Cloner ce repo ou télécharger le ZIP
2. Importer sur [https://vercel.com](https://vercel.com)
3. Modifier l'URL du webhook dans `index.html` ligne 73

## Licence

MIT
