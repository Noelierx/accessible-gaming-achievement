# Succès débloqué : Rendre son jeu vidéo accessible

## Comment faire ?

### Architecture modulaire
```mermaid
graph TD
    A[Core Game Engine] --> B[Accessibility Manager]
    B --> C[Visual Accessibility]
    B --> D[Audio Accessibility]
    B --> E[Input Accessibility]
    B --> F[Cognitive Accessibility]
    C --> G[Color Filters]
    C --> H[Text Scaling]
    C --> I[UI Contrast]
    D --> J[Subtitles System]
    D --> K[Sound Visualizer]
    D --> L[Text-to-Speech]
    E --> M[Input Remapping]
    E --> N[Adaptive Controls]
    F --> O[Difficulty Scaling]
    F --> P[Game Speed Control]
    F --> Q[Tutorial System]
```

### Référentiels et Guidelines
- [Xbox Accessibility Guidelines](https://docs.microsoft.com/en-us/gaming/accessibility/xbox-accessibility-guidelines)
- [Games Accessibility Guidelines](http://gameaccessibilityguidelines.com/)
- [Accessible Player Experiences (APX)](https://accessible.games/)

### Formations
- [Accessible Design with Unreal Engine](https://dev.epicgames.com/community/learning/courses/7M1/accessible-design-with-unreal-engine/yGwl/accessible-design-in-unreal-engine-overview)
- [Microsoft Learn : Gaming accessibility fundamentals](https://learn.microsoft.com/en-us/training/paths/gaming-accessibility-fundamentals/)

### Outils de Développement
- [Unity Accessibility Plugin](https://github.com/mikrima/UnityAccessibilityPlugin)
- [Microsoft Game Accessibility Testing Service (MGATS)](https://learn.microsoft.com/en-us/gaming/accessibility/mgats)

### Intégration Continue
- **CI/CD** : Utilisation de services comme Jenkins, Travis CI, ou GitHub Actions pour automatiser les tests d’accessibilité.

