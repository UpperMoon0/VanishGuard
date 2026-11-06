@Library('nstut-ci') _

// Reviewed main only; Windows agents provide pinned JDK 17 and native Gradle.
// Keep GitHub-hosted pull request and disposable Forge patch smoke workflows.
nstutNativeGradle(
    agentLabel: 'ci-native-gradle-ready && ci-windows-native',
    targets: [
        [
            id: 'forge1201',
            name: 'Forge 1.20.1 unit tests and production reobfuscated JAR',
            java: 17,
            minutes: 60,
            tasks: ['test', 'build']
        ]
    ]
)
