# GUI2

## Planning

| Date     | Description                                                                                                                                                                                                                                                                                                                              |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 10.11.25 | Introduction <br /> Material Design <br /> Imperatif vs déclaratif <br /> Installation Android Studio + prise en main <br /> Codelab: [Jetpack Compose Basics](https://developer.android.com/codelabs/jetpack-compose-basics) <br /> Codelab: [Basic layouts in Compose](https://developer.android.com/codelabs/jetpack-compose-layouts) |
| 17.11.25 | Maquettes                                                                                                                                                                                                                                                                                                                                |
| 24.11.25 | Maquettes + Projet                                                                                                                                                                                                                                                                                                                       |
| 01.12.25 | Projet                                                                                                                                                                                                                                                                                                                                   |
| 15.12.25 | Projet                                                                                                                                                                                                                                                                                                                                   |
| 22.12.25 | Vacances                                                                                                                                                                                                                                                                                                                                 |
| 29.12.25 | Vacances                                                                                                                                                                                                                                                                                                                                 |
| 05.01.26 | Projet                                                                                                                                                                                                                                                                                                                                   |
| 12.01.26 | Projet + Rendu projet                                                                                                                                                                                                                                                                                                                    |

## Ressources

### Jetpack Compose

- [Thinking in Compose](https://developer.android.com/develop/ui/compose/mental-model)
- [Example Jetpack Compose apps](https://developer.android.com/jetpack/compose/samples)
- [Bitwarden open source app using Jetpack Compose](https://github.com/bitwarden/android)
- [Jetpack Compose Playground (community-driven wiki)](https://foso.github.io/Jetpack-Compose-Playground/)
- [Type safety in Kotlin DSL and Navigation Compose](https://developer.android.com/guide/navigation/design/type-safety)

### Material Design

- [Material Design](https://m3.material.io/)
- [Material Design Components](https://m3.material.io/components)

### Figma

- [Material 3 Design Kit (Figma)](https://www.figma.com/community/file/1035203688168086460/material-3-design-kit)
- [Exemples de maquettes (Google Drive)](https://www.figma.com/community/file/1383784439178391844)

### Autre

- [Imperative vs Declarative Programming](https://ui.dev/imperative-vs-declarative-programming)

## Codelabs

- [Jetpack Compose Basics](https://developer.android.com/codelabs/jetpack-compose-basics)
- [State in Jetpack Compose](https://developer.android.com/codelabs/jetpack-compose-state)
- [(Deprecated) Use ContraintLayout to design your Android views](https://developer.android.com/codelabs/constraint-layout?)

## Projet

Le module sera évalué sur la réalisation d'une application Android utilisant Jetpack Compose. L'application devra respecter les principes de conception Material Design. L'objectif est de démontrer la capacité à réaliser une maquette d'application et de la réaliser à l'aide de Jetpack Compose.

Le projet devra inclure au minimum les éléments d'interface suivants :

- Une page contenant une liste d'éléments cliquables (avec navigation vers nouvelle page).
- Une page affichant les détails d'un élément.
- Utilisation de composants interactifs: [Search](https://m3.material.io/components/search/overview), [Tabs](https://m3.material.io/components/tabs/overview), [Dialogs](https://m3.material.io/components/dialogs/overview), [Bottom Sheets](https://m3.material.io/components/bottom-sheets/overview), etc.

Le projet sera réalisé par groupe de 2 à 3 personnes.

Quelques idées de sujets:

- Réservation de concerts / événements
- Librairie de livres audio
- Réservation d'hôtels
- Blog / News (Reddit, Substack, etc.)
- Client mail
- Boutique en ligne (Zalando, Digitec, etc.)

### Évaluation

- Maquettes
  - Cohérence de l'interface utilisateur avec les besoins exprimés par le sujet sélectionné. (Est-ce que l'interface répond de manière ciblée aux besoins?)
  - Utilisation correcte de l'outil pour la réalisation des maquettes (Figma ou autre)
- Respect des principes de conception Material Design
  - Respect du design system Material 3
    - [Typographie](https://m3.material.io/styles/typography/overview)
    - [Couleurs](https://m3.material.io/styles/color)
    - [Espacements](https://m3.material.io/foundations/layout/understanding-layout/spacing)
    - [Gestes et animations](https://m3.material.io/foundations/interaction/gestures)
  - Respect des bonnes pratiques en terme d'accessibilité
    - Contraste des couleurs
    - [Taille des cibles tactiles](https://m3.material.io/foundations/designing/structure#8584de9a-6337-4234-9120-38d0227c5d21)
  - Utilisation appropriée des composants Material Design
- Implémentation
  - Correspondance de l'implémentation avec la maquette
  - [Le thème est personnalisé en suivant les bonnes pratiques de la librairie material3](https://developer.android.com/develop/ui/compose/designsystems/material3#material-theming)
  - [L'application est pensée pour différents formats d'écran (téléphone, tablette, paysage, portrait) et s'adapte en conséquence](https://m3.material.io/foundations/layout/applying-layout/window-size-classes)
  - [La navigation entre les écrans respecte les principes de navigation Android](https://developer.android.com/guide/navigation/principles)
  - L'application utilise des composables interactifs et ceux-ci peuvent être utilisés et leur état est géré correctement
  - L'interface utilisateur est soignée (orthographe, alignement)
  - L'application compile
