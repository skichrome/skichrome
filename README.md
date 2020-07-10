## Bienvenue sur mon profil Github :wave:

### Moi

```Kotlin
data class Me(
    val name: String = "Toni",
    val age: Int = 24,
    val department: String = "Haute-Savoie",
    val degree: String = "Développeur d'applications Android",
    val school: String = "OpenClassrooms",
    val relevantExperience: List<String> = listOf("Département de la Haute-Loire")
)
```

Toni, 24 ans et haut savoyard, je viens de terminer - et valider - ma formation de développeur d'applications Android en alternance avec OpenClassrooms. Je suis donc maintenant disponible et à l'écoute de toute proposition pour devenir développeur Android, mais pas que (je suis toujours prêt à découvrir d'autres environnements).

Pour mon alternance, je l'ai réalisée au Département de la Haute-Loire, et j'ai pu développer une application de découverte du patrimoine du département, en Kotlin pour les utilisateurs Android, et en PHP avec Symfony pour les autres utilisateurs. Le principe est qu'une personne peut scanner un QrCode qui identifie un point d'intérêt pour accéder à du contenu augmenté. Grâce à cette expérience, je maîtrise l'utilisation des caméras des smartphones Android et le décodage des QrCodes avec MLKit de Firebase. J'ai pu également conforter mes connaissances en SQLite avec l'utilisation de la librairie Room et le design d'une architecture d'une base de données SQL.
Enfin, j'ai pu apprendre à administrer un serveur sous Linux (CentOS et Debian), et j'ai de bonnes bases en réseau.

### Mes compétences

```Kotlin
enum class MainSkills
{
    KOTLIN,
    NAVIGATION_COMPONENT,
    ARCHITECTURE_COMPONENT,
    KOTLIN_COROUTINES,
    RETROFIT,
    UNIT_TESTS_INTEGRATION_TESTS
}
```

Vous retrouverez sur ce Github mes projets développés pour ma formation en guise de vitrine de mes compétences, notamment la dernière application en date, [EasyVGP](https://github.com/skichrome/easy-vgp-oc), qui est une application de gestion de contrôles de machines et matériels de levage. 

Aujourd'hui, Android n'a quasiment plus de secrets pour moi, je suis passé à 99% au développement en Kotlin mais garde mes marques en développement Java. Côté connaissances des outils et patterns sous Android, je connais bien l'architecture MVVM et je pense mon code pour faciliter les tests unitaires et d'intégration, j'utilise le Navigation Component pour simplifier et assurer une bonne navigation dans mes applications, je maîtrise les Coroutines en Kotlin pour gérer les tâches asynchrones tout en limitant l'impact sur la mémoire vive des terminaux des utilisateurs.

### Les outils que je connais bien

```Kotlin
enum class WellKnownTools
{
    FIREBASE,
    KTOR,
    JENKINS,
    GIT,
    GITLAB_GITHUB,
}
```

Pour la gestion de mes backends, j'ai beaucoup utilisé Firebase, mais également, pour l'application [Real Estate Manager](https://github.com/skichrome/RealEstateManager) notamment, un backend 100% maison basé sur Ktor, que vous retrouverez [ici](https://github.com/skichrome/ktor-real-estate-manager).

Sur ce Github, vous verrez des badges qui indiquent si mes projets sont compilés avec succès, j'ai choisi d'aller plus loin que ce que j'ai pu faire avec OpenClassrooms et d'utiliser mon propre serveur Jenkins, pour compiler (et pour les derniers projets exécuter les tests) mes applications et assurer que le code qui est sur mes repositories est stable.
