# Sc-dult

App d'aide à la réduction de consommation de contenu adulte, basée sur la
transparence (pas de piège caché) et l'accountability partner.

## Ce qui est fait (UI seulement pour l'instant)

- Onboarding avec choix de durée d'engagement
- Écran de consentement explicite pour le Mode Verrouillé (2 checkboxes obligatoires)
- Écran d'accueil : streak, statut du verrouillage, bouton SOS
- Écran SOS : respiration guidée, marche, exercice, playlist

## Ce qui n'est PAS encore fait (prochaines étapes)

- Le vrai blocage DNS (VpnService Android en Kotlin, natif)
- La sauvegarde des données (actuellement rien n'est persisté)
- Le système de notification à l'accountability partner
- Le blocage anti-désinstallation

## Comment tester sans installer Android Studio

1. Crée un compte GitHub gratuit si tu n'en as pas.
2. Crée un nouveau repo, upload tous ces fichiers (glisser-déposer sur
   la page GitHub, pas besoin de Git en ligne de commande).
3. Va dans l'onglet "Actions" du repo → le workflow "Build APK" se lance
   automatiquement.
4. Une fois terminé (~5 min), télécharge l'APK dans "Artifacts".
5. Transfère l'APK sur ton téléphone Android (Google Drive, câble USB...)
   et installe-le (il faudra autoriser "sources inconnues").

## Stack

- Flutter / Dart
- GitHub Actions pour la compilation cloud (gratuit, pas besoin d'Android Studio)
