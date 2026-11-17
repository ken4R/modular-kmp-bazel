# modular-kmp-bazel

Projet mobile modulaire, iOS et Android : la logique est écrite une seule fois en Kotlin Multiplatform, l'interface reste native sur chaque plateforme (SwiftUI et Jetpack Compose).

Ce dépôt porte le prototype de la solution A, dite hybride : Gradle construit le code partagé et l'application Android, Bazel construit l'application iOS.
